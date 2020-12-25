+++
title = "The cosine principle, radial effect and entropy in the generalized Lozixa0map"

+++
The generalized [Lozi
map](https://manasataramgini.wordpress.com/2016/12/26/some-reminiscences-of-our-study-of-chaotic-maps-2/)
is a good way to illustrate the cosine principle and the radial effects
(in lay circles to which I belong in this regard, as opposed to
mathematicians). The generalized Lozi map is a 2-dimensional map defined
thus:

![x\_{n+1}= 1 + y\_n +
a\|x\_n\|](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D+1+%2B+y_n+%2B+a%7Cx_n%7C&bg=ffffff&fg=333333&s=0&c=20201002 "x_{n+1}= 1 + y_n + a|x_n|")  
![y\_{n+1}=
-x\_n](https://s0.wp.com/latex.php?latex=y_%7Bn%2B1%7D%3D+-x_n&bg=ffffff&fg=333333&s=0&c=20201002 "y_{n+1}= -x_n")

The map is area-preserving and yields “aesthetic” images for ![a \\in
\[-0.6,1.1\]](https://s0.wp.com/latex.php?latex=a+%5Cin+%5B-0.6%2C1.1%5D&bg=ffffff&fg=333333&s=0&c=20201002 "a \in [-0.6,1.1]").
Additionally, values ![a=-1;
a=\\sqrt{2}](https://s0.wp.com/latex.php?latex=a%3D-1%3B+a%3D%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "a=-1; a=\sqrt{2}")
are also somewhat aesthetic and interesting. We have previously
described the [cosine
principle](https://manasataramgini.wordpress.com/2019/01/06/a-novel-discrete-map-exhibiting-chaotic-behavior/)
for various dynamical systems, but we reiterate it here for the
generalized Lozi map as it is one of the easiest ones to explain to a
layperson. First, a few words on how we visualize this map. We start
with the vertices of a 60-sided polygon circumscribed by a circle of
radius
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0&c=20201002 "r"),
centered at
![(0,0)](https://s0.wp.com/latex.php?latex=%280%2C0%29&bg=ffffff&fg=333333&s=0&c=20201002 "(0,0)"),
and record the evolution of each vertex for a 1000 iterations under the
map. Since the map has an absolute value term, it will be bilaterally
symmetric along the line
![y=-x](https://s0.wp.com/latex.php?latex=y%3D-x&bg=ffffff&fg=333333&s=0&c=20201002 "y=-x").
Hence, we rotate the iterates by an angle of
![-\\tfrac{\\pi}{4}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B%5Cpi%7D%7B4%7D&bg=ffffff&fg=333333&s=0&c=20201002 "-\tfrac{\pi}{4}"),
then scale and center the points, and plot the evolutes of each vertex
(orbit of the vertex) in a different color. The examples of 9 such
mappings starting with the said polygon in a circle of radius
![r=0.2](https://s0.wp.com/latex.php?latex=r%3D0.2&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.2")
are shown in Figure 1.

[![Lozi1](https://manasataramgini.files.wordpress.com/2020/12/lozi1.png?w=602&h=602)](https://manasataramgini.files.wordpress.com/2020/12/lozi1.png)

Figure 1

The values of of the parameter are chosen such that
![a=2\\cos\\left(\\tfrac{2\\pi}{p/q}\\right)](https://s0.wp.com/latex.php?latex=a%3D2%5Ccos%5Cleft%28%5Ctfrac%7B2%5Cpi%7D%7Bp%2Fq%7D%5Cright%29&bg=ffffff&fg=333333&s=0&c=20201002 "a=2\cos\left(\tfrac{2\pi}{p/q}\right)"),
where
![p,q](https://s0.wp.com/latex.php?latex=p%2Cq&bg=ffffff&fg=333333&s=0&c=20201002 "p,q")
are integers. We observe that the value of
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")
determines a key aspect of the shape of the map, i.e. in each map there
is a central, largely excluded area that takes the form of a polygon
with
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")-sides.
This is the cosine principle. More generally, the shape of the central
region of the map is determined by the
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")
corresponding to the
![2\\cos(\\theta)](https://s0.wp.com/latex.php?latex=2%5Ccos%28%5Ctheta%29&bg=ffffff&fg=333333&s=0&c=20201002 "2\cos(\theta)")
closest to
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a").
Note that for the case
![\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\tfrac{\pi}{2}"),
we take a number relatively close to 0, for at 0 the map is degenerate.
Outside of the polygonal exclusion zone, we may find chaotic behavior
but it is still bounded within a unique external shape. The chaos is
particularly apparent in the cases when ![a=-1; 1;
\\sqrt{2}](https://s0.wp.com/latex.php?latex=a%3D-1%3B+1%3B+%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "a=-1; 1; \sqrt{2}")
when the map respectively yields the headless gingerbread man, the
classical gingerbread man and the tripodal gingerbread man strange
attractors. At the other values of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a"),
we see bands of chaos interspersed with rings of closed loops that
resemble the period-doubling phenomenon in other strange attractors
prior to the outbreak of full-fledged chaos.

In Figure 2 we produce the same plot by changing the radius of the
circumscribing circle of the initial polygon to
![r=0.45](https://s0.wp.com/latex.php?latex=r%3D0.45&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.45").
We can see that at this radius, for the low
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")
the cosine principle remains dominant, but for large
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")
the polygonal zone gets “smoothened” out (e.g. for
![p=9..11](https://s0.wp.com/latex.php?latex=p%3D9..11&bg=ffffff&fg=333333&s=0&c=20201002 "p=9..11")).
This indicates the radial principle, i.e. the effect of the starting
radius on the degree of expression of the cosine principle in the map.

[![Lozi2](https://manasataramgini.files.wordpress.com/2020/12/lozi2.png?w=580&h=580)](https://manasataramgini.files.wordpress.com/2020/12/lozi2.png)

Figure 2

The degree of chaos can be seen as the measure of entropy of the map. By
following the colors, one can see that when ![a=-1; 1;
\\sqrt{2}](https://s0.wp.com/latex.php?latex=a%3D-1%3B+1%3B+%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "a=-1; 1; \sqrt{2}")
the orbits of a given starting vertex under the map are all over the
place within the attractor boundary. In contrast, for the other values
of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a"),
the evolutes are mostly limited to particular bands. When ![a \\approx
0](https://s0.wp.com/latex.php?latex=a+%5Capprox+0&bg=ffffff&fg=333333&s=0&c=20201002 "a \approx 0")
then the evolute of each vertex is limited to a certain concentric
curve. Thus, the former lie at the high end of the entropy spectrum and
the latter at the low end. A proxy for the entropy distribution of the
attractor can be obtained by computing the coefficient of variation,
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0&c=20201002 "c"),
i.e. the ratio of the standard deviation to the mean of the distances of
the evolutes of a particular vertex from the center of the map:

![c=\\dfrac{\\sigma\_d}{\\mu\_d}](https://s0.wp.com/latex.php?latex=c%3D%5Cdfrac%7B%5Csigma_d%7D%7B%5Cmu_d%7D&bg=ffffff&fg=333333&s=0&c=20201002 "c=\dfrac{\sigma_d}{\mu_d}"),
where
![\\sigma\_d](https://s0.wp.com/latex.php?latex=%5Csigma_d&bg=ffffff&fg=333333&s=0&c=20201002 "\sigma_d")
is the standard deviation and
![\\mu\_d](https://s0.wp.com/latex.php?latex=%5Cmu_d&bg=ffffff&fg=333333&s=0&c=20201002 "\mu_d")
the mean distance from the center

We plot
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0&c=20201002 "c")
for the maps with
![r=0.2](https://s0.wp.com/latex.php?latex=r%3D0.2&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.2")
(Figure 1) and
![r=0.45](https://s0.wp.com/latex.php?latex=r%3D0.45&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.45")
(Figure 2) for each vertex at 60 angles from
![0..2\\pi](https://s0.wp.com/latex.php?latex=0..2%5Cpi&bg=ffffff&fg=333333&s=0&c=20201002 "0..2\pi")
respectively in Figures 3 and 4. The mean
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0&c=20201002 "c")
is shown as
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0&c=20201002 "\mu")
for each plot.

[![entropy1](https://manasataramgini.files.wordpress.com/2020/12/entropy1.png?w=506&h=506)](https://manasataramgini.files.wordpress.com/2020/12/entropy1.png)Figure
3

[![entropy2](https://manasataramgini.files.wordpress.com/2020/12/entropy2.png?w=476&h=476)](https://manasataramgini.files.wordpress.com/2020/12/entropy2.png)Figure
4

We note that
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0&c=20201002 "\mu")
for ![a=-1; 1;
\\sqrt{2}](https://s0.wp.com/latex.php?latex=a%3D-1%3B+1%3B+%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "a=-1; 1; \sqrt{2}")
is significantly (an order of magnitude) greater than the
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0&c=20201002 "\mu")
those for the other
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a").
Further, the radial effect can also be seen affecting the entropy of a
map. While it remains roughly the same or is lower for the high entropy
triangular, hexagonal and octagonal
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a"),
for the remaining polygonal
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a")
the entropy rises at
![r=0.45](https://s0.wp.com/latex.php?latex=r%3D0.45&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.45")
relative
![r=0.2](https://s0.wp.com/latex.php?latex=r%3D0.2&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.2").
In the pentagonal case, it is mostly across the board while we see
specific peaks in the decagonal and heptagonal case.

We next examine the radial effect and entropy more systematically for a
fixed value of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a")
by choosing the hendecagonal value
![a=2\\cos\\left(\\tfrac{2\\pi}{11/3}\\right)](https://s0.wp.com/latex.php?latex=a%3D2%5Ccos%5Cleft%28%5Ctfrac%7B2%5Cpi%7D%7B11%2F3%7D%5Cright%29&bg=ffffff&fg=333333&s=0&c=20201002 "a=2\cos\left(\tfrac{2\pi}{11/3}\right)").
The map is shown in Figure 5 and the entropy proxy
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0&c=20201002 "c")
in Figure 6.

[![Lozi5](https://manasataramgini.files.wordpress.com/2020/12/lozi5.png?w=587&h=587)](https://manasataramgini.files.wordpress.com/2020/12/lozi5.png)Figure
5

![entropy5](https://manasataramgini.files.wordpress.com/2020/12/entropy5.png?w=473&h=473)Figure
6

Here we see two disconnected effects of the radius. First, at certain
values the inner hendecagon is lost (e.g.
![r=0.1](https://s0.wp.com/latex.php?latex=r%3D0.1&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.1"))
or becomes smoothened out (e.g. ![r=0.5;
0.6](https://s0.wp.com/latex.php?latex=r%3D0.5%3B+0.6&bg=ffffff&fg=333333&s=0&c=20201002 "r=0.5; 0.6")).
Second, the entropy of the orbits of certain vertices dramatically rises
for some values (e.g. ![r=
0.5..0.8](https://s0.wp.com/latex.php?latex=r%3D+0.5..0.8&bg=ffffff&fg=333333&s=0&c=20201002 "r= 0.5..0.8")).
The radial effect on neither the entropy nor the expression of the
polygonal inner zone is the same across different
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a")
values. However, more generally, the lower the number of polygon sides,
stronger is the polygonal expression across
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0&c=20201002 "r").

Finally, we touch upon a general philosophical point that can be
realized from such chaotic systems. While it is not specific to this
generalized Lozi attractor, we take this opportunity to articulate it
because we have presented the entropy concept. Most people agree that
the attractors with neither too much entropy nor too little entropy are
aesthetically most pleasing. This also has a counterpart in biology.
Selection tends to prefer systems with an optimal entropy. Too much
entropy in a structure (say a protein) and it is too disordered to be
useful for most functions. Too little entropy and it is again too rigid
to be useful for much. Moreover, from an evolvability viewpoint, too
rigid a structure offers too little option for exploring multiple
functions in biochemical function space. Too much disorder again means
that it explores too much space to perform any function well enough to
be selected. Hence, structures with some entropy optimum tend to be
selected rather than those with minimum or maximum entropy. Selection
can be conceived as maximizing a certain function, say
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0&c=20201002 "f(x)")
for simplicity, in a given entity under selection. This
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0&c=20201002 "f(x)")
will then be the fitness function. We can see from the above that
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0&c=20201002 "f(x)")
cannot directly or inversely track mean entropy because that will not
maximize fitness which is at some optimal entropy. It has to hence track
something else. This would depend on the optimal band of entropy that is
selected by the given constraints. For example, one field of constraints
could select for an optimal band of mean
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0&c=20201002 "c"),
like ![\\mu \\in \[0.03,
0.1\]](https://s0.wp.com/latex.php?latex=%5Cmu+%5Cin+%5B0.03%2C+0.1%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\mu \in [0.03, 0.1]").
Such a field will select
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a")
corresponding to the pentagon, heptagon, nonagon and decagon while
avoiding the triangle, hexagon and octagon for too high entropy and the
square and hendecagon for too low entropy (Figure 1, 3). This constraint
field will also select for other values (e.g. Figures 7 and 8) that have
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0&c=20201002 "\mu")
is in this interval (Panels 1, 2, 6). Thus, the
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0&c=20201002 "f(x)")
will be a function with local peaks that is very different from the
underlying reality of a continuous entropy distribution from low to
high. Thus, selection translates the underlying reality into a sensed
structure very different from it. The philosophical corollary to this is
that a sensed structure will be different from and unlikely to reflect
the underlying reality.

[![Lozi6](https://manasataramgini.files.wordpress.com/2020/12/lozi6.png?w=586&h=586)](https://manasataramgini.files.wordpress.com/2020/12/lozi6.png)Figure
7

[![entropy6](https://manasataramgini.files.wordpress.com/2020/12/entropy6.png?w=508&h=508)](https://manasataramgini.files.wordpress.com/2020/12/entropy6.png)Figure
8
