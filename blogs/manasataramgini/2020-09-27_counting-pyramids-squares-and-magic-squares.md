+++
title = "Counting pyramids, squares and magicxa0squares"

+++
[![pyramidal\_numbers](https://manasataramgini.files.wordpress.com/2020/09/pyramidal_numbers.png?w=475&h=440)](https://manasataramgini.files.wordpress.com/2020/09/pyramidal_numbers.png)

Figure 1. Pyramidal numbers

The following note provides some exceedingly elementary mathematics,
primarily for bālabodhana. Sometime back we heard a talk by a famous
contemporary mathematician (M. Bhargava) in which he described how as a
kid he discovered for himself the formula for pyramidal numbers (i.e.
defined by the number of spheres packed in pyramids with a square base;
Figure 1). It reminded us of a parallel experience in our childhood, and
also of the difference between an ordinary person and a mathematician.
In those long past days, we found ourselves in the company of a clansman
who had a much lower sense of purpose than us in our youth (it seems to
have inverted in adulthood). Hence, he kept himself busy by leafing
through books of “puzzles” or playing video games. He showed us one such
“puzzle” which was puzzling him. It showed something like Figure 1 and
asked the reader to find the total number of balls in the pile if a
base-edge had 15 balls. We asked him why that was a big deal — after
all, it was just a lot of squaring and addition and suggested that we
get started with a paper and pencil. He responded that he too had
realized the same but had divined that what the questioner wanted was a
formula into which we could plug in a base-edge with any number of balls
and get the answer. We tried to figure out that formula but failed;
thus, we sorted with the mere mortals rather than the great
intellectuals.

Nevertheless, our effort was not entirely a waste. In the process of
attempting to crack the formula, we discovered for ourselves an
isomorphism: The count of the balls in the pyramid is the same as the
total number of squares that can be counted in a ![n\\times
n](https://s0.wp.com/latex.php?latex=n%5Ctimes+n&bg=ffffff&fg=333333&s=0&c=20201002 "n\times n")
square grid (Figure 2). In this mapping, the single ball on the top is
equivalent to the biggest or the bounding square. The base layer of the
pyramid corresponds to the individual squares of the grid. All other
layers map onto interstitial squares — in Figure 2 we show how those are
defined by pink shading and cross-hatching of one example of them. In
this mapping, the entire pyramid is mapped into the interior of the
apical ball, which is now represented as a sphere. Thus, the number of
balls packed into a pyramid and the number of squares in a ![n\\times
n](https://s0.wp.com/latex.php?latex=n%5Ctimes+n&bg=ffffff&fg=333333&s=0&c=20201002 "n\times n")
square grid are merely 3D and 2D representations of the same number,
i.e. the sum of squares
![1^2+2^2+3^2...n^2](https://s0.wp.com/latex.php?latex=1%5E2%2B2%5E2%2B3%5E2...n%5E2&bg=ffffff&fg=333333&s=0&c=20201002 "1^2+2^2+3^2...n^2")

[![pyrFig2](https://manasataramgini.files.wordpress.com/2020/09/pyrfig2.png?w=640)](https://manasataramgini.files.wordpress.com/2020/09/pyrfig2.png)Figure
2. The total number of squares formed by contact in a square grid.

We got our answer to this a couple of years later when we started
reading the Āryabhaṭīyam of Āryabhaṭa, one of the greatest Hindu
scientists of all times. He says:

saika-sa-gaccha-padānām kramāt-tri-saṃvargitasya ṣaṣṭho .aṃśaḥ \|  
varga-citi-ghanaḥ sa bhavet citi-vargo ghana-citi-ghanaś ca \|\| AB 2.22

The sixth part of the product of the three quantities, viz. the number
of terms, the number of terms plus one, and twice the number of terms
plus one is the sum of the squares. The square of the sum of the
(original) series is the sum of the cubes. \[vide KS Shukla\].

In modern language, we would render the first formula, which concerns
us, as:

![\\displaystyle \\sum\_{j=1}^{n} j^2 =
\\dfrac{n(n+1)(2n+1)}{6}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bj%3D1%7D%5E%7Bn%7D+j%5E2+%3D+%5Cdfrac%7Bn%28n%2B1%29%282n%2B1%29%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\displaystyle \sum_{j=1}^{n} j^2 = \dfrac{n(n+1)(2n+1)}{6}")

This is the formula for the figurate numbers known as the pyramidal
numbers as they define square pyramids (Figure 1). A pratyakṣa geometric
proof for this offered by the great Gārgya Nīlakaṇṭha somayājin (Figure
3). While this proof appears in Nīlakaṇṭha’s bhāṣya on the Āryabhaṭīyam,
it is likely that some such proof was already known to Āryabhaṭa.

[![pyramidal\_numbers\_nIlakaNTha](https://manasataramgini.files.wordpress.com/2020/09/pyramidal_numbers_nilakantha.png?w=569&h=429)](https://manasataramgini.files.wordpress.com/2020/09/pyramidal_numbers_nilakantha.png)

Figure 3. The formula for pyramidal numbers or the sum of squares of
integers.

For bālabodhana:

1\) He first asks you to lay a rectangular floor of
![(2n+1)(n+1)](https://s0.wp.com/latex.php?latex=%282n%2B1%29%28n%2B1%29&bg=ffffff&fg=333333&s=0&c=20201002 "(2n+1)(n+1)")
cubic units.

2\) Then you erect the walls on 3 of sides of the floor of height
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n")
cubic units, namely the 2 sides of length
![n+1](https://s0.wp.com/latex.php?latex=n%2B1&bg=ffffff&fg=333333&s=0&c=20201002 "n+1")
and 1 side of length
![2n+1](https://s0.wp.com/latex.php?latex=2n%2B1&bg=ffffff&fg=333333&s=0&c=20201002 "2n+1").

3\) The shell thus constructed has:

![(2n+1)(n+1)=2n^2+3n+1
\\rightarrow](https://s0.wp.com/latex.php?latex=%282n%2B1%29%28n%2B1%29%3D2n%5E2%2B3n%2B1+%5Crightarrow&bg=ffffff&fg=333333&s=0&c=20201002 "(2n+1)(n+1)=2n^2+3n+1 \rightarrow")
floor

![(2n+1)n-(2n+1)=2n^2-n-1
\\rightarrow](https://s0.wp.com/latex.php?latex=%282n%2B1%29n-%282n%2B1%29%3D2n%5E2-n-1+%5Crightarrow&bg=ffffff&fg=333333&s=0&c=20201002 "(2n+1)n-(2n+1)=2n^2-n-1 \rightarrow")
backwall

![2(n^2-n)=2n^2-2n
\\rightarrow](https://s0.wp.com/latex.php?latex=2%28n%5E2-n%29%3D2n%5E2-2n+%5Crightarrow&bg=ffffff&fg=333333&s=0&c=20201002 "2(n^2-n)=2n^2-2n \rightarrow")
sidewalls

i.e. a total of
![6n^2](https://s0.wp.com/latex.php?latex=6n%5E2&bg=ffffff&fg=333333&s=0&c=20201002 "6n^2")
cubic units or bricks.

From the figure, it is apparent that the shell can accommodate another
shell based on
![(n-1)](https://s0.wp.com/latex.php?latex=%28n-1%29&bg=ffffff&fg=333333&s=0&c=20201002 "(n-1)"),
which in turn can accommodate one based on
![(n-2)](https://s0.wp.com/latex.php?latex=%28n-2%29&bg=ffffff&fg=333333&s=0&c=20201002 "(n-2)")
units and so on till 1. Thus, we can fill a cuboid of volume,

![\\displaystyle n(n+1)(2n+1)= 6\\sum\_{j=1}^{n}
j^2](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+n%28n%2B1%29%282n%2B1%29%3D+6%5Csum_%7Bj%3D1%7D%5E%7Bn%7D+j%5E2&bg=ffffff&fg=333333&s=0&c=20201002 "\displaystyle n(n+1)(2n+1)= 6\sum_{j=1}^{n} j^2"),

This yields Āryabhaṭa’s formula from which we can write the sequence of
pyramidal numbers
![Py\_n](https://s0.wp.com/latex.php?latex=Py_n&bg=ffffff&fg=333333&s=0&c=20201002 "Py_n")
as:

**1, 5, 14, 30, 55, 91, 140, 204, 285, 385, 506, 650, 819, 1015, 1240…**

We had earlier seen Āryabhaṭa and Nīlakaṇṭha’s work on triangular
numbers (sum of integers) and tetrahedral numbers (the sum of the sum of
integers) \[[footnote
1](https://manasataramgini.wordpress.com/2017/10/23/triangles-hexes-and-cubes/)\].
From that, we know the formula for tetrahedral numbers to be:

![Te\_n=\\dfrac{n(n+1)(n+2)}{6}](https://s0.wp.com/latex.php?latex=Te_n%3D%5Cdfrac%7Bn%28n%2B1%29%28n%2B2%29%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002 "Te_n=\dfrac{n(n+1)(n+2)}{6}")

**1, 4, 10, 20, 35, 56, 84, 120, 165, 220, 286, 364, 455, 560, 680…**

We see that
![Py\_n=Te\_n+Te\_{n-1}](https://s0.wp.com/latex.php?latex=Py_n%3DTe_n%2BTe_%7Bn-1%7D&bg=ffffff&fg=333333&s=0&c=20201002 "Py_n=Te_n+Te_{n-1}").
This can be easily proven by seeing that merging two successive
tetrahedral piles of spheres we get a square pyramid pile of balls (see
figure in \[[footnote
1](https://manasataramgini.wordpress.com/2017/10/23/triangles-hexes-and-cubes/)\]).
Shortly thereafter, this led us to finding for ourselves the space
occupancy or density constant for atomic packing. Consider uniformly
sized spherical atoms to be packed in a pyramid, like in Figure 1. Then
the question is what fraction of the volume of the pyramid will be
occupied by matter. We know that the volume of the pyramid whose side
length is
![l](https://s0.wp.com/latex.php?latex=l&bg=ffffff&fg=333333&s=0&c=20201002 "l")
is ![V =
\\tfrac{l^2a}{3}](https://s0.wp.com/latex.php?latex=V+%3D+%5Ctfrac%7Bl%5E2a%7D%7B3%7D&bg=ffffff&fg=333333&s=0&c=20201002 "V = \tfrac{l^2a}{3}"),
where
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0&c=20201002 "a")
is its height. From the bhujā-koṭi-karṇa-nyāya we have its height as
![\\tfrac{l}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bl%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\tfrac{l}{\sqrt{2}}").
Hence,

![V =
\\tfrac{l^3}{3\\sqrt{2}}](https://s0.wp.com/latex.php?latex=V+%3D+%5Ctfrac%7Bl%5E3%7D%7B3%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0&c=20201002 "V = \tfrac{l^3}{3\sqrt{2}}")

Now the volume occupied by the atoms from Āryabhaṭa’s series sum is:

![V\_a=\\dfrac{2n^3+3n^2+n}{6}\\cdot \\dfrac{4\\pi
r^3}{3}](https://s0.wp.com/latex.php?latex=V_a%3D%5Cdfrac%7B2n%5E3%2B3n%5E2%2Bn%7D%7B6%7D%5Ccdot+%5Cdfrac%7B4%5Cpi+r%5E3%7D%7B3%7D&bg=ffffff&fg=333333&s=0&c=20201002 "V_a=\dfrac{2n^3+3n^2+n}{6}\cdot \dfrac{4\pi r^3}{3}")

The radius of each atom is
![r=\\tfrac{l}{2n}](https://s0.wp.com/latex.php?latex=r%3D%5Ctfrac%7Bl%7D%7B2n%7D&bg=ffffff&fg=333333&s=0&c=20201002 "r=\tfrac{l}{2n}").
Plugging this in the above we get:

![V\_a=\\dfrac{2n^3+3n^2+n}{6}\\cdot \\dfrac{4\\pi
l^3}{24n^3}](https://s0.wp.com/latex.php?latex=V_a%3D%5Cdfrac%7B2n%5E3%2B3n%5E2%2Bn%7D%7B6%7D%5Ccdot+%5Cdfrac%7B4%5Cpi+l%5E3%7D%7B24n%5E3%7D&bg=ffffff&fg=333333&s=0&c=20201002 "V_a=\dfrac{2n^3+3n^2+n}{6}\cdot \dfrac{4\pi l^3}{24n^3}")

Simplifying we get:

![V\_a = \\left( \\dfrac{1}{18}+
\\dfrac{1}{12n}+\\dfrac{1}{36n^2}\\right)\\pi
l^3](https://s0.wp.com/latex.php?latex=V_a+%3D+%5Cleft%28+%5Cdfrac%7B1%7D%7B18%7D%2B+%5Cdfrac%7B1%7D%7B12n%7D%2B%5Cdfrac%7B1%7D%7B36n%5E2%7D%5Cright%29%5Cpi+l%5E3&bg=ffffff&fg=333333&s=0&c=20201002 "V_a = \left( \dfrac{1}{18}+ \dfrac{1}{12n}+\dfrac{1}{36n^2}\right)\pi l^3")

Since the atoms have infinitesimal radius we can take the limit ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0&c=20201002 "n \to \infty")
and we are left with:

![\\displaystyle \\lim\_{n \\to \\infty} V\_a =\\dfrac{\\pi
l^3}{18}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+V_a+%3D%5Cdfrac%7B%5Cpi+l%5E3%7D%7B18%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\displaystyle \lim_{n \to \infty} V_a =\dfrac{\pi l^3}{18}")

Thus, we get,

![\\dfrac{V\_a}{V}=\\dfrac{\\pi}{3\\sqrt{2}} \\approx
0.7404805](https://s0.wp.com/latex.php?latex=%5Cdfrac%7BV_a%7D%7BV%7D%3D%5Cdfrac%7B%5Cpi%7D%7B3%5Csqrt%7B2%7D%7D+%5Capprox+0.7404805&bg=ffffff&fg=333333&s=0&c=20201002 "\dfrac{V_a}{V}=\dfrac{\pi}{3\sqrt{2}} \approx 0.7404805")

Hence, little under
![\\tfrac{3}{4}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B3%7D%7B4%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\tfrac{3}{4}")
of the space occupied by solid matter is filled by uniform spherical
atoms. This meditation on atomic packing led us to another way of
counting squares. Imagine circles packed as in Figure 4. The circles can
then be used to define squares. The most obvious set of squares is
equivalent to the ![n \\times
n](https://s0.wp.com/latex.php?latex=n+%5Ctimes+n&bg=ffffff&fg=333333&s=0&c=20201002 "n \times n")
grid that we considered above. Here the smallest squares of the grid are
equivalent to those circumscribing each circle, or alternative inscribed
within it as shown in the example with just 1 circle. We can also join
the centers of the circles and get bigger squares. If we instead
circumscribe the circles we get an equivalent number corresponding to
the bounding and interstitial squares of the ![n \\times
n](https://s0.wp.com/latex.php?latex=n+%5Ctimes+n&bg=ffffff&fg=333333&s=0&c=20201002 "n \times n")
grid. However, we notice (as shown in the ![3 \\times
3](https://s0.wp.com/latex.php?latex=3+%5Ctimes+3&bg=ffffff&fg=333333&s=0&c=20201002 "3 \times 3")
example) that we can also get additional squares by joining the centers
cross-ways. So the question was what is the total number of squares if
we count in this manner?

[![pyrFig4](https://manasataramgini.files.wordpress.com/2020/09/pyrfig4.png?w=640)](https://manasataramgini.files.wordpress.com/2020/09/pyrfig4.png)Figure
4. Squares defined by packed circles.

We noticed that the first two cases will have the same number of squares
as the pyramidal number case. However, from the ![3 \\times
3](https://s0.wp.com/latex.php?latex=3+%5Ctimes+3&bg=ffffff&fg=333333&s=0&c=20201002 "3 \times 3")
case onward we will get additional squares. We noticed that for ![3
\\times
3](https://s0.wp.com/latex.php?latex=3+%5Ctimes+3&bg=ffffff&fg=333333&s=0&c=20201002 "3 \times 3")
we get one additional square beyond the pyramidal numbers; for the ![4
\\times
4](https://s0.wp.com/latex.php?latex=4+%5Ctimes+4&bg=ffffff&fg=333333&s=0&c=20201002 "4 \times 4")
case we get 4 additional squares. It can be seen that the number of
additional squares essentially define tetrahedral numbers; thus, we can
write the sequence
![S\_n](https://s0.wp.com/latex.php?latex=S_n&bg=ffffff&fg=333333&s=0&c=20201002 "S_n")
of this mode of counting as below:

![S\_1=Py\_1,
S\_2=Py\_2](https://s0.wp.com/latex.php?latex=S_1%3DPy_1%2C+S_2%3DPy_2&bg=ffffff&fg=333333&s=0&c=20201002 "S_1=Py_1, S_2=Py_2"),
when ![n\\ge 3,
S\_n=Py\_n+Te\_{n-2}](https://s0.wp.com/latex.php?latex=n%5Cge+3%2C+S_n%3DPy_n%2BTe_%7Bn-2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "n\ge 3, S_n=Py_n+Te_{n-2}").

![\\therefore S\_n=\\dfrac{n(n+1)(2n+1)}{6} + \\dfrac{n(n-1)(n-2)}{6}=
\\dfrac{n^3+n}{2}](https://s0.wp.com/latex.php?latex=%5Ctherefore+S_n%3D%5Cdfrac%7Bn%28n%2B1%29%282n%2B1%29%7D%7B6%7D+%2B+%5Cdfrac%7Bn%28n-1%29%28n-2%29%7D%7B6%7D%3D+%5Cdfrac%7Bn%5E3%2Bn%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\therefore S_n=\dfrac{n(n+1)(2n+1)}{6} + \dfrac{n(n-1)(n-2)}{6}= \dfrac{n^3+n}{2}")

![S\_n:](https://s0.wp.com/latex.php?latex=S_n%3A&bg=ffffff&fg=333333&s=0&c=20201002 "S_n:")
**1, 5, 15, 34, 65, 111, 175, 260, 369, 505, 671, 870, 1105, 1379,
1695…**

We can also derive this sequence in another way. Write the natural
numbers thus:

**(1); (2,3); (4,5,6); (7,8,9,10); (11,12,13,14,15);…**

If we then take the sum of each group in brackets, which has ![1, 2, 3
...
n](https://s0.wp.com/latex.php?latex=1%2C+2%2C+3+...+n&bg=ffffff&fg=333333&s=0&c=20201002 "1, 2, 3 ... n")
elements, we get
![S\_n](https://s0.wp.com/latex.php?latex=S_n&bg=ffffff&fg=333333&s=0&c=20201002 "S_n").

We observe that from the 3rd term onward this sequence remarkably yields
the magic constants
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0&c=20201002 "M")
(row, column and diagonal sums or the largest eigenvalue of the matrix
defined by the magic square) for the minimal magic squares (bhadra-s)
i.e. magic squares made of numbers from
![1:n^2](https://s0.wp.com/latex.php?latex=1%3An%5E2&bg=ffffff&fg=333333&s=0&c=20201002 "1:n^2")
where
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n")
is the order or the side length of it \[[footnote
2](https://manasataramgini.wordpress.com/2017/05/14/the-magic-of-the-deva-ogdoad/)\].
We also realized then that this was the basis of the “magic choice”
property which we used in a schoolyard trick. That is illustrated in
Figure 5.

[![pyrFig5](https://manasataramgini.files.wordpress.com/2020/09/pyrfig5.png?w=528&h=522)](https://manasataramgini.files.wordpress.com/2020/09/pyrfig5.png)

Figure 5. Magic choice.

Write a ![n \\times
n](https://s0.wp.com/latex.php?latex=n+%5Ctimes+n&bg=ffffff&fg=333333&s=0&c=20201002 "n \times n")
square of all integers from
![1...n^2](https://s0.wp.com/latex.php?latex=1...n%5E2&bg=ffffff&fg=333333&s=0&c=20201002 "1...n^2").
Ask a person to silently randomly choose
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n")
numbers such that each row and column of the square is represented once
(orange circles in Figure 5) and sum them up. Then, without him
revealing anything you tell him the sum. The sum will be
![S\_n](https://s0.wp.com/latex.php?latex=S_n&bg=ffffff&fg=333333&s=0&c=20201002 "S_n").
This is the weaker condition which can be converted to a magic square
for all ![n\\ge
3](https://s0.wp.com/latex.php?latex=n%5Cge+3&bg=ffffff&fg=333333&s=0&c=20201002 "n\ge 3").

Finally, we will consider another sequence that can be derived like the
above. It is the simple sum of pyramidal and tetrahedral numbers without
shifting the latter by 2 terms as we did above to get
![S\_n](https://s0.wp.com/latex.php?latex=S_n&bg=ffffff&fg=333333&s=0&c=20201002 "S_n").
Thus, this new sequence is:

![I\_n = \\dfrac{n(n+1)(2n+1)}{6} +\\dfrac{n(n+1)(n+2)}{6}
=\\dfrac{n(n+1)^2}{2}](https://s0.wp.com/latex.php?latex=I_n+%3D+%5Cdfrac%7Bn%28n%2B1%29%282n%2B1%29%7D%7B6%7D+%2B%5Cdfrac%7Bn%28n%2B1%29%28n%2B2%29%7D%7B6%7D+%3D%5Cdfrac%7Bn%28n%2B1%29%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002 "I_n = \dfrac{n(n+1)(2n+1)}{6} +\dfrac{n(n+1)(n+2)}{6} =\dfrac{n(n+1)^2}{2}")

![I\_n:](https://s0.wp.com/latex.php?latex=I_n%3A&bg=ffffff&fg=333333&s=0&c=20201002 "I_n:")
**2, 9, 24, 50, 90, 147, 224, 324, 450, 605, 792, 1014, 1274, 1575,
1920, 2312, 2754, 3249, 3800, 4410…**

We observe that this sequence defines the sum of the integers in the
interstices between triangular numbers (Figure 6). Further, it also has
a geometric interpretation in the form of the area of the triangular
number trapezium (Figure 6). Successive, triangular number trapezia are
defined by the following 4 points: ![(0,T\_n); (T\_n, T\_{n+1});
(T\_{n+1},T\_{n+2}); (T\_n+1,
0)](https://s0.wp.com/latex.php?latex=%280%2CT_n%29%3B+%28T_n%2C+T_%7Bn%2B1%7D%29%3B+%28T_%7Bn%2B1%7D%2CT_%7Bn%2B2%7D%29%3B+%28T_n%2B1%2C+0%29&bg=ffffff&fg=333333&s=0&c=20201002 "(0,T_n); (T_n, T_{n+1}); (T_{n+1},T_{n+2}); (T_n+1, 0)").
These trapezia always have an integral area equal to
![I\_n](https://s0.wp.com/latex.php?latex=I_n&bg=ffffff&fg=333333&s=0&c=20201002 "I_n")
starting from 9.

![pyrFig6A](https://manasataramgini.files.wordpress.com/2020/09/pyrfig6a.png?w=562&h=343)

![pyrFig6B](https://manasataramgini.files.wordpress.com/2020/09/pyrfig6b.png?w=461&h=634)Figure
6. Triangular number interstitial sums and integer area trapezia.

------------------------------------------------------------------------

Footnote 1:
<https://manasataramgini.wordpress.com/2017/10/23/triangles-hexes-and-cubes/>  
Footnote 2:
<https://manasataramgini.wordpress.com/2017/05/14/the-magic-of-the-deva-ogdoad/>
