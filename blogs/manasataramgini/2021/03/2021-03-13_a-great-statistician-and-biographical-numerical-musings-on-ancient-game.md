+++
title = "A great statistician, and biographical, numerical musings on ancientxa0game"
date = "2021-03-13"

+++
Recently my friend brought it to my attention that C. Radhakrishna Rao
had scored a century. Born in 1920 CE to Doraswamy Nayadu and A.
Laxmikanthamma from the Andhra country, he is one of the great
mathematical thinkers and statisticians of our age. He came from a
high-performing family but even against that background he was clearly
an outlier showing early signs of mathematical genius and extraordinary
memory beyond mathematics. An example of this was seen in his youth in
an award he received for his anatomical knowledge, wherein he displayed
his perfect recall of all bones and structures of the body. He might
have been an outstanding mathematician but the lack of opportunities to
pursue research in India or elsewhere during WW2 led him to going to
ISI, Kolkata and becoming a statistician. By the age 20, he was doing
and publishing his research by himself and eventually was awarded a PhD
for his pioneering statistical work on biometrics at the Cambridge
University with Ronald Fisher as his supervisor. By the age 28, he was a
professor who had authored several works at the frontier of statistics.
Over his 100 years he has been prolific and actively publishing into
this advanced years — an outlier in every sense — a truly rare genetic
configuration.

CR Rao wrote a very accessible book for a lay audience titled
*Statistics and truth: putting chance to work*. This small book provides
a great introduction to the utility and the consequences of well-founded
numerical and probabilistic thinking with examples from diverse
sciences. We found the book particularly attractive because, despite
being a mathematical layman, we stumbled onto the probabilistic view of
existence around the 15th year of our life. Rao’s book then lent proper
shape to our thoughts that had been born from several experiments and
explorations. To us, the probabilistic view is the fructification of an
ancient strand of Hindu thought first articulated in a ṛk from the
pathetic sūkta of Kavaṣa Ailūṣa (RV10.34.8):

tripañcāśaḥ krīḻati vrāta eṣāṃ  
deva iva savitā satyadharmā ।  
ugrasya cin manyave nā namante  
rājā cid ebhyo nama it kṛṇoti ॥

Three times fifty plays the swarm of these,  
like the god Savitṛ of true laws.  
To the fury of even the fierce they bow not ;  
even the king verily makes his bow to them.

The ṛk is referring to the game of chance, apparently one of the
favorite games of the old Ārya-s played with vibhīdaka/vibhītaka nuts.
Rao’s essays inspired us to explore the basic numerical aspects of this
game at the end of junior college (Also the time we were studying the RV
and AV). We present a freshly illustrated version of that here for other
simple-minded folks. The game may be reconstructed thus: A hole was dug
in the ground and 150 nuts were thrown into it. Then the player drew a
handful of those to get out
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)
nuts (probably there were some constraints against cheating by drawing
just 4 nuts that are not entirely clear. A possible alternative
formulation involves casting the 150 nuts towards the hole and only
those
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)
that fell into the hole were considered for the ensuing operation). If
![n\\mod 4 \\equiv
0](https://s0.wp.com/latex.php?latex=n%5Cmod+4+%5Cequiv+0&bg=ffffff&fg=333333&s=0&c=20201002)
then it was a Kṛta (K) or the best result. The next 3 successively lower
ranked results were ![n\\mod 4 \\equiv
3](https://s0.wp.com/latex.php?latex=n%5Cmod+4+%5Cequiv+3&bg=ffffff&fg=333333&s=0&c=20201002),
a Treta (T); ![n\\mod 4 \\equiv
2](https://s0.wp.com/latex.php?latex=n%5Cmod+4+%5Cequiv+2&bg=ffffff&fg=333333&s=0&c=20201002)
a Dvāpara (D); ![n\\mod 4 \\equiv
1](https://s0.wp.com/latex.php?latex=n%5Cmod+4+%5Cequiv+1&bg=ffffff&fg=333333&s=0&c=20201002),
a Kali (L). It is unclear if the results were named for the 4 yuga-s or
vice versa. In our childhood, our grandmother played this game with us
albeit with tamarind seeds she had saved after peeling off the fruit. We
manually worked out the number of different combinations (hence, order
does not matter) formed from the 4 types of results (K, T, D, L) that
can be seen in 1, 2, 3… successive draws: in 1 draw you can have K, T, D
or L ![\\to
4](https://s0.wp.com/latex.php?latex=%5Cto+4&bg=ffffff&fg=333333&s=0&c=20201002)
possible combinations. In 2 draws you can have: KK, KT, KL, KD, TT, TD,
TL, DD, DL or LL ![\\to
10](https://s0.wp.com/latex.php?latex=%5Cto+10&bg=ffffff&fg=333333&s=0&c=20201002)
possible combinations. So on. The sequence of the number of possible
combinations goes as: 4, 10, 20, 35… This gave us an introduction to
some the principles of combinatorics that only later in life we learned
to be governed by the multinomial theorem:  
Kṛta, Treta, Dvāpara, Kali ![\\mapsto
m=4](https://s0.wp.com/latex.php?latex=%5Cmapsto+m%3D4&bg=ffffff&fg=333333&s=0&c=20201002);
![n=1, 2,
3...](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0&c=20201002)
successive draws; hence, the total number of possible combinations in
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)
successive draws is:

![N={{n+m-1} \\choose
{m-1}}](https://s0.wp.com/latex.php?latex=N%3D%7B%7Bn%2Bm-1%7D+%5Cchoose+%7Bm-1%7D%7D&bg=ffffff&fg=333333&s=0&c=20201002)

We wondered about the precise chance of getting a combination in
consecutive set of draws. We finally understood this only upon
apprehending the multinomial theorem. This allowed us to compute say,
the chance of getting 4 kṛta-s in 4 consecutive draws as
![\\tfrac{4!}{4!\\cdot 0! \\cdot 0! \\cdot 0!}\\cdot
\\tfrac{1}{256}=0.00390625](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B4%21%7D%7B4%21%5Ccdot+0%21+%5Ccdot+0%21+%5Ccdot+0%21%7D%5Ccdot+%5Ctfrac%7B1%7D%7B256%7D%3D0.00390625&bg=ffffff&fg=333333&s=0&c=20201002),
which is pretty low. On the other end the chance of get all the 4
results in 4 consecutive draws, i.e. KTDL, is much higher:
![\\tfrac{4!}{1!\\cdot 1! \\cdot 1! \\cdot 1!}\\cdot
\\tfrac{1}{256}=\\tfrac{3}{32}=0.09375](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B4%21%7D%7B1%21%5Ccdot+1%21+%5Ccdot+1%21+%5Ccdot+1%21%7D%5Ccdot+%5Ctfrac%7B1%7D%7B256%7D%3D%5Ctfrac%7B3%7D%7B32%7D%3D0.09375&bg=ffffff&fg=333333&s=0&c=20201002).
Since the vibhīdaka game was for gambling, we can assign the scores from
4 for K to 1 for L and measure ones cumulative gains over multiple
draws. We asked, for example, in 4 successive draws what will be
distribution of scores (Figure 1) — what score will one have the highest
chance of obtaining. We can see that the scores will be distributed
between between 4 (LLLL) to 16 (KKKK). We had intuitively realized in
our childhood that one had the greatest chance of of having the midpoint
score of 10. With the multinomial distribution we could calculate the
precise probability of getting the score 10 as 0.171875. This gave us a
good feel for the multinomial distribution and how we could get a
central tendency in terms of the most probable consequence (score) even
multiple scores had the same number of generating combinations (first vs
second panel).

**[![vibhIdaka_4draws](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_4draws.png?w=634&h=634)](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_4draws.png)Figure
1.** The number of distinct combinations and probabilities of getting a
given score in 4 draws.

Thus, we can reach any integer by the sum of the scores in a certain
number of draws (order does not matter as only the sum matters). The
draws resulting in scores adding to the first few integers are shown in
Table 1.  
Table 1

| Integer | Draws                                                              | Number |
|:--------|:-------------------------------------------------------------------|:-------|
| 1       | L                                                                  | 1      |
| 2       | D, LL                                                              | 2      |
| 3       | T, DL, LLL                                                         | 3      |
| 4       | K, TL, DD, DLL, LLLL                                               | 5      |
| 5       | KL, TD, TLL, DDL, DLLL, LLLLL                                      | 6      |
| 6       | KD, KLL, TT, TDL, TLLL, DDD, DDLL, DLLLL, LLLLLL                   | 9      |
| 7       | KT, KDL, KLLL, TTL, TDD, TDLL, TLLLL, DDDL, DDLLL, DLLLLL, LLLLLLL | 11     |

Inspired by Hofstadter, after some trial and error, we were able to
formulate an alternating recursion formula to obtain this sequence of
the total number of ways of reaching an integer as a sum of integers
from 1..4. We first manually compute the first 4 entries as above. Then
the odd terms are given by the recursion:  
![f\[n\]=f\[n-3\]+f\[n-1\]-f\[n-4\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-3%5D%2Bf%5Bn-1%5D-f%5Bn-4%5D&bg=ffffff&fg=333333&s=0&c=20201002)  
The even terms are given by:  
![f\[n\]=f\[n-3\]+f\[n-1\]-f\[n-4\]+\\left
\\lfloor\\tfrac{n}{4}-1\\right\\rfloor+2](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-3%5D%2Bf%5Bn-1%5D-f%5Bn-4%5D%2B%5Cleft+%5Clfloor%5Ctfrac%7Bn%7D%7B4%7D-1%5Cright%5Crfloor%2B2&bg=ffffff&fg=333333&s=0&c=20201002)  
![\\lfloor x
\\rfloor](https://s0.wp.com/latex.php?latex=%5Clfloor+x+%5Crfloor&bg=ffffff&fg=333333&s=0&c=20201002)
in the floor function or first integer ![\\le
x](https://s0.wp.com/latex.php?latex=%5Cle+x&bg=ffffff&fg=333333&s=0&c=20201002)  
Thus, we have ![\\mathbf{f: 1, 2, 3, 5, 6, 9, 11, 15, 18, 23, 27, 34,
39, 47, 54, 64, 72, 84, 94, 108
\\cdots}](https://s0.wp.com/latex.php?latex=%5Cmathbf%7Bf%3A+1%2C+2%2C+3%2C+5%2C+6%2C+9%2C+11%2C+15%2C+18%2C+23%2C+27%2C+34%2C+39%2C+47%2C+54%2C+64%2C+72%2C+84%2C+94%2C+108+%5Ccdots%7D&bg=ffffff&fg=333333&s=0&c=20201002)

We also devised an alternative algorithm that is well suited for a
computer to extract this sequence. This algorithm revealed a close
relationship between this sequence and geometry of triangles.
Effectively, the above sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0&c=20201002)
gives the total number of integer triangles that have perimeter ![P \\le
n](https://s0.wp.com/latex.php?latex=P+%5Cle+n&bg=ffffff&fg=333333&s=0&c=20201002)
for ![n \\in 4, 5, 6
\\cdots](https://s0.wp.com/latex.php?latex=n+%5Cin+4%2C+5%2C+6+%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002).
Thus, for
![n=4](https://s0.wp.com/latex.php?latex=n%3D4&bg=ffffff&fg=333333&s=0&c=20201002)
we can have only 1 integer triangle,
![1-1-1](https://s0.wp.com/latex.php?latex=1-1-1&bg=ffffff&fg=333333&s=0&c=20201002),
that has ![P \\le
4](https://s0.wp.com/latex.php?latex=P+%5Cle+4&bg=ffffff&fg=333333&s=0&c=20201002).
For ![P \\le
5](https://s0.wp.com/latex.php?latex=P+%5Cle+5&bg=ffffff&fg=333333&s=0&c=20201002)
we have 2 triangles ![(1-1-1,
1-2-2)](https://s0.wp.com/latex.php?latex=%281-1-1%2C+1-2-2%29&bg=ffffff&fg=333333&s=0&c=20201002)
and so on (Figure 1, Table 2). Since the smallest integer triangle has
![P=3](https://s0.wp.com/latex.php?latex=P%3D3&bg=ffffff&fg=333333&s=0&c=20201002)
we can get the 0th term of
![f\[0\]=1](https://s0.wp.com/latex.php?latex=f%5B0%5D%3D1&bg=ffffff&fg=333333&s=0&c=20201002).
Then we can state that
![f\[P-3\]](https://s0.wp.com/latex.php?latex=f%5BP-3%5D&bg=ffffff&fg=333333&s=0&c=20201002)
provides the number of integer triangles with ![P \\le n; n=3, 4, 5
\\cdots
\\infty](https://s0.wp.com/latex.php?latex=P+%5Cle+n%3B+n%3D3%2C+4%2C+5+%5Ccdots+%5Cinfty&bg=ffffff&fg=333333&s=0&c=20201002).

**[![vibhIdaka_tri01](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_tri01.png?w=640)](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_tri01.png)Figure
2.** First 18 integer triangles

Figure 1 shows the first 18 integer triangles, i.e. those with ![P \\le
12](https://s0.wp.com/latex.php?latex=P+%5Cle+12&bg=ffffff&fg=333333&s=0&c=20201002).
One immediately notices that in this set the isosceles triangles
dominate (Table 2). Of these every
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0&c=20201002)
divisible by 3 will yield one equilateral triangle; thus equilateral
triangles are the most common repeating type of triangle. There are only
3 scalene triangles in the first 18 integer triangles of which one is
the famous
![3-4-5](https://s0.wp.com/latex.php?latex=3-4-5&bg=ffffff&fg=333333&s=0&c=20201002)
right triangle, which is also the first Brahmagupta triangle (integer
triangles with successive sides differing by 1 and integer area). We
first computed the the number of triangles with ![P \\le
n](https://s0.wp.com/latex.php?latex=P+%5Cle+n&bg=ffffff&fg=333333&s=0&c=20201002)
that are isosceles. This sequence goes as:

![\\mathbf{f_i: 1, 1, 2, 3, 5, 6, 8, 10, 13, 15, 18, 21, 25, 28, 32, 36,
41, 45, 50, 55, 61, 66, 72, 78
\\cdots}](https://s0.wp.com/latex.php?latex=%5Cmathbf%7Bf_i%3A+1%2C+1%2C+2%2C+3%2C+5%2C+6%2C+8%2C+10%2C+13%2C+15%2C+18%2C+21%2C+25%2C+28%2C+32%2C+36%2C+41%2C+45%2C+50%2C+55%2C+61%2C+66%2C+72%2C+78+%5Ccdots%7D&bg=ffffff&fg=333333&s=0&c=20201002)

Strikingly, every alternate term in this sequence from the second term
onward is a triangular number, i.e. the sum of integers from ![1\\cdots
n](https://s0.wp.com/latex.php?latex=1%5Ccdots+n&bg=ffffff&fg=333333&s=0&c=20201002).
The terms between them are the integer midpoints between successive
triangular numbers. This understanding helps us derive a formula for
this sequence:

![f\[n\]=\\left \\lceil \\frac{n^2}{8}
\\right\\rfloor](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D%5Cleft+%5Clceil+%5Cfrac%7Bn%5E2%7D%7B8%7D+%5Cright%5Crfloor&bg=ffffff&fg=333333&s=0&c=20201002)

Here the ![\\left \\lceil x
\\right\\rfloor](https://s0.wp.com/latex.php?latex=%5Cleft+%5Clceil+x+%5Cright%5Crfloor&bg=ffffff&fg=333333&s=0&c=20201002)
function is the rounding up function, wherein if
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0&c=20201002)
is an integer ![\\left \\lceil k+ \\tfrac{1}{2} \\right\\rfloor
=k+1](https://s0.wp.com/latex.php?latex=%5Cleft+%5Clceil+k%2B+%5Ctfrac%7B1%7D%7B2%7D+%5Cright%5Crfloor+%3Dk%2B1&bg=ffffff&fg=333333&s=0&c=20201002)
and the rest are rounded to the nearest integer.  
Table 2

| P ≤ n | # triangles | # isosceles | # scalene |
|------:|------------:|------------:|----------:|
|     3 |           1 |           1 |         0 |
|     4 |           1 |           1 |         0 |
|     5 |           2 |           2 |         0 |
|     6 |           3 |           3 |         0 |
|     7 |           5 |           5 |         0 |
|     8 |           6 |           6 |         0 |
|     9 |           9 |           8 |         1 |
|    10 |          11 |          10 |         1 |
|    11 |          15 |          13 |         2 |
|    12 |          18 |          15 |         3 |
|    13 |          23 |          18 |         5 |
|    14 |          27 |          21 |         6 |
|    15 |          34 |          25 |         9 |
|    16 |          39 |          28 |        11 |
|    17 |          47 |          32 |        15 |
|    18 |          54 |          36 |        18 |
|    19 |          64 |          41 |        23 |
|    20 |          72 |          45 |        27 |
|    21 |          84 |          50 |        34 |
|    22 |          94 |          55 |        39 |
|    23 |         108 |          61 |        47 |
|    24 |         120 |          66 |        54 |
|    25 |         136 |          72 |        64 |
|    26 |         150 |          78 |        72 |
|    27 |         169 |          85 |        84 |
|    28 |         185 |          91 |        94 |
|    29 |         206 |          98 |       108 |
|    30 |         225 |         105 |       120 |
|    31 |         249 |         113 |       136 |
|    32 |         270 |         120 |       150 |
|    33 |         297 |         128 |       169 |
|    34 |         321 |         136 |       185 |

Remarkably, we find that the first scalene triangle appears at
![P=9](https://s0.wp.com/latex.php?latex=P%3D9&bg=ffffff&fg=333333&s=0&c=20201002)
and then scales exactly as
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0&c=20201002)
but with an offset of 9. Thus, the number of scalene triangle with ![P
\\le n=
f\[P-9\]](https://s0.wp.com/latex.php?latex=P+%5Cle+n%3D+f%5BP-9%5D&bg=ffffff&fg=333333&s=0&c=20201002).
The sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0&c=20201002)
scales approximately as a polynomial with positive cubic and square
terms, whereas the number of isosceles triangles with ![P \\le
n](https://s0.wp.com/latex.php?latex=P+%5Cle+n&bg=ffffff&fg=333333&s=0&c=20201002)
scales as ![\\left \\lceil \\tfrac{n^2}{8}
\\right\\rfloor](https://s0.wp.com/latex.php?latex=%5Cleft+%5Clceil+%5Ctfrac%7Bn%5E2%7D%7B8%7D+%5Cright%5Crfloor&bg=ffffff&fg=333333&s=0&c=20201002).
Hence, even though the isosceles triangles are dominant at low
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0&c=20201002)
they will become increasingly rare (Table 2) and their fraction of the
total number of triangles will tend to 0.

We can also look at the largest angle of the integer triangles (Figure
2). These are plotted along the arc of the unit circle defined by them
and scaled and colored as per their frequency of occurrence. As noted
above, every third perimeter will define an equilateral triangle. This
will result in the smallest of these angles
![\\arccos\\left(\\tfrac{1}{2}\\right) =
60^\\circ](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B2%7D%5Cright%29+%3D+60%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
being the most common. The zone exclusion in its vicinity shows that one
needs large sides to approximate the equilateral triangles (e.g. the
bigger Brahmagupta triangles). Beyond these, other major angles that are
repeatedly observed are: ![\\arccos\\left(\\tfrac{1}{4}\\right) =
75.52^\\circ](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B4%7D%5Cright%29+%3D+75.52%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002);
![\\arccos\\left(\\tfrac{1}{6}\\right)
=80.406^\\circ](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B6%7D%5Cright%29+%3D80.406%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002);
![\\arccos\\left(\\tfrac{1}{8}\\right) =
82.83^\\circ](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B8%7D%5Cright%29+%3D+82.83%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002);
![\\arccos\\left(\\tfrac{1}{3}\\right) =
70.53^\\circ](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B3%7D%5Cright%29+%3D+70.53%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002).
For example, the common version of the
![\\arccos\\left(\\tfrac{1}{4}\\right)](https://s0.wp.com/latex.php?latex=%5Carccos%5Cleft%28%5Ctfrac%7B1%7D%7B4%7D%5Cright%29&bg=ffffff&fg=333333&s=0&c=20201002)
triangle arises whenever the perimeter ![P= 5k; k=1,2,3
\\cdots](https://s0.wp.com/latex.php?latex=P%3D+5k%3B+k%3D1%2C2%2C3+%5Ccdots&bg=ffffff&fg=333333&s=0&c=20201002).
Thus, these are all versions of the
![1-2-2](https://s0.wp.com/latex.php?latex=1-2-2&bg=ffffff&fg=333333&s=0&c=20201002)
triangle. However, rare scalene versions can arise, for example, in the
form of the
![6-7-8](https://s0.wp.com/latex.php?latex=6-7-8&bg=ffffff&fg=333333&s=0&c=20201002)
triangle and its higher homologs. Apart from the trivial equilateral
triangles, 2 other integer rational sector triangles, the right or
![90^\\circ](https://s0.wp.com/latex.php?latex=90%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
(bhujā-koṭi-karṇa triples) and the
![120^\\circ](https://s0.wp.com/latex.php?latex=120%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
triangles (e.g. ![3-5-7,
P=15](https://s0.wp.com/latex.php?latex=3-5-7%2C+P%3D15&bg=ffffff&fg=333333&s=0&c=20201002))
appear repeatedly with a lower frequency defined by their
[triple-generating
equations](https://manasataramgini.wordpress.com/2019/12/01/some-notes-on-rational-sector-triangle-triples/).

**![vibhIdaka_cos01](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_cos01.png?w=640)Figure
3.** The plots of the largest angles for integer triangles with ![P \\le
34](https://s0.wp.com/latex.php?latex=P+%5Cle+34&bg=ffffff&fg=333333&s=0&c=20201002)

Finally, this search of integer triangles also provides a mean to
construct triangles, one of whose angles are approximately a radian
(Figure 3). In first 511 triangles, ![(P\\le
40)](https://s0.wp.com/latex.php?latex=%28P%5Cle+40%29&bg=ffffff&fg=333333&s=0&c=20201002),
the
![5-13-15](https://s0.wp.com/latex.php?latex=5-13-15&bg=ffffff&fg=333333&s=0&c=20201002)
triangle provides an angle that approaches 1 radian the closest:
![1.0003^c](https://s0.wp.com/latex.php?latex=1.0003%5Ec&bg=ffffff&fg=333333&s=0&c=20201002).

**[![vibhIdaka_tri02](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_tri02.png?w=637&h=584)](https://manasataramgini.files.wordpress.com/2021/03/vibhidaka_tri02.png)Figure
4.** Triangles with an angle approximating a radian.

The above observations gave us useful introductory lesson on the path to
statistical mechanics. Let us consider the isosceles triangles as
representing great order (because the is less freedom in their sides)
and the scalene triangles as representing greater disorder (more freedom
in their sides). A simple multinomial derived score results in the
proportion of the order configurations decreasing over time (more
draws), i.e. disorder dominates, resembling entropy in the physical
world. Among the more “ordered” states the dominant one tends to be that
which is in the most “central” configuration, i.e. the equilateral
triangle. Finally, certain peculiar configurations can repeatedly emerge
if they happen to have special [generating
equations](https://manasataramgini.wordpress.com/2019/12/01/some-notes-on-rational-sector-triangle-triples/)
like the
![90^\\circ](https://s0.wp.com/latex.php?latex=90%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
or
![120^\\circ](https://s0.wp.com/latex.php?latex=120%5E%5Ccirc&bg=ffffff&fg=333333&s=0&c=20201002)
triangles.
