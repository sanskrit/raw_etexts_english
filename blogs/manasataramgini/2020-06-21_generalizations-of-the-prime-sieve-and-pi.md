+++
title = "Generalizations of the prime sieve and Pi"

+++
[PDF
version](https://manasataramgini.files.wordpress.com/2020/06/sieves-1.pdf)
for better reading

Eratosthenes, the preeminent yavana philosopher of early Ptolemaic Egypt
\[footnote 1\], composed a hymn to the god Hermes of which only some
fragments have come down to us. This connection to Hermes is evidently
related to his Egyptian locus, where the old ritual-experts saw all
manner of clever inventions and ritual ordinances as being set down by
their god Thoth, who was syncretized with Hermes of the yavana
conquerors of Egypt. In this hymn, Eratosthenes describes Hermes as
looking down on universe from the highest sphere of heaven
(![\\sim](https://s0.wp.com/latex.php?latex=%5Csim&bg=ffffff&fg=333333&s=0
"\\sim") Ārya parame vyoman \[footnote 2\]. As he did so, Hermes is
mentioned as perceiving the harmony of the spheres of the planets and
the world axis passing through the earth in the center. Eratosthenes
represented these harmonies in the form of the lyre that was invented by
the god Hermes and gifted to the god Apollo. Eratosthenes, held that
while surveying the universe from the highest sphere, Hermes saw that
the “harmony of the spheres” was the same as the harmony of his lyre.
This equivalence of the harmonies was seen by these yavanācarya-s as
illustrating the desmos (equivalent of Ārya saṃbandha: the common
thread, bindings, equivalences) that runs across different branches of
mathematics (noted by Friedrich Solmsen who brought to light the
religious background of Eratosthenes, something that is ignored by those
who wish to paint him in the image of a modern “scientist” of the
Occident ). Indeed, similar “harmonies” were perceived by the yavana
sage Pythagoras and before him in the form of the numerical sambandha-s
of the Ārya-s of the Yajurveda — such mysterious numerical patterns and
conjunctions bring together apparent disparate branches of mathematics.

Keeping with the god with whom he had a special connection, Eratosthenes
was the inventive kind, who, while a Platonist (made clear by the sage
Iamblichus), was somewhat unlike those of the pure geometric school — he
described to king Ptolemaios a method of doubling the Delian altar of
Apollo with a machine rather than the geometric constructions of Eudoxus
(believed to be divinely inspired) using the curve known as the kampyle
![(y^{2}=\\tfrac{x^{4}}{a^{2}}-x^{2})](https://s0.wp.com/latex.php?latex=%28y%5E%7B2%7D%3D%5Ctfrac%7Bx%5E%7B4%7D%7D%7Ba%5E%7B2%7D%7D-x%5E%7B2%7D%29&bg=ffffff&fg=333333&s=0
"(y^{2}=\\tfrac{x^{4}}{a^{2}}-x^{2})") or the conics used by Plato’s
associates Menaechmus and Dinostratus. Likewise, he was more like the
Ārya-s in his algorithmic methods pertaining to numbers — perhaps most
famously the sieve for prime numbers is attributed to him. We had the
experience of such a sambandha while exploring the prime sieve and its
generalizations.

The prime sieve is a simple but powerful algorithm for extracting the
sequence of prime numbers
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
that one might have learned in elementary school. While a product of the
ancient world, its power is best appreciated in the modern computer age
and is recommended to students as one of the first computer programs to
write. In its modern form it goes thus (the ancient yavana concept of
numbers was geometric and not exactly the same as we might take it be):

• Write out the sequence of integers ![2, 3, 4, 5, 6, 7, 8, 9, 10, 11,
12, 13, 14, 15, 16, 17, 18, 19, 20, 21
\\dots](https://s0.wp.com/latex.php?latex=2%2C+3%2C+4%2C+5%2C+6%2C+7%2C+8%2C+9%2C+10%2C+11%2C+12%2C+13%2C+14%2C+15%2C+16%2C+17%2C+18%2C+19%2C+20%2C+21+%5Cdots&bg=ffffff&fg=333333&s=0
"2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21 \\dots")

• Move the first integer in this sequence to sequence
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
and kill all its multiples from the above sequence (circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-9.png?w=1024)

• This yields a new sequence: ![3, 5, 7, 9, 11, 13, 15, 17, 19, 21
\\dots](https://s0.wp.com/latex.php?latex=3%2C+5%2C+7%2C+9%2C+11%2C+13%2C+15%2C+17%2C+19%2C+21+%5Cdots&bg=ffffff&fg=333333&s=0
"3, 5, 7, 9, 11, 13, 15, 17, 19, 21 \\dots") Again move the first term
of this sequence to sequence
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
and kill its multiples in this sequence (circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-2.png?w=650)

• Repeat this procedure with ![5, 7, 11, 13, 17, 19
\\dots](https://s0.wp.com/latex.php?latex=5%2C+7%2C+11%2C+13%2C+17%2C+19+%5Cdots&bg=ffffff&fg=333333&s=0
"5, 7, 11, 13, 17, 19 \\dots") for as many cycles as required. Thus, you
get the sequence of prime numbers ![p: 2, 3, 5, 7, 11, 13, 17, 19
\\dots](https://s0.wp.com/latex.php?latex=p%3A+2%2C+3%2C+5%2C+7%2C+11%2C+13%2C+17%2C+19+%5Cdots&bg=ffffff&fg=333333&s=0
"p: 2, 3, 5, 7, 11, 13, 17, 19 \\dots")

Millennia after Eratosthenes, in the 1950s, Jabotinsky generalized this
sieve algorithm to generate other notable sequences. The first of these
goes thus:

• Write out the sequence of integers ![1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21
\\dots](https://s0.wp.com/latex.php?latex=1%2C+2%2C+3%2C+4%2C+5%2C+6%2C+7%2C+8%2C+9%2C+10%2C+11%2C+12%2C+13%2C+14%2C+15%2C+16%2C+17%2C+18%2C+19%2C+20%2C+21+%5Cdots&bg=ffffff&fg=333333&s=0
"1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21 \\dots")

• Move the first integer in this sequence to sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and kill all integers by jumping by a skip of size equal to that first
integer, starting from that first integer of the above sequence
(circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-3.png?w=1024)

• This yields a new sequence: ![2, 4, 6, 8, 10, 12, 14, 16, 18, 20
\\dots](https://s0.wp.com/latex.php?latex=2%2C+4%2C+6%2C+8%2C+10%2C+12%2C+14%2C+16%2C+18%2C+20+%5Cdots&bg=ffffff&fg=333333&s=0
"2, 4, 6, 8, 10, 12, 14, 16, 18, 20 \\dots") Again move the first term
of this sequence to sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and kill all integers by jumping with a skip equal to the new first
integer starting from it (circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-10.png?w=595)

• This yields a new sequence: ![4, 6, 10, 12, 16, 18, 22, 24, 28, 30,
34, 36, 40
\\dots](https://s0.wp.com/latex.php?latex=4%2C+6%2C+10%2C+12%2C+16%2C+18%2C+22%2C+24%2C+28%2C+30%2C+34%2C+36%2C+40+%5Cdots&bg=ffffff&fg=333333&s=0
"4, 6, 10, 12, 16, 18, 22, 24, 28, 30, 34, 36, 40 \\dots"). We
illustrate the next few steps below:

![](https://manasataramgini.files.wordpress.com/2020/06/image-5.png?w=1024)

• Thus, the above sieve yields the sequence

![a=1, 2, 4, 6, 10, 12, 16, 22, 24, 28, 36, 40, 42, 46, 52, 60, 66, 70,
76, 82
\\dots](https://s0.wp.com/latex.php?latex=a%3D1%2C+2%2C+4%2C+6%2C+10%2C+12%2C+16%2C+22%2C+24%2C+28%2C+36%2C+40%2C+42%2C+46%2C+52%2C+60%2C+66%2C+70%2C+76%2C+82+%5Cdots&bg=ffffff&fg=333333&s=0
"a=1, 2, 4, 6, 10, 12, 16, 22, 24, 28, 36, 40, 42, 46, 52, 60, 66, 70, 76, 82 \\dots")

The form of the sequence originally published by Erdős and Jabotinsky is
the above sequence plus 1 (Sometimes called Ludic numbers). i.e.:

![2, 3, 5, 7, 11, 13, 17, 23, 25, 29, 37, 41, 43, 47, 53
\\dots](https://s0.wp.com/latex.php?latex=2%2C+3%2C+5%2C+7%2C+11%2C+13%2C+17%2C+23%2C+25%2C+29%2C+37%2C+41%2C+43%2C+47%2C+53+%5Cdots&bg=ffffff&fg=333333&s=0
"2, 3, 5, 7, 11, 13, 17, 23, 25, 29, 37, 41, 43, 47, 53 \\dots")

This sequence can also be generated by applying a sieve just as above
starting with an initial sequence ![2, 3, 4, 5, 6
\\dots](https://s0.wp.com/latex.php?latex=2%2C+3%2C+4%2C+5%2C+6+%5Cdots&bg=ffffff&fg=333333&s=0
"2, 3, 4, 5, 6 \\dots") and killing integers with a skip of size equal
to first term of the intermediate sequence minus 1. As one can see, this
version of the sequence includes certain primes and certain odd numbers
which are not primes (e.g. 25, 77, 91, 115, 119, 121, 143, 161, 175 …).

We know that prime number sequence
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
has a scaling which can be asymptotically represented by ![p\[n\] \\sim
n\\log(n)](https://s0.wp.com/latex.php?latex=p%5Bn%5D+%5Csim+n%5Clog%28n%29&bg=ffffff&fg=333333&s=0
"p[n] \\sim n\\log(n)"). Now we can ask how does this sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
generated by the generalized sieve scale (Figure 1)?

![Figure 1. Scaling of sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a").](https://manasataramgini.files.wordpress.com/2020/06/jaber1.png?w=1024)

We see that
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
grows more rapidly than
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
(Figure 1, black line) though it must be asymptotic to the latter. Thus,
there must be additional terms to get a better asymptotic fit than
![n\\log(n)](https://s0.wp.com/latex.php?latex=n%5Clog%28n%29&bg=ffffff&fg=333333&s=0
"n\\log(n)") (Figure 1, gray line). Figure 1 shows at till the term
10000 ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") lies between:

![n\\log(n)+\\tfrac{1}{2}n(\\log(\\log(n)))^2](https://s0.wp.com/latex.php?latex=n%5Clog%28n%29%2B%5Ctfrac%7B1%7D%7B2%7Dn%28%5Clog%28%5Clog%28n%29%29%29%5E2&bg=ffffff&fg=333333&s=0
"n\\log(n)+\\tfrac{1}{2}n(\\log(\\log(n)))^2") (brown dotted line) and

![n\\log(n)+\\tfrac{1}{2}n(\\log(\\log(n)))^2 +
(2-\\gamma)n\\log(\\log(n))](https://s0.wp.com/latex.php?latex=n%5Clog%28n%29%2B%5Ctfrac%7B1%7D%7B2%7Dn%28%5Clog%28%5Clog%28n%29%29%29%5E2+%2B+%282-%5Cgamma%29n%5Clog%28%5Clog%28n%29%29&bg=ffffff&fg=333333&s=0
"n\\log(n)+\\tfrac{1}{2}n(\\log(\\log(n)))^2 + (2-\\gamma)n\\log(\\log(n))")
(brown solid line),

where ![\\gamma = -\\textrm{di}\\gamma(1) \\approx
0.5772157](https://s0.wp.com/latex.php?latex=%5Cgamma+%3D+-%5Ctextrm%7Bdi%7D%5Cgamma%281%29+%5Capprox+0.5772157&bg=ffffff&fg=333333&s=0
"\\gamma = -\\textrm{di}\\gamma(1) \\approx 0.5772157") is Euler’s
constant.

Erdős and Jabotinsky have shown that for large
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
the growth of sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
exceeds the above higher bound by a further correction term.

We can generate another related sequence by a similar sieve where we
kill the terms by skipping over ![2
\\times](https://s0.wp.com/latex.php?latex=2+%5Ctimes&bg=ffffff&fg=333333&s=0
"2 \\times") the value first term. This results in the sequence

![b: 1, 2, 3, 5, 6, 8, 11, 12, 14, 18, 20, 21, 23, 26, 30, 33, 35, 38,
41, 44
\\dots](https://s0.wp.com/latex.php?latex=b%3A+1%2C+2%2C+3%2C+5%2C+6%2C+8%2C+11%2C+12%2C+14%2C+18%2C+20%2C+21%2C+23%2C+26%2C+30%2C+33%2C+35%2C+38%2C+41%2C+44+%5Cdots&bg=ffffff&fg=333333&s=0
"b: 1, 2, 3, 5, 6, 8, 11, 12, 14, 18, 20, 21, 23, 26, 30, 33, 35, 38, 41, 44 \\dots")

Unlike the sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") it
includes both odd and even numbers and one notices that
![b\[n\]=\\tfrac{a\[n\]}{2}](https://s0.wp.com/latex.php?latex=b%5Bn%5D%3D%5Ctfrac%7Ba%5Bn%5D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"b[n]=\\tfrac{a[n]}{2}") starting from the term
![a\[2\]](https://s0.wp.com/latex.php?latex=a%5B2%5D&bg=ffffff&fg=333333&s=0
"a[2]").

As one can see it scales at half rate of the sequence
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
Thus, this type of generalized sieve reveals that sequences arising from
a process, where the skip is dependent on the first term of the
intermediate sequence, are asymptotic with a function whose base term is
of the form ![a\_n \\sim k
n\\log(n)](https://s0.wp.com/latex.php?latex=a_n+%5Csim+k+n%5Clog%28n%29&bg=ffffff&fg=333333&s=0
"a_n \\sim k n\\log(n)"), where
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") is
a constant. One may say that of these the one which yields the primes is
some kind of an optimal sieve that lets neither too few nor two many
numbers pass through it. Thus, intuitively, the primes can be seen as an
inherent optimal path through the number world.

The next type of sieve of Jabotinsky is operated thus:

• Write out the sequence of integers ![1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21
\\dots](https://s0.wp.com/latex.php?latex=1%2C+2%2C+3%2C+4%2C+5%2C+6%2C+7%2C+8%2C+9%2C+10%2C+11%2C+12%2C+13%2C+14%2C+15%2C+16%2C+17%2C+18%2C+19%2C+20%2C+21+%5Cdots&bg=ffffff&fg=333333&s=0
"1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21 \\dots")

• Move the first integer in this sequence to sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
and kill all integers by jumping by a skip of size 1 starting from the
first integer of the above sequence (circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-8.png?w=1024)

• This yields a new sequence: ![2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22,
24, 26, 28, 30, 32, 34, 36, 38, 40
\\dots](https://s0.wp.com/latex.php?latex=2%2C+4%2C+6%2C+8%2C+10%2C+12%2C+14%2C+16%2C+18%2C+20%2C+22%2C+24%2C+26%2C+28%2C+30%2C+32%2C+34%2C+36%2C+38%2C+40+%5Cdots&bg=ffffff&fg=333333&s=0
"2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40 \\dots")
Now we operate on this sequence by sending the first term to sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
and starting from it killing all terms by jump with a skip of 2
(circled):

![](https://manasataramgini.files.wordpress.com/2020/06/image-7.png?w=1024)

• This yields a new sequence: ![4, 6, 10, 12, 16, 18, 22, 24, 28, 30,
34, 36, 40, 42, 46, 48, 52, 54
\\dots](https://s0.wp.com/latex.php?latex=4%2C+6%2C+10%2C+12%2C+16%2C+18%2C+22%2C+24%2C+28%2C+30%2C+34%2C+36%2C+40%2C+42%2C+46%2C+48%2C+52%2C+54+%5Cdots&bg=ffffff&fg=333333&s=0
"4, 6, 10, 12, 16, 18, 22, 24, 28, 30, 34, 36, 40, 42, 46, 48, 52, 54 \\dots")
We repeat the above procedure, killing terms in each iteration with
skips of 3, 4, 5… As a result we get the sequence:

![f: 1, 2, 4, 6, 10, 12, 18, 22, 30, 34, 42, 48
\\dots](https://s0.wp.com/latex.php?latex=f%3A+1%2C+2%2C+4%2C+6%2C+10%2C+12%2C+18%2C+22%2C+30%2C+34%2C+42%2C+48+%5Cdots&bg=ffffff&fg=333333&s=0
"f: 1, 2, 4, 6, 10, 12, 18, 22, 30, 34, 42, 48 \\dots")

This sequence relates to a function on positive integers
![\\textrm{jab}(n)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bjab%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\textrm{jab}(n)"); we illustrate this function by the example of
![\\textrm{jab}(8)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bjab%7D%288%29&bg=ffffff&fg=333333&s=0
"\\textrm{jab}(8)"):

• We take 8 and reduce it by 1 to get 7.

• We then get the lowest multiple of 7 that is greater than 8
![\\rightarrow
14](https://s0.wp.com/latex.php?latex=%5Crightarrow+14&bg=ffffff&fg=333333&s=0
"\\rightarrow 14").

• We then reduce 7 by 1 ![\\rightarrow
6](https://s0.wp.com/latex.php?latex=%5Crightarrow+6&bg=ffffff&fg=333333&s=0
"\\rightarrow 6") and obtain lowest multiple of 6 that is greater than
14 ![\\rightarrow
18](https://s0.wp.com/latex.php?latex=%5Crightarrow+18&bg=ffffff&fg=333333&s=0
"\\rightarrow 18").

• We continue this procedure till the successive reduction ends in 1.
The corresponding sequence of their multiples is:

![8 \\rightarrow 14 \\rightarrow 18 \\rightarrow 20 \\rightarrow 20
\\rightarrow 21 \\rightarrow 22 \\rightarrow
22](https://s0.wp.com/latex.php?latex=8+%5Crightarrow+14+%5Crightarrow+18+%5Crightarrow+20+%5Crightarrow+20+%5Crightarrow+21+%5Crightarrow+22+%5Crightarrow+22&bg=ffffff&fg=333333&s=0
"8 \\rightarrow 14 \\rightarrow 18 \\rightarrow 20 \\rightarrow 20 \\rightarrow 21 \\rightarrow 22 \\rightarrow 22")

• Thus, we get
![\\textrm{jab}(8)=22](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bjab%7D%288%29%3D22&bg=ffffff&fg=333333&s=0
"\\textrm{jab}(8)=22")

Remarkably, it turns out that
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f") is
the sequence of
![\\textrm{jab}(n)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Bjab%7D%28n%29&bg=ffffff&fg=333333&s=0
"\\textrm{jab}(n)").

![Figure 2. Scaling of sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0
"f")](https://manasataramgini.files.wordpress.com/2020/06/jaber2.png?w=1024)

Even more remarkably, ![f\[n\] =
\\tfrac{n^2}{\\pi}+c](https://s0.wp.com/latex.php?latex=f%5Bn%5D+%3D+%5Ctfrac%7Bn%5E2%7D%7B%5Cpi%7D%2Bc&bg=ffffff&fg=333333&s=0
"f[n] = \\tfrac{n^2}{\\pi}+c"); where
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c") is
a correction term. Erdős and Jabotinsky showed that
![c=\\mathcal{O}(x)](https://s0.wp.com/latex.php?latex=c%3D%5Cmathcal%7BO%7D%28x%29&bg=ffffff&fg=333333&s=0
"c=\\mathcal{O}(x)") in the big
![\\mathcal{O}](https://s0.wp.com/latex.php?latex=%5Cmathcal%7BO%7D&bg=ffffff&fg=333333&s=0
"\\mathcal{O}") notation. For relatively small
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") we
can safely write ![f\[n\] \\approx
\\tfrac{n^2}{\\pi}](https://s0.wp.com/latex.php?latex=f%5Bn%5D+%5Capprox+%5Ctfrac%7Bn%5E2%7D%7B%5Cpi%7D&bg=ffffff&fg=333333&s=0
"f[n] \\approx \\tfrac{n^2}{\\pi}"), i.e. a parabolic scaling with
![\\tfrac{1}{\\pi}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B1%7D%7B%5Cpi%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{1}{\\pi}") as the coefficient (brown line in Figure 2). Thus,
the generalized sieving procedure yields a sequence that provides a
mysterious “desmos” to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") yet again linking disparate branches of mathematics. More
generally, it points that beneath these branches lie relatively simply
computational processes such as the sieve, whose original form was
attributed to Eratosthenes, which yields a variety of entities
organically, like prime numbers or
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi").

Finally, this parabolic scaling with
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") as the constant also brings to mind an interesting iterative
generator of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") and
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e"),
apparently first discovered by Cloitre:

• Initiate two maps with the terms
![x\_1=y\_1=0](https://s0.wp.com/latex.php?latex=x_1%3Dy_1%3D0&bg=ffffff&fg=333333&s=0
"x_1=y_1=0") and
![x\_2=y\_2=1](https://s0.wp.com/latex.php?latex=x_2%3Dy_2%3D1&bg=ffffff&fg=333333&s=0
"x_2=y_2=1")

• Iterate the maps as
![x\_n=x\_{n-1}+\\tfrac{x\_{n-2}}{n-2}](https://s0.wp.com/latex.php?latex=x_n%3Dx_%7Bn-1%7D%2B%5Ctfrac%7Bx_%7Bn-2%7D%7D%7Bn-2%7D&bg=ffffff&fg=333333&s=0
"x_n=x_{n-1}+\\tfrac{x_{n-2}}{n-2}") and
![y\_n=\\tfrac{y\_{n-1}}{n-2}+y\_{n-2}](https://s0.wp.com/latex.php?latex=y_n%3D%5Ctfrac%7By_%7Bn-1%7D%7D%7Bn-2%7D%2By_%7Bn-2%7D&bg=ffffff&fg=333333&s=0
"y_n=\\tfrac{y_{n-1}}{n-2}+y_{n-2}")

• ![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") scales as
![\\tfrac{n}{e}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7Be%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{e}") and
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") scales as
![\\sqrt{\\tfrac{2n}{\\pi}}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B%5Ctfrac%7B2n%7D%7B%5Cpi%7D%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{\\tfrac{2n}{\\pi}}")

![Figure 3. Maps generating
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e")
and ![pi](https://s0.wp.com/latex.php?latex=pi&bg=ffffff&fg=333333&s=0
"pi").](https://manasataramgini.files.wordpress.com/2020/06/jaber3.png?w=1024)

Here, while the map generates
![e](https://s0.wp.com/latex.php?latex=e&bg=ffffff&fg=333333&s=0 "e")
via a linear relationship it generated
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") via a parabolic relationship.

-----

Footnote 1: Sometimes he is called the new or second Plato; Archimedes
addresses him as philosophías proestō̃ta

Footnote 2: This evidently derives from an old IE tradition as one can
also compare it with the phrase used for the cognate deity Pūṣaṇ:
saṃcakṣāṇo bhuvanā deva īyate by the Aṅgiras, Bharadvāja
Bārhaspatya, in RV 6.58.2. In Greek world, there were two evolutes
descending from the Proto-Indo-European cognate of Pūṣaṇ: Hermes and Pan
