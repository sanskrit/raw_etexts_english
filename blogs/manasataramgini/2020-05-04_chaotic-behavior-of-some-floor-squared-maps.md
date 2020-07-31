+++
title = "Chaotic behavior of some floor-squared maps"

+++
Consider the one dimensional maps of the form:

![x\_{n+1}=\\dfrac{\\left(\\lfloor x\_n \\rfloor \\right)^2 +
\\{x\_n\\}^2
}{ax\_n}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B%5Cleft%28%5Clfloor+x_n+%5Crfloor+%5Cright%29%5E2+%2B+%5C%7Bx_n%5C%7D%5E2+%7D%7Bax_n%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{\\left(\\lfloor x_n \\rfloor \\right)^2 + \\{x_n\\}^2 }{ax_n}"),
where ![\\{x\_n\\}=x-\\lfloor x
\\rfloor](https://s0.wp.com/latex.php?latex=%5C%7Bx_n%5C%7D%3Dx-%5Clfloor+x+%5Crfloor&bg=ffffff&fg=333333&s=0
"\\{x_n\\}=x-\\lfloor x \\rfloor") is the fractional part of
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")

What will be evolution of a
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") under this map when
![a=2](https://s0.wp.com/latex.php?latex=a%3D2&bg=ffffff&fg=333333&s=0
"a=2") or
![a=3](https://s0.wp.com/latex.php?latex=a%3D3&bg=ffffff&fg=333333&s=0
"a=3")? We can see that for
![x\_0\>0](https://s0.wp.com/latex.php?latex=x_0%3E0&bg=ffffff&fg=333333&s=0
"x_0\>0") it will tend converge. However, the behavior is far more
interesting for
![x\_0\<0](https://s0.wp.com/latex.php?latex=x_0%3C0&bg=ffffff&fg=333333&s=0
"x_0\<0"): It turns out that in these cases the trajectory of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") exhibits chaotic behavior (Figure 1, 2, 3, 4).

[![floor\_square01a2\_ev](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_ev.png?w=640)](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_ev.png)Figure
1

Here,
![a=2](https://s0.wp.com/latex.php?latex=a%3D2&bg=ffffff&fg=333333&s=0
"a=2") and we use
![x\_0=-1.464](https://s0.wp.com/latex.php?latex=x_0%3D-1.464&bg=ffffff&fg=333333&s=0
"x_0=-1.464"); of course all other
![x\_0\<0](https://s0.wp.com/latex.php?latex=x_0%3C0&bg=ffffff&fg=333333&s=0
"x_0\<0") show comparable behavior (but the choice of this for
illustration
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") will become clear below). The evolution is plotted after
discarding the first few values of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n"). While the evolution of
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") under the map is chaotic it is not entirely random. There are
preferred zones and which
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") inhabits. This can be better visualized by plotting a histogram
of all the values of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") in the evolution under the map for 20000 iterations.

[![floor\_square01a2\_hist](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_hist.png?w=640)](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_hist.png)Figure
2

We can see that for any value of
![x\_0\<0](https://s0.wp.com/latex.php?latex=x_0%3C0&bg=ffffff&fg=333333&s=0
"x_0\<0") the iterates will be quickly pushed below -1. Further, we can
also see that once a value is ![-2.5 \\le x \\le
-1](https://s0.wp.com/latex.php?latex=-2.5+%5Cle+x+%5Cle+-1&bg=ffffff&fg=333333&s=0
"-2.5 \\le x \\le -1") it will remain orbiting within these bounds.
Thus, it settles into an attractor in this interval. However, we observe
that there is are 2 zones of exclusion in this interval. Even though we
initiate the mapping in the middle of the larger zone of exclusion
(which is why we chose
![x\_0=-1.464](https://s0.wp.com/latex.php?latex=x_0%3D-1.464&bg=ffffff&fg=333333&s=0
"x_0=-1.464")), we observe that
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") moves away from that zone and mostly keeps away from it. As it
oscillates between -1 and -2.5
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") repeatedly approaches the second zone of exclusion from either
side but gets repelled by it. How can we precisely determine these
repellors of the map? Those can be determined by solving the equation:

![2x^2=\\left(\\lfloor x \\rfloor \\right)^2+\\left(x-\\lfloor x
\\rfloor
\\right)^2](https://s0.wp.com/latex.php?latex=2x%5E2%3D%5Cleft%28%5Clfloor+x+%5Crfloor+%5Cright%29%5E2%2B%5Cleft%28x-%5Clfloor+x+%5Crfloor+%5Cright%29%5E2&bg=ffffff&fg=333333&s=0
"2x^2=\\left(\\lfloor x \\rfloor \\right)^2+\\left(x-\\lfloor x \\rfloor \\right)^2")

We have to solve such equations piecemeal due to the discontinuity of
the ![\\lfloor x
\\rfloor](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor&bg=ffffff&fg=333333&s=0
"\\lfloor x \\rfloor") function. Because of the interval within which
the attractor lies we have to only consider its solutions where
![\\lfloor x
\\rfloor=-2](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor%3D-2&bg=ffffff&fg=333333&s=0
"\\lfloor x \\rfloor=-2") and ![\\lfloor x
\\rfloor=-3](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor%3D-3&bg=ffffff&fg=333333&s=0
"\\lfloor x \\rfloor=-3"). By substituting these two values of the
floors in the above floor equation we get the two quadratics
![x^2-4x-8=0](https://s0.wp.com/latex.php?latex=x%5E2-4x-8%3D0&bg=ffffff&fg=333333&s=0
"x^2-4x-8=0") and
![x^2-6x-18=0](https://s0.wp.com/latex.php?latex=x%5E2-6x-18%3D0&bg=ffffff&fg=333333&s=0
"x^2-6x-18=0"), whose roots will yield the repellors. The solutions of
the first are ![2 \\pm
2\\sqrt{3}](https://s0.wp.com/latex.php?latex=2+%5Cpm+2%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"2 \\pm 2\\sqrt{3}"). Since only the negative root is within interval of
for our attractor, we have one repellor as ![r\_1=2 -
2\\sqrt{3}](https://s0.wp.com/latex.php?latex=r_1%3D2+-+2%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"r_1=2 - 2\\sqrt{3}"). Similarly, from the second equation we get the
second repellor to be ![r\_2=3 -
3\\sqrt{3}](https://s0.wp.com/latex.php?latex=r_2%3D3+-+3%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"r_2=3 - 3\\sqrt{3}"). These are shown as green lines in the above
figures. One can see we initiated the map close to
![r\_1](https://s0.wp.com/latex.php?latex=r_1&bg=ffffff&fg=333333&s=0
"r_1") and saw how it was repelled. However, if ![x\_0=2 - 2\\sqrt{3},
x\_0=3 -
3\\sqrt{3}](https://s0.wp.com/latex.php?latex=x_0%3D2+-+2%5Csqrt%7B3%7D%2C+x_0%3D3+-+3%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"x_0=2 - 2\\sqrt{3}, x_0=3 - 3\\sqrt{3}") then
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") remains fixed. Thus, while ![r\_1,
r\_2](https://s0.wp.com/latex.php?latex=r_1%2C+r_2&bg=ffffff&fg=333333&s=0
"r_1, r_2") repel
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") in their vicinity they are fixed points on the map (green
points).

[![floor\_square01a3\_ev](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a3_ev.png?w=640)](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a3_ev.png)Figure
3

Here,
![a=3](https://s0.wp.com/latex.php?latex=a%3D3&bg=ffffff&fg=333333&s=0
"a=3") and we initiate the mapping with
![x\_0=-0.618](https://s0.wp.com/latex.php?latex=x_0%3D-0.618&bg=ffffff&fg=333333&s=0
"x_0=-0.618"). We can see that in this case for all ![x\_0 \<
0](https://s0.wp.com/latex.php?latex=x_0+%3C+0&bg=ffffff&fg=333333&s=0
"x_0 \< 0") the iterates with be pushed below
![-\\tfrac{1}{3}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"-\\tfrac{1}{3}"). Further, once ![-\\tfrac{5}{3} \\le x\_n \\le
-\\tfrac{1}{3}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B5%7D%7B3%7D+%5Cle+x_n+%5Cle+-%5Ctfrac%7B1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"-\\tfrac{5}{3} \\le x_n \\le -\\tfrac{1}{3}") we can see that
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") will be trapped in an orbit within this interval. As in the above
case, in the example illustrated in Figure 3, after briefly oscillating
close to
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0"),
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") gets repelled away from it and that region is an exclusion zone
for
![x\_0\<0](https://s0.wp.com/latex.php?latex=x_0%3C0&bg=ffffff&fg=333333&s=0
"x_0\<0"). However, unlike in the above case we do not have a clear
second exclusion zone here (Figure 4).

[![floor\_square01a3\_hist](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a3_hist.png?w=640)](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a3_hist.png)Figure
4

Instead, we see that there are repeated attempts to come close to a
certain line followed by repulsion away from it to flanking bands. As a
result we do not get the second exclusion zone but have a saddle-like
distribution around the line that is repeatedly approached. As in the
above case to identify the primary repellor and the secondary value that
behaves like a pseudo-attractor and also a repellor we need to solve the
floor equation:

![3x^2=\\left(\\lfloor x \\rfloor \\right)^2+\\left(x-\\lfloor x
\\rfloor
\\right)^2](https://s0.wp.com/latex.php?latex=3x%5E2%3D%5Cleft%28%5Clfloor+x+%5Crfloor+%5Cright%29%5E2%2B%5Cleft%28x-%5Clfloor+x+%5Crfloor+%5Cright%29%5E2&bg=ffffff&fg=333333&s=0
"3x^2=\\left(\\lfloor x \\rfloor \\right)^2+\\left(x-\\lfloor x \\rfloor \\right)^2")

Again we solve it piecemeal. This time given the interval of our
attractor ![\[-\\tfrac{5}{3},
-\\tfrac{1}{3}\]](https://s0.wp.com/latex.php?latex=%5B-%5Ctfrac%7B5%7D%7B3%7D%2C+-%5Ctfrac%7B1%7D%7B3%7D%5D&bg=ffffff&fg=333333&s=0
"[-\\tfrac{5}{3}, -\\tfrac{1}{3}]") we have to consider only ![\\lfloor
x \\rfloor=
-1](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor%3D+-1&bg=ffffff&fg=333333&s=0
"\\lfloor x \\rfloor= -1") and ![\\lfloor x \\rfloor=
-2](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor%3D+-2&bg=ffffff&fg=333333&s=0
"\\lfloor x \\rfloor= -2"). By substituting the first floor value in the
above equation we get the quadratic
![x^2-x-1=0](https://s0.wp.com/latex.php?latex=x%5E2-x-1%3D0&bg=ffffff&fg=333333&s=0
"x^2-x-1=0") whose solutions are ![\\phi,
-\\tfrac{1}{\\phi}](https://s0.wp.com/latex.php?latex=%5Cphi%2C+-%5Ctfrac%7B1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"\\phi, -\\tfrac{1}{\\phi}"), where
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") is the Golden Ratio. Taking only the negative value that is in
the interval which matters for us, we get the repellor of this map to be
![r\_1=\\tfrac{-1}{\\phi}](https://s0.wp.com/latex.php?latex=r_1%3D%5Ctfrac%7B-1%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"r_1=\\tfrac{-1}{\\phi}"). With the next floor we get the quadratic
![x^2-2x-4=0](https://s0.wp.com/latex.php?latex=x%5E2-2x-4%3D0&bg=ffffff&fg=333333&s=0
"x^2-2x-4=0") with roots ![2 \\phi,
-\\tfrac{2}{\\phi}](https://s0.wp.com/latex.php?latex=2+%5Cphi%2C+-%5Ctfrac%7B2%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"2 \\phi, -\\tfrac{2}{\\phi}"). The second of these give us
![r\_2=-\\tfrac{2}{\\phi}](https://s0.wp.com/latex.php?latex=r_2%3D-%5Ctfrac%7B2%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"r_2=-\\tfrac{2}{\\phi}") the pseudo-attractor-repellor. This
pseudo-attractor-repellor is like the superficially alluring woman who
draws you but is a repellor you when you get too close. As in the above
case ![r\_1,
r\_2](https://s0.wp.com/latex.php?latex=r_1%2C+r_2&bg=ffffff&fg=333333&s=0
"r_1, r_2") are also fixed points of the map.

Finally, we can investigate the evolution of closely separated
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") to see how closely they parallel each other (Figure 5).

[![floor\_square01a2\_evcomp](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_evcomp.png?w=640)](https://manasataramgini.files.wordpress.com/2020/05/floor_square01a2_evcomp.png)Figure
5

Here we compare the evolution of
![x\_0=-0.1464](https://s0.wp.com/latex.php?latex=x_0%3D-0.1464&bg=ffffff&fg=333333&s=0
"x_0=-0.1464") and
![x\_0=-0.1465](https://s0.wp.com/latex.php?latex=x_0%3D-0.1465&bg=ffffff&fg=333333&s=0
"x_0=-0.1465") under the first map. We observe that while they are
statistically the same in behavior the actual trajectories rapidly
diverge. This is a hall mark of chaotic behavior.
