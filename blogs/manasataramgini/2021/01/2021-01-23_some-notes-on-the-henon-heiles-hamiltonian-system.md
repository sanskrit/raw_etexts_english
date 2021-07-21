+++
title = "Some notes on the Henon-Heiles Hamiltonianxa0system"
date = "2021-01-23"

+++
Anyone familiar with dynamical systems knows of the Henon-Heiles (HH)
system. What we are presenting here is well-known stuff about which
reams of material have been written. However, we offer certain tricks
for visualizing this system that make it easy for lay readers with just
a high school knowledge of mathematics to play with. The HH system was
discovered by the French astronomer Henon and his colleague Heiles when
they were studying the motion of stars in the galaxy under the influence
of the gravity of the total matter in the galaxy. The true astronomical
significance of these equations outside the scope of the current
discussion. Our own original interest in this problem was primarily from
the perspective experimental mathematics (“play physics”), starting as
an extension to our interest in defining ovals by means of ordinary
differential equations (ODEs). The system defined by Henon and Heiles
considers the motion of a body in 2 dimensional Euclidean space, i.e. a
fixed plane. The phase space describing the motion is thus defined by
the variables ![(x, y, p_x,
p_y)](https://s0.wp.com/latex.php?latex=%28x%2C+y%2C+p_x%2C+p_y%29&bg=ffffff&fg=333333&s=0&c=20201002),
where ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0&c=20201002)
describe the position in two dimensions and ![p_x,
p_y](https://s0.wp.com/latex.php?latex=p_x%2C+p_y&bg=ffffff&fg=333333&s=0&c=20201002)
describes the momentum in the two directions. Given that the momenta are
![p_x= mx';
p_y=my'](https://s0.wp.com/latex.php?latex=p_x%3D+mx%27%3B+p_y%3Dmy%27&bg=ffffff&fg=333333&s=0&c=20201002),
for a body of unit mass the momenta become the derivative of the
position variables with respect to time ![(x'=\\tfrac{dx}{dt},
y'=\\tfrac{dy}{dt})](https://s0.wp.com/latex.php?latex=%28x%27%3D%5Ctfrac%7Bdx%7D%7Bdt%7D%2C+y%27%3D%5Ctfrac%7Bdy%7D%7Bdt%7D%29&bg=ffffff&fg=333333&s=0&c=20201002).
Henon and Heiles considered a potential described by the equation:

![V(x,y) = \\dfrac{x^2+y^2}{2}+x^2y-\\dfrac{y^3}{3} \\kern 3em \\cdots
\\S
1](https://s0.wp.com/latex.php?latex=V%28x%2Cy%29+%3D+%5Cdfrac%7Bx%5E2%2By%5E2%7D%7B2%7D%2Bx%5E2y-%5Cdfrac%7By%5E3%7D%7B3%7D+%5Ckern+3em+%5Ccdots+%5CS+1&bg=ffffff&fg=333333&s=0&c=20201002)

The potential energy of a simple harmonic oscillator in the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0&c=20201002)
direction is
![V(x)=\\tfrac{kx^2}{2}](https://s0.wp.com/latex.php?latex=V%28x%29%3D%5Ctfrac%7Bkx%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002).
By taking a unit force constant
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0&c=20201002)
we see that the terms
![\\tfrac{x^2+y^2}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bx%5E2%2By%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002)
in ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0&c=20201002)
represent two orthogonal simple harmonic oscillators. The further
nonlinear term,
![x^2y-\\tfrac{y^3}{3}](https://s0.wp.com/latex.php?latex=x%5E2y-%5Ctfrac%7By%5E3%7D%7B3%7D&bg=ffffff&fg=333333&s=0&c=20201002),
in ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0&c=20201002)
is a perturbation that couples these oscillators. This potential takes
the form of a cubic hyperboloid-paraboloid and is visualized in Figure
1.

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig1-1.png)

Figure 1.

The kinetic energy of the body is given by
![T=\\tfrac{mv^2}{2}](https://s0.wp.com/latex.php?latex=T%3D%5Ctfrac%7Bmv%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002);
where
![v](https://s0.wp.com/latex.php?latex=v&bg=ffffff&fg=333333&s=0&c=20201002)
is the velocity of the body. Thus, for the above-defined HH system we
get
![T=\\tfrac{x'^2+y'^2}{2}](https://s0.wp.com/latex.php?latex=T%3D%5Ctfrac%7Bx%27%5E2%2By%27%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002).
The Hamiltonian of a system, which represents its total energy, is given
by
![H=T+V](https://s0.wp.com/latex.php?latex=H%3DT%2BV&bg=ffffff&fg=333333&s=0&c=20201002).
Since this is an energy conserving system, its total energy is equal to
a scalar constant
![E](https://s0.wp.com/latex.php?latex=E&bg=ffffff&fg=333333&s=0&c=20201002),
i.e. the energy level of the system. Thus, for the HH system we get:

![H=\\dfrac{x'^2+y'^2+x^2+y^2}{2}+x^2y-\\dfrac{y^3}{3}= E \\kern 3em
\\cdots \\S
2](https://s0.wp.com/latex.php?latex=H%3D%5Cdfrac%7Bx%27%5E2%2By%27%5E2%2Bx%5E2%2By%5E2%7D%7B2%7D%2Bx%5E2y-%5Cdfrac%7By%5E3%7D%7B3%7D%3D+E+%5Ckern+3em+%5Ccdots+%5CS+2&bg=ffffff&fg=333333&s=0&c=20201002)

If we section the 3D curve
![V(x,y)](https://s0.wp.com/latex.php?latex=V%28x%2Cy%29&bg=ffffff&fg=333333&s=0&c=20201002)
by planes corresponding to different energy levels
![z=E](https://s0.wp.com/latex.php?latex=z%3DE&bg=ffffff&fg=333333&s=0&c=20201002),
we get the equipotential curves within which the
![x,y](https://s0.wp.com/latex.php?latex=x%2Cy&bg=ffffff&fg=333333&s=0&c=20201002)
would lie for a given energy level (Figure 2). We observe that if
![E=\\tfrac{1}{6}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002),
the equipotential curve becomes 3 intersecting lines that form an
equilateral triangle defined by the equilibrium points
![(-\\tfrac{\\sqrt{3}}{2}, -\\tfrac{1}{2}); (0,1);
(\\tfrac{\\sqrt{3}}{2},
-\\tfrac{1}{2}))](https://s0.wp.com/latex.php?latex=%28-%5Ctfrac%7B%5Csqrt%7B3%7D%7D%7B2%7D%2C+-%5Ctfrac%7B1%7D%7B2%7D%29%3B+%280%2C1%29%3B+%28%5Ctfrac%7B%5Csqrt%7B3%7D%7D%7B2%7D%2C+-%5Ctfrac%7B1%7D%7B2%7D%29%29&bg=ffffff&fg=333333&s=0&c=20201002).
Within this equilateral triangle, the body exhibits bounded motion.
Thus, for all
![E\<\\tfrac{1}{6}](https://s0.wp.com/latex.php?latex=E%3C%5Ctfrac%7B1%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002)
we get bounded trajectories in the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0&c=20201002)
plane. As
![E](https://s0.wp.com/latex.php?latex=E&bg=ffffff&fg=333333&s=0&c=20201002)
becomes smaller the central equipotential boundary tends towards a
circle and degenerates to a point at 0. However, for
![E>\\tfrac{1}{6}](https://s0.wp.com/latex.php?latex=E%3E%5Ctfrac%7B1%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002)
we get curves that are open; hence, at these energy levels the body can
escape to infinity via the open lanes. Thus, there is a clearly defined
escape energy level for this system,
![E=\\tfrac{1}{6}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002).

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig2-1.png)

Figure 2. The energy levels correspond to ![E=\\tfrac{1}{32},
\\tfrac{1}{16}, \\tfrac{1}{12},\\tfrac{1}{8},\\tfrac{1}{6},
\\tfrac{1}{4}, \\tfrac{1}{3}, 1, 2, 3,
4](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B32%7D%2C+%5Ctfrac%7B1%7D%7B16%7D%2C+%5Ctfrac%7B1%7D%7B12%7D%2C%5Ctfrac%7B1%7D%7B8%7D%2C%5Ctfrac%7B1%7D%7B6%7D%2C+%5Ctfrac%7B1%7D%7B4%7D%2C+%5Ctfrac%7B1%7D%7B3%7D%2C+1%2C+2%2C+3%2C+4&bg=ffffff&fg=333333&s=0&c=20201002)

To study the trajectories under this system we first obtain the
equations for the force acting on a body of unit mass (acceleration) in
each direction from the above potential by taking the negative partial
derivative with respect to each positional variable:

![x''= -\\dfrac{\\partial V(x,y)}{\\partial x} =
-x-2xy](https://s0.wp.com/latex.php?latex=x%27%27%3D+-%5Cdfrac%7B%5Cpartial+V%28x%2Cy%29%7D%7B%5Cpartial+x%7D+%3D+-x-2xy&bg=ffffff&fg=333333&s=0&c=20201002)

![y''= -\\dfrac{\\partial V(x,y)}{\\partial y} = -y
-x^2+y^2](https://s0.wp.com/latex.php?latex=y%27%27%3D+-%5Cdfrac%7B%5Cpartial+V%28x%2Cy%29%7D%7B%5Cpartial+y%7D+%3D+-y+-x%5E2%2By%5E2&bg=ffffff&fg=333333&s=0&c=20201002)

From the above can now get a system of ODEs thus:

![x'=p_x](https://s0.wp.com/latex.php?latex=x%27%3Dp_x&bg=ffffff&fg=333333&s=0&c=20201002)  
![y'=p_y](https://s0.wp.com/latex.php?latex=y%27%3Dp_y&bg=ffffff&fg=333333&s=0&c=20201002)  
![p_x'=x''=
-x-2xy](https://s0.wp.com/latex.php?latex=p_x%27%3Dx%27%27%3D+-x-2xy&bg=ffffff&fg=333333&s=0&c=20201002)  
![p_y'=y''=-y -x^2+y^2 \\kern 3em \\cdots \\S
3](https://s0.wp.com/latex.php?latex=p_y%27%3Dy%27%27%3D-y+-x%5E2%2By%5E2+%5Ckern+3em+%5Ccdots+%5CS+3&bg=ffffff&fg=333333&s=0&c=20201002)

The solutions to this system ![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0&c=20201002)
yield a curve in the 4-dimensional phase-space ![(x,y, p_x,
p_y)](https://s0.wp.com/latex.php?latex=%28x%2Cy%2C+p_x%2C+p_y%29&bg=ffffff&fg=333333&s=0&c=20201002).
To solve ![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0&c=20201002)
we first need to obtain some initial conditions for a given energy level
![E](https://s0.wp.com/latex.php?latex=E&bg=ffffff&fg=333333&s=0&c=20201002)
using the Hamiltonian ![\\S
2](https://s0.wp.com/latex.php?latex=%5CS+2&bg=ffffff&fg=333333&s=0&c=20201002).
We do that by setting
![x_0=0](https://s0.wp.com/latex.php?latex=x_0%3D0&bg=ffffff&fg=333333&s=0&c=20201002).
We then choose some values of ![y_0,
p\_{y0}=y_0'](https://s0.wp.com/latex.php?latex=y_0%2C+p_%7By0%7D%3Dy_0%27&bg=ffffff&fg=333333&s=0&c=20201002).
From those we can calculate
![p\_{x0}=x_0'](https://s0.wp.com/latex.php?latex=p_%7Bx0%7D%3Dx_0%27&bg=ffffff&fg=333333&s=0&c=20201002)
thus:

![p\_{x0}=
\\sqrt{2E-p_y^2-y^2+\\dfrac{2y^3}{3}}](https://s0.wp.com/latex.php?latex=p_%7Bx0%7D%3D+%5Csqrt%7B2E-p_y%5E2-y%5E2%2B%5Cdfrac%7B2y%5E3%7D%7B3%7D%7D&bg=ffffff&fg=333333&s=0&c=20201002)

One can see that this places a constraint on the allowed ![y_0,
p\_{y0}](https://s0.wp.com/latex.php?latex=y_0%2C+p_%7By0%7D&bg=ffffff&fg=333333&s=0&c=20201002)
— they have to be chosen such that
![p\_{x0}](https://s0.wp.com/latex.php?latex=p_%7Bx0%7D&bg=ffffff&fg=333333&s=0&c=20201002)
is real. Once we have these initial conditions we can solve the above
ODEs with efficient LSODA solver written by Alan Hindmarsh and Linda
Petzold or you can write your own solver by the method of Runge and
Kutta as we did in our youth. Initial results below are shown using the
LSODA solver. However, we will see below that we can also obtain
solutions without using traditional ODE solutions. Figure 4 shows an
example of solution for the energy level
![E=\\tfrac{1}{8}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B8%7D&bg=ffffff&fg=333333&s=0&c=20201002)
and initial conditions ![x_0=0; y_0= 0.1, y_0'=
0.14](https://s0.wp.com/latex.php?latex=x_0%3D0%3B+y_0%3D+0.1%2C+y_0%27%3D+0.14&bg=ffffff&fg=333333&s=0&c=20201002)
in the 3D space defined by ![x, y,
y'](https://s0.wp.com/latex.php?latex=x%2C+y%2C+y%27&bg=ffffff&fg=333333&s=0&c=20201002)

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig3-1.png)

Figure 3.

To get a better understanding of its behavior, we can visualize the
solution in several other ways Figure 4. First, we can simply look at
the way ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0&c=20201002)
change with time (first 2 top left panels of Figure 4). As expected,
![x(t),
y(t)](https://s0.wp.com/latex.php?latex=x%28t%29%2C+y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
would be oscillatory functions that cannot be defined using any
elementary functions. We can also examine the positional trajectory of
the body in its plane of motion by plotting ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0&c=20201002)
(top right panel of Figure 4). From the equipotential curves defined
above from ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0&c=20201002),
we can see that this trajectory would be bounded by the closed loop of
the curve defined by the equation (shown in blue):

![\\dfrac{x^2+y^2}{2}+x^2y-\\dfrac{y^3}{3}=E](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bx%5E2%2By%5E2%7D%7B2%7D%2Bx%5E2y-%5Cdfrac%7By%5E3%7D%7B3%7D%3DE&bg=ffffff&fg=333333&s=0&c=20201002)

We can also plot ![y,
y'](https://s0.wp.com/latex.php?latex=y%2C+y%27&bg=ffffff&fg=333333&s=0&c=20201002)
(bottom left panel of Figure 4) which shows how momentum changes with
the position in the
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0&c=20201002)
direction. This curve will be bounded by a special oval (shown in blue)
that is determined by letting ![x=0;
x'=0](https://s0.wp.com/latex.php?latex=x%3D0%3B+x%27%3D0&bg=ffffff&fg=333333&s=0&c=20201002)
in the Hamiltonian ![\\S
2](https://s0.wp.com/latex.php?latex=%5CS+2&bg=ffffff&fg=333333&s=0&c=20201002).
This gives us a cubic curve defined by the equation (in standard
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0&c=20201002)
coordinates, not the ![(x,
y)](https://s0.wp.com/latex.php?latex=%28x%2C+y%29&bg=ffffff&fg=333333&s=0&c=20201002)
of the phase space of the solutions of ![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0&c=20201002)):

![\\dfrac{x^2+y^2}{2}-\\dfrac{x^3}{3}=E \\kern 3em \\cdots \\S
4](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bx%5E2%2By%5E2%7D%7B2%7D-%5Cdfrac%7Bx%5E3%7D%7B3%7D%3DE+%5Ckern+3em+%5Ccdots+%5CS+4&bg=ffffff&fg=333333&s=0&c=20201002)

The closed loop of the cubic ![\\S
4](https://s0.wp.com/latex.php?latex=%5CS+4&bg=ffffff&fg=333333&s=0&c=20201002)
is the bounding oval, which was what got us first interested in the HH
system in the 16th year of our life.

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig4-1.png)

Figure 4.

Finally, the bottom right panel of Figure 4 shows the Poincare section
that records the points where the curve shown in Figure 3 pierces the
plane
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0&c=20201002)
(See below for further discussions). It is obvious that these are a
subset of the ![y,
y'](https://s0.wp.com/latex.php?latex=y%2C+y%27&bg=ffffff&fg=333333&s=0&c=20201002)
plot and will thus be bounded by the same oval ![\\S
4](https://s0.wp.com/latex.php?latex=%5CS+4&bg=ffffff&fg=333333&s=0&c=20201002).

The way to compute the Poincare section is to search the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0&c=20201002)
values of solution for cases where the sign of
![x_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0&c=20201002)
and
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0&c=20201002)
are different. Such successive points will bound the segments of the
curve that pierce the plane
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0&c=20201002).
Given that our steps for numerical integration are small, we can
calculate the corresponding values of ![y,
y'](https://s0.wp.com/latex.php?latex=y%2C+y%27&bg=ffffff&fg=333333&s=0&c=20201002)
using linear interpolation: ![y=\\tfrac{y_n+y\_{n+1}}{2}; \\;
y'=\\tfrac{y_n+y\_{n+1}}{2}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7By_n%2By_%7Bn%2B1%7D%7D%7B2%7D%3B+%5C%3B+y%27%3D%5Ctfrac%7By_n%2By_%7Bn%2B1%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002).
Plotting the thus calculated ![y,
y'](https://s0.wp.com/latex.php?latex=y%2C+y%27&bg=ffffff&fg=333333&s=0&c=20201002)
will give us the Poincare sections for a given starting point. Now, we
can also calculate the solutions for above system ![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0&c=20201002)
without solving the ODEs by converting it into a discrete difference
equation. These difference equations have a step parameter
![\\epsilon](https://s0.wp.com/latex.php?latex=%5Cepsilon&bg=ffffff&fg=333333&s=0&c=20201002),
which if kept small can yield solutions equivalent to that obtained by
solving the ODEs. The system of difference equations goes thus:

![p\_{xn+1}= p\_{xn}+\\epsilon
(-x_n-2x_ny_n)](https://s0.wp.com/latex.php?latex=p_%7Bxn%2B1%7D%3D+p_%7Bxn%7D%2B%5Cepsilon+%28-x_n-2x_ny_n%29&bg=ffffff&fg=333333&s=0&c=20201002)  
![p\_{yn+1}= p\_{yn} + \\epsilon
(-y_n+y_n^2-x_n^2)](https://s0.wp.com/latex.php?latex=p_%7Byn%2B1%7D%3D+p_%7Byn%7D+%2B+%5Cepsilon+%28-y_n%2By_n%5E2-x_n%5E2%29&bg=ffffff&fg=333333&s=0&c=20201002)  
![x\_{n+1}= x_n+\\epsilon
p\_{xn+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D+x_n%2B%5Cepsilon+p_%7Bxn%2B1%7D&bg=ffffff&fg=333333&s=0&c=20201002)  
![y\_{n+1}= y_n+\\epsilon
p\_{yn+1}](https://s0.wp.com/latex.php?latex=y_%7Bn%2B1%7D%3D+y_n%2B%5Cepsilon+p_%7Byn%2B1%7D&bg=ffffff&fg=333333&s=0&c=20201002)

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig5-1.png)

Figure 5.

We empirically determined that by setting ![\\epsilon
=0.02](https://s0.wp.com/latex.php?latex=%5Cepsilon+%3D0.02&bg=ffffff&fg=333333&s=0&c=20201002)
we can get results similar to the solution of the ODEs with time steps
of 0.01. This provides us an easy mechanism, with somewhat higher speed
than the ODE solver, to obtain equivalent solutions for the HH system.
This in turn allows us to explore the Poincare sections for different
initial values at a much higher density. Figure 5 shows one such
exploration of Poincare sections for the energy level
![E=0.128](https://s0.wp.com/latex.php?latex=E%3D0.128&bg=ffffff&fg=333333&s=0&c=20201002)
with 100 different initial conditions, each plotted in a different
color. The result is a beautiful oval with an inner decoration by a
strange attractor reminiscent of one of the ovoids produced for the
Russian royalty. The attractor shows clear preferred regions for the
intersections of certain orbits and regions where the intersections are
chaotically distributed. To better understand the relationship between
the structure of the Poincare sections and the form of the orbits on the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0&c=20201002)
plane we take the case of
![E=\\tfrac{1}{8}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B8%7D&bg=ffffff&fg=333333&s=0&c=20201002)
and examine 12 initial points chosen from different regions of the
Poincare sections, i.e. defined ![y_0,
y_0'](https://s0.wp.com/latex.php?latex=y_0%2C+y_0%27&bg=ffffff&fg=333333&s=0&c=20201002),
with
![x_0=0](https://s0.wp.com/latex.php?latex=x_0%3D0&bg=ffffff&fg=333333&s=0&c=20201002)
(Figure 6).

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig6-1.png)

Figure 6.

The trajectories of these initial points on the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0&c=20201002)
plane are plotted in Figure 7. Towards the narrow end of the bounding
oval we have an oval exclusion zone and the towards the broad end of the
oval we have a candra-bindu (crescent and dot) clearing zone. The
initial point 1 lies at the center of the narrow end oval clearing. This
initial point and the center of the crescent clearing at the broad end
(not shown) yield a trajectory with a single loop with 3 apexes (top
row, leftmost plot of Figure 7). The next trajectory (top row, next plot
moving left to right) is a straight line at a
![45^\\circ](https://s0.wp.com/latex.php?latex=45%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
incline and corresponds to the center of the two “eyes” of the Poincare
section (point 2 in figure 6 is one of these eyes).

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig7-1.png)

Figure 7. The trajectories of the points corresponding to Figure 6 in
left to right in 3 rows from top to bottom.

The basis of these trajectories can be understood from the plots of the
functions ![x(t);
y(t)](https://s0.wp.com/latex.php?latex=x%28t%29%3B+y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
(Figure 8; for every point in Figure 6 and trajectory in Figure 7 the
corresponding ![x(t);
y(t)](https://s0.wp.com/latex.php?latex=x%28t%29%3B+y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
are shown one below the other from top to bottom in 2 columns). The
first two trajectories result from oscillations where both
![x(t)](https://s0.wp.com/latex.php?latex=x%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
and
![y(t)](https://s0.wp.com/latex.php?latex=y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
have period 1 — they show the same repeating pattern after one
oscillation. Thus, these two cases can be said to be in a 1:1 resonance.
In the second case, they are additionally in phase, i.e. the crest and
trough at the same time.

Point 3 samples the center one of the four “islands” which surround the
above-mentioned “eyes” of the Poincare section. Each of the
island-centers results in a trajectory like the 3rd plot (Figure 7, top
row). Point 4 samples one of the small crescents in the vicinity of the
oval exclusion zone around point 1 and results in the trajectory seen in
plot 4 of Figure 7. These two trajectories result from ![x(t);
y(t)](https://s0.wp.com/latex.php?latex=x%28t%29%3B+y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
where both have a periodicity of 4, i.e. a 4:4 resonance. Of the two the
trajectory 3 arises from a case where in addition to 4:4 resonance the
two oscillators are also in phase.

Point 5 (Figure 6) and its corresponding trajectory (Figure 7)
corresponds to two period 5 oscillators in a 5:5 resonance (Figure 8).
Such 5:5 resonance oscillators are a pervasive feature of the HH system
at this energy level and correspond to the 5 islands of exclusion around
the oval exclusion around point 1, the center of the bindu and the two
exclusion zones flanking either tip of the crescent.

![](https://manasataramgini.files.wordpress.com/2021/01/henhei_fig8-1.png)

Figure 8

Point 6 corresponds to a trajectory arising from a 8:9 resonance; point
7 evolves into a more complex 5:25 resonance; the trajectory of point 8
simulates a 3D ribbon and arises from the even more complex 11:37
resonance.

The trajectories arising from points 9, 10 and 11 exhibit what might be
termed quasiperiodic behavior. In the case of the evolution of point 9,
![x(t)](https://s0.wp.com/latex.php?latex=x%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
has a quasiperiod of 4, i.e., it has a similar pattern repetition after
every 4 oscillation but the successive repeats are not identical but
change slightly over time.
![y(t)](https://s0.wp.com/latex.php?latex=y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002),
on the contrary, has a strict period of 1. In the evolution of point 10,
![x(t)](https://s0.wp.com/latex.php?latex=x%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
has a quasiperiod of 5 which is overlayed on a nearly regular higher
period of 15. These two points are representative of the evolution of
the points in the zones close the bounding oval on its narrow side. One
may note that the evolution of point 11 is like a “broadband” version of
the 5:5 resonance points. Keeping with this,
![x(t)](https://s0.wp.com/latex.php?latex=x%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
has a strict period of 5, whereas
![y(t)](https://s0.wp.com/latex.php?latex=y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
has a quasiperiod of 5 with higher-order repeat patterns of multiples of
5.

Finally, the evolution of point 12 is chaotic, i.e. the oscillations
have no discernible period. The irregularity is marked in
![y(t)](https://s0.wp.com/latex.php?latex=y%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
but is
![x(t)](https://s0.wp.com/latex.php?latex=x%28t%29&bg=ffffff&fg=333333&s=0&c=20201002)
it manifests more slowly over time. These chaotic trajectories form the
bulk of the central uniform distribution of points in the Poincare
section. The appearance of chaos can be seen as the limit of the
trajectories with increasingly complex or longer period resonances. The
quasiperiodic orbits with a nearly regular short period internal repeat
structure might be seen as lying at the edge of long periods and true
periodicity. In terms of energy levels, chaos starts appearing in the
central regions close to
![E=\\tfrac{1}{10}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B10%7D&bg=ffffff&fg=333333&s=0&c=20201002)
and by
![E=\\tfrac{1}{8}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B8%7D&bg=ffffff&fg=333333&s=0&c=20201002)
constitutes the bulk of the internal structure of the Poincare section
with internal islands of periodicity and quasiperiodicity in the
anterior periphery of the oval. By the limiting
![E=\\tfrac{1}{6}](https://s0.wp.com/latex.php?latex=E%3D%5Ctfrac%7B1%7D%7B6%7D&bg=ffffff&fg=333333&s=0&c=20201002)
nearly all of the trajectories become chaotic.

In conclusion, the HH system qualitatively shows all the typical forms
of oscillatory behaviors observed in natural systems (e.g. variable star
light curves, weather patterns, population dynamics and far-from
equilibrium oscillatory chemical reactions): periodicity with different
resonances, quasiperiodicity and chaos. It thus provides a good example
how any system whose phase space is defined by even simple ODEs with
non-linear terms can exhibit the behavioral diversity characteristic of
natural systems.
