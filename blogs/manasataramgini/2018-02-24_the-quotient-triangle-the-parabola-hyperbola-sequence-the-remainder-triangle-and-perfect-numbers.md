+++
title = "The quotient triangle, the parabola-hyperbola sequence, the remainder triangle and perfect numbers"

+++
**The quotient triangle**  
Consider a positive integer
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
Then for all
![k=1,2,3...n](https://s0.wp.com/latex.php?latex=k%3D1%2C2%2C3...n&bg=ffffff&fg=333333&s=0
"k=1,2,3...n") do the floor operation ![T\_q\[n\]= \\left\\lfloor
\\tfrac{n}{k}\\right\\rfloor](https://s0.wp.com/latex.php?latex=T_q%5Bn%5D%3D+%5Cleft%5Clfloor+%5Ctfrac%7Bn%7D%7Bk%7D%5Cright%5Crfloor&bg=ffffff&fg=333333&s=0
"T_q[n]= \\left\\lfloor \\tfrac{n}{k}\\right\\rfloor"). Say
![n=10](https://s0.wp.com/latex.php?latex=n%3D10&bg=ffffff&fg=333333&s=0
"n=10"), we get ![T\_q\[10\]=10, 5, 3, 2, 2, 1, 1, 1, 1,
1](https://s0.wp.com/latex.php?latex=T_q%5B10%5D%3D10%2C+5%2C+3%2C+2%2C+2%2C+1%2C+1%2C+1%2C+1%2C+1&bg=ffffff&fg=333333&s=0
"T_q[10]=10, 5, 3, 2, 2, 1, 1, 1, 1, 1"), a sequence of quotients of the
division ![n \\div
k](https://s0.wp.com/latex.php?latex=n+%5Cdiv+k&bg=ffffff&fg=333333&s=0
"n \\div k"). If we do this for all ![n=1, 2, 3, 4
...](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3%2C+4+...&bg=ffffff&fg=333333&s=0
"n=1, 2, 3, 4 ...") we get the quotient triangular array
![T\_q\[n,k\]](https://s0.wp.com/latex.php?latex=T_q%5Bn%2Ck%5D&bg=ffffff&fg=333333&s=0
"T_q[n,k]") whose top few elements are show below.

![\\begin{tabular}{|\*{10}{r|}} \\cline{1-1} 1\\\\ \\cline{1-2} 2 &
1\\\\ \\cline{1-3} 3 & 1 & 1\\\\ \\cline{1-4} 4 & 2 & 1 & 1\\\\
\\cline{1-5} 5 & 2 & 1 & 1 & 1\\\\ \\cline{1-6} 6 & 3 & 2 & 1 & 1 &
1\\\\ \\cline{1-7} 7 & 3 & 2 & 1 & 1 & 1 & 1\\\\ \\cline{1-8} 8 & 4 & 2
& 2 & 1 & 1 & 1 & 1\\\\ \\cline{1-9} 9 & 4 & 3 & 2 & 1 & 1 & 1 & 1 &
1\\\\ \\cline{1-10} 10 & 5 & 3 & 2 & 2 & 1 & 1 & 1 & 1 & 1\\\\
\\cline{1-10}
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7C%2A%7B10%7D%7Br%7C%7D%7D+%5Ccline%7B1-1%7D+1%5C%5C+%5Ccline%7B1-2%7D+2+%26+1%5C%5C+%5Ccline%7B1-3%7D+3+%26+1+%26+1%5C%5C+%5Ccline%7B1-4%7D+4+%26+2+%26+1+%26+1%5C%5C+%5Ccline%7B1-5%7D+5+%26+2+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-6%7D+6+%26+3+%26+2+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-7%7D+7+%26+3+%26+2+%26+1+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-8%7D+8+%26+4+%26+2+%26+2+%26+1+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-9%7D+9+%26+4+%26+3+%26+2+%26+1+%26+1+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-10%7D+10+%26+5+%26+3+%26+2+%26+2+%26+1+%26+1+%26+1+%26+1+%26+1%5C%5C+%5Ccline%7B1-10%7D+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|*{10}{r|}} \\cline{1-1} 1\\\\ \\cline{1-2} 2 & 1\\\\ \\cline{1-3} 3 & 1 & 1\\\\ \\cline{1-4} 4 & 2 & 1 & 1\\\\ \\cline{1-5} 5 & 2 & 1 & 1 & 1\\\\ \\cline{1-6} 6 & 3 & 2 & 1 & 1 & 1\\\\ \\cline{1-7} 7 & 3 & 2 & 1 & 1 & 1 & 1\\\\ \\cline{1-8} 8 & 4 & 2 & 2 & 1 & 1 & 1 & 1\\\\ \\cline{1-9} 9 & 4 & 3 & 2 & 1 & 1 & 1 & 1 & 1\\\\ \\cline{1-10} 10 & 5 & 3 & 2 & 2 & 1 & 1 & 1 & 1 & 1\\\\ \\cline{1-10} \\end{tabular}")

It is obvious that the first column
![T\_q\[n,1\]](https://s0.wp.com/latex.php?latex=T_q%5Bn%2C1%5D&bg=ffffff&fg=333333&s=0
"T_q[n,1]") is the sequence of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
itself. The second column
![T\_q\[n,2\]](https://s0.wp.com/latex.php?latex=T_q%5Bn%2C2%5D&bg=ffffff&fg=333333&s=0
"T_q[n,2]") is the sequence of positive integers, each repeated twice;
the third column
![T\_q\[n,3\]](https://s0.wp.com/latex.php?latex=T_q%5Bn%2C3%5D&bg=ffffff&fg=333333&s=0
"T_q[n,3]") is the sequence of positive integers, each repeated thrice;
so on.

It we linearize this triangular array we get the sequence ![f\_q= 1, 2,
1, 3, 1, 1, 4, 2, 1,
1...](https://s0.wp.com/latex.php?latex=f_q%3D+1%2C+2%2C+1%2C+3%2C+1%2C+1%2C+4%2C+2%2C+1%2C+1...&bg=ffffff&fg=333333&s=0
"f_q= 1, 2, 1, 3, 1, 1, 4, 2, 1, 1..."). Since each row of the
triangular array adds ![n=1, 2, 3,
4...](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3%2C+4...&bg=ffffff&fg=333333&s=0
"n=1, 2, 3, 4...") elements to the sequence, it grows as the sum of
numbers from 1:n. We see that the successive maxima are attained at the
following terms of
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q"): 1, 2, 4, 7, 11, 16, 22, 29, 37, 46, 56… We can plot
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") by placing the first term
![f\_q\[1\]](https://s0.wp.com/latex.php?latex=f_q%5B1%5D&bg=ffffff&fg=333333&s=0
"f_q[1]") at 0, i.e., its x-coordinate will be 0, while its y-coordinate
will be
![f\_q\[1\]](https://s0.wp.com/latex.php?latex=f_q%5B1%5D&bg=ffffff&fg=333333&s=0
"f_q[1]"); for ![x=1,
y=f\_q\[2\]](https://s0.wp.com/latex.php?latex=x%3D1%2C+y%3Df_q%5B2%5D&bg=ffffff&fg=333333&s=0
"x=1, y=f_q[2]") and so on. Based on the sum of integers 1:n we can show
that the successive maxima attained by the sequence would be bounded in
this plot by the parabola (Figure 1):

![y=\\dfrac{\\sqrt{1+8x}-1}{2}+1](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7B%5Csqrt%7B1%2B8x%7D-1%7D%7B2%7D%2B1&bg=ffffff&fg=333333&s=0
"y=\\dfrac{\\sqrt{1+8x}-1}{2}+1")

[![Quo\_Rem\_Fig1](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig1.png)Figure
1

This sequence
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") also features cycles of decaying values (Figure 1) between
successive maxima, starting from one maximum and going to 1 before
jumping back to the next maximum and decaying again. Since the quotients
are successively determined by ![n/1, n/2, n/3...3 = n\\big/ n/3, 2 =
n\\big/ n/2, 1 = n\\big/
1/n](https://s0.wp.com/latex.php?latex=n%2F1%2C+n%2F2%2C+n%2F3...3+%3D+n%5Cbig%2F+n%2F3%2C+2+%3D+n%5Cbig%2F+n%2F2%2C+1+%3D+n%5Cbig%2F+1%2Fn&bg=ffffff&fg=333333&s=0
"n/1, n/2, n/3...3 = n\\big/ n/3, 2 = n\\big/ n/2, 1 = n\\big/ 1/n"),
each cycle of the sequence of length
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
a discrete form of the rectangular hyperbola (Figure 2):

![y=\\dfrac{n}{x}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7Bn%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{n}{x}")

[![Quo\_Rem\_Fig2](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig2.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig2.png)Figure
2

Thus, we may term sequence
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") the parabola-hyperbola sequence. Since any ![n/2 \< k \\le
n](https://s0.wp.com/latex.php?latex=n%2F2+%3C+k+%5Cle+n&bg=ffffff&fg=333333&s=0
"n/2 \< k \\le n") will produce quotient 1, the fraction of 1s in
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") will converge to
![f(1)=1-1/2=1/2](https://s0.wp.com/latex.php?latex=f%281%29%3D1-1%2F2%3D1%2F2&bg=ffffff&fg=333333&s=0
"f(1)=1-1/2=1/2"); similarly, ![n/3 \< k \\le
n/2](https://s0.wp.com/latex.php?latex=n%2F3+%3C+k+%5Cle+n%2F2&bg=ffffff&fg=333333&s=0
"n/3 \< k \\le n/2") with produce quotient 2; hence, the fraction of 2s
in ![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") will converge to
![f(2)=1/2-1/3=1/6](https://s0.wp.com/latex.php?latex=f%282%29%3D1%2F2-1%2F3%3D1%2F6&bg=ffffff&fg=333333&s=0
"f(2)=1/2-1/3=1/6"). Thus, generally ![f(k) \\sim
\\tfrac{1}{k(k+1)}](https://s0.wp.com/latex.php?latex=f%28k%29+%5Csim+%5Ctfrac%7B1%7D%7Bk%28k%2B1%29%7D&bg=ffffff&fg=333333&s=0
"f(k) \\sim \\tfrac{1}{k(k+1)}").

We then define a summatory sequence
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") such that each term is the sum of the nth row of the
quotient triangular array
![T\_q](https://s0.wp.com/latex.php?latex=T_q&bg=ffffff&fg=333333&s=0
"T_q"):

![\\varsigma\[n\]=\\displaystyle \\sum\_{k=1}^n
T\_q\[n,k\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5En+T_q%5Bn%2Ck%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]=\\displaystyle \\sum_{k=1}^n T_q[n,k]")

This sequence goes thus: 1, 3, 5, 8, 10, 14, 16, 20, 23, 27… and is
shown graphically in figure 3.

[![Quo\_Rem\_Fig3](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig3.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig3.png)Figure
3

Each term of this sequence is the sum of the terms in a given hyperbolic
cycle (Figure 2) of sequence
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") (Figure 1). Thus, it can be approximated in continuous form by
the area under the hyperbola corresponding to each cycle
![y=n/x](https://s0.wp.com/latex.php?latex=y%3Dn%2Fx&bg=ffffff&fg=333333&s=0
"y=n/x"). Hence, we can create a continuous approximation for
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") by the integral function:

![y=\\displaystyle \\int\_1^x \\dfrac{x
dt}{t}=x\\log(x)](https://s0.wp.com/latex.php?latex=y%3D%5Cdisplaystyle+%5Cint_1%5Ex+%5Cdfrac%7Bx+dt%7D%7Bt%7D%3Dx%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"y=\\displaystyle \\int_1^x \\dfrac{x dt}{t}=x\\log(x)")

This is shown by the red curve in Figure 3. We notice that this
continuous approximation falls short of actual discrete
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") sequence. This correction factor can be empirically
determined using the method of least squares to be a linear term. Thus,
with this correction the below function provides a good fit for the
average behavior of
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]"):

![y=x\\log(x)+0.154
x](https://s0.wp.com/latex.php?latex=y%3Dx%5Clog%28x%29%2B0.154+x&bg=ffffff&fg=333333&s=0
"y=x\\log(x)+0.154 x")

The empirical determination of this correction term prompted us to try
to determine it from first principles. The function
![y=x\\log(x)](https://s0.wp.com/latex.php?latex=y%3Dx%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"y=x\\log(x)") is a continuous approximation of the area in one cycle of
the sequence
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q"). But in reality our
![f\_q](https://s0.wp.com/latex.php?latex=f_q&bg=ffffff&fg=333333&s=0
"f_q") cycles are approximately the discrete harmonic series as opposed
to a smooth hyperbola. From Euler’s work we know that the difference
between the discrete form and the continuous integral converges to that
mysterious number Euler’s constant ![\\gamma=
0.5772157...](https://s0.wp.com/latex.php?latex=%5Cgamma%3D+0.5772157...&bg=ffffff&fg=333333&s=0
"\\gamma= 0.5772157...") for a unit hyperbola. To make use of this we
tried some experiments with the hyperbola and realized that the best way
to capture the area of the cycle was to use the symmetry of the
hyperbola
![y=n/x](https://s0.wp.com/latex.php?latex=y%3Dn%2Fx&bg=ffffff&fg=333333&s=0
"y=n/x") about the line
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") (Figure 2). Here, we can count all
![n/k](https://s0.wp.com/latex.php?latex=n%2Fk&bg=ffffff&fg=333333&s=0
"n/k") in a cycle vertically till
![\\sqrt{n}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{n}") (see vertical line in Figure 2). The due to symmetry we can
make the count again from the other end horizontally till
![\\sqrt{n}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{n}"). This way we would have completely covered all the discrete
counts except that we would have counted the square ![\\sqrt{n} \\times
\\sqrt{n}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bn%7D+%5Ctimes+%5Csqrt%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{n} \\times \\sqrt{n}") twice. Hence, need to subtract
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
from our sum. We can get the two symmetric discrete sums now by the
addition of
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") to the integral of the continuous form. Thus, we can write
the approximate area for a cycle and hence the function approximating
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") as:

![y=x(2\\displaystyle \\int\_1^{\\sqrt{x}}
\\dfrac{dt}{t}+\\gamma)-(\\sqrt{x})^2=
2x(\\log(\\sqrt{x})+\\gamma)-x=2x(\\dfrac{1}{2}\\log(x)+\\gamma)-x=x\\log(x)+(2\\gamma-1)x](https://s0.wp.com/latex.php?latex=y%3Dx%282%5Cdisplaystyle+%5Cint_1%5E%7B%5Csqrt%7Bx%7D%7D+%5Cdfrac%7Bdt%7D%7Bt%7D%2B%5Cgamma%29-%28%5Csqrt%7Bx%7D%29%5E2%3D+2x%28%5Clog%28%5Csqrt%7Bx%7D%29%2B%5Cgamma%29-x%3D2x%28%5Cdfrac%7B1%7D%7B2%7D%5Clog%28x%29%2B%5Cgamma%29-x%3Dx%5Clog%28x%29%2B%282%5Cgamma-1%29x&bg=ffffff&fg=333333&s=0
"y=x(2\\displaystyle \\int_1^{\\sqrt{x}} \\dfrac{dt}{t}+\\gamma)-(\\sqrt{x})^2= 2x(\\log(\\sqrt{x})+\\gamma)-x=2x(\\dfrac{1}{2}\\log(x)+\\gamma)-x=x\\log(x)+(2\\gamma-1)x")

Thus, we get our correction term to be
![2\\gamma-1=0.1544313...](https://s0.wp.com/latex.php?latex=2%5Cgamma-1%3D0.1544313...&bg=ffffff&fg=333333&s=0
"2\\gamma-1=0.1544313..."). It gave us great pleasure to have figured
this out from scratch without any study of mathematical literature in
this regard. We noticed that this already good fit can be made even
better by addition of a further constant term
![c=5.479](https://s0.wp.com/latex.php?latex=c%3D5.479&bg=ffffff&fg=333333&s=0
"c=5.479"). We do not know if this is really a constant or is some
subtle term currently beyond our reach. Thus, we may write the final
function approximating summatory
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") sequence as:

![y=x\\log(x)+(2\\gamma
-1)x+5.479](https://s0.wp.com/latex.php?latex=y%3Dx%5Clog%28x%29%2B%282%5Cgamma+-1%29x%2B5.479&bg=ffffff&fg=333333&s=0
"y=x\\log(x)+(2\\gamma -1)x+5.479")

This function gives a mean difference of ![6.8 \\times
10^{-4}](https://s0.wp.com/latex.php?latex=6.8+%5Ctimes+10%5E%7B-4%7D&bg=ffffff&fg=333333&s=0
"6.8 \\times 10^{-4}") with
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") for
![n=1:30000](https://s0.wp.com/latex.php?latex=n%3D1%3A30000&bg=ffffff&fg=333333&s=0
"n=1:30000") (Figure 3: light blue dashed line). While this captures the
average behavior of
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]"), examination of the specific behavior of
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") shows that it exhibits saltations that are greater than
usual at certain values. To better understand this we created the
difference sequence ![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]") (Figure 4):

![\\Delta \\varsigma\[n\]=
\\varsigma\[n+1\]-\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D%3D+%5Cvarsigma%5Bn%2B1%5D-%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]= \\varsigma[n+1]-\\varsigma[n]")

[![Quo\_Rem\_Fig4](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig4.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig4.png)Figure
4. We are yet to figure a curve to fit the successive maxima attained by
![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]").

The sequence ![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]") shows several interesting features which we
consider in detail below:  
1\) The lowest value it ever attains is 2. A closer examination of the
indices at which ![\\Delta
\\varsigma\[n\]=2](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D%3D2&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]=2") reveals that they correspond to
![n+1](https://s0.wp.com/latex.php?latex=n%2B1&bg=ffffff&fg=333333&s=0
"n+1") being a prime in the parent
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") sequence. Thus, there are as many minima in ![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]") as there are primes. This can be explained
thus: Since, a prime is completely divisible only by ![k=1,
n](https://s0.wp.com/latex.php?latex=k%3D1%2C+n&bg=ffffff&fg=333333&s=0
"k=1, n"), these two values will generate quotients of 1 and
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
respectively to add to the quotient sum. The remaining quotients will be
the same as previous number as none of the other
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
between 1 and
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
will perfectly divide the prime. Thus, the quotient sum will minimally
differ from that of the previous number by 2.

2\) Jumps above the median value of 6 (for this range; Figure 4: violet
line) have propensity to increase with increasing
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
Analysis of these jumps revealed that they have a significantly higher
propensity to occur at
![n=6k-1](https://s0.wp.com/latex.php?latex=n%3D6k-1&bg=ffffff&fg=333333&s=0
"n=6k-1"). Figure 5 shows a box-plot of ![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]"), which indicates that the median value of this
sequence for
![n=6k-1](https://s0.wp.com/latex.php?latex=n%3D6k-1&bg=ffffff&fg=333333&s=0
"n=6k-1") is significantly higher than median value of the sequence for
any other
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") as
well as the median value of the overall sequence. This can be explained
by considering the following
![n=6k-1](https://s0.wp.com/latex.php?latex=n%3D6k-1&bg=ffffff&fg=333333&s=0
"n=6k-1") corresponds to
![n=6k](https://s0.wp.com/latex.php?latex=n%3D6k&bg=ffffff&fg=333333&s=0
"n=6k") in the parent
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]") sequence. A number of the form
![6k](https://s0.wp.com/latex.php?latex=6k&bg=ffffff&fg=333333&s=0 "6k")
will undergo complete divisions by at least 1, 2, 3, 6 out of the first
6 ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
However, the number before it
![6k-1](https://s0.wp.com/latex.php?latex=6k-1&bg=ffffff&fg=333333&s=0
"6k-1") will not be divisible by 2, 3 or their multiples. Since it
cannot undergo complete division by them, its quotients will be less
than the corresponding ones of
![6k](https://s0.wp.com/latex.php?latex=6k&bg=ffffff&fg=333333&s=0 "6k")
by 1. Thus there will be a jump in ![\\Delta
\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[n]") corresponding to
![n=6k](https://s0.wp.com/latex.php?latex=n%3D6k&bg=ffffff&fg=333333&s=0
"n=6k") in
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]"). As e.g. consider 12:  
![\\varsigma\[10\]=
10+5+3+2+2+1+1+1+1+1=27](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5B10%5D%3D+10%2B5%2B3%2B2%2B2%2B1%2B1%2B1%2B1%2B1%3D27&bg=ffffff&fg=333333&s=0
"\\varsigma[10]= 10+5+3+2+2+1+1+1+1+1=27")  
![\\varsigma\[11\]=
11+5+3+2+2+1+1+1+1+1+1=29](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5B11%5D%3D+11%2B5%2B3%2B2%2B2%2B1%2B1%2B1%2B1%2B1%2B1%3D29&bg=ffffff&fg=333333&s=0
"\\varsigma[11]= 11+5+3+2+2+1+1+1+1+1+1=29")  
![\\varsigma\[12\]=
12+6+4+3+2+2+1+1+1+1+1+1=35](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5B12%5D%3D+12%2B6%2B4%2B3%2B2%2B2%2B1%2B1%2B1%2B1%2B1%2B1%3D35&bg=ffffff&fg=333333&s=0
"\\varsigma[12]= 12+6+4+3+2+2+1+1+1+1+1+1=35");  
![\\varsigma\[13\]=
13+6+4+3+2+2+1+1+1+1+1+1+1=37](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5B13%5D%3D+13%2B6%2B4%2B3%2B2%2B2%2B1%2B1%2B1%2B1%2B1%2B1%2B1%3D37&bg=ffffff&fg=333333&s=0
"\\varsigma[13]= 13+6+4+3+2+2+1+1+1+1+1+1+1=37")  
Thus,
![\\varsigma\[12\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5B12%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[12]") causes a spike in ![\\Delta
\\varsigma\[11\]=6](https://s0.wp.com/latex.php?latex=%5CDelta+%5Cvarsigma%5B11%5D%3D6&bg=ffffff&fg=333333&s=0
"\\Delta \\varsigma[11]=6") due to completion of divisions by 2,3,4,6.

[![Quo\_Rem\_Fig5](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig5.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig5.png)Figure
5.

3\) Notably, the successive record values of
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") for
![n\<30000](https://s0.wp.com/latex.php?latex=n%3C30000&bg=ffffff&fg=333333&s=0
"n\<30000") are attained at: 1, 3, 5, 11, 23, 35, 47, 59, 119, 179, 239,
359, 719, 839, 1259, 1679, 2519, 5039, 7559, 10079, 15119, 20159, 25199,
27719 (Figure 4). These values of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
correspond to 2, 4, 6, 12, 24, 36, 48, 60, 120, 180, 240, 360, 720, 840,
1260, 1680, 2520, 5040, 7560, 10080, 15120, 20160, 25200, 27720 in
![\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\varsigma[n]"). Remarkably, these latter numbers are the highly
composite numbers first defined by Ramanujan in 1915 CE. They are
numbers with more divisors than any integer smaller than them. We can
see why these highly composite numbers spawn maxima in
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") — they will be maximally completely divided and
thus yield the largest quotient sum for any number up to them. Thus,
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") presents them as antipodes to the primes.
Further, Ramanujan defined a second more inclusive set of numbers, the
largely composite numbers, which are numbers with more or the same
number of divisors than any integer smaller than them. This more
inclusive set spawns high-points in
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]"), which are not maxima but still stand out
(Figure 4).

As an aside one may note that the above
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") at
which the
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") maxima occur are often primes: 15 out of the 24.
Most of these are also in particular Sophie Germain or safe primes
(primes of form where if
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") is
a prime and
![2p+1](https://s0.wp.com/latex.php?latex=2p%2B1&bg=ffffff&fg=333333&s=0
"2p+1") is also a prime. Then the former is Sophie Germain prime and the
latter a safe prime).

4\) The successive record values of
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") are: 2, 3, 4, 6, 8, 9, 10, 12, 16, 18, 20, 24,
30, 32, 36, 40, 48, 60, 64, 72, 80, 84, 90, 96… It turns out this
sequence (another recorded by Ramanujan) is the number of divisors of
the corresponding highly composite numbers which spawn the
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") maximum. Thus, the successive maximum values of
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") are attained at
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
one less than a highly composite number and is equal to the number of
divisors of the HCN.

5\) From the the above discussion of the specific cases of the maxima
and minima it should be apparent that:

![\\Delta\\varsigma\[n\]=\\tau\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D%3D%5Ctau%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]=\\tau[n]") where
![\\tau\[n\]](https://s0.wp.com/latex.php?latex=%5Ctau%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\tau[n]") is the number of divisors including 1 and
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
itself for ![n \\ge
2](https://s0.wp.com/latex.php?latex=n+%5Cge+2&bg=ffffff&fg=333333&s=0
"n \\ge 2").

**The remainder triangle**  
The above triangular array
![T\_q](https://s0.wp.com/latex.php?latex=T_q&bg=ffffff&fg=333333&s=0
"T_q") can be converted to a second triangular array by the below
transformation:

![T\_r\[n,k\]=n-k \\cdot
T\_q\[n,k\]](https://s0.wp.com/latex.php?latex=T_r%5Bn%2Ck%5D%3Dn-k+%5Ccdot+T_q%5Bn%2Ck%5D&bg=ffffff&fg=333333&s=0
"T_r[n,k]=n-k \\cdot T_q[n,k]")

This
![T\_r](https://s0.wp.com/latex.php?latex=T_r&bg=ffffff&fg=333333&s=0
"T_r") turns out to be the triangular array of remainders. This can be
alternatively obtained thus: Consider a positive integer
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
Then for all
![k=1,2,3...n](https://s0.wp.com/latex.php?latex=k%3D1%2C2%2C3...n&bg=ffffff&fg=333333&s=0
"k=1,2,3...n"), ![T\_r\[n\] \\equiv n \\mod
k](https://s0.wp.com/latex.php?latex=T_r%5Bn%5D+%5Cequiv+n+%5Cmod+k&bg=ffffff&fg=333333&s=0
"T_r[n] \\equiv n \\mod k"). Say
![n=10](https://s0.wp.com/latex.php?latex=n%3D10&bg=ffffff&fg=333333&s=0
"n=10"), we get ![T\_r\[10\]=0, 0, 1, 2, 0, 4, 3, 2, 1,
0](https://s0.wp.com/latex.php?latex=T_r%5B10%5D%3D0%2C+0%2C+1%2C+2%2C+0%2C+4%2C+3%2C+2%2C+1%2C+0&bg=ffffff&fg=333333&s=0
"T_r[10]=0, 0, 1, 2, 0, 4, 3, 2, 1, 0"), a sequence of remainders of the
division ![n \\div
k](https://s0.wp.com/latex.php?latex=n+%5Cdiv+k&bg=ffffff&fg=333333&s=0
"n \\div k"). If we do this for all ![n=1, 2, 3, 4
...](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3%2C+4+...&bg=ffffff&fg=333333&s=0
"n=1, 2, 3, 4 ...") we get the remainder triangular array
![T\_r\[n,k\]](https://s0.wp.com/latex.php?latex=T_r%5Bn%2Ck%5D&bg=ffffff&fg=333333&s=0
"T_r[n,k]"), which is the same as the array obtained by the above-stated
transformation of
![T\_q\[n,k\]](https://s0.wp.com/latex.php?latex=T_q%5Bn%2Ck%5D&bg=ffffff&fg=333333&s=0
"T_q[n,k]"). Shown below are its initial terms.

![\\begin{tabular}{|\*{10}{r|}} \\cline{1-1} 0 \\\\ \\cline{1-2} 0 & 0
\\\\ \\cline{1-3} 0 & 1 & 0 \\\\ \\cline{1-4} 0 & 0 & 1 & 0 \\\\
\\cline{1-5} 0 & 1 & 2 & 1 & 0 \\\\ \\cline{1-6} 0 & 0 & 0 & 2 & 1 & 0
\\\\ \\cline{1-7} 0 & 1 & 1 & 3 & 2 & 1 & 0 \\\\ \\cline{1-8} 0 & 0 & 2
& 0 & 3 & 2 & 1 & 0 \\\\ \\cline{1-9} 0 & 1 & 0 & 1 & 4 & 3 & 2 & 1 & 0
\\\\ \\cline{1-10} 0 & 0 & 1 & 2 & 0 & 4 & 3 & 2 & 1 & 0 \\\\
\\cline{1-10}
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7C%2A%7B10%7D%7Br%7C%7D%7D+%5Ccline%7B1-1%7D+0+%5C%5C+%5Ccline%7B1-2%7D+0+%26+0+%5C%5C+%5Ccline%7B1-3%7D+0+%26+1+%26+0+%5C%5C+%5Ccline%7B1-4%7D+0+%26+0+%26+1+%26+0+%5C%5C+%5Ccline%7B1-5%7D+0+%26+1+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-6%7D+0+%26+0+%26+0+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-7%7D+0+%26+1+%26+1+%26+3+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-8%7D+0+%26+0+%26+2+%26+0+%26+3+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-9%7D+0+%26+1+%26+0+%26+1+%26+4+%26+3+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-10%7D+0+%26+0+%26+1+%26+2+%26+0+%26+4+%26+3+%26+2+%26+1+%26+0+%5C%5C+%5Ccline%7B1-10%7D+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|*{10}{r|}} \\cline{1-1} 0 \\\\ \\cline{1-2} 0 & 0 \\\\ \\cline{1-3} 0 & 1 & 0 \\\\ \\cline{1-4} 0 & 0 & 1 & 0 \\\\ \\cline{1-5} 0 & 1 & 2 & 1 & 0 \\\\ \\cline{1-6} 0 & 0 & 0 & 2 & 1 & 0 \\\\ \\cline{1-7} 0 & 1 & 1 & 3 & 2 & 1 & 0 \\\\ \\cline{1-8} 0 & 0 & 2 & 0 & 3 & 2 & 1 & 0 \\\\ \\cline{1-9} 0 & 1 & 0 & 1 & 4 & 3 & 2 & 1 & 0 \\\\ \\cline{1-10} 0 & 0 & 1 & 2 & 0 & 4 & 3 & 2 & 1 & 0 \\\\ \\cline{1-10} \\end{tabular}")

We observe that each column in
![T\_r](https://s0.wp.com/latex.php?latex=T_r&bg=ffffff&fg=333333&s=0
"T_r") can be described thus: 1st, all 0s; 2nd a 2-term cycle sequence
of 0,1; 3rd a 3-term cycle of sequence 0,1,2. In general terms the kth
column is a
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
term cycle of form
![0,1,2...k-1](https://s0.wp.com/latex.php?latex=0%2C1%2C2...k-1&bg=ffffff&fg=333333&s=0
"0,1,2...k-1")

If we linearize
![T\_r](https://s0.wp.com/latex.php?latex=T_r&bg=ffffff&fg=333333&s=0
"T_r") we get the remainders sequence
![f\_r](https://s0.wp.com/latex.php?latex=f_r&bg=ffffff&fg=333333&s=0
"f_r"), which goes 0, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 1, 2, 1, 0, 0, 0, 0,
2, 1… As the linearization of a triangular array
![f\_r](https://s0.wp.com/latex.php?latex=f_r&bg=ffffff&fg=333333&s=0
"f_r") also grows as ![\\sum\_{j=1}^n
j](https://s0.wp.com/latex.php?latex=%5Csum_%7Bj%3D1%7D%5En+j&bg=ffffff&fg=333333&s=0
"\\sum_{j=1}^n j"), where
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
the row number of
![T\_r](https://s0.wp.com/latex.php?latex=T_r&bg=ffffff&fg=333333&s=0
"T_r"). The sequence is plotted in Figure 6 with the x-coordinate of the
first term as 0 and y=coordinate as
![f\_r\[1\]](https://s0.wp.com/latex.php?latex=f_r%5B1%5D&bg=ffffff&fg=333333&s=0
"f_r[1]").

[![Quo\_Rem\_Fig6](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig6.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig6.png)Figure
6

It shows cycles of length
![n=1,2,3..](https://s0.wp.com/latex.php?latex=n%3D1%2C2%2C3..&bg=ffffff&fg=333333&s=0
"n=1,2,3.."). Each pair of cycles shows the same maximum value.
Examination of the sequence shows that successively greater maxima are
all bounded by the parabola:

![y=\\dfrac{\\sqrt{1+2x}-1}{2}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7B%5Csqrt%7B1%2B2x%7D-1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{\\sqrt{1+2x}-1}{2}")

Just as we did with
![T\_q](https://s0.wp.com/latex.php?latex=T_q&bg=ffffff&fg=333333&s=0
"T_q"), we can similarly define the summatory sequence
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") (we are using this notation after we discovered post facto
that
![\\rho](https://s0.wp.com/latex.php?latex=%5Crho&bg=ffffff&fg=333333&s=0
"\\rho") has been used for related remainder sequences in the
mathematical literature, where each term is the sum of the numbers in a
row of
![T\_r](https://s0.wp.com/latex.php?latex=T_r&bg=ffffff&fg=333333&s=0
"T_r"). This sequence goes thus: 0, 0, 1, 1, 4, 3, 8, 8, 12, 13, 22, 17,
28, 31, 36, 36, 51, 47, 64, 61… It is plotted in Figure 7.

[![Quo\_Rem\_Fig7](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig7.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig7.png)Figure
7

We determined that the sequence can be described by a continuous
function, a parabola of the form ![y=a
x^2](https://s0.wp.com/latex.php?latex=y%3Da+x%5E2&bg=ffffff&fg=333333&s=0
"y=a x^2") (shown as red line in Figure 7), where we empirically
determined ![a \\approx
0.177](https://s0.wp.com/latex.php?latex=a+%5Capprox+0.177&bg=ffffff&fg=333333&s=0
"a \\approx 0.177").

We next sought to obtain the exact value of the constant of the parabola
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
from first principles. For this consider the plot a single cycle of
length ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") of sequence
![f\_r](https://s0.wp.com/latex.php?latex=f_r&bg=ffffff&fg=333333&s=0
"f_r") (Figure 8). We observe that as ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty") it is a series of right triangles.

[![Quo\_Rem\_Fig8](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig8.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig8.png)Figure
8

The largest of these triangles is an isosceles triangle with ![h=n/2,
b=n/2](https://s0.wp.com/latex.php?latex=h%3Dn%2F2%2C+b%3Dn%2F2&bg=ffffff&fg=333333&s=0
"h=n/2, b=n/2"). The next triangle has ![h=n/3,
b=n/6](https://s0.wp.com/latex.php?latex=h%3Dn%2F3%2C+b%3Dn%2F6&bg=ffffff&fg=333333&s=0
"h=n/3, b=n/6"), the next has ![h=n/4,
b=n/12](https://s0.wp.com/latex.php?latex=h%3Dn%2F4%2C+b%3Dn%2F12&bg=ffffff&fg=333333&s=0
"h=n/4, b=n/12"). Thus, the general expression for the heights and bases
of these triangles is ![h=n\\cdot\\tfrac{1}{k+1}, b=n \\cdot
\\tfrac{1}{k(k+1)}](https://s0.wp.com/latex.php?latex=h%3Dn%5Ccdot%5Ctfrac%7B1%7D%7Bk%2B1%7D%2C+b%3Dn+%5Ccdot+%5Ctfrac%7B1%7D%7Bk%28k%2B1%29%7D&bg=ffffff&fg=333333&s=0
"h=n\\cdot\\tfrac{1}{k+1}, b=n \\cdot \\tfrac{1}{k(k+1)}") where
![k=1,2,3...](https://s0.wp.com/latex.php?latex=k%3D1%2C2%2C3...&bg=ffffff&fg=333333&s=0
"k=1,2,3...") and the area of the triangles would be ![A=n^2 \\cdot
\\tfrac{1}{2k(k+1)^2}](https://s0.wp.com/latex.php?latex=A%3Dn%5E2+%5Ccdot+%5Ctfrac%7B1%7D%7B2k%28k%2B1%29%5E2%7D&bg=ffffff&fg=333333&s=0
"A=n^2 \\cdot \\tfrac{1}{2k(k+1)^2}"). Thus at limit the area under the
triangles in a single cycle, which will be the value of the nth term of
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") for large
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"),
will be given by the sum (assuming ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty")):

![y=n^2\\displaystyle \\sum\_{k=1}^\\infty
\\dfrac{1}{2k(k+1)^2}](https://s0.wp.com/latex.php?latex=y%3Dn%5E2%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B1%7D%7B2k%28k%2B1%29%5E2%7D&bg=ffffff&fg=333333&s=0
"y=n^2\\displaystyle \\sum_{k=1}^\\infty \\dfrac{1}{2k(k+1)^2}")

We realized, much to our pleasure on discovering it, that this sum is
convergent and remarkably can be expressed in terms of the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function as:

![\\displaystyle \\sum\_{k=1}^\\infty \\dfrac{1}{2k(k+1)^2}=
1-\\dfrac{\\zeta(2)}{2}=1-\\dfrac{\\pi^2}{12} \\approx
0.177532966](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B1%7D%7B2k%28k%2B1%29%5E2%7D%3D+1-%5Cdfrac%7B%5Czeta%282%29%7D%7B2%7D%3D1-%5Cdfrac%7B%5Cpi%5E2%7D%7B12%7D+%5Capprox+0.177532966&bg=ffffff&fg=333333&s=0
"\\displaystyle \\sum_{k=1}^\\infty \\dfrac{1}{2k(k+1)^2}= 1-\\dfrac{\\zeta(2)}{2}=1-\\dfrac{\\pi^2}{12} \\approx 0.177532966")

Thus we can express the parabola fitting the sequence
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") precisely as:

![y=\\left(1-\\dfrac{\\pi^2}{12}\\right)x^2](https://s0.wp.com/latex.php?latex=y%3D%5Cleft%281-%5Cdfrac%7B%5Cpi%5E2%7D%7B12%7D%5Cright%29x%5E2&bg=ffffff&fg=333333&s=0
"y=\\left(1-\\dfrac{\\pi^2}{12}\\right)x^2")

Thus, again we stumble upon one of those deep links we seen in
mathematics, in this case between remainders of division and the number
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). Now, to study the exact behavior of
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") we define the difference sequence ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]"):

![\\Delta \\rho\[n\]
=\\rho\[n+1\]-\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D+%3D%5Crho%5Bn%2B1%5D-%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n] =\\rho[n+1]-\\rho[n]")

This difference sequence is plotted in Figure 9.

[![Quo\_Rem\_Fig9](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig9.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/quo_rem_fig9.png)Figure
9. The points corresponding to perfect numbers and powers of 2 are shown
in red and blue respectively.

The ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") sequence shows the following notable features:  
1\) ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") takes positive values more often than negative
values (3.03:1) in the first 30000 terms. This corresponds to the ratio
of numbers with the sum of their divisors smaller than themselves being
less than them by at least 2 (known as deficient numbers) to those whose
sum of divisors smaller than them is equal or greater than them. This
will become clear from the discussion that follows further down.

2\) Successive maxima, i.e. the record value of the sequence up to
certain ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") occur only at even values of ![n \>
1](https://s0.wp.com/latex.php?latex=n+%3E+1&bg=ffffff&fg=333333&s=0
"n \> 1"). Closer examination revealed that the maxima are associated
with ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") being a prime in the parent sequence
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]"); then ![\\Delta
\\rho\[n-1\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn-1%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n-1]") will be a maximum. If we take a number
![6k](https://s0.wp.com/latex.php?latex=6k&bg=ffffff&fg=333333&s=0 "6k")
then the numbers ![6k+2,
6k+4](https://s0.wp.com/latex.php?latex=6k%2B2%2C+6k%2B4&bg=ffffff&fg=333333&s=0
"6k+2, 6k+4") will be even.
![6k+3](https://s0.wp.com/latex.php?latex=6k%2B3&bg=ffffff&fg=333333&s=0
"6k+3") will be divisible by 3. Thus, these will not be primes. That
leaves
![6k+1](https://s0.wp.com/latex.php?latex=6k%2B1&bg=ffffff&fg=333333&s=0
"6k+1") and
![6k+5](https://s0.wp.com/latex.php?latex=6k%2B5&bg=ffffff&fg=333333&s=0
"6k+5"); the latter is the same as
![6k-1](https://s0.wp.com/latex.php?latex=6k-1&bg=ffffff&fg=333333&s=0
"6k-1") for another
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
Thus, ![6k \\pm
1](https://s0.wp.com/latex.php?latex=6k+%5Cpm+1&bg=ffffff&fg=333333&s=0
"6k \\pm 1") will not be divisible by 2 and 3 and could be prime ![\\ge
5](https://s0.wp.com/latex.php?latex=%5Cge+5&bg=ffffff&fg=333333&s=0
"\\ge 5"). Thus, all primes ![p \\ge
5](https://s0.wp.com/latex.php?latex=p+%5Cge+5&bg=ffffff&fg=333333&s=0
"p \\ge 5") can be expressed as ![6k \\pm
1](https://s0.wp.com/latex.php?latex=6k+%5Cpm+1&bg=ffffff&fg=333333&s=0
"6k \\pm 1"). Hence, in the sequence ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]"),
![p=6k+1](https://s0.wp.com/latex.php?latex=p%3D6k%2B1&bg=ffffff&fg=333333&s=0
"p=6k+1") will correspond
![n=6k](https://s0.wp.com/latex.php?latex=n%3D6k&bg=ffffff&fg=333333&s=0
"n=6k") and
![p=6k-1](https://s0.wp.com/latex.php?latex=p%3D6k-1&bg=ffffff&fg=333333&s=0
"p=6k-1") to
![n=6k-2](https://s0.wp.com/latex.php?latex=n%3D6k-2&bg=ffffff&fg=333333&s=0
"n=6k-2"). Thus, at ![n \\ge
6](https://s0.wp.com/latex.php?latex=n+%5Cge+6&bg=ffffff&fg=333333&s=0
"n \\ge 6"), the successive ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") maxima occur at
![n=6k](https://s0.wp.com/latex.php?latex=n%3D6k&bg=ffffff&fg=333333&s=0
"n=6k") or
![n=6k-2](https://s0.wp.com/latex.php?latex=n%3D6k-2&bg=ffffff&fg=333333&s=0
"n=6k-2") corresponding to every
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
that related to a prime in the
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") sequence. That ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") successive maxima will occur at primes can be
explained easily. A prime will not be divisible by any number other than
1 and itself so all other remainders will be non-zero. The number before
it will have at least 2 or at least 2, 3 and 6 as divisors that will
yield remainder 0. Thus, a prime will result in remainders adding to a
larger number relative to the remainder sum of its prior number, thereby
causing a maximum to attained. Thus, there will as many successive
maxima in ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") as primes.

3\) ![\\Delta
\\rho\[n\]=0](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D%3D0&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]=0") only when
![n=2^k-1](https://s0.wp.com/latex.php?latex=n%3D2%5Ek-1&bg=ffffff&fg=333333&s=0
"n=2^k-1"), which corresponds to
![n=2^k](https://s0.wp.com/latex.php?latex=n%3D2%5Ek&bg=ffffff&fg=333333&s=0
"n=2^k") in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]").

4\) Negative values of ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") show a more complex behavior. They are seen where
the ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") is a number which might be perfect numbers, abundant numbers
and highly abundant numbers. We discuss these in detail below.

5\) The successive minima, i.e. record negative values assumed by
![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") for a given
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
are fewer than the successive maxima. While we see a succession of 3245
maxima, corresponding the same number of primes in the first 30000 terms
of ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]"), we only see a succession of 60 minima. We did some
experimentation to discover where these minima occur. Let us define an
arithmetic function as below for all ![n \\ge
2](https://s0.wp.com/latex.php?latex=n+%5Cge+2&bg=ffffff&fg=333333&s=0
"n \\ge 2"):

![s\[n\]=\\left(\\displaystyle \\sum
d\_n\[i\]\\right)-2n](https://s0.wp.com/latex.php?latex=s%5Bn%5D%3D%5Cleft%28%5Cdisplaystyle+%5Csum+d_n%5Bi%5D%5Cright%29-2n&bg=ffffff&fg=333333&s=0
"s[n]=\\left(\\displaystyle \\sum d_n[i]\\right)-2n"). Where
![d\_n\[i\]](https://s0.wp.com/latex.php?latex=d_n%5Bi%5D&bg=ffffff&fg=333333&s=0
"d_n[i]") is a divisor of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
from
![d\[i\]=1...n](https://s0.wp.com/latex.php?latex=d%5Bi%5D%3D1...n&bg=ffffff&fg=333333&s=0
"d[i]=1...n")

Whenever
![s\[n\]](https://s0.wp.com/latex.php?latex=s%5Bn%5D&bg=ffffff&fg=333333&s=0
"s[n]") is greater than
![s\[k\]](https://s0.wp.com/latex.php?latex=s%5Bk%5D&bg=ffffff&fg=333333&s=0
"s[k]") of all
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
integers lesser than it, then
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
considered part of the sequence. It goes: 2, 6, 12, 24, 36, 48, 60, 72,
84, 96… and may be called “remainder anti-primes”. When
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
belongs to this sequence in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") it spawns a minimum at ![\\Delta
\\rho\[n-1\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn-1%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n-1]"). Thus, for ![n\\ge
5](https://s0.wp.com/latex.php?latex=n%5Cge+5&bg=ffffff&fg=333333&s=0
"n\\ge 5") the successive minima occur only at a
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") of
the form
![6k-1](https://s0.wp.com/latex.php?latex=6k-1&bg=ffffff&fg=333333&s=0
"6k-1"). Remainder anti-primes are a subset of a class of numbers,
highly abundant numbers, defined by the mathematician S.
Sivasankaranarayana Pillai. These are numbers whose divisors smaller
than themselves sum up to a value, which is bigger than the sum of the
divisors for each of the numbers smaller than that number. More
generally, whenever
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") of
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") is a highly abundant number it results in strongly negative
values in ![\\Delta
\\rho\[n-1\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn-1%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n-1]").

6\) Definition of
![s\[n\]](https://s0.wp.com/latex.php?latex=s%5Bn%5D&bg=ffffff&fg=333333&s=0
"s[n]") also helps us understand the value assumed by ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]"):

![\\Delta
\\rho\[n-1\]=-(s\[n\]+1)](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn-1%5D%3D-%28s%5Bn%5D%2B1%29&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n-1]=-(s[n]+1)")

Thus, for a prime
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
since the divisors are only ![1,
p](https://s0.wp.com/latex.php?latex=1%2C+p&bg=ffffff&fg=333333&s=0
"1, p"), we have ![\\Delta
\\rho\[p-1\]=-(p+1-2p+1)=p-2](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bp-1%5D%3D-%28p%2B1-2p%2B1%29%3Dp-2&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[p-1]=-(p+1-2p+1)=p-2"). Thus successive maxima in
![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") occur at
![n=p-1](https://s0.wp.com/latex.php?latex=n%3Dp-1&bg=ffffff&fg=333333&s=0
"n=p-1") and attain the value
![p-2](https://s0.wp.com/latex.php?latex=p-2&bg=ffffff&fg=333333&s=0
"p-2"). Thus, after 1 they are either of the form
![6k-1](https://s0.wp.com/latex.php?latex=6k-1&bg=ffffff&fg=333333&s=0
"6k-1") or
![6k-3](https://s0.wp.com/latex.php?latex=6k-3&bg=ffffff&fg=333333&s=0
"6k-3") and will always be odd. Further, this implies that the
successive maxima are bounded by the line
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") (Figure 9). The successive minima usually take the form ![-6k
\\pm 1, -6k \\pm 2, -6k \\pm
3](https://s0.wp.com/latex.php?latex=-6k+%5Cpm+1%2C+-6k+%5Cpm+2%2C+-6k+%5Cpm+3&bg=ffffff&fg=333333&s=0
"-6k \\pm 1, -6k \\pm 2, -6k \\pm 3"). The middle of these, the only
even values of minima, are very rare: there being on 3 in the first
30000 terms, namely ![\\Delta \\rho\[35, 71, 7199\]= -20, -52,
-10990](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5B35%2C+71%2C+7199%5D%3D++-20%2C+-52%2C+-10990&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[35, 71, 7199]=  -20, -52, -10990"). The successive minima
increase in magnitude with increasing
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
but can attain much greater magnitudes than the maxima in their
vicinity. Their increase with
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
not linear unlike the maxima as the
![s\[n\]](https://s0.wp.com/latex.php?latex=s%5Bn%5D&bg=ffffff&fg=333333&s=0
"s[n]") for this specialized subset of highly abundant numbers grows
rapidly. We empirically found a curve of the form
![y=-\\tfrac{x\\log(x)}{5.017}](https://s0.wp.com/latex.php?latex=y%3D-%5Ctfrac%7Bx%5Clog%28x%29%7D%7B5.017%7D&bg=ffffff&fg=333333&s=0
"y=-\\tfrac{x\\log(x)}{5.017}") to approximately fit them (Figure 9).

7\) When
![\\Delta\\rho\[n\]=-1](https://s0.wp.com/latex.php?latex=%5CDelta%5Crho%5Bn%5D%3D-1&bg=ffffff&fg=333333&s=0
"\\Delta\\rho[n]=-1") it corresponds to
![n+1](https://s0.wp.com/latex.php?latex=n%2B1&bg=ffffff&fg=333333&s=0
"n+1"), i.e.
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") of 6, 28, 496, 8128 in our range of 1:30000. These numbers
are known after the Pythagorean sage Nicomachus as perfect numbers
because their divisors other than themselves add up exactly to them (one
can see why this is so from the above, ![\\Delta
\\rho\[n-1\]=-(s\[n\]+1)](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn-1%5D%3D-%28s%5Bn%5D%2B1%29&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n-1]=-(s[n]+1)")):  
6=1+2+3  
28=1+2+4+7+14  
496=1+2+4+8+16+31+62+124+248  
8128=1+2+4+8+16+32+64+127+254+508+1016+2032+4064  
One notices that they have a curious form with respect to the powers of
2:  
![6=2^0+2^1+2^2-2^0](https://s0.wp.com/latex.php?latex=6%3D2%5E0%2B2%5E1%2B2%5E2-2%5E0&bg=ffffff&fg=333333&s=0
"6=2^0+2^1+2^2-2^0")  
![28=2^0+2^1+2^2+2^3-2^0+2^4+2^1](https://s0.wp.com/latex.php?latex=28%3D2%5E0%2B2%5E1%2B2%5E2%2B2%5E3-2%5E0%2B2%5E4%2B2%5E1&bg=ffffff&fg=333333&s=0
"28=2^0+2^1+2^2+2^3-2^0+2^4+2^1")  
![496=2^0+2^1+2^2+2^3+2^4+2^5-2^0+2^6-2^1+2^7-2^2+2^8-2^3](https://s0.wp.com/latex.php?latex=496%3D2%5E0%2B2%5E1%2B2%5E2%2B2%5E3%2B2%5E4%2B2%5E5-2%5E0%2B2%5E6-2%5E1%2B2%5E7-2%5E2%2B2%5E8-2%5E3&bg=ffffff&fg=333333&s=0
"496=2^0+2^1+2^2+2^3+2^4+2^5-2^0+2^6-2^1+2^7-2^2+2^8-2^3")  
![8128=2^0+2^1+2^2+2^3+2^4+2^5+2^6+2^7-2^0+2^8-2^1+2^9-2^2+2^{10}-2^3+2^{11}-2^4+2^{12}-2^5](https://s0.wp.com/latex.php?latex=8128%3D2%5E0%2B2%5E1%2B2%5E2%2B2%5E3%2B2%5E4%2B2%5E5%2B2%5E6%2B2%5E7-2%5E0%2B2%5E8-2%5E1%2B2%5E9-2%5E2%2B2%5E%7B10%7D-2%5E3%2B2%5E%7B11%7D-2%5E4%2B2%5E%7B12%7D-2%5E5&bg=ffffff&fg=333333&s=0
"8128=2^0+2^1+2^2+2^3+2^4+2^5+2^6+2^7-2^0+2^8-2^1+2^9-2^2+2^{10}-2^3+2^{11}-2^4+2^{12}-2^5")

More generally, if
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") is
a prime and
![2p-1](https://s0.wp.com/latex.php?latex=2p-1&bg=ffffff&fg=333333&s=0
"2p-1") is also a prime (such primes are called Mersenne primes) then
![2^{p-1}(2^p -
1)](https://s0.wp.com/latex.php?latex=2%5E%7Bp-1%7D%282%5Ep+-+1%29&bg=ffffff&fg=333333&s=0
"2^{p-1}(2^p - 1)") is a perfect number. The search for such perfect
numbers goes on this date computationally and checking online while
writing this article shows that to date 50 such numbers have been found.
All known perfect numbers are of a form ending in 6 or 28. Yet it has
not be formally proven that no odd perfect numbers exist or if there are
an infinite number of perfect numbers\!

8\) Abundant numbers are those numbers whose divisors smaller than
themselves add up to a number greater than themselves. e.g.
![d(12)=1,2,3,4,6;
12\<16](https://s0.wp.com/latex.php?latex=d%2812%29%3D1%2C2%2C3%2C4%2C6%3B+12%3C16&bg=ffffff&fg=333333&s=0
"d(12)=1,2,3,4,6; 12\<16"). When
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
an abundant number in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") it results in a negative value of
![\\Delta\\rho\[n-1\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Crho%5Bn-1%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\rho[n-1]"). The odd abundant numbers like 945, 1575, 2205 in
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") result in the only even indices (
![n-1](https://s0.wp.com/latex.php?latex=n-1&bg=ffffff&fg=333333&s=0
"n-1")) at which the sequence
![\\Delta\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\rho[n]") is negative.

9\) ![\\Delta
\\rho\[n\]=-2](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D%3D-2&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]=-2") is unknown to us. This would imply that the sum
of the divisors of a number which are smaller than it can never be 1
more than the number. Similarly ![\\Delta
\\rho\[n\]=2](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D%3D2&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]=2"), appears to be unknown, i.e. corresponding to
deficient numbers with a deficiency of 3. We do not know if these have
been proven or disproven. ![\\Delta
\\rho\[n\]=1](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D%3D1&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]=1") are also rare. We get only 3 such numbers from
1:30000 which correspond the below
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") of
![\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\rho[n]") and observe that:  
![3=3\\times 1; \\;
1=3-2](https://s0.wp.com/latex.php?latex=3%3D3%5Ctimes+1%3B+%5C%3B+1%3D3-2&bg=ffffff&fg=333333&s=0
"3=3\\times 1; \\; 1=3-2")  
![10=1\\times 2 \\times 5; \\;
1+2+5=10-2](https://s0.wp.com/latex.php?latex=10%3D1%5Ctimes+2+%5Ctimes+5%3B+%5C%3B+1%2B2%2B5%3D10-2&bg=ffffff&fg=333333&s=0
"10=1\\times 2 \\times 5; \\; 1+2+5=10-2")  
![136=1 \\times 2 \\times 4 \\times 8 \\times 17 \\times 34 \\times 68;
\\; 1 + 2 + 4 + 8 + 17 + 34 +68
=136-2](https://s0.wp.com/latex.php?latex=136%3D1+%5Ctimes+2+%5Ctimes+4+%5Ctimes+8+%5Ctimes+17+%5Ctimes+34+%5Ctimes+68%3B+%5C%3B+1+%2B+2+%2B+4+%2B+8+%2B+17+%2B+34+%2B68+%3D136-2&bg=ffffff&fg=333333&s=0
"136=1 \\times 2 \\times 4 \\times 8 \\times 17 \\times 34 \\times 68; \\; 1 + 2 + 4 + 8 + 17 + 34 +68 =136-2")  
These are numbers whose sum of divisors smaller than them fall short of
them by 2. Similarly, we have only 5 numbers resulting in
![\\Delta\\rho\[n\]=-3](https://s0.wp.com/latex.php?latex=%5CDelta%5Crho%5Bn%5D%3D-3&bg=ffffff&fg=333333&s=0
"\\Delta\\rho[n]=-3"): 20, 104 464, 650, 1952. These are numbers whose
sum of divisors smaller than them exceed them by 2.

**Epilog**  
The
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") and ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") sequences (Figures 4 and 9) are striking in being
simple means of illustrating the fundamental asymmetry in the number
world between primes and their anti-numbers.
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]") reveals the highly composite numbers, and more
weakly the largely composite numbers of Ramanujan as the antipodes of
primes. ![\\Delta
\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta+%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta \\rho[n]") suggests that the remainder anti-primes, a subset of
the highly abundant numbers of Pillai, are the anti-numbers of primes.
From the vantage point of these sequences the primes appear to define a
more regular pattern in terms of minima and maxima respectively while
these anti-numbers define more mysterious patterns.

There are some questions for which we do not have ready answers are
(though they might have been answered/studied by mathematicians):  
1\) Can you give an exact form for the constant correction term used to
recapitulating
![\\varsigma(x)](https://s0.wp.com/latex.php?latex=%5Cvarsigma%28x%29&bg=ffffff&fg=333333&s=0
"\\varsigma(x)")?  
2\) Can you derive a function that bounds the maxima of
![\\Delta\\varsigma\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Cvarsigma%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\varsigma[n]")?  
3\) Can you derive the exact form of the bounding function of the minima
of
![\\Delta\\rho\[n\]](https://s0.wp.com/latex.php?latex=%5CDelta%5Crho%5Bn%5D&bg=ffffff&fg=333333&s=0
"\\Delta\\rho[n]")?

We carried out all this quite independently of the mathematical
literature and were pleased to see the organic emergence of the two
classes of anti-prime numbers including those previously discovered by
Ramanujan. We showed an earlier variant of this material to a person
with extraordinary mathematical talent. He brought to our attention a
formal proof for the relationship between perfect numbers and the
remainder sequence, which was given to him by a poorly known genius
Suryanarayana from Vishakhapatnam who studied such issues extensively in
the last century. However, such a proof might have been first published
by the mathematician Lucas in the late 1800s. Searching the internet, we
came across a simple presentation of that proof in an excellent paper by
Spivey in the Mathematics Magazine in 2005. Hence, we are not providing
that here. Otherwise our account here provides a summary of the main
interesting results concerning these sequences we found as part of our
investigation.
