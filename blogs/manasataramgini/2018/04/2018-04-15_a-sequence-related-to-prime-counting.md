+++
title = "A sequence related to prime counting"

+++
The current note arose as an exploration branching off from the matter
discussed in these earlier notes: [this
one](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/)
and [this
one](https://manasataramgini.wordpress.com/2018/02/12/counting-primes-arithmetic-functions-ramanujan-and-the-like/).
As we saw before, Carl Gauss, while still in his teens, produced his
first estimate of the prime number distribution in the form of the
function:

![\\pi(n) \\sim
\\dfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\pi(n) \\sim \\dfrac{n}{\\log(n)}")

Here is
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") is the prime counting function, which counts the number of
prime numbers up to a given number
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"),
and
![\\log(n)](https://s0.wp.com/latex.php?latex=%5Clog%28n%29&bg=ffffff&fg=333333&s=0
"\\log(n)") is the natural logarithm of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
The
![\\sim](https://s0.wp.com/latex.php?latex=%5Csim&bg=ffffff&fg=333333&s=0
"\\sim") notation indicates that the prime counting function is
asymptotic with
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}"), i.e. as ![n\\to
\\infty](https://s0.wp.com/latex.php?latex=n%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n\\to \\infty") the ratio ![\\pi(n)\\big / \\tfrac{n}{\\log(n)} \\to
1](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29%5Cbig+%2F+%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D+%5Cto+1&bg=ffffff&fg=333333&s=0
"\\pi(n)\\big / \\tfrac{n}{\\log(n)} \\to 1").

Subsequently, Gauss refined his fit for the prime counting function by
using the famed logarithmic integral
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). We were curious if there was some arithmetic
function, which was actually fitted by
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") rather it being merely a single term
approximation of the
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)"). In course of some arithmetic experiments, we stumbled upon a
sequence, which we believe, without formal proof, is fitted by
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") in terms of average behavior.

This sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f") is
defined thus:
![f\[1\]=1](https://s0.wp.com/latex.php?latex=f%5B1%5D%3D1&bg=ffffff&fg=333333&s=0
"f[1]=1"). Thereafter, add
![n-1](https://s0.wp.com/latex.php?latex=n-1&bg=ffffff&fg=333333&s=0
"n-1") to all terms
![f\[1:(n-1)\]](https://s0.wp.com/latex.php?latex=f%5B1%3A%28n-1%29%5D&bg=ffffff&fg=333333&s=0
"f[1:(n-1)]"). Count how many of
![f\[1:(n-1)\]+(n-1)](https://s0.wp.com/latex.php?latex=f%5B1%3A%28n-1%29%5D%2B%28n-1%29&bg=ffffff&fg=333333&s=0
"f[1:(n-1)]+(n-1)") are primes. This count is
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"). For example when
![n=2](https://s0.wp.com/latex.php?latex=n%3D2&bg=ffffff&fg=333333&s=0
"n=2") we add 2-1=1 to 1 we get 2. Which is a single prime; hence,
![f\[2\]=1](https://s0.wp.com/latex.php?latex=f%5B2%5D%3D1&bg=ffffff&fg=333333&s=0
"f[2]=1"). Now for
![n=3](https://s0.wp.com/latex.php?latex=n%3D3&bg=ffffff&fg=333333&s=0
"n=3") we add 3-1=2 to the first two terms and we get 3, 3. Thus, we
have 2 primes; hence
![f\[3\]=2](https://s0.wp.com/latex.php?latex=f%5B3%5D%3D2&bg=ffffff&fg=333333&s=0
"f[3]=2"). For
![n=4](https://s0.wp.com/latex.php?latex=n%3D4&bg=ffffff&fg=333333&s=0
"n=4"), we add 4-1=3 to the prior terms and get 4, 4, 5, which yields a
single prime, 5; hence,
![f\[4\]=1](https://s0.wp.com/latex.php?latex=f%5B4%5D%3D1&bg=ffffff&fg=333333&s=0
"f[4]=1"). Thus, the first few terms of the sequence goes: 1, 1, 2, 1,
3, 1, 4, 1, 1, 2, 7, 2, 7, 1, 1, 4, 11, 3, 9, 2, 4, 4, 11, 0, 2, 4, 4,
11, 11, 6. Figure 1 shows a plot of the first 20000 terms of the
sequence.

[![prime\_back\_addition\_fig1](https://manasataramgini.files.wordpress.com/2018/04/prime_back_addition_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2018/04/prime_back_addition_fig1.png)Figure
1

The blue line is the plot of this sequence and we notice right away that
despite the fluctuations the average tendency is to grow with
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
Via numerical experiments we were able to establish that this average
growth is fitted best by the function
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") (red line in Figure 1). The green line in Figure
1 is the count of primes
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)"). We observe that though some extreme values of
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
exceed
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)"), the average behavior of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"), i.e. ![\\tfrac{n}{\\log(n)} \<
\\pi(n)](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D+%3C+%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)} \< \\pi(n)"). This relates to a central
development in the number theory: when Gauss conjectured the asymptotic
relationship between
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") and
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") the mathematical apparatus was not yet in place to prove it.
This was finally developed by his last student Bernhard Riemann. Using
those ideas, nearly century after Gauss’ conjecture, Hadamard and de la
Vallée-Poussin proved it and it became known as the Prime Number
Theorem. Further, de la Vallée-Poussin showed that
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") was related to
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") thus:

![\\pi(n)=\\dfrac{n}{\\log(n)}+O\\left(\\dfrac{n}{\\log^2(n)}\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29%3D%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D%2BO%5Cleft%28%5Cdfrac%7Bn%7D%7B%5Clog%5E2%28n%29%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi(n)=\\dfrac{n}{\\log(n)}+O\\left(\\dfrac{n}{\\log^2(n)}\\right)")

Here, the second term is gives the error and is denoted using the big-O
notation which was explained in [an earlier
note](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/).
This indicates that indeed
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") would be less than
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)"). Thus, as can be seen in Figure 1 the average growth of
![f\[n\]\<\\pi(n)](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3C%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"f[n]\<\\pi(n)").

We then used
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") to ‘rectify’
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") i.e. obtain:

![f\[n\]-\\dfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\dfrac{n}{\\log(n)}")

[![Prime\_back\_addition\_fig2](https://manasataramgini.files.wordpress.com/2018/04/prime_back_addition_fig2.png?w=640)](https://manasataramgini.files.wordpress.com/2018/04/prime_back_addition_fig2.png)Figure
2

This rectified
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") is plotted in Figure 2 and provides a clear picture of
fluctuations in
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") once we have removed the average growth trend. We observe right
away that the amplitude of the fluctuations grows with
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").
To determine this growth trend of the rectified
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"), we first noticed from Figure 1 that
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") tends to run close to the maxima of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"). Hence, we utilized the asymptotic expansion of
![\\textrm{Li}(n)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n)"), which is a better approximation of
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") and captures the behavior beyond the basic
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}") term:

![\\textrm{Li}(n) \\sim \\dfrac{n}{\\log(n)} \\displaystyle
\\sum\_{k=0}^\\infty
\\dfrac{k\!}{(\\log(n))^k}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D+%5Cdisplaystyle+%5Csum_%7Bk%3D0%7D%5E%5Cinfty+%5Cdfrac%7Bk%21%7D%7B%28%5Clog%28n%29%29%5Ek%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n) \\sim \\dfrac{n}{\\log(n)} \\displaystyle \\sum_{k=0}^\\infty \\dfrac{k!}{(\\log(n))^k}")

![\\textrm{Li}(n) \\sim
\\dfrac{n}{\\log(n)}+\\dfrac{n}{\\log^2(n)}+\\dfrac{2n}{\\log^3(n)}+\\dfrac{6n}{\\log^4(n)}...](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D%2B%5Cdfrac%7Bn%7D%7B%5Clog%5E2%28n%29%7D%2B%5Cdfrac%7B2n%7D%7B%5Clog%5E3%28n%29%7D%2B%5Cdfrac%7B6n%7D%7B%5Clog%5E4%28n%29%7D...&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n) \\sim \\dfrac{n}{\\log(n)}+\\dfrac{n}{\\log^2(n)}+\\dfrac{2n}{\\log^3(n)}+\\dfrac{6n}{\\log^4(n)}...")

Using the first 4 terms to approximate the growth of the amplitude of
rectified
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") we get the red bounding curves shown in Figure 2. Thus, we
conjecture that while
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") grows on an average as
![\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)}"), the amplitude of its fluctuations is roughly
approximated by
![\\textrm{Li}(n)-\\tfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29-%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n)-\\tfrac{n}{\\log(n)}") (Green bounding curves in Figure
2).
