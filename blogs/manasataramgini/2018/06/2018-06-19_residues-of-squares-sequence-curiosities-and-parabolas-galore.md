+++
title = "Residues of squares, sequence curiosities and parabolas galore"

+++
**Squares and their residues**  
This is an exploration of number triangles in the same vein as some
other such we have previously described . It resulted in some
observations that seemed interesting to us. Some are perhaps trivial but
some seem puzzling to us probably on account of our very meager
mathematics.

Consider the triangle of squares
![T\_s](https://s0.wp.com/latex.php?latex=T_s&bg=ffffff&fg=333333&s=0
"T_s"). The
![j^{th}](https://s0.wp.com/latex.php?latex=j%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"j^{th}") row of
![T\_s](https://s0.wp.com/latex.php?latex=T_s&bg=ffffff&fg=333333&s=0
"T_s") is comprised of squares of all integers
![1:j](https://s0.wp.com/latex.php?latex=1%3Aj&bg=ffffff&fg=333333&s=0
"1:j"); illustrated below is the tip of this triangle.

![\\begin{tabular}{|\*{15}{r|}} \\cline{1-1} 1 \\\\ \\cline{1-2} 1 & 4
\\\\ \\cline{1-3} 1 & 4 & 9 \\\\ \\cline{1-4} 1 & 4 & 9 & 16 \\\\
\\cline{1-5} 1 & 4 & 9 & 16 & 25 \\\\ \\cline{1-6} 1 & 4 & 9 & 16 & 25 &
36 \\\\ \\cline{1-7} 1 & 4 & 9 & 16 & 25 & 36 & 49 \\\\ \\cline{1-8} 1 &
4 & 9 & 16 & 25 & 36 & 49 & 64\\\\ \\cline{1-9} 1 & 4 & 9 & 16 & 25 & 36
& 49 & 64 & 81 \\\\ \\cline{1-10} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 &
81 & 100 \\\\ \\cline{1-11} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 &
100 & 121 \\\\ \\cline{1-12} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 &
100 & 121 & 144 \\\\ \\cline{1-13} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 &
81 & 100 & 121 & 144 & 169 \\\\ \\cline{1-14} 1 & 4 & 9 & 16 & 25 & 36 &
49 & 64 & 81 & 100 & 121 & 144 & 169 & 196 \\\\ \\cline{1-15} 1 & 4 & 9
& 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 & 144 & 169 & 196 & 225 \\\\
\\cline{1-15}
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7C%2A%7B15%7D%7Br%7C%7D%7D+%5Ccline%7B1-1%7D+1+%5C%5C+%5Ccline%7B1-2%7D+1+%26+4+%5C%5C+%5Ccline%7B1-3%7D+1+%26+4+%26+9+%5C%5C+%5Ccline%7B1-4%7D+1+%26+4+%26+9+%26+16+%5C%5C+%5Ccline%7B1-5%7D+1+%26+4+%26+9+%26+16+%26+25+%5C%5C+%5Ccline%7B1-6%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%5C%5C+%5Ccline%7B1-7%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%5C%5C+%5Ccline%7B1-8%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64%5C%5C+%5Ccline%7B1-9%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%5C%5C+%5Ccline%7B1-10%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%5C%5C+%5Ccline%7B1-11%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%26+121+%5C%5C+%5Ccline%7B1-12%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%26+121+%26+144+%5C%5C+%5Ccline%7B1-13%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%26+121+%26+144+%26+169+%5C%5C+%5Ccline%7B1-14%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%26+121+%26+144+%26+169+%26+196+%5C%5C+%5Ccline%7B1-15%7D+1+%26+4+%26+9+%26+16+%26+25+%26+36+%26+49+%26+64+%26+81+%26+100+%26+121+%26+144+%26+169+%26+196+%26+225+%5C%5C+%5Ccline%7B1-15%7D+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|*{15}{r|}} \\cline{1-1} 1 \\\\ \\cline{1-2} 1 & 4 \\\\ \\cline{1-3} 1 & 4 & 9 \\\\ \\cline{1-4} 1 & 4 & 9 & 16 \\\\ \\cline{1-5} 1 & 4 & 9 & 16 & 25 \\\\ \\cline{1-6} 1 & 4 & 9 & 16 & 25 & 36 \\\\ \\cline{1-7} 1 & 4 & 9 & 16 & 25 & 36 & 49 \\\\ \\cline{1-8} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64\\\\ \\cline{1-9} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 \\\\ \\cline{1-10} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 \\\\ \\cline{1-11} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 \\\\ \\cline{1-12} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 & 144 \\\\ \\cline{1-13} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 & 144 & 169 \\\\ \\cline{1-14} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 & 144 & 169 & 196 \\\\ \\cline{1-15} 1 & 4 & 9 & 16 & 25 & 36 & 49 & 64 & 81 & 100 & 121 & 144 & 169 & 196 & 225 \\\\ \\cline{1-15} \\end{tabular}")

We then obtain the square residue triangle
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") from it by following operation, ![T\_{sr}\[j,k\]=
T\_{s}\[j,k\] \\mod
j](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D%5Bj%2Ck%5D%3D+T_%7Bs%7D%5Bj%2Ck%5D+%5Cmod+j&bg=ffffff&fg=333333&s=0
"T_{sr}[j,k]= T_{s}[j,k] \\mod j"). The first 15 rows of this triangle
are shown below.

![\\begin{tabular}{|\*{15}{r|}} \\cline{1-1} 0 \\\\ \\cline{1-2} 1 & 0
\\\\ \\cline{1-3} 1 & 1 & 0 \\\\ \\cline{1-4} 1 & 0 & 1 & 0 \\\\
\\cline{1-5} 1 & 4 & 4 & 1 & 0 \\\\ \\cline{1-6} 1 & 4 & 3 & 4 & 1 & 0
\\\\ \\cline{1-7} 1 & 4 & 2 & 2 & 4 & 1 & 0 \\\\ \\cline{1-8} 1 & 4 & 1
& 0 & 1 & 4 & 1 & 0 \\\\ \\cline{1-9} 1 & 4 & 0 & 7 & 7 & 0 & 4 & 1 & 0
\\\\ \\cline{1-10} 1 & 4 & 9 & 6 & 5 & 6 & 9 & 4 & 1 & 0 \\\\
\\cline{1-11} 1 & 4 & 9 & 5 & 3 & 3 & 5 & 9 & 4 & 1 & 0 \\\\
\\cline{1-12} 1 & 4 & 9 & 4 & 1 & 0 & 1 & 4 & 9 & 4 & 1 & 0 \\\\
\\cline{1-13} 1 & 4 & 9 & 3 & 12 & 10 & 10 & 12 & 3 & 9 & 4 & 1 & 0 \\\\
\\cline{1-14} 1 & 4 & 9 & 2 & 11 & 8 & 7 & 8 & 11 & 2 & 9 & 4 & 1 & 0
\\\\ \\cline{1-15} 1 & 4 & 9 & 1 & 10 & 6 & 4 & 4 & 6 & 10 & 1 & 9 & 4 &
1 & 0 \\\\ \\cline{1-15}
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7C%2A%7B15%7D%7Br%7C%7D%7D+%5Ccline%7B1-1%7D+0+%5C%5C+%5Ccline%7B1-2%7D+1+%26+0+%5C%5C+%5Ccline%7B1-3%7D+1+%26+1+%26+0+%5C%5C+%5Ccline%7B1-4%7D+1+%26+0+%26+1+%26+0+%5C%5C+%5Ccline%7B1-5%7D+1+%26+4+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-6%7D+1+%26+4+%26+3+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-7%7D+1+%26+4+%26+2+%26+2+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-8%7D+1+%26+4+%26+1+%26+0+%26+1+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-9%7D+1+%26+4+%26+0+%26+7+%26+7+%26+0+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-10%7D+1+%26+4+%26+9+%26+6+%26+5+%26+6+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-11%7D+1+%26+4+%26+9+%26+5+%26+3+%26+3+%26+5+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-12%7D+1+%26+4+%26+9+%26+4+%26+1+%26+0+%26+1+%26+4+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-13%7D+1+%26+4+%26+9+%26+3+%26+12+%26+10+%26+10+%26+12+%26+3+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-14%7D+1+%26+4+%26+9+%26+2+%26+11+%26+8+%26+7+%26+8+%26+11+%26+2+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-15%7D+1+%26+4+%26+9+%26+1+%26+10+%26+6+%26+4+%26+4+%26+6+%26+10+%26+1+%26+9+%26+4+%26+1+%26+0+%5C%5C+%5Ccline%7B1-15%7D+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|*{15}{r|}} \\cline{1-1} 0 \\\\ \\cline{1-2} 1 & 0 \\\\ \\cline{1-3} 1 & 1 & 0 \\\\ \\cline{1-4} 1 & 0 & 1 & 0 \\\\ \\cline{1-5} 1 & 4 & 4 & 1 & 0 \\\\ \\cline{1-6} 1 & 4 & 3 & 4 & 1 & 0 \\\\ \\cline{1-7} 1 & 4 & 2 & 2 & 4 & 1 & 0 \\\\ \\cline{1-8} 1 & 4 & 1 & 0 & 1 & 4 & 1 & 0 \\\\ \\cline{1-9} 1 & 4 & 0 & 7 & 7 & 0 & 4 & 1 & 0 \\\\ \\cline{1-10} 1 & 4 & 9 & 6 & 5 & 6 & 9 & 4 & 1 & 0 \\\\ \\cline{1-11} 1 & 4 & 9 & 5 & 3 & 3 & 5 & 9 & 4 & 1 & 0 \\\\ \\cline{1-12} 1 & 4 & 9 & 4 & 1 & 0 & 1 & 4 & 9 & 4 & 1 & 0 \\\\ \\cline{1-13} 1 & 4 & 9 & 3 & 12 & 10 & 10 & 12 & 3 & 9 & 4 & 1 & 0 \\\\ \\cline{1-14} 1 & 4 & 9 & 2 & 11 & 8 & 7 & 8 & 11 & 2 & 9 & 4 & 1 & 0 \\\\ \\cline{1-15} 1 & 4 & 9 & 1 & 10 & 6 & 4 & 4 & 6 & 10 & 1 & 9 & 4 & 1 & 0 \\\\ \\cline{1-15} \\end{tabular}")

**The rows of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}")**  
If we look at each row of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"), we see a mirror symmetry upon excluding the last term which
is always 0. Leaving out the final 0, the first and the last
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
elements of the
![j^{th}](https://s0.wp.com/latex.php?latex=j%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"j^{th}") row are the squares
![1^2:n^2\<j](https://s0.wp.com/latex.php?latex=1%5E2%3An%5E2%3Cj&bg=ffffff&fg=333333&s=0
"1^2:n^2\<j"). Thus, the same squares
![1^2:n^2](https://s0.wp.com/latex.php?latex=1%5E2%3An%5E2&bg=ffffff&fg=333333&s=0
"1^2:n^2") are found at the beginning of each row from
![j=n^2+1](https://s0.wp.com/latex.php?latex=j%3Dn%5E2%2B1&bg=ffffff&fg=333333&s=0
"j=n^2+1") to
![j=(n+1)^2](https://s0.wp.com/latex.php?latex=j%3D%28n%2B1%29%5E2&bg=ffffff&fg=333333&s=0
"j=(n+1)^2"). After that a new square
![(n+1)^2](https://s0.wp.com/latex.php?latex=%28n%2B1%29%5E2&bg=ffffff&fg=333333&s=0
"(n+1)^2") gets added to this run of squares at the beginning and end of
the row. The reason for this is rather obvious: All
![1^2:n^2\<j](https://s0.wp.com/latex.php?latex=1%5E2%3An%5E2%3Cj&bg=ffffff&fg=333333&s=0
"1^2:n^2\<j") will leave themselves behind as residues of the modulo
operation with
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0 "j").
![j^2](https://s0.wp.com/latex.php?latex=j%5E2&bg=ffffff&fg=333333&s=0
"j^2") will result in a residue in the form of the terminal 0 of that
row. Then ![(j-1)^2, (j-2)^2 ...
(j-n)^2](https://s0.wp.com/latex.php?latex=%28j-1%29%5E2%2C+%28j-2%29%5E2+...+%28j-n%29%5E2&bg=ffffff&fg=333333&s=0
"(j-1)^2, (j-2)^2 ... (j-n)^2") for
![n^2\<j](https://s0.wp.com/latex.php?latex=n%5E2%3Cj&bg=ffffff&fg=333333&s=0
"n^2\<j") will leave residues
![n^2:1^2](https://s0.wp.com/latex.php?latex=n%5E2%3A1%5E2&bg=ffffff&fg=333333&s=0
"n^2:1^2"), i.e., in the reverse order as the starting run. The middle
part of each row between these square terms may or may not be square
terms but will also symmetrically expand. The pattern of residues is
unique for each row of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") but the basic symmetry of the parabolic ascent and descent is
common to all. This is illustrated in Figure 1

[![square\_mod\_Fig1](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig1.png)*Figure
1. Figure 1 shows 9 different rows of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"). The first row —
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0 "j")
divisible by 4; second row — other numbers; third row — primes. The
successive values are alternately colored blue and red.*

We observe that for
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0 "j")
divisible by 4 we get a supersymmetry, wherein each symmetric half of
the row is further symmetric (Figure 1, row 1). All other
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0 "j")
show a pseudo-supersymmetry (Figure 1, rows 2 and 3). All
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0 "j")
also display a central parabolic region but its particular form varies
from number to number.

**The columns of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}")**  
Now, if we look at
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") vertically, every column
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
starts with a 0. It eventually terminates in a continuous run of square
terms with the value
![k^2](https://s0.wp.com/latex.php?latex=k%5E2&bg=ffffff&fg=333333&s=0
"k^2"). Thus, the first column terminates in a continuous run of 1s, the
second column in a run of 4s, the third in a run of 9s, so on. In a
given column, between the starting 0 and the first
![k^2](https://s0.wp.com/latex.php?latex=k%5E2&bg=ffffff&fg=333333&s=0
"k^2") term we observe several notable patterns:  
1\) Immediately after the starting 0 there is an ascending sequence of
square terms. This becomes apparent from the second column, i.e.
![k=2](https://s0.wp.com/latex.php?latex=k%3D2&bg=ffffff&fg=333333&s=0
"k=2") onwards, where after 0 we get a 1. For
![k=3](https://s0.wp.com/latex.php?latex=k%3D3&bg=ffffff&fg=333333&s=0
"k=3"), the sequence is 1, 4 — a new square term 4 is seen. 1,4 then
continues as the initial ascending sequence of square terms till
![k=6](https://s0.wp.com/latex.php?latex=k%3D6&bg=ffffff&fg=333333&s=0
"k=6"). At
![k=7](https://s0.wp.com/latex.php?latex=k%3D7&bg=ffffff&fg=333333&s=0
"k=7"), we get a new square term 9; thus yielding the ascending sequence
of square terms 1, 4, 9, which continues till
![k=12](https://s0.wp.com/latex.php?latex=k%3D12&bg=ffffff&fg=333333&s=0
"k=12"). At
![k=13](https://s0.wp.com/latex.php?latex=k%3D13&bg=ffffff&fg=333333&s=0
"k=13"), we get next square term 16, yielding the ascending sequence of
square terms 1, 4, 9, 16. Thus, we derived the general formula for the
number of terms
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") in
this ascending run of square terms as:  
![n=\\textrm{round}(\\sqrt{k})](https://s0.wp.com/latex.php?latex=n%3D%5Ctextrm%7Bround%7D%28%5Csqrt%7Bk%7D%29&bg=ffffff&fg=333333&s=0
"n=\\textrm{round}(\\sqrt{k})"); with the sequence of square terms being
1, 4, 9…
![\\left(\\textrm{round}(\\sqrt{k})\\right)^2](https://s0.wp.com/latex.php?latex=%5Cleft%28%5Ctextrm%7Bround%7D%28%5Csqrt%7Bk%7D%29%5Cright%29%5E2&bg=ffffff&fg=333333&s=0
"\\left(\\textrm{round}(\\sqrt{k})\\right)^2")  
Thus, the new square term gets added when
![k=n^2-n+1](https://s0.wp.com/latex.php?latex=k%3Dn%5E2-n%2B1&bg=ffffff&fg=333333&s=0
"k=n^2-n+1"), i.e. at 1, 3, 7, 13, 21, 31, 43, 57, 73, 91… (see below
for more on this sequence)

2\) The next pattern is more complicated. Starting from the largest and
last square term of the initial ascending run of square terms of the
column ![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0
"k") (described above), we start seeing a series of descending runs,
until we hit a terminal 0, which precedes the concluding continuous
sequence of square terms
![k^2](https://s0.wp.com/latex.php?latex=k%5E2&bg=ffffff&fg=333333&s=0
"k^2"). To understand this let us examine the column
![k=7](https://s0.wp.com/latex.php?latex=k%3D7&bg=ffffff&fg=333333&s=0
"k=7") of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"). Below are its first 46 terms:  
0, 1, 4, 9, 5, 1, 10, 7, 4, 1, 15, 13, 11, 9, 7, 5, 3, 1, 24, 23, 22,
21, 20, 19, 18, 17, 16, 15, 14, 13, 12, 11, 10, 9, 8, 7, 6, 5, 4, 3, 2,
1, 0, 49, 49, 49  
The first term is the starting 0. Terms 2, 3 and 4 are the 3 ascending
square terms 1, 4, 9. Terms 44:46 are the first 3 of the terminal
continuous run of square terms
![k^2=49](https://s0.wp.com/latex.php?latex=k%5E2%3D49&bg=ffffff&fg=333333&s=0
"k^2=49"). In between are the descending runs that are under
consideration. From term 4 which is 9 we descend to 5 and then to 1
(terms 5 and 6 of above sequence); this is a descent by 4. Then we have
10, 7, 4, 1, which is a descent by 3. Then we have 11, 9, 7, 5, 3, 1,
which is a descent by 2. Then we have 24, 23, 22, 21, 20, 19, 18, 17,
16, 15, 14, 13, 12, 11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0, which is a
descent by 1. For all columns we have a descent by 1. For higher
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") we
see the addition of new runs of descent by 2, 3, 4 ,so on. Thus, for
column
![k=7](https://s0.wp.com/latex.php?latex=k%3D7&bg=ffffff&fg=333333&s=0
"k=7"), we have descents by 4, 3, 2, 1.

3\) We notice that in
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"), for a column
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k"),
these descents by 1, 2, 3… begin with a certain number that keeps
increasing. The descents by each number continue till they hit 0 or the
positive integer nearest to 0, which can be attained via such a descent.
Thus, the descent by 1 sequence will always terminate in a 0. However,
as we saw above, for
![k=7](https://s0.wp.com/latex.php?latex=k%3D7&bg=ffffff&fg=333333&s=0
"k=7"), the descent by 2 starts with 11; so the integer nearest to 0
that the run can reach is 1. Now if we look at the descent by 1
sequence, the first column,
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1"), has just 0 before the continuous run of 1s; so we can take the
start of the descent by 1 as 0. For
![k=2](https://s0.wp.com/latex.php?latex=k%3D2&bg=ffffff&fg=333333&s=0
"k=2") the descent by 1 begins with 1; for
![k=3](https://s0.wp.com/latex.php?latex=k%3D3&bg=ffffff&fg=333333&s=0
"k=3") it begins with 4; for
![k=4](https://s0.wp.com/latex.php?latex=k%3D4&bg=ffffff&fg=333333&s=0
"k=4") it begins with 7; for
![k=5](https://s0.wp.com/latex.php?latex=k%3D5&bg=ffffff&fg=333333&s=0
"k=5") it begins with 12. Similarly, we can identify the starting
integers with which the descent by 2, 3, 4… begin for successive columns
of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"). This is shown in table 1.

![\\begin{tabular}{|l|r|r|r|r|r|r|r|r|r|} \\hline k \\textbackslash d &
1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 \\\\ \\hline 1 & 0 & & & & & & & &
\\\\ 2 & 1 & 0 & & & & & & & \\\\ 3 & 4 & 1 & 0 & & & & & & \\\\ 4 & 7 &
4 & 1 & & & & & & \\\\ 5 & 12 & 7 & 4 & & & & & & \\\\ 6 & 17 & 10 & 6 &
4 & & & & & \\\\ 7 & 24 & 15 & 10 & 9 & & & & & \\\\ 8 & 31 & 20 & 13 &
12 & 9 & & & & \\\\ 9 & 40 & 25 & 18 & 13 & 11 & 9 & & & \\\\ 10 & 49 &
32 & 22 & 16 & 15 & 10 & 9 & & \\\\ 11 & 60 & 39 & 28 & 21 & 16 & 13 & 9
& 9 & \\\\ 12 & 71 & 46 & 33 & 28 & 19 & 18 & 11 & 8 & 9 \\\\ \\hline
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7Cl%7Cr%7Cr%7Cr%7Cr%7Cr%7Cr%7Cr%7Cr%7Cr%7C%7D+%5Chline+k+%5Ctextbackslash+d+%26+1+%26+2+%26+3+%26+4+%26+5+%26+6+%26+7+%26+8+%26+9+%5C%5C+%5Chline+1+%26+0+%26+%26+%26+%26+%26+%26+%26+%26+%5C%5C+2+%26+1+%26+0+%26+%26+%26+%26+%26+%26+%26+%5C%5C+3+%26+4+%26+1+%26+0+%26+%26+%26+%26+%26+%26+%5C%5C+4+%26+7+%26+4+%26+1+%26+%26+%26+%26+%26+%26+%5C%5C+5+%26+12+%26+7+%26+4+%26+%26+%26+%26+%26+%26+%5C%5C+6+%26+17+%26+10+%26+6+%26+4+%26+%26+%26+%26+%26+%5C%5C+7+%26+24+%26+15+%26+10+%26+9+%26+%26+%26+%26+%26+%5C%5C+8+%26+31+%26+20+%26+13+%26+12+%26+9+%26+%26+%26+%26+%5C%5C+9+%26+40+%26+25+%26+18+%26+13+%26+11+%26+9+%26+%26+%26+%5C%5C+10+%26+49+%26+32+%26+22+%26+16+%26+15+%26+10+%26+9+%26+%26+%5C%5C+11+%26+60+%26+39+%26+28+%26+21+%26+16+%26+13+%26+9+%26+9+%26+%5C%5C+12+%26+71+%26+46+%26+33+%26+28+%26+19+%26+18+%26+11+%26+8+%26+9+%5C%5C+%5Chline+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|l|r|r|r|r|r|r|r|r|r|} \\hline k \\textbackslash d & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 \\\\ \\hline 1 & 0 & & & & & & & & \\\\ 2 & 1 & 0 & & & & & & & \\\\ 3 & 4 & 1 & 0 & & & & & & \\\\ 4 & 7 & 4 & 1 & & & & & & \\\\ 5 & 12 & 7 & 4 & & & & & & \\\\ 6 & 17 & 10 & 6 & 4 & & & & & \\\\ 7 & 24 & 15 & 10 & 9 & & & & & \\\\ 8 & 31 & 20 & 13 & 12 & 9 & & & & \\\\ 9 & 40 & 25 & 18 & 13 & 11 & 9 & & & \\\\ 10 & 49 & 32 & 22 & 16 & 15 & 10 & 9 & & \\\\ 11 & 60 & 39 & 28 & 21 & 16 & 13 & 9 & 9 & \\\\ 12 & 71 & 46 & 33 & 28 & 19 & 18 & 11 & 8 & 9 \\\\ \\hline \\end{tabular}")  
Table 1. The starting integer of each descent run by ![d=1, 2,
3...9](https://s0.wp.com/latex.php?latex=d%3D1%2C+2%2C+3...9&bg=ffffff&fg=333333&s=0
"d=1, 2, 3...9") (horizontal) for the first 12 columns of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") (vertical) are shown.

Thus, we get sequences of the starting integers of the descent by a
given ![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0
"d") in the successive columns of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"):  
![d=1](https://s0.wp.com/latex.php?latex=d%3D1&bg=ffffff&fg=333333&s=0
"d=1"); 0, 1, 4, 7, 12, 17… After the starting 0 here successive terms
differ by 3, 3, 5, 5, 7, 7…  
![d=2](https://s0.wp.com/latex.php?latex=d%3D2&bg=ffffff&fg=333333&s=0
"d=2"); 0, 1, 4, 7, 10, 15… After the starting 0 here successive terms
differ by 3, 3, 3, 5, 5, 5,7,7,7…  
![d=3](https://s0.wp.com/latex.php?latex=d%3D3&bg=ffffff&fg=333333&s=0
"d=3"); 0, 1, 4, 6, 10, 13…  
So on, as in Table 1. For the first three of these sequences, i.e. the
starting integers of the descent by 1, 2 and 3 in the successive columns
of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"), we were able to derive general formulae for the
![n^{th}](https://s0.wp.com/latex.php?latex=n%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"n^{th}") term of these sequences:  
![d=1; \\; \\left \\lfloor \\dfrac{n^2}{ 2} \\right
\\rfloor+n](https://s0.wp.com/latex.php?latex=d%3D1%3B+%5C%3B+%5Cleft+%5Clfloor+%5Cdfrac%7Bn%5E2%7D%7B+2%7D+%5Cright+%5Crfloor%2Bn&bg=ffffff&fg=333333&s=0
"d=1; \\; \\left \\lfloor \\dfrac{n^2}{ 2} \\right \\rfloor+n")

![d=2; \\; \\left \\lfloor \\dfrac{n(n+2)}{3}\\right
\\rfloor-1](https://s0.wp.com/latex.php?latex=d%3D2%3B+%5C%3B+%5Cleft+%5Clfloor+%5Cdfrac%7Bn%28n%2B2%29%7D%7B3%7D%5Cright+%5Crfloor-1&bg=ffffff&fg=333333&s=0
"d=2; \\; \\left \\lfloor \\dfrac{n(n+2)}{3}\\right \\rfloor-1")

![d=3; \\; \\left\\lfloor\\dfrac{n(n+6)}{4}\\right
\\rfloor](https://s0.wp.com/latex.php?latex=d%3D3%3B+%5C%3B+%5Cleft%5Clfloor%5Cdfrac%7Bn%28n%2B6%29%7D%7B4%7D%5Cright+%5Crfloor&bg=ffffff&fg=333333&s=0
"d=3; \\; \\left\\lfloor\\dfrac{n(n+6)}{4}\\right \\rfloor")

[![square\_mod\_Fig2](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig2.png?w=640)](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig2.png)*Figure
2. The number of edges in the graph are shown above it in red . The
number of unit square cells in the graph are shown in blue below it.*

Remarkably, for the first of these sequences,
![d=1](https://s0.wp.com/latex.php?latex=d%3D1&bg=ffffff&fg=333333&s=0
"d=1"), we were able to find a clear geometric interpretation. It
corresponds to the number of edges found in the alternating
square-rectangle graph, which is formed by extending the previous
element by a unit (Figure 2, panel 1). This sequence has been described
in OEIS as appearing in several surprising contexts relating to packing
of shapes and beyond. However, to our knowledge this is the first time
it has been found emerging in the triangle
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"). The second of these sequences corresponding to
![d=2](https://s0.wp.com/latex.php?latex=d%3D2&bg=ffffff&fg=333333&s=0
"d=2") may also be interpreted as the number of edges in a growing graph
of unit squares (Figure 2, panel 2), but describing the growth pattern
is less simple than what we see for the case of
![d=1](https://s0.wp.com/latex.php?latex=d%3D1&bg=ffffff&fg=333333&s=0
"d=1"). One can imagine that these sequences provide analogies for the
growth of cell-layers under certain constraints. We are yet to find a
clear geometric interpretation for the case of
![d=3](https://s0.wp.com/latex.php?latex=d%3D3&bg=ffffff&fg=333333&s=0
"d=3"). We have not yet been able to find general formulae for ![d \\ge
4](https://s0.wp.com/latex.php?latex=d+%5Cge+4&bg=ffffff&fg=333333&s=0
"d \\ge 4"). It is something that mathematicians might be able to find.

4\) Then we ask the question as to how many terms the total set of runs
of descent in given column
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") occupy. For
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1"), it is obviously 0. For
![k=2](https://s0.wp.com/latex.php?latex=k%3D2&bg=ffffff&fg=333333&s=0
"k=2") the terms are 1,0; thus, the number of terms is 2. For
![k=3](https://s0.wp.com/latex.php?latex=k%3D3&bg=ffffff&fg=333333&s=0
"k=3"), the terms are 4, 3, 2, 1, 0; thus the number of terms are 5. For
![k=7](https://s0.wp.com/latex.php?latex=k%3D7&bg=ffffff&fg=333333&s=0
"k=7"), which we saw above, the total number of terms occupied by the
runs of descent is 40. We derived the general formula for the total
number of terms in the runs of descent for a column
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k"):

![k^2-k-\\textrm{round}(\\sqrt{k})+1](https://s0.wp.com/latex.php?latex=k%5E2-k-%5Ctextrm%7Bround%7D%28%5Csqrt%7Bk%7D%29%2B1&bg=ffffff&fg=333333&s=0
"k^2-k-\\textrm{round}(\\sqrt{k})+1")

This to our knowledge is a novel sequence whose significance in the
context of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") has not been previously described.

5\) From the above results it also becomes apparent that the total
number of terms in a column
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") before the terminal continuous run of square terms
![k^2](https://s0.wp.com/latex.php?latex=k%5E2&bg=ffffff&fg=333333&s=0
"k^2") is given by formula
![k^2-k+1](https://s0.wp.com/latex.php?latex=k%5E2-k%2B1&bg=ffffff&fg=333333&s=0
"k^2-k+1"). This sequence 1, 3, 7, 13, 21, 31, 43, 57, 73, 91, 111 … is
another famous sequence with a clear geometric significance. It is the
number of cycles that exist in a pyramid graph (also known as a wheel
graph). It has many other interesting properties (see OEIS), but to our
knowledge, this is the first report of its occurrence in the context of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}").

Thus,
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") is the mother of many interesting sequences that show up in
other contexts with various geometric/topological implications.

**The overall structure of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}")**

[![Square\_mod\_Fig3](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig3.png?w=640)](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig3.png)*Figure
3. In the left panel
![T\_{sr}\[300,300\]](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D%5B300%2C300%5D&bg=ffffff&fg=333333&s=0
"T_{sr}[300,300]") is plotted using a different color for each value. In
the right panel the values of
![T\_{sr}\[300,300\]](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D%5B300%2C300%5D&bg=ffffff&fg=333333&s=0
"T_{sr}[300,300]") are modulated using
![\\textrm{arcsinh}(x)](https://s0.wp.com/latex.php?latex=%5Ctextrm%7Barcsinh%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\textrm{arcsinh}(x)") to reveal the internal structure more clearly.*

The above-described row-wise and column-wise patterns in
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") combine to give rise to a further intricate structure that
becomes apparent if we visualize
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") graphically by plotting each cell of the triangle in a
different color (Figure 3). We see a central family of nested conics
along the median of the triangle. This is flanked by further such curves
along the medians of the two triangles formed by the median of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") and also their flanks. A mathematician might be able to
provide the equations to describe these curves in
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}").

Finally, if we take
![T\_{sr}\[j,k\]](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D%5Bj%2Ck%5D&bg=ffffff&fg=333333&s=0
"T_{sr}[j,k]") up to a certain value of ![j,
k](https://s0.wp.com/latex.php?latex=j%2C+k&bg=ffffff&fg=333333&s=0
"j, k"), we can ask what are the frequencies of the various integers in
it (Figure 4) ?

[![Square\_mod\_Fig4](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig4.png?w=640)](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig4.png)*Figure
4. The frequencies of the all integers occurring in
![T\_{sr}\[1000,1000\]](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D%5B1000%2C1000%5D&bg=ffffff&fg=333333&s=0
"T_{sr}[1000,1000]"). The brown line is the best linear fit for the
frequency of the successive perfect squares. The unusually low (red) and
high (violet) values among the non-squares are marked.*

It is immediately apparent that the perfect squares occur at much higher
frequencies than the non-squares. Why this is the case can be generally
understood from the above discussion on the rows and columns of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"), which over-represent perfect squares. The frequencies of
successive perfect squares decrease almost linearly (Figure 4, fit
line). Among the non-squares, we observe that unusually low and
unusually high frequencies are often seen for certain numbers just
before or just after the perfect squares (Figure 4). The exact basis of
this pattern is in need of an explanation.

**The linearization of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}")**  
Another way to examine the structure of
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") is to linearize it. This is done by concatenating successive
rows to generate the sequence
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f").
The first few terms of
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
are shown below:  
0, 1, 0, 1, 1, 0, 1, 0, 1, 0, 1, 4, 4, 1, 0, 1, 4, 3, 4, 1…  
We then plot
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
such that the first term is placed at 0 with
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") being y-coordinate and
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
being the x-coordinate (Figure 5).

*[![Square\_mod\_Fig5](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig5.png?w=640)](https://manasataramgini.files.wordpress.com/2018/06/square_mod_fig5.png)Figure
5. A plot of
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
with successive terms alternately colored red and blue. The bounding
parabola (green) and the primary parabolic attractors (pink) are plotted
over ![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0
"f").*

Given that
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f") is
created by linearizing a triangle it is bounded by a parabola (Figure 5)
of the form:

![y=\\dfrac{-1+\\sqrt{1+8x}}{2}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7B-1%2B%5Csqrt%7B1%2B8x%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{-1+\\sqrt{1+8x}}{2}")

Under this parabola the plot of
![f](https://s0.wp.com/latex.php?latex=f&bg=ffffff&fg=333333&s=0 "f")
reveals a complex pattern, which is clearly non-random. There are
curves, which might be termed attractors, on which the points tend to
occur more frequently than elsewhere:  
1\) The most obvious attractors are straight lines of the form
![y=k^2](https://s0.wp.com/latex.php?latex=y%3Dk%5E2&bg=ffffff&fg=333333&s=0
"y=k^2"); where ![k \\in
\\mathbb{N}](https://s0.wp.com/latex.php?latex=k+%5Cin+%5Cmathbb%7BN%7D&bg=ffffff&fg=333333&s=0
"k \\in \\mathbb{N}") (Figure 5).  
This relates to the preponderance of square terms in
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}") (Figure 4).

2\) The next most visible attractors are the parabolic arcs that start
from the bounding parabola and run towards the x-axis (Figure 5). We
term these the primary parabolic attractors. The coordinates of the
starting points of
![n^{th}](https://s0.wp.com/latex.php?latex=n%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"n^{th}") parabolic attractor, ( ![x\[n\],
y\[n\]](https://s0.wp.com/latex.php?latex=x%5Bn%5D%2C+y%5Bn%5D&bg=ffffff&fg=333333&s=0
"x[n], y[n]")) are specified by the following algorithm:

Let ![r\_1\[j\]= j^2;\\; j=1, 2,
3...](https://s0.wp.com/latex.php?latex=r_1%5Bj%5D%3D+j%5E2%3B%5C%3B+j%3D1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0
"r_1[j]= j^2;\\; j=1, 2, 3...")

![r\_2\[k\]=\\frac{r\_1\[j\]+r\_1\[j+1\]}{2}](https://s0.wp.com/latex.php?latex=r_2%5Bk%5D%3D%5Cfrac%7Br_1%5Bj%5D%2Br_1%5Bj%2B1%5D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"r_2[k]=\\frac{r_1[j]+r_1[j+1]}{2}")

![r=\\textrm{sort}(r\_1,r\_2)](https://s0.wp.com/latex.php?latex=r%3D%5Ctextrm%7Bsort%7D%28r_1%2Cr_2%29&bg=ffffff&fg=333333&s=0
"r=\\textrm{sort}(r_1,r_2)")

![y\[n\]=2r\[n\]](https://s0.wp.com/latex.php?latex=y%5Bn%5D%3D2r%5Bn%5D&bg=ffffff&fg=333333&s=0
"y[n]=2r[n]")

![x\[n\]=y\[n\] \\cdot
r\[n\]](https://s0.wp.com/latex.php?latex=x%5Bn%5D%3Dy%5Bn%5D+%5Ccdot+r%5Bn%5D&bg=ffffff&fg=333333&s=0
"x[n]=y[n] \\cdot r[n]")

The
![n^{th}](https://s0.wp.com/latex.php?latex=n%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"n^{th}") primary parabolic attractors themselves are defined by the
equations of the form:

![y=a\[n\]-\\sqrt{bx-c\[n\]}](https://s0.wp.com/latex.php?latex=y%3Da%5Bn%5D-%5Csqrt%7Bbx-c%5Bn%5D%7D&bg=ffffff&fg=333333&s=0
"y=a[n]-\\sqrt{bx-c[n]}")

We empirically determined that
![b=1.89](https://s0.wp.com/latex.php?latex=b%3D1.89&bg=ffffff&fg=333333&s=0
"b=1.89").

![a\[n\]=\\left \\lceil \\left( n+\\frac{2}{3} \\right)^2 \\right
\\rceil](https://s0.wp.com/latex.php?latex=a%5Bn%5D%3D%5Cleft+%5Clceil+%5Cleft%28+n%2B%5Cfrac%7B2%7D%7B3%7D+%5Cright%29%5E2+%5Cright+%5Crceil&bg=ffffff&fg=333333&s=0
"a[n]=\\left \\lceil \\left( n+\\frac{2}{3} \\right)^2 \\right \\rceil")

Thus, ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") is a sequence whose first few terms are: 3, 8, 14, 22, 33, 45, 59,
76, 94, 114, 137, 161, 187, 216, 246, 278, 313, 349, 387, 428, 470, 514,
561.  
We were unable to derive a general formula for
![c\[n\]](https://s0.wp.com/latex.php?latex=c%5Bn%5D&bg=ffffff&fg=333333&s=0
"c[n]"). However, we empirically determined the first few terms of
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c") to
be: 1, 25, 50, 100, 100, 200, 200, 400, 480, 600, 700, 1000, 1100, 1400,
1550, 2100, 2000, 2700, 2800, 3250, 3250, 4200, 3900.  
Perhaps a mathematician could derive the a general formula for sequence
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
and also provide a means of deriving the value of
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
from first principles.

3\) Finally, a closer look reveals secondary attractors in the form of
fainter parabolic arcs and lines. We have not attempted to derive their
equations. A general scheme for identifying them would be of interest.

In conclusion the humble
![T\_{sr}](https://s0.wp.com/latex.php?latex=T_%7Bsr%7D&bg=ffffff&fg=333333&s=0
"T_{sr}"), which can be derived using elementary school mathematics,
spawns some interesting patterns and sequences that might uncannily
appear in other places.
