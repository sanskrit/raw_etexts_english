+++
title = "Counting primes, arithmetic functions, Ramanujan and the like"

+++
We originally wished to have a tail-piece for [our previous
note](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/)
that would describe more precisely the relationship between the [Möbius
function](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/)
and the distribution of prime numbers. However, since that would have
needed a bit of a detour in order to be clearer to an unfamiliar reader,
we decided to tell that story more expansively and separately. All that
will be said here is elementary stuff that has been narrated many times
by many other people. Nevertheless, given that this is a mathematical
story everyone likes to tell, we are also telling it in the way it
impressed itself on our own consciousness.

What is the distribution of prime numbers? This is a question many of us
might have wondered about in school. The typical school teacher, which
we had, showed little interest in answering it. The number of prime
numbers less than or equal to a number
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x") is
termed
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") or the prime counting function. The 15 year old Carl Gauss
spent his fallow time finding prime numbers in intervals of 1000s and
thus built up an impressive list of them. From that he deduced an
approximate expression for their distribution and wrote it down on his
log tables:

![\\pi(n) \\sim
\\dfrac{n}{\\log(n)}](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\pi(n) \\sim \\dfrac{n}{\\log(n)}")

Here the
![\\sim](https://s0.wp.com/latex.php?latex=%5Csim&bg=ffffff&fg=333333&s=0
"\\sim") notation means that as ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty") the ratio of
![\\pi(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n)") to ![\\tfrac{n}{\\log(n)} \\to
1](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B%5Clog%28n%29%7D+%5Cto+1&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{\\log(n)} \\to 1"), i.e., they are asymptotic. Later, his
rival the French mathematician Legendre published a similar result:

![\\pi(n) \\sim
\\dfrac{n}{\\log(n)-1.08366}](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29-1.08366%7D&bg=ffffff&fg=333333&s=0
"\\pi(n) \\sim \\dfrac{n}{\\log(n)-1.08366}")

But the Russian scientist Chebyshev showed that rather than 1.08366 the
negative term would be correctly 1 as
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
becomes large. Gauss subsequently improved his conjecture using the
below function:

![\\pi(n) \\sim
\\textrm{Li}(n)](https://s0.wp.com/latex.php?latex=%5Cpi%28n%29+%5Csim+%5Ctextrm%7BLi%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\pi(n) \\sim \\textrm{Li}(n)"), where ![\\textrm{Li}(n)=\\displaystyle
\\int\_2^n
\\dfrac{dx}{\\log(x)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29%3D%5Cdisplaystyle+%5Cint_2%5En+%5Cdfrac%7Bdx%7D%7B%5Clog%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n)=\\displaystyle \\int_2^n \\dfrac{dx}{\\log(x)}")

His former student and professorial successor at Göttingen, Dirichlet,
independently arrived at the same function, the logarithmic integral
![\\int\_0^x\\tfrac{dt}{\\log(t)}](https://s0.wp.com/latex.php?latex=%5Cint_0%5Ex%5Ctfrac%7Bdt%7D%7B%5Clog%28t%29%7D&bg=ffffff&fg=333333&s=0
"\\int_0^x\\tfrac{dt}{\\log(t)}"), as a possible expression for the
asymptotic distribution of prime numbers, though he expressed it as a
series.
![\\textrm{Li}(n)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n)") can be expressed as a series, which for large
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"),
can give as close approximations of it as needed depending on number of
terms we use. Such a series is termed an asymptotic series for
![\\textrm{Li}(n)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n)").

![\\textrm{Li}(n) \\sim \\dfrac{n}{\\log(n)} +
\\dfrac{n}{(\\log(n))^2}+\\dfrac{2n}{(\\log(n))^3}+\\dfrac{6n}{(\\log(n))^4}...=\\displaystyle
\\sum\_{k=0}^\\infty \\dfrac{k\!\\cdot
n}{(\\log(n))^{k+1}}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28n%29+%5Csim+%5Cdfrac%7Bn%7D%7B%5Clog%28n%29%7D+%2B+%5Cdfrac%7Bn%7D%7B%28%5Clog%28n%29%29%5E2%7D%2B%5Cdfrac%7B2n%7D%7B%28%5Clog%28n%29%29%5E3%7D%2B%5Cdfrac%7B6n%7D%7B%28%5Clog%28n%29%29%5E4%7D...%3D%5Cdisplaystyle+%5Csum_%7Bk%3D0%7D%5E%5Cinfty+%5Cdfrac%7Bk%21%5Ccdot+n%7D%7B%28%5Clog%28n%29%29%5E%7Bk%2B1%7D%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(n) \\sim \\dfrac{n}{\\log(n)} + \\dfrac{n}{(\\log(n))^2}+\\dfrac{2n}{(\\log(n))^3}+\\dfrac{6n}{(\\log(n))^4}...=\\displaystyle \\sum_{k=0}^\\infty \\dfrac{k!\\cdot n}{(\\log(n))^{k+1}}")

As a numerical example: ![\\textrm{Li}(10000) =
1246.137](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%2810000%29+%3D+1246.137&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(10000) = 1246.137"). Using the first 4 terms of the above
series we get a value of
![1237.554](https://s0.wp.com/latex.php?latex=1237.554&bg=ffffff&fg=333333&s=0
"1237.554"), which is a
![.69\\%](https://s0.wp.com/latex.php?latex=.69%5C%25&bg=ffffff&fg=333333&s=0
".69\\%") error. ![\\textrm{Li}(100000) =
9629.809](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28100000%29+%3D+9629.809&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(100000) = 9629.809"). Again using the first 4 terms of the
series we get
![9605.549](https://s0.wp.com/latex.php?latex=9605.549&bg=ffffff&fg=333333&s=0
"9605.549"), which is a a
![.25\\%](https://s0.wp.com/latex.php?latex=.25%5C%25&bg=ffffff&fg=333333&s=0
".25\\%") error. One also notices that the first term of this series
yields Gauss’s original cruder approximation. Figure 1 shows ![\\pi(x),
\\tfrac{x}{\\log(x)},
\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29%2C+%5Ctfrac%7Bx%7D%7B%5Clog%28x%29%7D%2C+%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x), \\tfrac{x}{\\log(x)}, \\textrm{Li}(x)"). The proofs of these
conjectures were first obtained in the later 1800s after Riemann’s
discovery of the complete
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function and came to be known as the famous prime number
theorem.

[![Pi\_xbylog\_Li](https://manasataramgini.files.wordpress.com/2018/02/pi_xbylog_li.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/pi_xbylog_li.png)Figure
1
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") in red,
![\\tfrac{x}{\\log(x)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bx%7D%7B%5Clog%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{x}{\\log(x)}") in blue and
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") in green.

Now, this function
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") was already discovered before Gauss by Leonhard Euler
but its first extensive study is part of a story of the lives and times
of men. When a supernova like Gauss shines in the firmament the light of
other stars, even if bright, gets drowned. That indeed was the fate of
his compatriot Johann von Soldner. Born about an year before Gauss, von
Soldner was another of those self-taught geniuses who at an early age
showed a talent both in mathematics and making instruments of his own.
He went on to be scientist of note and a land surveyor ([even as
Gauss](https://manasataramgini.wordpress.com/2017/06/11/some-personal-reflections-on-carl-gauss-bernhard-riemann-and-associated-matters/)).
Among other things, he was one of the first to predict the bending of
light by gravity (of course Newton himself believed that gravity would
act on light particles and bend their path but von Soldner made
numerically precise predictions of what the value would be). He proposed
an experiment of observing stars in the near the Sun in the sky to test
this proposed bending (something later measured by the famous faked
experiments of Arthur Eddington as part of testing Einstein’s prediction
of the same from his theory of relativity). In 1809 CE, von Soldner
using his great capacity for numerical calculations studied
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and provided a table of its values up to 7 decimal
places. In the process he also calculated Euler’s constant
![\\gamma=0.577215...](https://s0.wp.com/latex.php?latex=%5Cgamma%3D0.577215...&bg=ffffff&fg=333333&s=0
"\\gamma=0.577215...") that plays a key role in evaluating this integral
to more than thirty places. He obtained a different value from the 19th
place onwards for
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") than that obtained by earlier by geometer Mascheroni during
his study of Euler’s Gamma function. The difference caught the eye of
Gauss given his interest in
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and his own computation recovered von Soldner’s value
till the 22nd place. Gauss then called upon his 19 year old student, the
astronomer Friedrich Nicolai, who was a mental calculating prodigy, to
calculate Euler’s constant using a method based on Euler’s own sums. He
did so to 40 decimal places showing von Soldner to be correct. As a
result of von Soldner’s tables we got the first glimpse of how
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") looks (Figure 2). Von Soldner also realized at one
value of
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
the value of
![\\textrm{Li}(x)=0](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3D0&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)=0") while being apparently unaware of its importance in
the matter of the prime number distribution.

[![Li\_of\_x](https://manasataramgini.files.wordpress.com/2018/02/li_of_x.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/li_of_x.png)Figure
2 with the Ramanujan-Soldner point

Unaware of most of the work done in the West over the past century,
Srinivasa Ramanujan carried out his own studies to independently obtain
expressions for the prime number distribution. In the process he
discovered for himself that
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") approximated the prime counting function. Ramanujan
discovered multiple fast-converging series to evaluate
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). The simplest of which is:

![\\textrm{Li}(x) = \\gamma + \\log(\\log(x))+\\displaystyle
\\sum\_{k=1}^\\infty \\dfrac{\\log(x)^k}{k\!\\cdot
k}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29+%3D+%5Cgamma+%2B+%5Clog%28%5Clog%28x%29%29%2B%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%5Clog%28x%29%5Ek%7D%7Bk%21%5Ccdot+k%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x) = \\gamma + \\log(\\log(x))+\\displaystyle \\sum_{k=1}^\\infty \\dfrac{\\log(x)^k}{k!\\cdot k}"),
where
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") is Euler’s constant.

In studying
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") Ramanujan also independently discovered the
approximate value of
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
for which
![\\textrm{Li}(x)=0](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3D0&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)=0") (Figure 2) and mentioned it in his exchange with
Hardy. Thus, it is now known as the Ramanujan-Soldner constant:
1.45136….

To gain further appreciation of Ramanujan’s independent discovery of the
use of
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") in approximating
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") we shall step back to the studies of Riemann in this regard.
Riemann wondered if he could get a better approximation of the prime
counting function
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") than
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and arrived at the following expression:

![\\pi(x) = \\textrm{Li}(x) - \\dfrac{\\textrm{Li}(\\sqrt{x})}{2}
+t\_1+t\_2...](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29+%3D+%5Ctextrm%7BLi%7D%28x%29+-+%5Cdfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D+%2Bt_1%2Bt_2...&bg=ffffff&fg=333333&s=0
"\\pi(x) = \\textrm{Li}(x) - \\dfrac{\\textrm{Li}(\\sqrt{x})}{2} +t_1+t_2...")

Since we are keeping this note very basic we shall not expand on the
additional terms ![t\_1,
t\_2...](https://s0.wp.com/latex.php?latex=t_1%2C+t_2...&bg=ffffff&fg=333333&s=0
"t_1, t_2..."), but the
![t\_1](https://s0.wp.com/latex.php?latex=t_1&bg=ffffff&fg=333333&s=0
"t_1") term is related to the zeros of the Riemann’s
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function in the complex plane. However, by using just the
first listed term alone we get the fit shown in Figure 3.

[![pi\_xbylog\_Li\_Li\_Corr](https://manasataramgini.files.wordpress.com/2018/02/pi_xbylog_li_li_corr.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/pi_xbylog_li_li_corr.png)Figure
3
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") in red,
![\\tfrac{x}{\\log(x)}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bx%7D%7B%5Clog%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{x}{\\log(x)}") in blue,
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") in green and ![\\textrm{Li}(x) -
\\dfrac{\\textrm{Li}(\\sqrt{x})}{2}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29+-+%5Cdfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x) - \\dfrac{\\textrm{Li}(\\sqrt{x})}{2}") is in black.

One notices right away that it is a better approximation in the range
shown and on average is better than just
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). Ramanujan independently arrived at the same
expression, short of the additional term dependent on the complex plane
zeros of the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function, and mentioned it to Hardy in course of their early
exchange of letters. In his expression he captured that fact that
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") does not count the prime numbers per say but the
integer powers of primes weighted by
![\\tfrac{1}{n}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{n}"). Thus, the first term
![\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}") corrects for the squares of
primes; similarly in Ramanujan’s equivalent expression the term
![\\tfrac{\\textrm{Li}(\\sqrt\[3\]{x})}{3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%5B3%5D%7Bx%7D%29%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\textrm{Li}(\\sqrt[3]{x})}{3}") would correct for cubes of
primes and so on.

From figure 1 and figure 2 we see that ![\\textrm{Li}(x)\>
\\pi(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3E+%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)\> \\pi(x)") in the range we have plotted it. Indeed,
the fact that the negative term
![-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}") results in a better fit to
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") is in line with this. This led Gauss and Riemann to wonder if
indeed
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") was always greater than
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"). It appears Ramanujan also initially might have thought the
same and saw the negative terms as “bringing down”
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") to
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"). This indeed remains true for all
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
that has been within our computational reach to date. However,
remarkably, Littlewood produced a proof that
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") cross each other infinite number of times. This proof is
rather difficult for those of meagre mathematical capacity, but it
indicated that there should be some very large number where
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") will, for the first time, become greater than
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). This can be intuitively understood in terms of the
above expression for
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") in terms of
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") provided by Riemann. As noted above, beyond the terms
that correct for the powers of primes (the biggest being
![-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}")), there is the term based on the
complex-plane zeros of the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function. While normally that term reduces to something
negligible, at some big number that term could neutralize the
![-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}](https://s0.wp.com/latex.php?latex=-%5Ctfrac%7B%5Ctextrm%7BLi%7D%28%5Csqrt%7Bx%7D%29%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"-\\tfrac{\\textrm{Li}(\\sqrt{x})}{2}") term and make
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") bigger than
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). We have not reached that number through direct
computation but Littlewood’s student Skewes came up with the first
estimates of how big that number could be. Since then there has been a
very active program in computational mathematics to size up that number.
When I last checked it was established that the first crossing of
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") would happen somewhere near the gargantuan ![1.397162914
\\times
10^{316}](https://s0.wp.com/latex.php?latex=1.397162914+%5Ctimes+10%5E%7B316%7D&bg=ffffff&fg=333333&s=0
"1.397162914 \\times 10^{316}"). This is truly an example of how
computational intuition gained from even large numbers can eventually
fail at some humongous number out of the reach our computation.

In addition to the above Riemann also discovered yet another prime
counting function that he thought would be more or less the same as
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"). This function
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") combines the [Möbius
function](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/)
![\\mu(x)](https://s0.wp.com/latex.php?latex=%5Cmu%28x%29&bg=ffffff&fg=333333&s=0
"\\mu(x)"), which we described in the previous note and
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"):

![\\textrm{Ri}(x)= \\displaystyle \\sum\_{n=1}^\\infty
\\dfrac{\\mu(n)}{n}\\cdot\\textrm{Li}(x^{1/n})](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29%3D+%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%5Cmu%28n%29%7D%7Bn%7D%5Ccdot%5Ctextrm%7BLi%7D%28x%5E%7B1%2Fn%7D%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)= \\displaystyle \\sum_{n=1}^\\infty \\dfrac{\\mu(n)}{n}\\cdot\\textrm{Li}(x^{1/n})")

[![pi\_Li\_Ri](https://manasataramgini.files.wordpress.com/2018/02/pi_li_ri.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/pi_li_ri.png)[![Pi\_minus\_Ri](https://manasataramgini.files.wordpress.com/2018/02/pi_minus_ri.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/pi_minus_ri.png)Figure
4. Part 1:
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") is in red,
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") in black and
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") in green; Part 2:
![\\pi(x)-\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29-%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)-\\textrm{Ri}(x)")

In Figure 4 we calculated
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") as an approximation using the sum of the first 1000
terms in the above expression. This gives a value correct to the first
place after the decimal point. This enough for our current purpose but
is computationally costly as you need 1000 terms just to get this level
of accuracy. As can be seen in Figure 4,
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") closely approximates
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") in the range we have plotted. Strikingly, Ramanujan entirely
independently of Riemann arrived at the same function as
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") in course of his studies on the prime number
distribution before he began his exchange with Hardy.

As we saw, the original definition of
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") takes a lot of terms to get even limited accuracy. In
the late 1800s the Scandinavian mathematician J.P. Gram discovered a
series
![\\textrm{G}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BG%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{G}(x)") that is equivalent to
![\\textrm{Ri}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}") using the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function:

![\\textrm{G}(x)=1+\\displaystyle \\sum\_{k=1}^\\infty
\\dfrac{(\\log(x))^k}{k \\cdot k\!
\\zeta(k+1)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BG%7D%28x%29%3D1%2B%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%28%5Clog%28x%29%29%5Ek%7D%7Bk+%5Ccdot+k%21+%5Czeta%28k%2B1%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{G}(x)=1+\\displaystyle \\sum_{k=1}^\\infty \\dfrac{(\\log(x))^k}{k \\cdot k! \\zeta(k+1)}")

Using the above series with just 99 terms we can compute
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") to at least 5 places beyond the decimal point.
Interestingly, Ramanujan arrived at yet another fast-converging series
(we will call it
![\\textrm{Rjn}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRjn%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rjn}(x)") after him) on his own to approximate
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"), which gives values close to
![\\textrm{G}(x)=\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BG%7D%28x%29%3D%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{G}(x)=\\textrm{Ri}(x)") (Figure 5, top panel). Being the
master of the Bernoulli numbers, which have an intimate connection with
the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function, Ramanujan used them instead of that function.

![\\textrm{Rjn}(x)= \\dfrac{4}{\\pi} \\displaystyle \\sum\_{k=1}^\\infty
\\dfrac{(-1)^{k-1}\\cdot k}{(2k-1)\\cdot B\_{2k}} \\cdot
\\left(\\dfrac{\\log(x)}{2\\pi}\\right)^{2k-1}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRjn%7D%28x%29%3D+%5Cdfrac%7B4%7D%7B%5Cpi%7D+%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%5Cinfty+%5Cdfrac%7B%28-1%29%5E%7Bk-1%7D%5Ccdot+k%7D%7B%282k-1%29%5Ccdot+B_%7B2k%7D%7D+%5Ccdot+%5Cleft%28%5Cdfrac%7B%5Clog%28x%29%7D%7B2%5Cpi%7D%5Cright%29%5E%7B2k-1%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Rjn}(x)= \\dfrac{4}{\\pi} \\displaystyle \\sum_{k=1}^\\infty \\dfrac{(-1)^{k-1}\\cdot k}{(2k-1)\\cdot B_{2k}} \\cdot \\left(\\dfrac{\\log(x)}{2\\pi}\\right)^{2k-1}")
where
![B\_{2k}](https://s0.wp.com/latex.php?latex=B_%7B2k%7D&bg=ffffff&fg=333333&s=0
"B_{2k}") are even Bernoulli numbers.

Ramanujan did not stop there and went on to produce a further
approximation of
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") as a definite integral, which we will denote as the Ramanujan
integral
![\\textrm{Rji}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRji%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rji}(x)"):

![\\textrm{Rji}(x)=\\displaystyle \\int\_0^\\infty \\dfrac{(\\log(x))^t
dt}{t \\cdot \\Gamma(t+1) \\cdot
\\zeta(t+1)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRji%7D%28x%29%3D%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+%5Cdfrac%7B%28%5Clog%28x%29%29%5Et+dt%7D%7Bt+%5Ccdot+%5CGamma%28t%2B1%29+%5Ccdot+%5Czeta%28t%2B1%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Rji}(x)=\\displaystyle \\int_0^\\infty \\dfrac{(\\log(x))^t dt}{t \\cdot \\Gamma(t+1) \\cdot \\zeta(t+1)}")
where
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") is the Gamma function.

This integral too gives values close to the series
![\\textrm{Rjn(x)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRjn%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Rjn(x)}") and
![\\textrm{G}(x)=\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BG%7D%28x%29%3D%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{G}(x)=\\textrm{Ri}(x)") as shown in Figure 5.

[![Ri\_Ramanujan\_functions\_Differences](https://manasataramgini.files.wordpress.com/2018/02/ri_ramanujan_functions_differences.png?w=640)](https://manasataramgini.files.wordpress.com/2018/02/ri_ramanujan_functions_differences.png)Figure
5. In the top panel the
![\\textrm{Rjn}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRjn%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rjn}(x)") was calculated using the first 15 terms, which are
sufficient to give convergence to 5 places after the decimal point. In
the bottom panel
![\\textrm{Rji}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRji%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rji}(x)") was approximately calculated using the Gauss-Kronrod
numerical integration method with the upper limit of the integral taken
as 150 due to limitations in evaluation beyond that.

As we saw above (Figure 4)
![\\textrm{Ri}(x)=\\textrm{G}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29%3D%5Ctextrm%7BG%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)=\\textrm{G}(x)") approximates
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") better than
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") in the range we have plotted it (the plot will be
practically identical for the Ramanujan series and integral given that
their values are close to
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)"): Figure 5). This indeed has been shown to be true
computationally for
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
even 10000 times bigger than our plotted range. Thus, it is not
surprising that both Riemann and Ramanujan thought that
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)"),
![\\textrm{Rjn}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRjn%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rjn}(x)"),
![\\textrm{Rji}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRji%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Rji}(x)") are much better approximations of
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") than
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") or more or less
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") itself. However, here again numerical intuition was shown to
be imprecise. In a publication by Hardy and Littlewood, the latter
remarkably proved that starting at some large number
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") would become a better approximation of
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") than these functions of Riemann, Gram and Ramanujan. Further,
they would swap positions as the better approximation of
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)") an infinite number of times in the realm of giant numbers.
Thus, one can only say that:

![\\textrm{Ri}(x)=\\textrm{G}(x) \\sim \\pi(x);\\; \\textrm{Rjn}(x)
\\sim \\pi(x); \\; \\textrm{Rji}(x) \\sim
\\pi(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29%3D%5Ctextrm%7BG%7D%28x%29+%5Csim+%5Cpi%28x%29%3B%5C%3B+%5Ctextrm%7BRjn%7D%28x%29+%5Csim+%5Cpi%28x%29%3B+%5C%3B+%5Ctextrm%7BRji%7D%28x%29+%5Csim+%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)=\\textrm{G}(x) \\sim \\pi(x);\\; \\textrm{Rjn}(x) \\sim \\pi(x); \\; \\textrm{Rji}(x) \\sim \\pi(x)")

Ramanujan did all this work in isolation at Kumbhaghoṇa and Chennai
before leaving for Cambridge. It must be remembered that he did have
access to any serious cutting edge literature and his primary
inspiration was evidently provided by Carr’s synopsis. Thus, after
reading Carr, at age 17 Ramanujan independently discovered the famous
Bernoulli numbers, which were originally discovered by Jakob Bernoulli
(and perhaps by the Japanese Samurai Seki Takakazu or someone of his
school) and were subject of much investigation in the west. Armed with
this he went on to calculate Euler’s constant
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") to 15 places after the decimal point, thus coursing on the
path taken by Euler. This formed the platform for his foray into the
distribution of prime numbers. While this has been routinely described
as nonrigorous work starting from Hardy’s initial letters to Ramanujan,
it does bring out his extraordinary intuition. To us this work
established his connection to the past greats, even as Littlewood
declared to Hardy that he was in the league of Euler or Jacobi (Or
Bertrand Russell: “*I found Hardy and Littlewood in a state of wild
excitement because they believe they have found a second Newton, a Hindu
clerk in Madras making 20 pounds a year.*“). Indeed, it is rather
striking how he single-handed covered some of the key ground spanned by
the discoveries of Jakob Bernoulli, Euler, Gauss, Dirichlet and Riemann.
He rediscovered many of their intuitions regarding the prime counting
function. Not just that, he came up with his own with expressions,
sometimes better the previously published ones, for the Bernoulli
numbers,
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"),
![\\textrm{Ri}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BRi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ri}(x)") and other asymptotic expressions for
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"). Short of the Riemann
![\\zeta](https://s0.wp.com/latex.php?latex=%5Czeta&bg=ffffff&fg=333333&s=0
"\\zeta") function in the complex plane with its non-trivial zeros,
Ramanujan penetrated key elements of the great prime number question all
by himself. Thus, he was like one man all by himself trying to cover the
“gap” in the mathematics of the Hindus following its decline from the
high-point reached by the nambūtiri-s and their school. In many ways,
while operating in modern mathematics, he seemed mysteriously “channel”
the characteristics of the old Hindu greats, with their love for
approximating functions and fast-converging series, which they delighted
in since the age of the Yajurveda.

If Ramanujan represents the mastery of intuition, the other side, that
certainty comes from rigor, is shown by the striking proofs of
Littlewood regarding the
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and other approximations and
![\\pi(x)](https://s0.wp.com/latex.php?latex=%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\pi(x)"). This was exemplified by Gauss, who, though unrivalled at
intuition and experimentation, strove for rigor. He did not publish many
of his works that contained key intuitions if he was unable to produce a
proof for them as exemplified in his dense and rigor-filled
Disquisitiones Arithmeticae. This aspect of mathematics, which is
especially seen in higher arithmetic, is what sets mathematics apart
from science. In science, barring those aspects which are truly reduced
to a mathematical abstraction, we have nothing like a proof. Instead, a
hypothesis is repeatedly tested for falsification. Thus, in scientific
setting, things like ![\\textrm{Li}(x)\>
\\pi(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3E+%5Cpi%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)\> \\pi(x)"), or as we saw in the [previous
article](https://manasataramgini.wordpress.com/2018/02/03/our-auto-discovery-of-the-mobius-and-mertens-sequences/)
the Mertens function being inside the
![\\sqrt{n}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{n}") parabola, would have survived all attempts at falsification
by direct experimentation (in this case computational). Yet, in
mathematics they can be ultimately falsified even though they lie beyond
the reach of direct experimentation.

Nevertheless, the fact that Ramanujan, far removed in space and time,
was able to recapitulate and out do results of other great
mathematicians before him suggests that mathematics is by no means an
invention of the human mind. Rather, Ramanujan, like Euler, or Gauss or
Riemann before him, were tapping into that Platonic realm where the
mathematical ideals exist. The human intuition might grasp only
“smudged” image of the ideal, yet because it exists even those
images would be similar when apprehended independently by different
explorers. Then the apparatus of rigor might get one closer to the
ideal, but only after the intuition has apprehended it in the first
place.
