+++
title = "The square root spiral and the Gamma function: entwined analogies"

+++
The topic discussed here is something on which considerable serious
mathematical literature has published by P.J Davis, W. Gautschi and
others. This partly historical narration is just a personal account of
our journey through the same as a non-mathematician. As for the detour
on the Gamma function its allure has been so much that everyone from the
ordinary college lecturer to the Fields medalist Manjul Bhargava has
written something about it. Its invisible hand is felt in science
especially in the form of various statistical distributions that show up
in as disparate phenomena as the distribution of the number of molecules
of widely expressed proteins or the distribution of positions in a
protein’s sequence evolving at different rates. Thus, we could not pass
up the opportunity for a little mention of it.

The story begins with a problem which one might have encountered in the
context of elementary geometric puzzles that one is asked to solve as a
youth: If you have a circle of radius
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
then how do you dissect it into
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
concentric circular rings of equal area using just a compass and
straight edge? Of course the first “ring” would be disc rather than a
ring. It is achieved by means of the below construction (Figure 1):

![circle\_dissection](https://manasataramgini.files.wordpress.com/2017/07/circle_dissection.png?w=640)Figure
1

1\) Let point A be the center of the circle of radius
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
which we seek to dissect into
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
rings.  
2\) Construct a unit of length of
![r=\\tfrac{R}{\\sqrt{n}}](https://s0.wp.com/latex.php?latex=r%3D%5Ctfrac%7BR%7D%7B%5Csqrt%7Bn%7D%7D&bg=ffffff&fg=333333&s=0
"r=\\tfrac{R}{\\sqrt{n}}").  
3\) Draw
![\\overline{AB}=r](https://s0.wp.com/latex.php?latex=%5Coverline%7BAB%7D%3Dr&bg=ffffff&fg=333333&s=0
"\\overline{AB}=r"). Then draw a segment of the same unit length
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0 "r")
perpendicular to
![\\overline{AB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAB%7D&bg=ffffff&fg=333333&s=0
"\\overline{AB}") at point B. Join A to the free end B1 of this new
segment.  
4\) Draw a further segment of length
![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0 "r")
perpendicular to
![\\overline{AB1}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAB1%7D&bg=ffffff&fg=333333&s=0
"\\overline{AB1}") and join its free end to A.  
5\) Repeat this procedure
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
times;
![n=17](https://s0.wp.com/latex.php?latex=n%3D17&bg=ffffff&fg=333333&s=0
"n=17") in figure 1. Draw circles with A as center with each of the
segments beginning with A as their respective radii. This completes the
required dissection.

One can see from the figure that the construction results in a sequence
of side-sharing right triangles whose hypotenuses increase successively
as the square roots of the natural numbers. Their legs of unit length
trace out a spiral path. Hence, this figure might be termed the square
root spiral (SRS). One may also see that as the number of dissections
![n\\rightarrow
\\infty](https://s0.wp.com/latex.php?latex=n%5Crightarrow+%5Cinfty&bg=ffffff&fg=333333&s=0
"n\\rightarrow \\infty") we are left with thinner and thinner rings that
are essentially the circumference of the circle:
![\\tfrac{\\text{d}A}{\\text{d}r}=2\\pi
r](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Ctext%7Bd%7DA%7D%7B%5Ctext%7Bd%7Dr%7D%3D2%5Cpi+r&bg=ffffff&fg=333333&s=0
"\\tfrac{\\text{d}A}{\\text{d}r}=2\\pi r").

In the above construction we used
![n=17](https://s0.wp.com/latex.php?latex=n%3D17&bg=ffffff&fg=333333&s=0
"n=17") because adding one more unit results in the spiral going past
the first turn (Figure 2). Thus, 17 is the whole number in turn 1; 54 in
turn 2; 110 in turn 3. Now, based on this number 17 it has been claimed
on flimsy evidence that this figure might have been constructed by
Plato’s teacher Theodorus in Greek antiquity. Plato, with his
characteristic eye for interesting mathematics, records the following
conversation (at \~360 BCE) between Socrates and his friend the
mathematician Theaetetus who laid the foundations of some key aspects of
Greek mathematics. Here Theaetetus is telling Socrates regarding his
study of square roots with another mathematician Theodorus (Theaetetus,
Jowett translation):

Theaet.: Theodorus was writing out for us something about roots, such as
the roots of three or five, showing that they are incommensurable by the
unit: he selected other examples up to seventeen — there he stopped. Now
as there are innumerable roots, the notion occurred to us of attempting
to include them all under one name or class.  
Soc.: And did you find such a class?  
Theaet.: I think that we did; but I should like to have your opinion.  
Soc.: Let me hear.  
Theaet.: We divided all numbers into two classes: those which are made
up of equal factors multiplying into one another, which we compared to
square figures and called square or equilateral numbers — that was one
class.  
Soc.: Very good.  
Theaet.: The intermediate numbers, such as three and five, and every
other number which is made up of unequal factors, either of a greater
multiplied by a less, or of a less multiplied by a greater, and when
regarded as a figure, is contained in unequal sides;-all these we
compared to oblong figures, and called them oblong numbers.  
Soc.: Capital;…

It is clear from what Theaetetus tells Socrates that they were talking
about dividing all natural numbers into perfect squares like 1, 4, 9,
16, … which yield a root which is measurable as units and all other
numbers in between which do not. These Theaetetus considered oblong
numbers for they needed unequal factors to constitute them. The question
is when Theodorus wrote out those numbers to illustrate the non-perfect
squares why did he stop at 17? It has been speculated that in
establishing their being “incommensurable by the unit” Theodorus had
made use of a construction as in figure 1 and he stopped at 17 because
he had reached maximum number of natural numbers that can be
accommodated in a single turn of the spiral. Of course there is no
evidence that this was the real reason for his choice of 17 (17 had some
importance in Indo-European tradition so there could be other reasons).

![squareroot\_spiral](https://manasataramgini.files.wordpress.com/2017/07/squareroot_spiral.png?w=640)Figure
2

Interestingly, while we drew out this figure of the SRS for ourselves as
part of the geometric constructions we indulged in in our youth, it has
sparked much mathematical activity only in the last 3 decades. As is
clear from figure 2 this spiral is a discrete spiral in that the radius
increases in jumps of the square roots of the natural numbers. The
mathematician Davis (also a historian of Euler’s and Gauss’ studies on
special functions) asked an interesting question: Can one find a smooth,
analytic curve that describes the square root spiral and interpolates
all the intermediate values between the discrete square root radii of
the discrete spiral? Davis the solved this question rather remarkably
following the footsteps of Leonhard Euler.

Before we get to that we shall first create a further generalization of
the discrete SRS: After having constructed the initial discrete SRS as
described above, reflect (invert) the point B which initiates the spiral
on the
![\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}") hypotenuse to get a new point. Then reflect the outer end
of the
![\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}") hypotenuse on the
![\\sqrt{3}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{3}") hypotenuse; then reflect the outer end of the
![\\sqrt{3}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{3}") hypotenuse on the 2 hypotenuse, so on. This yields the
second branch of the discrete SRS (in red in figure 2). So the Davis
problem in its more general form requires one to interpolate a smooth
curve through both the branches of of the discrete SRS.

The approach taken by Davis to solve it along with the solution has some
striking parallels the story one of the great problems in the history of
modern mathematics (described by Davis himself). Hence, we shall take
detour to look a bit at that famous problem. The factorial function was
originally discovered by Hindu mathematicians. For instance, it is
clearly provided by the Kashmirian polymath finance minister of the
Seuna Yādava rulers Śārṅgadeva in his work on the theory of Hindu music
the Saṃgīta-Ratnākara in 1225 CE. This original form of the factorial
function is organically described as the serial product of natural
numbers: ![n\!=1\\times 2\\times...(n-1)\\times
n](https://s0.wp.com/latex.php?latex=n%21%3D1%5Ctimes+2%5Ctimes...%28n-1%29%5Ctimes+n&bg=ffffff&fg=333333&s=0
"n!=1\\times 2\\times...(n-1)\\times n"). In the first half of the 1700s
it was noticed that these discrete points of the factorial function
seemed to define a curve. But the question was how does one find the
intermediate points of the curve like say 2.5\!. The interest in this
type of interpolation problem was likely initiated by Newton in England
and passed on to his junior associate, the Frenchman de Moivre. In
course of his study of probability de Moivre discovered the first
continuous function that was an approximate fit to the discrete
factorials:  
![n\! \\sim k\\cdot
\\sqrt{n}\\left(\\dfrac{n}{e}\\right)^n](https://s0.wp.com/latex.php?latex=n%21+%5Csim+k%5Ccdot+%5Csqrt%7Bn%7D%5Cleft%28%5Cdfrac%7Bn%7D%7Be%7D%5Cright%29%5En&bg=ffffff&fg=333333&s=0
"n! \\sim k\\cdot \\sqrt{n}\\left(\\dfrac{n}{e}\\right)^n"); where
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") is
a constant.  
His junior associate Stirling after some experimentation refined the
value of the constant as
![k=\\sqrt{2\\pi}](https://s0.wp.com/latex.php?latex=k%3D%5Csqrt%7B2%5Cpi%7D&bg=ffffff&fg=333333&s=0
"k=\\sqrt{2\\pi}") leading to many people wrongly attributing the
formula to him instead of de Moivre.

In this context we might note that Srinivasa Ramanujan discovered
another close approximation for the factorial function:  
![y=
\\dfrac{\\log(\\pi)}{2}-n+n\\log(n)+\\dfrac{\\log(n(1+4n(1+2n)))}{6};
\\; n\! \\approx
e^y](https://s0.wp.com/latex.php?latex=y%3D+%5Cdfrac%7B%5Clog%28%5Cpi%29%7D%7B2%7D-n%2Bn%5Clog%28n%29%2B%5Cdfrac%7B%5Clog%28n%281%2B4n%281%2B2n%29%29%29%7D%7B6%7D%3B+%5C%3B+n%21+%5Capprox+e%5Ey&bg=ffffff&fg=333333&s=0
"y= \\dfrac{\\log(\\pi)}{2}-n+n\\log(n)+\\dfrac{\\log(n(1+4n(1+2n)))}{6}; \\; n! \\approx e^y")

This formula of de Moivre indicated how the curve fitting the discrete
factorials should approximately look at intermediate values. However,
the precise fitting function was a problem baffled all attempts made by
Stirling, Daniel Bernoulli and Goldbach. Finally, in 1729 CE Goldbach
brought the problem to the 22 year old Leonhard Euler’s attention in his
letter from Moscow to the latter at St. Petersburg. Euler, giving a
taste of his unrivaled greatness, solved the problem in his letters
responding to Goldbach the same year and the next year published a
detailed paper on his use of “higher” calculus to solve the problem.
Answer to the general interpolation problem was the Gamma function
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)"); In modern notation
![n\!=\\Gamma(n+1)](https://s0.wp.com/latex.php?latex=n%21%3D%5CGamma%28n%2B1%29&bg=ffffff&fg=333333&s=0
"n!=\\Gamma(n+1)") and the values of the function at intermediate
positions provides the smooth interpolation between the discrete
factorial values.

One of Euler’s definitions of
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") was the Eulerian integral:  
![\\Gamma(x)=\\displaystyle \\int\_0^\\infty e^{-t}t^{x-1}
dt](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29%3D%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Dt%5E%7Bx-1%7D+dt&bg=ffffff&fg=333333&s=0
"\\Gamma(x)=\\displaystyle \\int_0^\\infty e^{-t}t^{x-1} dt")

While there is no general way of solving this integral one can see the
following:  
If
![x=1](https://s0.wp.com/latex.php?latex=x%3D1&bg=ffffff&fg=333333&s=0
"x=1"), ![\\Gamma(1)=\\displaystyle \\int\_0^\\infty e^{-t}dt=-e^{-t}
\\Bigr
|\_0^\\infty=0-(-1)=1](https://s0.wp.com/latex.php?latex=%5CGamma%281%29%3D%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Ddt%3D-e%5E%7B-t%7D+%5CBigr+%7C_0%5E%5Cinfty%3D0-%28-1%29%3D1&bg=ffffff&fg=333333&s=0
"\\Gamma(1)=\\displaystyle \\int_0^\\infty e^{-t}dt=-e^{-t} \\Bigr |_0^\\infty=0-(-1)=1")

Now, if we make the substitution ![x\\rightarrow
x+1](https://s0.wp.com/latex.php?latex=x%5Crightarrow+x%2B1&bg=ffffff&fg=333333&s=0
"x\\rightarrow x+1") then we get:  
![\\Gamma(x+1)=\\displaystyle \\int\_0^\\infty e^{-t}t^{x}
dt](https://s0.wp.com/latex.php?latex=%5CGamma%28x%2B1%29%3D%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Dt%5E%7Bx%7D+dt&bg=ffffff&fg=333333&s=0
"\\Gamma(x+1)=\\displaystyle \\int_0^\\infty e^{-t}t^{x} dt"); on which
we use integration by parts,  
![\\int u dv = u\\cdot v - \\int v du
](https://s0.wp.com/latex.php?latex=%5Cint+u+dv+%3D+u%5Ccdot+v+-+%5Cint+v+du+&bg=ffffff&fg=333333&s=0
"\\int u dv = u\\cdot v - \\int v du "),  
thus for the above we have:  
![\\displaystyle -\\int\_0^\\infty e^{-t}t^{x} dt=e^{-t}t^{x}\\Bigr
|\_0^\\infty- \\int\_0^\\infty e^{-t}xt^{x-1} dt=-e^{-t}t^{x}\\Bigr
|\_0^\\infty+x \\int\_0^\\infty e^{-t}t^{x-1}dt =\\lim\_{t \\to \\infty}
-\\dfrac{t^x}{e^t}-0^x\\cdot e^{-0}+
x\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+-%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Dt%5E%7Bx%7D+dt%3De%5E%7B-t%7Dt%5E%7Bx%7D%5CBigr+%7C_0%5E%5Cinfty-+%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Dxt%5E%7Bx-1%7D+dt%3D-e%5E%7B-t%7Dt%5E%7Bx%7D%5CBigr+%7C_0%5E%5Cinfty%2Bx+%5Cint_0%5E%5Cinfty+e%5E%7B-t%7Dt%5E%7Bx-1%7Ddt+%3D%5Clim_%7Bt+%5Cto+%5Cinfty%7D+-%5Cdfrac%7Bt%5Ex%7D%7Be%5Et%7D-0%5Ex%5Ccdot+e%5E%7B-0%7D%2B+x%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\displaystyle -\\int_0^\\infty e^{-t}t^{x} dt=e^{-t}t^{x}\\Bigr |_0^\\infty- \\int_0^\\infty e^{-t}xt^{x-1} dt=-e^{-t}t^{x}\\Bigr |_0^\\infty+x \\int_0^\\infty e^{-t}t^{x-1}dt =\\lim_{t \\to \\infty} -\\dfrac{t^x}{e^t}-0^x\\cdot e^{-0}+ x\\Gamma(x)")  
Since, in the above expression the exponential function in the
denominator will always catch with the power function in the numerator
that limit will be 0. Thus we get,  
![\\Gamma(x+1)=x\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%2B1%29%3Dx%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x+1)=x\\Gamma(x)")

One will notice right away that this captures the discrete factorial
function when
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x") is
a natural number. Further, all we need to do is to somehow obtain the
values for
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") from 0:1 then we can use the above relationship to extend
it for other positive intervals. Thus, Euler’s
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") provides a function to extrapolate the factorial for the
intermediate values but the question remains as the how do we get the
values from 0:1. One of those values
![x=\\tfrac{1}{2}](https://s0.wp.com/latex.php?latex=x%3D%5Ctfrac%7B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x=\\tfrac{1}{2}") can be obtained using relatively straightforward
means from the Eulerian integral:  
![\\Gamma(\\tfrac{1}{2})= \\displaystyle \\int\_0^\\infty
\\dfrac{e^{-t}}{\\sqrt{t}}dt](https://s0.wp.com/latex.php?latex=%5CGamma%28%5Ctfrac%7B1%7D%7B2%7D%29%3D+%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+%5Cdfrac%7Be%5E%7B-t%7D%7D%7B%5Csqrt%7Bt%7D%7Ddt&bg=ffffff&fg=333333&s=0
"\\Gamma(\\tfrac{1}{2})= \\displaystyle \\int_0^\\infty \\dfrac{e^{-t}}{\\sqrt{t}}dt")  
We resort to the substitution ![t=u^2 \\; \\therefore dt=2u
du](https://s0.wp.com/latex.php?latex=t%3Du%5E2+%5C%3B+%5Ctherefore+dt%3D2u+du&bg=ffffff&fg=333333&s=0
"t=u^2 \\; \\therefore dt=2u du")  
![\\therefore \\Gamma(\\tfrac{1}{2})= \\displaystyle 2 \\int\_0^\\infty
e^{-u^2}
du](https://s0.wp.com/latex.php?latex=%5Ctherefore+%5CGamma%28%5Ctfrac%7B1%7D%7B2%7D%29%3D+%5Cdisplaystyle+2+%5Cint_0%5E%5Cinfty+e%5E%7B-u%5E2%7D+du&bg=ffffff&fg=333333&s=0
"\\therefore \\Gamma(\\tfrac{1}{2})= \\displaystyle 2 \\int_0^\\infty e^{-u^2} du")  
Remarkably, the core of above integral is the one specifying half the
area under a Gaussian Bell curve; so it evaluates to
![\\tfrac{\\sqrt{\\pi}}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Csqrt%7B%5Cpi%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\sqrt{\\pi}}{2}")  
![\\therefore \\Gamma(\\tfrac{1}{2})=2
\\dfrac{\\sqrt{\\pi}}{2}=\\sqrt{\\pi}](https://s0.wp.com/latex.php?latex=%5Ctherefore+%5CGamma%28%5Ctfrac%7B1%7D%7B2%7D%29%3D2+%5Cdfrac%7B%5Csqrt%7B%5Cpi%7D%7D%7B2%7D%3D%5Csqrt%7B%5Cpi%7D&bg=ffffff&fg=333333&s=0
"\\therefore \\Gamma(\\tfrac{1}{2})=2 \\dfrac{\\sqrt{\\pi}}{2}=\\sqrt{\\pi}")  
This is one of those deep results that when you see and imbibe for the
first time it produces a profound effect on you — how the problem of
generalizing the factorial function leads you to the squaring of the
circle and the limit from the famed central limit theorem i.e. the
normal distribution. Thus, in the least we can get ![\\Gamma(1.5),
\\Gamma(2.5)](https://s0.wp.com/latex.php?latex=%5CGamma%281.5%29%2C+%5CGamma%282.5%29&bg=ffffff&fg=333333&s=0
"\\Gamma(1.5), \\Gamma(2.5)") etc trivially using the above recurrence
relationship.

However, Euler himself obtained
![\\Gamma(\\tfrac{1}{2})](https://s0.wp.com/latex.php?latex=%5CGamma%28%5Ctfrac%7B1%7D%7B2%7D%29&bg=ffffff&fg=333333&s=0
"\\Gamma(\\tfrac{1}{2})") by using a product formula. It was such
product formulae and other series which Euler, Gauss and their
successors used to provide the other values of
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)"). Gauss with his student, the astronomer Friedrich Nicolai,
who was a calculating prodigy, prepared tables of the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") which served the mathematical community throughout the
1800s. In his investigations on
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") Gauss, building on Euler’s product formula developed the
famous product formula:  
![\\Gamma(x)=\\displaystyle \\lim\_{n \\to \\infty} \\dfrac{n^x
n\!}{x(x+1)...(x+n)}](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29%3D%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+%5Cdfrac%7Bn%5Ex+n%21%7D%7Bx%28x%2B1%29...%28x%2Bn%29%7D&bg=ffffff&fg=333333&s=0
"\\Gamma(x)=\\displaystyle \\lim_{n \\to \\infty} \\dfrac{n^x n!}{x(x+1)...(x+n)}")  
This formula is quite slow in converging and rakes up huge numbers in
the calculation: e.g. with
![n=100](https://s0.wp.com/latex.php?latex=n%3D100&bg=ffffff&fg=333333&s=0
"n=100") we get ![\\Gamma(0.1) \\approx
9.51](https://s0.wp.com/latex.php?latex=%5CGamma%280.1%29+%5Capprox+9.51&bg=ffffff&fg=333333&s=0
"\\Gamma(0.1) \\approx 9.51") correct to 2 places after the decimal
point when rounded.

It is this kind of product formulae that bring us back to our original
question of interpolation of the square root spiral. Armed with his deep
knowledge of the history of the methods of Euler and Gauss in attacking
the Gamma function, Davis solved the SRS problem by producing a product
formula, which for a given number
![\\alpha](https://s0.wp.com/latex.php?latex=%5Calpha&bg=ffffff&fg=333333&s=0
"\\alpha"), which corresponds to the natural numbers 0,1,2,3… or any
value between them, produces the exact coordinates of the SRS in the
complex plane. This remarkable formula is:

![T(\\alpha)=\\displaystyle \\prod\_{k=1}^{\\infty}
\\dfrac{1+\\dfrac{i}{\\sqrt{k}}}{1+\\dfrac{i}{\\sqrt{k+\\alpha-1}}}](https://s0.wp.com/latex.php?latex=T%28%5Calpha%29%3D%5Cdisplaystyle+%5Cprod_%7Bk%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%2B%5Cdfrac%7Bi%7D%7B%5Csqrt%7Bk%7D%7D%7D%7B1%2B%5Cdfrac%7Bi%7D%7B%5Csqrt%7Bk%2B%5Calpha-1%7D%7D%7D&bg=ffffff&fg=333333&s=0
"T(\\alpha)=\\displaystyle \\prod_{k=1}^{\\infty} \\dfrac{1+\\dfrac{i}{\\sqrt{k}}}{1+\\dfrac{i}{\\sqrt{k+\\alpha-1}}}"),
where ![i=\\sqrt{-1}, \\alpha \\ge
0](https://s0.wp.com/latex.php?latex=i%3D%5Csqrt%7B-1%7D%2C+%5Calpha+%5Cge+0&bg=ffffff&fg=333333&s=0
"i=\\sqrt{-1}, \\alpha \\ge 0")  
Here
![|T(\\alpha)|=\\sqrt{\\alpha}](https://s0.wp.com/latex.php?latex=%7CT%28%5Calpha%29%7C%3D%5Csqrt%7B%5Calpha%7D&bg=ffffff&fg=333333&s=0
"|T(\\alpha)|=\\sqrt{\\alpha}") This captures the basic square root
radius or hypotenuse seen in the discrete SRS.

Strikingly, analogous to the Gamma function the SRS equation also has a
recurrence formula:  
![T(\\alpha+1)=\\left(1+\\dfrac{i}{\\sqrt{\\alpha}}\\right)T(\\alpha)](https://s0.wp.com/latex.php?latex=T%28%5Calpha%2B1%29%3D%5Cleft%281%2B%5Cdfrac%7Bi%7D%7B%5Csqrt%7B%5Calpha%7D%7D%5Cright%29T%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"T(\\alpha+1)=\\left(1+\\dfrac{i}{\\sqrt{\\alpha}}\\right)T(\\alpha)")  
From these relationships we get:  
![|T(\\alpha+1)-T(\\alpha)|=|T(\\alpha)+\\dfrac{iT(\\alpha)}{\\sqrt{\\alpha}}-T(\\alpha)|=|i|\\dfrac{\\sqrt{\\alpha}}{\\sqrt{\\alpha}}=-i\\cdot
i=1](https://s0.wp.com/latex.php?latex=%7CT%28%5Calpha%2B1%29-T%28%5Calpha%29%7C%3D%7CT%28%5Calpha%29%2B%5Cdfrac%7BiT%28%5Calpha%29%7D%7B%5Csqrt%7B%5Calpha%7D%7D-T%28%5Calpha%29%7C%3D%7Ci%7C%5Cdfrac%7B%5Csqrt%7B%5Calpha%7D%7D%7B%5Csqrt%7B%5Calpha%7D%7D%3D-i%5Ccdot+i%3D1&bg=ffffff&fg=333333&s=0
"|T(\\alpha+1)-T(\\alpha)|=|T(\\alpha)+\\dfrac{iT(\\alpha)}{\\sqrt{\\alpha}}-T(\\alpha)|=|i|\\dfrac{\\sqrt{\\alpha}}{\\sqrt{\\alpha}}=-i\\cdot i=1")  
This captures the basic relationship of the successive natural numbers
in the discrete SRS. Like with
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") all we need to do is to calculate the values of
![T(\\alpha)](https://s0.wp.com/latex.php?latex=T%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"T(\\alpha)") from 0:1. Then using the recurrence relationship we can
extend it for all other values.

Like the Gauss product formula for
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") the
![T(\\alpha)](https://s0.wp.com/latex.php?latex=T%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"T(\\alpha)") formula is also slow converging. To get reasonable
accuracy we need to calculate at least 20000 terms of the above product.
E.g. with this computation we get
![T(2)=1.414213562373095](https://s0.wp.com/latex.php?latex=T%282%29%3D1.414213562373095&bg=ffffff&fg=333333&s=0
"T(2)=1.414213562373095"). Thankfully, this can be done quite fast with
even your modern laptop and thus we get the continuous SRS in figure 3.

![Sqrt\_spiral](https://manasataramgini.files.wordpress.com/2017/07/sqrt_spiral.png?w=640)Figure
3

With this in place we can look at a few other things. For example, if
one plots the positions of the perfect squares (those which Theaetetus
mentions to Socrates) on the SRS we surprisingly find them to lie on a
triradiate pattern of gently curving spirals radiating from the number
1. The three arms have respectively:

![\\alpha=4, 25, 64, 121...\\rightarrow
9k^2+12k+4](https://s0.wp.com/latex.php?latex=%5Calpha%3D4%2C+25%2C+64%2C+121...%5Crightarrow+9k%5E2%2B12k%2B4&bg=ffffff&fg=333333&s=0
"\\alpha=4, 25, 64, 121...\\rightarrow 9k^2+12k+4")  
![\\alpha=9, 36, 81, 144... \\rightarrow
9k^2+18k+9](https://s0.wp.com/latex.php?latex=%5Calpha%3D9%2C+36%2C+81%2C+144...+%5Crightarrow+9k%5E2%2B18k%2B9&bg=ffffff&fg=333333&s=0
"\\alpha=9, 36, 81, 144... \\rightarrow 9k^2+18k+9")  
![\\alpha=16, 49, 100, 169... \\rightarrow
9k^2+24k+16](https://s0.wp.com/latex.php?latex=%5Calpha%3D16%2C+49%2C+100%2C+169...+%5Crightarrow+9k%5E2%2B24k%2B16&bg=ffffff&fg=333333&s=0
"\\alpha=16, 49, 100, 169... \\rightarrow 9k^2+24k+16") where
![k=0,1,2,3...](https://s0.wp.com/latex.php?latex=k%3D0%2C1%2C2%2C3...&bg=ffffff&fg=333333&s=0
"k=0,1,2,3...")

The next question is how does one capture the second branch of the SRS
which was obtained in its discrete form via reflection on the subsequent
hypotenuse. For this Davis figured out that one could use a generalized
reflection formulation which gives
![S(\\alpha)](https://s0.wp.com/latex.php?latex=S%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"S(\\alpha)") i.e. the position in the complex plane for the second
branch:  
![S(\\alpha)=\\dfrac{1+\\dfrac{i}{\\sqrt{\\alpha}}}{1-\\dfrac{i}{\\sqrt{\\alpha}}}T(\\alpha)](https://s0.wp.com/latex.php?latex=S%28%5Calpha%29%3D%5Cdfrac%7B1%2B%5Cdfrac%7Bi%7D%7B%5Csqrt%7B%5Calpha%7D%7D%7D%7B1-%5Cdfrac%7Bi%7D%7B%5Csqrt%7B%5Calpha%7D%7D%7DT%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"S(\\alpha)=\\dfrac{1+\\dfrac{i}{\\sqrt{\\alpha}}}{1-\\dfrac{i}{\\sqrt{\\alpha}}}T(\\alpha)")  
Thus once we have
![T(\\alpha)](https://s0.wp.com/latex.php?latex=T%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"T(\\alpha)") we can now use this reflection formula to get the points
on second branch. The thus computed complete continuous SRS is shown in
Figure 4.

![Sqrt\_spiral\_2](https://manasataramgini.files.wordpress.com/2017/07/sqrt_spiral_2.png?w=640)Figure
4

Here again one can see a parallel to the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)"): How does one gets its values for negative
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x").
This brings out a remarkable connection between the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") and the trigonometric functions in analogous reflection
formula:

![\\Gamma(-x)=-\\dfrac{\\pi}{\\sin(\\pi
x)x\\Gamma(x)}](https://s0.wp.com/latex.php?latex=%5CGamma%28-x%29%3D-%5Cdfrac%7B%5Cpi%7D%7B%5Csin%28%5Cpi+x%29x%5CGamma%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\Gamma(-x)=-\\dfrac{\\pi}{\\sin(\\pi x)x\\Gamma(x)}")

Thus, once we know the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") for positive values we can get the negative ones by this
reflection formula. Unlike the positive
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
for which grows explosively we see oscillations in negative
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
arising from the trigonometric connection.

Davis then investigated the slope of tangent to the SRS at the point
where it cuts the x-axis for the first time after the origin, i.e. the
derivative of
![T(\\alpha)](https://s0.wp.com/latex.php?latex=T%28%5Calpha%29&bg=ffffff&fg=333333&s=0
"T(\\alpha)") at 1,
![T'(1)](https://s0.wp.com/latex.php?latex=T%27%281%29&bg=ffffff&fg=333333&s=0
"T'(1)"). Gautschi termed this number
![\\theta](https://s0.wp.com/latex.php?latex=%5Ctheta&bg=ffffff&fg=333333&s=0
"\\theta") in the honor of Theodorus and it is given by the simple but
interesting series:  
![\\theta=\\displaystyle
\\sum\_{k=1}^{\\infty}\\dfrac{1}{k^{3/2}+\\sqrt{k}}](https://s0.wp.com/latex.php?latex=%5Ctheta%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%7B%5Cinfty%7D%5Cdfrac%7B1%7D%7Bk%5E%7B3%2F2%7D%2B%5Csqrt%7Bk%7D%7D&bg=ffffff&fg=333333&s=0
"\\theta=\\displaystyle \\sum_{k=1}^{\\infty}\\dfrac{1}{k^{3/2}+\\sqrt{k}}")

This is an awfully slow converging series: by computing the above sum
for 1000000 terms we obtain rounded off to two places after decimal
point
![\\theta=1.86](https://s0.wp.com/latex.php?latex=%5Ctheta%3D1.86&bg=ffffff&fg=333333&s=0
"\\theta=1.86"), which is correct for those two places. There are
complicated, faster-converging methods which have been published in
computer science studies. One such discovered by Phillips involves
getting the sum
![\\theta\_{n-1}](https://s0.wp.com/latex.php?latex=%5Ctheta_%7Bn-1%7D&bg=ffffff&fg=333333&s=0
"\\theta_{n-1}") as above till
![k=n-1](https://s0.wp.com/latex.php?latex=k%3Dn-1&bg=ffffff&fg=333333&s=0
"k=n-1") where
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
relatively small and then adding a monstrous remainder term derived from
the Euler summation formula:

![\\theta=\\theta\_{n-1}+\\dfrac{1}{\\sqrt{n}}\\left(2-\\dfrac{1}{6n}+\\dfrac{1}{40n^2}+\\dfrac{1}{168n^3}-\\dfrac{5}{1152n^4}-\\dfrac{3}{1408n^5}-\\dfrac{303}{66560n^6}\\right)](https://s0.wp.com/latex.php?latex=%5Ctheta%3D%5Ctheta_%7Bn-1%7D%2B%5Cdfrac%7B1%7D%7B%5Csqrt%7Bn%7D%7D%5Cleft%282-%5Cdfrac%7B1%7D%7B6n%7D%2B%5Cdfrac%7B1%7D%7B40n%5E2%7D%2B%5Cdfrac%7B1%7D%7B168n%5E3%7D-%5Cdfrac%7B5%7D%7B1152n%5E4%7D-%5Cdfrac%7B3%7D%7B1408n%5E5%7D-%5Cdfrac%7B303%7D%7B66560n%5E6%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\theta=\\theta_{n-1}+\\dfrac{1}{\\sqrt{n}}\\left(2-\\dfrac{1}{6n}+\\dfrac{1}{40n^2}+\\dfrac{1}{168n^3}-\\dfrac{5}{1152n^4}-\\dfrac{3}{1408n^5}-\\dfrac{303}{66560n^6}\\right)")

Plugging
![n=15](https://s0.wp.com/latex.php?latex=n%3D15&bg=ffffff&fg=333333&s=0
"n=15") we now effortlessly get ![\\theta=
1.8600250790563](https://s0.wp.com/latex.php?latex=%5Ctheta%3D+1.8600250790563&bg=ffffff&fg=333333&s=0
"\\theta= 1.8600250790563") which is correct to 9 decimal places after
the point.

Again there is a parallel to the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)"). Euler discovered that the slope of the tangent to
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") at
![x=1](https://s0.wp.com/latex.php?latex=x%3D1&bg=ffffff&fg=333333&s=0
"x=1") is
![\\Gamma'(1)=-\\gamma](https://s0.wp.com/latex.php?latex=%5CGamma%27%281%29%3D-%5Cgamma&bg=ffffff&fg=333333&s=0
"\\Gamma'(1)=-\\gamma"). This
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") is the famous Euler’s constant and is similarly given by an
infinite sum:

![\\gamma =\\displaystyle \\sum\_{k=1}^\\infty
\\dfrac{1}{k}-\\log\\left(1+\\dfrac{1}{k}\\right)](https://s0.wp.com/latex.php?latex=%5Cgamma+%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B1%7D%7Bk%7D-%5Clog%5Cleft%281%2B%5Cdfrac%7B1%7D%7Bk%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\gamma =\\displaystyle \\sum_{k=1}^\\infty \\dfrac{1}{k}-\\log\\left(1+\\dfrac{1}{k}\\right)")

This sum converges more quickly: with 100 terms we get rounded of to 4
places
![\\gamma=0.5772](https://s0.wp.com/latex.php?latex=%5Cgamma%3D0.5772&bg=ffffff&fg=333333&s=0
"\\gamma=0.5772") which is correct for that many places after the
decimal point. This
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") is an important constant in science coming up a lot not just
in the calculation of
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") but also the famed zeta function and various statistical
distributions. Euler with his prodigious mental computational abilities
attacked it several times in his life computing it to 16 decimal places
before his death. Later the Mascheroni computed it to more places. Gauss
himself capable of extraordinary numeration found that Mascheroni had
made a mistake in the 21st place and asked his student, the astronomer
Nicolai, who was a human computer of his age to to verify his result.
Nicolai obtained the value correct to 40 decimal places, a record which
stood for 50 years. Ramanujan discovered some really dramatic looking
formulae relating to
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma"), including those with fast convergence; however we shall not
talk about them here.

![Sqrt\_spiral\_pispacing](https://manasataramgini.files.wordpress.com/2017/07/sqrt_spiral_pispacing.png?w=640)Figure
5

In figure 5 we see that each successive turn of the SRS is greater than
the previous one by a value of nearly
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). The SRS turn separation indeed converges towards
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") asymptotically. This leads to the question of whether there is a
way to calculate the number of discrete radii that lie within each turn
of the SRS. For this Hlawka calculated something called
Schneckenkonstante ![K =
-2.157782](https://s0.wp.com/latex.php?latex=K+%3D+-2.157782&bg=ffffff&fg=333333&s=0
"K = -2.157782") based on which Kochiemba/Wilson have computed the
sequence of the number of discrete radii (
![nr\[n\]](https://s0.wp.com/latex.php?latex=nr%5Bn%5D&bg=ffffff&fg=333333&s=0
"nr[n]"); OEIS: A072895) contained within the turn
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") of
the SRS thus:  
![nr\[n\]=\\text{trunc}\\left(\\left(n\\pi -\\dfrac{K}{2}\\right)^2 -
\\dfrac{1}{6}\\right)](https://s0.wp.com/latex.php?latex=nr%5Bn%5D%3D%5Ctext%7Btrunc%7D%5Cleft%28%5Cleft%28n%5Cpi+-%5Cdfrac%7BK%7D%7B2%7D%5Cright%29%5E2+-+%5Cdfrac%7B1%7D%7B6%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"nr[n]=\\text{trunc}\\left(\\left(n\\pi -\\dfrac{K}{2}\\right)^2 - \\dfrac{1}{6}\\right)")  
This yields the sequence: 0, 17, 54, 110, 186, 281, 396, 532, 686, 861,
1055… as the number of discrete radii per turn. The difference between
the square roots of successive terms of this sequence (Figure 6)
fluctuates around
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") with the fluctuations decreasing in amplitude as the number of
turns increase. The value can come quite close to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). For the first 100 turns
![\\sqrt{nr\[85\]}-\\sqrt{nr\[84\]}=\\sqrt{70210}-\\sqrt{68555}=3.1415990193488](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bnr%5B85%5D%7D-%5Csqrt%7Bnr%5B84%5D%7D%3D%5Csqrt%7B70210%7D-%5Csqrt%7B68555%7D%3D3.1415990193488&bg=ffffff&fg=333333&s=0
"\\sqrt{nr[85]}-\\sqrt{nr[84]}=\\sqrt{70210}-\\sqrt{68555}=3.1415990193488"),
which comes within ![6.366 \\times
10^{-6}](https://s0.wp.com/latex.php?latex=6.366+%5Ctimes+10%5E%7B-6%7D&bg=ffffff&fg=333333&s=0
"6.366 \\times 10^{-6}") of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi").

![Sqrt\_spiral\_pi\_convergence](https://manasataramgini.files.wordpress.com/2017/07/sqrt_spiral_pi_convergence.png?w=640)Figure
6

Finally, coming back to where we started, there is a simple a map in the
complex plane discovered by Davis that produces discrete points of all
manner of spirals including the SRS:  
![z\_{n+1}=az\_n+\\dfrac{bz\_n}{|zn|}](https://s0.wp.com/latex.php?latex=z_%7Bn%2B1%7D%3Daz_n%2B%5Cdfrac%7Bbz_n%7D%7B%7Czn%7C%7D&bg=ffffff&fg=333333&s=0
"z_{n+1}=az_n+\\dfrac{bz_n}{|zn|}")  
Here ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") and
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
are constants or vary with each iteration. When ![a=1;\\; b=i; \\;
z\_0=1](https://s0.wp.com/latex.php?latex=a%3D1%3B%5C%3B+b%3Di%3B+%5C%3B+z_0%3D1&bg=ffffff&fg=333333&s=0
"a=1;\\; b=i; \\; z_0=1") we get the discrete points on the SRS (Figure
7). When ![|a| \\ne 1;\\; Im(a) \\ne 0; \\;
b=0](https://s0.wp.com/latex.php?latex=%7Ca%7C+%5Cne+1%3B%5C%3B+Im%28a%29+%5Cne+0%3B+%5C%3B+b%3D0&bg=ffffff&fg=333333&s=0
"|a| \\ne 1;\\; Im(a) \\ne 0; \\; b=0") we get discrete points on the
logarithmic spiral discovered by Rene Descartes. When ![|a|=1; \\; a
\\ne 1,-1; \\; b=k\\cdot a;
k\>0](https://s0.wp.com/latex.php?latex=%7Ca%7C%3D1%3B+%5C%3B+a+%5Cne+1%2C-1%3B+%5C%3B+b%3Dk%5Ccdot+a%3B+k%3E0&bg=ffffff&fg=333333&s=0
"|a|=1; \\; a \\ne 1,-1; \\; b=k\\cdot a; k\>0") we get an Archimedean
spiral. When
![a=\\cos\\left(\\tfrac{\\pi}{4}\\right)+i\\sin\\left(\\tfrac{\\pi}{4}\\right);
b=\\overline{a},
z\_0=1](https://s0.wp.com/latex.php?latex=a%3D%5Ccos%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B4%7D%5Cright%29%2Bi%5Csin%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B4%7D%5Cright%29%3B+b%3D%5Coverline%7Ba%7D%2C+z_0%3D1&bg=ffffff&fg=333333&s=0
"a=\\cos\\left(\\tfrac{\\pi}{4}\\right)+i\\sin\\left(\\tfrac{\\pi}{4}\\right); b=\\overline{a}, z_0=1")
we get something that grows like the SRS but has a more complex wave
like internal pattern (Figure 7). This is reminiscent of the
convergences seen in [the Henon
map](https://manasataramgini.wordpress.com/2016/12/18/some-reminiscences-of-our-study-of-chaotic-maps-1/),
only that these are divergences. When ![a=1.1+.3i; \\; b=-a; \\;
z\_0=1.1](https://s0.wp.com/latex.php?latex=a%3D1.1%2B.3i%3B+%5C%3B+b%3D-a%3B+%5C%3B+z_0%3D1.1&bg=ffffff&fg=333333&s=0
"a=1.1+.3i; \\; b=-a; \\; z_0=1.1") the map shows chaotic behavior but
the attractor is localized to 4 concentric circular shells (Figure 7).
Finally, when
![a=\\cos\\left(\\tfrac{\\pi}{4}\\right)+i\\sin\\left(\\tfrac{\\pi}{4}\\right)](https://s0.wp.com/latex.php?latex=a%3D%5Ccos%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B4%7D%5Cright%29%2Bi%5Csin%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B4%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"a=\\cos\\left(\\tfrac{\\pi}{4}\\right)+i\\sin\\left(\\tfrac{\\pi}{4}\\right)")
and ![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0
"b") varies with each iteration
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") as
![b=\\sin(n)+\\sin\\left(\\tfrac{n}{5}\\right); \\;
z\_0=1](https://s0.wp.com/latex.php?latex=b%3D%5Csin%28n%29%2B%5Csin%5Cleft%28%5Ctfrac%7Bn%7D%7B5%7D%5Cright%29%3B+%5C%3B+z_0%3D1&bg=ffffff&fg=333333&s=0
"b=\\sin(n)+\\sin\\left(\\tfrac{n}{5}\\right); \\; z_0=1") we get a
complex braided spiral arrangement of the points (Figure 7).

![Sqrt\_Spiral\_cmplex\_map](https://manasataramgini.files.wordpress.com/2017/07/sqrt_spiral_cmplex_map.png?w=640)Figure
7
