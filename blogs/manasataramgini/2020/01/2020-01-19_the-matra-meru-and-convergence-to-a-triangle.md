+++
title = "The Mātrā-meru and convergence to a triangle"

+++
What is presented below will be elementary for someone with even just
the mastery of secondary school mathematics. Nevertheless, even simple
stuff might present points of interest to people who see beauty in such
things. Consider the following question:

Given the first 2 terms ![0 \\le x\_1, x\_2 \\le
1](https://s0.wp.com/latex.php?latex=0+%5Cle+x_1%2C+x_2+%5Cle+1&bg=ffffff&fg=333333&s=0
"0 \\le x_1, x_2 \\le 1"), what will be the behavior of the sequence
defined by the recursive relationship:

![x\_{n+1}=x\_n\\sqrt{1-x\_{n-1}^2}+x\_{n-1}\\sqrt{1-x\_n^2}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3Dx_n%5Csqrt%7B1-x_%7Bn-1%7D%5E2%7D%2Bx_%7Bn-1%7D%5Csqrt%7B1-x_n%5E2%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=x_n\\sqrt{1-x_{n-1}^2}+x_{n-1}\\sqrt{1-x_n^2}")

*Answer:* It will converge to a cycle of length 3, where ![x\_n,
x\_{n+1},
x\_{n+2}](https://s0.wp.com/latex.php?latex=x_n%2C+x_%7Bn%2B1%7D%2C+x_%7Bn%2B2%7D&bg=ffffff&fg=333333&s=0
"x_n, x_{n+1}, x_{n+2}") will be the sines of the 3 angles of a right or
an acute triangle. Further, let
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0 "M") be
the well-known Mātrā-meru sequence: **1, 1, 2, 3, 5, 8, 13, 21…**, then:

![x\_n=\\sin\\left(M\[n\]\\arcsin\\left(x\_1\\right)+M\[n+1\]
\\arcsin\\left(x\_2\\right)
\\right)](https://s0.wp.com/latex.php?latex=x_n%3D%5Csin%5Cleft%28M%5Bn%5D%5Carcsin%5Cleft%28x_1%5Cright%29%2BM%5Bn%2B1%5D+%5Carcsin%5Cleft%28x_2%5Cright%29+%5Cright%29&bg=ffffff&fg=333333&s=0
"x_n=\\sin\\left(M[n]\\arcsin\\left(x_1\\right)+M[n+1] \\arcsin\\left(x_2\\right) \\right)");  
![x\_{n+1}=\\sin\\left(M\[n+1\]\\arcsin\\left(x\_1\\right)+M\[n+2\]
\\arcsin\\left(x\_2\\right)
\\right)](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Csin%5Cleft%28M%5Bn%2B1%5D%5Carcsin%5Cleft%28x_1%5Cright%29%2BM%5Bn%2B2%5D+%5Carcsin%5Cleft%28x_2%5Cright%29+%5Cright%29&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\sin\\left(M[n+1]\\arcsin\\left(x_1\\right)+M[n+2] \\arcsin\\left(x_2\\right) \\right)");  
![x\_{n+2}=\\sin\\left(\\pi-M\[n+2\]\\arcsin\\left(x\_1\\right)+M\[n+3\]
\\arcsin\\left(x\_2\\right)
\\right)](https://s0.wp.com/latex.php?latex=x_%7Bn%2B2%7D%3D%5Csin%5Cleft%28%5Cpi-M%5Bn%2B2%5D%5Carcsin%5Cleft%28x_1%5Cright%29%2BM%5Bn%2B3%5D+%5Carcsin%5Cleft%28x_2%5Cright%29+%5Cright%29&bg=ffffff&fg=333333&s=0
"x_{n+2}=\\sin\\left(\\pi-M[n+2]\\arcsin\\left(x_1\\right)+M[n+3] \\arcsin\\left(x_2\\right) \\right)")

Where ![M\[n+1\]\\arcsin\\left(x\_1\\right)+M\[n+2\]
\\arcsin\\left(x\_2\\right)](https://s0.wp.com/latex.php?latex=M%5Bn%2B1%5D%5Carcsin%5Cleft%28x_1%5Cright%29%2BM%5Bn%2B2%5D+%5Carcsin%5Cleft%28x_2%5Cright%29&bg=ffffff&fg=333333&s=0
"M[n+1]\\arcsin\\left(x_1\\right)+M[n+2] \\arcsin\\left(x_2\\right)") is
the largest such angle that is ![\\le
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Cle+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\le \\tfrac{\\pi}{2}")

This can be easily proved thus:

1\) Since ![0 \\le x\_1, x\_2 \\le
1](https://s0.wp.com/latex.php?latex=0+%5Cle+x_1%2C+x_2+%5Cle+1&bg=ffffff&fg=333333&s=0
"0 \\le x_1, x_2 \\le 1"), we can write ![x\_1=\\sin(A),
x\_2=\\sin(B)](https://s0.wp.com/latex.php?latex=x_1%3D%5Csin%28A%29%2C+x_2%3D%5Csin%28B%29&bg=ffffff&fg=333333&s=0
"x_1=\\sin(A), x_2=\\sin(B)").

2\) Thus, given the recursive relationship the next term becomes,  
![x\_3=\\sin(A)\\cos(B)+\\sin(B)\\cos(A)=\\sin(A+B)](https://s0.wp.com/latex.php?latex=x_3%3D%5Csin%28A%29%5Ccos%28B%29%2B%5Csin%28B%29%5Ccos%28A%29%3D%5Csin%28A%2BB%29&bg=ffffff&fg=333333&s=0
"x_3=\\sin(A)\\cos(B)+\\sin(B)\\cos(A)=\\sin(A+B)")

3\) Continuing this way, we can write,  
![x\_4=\\sin(A+2B); \\; x\_5=\\sin(2A+3B); \\; x\_6=
\\sin(3A+5B)](https://s0.wp.com/latex.php?latex=x_4%3D%5Csin%28A%2B2B%29%3B+%5C%3B+x_5%3D%5Csin%282A%2B3B%29%3B+%5C%3B+x_6%3D+%5Csin%283A%2B5B%29&bg=ffffff&fg=333333&s=0
"x_4=\\sin(A+2B); \\; x_5=\\sin(2A+3B); \\; x_6= \\sin(3A+5B)").

We notice the multiplicands of ![A,
B](https://s0.wp.com/latex.php?latex=A%2C+B&bg=ffffff&fg=333333&s=0
"A, B") are the successive terms of the Mātrā-meru sequence. Thus,
![x\_n=\\sin\\left(M\[k\]A+M\[k+1\] B
\\right)](https://s0.wp.com/latex.php?latex=x_n%3D%5Csin%5Cleft%28M%5Bk%5DA%2BM%5Bk%2B1%5D+B+%5Cright%29&bg=ffffff&fg=333333&s=0
"x_n=\\sin\\left(M[k]A+M[k+1] B \\right)").

4\) This will continue till
![M\[k\]A+M\[k+1\]B](https://s0.wp.com/latex.php?latex=M%5Bk%5DA%2BM%5Bk%2B1%5DB&bg=ffffff&fg=333333&s=0
"M[k]A+M[k+1]B") comes closest to
![\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{2}"). Then the next term ![M\[k+1\]A+M\[k+2\]B \\ge
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=M%5Bk%2B1%5DA%2BM%5Bk%2B2%5DB+%5Cge+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"M[k+1]A+M[k+2]B \\ge \\tfrac{\\pi}{2}"). But due the symmetry of the
sine function,

![\\sin(M\[k+1\]A+M\[k+2\]B)=\\sin(\\pi-M\[k+1\]A+M\[k+2\]B)](https://s0.wp.com/latex.php?latex=%5Csin%28M%5Bk%2B1%5DA%2BM%5Bk%2B2%5DB%29%3D%5Csin%28%5Cpi-M%5Bk%2B1%5DA%2BM%5Bk%2B2%5DB%29&bg=ffffff&fg=333333&s=0
"\\sin(M[k+1]A+M[k+2]B)=\\sin(\\pi-M[k+1]A+M[k+2]B)").

Since,
![M\[k+1\]A+M\[k+2\]B=M\[k-1\]A+M\[k\]B+M\[k\]A+M\[k+1\]B](https://s0.wp.com/latex.php?latex=M%5Bk%2B1%5DA%2BM%5Bk%2B2%5DB%3DM%5Bk-1%5DA%2BM%5Bk%5DB%2BM%5Bk%5DA%2BM%5Bk%2B1%5DB&bg=ffffff&fg=333333&s=0
"M[k+1]A+M[k+2]B=M[k-1]A+M[k]B+M[k]A+M[k+1]B"),

we get ![M\[k-1\]A+M\[k\]B+M\[k\]A+M\[k+1\]B+\\pi-M\[k+1\]A+M\[k+2\]B =
\\pi](https://s0.wp.com/latex.php?latex=M%5Bk-1%5DA%2BM%5Bk%5DB%2BM%5Bk%5DA%2BM%5Bk%2B1%5DB%2B%5Cpi-M%5Bk%2B1%5DA%2BM%5Bk%2B2%5DB+%3D+%5Cpi&bg=ffffff&fg=333333&s=0
"M[k-1]A+M[k]B+M[k]A+M[k+1]B+\\pi-M[k+1]A+M[k+2]B = \\pi").

Thus, at this stage the three successive terms ![x\_n, x\_{n+1},
x\_{n+2}](https://s0.wp.com/latex.php?latex=x_n%2C+x_%7Bn%2B1%7D%2C+x_%7Bn%2B2%7D&bg=ffffff&fg=333333&s=0
"x_n, x_{n+1}, x_{n+2}") are sines of the 3 angles of an acute or right
triangle and they will settle into a cycle of those 3 values
![\_{...\\blacksquare}](https://s0.wp.com/latex.php?latex=_%7B...%5Cblacksquare%7D&bg=ffffff&fg=333333&s=0
"_{...\\blacksquare}")

Hence, the above recursive relationship results in any pair of ![x\_1,
x\_2](https://s0.wp.com/latex.php?latex=x_1%2C+x_2&bg=ffffff&fg=333333&s=0
"x_1, x_2") converging to the 3 sines of an acute or right triangle. As
a corollary if you start with ![x\_1,
x\_2](https://s0.wp.com/latex.php?latex=x_1%2C+x_2&bg=ffffff&fg=333333&s=0
"x_1, x_2") which are already sines of an acute or right triangle then
you stay on that triangle. Let us consider some special cases below
(Figure 1).

[![Contri\_Fig1](https://manasataramgini.files.wordpress.com/2020/01/contri_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2020/01/contri_fig1.png)Figure
1. The angles are given in degrees for ease of representation

When
![x\_1=x\_2=\\tfrac{\\sqrt{3}}{2}](https://s0.wp.com/latex.php?latex=x_1%3Dx_2%3D%5Ctfrac%7B%5Csqrt%7B3%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x_1=x_2=\\tfrac{\\sqrt{3}}{2}") then the values are on an equilateral
triangle and the iterates remain fixed on that triangle (Figure 1, panel
1).

When ![x\_1=\\tfrac{3}{4}; \\;
x\_2=\\tfrac{4}{5}](https://s0.wp.com/latex.php?latex=x_1%3D%5Ctfrac%7B3%7D%7B4%7D%3B+%5C%3B+x_2%3D%5Ctfrac%7B4%7D%7B5%7D&bg=ffffff&fg=333333&s=0
"x_1=\\tfrac{3}{4}; \\; x_2=\\tfrac{4}{5}") then the values are on the
3-4-5 right triangle and the iterates remain fixed on that triangle
(Figure 1, panel 2).

When ![x\_1=\\tfrac{1}{\\sqrt{2}}; \\;
x\_2=\\tfrac{1}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=x_1%3D%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D%3B+%5C%3B+x_2%3D%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"x_1=\\tfrac{1}{\\sqrt{2}}; \\; x_2=\\tfrac{1}{\\sqrt{2}}") then the
values are on the half-square right triangle and the iterates remain
fixed on that triangle (Figure 1, panel 3).

When
![x\_1=x\_2=\\tfrac{1}{2}](https://s0.wp.com/latex.php?latex=x_1%3Dx_2%3D%5Ctfrac%7B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x_1=x_2=\\tfrac{1}{2}") then they are not an acute or right triangle.
However, within one iteration the iterates converge to the sines of a
right triangle, namely the ![30^\\circ-60^\\circ-90^\\circ \\;
\\triangle](https://s0.wp.com/latex.php?latex=30%5E%5Ccirc-60%5E%5Ccirc-90%5E%5Ccirc+%5C%3B+%5Ctriangle&bg=ffffff&fg=333333&s=0
"30^\\circ-60^\\circ-90^\\circ \\; \\triangle") (Figure 1, panel 4).

It is easy to see that if ![\\tfrac{1}{\\sqrt{2}} \\ge x\_1=x\_2 \\le
1](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D+%5Cge+x_1%3Dx_2+%5Cle+1&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{\\sqrt{2}} \\ge x_1=x_2 \\le 1") then they are on an
isosceles triangle and remain on that. However, if
![\\arcsin(x\_1)+\\arcsin(x\_2) \<
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Carcsin%28x_1%29%2B%5Carcsin%28x_2%29+%3C+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\arcsin(x_1)+\\arcsin(x_2) \< \\tfrac{\\pi}{2}") then can we converge
to an isosceles acute triangle? This happens in special cases which can
be determined by solving an equation. In order to do so we shall take
![x\_2=x; \\; x\_1=k-x; \\; k\<
\\sqrt{2}](https://s0.wp.com/latex.php?latex=x_2%3Dx%3B+%5C%3B+x_1%3Dk-x%3B+%5C%3B+k%3C+%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"x_2=x; \\; x_1=k-x; \\; k\< \\sqrt{2}"). From the above proof the
successive angles corresponding to the iterates of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") are:

![\\arcsin(k-x); \\; \\arcsin(x); \\arcsin(k-x) + \\arcsin(x); \\;
\\arcsin(k-x) + 2\\arcsin(x); \\; 2\\arcsin(k-x) + 3\\arcsin(x); \\;
3\\arcsin(k-x) +
5\\arcsin(x)...](https://s0.wp.com/latex.php?latex=%5Carcsin%28k-x%29%3B+%5C%3B+%5Carcsin%28x%29%3B+%5Carcsin%28k-x%29+%2B+%5Carcsin%28x%29%3B+%5C%3B+%5Carcsin%28k-x%29+%2B+2%5Carcsin%28x%29%3B+%5C%3B+2%5Carcsin%28k-x%29+%2B+3%5Carcsin%28x%29%3B+%5C%3B+3%5Carcsin%28k-x%29+%2B+5%5Carcsin%28x%29...&bg=ffffff&fg=333333&s=0
"\\arcsin(k-x); \\; \\arcsin(x); \\arcsin(k-x) + \\arcsin(x); \\; \\arcsin(k-x) + 2\\arcsin(x); \\; 2\\arcsin(k-x) + 3\\arcsin(x); \\; 3\\arcsin(k-x) + 5\\arcsin(x)...")

Thus, we have to look for real solutions of the equations such as:

![\\arcsin(k-x)=\\pi -
(\\arcsin(k-x)+\\arcsin(x))](https://s0.wp.com/latex.php?latex=%5Carcsin%28k-x%29%3D%5Cpi+-+%28%5Carcsin%28k-x%29%2B%5Carcsin%28x%29%29&bg=ffffff&fg=333333&s=0
"\\arcsin(k-x)=\\pi - (\\arcsin(k-x)+\\arcsin(x))")  
![\\arcsin(x) = \\pi -(\\arcsin(k-x) +
\\arcsin(x)](https://s0.wp.com/latex.php?latex=%5Carcsin%28x%29+%3D+%5Cpi+-%28%5Carcsin%28k-x%29+%2B+%5Carcsin%28x%29&bg=ffffff&fg=333333&s=0
"\\arcsin(x) = \\pi -(\\arcsin(k-x) + \\arcsin(x)")  
![\\arcsin(x) = \\pi -(\\arcsin(k-x) + 2\\arcsin(x))
...](https://s0.wp.com/latex.php?latex=%5Carcsin%28x%29+%3D+%5Cpi+-%28%5Carcsin%28k-x%29+%2B+2%5Carcsin%28x%29%29+...&bg=ffffff&fg=333333&s=0
"\\arcsin(x) = \\pi -(\\arcsin(k-x) + 2\\arcsin(x)) ...")

Let consider the example of ![k=
1](https://s0.wp.com/latex.php?latex=k%3D+1&bg=ffffff&fg=333333&s=0
"k= 1"): with either of the first two equations we get degenerate
triangles (e.g. ![x\_1=0, x\_2=1,
x\_3=1](https://s0.wp.com/latex.php?latex=x_1%3D0%2C+x_2%3D1%2C+x_3%3D1&bg=ffffff&fg=333333&s=0
"x_1=0, x_2=1, x_3=1")). However, if we instead take
![x\_1=\\tfrac{1}{m},
x\_2=\\tfrac{m-1}{m}](https://s0.wp.com/latex.php?latex=x_1%3D%5Ctfrac%7B1%7D%7Bm%7D%2C+x_2%3D%5Ctfrac%7Bm-1%7D%7Bm%7D&bg=ffffff&fg=333333&s=0
"x_1=\\tfrac{1}{m}, x_2=\\tfrac{m-1}{m}") for some large
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m") we
get near-isosceles triangles (Figure 1, panel 5).

The one equation with a real solution for
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1"), which gives a unique isosceles triangle, is seen when:

![\\arcsin(1-x) +3 \\arcsin(x) = \\pi, \\; x \\approx
0.83756543528332](https://s0.wp.com/latex.php?latex=%5Carcsin%281-x%29+%2B3+%5Carcsin%28x%29+%3D+%5Cpi%2C+%5C%3B+x+%5Capprox+0.83756543528332&bg=ffffff&fg=333333&s=0
"\\arcsin(1-x) +3 \\arcsin(x) = \\pi, \\; x \\approx 0.83756543528332")

This ![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x") is the greatest root
![(r\_1)](https://s0.wp.com/latex.php?latex=%28r_1%29&bg=ffffff&fg=333333&s=0
"(r_1)") of the cubic equation
![4x^3-4x+1=0](https://s0.wp.com/latex.php?latex=4x%5E3-4x%2B1%3D0&bg=ffffff&fg=333333&s=0
"4x^3-4x+1=0"). Thus, ![x\_1=1-r\_1, x\_2=
r\_1](https://s0.wp.com/latex.php?latex=x_1%3D1-r_1%2C+x_2%3D+r_1&bg=ffffff&fg=333333&s=0
"x_1=1-r_1, x_2= r_1") yields an isosceles triangle with its equal
angles ![\\arcsin(r\_1) \\approx
56.88^\\circ](https://s0.wp.com/latex.php?latex=%5Carcsin%28r_1%29+%5Capprox+56.88%5E%5Ccirc&bg=ffffff&fg=333333&s=0
"\\arcsin(r_1) \\approx 56.88^\\circ") (Figure 1, panel 6).

Next we shall consider the evolution of certain special sequences of
triangles. The first is where ![x\_1,
x\_2](https://s0.wp.com/latex.php?latex=x_1%2C+x_2&bg=ffffff&fg=333333&s=0
"x_1, x_2") are constituted by successive terms of the Mātrā-meru
sequence (Figure 2).

[![Contri\_Fig2\_meru](https://manasataramgini.files.wordpress.com/2020/01/contri_fig2_meru.png?w=640)](https://manasataramgini.files.wordpress.com/2020/01/contri_fig2_meru.png)Figure
2.

Here, the triangles start with the ![30^\\circ-60^\\circ-90^\\circ \\;
\\triangle](https://s0.wp.com/latex.php?latex=30%5E%5Ccirc-60%5E%5Ccirc-90%5E%5Ccirc+%5C%3B+%5Ctriangle&bg=ffffff&fg=333333&s=0
"30^\\circ-60^\\circ-90^\\circ \\; \\triangle") and converge to a unique
scalene triangle with angles ![\\arcsin\\left(\\tfrac{1}{\\phi}\\right)
- \\arcsin\\left(\\tfrac{3\\phi-1}{2\\phi+1}\\right) -
\\arcsin\\left(\\tfrac{2\\sqrt{\\phi}}{\\phi+1}\\right) \\approx
38.17^\\circ - 65.48^\\circ -
76.35^\\circ](https://s0.wp.com/latex.php?latex=%5Carcsin%5Cleft%28%5Ctfrac%7B1%7D%7B%5Cphi%7D%5Cright%29+-+%5Carcsin%5Cleft%28%5Ctfrac%7B3%5Cphi-1%7D%7B2%5Cphi%2B1%7D%5Cright%29+-+%5Carcsin%5Cleft%28%5Ctfrac%7B2%5Csqrt%7B%5Cphi%7D%7D%7B%5Cphi%2B1%7D%5Cright%29+%5Capprox+38.17%5E%5Ccirc+-+65.48%5E%5Ccirc+-+76.35%5E%5Ccirc&bg=ffffff&fg=333333&s=0
"\\arcsin\\left(\\tfrac{1}{\\phi}\\right) - \\arcsin\\left(\\tfrac{3\\phi-1}{2\\phi+1}\\right) - \\arcsin\\left(\\tfrac{2\\sqrt{\\phi}}{\\phi+1}\\right) \\approx 38.17^\\circ - 65.48^\\circ - 76.35^\\circ"),
where ![\\phi=
\\tfrac{1+\\sqrt{5}}{2}](https://s0.wp.com/latex.php?latex=%5Cphi%3D+%5Ctfrac%7B1%2B%5Csqrt%7B5%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\phi= \\tfrac{1+\\sqrt{5}}{2}") is the Golden ratio.

The last panel here shows an interesting numeric coincidence. If you
start with ![x\_1=r\_1,
x\_2=1-r\_1](https://s0.wp.com/latex.php?latex=x_1%3Dr_1%2C+x_2%3D1-r_1&bg=ffffff&fg=333333&s=0
"x_1=r_1, x_2=1-r_1") (see above for
![r\_1](https://s0.wp.com/latex.php?latex=r_1&bg=ffffff&fg=333333&s=0
"r_1")) you converge to a triangle close to that emerging from the
Mātrā-meru sequence. Is there more to this than the coincidence of
values?

Finally, let us consider 2 other special triangles that emerge as
convergents for 2 related types of operations based on the Mātrā-meru
sequence (Figure 3).

[![Contri\_Fig3\_meru\_dens](https://manasataramgini.files.wordpress.com/2020/01/contri_fig3_meru_dens.png?w=640)](https://manasataramgini.files.wordpress.com/2020/01/contri_fig3_meru_dens.png)Figure
3.

The first 2 rows (in light green) show triangles emerging from
![x\_1=\\tfrac{1}{M\[k\]},
x\_2=\\tfrac{1}{M\[k+1\]}](https://s0.wp.com/latex.php?latex=x_1%3D%5Ctfrac%7B1%7D%7BM%5Bk%5D%7D%2C+x_2%3D%5Ctfrac%7B1%7D%7BM%5Bk%2B1%5D%7D&bg=ffffff&fg=333333&s=0
"x_1=\\tfrac{1}{M[k]}, x_2=\\tfrac{1}{M[k+1]}"), where ![k=2, 3,
4...](https://s0.wp.com/latex.php?latex=k%3D2%2C+3%2C+4...&bg=ffffff&fg=333333&s=0
"k=2, 3, 4..."). Here again, we start with a
![30^\\circ-60^\\circ-90^\\circ \\;
\\triangle](https://s0.wp.com/latex.php?latex=30%5E%5Ccirc-60%5E%5Ccirc-90%5E%5Ccirc+%5C%3B+%5Ctriangle&bg=ffffff&fg=333333&s=0
"30^\\circ-60^\\circ-90^\\circ \\; \\triangle") and converge to a
triangle of the form ![\\approx 70.82^\\circ - 65.41^\\circ -
43.77^\\circ](https://s0.wp.com/latex.php?latex=%5Capprox+70.82%5E%5Ccirc+-+65.41%5E%5Ccirc+-+43.77%5E%5Ccirc&bg=ffffff&fg=333333&s=0
"\\approx 70.82^\\circ - 65.41^\\circ - 43.77^\\circ").

The second 2 rows (in yellow) show triangles emerging from
![x\_1=\\tfrac{1}{M\[k\]},
x\_2=\\tfrac{1}{M\[k\]}](https://s0.wp.com/latex.php?latex=x_1%3D%5Ctfrac%7B1%7D%7BM%5Bk%5D%7D%2C+x_2%3D%5Ctfrac%7B1%7D%7BM%5Bk%5D%7D&bg=ffffff&fg=333333&s=0
"x_1=\\tfrac{1}{M[k]}, x_2=\\tfrac{1}{M[k]}"), where ![k=3, 4,
5...](https://s0.wp.com/latex.php?latex=k%3D3%2C+4%2C+5...&bg=ffffff&fg=333333&s=0
"k=3, 4, 5..."). These converge to a triangle of the form ![\\approx
87.29^\\circ - 57.30^\\circ -
35.41^\\circ](https://s0.wp.com/latex.php?latex=%5Capprox+87.29%5E%5Ccirc+-+57.30%5E%5Ccirc+-+35.41%5E%5Ccirc&bg=ffffff&fg=333333&s=0
"\\approx 87.29^\\circ - 57.30^\\circ - 35.41^\\circ").
