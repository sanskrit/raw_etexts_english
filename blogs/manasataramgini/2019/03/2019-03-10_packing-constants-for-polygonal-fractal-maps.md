+++
title = "Packing constants for polygonal fractal maps"

+++
Among the very first programs which we wrote in our childhood was one to
generate the famous Sierpinski triangle as an attractor using the “Chaos
Game” algorithm of Barnsley. A couple of years later we returned to it
generalize it as a map in the complex plane. Consider the polynomial
equation,

![z^m+1=0](https://s0.wp.com/latex.php?latex=z%5Em%2B1%3D0&bg=ffffff&fg=333333&s=0
"z^m+1=0"), where integer
![m=3,4,5...](https://s0.wp.com/latex.php?latex=m%3D3%2C4%2C5...&bg=ffffff&fg=333333&s=0
"m=3,4,5...")

The roots of this equation, ![z\_j: z\_1, z\_2...
z\_m](https://s0.wp.com/latex.php?latex=z_j%3A+z_1%2C+z_2...+z_m&bg=ffffff&fg=333333&s=0
"z_j: z_1, z_2... z_m"), define the vertices of a
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0
"m")-sided polygon in the complex plan. For example, if
![m=3](https://s0.wp.com/latex.php?latex=m%3D3&bg=ffffff&fg=333333&s=0
"m=3"), we get an equilateral triangle defined by the roots ![z\_1=
\\tfrac{1}{2}+\\tfrac{\\sqrt{3}i}{2}, z\_2= -1, z\_3=
\\tfrac{1}{2}-\\tfrac{\\sqrt{3}i}{2}](https://s0.wp.com/latex.php?latex=z_1%3D+%5Ctfrac%7B1%7D%7B2%7D%2B%5Ctfrac%7B%5Csqrt%7B3%7Di%7D%7B2%7D%2C+z_2%3D+-1%2C+z_3%3D+%5Ctfrac%7B1%7D%7B2%7D-%5Ctfrac%7B%5Csqrt%7B3%7Di%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"z_1= \\tfrac{1}{2}+\\tfrac{\\sqrt{3}i}{2}, z_2= -1, z_3= \\tfrac{1}{2}-\\tfrac{\\sqrt{3}i}{2}").

With this in place the Chaos Game map is defined for a given
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m")
as:

![z\_{n+1}=r(z\_n+z\_j)](https://s0.wp.com/latex.php?latex=z_%7Bn%2B1%7D%3Dr%28z_n%2Bz_j%29&bg=ffffff&fg=333333&s=0
"z_{n+1}=r(z_n+z_j)"),

where
![z\_j](https://s0.wp.com/latex.php?latex=z_j&bg=ffffff&fg=333333&s=0
"z_j") is one of the
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m")
roots chosen randomly with equal probability as the others in each
iteration of the map and ![0\<r\\le
1](https://s0.wp.com/latex.php?latex=0%3Cr%5Cle+1&bg=ffffff&fg=333333&s=0
"0\<r\\le 1"). If
![r=1](https://s0.wp.com/latex.php?latex=r%3D1&bg=ffffff&fg=333333&s=0
"r=1") for any
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m") we
get a random-walk structure (Figure 1).

[![chg06\_1](https://manasataramgini.files.wordpress.com/2019/03/chg06_1.png?w=629&h=629)](https://manasataramgini.files.wordpress.com/2019/03/chg06_1.png)Figure
1

For other ![m,
r](https://s0.wp.com/latex.php?latex=m%2C+r&bg=ffffff&fg=333333&s=0
"m, r") we get chaotic maps and for particular values of ![m,
r](https://s0.wp.com/latex.php?latex=m%2C+r&bg=ffffff&fg=333333&s=0
"m, r") we get attractors with a fractal structure. Thus, the Sierpinski
triangle is obtained with ![m=3,
r=\\tfrac{1}{2}](https://s0.wp.com/latex.php?latex=m%3D3%2C+r%3D%5Ctfrac%7B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"m=3, r=\\tfrac{1}{2}"). This fills the triangle defined by ![z\_1,
z\_2,
z\_3](https://s0.wp.com/latex.php?latex=z_1%2C+z_2%2C+z_3&bg=ffffff&fg=333333&s=0
"z_1, z_2, z_3")

[![chg03](https://manasataramgini.files.wordpress.com/2019/03/chg03.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg03.png)Figure
2

For ![m=4,
r=\\tfrac{1}{1+\\sqrt{2}}](https://s0.wp.com/latex.php?latex=m%3D4%2C+r%3D%5Ctfrac%7B1%7D%7B1%2B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"m=4, r=\\tfrac{1}{1+\\sqrt{2}}") we get the fractal street block
(Figure 3).

[![chg04](https://manasataramgini.files.wordpress.com/2019/03/chg04.png?w=655&h=655)](https://manasataramgini.files.wordpress.com/2019/03/chg04.png)Figure
3

We currently revisited this map because of a curious problem that
emerges when we continue this operation as below for further polygons.
For ![m=5,
r=1-\\tfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=m%3D5%2C+r%3D1-%5Ctfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"m=5, r=1-\\tfrac{1}{\\phi}") (where
![\\phi=\\tfrac{1+\\sqrt{5}}{2}](https://s0.wp.com/latex.php?latex=%5Cphi%3D%5Ctfrac%7B1%2B%5Csqrt%7B5%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\phi=\\tfrac{1+\\sqrt{5}}{2}"), the Golden Ratio) we get the fractal
pentagons surrounding the interior penta-flake (Figure 4).

[![chg05](https://manasataramgini.files.wordpress.com/2019/03/chg05.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg05.png)Figure
4

For ![m=6,
r=\\tfrac{1}{3}](https://s0.wp.com/latex.php?latex=m%3D6%2C+r%3D%5Ctfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"m=6, r=\\tfrac{1}{3}") we get the fractal hexagons surrounding the
interior Koch’s snowflake (Figure 5).

[![chg06](https://manasataramgini.files.wordpress.com/2019/03/chg06.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg06.png)Figure
5

For ![m=7,
r=\\tfrac{1}{S}](https://s0.wp.com/latex.php?latex=m%3D7%2C+r%3D%5Ctfrac%7B1%7D%7BS%7D&bg=ffffff&fg=333333&s=0
"m=7, r=\\tfrac{1}{S}") (where
![S=2+2\\cos\\left(\\tfrac{2\\pi}{7}\\right)](https://s0.wp.com/latex.php?latex=S%3D2%2B2%5Ccos%5Cleft%28%5Ctfrac%7B2%5Cpi%7D%7B7%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"S=2+2\\cos\\left(\\tfrac{2\\pi}{7}\\right)"), the Silver constant. The
[Silver
constant](https://manasataramgini.wordpress.com/2017/06/01/constructing-a-regular-heptagon-with-hyperbola-and-parabola/)
is an algebraic number which is the real root of the cubic
![x^3-5x^2+6x-1](https://s0.wp.com/latex.php?latex=x%5E3-5x%5E2%2B6x-1&bg=ffffff&fg=333333&s=0
"x^3-5x^2+6x-1")) we get the fractal heptagon necklace surrounding the
interior hepta-flake (Figure 6).

[![chg07](https://manasataramgini.files.wordpress.com/2019/03/chg07.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg07.png)Figure
6

For ![m=8,
r=\\tfrac{1}{2+\\sqrt{2}}](https://s0.wp.com/latex.php?latex=m%3D8%2C+r%3D%5Ctfrac%7B1%7D%7B2%2B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"m=8, r=\\tfrac{1}{2+\\sqrt{2}}") we get the fractal octagon necklace
(Figure 7).

[![chg08](https://manasataramgini.files.wordpress.com/2019/03/chg08.png?w=653&h=653)](https://manasataramgini.files.wordpress.com/2019/03/chg08.png)Figure
7

For ![m=9,
r=\\tfrac{1}{2+2\\cos\\left(\\pi/9\\right)}](https://s0.wp.com/latex.php?latex=m%3D9%2C+r%3D%5Ctfrac%7B1%7D%7B2%2B2%5Ccos%5Cleft%28%5Cpi%2F9%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"m=9, r=\\tfrac{1}{2+2\\cos\\left(\\pi/9\\right)}") we get the fractal
nonagon necklace (Figure 8).

[![chg09](https://manasataramgini.files.wordpress.com/2019/03/chg09.png?w=640)](https://manasataramgini.files.wordpress.com/2019/03/chg09.png)Figure
8

For ![m=10,
r=\\tfrac{1}{1+2\\phi}](https://s0.wp.com/latex.php?latex=m%3D10%2C+r%3D%5Ctfrac%7B1%7D%7B1%2B2%5Cphi%7D&bg=ffffff&fg=333333&s=0
"m=10, r=\\tfrac{1}{1+2\\phi}") we get the fractal decagon necklace
(Figure 9).

[![chg10](https://manasataramgini.files.wordpress.com/2019/03/chg10.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg10.png)Figure
9

For ![m=11, r\\approx
0.2209](https://s0.wp.com/latex.php?latex=m%3D11%2C+r%5Capprox+0.2209&bg=ffffff&fg=333333&s=0
"m=11, r\\approx 0.2209") we get the fractal hendecagon necklace (Figure
10).

[![chg11](https://manasataramgini.files.wordpress.com/2019/03/chg11.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg11.png)Figure
10

For ![m=12,
r=\\tfrac{1}{3+\\sqrt{3}}](https://s0.wp.com/latex.php?latex=m%3D12%2C+r%3D%5Ctfrac%7B1%7D%7B3%2B%5Csqrt%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"m=12, r=\\tfrac{1}{3+\\sqrt{3}}") we get the fractal dodecagon necklace
(Figure 11).

[![chg12](https://manasataramgini.files.wordpress.com/2019/03/chg12.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg12.png)Figure
11

Given that these attractors are fractal, they have an infinite perimeter
but occupy a finite area. Thus, one can define a common feature for the
above attractors namely “tangency” of the fractal elements, i.e., each
polygonal unit is distinct from its neighbor with the same scale-factor
but at same time makes a contact with it like a tangent. While for the
triangle and the square this definition is a bit murky, it is clearly
visible from the pentagon onward. It can be contrasted with other
fractal attractors obtained by this method where the elements overlap or
are shared. For instance for ![m=12,
r=\\tfrac{1}{2+2\\cos\\left(\\pi/6\\right)}](https://s0.wp.com/latex.php?latex=m%3D12%2C+r%3D%5Ctfrac%7B1%7D%7B2%2B2%5Ccos%5Cleft%28%5Cpi%2F6%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"m=12, r=\\tfrac{1}{2+2\\cos\\left(\\pi/6\\right)}"), we have the
expected dodecad structure but two dodecad sub-elements are shared by
each of the adjacent elements (Figure 12).

[![chg\_12\_wheel\_time](https://manasataramgini.files.wordpress.com/2019/03/chg_12_wheel_time.png?w=654&h=654)](https://manasataramgini.files.wordpress.com/2019/03/chg_12_wheel_time.png)Figure
12

In the above examples (Figure 2-11) we have determined for each polygon
the value of
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0 "r")
which results in a tangent attractor:

![m=3, r=\\tfrac{1}{2}; m=4, r=\\tfrac{1}{1+\\sqrt{2}}; m=5,
r=1-\\tfrac{1}{\\phi}; m=6, r=\\tfrac{1}{3};\\\\ m=7, r=\\tfrac{1}{S};
m=8, r=\\tfrac{1}{2+\\sqrt{2}}; m=9,
r=\\tfrac{1}{2+2\\cos\\left(\\pi/9\\right)}; \\\\ m=10,
r=\\tfrac{1}{1+2\\phi}, ; m=11, r\\approx 0.2209; m=12,
r=\\tfrac{1}{3+\\sqrt{3}}](https://s0.wp.com/latex.php?latex=m%3D3%2C+r%3D%5Ctfrac%7B1%7D%7B2%7D%3B+m%3D4%2C+r%3D%5Ctfrac%7B1%7D%7B1%2B%5Csqrt%7B2%7D%7D%3B+m%3D5%2C+r%3D1-%5Ctfrac%7B1%7D%7B%5Cphi%7D%3B+m%3D6%2C+r%3D%5Ctfrac%7B1%7D%7B3%7D%3B%5C%5C+++m%3D7%2C+r%3D%5Ctfrac%7B1%7D%7BS%7D%3B+m%3D8%2C+r%3D%5Ctfrac%7B1%7D%7B2%2B%5Csqrt%7B2%7D%7D%3B+m%3D9%2C+r%3D%5Ctfrac%7B1%7D%7B2%2B2%5Ccos%5Cleft%28%5Cpi%2F9%5Cright%29%7D%3B+%5C%5C++m%3D10%2C+r%3D%5Ctfrac%7B1%7D%7B1%2B2%5Cphi%7D%2C+%3B+m%3D11%2C++r%5Capprox+0.2209%3B+m%3D12%2C+r%3D%5Ctfrac%7B1%7D%7B3%2B%5Csqrt%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"m=3, r=\\tfrac{1}{2}; m=4, r=\\tfrac{1}{1+\\sqrt{2}}; m=5, r=1-\\tfrac{1}{\\phi}; m=6, r=\\tfrac{1}{3};\\\\   m=7, r=\\tfrac{1}{S}; m=8, r=\\tfrac{1}{2+\\sqrt{2}}; m=9, r=\\tfrac{1}{2+2\\cos\\left(\\pi/9\\right)}; \\\\  m=10, r=\\tfrac{1}{1+2\\phi}, ; m=11,  r\\approx 0.2209; m=12, r=\\tfrac{1}{3+\\sqrt{3}}")

For
![m=5..8](https://s0.wp.com/latex.php?latex=m%3D5..8&bg=ffffff&fg=333333&s=0
"m=5..8") it is the reciprocal of
![2+2\\cos\\left(\\tfrac{2\\pi}{m}\\right)=4\\cos^2\\left(\\tfrac{\\pi}{m}\\right)](https://s0.wp.com/latex.php?latex=2%2B2%5Ccos%5Cleft%28%5Ctfrac%7B2%5Cpi%7D%7Bm%7D%5Cright%29%3D4%5Ccos%5E2%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7Bm%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"2+2\\cos\\left(\\tfrac{2\\pi}{m}\\right)=4\\cos^2\\left(\\tfrac{\\pi}{m}\\right)"),
which are known as Beraha constants (
![B\_n](https://s0.wp.com/latex.php?latex=B_n&bg=ffffff&fg=333333&s=0
"B_n")) that appear in graph-coloring theory. However, for
![m=9..12](https://s0.wp.com/latex.php?latex=m%3D9..12&bg=ffffff&fg=333333&s=0
"m=9..12") this principle clearly breaks down: e.g. for
![m=12](https://s0.wp.com/latex.php?latex=m%3D12&bg=ffffff&fg=333333&s=0
"m=12"), we see that
![\\tfrac{1}{B\_{12}}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7BB_%7B12%7D%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{B_{12}}") yields the overlapping attractor (Figure 12). We
have been able to obtain closed forms for the
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0 "r")
that yield tangent attractors for all
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m")
except 11, where we report an empirically determined approximate value.
What is the closed form expression for it? This leads to the question of
whether there is a general formula to obtain our
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0 "r")
that results in tangency? To our knowledge these have not been answered.
