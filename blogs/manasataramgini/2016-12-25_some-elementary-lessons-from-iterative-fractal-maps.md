+++
title = "Some elementary lessons from iterative fractal maps"

+++
The famous Sierpinski gasket was one of the first fractals we wrote code
for when we got access to a computer. It impressed us enormously that an
intricate object with self-similarity over all scales could be generated
by a rather simple process:  
1\) Take three points that would define a triangle.  
2\) Take a fourth starting point.  
3\) Randomly pick one of the three vertices of the triangle. Plot the
midpoint between the fourth starting point and the chosen vertex.  
4\) Repeat this process with that midpoint for a large number of
iterations.  
5\) The points thus generated would converge to an attractor which is
the Sierpinski gasket.

This process inspired us to use this procedure more extensively to
develop other such fractal objects. We found an answer for this shortly
thereafter in a book by the mathematician Barnsley precisely about this
topic. In it Barnsley said something to the tune that we would stop
looking objects in nature the same way once we see the fractals such as
those for which he provided a recipe for construction. This had indeed
already started happening to us with our encounter with the Sierpinski
gasket. Notably, around that time we recorded a statement of Johannes
Kepler (which we read somewhere), which was earlier expression of the
same idea:  
“*I believe the geometric proportion served the creator as an idea when
he introduced the continuous generation of similar objects from similar
objects.*”

The Hindu enacts such a concept when he performs śrauta rituals with
complex rituals developing recursively with some modification from a
simple “prakṛti”.

Coming back to Barnsley, he called these fractals Iterated Function
Systems (IFS) and they are generated thus:  
![\\begin{bmatrix} x\_{n+1} \\\\ y\_{n+1} \\end{bmatrix} =
\\begin{bmatrix} a & b\\\\ c & d\\end{bmatrix}\_i \\begin{bmatrix}
x\_{n} \\\\ y\_{n} \\end{bmatrix} + \\begin{bmatrix} e \\\\ f
\\end{bmatrix}\_i; \\;
p\_i](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bbmatrix%7D+x_%7Bn%2B1%7D+%5C%5C+y_%7Bn%2B1%7D+%5Cend%7Bbmatrix%7D+%3D+%5Cbegin%7Bbmatrix%7D+a+%26+b%5C%5C+c+%26+d%5Cend%7Bbmatrix%7D_i+%5Cbegin%7Bbmatrix%7D+x_%7Bn%7D+%5C%5C+y_%7Bn%7D+%5Cend%7Bbmatrix%7D+%2B+%5Cbegin%7Bbmatrix%7D+e+%5C%5C+f+%5Cend%7Bbmatrix%7D_i%3B+%5C%3B+p_i&bg=ffffff&fg=333333&s=0
"\\begin{bmatrix} x_{n+1} \\\\ y_{n+1} \\end{bmatrix} = \\begin{bmatrix} a & b\\\\ c & d\\end{bmatrix}_i \\begin{bmatrix} x_{n} \\\\ y_{n} \\end{bmatrix} + \\begin{bmatrix} e \\\\ f \\end{bmatrix}_i; \\; p_i")  
where
![i=1..n](https://s0.wp.com/latex.php?latex=i%3D1..n&bg=ffffff&fg=333333&s=0
"i=1..n")

As one can see this map defines a set of affine transformations that are
recursively applied to the starting coordinates
![(x\_n,y\_n)](https://s0.wp.com/latex.php?latex=%28x_n%2Cy_n%29&bg=ffffff&fg=333333&s=0
"(x_n,y_n)"). However, there can be a set of n such of matrices
![1..n](https://s0.wp.com/latex.php?latex=1..n&bg=ffffff&fg=333333&s=0
"1..n") any one of which
![i](https://s0.wp.com/latex.php?latex=i&bg=ffffff&fg=333333&s=0 "i")
can be applied to the point at a time with a probability of
![p\_i](https://s0.wp.com/latex.php?latex=p_i&bg=ffffff&fg=333333&s=0
"p_i"). For each mapping of the point we have 7 numbers, 6 from the
transformation matrices
![(a..f)](https://s0.wp.com/latex.php?latex=%28a..f%29&bg=ffffff&fg=333333&s=0
"(a..f)") and the 7th being the probability with which it is applied
![p\_i](https://s0.wp.com/latex.php?latex=p_i&bg=ffffff&fg=333333&s=0
"p_i").

Barnsley’s most famous fractal map was the fern leaf. Several variants
of this have been generated (some by us and others whose creators are
either Barnsley himself or others not known to us).

![fernleaves](https://manasataramgini.files.wordpress.com/2016/12/fernleaves.png?w=640)

Figure 1: the first one is Barnsley’s original fern leaf

Given that a relatively small number of values to can generate a rather
complex object by this procedure, Barnsley developed this as a method
for compression of images. To us the IFS immediately struck us as being
a mechanism for illustrating evolution: In the simplest scenario, the
values in the above matrices and the probability of its choice can be
seen as ‘genes’ which are prone to mutations with quantitative effects
on traits. Thus, one can allow the matrices to mutate while we act as
the proxy for natural selection.

The same is quite well-illustrated by another of the IFS fractals the
leaf. In this leaf we have 4 matrices which gives us a total of
![24+4=28](https://s0.wp.com/latex.php?latex=24%2B4%3D28&bg=ffffff&fg=333333&s=0
"24+4=28") ‘genes’ which might be mutated. If we impose the conditions
of continuity of the attractor region (a very real biological one) and
reasonable bilateral symmetry then only 10 of those ‘genes’ can take
mutations. Now, by letting them undergo mutation and selection we can
see evolution occur in silico and spawn a variety of leaf forms close to
what we actually see in nature.

![ifs\_leaf](https://manasataramgini.files.wordpress.com/2016/12/ifs_leaf.png?w=640)Figure
2

One might learn two things from this:  
1\) If we give a person with no knowledge of how the matrices were
constructed for generating a given shape, e.g. the leaf, he can mutate
the ‘genes’ randomly and figure out how it works. After some mutagenesis
he would soon discover that different ‘genes’ have different
morphological roles and there is even a degree of hierarchy in terms of
their effect on form. He would soon understand the difference between
null mutations and change of function mutations. Thus, he can put
together a developmental network for the role of the ‘genes’ in the
development of the in silico leaf. In doing this on a very small scale
he would have reproduced what geneticists have done to unravel the
genetic networks for the development of real organisms like
Caenorhabditis, Drosophila and the Danio (e.g. Nüsslein-Volhard and
Wieschaus et al). Such efforts entirely dominated developmental biology
and genetics for almost two decades.

2\) Beyond doubt these efforts of the developmental geneticists
contributed fundamentally to our understanding of biology. But in the
end it spawned the field that is often irritatingly referred to as
“evo-devo” — an attempt to marry the foundation of biology in the form
of the evolutionary theory with developmental genetics. In our youth,
even as we were discovering the beauty of IFS for ourselves, we were
aligned towards a future as an evolutionary developmental geneticist. We
even thought we should apprentice ourselves as a slave in one of those
powerhouse developmental genetics labs, where we could bring our
knowledge of evolution which was much ahead of theirs in those days. It
was in this context the IFS experiments offered us an important negative
lesson. We saw that the so-called evo-devo field was proceeding in a
rather pedestrian direction. It was one where the protein or RNA
products of the genes and were mostly faceless blobs (they would often
literally be illustrated by researchers as such), with the primary
expression of the studies being simple genome-demographic summaries from
angle of genes they knew best and organism-specific variations of the
maps of gene-interactions in development. To us this was not
qualitatively telling us anything new about evolution of development
beyond what we could glean from in silico experiments with systems such
as IFS. Instead, we realized that we had to take a path that got
directly to heart of what is unique to biology, i.e. the biochemistry of
those gene products. This resonated with where we first began our
science the chemistry of biological molecules. It was placing that
within the framework of the evolutionary theory, which was to lead us
closer to the foundations of biology than any of this other stuff.

In our childhood we had spent a lot of time simply gazing through the
kaleidoscope. It brought home to us that one principle of aesthetics was
symmetry. When we learned of IFS we saw how simple recursion was a
second principle of aesthetics. We found that a very simple IFS could
result objects of great beauty especially when combined with first
principle symmetry. This led us to play with a simple map, namely one to
generate the limit curve of a bifurcating tree. This can be done by
choosing the below three matrices with equal probability:

![\\begin{bmatrix} x\_{n+1} \\\\ y\_{n+1} \\end{bmatrix} =
\\begin{bmatrix} s \\cos(\\theta) & -s\\sin(\\theta)\\\\ s
\\sin(\\theta) & s \\cos(\\theta)\\end{bmatrix} \\begin{bmatrix} x\_{n}
\\\\ y\_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 1 \\end{bmatrix};
\\;
p\_1=\\frac{1}{3}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bbmatrix%7D+x_%7Bn%2B1%7D+%5C%5C+y_%7Bn%2B1%7D+%5Cend%7Bbmatrix%7D+%3D+%5Cbegin%7Bbmatrix%7D+s+%5Ccos%28%5Ctheta%29+%26+-s%5Csin%28%5Ctheta%29%5C%5C+s+%5Csin%28%5Ctheta%29+%26+s+%5Ccos%28%5Ctheta%29%5Cend%7Bbmatrix%7D+%5Cbegin%7Bbmatrix%7D+x_%7Bn%7D+%5C%5C+y_%7Bn%7D+%5Cend%7Bbmatrix%7D+%2B+%5Cbegin%7Bbmatrix%7D+0+%5C%5C+1+%5Cend%7Bbmatrix%7D%3B+%5C%3B+p_1%3D%5Cfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\begin{bmatrix} x_{n+1} \\\\ y_{n+1} \\end{bmatrix} = \\begin{bmatrix} s \\cos(\\theta) & -s\\sin(\\theta)\\\\ s \\sin(\\theta) & s \\cos(\\theta)\\end{bmatrix} \\begin{bmatrix} x_{n} \\\\ y_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 1 \\end{bmatrix}; \\; p_1=\\frac{1}{3}")

![\\begin{bmatrix} x\_{n+1} \\\\ y\_{n+1} \\end{bmatrix} =
\\begin{bmatrix} s \\cos(\\theta) & s\\sin(\\theta)\\\\ -s
\\sin(\\theta) & s \\cos(\\theta)\\end{bmatrix} \\begin{bmatrix} x\_{n}
\\\\ y\_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 1 \\end{bmatrix};
\\;
p\_2=\\frac{1}{3}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bbmatrix%7D+x_%7Bn%2B1%7D+%5C%5C+y_%7Bn%2B1%7D+%5Cend%7Bbmatrix%7D+%3D+%5Cbegin%7Bbmatrix%7D+s+%5Ccos%28%5Ctheta%29+%26+s%5Csin%28%5Ctheta%29%5C%5C+-s+%5Csin%28%5Ctheta%29+%26+s+%5Ccos%28%5Ctheta%29%5Cend%7Bbmatrix%7D+%5Cbegin%7Bbmatrix%7D+x_%7Bn%7D+%5C%5C+y_%7Bn%7D+%5Cend%7Bbmatrix%7D+%2B+%5Cbegin%7Bbmatrix%7D+0+%5C%5C+1+%5Cend%7Bbmatrix%7D%3B+%5C%3B+p_2%3D%5Cfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\begin{bmatrix} x_{n+1} \\\\ y_{n+1} \\end{bmatrix} = \\begin{bmatrix} s \\cos(\\theta) & s\\sin(\\theta)\\\\ -s \\sin(\\theta) & s \\cos(\\theta)\\end{bmatrix} \\begin{bmatrix} x_{n} \\\\ y_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 1 \\end{bmatrix}; \\; p_2=\\frac{1}{3}")

![\\begin{bmatrix} x\_{n+1} \\\\ y\_{n+1} \\end{bmatrix} =
\\begin{bmatrix} 1 & 0\\\\ 0 & 1\\end{bmatrix} \\begin{bmatrix} x\_{n}
\\\\ y\_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 0 \\end{bmatrix};
\\;
p\_3=\\frac{1}{3}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bbmatrix%7D+x_%7Bn%2B1%7D+%5C%5C+y_%7Bn%2B1%7D+%5Cend%7Bbmatrix%7D+%3D+%5Cbegin%7Bbmatrix%7D+1+%26+0%5C%5C+0+%26+1%5Cend%7Bbmatrix%7D+%5Cbegin%7Bbmatrix%7D+x_%7Bn%7D+%5C%5C+y_%7Bn%7D+%5Cend%7Bbmatrix%7D+%2B+%5Cbegin%7Bbmatrix%7D+0+%5C%5C+0+%5Cend%7Bbmatrix%7D%3B+%5C%3B+p_3%3D%5Cfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\begin{bmatrix} x_{n+1} \\\\ y_{n+1} \\end{bmatrix} = \\begin{bmatrix} 1 & 0\\\\ 0 & 1\\end{bmatrix} \\begin{bmatrix} x_{n} \\\\ y_{n} \\end{bmatrix} + \\begin{bmatrix} 0 \\\\ 0 \\end{bmatrix}; \\; p_3=\\frac{1}{3}")

Here ![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0
"s") is the scaling factor whereas
![\\theta](https://s0.wp.com/latex.php?latex=%5Ctheta&bg=ffffff&fg=333333&s=0
"\\theta") is the angle by which the branches of the bifurcating tree
are rotated. Finally, we can rotate each fractal a fixed number of times
to obtain a particular kaleidoscopic symmetry. In the first example
below we have an overall symmetry of 6 with various
![\\theta](https://s0.wp.com/latex.php?latex=%5Ctheta&bg=ffffff&fg=333333&s=0
"\\theta") values and
![s=\\frac{1}{\\phi}](https://s0.wp.com/latex.php?latex=s%3D%5Cfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"s=\\frac{1}{\\phi}") the Golden ratio.

![ifs\_angle\_curve](https://manasataramgini.files.wordpress.com/2016/12/ifs_angle_curve.png?w=640)Figure
3

In the second example we have a symmetry of 4 with similar rotations and
scaling as above. One may note that the first case in this figure where
![\\theta=\\frac{\\pi}{4}](https://s0.wp.com/latex.php?latex=%5Ctheta%3D%5Cfrac%7B%5Cpi%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\theta=\\frac{\\pi}{4}") we get a structure that is immediately
reminiscent of the floor plans towards which the central spire of the
great Hindu temples (e.g. at Khajuraho) converged to before the coming
down of the green curtain.

![ifs\_angle\_curve\_4](https://manasataramgini.files.wordpress.com/2016/12/ifs_angle_curve_4.png?w=640)Figure
4
