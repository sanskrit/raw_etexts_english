+++
title = "A simple second order differential equation, ovals and chaos"

+++
In our youth as a consequence of our undying fascination with ovals we
explored many means of generating them. In course of those explorations
we experimentally arrived at a simple second order differential equation
that generated oval patterns. It also taught us lessons on chaotic
systems emerging from differential equations even before we actually
explored the famous Lorenz and Rossler attractors for ourselves. The
inspiration came from the very well-known harmonic oscillator which is
one of the first differential equations you might study as a layperson:
![\\tfrac{d^2x}{dt^2}=-ax](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bd%5E2x%7D%7Bdt%5E2%7D%3D-ax&bg=ffffff&fg=333333&s=0
"\\tfrac{d^2x}{dt^2}=-ax"), where
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") is
a positive constant that has some direct meaning in physics as the ratio
of the restoration constant to the mass of the oscillator. With this
foundation, we wondered what might happen if we used a cubic term
instead which was in turn coupled to a periodic forcing from a regular
harmonic oscillator. Thus, we arrived at the below equation with 3
parameters ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c"):

![\\dfrac{d^2x}{dt^2}=-abx^3+a\\cos\\left(\\dfrac{2\\pi t}{c}\\right)
\\; \\; \\; \\S
1](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bd%5E2x%7D%7Bdt%5E2%7D%3D-abx%5E3%2Ba%5Ccos%5Cleft%28%5Cdfrac%7B2%5Cpi+t%7D%7Bc%7D%5Cright%29+%5C%3B+%5C%3B+%5C%3B+%5CS+1&bg=ffffff&fg=333333&s=0
"\\dfrac{d^2x}{dt^2}=-abx^3+a\\cos\\left(\\dfrac{2\\pi t}{c}\\right) \\; \\; \\; \\S 1")

It became obvious to us this equation has no solution in terms of
elementary functions but we could semi-intuitively figure out that
solutions are likely to generate oval-like figures. To test this out we
had actually solve it numerically. Just before this foray, a visiting
relative, who was a college teacher, mentioned to us that the mark of
man was to solve ordinary differential equations using the method of
Rangā and Kuṭṭi on hand-held calculator. We had learned Euler’s method
as a part of our education in basic numerical calculus but the this new
method, apparently discovered by these south Indian savants, was
something we had never heard of. Accordingly, we looked up a book
featuring numerical analysis, which our father often recommended to us,
and realized that the relative was actually referring to a
generalization of the Eulerian method by the two śulapuruṣa-s Runge and
Kutta. This differential equation offered us an opportunity to apply it
to something interesting and we spent sometime writing a program to do
the same. With that in hand, we could solve the above 2nd order DE by
writing it as two linked 1st order ordinary DEs.

![\\dfrac{dx}{dt}=ay](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bdx%7D%7Bdt%7D%3Day&bg=ffffff&fg=333333&s=0
"\\dfrac{dx}{dt}=ay")

![\\dfrac{dy}{dt}=-bx^3+\\cos\\left(\\dfrac{2\\pi
t}{c}\\right)](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bdy%7D%7Bdt%7D%3D-bx%5E3%2B%5Ccos%5Cleft%28%5Cdfrac%7B2%5Cpi+t%7D%7Bc%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\dfrac{dy}{dt}=-bx^3+\\cos\\left(\\dfrac{2\\pi t}{c}\\right)")

![Figure 1. Some solutions of ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") for different values of the parameters ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c") with
![x\_0=y\_0=0](https://s0.wp.com/latex.php?latex=x_0%3Dy_0%3D0&bg=ffffff&fg=333333&s=0
"x_0=y_0=0") (click to
magnify).](https://manasataramgini.files.wordpress.com/2020/06/cubtrigx2.png?w=1024)

Consequently, we had an unfolding of the solutions for it which
presented an interesting picture (Figure 1): We saw before our eyes the
entire range of oscillations with simple periodicity, quasi-periodicity,
superimposed beats of different frequencies and various types of chaotic
oscillations. Thus, we saw this simple DE recapitulate all manner of
oscillatory phenomena we had encountered in nature: the changes is
numbers of molecules in during the cell cycle, populations of organisms
in the ecosystem, climatic patterns and the light-curves of variable
stars.

![Figure 2. ![x,
\\dot{x}](https://s0.wp.com/latex.php?latex=x%2C+%5Cdot%7Bx%7D&bg=ffffff&fg=333333&s=0
"x, \\dot{x}") for the same values of the parameters ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c") as in Figure 1 with
![x\_0=y\_0=0](https://s0.wp.com/latex.php?latex=x_0%3Dy_0%3D0&bg=ffffff&fg=333333&s=0
"x_0=y_0=0") (click to
magnify).](https://manasataramgini.files.wordpress.com/2020/06/cubtrig2.png?w=1024)

If we plotted ![x,
\\dot{x}](https://s0.wp.com/latex.php?latex=x%2C+%5Cdot%7Bx%7D&bg=ffffff&fg=333333&s=0
"x, \\dot{x}") we got our desired oval-like shapes. Notably, the cases
where the solution is clearly chaotic we get a space-filling entangling
of near oval paths in this plot.

![Figure 3. Plots of solutions with the
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
parameter changing while keeping ![a,
c](https://s0.wp.com/latex.php?latex=a%2C+c&bg=ffffff&fg=333333&s=0
"a, c") constant in each row (click to
magnify).](https://manasataramgini.files.wordpress.com/2020/06/cubtrigx5.png?w=1024)

![Figure 4. ![x,
\\dot{x}](https://s0.wp.com/latex.php?latex=x%2C+%5Cdot%7Bx%7D&bg=ffffff&fg=333333&s=0
"x, \\dot{x}") plots of the above solutions (click to
magnify).](https://manasataramgini.files.wordpress.com/2020/06/cubtrig5.png?w=1024)

From Figure 4 we can see that the amplitude parameter
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and the wavelength parameter
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c") of
the sinusoidal term of ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") are the primary determinants of “shape” of the solution, while
the parameter
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
associated with the cubic terms interacts with them to determine where
chaos occurs.
