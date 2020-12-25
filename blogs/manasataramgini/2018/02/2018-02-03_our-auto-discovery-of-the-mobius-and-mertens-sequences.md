+++
title = "Our auto-discovery of the Möbius and Mertens sequences"

+++
Recently, we were explaining to our friend the Möbius and the Mertens
functions and their relationship to the prime number distribution. We
also heard with some wonder from a physicist of a theoretical model
where multiparticle states behave as bosons or fermions in way
predicated by the Möbius function. This prompted us to put down the tale
of our autodiscovery of the Möbius and Mertens sequences in our youth.
On one hand that journey gave us some satisfaction that we, in a very
limited way, were on our own able to recapitulate the journey of the
great minds. But, at the same time, it also brought us down to earth
showing how little we were able to do on our own following the
rediscovery of their results, thus, telling us how the truly great and
pedestrian are distinct.

As we have described before, we began our exploration of sequences by
hand and computer inspired by Hofstadter’s book (GEB). One of the
sequences that we conceived in course of this exploration was a
one-seeded sequence which goes thus in words: We start with 1 as the
first term. Then for every integer
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
from 1 to
![n-1](https://s0.wp.com/latex.php?latex=n-1&bg=ffffff&fg=333333&s=0
"n-1") we test if it divides
![n=2,3,4...](https://s0.wp.com/latex.php?latex=n%3D2%2C3%2C4...&bg=ffffff&fg=333333&s=0
"n=2,3,4..."). For each
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"),
we then take the negative of the sum of all the
![f\[k\]](https://s0.wp.com/latex.php?latex=f%5Bk%5D&bg=ffffff&fg=333333&s=0
"f[k]"), where
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
satisfies this divisibility condition. This becomes the value of the nth
term of the sequence
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]")

![f\[1\]=1](https://s0.wp.com/latex.php?latex=f%5B1%5D%3D1&bg=ffffff&fg=333333&s=0
"f[1]=1")  
![\\displaystyle f\[n\]= -\\sum\_{k}
f\[k\]](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+f%5Bn%5D%3D+-%5Csum_%7Bk%7D+f%5Bk%5D&bg=ffffff&fg=333333&s=0
"\\displaystyle f[n]= -\\sum_{k} f[k]") where ![n \\mod k \\equiv 0, 1
\\le k \<
n](https://s0.wp.com/latex.php?latex=n+%5Cmod+k+%5Cequiv+0%2C+1+%5Cle+k+%3C+n&bg=ffffff&fg=333333&s=0
"n \\mod k \\equiv 0, 1 \\le k \< n")

We were at first surprised to see that this sequence takes only 3 values
-1, 0, 1. The first 25 terms are: 1, -1, -1, 0, -1, 1, -1, 0, 0, 1, -1,
0, -1, 1, 1, 0, -1, 0, -1, 0, 1, 1, -1, 0, 0

[![Mobius\_function](https://manasataramgini.files.wordpress.com/2018/02/mobius_function.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/mobius_function.png)Figure
1. A plot of the first 2000 terms (the red short lines are
![f\[n\]=0](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D0&bg=ffffff&fg=333333&s=0
"f[n]=0")).

The sequence (Figure 1) at first looked almost random but after looking
more closely we began to discern a pattern. First we asked where do the
0s come? After analyzing their locations it became clear that they came
wherever
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
a perfect square of a prime number or a multiple of such a perfect
square. Thus,
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") where
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
4, 8, 9, 12, 16, 18, 20, 24, 25… are all 0s. We then asked where the -1s
and 1s come. It was immediately clear that when
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
a prime
![f\[n\]=-1](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D-1&bg=ffffff&fg=333333&s=0
"f[n]=-1"). Why this should be so is obvious from the way we defined our
sequence. We also noticed that whenever a number has a odd number of
prime factors then
![f\[n\]=-1](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D-1&bg=ffffff&fg=333333&s=0
"f[n]=-1"). Thus ![n=30=2 \\times 3 \\times 5; \\;
f\[30\]=-1](https://s0.wp.com/latex.php?latex=n%3D30%3D2+%5Ctimes+3+%5Ctimes+5%3B+%5C%3B+f%5B30%5D%3D-1&bg=ffffff&fg=333333&s=0
"n=30=2 \\times 3 \\times 5; \\; f[30]=-1") or ![n=42=2 \\times 3
\\times 7; \\;
f\[42\]=-1](https://s0.wp.com/latex.php?latex=n%3D42%3D2+%5Ctimes+3+%5Ctimes+7%3B+%5C%3B+f%5B42%5D%3D-1&bg=ffffff&fg=333333&s=0
"n=42=2 \\times 3 \\times 7; \\; f[42]=-1"). For all the remaining
values of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") we
get
![f\[n\]=1](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D1&bg=ffffff&fg=333333&s=0
"f[n]=1"). These values of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
have a even number of prime factors. Thus, for ![n=6=2 \\times 3, 21=3
\\times
7](https://s0.wp.com/latex.php?latex=n%3D6%3D2+%5Ctimes+3%2C+21%3D3+%5Ctimes+7&bg=ffffff&fg=333333&s=0
"n=6=2 \\times 3, 21=3 \\times 7") we get
![f\[n\]=1](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D1&bg=ffffff&fg=333333&s=0
"f[n]=1"). One learns from these patterns how the
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") values for a given
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
can be understood on the basis of the sequence definition.

These patterns also directed us to render them graphically as a square
matrix with its total number of cells amounting to a certain perfect
square ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") where each cell takes one of three colors based on the value of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"). By playing with different dimensions we arrived at ![n=125
\\times
125](https://s0.wp.com/latex.php?latex=n%3D125+%5Ctimes+125&bg=ffffff&fg=333333&s=0
"n=125 \\times 125") for capturing the above-described structure of this
sequence (Figure 2). The 5 vertical lines are generated by the square
number 25 and its multiples. The square number 4 and its multiples
create the
![135^o](https://s0.wp.com/latex.php?latex=135%5Eo&bg=ffffff&fg=333333&s=0
"135^o") one-square cross-lines. 9 and its multiples create the
![45^o](https://s0.wp.com/latex.php?latex=45%5Eo&bg=ffffff&fg=333333&s=0
"45^o") cross-lines. When multiples of 9 and 4 come adjacent to each
other e.g. (8,9), (27,28), (44,45), (63,64), (80,81), they create the
broad 4-square cross-lines. They have an alternating prime number
separation of 19 and 17.

[![Mobius\_function2](https://manasataramgini.files.wordpress.com/2018/02/mobius_function2.png?w=581&h=581)](https://manasataramgini.files.wordpress.com/2018/02/mobius_function2.png)Figure
2.
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") for ![n=125 \\times
125](https://s0.wp.com/latex.php?latex=n%3D125+%5Ctimes+125&bg=ffffff&fg=333333&s=0
"n=125 \\times 125") with the first row from bottom being
![n=1:125](https://s0.wp.com/latex.php?latex=n%3D1%3A125&bg=ffffff&fg=333333&s=0
"n=1:125"). Brown: -1; light yellow: 0; green: 1

This pattern led us to ask the question as to what fraction of the area
of a square, like the above one, is one of the three colors.
Experimentally, it is obvious that the 0s occupy most area, while the
remainder is evenly split between -1 and 1. Figure 2 helped us to arrive
at approximate value for the area occupied by the zeros. For the first
row
![n=1:125](https://s0.wp.com/latex.php?latex=n%3D1%3A125&bg=ffffff&fg=333333&s=0
"n=1:125"), counting repeat numbers only once, we get: 31 numbers
containing 4 as a factor; 10 with 9; 4 with 25; 2 with 49 and 1 with
121. This adds to 48. Thus for the first row of figure 2 the fraction of
0s is
![\\tfrac{48}{125}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B48%7D%7B125%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{48}{125}"). Given that these smaller squares set the basic
patterns in figure 2, and as we climb up the matrix we add additional
perfect squares (e.g.
![13^2=169](https://s0.wp.com/latex.php?latex=13%5E2%3D169&bg=ffffff&fg=333333&s=0
"13^2=169") between
![n=126:250](https://s0.wp.com/latex.php?latex=n%3D126%3A250&bg=ffffff&fg=333333&s=0
"n=126:250")) and their multiples, we added 1 more to the numerator to
arrive at the fraction of 0s ![\\approx \\tfrac{49}{125}=
0.392](https://s0.wp.com/latex.php?latex=%5Capprox+%5Ctfrac%7B49%7D%7B125%7D%3D+0.392&bg=ffffff&fg=333333&s=0
"\\approx \\tfrac{49}{125}= 0.392"). The experimentally determined value
oscillates in the vicinity of that value with a tendency for convergence
with increasing
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
(Figure 3).

[![Mobius\_convergence](https://manasataramgini.files.wordpress.com/2018/02/mobius_convergence.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/mobius_convergence.png)Figure
3. The gray line in the top panel is
![1-\\tfrac{6}{\\pi^2}](https://s0.wp.com/latex.php?latex=1-%5Ctfrac%7B6%7D%7B%5Cpi%5E2%7D&bg=ffffff&fg=333333&s=0
"1-\\tfrac{6}{\\pi^2}") while in the bottom panel it is
![\\tfrac{3}{\\pi^2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B3%7D%7B%5Cpi%5E2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{3}{\\pi^2}")

This value to which the fraction of 0s converges immediately caught our
eye because of a book we had just borrowed from the local library on
elementary number theory. It informed us about the masterful discovery
of the great Leonhard Euler: What is the probability that any two
positive integers chosen at random are mutually prime (i.e. have GCD=1
or are coprime)? The solution to this problem is related in turn to what
was called the Basel problem after the hometown of Euler and the
Bernoullis. The Basel problem asks the sum of the infinite series:

![1+\\dfrac{1}{4}+\\dfrac{1}{9}+\\dfrac{1}{16}+\\dfrac{1}{25}...=
\\displaystyle \\sum\_{n=1}^\\infty
\\dfrac{1}{n^2}](https://s0.wp.com/latex.php?latex=1%2B%5Cdfrac%7B1%7D%7B4%7D%2B%5Cdfrac%7B1%7D%7B9%7D%2B%5Cdfrac%7B1%7D%7B16%7D%2B%5Cdfrac%7B1%7D%7B25%7D...%3D+%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B1%7D%7Bn%5E2%7D&bg=ffffff&fg=333333&s=0
"1+\\dfrac{1}{4}+\\dfrac{1}{9}+\\dfrac{1}{16}+\\dfrac{1}{25}...= \\displaystyle \\sum_{n=1}^\\infty \\dfrac{1}{n^2}")

The 28 year old Euler showed that this sum is
![\\tfrac{\\pi^2}{6}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%5E2%7D%7B6%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi^2}{6}"), thus, surprisingly, bringing in the number
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). Now the answer to the original question is the inverse of this
number. Thus, the probability that two randomly chosen integers are
coprime is ![\\tfrac{6}{\\pi^2} \\approx
\\tfrac{76}{125}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B6%7D%7B%5Cpi%5E2%7D+%5Capprox+%5Ctfrac%7B76%7D%7B125%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{6}{\\pi^2} \\approx \\tfrac{76}{125}"). This, result, even more
miraculously, connects
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") to the relatively prime numbers (Figure 4).

[![comprimality\_matrix](https://manasataramgini.files.wordpress.com/2018/02/comprimality_matrix.png?w=604&h=604)](https://manasataramgini.files.wordpress.com/2018/02/comprimality_matrix.png)Figure
4. The matrix of relative primality of pairs of integers for
![n=1:100](https://s0.wp.com/latex.php?latex=n%3D1%3A100&bg=ffffff&fg=333333&s=0
"n=1:100"). The area in red to the total area of the square converges to
![\\tfrac{6}{\\pi^2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B6%7D%7B%5Cpi%5E2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{6}{\\pi^2}")

That approximate value we list above immediately led us to realize that
our fraction of the area under 0s in figure 2 or, more precisely, the
asymptotic fraction of 0s in our above sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
should be exactly
![1-\\tfrac{6}{\\pi^2}](https://s0.wp.com/latex.php?latex=1-%5Ctfrac%7B6%7D%7B%5Cpi%5E2%7D&bg=ffffff&fg=333333&s=0
"1-\\tfrac{6}{\\pi^2}"). This also gives the fraction of numbers
containing perfect squares in
![1:n](https://s0.wp.com/latex.php?latex=1%3An&bg=ffffff&fg=333333&s=0
"1:n"). Conversely, the fraction of -1s and 1s in our sequence are
![\\tfrac{3}{\\pi^2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B3%7D%7B%5Cpi%5E2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{3}{\\pi^2}"). This gives the fraction of square-free numbers,
which are products or even or odd number of primes in
![1:n](https://s0.wp.com/latex.php?latex=1%3An&bg=ffffff&fg=333333&s=0
"1:n") Thus, an exploration of a sequence simply out of the curiosity of
checking out patterns emerging from divisibility led us to a deep link
to primality and
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi").

Given that the fraction of -1s and 1s are approximately the same we
wondered what might be the trends in the sum of the above series
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f").
Accordingly we defined new series thus:

![f1\[n\]=\\displaystyle \\sum\_{k=1}^n
f\[k\]](https://s0.wp.com/latex.php?latex=f1%5Bn%5D%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5En+f%5Bk%5D&bg=ffffff&fg=333333&s=0
"f1[n]=\\displaystyle \\sum_{k=1}^n f[k]")

Figure 5 shows a plot of
![f1\[n\]](https://s0.wp.com/latex.php?latex=f1%5Bn%5D&bg=ffffff&fg=333333&s=0
"f1[n]") for
![n=1:30000](https://s0.wp.com/latex.php?latex=n%3D1%3A30000&bg=ffffff&fg=333333&s=0
"n=1:30000")

[![Mertens](https://manasataramgini.files.wordpress.com/2018/02/mertens.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/mertens.png)Figure
5

It is clear that
![f1\[n\]](https://s0.wp.com/latex.php?latex=f1%5Bn%5D&bg=ffffff&fg=333333&s=0
"f1[n]") oscillates between negative and positive values in a what looks
like random walk. However, we do notice that as
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
increases the extreme values reached by
![f1\[n\]](https://s0.wp.com/latex.php?latex=f1%5Bn%5D&bg=ffffff&fg=333333&s=0
"f1[n]") are greater (Figure 6).

[![Mertens\_extrema](https://manasataramgini.files.wordpress.com/2018/02/mertens_extrema.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/mertens_extrema.png)Figure
6

We wondered what this rate of increase might approximated by. But that
was where we hit the end of our explorations. Those days the internet
was not yet available to us and Riemann hypothesis was not the kind of
thing that was widely known in lay circles. We knew of it and the famed
Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function but nothing much of the intricacies of this
hypothesis. It was then that in a city teeming with Meccan demons we
briefly borrowed a dense tome on the number theory from a distant
relative of ours who was belonged to a clan with multi-generational
mathematical talent. It was there that we learned that our
auto-discovered sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
was something that was first described by the prince of the mathematics,
Carl Gauss, in his late teens or early twenties and published in his
famed Disquisitiones Arithmeticae. However, it came be known after a
student of his, August Möbius, who rediscovered and studied it more than
30 years later. This Möbius function can be defined thus:

![\\mu(n)=\\begin{cases} 0; \\textrm{n contains square of a prime}\\\\
1; n=1\\\\ (-1)^k; \\textrm{n is product of k distinct primes}
\\end{cases}](https://s0.wp.com/latex.php?latex=%5Cmu%28n%29%3D%5Cbegin%7Bcases%7D+0%3B+%5Ctextrm%7Bn+contains+square+of+a+prime%7D%5C%5C+1%3B+n%3D1%5C%5C+%28-1%29%5Ek%3B+%5Ctextrm%7Bn+is+product+of+k+distinct+primes%7D+%5Cend%7Bcases%7D&bg=ffffff&fg=333333&s=0
"\\mu(n)=\\begin{cases} 0; \\textrm{n contains square of a prime}\\\\ 1; n=1\\\\ (-1)^k; \\textrm{n is product of k distinct primes} \\end{cases}")

This
![\\mu(n)](https://s0.wp.com/latex.php?latex=%5Cmu%28n%29&bg=ffffff&fg=333333&s=0
"\\mu(n)") has a relationship to the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta"):

![\\displaystyle \\sum\_{n=1}^\\infty \\dfrac{\\mu(n)}{n^s}=
\\dfrac{1}{\\zeta(s)}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%5Cmu%28n%29%7D%7Bn%5Es%7D%3D+%5Cdfrac%7B1%7D%7B%5Czeta%28s%29%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle \\sum_{n=1}^\\infty \\dfrac{\\mu(n)}{n^s}= \\dfrac{1}{\\zeta(s)}")
where ![s \\in
\\mathbb{C}](https://s0.wp.com/latex.php?latex=s+%5Cin+%5Cmathbb%7BC%7D&bg=ffffff&fg=333333&s=0
"s \\in \\mathbb{C}")

The fraction of 0s in our sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
can be expressed as converging to
![1-\\tfrac{1}{\\zeta(2)}](https://s0.wp.com/latex.php?latex=1-%5Ctfrac%7B1%7D%7B%5Czeta%282%29%7D&bg=ffffff&fg=333333&s=0
"1-\\tfrac{1}{\\zeta(2)}") and the fraction of 1s and -1s as converging
to
![\\tfrac{1}{2\\zeta(2)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B2%5Czeta%282%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{2\\zeta(2)}")

Another interesting property of
![\\mu(n)](https://s0.wp.com/latex.php?latex=%5Cmu%28n%29&bg=ffffff&fg=333333&s=0
"\\mu(n)") is seen when it is included in a series of Lambert; we get
this interesting sum:

![\\displaystyle \\sum\_{n=1}^\\infty \\mu(n) \\cdot
\\dfrac{x^n}{1-x^n}=x](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cmu%28n%29+%5Ccdot+%5Cdfrac%7Bx%5En%7D%7B1-x%5En%7D%3Dx&bg=ffffff&fg=333333&s=0
"\\displaystyle \\sum_{n=1}^\\infty \\mu(n) \\cdot \\dfrac{x^n}{1-x^n}=x")
where ![|x|
\<1](https://s0.wp.com/latex.php?latex=%7Cx%7C+%3C1&bg=ffffff&fg=333333&s=0
"|x| \<1")

The summatory sequence which we described above as
![f1](https://s0.wp.com/latex.php?latex=f1&bg=ffffff&fg=333333&s=0 "f1")
turned out to be a function discovered by Mertens
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)") in the late 1800s. Mertens, after computing the first
![10^5](https://s0.wp.com/latex.php?latex=10%5E5&bg=ffffff&fg=333333&s=0
"10^5") values by hand, boldly conjectured that
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)") will for all
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
lie inside the parabola
![y=\\sqrt{x}](https://s0.wp.com/latex.php?latex=y%3D%5Csqrt%7Bx%7D&bg=ffffff&fg=333333&s=0
"y=\\sqrt{x}"), shown in blue in Figure 4. But this conjecture was shown
to be false in our times by Odlyzko and te Riele. However, the first
value for which
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)") will out grow the parabola is so large that it is way
outside our current computational reach. But weaker expressions related
to this conjecture are shown to be equivalent to the Riemann hypothesis,
which we will assume the reader is familiar with:

![M(x)=O(x^{1/2+\\epsilon})](https://s0.wp.com/latex.php?latex=M%28x%29%3DO%28x%5E%7B1%2F2%2B%5Cepsilon%7D%29&bg=ffffff&fg=333333&s=0
"M(x)=O(x^{1/2+\\epsilon})") where ![\\epsilon
\>0](https://s0.wp.com/latex.php?latex=%5Cepsilon+%3E0&bg=ffffff&fg=333333&s=0
"\\epsilon \>0")

To briefly explain the big
![O](https://s0.wp.com/latex.php?latex=O&bg=ffffff&fg=333333&s=0 "O")
notation for an unfamiliar reader: Let there be two functions
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0
"f(x)") and
![g(x)](https://s0.wp.com/latex.php?latex=g%28x%29&bg=ffffff&fg=333333&s=0
"g(x)") whose behavior we are comparing as ![x \\to
\\infty](https://s0.wp.com/latex.php?latex=x+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"x \\to \\infty"). In our current case
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0
"f(x)") is
![M(x)](https://s0.wp.com/latex.php?latex=M%28x%29&bg=ffffff&fg=333333&s=0
"M(x)") and
![g(x)=x^{1/2+\\epsilon}](https://s0.wp.com/latex.php?latex=g%28x%29%3Dx%5E%7B1%2F2%2B%5Cepsilon%7D&bg=ffffff&fg=333333&s=0
"g(x)=x^{1/2+\\epsilon}").  
If ![|f(x)| \\le K\\cdot
|g(x)|](https://s0.wp.com/latex.php?latex=%7Cf%28x%29%7C+%5Cle+K%5Ccdot+%7Cg%28x%29%7C&bg=ffffff&fg=333333&s=0
"|f(x)| \\le K\\cdot |g(x)|") for all ![x \\ge
x\_0](https://s0.wp.com/latex.php?latex=x+%5Cge+x_0&bg=ffffff&fg=333333&s=0
"x \\ge x_0"), where
![K](https://s0.wp.com/latex.php?latex=K&bg=ffffff&fg=333333&s=0 "K") is
a positive real constant and
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") is some real number, then we may state that
![f(x)=O(g(x))](https://s0.wp.com/latex.php?latex=f%28x%29%3DO%28g%28x%29%29&bg=ffffff&fg=333333&s=0
"f(x)=O(g(x))").

The link to the prime distribution also comes out in a nice relationship
discovered by Mertens between
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)") with the functions defined by the famed Russian
scientist Chebyshev in his study of this problem (figure 7). The first
of Chebyshev function
![\\Theta(n)](https://s0.wp.com/latex.php?latex=%5CTheta%28n%29&bg=ffffff&fg=333333&s=0
"\\Theta(n)") is defined thus:

![\\Theta(n)= \\displaystyle \\sum\_{p \\le n}
\\log(p)](https://s0.wp.com/latex.php?latex=%5CTheta%28n%29%3D+%5Cdisplaystyle+%5Csum_%7Bp+%5Cle+n%7D+%5Clog%28p%29&bg=ffffff&fg=333333&s=0
"\\Theta(n)= \\displaystyle \\sum_{p \\le n} \\log(p)") where ![p \\le
n](https://s0.wp.com/latex.php?latex=p+%5Cle+n&bg=ffffff&fg=333333&s=0
"p \\le n") are all primes less than or equal to
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")

The second Chebyshev function
![\\psi](https://s0.wp.com/latex.php?latex=%5Cpsi&bg=ffffff&fg=333333&s=0
"\\psi") is defined thus:

![\\psi(n)=\\displaystyle \\sum\_{p \\le n} \\left \\lfloor \\log\_p(n)
\\right \\rfloor
\\log(p)](https://s0.wp.com/latex.php?latex=%5Cpsi%28n%29%3D%5Cdisplaystyle+%5Csum_%7Bp+%5Cle+n%7D+%5Cleft+%5Clfloor+%5Clog_p%28n%29+%5Cright+%5Crfloor+%5Clog%28p%29&bg=ffffff&fg=333333&s=0
"\\psi(n)=\\displaystyle \\sum_{p \\le n} \\left \\lfloor \\log_p(n) \\right \\rfloor \\log(p)")
where ![p \\le
n](https://s0.wp.com/latex.php?latex=p+%5Cle+n&bg=ffffff&fg=333333&s=0
"p \\le n") are all primes less than or equal to
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")

[![Chebyshev\_primes](https://manasataramgini.files.wordpress.com/2018/02/chebyshev_primes.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/chebyshev_primes.png)Figure
7. The top panels show the growth of the two Chebyshev functions. The
bottom left panel shows the convergence ![\\tfrac{n}{\\Theta(n)} \\to
1](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5CTheta%28n%29%7D+%5Cto+1&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\Theta(n)} \\to 1"). The right bottom panel shows the
fluctuations of
![\\psi(n)-n](https://s0.wp.com/latex.php?latex=%5Cpsi%28n%29-n&bg=ffffff&fg=333333&s=0
"\\psi(n)-n") reminiscent of
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)").

This
![\\psi(n)](https://s0.wp.com/latex.php?latex=%5Cpsi%28n%29&bg=ffffff&fg=333333&s=0
"\\psi(n)") is related to the
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)") thus:

![\\psi(n)=\\displaystyle \\sum\_{k=1}^n \\textrm{M}\\left (\\left
\\lfloor \\dfrac{n}{k} \\right \\rfloor \\right ) \\cdot
\\log(k)](https://s0.wp.com/latex.php?latex=%5Cpsi%28n%29%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5En+%5Ctextrm%7BM%7D%5Cleft+%28%5Cleft+%5Clfloor+%5Cdfrac%7Bn%7D%7Bk%7D+%5Cright+%5Crfloor+%5Cright+%29+%5Ccdot+%5Clog%28k%29&bg=ffffff&fg=333333&s=0
"\\psi(n)=\\displaystyle \\sum_{k=1}^n \\textrm{M}\\left (\\left \\lfloor \\dfrac{n}{k} \\right \\rfloor \\right ) \\cdot \\log(k)")

We first computationally demonstrated this relationship for ourselves
when we learned that our
![f1](https://s0.wp.com/latex.php?latex=f1&bg=ffffff&fg=333333&s=0 "f1")
was none other than
![\\textrm{M}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BM%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{M}(x)"). Thus, with just a household computer, working
knowledge of a modern computer language, and some school and elementary
college level numeracy one can at least get a glimpse of some of the
deepest issues in mathematics. Visualizing some of these, even at a very
low level as we have done, gives you a mystical experience — i.e. a
glimpse of some of deep mysteries of existence.
