+++
title = "Fermat’s little theorem and the periods of the reciprocals of primes"

+++
**From the genetic code to the proof of Fermat’s little theorem**  
Nucleic acids encode the 20 amino acids found in the sequence of a
protein using just 4 bases: A, G, T, C in DNA. Thus, the 4-symbol
nucleic acid alphabet encodes a 20-symbol protein alphabet. This is
achieved by having 3 letters in the nucleic acid language (a codon) code
for one letter in the protein language or for the stop sign to terminate
the protein sequence. This is the famed genetic code. When we first
learned of it at age 10, we became fascinated with the process of
encoding and while playing around with codons, we learned not just the
foundations of biology but also some of the basics of combinatorics.
That was perhaps the reason why some years later in college we were
quite agile with elementary combinatorics despite not having any special
mathematical spark.

The first and the most obvious thing we observed was that the total
number of codons in the genetic code was the total number permutations
with replacements that could achieved in 3-letter words using a 4-symbol
alphabet: ![4\\times 4\\times 4 =
64](https://s0.wp.com/latex.php?latex=4%5Ctimes+4%5Ctimes+4+%3D+64&bg=ffffff&fg=333333&s=0
"4\\times 4\\times 4 = 64"). A closer look then revealed that these
3-letter words, i.e. codons, could be classified into groups by
arranging them as ring graphs (Figure 1). Since nucleic acids have a
polarity imparted by the (deoxy) ribose ring of the sugar, i.e.
![5'\\rightarrow
3'](https://s0.wp.com/latex.php?latex=5%27%5Crightarrow+3%27&bg=ffffff&fg=333333&s=0
"5'\\rightarrow 3'"), each of these ring graphs are directed: they take
the form of an uroboros. Thus, we get into 24 distinct groups

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig1_fermat_little.png?w=520&h=477)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig1_fermat_little.png)

Figure 1

Of these, 4 rings are homopolymeric, i.e. AAA, GGG, TTT and CCC. Any
circular permutation of them will yield the same codon again. Each of
the remaining 20 rings is heteropolymeric. Hence, when circularly
permuted, each will always yield 3 different codons. For example, the
first ring in the second row (Figure 1) will yield AGA, GAA and AAG.
Thus, we get the total number of permutations possible in the 3-letter
words with a 4-symbol alphabet as: ![20 \\times 3 +4
=64](https://s0.wp.com/latex.php?latex=20+%5Ctimes+3+%2B4+%3D64&bg=ffffff&fg=333333&s=0
"20 \\times 3 +4 =64"). This reveals a more important truth of
combinatorics: If you have any word of prime number length then by
definition, other than for homotypic words (equivalent to a
homopolymeric codon), it will always have same prime number of circular
permutations when the letters are arranged on a directed ring graph as
in Figure 1. 3 is the prime number in the case of the genetic code;
hence; the circular permutations of the heteropolymeric rings yield 3
codons each. We can express this as a generalization thus: Let
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") be
the number of symbols in the alphabet. Let
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") be
a prime which is the length of the word in that alphabet. We also insist
that ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") is not divisible by
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p").
Then the total number of
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0
"p")-letter words will be
![n=a^p](https://s0.wp.com/latex.php?latex=n%3Da%5Ep&bg=ffffff&fg=333333&s=0
"n=a^p"). Of these the homotypic words will amount to
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
Thus, the remainder will be
![a^p-a](https://s0.wp.com/latex.php?latex=a%5Ep-a&bg=ffffff&fg=333333&s=0
"a^p-a") words. Now, these remaining words, by the above principle of
arranging on directed ring graphs, can be grouped into
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
sets each of
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
words. Thus, ![a^p-a=
kp](https://s0.wp.com/latex.php?latex=a%5Ep-a%3D+kp&bg=ffffff&fg=333333&s=0
"a^p-a= kp"); therefore it will be divisible by
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p").
Alternatively,

![(a^p-a) \\mod p =0; \\; \\therefore (a^{p-1}-1) \\mod p=0; \\;
\\therefore a^{p-1} \\mod p
=1](https://s0.wp.com/latex.php?latex=%28a%5Ep-a%29+%5Cmod+p+%3D0%3B+%5C%3B+%5Ctherefore+%28a%5E%7Bp-1%7D-1%29+%5Cmod+p%3D0%3B+%5C%3B+%5Ctherefore+a%5E%7Bp-1%7D+%5Cmod+p+%3D1&bg=ffffff&fg=333333&s=0
"(a^p-a) \\mod p =0; \\; \\therefore (a^{p-1}-1) \\mod p=0; \\; \\therefore a^{p-1} \\mod p =1")

This is the famous Fermat’s little theorem of arithmetic. Fermat had
proposed it without a proof but it was subsequently proven by Liebniz.
Euler published a proof more than 50 years later, apparently unaware of
Liebniz’s manuscript which is believed to have not been formally
published. He then provided its general form, the theorem of Euler
regarding the totient function
![\\varphi(n)](https://s0.wp.com/latex.php?latex=%5Cvarphi%28n%29&bg=ffffff&fg=333333&s=0
"\\varphi(n)"), which we had encountered in the [previous
note](https://manasataramgini.wordpress.com/2018/10/05/a-laymans-overview-of-the-arithmetic-of-encryption/).
The above proof which we presented is the proof by combinatorics. It was
apparently first published by the mathematician Golomb and is a variant
of Euler’s original proof.

**The periods of the reciprocals of prime numbers**  
Early tetrapods showed a wide range of finger-counts in their limbs:
*Acanthostega* had an 8-fingered limb; *Ichthyostega* showed a
7-fingered hind-limb; *Tulerpeton* had 6 fingers. Some time thereafter,
perhaps in a form like *Crassigyrinus*, the number 5 got fixed. While
there are frequent deviations from this in particular lineages, like
amphibians losing a finger in the forelimb, the 5-fingered state
continued to be the common baseline in most surviving tetrapod clades.
Thus, we got our 5-fingered hands. This combined with our bilateral
symmetry gave us a number system based on the product of 2 primes:
![10=2 \\times
5](https://s0.wp.com/latex.php?latex=10%3D2+%5Ctimes+5&bg=ffffff&fg=333333&s=0
"10=2 \\times 5"); i.e., the decimal system. While some islanders of
Papua have apparently opted for the smaller senary system based on
![6=2\\times3](https://s0.wp.com/latex.php?latex=6%3D2%5Ctimes3&bg=ffffff&fg=333333&s=0
"6=2\\times3"), the former system came to be the dominant usage of the
world.

The peculiarities of the decimal system caught our fancy when our father
began teaching us decimal fractions as a kid. We were fascinated by the
observation that some decimal fractions terminated:
![\\tfrac{1}{8}=0.125](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B8%7D%3D0.125&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{8}=0.125"), whereas others just fell into a cycle:
![\\tfrac{1}{11}=0.090909...](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B11%7D%3D0.090909...&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{11}=0.090909..."). We asked our father why this was so? He
told us to focus on: 1) reciprocals, i.e. fractions of the type
![\\tfrac{1}{a}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Ba%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{a}") because all other fractions are integer multiples of
such and 2) to look out for primes. Then thinking it would be good for
us to get some practice with division, he let us keep to dividing 1 by
various numbers.

If one were to do this arithmetic operation, sooner or later, one
realizes the following:  
1\) Only fractions of the form ![\\tfrac{1}{2^m
5^n}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B2%5Em+5%5En%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{2^m 5^n}") or their multiple terminate. The number of
decimal places after which they terminate is
![\\max(m,n)](https://s0.wp.com/latex.php?latex=%5Cmax%28m%2Cn%29&bg=ffffff&fg=333333&s=0
"\\max(m,n)"). This is easily understood. One needs to divide as many
units as the maximum number of times 2 or 5 appear in the denominator;
hence, the decimal fraction terminates after that many digits after the
point.

2\) If the fraction is of the form ![\\tfrac{1}{2^m 5^n p\_1^a
p\_2^b...}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B2%5Em+5%5En+p_1%5Ea+p_2%5Eb...%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{2^m 5^n p_1^a p_2^b...}"), where ![p\_1,
p\_2...](https://s0.wp.com/latex.php?latex=p_1%2C+p_2...&bg=ffffff&fg=333333&s=0
"p_1, p_2...") are the primes other than 2 and 5 then it always cycles
after an initial run of numbers whose length again depends of the ![2^m
5^n](https://s0.wp.com/latex.php?latex=2%5Em+5%5En&bg=ffffff&fg=333333&s=0
"2^m 5^n") part of the denominator as in the first case.

3\) To better understand the cycles let us restrict ourselves to the
basic situation where the fraction is of the form
![\\tfrac{1}{p}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Bp%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{p}"), where
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") is
any prime other than 2 or 5. Such fractions are always pure cycles in
the decimal form. We define cycle-length
![l](https://s0.wp.com/latex.php?latex=l&bg=ffffff&fg=333333&s=0 "l") as
the length of the repeating pattern of digits. Since,
![\\tfrac{1}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{2}") and
![\\tfrac{1}{5}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B5%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{5}") terminate we can take their
![l=0](https://s0.wp.com/latex.php?latex=l%3D0&bg=ffffff&fg=333333&s=0
"l=0"). For other primes we see
![l](https://s0.wp.com/latex.php?latex=l&bg=ffffff&fg=333333&s=0 "l")
take various values as below:

![\\dfrac{1}{3}=0.\\overline{3};
l=1](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B3%7D%3D0.%5Coverline%7B3%7D%3B+l%3D1&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{3}=0.\\overline{3}; l=1")

![\\dfrac{1}{7}= 0.\\overline{142857};
l=6](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B7%7D%3D+0.%5Coverline%7B142857%7D%3B+l%3D6&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{7}= 0.\\overline{142857}; l=6")

![\\dfrac{1}{11}=0.\\overline{09};
l=2](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B11%7D%3D0.%5Coverline%7B09%7D%3B+l%3D2&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{11}=0.\\overline{09}; l=2")

![\\dfrac{1}{13}=0.\\overline{076923};
l=6](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B13%7D%3D0.%5Coverline%7B076923%7D%3B+l%3D6&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{13}=0.\\overline{076923}; l=6")

![\\dfrac{1}{17}=0.\\overline{ 0588235294117647};
l=16](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B17%7D%3D0.%5Coverline%7B+0588235294117647%7D%3B+l%3D16&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{17}=0.\\overline{ 0588235294117647}; l=16")

![\\dfrac{1}{19}=0.\\overline{ 052631578947368421};
l=18](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7B19%7D%3D0.%5Coverline%7B+052631578947368421%7D%3B+l%3D18&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{19}=0.\\overline{ 052631578947368421}; l=18")

What determines the length of the cycle for a given prime? We observe
that the cycle is determined by when a multiple of the denominator
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
becomes 1 less than a power of 10 for the first time. Thus we have:
![3\\times 3=
9](https://s0.wp.com/latex.php?latex=3%5Ctimes+3%3D+9&bg=ffffff&fg=333333&s=0
"3\\times 3= 9"). Hence, the cycle for
![\\tfrac{1}{3}=0.\\overline{3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B3%7D%3D0.%5Coverline%7B3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{3}=0.\\overline{3}"). Similarly, ![7\\times 142857=
999999](https://s0.wp.com/latex.php?latex=7%5Ctimes+142857%3D+999999&bg=ffffff&fg=333333&s=0
"7\\times 142857= 999999"). Hence, the cycle for
![\\tfrac{1}{7}=0.\\overline{142857}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B7%7D%3D0.%5Coverline%7B142857%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{7}=0.\\overline{142857}"). Another example: ![11\\times 09=
99](https://s0.wp.com/latex.php?latex=11%5Ctimes+09%3D+99&bg=ffffff&fg=333333&s=0
"11\\times 09= 99"). Hence, the cycle for
![\\tfrac{1}{11}=0.\\overline{09}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B11%7D%3D0.%5Coverline%7B09%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{11}=0.\\overline{09}"). This can be formally expressed thus:
When ![10^n \\mod p =
1](https://s0.wp.com/latex.php?latex=10%5En+%5Cmod+p+%3D+1&bg=ffffff&fg=333333&s=0
"10^n \\mod p = 1") then the length of the decimal cycle of
![\\tfrac{1}{p}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Bp%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{p}") is
![l=n](https://s0.wp.com/latex.php?latex=l%3Dn&bg=ffffff&fg=333333&s=0
"l=n"). The pattern of repetition is then given by
![\\tfrac{10^n-1}{p}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B10%5En-1%7D%7Bp%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{10^n-1}{p}") with the appropriate padding 0s.

With this in place, one can now show that for a given prime
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p"),
the maximum length of a cycle can be
![p-1](https://s0.wp.com/latex.php?latex=p-1&bg=ffffff&fg=333333&s=0
"p-1"). By Fermat’s little theorem (see above), ![10^{p-1} \\mod p
=1](https://s0.wp.com/latex.php?latex=10%5E%7Bp-1%7D+%5Cmod+p+%3D1&bg=ffffff&fg=333333&s=0
"10^{p-1} \\mod p =1"). Thus, we will reach a number 1 less than a power
of 10, which is also divisible by
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p"),
latest by
![10^{p-1}-1](https://s0.wp.com/latex.php?latex=10%5E%7Bp-1%7D-1&bg=ffffff&fg=333333&s=0
"10^{p-1}-1"); therefore, in these cases
![l=p-1](https://s0.wp.com/latex.php?latex=l%3Dp-1&bg=ffffff&fg=333333&s=0
"l=p-1"). In the above examples we see this for 7, 17 and 19. An
examination of the distribution of the digits from
![0..9](https://s0.wp.com/latex.php?latex=0..9&bg=ffffff&fg=333333&s=0
"0..9") for fractions with long cycles shows that they are all present
in equal frequency.

This now leads us to an interesting sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
such that
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") is defined as the length of the decimal cycle of the reciprocal
of the
![n^{th}](https://s0.wp.com/latex.php?latex=n%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"n^{th}") prime, i.e.
![l(\\tfrac{1}{p\_n})](https://s0.wp.com/latex.php?latex=l%28%5Ctfrac%7B1%7D%7Bp_n%7D%29&bg=ffffff&fg=333333&s=0
"l(\\tfrac{1}{p_n})"). The Englishman W. Shanks was the first to compute
this sequence in the pre-computer era for every
![p\<20000](https://s0.wp.com/latex.php?latex=p%3C20000&bg=ffffff&fg=333333&s=0
"p\<20000"), i.e., the first 2262 primes and triumphantly presented his
results before the Royal Society of England. Unlike Shanks, in our first
attempt at this in our childhood we quickly ran out of steam but we had
at least obtained some basic picture of the “lay of the land” of the
sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f").
Hence, we wondered how Shanks reached his goal: was it by brute force or
by some trick which the late Śaṃkarācarya of the Govardhana-maṭha used.
In any case, as time passed my father had grown richer and procured a
computer for me. As a result, I revisited this problem and could now
reach where old Shanks had gone.
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
runs thus:  
0, 1, 0, 6, 2, 6, 16, 18, 22, 28, 15, 3, 5, 21, 46, 13, 58, 60, 33,
35…  
One notices that sometimes
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") is even and other times odd. If it is even the corresponding
![\\tfrac{1}{p\_n}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7Bp_n%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{p_n}") has a curious property, which we illustrate with few
examples:

![f\[4\]=6 \\equiv \\dfrac{1}{7} \\equiv 0.142 |
857](https://s0.wp.com/latex.php?latex=f%5B4%5D%3D6+%5Cequiv+%5Cdfrac%7B1%7D%7B7%7D+%5Cequiv+0.142+%7C+857&bg=ffffff&fg=333333&s=0
"f[4]=6 \\equiv \\dfrac{1}{7} \\equiv 0.142 | 857")

![f\[7\]=16 \\equiv \\dfrac{1}{17} \\equiv 0.05882352 |
94117647](https://s0.wp.com/latex.php?latex=f%5B7%5D%3D16+%5Cequiv+%5Cdfrac%7B1%7D%7B17%7D+%5Cequiv+0.05882352+%7C+94117647&bg=ffffff&fg=333333&s=0
"f[7]=16 \\equiv \\dfrac{1}{17} \\equiv 0.05882352 | 94117647")

Thus, we see that for fractions with an even cycle the sum of each of
the digits in the first
![\\tfrac{l}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bl%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{l}{2}") digits with the corresponding digit in the final
![\\tfrac{l}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bl%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{l}{2}") digits is 9; e.g. in the case of ![p\_n=7:
1+8=4+5=2+7=9](https://s0.wp.com/latex.php?latex=p_n%3D7%3A+1%2B8%3D4%2B5%3D2%2B7%3D9&bg=ffffff&fg=333333&s=0
"p_n=7: 1+8=4+5=2+7=9"). Likewise, for ![p\_n=17:
0+9=5+4=8+1=8+1=2+7=3+6=5+5=2+7=9](https://s0.wp.com/latex.php?latex=p_n%3D17%3A+0%2B9%3D5%2B4%3D8%2B1%3D8%2B1%3D2%2B7%3D3%2B6%3D5%2B5%3D2%2B7%3D9&bg=ffffff&fg=333333&s=0
"p_n=17: 0+9=5+4=8+1=8+1=2+7=3+6=5+5=2+7=9"). This knowledge halves the
calculation as long as you know you have reached the midpoint of the
cycle. But this leads to the question: what is the distribution of cycle
lengths? A good way to approach this question is by plotting
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") against the corresponding
![p\_n](https://s0.wp.com/latex.php?latex=p_n&bg=ffffff&fg=333333&s=0
"p_n"). This is shown in Figure 2.

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig2_plot_vs_p.png?w=640&h=401)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig2_plot_vs_p.png)Figure
2.
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") are plotted as both points and heights against
![p\_n](https://s0.wp.com/latex.php?latex=p_n&bg=ffffff&fg=333333&s=0
"p_n") for the first 1229 primes. Every 5 successive
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") are plotted as heights of a different color.

We observe that in this plot the terms of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") fall on lines of the form
![y=\\tfrac{x-1}{k}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx-1%7D%7Bk%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x-1}{k}"), where ![k=1, 2, 3,
4...](https://s0.wp.com/latex.php?latex=k%3D1%2C+2%2C+3%2C+4...&bg=ffffff&fg=333333&s=0
"k=1, 2, 3, 4..."). Those where the cycle length is of the form
![l=p\_n-1](https://s0.wp.com/latex.php?latex=l%3Dp_n-1&bg=ffffff&fg=333333&s=0
"l=p_n-1") will fall on
![y=x-1](https://s0.wp.com/latex.php?latex=y%3Dx-1&bg=ffffff&fg=333333&s=0
"y=x-1"). Those for which
![l=\\tfrac{p\_n-1}{2}](https://s0.wp.com/latex.php?latex=l%3D%5Ctfrac%7Bp_n-1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"l=\\tfrac{p_n-1}{2}"), e.g.
![p\_n=13](https://s0.wp.com/latex.php?latex=p_n%3D13&bg=ffffff&fg=333333&s=0
"p_n=13"), will fall on
![y=\\tfrac{x-1}{2}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx-1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x-1}{2}") and so on. Since all primes other than 2 are odd,
![p\_n-1](https://s0.wp.com/latex.php?latex=p_n-1&bg=ffffff&fg=333333&s=0
"p_n-1") will be even. Thus,
![\\tfrac{p\_n-1}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bp_n-1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{p_n-1}{2}") might be even or odd. Further,
![\\tfrac{p\_n-1}{3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bp_n-1%7D%7B3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{p_n-1}{3}") will be even. Thus, given that only when
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") is
even we can get odd-length cycles, the number of primes with odd-length
cycles will be less than the number of primes with even-length cycles.
The ratio of the number of odd-length cycles to even-length cycles for
the first 2262 primes it is 0.487. While it close to
![\\tfrac{1}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{2}"), it is not clear if it converges to a particular value.

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig3_odd_even_cycle.png?w=640&h=401)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig3_odd_even_cycle.png)Figure
3. Primes with even-length cycles are colored blue and those with
odd-length cycles are colored red. The first 2262 primes are arranged
from left to right 58 per row in 39 rows.

In Figure 3 we depict the first 2262 primes colored according to whether
they have an even- or odd-length cycle. There is no obviously
discernible pattern. Yet, there could be a subtle one which we are
unable to describe: whether such a pattern exists remains an open
question to us.

The
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") and the corresponding
![p\_n](https://s0.wp.com/latex.php?latex=p_n&bg=ffffff&fg=333333&s=0
"p_n") can be classified into different families depending on which line
of the form
![y=\\tfrac{x-1}{k}](https://s0.wp.com/latex.php?latex=y%3D%5Ctfrac%7Bx-1%7D%7Bk%7D&bg=ffffff&fg=333333&s=0
"y=\\tfrac{x-1}{k}") they fall on (Figure 2). Thus, for
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1"), we have the cycle 1 family; for
![k=2](https://s0.wp.com/latex.php?latex=k%3D2&bg=ffffff&fg=333333&s=0
"k=2") we have the cycle 2 family and so on. The frequency of the cycle
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
families for
![k=1..50](https://s0.wp.com/latex.php?latex=k%3D1..50&bg=ffffff&fg=333333&s=0
"k=1..50") in the first 2262 primes is shown in figure 4.

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig4_cyclek_fam1.png?w=640&h=401)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig4_cyclek_fam1.png)Figure
4.

We observe that the cycle 1 primes are the most common: 7, 17, 19, 23,
29, 47, 59, 61, 97, 109…  
Then cycle 2 primes: 3, 13, 31, 43, 67, 71, 83, 89, 107, 151…  
Thereafter the cycles become rarer rapidly. Cycle 3: 103, 127, 139, 331,
349, 421, 457, 463, 607, 661…  
cycle 4: 53, 173, 277, 317, 397, 769, 773, 797, 809, 853…  
cycle 5 is anomalously rarer than the flanking even
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
cycles: 11, 251, 1061, 1451, 1901, 1931, 2381, 3181, 3491, 3851…  
This anomalous rarity continues for at least few subsequent odd ![k=7,
9, 11, 13,
15...](https://s0.wp.com/latex.php?latex=k%3D7%2C+9%2C+11%2C+13%2C+15...&bg=ffffff&fg=333333&s=0
"k=7, 9, 11, 13, 15...") relative to the flanking even
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").
The frequencies of the primes belonging to each cycle appear to converge
to particular values. Whether there is some systematic way for
accounting for this distribution remains an open question to us.

We can also look at the first prime in each cycle: The first prime to
show cycle 1 is 7; the first to show cycle 2 is 3; then we get a
dramatic jump with the first to show cycle 3 being 103 and so on. Thus
we can define a sequence which is the first prime in each cycle: 7, 3,
103, 53, 11, 79, 211, 41, 73, 281, 353, 37, 2393, 449, 3061, 1889, 137,
2467, 16189, 641. Figure 5 shows a plot of this sequence.

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig5_1st_cyck.png?w=640&h=401)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig5_1st_cyck.png)Figure
5. The first prime in each cycle is plotted as both a height and a
point. The cycles which were not attained in the first 2262 primes are
shown as red empty circles.

This plot leave us with many unanswered questions: 1) Is there someway
to decide a priori what will be the first prime to have a certain
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
cycle? 2) Is there some pattern to the plot in Figure 5? 3) We observed
that from
![k=29](https://s0.wp.com/latex.php?latex=k%3D29&bg=ffffff&fg=333333&s=0
"k=29") onward there are several
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
for which the cycle is not initiated within the range of the first 2262
primes we used in this plot. Are there are any
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
for which a cycle is never initiated?

Finally, we could ask the question: what is the count of the primes of
cycle ![k \\le
n](https://s0.wp.com/latex.php?latex=k+%5Cle+n&bg=ffffff&fg=333333&s=0
"k \\le n"), i.e., the counting function for cycle
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
primes. This is shown for cycle 1 primes in Figure 6.

[![](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig6_cycle1_counting.png?w=640&h=401)](https://manasataramgini.files.wordpress.com/2018/11/prime_inverse_a002371_fig6_cycle1_counting.png)Figure
6. The heights in blue are the number of cycle 1 primes ![\\le
n](https://s0.wp.com/latex.php?latex=%5Cle+n&bg=ffffff&fg=333333&s=0
"\\le n"). The curves in red are
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)") and
![0.3824\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=0.3824%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"0.3824\\textrm{Li}(x)") respectively.

We observe that this count can be described by a fraction of the prime
counting function or its asymptotic equivalent. In the above case, we
use the logarithmic integral
![\\textrm{Li}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLi%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{Li}(x)"). The fraction is the convergent frequency of the
cycle ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0
"k"), which in the case of cycle 1 can be computed to be approximately
0.3824 using the first 2262 primes. This again brings us to the issue of
whether one can obtain a closed form description for these frequencies.
