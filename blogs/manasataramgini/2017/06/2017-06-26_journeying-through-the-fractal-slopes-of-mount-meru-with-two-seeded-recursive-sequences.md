+++
title = "Journeying through the fractal slopes of mount Meru with two-seeded recursive sequences"

+++
The Hindus have been fascinated by sequences and series from the
beginning of their civilizational memory recorded in the Veda. This
continues down to the medieval mathematician Nārāyaṇa paṇḍita,
who discovered a general formula (sāmāsika paṅkti) that can be to
obtain the ‘Meru-średhī’ (known in the west as Fibonacci’s sequence). He
uses it as a model to explain the population dynamics of cows. In modern
terms the formula goes thus:  
Let
![f\[1\]=f\[2\]=1](https://s0.wp.com/latex.php?latex=f%5B1%5D%3Df%5B2%5D%3D1&bg=ffffff&fg=333333&s=0
"f[1]=f[2]=1"). These are two seeds of the sequence. Then,  
![f\[n\]=f\[n-1\]+f\[n-2\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-1%5D%2Bf%5Bn-2%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-1]+f[n-2]"), where
![n=3,4,5...](https://s0.wp.com/latex.php?latex=n%3D3%2C4%2C5...&bg=ffffff&fg=333333&s=0
"n=3,4,5...").  
One sees that this yields the famous sequence: 1, 1, 2, 3, 5, 8, 13, 21,
34, 55… i.e. a version of Nārāyaṇa’s Dhenu-saṃkhya or cow-numbers. We
may denote this special sequence as
![M\[n\]](https://s0.wp.com/latex.php?latex=M%5Bn%5D&bg=ffffff&fg=333333&s=0
"M[n]"). It is well-known that,  
![\\displaystyle \\lim\_{n \\to \\infty}
\\dfrac{M\[n+1\]}{M\[n\]}=\\phi](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D+%5Cdfrac%7BM%5Bn%2B1%5D%7D%7BM%5Bn%5D%7D%3D%5Cphi&bg=ffffff&fg=333333&s=0
"\\displaystyle \\lim_{n \\to \\infty} \\dfrac{M[n+1]}{M[n]}=\\phi"),
where
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") is the Golden ratio.  
[Thus, as we have illustrated
before,](https://manasataramgini.wordpress.com/2016/10/04/some-meanderings-among-golden-stuff-2/)
the Dhenu-saṃkhya can be obtained as integer values of a function based
on
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi").

Closer to our times, following the discovery of [a everywhere continuous
but nowhere differentiable function by Bernhard
Riemann](https://manasataramgini.wordpress.com/2017/03/26/some-visions-of-infinity-from-the-past-and-our-times/),
the Japanese mathematician Teiji Takagi discovered another remarkable
curve of this type. Let function
![s(x)](https://s0.wp.com/latex.php?latex=s%28x%29&bg=ffffff&fg=333333&s=0
"s(x)") be defined as,  
![s\\left(x\\right)=\\min \\left(\\left(x-\\lfloor x \\rfloor
\\right),\\textrm{abs}\\left(x-\\lceil x \\rceil
\\right)\\right)](https://s0.wp.com/latex.php?latex=s%5Cleft%28x%5Cright%29%3D%5Cmin+%5Cleft%28%5Cleft%28x-%5Clfloor+x+%5Crfloor+%5Cright%29%2C%5Ctextrm%7Babs%7D%5Cleft%28x-%5Clceil+x+%5Crceil+%5Cright%29%5Cright%29&bg=ffffff&fg=333333&s=0
"s\\left(x\\right)=\\min \\left(\\left(x-\\lfloor x \\rfloor \\right),\\textrm{abs}\\left(x-\\lceil x \\rceil \\right)\\right)")

Then the Takagi function is defined as,  
![f\\left(x\\right)=\\displaystyle \\sum \_{n=0}^\\infty w^n \\cdot
s\\left(2^n x
\\right)](https://s0.wp.com/latex.php?latex=f%5Cleft%28x%5Cright%29%3D%5Cdisplaystyle+%5Csum+_%7Bn%3D0%7D%5E%5Cinfty+w%5En+%5Ccdot+s%5Cleft%282%5En+x+%5Cright%29&bg=ffffff&fg=333333&s=0
"f\\left(x\\right)=\\displaystyle \\sum _{n=0}^\\infty w^n \\cdot s\\left(2^n x \\right)")
Parameter
![w=0.5](https://s0.wp.com/latex.php?latex=w%3D0.5&bg=ffffff&fg=333333&s=0
"w=0.5") gives an aesthetically pleasing curve. As can be seen from the
figure the curve as has fractal form keeping with its undifferentiable
nature

[![Figure1\_Takagi\_curve](https://manasataramgini.files.wordpress.com/2017/06/figure1_takagi_curve.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure1_takagi_curve.png)Figure
1. The Takagi curve (red)

A lay person may wonder why we are mentioning these two seemingly
disparate pieces of mathematics together. The connection between them
becomes apparent via the remarkable sequences discovered by the
scientist-philosopher Douglas Hofstadter. He first presented these ideas
in his curious book ‘Gödel, Escher, Bach: An Eternal Golden Braid’.

Our own journey through these began in the days of our youth when we
chanced upon Hofstadter’s book in a book-store. Not having the cash to
procure it we spent sometime taking in its braided ideas right there.
While that encounter was not enough to take in all the sequences he
discussed in the book we got enough of the basic idea to experiment by
ourselves. The basic idea behind the Hofstadter class of sequences is a
generalization of the procedure behind the Meru-średhī. This can be
illustrated with the sequence with which we first experimented:  
![f\[n\]=n-f\[f\[n-1\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Dn-f%5Bf%5Bn-1%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=n-f[f[n-1]]"), where
![f\[1\]=f\[2\]=1](https://s0.wp.com/latex.php?latex=f%5B1%5D%3Df%5B2%5D%3D1&bg=ffffff&fg=333333&s=0
"f[1]=f[2]=1") and
![n=3,4...](https://s0.wp.com/latex.php?latex=n%3D3%2C4...&bg=ffffff&fg=333333&s=0
"n=3,4...")  
Like
![M\[n\]](https://s0.wp.com/latex.php?latex=M%5Bn%5D&bg=ffffff&fg=333333&s=0
"M[n]") it is also initiated with two seed values but the definition of
the subsequent elements involves a nested definition. The definition
itself looks simple and yields the following sequence:  
1, 1, 2, 3, 3, 4, 4, 5, 6, 6, 7, 8, 8, 9, 9, 10, 11, 11, 12, 12, 13, 14…

One notices that unlike the Dhenu-saṃkhya-s this sequence covers all the
positive integers. However, some are repeated multiple times.
Interestingly, we observe that ![f\[3\]=2, f\[5\]=3, f\[8\]=5,
f\[13\]=8,
f\[21\]=13](https://s0.wp.com/latex.php?latex=f%5B3%5D%3D2%2C+f%5B5%5D%3D3%2C+f%5B8%5D%3D5%2C+f%5B13%5D%3D8%2C+f%5B21%5D%3D13&bg=ffffff&fg=333333&s=0
"f[3]=2, f[5]=3, f[8]=5, f[13]=8, f[21]=13"). Thus more generally
![f\\left \[M\[n\] \\right
\]=M\[n-1\]](https://s0.wp.com/latex.php?latex=f%5Cleft+%5BM%5Bn%5D+%5Cright+%5D%3DM%5Bn-1%5D&bg=ffffff&fg=333333&s=0
"f\\left [M[n] \\right ]=M[n-1]"). Moreover, once we have this sequence
we can also write out pairs of the form
![(f\[n\],n)](https://s0.wp.com/latex.php?latex=%28f%5Bn%5D%2Cn%29&bg=ffffff&fg=333333&s=0
"(f[n],n)"). The set of such pairs can be represented as edges of a
graph (i.e. ![f\[n\] \\rightarrow
n](https://s0.wp.com/latex.php?latex=f%5Bn%5D+%5Crightarrow+n&bg=ffffff&fg=333333&s=0
"f[n] \\rightarrow n")), which turns out to be a tree.

[![Figure2\_Meru\_tree](https://manasataramgini.files.wordpress.com/2017/06/figure2_meru_tree.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure2_meru_tree.png)Figure
2. Graph of
![(f\[n\],n=1:50)](https://s0.wp.com/latex.php?latex=%28f%5Bn%5D%2Cn%3D1%3A50%29&bg=ffffff&fg=333333&s=0
"(f[n],n=1:50)")

The tree displays an interesting structure which resembles an
evolutionary process of descent through modification. In this we can
recognize a “primitive” lineage which is the line of descent comprised
of
![M\[n\]](https://s0.wp.com/latex.php?latex=M%5Bn%5D&bg=ffffff&fg=333333&s=0
"M[n]"). The remain lines of descent branching off from it also display
a Meru-średhī process albeit each at a different level. For e.g. we have
the line of descent: 3, 4, 7, 11, 18, 29, 47…

Our next advance in understanding these sequences came from reading a
paper by Clifford Pickover, which presented a means of graphically
visualizing the structure of these sequences. Inspired by this we used a
slightly different graphical representation to study the structure
specified by these sequences. One of the notable Hofstadter sequences
is,  
![f\[n\]=f\[f\[n-1\]\]+f\[n-f\[n-1\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bn-1%5D%5D%2Bf%5Bn-f%5Bn-1%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[n-1]]+f[n-f[n-1]]")

The technique we used to visualize the sequence is to subtract a certain
factor proportional to
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
from the
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") in order to render the values along the x-axis rather than as
along the curve which the increasing
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") follows. We call this rectification. Thus we rectify the above
sequence by plotting ![(n,
f\[n\]-\\tfrac{n}{2})](https://s0.wp.com/latex.php?latex=%28n%2C+f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D%29&bg=ffffff&fg=333333&s=0
"(n, f[n]-\\tfrac{n}{2})")

[![Figure3\_Hofstadter\_batrachion](https://manasataramgini.files.wordpress.com/2017/06/figure3_hofstadter_batrachion.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure3_hofstadter_batrachion.png)Figure
3. ![(n,
f\[n\]-\\tfrac{n}{2})](https://s0.wp.com/latex.php?latex=%28n%2C+f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D%29&bg=ffffff&fg=333333&s=0
"(n, f[n]-\\tfrac{n}{2})") for
![f\[n\]=f\[f\[n-1\]\]+f\[n-f\[n-1\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bn-1%5D%5D%2Bf%5Bn-f%5Bn-1%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[n-1]]+f[n-f[n-1]]")

Remarkably we get ever larger copies of the Takagi curve, with each loop
progressing in width as 2, 4, 8, 16, … i.e. the powers of 2 (Figure 3).
Thus, the curve captures the binary base representation of integers up
to a give integer and the fractal has a predictable form. The successive
loops of the structure also represent a journey into the fractal
structure of the Takagi curve.

[![Figure4\_Mallows](https://manasataramgini.files.wordpress.com/2017/06/figure4_mallows.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure4_mallows.png)Figure
4.
![f\[n\]=f\[f\[n-2\]\]+f\[n-f\[n-2\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bn-2%5D%5D%2Bf%5Bn-f%5Bn-2%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[n-2]]+f[n-f[n-2]]") rectified as
![f\[n\]-.68n](https://s0.wp.com/latex.php?latex=f%5Bn%5D-.68n&bg=ffffff&fg=333333&s=0
"f[n]-.68n")

Another such sequence was discovered by Mallows (Figure 4), which has an
overall similar behavior as the above sequence of Hofstadter. However,
rather than the regular symmetric Takagi curve generated by the sequence
it has a more jagged fractal curve with a distinct pattern of two peaks
followed by three peaks.

Returning to the original sequence we studied,
![f\[n\]=n-f\[f\[n-1\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Dn-f%5Bf%5Bn-1%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=n-f[f[n-1]]"), we can rectify it using
![f\[n\]-\\tfrac{n}{\\phi}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{\\phi}").

[![Figure5\_Hofstader\_one\_by\_phi\_doubly\_recursive](https://manasataramgini.files.wordpress.com/2017/06/figure5_hofstader_one_by_phi_doubly_recursive.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure5_hofstader_one_by_phi_doubly_recursive.png)Figure
5.
![f\[n\]=n-f\[f\[n-1\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Dn-f%5Bf%5Bn-1%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=n-f[f[n-1]]")

It has a very different structure from the above sequences. Instead of
ever-increasing loops this is characterized by rapid but fixed bandwidth
of oscillation with basic reoccurring units incorporated into higher
order reoccurring units, reflective of its tree structure discussed
above.

One would notice that the generative formulae for these sequences,
unlike that of the Meru-średhī, involve doubly nested specifications.
Such specifications mostly lead to sterile sequences because the index
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
for a given
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") can drop below 1 or above the current value thus killing the
sequence. Nevertheless, there are several additional productive formulae
beyond the above that lead to a range of interesting behavior. These are
illustrated before.

[![Figure6\_Hofstadter\_pseudo\_repetitive](https://manasataramgini.files.wordpress.com/2017/06/figure6_hofstadter_pseudo_repetitive.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure6_hofstadter_pseudo_repetitive.png)Figure
6.
![f\[n\]=f\[n-f\[n-1\]\]+f\[n-f\[n-2\]-1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-f%5Bn-1%5D%5D%2Bf%5Bn-f%5Bn-2%5D-1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-f[n-1]]+f[n-f[n-2]-1]") rectified using
![f\[n\]-\\tfrac{n}{2}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{2}").

Somewhat similar theme to the above case with similar looking motifs
nested at multiple levels giving rise to a pseudo-repetitive appearance.

[![Figure7\_Hofstadter\_pulsations](https://manasataramgini.files.wordpress.com/2017/06/figure7_hofstadter_pulsations.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure7_hofstadter_pulsations.png)Figure
7.
![f\[n\]=f\[n-f\[n-1\]\]+f\[n-f\[n-2\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-f%5Bn-1%5D%5D%2Bf%5Bn-f%5Bn-2%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-f[n-1]]+f[n-f[n-2]]") rectified using
![f\[n\]-\\tfrac{n}{2}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{2}")

This is one of Hofstadter’s discoveries which has ever larger pulses of
high intensity fluctuations of similar form separated by regions of low
intensity fluctuations. The repetition of the same basic form albeit
with variation at larger and larger scales resembles the formula
generating the Takagi curve.

[![Figure8\_Hofstadter\_sinusoid](https://manasataramgini.files.wordpress.com/2017/06/figure8_hofstadter_sinusoid.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure8_hofstadter_sinusoid.png)Figure
8.
![f\[n\]=f\[f\[n-1\]\]+f\[n-f\[n-2\]-1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bn-1%5D%5D%2Bf%5Bn-f%5Bn-2%5D-1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[n-1]]+f[n-f[n-2]-1]") rectified using
![f\[n\]-\\tfrac{n}{2}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{2}")

Another Hofstadter sequence similar to the above but the pulses
themselves are arranged on waves of ever-increasing wave-length giving
it the form of ever-larger sigmoids.

[![Figure9\_Hofstadter\_Wolfram\_wavy](https://manasataramgini.files.wordpress.com/2017/06/figure9_hofstadter_wolfram_wavy.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure9_hofstadter_wolfram_wavy.png)Figure
9. ![f\[n\]=f\[f\[n-1\]\]+f\[n-2\\cdot
f\[n-1\]+1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bn-1%5D%5D%2Bf%5Bn-2%5Ccdot+f%5Bn-1%5D%2B1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[n-1]]+f[n-2\\cdot f[n-1]+1]").

This is non-linear in terms of its central growth curve and cannot be
perfectly rectified. Hence, the factor
![f\[n\]-.42n^{.818}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-.42n%5E%7B.818%7D&bg=ffffff&fg=333333&s=0
"f[n]-.42n^{.818}") is used. This was discovered by Stephen Wolfram in
an excellent introduction to these sequences for a lay reader although
he does little to acknowledge his predecessors’ work. It shows a higher
order wavy pattern of increasing wavelength but within it the pulsations
show much more irregularity.

[![Figure10\_Hofstadter\_random](https://manasataramgini.files.wordpress.com/2017/06/figure10_hofstadter_random.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure10_hofstadter_random.png)Figure
10.
![f\[n\]=f\[n-f\[n-1\]-1\]+f\[n-f\[n-2\]-1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-f%5Bn-1%5D-1%5D%2Bf%5Bn-f%5Bn-2%5D-1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-f[n-1]-1]+f[n-f[n-2]-1]") rectified using
![f\[n\]-\\tfrac{n}{2}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{2}")

Unlike the above this shows neither regions of reduced intensity
pulsation nor a higher order wavy pattern. Instead is simply shows a
chaotic pattern of fluctuations which grow in magnitude with
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n").

If the above sequences were generated using doubly nested specifications
we also find complex behavior emerging from triply nested formulations.
We discovered for ourselves some such sequences which are illustrated
below.

[![Figure11\_triply\_nested\_.6823](https://manasataramgini.files.wordpress.com/2017/06/figure11_triply_nested_-6823.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure11_triply_nested_-6823.png)Figure
11.
![f\[n\]=n-f\[f\[f\[n-2\]\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Dn-f%5Bf%5Bf%5Bn-2%5D%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=n-f[f[f[n-2]]]") rectified using
![f\[n\]-0.6823n](https://s0.wp.com/latex.php?latex=f%5Bn%5D-0.6823n&bg=ffffff&fg=333333&s=0
"f[n]-0.6823n")

This is a triply nested relative of the generative formula shown in
Figure 5. Like it is shows a fixed bandwidth along with some basic
motifs reoccurring at various scales.

[![Figure12\_triply\_nested\_seahorse](https://manasataramgini.files.wordpress.com/2017/06/figure12_triply_nested_seahorse.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure12_triply_nested_seahorse.png)Figure
12.
![f\[n\]=f\[f\[f\[n-1\]\]\]+f\[n-f\[f\[n-2\]\]-1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bf%5Bn-1%5D%5D%5D%2Bf%5Bn-f%5Bf%5Bn-2%5D%5D-1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[f[n-1]]]+f[n-f[f[n-2]]-1]") rectified using
![f\[n\]-0.45n](https://s0.wp.com/latex.php?latex=f%5Bn%5D-0.45n&bg=ffffff&fg=333333&s=0
"f[n]-0.45n")

This formula resembles the doubly nested version seen in Figure 8 and
like it shows a higher order wave-like structure with increasing
wavelength. Each wave module is a “sea-horse”-like structure, which
develops an increasingly complex pattern of fluctuations as it grows
larger in size.

[![Figure13\_Mt\_Meru](https://manasataramgini.files.wordpress.com/2017/06/figure13_mt_meru.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure13_mt_meru.png)Figure
13.
![f\[n\]=f\[f\[f\[n-1\]\]\]+f\[n-f\[f\[n-1\]\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bf%5Bn-1%5D%5D%5D%2Bf%5Bn-f%5Bf%5Bn-1%5D%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[f[n-1]]]+f[n-f[f[n-1]]]") rectified using
![f\[n\]-\\tfrac{n}{\\phi}](https://s0.wp.com/latex.php?latex=f%5Bn%5D-%5Ctfrac%7Bn%7D%7B%5Cphi%7D&bg=ffffff&fg=333333&s=0
"f[n]-\\tfrac{n}{\\phi}")

This triply nested formula shows a link to the Meru-średhī and
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") similar to the one explored in Figure 5. The rectified form
shows cycles of increasing size in the sequence 2, 5, 13, 34 … i.e.
![M\[2k+1\],\\;
k=1,2,3,4...](https://s0.wp.com/latex.php?latex=M%5B2k%2B1%5D%2C%5C%3B+k%3D1%2C2%2C3%2C4...&bg=ffffff&fg=333333&s=0
"M[2k+1],\\; k=1,2,3,4..."). These cycles are a journey up and down a
fractal mountain, which we term the journey through the slopes mount
Meru. The mountain has some fractal faces and others which are sheer
cliffs. Further, the set of edges ![f\[n\] \\rightarrow
n](https://s0.wp.com/latex.php?latex=f%5Bn%5D+%5Crightarrow+n&bg=ffffff&fg=333333&s=0
"f[n] \\rightarrow n") constitute a tree graph as seen with the
above-described doubly nested version. Remarkably, there is one
primitive lineage from which all other lineages branch off which is the
Meru-średhī with the Dhenu-saṃkhya-s (Figure 14). Now the branches also
show a curious relationship to the Dhenu-saṃkhya-s: at any section
through a given level in the tree we have that many branches as the
numbers that would count up to the corresponding Dhenu-saṃkhya in that
level. Thus at the level of first branch the numbers are 4, 5 (2
branches); at the next level the numbers on the branches are 6,7,8 (3
branches); at the next level 9,10,11,12,13 (5 branches) and so on. Thus
on each branch there is an inherent relationship to the underlying
Dhenu-saṃkhya, which can be seen in the figure. Whereas the graph in
Figure 2 shows a strict bifurcation this graph shows a pattern for
n-furcation related to the Dhenu-saṃkhya: if a non-primitive branch
emerges from a number the
![M\[n\]](https://s0.wp.com/latex.php?latex=M%5Bn%5D&bg=ffffff&fg=333333&s=0
"M[n]") then it will display
![n-3](https://s0.wp.com/latex.php?latex=n-3&bg=ffffff&fg=333333&s=0
"n-3")-furcation (Figure 14). Thus, the branch from
![M\[4\]](https://s0.wp.com/latex.php?latex=M%5B4%5D&bg=ffffff&fg=333333&s=0
"M[4]")=3 will show 1-furcation; the branch from
![M\[5\]=5](https://s0.wp.com/latex.php?latex=M%5B5%5D%3D5&bg=ffffff&fg=333333&s=0
"M[5]=5") will show 2-furcation; the branch from
![M\[6\]=8](https://s0.wp.com/latex.php?latex=M%5B6%5D%3D8&bg=ffffff&fg=333333&s=0
"M[6]=8") with show 3-furcation and so on.

[![Figure14\_meru\_tree\_triple\_recursive](https://manasataramgini.files.wordpress.com/2017/06/figure14_meru_tree_triple_recursive.png?w=640)](https://manasataramgini.files.wordpress.com/2017/06/figure14_meru_tree_triple_recursive.png)Figure
14. The branching graph for
![f\[n\]=f\[f\[f\[n-1\]\]\]+f\[n-f\[f\[n-1\]\]\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bf%5Bf%5Bn-1%5D%5D%5D%2Bf%5Bn-f%5Bf%5Bn-1%5D%5D%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[f[f[n-1]]]+f[n-f[f[n-1]]]")

One could explore other interesting features of these sequences but we
stop here with the philosophical insight the imparted to us. Simple
two-seeded sequences like the Meru-średhī represent a process that is
directly dependent on the state of the system at two former time points.
Thus they evolve directly as a function of time like the unconstrained
growth of an organism under ideal conditions, which Nārāyaṇa tried to
model. However, the doubly and triply nested generative formulae, while
starting from the same seeds, do not develop directly dependent on time
but rather as a second or third order consequence of states at former
time points. Thus, while the simple case might be seen as a direct
reaction of two former reactants leading to a current product, the
nested specifications can be seen as reactants at former time leading to
further reactants which in turn specify the current product. What we
observer is that by the simple act of including this kind of higher
order specification we get several different kinds of complexity: Some
forms of complexity like the Takagi curve while intricate have a regular
pattern to them. Other forms show different degrees of higher order
pattern but are much more irregular in their immediate behavior. Finally
there are those that are very irregular and not obviously predictable
beyond some general statistical features. Actions on simple strings can
generate complex forms — hence, these sequences could serve as an
analogy for how higher order dependencies naturally generates complex
structure in nature. Such processes could also be behind the patterns of
other systems like human history. A question that leads to a deep
philosophical puzzle is whether such processes might be active in
biological systems.
