+++
title = "Median and pedal triangles and derived fractals: an introductory account"

+++
It is rather easily seen that joining the midpoints of the sides of a
triangle yields four congruent triangles that in turn are similar to the
original triangle (Figure 1). This figure might be used to provided a
self-evident geometric demonstration of the sum of a series (Figure 1):

![1by4\_1by3](https://manasataramgini.files.wordpress.com/2017/08/1by4_1by3.png?w=640)Figure
1

![\\dfrac{1}{4}+\\dfrac{1}{16}+\\dfrac{1}{64}... = \\displaystyle
\\sum\_{k=1}^{\\infty}
\\dfrac{1}{4^k}=\\dfrac{1}{3}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B4%7D%2B%5Cdfrac%7B1%7D%7B16%7D%2B%5Cdfrac%7B1%7D%7B64%7D...+%3D+%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%7D%7B4%5Ek%7D%3D%5Cdfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{4}+\\dfrac{1}{16}+\\dfrac{1}{64}... = \\displaystyle \\sum_{k=1}^{\\infty} \\dfrac{1}{4^k}=\\dfrac{1}{3}")

This median triangle is also the source of rather miraculous figure
(Figure 2) that has attracted and delighted numerous mathematicians and
laymen alike since at least the days of the mathematician Cesaro. The
figure in question is obtained rather easily: Remove the median triangle
(![\\triangle
EFD](https://s0.wp.com/latex.php?latex=%5Ctriangle+EFD&bg=ffffff&fg=333333&s=0
"\\triangle EFD")) of a starting triangle ![\\triangle
ABC](https://s0.wp.com/latex.php?latex=%5Ctriangle+ABC&bg=ffffff&fg=333333&s=0
"\\triangle ABC"). Repeat this procedure on the three remaining
congruent triangles. Continue ad infinitum. The figure you get (Figure
2) is famous as the Sierpinski triangle.

![sierpinski](https://manasataramgini.files.wordpress.com/2017/08/sierpinski.png?w=640)Figure
2

While this is the geometrically obvious way of constructing it, the
Sierpinski triangle can also be constructed by a slightly less-obvious
method. Take a starting triangle and a random initial point. Randomly
choose one of the three vertices of the starting triangle and draw the
midpoint between the initial point and the chosen vertex. This midpoint
becomes the new initial point. Again chose one of the three vertices of
the starting triangle randomly and draw the midpoint between the new
initial point and the chosen vertex. Repeat this process endlessly.
Surprisingly, all the points drawn by the above procedure will settle
down into a locus which is the same Sierpinski triangle (Figure 3). One
of the very first programs we have memory of writing was to draw this
figure by this method.

![Sierpinski](https://manasataramgini.files.wordpress.com/2017/08/sierpinski1-e1501732678652.png?w=640)Figure
3

Notably, this figure also arises rather organically from arithmetic,
thereby pointing to a deep connection between simple numbers and
geometry. Consider the below matrix
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0 "M"):

![\\begin{matrix} & & & & 1 & & & & &\\\\ & & & 1 & & 1 & & & & \\\\ & &
1 & & 2 & & 1 & & & \\\\ & 1 & & 3 & & 3 & & 1 & & \\\\ 1 & & 4 & & 6 &
& 4 & & 1 & \\\\
\\end{matrix}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bmatrix%7D+%26+%26+%26+%26+1+%26+%26+%26+%26+%26%5C%5C+%26+%26+%26+1+%26+%26+1+%26+%26+%26+%26+%5C%5C+%26+%26+1+%26+%26+2+%26+%26+1+%26+%26+%26+%5C%5C+%26+1+%26+%26+3+%26+%26+3+%26+%26+1+%26+%26+%5C%5C+1+%26+%26+4+%26+%26+6+%26+%26+4+%26+%26+1+%26+%5C%5C+%5Cend%7Bmatrix%7D&bg=ffffff&fg=333333&s=0
"\\begin{matrix} & & & & 1 & & & & &\\\\ & & & 1 & & 1 & & & & \\\\ & & 1 & & 2 & & 1 & & & \\\\ & 1 & & 3 & & 3 & & 1 & & \\\\ 1 & & 4 & & 6 & & 4 & & 1 & \\\\ \\end{matrix}")

This is the well-known meru-prastāra of the Hindus of yore. The
expansion of the binomial
![(x+y)^n](https://s0.wp.com/latex.php?latex=%28x%2By%29%5En&bg=ffffff&fg=333333&s=0
"(x+y)^n") has the coefficients as above. Now, if we apply the modulo
operator ![M \\; \\mathrm{mod} \\;
2](https://s0.wp.com/latex.php?latex=M+%5C%3B+%5Cmathrm%7Bmod%7D+%5C%3B+2&bg=ffffff&fg=333333&s=0
"M \\; \\mathrm{mod} \\; 2") to this matrix it is converted to a matrix
of 0s and 1s. If we assign different color values to 0 and 1 and plot
the matrix then we get our Sierpinski triangle (Figure 4).

![Meru\_sierpinski](https://manasataramgini.files.wordpress.com/2017/08/meru_sierpinski.jpg?w=640)Figure
4

The Sierpinski triangle is a good way of illustrating fractal dimension
to a beginner. Topological dimension is defined as the degrees of
freedom of movement one has on a given geometric entity. On a point we
cannot move anywhere other than it; hence we have 0 degrees of freedom
and its dimension is 0. On a line we can move along the line; hence we
have 1 degree of freedom. On plane likewise we have 2 degrees of freedom
and so on. This can be objectively measured for a figure based on how
many copies
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") of
the original figure we get when we magnify it by a certain factor
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0 "M").
Thus we define the dimension as:  
![D=\\dfrac{\\log(k)}{\\log(M)}](https://s0.wp.com/latex.php?latex=D%3D%5Cdfrac%7B%5Clog%28k%29%7D%7B%5Clog%28M%29%7D&bg=ffffff&fg=333333&s=0
"D=\\dfrac{\\log(k)}{\\log(M)}")

On can see that if we magnify a linear segment by two then we can fit
two copies of the original segment in the magnification; thus
![D=\\tfrac{\\log 2}{\\log
2}=1](https://s0.wp.com/latex.php?latex=D%3D%5Ctfrac%7B%5Clog+2%7D%7B%5Clog+2%7D%3D1&bg=ffffff&fg=333333&s=0
"D=\\tfrac{\\log 2}{\\log 2}=1"). If we magnify a square by two we get
four copies of of the original square; thus ![D=\\tfrac{\\log 2^2}{\\log
2}=2](https://s0.wp.com/latex.php?latex=D%3D%5Ctfrac%7B%5Clog+2%5E2%7D%7B%5Clog+2%7D%3D2&bg=ffffff&fg=333333&s=0
"D=\\tfrac{\\log 2^2}{\\log 2}=2"). If we magnify a cube by two then we
can fit 8 copies of the original cube in the magnification; thus
![D=\\tfrac{\\log 2^3}{\\log
2}=3](https://s0.wp.com/latex.php?latex=D%3D%5Ctfrac%7B%5Clog+2%5E3%7D%7B%5Clog+2%7D%3D3&bg=ffffff&fg=333333&s=0
"D=\\tfrac{\\log 2^3}{\\log 2}=3"). But what about a figure like the
Sierpinski triangle? From the above figure we can see that for each
doubling of magnification of the Sierpinski triangle we get 3 copies of
it. Thus, ![D=\\tfrac{\\log 3}{\\log
2}=1.584963](https://s0.wp.com/latex.php?latex=D%3D%5Ctfrac%7B%5Clog+3%7D%7B%5Clog+2%7D%3D1.584963&bg=ffffff&fg=333333&s=0
"D=\\tfrac{\\log 3}{\\log 2}=1.584963"). This gives us a measure for
fractional dimentionality i.e. we can move on parts of the plane but not
all of it. Thus, its dimension is neither 1 as a line nor 2 as the
complete plane but in between.

This much is known to many moderately educated people. However, a
slightly more involved figure is arises from pedal triangles (Figure 5).
Here, we draw the altitudes of an acute angled triangle (for a right
triangle two of the altitudes are its sides while for an obtuse angled
triangle they will lie outside). By joining the feet of the altitudes
i.e. the point where the altitude of the triangle intersects the side we
dissect the triangle again into four triangles. Here the triangles are
generally unequal. However, the three peripheral triangles generated by
this construction are similar to each other and the starting triangle
(Figure 5).

![Pedal\_triangle\_similarity](https://manasataramgini.files.wordpress.com/2017/08/pedal_triangle_similarity.png?w=640)Figure
5

If we know carry out a Sierpinski-like process described above for this
configuration of triangles we get another interesting fractal figure
(Figure 6). For an equilateral triangle it becomes same as the
Sierpinski triangle but for all other acute angled triangles it assumes
a more complex form. It appears that this fractal has an even greater
fractal dimension than the typical Sierpinski triangle.

![Pedal\_triangle](https://manasataramgini.files.wordpress.com/2017/08/pedal_triangle.png?w=640)Figure
6

Finally, returning to the midpoints of the sides of a triangle, if we
join them to the opposite vertices we then get the medians of a
triangle. The three medians are concurrent at the centroid of the
triangle. Now if we join the centroid to the three vertices of the
triangle we dissect the triangle into three triangles. Repeating this
procedure for all three newly obtained triangles and iterating it for
each of those triangles and so on we get another interesting figure
(Figure 7). This is certain fold in origami which in principle can be
carried out on paper. In this figure the area of each triangle tends to
0 as as the number of dissected triangles tends to infinity. Thus, it is
good example of the concept of the balance of 0 and
![\\infty](https://s0.wp.com/latex.php?latex=%5Cinfty&bg=ffffff&fg=333333&s=0
"\\infty") conceived by āchārya Bhāskara-II in his account of these
concepts.

![triangle\_centroid\_dissection](https://manasataramgini.files.wordpress.com/2017/08/triangle_centroid_dissection.png?w=640)Figure
7
