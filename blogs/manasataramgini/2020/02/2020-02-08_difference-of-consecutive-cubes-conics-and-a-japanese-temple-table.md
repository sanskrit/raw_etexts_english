+++
title = "Difference of consecutive cubes, conics and a Japanese temple tablet"

+++
**Introduction**  
In our part of the world, someone with even a nominal knowledge of
mathematics might be aware of the taxicab number made famous by the
conversation of Ramanujan and Hardy: the smallest number that can be
expressed as the sum of two distinct pairs positive cubes: ![1729=1^3 +
12^3 = 9^3 +
10^3](https://s0.wp.com/latex.php?latex=1729%3D1%5E3+%2B+12%5E3+%3D+9%5E3+%2B+10%5E3&bg=ffffff&fg=333333&s=0
"1729=1^3 + 12^3 = 9^3 + 10^3"). This number is just one of a family of
such taxicab numbers with deep connections to other objects in the
mathematical world that were discovered by Ramanujan long before anyone
knew of their significance. There are several other interesting
questions, which, in a similar vein, relate to the sum and difference of
cubes. From Fermat’s last theorem we know that the indeterminate
equation
![x^3+y^3=z^3](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3Dz%5E3&bg=ffffff&fg=333333&s=0
"x^3+y^3=z^3") cannot have any non-trivial integer solutions
(non-trivial being where none of the solutions are 0). However, this
still leaves open other possibilities with sums of 3 cubes and
differences of the cubes and the like. For example, one popular and
widely investigated one asks which integers can be expressed as a sum of
any three cubes. When we learned that Fermat’s last theorem precludes
integer solutions for
![x^3+y^3=z^3](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3Dz%5E3&bg=ffffff&fg=333333&s=0
"x^3+y^3=z^3") in our early youth, we wondered if there are non-trivial
positive integer solutions indeterminate equation:
![x^3+y^3+z^3=w^3](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%2Bz%5E3%3Dw%5E3&bg=ffffff&fg=333333&s=0
"x^3+y^3+z^3=w^3"). Soon we became interested and investigated one
specific version of it of the form:

![x^3+y^3=w^3-z^3](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3Dw%5E3-z%5E3&bg=ffffff&fg=333333&s=0
"x^3+y^3=w^3-z^3"), where
![w=z+1](https://s0.wp.com/latex.php?latex=w%3Dz%2B1&bg=ffffff&fg=333333&s=0
"w=z+1"); thus, we have ![x^3+y^3=3z^2+3z+1 \\;\\;\\; (\\S
1)](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3D3z%5E2%2B3z%2B1+%5C%3B%5C%3B%5C%3B+%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"x^3+y^3=3z^2+3z+1 \\;\\;\\; (\\S 1)")

This led us to discovering and proving for ourselves a simple arithmetic
theorem concerning such cubes. Later, we read to our amazement that a
related problem had been considered on a Japanese temple tablet in a
beautiful “mystical”-sounding verse and solved in a commentary on it.
This inspired us to look at the problem again and we discovered further
interesting links between conics and these cubes. We detail these
explorations and the Japanese temple tablet below.

**The difference of consecutive cubes and an arithmetic theorem**  
We first asked when does the difference of consecutive cubes result in a
sum of two cubes. This idea came to us as a parallel to the
bhujā-koṭi-karṇa triples. While we have 4 cubes in ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"), given that two are consecutive, we only have a triple of
distinct positive integers ![x, y,
z](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z&bg=ffffff&fg=333333&s=0
"x, y, z") bearing the relationship:

![z = \\dfrac{\\sqrt{12x^3 + 12y^3 - 3} -3}{6} \\; \\; \\; (\\S
2)](https://s0.wp.com/latex.php?latex=z+%3D+%5Cdfrac%7B%5Csqrt%7B12x%5E3+%2B+12y%5E3+-+3%7D+-3%7D%7B6%7D+%5C%3B+%5C%3B+%5C%3B+%28%5CS+2%29&bg=ffffff&fg=333333&s=0
"z = \\dfrac{\\sqrt{12x^3 + 12y^3 - 3} -3}{6} \\; \\; \\; (\\S 2)")

Thus, we have to search for the all the cases where ![(\\S
2)](https://s0.wp.com/latex.php?latex=%28%5CS+2%29&bg=ffffff&fg=333333&s=0
"(\\S 2)") evaluates to an integer given dyads of positive integers ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y"). If we order the resultant triples such that ![x \< y \<
z](https://s0.wp.com/latex.php?latex=x+%3C+y+%3C+z&bg=ffffff&fg=333333&s=0
"x \< y \< z") we get a unique set of triples, e.g. 1, 6, 8:
![1^3+6^3=9^3-8^3](https://s0.wp.com/latex.php?latex=1%5E3%2B6%5E3%3D9%5E3-8%5E3&bg=ffffff&fg=333333&s=0
"1^3+6^3=9^3-8^3"). Figure 1 shows a plot of ![x, y,
z](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z&bg=ffffff&fg=333333&s=0
"x, y, z") for all ![x,
y\<20000](https://s0.wp.com/latex.php?latex=x%2C+y%3C20000&bg=ffffff&fg=333333&s=0
"x, y\<20000"), a total of 1173 triples.

[![cube.diff3D\_fig1](https://manasataramgini.files.wordpress.com/2020/02/cube.diff3d_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2020/02/cube.diff3d_fig1.png)Figure
1

The plot initially reminds one of a first time observer of the sky with
a great mass of stellar points with some vague patterns among them.
Given that
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") is
dependent on ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") and the points lie on a single curved surface in 3D, we can
reduce dimensions for simplicity and plot just ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") (Figure 2).

[![cube.diffsolns\_fig2](https://manasataramgini.files.wordpress.com/2020/02/cube.diffsolns_fig2.png?w=640)](https://manasataramgini.files.wordpress.com/2020/02/cube.diffsolns_fig2.png)Figure
2.

As we have ordered our triples ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") all points obviously lie above the
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") line. We then notice the first clear pattern. There are set of
regularly arranged points (in red in Figure 2) that mark the left margin
of the plot. These points lead us to the following theorem:

**The cube of every positive integer is equal to the difference of the
cubes of two consecutive positive integers minus the cube a third
positive integer.**

To prove this let us consider those regularly arranged points. The first
few of them are tabulated below:

| x |   y |
| -: | --: |
| 1 |   6 |
| 2 |  17 |
| 3 |  34 |
| 4 |  57 |
| 5 |  86 |
| 6 | 121 |

We observe that the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
values of these points include each positive integer in order. The
corresponding
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0 "y")
grows rapidly and follows a peculiar pattern. This pattern is
represented by the numbers lying on the 5th spoke hexagonal spiral
(Figure 3) where 6 spokes separated by the rotation angle of
![\\tfrac{\\pi}{3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{3}") radians pass through the origin.

[![cube.diffspiral\_fig3](https://manasataramgini.files.wordpress.com/2020/02/cube.diffspiral_fig3.png?w=619&h=619)](https://manasataramgini.files.wordpress.com/2020/02/cube.diffspiral_fig3.png)

Figure 3.

The numbers lying on the 5th spoke of this spiral can be represented by
the formula:
![3n^2+2n+1](https://s0.wp.com/latex.php?latex=3n%5E2%2B2n%2B1&bg=ffffff&fg=333333&s=0
"3n^2+2n+1"). Thus, we have ![x=1, 2,
3...n](https://s0.wp.com/latex.php?latex=x%3D1%2C+2%2C+3...n&bg=ffffff&fg=333333&s=0
"x=1, 2, 3...n") and the corresponding
![y=3n^2+2n+1](https://s0.wp.com/latex.php?latex=y%3D3n%5E2%2B2n%2B1&bg=ffffff&fg=333333&s=0
"y=3n^2+2n+1"). Hence,

![x^3+y^3=n^3+(3n^2+2n+1)^3= 3(3n^3 + 3n^2 + 2n)^2 + 3 (3n^3 + 3n^2 +
2n) + 1 \\;\\;\\; (\\S
3)](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3Dn%5E3%2B%283n%5E2%2B2n%2B1%29%5E3%3D+3%283n%5E3+%2B+3n%5E2+%2B+2n%29%5E2+%2B+3+%283n%5E3+%2B+3n%5E2+%2B+2n%29+%2B+1+%5C%3B%5C%3B%5C%3B+%28%5CS+3%29&bg=ffffff&fg=333333&s=0
"x^3+y^3=n^3+(3n^2+2n+1)^3= 3(3n^3 + 3n^2 + 2n)^2 + 3 (3n^3 + 3n^2 + 2n) + 1 \\;\\;\\; (\\S 3)")

If we write ![z=3n^3 + 3n^2 +
2n](https://s0.wp.com/latex.php?latex=z%3D3n%5E3+%2B+3n%5E2+%2B+2n&bg=ffffff&fg=333333&s=0
"z=3n^3 + 3n^2 + 2n"), the right hand side of ![(\\S
3)](https://s0.wp.com/latex.php?latex=%28%5CS+3%29&bg=ffffff&fg=333333&s=0
"(\\S 3)") becomes
![(z+1)^3-z^3](https://s0.wp.com/latex.php?latex=%28z%2B1%29%5E3-z%5E3&bg=ffffff&fg=333333&s=0
"(z+1)^3-z^3")

![\\therefore
x^3=(z+1)^3-z^3-y^3](https://s0.wp.com/latex.php?latex=%5Ctherefore+x%5E3%3D%28z%2B1%29%5E3-z%5E3-y%5E3&bg=ffffff&fg=333333&s=0
"\\therefore x^3=(z+1)^3-z^3-y^3"), where ![x=n;\\; y=3n^2+2n+1;\\;
z=3n^3 + 3n^2 + 2n \\;\\;\\;
\_{...\\blacksquare}](https://s0.wp.com/latex.php?latex=x%3Dn%3B%5C%3B+y%3D3n%5E2%2B2n%2B1%3B%5C%3B+z%3D3n%5E3+%2B+3n%5E2+%2B+2n+%5C%3B%5C%3B%5C%3B+_%7B...%5Cblacksquare%7D&bg=ffffff&fg=333333&s=0
"x=n;\\; y=3n^2+2n+1;\\; z=3n^3 + 3n^2 + 2n \\;\\;\\; _{...\\blacksquare}")

Thus, this theorem illustrates one deep connection between the cubes of
numbers the hexagonal number spiral.

**The Japanese temple tablet**  
The Samurai intellectual Shiraishi Chochu recorded a problem inscribed
in tablet hung at a temple in the 1800s by the poorly known
mathematician Gokai Ampon:

*“There are three integral numbers, heaven, earth, and man, which being
cubed and added together give a result of which the cube root has no
decimal part. Required to find the numbers.”* – translation from Smith
and Mikami

In essence, Gokai Ampon wants us to find integer solutions to
indeterminate equation
![x^3+y^3+z^3=w^3](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%2Bz%5E3%3Dw%5E3&bg=ffffff&fg=333333&s=0
"x^3+y^3+z^3=w^3"), which is the same question that had originally
prompted our quest. His solutions recorded by Shiraishi Chochu are a
particular class of solutions to
![x^3+y^3=3z^2+3z+1](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3D3z%5E2%2B3z%2B1&bg=ffffff&fg=333333&s=0
"x^3+y^3=3z^2+3z+1"), i.e. the sum of the cubes of two positive integer
being the difference of the cubes of consecutive positive integers.

If we look at Figure 2, we find that among the mass of points with
apparently no discernible order there are a group of regularly arranged
points coming in pairs with the same
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
value and lying on a slim parabola (colored purple). It was this group
of points that caught Gokai Ampon’s attention. The first few of the
pairs are listed below:

|   x |  y₁ |  y₂ |
| --: | --: | --: |
|   3 |   4 |  10 |
|  12 |  19 |  31 |
|  27 |  46 |  64 |
|  48 |  85 | 109 |
|  75 | 136 | 166 |
| 108 | 199 | 235 |

We observe that for these points
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
takes the form ![3n^2; \\; n=1, 2,
3...](https://s0.wp.com/latex.php?latex=3n%5E2%3B+%5C%3B+n%3D1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0
"3n^2; \\; n=1, 2, 3..."). For
![y\_1](https://s0.wp.com/latex.php?latex=y_1&bg=ffffff&fg=333333&s=0
"y_1") we get a fit with ![6n^2 -3n
+1](https://s0.wp.com/latex.php?latex=6n%5E2+-3n+%2B1&bg=ffffff&fg=333333&s=0
"6n^2 -3n +1") and for
![y\_2](https://s0.wp.com/latex.php?latex=y_2&bg=ffffff&fg=333333&s=0
"y_2") with ![6n^2 +3n
+1](https://s0.wp.com/latex.php?latex=6n%5E2+%2B3n+%2B1&bg=ffffff&fg=333333&s=0
"6n^2 +3n +1"). Thus, with
![y\_1](https://s0.wp.com/latex.php?latex=y_1&bg=ffffff&fg=333333&s=0
"y_1") we have:

![x^3+y\_1^3=(3n^2)^3+(6n^2 -3n +1)^3 = 3 \\cdot 3^2(2 n^2-3 n^3 - n)^2
+ 3 \\cdot 3 (2 n^2-3 n^3 - n) + 1 \\;\\;\\; (\\S
4)](https://s0.wp.com/latex.php?latex=x%5E3%2By_1%5E3%3D%283n%5E2%29%5E3%2B%286n%5E2+-3n+%2B1%29%5E3+%3D+3+%5Ccdot+3%5E2%282+n%5E2-3+n%5E3+-+n%29%5E2+%2B+3+%5Ccdot+3+%282+n%5E2-3+n%5E3+-+n%29+%2B+1+%5C%3B%5C%3B%5C%3B+%28%5CS+4%29&bg=ffffff&fg=333333&s=0
"x^3+y_1^3=(3n^2)^3+(6n^2 -3n +1)^3 = 3 \\cdot 3^2(2 n^2-3 n^3 - n)^2 + 3 \\cdot 3 (2 n^2-3 n^3 - n) + 1 \\;\\;\\; (\\S 4)")

By writing ![z\_1=3(2 n^2-3 n^3 -
n)](https://s0.wp.com/latex.php?latex=z_1%3D3%282+n%5E2-3+n%5E3+-+n%29&bg=ffffff&fg=333333&s=0
"z_1=3(2 n^2-3 n^3 - n)") and plugging it in ![(\\S
4)](https://s0.wp.com/latex.php?latex=%28%5CS+4%29&bg=ffffff&fg=333333&s=0
"(\\S 4)") we get ![x^3+y\_1^3+z\_1^3=
(z\_1+1)^3](https://s0.wp.com/latex.php?latex=x%5E3%2By_1%5E3%2Bz_1%5E3%3D+%28z_1%2B1%29%5E3&bg=ffffff&fg=333333&s=0
"x^3+y_1^3+z_1^3= (z_1+1)^3"), which is a family of valid solutions to
the Japanese problem. Given that we are only considering positive
integers, the final parameterization will be ![z\_1=3(3 n^3- 2 n^2+
n)-1](https://s0.wp.com/latex.php?latex=z_1%3D3%283+n%5E3-+2+n%5E2%2B+n%29-1&bg=ffffff&fg=333333&s=0
"z_1=3(3 n^3- 2 n^2+ n)-1"). Similarly, with
![y\_2](https://s0.wp.com/latex.php?latex=y_2&bg=ffffff&fg=333333&s=0
"y_2") we get:

![x^3+y\_2^3=(3n^2)^3+(6n^2 +3n +1)^3 = 3 \\cdot 3^2 (3 n^3 + 2 n^2 +
n)^2 + 3 \\cdot 3 (3 n^3 + 2 n^2 + n) + 1 \\;\\;\\; (\\S
5)](https://s0.wp.com/latex.php?latex=x%5E3%2By_2%5E3%3D%283n%5E2%29%5E3%2B%286n%5E2+%2B3n+%2B1%29%5E3+%3D+3+%5Ccdot+3%5E2+%283+n%5E3+%2B+2+n%5E2+%2B+n%29%5E2+%2B+3+%5Ccdot+3+%283+n%5E3+%2B+2+n%5E2+%2B+n%29+%2B+1+%5C%3B%5C%3B%5C%3B+%28%5CS+5%29&bg=ffffff&fg=333333&s=0
"x^3+y_2^3=(3n^2)^3+(6n^2 +3n +1)^3 = 3 \\cdot 3^2 (3 n^3 + 2 n^2 + n)^2 + 3 \\cdot 3 (3 n^3 + 2 n^2 + n) + 1 \\;\\;\\; (\\S 5)")

By plugging ![z\_2= 3 (3 n^3 + 2 n^2 +
n)](https://s0.wp.com/latex.php?latex=z_2%3D+3+%283+n%5E3+%2B+2+n%5E2+%2B+n%29&bg=ffffff&fg=333333&s=0
"z_2= 3 (3 n^3 + 2 n^2 + n)") in ![(\\S
5)](https://s0.wp.com/latex.php?latex=%28%5CS+5%29&bg=ffffff&fg=333333&s=0
"(\\S 5)") we get ![x^3+y\_1^3+z\_2^3=
(z\_2+1)^3](https://s0.wp.com/latex.php?latex=x%5E3%2By_1%5E3%2Bz_2%5E3%3D+%28z_2%2B1%29%5E3&bg=ffffff&fg=333333&s=0
"x^3+y_1^3+z_2^3= (z_2+1)^3"), the second valid family of valid
solutions to the Japanese problem.

One can see that these two solutions are lattice points on a parabola
whose parametric equation is ![(x=3t^2, y=6t^2 \\pm 3t
+1)](https://s0.wp.com/latex.php?latex=%28x%3D3t%5E2%2C+y%3D6t%5E2+%5Cpm+3t+%2B1%29&bg=ffffff&fg=333333&s=0
"(x=3t^2, y=6t^2 \\pm 3t +1)"). Thus, both our solution which covers the
cubes of every positive integer and the Japanese solutions are 2
distinct parameterized families corresponding to parabolas in the
![(x,y)](https://s0.wp.com/latex.php?latex=%28x%2Cy%29&bg=ffffff&fg=333333&s=0
"(x,y)") plane.

**The elliptical families**  
When we learned of the Japanese solutions, we wondered if there might be
any other families of solutions hidden within the apparent disorder of
the total set of all solutions. Returning to the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0
"x-y") plot, we noted that several points lie on arcs of increasing size
(shown as orange and pink points in Figure 2). Examining these, we
discovered that they are integer points lying on pairs of related
ellipses of eccentricity
![\\sqrt{\\tfrac{2}{3}}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B%5Ctfrac%7B2%7D%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{\\tfrac{2}{3}}") that have equations of the form:

![\\begin{cases} x^2-xy+y^2-ax-by+c=0 \\\\\[6pt\] x^2-xy+y^2-bx-ay+c=0
\\end{cases} \\; \\; \\; (\\S
6)](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bcases%7D+x%5E2-xy%2By%5E2-ax-by%2Bc%3D0+%5C%5C%5B6pt%5D+x%5E2-xy%2By%5E2-bx-ay%2Bc%3D0+%5Cend%7Bcases%7D+%5C%3B+%5C%3B+%5C%3B+%28%5CS+6%29&bg=ffffff&fg=333333&s=0
"\\begin{cases} x^2-xy+y^2-ax-by+c=0 \\\\[6pt] x^2-xy+y^2-bx-ay+c=0 \\end{cases} \\; \\; \\; (\\S 6)")

Where the 3 parameters ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c") are defined by:

![c=27u^4+9u^2+1\\\\\[6pt\] a=c+(9u^2+1) = 27u^4 + 18u^2 + 2\\\\\[6pt\]
b=c-(9u^2+2)= 27u^4 -
1](https://s0.wp.com/latex.php?latex=c%3D27u%5E4%2B9u%5E2%2B1%5C%5C%5B6pt%5D+a%3Dc%2B%289u%5E2%2B1%29+%3D+27u%5E4+%2B+18u%5E2+%2B+2%5C%5C%5B6pt%5D+b%3Dc-%289u%5E2%2B2%29%3D+27u%5E4+-+1&bg=ffffff&fg=333333&s=0
"c=27u^4+9u^2+1\\\\[6pt] a=c+(9u^2+1) = 27u^4 + 18u^2 + 2\\\\[6pt] b=c-(9u^2+2)= 27u^4 - 1")

The lattice points of ![(\\S
6)](https://s0.wp.com/latex.php?latex=%28%5CS+6%29&bg=ffffff&fg=333333&s=0
"(\\S 6)") are solutions to ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)") and emerge at special values of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u").
First few values of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
and the number of solutions they yield on the 2 corresponding ellipses
are shown in Figure 4 and Table 1.

[![cube.diffelliptical\_fig4](https://manasataramgini.files.wordpress.com/2020/02/cube.diffelliptical_fig4.png?w=640)](https://manasataramgini.files.wordpress.com/2020/02/cube.diffelliptical_fig4.png)Figure
4

Table 1

![cubediff\_table1](https://manasataramgini.files.wordpress.com/2020/02/cubediff_table1.png?w=640)

The ellipses first corresponding to the few values of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
that yield solutions numbering ![\\ge
2](https://s0.wp.com/latex.php?latex=%5Cge+2&bg=ffffff&fg=333333&s=0
"\\ge 2") are show in Figure 5. Not all values of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
are equally rich in terms of solutions for ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"). The integers (1, 2, 3…), thirds i.e. ![n \\pm
\\tfrac{1}{3}](https://s0.wp.com/latex.php?latex=n+%5Cpm+%5Ctfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"n \\pm \\tfrac{1}{3}") consistently yield solutions but the integers
tend to be clearly richer than the thirds (Figure 4). Other than
integers, certain irrational values of the form
![u=\\sqrt{\\tfrac{6n+1}{6}}](https://s0.wp.com/latex.php?latex=u%3D%5Csqrt%7B%5Ctfrac%7B6n%2B1%7D%7B6%7D%7D&bg=ffffff&fg=333333&s=0
"u=\\sqrt{\\tfrac{6n+1}{6}}") are particularly rich in solutions. Other
than those,
![u=\\sqrt{12}](https://s0.wp.com/latex.php?latex=u%3D%5Csqrt%7B12%7D&bg=ffffff&fg=333333&s=0
"u=\\sqrt{12}") and certain values of the form
![u=\\sqrt{\\tfrac{6n+1}{18}}, u=
\\sqrt{\\tfrac{6n+2}{18}}](https://s0.wp.com/latex.php?latex=u%3D%5Csqrt%7B%5Ctfrac%7B6n%2B1%7D%7B18%7D%7D%2C+u%3D+%5Csqrt%7B%5Ctfrac%7B6n%2B2%7D%7B18%7D%7D&bg=ffffff&fg=333333&s=0
"u=\\sqrt{\\tfrac{6n+1}{18}}, u= \\sqrt{\\tfrac{6n+2}{18}}") are also
rich in solutions. Thus, ![12a, 12b,
12c](https://s0.wp.com/latex.php?latex=12a%2C+12b%2C+12c&bg=ffffff&fg=333333&s=0
"12a, 12b, 12c") are integers for all
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u"),
yielding solutions lying on ellipses. However, it remains unclear if
there is a general rule to determine which of the quadratic surds that
take the above forms will be
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
that yield solutions for ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"). In any case the given that integer
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
yield solutions for ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)") that lie on defined ellipses the family of such elliptical
solutions is infinite.

[![cube\_Ellipse\_complete\_workout](https://manasataramgini.files.wordpress.com/2020/02/cube_ellipse_complete_workout.png?w=652&h=670)](https://manasataramgini.files.wordpress.com/2020/02/cube_ellipse_complete_workout.png)Figure
5

Finally, we may note one special feature of the family of elliptical
solutions that are specifically associated with the integer values of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u").
Given that the solutions ![x, y,
z](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z&bg=ffffff&fg=333333&s=0
"x, y, z") define a simple curved surface (Figure 1), i.e. the surface
does not show any folding, there can utmost be 2 pairs of ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") that yield the same
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z").
There are 29
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
which can be derived from 2 distinct pairs of ![x, y\<
20000](https://s0.wp.com/latex.php?latex=x%2C+y%3C+20000&bg=ffffff&fg=333333&s=0
"x, y\< 20000"). For example: ![9^3+ 58^3= 22^3 +
57^3=256^3-255^3](https://s0.wp.com/latex.php?latex=9%5E3%2B+58%5E3%3D+22%5E3+%2B+57%5E3%3D256%5E3-255%5E3&bg=ffffff&fg=333333&s=0
"9^3+ 58^3= 22^3 + 57^3=256^3-255^3"). Thus, (9, 58) and (22, 57) form a
pair that yield the same
![z=255](https://s0.wp.com/latex.php?latex=z%3D255&bg=ffffff&fg=333333&s=0
"z=255"). The majority of such pairs of solutions with the same
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
lie on the ellipses arising from integer
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u").
Further, each such ellipse contains a pair whose whose
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
values are respectively defined by ![x\_1 =9u^3; x\_2=
9u^3+9u^2+3u+1](https://s0.wp.com/latex.php?latex=x_1+%3D9u%5E3%3B+x_2%3D+9u%5E3%2B9u%5E2%2B3u%2B1&bg=ffffff&fg=333333&s=0
"x_1 =9u^3; x_2= 9u^3+9u^2+3u+1"). The corresponding
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0 "y")
values can be obtained by plugging
![x\_1](https://s0.wp.com/latex.php?latex=x_1&bg=ffffff&fg=333333&s=0
"x_1") into the second ellipse and
![x\_2](https://s0.wp.com/latex.php?latex=x_2&bg=ffffff&fg=333333&s=0
"x_2") into the first ellipse in ![(\\S
6](https://s0.wp.com/latex.php?latex=%28%5CS+6&bg=ffffff&fg=333333&s=0
"(\\S 6")). Thus we get ![y\_1= 27n^4 + 18n^3 + 9n^2 + 3n + 1;
y\_2=27n^4 + 18n^3 + 9n^2 +
3n](https://s0.wp.com/latex.php?latex=y_1%3D+27n%5E4+%2B+18n%5E3+%2B+9n%5E2+%2B+3n+%2B+1%3B+y_2%3D27n%5E4+%2B+18n%5E3+%2B+9n%5E2+%2B+3n&bg=ffffff&fg=333333&s=0
"y_1= 27n^4 + 18n^3 + 9n^2 + 3n + 1; y_2=27n^4 + 18n^3 + 9n^2 + 3n");
thus, for these cases
![y\_1=y\_2+1](https://s0.wp.com/latex.php?latex=y_1%3Dy_2%2B1&bg=ffffff&fg=333333&s=0
"y_1=y_2+1"). These pairs are shown below for ![u=1, 2, 3,
4](https://s0.wp.com/latex.php?latex=u%3D1%2C+2%2C+3%2C+4&bg=ffffff&fg=333333&s=0
"u=1, 2, 3, 4").

Thus, these paired values define an infinite family by themselves lying
on in the curves defined by the below parametric equations (Figure 5,
blue curve):

![\\begin{cases} x= 9t^3\\\\\[6pt\] y= 27t^4 + 18t^3 + 9t^2 + 3t + 1
\\end{cases}\\\\\[10pt\] \\begin{cases} x=9t^3+9t^2+3t+1\\\\\[6pt\]
y=27t^4 + 18t^3 + 9t^2 + 3t
\\end{cases}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bcases%7D+x%3D+9t%5E3%5C%5C%5B6pt%5D+y%3D+27t%5E4+%2B+18t%5E3+%2B+9t%5E2+%2B+3t+%2B+1+%5Cend%7Bcases%7D%5C%5C%5B10pt%5D+%5Cbegin%7Bcases%7D+x%3D9t%5E3%2B9t%5E2%2B3t%2B1%5C%5C%5B6pt%5D+y%3D27t%5E4+%2B+18t%5E3+%2B+9t%5E2+%2B+3t+%5Cend%7Bcases%7D&bg=ffffff&fg=333333&s=0
"\\begin{cases} x= 9t^3\\\\[6pt] y= 27t^4 + 18t^3 + 9t^2 + 3t + 1 \\end{cases}\\\\[10pt] \\begin{cases} x=9t^3+9t^2+3t+1\\\\[6pt] y=27t^4 + 18t^3 + 9t^2 + 3t \\end{cases}")

There are a minority of pairs which lie outside of the ellipses. We do
not know as yet if they define any other families of solutions. More
generally, it is also not clear if there are any other families of
solutions beyond the above parabolic and elliptical families.

**Sum of cubes of 2 positive integers that equal the difference of cubes
successive same-parity positive integers**  
In this final section we shall briefly consider a related indeterminate
equation:

![x^3+y^3=(z+2)^3-z^3=6z^2+12z+8 \\; \\; \\; (\\S
7)](https://s0.wp.com/latex.php?latex=x%5E3%2By%5E3%3D%28z%2B2%29%5E3-z%5E3%3D6z%5E2%2B12z%2B8+%5C%3B+%5C%3B+%5C%3B+%28%5CS+7%29&bg=ffffff&fg=333333&s=0
"x^3+y^3=(z+2)^3-z^3=6z^2+12z+8 \\; \\; \\; (\\S 7)")

One can see right away that some of the regular families of solutions of
![(\\S
7)](https://s0.wp.com/latex.php?latex=%28%5CS+7%29&bg=ffffff&fg=333333&s=0
"(\\S 7)") are related to those of ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"). The first relates to the above theorem regarding the cubes
of every positive integer. In this case the equivalent is:

**The cube of every positive even number is equal to the difference of
the cubes of two consecutive even numbers minus the cube of another even
number.**

These correspond to the solutions to ![(\\S
7)](https://s0.wp.com/latex.php?latex=%28%5CS+7%29&bg=ffffff&fg=333333&s=0
"(\\S 7)") of the form ![(x=2n, y= 6n^2 + 4n +
2](https://s0.wp.com/latex.php?latex=%28x%3D2n%2C+y%3D+6n%5E2+%2B+4n+%2B+2&bg=ffffff&fg=333333&s=0
"(x=2n, y= 6n^2 + 4n + 2") (Figure 6, violet curve). Further, the
equivalents of the solutions to Gokai Ampon’s points in this case lie on
the parabola defined by the parametric equation: ![(x=6t^2, 12t^2 - 6t +
2)](https://s0.wp.com/latex.php?latex=%28x%3D6t%5E2%2C+12t%5E2+-+6t+%2B+2%29&bg=ffffff&fg=333333&s=0
"(x=6t^2, 12t^2 - 6t + 2)") (Figure 6, purple curve). However, the
solutions to ![(\\S
7)](https://s0.wp.com/latex.php?latex=%28%5CS+7%29&bg=ffffff&fg=333333&s=0
"(\\S 7)") feature a unique parabolic family of solutions with no
equivalent among the solutions of ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"). These lie on the parabola defined by the parametric
equation: ![(3t^2 - t + 1, 3t^2 + t +
1)](https://s0.wp.com/latex.php?latex=%283t%5E2+-+t+%2B+1%2C+3t%5E2+%2B+t+%2B+1%29&bg=ffffff&fg=333333&s=0
"(3t^2 - t + 1, 3t^2 + t + 1)") (Figure 6, orange curve). These
correspond to ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") such as:  
(3, 5); (11, 15) (25, 31) (45, 53)… Thus, ![x=3n^2 - n +
1](https://s0.wp.com/latex.php?latex=x%3D3n%5E2+-+n+%2B+1&bg=ffffff&fg=333333&s=0
"x=3n^2 - n + 1") and ![y=3n^2 + n +
1](https://s0.wp.com/latex.php?latex=y%3D3n%5E2+%2B+n+%2B+1&bg=ffffff&fg=333333&s=0
"y=3n^2 + n + 1") provide another link to the hexagonal number spiral as
they correspond to numbers that respectively lie on its 2nd and 4th
spoke (Figure 3). With this in hand, we can show that for these ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") give rise to ![z=3 n^3 + 2 n -
1](https://s0.wp.com/latex.php?latex=z%3D3+n%5E3+%2B+2+n+-+1&bg=ffffff&fg=333333&s=0
"z=3 n^3 + 2 n - 1"), which defines the sequence: **4, 27, 86, 199, 384,
659, 1042…**

As with the solutions to ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)"), here too we have the equivalent elliptical families
corresponding to the integer lattice points on ellipses of eccentricity
![\\sqrt{\\tfrac{2}{3}}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B%5Ctfrac%7B2%7D%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{\\tfrac{2}{3}}") that have equations of the form:

![x^2-xy+y^2-ax-by+c=0 \\\\\[6pt\]
x^2-xy+y^2-bx-ay+c=0](https://s0.wp.com/latex.php?latex=x%5E2-xy%2By%5E2-ax-by%2Bc%3D0+%5C%5C%5B6pt%5D+x%5E2-xy%2By%5E2-bx-ay%2Bc%3D0&bg=ffffff&fg=333333&s=0
"x^2-xy+y^2-ax-by+c=0 \\\\[6pt] x^2-xy+y^2-bx-ay+c=0")

Here the 3 parameters ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c") are defined by:

![a=54u^4 + 36u^2 + 4\\\\\[6pt\] b=54u^4 - 2\\\\\[6pt\] c=108u^4 + 36u^2
+
4](https://s0.wp.com/latex.php?latex=a%3D54u%5E4+%2B+36u%5E2+%2B+4%5C%5C%5B6pt%5D+b%3D54u%5E4+-+2%5C%5C%5B6pt%5D+c%3D108u%5E4+%2B+36u%5E2+%2B+4&bg=ffffff&fg=333333&s=0
"a=54u^4 + 36u^2 + 4\\\\[6pt] b=54u^4 - 2\\\\[6pt] c=108u^4 + 36u^2 + 4")

However, the
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0 "u")
which yield elliptical solutions for ![(\\S
7)](https://s0.wp.com/latex.php?latex=%28%5CS+7%29&bg=ffffff&fg=333333&s=0
"(\\S 7)") are the same as those that yield solutions for ![(\\S
1)](https://s0.wp.com/latex.php?latex=%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"(\\S 1)") and there is an equivalence in the corresponding solutions.
Figure 6 shows a few elliptical solutions ![\\left(u=2,
\\sqrt{\\tfrac{37}{3}}, \\tfrac{\\sqrt{73}}{3},
3\\right)](https://s0.wp.com/latex.php?latex=%5Cleft%28u%3D2%2C+%5Csqrt%7B%5Ctfrac%7B37%7D%7B3%7D%7D%2C+%5Ctfrac%7B%5Csqrt%7B73%7D%7D%7B3%7D%2C+3%5Cright%29&bg=ffffff&fg=333333&s=0
"\\left(u=2, \\sqrt{\\tfrac{37}{3}}, \\tfrac{\\sqrt{73}}{3}, 3\\right)").

In conclusion, this exploration reveals connections between a certain
class of cubic indeterminate equations and families of solutions defined
by particular parabolas and ellipses. It is not known to us if any one
previously studied these elliptical families or reported any other
families beyond those considered here.

[![cube2\_ellipse\_workout](https://manasataramgini.files.wordpress.com/2020/02/cube2_ellipse_workout.png?w=603&h=602)](https://manasataramgini.files.wordpress.com/2020/02/cube2_ellipse_workout.png)

Figure 6
