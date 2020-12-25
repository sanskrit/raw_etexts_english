+++
title = "A modern glance at Nārāyaṇa-paṇḍita’s combinatorics-1"

+++
For improved reading experience one may use the [PDF
version](https://manasataramgini.files.wordpress.com/2019/09/narayana_combinatorics.pdf).

Students of the history of Hindu mathematics are well-acquainted with
Nārāyaṇa-paṇḍita’s sophisticated treatment of various aspects of
combinatorics and integer sequences in his Gaṇita-kaumudī composed in
1356 CE. In that work he gives about 43 problems relating to
combinatorics. Continuing with our study of various aspects of
Nārāyaṇa’s work using a modern lens, in this note we shall look at
some of his problems in combinatorics and what a modern (low level)
student can learn from them.

The first problem we shall look at introduces a student to the discrete
factorial function
![n\!](https://s0.wp.com/latex.php?latex=n%21&bg=ffffff&fg=333333&s=0
"n!") using a verse in the Vasantatilakā meter;  
Problem-1:  
cāpeṣu khaḍga-ḍamarūka-kapāla-pāśaiḥ khaṭvāṅga-śūla-phaṇi-śakti-yutair
bhavanti ।  
anyonya-hasta-kalitaiḥ kati mūrtibhedāḥ śambho harer iva
gadā’ri-saroja-śaṅkhaiḥ ॥  
With a bow (1), an arrow (2), a sword (3), a double-drum (4), a skull
(5), a lasso (6), a skull-topped rod (7), a trident (8), a snake (9) and
a spear (10) — by changing them from one hand to another how many
different images of Rudra come to be? Likewise, of Viṣṇu with a mace
(1), a wheel (2), a lotus (3) and a conch (4).

For Rudra with 10 arms the answer is
![10\!=3628800](https://s0.wp.com/latex.php?latex=10%21%3D3628800&bg=ffffff&fg=333333&s=0
"10!=3628800"), whereas for Viṣṇu it is
![4\!=24](https://s0.wp.com/latex.php?latex=4%21%3D24&bg=ffffff&fg=333333&s=0
"4!=24"). This problem was well-known among earlier Hindu scientists and
is not original to Nārāyaṇa. Here, he is merely reusing this verse
without any change from Bhāskara-II’s Līlāvatī. In the case of Viṣṇu,
each of these 24 permutations have a specific name starting from Keśava.
There are correspondingly 24 forms of Lakṣmī. These forms are an
important aspect of the Pañcarātra system where they are counted along
with the 4 basic vyūha-s in the śuddha-mūrti-s (“Platonic” forms) in
texts like the Nārada-pāñcarātra and are attested in iconography across
the Indosphere. The general use of permutations in various endeavors is
mentioned by Nārāyaṇa after he provides the procedure for writing out
the permutations:  
aṅka-prastāra-vidhiś caivaṃ mūrtiprabhedānām ।  
sa-ri-ga-ma-pa-dha-nīty eṣāṃ vīṇāyā nikvaṇānāṃ ca ॥  
This procedure generating the permutation of digits is also used in
permutations of images \[of deities\], sa-ri-ga-ma-pa-dha-ni (the notes
of Hindu music) and the notes produced by the vīṇā.

Problem-2 (A verse again in the Vasantatilakā meter):  
dhātrī lavaṅga-dala-kesara nāga-railā vakraṃ kaṇāḥ samaricāḥ sasitā
bhavanti ।  
ekādibhiś ca militair gadināṃ katīha cūrṇāni bho vada gadāpanude gadajña
॥  
O apothecary, how many different different disease-curing spice-powders
come from mixing one etc (i.e. 1, 2, 3…) of gooseberry, clove, cinnamon,
saffron, ginger, cardamom, Indian may apple (*Sinopodophyllum
hexandrum*), cumin, pepper and sugar?

This type of problem is encountered widely in Hindu literature — we find
a discussion of the combinations of tastes in the medical saṃhitā-s of
Caraka and Suśruta. Subsequently, the great naturalist Varāhamihira in
![\\sim](https://s0.wp.com/latex.php?latex=%5Csim&bg=ffffff&fg=333333&s=0
"\\sim") 550 CE discussed the production of various perfumes by
combinations of basic scents. Such combinations are also discussed by
king Bhojadeva Paramāra in his chemical treatise in the 1000s of the CE.
Related problems are also taken up in Bhāskara-II and by the polymath
Śārṅgadeva in his musical treatise. This particular problem is rather
typical of the combinations used in preparation of drugs in Āyurveda. As
a pharmacological aside the Indian may apple if properly used can be
quite effective treating tumors caused by certain papillomaviruses.
Returning to the solution of the problem, we need to recall the formula
for combinations:

![{}^nC\_k =
\\dfrac{n\!}{k\!(n-k)\!}](https://s0.wp.com/latex.php?latex=%7B%7D%5EnC_k+%3D+%5Cdfrac%7Bn%21%7D%7Bk%21%28n-k%29%21%7D&bg=ffffff&fg=333333&s=0
"{}^nC_k = \\dfrac{n!}{k!(n-k)!}")

Let ![N](https://s0.wp.com/latex.php?latex=N&bg=ffffff&fg=333333&s=0
"N") be the total number of powders that can be created via each set of
combinations: by taking 1 at a time we get 10, by taking 2 at time we
get
![{}^{10}C\_2=45](https://s0.wp.com/latex.php?latex=%7B%7D%5E%7B10%7DC_2%3D45&bg=ffffff&fg=333333&s=0
"{}^{10}C_2=45") and so on. Thus, we get:

![N=\\displaystyle \\sum\_{k=1}^{10}
{}^{10}C\_k=1023](https://s0.wp.com/latex.php?latex=N%3D%5Cdisplaystyle+%5Csum_%7Bk%3D1%7D%5E%7B10%7D+%7B%7D%5E%7B10%7DC_k%3D1023&bg=ffffff&fg=333333&s=0
"N=\\displaystyle \\sum_{k=1}^{10} {}^{10}C_k=1023")

[![nArAyaNa\_combinations\_Fig1](https://manasataramgini.files.wordpress.com/2019/09/narayana_combinations_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2019/09/narayana_combinations_fig1.png)Figure
1

In Hindu tradition, the study of combinations and their sum goes back to
at least the Chandas-śāstra (the treatise on meters) of Piṅgala. This
has been extensively discussed in the literature and we present it only
briefly:

pare pūrṇam । pare pūrṇam iti । CS 8.34-35  
Complete it by using the two distal ends. Repeat to complete using the
distal flanking ends.

While these original sūtra-s of Piṅgala are difficult to directly
understand, they have been explained in the glosses of several authors
since (e.g. Kedāra-bhaṭṭa and Halāyudha). The two sūtra-s specify the
construction of the Meru-prastāra or the combinatorial triangle. The
first sūtra implies that you write out the flanking cells with 1
corresponding to row
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"):

![1 \\\\ 1 \\quad 1 \\\\ 1 \\quad {. } \\quad 1 \\\\ 1 \\quad {. }
\\quad {. } \\quad 1 \\\\ 1 \\quad {. } \\quad {. } \\quad {. } \\quad 1
\\\\ 1 \\quad {. } \\quad { .} \\quad {. } \\quad {. } \\quad 1 \\\\
](https://s0.wp.com/latex.php?latex=1+%5C%5C+1+%5Cquad+1+%5C%5C+1+%5Cquad+%7B.+%7D+%5Cquad+1+%5C%5C+1+%5Cquad+%7B.+%7D+%5Cquad+%7B.+%7D+%5Cquad+1+%5C%5C+1+%5Cquad+%7B.+%7D+%5Cquad+%7B.+%7D+%5Cquad+%7B.+%7D+%5Cquad+1+%5C%5C+1+%5Cquad+%7B.+%7D+%5Cquad+%7B+.%7D+%5Cquad+%7B.+%7D+%5Cquad+%7B.+%7D+%5Cquad+1+%5C%5C+&bg=ffffff&fg=333333&s=0
"1 \\\\ 1 \\quad 1 \\\\ 1 \\quad {. } \\quad 1 \\\\ 1 \\quad {. } \\quad {. } \\quad 1 \\\\ 1 \\quad {. } \\quad {. } \\quad {. } \\quad 1 \\\\ 1 \\quad {. } \\quad { .} \\quad {. } \\quad {. } \\quad 1 \\\\ ")

The second sūtra implies that you fill in the interior cell by repeating
the procedure:

![1 \\\\ 1 \\quad 1 \\\\ 1 \\quad 2 \\quad 1 \\\\ 1 \\quad 3 \\quad 3
\\quad 1 \\\\ 1 \\quad 4 \\quad 6 \\quad 4 \\quad 1 \\\\ 1 \\quad 5
\\quad 10 \\quad 10 \\quad 5 \\quad 1 \\\\
](https://s0.wp.com/latex.php?latex=1+%5C%5C+1+%5Cquad+1+%5C%5C+1+%5Cquad+2+%5Cquad+1+%5C%5C+1+%5Cquad+3+%5Cquad+3+%5Cquad+1+%5C%5C+1+%5Cquad+4+%5Cquad+6+%5Cquad+4+%5Cquad+1+%5C%5C+1+%5Cquad+5+%5Cquad+10+%5Cquad+10+%5Cquad+5+%5Cquad+1+%5C%5C+&bg=ffffff&fg=333333&s=0
"1 \\\\ 1 \\quad 1 \\\\ 1 \\quad 2 \\quad 1 \\\\ 1 \\quad 3 \\quad 3 \\quad 1 \\\\ 1 \\quad 4 \\quad 6 \\quad 4 \\quad 1 \\\\ 1 \\quad 5 \\quad 10 \\quad 10 \\quad 5 \\quad 1 \\\\ ")

While this is extensively discussed in the context of Chandas, one can
also find a clear algorithm in Bhāskara-II’s Līlāvatī using the
combination function to produce not just the combinatorial triangle
(Meru) but also any row or cell of it. Thus, from the Meru we can write
the formula for the expansion of a binomial as:

![(x+y)^n=\\displaystyle \\sum\_{k=0}^{n}{}^nC\_k x^k
y^{n-k}](https://s0.wp.com/latex.php?latex=%28x%2By%29%5En%3D%5Cdisplaystyle+%5Csum_%7Bk%3D0%7D%5E%7Bn%7D%7B%7D%5EnC_k+x%5Ek+y%5E%7Bn-k%7D&bg=ffffff&fg=333333&s=0
"(x+y)^n=\\displaystyle \\sum_{k=0}^{n}{}^nC_k x^k y^{n-k}")

This tells us that the null-product or
![0\!=1](https://s0.wp.com/latex.php?latex=0%21%3D1&bg=ffffff&fg=333333&s=0
"0!=1") (implicitly provided in Bhāskara-II’s algorithm: there only 1
way of not choosing anything). The magnitudes of the
![k^{th}](https://s0.wp.com/latex.php?latex=k%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"k^{th}")-combination or the values assumed by the combination function
for a given
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") as
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
changes determine the values of the individual terms of the above
expansion. Hence, we use the problem-2 to introduce and illustrate to
students the shape of the binomial distribution (Figure 1). Since the
Meru itself can be seen as the triangle of
![(1+1)^n](https://s0.wp.com/latex.php?latex=%281%2B1%29%5En&bg=ffffff&fg=333333&s=0
"(1+1)^n"), we get the formula for the sum of combinations for a given
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
as,

![N=\\displaystyle \\sum\_{k=0}^{n}
{}^{n}C\_k=2^n](https://s0.wp.com/latex.php?latex=N%3D%5Cdisplaystyle+%5Csum_%7Bk%3D0%7D%5E%7Bn%7D+%7B%7D%5E%7Bn%7DC_k%3D2%5En&bg=ffffff&fg=333333&s=0
"N=\\displaystyle \\sum_{k=0}^{n} {}^{n}C_k=2^n")

If we leave out the null combination
![k=0](https://s0.wp.com/latex.php?latex=k%3D0&bg=ffffff&fg=333333&s=0
"k=0"), we get
![N=2^n-1](https://s0.wp.com/latex.php?latex=N%3D2%5En-1&bg=ffffff&fg=333333&s=0
"N=2^n-1") as in the problem-2 where
![N=2^{10}-1](https://s0.wp.com/latex.php?latex=N%3D2%5E%7B10%7D-1&bg=ffffff&fg=333333&s=0
"N=2^{10}-1").

As this note is part historical and part educational (for a low-level
student), let us next consider another binomial expansion that played a
cornerstone role in the origin of modern mathematics,

![\\displaystyle \\lim\_{n \\to \\infty}
\\left(1+\\dfrac{1}{n}\\right)^n](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+%5Cleft%281%2B%5Cdfrac%7B1%7D%7Bn%7D%5Cright%29%5En&bg=ffffff&fg=333333&s=0
"\\displaystyle \\lim_{n \\to \\infty} \\left(1+\\dfrac{1}{n}\\right)^n")

We can intuitively sense based on the easily-determined first 3 terms
that it might converge to some number between 2 and 3 but what is that
number? We can experimentally see that the above expression converges
slowly: for
![n=10](https://s0.wp.com/latex.php?latex=n%3D10&bg=ffffff&fg=333333&s=0
"n=10") we get 2.6; for
![n=100](https://s0.wp.com/latex.php?latex=n%3D100&bg=ffffff&fg=333333&s=0
"n=100") we get 2.7; for
![n=200](https://s0.wp.com/latex.php?latex=n%3D200&bg=ffffff&fg=333333&s=0
"n=200") we have 2.71. This is exactly where Jakob Bernoulli got to when
he first encountered this problem and realized that it was converging to
something around 2.71. However, we can do better by determining the
limit:

![\\displaystyle \\lim\_{n \\to \\infty}
\\left(1+\\dfrac{1}{n}\\right)^n = \\dfrac{1}{0\! \\cdot n^0}+
\\dfrac{n}{1\! \\cdot n^1} + \\dfrac{n\\cdot (n-1)}{2\! \\cdot n^2}+
\\dfrac{n\\cdot (n-1) \\cdot (n-2)}{3\! \\cdot n^3}...\\\\\[10pt\] =
\\dfrac{1}{n^0 \\cdot0\!}+ \\dfrac{n}{n \\cdot 1\!} + \\dfrac{n^2 \\cdot
(1-1/n)}{n^2 \\cdot 2\!}+ \\dfrac{n^3\\cdot (1-1/n) \\cdot (1-2/n)}{n^3
\\cdot 3\! }...\\\\\[10pt\] = \\dfrac{1}{0\!}+ \\dfrac{1}{1\!} +
\\dfrac{(1-1/n)}{2\!}+ \\dfrac{(1-1/n) \\cdot
(1-2/n)}{3\!}...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+%5Cleft%281%2B%5Cdfrac%7B1%7D%7Bn%7D%5Cright%29%5En+%3D+%5Cdfrac%7B1%7D%7B0%21+%5Ccdot+n%5E0%7D%2B+%5Cdfrac%7Bn%7D%7B1%21+%5Ccdot+n%5E1%7D+%2B+%5Cdfrac%7Bn%5Ccdot+%28n-1%29%7D%7B2%21+%5Ccdot+n%5E2%7D%2B+%5Cdfrac%7Bn%5Ccdot+%28n-1%29+%5Ccdot+%28n-2%29%7D%7B3%21+%5Ccdot+n%5E3%7D...%5C%5C%5B10pt%5D+%3D+%5Cdfrac%7B1%7D%7Bn%5E0+%5Ccdot0%21%7D%2B+%5Cdfrac%7Bn%7D%7Bn+%5Ccdot+1%21%7D+%2B+%5Cdfrac%7Bn%5E2+%5Ccdot+%281-1%2Fn%29%7D%7Bn%5E2+%5Ccdot+2%21%7D%2B+%5Cdfrac%7Bn%5E3%5Ccdot+%281-1%2Fn%29+%5Ccdot+%281-2%2Fn%29%7D%7Bn%5E3+%5Ccdot+3%21+%7D...%5C%5C%5B10pt%5D+%3D+%5Cdfrac%7B1%7D%7B0%21%7D%2B+%5Cdfrac%7B1%7D%7B1%21%7D+%2B+%5Cdfrac%7B%281-1%2Fn%29%7D%7B2%21%7D%2B+%5Cdfrac%7B%281-1%2Fn%29+%5Ccdot+%281-2%2Fn%29%7D%7B3%21%7D...&bg=ffffff&fg=333333&s=0
"\\displaystyle \\lim_{n \\to \\infty} \\left(1+\\dfrac{1}{n}\\right)^n = \\dfrac{1}{0! \\cdot n^0}+ \\dfrac{n}{1! \\cdot n^1} + \\dfrac{n\\cdot (n-1)}{2! \\cdot n^2}+ \\dfrac{n\\cdot (n-1) \\cdot (n-2)}{3! \\cdot n^3}...\\\\[10pt] = \\dfrac{1}{n^0 \\cdot0!}+ \\dfrac{n}{n \\cdot 1!} + \\dfrac{n^2 \\cdot (1-1/n)}{n^2 \\cdot 2!}+ \\dfrac{n^3\\cdot (1-1/n) \\cdot (1-2/n)}{n^3 \\cdot 3! }...\\\\[10pt] = \\dfrac{1}{0!}+ \\dfrac{1}{1!} + \\dfrac{(1-1/n)}{2!}+ \\dfrac{(1-1/n) \\cdot (1-2/n)}{3!}...")

Taking the limit ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty") we get:

![\\displaystyle \\lim n \\to \\infty \\left(1+\\dfrac{1}{n}\\right)^n=
\\sum\_{n=0}^{\\infty}
\\dfrac{1}{n\!}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim+n+%5Cto+%5Cinfty+%5Cleft%281%2B%5Cdfrac%7B1%7D%7Bn%7D%5Cright%29%5En%3D+%5Csum_%7Bn%3D0%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%7D%7Bn%21%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle \\lim n \\to \\infty \\left(1+\\dfrac{1}{n}\\right)^n= \\sum_{n=0}^{\\infty} \\dfrac{1}{n!}")

Thus, our limit is the infinite sum of the reciprocal of the factorials.
This is much faster-converging and with just 10 terms converges to 7
places after the decimal point to 2.7182818… The importance of this
limit and the number it converges to comes to fore in another central
result in the emergence of modern mathematics: What is the rate of
change (derivative) of the logarithmic function? Let us start with a
logarithm taken to some base
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b"),
i.e.
![y=\\log\_b(x)](https://s0.wp.com/latex.php?latex=y%3D%5Clog_b%28x%29&bg=ffffff&fg=333333&s=0
"y=\\log_b(x)"). Hence,

![\\displaystyle \\dfrac{dy}{dx}=\\lim\_{\\delta x \\to 0}
\\dfrac{\\log\_b(x+\\delta x)-\\log\_b(x)}{\\delta x} =\\log\_b\\left(
\\dfrac{x+\\delta x}{x}\\right)^{1/\\delta x} =\\log\_b\\left(
1+\\dfrac{\\delta x}{x}\\right)^{1/\\delta x} \\\\\[10pt\]
=\\log\_b\\left( 1+\\dfrac{\\delta x}{x}\\right)^{x/\\delta x \\times
1/x} =\\dfrac{1}{x}\\log\_b\\left( 1+\\dfrac{\\delta
x}{x}\\right)^{x/\\delta
x}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cdfrac%7Bdy%7D%7Bdx%7D%3D%5Clim_%7B%5Cdelta+x+%5Cto+0%7D+%5Cdfrac%7B%5Clog_b%28x%2B%5Cdelta+x%29-%5Clog_b%28x%29%7D%7B%5Cdelta+x%7D+%3D%5Clog_b%5Cleft%28+%5Cdfrac%7Bx%2B%5Cdelta+x%7D%7Bx%7D%5Cright%29%5E%7B1%2F%5Cdelta+x%7D+%3D%5Clog_b%5Cleft%28+1%2B%5Cdfrac%7B%5Cdelta+x%7D%7Bx%7D%5Cright%29%5E%7B1%2F%5Cdelta+x%7D+%5C%5C%5B10pt%5D+%3D%5Clog_b%5Cleft%28+1%2B%5Cdfrac%7B%5Cdelta+x%7D%7Bx%7D%5Cright%29%5E%7Bx%2F%5Cdelta+x+%5Ctimes+1%2Fx%7D+%3D%5Cdfrac%7B1%7D%7Bx%7D%5Clog_b%5Cleft%28+1%2B%5Cdfrac%7B%5Cdelta+x%7D%7Bx%7D%5Cright%29%5E%7Bx%2F%5Cdelta+x%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle \\dfrac{dy}{dx}=\\lim_{\\delta x \\to 0} \\dfrac{\\log_b(x+\\delta x)-\\log_b(x)}{\\delta x} =\\log_b\\left( \\dfrac{x+\\delta x}{x}\\right)^{1/\\delta x} =\\log_b\\left( 1+\\dfrac{\\delta x}{x}\\right)^{1/\\delta x} \\\\[10pt] =\\log_b\\left( 1+\\dfrac{\\delta x}{x}\\right)^{x/\\delta x \\times 1/x} =\\dfrac{1}{x}\\log_b\\left( 1+\\dfrac{\\delta x}{x}\\right)^{x/\\delta x}")

Now we can write ![\\tfrac{\\delta
x}{x}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cdelta+x%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\delta x}{x}") as some ![\\tfrac{1}{n}; \\therefore
\\tfrac{x}{\\delta
x}=n](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Bn%7D%3B+%5Ctherefore+%5Ctfrac%7Bx%7D%7B%5Cdelta+x%7D%3Dn&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{n}; \\therefore \\tfrac{x}{\\delta x}=n"). As ![\\delta x
\\to 0, n \\to
\\infty](https://s0.wp.com/latex.php?latex=%5Cdelta+x+%5Cto+0%2C+n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"\\delta x \\to 0, n \\to \\infty"). Thus, we can rewrite our limit as:

![\\displaystyle \\dfrac{d}{dx}y= \\lim\_{n \\to \\infty}
\\dfrac{1}{x}\\log\_b\\left(
1+\\dfrac{1}{n}\\right)^{n}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cdfrac%7Bd%7D%7Bdx%7Dy%3D+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+%5Cdfrac%7B1%7D%7Bx%7D%5Clog_b%5Cleft%28+1%2B%5Cdfrac%7B1%7D%7Bn%7D%5Cright%29%5E%7Bn%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle \\dfrac{d}{dx}y= \\lim_{n \\to \\infty} \\dfrac{1}{x}\\log_b\\left( 1+\\dfrac{1}{n}\\right)^{n}")

We observe that this is the same limit we evaluated above. Now, if we
define ![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0
"e") as the sum of the reciprocal of the factorials, which is the limit,
and set
![b=e](https://s0.wp.com/latex.php?latex=b%3De&bg=ffffff&fg=333333&s=0
"b=e") then
![\\tfrac{d}{dx}\\log\_e(x)=\\tfrac{1}{x}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bd%7D%7Bdx%7D%5Clog_e%28x%29%3D%5Ctfrac%7B1%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{d}{dx}\\log_e(x)=\\tfrac{1}{x}"). Thus, we get
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e") to
be the natural base of logarithmic function and the derivative of
![\\log(x)](https://s0.wp.com/latex.php?latex=%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"\\log(x)"). Conversely, the area under a unit rectangular hyperbola,
i.e
![y=\\tfrac{1}{x}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7B1%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{1}{x}") is the logarithmic function with base
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e").

Armed with
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e"),
we can next retrace certain developments in the history of early modern
mathematics. What is the relationship of an arbitrary exponential curve
![y=a^x](https://s0.wp.com/latex.php?latex=y%3Da%5Ex&bg=ffffff&fg=333333&s=0
"y=a^x") to
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e").
For this we need to first determine the derivative of
![a^x](https://s0.wp.com/latex.php?latex=a%5Ex&bg=ffffff&fg=333333&s=0
"a^x"). This is trivially done now that we have the derivative of
![\\log(x)](https://s0.wp.com/latex.php?latex=%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"\\log(x)"):

![y=a^x \\; \\therefore \\log(y)=x \\log(a)\\\\\[10pt\] \\dfrac{d
\\log(y)}{dx}=\\log(a)\\\\\[10pt\] \\dfrac{d \\log(y)}{dy}\\cdot
\\dfrac{dy}{dx}=\\log(a)\\\\\[10pt\] \\dfrac{1}{y}\\cdot
\\dfrac{dy}{dx}=\\log(a)\\\\\[10pt\] \\dfrac{dy}{dx}=y\\log(x)=a^x
\\log(a)](https://s0.wp.com/latex.php?latex=y%3Da%5Ex+%5C%3B+%5Ctherefore+%5Clog%28y%29%3Dx+%5Clog%28a%29%5C%5C%5B10pt%5D+%5Cdfrac%7Bd+%5Clog%28y%29%7D%7Bdx%7D%3D%5Clog%28a%29%5C%5C%5B10pt%5D+%5Cdfrac%7Bd+%5Clog%28y%29%7D%7Bdy%7D%5Ccdot+%5Cdfrac%7Bdy%7D%7Bdx%7D%3D%5Clog%28a%29%5C%5C%5B10pt%5D+%5Cdfrac%7B1%7D%7By%7D%5Ccdot+%5Cdfrac%7Bdy%7D%7Bdx%7D%3D%5Clog%28a%29%5C%5C%5B10pt%5D+%5Cdfrac%7Bdy%7D%7Bdx%7D%3Dy%5Clog%28x%29%3Da%5Ex+%5Clog%28a%29&bg=ffffff&fg=333333&s=0
"y=a^x \\; \\therefore \\log(y)=x \\log(a)\\\\[10pt] \\dfrac{d \\log(y)}{dx}=\\log(a)\\\\[10pt] \\dfrac{d \\log(y)}{dy}\\cdot \\dfrac{dy}{dx}=\\log(a)\\\\[10pt] \\dfrac{1}{y}\\cdot \\dfrac{dy}{dx}=\\log(a)\\\\[10pt] \\dfrac{dy}{dx}=y\\log(x)=a^x \\log(a)")

[![exponentials\_e](https://manasataramgini.files.wordpress.com/2019/09/exponentials_e.png?w=640)](https://manasataramgini.files.wordpress.com/2019/09/exponentials_e.png)Figure
2

With this in hand we can see the relationship of any exponential curve
![y=a^x](https://s0.wp.com/latex.php?latex=y%3Da%5Ex&bg=ffffff&fg=333333&s=0
"y=a^x") to
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e")
(Figure 2):  
![\\bullet](https://s0.wp.com/latex.php?latex=%5Cbullet&bg=ffffff&fg=333333&s=0
"\\bullet") Consider the family of exponential curves
![y=a^x](https://s0.wp.com/latex.php?latex=y%3Da%5Ex&bg=ffffff&fg=333333&s=0
"y=a^x") (Figure 2; the red curve is
![y=e^x](https://s0.wp.com/latex.php?latex=y%3De%5Ex&bg=ffffff&fg=333333&s=0
"y=e^x")). From the above result we see that the tangent to a
exponential curve will have the slope
![m=\\log(a)a^x](https://s0.wp.com/latex.php?latex=m%3D%5Clog%28a%29a%5Ex&bg=ffffff&fg=333333&s=0
"m=\\log(a)a^x")

![\\bullet](https://s0.wp.com/latex.php?latex=%5Cbullet&bg=ffffff&fg=333333&s=0
"\\bullet") Let
![x=\\tfrac{1}{\\log(a)}](https://s0.wp.com/latex.php?latex=x%3D%5Ctfrac%7B1%7D%7B%5Clog%28a%29%7D&bg=ffffff&fg=333333&s=0
"x=\\tfrac{1}{\\log(a)}"). Then:
![m=\\log(a)a^{1/\\log(a)}=\\log(a)a^{\\log(e)/\\log(a)}=\\log(a)
a^{\\log\_a(e)}=e\\log(a)](https://s0.wp.com/latex.php?latex=m%3D%5Clog%28a%29a%5E%7B1%2F%5Clog%28a%29%7D%3D%5Clog%28a%29a%5E%7B%5Clog%28e%29%2F%5Clog%28a%29%7D%3D%5Clog%28a%29+a%5E%7B%5Clog_a%28e%29%7D%3De%5Clog%28a%29&bg=ffffff&fg=333333&s=0
"m=\\log(a)a^{1/\\log(a)}=\\log(a)a^{\\log(e)/\\log(a)}=\\log(a) a^{\\log_a(e)}=e\\log(a)")

![\\bullet](https://s0.wp.com/latex.php?latex=%5Cbullet&bg=ffffff&fg=333333&s=0
"\\bullet") A line passing through origin has the equation
![y=mx](https://s0.wp.com/latex.php?latex=y%3Dmx&bg=ffffff&fg=333333&s=0
"y=mx"). We set
![m=e\\log(a)](https://s0.wp.com/latex.php?latex=m%3De%5Clog%28a%29&bg=ffffff&fg=333333&s=0
"m=e\\log(a)"); when
![x=\\tfrac{1}{\\log(a)}](https://s0.wp.com/latex.php?latex=x%3D%5Ctfrac%7B1%7D%7B%5Clog%28a%29%7D&bg=ffffff&fg=333333&s=0
"x=\\tfrac{1}{\\log(a)}") the equation of the line yields
![y=e](https://s0.wp.com/latex.php?latex=y%3De&bg=ffffff&fg=333333&s=0
"y=e"). Similarly, the equation of the exponential curve yields
![y=a^{1/\\log(a)}=e](https://s0.wp.com/latex.php?latex=y%3Da%5E%7B1%2F%5Clog%28a%29%7D%3De&bg=ffffff&fg=333333&s=0
"y=a^{1/\\log(a)}=e"). Thus, the line
![y=e\\log(a)x](https://s0.wp.com/latex.php?latex=y%3De%5Clog%28a%29x&bg=ffffff&fg=333333&s=0
"y=e\\log(a)x") is the tangent to
![y=a^x](https://s0.wp.com/latex.php?latex=y%3Da%5Ex&bg=ffffff&fg=333333&s=0
"y=a^x") from origin.

![\\bullet](https://s0.wp.com/latex.php?latex=%5Cbullet&bg=ffffff&fg=333333&s=0
"\\bullet") Thus, the tangent to an exponential curve from the origin
will touch it at a height of
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e")
from the
![X](https://s0.wp.com/latex.php?latex=X&bg=ffffff&fg=333333&s=0
"X")-axis at
![x=\\tfrac{1}{\\log(e)}](https://s0.wp.com/latex.php?latex=x%3D%5Ctfrac%7B1%7D%7B%5Clog%28e%29%7D&bg=ffffff&fg=333333&s=0
"x=\\tfrac{1}{\\log(e)}")

Given the derivative of the exponential function, it is obvious that the
derivative of
![e^x](https://s0.wp.com/latex.php?latex=e%5Ex&bg=ffffff&fg=333333&s=0
"e^x") is
![e^x](https://s0.wp.com/latex.php?latex=e%5Ex&bg=ffffff&fg=333333&s=0
"e^x"). This in turn allows one to establish the relationship of any
power of
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e") to
the reciprocal of factorials. Consider the infinite series:

![\\displaystyle \\textrm{f}(x)= \\sum\_{n=0}^{\\infty}
\\dfrac{x^n}{n\!}=1+x+\\dfrac{x^2}{2}+\\dfrac{x^3}{3\!}+\\dfrac{x^4}{4\!}+...\\\\\[10pt\]\\\\
\\dfrac{d \\textrm{f}(x)}{dx} =
1+x+\\dfrac{x^2}{2}+\\dfrac{x^3}{3\!}+...\\\\\[10pt\] \\therefore
\\dfrac{d \\textrm{f}(x)}{dx} =
\\textrm{f}(x)](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Ctextrm%7Bf%7D%28x%29%3D+%5Csum_%7Bn%3D0%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7Bx%5En%7D%7Bn%21%7D%3D1%2Bx%2B%5Cdfrac%7Bx%5E2%7D%7B2%7D%2B%5Cdfrac%7Bx%5E3%7D%7B3%21%7D%2B%5Cdfrac%7Bx%5E4%7D%7B4%21%7D%2B...%5C%5C%5B10pt%5D%5C%5C+%5Cdfrac%7Bd+%5Ctextrm%7Bf%7D%28x%29%7D%7Bdx%7D+%3D+1%2Bx%2B%5Cdfrac%7Bx%5E2%7D%7B2%7D%2B%5Cdfrac%7Bx%5E3%7D%7B3%21%7D%2B...%5C%5C%5B10pt%5D+%5Ctherefore+%5Cdfrac%7Bd+%5Ctextrm%7Bf%7D%28x%29%7D%7Bdx%7D+%3D+%5Ctextrm%7Bf%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\displaystyle \\textrm{f}(x)= \\sum_{n=0}^{\\infty} \\dfrac{x^n}{n!}=1+x+\\dfrac{x^2}{2}+\\dfrac{x^3}{3!}+\\dfrac{x^4}{4!}+...\\\\[10pt]\\\\ \\dfrac{d \\textrm{f}(x)}{dx} = 1+x+\\dfrac{x^2}{2}+\\dfrac{x^3}{3!}+...\\\\[10pt] \\therefore \\dfrac{d \\textrm{f}(x)}{dx} = \\textrm{f}(x)")

Now the function whose derivative is the same as the function itself is
![e^x](https://s0.wp.com/latex.php?latex=e%5Ex&bg=ffffff&fg=333333&s=0
"e^x"); hence,

![\\displaystyle e^x= \\sum\_{n=0}^{\\infty}
\\dfrac{x^n}{n\!}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+e%5Ex%3D+%5Csum_%7Bn%3D0%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7Bx%5En%7D%7Bn%21%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle e^x= \\sum_{n=0}^{\\infty} \\dfrac{x^n}{n!}")

Thus, this gives the relationship of a power of
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e") to
the reciprocal of factorials. If we put
![x=1](https://s0.wp.com/latex.php?latex=x%3D1&bg=ffffff&fg=333333&s=0
"x=1") in the above we get the same infinite series for
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e") as
we obtained from the above limit. With this in hand, we can arrive at
one of the most remarkable functions discovered in the history of early
modern mathematics that is key to our understanding of the universe.

[![nArAyaNa\_normal\_Figure3](https://manasataramgini.files.wordpress.com/2019/09/narayana_normal_figure3.png?w=640)](https://manasataramgini.files.wordpress.com/2019/09/narayana_normal_figure3.png)Figure
3

In problem-2 we saw the magnitudes assumed by the combination function.
We see that they appear to define a bell-shaped curve (Figure 2, 3).
What is the curve that best approximates the binomial coefficients as
![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty") (Figure 3; shown for
![n=50](https://s0.wp.com/latex.php?latex=n%3D50&bg=ffffff&fg=333333&s=0
"n=50")). For this we can begin by noting the following. It is a
symmetric curve around the central or the highest value binomial
coefficients. It falls sub-exponentially and is asymptotic to the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis. Given this we can try to construct this basic shape with its
maximum centered on
![(0,1)](https://s0.wp.com/latex.php?latex=%280%2C1%29&bg=ffffff&fg=333333&s=0
"(0,1)") using an infinite series approach (Figure 4). Given that it is
symmetric, we only need to consider even powers of
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x") in
such a series.

[![bell\_curve\_expansion](https://manasataramgini.files.wordpress.com/2019/09/bell_curve_expansion.png?w=640)](https://manasataramgini.files.wordpress.com/2019/09/bell_curve_expansion.png)Figure
4

We start with
![y=\\tfrac{x^0}{0\!}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx%5E0%7D%7B0%21%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x^0}{0!}"). This in the least captures the maximum but little
else. So the next term corrects this by a subtraction to get a curve
around the maximum; thus
![y=\\tfrac{x^0}{0\!}-\\tfrac{x^2}{1\!}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx%5E0%7D%7B0%21%7D-%5Ctfrac%7Bx%5E2%7D%7B1%21%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x^0}{0!}-\\tfrac{x^2}{1!}"). However, this correct falls
straight down and we have to add a term to get closer to the asymptotic
behavior with respect to the
![X](https://s0.wp.com/latex.php?latex=X&bg=ffffff&fg=333333&s=0
"X")-axis. Thus we get:
![y=\\tfrac{x^0}{0\!}-\\tfrac{x^2}{1\!}+\\tfrac{x^4}{2\!}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx%5E0%7D%7B0%21%7D-%5Ctfrac%7Bx%5E2%7D%7B1%21%7D%2B%5Ctfrac%7Bx%5E4%7D%7B2%21%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x^0}{0!}-\\tfrac{x^2}{1!}+\\tfrac{x^4}{2!}"). We continue
this process (first 8 steps are shown in Figure 4) and get the infinite
series:

![y=\\displaystyle \\sum\_{0}^{\\infty}
\\dfrac{\\left(-x^2\\right)^n}{n\!}](https://s0.wp.com/latex.php?latex=y%3D%5Cdisplaystyle+%5Csum_%7B0%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B%5Cleft%28-x%5E2%5Cright%29%5En%7D%7Bn%21%7D&bg=ffffff&fg=333333&s=0
"y=\\displaystyle \\sum_{0}^{\\infty} \\dfrac{\\left(-x^2\\right)^n}{n!}")

From the above series for a power of
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e") we
can immediately see that:

![y=e^{-x^2}](https://s0.wp.com/latex.php?latex=y%3De%5E%7B-x%5E2%7D&bg=ffffff&fg=333333&s=0
"y=e^{-x^2}")

This is the famous equation of the shape of the normal distribution,
which is a limit of the binomial distribution as ![n \\to
\\infty](https://s0.wp.com/latex.php?latex=n+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"n \\to \\infty"). With this we can now provide the continuous
approximation for the combination function normalized by the maximal
combination (Figure 3):

![y=e^{-(x-n/2)^2/(n/2)}](https://s0.wp.com/latex.php?latex=y%3De%5E%7B-%28x-n%2F2%29%5E2%2F%28n%2F2%29%7D&bg=ffffff&fg=333333&s=0
"y=e^{-(x-n/2)^2/(n/2)}")

Thus for the actual combination function we get:

![y={}^nC\_{n/2}e^{-(x-n/2)^2/(n/2)}](https://s0.wp.com/latex.php?latex=y%3D%7B%7D%5EnC_%7Bn%2F2%7De%5E%7B-%28x-n%2F2%29%5E2%2F%28n%2F2%29%7D&bg=ffffff&fg=333333&s=0
"y={}^nC_{n/2}e^{-(x-n/2)^2/(n/2)}")

Problem-3:  
nāgāgni-randhrair-dvi-guṇo’ṅga-candrair  
vadāśu rupādi navāvasānaiḥ ।  
bhedām̐ś ca labdhy aṅka-mukhāntya-bhedān  
ūrdhvāṅka-yogaṃ sakalāṅka-yogam ।  
aṅka-prapātaṃ ca sakhe pṛthak te  
vadā ‘ṅkapāśe ‘sti pariśramaś cet ॥  
Snakes (8), fires (3), deficit (9): (9,3,8); two (2), guṇa-s (3), limbs
\[of Veda\] (6), moon (1): (1, 6, 3, 2); starting from form (1) to nine
(9): (1,2,3…9); Quickly state: (i) the number of permutations; (ii) the
number of permutations either beginning or ending in one of those
digits; (iii) sum of digits in a particular place; (iv) sum of all
numbers \[formed by permutation of the digits\]; (v) the total number of
digits; O friend state these for each set separately if you have labored
on combinatorics.

Let ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") be the number of the objects participating in the permutations
without replacement and
![s](https://s0.wp.com/latex.php?latex=s&bg=ffffff&fg=333333&s=0 "s") be
those objects, in this case digits. Given this, the problem
systematically takes you through several interesting questions:  
(i) The bheda-s, i.e. permutations:
![n\!](https://s0.wp.com/latex.php?latex=n%21&bg=ffffff&fg=333333&s=0
"n!"). For
![s=1..9](https://s0.wp.com/latex.php?latex=s%3D1..9&bg=ffffff&fg=333333&s=0
"s=1..9") it is 362880.

(ii) The aṅka-mukha-s or aṅkāntya-s, i.e. number of permutations that
either begin or those that end in a particular digit: ![(n-1)\!=
\\Gamma(n)](https://s0.wp.com/latex.php?latex=%28n-1%29%21%3D+%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"(n-1)!= \\Gamma(n)"). This is so because we keep one position constant
and allow the remaining to vary freely; thus,
![n-1](https://s0.wp.com/latex.php?latex=n-1&bg=ffffff&fg=333333&s=0
"n-1") positions are available for permutation. For ![s=
1..9](https://s0.wp.com/latex.php?latex=s%3D+1..9&bg=ffffff&fg=333333&s=0
"s= 1..9") it is 40320.

(iii) The ūrdhvāṅka-yoga, i.e. the sum of the numbers in a particular
column. ![\\Gamma(n) \\cdot \\sum
s](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29+%5Ccdot+%5Csum+s&bg=ffffff&fg=333333&s=0
"\\Gamma(n) \\cdot \\sum s"). From the above we saw that the number of
permutations starting with a particular digit is
![\\Gamma(n)](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"\\Gamma(n)"). Thus, for a given column, we will have that many
permutations with each digit. Thus, ![\\sum
s](https://s0.wp.com/latex.php?latex=%5Csum+s&bg=ffffff&fg=333333&s=0
"\\sum s") multiplied with
![\\Gamma(n)](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"\\Gamma(n)") will give us the sum for a given column. For ![s=
1..9](https://s0.wp.com/latex.php?latex=s%3D+1..9&bg=ffffff&fg=333333&s=0
"s= 1..9") it is 1814400

(iv) The sakalāṅka-yoga, i.e. the sum of all the numbers formed by the
digit permutations. ![\\Gamma(n) \\cdot \\sum s \\cdot (\\displaystyle
\\sum\_{k=0}^{n-1}
10^k)](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29+%5Ccdot+%5Csum+s+%5Ccdot+%28%5Cdisplaystyle+%5Csum_%7Bk%3D0%7D%5E%7Bn-1%7D+10%5Ek%29&bg=ffffff&fg=333333&s=0
"\\Gamma(n) \\cdot \\sum s \\cdot (\\displaystyle \\sum_{k=0}^{n-1} 10^k)").
We have the expression for the sum of a column from above. Now, consider
a small example of the given problem with 3 digits. We can rewrite the
numbers formed by the permutations to keep the same total thus:

![\\begin{matrix} 1 \\quad 2 \\quad 3\\\\ 1 \\quad 3 \\quad 2\\\\ 2
\\quad 1 \\quad 3\\\\ 2 \\quad 3 \\quad 1\\\\ 3 \\quad 1 \\quad 2\\\\ 3
\\quad 2 \\quad 1\\\\ \\end{matrix} \\; \\to \\; \\begin{matrix} 1
\\quad 1 \\quad 1\\\\ 1 \\quad 1 \\quad 1\\\\ 2 \\quad 2 \\quad 2\\\\ 2
\\quad 2 \\quad 2\\\\ 3 \\quad 3 \\quad 3\\\\ 3 \\quad 3 \\quad 3\\\\
\\end{matrix}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bmatrix%7D+1+%5Cquad+2+%5Cquad+3%5C%5C+1+%5Cquad+3+%5Cquad+2%5C%5C+2+%5Cquad+1+%5Cquad+3%5C%5C+2+%5Cquad+3+%5Cquad+1%5C%5C+3+%5Cquad+1+%5Cquad+2%5C%5C+3+%5Cquad+2+%5Cquad+1%5C%5C+%5Cend%7Bmatrix%7D+%5C%3B+%5Cto+%5C%3B+%5Cbegin%7Bmatrix%7D+1+%5Cquad+1+%5Cquad+1%5C%5C+1+%5Cquad+1+%5Cquad+1%5C%5C+2+%5Cquad+2+%5Cquad+2%5C%5C+2+%5Cquad+2+%5Cquad+2%5C%5C+3+%5Cquad+3+%5Cquad+3%5C%5C+3+%5Cquad+3+%5Cquad+3%5C%5C+%5Cend%7Bmatrix%7D&bg=ffffff&fg=333333&s=0
"\\begin{matrix} 1 \\quad 2 \\quad 3\\\\ 1 \\quad 3 \\quad 2\\\\ 2 \\quad 1 \\quad 3\\\\ 2 \\quad 3 \\quad 1\\\\ 3 \\quad 1 \\quad 2\\\\ 3 \\quad 2 \\quad 1\\\\ \\end{matrix} \\; \\to \\; \\begin{matrix} 1 \\quad 1 \\quad 1\\\\ 1 \\quad 1 \\quad 1\\\\ 2 \\quad 2 \\quad 2\\\\ 2 \\quad 2 \\quad 2\\\\ 3 \\quad 3 \\quad 3\\\\ 3 \\quad 3 \\quad 3\\\\ \\end{matrix}")

As a result we can express the sum of all numbers formed by the
permutation of the digits to be the sum of a column multiplied by
![\\sum\_{k=0}^{n-1}
10^k](https://s0.wp.com/latex.php?latex=%5Csum_%7Bk%3D0%7D%5E%7Bn-1%7D+10%5Ek&bg=ffffff&fg=333333&s=0
"\\sum_{k=0}^{n-1} 10^k"); 111 for the above example. Thus, for
![s=1..9](https://s0.wp.com/latex.php?latex=s%3D1..9&bg=ffffff&fg=333333&s=0
"s=1..9") we get ![1814400 \\times 111111111=
201599999798400](https://s0.wp.com/latex.php?latex=1814400+%5Ctimes+111111111%3D+201599999798400&bg=ffffff&fg=333333&s=0
"1814400 \\times 111111111= 201599999798400").

(v) Finally, the aṅka-prapāta, i.e. the total number of digits in all
the permutations. ![n^2\\cdot
\\Gamma(n)](https://s0.wp.com/latex.php?latex=n%5E2%5Ccdot+%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"n^2\\cdot \\Gamma(n)"). Since there will be
![n\!](https://s0.wp.com/latex.php?latex=n%21&bg=ffffff&fg=333333&s=0
"n!") permutations and
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
starting digits it is easy to see that the total number of digits across
all permutations will be the above expression. For
![s=1..9](https://s0.wp.com/latex.php?latex=s%3D1..9&bg=ffffff&fg=333333&s=0
"s=1..9") it is 3265920.

One would have noticed that we have used
![\\Gamma(n)](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"\\Gamma(n)") for
![(n-1)\!](https://s0.wp.com/latex.php?latex=%28n-1%29%21&bg=ffffff&fg=333333&s=0
"(n-1)!"). When Gauss studied the continuous form of the factorial
function he merely took it as
![x\!](https://s0.wp.com/latex.php?latex=x%21&bg=ffffff&fg=333333&s=0
"x!"); however, the French mathematician Legendre defined it using
![\\Gamma(n)=(x-1)\!](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29%3D%28x-1%29%21&bg=ffffff&fg=333333&s=0
"\\Gamma(n)=(x-1)!"). We take the Legendre definition of the famous
Gamma function as it naturally emerges in solutions of problems such as
that of Nārāyaṇa. Indeed, this definition also naturally emerges from
the famous integral of Euler for
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") that behaves just like the
![(n-1)\!](https://s0.wp.com/latex.php?latex=%28n-1%29%21&bg=ffffff&fg=333333&s=0
"(n-1)!") function. Being an integral this also gives the continuous
form of the
![\\Gamma(x)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x)") function specifying the value of the function for
non-integer
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x").
Euler’s integral:

![\\Gamma(x) = \\displaystyle \\int\_0^\\infty
t^{x-1}e^{-t}dt](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29+%3D+%5Cdisplaystyle+%5Cint_0%5E%5Cinfty+t%5E%7Bx-1%7De%5E%7B-t%7Ddt&bg=ffffff&fg=333333&s=0
"\\Gamma(x) = \\displaystyle \\int_0^\\infty t^{x-1}e^{-t}dt")

This integral can be handled using the rule for integration by parts:  
![\\int f(x) \\cdot g(x)dx = f(x) \\int g(x) dx - \\int f'(x) (\\int
g(x) dx)
dx](https://s0.wp.com/latex.php?latex=%5Cint+f%28x%29+%5Ccdot+g%28x%29dx+%3D+f%28x%29+%5Cint+g%28x%29+dx+-+%5Cint+f%27%28x%29+%28%5Cint+g%28x%29+dx%29+dx&bg=ffffff&fg=333333&s=0
"\\int f(x) \\cdot g(x)dx = f(x) \\int g(x) dx - \\int f'(x) (\\int g(x) dx) dx")  
Using
![f(x)=t^{x-1}](https://s0.wp.com/latex.php?latex=f%28x%29%3Dt%5E%7Bx-1%7D&bg=ffffff&fg=333333&s=0
"f(x)=t^{x-1}") and
![g(x)=e^{-t}](https://s0.wp.com/latex.php?latex=g%28x%29%3De%5E%7B-t%7D&bg=ffffff&fg=333333&s=0
"g(x)=e^{-t}") we get:

![\\Gamma(x) = t^{x-1} \\int e^{-t}dt - \\int (x-1) t^{x-2} (\\int
e^{-t}dt) dt \\\\\[7pt\] = -t^{x-1} e^{-t} + (x-1)\\int t^{x-2}e^{-t}
dt](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29+%3D+t%5E%7Bx-1%7D+%5Cint+e%5E%7B-t%7Ddt+-+%5Cint+%28x-1%29+t%5E%7Bx-2%7D+%28%5Cint+e%5E%7B-t%7Ddt%29+dt+%5C%5C%5B7pt%5D+%3D+-t%5E%7Bx-1%7D+e%5E%7B-t%7D+%2B+%28x-1%29%5Cint+t%5E%7Bx-2%7De%5E%7B-t%7D+dt&bg=ffffff&fg=333333&s=0
"\\Gamma(x) = t^{x-1} \\int e^{-t}dt - \\int (x-1) t^{x-2} (\\int e^{-t}dt) dt \\\\[7pt] = -t^{x-1} e^{-t} + (x-1)\\int t^{x-2}e^{-t} dt")

Taking the limits we get:

![\\Gamma(x) = \\displaystyle \\left. -t^{x-1} e^{-t}
\\right\\rvert\_{0}^{\\infty} + (x-1) \\int\_{0}^{\\infty} t^{x-2}e^{-t}
dt\\\\\[10pt\] \\therefore \\Gamma(x) =
(x-1)\\Gamma(x-1)](https://s0.wp.com/latex.php?latex=%5CGamma%28x%29+%3D+%5Cdisplaystyle+%5Cleft.+-t%5E%7Bx-1%7D+e%5E%7B-t%7D+%5Cright%5Crvert_%7B0%7D%5E%7B%5Cinfty%7D+%2B+%28x-1%29+%5Cint_%7B0%7D%5E%7B%5Cinfty%7D+t%5E%7Bx-2%7De%5E%7B-t%7D+dt%5C%5C%5B10pt%5D+%5Ctherefore+%5CGamma%28x%29+%3D+%28x-1%29%5CGamma%28x-1%29&bg=ffffff&fg=333333&s=0
"\\Gamma(x) = \\displaystyle \\left. -t^{x-1} e^{-t} \\right\\rvert_{0}^{\\infty} + (x-1) \\int_{0}^{\\infty} t^{x-2}e^{-t} dt\\\\[10pt] \\therefore \\Gamma(x) = (x-1)\\Gamma(x-1)")

By putting
![x=n](https://s0.wp.com/latex.php?latex=x%3Dn&bg=ffffff&fg=333333&s=0
"x=n") and doing the above repeatedly we get
![\\Gamma(n)=(n-1)(n-2)...](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29%3D%28n-1%29%28n-2%29...&bg=ffffff&fg=333333&s=0
"\\Gamma(n)=(n-1)(n-2)...") until we reach 1 at which point the integral
becomes:

![\\Gamma(n)=\\displaystyle (n-1)(n-2)..2 \\cdot 1 \\int\_{0}^{\\infty}
t^0 e^{-t} dt
=(n-1)\!](https://s0.wp.com/latex.php?latex=%5CGamma%28n%29%3D%5Cdisplaystyle+%28n-1%29%28n-2%29..2+%5Ccdot+1+%5Cint_%7B0%7D%5E%7B%5Cinfty%7D+t%5E0+e%5E%7B-t%7D+dt+%3D%28n-1%29%21&bg=ffffff&fg=333333&s=0
"\\Gamma(n)=\\displaystyle (n-1)(n-2)..2 \\cdot 1 \\int_{0}^{\\infty} t^0 e^{-t} dt =(n-1)!")

In the final part of this note we shall consider the integer sequence
defined by the aṅka-prapāta: ![n^2\\cdot
\\Gamma(n)](https://s0.wp.com/latex.php?latex=n%5E2%5Ccdot+%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"n^2\\cdot \\Gamma(n)"). Now let us do this for the sets of ![n=1, 2, 3,
4...](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3%2C+4...&bg=ffffff&fg=333333&s=0
"n=1, 2, 3, 4...") permutable symbols. We get the integer sequence
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"):  
**1, 4, 18, 96, 600, 4320, 35280, 322560, 3265920…**

This sequence has a notable property. It defines the number of integers
from
![1..k\!](https://s0.wp.com/latex.php?latex=1..k%21&bg=ffffff&fg=333333&s=0
"1..k!") that are not divisible by
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
for ![k=2, 3,
4...](https://s0.wp.com/latex.php?latex=k%3D2%2C+3%2C+4...&bg=ffffff&fg=333333&s=0
"k=2, 3, 4..."). Why this is so is easy to apprehend: Since we start
from 2, we have
![k=n+1](https://s0.wp.com/latex.php?latex=k%3Dn%2B1&bg=ffffff&fg=333333&s=0
"k=n+1"). Now the numbers that will be divisible by
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
between
![1..k\!](https://s0.wp.com/latex.php?latex=1..k%21&bg=ffffff&fg=333333&s=0
"1..k!") will amount to
![\\tfrac{k\!}{k}=(k-1)\!=n\!](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bk%21%7D%7Bk%7D%3D%28k-1%29%21%3Dn%21&bg=ffffff&fg=333333&s=0
"\\tfrac{k!}{k}=(k-1)!=n!"). Therefore, the numbers that will not be
divisible by
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
will amount to ![(n+1)\!-n\!=n\!(n+1)-n\!=n (n-1)\! (n+1-1)=n^2
\\Gamma(n)](https://s0.wp.com/latex.php?latex=%28n%2B1%29%21-n%21%3Dn%21%28n%2B1%29-n%21%3Dn+%28n-1%29%21+%28n%2B1-1%29%3Dn%5E2+%5CGamma%28n%29&bg=ffffff&fg=333333&s=0
"(n+1)!-n!=n!(n+1)-n!=n (n-1)! (n+1-1)=n^2 \\Gamma(n)").

If we take the sum of the reciprocals of this sequence we see that it
converges to a constant:

![\\displaystyle \\sum\_{n=1}^{\\infty} \\dfrac{1}{n^2 \\Gamma(n)} =
1.3179021514544...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%7D%7Bn%5E2+%5CGamma%28n%29%7D+%3D+1.3179021514544...&bg=ffffff&fg=333333&s=0
"\\displaystyle \\sum_{n=1}^{\\infty} \\dfrac{1}{n^2 \\Gamma(n)} = 1.3179021514544...")

Now, what is this number? We discovered that this number emerges from
the solution of an interesting definite integral:

![\\displaystyle \\int\_0^1 \\dfrac{e^x-1}{x} dx=
1.3179021514544...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cint_0%5E1+%5Cdfrac%7Be%5Ex-1%7D%7Bx%7D+dx%3D+1.3179021514544...&bg=ffffff&fg=333333&s=0
"\\displaystyle \\int_0^1 \\dfrac{e^x-1}{x} dx= 1.3179021514544...")

The integral can be split up as:

![\\displaystyle \\int \\dfrac{e^x}{x} dx - \\int \\dfrac{1}{x} dx=
\\int \\dfrac{e^x}{x} dx
-\\log(x)+C](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cint+%5Cdfrac%7Be%5Ex%7D%7Bx%7D+dx+-+%5Cint+%5Cdfrac%7B1%7D%7Bx%7D+dx%3D+%5Cint+%5Cdfrac%7Be%5Ex%7D%7Bx%7D+dx+-%5Clog%28x%29%2BC&bg=ffffff&fg=333333&s=0
"\\displaystyle \\int \\dfrac{e^x}{x} dx - \\int \\dfrac{1}{x} dx= \\int \\dfrac{e^x}{x} dx -\\log(x)+C")

[![Eix\_etc](https://manasataramgini.files.wordpress.com/2019/09/eix_etc.png?w=640)](https://manasataramgini.files.wordpress.com/2019/09/eix_etc.png)Figure
5

It is immediately apparent that the first integral ![\\int
\\dfrac{e^x}{x}
dx](https://s0.wp.com/latex.php?latex=%5Cint+%5Cdfrac%7Be%5Ex%7D%7Bx%7D+dx&bg=ffffff&fg=333333&s=0
"\\int \\dfrac{e^x}{x} dx") is a tricky one: the function ![y=
\\dfrac{e^x}{x}](https://s0.wp.com/latex.php?latex=y%3D+%5Cdfrac%7Be%5Ex%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"y= \\dfrac{e^x}{x}") diverges to
![\\infty](https://s0.wp.com/latex.php?latex=%5Cinfty&bg=ffffff&fg=333333&s=0
"\\infty") as ![x^+ \\to
0](https://s0.wp.com/latex.php?latex=x%5E%2B+%5Cto+0&bg=ffffff&fg=333333&s=0
"x^+ \\to 0") (from positive side) and to
![-\\infty](https://s0.wp.com/latex.php?latex=-%5Cinfty&bg=ffffff&fg=333333&s=0
"-\\infty") as ![x^- \\to
0](https://s0.wp.com/latex.php?latex=x%5E-+%5Cto+0&bg=ffffff&fg=333333&s=0
"x^- \\to 0") (from negative side). Remarkably, these opposite
divergences cancel each other and the integral converges to a fixed
value. Thus we can evaluate it to a given
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
as:

![\\textrm{Ei}(x) = \\displaystyle \\int\_{-\\infty}^x \\dfrac{e^t}{t}
dt](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29+%3D+%5Cdisplaystyle+%5Cint_%7B-%5Cinfty%7D%5Ex+%5Cdfrac%7Be%5Et%7D%7Bt%7D+dt&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x) = \\displaystyle \\int_{-\\infty}^x \\dfrac{e^t}{t} dt")

This function
![\\textrm{Ei}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)") is the exponential integral with deep connections
with permutations. The two divergences of ![y=
\\dfrac{e^x}{x}](https://s0.wp.com/latex.php?latex=y%3D+%5Cdfrac%7Be%5Ex%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"y= \\dfrac{e^x}{x}") exactly cancel each other when
![x=\\log(\\mu)=0.37250741...](https://s0.wp.com/latex.php?latex=x%3D%5Clog%28%5Cmu%29%3D0.37250741...&bg=ffffff&fg=333333&s=0
"x=\\log(\\mu)=0.37250741..."), i.e.
![\\textrm{Ei}(x)=0](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29%3D0&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)=0"). This
![\\mu=1.451369234](https://s0.wp.com/latex.php?latex=%5Cmu%3D1.451369234&bg=ffffff&fg=333333&s=0
"\\mu=1.451369234") is the Soldner-Ramanujan constant that was first
discovered by Johann von Soldner and independently by Ramanujan who
arrived at it when he discovered multiple series for the logarithmic
integral ![\\textrm{Li}(x)=\\int\_0^x
\\tfrac{dx}{\\log(x)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3D%5Cint_0%5Ex+%5Ctfrac%7Bdx%7D%7B%5Clog%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)=\\int_0^x \\tfrac{dx}{\\log(x)}") (Figure 5), which
Gauss had shown to provide the asymptotic description of the
distribution of prime numbers. The famed ![\\textrm{Li}(x) =
\\textrm{Ei}(\\log(x))](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29+%3D+%5Ctextrm%7BEi%7D%28%5Clog%28x%29%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x) = \\textrm{Ei}(\\log(x))"). Returning, to our original
integral we can thus write its indefinite solution as:

![\\displaystyle \\int \\dfrac{e^x-1}{x} dx= \\textrm{Ei}(x) -\\log(x)
+C](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cint+%5Cdfrac%7Be%5Ex-1%7D%7Bx%7D+dx%3D+%5Ctextrm%7BEi%7D%28x%29+-%5Clog%28x%29+%2BC&bg=ffffff&fg=333333&s=0
"\\displaystyle \\int \\dfrac{e^x-1}{x} dx= \\textrm{Ei}(x) -\\log(x) +C")

Now we observe that as ![x^+ \\to 0,\\; \\textrm{Ei}(x) \\to \\infty,\\;
\\log(x) \\to
-\\infty](https://s0.wp.com/latex.php?latex=x%5E%2B+%5Cto+0%2C%5C%3B+%5Ctextrm%7BEi%7D%28x%29+%5Cto+%5Cinfty%2C%5C%3B+%5Clog%28x%29+%5Cto+-%5Cinfty&bg=ffffff&fg=333333&s=0
"x^+ \\to 0,\\; \\textrm{Ei}(x) \\to \\infty,\\; \\log(x) \\to -\\infty")
(we only consider the approach to 0 from positive side for only there
the real
![\\log(x)](https://s0.wp.com/latex.php?latex=%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"\\log(x)") is defined). The two remarkably balance each other such that
as ![x^+ \\to
0](https://s0.wp.com/latex.php?latex=x%5E%2B+%5Cto+0&bg=ffffff&fg=333333&s=0
"x^+ \\to 0") the above integral converges to
![\\gamma=0.577215664...](https://s0.wp.com/latex.php?latex=%5Cgamma%3D0.577215664...&bg=ffffff&fg=333333&s=0
"\\gamma=0.577215664..."), which is the famous Euler-Mascheroni constant
with a deep connection to the Gamma function (See below). Thus, the
definite integral (Figure 5):

![\\displaystyle \\int\_0^1 \\dfrac{e^x-1}{x} dx=
\\textrm{Ei}(1)-\\gamma=1.3179021514544...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Cint_0%5E1+%5Cdfrac%7Be%5Ex-1%7D%7Bx%7D+dx%3D+%5Ctextrm%7BEi%7D%281%29-%5Cgamma%3D1.3179021514544...&bg=ffffff&fg=333333&s=0
"\\displaystyle \\int_0^1 \\dfrac{e^x-1}{x} dx= \\textrm{Ei}(1)-\\gamma=1.3179021514544...")

This leads us to the formula:

![\\textrm{Ei}(1)=\\displaystyle \\gamma + \\sum\_{n=1}^{\\infty}
\\dfrac{1}{n^2\\Gamma(n)} =
1.89511781635...](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%281%29%3D%5Cdisplaystyle+%5Cgamma+%2B+%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%7D%7Bn%5E2%5CGamma%28n%29%7D+%3D+1.89511781635...&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(1)=\\displaystyle \\gamma + \\sum_{n=1}^{\\infty} \\dfrac{1}{n^2\\Gamma(n)} = 1.89511781635...")

From this and the above indefinite integral we can obtain the general
formula for
![\\textrm{Ei}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)") as:

![\\textrm{Ei}(x)=\\displaystyle \\gamma +\\log(x) +
\\sum\_{n=1}^{\\infty}
\\dfrac{x^n}{n^2\\Gamma(n)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29%3D%5Cdisplaystyle+%5Cgamma+%2B%5Clog%28x%29+%2B+%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7Bx%5En%7D%7Bn%5E2%5CGamma%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)=\\displaystyle \\gamma +\\log(x) + \\sum_{n=1}^{\\infty} \\dfrac{x^n}{n^2\\Gamma(n)}")

If we now substitute
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x") by
![\\log(x)](https://s0.wp.com/latex.php?latex=%5Clog%28x%29&bg=ffffff&fg=333333&s=0
"\\log(x)") we get the series for the logarithmic integral as:

![\\textrm{Li}(x)=\\displaystyle \\gamma +\\log(\\log(x)) +
\\sum\_{n=1}^{\\infty}
\\dfrac{\\log^n(x)}{n^2\\Gamma(n)}](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29%3D%5Cdisplaystyle+%5Cgamma+%2B%5Clog%28%5Clog%28x%29%29+%2B+%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B%5Clog%5En%28x%29%7D%7Bn%5E2%5CGamma%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)=\\displaystyle \\gamma +\\log(\\log(x)) + \\sum_{n=1}^{\\infty} \\dfrac{\\log^n(x)}{n^2\\Gamma(n)}")

This was the series for
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") that Ramanujan arrived at unaware of work of Gauss,
Soldner and their successors in Europe. He then went on to discover
other series that converged even faster to
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). With these relationships one can finally obtain a
relationship between the mysterious Euler-Mascheroni constant
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") that appears in various formulae pertaining to both the
number world and the natural world and the Soldner-Ramanujan constant
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0
"\\mu") of number theory. Since
![\\textrm{Ei}(x)=0](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29%3D0&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)=0") when
![x=\\log(\\mu)](https://s0.wp.com/latex.php?latex=x%3D%5Clog%28%5Cmu%29&bg=ffffff&fg=333333&s=0
"x=\\log(\\mu)") by substituting this into the above series for
![\\textrm{Ei}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BEi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Ei}(x)") we get:

![\\gamma = -\\Gamma'(1) =\\displaystyle \\lim\_{n \\to \\infty}\\left(
\\sum\_{k=1}^{n}\\dfrac{1}{k} -\\log(n) \\right) = -\\log(\\log(\\mu)) -
\\sum\_{n=1}^{\\infty}
\\dfrac{\\log^n(\\mu)}{n^2\\Gamma(n)}](https://s0.wp.com/latex.php?latex=%5Cgamma+%3D+-%5CGamma%27%281%29+%3D%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D%5Cleft%28+%5Csum_%7Bk%3D1%7D%5E%7Bn%7D%5Cdfrac%7B1%7D%7Bk%7D+-%5Clog%28n%29+%5Cright%29+%3D+-%5Clog%28%5Clog%28%5Cmu%29%29+-+%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B%5Clog%5En%28%5Cmu%29%7D%7Bn%5E2%5CGamma%28n%29%7D&bg=ffffff&fg=333333&s=0
"\\gamma = -\\Gamma'(1) =\\displaystyle \\lim_{n \\to \\infty}\\left( \\sum_{k=1}^{n}\\dfrac{1}{k} -\\log(n) \\right) = -\\log(\\log(\\mu)) - \\sum_{n=1}^{\\infty} \\dfrac{\\log^n(\\mu)}{n^2\\Gamma(n)}")

The first expression
![\\Gamma'(x)](https://s0.wp.com/latex.php?latex=%5CGamma%27%28x%29&bg=ffffff&fg=333333&s=0
"\\Gamma'(x)") is the derivative of the Gamma function. The second
expression is Euler’s original definition of
![\\gamma](https://s0.wp.com/latex.php?latex=%5Cgamma&bg=ffffff&fg=333333&s=0
"\\gamma") as a limit. The third is what we obtain from the above
substitution, which gives it in relationship to
![\\mu](https://s0.wp.com/latex.php?latex=%5Cmu&bg=ffffff&fg=333333&s=0
"\\mu") as derived from Ramanujan’s series.

Thus, in the works of the last great mathematicians of the Hindu
tradition like Bhāskara-II, Nārāyaṇa and Mādhava we see the preamble to
the developments of modern mathematics, which revealed the deep links
between the number world and the natural world. Nārāyaṇa’s interest in
combinatorics, sequences and sums may be compared with that of Euler.
Armed with a photographic memory and an enormous capacity for numerical
calculations, Euler was much like a paṇḍita of yore. Indeed, he dealt
with infinite sums and definite integrals almost like a continuation of
that old tradition. But among the Hindus it was Ramanujan, who close to
600 years after Nārāyaṇa and Mādhava nearly seemed as if he was
channeling them to single-handedly take their tradition to a conclusion.
