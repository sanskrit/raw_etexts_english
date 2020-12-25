+++
title = "Convergence to a palindrome"

+++
This is a brief account of a sequence we constructed inspired by
Dattatreya Ramachandra Kaprekar. It is not known to us if he had
discovered it in one of his obscure publications from a small town in
the Maharatta country. In any case we explored this sequence
independently upon hearing of some procedures he used in his work.
Consider a number like
![n=100](https://s0.wp.com/latex.php?latex=n%3D100&bg=ffffff&fg=333333&s=0
"n=100"). Its reverse is
![r(n)=1](https://s0.wp.com/latex.php?latex=r%28n%29%3D1&bg=ffffff&fg=333333&s=0
"r(n)=1"). Then,
![n+r(n)=101](https://s0.wp.com/latex.php?latex=n%2Br%28n%29%3D101&bg=ffffff&fg=333333&s=0
"n+r(n)=101"). We find that 101 is a palindrome. Consider another case
![n=155](https://s0.wp.com/latex.php?latex=n%3D155&bg=ffffff&fg=333333&s=0
"n=155"), then
![n+r(n)=155+551=706](https://s0.wp.com/latex.php?latex=n%2Br%28n%29%3D155%2B551%3D706&bg=ffffff&fg=333333&s=0
"n+r(n)=155+551=706"). This is not a palindrome so we continue the same
process ![n+r(n)=706+607=1313 \\rightarrow
n+r(n)=1313+3131=4444](https://s0.wp.com/latex.php?latex=n%2Br%28n%29%3D706%2B607%3D1313+%5Crightarrow+n%2Br%28n%29%3D1313%2B3131%3D4444&bg=ffffff&fg=333333&s=0
"n+r(n)=706+607=1313 \\rightarrow n+r(n)=1313+3131=4444"). Thus, after 3
iterations of the process we have a palindrome. Thus, if we take any
number and perform this operation of adding it to its digital reverse
iteratively till we get a palindrome then our sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f") is
defined as the palindrome to which each number
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
converges. Thus, ![f\[100\]=101;
f\[155\]=4444](https://s0.wp.com/latex.php?latex=f%5B100%5D%3D101%3B+f%5B155%5D%3D4444&bg=ffffff&fg=333333&s=0
"f[100]=101; f[155]=4444"). One question which arose was whether there
are ![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0
"n") that never converge to a palindrome. Between 1:99 all numbers
converge to a palindrome even if a large one. Hence, we explored 100:999
in greater detail. Figure 1 shows a plot of
![f\[100:999\]](https://s0.wp.com/latex.php?latex=f%5B100%3A999%5D&bg=ffffff&fg=333333&s=0
"f[100:999]")

![Palin\_Fig1](https://manasataramgini.files.wordpress.com/2018/04/palin_fig1.png?w=640)Figure
1. y-axis:
![\\log\_{10}(f\[n\])](https://s0.wp.com/latex.php?latex=%5Clog_%7B10%7D%28f%5Bn%5D%29&bg=ffffff&fg=333333&s=0
"\\log_{10}(f[n])")

Of these our experiments suggested that the following 13 numbers in the
range 100:999 never converge to a palindrome (marked by red dots in
Figure 1): 196, 295, 394, 493, 592, 689, 691, 788, 790, 879, 887, 978,
986. One can see that barring 790 all of them come in pairs. The maximum
value attained by
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") in this range is the 13 digit number: 8813200023188. This value
is attained when
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") is
187, 286, 385, 484, 583, 682, 781, 869, 880, 968. Comparable to the
non-converging cases, here all ten cases come as pairs. There is also an
interesting pattern for both the maxima and the non-converging cases: we
observe that in each century it comes one number earlier but at some
point a “new line of descent” emerges which then perpetuates the same
pattern along with the older one. The same maximum value is attained for
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") in
the range 1:99, with ![f\[89\],
f\[98\]=16668488486661](https://s0.wp.com/latex.php?latex=f%5B89%5D%2C+f%5B98%5D%3D16668488486661&bg=ffffff&fg=333333&s=0
"f[89], f[98]=16668488486661").

Omitting the single digit numbers, 11 is the primordial palindromic
number and its multiples often tend to have a palindromic structure. Its
multiples for
![k=1:9](https://s0.wp.com/latex.php?latex=k%3D1%3A9&bg=ffffff&fg=333333&s=0
"k=1:9") are the only double digit palindromes. Multiples of 11 are also
found among the triple digit palindromes: 121, 242, 363, 484, 616, 737,
858, 979. For
![n=1:99](https://s0.wp.com/latex.php?latex=n%3D1%3A99&bg=ffffff&fg=333333&s=0
"n=1:99") all
![n\>4](https://s0.wp.com/latex.php?latex=n%3E4&bg=ffffff&fg=333333&s=0
"n\>4") converge to a palindrome which is a multiple of 11. For
![n=100:999](https://s0.wp.com/latex.php?latex=n%3D100%3A999&bg=ffffff&fg=333333&s=0
"n=100:999"),
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") have 64 unique prime factors ranging from 2 to 18209090957.
Notably, the largest number of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"), 641, are divisible by 11. Thus, the most frequent convergence
even in this range is to a multiple of 11 (Figure 2).

![Palin\_Fig2](https://manasataramgini.files.wordpress.com/2018/04/palin_fig2.png?w=640)Figure
2. The number of
![f\[100:999\]](https://s0.wp.com/latex.php?latex=f%5B100%3A999%5D&bg=ffffff&fg=333333&s=0
"f[100:999]"), which are divisible by a given prime divisor from the set
of all unique prime factors of
![f\[100:999\]](https://s0.wp.com/latex.php?latex=f%5B100%3A999%5D&bg=ffffff&fg=333333&s=0
"f[100:999]").

Figure 2 shows that other than than the first few primes (2, 3, 5, 7
etc) there are some anomalous standout values. Notable among these are
37 which with 3 reaches a palindrome ![3 \\times 37=
111](https://s0.wp.com/latex.php?latex=3+%5Ctimes+37%3D+111&bg=ffffff&fg=333333&s=0
"3 \\times 37= 111") and other palindromic primes, most notably 101 and
131. The convergent might itself be a palindromic prime and for
![f\[100:999\]](https://s0.wp.com/latex.php?latex=f%5B100%3A999%5D&bg=ffffff&fg=333333&s=0
"f[100:999]") we have 101, 727, 929, 181, 383, 787. As can be seen in
Figure 1 (Violet points) the
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
for which these palindromic prime convergents are reached have a
distinctive pattern of distribution reminiscent of the maxima and
non-converging values.

Finally, this sequence is notable for the very large values that are
attained amidst otherwise pedestrian values (Figure 3).

![Palin\_fig3](https://manasataramgini.files.wordpress.com/2018/04/palin_fig3.png?w=640)Figure
3. x-axis in
![\\textrm{arcsinh}(f\[n\])](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Barcsinh%7D%28f%5Bn%5D%29&bg=ffffff&fg=333333&s=0
"\\textrm{arcsinh}(f[n])") scale. Mean of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") is the red line while the median is the blue line

This makes for an interesting distribution where extreme events on the
right end are rare but enormous in magnitude. This is reflected in the
difference of several orders of magnitude between the mean and the
median of
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"). However, at least the actual occurrence of these extreme values
is quite regular (Figure 1).
