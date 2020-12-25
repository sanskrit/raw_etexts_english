+++
title = "An arithmetic experiment and an unsolvedxa0problem"

+++
We realized that a simple arithmetic experiment we had performed in our
youth is actually related to an unsolved problem in number theory. It
goes thus: consider the sequence of natural numbers ![n=1, 2, 3, 4
\\cdots](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3%2C+4+%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002 "n=1, 2, 3, 4 \cdots")
Then find the distance of
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n")
to nearest prime
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0&c=20201002 "p")
that is 1) greater than or equal to
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n")
or 2) less than or equal to
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n").
Thus, ![d\_1\[n\]=p-n,
d\_2\[n\]=n-p](https://s0.wp.com/latex.php?latex=d_1%5Bn%5D%3Dp-n%2C+d_2%5Bn%5D%3Dn-p&bg=ffffff&fg=333333&s=0&c=20201002 "d_1[n]=p-n, d_2[n]=n-p").
We then define the arithmetic function ![f\_1\[n\]=d\_1\[n\]
d\_2\[n\]](https://s0.wp.com/latex.php?latex=f_1%5Bn%5D%3Dd_1%5Bn%5D+d_2%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[n]=d_1[n] d_2[n]").
Since, 1 has no prime before it, we can either have
![f\_1\[1\]](https://s0.wp.com/latex.php?latex=f_1%5B1%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[1]")
as undefined or assign 0 to it. The corresponding sequence goes thus:

![f\_1 \\rightarrow ?, 0, 0, 1, 0, 1, 0, 3, 4, 3, 0, 1, 0, 3, 4
\\cdots](https://s0.wp.com/latex.php?latex=f_1+%5Crightarrow+%3F%2C+0%2C+0%2C+1%2C+0%2C+1%2C+0%2C+3%2C+4%2C+3%2C+0%2C+1%2C+0%2C+3%2C+4+%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002 "f_1 \rightarrow ?, 0, 0, 1, 0, 1, 0, 3, 4, 3, 0, 1, 0, 3, 4 \cdots")

The function as a nice shape with symmetric maxima that remind one of
reptilian teeth (Figure 1).

[![prime\_Distance\_1](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_1.png?w=640)](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_1.png)Figure
1.

Now, where do the successive local maxima of this function occur? If we
leave out the undefined
![f\_1\[1\]](https://s0.wp.com/latex.php?latex=f_1%5B1%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[1]")
we see that these occur in a sequence which we call
![f\_2](https://s0.wp.com/latex.php?latex=f_2&bg=ffffff&fg=333333&s=0&c=20201002 "f_2"):

![f\_2 \\rightarrow 3, 5, 8, 11, 14, 17, 20, 25, 29, 33, 38
\\cdots](https://s0.wp.com/latex.php?latex=f_2+%5Crightarrow+3%2C+5%2C+8%2C+11%2C+14%2C+17%2C+20%2C+25%2C+29%2C+33%2C+38+%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002 "f_2 \rightarrow 3, 5, 8, 11, 14, 17, 20, 25, 29, 33, 38 \cdots")

One can right away intuitively conclude that this sequence captures the
occurrences of primes in natural number space by defining some kind of
central position between them. Hence, we can more explicitly ask, what
is the relation of
![f\_2](https://s0.wp.com/latex.php?latex=f_2&bg=ffffff&fg=333333&s=0&c=20201002 "f_2")
to the arithmetic and geometric means of successive primes behave? We
find that the above sequence ![f\_2= \\lfloor \\textrm{GM}(p\_n,
p\_{n+1})
\\rfloor](https://s0.wp.com/latex.php?latex=f_2%3D+%5Clfloor+%5Ctextrm%7BGM%7D%28p_n%2C+p_%7Bn%2B1%7D%29+%5Crfloor&bg=ffffff&fg=333333&s=0&c=20201002 "f_2= \lfloor \textrm{GM}(p_n, p_{n+1}) \rfloor")
and ![f\_2 = \\textrm{AM}(p\_n, p\_{n+1}) -
1](https://s0.wp.com/latex.php?latex=f_2+%3D+%5Ctextrm%7BAM%7D%28p_n%2C+p_%7Bn%2B1%7D%29+-+1&bg=ffffff&fg=333333&s=0&c=20201002 "f_2 = \textrm{AM}(p_n, p_{n+1}) - 1")
for primes starting with 3 onward. One can see that the local maxima of
![f\_1](https://s0.wp.com/latex.php?latex=f_1&bg=ffffff&fg=333333&s=0&c=20201002 "f_1"),
i.e. the values of
![f\_1\[f\_2\]](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2]")
(if we count leaving out the undefined first term in
![f\_1](https://s0.wp.com/latex.php?latex=f_1&bg=ffffff&fg=333333&s=0&c=20201002 "f_1")),
are all square numbers. These have a specific relationship to the prime
difference function ![\\textrm{pd}\[n\]=
p\_{n+1}-p\_n](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpd%7D%5Bn%5D%3D+p_%7Bn%2B1%7D-p_n&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pd}[n]= p_{n+1}-p_n")
starting from 3 (Figure 2). Given that from 3 onward every prime is odd,
the corresponding
![\\textrm{pd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pd}[n]")
will be even. Then, we have the following relationship to the local
maxima in
![f\_1](https://s0.wp.com/latex.php?latex=f_1&bg=ffffff&fg=333333&s=0&c=20201002 "f_1"):

![f\_1\[f\_2\] =
\\dfrac{\\left(\\textrm{pd}\[n\]\\right)^2}{4}](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D+%3D+%5Cdfrac%7B%5Cleft%28%5Ctextrm%7Bpd%7D%5Bn%5D%5Cright%29%5E2%7D%7B4%7D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2] = \dfrac{\left(\textrm{pd}[n]\right)^2}{4}")

[![prime\_Distance\_2](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_2.png?w=640)](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_2.png)Figure
2.

Thus, the local maxima of
![f\_1](https://s0.wp.com/latex.php?latex=f_1&bg=ffffff&fg=333333&s=0&c=20201002 "f_1")
help define a certain parabolically rescaled version of the prime
difference function, which, as we will see below, has utility in
understanding aspects of the occurrence of successive primes.

We know that ![\\textrm{AM} \\ge
\\textrm{GM}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BAM%7D+%5Cge+%5Ctextrm%7BGM%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{AM} \ge \textrm{GM}")
and ![\\textrm{GM}(p\_n,
p\_{n+1})](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BGM%7D%28p_n%2C+p_%7Bn%2B1%7D%29&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{GM}(p_n, p_{n+1})")
will never be a whole number. Thus, we can define the arithmetic
function ![\\textrm{pmd}\[n\] = \\textrm{AM}(p\_n, p\_{n+1}) -
\\textrm{GM}(p\_n,
p\_{n+1})](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D+%3D+%5Ctextrm%7BAM%7D%28p_n%2C+p_%7Bn%2B1%7D%29+-+%5Ctextrm%7BGM%7D%28p_n%2C+p_%7Bn%2B1%7D%29&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n] = \textrm{AM}(p_n, p_{n+1}) - \textrm{GM}(p_n, p_{n+1})").
One experimentally notes the asymptotic behavior that as ![n \\to
\\infty, \\; \\textrm{pmd}\[n\] \\to
0](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty%2C+%5C%3B+%5Ctextrm%7Bpmd%7D%5Bn%5D+%5Cto+0&bg=ffffff&fg=333333&s=0&c=20201002 "n \to \infty, \; \textrm{pmd}[n] \to 0").
However, this secular decay is marked local fluctuations. There are two
notable features of this (Figure 3): 1) The maximum value of
![\\textrm{pmd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n]")
is 0.22503561260788 for
![n=4](https://s0.wp.com/latex.php?latex=n%3D4&bg=ffffff&fg=333333&s=0&c=20201002 "n=4")
which corresponds to the ![p\_n=7,
p\_{n+1}=11](https://s0.wp.com/latex.php?latex=p_n%3D7%2C+p_%7Bn%2B1%7D%3D11&bg=ffffff&fg=333333&s=0&c=20201002 "p_n=7, p_{n+1}=11").
Thus, we can conjecture that the difference between the arithmetic and
geometric means of successive primes is always less than one fourth,
i.e. ![\\textrm{pmd}\[n\] &lt;
\\tfrac{1}{4}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D+%3C+%5Ctfrac%7B1%7D%7B4%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n] < \tfrac{1}{4}").
2) The fluctuations of
![\\textrm{pmd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n]")
starting from
![n=2](https://s0.wp.com/latex.php?latex=n%3D2&bg=ffffff&fg=333333&s=0&c=20201002 "n=2")
exactly mirror the fluctuations defined by the local maxima of
![f\_1\[n\]](https://s0.wp.com/latex.php?latex=f_1%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[n]"),
i.e.
![f\_1\[f\_2\]](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2]"),
with the magnitude of the
![f\_1\[f\_2\]](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2]")
peak tracking the magnitude of the peak in
![\\textrm{pmd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n]").
The first time a peak of given magnitude appears in
![f\_1\[f\_2\]](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2]")
it has the largest corresponding effect in
![\\textrm{pmd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n]")
with all subsequent appearances of the peak of the same magnitude being
increasingly muted.

[![prime\_Distance\_3](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_3.png?w=640)](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_3.png)Figure
3.

Thus, we can empirically determine that (Figure 4):

![\\dfrac{f\_1\[f\_2\]}{\\textrm{pmd}\[n\]} \\approx 2.3 n
\\log(n)](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bf_1%5Bf_2%5D%7D%7B%5Ctextrm%7Bpmd%7D%5Bn%5D%7D+%5Capprox+2.3+n+%5Clog%28n%29&bg=ffffff&fg=333333&s=0&c=20201002 "\dfrac{f_1[f_2]}{\textrm{pmd}[n]} \approx 2.3 n \log(n)")

![prime\_Distance\_4](https://manasataramgini.files.wordpress.com/2020/08/prime_distance_4.png?w=640)Figure
4. The green filled curve is
![\\dfrac{f\_1\[f\_2\]}{\\textrm{pmd}\[n\]}](https://s0.wp.com/latex.php?latex=%5Cdfrac%7Bf_1%5Bf_2%5D%7D%7B%5Ctextrm%7Bpmd%7D%5Bn%5D%7D&bg=ffffff&fg=333333&s=0&c=20201002 "\dfrac{f_1[f_2]}{\textrm{pmd}[n]}")
while the dark red curve is ![y=2.3 n
\\log(x)](https://s0.wp.com/latex.php?latex=y%3D2.3+n+%5Clog%28x%29&bg=ffffff&fg=333333&s=0&c=20201002 "y=2.3 n \log(x)")

Whether there is some closed form for the constant 2.3 remains an open
question to us. After we posted this note, an acquaintance from Twitter
provided a
[proof](https://colab.research.google.com/drive/1dbzmt61xvNwCLEr6dXKcNLl1tjGZWxcI)
for why the constant in the above equation should be should be 2 for
large
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002 "n").

Prime gaps have been intensely studied since at least Legendre who had a
conjecture regarding them; several tighter variants of that conjecture
have been proposed repeatedly since then. Hence, looked up the
literature to see if our conjecture regarding the difference of the
arithmetic and geometric means of successive primes might be equivalent
to any of those. We learnt recently that it is a version of a conjecture
stated by Andrica, in 1986, just about a decade before when we began
exploring the function
![f\_1\[n\]](https://s0.wp.com/latex.php?latex=f_1%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[n]").
It goes thus:

![\\sqrt{p\_{n+1}}-\\sqrt{p\_n} &lt;
1](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bp_%7Bn%2B1%7D%7D-%5Csqrt%7Bp_n%7D+%3C+1&bg=ffffff&fg=333333&s=0&c=20201002 "\sqrt{p_{n+1}}-\sqrt{p_n} < 1")

The form in which we present the conjecture appears to be a nice
statement of a strong version of the Andrica conjecture and
![f\_1\[f\_2\]](https://s0.wp.com/latex.php?latex=f_1%5Bf_2%5D&bg=ffffff&fg=333333&s=0&c=20201002 "f_1[f_2]")
provides a cleaner comparison for the fluctuations in
![\\textrm{pmd}\[n\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bpmd%7D%5Bn%5D&bg=ffffff&fg=333333&s=0&c=20201002 "\textrm{pmd}[n]")
than the simple prime gap function. Remarkably, simple as these
conjectures are, they have not been proven to date. Moreover, it seems
that even if the Riemann hypothesis were to be true, that by itself will
not imply these conjectures. Thus, yet again we have simple arithmetic
statements that can be understood or arrived at even by a school kid but
are extraordinarily difficult to prove formally. The philosophical
implications of these are interesting to us.
