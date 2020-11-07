+++
title = "A golden construction"

+++
Anyone with even a small fancy for geometrical matters would have at
some point in their lives played with the golden ratio
(![\\phi=\\dfrac{1+\\sqrt{5}}{2}\\approx
1.61803398875](https://s0.wp.com/latex.php?latex=%5Cphi%3D%5Cdfrac%7B1%2B%5Csqrt%7B5%7D%7D%7B2%7D%5Capprox+1.61803398875&bg=ffffff&fg=333333&s=0
"\\phi=\\dfrac{1+\\sqrt{5}}{2}\\approx 1.61803398875")). Indeed, we too
have had our share of fun and games with the golden ratio. In course of
this we stumbled upon what seemed to us an interesting geometrical
problem although it is likely to be seen as a trivial issue by
mathematicians.
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") was apparently rather important to the yavana-s. Among the
Hindus as we have noted before, it was used in the construction of the
śrīcakra, the primary yantra of the śrīkula tradition.

**Problem and the rules of the game**  
Starting material: A unit square. For convenience we place one vertex at
origin and one side on the x-axis.  
Objective: To construct a recursive golden rectangle and a golden spiral
of any given resolution using this unit square. At the risk of sounding
slow-witted I must emphasize this is not the same as drawing a golden
rectangle and sectioning it.  
It is well-known that the recursive golden rectangle is constructed by
starting with a unit square and repeatedly drawing squares which are
scaled by a factor of ![\\phi-1=\\dfrac{1}{\\phi} \\approx
0.61803398875](https://s0.wp.com/latex.php?latex=%5Cphi-1%3D%5Cdfrac%7B1%7D%7B%5Cphi%7D+%5Capprox+0.61803398875&bg=ffffff&fg=333333&s=0
"\\phi-1=\\dfrac{1}{\\phi} \\approx 0.61803398875") and arranging them
in an inwardly spiralling fashion. The golden spiral is obtained by
drawing a quadrant arc using one vertex of each of these squares as the
center and the side of the square as the radius such that we get a
smooth curve. Figure 1 shows a few iterations of this being done
manually.

![golden\_manual](https://manasataramgini.files.wordpress.com/2016/08/golden_manual.png?w=640)Figure
1

Now doing the above is a tedious manual procedure with its limitations.
So the question was can we do it relatively automatically taking
advantage of a modern construction software like GeoGebra. One could
technically compute the coordinates of each new square and draw them out
with such a program but this is tedious too and needs some rather
unappetizing programming sleights. Instead, we wish to achieve this
construction using only the following three allowed operations, which
can be easily automatically repeated in construction software (e.g.
GeoGebra) to obtain a recursive golden rectangle of spiral of any
desired resolution:  
1\) A single vector which can translate (rectilinear displacement) the
starting unit square by a given distance in a given direction. Figure 2
shows the displacement of our unit square
(![square\_1](https://s0.wp.com/latex.php?latex=square_1&bg=ffffff&fg=333333&s=0
"square_1") by the vector
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u") to
get
![square\_2](https://s0.wp.com/latex.php?latex=square_2&bg=ffffff&fg=333333&s=0
"square_2").  
![u=\\begin{bmatrix} -1.66\\\\ 0.73 \\end{bmatrix}
](https://s0.wp.com/latex.php?latex=u%3D%5Cbegin%7Bbmatrix%7D+-1.66%5C%5C+0.73+%5Cend%7Bbmatrix%7D+&bg=ffffff&fg=333333&s=0
"u=\\begin{bmatrix} -1.66\\\\ 0.73 \\end{bmatrix} ")

![golden\_translation](https://manasataramgini.files.wordpress.com/2016/08/golden_translation.png?w=640)Figure
2

2\) Dilation (scaling) with the origin as the center of dilation. This
operation allows one to scale an object (in our case the unit square) by
any factor such that ratio of the distance of any point on scaled square
from origin to distance of its equivalent point on the the unit square
from origin is equal to the scaling factor. Figure 3 shows such a
dilation operation performed on
![square\_2](https://s0.wp.com/latex.php?latex=square_2&bg=ffffff&fg=333333&s=0
"square_2") by
![scaling\\;factor=\\dfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=scaling%5C%3Bfactor%3D%5Cdfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"scaling\\;factor=\\dfrac{1}{\\phi}") to get
![square\_3](https://s0.wp.com/latex.php?latex=square_3&bg=ffffff&fg=333333&s=0
"square_3").

![golden\_dilation](https://manasataramgini.files.wordpress.com/2016/08/golden_dilation.png?w=640)Figure
3

3\) Rotation of an object about origin by a constant angle in one
direction. Figure 4 shows the rotation of
![square\_3](https://s0.wp.com/latex.php?latex=square_3&bg=ffffff&fg=333333&s=0
"square_3") by
![90^o](https://s0.wp.com/latex.php?latex=90%5Eo&bg=ffffff&fg=333333&s=0
"90^o") to get
![square\_4](https://s0.wp.com/latex.php?latex=square_4&bg=ffffff&fg=333333&s=0
"square_4").

![golden\_rotation](https://manasataramgini.files.wordpress.com/2016/08/golden_rotation.png?w=640)Figure
4

To get a flavor of how this works when done recursively we start with
our unit square
![square\_1](https://s0.wp.com/latex.php?latex=square_1&bg=ffffff&fg=333333&s=0
"square_1"), which is what we need to construct the golden rectangle,
and inscribe a circular quadrant inside it. We then apply following
series of operations recursively on these two object: Translate by
vector ![v](https://s0.wp.com/latex.php?latex=v&bg=ffffff&fg=333333&s=0
"v"), then dilate by a certain scaling factor and then rotate by a given
angle. For obtaining the golden rectangle, one can find the rotation
angle easily. As one can see from the manual construction in Figure 1,
for a recursive rectangle each successive square must be rotated by
![90^o](https://s0.wp.com/latex.php?latex=90%5Eo&bg=ffffff&fg=333333&s=0
"90^o"). The scale-factor is also obvious because we are aiming for a
golden rectangle; the square must be successively scaled by the factor
of ![\\left ( \\dfrac{1}{\\phi}\\right
)^n](https://s0.wp.com/latex.php?latex=%5Cleft+%28+%5Cdfrac%7B1%7D%7B%5Cphi%7D%5Cright+%29%5En&bg=ffffff&fg=333333&s=0
"\\left ( \\dfrac{1}{\\phi}\\right )^n"), where
![n=0,1,2,3\\;...](https://s0.wp.com/latex.php?latex=n%3D0%2C1%2C2%2C3%5C%3B...&bg=ffffff&fg=333333&s=0
"n=0,1,2,3\\;...") for each iteration. But these two are not enough as
can be seen in Figure 5. There we apply the above rotation and dilation
transformations on
![square\_1](https://s0.wp.com/latex.php?latex=square_1&bg=ffffff&fg=333333&s=0
"square_1") with an arbitrary translation vector
![v](https://s0.wp.com/latex.php?latex=v&bg=ffffff&fg=333333&s=0 "v")
thus:  
![Rotate\[Dilate\[Translate\[square\_1, v\],\\;b^n\],
\\dfrac{n\\pi}{2}\],
n=0\\;to\\;10](https://s0.wp.com/latex.php?latex=Rotate%5BDilate%5BTranslate%5Bsquare_1%2C+v%5D%2C%5C%3Bb%5En%5D%2C+%5Cdfrac%7Bn%5Cpi%7D%7B2%7D%5D%2C+n%3D0%5C%3Bto%5C%3B10&bg=ffffff&fg=333333&s=0
"Rotate[Dilate[Translate[square_1, v],\\;b^n], \\dfrac{n\\pi}{2}], n=0\\;to\\;10")  
where the vector is:  
![v=\\begin{bmatrix} -1.23\\\\ 0.42 \\end{bmatrix}
](https://s0.wp.com/latex.php?latex=v%3D%5Cbegin%7Bbmatrix%7D+-1.23%5C%5C+0.42+%5Cend%7Bbmatrix%7D+&bg=ffffff&fg=333333&s=0
"v=\\begin{bmatrix} -1.23\\\\ 0.42 \\end{bmatrix} ")

![golden\_transformation](https://manasataramgini.files.wordpress.com/2016/08/golden_transformation1.png?w=640)Figure
5

We get a spiral arrangement of the squares and the quadrant arcs but
clearly this is not the golden rectangle or spiral. Hence, the big
question is how do we find the right translation vector and how many
such vectors exist which can produce a recursive golden rectangle with
the unit square.

**Determination of translation vector and construction of the desired
golden entities**  
The determination of the translation vectors to produce the golden
rectangles and spirals involves an interesting construction. We are not
going to repeat the well-known constructions of the yavana-s by which
they obtained
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") and
![\\phi-1=\\dfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=%5Cphi-1%3D%5Cdfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"\\phi-1=\\dfrac{1}{\\phi}"). We start with segments of these values
already pre-constructed:  
1\) Let the unit square be ABCD with point A at origin.  
2\) From point A in the direction opposite to side
![\\overline{AB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAB%7D&bg=ffffff&fg=333333&s=0
"\\overline{AB}") along the same straight line mark the point G at
distance
![1-\\dfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=1-%5Cdfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"1-\\dfrac{1}{\\phi}") and point H at distance
![\\dfrac{\\phi}{2}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%5Cphi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{\\phi}{2}").  
3\) From point A in the direction opposite to side
![\\overline{AD}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAD%7D&bg=ffffff&fg=333333&s=0
"\\overline{AD}") along the same straight line mark the point F at
distance
![\\dfrac{2-\\phi}{2}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B2-%5Cphi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{2-\\phi}{2}") and point E at distance
![\\dfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{\\phi}").  
4\) Draw
![\\overleftrightarrow{GF}](https://s0.wp.com/latex.php?latex=%5Coverleftrightarrow%7BGF%7D&bg=ffffff&fg=333333&s=0
"\\overleftrightarrow{GF}"). Drop perpendiculars to
![\\overleftrightarrow{GF}](https://s0.wp.com/latex.php?latex=%5Coverleftrightarrow%7BGF%7D&bg=ffffff&fg=333333&s=0
"\\overleftrightarrow{GF}") from points H and E to meet it at points I
and J.  
5\) One will notice that ![\\overline{IJ}\\cong
\\overline{AB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BIJ%7D%5Ccong+%5Coverline%7BAB%7D&bg=ffffff&fg=333333&s=0
"\\overline{IJ}\\cong \\overline{AB}") i.e. it is congruent to the sides
of the unit square.  
6\) Now use
![\\overline{IJ}](https://s0.wp.com/latex.php?latex=%5Coverline%7BIJ%7D&bg=ffffff&fg=333333&s=0
"\\overline{IJ}") to complete the construction of square IJKL which is
congruent to our unit square ABCD.  
7\) Draw vectors ![u\_1, u\_2, u\_3,
u\_4](https://s0.wp.com/latex.php?latex=u_1%2C+u_2%2C+u_3%2C+u_4&bg=ffffff&fg=333333&s=0
"u_1, u_2, u_3, u_4") that connect point A to points I, J, K and L. Any
of these 4 vectors can serve as translation vectors with the above
dilation and rotation factors to give us 4 golden rectangles from the
unit square ABCD and 4 golden spirals from the 4 quadrant arcs inscribed
in square ABCD (Figure 6 and 7).

![golden\_construction\_1](https://manasataramgini.files.wordpress.com/2016/08/golden_construction_1.png?w=640)Figure
6: single example of golden rectangle/spiral

![golden\_construction\_2](https://manasataramgini.files.wordpress.com/2016/08/golden_construction_2.png?w=640)Figure
7: All four golden rectangles and spirals

This construction reveals some interesting features:  
1\) The angle between the vectors
![u\_1](https://s0.wp.com/latex.php?latex=u_1&bg=ffffff&fg=333333&s=0
"u_1") and
![u\_2](https://s0.wp.com/latex.php?latex=u_2&bg=ffffff&fg=333333&s=0
"u_2") is
![\\dfrac{3\\pi}{4}=135^o](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B3%5Cpi%7D%7B4%7D%3D135%5Eo&bg=ffffff&fg=333333&s=0
"\\dfrac{3\\pi}{4}=135^o") and each vector is separated from the
adjacent one by
![\\dfrac{\\pi}{4}=45^o](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%5Cpi%7D%7B4%7D%3D45%5Eo&bg=ffffff&fg=333333&s=0
"\\dfrac{\\pi}{4}=45^o"). Thus the 4 vectors together form a trisection
of the angle
![\\dfrac{3\\pi}{4}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B3%5Cpi%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{3\\pi}{4}").  
2)As noted above the square IJKL which determines the end points of the
four translation vectors is congruent to the starting unit square but
from the construction we can see that it is rotated with respect to it
by an angle of
![\\theta](https://s0.wp.com/latex.php?latex=%5Ctheta&bg=ffffff&fg=333333&s=0
"\\theta"), where
![\\theta=\\sin^{-1}\\left(\\dfrac{2}{2\\phi-1}\\right)=\\cos^{-1}\\left(\\dfrac{1}{2\\phi-1}\\right)=\\tan^{-1}(2)
\\approx63.43^o](https://s0.wp.com/latex.php?latex=%5Ctheta%3D%5Csin%5E%7B-1%7D%5Cleft%28%5Cdfrac%7B2%7D%7B2%5Cphi-1%7D%5Cright%29%3D%5Ccos%5E%7B-1%7D%5Cleft%28%5Cdfrac%7B1%7D%7B2%5Cphi-1%7D%5Cright%29%3D%5Ctan%5E%7B-1%7D%282%29+%5Capprox63.43%5Eo&bg=ffffff&fg=333333&s=0
"\\theta=\\sin^{-1}\\left(\\dfrac{2}{2\\phi-1}\\right)=\\cos^{-1}\\left(\\dfrac{1}{2\\phi-1}\\right)=\\tan^{-1}(2) \\approx63.43^o"). This
angle is the supplementary angle of the dihedral angle of a
dodecahedron.  
3\) From the construction we can show the shortest of the vectors is:  
![u\_2=\\begin{bmatrix} \\dfrac{2-\\phi}{2\\phi-1}\\\\\[10
pt\]-\\dfrac{2-\\phi}{2\\phi-1}\\phi
\\end{bmatrix}](https://s0.wp.com/latex.php?latex=u_2%3D%5Cbegin%7Bbmatrix%7D+%5Cdfrac%7B2-%5Cphi%7D%7B2%5Cphi-1%7D%5C%5C%5B10+pt%5D-%5Cdfrac%7B2-%5Cphi%7D%7B2%5Cphi-1%7D%5Cphi+%5Cend%7Bbmatrix%7D&bg=ffffff&fg=333333&s=0
"u_2=\\begin{bmatrix} \\dfrac{2-\\phi}{2\\phi-1}\\\\[10 pt]-\\dfrac{2-\\phi}{2\\phi-1}\\phi \\end{bmatrix}")

![|u\_2|=\\dfrac{(2-\\phi)\\sqrt{2+\\phi}}{2\\phi-1}](https://s0.wp.com/latex.php?latex=%7Cu_2%7C%3D%5Cdfrac%7B%282-%5Cphi%29%5Csqrt%7B2%2B%5Cphi%7D%7D%7B2%5Cphi-1%7D&bg=ffffff&fg=333333&s=0
"|u_2|=\\dfrac{(2-\\phi)\\sqrt{2+\\phi}}{2\\phi-1}")  
3\) The six ratios of the magnitudes of the 4 translation vectors can be
expressed as relationships featuring
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") thus:  
![\\dfrac{|u\_3|}{|u\_1|}=\\phi](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_3%7C%7D%7B%7Cu_1%7C%7D%3D%5Cphi&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_3|}{|u_1|}=\\phi")

![\\dfrac{|u\_4|}{|u\_2|}=\\phi^3=2\\phi+1](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_4%7C%7D%7B%7Cu_2%7C%7D%3D%5Cphi%5E3%3D2%5Cphi%2B1&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_4|}{|u_2|}=\\phi^3=2\\phi+1")

![\\dfrac{|u\_4|}{|u\_1|}=1+\\dfrac{1}{\\sqrt\[3\]{\\phi}}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_4%7C%7D%7B%7Cu_1%7C%7D%3D1%2B%5Cdfrac%7B1%7D%7B%5Csqrt%5B3%5D%7B%5Cphi%7D%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_4|}{|u_1|}=1+\\dfrac{1}{\\sqrt[3]{\\phi}}")

![\\dfrac{|u\_3|}{|u\_2|}=2+\\dfrac{2}{\\sqrt\[3\]{\\phi}}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_3%7C%7D%7B%7Cu_2%7C%7D%3D2%2B%5Cdfrac%7B2%7D%7B%5Csqrt%5B3%5D%7B%5Cphi%7D%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_3|}{|u_2|}=2+\\dfrac{2}{\\sqrt[3]{\\phi}}")

![\\dfrac{|u\_1|}{|u\_2|}=\\sqrt{2}\\phi](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_1%7C%7D%7B%7Cu_2%7C%7D%3D%5Csqrt%7B2%7D%5Cphi&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_1|}{|u_2|}=\\sqrt{2}\\phi")

![\\dfrac{|u\_4|}{|u\_3|}=\\dfrac{\\phi}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%7Cu_4%7C%7D%7B%7Cu_3%7C%7D%3D%5Cdfrac%7B%5Cphi%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"\\dfrac{|u_4|}{|u_3|}=\\dfrac{\\phi}{\\sqrt{2}}")
