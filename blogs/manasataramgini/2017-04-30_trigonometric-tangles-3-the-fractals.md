+++
title = "Trigonometric tangles-3: the fractals"

+++
See also:
<https://manasataramgini.wordpress.com/2016/05/06/the-astroid-the-deltoid-and-the-fish-within-the-fish/>

This exploration began in days of youth shortly after we learned about
complex numbers. It culminated only much later in adulthood when we
discovered for ourselves a class of fractal curves related to a
celebrated curve discovered by the great mathematicians Bernhard Riemann
and Karl Weierstrass. We detail it here covering some very elementary
mathematics because retracing the path one has taken often helps when
one has to teach the same to a young student of pedestrian quantitative
IQ like ourselves.

A unit circle with center at origin
(![0+0i](https://s0.wp.com/latex.php?latex=0%2B0i&bg=ffffff&fg=333333&s=0
"0+0i")) may be defined in the complex plane by the equation:  
![z=\\cos(\\theta)+i\\sin(\\theta); \\; \\theta \\in
\[0,2\\pi\]](https://s0.wp.com/latex.php?latex=z%3D%5Ccos%28%5Ctheta%29%2Bi%5Csin%28%5Ctheta%29%3B+%5C%3B+%5Ctheta+%5Cin+%5B0%2C2%5Cpi%5D&bg=ffffff&fg=333333&s=0
"z=\\cos(\\theta)+i\\sin(\\theta); \\; \\theta \\in [0,2\\pi]"),  
which by the fundamental discovery of the great Leonhard Euler
becomes:  
![z=e^{i\\theta}](https://s0.wp.com/latex.php?latex=z%3De%5E%7Bi%5Ctheta%7D&bg=ffffff&fg=333333&s=0
"z=e^{i\\theta}")  
From the above it is apparent that equation of this unit circle might be
written as:  
![z\\overline{z} = |z|=1; \\; z \\in
\\mathbb{C}](https://s0.wp.com/latex.php?latex=z%5Coverline%7Bz%7D+%3D+%7Cz%7C%3D1%3B+%5C%3B+z+%5Cin+%5Cmathbb%7BC%7D&bg=ffffff&fg=333333&s=0
"z\\overline{z} = |z|=1; \\; z \\in \\mathbb{C}")  
Now this definition of the unit circle in the complex allows us carry
out a variety of interesting mappings. A mapping is an operation which
transforms the points on the unit circle
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") to
another set of points
![z'](https://s0.wp.com/latex.php?latex=z%27&bg=ffffff&fg=333333&s=0
"z'"). The simplest of these is the power operation:  
![z' \\mapsto z^n \\; n \\in
\\mathbb{N}](https://s0.wp.com/latex.php?latex=z%27+%5Cmapsto+z%5En+%5C%3B+n+%5Cin+%5Cmathbb%7BN%7D&bg=ffffff&fg=333333&s=0
"z' \\mapsto z^n \\; n \\in \\mathbb{N}")  
This mapping simply involves the operation of raising every
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") to
a positive integer
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") to
obtain
![z'](https://s0.wp.com/latex.php?latex=z%27&bg=ffffff&fg=333333&s=0
"z'"). What this operation does is to simply redistribute the points
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") to
other points
![z'](https://s0.wp.com/latex.php?latex=z%27&bg=ffffff&fg=333333&s=0
"z'") back on the unit circle. However, if we connect every
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") to
its corresponding
![z'](https://s0.wp.com/latex.php?latex=z%27&bg=ffffff&fg=333333&s=0
"z'") by a segment then the envelope of those segments defines an
epicycloid in the unit circle with
![n-1](https://s0.wp.com/latex.php?latex=n-1&bg=ffffff&fg=333333&s=0
"n-1") cusps. Thus, for squaring we get a cardioid, for cubing a
nephroid, for power 4 a tricuspid epicycloid and so on.

![epicycloids\_complex](https://manasataramgini.files.wordpress.com/2017/04/epicycloids_complex.png?w=640)

Figure 1: Epicycloids obtained via the map ![z' \\mapsto z^n \\; n \\in
\\mathbb{N}](https://s0.wp.com/latex.php?latex=z%27+%5Cmapsto+z%5En+%5C%3B+n+%5Cin+%5Cmathbb%7BN%7D&bg=ffffff&fg=333333&s=0
"z' \\mapsto z^n \\; n \\in \\mathbb{N}") map

It is this relationship to the exponent which gives basis for the form
of the core region of the famous fractal known as the Mandelbrot set.
Thus, for a Mandelbrot set created by the the map of the form
![z'=z^2+c](https://s0.wp.com/latex.php?latex=z%27%3Dz%5E2%2Bc&bg=ffffff&fg=333333&s=0
"z'=z^2+c") we get a cardioid; for
![z'=z^3+c](https://s0.wp.com/latex.php?latex=z%27%3Dz%5E3%2Bc&bg=ffffff&fg=333333&s=0
"z'=z^3+c") we get a nephroid; so on.

![Mandelbrot\_zcubed](https://manasataramgini.files.wordpress.com/2017/04/mandelbrot_zcubed.png?w=640)Figure
2: Mandelbrot set for
![z^3](https://s0.wp.com/latex.php?latex=z%5E3&bg=ffffff&fg=333333&s=0
"z^3") showing nephroid

Now, you can distort the unit circle by the map of the form:  
![z'\\mapsto az+b\\overline{z}; \\; a,b \\in
\\mathbb{C}](https://s0.wp.com/latex.php?latex=z%27%5Cmapsto+az%2Bb%5Coverline%7Bz%7D%3B+%5C%3B+a%2Cb+%5Cin+%5Cmathbb%7BC%7D&bg=ffffff&fg=333333&s=0
"z'\\mapsto az+b\\overline{z}; \\; a,b \\in \\mathbb{C}")  
This yields an ellipse with foci at ![\\pm
\\sqrt{ab}](https://s0.wp.com/latex.php?latex=%5Cpm+%5Csqrt%7Bab%7D&bg=ffffff&fg=333333&s=0
"\\pm \\sqrt{ab}") and can be visualized as the projection of the great
circles of a sphere on to a plane.

![circle2ellipse](https://manasataramgini.files.wordpress.com/2017/04/circle2ellipse.png?w=640)

Figure 3: Mapping a unit circle on to ellipses.

Instead of the unit circle with center at origin let us consider a
general circle in the complex plane. Its equation is:  
![|z-c|=a; \\; a \\in \\mathbb{R}; c \\in
\\mathbb{C}](https://s0.wp.com/latex.php?latex=%7Cz-c%7C%3Da%3B+%5C%3B+a+%5Cin+%5Cmathbb%7BR%7D%3B+c+%5Cin+%5Cmathbb%7BC%7D&bg=ffffff&fg=333333&s=0
"|z-c|=a; \\; a \\in \\mathbb{R}; c \\in \\mathbb{C}")  
Thus the center of the circle is at
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
and radius is
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
Now let us consider a circle with ![c=1+0i,
a=1](https://s0.wp.com/latex.php?latex=c%3D1%2B0i%2C+a%3D1&bg=ffffff&fg=333333&s=0
"c=1+0i, a=1") — a unit circle passing through origin. If we deploy the
following map on it ![z'\\mapsto
\\sqrt{z}](https://s0.wp.com/latex.php?latex=z%27%5Cmapsto+%5Csqrt%7Bz%7D&bg=ffffff&fg=333333&s=0
"z'\\mapsto \\sqrt{z}"), the square root function being two-valued
creates a ![1\\mapsto
2](https://s0.wp.com/latex.php?latex=1%5Cmapsto+2&bg=ffffff&fg=333333&s=0
"1\\mapsto 2") mapping. This results in the bilobed lemniscate
discovered by Jakob Bernoulli which crosses over at origin and with foci
at ![\\pm
1](https://s0.wp.com/latex.php?latex=%5Cpm+1&bg=ffffff&fg=333333&s=0
"\\pm 1"). If we instead deploy the squaring map ![z'\\mapsto
z^2](https://s0.wp.com/latex.php?latex=z%27%5Cmapsto+z%5E2&bg=ffffff&fg=333333&s=0
"z'\\mapsto z^2") on this circle we end up with a cardioid. Instead of
the above unit circle consider a vertical line passing through
![c=1+0i](https://s0.wp.com/latex.php?latex=c%3D1%2B0i&bg=ffffff&fg=333333&s=0
"c=1+0i"). Its equation would be
![z=1+iy](https://s0.wp.com/latex.php?latex=z%3D1%2Biy&bg=ffffff&fg=333333&s=0
"z=1+iy"). If we similarly apply the square root operator on it gets
mapped onto to a double branched curve the rectangular hyperbola. On the
other hand application of the squaring operator on this vertical line
bends it into a left facing parabola. Thus, the ellipse, hyperbola and
parabola can be seen as secondary conics generated from the line and
circle.

![circle\_cassinian\_map](https://manasataramgini.files.wordpress.com/2017/04/circle_cassinian_map.png?w=640)Figure
4

Now if the circle has
![a\<1](https://s0.wp.com/latex.php?latex=a%3C1&bg=ffffff&fg=333333&s=0
"a\<1") then the same square root map creates two disjoint lobes which
are the ovals discovered by the astronomer Cassini, whereas the square
map creates a limacon. Similarly if
![a\>1](https://s0.wp.com/latex.php?latex=a%3E1&bg=ffffff&fg=333333&s=0
"a\>1") the mapping merges the lobes into continuous Cassinian curves
and limacons with an internal lobe.

Having seen these very simple maps we now move on to the fractal
mappings of the unit circle at origin which use the same basic principle
but a mapping function that can generate fractal structure. Upon
discovering these we realized that what we arrived at what is a
generalized form the Riemann-Weierstrass function. Hence, before we look
a those mappings we shall take a brief look at this remarkable function
that marked the beginning of the study of fractals. The great Carl Gauss
wondered if all continuous functions are differentiable except at a
“limited” set of special points (e.g. the cusp of an epicycloid). A
few years after his death his brilliant successor Bernhard Riemann
discovered a function which is continuous everywhere but is most
undifferentiable. He was probably unable to develop this further due to
his early death a few years later. Karl Weierstrass presented this
function in a more complete form and subsequently Hardy established a
partial proof for its undifferentiablity. These self-similar curves can
be formulated in multiple different ways of which the simplest is of the
form:  
![y=\\displaystyle \\sum\_{n=1}^\\infty \\dfrac{\\sin(n^a \\pi x)}{(n^a
\\pi)}; \\; a,n \\in
\\mathbb{N}\_1](https://s0.wp.com/latex.php?latex=y%3D%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%5Csin%28n%5Ea+%5Cpi+x%29%7D%7B%28n%5Ea+%5Cpi%29%7D%3B+%5C%3B+a%2Cn+%5Cin+%5Cmathbb%7BN%7D_1&bg=ffffff&fg=333333&s=0
"y=\\displaystyle \\sum_{n=1}^\\infty \\dfrac{\\sin(n^a \\pi x)}{(n^a \\pi)}; \\; a,n \\in \\mathbb{N}_1")  
Here ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") is the power which above 5 considerably smoothens the curve.

![weierstrass](https://manasataramgini.files.wordpress.com/2017/04/weierstrass.png?w=640)

Figure 5

Another formulation which generates a greater variety of these curves is
given by:  
![y=\\displaystyle \\sum\_{n=0}^\\infty a^n \\cos(b^n \\pi x);\\; a \\in
(0,1), b \\in
(1,\\infty)](https://s0.wp.com/latex.php?latex=y%3D%5Cdisplaystyle+%5Csum_%7Bn%3D0%7D%5E%5Cinfty+a%5En+%5Ccos%28b%5En+%5Cpi+x%29%3B%5C%3B+a+%5Cin+%280%2C1%29%2C+b+%5Cin+%281%2C%5Cinfty%29&bg=ffffff&fg=333333&s=0
"y=\\displaystyle \\sum_{n=0}^\\infty a^n \\cos(b^n \\pi x);\\; a \\in (0,1), b \\in (1,\\infty)")

This form recapitulates a range of interesting behavior like the
outlines of coastlines, clouds and mountains, and seemingly chaotic
fluctuations of values like light output of variable stars, climatic
variables and market prices.

![weierstrass2](https://manasataramgini.files.wordpress.com/2017/04/weierstrass2.png?w=640)

Figure 6

Now, our mappings on in complex plane are generated by the below map
operating on the unit circle described with center at
![0+0i](https://s0.wp.com/latex.php?latex=0%2B0i&bg=ffffff&fg=333333&s=0
"0+0i"):

![z' \\mapsto \\displaystyle \\sum\_{n=0}^\\infty
\\dfrac{z^{\\left(a+bn\\right)^c}}{\\left(a+bn\\right)^c}; \\; a,b,c
\\in
\\mathbb{R}](https://s0.wp.com/latex.php?latex=z%27+%5Cmapsto+%5Cdisplaystyle+%5Csum_%7Bn%3D0%7D%5E%5Cinfty+%5Cdfrac%7Bz%5E%7B%5Cleft%28a%2Bbn%5Cright%29%5Ec%7D%7D%7B%5Cleft%28a%2Bbn%5Cright%29%5Ec%7D%3B+%5C%3B+a%2Cb%2Cc+%5Cin+%5Cmathbb%7BR%7D&bg=ffffff&fg=333333&s=0
"z' \\mapsto \\displaystyle \\sum_{n=0}^\\infty \\dfrac{z^{\\left(a+bn\\right)^c}}{\\left(a+bn\\right)^c}; \\; a,b,c \\in \\mathbb{R}")  
“Good” forms are obtained for relative small
![(a,b,c)](https://s0.wp.com/latex.php?latex=%28a%2Cb%2Cc%29&bg=ffffff&fg=333333&s=0
"(a,b,c)"). In particular ![c \\in
\[1.5,3\]](https://s0.wp.com/latex.php?latex=c+%5Cin+%5B1.5%2C3%5D&bg=ffffff&fg=333333&s=0
"c \\in [1.5,3]"). The fractal forms generated by these mappings appear
to have some value in capturing various biological forms. One of the
most obvious forms that becomes apparent is the crenulated margin of a
leaf (e.g. first curve below). Indeed, we have used this and other
related Riemann-Weierstrass function formulations to generate a range of
leaf like forms.

![weierstrass\_tangles03](https://manasataramgini.files.wordpress.com/2017/04/weierstrass_tangles03.png?w=640)

Figure 7: various fractal maps of the above form with
![c=2](https://s0.wp.com/latex.php?latex=c%3D2&bg=ffffff&fg=333333&s=0
"c=2")

Another problem for which we found inspiration as we studied these
curves was that of packaging DNA in the cell. A bacterium like the
laboratory Escherichia coli has a cell of length \~.002 millimeter and
0.00157 mm circumference. However, its genome when fully extended is a
circle of circumference \~1.5 mm. So how is that circle of DNA fitted
into a cell with much smaller circumference and length? This is achieved
by coiling the chromosomal circle into loops and those loops to further
loops by the action of topoisomerases. Maps such as the above can
provide a means of visualizing such a looping processing.

![weierstrass\_tangles01](https://manasataramgini.files.wordpress.com/2017/04/weierstrass_tangles01.png?w=640)

Figure 8: Further fractal maps with
![c=2](https://s0.wp.com/latex.php?latex=c%3D2&bg=ffffff&fg=333333&s=0
"c=2") showing intricate looping.

Another activity in which these functions may be put to use is to
generate “music”. However, we are not presenting any samples here
because we had generated them long ago using a different programming
language we no longer use and are not sufficiently motivated to re-write
the “musical” code in the language we are currently using for these
demonstrations.

![weierstrass\_tangles04](https://manasataramgini.files.wordpress.com/2017/04/weierstrass_tangles04.png?w=640)Figure
9: Further fractal maps with fractional
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c").
