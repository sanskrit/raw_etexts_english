+++
title = "Some lessons we learned from 3-color totalistic cellular automata"

+++
Cellular automata (CA) have attracted people’s attention to different
degrees over the past several decades since the early work of pioneers
like Ulam and von Neumann. Remarkably von Neumann played with his
earliest versions of CA using a graph paper and pencil rather than a
computer. Subsequently, the man behind the modern computer and
high-level programming languages, Zuse, realized their great importance
as a fundamental model for existence. Further notable developments were
the game of life of Conway and the systematic study of CA by Wolfram.
Our first acquaintance with these entities occurred in our youth first
from Conway’s work and a paper of Michael Frame.

This immediately induced us to start pursuing CA. At that time we did
not really have the chance to study Conway and Wolfram’s work on CAs in
any great detail beyond obtaining the basic facts of how they worked.
Hence, we explored them on own with our first computer and consequently
obtained some qualitative insights and aesthetic satisfaction both of
which seemed remarkable to us. Here we talk mainly of the “3-color
totalistic CA” which were among the first we explored. Some of the rules
graphically presented here are those which Wolfram has studied in great
detail. The account here is simply our personal journey through them and
what we found interesting in their behavior.

***The definition of the 3-color totalistic CA:***  
1\) They are an one-dimensional array of cells with each cell having a
starting state (represented by their numerical value or color). In a
three color automaton they have 3 colors. We have chosen triplets like
(white, deepskyblue, navy), (white, cyan3, darkblue) or (white, orange,
red) for aesthetic reasons (they could be any other 3 colors).
Correspondingly, the states of the cells are assigned numerical values
![\[0,1,2\]](https://s0.wp.com/latex.php?latex=%5B0%2C1%2C2%5D&bg=ffffff&fg=333333&s=0
"[0,1,2]").

2\) The state of the cells changes from one generation to the next
depending on the state of 3 cells in the current generation: their own
state and that of their neighbors to their immediate left and right. For
a totalistic automaton it is the “total state value” across the 3 cells
that matters. Thus, we can have the following
![7](https://s0.wp.com/latex.php?latex=7&bg=ffffff&fg=333333&s=0 "7")
values:  
![\[2,2,2\] = 6; \[2,2,1\] = 5; \[2,1,1\] = 4; \[1,1,1\] = 3;
\\\\\[5pt\] \[1,1,0\] = 2; \[1,0,0\] = 1; \[0,0,0\] =
0](https://s0.wp.com/latex.php?latex=%5B2%2C2%2C2%5D+%3D+6%3B+%5B2%2C2%2C1%5D+%3D+5%3B+%5B2%2C1%2C1%5D+%3D+4%3B+%5B1%2C1%2C1%5D+%3D+3%3B+%5C%5C%5B5pt%5D+%5B1%2C1%2C0%5D+%3D+2%3B+%5B1%2C0%2C0%5D+%3D+1%3B+%5B0%2C0%2C0%5D+%3D+0&bg=ffffff&fg=333333&s=0
"[2,2,2] = 6; [2,2,1] = 5; [2,1,1] = 4; [1,1,1] = 3; \\\\[5pt] [1,1,0] = 2; [1,0,0] = 1; [0,0,0] = 0").  
Each of 7 total state values specify a one of three states for the given
cell in the next generation. These specifications are termed the rule of
the CA. For example, we can have the following rule:  
![6 \\rightarrow 0; 5 \\rightarrow 0; 4 \\rightarrow 2; 3 \\rightarrow
0; 2 \\rightarrow 1; 1 \\rightarrow 2; 0 \\rightarrow
0](https://s0.wp.com/latex.php?latex=6+%5Crightarrow+0%3B+5+%5Crightarrow+0%3B+4+%5Crightarrow+2%3B+3+%5Crightarrow+0%3B+2+%5Crightarrow+1%3B+1+%5Crightarrow+2%3B+0+%5Crightarrow+0&bg=ffffff&fg=333333&s=0
"6 \\rightarrow 0; 5 \\rightarrow 0; 4 \\rightarrow 2; 3 \\rightarrow 0; 2 \\rightarrow 1; 1 \\rightarrow 2; 0 \\rightarrow 0").  
Since total state value for the 3 cells is always listed from
![6:0](https://s0.wp.com/latex.php?latex=6%3A0&bg=ffffff&fg=333333&s=0
"6:0"), we can represent the rule by merely providing the vector of cell
state values specified by the
![7](https://s0.wp.com/latex.php?latex=7&bg=ffffff&fg=333333&s=0 "7")
total state values in that order, e.g. in the above case:
![\[0,0,2,0,1,2,0\]](https://s0.wp.com/latex.php?latex=%5B0%2C0%2C2%2C0%2C1%2C2%2C0%5D&bg=ffffff&fg=333333&s=0
"[0,0,2,0,1,2,0]") or simply the string
![0020120](https://s0.wp.com/latex.php?latex=0020120&bg=ffffff&fg=333333&s=0
"0020120"). Thus, one can see that there are total of
![3^7=2187](https://s0.wp.com/latex.php?latex=3%5E7%3D2187&bg=ffffff&fg=333333&s=0
"3^7=2187") possible rules. Wolfram further converts this string to a
decimal number that represents the rule by taking the string to be a
ternary number (i.e. base
![3](https://s0.wp.com/latex.php?latex=3&bg=ffffff&fg=333333&s=0 "3")).

3\) The starting values of the cells are plotted as the first row. These
are then updated based on the rule and plotted as the second row. The
rule is then applied to this row to get the next and so on. These are
successively plotted below the initial row to get a visual
representation of the CA.

4\) In principle the CAs were seen as operating on an infinite array of
cells. However, for practical purposes we plot them on a on cylinder.
Thus, the image presented is the cylinder rolled out as sheet with the
first and the last column being neighbors on the cylinder.

5\) The CAs can either be initiated with a single cell with a non-0
value or with a random sampling of values for the cells in the
initiating array. In the first figure all are initiated with single cell
with value 1. In the figures used here the array consists of 100 or 101
cells which evolves for 100 generations before being plotted.

![3rule\_totalistic\_behaviors](https://manasataramgini.files.wordpress.com/2016/11/3rule_totalistic_behaviors.png?w=640)

*Figure 1*

Several general kinds of behavior can be observed in the CAs in a
rule-dependent fashion as depicted in Figure 1

1\) Sterility: An example of this rule
![1110020](https://s0.wp.com/latex.php?latex=1110020&bg=ffffff&fg=333333&s=0
"1110020") which after 4 generations becomes an entirely 0-valued array
(Figure 1, top panel 1). In these cases all cells converge to a single
state with no further evolution.

2\) Simple alternation: Here all cells in the array alternate between
two state over successive generations. See below.

3\) Simple linear repetitive patterns: An example is rule
![2112020](https://s0.wp.com/latex.php?latex=2112020&bg=ffffff&fg=333333&s=0
"2112020") where from generation 5 onwards the cells converge to a
repeating pattern that spans 7 generations. The maximum width of the
non-0 cells remains constant in these patterns (Figure 1, top panel 2).

4\) Complex linear repetitive patterns: These patterns are similar to
the above but attain greater complexity in terms of the structure and
number of generations spanned by the repeating unit. Rule
![1211020](https://s0.wp.com/latex.php?latex=1211020&bg=ffffff&fg=333333&s=0
"1211020") is a good example with a long repeating pattern of 78
generations, such that we see only one unit here. Wolfram has shown that
this is the longest repeat for these CAs (Figure 1, top panel 3).

5\) Expanding repetitive patterns: These patterns are repetitive like
the above but do not have a constant width; instead they keep expanding
(e.g. rule
![2120210](https://s0.wp.com/latex.php?latex=2120210&bg=ffffff&fg=333333&s=0
"2120210"); Figure 1, bottom panel 1).

6\) Fractal patterns: These converge to a fractal-like form, typically a
version of the Sierpinski’s gasket. Geometrically this can be obtained
by forming triangles connecting the midpoints of the three sides of a
starting triangle. In the case of the CAs they grow from a minimal unit
outwards (e.g. rule
![0110220](https://s0.wp.com/latex.php?latex=0110220&bg=ffffff&fg=333333&s=0
"0110220"); Figure 1, bottom panel 2).

7\) Complex chaotic patterns: These keep growing in width but never have
a repeating pattern. Local patterns sometimes reappear elsewhere but
they do not come in the same context as the previous occurrence (e.g.
rule
![2210120](https://s0.wp.com/latex.php?latex=2210120&bg=ffffff&fg=333333&s=0
"2210120"); Figure 1, bottom panel 3).

![3color\_totalistic\_9](https://manasataramgini.files.wordpress.com/2016/11/3color_totalistic_9.png?w=640)

Figure 2

Similar looking rules do not mean similar behavior. As an example we can
look at the 9 CAs with successive rules from
![1102120](https://s0.wp.com/latex.php?latex=1102120&bg=ffffff&fg=333333&s=0
"1102120") to
![1102212](https://s0.wp.com/latex.php?latex=1102212&bg=ffffff&fg=333333&s=0
"1102212") in ternary notation which correspond to the Wolframian
![1041..1049](https://s0.wp.com/latex.php?latex=1041..1049&bg=ffffff&fg=333333&s=0
"1041..1049") in decimal (Figure 2). Mostly, the simpler patterns of
convergence tend to dominate. Here 1/9 rules produces a sterile pattern;
3/9 rules converge to simple alternation; 2/9 rules converge to simple
linear repetitive patterns. Of these
![1102121](https://s0.wp.com/latex.php?latex=1102121&bg=ffffff&fg=333333&s=0
"1102121") is notable in that it initially produces 32 generations of
complex non-repetitive growth and then suddenly collapses to a simple
linear pattern. 2/9 rules produce expanding repetitive patterns. 1/9
rules ($1102120$) produces an apparently complex chaotic pattern that
keeps growing.

![totalistic\_3color](https://manasataramgini.files.wordpress.com/2016/11/totalistic_3color.png?w=640)

Figure 3

If we instead start with an initial array of cells each randomly showing
one of the three values we get generally similar behavior but with some
interesting features that are not seen in the single cell initiations
(Figure 3):

1\) A striking example is
![0121020](https://s0.wp.com/latex.php?latex=0121020&bg=ffffff&fg=333333&s=0
"0121020") which shows a sterile pattern in a single cell initiation
that goes extinct after 4 generations. However, when it is initiated
with a random array of the three values it develops a complex pattern
with several branches as well as runs of linear repetitive patterns.
Thus, a singly sterile rule when given the opportunity to interact with
other initiations as a result of the random initiation develops into a
complex system. We term this symbiotic development.

2\) Rule
![0022010](https://s0.wp.com/latex.php?latex=0022010&bg=ffffff&fg=333333&s=0
"0022010") shows some initial complex patterns but all of these are
quickly channelized into simple linear repetitive patterns. Likewise,
rules
![0111020](https://s0.wp.com/latex.php?latex=0111020&bg=ffffff&fg=333333&s=0
"0111020") and
![1011020](https://s0.wp.com/latex.php?latex=1011020&bg=ffffff&fg=333333&s=0
"1011020") initially evolve complex branching which then goes extinct
and leaving just one or two dominant complex linear repetitive strands.
In rule
![1012020](https://s0.wp.com/latex.php?latex=1012020&bg=ffffff&fg=333333&s=0
"1012020") the initial complexity is quickly channelized into both
simple and complex linear repetitive patterns.

3\) Rule
![1022010](https://s0.wp.com/latex.php?latex=1022010&bg=ffffff&fg=333333&s=0
"1022010") produces expanding repetitive patterns which are interspersed
with runs of simple linear patterns.

4\) Rules like
![0022210](https://s0.wp.com/latex.php?latex=0022210&bg=ffffff&fg=333333&s=0
"0022210"),
![1001210](https://s0.wp.com/latex.php?latex=1001210&bg=ffffff&fg=333333&s=0
"1001210") and
![1020210](https://s0.wp.com/latex.php?latex=1020210&bg=ffffff&fg=333333&s=0
"1020210") quickly produce chaotic structures but these have certain
stereotypic sub-structures.

5\) Rules like
![0020120](https://s0.wp.com/latex.php?latex=0020120&bg=ffffff&fg=333333&s=0
"0020120") and
![0120120](https://s0.wp.com/latex.php?latex=0120120&bg=ffffff&fg=333333&s=0
"0120120") rapidly converge to even more chaotic structures than the
above, spawning what look closer to completely random patterns.

***Obvious analogical insights gained from these CA***  
CA provided the analogy for world view first developed by the computer
science pioneer Zuse in his “Rechnender Raum” that the universe based on
physics is actually computed on a system of CA. For Zuse this was more
than just an analogy with the structure of space itself perhaps
providing the canvas on which these CA played out with the “image”
forming as a result being all of existence. This intuition itself goes
back to Thomas Huxley the early Darwinist. While not having classic CA,
he had such an general analogy in mind for the working of nature:  
“*The chess-board is the world; the pieces are the phenomena of the
universe; the rules of the game are what we call the laws of Nature.*”

For us, primarily being a biological naturalist, the first encounter
with CA provided an analogy for how the processes of life were executed.
The fundamental unit of biological systems being the cell made this a
natural analogy for development. Indeed, on first seeing CA, the most
direct connection to certain biological forms appeared before our eyes.
For example, the patterns formed on the shells of *Conus *snails can be
quite explained by some form of totalistic CA as those illustrated here
(e.g. rule
![0022210](https://s0.wp.com/latex.php?latex=0022210&bg=ffffff&fg=333333&s=0
"0022210") and
![1020210](https://s0.wp.com/latex.php?latex=1020210&bg=ffffff&fg=333333&s=0
"1020210") can be favorably compared with actual snail shell patterns
illustrated by Gong et al). The totalistic rules can be explained in a
biological context as the concentration of a diffusible (like one of the
many signaling molecules that are secreted by cells) or cell-surface
morphogenetic signal. This concentration is the determinant of cell fate
and it can literally play out on a growing sheet of cells as seen here.

![conus](https://manasataramgini.files.wordpress.com/2016/11/conus.png?w=640)

*Gong et al*  E234–E241, doi: 10.1073/pnas.1119859109

However, CA also provided us with a more abstract biological insight.
Here, the CA are not to be equated with the actual biological cells but
used as analogs for other one-dimensional systems like transcription
factors binding to a linear DNA molecule or RNA-binding proteins binding
to a RNA molecule. Alternatively, they might be seen as covalent
modifications with “epigenetic” consequences on a linear string like
nucleic acids or the histone octamers on DNA. This kind of state
differences on the linear biological entity can determine the state of a
region in the next iteration. Continuing with this picture, at the
highest level of abstraction we can visualize CA representing serial
states of an auto-regulatory biological network, whose current state of
inputs determine the next state of the network, and those in turn the
next state and so on. This provided a powerful means of analogically
visualizing the emergence of various behaviors ranging from simple
oscillations to chaotic emergence of states in biological systems. The
advantage of visualizing them as emerging from underlying CA is that we
now have a discrete simple mechanism, which can be easily equated with
molecular interactions, behind various state manifestations in biology.

***Less obvious analogical insights gained from these CA***  
Finally, such CA provided us with intuition in an area which had looked
quite baffling and not amenable to mechanistic penetration, i.e. a
macroscopic view of history of civilizations. In history there are
several tendencies that have been qualitatively described: 1) “History
repeats itself” (rule
![2112020](https://s0.wp.com/latex.php?latex=2112020&bg=ffffff&fg=333333&s=0
"2112020")); 2) “Long cycles” (rule
![1211020](https://s0.wp.com/latex.php?latex=1211020&bg=ffffff&fg=333333&s=0
"1211020")); 3) “Rise and fall of a civilization” (rule
![1110020](https://s0.wp.com/latex.php?latex=1110020&bg=ffffff&fg=333333&s=0
"1110020")); 4) “Triumph of groups over units” (rule
![1110020](https://s0.wp.com/latex.php?latex=1110020&bg=ffffff&fg=333333&s=0
"1110020")); 5) “Great diversity at the base converging to a standard
type” (rule
![1011020](https://s0.wp.com/latex.php?latex=1011020&bg=ffffff&fg=333333&s=0
"1011020")); 6) “A flowering followed by loss of creativity” (rule
![1102121](https://s0.wp.com/latex.php?latex=1102121&bg=ffffff&fg=333333&s=0
"1102121")); 7) “Parallelism” (rule
![1012020](https://s0.wp.com/latex.php?latex=1012020&bg=ffffff&fg=333333&s=0
"1012020")); 8) “A many branched tree” (rules
![1102120](https://s0.wp.com/latex.php?latex=1102120&bg=ffffff&fg=333333&s=0
"1102120")); 9)”Waxing and waning periods” (rule
![1022010](https://s0.wp.com/latex.php?latex=1022010&bg=ffffff&fg=333333&s=0
"1022010")) 10) “Chaotic development” (rule
![0120120](https://s0.wp.com/latex.php?latex=0120120&bg=ffffff&fg=333333&s=0
"0120120")); 11) “navo-navaś camatkāraḥ (rule
![1020210](https://s0.wp.com/latex.php?latex=1020210&bg=ffffff&fg=333333&s=0
"1020210")).”

One could ask: “Alright, one can draw general parallels between these
patterns in history and the evolution of CA, but is there anything more
to it than just some vague similitude? Is it even useful?” We believe
the answer is in the affirmative, at least in the analogical realm, even
if not in the modelling sense. One could conceptualize civilization as
having certain minimal units (cells) which occupy a certain space over
which they can expand (the array on which the CA play out). The
civilizational units themselves can differentiate to have few distinct
intrinsic states while interacting with themselves in the near vicinity
and their environment (the null cells). The total of all these
interactions can be captured relatively simply as a single value, but
the fine gradations of this value matter in terms of the development of
the units in the subsequent generation.

Some might object to this as an overly simplistic reduction but studies
in other areas suggest that this is not necessarily a wrong thing. At a
fundamental level the statistical operation of obtaining the mean of a
data set can be seen as simplifying or reducing the complexity of the
data. Yet in many cases, the things we can do with, or understand from a
mean are much more than with the mass of data. Indeed, the mean or some
such statistical measure of central tendency can be sufficient to infer
the \*general\* behavior of the mass more easily than having just the
mass. As a practical example, while intelligence emerges from a complex
interaction between the products of many genes and the DNA containing
the genes themselves, it can still be simply captured as a number, which
is useful for several purposes. Likewise, the totalistic procedure can
be seen as sufficient to usefully specify the development of the system
but its fine gradations matter.

Thus, melding of intrinsic factors like genetics, social interaction
terms, and the environment of a civilizational unit into simple measure
can be seen as being sufficient to sustain a wide range of evolutionary
patterns that characterize history. A particularly notable case for us
was what is seen in rule
![0121020](https://s0.wp.com/latex.php?latex=0121020&bg=ffffff&fg=333333&s=0
"0121020") which when initiated with a single cell with value 1 dies out
quickly but when initiated with multiple cells random bearing an equal
number of 0,1 and 2 states shows complex development. This is a good
analogy for how single civilizational units might die if they are
isolated on their own but if they have many neighboring copies they can
synergistically develop complex behavior. Indeed rule
![0121020](https://s0.wp.com/latex.php?latex=0121020&bg=ffffff&fg=333333&s=0
"0121020") can combine many different types of behavior described above
when initiated from different sets of multiple random cells (Figure 4).

![3color\_totalistic\_many](https://manasataramgini.files.wordpress.com/2016/11/3color_totalistic_many.png?w=640)

Figure 4
