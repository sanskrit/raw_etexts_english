+++
title = "Two exceedingly simple sums related to triangularxa0numbers"
date = "2021-05-26"

+++
This note records some elementary arithmetic pertaining to triangular
numbers for bālabodhana. In our youth we found that having a flexible
attitude was good thing while obtaining closed forms for simple sums:
for some sums geometry (using methods of proofs pioneered by Āryabhaṭa
which continued down to Nīlakaṇṭha Somayājin) was the best way to go;
for others algebra was better. The intuition was in choosing the right
approach for a given sum. We illustrate that with two such sums.

**Sum 1** Obtain a closed form for the sum: ![\\displaystyle
\\sum\_{j=1}^{n}
(2j-1)^3](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bj%3D1%7D%5E%7Bn%7D+%282j-1%29%5E3&bg=ffffff&fg=333333&s=0&c=20201002)

These sums define a sequence: **1, 28, 153, 496, 1225…**  
Given that we can mostly only visually operate in 3 spatial dimensions,
our intuition suggested that a cubic sum as this is best tackled with
brute-force algebra with the formulae for individual terms derived by
Āryabhaṭa and his commentators. Thus we have:

![\\displaystyle \\sum\_{j=1}^{n} (2j-1)^3 = \\sum\_{j=1}^{n} 8 j^3 - 12
j^2 + 6 j-
1](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bj%3D1%7D%5E%7Bn%7D+%282j-1%29%5E3+%3D+%5Csum_%7Bj%3D1%7D%5E%7Bn%7D+8+j%5E3+-+12+j%5E2+%2B+6+j-+1&bg=ffffff&fg=333333&s=0&c=20201002)  
![= 2n^2(n+1)^2-2n(n+1)(2n+1)+3n(n+1)-n=
\\dfrac{(2n^2-1)2n^2}{2}](https://s0.wp.com/latex.php?latex=%3D+2n%5E2%28n%2B1%29%5E2-2n%28n%2B1%29%282n%2B1%29%2B3n%28n%2B1%29-n%3D+%5Cdfrac%7B%282n%5E2-1%292n%5E2%7D%7B2%7D&bg=ffffff&fg=333333&s=0&c=20201002)

The reason we wrote out the final solution in this unsimplified form is
to illustrate that the above sums will always be a triangular number of
the form:

![\\displaystyle \\sum\_{j=1}^{2j^2-1}
j](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bj%3D1%7D%5E%7B2j%5E2-1%7D+j&bg=ffffff&fg=333333&s=0&c=20201002),
i.e sums from 1 to **1, 7, 17, 31, 49…** or triangular numbers ![T_1,
T_7, T\_{17},
T\_{31}\\cdots](https://s0.wp.com/latex.php?latex=T_1%2C+T_7%2C+T_%7B17%7D%2C+T_%7B31%7D%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002)

Thus, the
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)th
terms of sequence of sums would be triangular number
![T_m](https://s0.wp.com/latex.php?latex=T_m&bg=ffffff&fg=333333&s=0&c=20201002),
where ![m=2j^2-1, j=1, 2,
3...](https://s0.wp.com/latex.php?latex=m%3D2j%5E2-1%2C+j%3D1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0&c=20201002).
From the above, one can also see that the difference of successive terms
of our original sequence of sums will be **27, 125, 343, 729…**, i.e.,
they are perfect cubes of the form
![(2k+1)^3](https://s0.wp.com/latex.php?latex=%282k%2B1%29%5E3&bg=ffffff&fg=333333&s=0&c=20201002)
(odd numbers 3, 5, 7, 9…). These cubes are thus the interstitial sums of
the indices
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0&c=20201002)
of the triangular numbers
![T_j](https://s0.wp.com/latex.php?latex=T_j&bg=ffffff&fg=333333&s=0&c=20201002)
up to the index
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0&c=20201002)
corresponding to the triangular number
![T_m](https://s0.wp.com/latex.php?latex=T_m&bg=ffffff&fg=333333&s=0&c=20201002)
that is a term of our original sequence. Thus:  
![j\\mapsto](https://s0.wp.com/latex.php?latex=j%5Cmapsto&bg=ffffff&fg=333333&s=0&c=20201002)
**1**, 2, 3, 4, 5, 6, **7**, 8, 9, 10, 11, 12, 13, 14, 15, 16, **17**,
18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, **31**…  
then, 2+3+4…+7=**27**; 8+9+10…+17=**125**; 18+19+20+21+22…+31 =**343**
and so on.

Another interesting feature of the original sequence is its decadal
cycle in the terms of the numbers in the last 2 places (written in
anti-Hindu, i.e. modern order). They will always end in the following
sequence of 10 numbers:  
**0, 1, 28, 53, 6, 25, 6, 53, 28, 1**  
Similarly, the index
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0&c=20201002)
of the triangular numbers
![T_m](https://s0.wp.com/latex.php?latex=T_m&bg=ffffff&fg=333333&s=0&c=20201002)
the define our sequence also shows a pentadic cycle in the last place of
the form:  
**1, 7, 7, 1, 9**

A comparable pattern is seen if we generate a sequence that is the sum
of successive terms of our original sequence: **1, 29, 181, 649, 1721,
3781, 7309, 12881…** The last place has a pentadic cycle of the form:
1,9,1,9,1. The last 2 places has a cycle of length 25: 01, 29, 81, 49,
21, 81, 09, 81, 69, 41, 61, 89, 81, 89, 61, 41, 69, 81, 09, 81, 21, 49,
81, 29, 01. Both are palindromic cycles.

Finally, the sum of the reciprocals of the original sequence converges
to a constant: 1.04607799646… We suspect there is a closed form for this
constant but have not been able to identify it.

**Sum 2** Obtain a closed form for the sum of alternating negative and
positive perfect squares: -1+4-9+16… i.e.

![\\displaystyle \\sum\_{j=1}^n (-1)^j
j^2](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Csum_%7Bj%3D1%7D%5En+%28-1%29%5Ej+j%5E2&bg=ffffff&fg=333333&s=0&c=20201002)

With the sum involving just square terms it is possible to use a
wordless geometric proof along the lines of that proposed by Āryabhaṭa
(Figure 1).

[![Sum_neg_pos_squares](https://manasataramgini.files.wordpress.com/2021/05/sum_neg_pos_squares.png?w=480&h=456)](https://manasataramgini.files.wordpress.com/2021/05/sum_neg_pos_squares.png)

Figure 1.

Thus, we get the above sum as ![-1^n
T_n](https://s0.wp.com/latex.php?latex=-1%5En+T_n&bg=ffffff&fg=333333&s=0&c=20201002),
where
![T_n](https://s0.wp.com/latex.php?latex=T_n&bg=ffffff&fg=333333&s=0&c=20201002)
is the
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)th
triangular number.
