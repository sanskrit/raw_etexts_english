+++
title = "Generating simple radially symmetricxa0art"
date = "2021-05-14"

+++
Many people experience beauty in structures with bilateral, radial and
rotational symmetries with or without recursion. The recursive or nested
structure are the foundation of the beauty in fractal form, the
generation of which has become increasingly easy for the lay person with
ever-improving computing power. One could generate beautiful fractal
structures using a range of open source software; however, there is no
substitute for writing ones own code and taking in some of the
mathematics behind the beauty — truly fractal structures provide the
clearest bridge between mathematics and beauty. While we have presented
some discussion on such structures on these pages, that is not the topic
of this note. Here, we shall talk about stuff that is mostly art for
art’s sake (We fully understand that what constitutes art can have some
subjectivity) that is generated based on simple repeats of certain
motifs with an emphasis on radial and rotational symmetries.

For at least three generations, there has been a strand in our family
with an interest in generating such art. While there certainly exist
people with much greater skill than us (you can even see manifestations
of genius in this regard), the driving force for us is the pleasure
derived from process of generating such art. One experiences a climax,
when the process of polishing the work culminates in a first person
experience of beatific satisfaction. In the two previous generations,
the main medium was the powder (rice flour, stone and other colored
powders) used in traditional alaṃkāra. In our case it began with
spending time in our youth with a kaleidoscope. That inspiration was
then transferred to paper, pen and compass but eventually it
transitioned to computer-aided *in silico* tools. Over the years we have
used many tools each with its own advantages and disadvantages. The
first programs we used were CorelDraw and Canvas. The latter, at that
time, was available to only on a Mac. It was a decent program but
expensive. Moreover, we never owned a Mac, and using it on a public or a
borrowed Mac was hardly convenient. Hence, it fell to the way side. I
continue to use CorelDraw for professional stuff, especially if the work
needs freedom of the hand and has some complexity; however, it is
expensive and a typical user might only be able access it via a funding
agency. Then the open source Inkscape came along, which evolved to be a
reasonable free substitute for CorelDraw. Although CorelDraw is
“smoother” to use, the current version of Inkscape is not bad at all.

However, we wanted something more “programmable” where one could adjust
various numerical parameters rather than going freehand — a language for
graphics. The first such we looked at was MetaPost — it had, what to us
were unfriendly aspects; however, the time we spent exploring it was not
a total waste because in the second decade of the 2000s of CE we learnt
of the existence of the PGF/TikZ (ironically named: “TikZ ist kein
Zeichenprogramm) languages that greatly improved on MetaPost in our
subjective opinion. Notably it could be used from within
![\\LaTeX](https://s0.wp.com/latex.php?latex=%5CLaTeX&bg=ffffff&fg=333333&s=0&c=20201002).
Thus, we finally settled on TikZ as the language to write these pieces
of art in. Following is an example of such with the compiled result
appended below.

    \documentclass[margin=5mm]{standalone}
    \usepackage{tikz}
    \usetikzlibrary{arrows, arrows.meta, patterns, shapes.geometric, decorations.shapes, shapes.misc, graphs, mindmap, calc, backgrounds}

    \begin{document}
    \begin{tikzpicture}
    \pgfdeclarelayer{background}
    \pgfdeclarelayer{foreground}
    \pgfsetlayers{background,main,foreground}

    \definecolor{col1}{RGB}{2, 35, 54}
    \definecolor{col2}{RGB}{15, 184, 184}
    \definecolor{col3}{RGB}{178, 209, 107}
    \definecolor{col4}{RGB}{199, 186, 99}
    \definecolor{col5}{RGB}{174, 137, 199}
    \definecolor{col6}{RGB}{59, 148, 126}
    \definecolor{col7}{RGB}{77, 148, 255}
    \definecolor{col8}{RGB}{230, 229, 202}
    \definecolor{col9}{RGB}{61, 69, 67}

    \foreach \x in {0,36,72, ...,324}{
    %wavy background
    \begin{pgfonlayer}{background}
    \draw[col1, fill=col1, rotate=\x, scale=.8] (0,0) -- (22.5:3.5) to [bend left=40] (-22.5:3.5) -- (0,0)--cycle;
    \end{pgfonlayer}

    %wavy dots
    \draw[decorate, decoration={shape backgrounds, shape=circle, shape size=.8mm, shape sep=1.512mm}, col3, fill=col3, rotate=\x, scale=.77] (18:3.5) to [bend left=40] (-18:3.5);

    %onion
    \draw[col4, fill=col4, rotate=\x+18, yshift=2.2cm, scale=.2] (-1,1) ..
    controls (-0.5,0.5) and (0.5,0.5) .. (1,1) .. controls (1.5,2) and (0,2) .. (0,2.5) .. controls (0,2) and (-1.5,2) .. (-1,1) --cycle;

    %petal
    \draw[col5, line width=1.5, rotate=\x, yshift=1.75cm, scale=.75] (0,1) .. controls (-0.5,0) and (0.5,0) .. (0,1) --cycle;

    %chandrabindu
    \begin{scope}[rotate=\x, xshift=2.1cm, scale=.3]
    \draw[col7, fill=col7] (0,-1) .. controls (-0.5,-1) and (-0.5,1) .. (0,1) ..controls (-1,1) and (-1,-1) .. cycle;
    \draw[col7, fill=col7] (0,0) circle (.25);
    \end{scope}
    %pipal leaf
    \draw[col8, line width=1, rotate=\x, xshift=1.35cm, scale=.15] (0,0) .. controls (-1,0.5) and (0,1.5) .. (1,1) .. controls (2,0.5) and (1.05,0.1) .. (2.1,0) .. controls (1.05,-0.1) and (2,-0.5) .. (1,-1) .. controls (0,-1.5) and (-1,-0.5) .. (0,0)--cycle;
    \begin{scope}[col3, rotate=\x+18, xshift=1.3cm, scale=.5]
    \def\y{20}
    \def\z{sin(30)}
    \def\w{1}
    \draw[line width=\w] (0,0) to[bend right=\y] (1,\z);
    \draw[line width=\w] (0,0) to (1,0);
    \draw[line width=\w] (0,0) to[bend right=-\y] (1,-\z);
    \end{scope}
    %dot in petal
    \draw[col8, fill=col8, rotate=\x+18, xshift=2.1cm] (0,0) circle (.05);

    %dot in pipal
    \draw[col8, fill=col8, rotate=\x, xshift=1.46cm] (0,0) circle (.05);
    }

    %tetrafolium
    \draw[col6, fill=col9, line width= 3, scale=.75] (-1.5,0) .. controls (-1.5,-2) and (2,1.5) .. (0,1.5) ..controls (-2,1.5) and (1.5,-2) .. (1.5,0) ..controls (1.5,2) and (-2,-1.5) .. (0,-1.5)..controls (2,-1.5) and (-1.5,2) .. cycle;

    \foreach \x in {0,90,180,270}{
    %releaux triangle
    \begin{scope}[rotate=\x, xshift=.75cm, scale=.25]
    \def\y{30}
    \draw[col3, fill=col3] (-.5, -0.8660254) to[bend right=\y] (1,0) to[bend right=\y] (-.5,0.8660254) to [bend right=\y] (-.5, -0.8660254) -- cycle;
    \draw[col1, fill=col1, xshift=.07cm] (0,0) circle(.3);
    \end{scope}
    }

    %central circles
    \draw[col2, fill=col2] (0,0) circle (.45);
    \shade[inner color=col8,outer color=black] (0,0) circle (.25);
    \end{tikzpicture}
    \end{document}

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig1.png?w=480&h=481)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig1.png)**Figure
1.**

This example uses decadal symmetry with central tetrad element. In our
subjective experience tetrad symmetry can be paired with other even
symmetries as long as they central or the exterior most elements.

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig2.png?w=480&h=489)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig2.png)**Figure
2.**

Ideally all repeated motifs should have at least bilateral symmetry.
However, one can get away with a layer or two of elements with just
rotational symmetry, like the “S” element in Figure 2. The choice of
color is another very important element — we like a degree of contrast
in all the piece. Appended below are a range of productions illustrating
different color choices.

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig3.png?w=483&h=480)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig3.png)

**Figure 3.**

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig4.png?w=480&h=484)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig4.png)

**Figure 4.**

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig5.png?w=492&h=480)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig5.png)

**Figure 5.**

[![](https://manasataramgini.files.wordpress.com/2021/05/deco_fig6.png?w=481&h=480)](https://manasataramgini.files.wordpress.com/2021/05/deco_fig6.png)

**Figure 6.**
