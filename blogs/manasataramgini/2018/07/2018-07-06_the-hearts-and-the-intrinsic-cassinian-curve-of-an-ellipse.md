+++
title = "The hearts and the intrinsic Cassinian curve of an ellipse"

+++
**Introduction**

This investigation began with our exploration of pedal curves during the
vacation following our university entrance exams in the days of our
youth. It led to us discovering for ourselves certain interesting
heart-shaped curves, which are distinct from the well-known limaçon of
Etienne Pascal and its special case the cardioid. It also led us to find
the intrinsic relationship between the ellipse and the Cassinian curve
that is associated with every ellipse. We detail here those observations
with the hindsight of multiple decades and the availability of excellent
modern geometric visualization software (in this case Geogebra) since
the days of our paper and pencil explorations (However, even then we had
an excellent set of ellipse and circle templates that our father had
gifted us and also an ellipse drawing tool which we had made inspired by
the yavanācārya Proclus). We first lay the ground work with some basic
results and concepts that provide the necessary background before
delving into the heart of the topic under discussion.

**The eccentric circles theorem**

*Given a circle and a point inside it, the locus of the midpoint of the
segment joining the said point to a moving point on the circle is
another circle with radius half that of the given circle and with its
center as midpoint of the given point and the center of the given
circle.*

[![ellipse\_excentric\_circle\_Fig1](https://manasataramgini.files.wordpress.com/2018/07/ellipse_excentric_circle_fig1.png?w=505&h=473)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_excentric_circle_fig1.png)Figure
1

Let
![(x,y)](https://s0.wp.com/latex.php?latex=%28x%2Cy%29&bg=ffffff&fg=333333&s=0
"(x,y)") be the coordinates of the point
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P") on
the given circle with center at origin
![O](https://s0.wp.com/latex.php?latex=O&bg=ffffff&fg=333333&s=0 "O")
(Figure 1) and radius
![2a](https://s0.wp.com/latex.php?latex=2a&bg=ffffff&fg=333333&s=0
"2a"). The coordinates of the given point are ![F\_1=(0,
2c)](https://s0.wp.com/latex.php?latex=F_1%3D%280%2C+2c%29&bg=ffffff&fg=333333&s=0
"F_1=(0, 2c)"). Let the coordinates of the midpoint
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0 "M") of
the segment
![\\overline{F\_1P}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1P%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1P}") be
![(x\_1,y\_1)](https://s0.wp.com/latex.php?latex=%28x_1%2Cy_1%29&bg=ffffff&fg=333333&s=0
"(x_1,y_1)"). From Figure 1 it is clear that:

![x\_1=\\dfrac{x+2c}{2},
y\_1=\\dfrac{y}{2}](https://s0.wp.com/latex.php?latex=x_1%3D%5Cdfrac%7Bx%2B2c%7D%7B2%7D%2C+y_1%3D%5Cdfrac%7By%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x_1=\\dfrac{x+2c}{2}, y_1=\\dfrac{y}{2}"); thus ![x=2x\_1-2c,
y=2y\_1](https://s0.wp.com/latex.php?latex=x%3D2x_1-2c%2C+y%3D2y_1&bg=ffffff&fg=333333&s=0
"x=2x_1-2c, y=2y_1").

By plugging these into the equation of the given circle
![x^2+y^2=4a^2](https://s0.wp.com/latex.php?latex=x%5E2%2By%5E2%3D4a%5E2&bg=ffffff&fg=333333&s=0
"x^2+y^2=4a^2") we get:

![4x\_1^2-8cx\_1+4c^2+4y\_1^2=4a^2](https://s0.wp.com/latex.php?latex=4x_1%5E2-8cx_1%2B4c%5E2%2B4y_1%5E2%3D4a%5E2&bg=ffffff&fg=333333&s=0
"4x_1^2-8cx_1+4c^2+4y_1^2=4a^2")

![x\_1^2-2cx+c^2+y\_1^2=a^2](https://s0.wp.com/latex.php?latex=x_1%5E2-2cx%2Bc%5E2%2By_1%5E2%3Da%5E2&bg=ffffff&fg=333333&s=0
"x_1^2-2cx+c^2+y_1^2=a^2")

![\\therefore (x-c)^2+y^2=a^2 \\rightarrow
\\textrm{Locus}(M)](https://s0.wp.com/latex.php?latex=%5Ctherefore+%28x-c%29%5E2%2By%5E2%3Da%5E2+%5Crightarrow+%5Ctextrm%7BLocus%7D%28M%29&bg=ffffff&fg=333333&s=0
"\\therefore (x-c)^2+y^2=a^2 \\rightarrow \\textrm{Locus}(M)")

Thus, the locus of
![M](https://s0.wp.com/latex.php?latex=M&bg=ffffff&fg=333333&s=0 "M") is
a circle with
![A=(0,c)](https://s0.wp.com/latex.php?latex=A%3D%280%2Cc%29&bg=ffffff&fg=333333&s=0
"A=(0,c)") as center and radius of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"):
![Q.E.D](https://s0.wp.com/latex.php?latex=Q.E.D&bg=ffffff&fg=333333&s=0
"Q.E.D").

**The ellipse**

*Given a line
![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0 "d")
and a point
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
outside it, what will be the locus of all points such that the ratio of
their distances from
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
and ![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0
"d") respectively is a given constant value
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c")?*

[![ellipse\_conics\_Fig2](https://manasataramgini.files.wordpress.com/2018/07/ellipse_conics_fig2.png?w=640)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_conics_fig2.png)Figure
2

From the solution shown in figure we get the equation of this locus to
be:

![x^2+(1-e\_c^2)y^2-2h(1+e\_c^2)y+(1-e\_c^2)h^2=0](https://s0.wp.com/latex.php?latex=x%5E2%2B%281-e_c%5E2%29y%5E2-2h%281%2Be_c%5E2%29y%2B%281-e_c%5E2%29h%5E2%3D0&bg=ffffff&fg=333333&s=0
"x^2+(1-e_c^2)y^2-2h(1+e_c^2)y+(1-e_c^2)h^2=0")

Being a quadratic curve it will be a conic. Specifically, when
![e\_c\<1](https://s0.wp.com/latex.php?latex=e_c%3C1&bg=ffffff&fg=333333&s=0
"e_c\<1") it is an ellipse; when
![e\_c\>1](https://s0.wp.com/latex.php?latex=e_c%3E1&bg=ffffff&fg=333333&s=0
"e_c\>1") it is a hyperbola and when
![e\_c=1](https://s0.wp.com/latex.php?latex=e_c%3D1&bg=ffffff&fg=333333&s=0
"e_c=1") it is a parabola. This relates to why these curves are called
conic sections. We can see that the distance from point
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
can be represented by the surface of an infinite bicone with vertex at
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F").
The distance from line
![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0 "d")
can be represented by a plane containing
![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0 "d").
The given ratio
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c") specifies the inclination of this plane such that the angle by
which the plane is inclined is
![\\theta=\\textrm{arctan}(e\_c)](https://s0.wp.com/latex.php?latex=%5Ctheta%3D%5Ctextrm%7Barctan%7D%28e_c%29&bg=ffffff&fg=333333&s=0
"\\theta=\\textrm{arctan}(e_c)"). The intersection of this plane and the
bicone generates the conic section, which when projected on the
![xy](https://s0.wp.com/latex.php?latex=xy&bg=ffffff&fg=333333&s=0 "xy")
plane appears as the conic curve specified by the above equation (Figure
3).

[![ellipse\_conics\_Fig3](https://manasataramgini.files.wordpress.com/2018/07/ellipse_conics_fig3.png?w=655&h=428)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_conics_fig3.png)Figure
3

Thus, when the inclination of the plane is less than
![\\pi/4](https://s0.wp.com/latex.php?latex=%5Cpi%2F4&bg=ffffff&fg=333333&s=0
"\\pi/4") it is an ellipse. When it is exactly
![\\pi/4](https://s0.wp.com/latex.php?latex=%5Cpi%2F4&bg=ffffff&fg=333333&s=0
"\\pi/4") it is a parabola. When it is between
![\\pi/4](https://s0.wp.com/latex.php?latex=%5Cpi%2F4&bg=ffffff&fg=333333&s=0
"\\pi/4") and
![\\pi/2](https://s0.wp.com/latex.php?latex=%5Cpi%2F2&bg=ffffff&fg=333333&s=0
"\\pi/2") we get a hyperbola. Corresponding to this are the Greek terms
ellipse: less than; para: equal; hyper: greater than. This number
![e\_c=\\tan(\\theta)](https://s0.wp.com/latex.php?latex=e_c%3D%5Ctan%28%5Ctheta%29&bg=ffffff&fg=333333&s=0
"e_c=\\tan(\\theta)") (where
![\\theta](https://s0.wp.com/latex.php?latex=%5Ctheta&bg=ffffff&fg=333333&s=0
"\\theta") is the angle of inclination of the generating plane) is the
eccentricity of the conic and
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F") is
a focus of the conic.

By definition the bipolar equation of an ellipse is ![r\_1+
r\_2=2a](https://s0.wp.com/latex.php?latex=r_1%2B+r_2%3D2a&bg=ffffff&fg=333333&s=0
"r_1+ r_2=2a"). Here,
![r\_1,r\_2](https://s0.wp.com/latex.php?latex=r_1%2Cr_2&bg=ffffff&fg=333333&s=0
"r_1,r_2") are the distances of a point on the ellipse from the two foci
of the ellipse ![F\_1,
F\_2](https://s0.wp.com/latex.php?latex=F_1%2C+F_2&bg=ffffff&fg=333333&s=0
"F_1, F_2").
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") is
the semimajor axis of the ellipse.
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") is one of the foci of the ellipse ( for instance, as determined
by the construction in Figure 2 and 3) then the second focus
![F\_2](https://s0.wp.com/latex.php?latex=F_2&bg=ffffff&fg=333333&s=0
"F_2") is at a distance of
![2c](https://s0.wp.com/latex.php?latex=2c&bg=ffffff&fg=333333&s=0 "2c")
from
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") along the major axis of the ellipse. ![c= e\_c\\cdot
a](https://s0.wp.com/latex.php?latex=c%3D+e_c%5Ccdot+a&bg=ffffff&fg=333333&s=0
"c= e_c\\cdot a"). Further, it is easy to see that
![a^2-c^2=b^2](https://s0.wp.com/latex.php?latex=a%5E2-c%5E2%3Db%5E2&bg=ffffff&fg=333333&s=0
"a^2-c^2=b^2"), where
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b") is
the semiminor axis of the ellipse.

**The eccentric circles of an ellipse**

*Given an ellipse and a point
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")
moving on it, 1) what is the locus of the foot of the perpendicular
dropped from a focus of the ellipse to the tangent at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")?
(i.e. locus of the intersection of the tangent at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")
and the line perpendicular to it from one of the foci. 2) What is the
locus of the reflection of one of the foci on the tangent drawn to the
ellipse at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").*

[![ellipse\_excentric\_circles\_Fig4](https://manasataramgini.files.wordpress.com/2018/07/ellipse_excentric_circles_fig4.png?w=547&h=472)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_excentric_circles_fig4.png)Figure
4

From Figure 4 it is clear that the ![\\triangle F\_1QP \\cong \\triangle
PQR](https://s0.wp.com/latex.php?latex=%5Ctriangle+F_1QP+%5Ccong+%5Ctriangle+PQR&bg=ffffff&fg=333333&s=0
"\\triangle F_1QP \\cong \\triangle PQR") by the SAS test. Hence,
![\\overline{F\_1P}=\\overline{PR}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1P%7D%3D%5Coverline%7BPR%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1P}=\\overline{PR}"). By definition of ellipse
![\\overline{F\_1P}+\\overline{F\_2P}=2a](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1P%7D%2B%5Coverline%7BF_2P%7D%3D2a&bg=ffffff&fg=333333&s=0
"\\overline{F_1P}+\\overline{F_2P}=2a"). Thus,
![\\overline{PR}+\\overline{F\_2P}=\\overline{F\_2R}=2a](https://s0.wp.com/latex.php?latex=%5Coverline%7BPR%7D%2B%5Coverline%7BF_2P%7D%3D%5Coverline%7BF_2R%7D%3D2a&bg=ffffff&fg=333333&s=0
"\\overline{PR}+\\overline{F_2P}=\\overline{F_2R}=2a"). Therefore, the
locus of
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R") is
a circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") with center
![F\_2](https://s0.wp.com/latex.php?latex=F_2&bg=ffffff&fg=333333&s=0
"F_2") and radius
![2a](https://s0.wp.com/latex.php?latex=2a&bg=ffffff&fg=333333&s=0
"2a").

It is clear from the definition of
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
that ![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0
"Q") is the midpoint (Figure 4) of
![\\overline{F\_1R}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1R%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1R}"). Therefore, by the eccentric circle theorem applied
to the above-defined circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") the locus of
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q") is
a circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") with radius
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and center as the midpoint of ![F\_1,
F\_2](https://s0.wp.com/latex.php?latex=F_1%2C+F_2&bg=ffffff&fg=333333&s=0
"F_1, F_2"), which is the center of the ellipse. Thus,
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") is the solution to the problem of the pedal curve of an ellipse
with the pedal point as one of the foci.
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") is also the circumcircle of the given ellipse. These two circles
![c\_1,
c\_2](https://s0.wp.com/latex.php?latex=c_1%2C+c_2&bg=ffffff&fg=333333&s=0
"c_1, c_2") are the two eccentric circles of an ellipse.

**Construction of an ellipse using its eccentric circles**

Since the radii of both eccentric circles of an ellipse are defined by
only the semimajor axis of the ellipse, the whole family of ellipses
with the same semimajor axis will share the radii of the eccentric
circles. Hence, we additionally need to define the foci to construct the
ellipse given one or both of its eccentric circles.

[![ellipse\_from\_c2\_Fig5](https://manasataramgini.files.wordpress.com/2018/07/ellipse_from_c2_fig5.png?w=632&h=443)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_from_c2_fig5.png)Figure
5

If we are given just the circumcircle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") and a focus
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") then we can construct the required ellipse thus (Figure 5):
Define focus
![F\_1=(-c,0)](https://s0.wp.com/latex.php?latex=F_1%3D%28-c%2C0%29&bg=ffffff&fg=333333&s=0
"F_1=(-c,0)"). Draw a segment connecting
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") to
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P"), a
point moving on the circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2"). Draw a perpendicular line to
![\\overline{F\_1P}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1P%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1P}") at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").
The envelop of all such lines would be our required ellipse.

[![ellipse\_from\_c1c2\_Fig6](https://manasataramgini.files.wordpress.com/2018/07/ellipse_from_c1c2_fig6.png?w=636&h=505)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_from_c1c2_fig6.png)Figure
6

If we are given both eccentric circles
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") and
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") then the construction is a little more involved but has
interesting consequences (Figure 6). First define the foci
![F\_1=(-c,0),
F\_2=(c,0)](https://s0.wp.com/latex.php?latex=F_1%3D%28-c%2C0%29%2C+F_2%3D%28c%2C0%29&bg=ffffff&fg=333333&s=0
"F_1=(-c,0), F_2=(c,0)"). Then draw circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") with origin as center and radius
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
Draw circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") with
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") as center and radius
![2a](https://s0.wp.com/latex.php?latex=2a&bg=ffffff&fg=333333&s=0
"2a"). Let
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P") be
a moving point on circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2"). Join
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") to
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").
Draw a line
![t](https://s0.wp.com/latex.php?latex=t&bg=ffffff&fg=333333&s=0 "t")
perpendicular to segment
![\\overline{F\_1P}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1P%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1P}") at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").
With ![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0
"P") as center draw a circle which passes through
![F\_2](https://s0.wp.com/latex.php?latex=F_2&bg=ffffff&fg=333333&s=0
"F_2"). This circle cuts the circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") at points
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
and ![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0
"B"). Join
![F\_1](https://s0.wp.com/latex.php?latex=F_1&bg=ffffff&fg=333333&s=0
"F_1") to both
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
and ![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0
"B"). The points where segments
![\\overline{F\_1A}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1A%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1A}") and
![\\overline{F\_1B}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_1B%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_1B}") intersect line
![t](https://s0.wp.com/latex.php?latex=t&bg=ffffff&fg=333333&s=0 "t")
are ![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0
"C") and
![D](https://s0.wp.com/latex.php?latex=D&bg=ffffff&fg=333333&s=0 "D")
(Figure 6). The locus of points
![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0 "C")
and ![D](https://s0.wp.com/latex.php?latex=D&bg=ffffff&fg=333333&s=0
"D") as point
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")
moves on
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") gives us the required ellipse (blue in Figure 6).

**The ellipse hearts**

Notably the above construction of an ellipse using both the eccentric
circles yields a companion curve (purple in Figure 6). It usually
assumes a heart-shaped form with a dimple or a cusp that superficially
resembles the limaçon of Etienne Pascal. However, a closer examination
reveals that it is not that curve and has a distinct shape; we term it
the ellipse-heart because every given ellipse will have its unique
ellipse-heart. From Figure 6 we can also see that the ellipse-heart can
be defined for a given ellipse as the locus of the reflection of the
point of tangency on the pedal line from one of the foci. Like the
Descartes oval and its dual the limaçon, this ellipse-heart can be seen
as the dual of the ellipse. Its shape can be described by the
eccentricity
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c") of the ellipse. For high eccentricity it shows a prominent dimple
that tends towards a cusp as ![e\_c \\to
1](https://s0.wp.com/latex.php?latex=e_c+%5Cto+1&bg=ffffff&fg=333333&s=0
"e_c \\to 1"). For
![e\_c\<\\tfrac{1}{2\\sqrt{3}}](https://s0.wp.com/latex.php?latex=e_c%3C%5Ctfrac%7B1%7D%7B2%5Csqrt%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"e_c\<\\tfrac{1}{2\\sqrt{3}}") it becomes a convex oval that becomes a
circle identical with the ellipse for
![e\_c=0](https://s0.wp.com/latex.php?latex=e_c%3D0&bg=ffffff&fg=333333&s=0
"e_c=0").

In order to derive the equation of this curve, we note that by the above
definition of the eccentric circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") we have
![\\overline{AC}=\\overline{F\_2D}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAC%7D%3D%5Coverline%7BF_2D%7D&bg=ffffff&fg=333333&s=0
"\\overline{AC}=\\overline{F_2D}"). We also observe (Figure 6) that the
ellipse-heart is obtained by subtracting
![\\overline{F\_2D}](https://s0.wp.com/latex.php?latex=%5Coverline%7BF_2D%7D&bg=ffffff&fg=333333&s=0
"\\overline{F_2D}") from the radius vector of the eccentric circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1"). Now,
![F\_2D](https://s0.wp.com/latex.php?latex=F_2D&bg=ffffff&fg=333333&s=0
"F_2D") is itself the radial vector of the ellipse with the focus as the
pole. This allows us to define the polar equation of the ellipse using
the focus as a pole as is done in celestial mechanics, where one
star/planet is at the focus and another star/planet/moon is moving in an
elliptical orbit around it. This equation of the ellipse is:

![r=\\dfrac{\\left(a^2-c^2\\right)}{a\\pm
c\\cdot\\cos\\left(\\theta\\right)}](https://s0.wp.com/latex.php?latex=r%3D%5Cdfrac%7B%5Cleft%28a%5E2-c%5E2%5Cright%29%7D%7Ba%5Cpm+c%5Ccdot%5Ccos%5Cleft%28%5Ctheta%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"r=\\dfrac{\\left(a^2-c^2\\right)}{a\\pm c\\cdot\\cos\\left(\\theta\\right)}")

Here the radial
![\\angle{\\theta}](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Ctheta%7D&bg=ffffff&fg=333333&s=0
"\\angle{\\theta}") is known as the “true anomaly”, as in the definition
of elliptical orbits in the planetary theories of Nīlakaṇṭha Somayājin
and Johannes Kepler. Given that ![\\overline{AC} \\; || \\;
\\overline{F\_2D}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAC%7D+%5C%3B+%7C%7C+%5C%3B+%5Coverline%7BF_2D%7D&bg=ffffff&fg=333333&s=0
"\\overline{AC} \\; || \\; \\overline{F_2D}") and in the opposite
direction we can derive the equation of the ellipse-heart by subtracting
the above radial vector from
![2a](https://s0.wp.com/latex.php?latex=2a&bg=ffffff&fg=333333&s=0
"2a"), the radial vector of the circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") with the appropriate signs. Thus, if the ellipse is:

![r=\\dfrac{\\left(a^2-c^2\\right)}{a-
c\\cdot\\cos\\left(\\theta\\right)}](https://s0.wp.com/latex.php?latex=r%3D%5Cdfrac%7B%5Cleft%28a%5E2-c%5E2%5Cright%29%7D%7Ba-+c%5Ccdot%5Ccos%5Cleft%28%5Ctheta%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"r=\\dfrac{\\left(a^2-c^2\\right)}{a- c\\cdot\\cos\\left(\\theta\\right)}"),

then its ellipse-heart is:

![r=2a-\\dfrac{\\left(a^2-c^2\\right)}{a+c\\cdot\\cos\\left(\\theta\\right)}](https://s0.wp.com/latex.php?latex=r%3D2a-%5Cdfrac%7B%5Cleft%28a%5E2-c%5E2%5Cright%29%7D%7Ba%2Bc%5Ccdot%5Ccos%5Cleft%28%5Ctheta%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"r=2a-\\dfrac{\\left(a^2-c^2\\right)}{a+c\\cdot\\cos\\left(\\theta\\right)}")

While the square of the above equation has an indefinite integral,
evaluating it is a bit complicated. Hence, we resorted to the expediency
of numerically integrating it and arrived at the area of the ellipse
heart
![A\_h](https://s0.wp.com/latex.php?latex=A_h&bg=ffffff&fg=333333&s=0
"A_h") to be:

![A\_h=\\pi
(4a^2-3ab)](https://s0.wp.com/latex.php?latex=A_h%3D%5Cpi+%284a%5E2-3ab%29&bg=ffffff&fg=333333&s=0
"A_h=\\pi (4a^2-3ab)"), where
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and ![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0
"b") are respectively the semimajor and semiminor axis of the ellipse.

Thus, ![A\_h=
A\_{c\_1}-3A\_e](https://s0.wp.com/latex.php?latex=A_h%3D+A_%7Bc_1%7D-3A_e&bg=ffffff&fg=333333&s=0
"A_h= A_{c_1}-3A_e"), where
![A\_{c\_1}](https://s0.wp.com/latex.php?latex=A_%7Bc_1%7D&bg=ffffff&fg=333333&s=0
"A_{c_1}") is the area of the eccentric circle
![c\_1](https://s0.wp.com/latex.php?latex=c_1&bg=ffffff&fg=333333&s=0
"c_1") and
![A\_e](https://s0.wp.com/latex.php?latex=A_e&bg=ffffff&fg=333333&s=0
"A_e") that of the ellipse. Further we also get:

![\\dfrac{A\_h}{A\_e}=4\\dfrac{a}{b}-3](https://s0.wp.com/latex.php?latex=%5Cdfrac%7BA_h%7D%7BA_e%7D%3D4%5Cdfrac%7Ba%7D%7Bb%7D-3&bg=ffffff&fg=333333&s=0
"\\dfrac{A_h}{A_e}=4\\dfrac{a}{b}-3")

Thus, when ![\\tfrac{a}{b}=\\tfrac{5}{4}, \\;
e\_c=\\tfrac{3}{5}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Ba%7D%7Bb%7D%3D%5Ctfrac%7B5%7D%7B4%7D%2C+%5C%3B+e_c%3D%5Ctfrac%7B3%7D%7B5%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{a}{b}=\\tfrac{5}{4}, \\; e_c=\\tfrac{3}{5}"), i.e. the three
ellipse parameters form a 3-4-5 right triangle then ![A\_h=2\\cdot
A\_e](https://s0.wp.com/latex.php?latex=A_h%3D2%5Ccdot+A_e&bg=ffffff&fg=333333&s=0
"A_h=2\\cdot A_e"). This is a beautiful configuration (Figure 7).
Finally, inspired by the above equation for the ellipse-heart we can
also define a second ellipse-heart using parametric equations as:

![x=\\left(2a-\\dfrac{\\left(a^2-c^2\\right)}{a+c\\cos\\left(t\\right)}\\right)\\cdot\\cos\\left(t\\right),
y=\\left(2a-\\dfrac{\\left(a^2-c^2\\right)}{a-c\\cos\\left(t\\right)}\\right)\\cdot\\sin\\left(t\\right)](https://s0.wp.com/latex.php?latex=x%3D%5Cleft%282a-%5Cdfrac%7B%5Cleft%28a%5E2-c%5E2%5Cright%29%7D%7Ba%2Bc%5Ccos%5Cleft%28t%5Cright%29%7D%5Cright%29%5Ccdot%5Ccos%5Cleft%28t%5Cright%29%2C+y%3D%5Cleft%282a-%5Cdfrac%7B%5Cleft%28a%5E2-c%5E2%5Cright%29%7D%7Ba-c%5Ccos%5Cleft%28t%5Cright%29%7D%5Cright%29%5Ccdot%5Csin%5Cleft%28t%5Cright%29&bg=ffffff&fg=333333&s=0
"x=\\left(2a-\\dfrac{\\left(a^2-c^2\\right)}{a+c\\cos\\left(t\\right)}\\right)\\cdot\\cos\\left(t\\right), y=\\left(2a-\\dfrac{\\left(a^2-c^2\\right)}{a-c\\cos\\left(t\\right)}\\right)\\cdot\\sin\\left(t\\right)")

This curve has a classic heart-shape (hotpink in Figure 7) for a part of
the range of eccentricities of the ellipse. These curves may be
considered bifocal like the ellipse, unlike the limaçons (including the
cardioid) derived from the unifocal circle. The ellipse and the
ellipse-hearts touch each other at the vertices of the ellipse. Figure 7
shows the relationships between a system of ellipses and their
corresponding ellipse-hearts. They might define the outlines of certain
leaves or the dehisced pod of the bastard poon tree.

[![ellipse\_hearts\_Fig7](https://manasataramgini.files.wordpress.com/2018/07/ellipse_hearts_fig7.png?w=537&h=496)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_hearts_fig7.png)Figure
7

**The Cassini curve of an ellipse**

*Every ellipse is associated with a confocal Cassini curve sharing
parameters with the ellipse.*

Even though the Cassini curves are well-known, that they are
intrinsically associated with every ellipse does not seem to be common
knowledge (at least as far as we know). This is despite the historical
associations of a version of the Cassini curve, the Cassini oval. Hence,
it excited us considerably when, in our youth, we discovered the two to
be intimately linked. The curve itself was discovered by the astrologer
and mathematician Giovanni Cassini in an interesting context: In the
west, as in India, the transition from geocentricity to heliocentricity
was neither immediate nor uncontested. Cassini, despite being a
prodigious observational astronomer, believed that the sun went around
the earth in an oval orbit, which was defined by one lobe of the curve
now known as the Cassini ovals. However, later in his life he realized
that he was totally wrong and that Kepler was right in describing the
orbit of the earth around the sun as an ellipse rather than an oval.

Now, how is the Cassini curve associated with the ellipse? It arises
from the following question: Given an ellipse with a point
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P") on
it, let points
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
and ![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0
"B") be the feet of the perpendiculars dropped from the two foci of the
ellipse ![F\_1,
F\_2](https://s0.wp.com/latex.php?latex=F_1%2C+F_2&bg=ffffff&fg=333333&s=0
"F_1, F_2") to the tangent at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").
What would be the locus of the points of intersection
![F](https://s0.wp.com/latex.php?latex=F&bg=ffffff&fg=333333&s=0 "F")
and ![E](https://s0.wp.com/latex.php?latex=E&bg=ffffff&fg=333333&s=0
"E") of the circles with radii
![r\_1=F\_1A](https://s0.wp.com/latex.php?latex=r_1%3DF_1A&bg=ffffff&fg=333333&s=0
"r_1=F_1A") and
![r\_2=F\_2B](https://s0.wp.com/latex.php?latex=r_2%3DF_2B&bg=ffffff&fg=333333&s=0
"r_2=F_2B") as
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P")
moves along the ellipse. We solved this thus:

[![ellipse\_ovals\_Fig8](https://manasataramgini.files.wordpress.com/2018/07/ellipse_ovals_fig8.png?w=660&h=500)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_ovals_fig8.png)Figure
8

From the above discussion it becomes clear that both
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
and ![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0
"B") will lie on the circumcircle of the ellipse
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") (Figure 8). As both are pedal points they would define parallel
lines
![\\overleftrightarrow{AD}](https://s0.wp.com/latex.php?latex=%5Coverleftrightarrow%7BAD%7D&bg=ffffff&fg=333333&s=0
"\\overleftrightarrow{AD}") and
![\\overleftrightarrow{BC}](https://s0.wp.com/latex.php?latex=%5Coverleftrightarrow%7BBC%7D&bg=ffffff&fg=333333&s=0
"\\overleftrightarrow{BC}") which form the rectangle
![ABCD](https://s0.wp.com/latex.php?latex=ABCD&bg=ffffff&fg=333333&s=0
"ABCD") inscribed in the circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2"). From this rectangle (Figure 8) it becomes clear that the
![\\overline{AF\_1}=\\overline{CF\_2}=r\_1](https://s0.wp.com/latex.php?latex=%5Coverline%7BAF_1%7D%3D%5Coverline%7BCF_2%7D%3Dr_1&bg=ffffff&fg=333333&s=0
"\\overline{AF_1}=\\overline{CF_2}=r_1") and
![\\overline{BF\_1}=\\overline{DF\_1}
=r\_2](https://s0.wp.com/latex.php?latex=%5Coverline%7BBF_1%7D%3D%5Coverline%7BDF_1%7D+%3Dr_2&bg=ffffff&fg=333333&s=0
"\\overline{BF_1}=\\overline{DF_1} =r_2"). We then apply the well-known
Euclidean intersecting chords theorem on
![AD](https://s0.wp.com/latex.php?latex=AD&bg=ffffff&fg=333333&s=0 "AD")
and the major axis of the ellipse
![V\_1V\_2](https://s0.wp.com/latex.php?latex=V_1V_2&bg=ffffff&fg=333333&s=0
"V_1V_2"). Thus we get:

![r\_1\\cdot r\_2=\\overline{V1F\_1}\\cdot
\\overline{V2F\_2}=(a-c)(a+c)=a^2-c^2=b^2](https://s0.wp.com/latex.php?latex=r_1%5Ccdot+r_2%3D%5Coverline%7BV1F_1%7D%5Ccdot+%5Coverline%7BV2F_2%7D%3D%28a-c%29%28a%2Bc%29%3Da%5E2-c%5E2%3Db%5E2&bg=ffffff&fg=333333&s=0
"r_1\\cdot r_2=\\overline{V1F_1}\\cdot \\overline{V2F_2}=(a-c)(a+c)=a^2-c^2=b^2")

Thus, the product of the two pedal segments of an ellipse is a constant
equal to the square of the semiminor axis: ![r\_1\\cdot
r\_2=b^2](https://s0.wp.com/latex.php?latex=r_1%5Ccdot+r_2%3Db%5E2&bg=ffffff&fg=333333&s=0
"r_1\\cdot r_2=b^2"). Now, the bipolar equation of the form ![r\_1\\cdot
r\_2=b^2](https://s0.wp.com/latex.php?latex=r_1%5Ccdot+r_2%3Db%5E2&bg=ffffff&fg=333333&s=0
"r_1\\cdot r_2=b^2") defines the Cassini curve. From this bipolar
equation we can derive its Cartesian equation:

![\\left((x - c)^2 + y^2 \\right) \\left((x + c)^2 + y^2\\right) = (a^2
-
c^2)^2=b^4](https://s0.wp.com/latex.php?latex=%5Cleft%28%28x+-+c%29%5E2+%2B+y%5E2+%5Cright%29+%5Cleft%28%28x+%2B+c%29%5E2+%2B+y%5E2%5Cright%29+%3D+%28a%5E2+-+c%5E2%29%5E2%3Db%5E4&bg=ffffff&fg=333333&s=0
"\\left((x - c)^2 + y^2 \\right) \\left((x + c)^2 + y^2\\right) = (a^2 - c^2)^2=b^4")

[![ellipse\_lemniscate\_Fig9](https://manasataramgini.files.wordpress.com/2018/07/ellipse_lemniscate_fig9.png?w=613&h=464)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_lemniscate_fig9.png)Figure
9

The form taken by the Cassini curve depends on the eccentricity of the
ellipse. When
![e\_c=0](https://s0.wp.com/latex.php?latex=e_c%3D0&bg=ffffff&fg=333333&s=0
"e_c=0"), the ellipse, circumcircle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") and the Cassini curve all become a coincident circle. When
![e\_c=\\tfrac{1}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=e_c%3D%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"e_c=\\tfrac{1}{\\sqrt{2}}"), the curve crosses over to become the
lemniscate of Bernoulli (Figure 9). When ![1\>e\_c\>
\\tfrac{1}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=1%3Ee_c%3E+%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"1\>e_c\> \\tfrac{1}{\\sqrt{2}}") it becomes two separate oval loops and
is the classic Cassinian oval. When
![\\tfrac{1}{\\sqrt{2}}\>e\_c\>\\tfrac{1}{\\sqrt{3}}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D%3Ee_c%3E%5Ctfrac%7B1%7D%7B%5Csqrt%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{\\sqrt{2}}\>e_c\>\\tfrac{1}{\\sqrt{3}}") the curve is
bilobed with central dimples but a single loop. When ![e\_c \\le
\\tfrac{1}{\\sqrt{3}}](https://s0.wp.com/latex.php?latex=e_c+%5Cle+%5Ctfrac%7B1%7D%7B%5Csqrt%7B3%7D%7D&bg=ffffff&fg=333333&s=0
"e_c \\le \\tfrac{1}{\\sqrt{3}}"), the curve takes the form of a single
biaxially symmetric convex oval. For values close to the minimum of the
range of
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c") the Cassini curve approximates a single circle while close to the
maximum it approximates two small circles. In conclusion, the
eccentricity of the ellipse
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c") is entirely sufficient describe the range of shapes adopted by
the Cassini curve. Indeed, we can conceive, the three curves, namely the
ellipse circumcircle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2"), the ellipse and the corresponding Cassini curve as three degrees
of response to the eccentricity parameter. The circle
![c\_2](https://s0.wp.com/latex.php?latex=c_2&bg=ffffff&fg=333333&s=0
"c_2") represents the
![0{th}](https://s0.wp.com/latex.php?latex=0%7Bth%7D&bg=ffffff&fg=333333&s=0
"0{th}") degree in that it does not change at all with
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c"). The ellipse represents the first degree response in that in
flattens uniformly along the minor axis with increasing
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c"). The Cassini curve represents the even more exaggerated second
degree response in that it starts of by flattening along the minor axis
even more rapidly than the ellipse. Thus it first dimples, then crosses
over as the lemniscate and finally breaks apart into the two loops of
the oval. Thus the first degree response is a conic while the second
degree response is a toric section (i.e. a section through the torus as
the Cassini curves). Figure 10 shows an animation of the evolving curve
with changing
![e\_c](https://s0.wp.com/latex.php?latex=e_c&bg=ffffff&fg=333333&s=0
"e_c").

[![ellipse\_animation\_fig10](https://manasataramgini.files.wordpress.com/2018/07/ellipse_animation_fig10.gif?w=640)](https://manasataramgini.files.wordpress.com/2018/07/ellipse_animation_fig10.gif)Figure
10
