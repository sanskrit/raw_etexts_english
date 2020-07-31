+++
title = "An apparition of Mordell"

+++
Consider the equation:

![y^2=x^3+k](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2Bk&bg=ffffff&fg=333333&s=0
"y^2=x^3+k")

where ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0
"k") is a positive integer 1, 2, 3… For a given
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k"),
will the above equation have integer solutions and, if yes, what are
they and how many?

We have heard of accounts of people receiving solutions to scientific or
mathematical problems in their dreams. We have never had any such dream;
in fact we get most of our scientific or mathematical insights when we
are either in a semi-awake but conscious reverie or at the peak of our
alertness. However, we on rare occasions we have had dreams which
present mathematical matters. On the night between the 18th and 19th of
Jan 2019 we had such dream. It was a long dream which featured human
faces we do not recall seeing in real life: we forgot their role in the
dream on waking. However, what we remembered of the dream was the
striking and repeated appearance of the above equation along with its
solutions for several
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
On waking, we distinctly recall seeing the cases of ![k=1, 8,
9](https://s0.wp.com/latex.php?latex=k%3D1%2C+8%2C+9&bg=ffffff&fg=333333&s=0
"k=1, 8, 9") though there were many more in the dream. There was a
degree of discomfort from the dream for in the groggy state of waking
from it we knew that some of these solutions had slipped away. So, at
the first chance we got, we played a bit with this equation this on our
laptop. We should mention that we have not previously played with this
equation and have given it little if any thought before: we glanced at
it when we had previously written about the cakravala but really did not
give it any further consideration then or thereafter. Hence, we were
charmed by its unexpected and strong appearance in our dream.

This equation is known as Mordell’s equation after the mathematician who
started studying it intensely about a century ago. The equation itself
was know before him to a French mathematician Bachet and is sometimes
given his name. It has apparently been widely studied by modern
mathematicians and they know a lot about it. As a mathematical layman we
are not presenting any of that discussion here but simply record below
our elementary exploration of it.

[![mordell\_fig1](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig1.png?w=573&h=573)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig1.png)

Figure 1.

These equations define a class of elliptic curves and by definition
given the square term they are symmetric about the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis (Figure 1). Since, we are here only looking at the real plane,
the curve is only defined starting from ![y=0,
x=-\\sqrt\[3\]{k}](https://s0.wp.com/latex.php?latex=y%3D0%2C+x%3D-%5Csqrt%5B3%5D%7Bk%7D&bg=ffffff&fg=333333&s=0
"y=0, x=-\\sqrt[3]{k}") where it cuts the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis. From there on it opens symmetrically towards
![\\infty](https://s0.wp.com/latex.php?latex=%5Cinfty&bg=ffffff&fg=333333&s=0
"\\infty") in the direction of the positive
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x").
So, essentially we are looking for the lattice points which lie on this
curve. Given the square term, we will get symmetric pairs of solutions
about the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis (Figure 1). In geometric terms, it might be viewed as the
problem of which squares and cubes with sides of integer units are
inter-convertible by the addition of
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
units.

Mordell had pointed out about a century ago that these equations might
have either no integer solutions or only a finite number of them. Let is
consider a concrete example with
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1"):
![y^2=x^3+1](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B1&bg=ffffff&fg=333333&s=0
"y^2=x^3+1"). One can get three trivial solutions right away: by setting
![x=-1](https://s0.wp.com/latex.php?latex=x%3D-1&bg=ffffff&fg=333333&s=0
"x=-1") we get
![y=0](https://s0.wp.com/latex.php?latex=y%3D0&bg=ffffff&fg=333333&s=0
"y=0"). Similarly, setting
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0
"x=0"), we get ![y=\\pm
1](https://s0.wp.com/latex.php?latex=y%3D%5Cpm+1&bg=ffffff&fg=333333&s=0
"y=\\pm 1"). Further, we see that if
![x=2](https://s0.wp.com/latex.php?latex=x%3D2&bg=ffffff&fg=333333&s=0
"x=2") we get ![y=\\pm
3](https://s0.wp.com/latex.php?latex=y%3D%5Cpm+3&bg=ffffff&fg=333333&s=0
"y=\\pm 3"). Thus, we can write the solutions as
![(x,y)](https://s0.wp.com/latex.php?latex=%28x%2Cy%29&bg=ffffff&fg=333333&s=0
"(x,y)") pairs: (-1,0); (0,1); (0, -1); (2,3); (2,-3): a total of 5
unique integer solutions. Can there be any more solutions than these? To
get an intuitive geometric feel for this we first observe how these
solutions sit on the curve (Figure 1). We notice that the 3 distinct
ones are on the same straight line (also applies to their mirror images
via a mirrored line). This is a important property of elliptic curves
(being cubic curves) that allows us to understand the situation better.

[![mordell\_fig2](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig2.png?w=490&h=788)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig2.png)Figure
2.

In Figure 2, we consider the curve
![y^2=x^3+1](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B1&bg=ffffff&fg=333333&s=0
"y^2=x^3+1") in greater detail. We observe that if we have two integer
solutions points
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")
and ![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0
"Q") and we connect them we get the third one
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1"). Thus, if we have two solutions, in this case the trivial ones,
we can easily find the third one by drawing a line through them and
seeing where it cuts the elliptic curve. The point where it cuts it
gives a further solution. We also see from the figure that joining
symmetric solutions like points
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q"),
![Q^\\prime](https://s0.wp.com/latex.php?latex=Q%5E%5Cprime&bg=ffffff&fg=333333&s=0
"Q^\\prime") will not yield any further solutions because the resultant
line will be parallel to the
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0
"y")-axis. Thus, we might get an additional solution only if the slope
of the line joining the 2 prior solutions is neither
![0](https://s0.wp.com/latex.php?latex=0&bg=ffffff&fg=333333&s=0 "0")
(coincident with the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis) nor
![\\infty](https://s0.wp.com/latex.php?latex=%5Cinfty&bg=ffffff&fg=333333&s=0
"\\infty") (parallel to
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0
"y")-axis). Hence, we may ask: now that we have
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1") can we get a further solution? We can see that joining
![Q^\\prime](https://s0.wp.com/latex.php?latex=Q%5E%5Cprime&bg=ffffff&fg=333333&s=0
"Q^\\prime") to
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1") yields a line that will never again cut the curve
![y^2=x^3+1](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B1&bg=ffffff&fg=333333&s=0
"y^2=x^3+1"). Thus, we can geometrically see that there can be no more
than the 5 above solutions we obtained.

In algebraic language the slope of the line joining the first two
solutions can be written as:

![m=\\dfrac{y\_P-y\_Q}{x\_P-x\_Q}](https://s0.wp.com/latex.php?latex=m%3D%5Cdfrac%7By_P-y_Q%7D%7Bx_P-x_Q%7D&bg=ffffff&fg=333333&s=0
"m=\\dfrac{y_P-y_Q}{x_P-x_Q}")

From this one can calculate the coordinates of the third point
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
as:

![x\_R=m^2-x\_P-x\_Q, \\;
y\_R=y\_P+m(x\_R-x\_P)](https://s0.wp.com/latex.php?latex=x_R%3Dm%5E2-x_P-x_Q%2C+%5C%3B+y_R%3Dy_P%2Bm%28x_R-x_P%29&bg=ffffff&fg=333333&s=0
"x_R=m^2-x_P-x_Q, \\; y_R=y_P+m(x_R-x_P)")

Thus, in Figure 2, if we were to join
![Q^\\prime](https://s0.wp.com/latex.php?latex=Q%5E%5Cprime&bg=ffffff&fg=333333&s=0
"Q^\\prime") to
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1") we have:  
![m=2](https://s0.wp.com/latex.php?latex=m%3D2&bg=ffffff&fg=333333&s=0
"m=2"); thus for the “new point” we get: ![x=4-0-2=2, \\;
y=-1+2(2-0)=3](https://s0.wp.com/latex.php?latex=x%3D4-0-2%3D2%2C+%5C%3B+y%3D-1%2B2%282-0%29%3D3&bg=ffffff&fg=333333&s=0
"x=4-0-2=2, \\; y=-1+2(2-0)=3").  
We simply get back
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1") indicating that there are no further integer solutions than the 5
we have.

One may also see a parallel between this procedure of obtaining a third
integer solution by joining two points and the process of obtaining a
composite number by multiplying two prime numbers. If we know the two
starting points it is easy to get the third but if we were to only know
the third point for a large number getting its precursors would be a
difficult task. This relates to the use of elliptic curves as an
alternative for primes in cryptography ([see our earlier note on the use
of prime numbers in the
same](https://manasataramgini.wordpress.com/2018/10/05/a-laymans-overview-of-the-arithmetic-of-encryption/)).

[](https://manasataramgini.wordpress.com/2019/01/22/an-apparition-of-mordell/mordell_fig3-1/)

![mordell\_fig3.1](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig3.1.png?w=349&h=599
"mordell_fig3.1")

[](https://manasataramgini.wordpress.com/2019/01/22/an-apparition-of-mordell/mordell_fig3-2/)

![mordell\_fig3.2](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig3.2.png?w=283&h=599
"mordell_fig3.2")

Figure 3.

In the case of
![y^2=x^3+1](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B1&bg=ffffff&fg=333333&s=0
"y^2=x^3+1") the joining procedure terminated after the first new point
we got but can there be cases where this yields more points? To see an
example of this let us consider
![y^2=x^3+9](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B9&bg=ffffff&fg=333333&s=0
"y^2=x^3+9"). One can get a trivial solution by simply placing
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0
"x=0") to get ![y=\\pm
3](https://s0.wp.com/latex.php?latex=y%3D%5Cpm+3&bg=ffffff&fg=333333&s=0
"y=\\pm 3"). Further, it is also easy to see that by taking
![x=-2](https://s0.wp.com/latex.php?latex=x%3D-2&bg=ffffff&fg=333333&s=0
"x=-2") we get ![y=\\pm
1](https://s0.wp.com/latex.php?latex=y%3D%5Cpm+1&bg=ffffff&fg=333333&s=0
"y=\\pm 1"). Thus, we get four points that we may call
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P"),
![P^\\prime](https://s0.wp.com/latex.php?latex=P%5E%5Cprime&bg=ffffff&fg=333333&s=0
"P^\\prime"),
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q"),
![Q^\\prime](https://s0.wp.com/latex.php?latex=Q%5E%5Cprime&bg=ffffff&fg=333333&s=0
"Q^\\prime")(Figure 3 panel 1). By joining
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P") to
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q") we
get a further point
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1"). Similarly, joining
![P^\\prime](https://s0.wp.com/latex.php?latex=P%5E%5Cprime&bg=ffffff&fg=333333&s=0
"P^\\prime") to
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q") or
![Q^\\prime](https://s0.wp.com/latex.php?latex=Q%5E%5Cprime&bg=ffffff&fg=333333&s=0
"Q^\\prime") to
![R\_1](https://s0.wp.com/latex.php?latex=R_1&bg=ffffff&fg=333333&s=0
"R_1") we get yet another point
![R\_2](https://s0.wp.com/latex.php?latex=R_2&bg=ffffff&fg=333333&s=0
"R_2"). We can likewise obtain their mirror images
![R^\\prime\_1](https://s0.wp.com/latex.php?latex=R%5E%5Cprime_1&bg=ffffff&fg=333333&s=0
"R^\\prime_1") and
![R^\\prime\_2](https://s0.wp.com/latex.php?latex=R%5E%5Cprime_2&bg=ffffff&fg=333333&s=0
"R^\\prime_2") (Figure 3). Finally, by joining
![R^\\prime\_1](https://s0.wp.com/latex.php?latex=R%5E%5Cprime_1&bg=ffffff&fg=333333&s=0
"R^\\prime_1") to
![R\_2](https://s0.wp.com/latex.php?latex=R_2&bg=ffffff&fg=333333&s=0
"R_2") we get yet another point
![R\_3](https://s0.wp.com/latex.php?latex=R_3&bg=ffffff&fg=333333&s=0
"R_3") and likewise we can get its mirror image point
![R^\\prime\_3](https://s0.wp.com/latex.php?latex=R%5E%5Cprime_3&bg=ffffff&fg=333333&s=0
"R^\\prime_3"). Beyond this the joining procedure yields no further
points. Thus, we are left with a total of 10 integer solutions for
![y^2=x^3+9](https://s0.wp.com/latex.php?latex=y%5E2%3Dx%5E3%2B9&bg=ffffff&fg=333333&s=0
"y^2=x^3+9"): (-2,1); (0,3); (3,6); (6,15); (40,253); (-2,-1); (0,-3);
(3,-6); (6,-15); (40,-253)

[![mordell\_fig4](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig4.png?w=605&h=649)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig4.png)Figure
4.

We can then systematically explore the solutions for all
![k=1..1000](https://s0.wp.com/latex.php?latex=k%3D1..1000&bg=ffffff&fg=333333&s=0
"k=1..1000"). If we plot all solutions and zoom in close to origin we
find a dense clustering of the solutions forming a swallow-tail like
structure whose outline is an integer approximation of an elliptic curve
(Figure 4).

[![mordell\_fig5](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig5.png?w=640)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig5.png)Figure
5.

We further find that some
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
have no integer solutions at all. There is a formal way to use modulos
and factorization to prove this for particular
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
The sequence of
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
for which no integer solutions exist can be computationally obtained and
goes as: 6, 7, 11, 13, 14, 20, 21, 23, 29, 32… Figure 5 shows how the
![n^{th}](https://s0.wp.com/latex.php?latex=n%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"n^{th}") term of this sequence grows. We find empirically that it
appears to be bounded by or at least approximated by the shape of a
scaled form of the logarithmic integral: ![y=\\pi^2
\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=y%3D%5Cpi%5E2+%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"y=\\pi^2 \\textrm{Li}(x)"). Whether this is true or what the
significance of it may be remains unknown to us.

[![mordell\_fig6](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig6.png?w=640)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig6.png)Figure
6.

We can also look at the sequence defined by the number of integer
solutions by
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
This is plotted in Figure 6 and remarkably shows a structure with no
obvious regularity. A closer look allows us to discern the following
patterns:  
1\) The most common number of solutions is 0. For
![k=1..1000](https://s0.wp.com/latex.php?latex=k%3D1..1000&bg=ffffff&fg=333333&s=0
"k=1..1000") this happens with a probability of 0.549, i.e. more than
half the times there are no integer solutions for Mordell’s equation.
The next most frequent number of solutions is 2. This happens with a
probability of 0.306 in this range. These are the cases when you just
have two symmetric solutions differing in the sign of their
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0 "y")
value.

2\) An odd number of solutions is obtained only when
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") is
a perfect cube. This is because only in this case we get the unpaired
solution of the form
![(-\\sqrt\[3\]{k},0)](https://s0.wp.com/latex.php?latex=%28-%5Csqrt%5B3%5D%7Bk%7D%2C0%29&bg=ffffff&fg=333333&s=0
"(-\\sqrt[3]{k},0)"). The cubic powers of 2 are particular rich in
solutions. E.g.
![k=2^9=512](https://s0.wp.com/latex.php?latex=k%3D2%5E9%3D512&bg=ffffff&fg=333333&s=0
"k=2^9=512") yields 9 solutions: (-8,0); (-7,13); (4,24); (8,32);
(184,2496); (-7,-13); (4,-24); (8,-32); (184,-2496).

3\) If ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0
"k") is a perfect square then for
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k"),
![k+1](https://s0.wp.com/latex.php?latex=k%2B1&bg=ffffff&fg=333333&s=0
"k+1") and
![k-1](https://s0.wp.com/latex.php?latex=k-1&bg=ffffff&fg=333333&s=0
"k-1") we will have at least 2 solutions: for
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") we
have
![(0,\\pm\\sqrt{k})](https://s0.wp.com/latex.php?latex=%280%2C%5Cpm%5Csqrt%7Bk%7D%29&bg=ffffff&fg=333333&s=0
"(0,\\pm\\sqrt{k})"); for
![k-1](https://s0.wp.com/latex.php?latex=k-1&bg=ffffff&fg=333333&s=0
"k-1") we have
![(1,\\pm\\sqrt{k})](https://s0.wp.com/latex.php?latex=%281%2C%5Cpm%5Csqrt%7Bk%7D%29&bg=ffffff&fg=333333&s=0
"(1,\\pm\\sqrt{k})"); for
![k+1](https://s0.wp.com/latex.php?latex=k%2B1&bg=ffffff&fg=333333&s=0
"k+1") we have
![(-1,\\pm\\sqrt{k})](https://s0.wp.com/latex.php?latex=%28-1%2C%5Cpm%5Csqrt%7Bk%7D%29&bg=ffffff&fg=333333&s=0
"(-1,\\pm\\sqrt{k})"). This would predict that, taken together, perfect
square ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0
"k") and their two immediate neighbors on either side would have a
higher average number of solutions than an equivalent number of
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
drawn at random in the same range. This is found to be the case
empirically (Figure 7).

[![mordell\_fig7](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig7.png?w=640)](https://manasataramgini.files.wordpress.com/2019/01/mordell_fig7.png)Figure
7.

The mean number of solutions of the square
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
and their immediate neighbors is 4.108696 (red line in Figure 7) as
opposed to the mean number of solutions of 1.522 (black line) for all
![k=1..1000](https://s0.wp.com/latex.php?latex=k%3D1..1000&bg=ffffff&fg=333333&s=0
"k=1..1000"). The former is 10.42 standard deviations away from the mean
for equivalently sized samples drawn randomly from
![k=1..1000](https://s0.wp.com/latex.php?latex=k%3D1..1000&bg=ffffff&fg=333333&s=0
"k=1..1000").

4\) Further some squares and square-neighbors show what we call a lucky
cubic conjunction (LCC), i.e. they generate a significantly larger
number of perfect squares when summed with cubes than other numbers. One
such square showing a LCC is
![15^2=225](https://s0.wp.com/latex.php?latex=15%5E2%3D225&bg=ffffff&fg=333333&s=0
"15^2=225"). It shows the record number of solutions (26) for
![k=1..1000](https://s0.wp.com/latex.php?latex=k%3D1..1000&bg=ffffff&fg=333333&s=0
"k=1..1000"): (-6,3); (-5,10); (0,15); (4,17); (6,21); (10,35); (15,60);
(30,165); (60,465); (180,2415); (336,6159); (351,6576); (720114,
611085363); (-6,-3); (-5,-10); (0,-15); (4,-17); (6,-21); (10,-35);
(15,-60); (30,-165); (60,-465); (180,-2415); (336,-6159); (351,-6576);
(720114, -611085363). One can right away see that:  
![-6^3+225=3^2\\\\ -5^3+225=10^2\\\\ 4^3+225=17^2\\\\ 6^3+225=21^2\\\\
10^3+225=35^2](https://s0.wp.com/latex.php?latex=-6%5E3%2B225%3D3%5E2%5C%5C+-5%5E3%2B225%3D10%5E2%5C%5C+4%5E3%2B225%3D17%5E2%5C%5C+6%5E3%2B225%3D21%5E2%5C%5C+10%5E3%2B225%3D35%5E2&bg=ffffff&fg=333333&s=0
"-6^3+225=3^2\\\\ -5^3+225=10^2\\\\ 4^3+225=17^2\\\\ 6^3+225=21^2\\\\ 10^3+225=35^2")
and so on.

A square neighbor with a LCC is
![17=16+1](https://s0.wp.com/latex.php?latex=17%3D16%2B1&bg=ffffff&fg=333333&s=0
"17=16+1") which has 8 cubic conjunctions leading to its 16 solutions:
(-2,3); (-1,4); (2,5); (4,9); (8,23); (43,282); (52,375); (5234,378661);
(-2,-3); (-1,-4); (2,-5); (4,-9); (8,-23); (43,-282); (52,-375);
(5234,-378661).

![1025=32^2+1](https://s0.wp.com/latex.php?latex=1025%3D32%5E2%2B1&bg=ffffff&fg=333333&s=0
"1025=32^2+1") is an even more monstrous square neighbor with a LCC
outside the range that we systematically explored. This number has a
whopping 16 cubic conjunctions giving rise to 32 solutions: (-10,5);
(-5,30); (-4,31); (-1,32); (4,33); (10,45); (20,95); (40,255); (50,355);
(64,513); (155,1930); (166,2139); (446,9419); (920,27905);
(3631,218796); (3730,227805); (-10,-5); (-5,-30); (-4,-31); (-1,-32);
(4,-33); (10,-45); (20,-95); (40,-255); (50,-355); (64,-513);
(155,-1930); (166,-2139); (446,-9419); (920,-27905); (3631,-218796);
(3730,-227805). In my computational exploration of these elliptic curves
I am yet to find any other that out does 1025.

5\) While
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
which are squares and square neighbors have at least 2 solutions
guaranteed, in principle a non-square or non-square neighbor number can
show a LCC and give rise to a large number of solutions. One such as
![k=297](https://s0.wp.com/latex.php?latex=k%3D297&bg=ffffff&fg=333333&s=0
"k=297") which shows 9 cubic conjunctions to give 18 solutions: (-6,9);
(-2,17); (3,18); (4,19); (12,45); (34,199); (48,333); (1362,50265);
(93844,28748141); (-6,-9); (-2,-17); (3,-18); (4,-19); (12,-45);
(34,-199); (48,-333); (1362,-50265); (93844,-28748141).
![k=873](https://s0.wp.com/latex.php?latex=k%3D873&bg=ffffff&fg=333333&s=0
"k=873") also shows a similar LCC, again with 9 cubic conjunctions.
Outside the range we systematically explored, we found
![k=2089](https://s0.wp.com/latex.php?latex=k%3D2089&bg=ffffff&fg=333333&s=0
"k=2089") to show a remarkable LCC with 14 conjunctions yielding 28
solutions: (-12,19); (-10,33); (-4,45); (3,46); (8,51); (18,89);
(60,467); (71,600); (80,717); (170,2217); (183,2476); (698,18441);
(9278,893679); (129968,46854861); (-12,-19); (-10,-33); (-4,-45);
(3,-46); (8,-51); (18,-89); (60,-467); (71,-600); (80,-717);
(170,-2217); (183,-2476); (698,-18441); (9278,-893679);
(129968,-46854861). This is the second highest number of solutions we
have seen for the Mordell’s equations we have studied.

A reader might explore these and see if he can find a
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
with bigger number of solution
