+++
title = "Nārāyaṇa’s sequence, Mādhava’s series and pi"

+++
**The coin-toss problem and Nārāyaṇa’s sequence**  
If you toss a fair coin
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
times how many of the possible result-sequences of tosses will not have
a successive run of 3 or more Heads? The same can be phrased as given
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
tosses of a fair coin, what is the probability of not getting 3 or more
successive Heads in the result-sequence. For a single toss
![(n=1)](https://s0.wp.com/latex.php?latex=%28n%3D1%29&bg=ffffff&fg=333333&s=0
"(n=1)") we have two result-sequences
![H,T](https://s0.wp.com/latex.php?latex=H%2CT&bg=ffffff&fg=333333&s=0
"H,T"); so we have 2 result-sequences with no run of 3 or more
continuous Heads. Let
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") be
the number of tosses,
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]") the number of result-sequences satisfying the condition and
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
the probability of its occurrence. This can be tabulated for the first
few coin tosses as below:

![\\begin{tabular}{|l|p{0.5\\linewidth}|l|l|} \\hline n & All
result-sequences & f\[n\] & p\\\\ \\hline 1 & H,T & 2 & 1\\\\ 2 & HH,
HT, TT, TH & 4 & 1\\\\ 3 & HHH, HHT, HTH, HTT, TTT, TTH, THH, THT & 7 &
0.875\\\\ 4 & HHHH, HHHT, HHTH, HTHH, HHTT, HTHT, HTTH, HTTT, TTTT,
TTTH, TTHT, THTT, TTHH, THHT, THTH, THHH & 13 & 0.8125\\\\ \\hline
\\end{tabular}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7Cl%7Cp%7B0.5%5Clinewidth%7D%7Cl%7Cl%7C%7D+%5Chline+n+%26+All+result-sequences+%26+f%5Bn%5D+%26+p%5C%5C+%5Chline+1+%26+H%2CT+%26+2+%26+1%5C%5C+2+%26+HH%2C+HT%2C+TT%2C+TH+%26+4+%26+1%5C%5C+3+%26+HHH%2C+HHT%2C+HTH%2C+HTT%2C+TTT%2C+TTH%2C+THH%2C+THT+%26+7+%26+0.875%5C%5C+4+%26+HHHH%2C+HHHT%2C+HHTH%2C+HTHH%2C+HHTT%2C+HTHT%2C+HTTH%2C+HTTT%2C+TTTT%2C+TTTH%2C+TTHT%2C+THTT%2C+TTHH%2C+THHT%2C+THTH%2C+THHH+%26+13+%26+0.8125%5C%5C+%5Chline+%5Cend%7Btabular%7D&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|l|p{0.5\\linewidth}|l|l|} \\hline n & All result-sequences & f[n] & p\\\\ \\hline 1 & H,T & 2 & 1\\\\ 2 & HH, HT, TT, TH & 4 & 1\\\\ 3 & HHH, HHT, HTH, HTT, TTT, TTH, THH, THT & 7 & 0.875\\\\ 4 & HHHH, HHHT, HHTH, HTHH, HHTT, HTHT, HTTH, HTTT, TTTT, TTTH, TTHT, THTT, TTHH, THHT, THTH, THHH & 13 & 0.8125\\\\ \\hline \\end{tabular}")

Thus we get the sequence as
![f\[n\]=2,4,7,13...](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D2%2C4%2C7%2C13...&bg=ffffff&fg=333333&s=0
"f[n]=2,4,7,13...") from which we can compute the probability as
![p=\\tfrac{f\[n\]}{2^n}](https://s0.wp.com/latex.php?latex=p%3D%5Ctfrac%7Bf%5Bn%5D%7D%7B2%5En%7D&bg=ffffff&fg=333333&s=0
"p=\\tfrac{f[n]}{2^n}"). The question then arises at to whether there is
a general formula for
![f\[n\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D&bg=ffffff&fg=333333&s=0
"f[n]"). The answer to this comes from a class of sequences described by
the great Hindu scientist Nārāyaṇa paṇḍita in 1356 CE. In his
Gaṇita-kaumudī he provides the following (first brought to the wider
public attention in modern times by Paramand Singh in his famous article
on such sequences):

ekāṅkau vinyasya prathamaṃ  
tat saṃyutiṃ puro vilikhet |  
utkramato ‘ntima-tulya-  
sthānāṅka-yutim puro vilikhet ||  
First placing 1 twice ![f\[1\]=1;
f\[2\]=1](https://s0.wp.com/latex.php?latex=f%5B1%5D%3D1%3B+f%5B2%5D%3D1&bg=ffffff&fg=333333&s=0
"f[1]=1; f[2]=1"), write their sum ahead
![f\[3\]=f\[1\]+f\[2\]=2](https://s0.wp.com/latex.php?latex=f%5B3%5D%3Df%5B1%5D%2Bf%5B2%5D%3D2&bg=ffffff&fg=333333&s=0
"f[3]=f[1]+f[2]=2"). Write ahead of that, write the sum of numbers in
reverse order \[and in\] positions equal to the “terminal”
![(q)](https://s0.wp.com/latex.php?latex=%28q%29&bg=ffffff&fg=333333&s=0
"(q)").

utkramato ‘ntima-tulya-  
sthāna-yutiṃ tat purastāc ca |  
antima-tulya sthānābhave  
tat saṃyutiṃ purastāc ca ||  
evaṃ saika-samāsa-sthānā-sāmāsikīyaṃ syāt |  
Write ahead of that, write the sum of numbers in reverse order \[and
in\] positions equal to the “terminal” (continue process). (This means:
If ![3 \\le n \\le
q](https://s0.wp.com/latex.php?latex=3+%5Cle+n+%5Cle+q&bg=ffffff&fg=333333&s=0
"3 \\le n \\le q") then
![f\[n\]=f\[n-1\]+f\[n-2\]...f\[2\]+f\[1\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-1%5D%2Bf%5Bn-2%5D...f%5B2%5D%2Bf%5B1%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-1]+f[n-2]...f[2]+f[1]")) In the absence of \[numbers in\]
positions equal to the terminal write in the front the sum of those \[in
available places\] (This means if
![q\<n](https://s0.wp.com/latex.php?latex=q%3Cn&bg=ffffff&fg=333333&s=0
"q\<n") then
![f\[n\]=f\[n-1\]+f\[n-2\]...f\[n-q\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-1%5D%2Bf%5Bn-2%5D...f%5Bn-q%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-1]+f[n-2]...f[n-q]") ). Thus, the numbers till the position
one more than \[the prior\] may be known as the additive sequence
![(f\[1\], f\[2\]...f\[n-q\],
f\[n-q+1\]...f\[n\])](https://s0.wp.com/latex.php?latex=%28f%5B1%5D%2C+f%5B2%5D...f%5Bn-q%5D%2C+f%5Bn-q%2B1%5D...f%5Bn%5D%29&bg=ffffff&fg=333333&s=0
"(f[1], f[2]...f[n-q], f[n-q+1]...f[n])").

One will note that if one takes
![q=2](https://s0.wp.com/latex.php?latex=q%3D2&bg=ffffff&fg=333333&s=0
"q=2") then we get the famous mātrā-meru sequence
![f\[n\]=f\[n-1\]+f\[n-2\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-1%5D%2Bf%5Bn-2%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-1]+f[n-2]") (known in the Occident as the Fibonacci sequence
after Leonardo of Pisa). Nārāyaṇa then goes on to provide a numerical
example for this class of additive sequences:  
udāharaṇam –  
samāse yatra sapta syur  
antimas trimitaḥ sakhe |  
kīdṛśī tatra kathaya  
paṅktiḥ sāmāsikī drutam ||  
Now an example: Friend, if we have 7 in the sequence and 3 as the
“terminal”
![(q=3)](https://s0.wp.com/latex.php?latex=%28q%3D3%29&bg=ffffff&fg=333333&s=0
"(q=3)") then quickly say what will be the additive sequence under
consideration.

The sequence in consideration in modern form starting from 0 will be
![f\[n\]=f\[n-1\]+f\[n+2\]+f\[n-3\]](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Df%5Bn-1%5D%2Bf%5Bn%2B2%5D%2Bf%5Bn-3%5D&bg=ffffff&fg=333333&s=0
"f[n]=f[n-1]+f[n+2]+f[n-3]"), with the first three terms being 0,1,1 (in
Nārāyaṇa’s reckoning they will be 1,1,2): **0, 1, 1, 2, 4, 7, 13, 24,
44, 81, 149, 274, 504, 927, 1705…** Thus, Nārāyaṇa’s numerical example
from
![f\[3\]](https://s0.wp.com/latex.php?latex=f%5B3%5D&bg=ffffff&fg=333333&s=0
"f[3]") onwards gives us the solution to the coin toss problem. In
modern times this sequence has been given the name “Tribonacci”. With
this, one can see that the probability of the getting a result-sequence
without 3 or more continuous heads decays with
![2^n](https://s0.wp.com/latex.php?latex=2%5En&bg=ffffff&fg=333333&s=0
"2^n") asymptotically towards 0.

**The convergent of Nārāyaṇa’s sequence and problem of the triple
proportional partition of a segment**  
Consider the geometric problem: Partition a line segment
![\\overline{AD}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAD%7D&bg=ffffff&fg=333333&s=0
"\\overline{AD}") of length
![t\_4](https://s0.wp.com/latex.php?latex=t_4&bg=ffffff&fg=333333&s=0
"t_4") in 3 parts ![t\_1, t\_2,
t\_3](https://s0.wp.com/latex.php?latex=t_1%2C+t_2%2C+t_3&bg=ffffff&fg=333333&s=0
"t_1, t_2, t_3") such that ![\\tfrac{t\_2}{t\_1} =
\\tfrac{t\_3}{t\_2}=\\tfrac{t\_4}{t\_3}=\\tfrac{t\_1+t\_2+t\_3}{t\_3}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bt_2%7D%7Bt_1%7D+%3D+%5Ctfrac%7Bt_3%7D%7Bt_2%7D%3D%5Ctfrac%7Bt_4%7D%7Bt_3%7D%3D%5Ctfrac%7Bt_1%2Bt_2%2Bt_3%7D%7Bt_3%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{t_2}{t_1} = \\tfrac{t_3}{t_2}=\\tfrac{t_4}{t_3}=\\tfrac{t_1+t_2+t_3}{t_3}")
(Figure 1).

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig1.png?w=640&h=101)](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig1.png)Figure
1

We can see that the above geometric process is equivalent to the
formulation of the above tryantima-sāmāsikā-paṅkti of Nārāyaṇa (Figure
1). This indicates that, at its limit, the convergent of the above
sequence of Nārāyaṇa,
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau"), will yield us the ratio in which the partition of the segment
should be performed. Thus, we have:

![\\tau= \\displaystyle \\lim\_{n \\to \\infty}\\dfrac{f\[n\]}{f\[n-1\]}
\\approx
1.8392867552141611325518525646532...](https://s0.wp.com/latex.php?latex=%5Ctau%3D+%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D%5Cdfrac%7Bf%5Bn%5D%7D%7Bf%5Bn-1%5D%7D+%5Capprox+1.8392867552141611325518525646532...&bg=ffffff&fg=333333&s=0
"\\tau= \\displaystyle \\lim_{n \\to \\infty}\\dfrac{f[n]}{f[n-1]} \\approx 1.8392867552141611325518525646532...")

This number, unlike the Golden ratio
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi"), the convergent of the mātrā-meru-paṅkti, cannot be constructed
using a straight edge and a compass. However, as we shall see below, it
can be easily constructed using two simply specified conics which can in
turn be constructed using the geometric mean theorem or other standard
methods (Figure 2).

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig2.png?w=640&h=475)](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig2.png)Figure
2

1\) Draw the parabola specified by
![y=x^2](https://s0.wp.com/latex.php?latex=y%3Dx%5E2&bg=ffffff&fg=333333&s=0
"y=x^2") with its vertex
![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0 "C") as
the origin.  
2\) Draw a unit rectangular hyperbola with center
![C\_h](https://s0.wp.com/latex.php?latex=C_h&bg=ffffff&fg=333333&s=0
"C_h") at
![(1,1)](https://s0.wp.com/latex.php?latex=%281%2C1%29&bg=ffffff&fg=333333&s=0
"(1,1)"). Therefore, its equation will be
![xy-x-y=1](https://s0.wp.com/latex.php?latex=xy-x-y%3D1&bg=ffffff&fg=333333&s=0
"xy-x-y=1").  
3\) The two conics will intersect at
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P").
Drop a perpendicular from
![P](https://s0.wp.com/latex.php?latex=P&bg=ffffff&fg=333333&s=0 "P") to
the ![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis to cut it at
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B").
![t\_1=\\overline{CB}=\\tau](https://s0.wp.com/latex.php?latex=t_1%3D%5Coverline%7BCB%7D%3D%5Ctau&bg=ffffff&fg=333333&s=0
"t_1=\\overline{CB}=\\tau").  
4\) Extend
![\\overline{CB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BCB%7D&bg=ffffff&fg=333333&s=0
"\\overline{CB}") by a unit to get point
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A").
![\\overline{BA}=1](https://s0.wp.com/latex.php?latex=%5Coverline%7BBA%7D%3D1&bg=ffffff&fg=333333&s=0
"\\overline{BA}=1").  
5\) Draw a circle with
![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0 "C") as
center and
![\\overline{CB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BCB%7D&bg=ffffff&fg=333333&s=0
"\\overline{CB}") as radius to cut the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-axis at
![X](https://s0.wp.com/latex.php?latex=X&bg=ffffff&fg=333333&s=0 "X").  
6\) Mark point
![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0 "Q")
along
![\\overline{CB}](https://s0.wp.com/latex.php?latex=%5Coverline%7BCB%7D&bg=ffffff&fg=333333&s=0
"\\overline{CB}") at a unit distance from
![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0 "C").
Join ![Q](https://s0.wp.com/latex.php?latex=Q&bg=ffffff&fg=333333&s=0
"Q") to ![X](https://s0.wp.com/latex.php?latex=X&bg=ffffff&fg=333333&s=0
"X").  
7\) Draw a perpendicular to
![\\overline{QX}](https://s0.wp.com/latex.php?latex=%5Coverline%7BQX%7D&bg=ffffff&fg=333333&s=0
"\\overline{QX}") at
![X](https://s0.wp.com/latex.php?latex=X&bg=ffffff&fg=333333&s=0 "X").
It will cut the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x")-Axis at point
![D](https://s0.wp.com/latex.php?latex=D&bg=ffffff&fg=333333&s=0 "D").
Join ![C](https://s0.wp.com/latex.php?latex=C&bg=ffffff&fg=333333&s=0
"C") to ![D](https://s0.wp.com/latex.php?latex=D&bg=ffffff&fg=333333&s=0
"D"). By the geometric mean theorem
![\\overline{CD}=\\tau^2](https://s0.wp.com/latex.php?latex=%5Coverline%7BCD%7D%3D%5Ctau%5E2&bg=ffffff&fg=333333&s=0
"\\overline{CD}=\\tau^2").

This gives us the required partition of
![\\overline{AD}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAD%7D&bg=ffffff&fg=333333&s=0
"\\overline{AD}") into 3 segments each proportional to the other as
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau"), and
![\\overline{AD}](https://s0.wp.com/latex.php?latex=%5Coverline%7BAD%7D&bg=ffffff&fg=333333&s=0
"\\overline{AD}") proportional to the largest partition
![\\overline{CD}](https://s0.wp.com/latex.php?latex=%5Coverline%7BCD%7D&bg=ffffff&fg=333333&s=0
"\\overline{CD}") again as
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau"). Thus, we have:

![\\tau=\\dfrac{\\tau^2+\\tau+1}{\\tau^2}](https://s0.wp.com/latex.php?latex=%5Ctau%3D%5Cdfrac%7B%5Ctau%5E2%2B%5Ctau%2B1%7D%7B%5Ctau%5E2%7D&bg=ffffff&fg=333333&s=0
"\\tau=\\dfrac{\\tau^2+\\tau+1}{\\tau^2}")

Hence,
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") is the root of the cubic equation
![\\tau^3-\\tau^2-\\tau-1=0](https://s0.wp.com/latex.php?latex=%5Ctau%5E3-%5Ctau%5E2-%5Ctau-1%3D0&bg=ffffff&fg=333333&s=0
"\\tau^3-\\tau^2-\\tau-1=0"). Thus, we see that the above construction
is achieved by solving this cubic via the intersection of the said
parabola and hyperbola. This cubic equation has only one real root which
is
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau"). We can take the help of computer algebra to obtain the exact
form of this root as:

![\\tau=\\dfrac{1}{3}\\left(1+\\left(19-3\\sqrt{33}\\right)^{1/3}+\\left(19+3\\sqrt{33}\\right)^{1/3}\\right)](https://s0.wp.com/latex.php?latex=%5Ctau%3D%5Cdfrac%7B1%7D%7B3%7D%5Cleft%281%2B%5Cleft%2819-3%5Csqrt%7B33%7D%5Cright%29%5E%7B1%2F3%7D%2B%5Cleft%2819%2B3%5Csqrt%7B33%7D%5Cright%29%5E%7B1%2F3%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\tau=\\dfrac{1}{3}\\left(1+\\left(19-3\\sqrt{33}\\right)^{1/3}+\\left(19+3\\sqrt{33}\\right)^{1/3}\\right)")

The other two roots are complex conjugates:

![\\tau'=\\dfrac{1}{3} - \\dfrac{(19 - 3 \\sqrt{33})^{1/3}- (19 + 3
\\sqrt{33})^{1/3}}{6} + i\\dfrac{ \\sqrt{3}(19 - 3
\\sqrt{33})^{1/3}-\\sqrt{3}(19 + 3 \\sqrt{33})^{1/3}}{6}\\\\\[7pt\]
\\overline{\\tau'}=\\dfrac{1}{3} - \\dfrac{(19 - 3 \\sqrt{33})^{1/3}-
(19 + 3 \\sqrt{33})^{1/3}}{6} - i\\dfrac{ \\sqrt{3}(19 - 3
\\sqrt{33})^{1/3}-\\sqrt{3}(19 + 3
\\sqrt{33})^{1/3}}{6}](https://s0.wp.com/latex.php?latex=%5Ctau%27%3D%5Cdfrac%7B1%7D%7B3%7D+-+%5Cdfrac%7B%2819+-+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D-+%2819+%2B+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D%7D%7B6%7D+%2B+i%5Cdfrac%7B+%5Csqrt%7B3%7D%2819+-+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D-%5Csqrt%7B3%7D%2819+%2B+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D%7D%7B6%7D%5C%5C%5B7pt%5D+%5Coverline%7B%5Ctau%27%7D%3D%5Cdfrac%7B1%7D%7B3%7D+-+%5Cdfrac%7B%2819+-+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D-+%2819+%2B+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D%7D%7B6%7D+-+i%5Cdfrac%7B+%5Csqrt%7B3%7D%2819+-+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D-%5Csqrt%7B3%7D%2819+%2B+3+%5Csqrt%7B33%7D%29%5E%7B1%2F3%7D%7D%7B6%7D&bg=ffffff&fg=333333&s=0
"\\tau'=\\dfrac{1}{3} - \\dfrac{(19 - 3 \\sqrt{33})^{1/3}- (19 + 3 \\sqrt{33})^{1/3}}{6} + i\\dfrac{ \\sqrt{3}(19 - 3 \\sqrt{33})^{1/3}-\\sqrt{3}(19 + 3 \\sqrt{33})^{1/3}}{6}\\\\[7pt] \\overline{\\tau'}=\\dfrac{1}{3} - \\dfrac{(19 - 3 \\sqrt{33})^{1/3}- (19 + 3 \\sqrt{33})^{1/3}}{6} - i\\dfrac{ \\sqrt{3}(19 - 3 \\sqrt{33})^{1/3}-\\sqrt{3}(19 + 3 \\sqrt{33})^{1/3}}{6}")

Comparable to the situation with
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") and its conjugate, these roots have a relationship of the form:

![\\tau=\\dfrac{1}{\\tau'
\\overline{\\tau'}}](https://s0.wp.com/latex.php?latex=%5Ctau%3D%5Cdfrac%7B1%7D%7B%5Ctau%27+%5Coverline%7B%5Ctau%27%7D%7D&bg=ffffff&fg=333333&s=0
"\\tau=\\dfrac{1}{\\tau' \\overline{\\tau'}}")

There are also some other curious identities satisfied by
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") like:  
![\\dfrac{(1+\\tau)^2}{1+\\tau^2}=\\tau](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B%281%2B%5Ctau%29%5E2%7D%7B1%2B%5Ctau%5E2%7D%3D%5Ctau&bg=ffffff&fg=333333&s=0
"\\dfrac{(1+\\tau)^2}{1+\\tau^2}=\\tau")

**The convergent of Nārāyaṇa’s sequence and Mādhava’s
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") and
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") series**  
The triple partitioning of a segment leads us to a geometric
construction that yields the relationship between
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") and
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") (Figure 3):

![\\pi=4\\left(\\arctan\\left(\\dfrac{1}{\\tau}\\right)+\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%3D4%5Cleft%28%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%7D%5Cright%29%2B%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%5E2%7D%5Cright%29%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi=4\\left(\\arctan\\left(\\dfrac{1}{\\tau}\\right)+\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)\\right)")

Figure 3 provides a proof for this of a type the old Hindus termed the
upapatti or what in today’s mathematics is a proof without words (to our
knowledge never presented before). Nevertheless, for the geometrically
less-inclined we add a few words below to clarify this.

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig3.png?w=640&h=573)](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig3.png)Figure
3

In Figure 3, one can see how
![\\angle{\\alpha}=\\arctan\\left(\\tfrac{1}{\\tau^2}\\right)](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Calpha%7D%3D%5Carctan%5Cleft%28%5Ctfrac%7B1%7D%7B%5Ctau%5E2%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\angle{\\alpha}=\\arctan\\left(\\tfrac{1}{\\tau^2}\\right)"). It
emerges once from the starting triply partitioned segment as
![\\angle{\\alpha}= \\arctan\\left (\\tfrac{\\tau}{\\tau^3}
\\right)](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Calpha%7D%3D+%5Carctan%5Cleft+%28%5Ctfrac%7B%5Ctau%7D%7B%5Ctau%5E3%7D+%5Cright%29&bg=ffffff&fg=333333&s=0
"\\angle{\\alpha}= \\arctan\\left (\\tfrac{\\tau}{\\tau^3} \\right)").
The construction creates segments ![t\_1, t\_2,
t\_3](https://s0.wp.com/latex.php?latex=t_1%2C+t_2%2C+t_3&bg=ffffff&fg=333333&s=0
"t_1, t_2, t_3") in the proportion of
![1:\\tau:\\tau^2](https://s0.wp.com/latex.php?latex=1%3A%5Ctau%3A%5Ctau%5E2&bg=ffffff&fg=333333&s=0
"1:\\tau:\\tau^2"). Thus, we get the second occurrence of
![\\angle{\\alpha}=\\arctan\\left (\\tfrac{t\_1}{t\_3}
\\right)](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Calpha%7D%3D%5Carctan%5Cleft+%28%5Ctfrac%7Bt_1%7D%7Bt_3%7D+%5Cright%29&bg=ffffff&fg=333333&s=0
"\\angle{\\alpha}=\\arctan\\left (\\tfrac{t_1}{t_3} \\right)"). That in
turn implies the occurrence of a vertical segment of size
![\\tau^2](https://s0.wp.com/latex.php?latex=%5Ctau%5E2&bg=ffffff&fg=333333&s=0
"\\tau^2"). From the construction we also get
![\\angle{\\beta}=\\arctan\\left
(\\tfrac{t\_3}{t\_1+t\_2+t\_3}\\right)=\\arctan\\left
(\\tfrac{1}{\\tau}\\right)](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Cbeta%7D%3D%5Carctan%5Cleft+%28%5Ctfrac%7Bt_3%7D%7Bt_1%2Bt_2%2Bt_3%7D%5Cright%29%3D%5Carctan%5Cleft+%28%5Ctfrac%7B1%7D%7B%5Ctau%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\angle{\\beta}=\\arctan\\left (\\tfrac{t_3}{t_1+t_2+t_3}\\right)=\\arctan\\left (\\tfrac{1}{\\tau}\\right)").
Thus,
![\\angle{\\alpha}+\\angle{\\beta}](https://s0.wp.com/latex.php?latex=%5Cangle%7B%5Calpha%7D%2B%5Cangle%7B%5Cbeta%7D&bg=ffffff&fg=333333&s=0
"\\angle{\\alpha}+\\angle{\\beta}") add up to form the congruent base
angles of an isosceles right triangle with congruent sides measuring
![\\tau+\\tau^2](https://s0.wp.com/latex.php?latex=%5Ctau%2B%5Ctau%5E2&bg=ffffff&fg=333333&s=0
"\\tau+\\tau^2"). This implies that:

![\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)+\\arctan\\left
(\\dfrac{1}{\\tau}\\right)= \\arctan(1)=\\dfrac{\\pi}{4}\\\\\[7pt\]
\\therefore
\\pi=4\\left(\\arctan\\left(\\dfrac{1}{\\tau}\\right)+\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)\\right)
\\; \\; \\;
\_{...\\blacksquare}](https://s0.wp.com/latex.php?latex=%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%5E2%7D%5Cright%29%2B%5Carctan%5Cleft+%28%5Cdfrac%7B1%7D%7B%5Ctau%7D%5Cright%29%3D+%5Carctan%281%29%3D%5Cdfrac%7B%5Cpi%7D%7B4%7D%5C%5C%5B7pt%5D+%5Ctherefore+%5Cpi%3D4%5Cleft%28%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%7D%5Cright%29%2B%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%5E2%7D%5Cright%29%5Cright%29+%5C%3B+%5C%3B+%5C%3B+_%7B...%5Cblacksquare%7D&bg=ffffff&fg=333333&s=0
"\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)+\\arctan\\left (\\dfrac{1}{\\tau}\\right)= \\arctan(1)=\\dfrac{\\pi}{4}\\\\[7pt] \\therefore \\pi=4\\left(\\arctan\\left(\\dfrac{1}{\\tau}\\right)+\\arctan\\left(\\dfrac{1}{\\tau^2}\\right)\\right) \\; \\; \\; _{...\\blacksquare}")

Likewise we can also see that:

![\\pi=\\dfrac{4}{3}\\left(\\arctan(\\tau)+\\arctan\\left(\\tau^2\\right)\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdfrac%7B4%7D%7B3%7D%5Cleft%28%5Carctan%28%5Ctau%29%2B%5Carctan%5Cleft%28%5Ctau%5E2%5Cright%29%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi=\\dfrac{4}{3}\\left(\\arctan(\\tau)+\\arctan\\left(\\tau^2\\right)\\right)")

Approximately contemporaneously with Nārāyaṇa’s work, apparently
unbeknownst to him, Mādhava, the great mathematician and astronomer from
Cerapada, presented his celebrated infinite series for the
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") function:

![\\arctan(x)=\\dfrac{x}{1}-\\dfrac{x^3}{3}+\\dfrac{x^5}{5}-\\dfrac{x^7}{7}...](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29%3D%5Cdfrac%7Bx%7D%7B1%7D-%5Cdfrac%7Bx%5E3%7D%7B3%7D%2B%5Cdfrac%7Bx%5E5%7D%7B5%7D-%5Cdfrac%7Bx%5E7%7D%7B7%7D...&bg=ffffff&fg=333333&s=0
"\\arctan(x)=\\dfrac{x}{1}-\\dfrac{x^3}{3}+\\dfrac{x^5}{5}-\\dfrac{x^7}{7}...")

We can use the first of the above relationships between
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") and
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") to obtain an infinite series for the former based on the
latter:  
![\\pi=4\\left(\\dfrac{1}{\\tau}-\\dfrac{1}{3\\tau^3}+\\dfrac{1}{5\\tau^5}-\\dfrac{1}{7\\tau^7}+\\dfrac{1}{9\\tau^9}-\\dfrac{1}{11\\tau^{11}}+\\dfrac{1}{13\\tau^{13}}...+\\dfrac{1}{\\tau^2}-\\dfrac{1}{3\\tau^6}+\\dfrac{1}{5\\tau^{10}}-\\dfrac{1}{7\\tau^{14}}...\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%3D4%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%7D-%5Cdfrac%7B1%7D%7B3%5Ctau%5E3%7D%2B%5Cdfrac%7B1%7D%7B5%5Ctau%5E5%7D-%5Cdfrac%7B1%7D%7B7%5Ctau%5E7%7D%2B%5Cdfrac%7B1%7D%7B9%5Ctau%5E9%7D-%5Cdfrac%7B1%7D%7B11%5Ctau%5E%7B11%7D%7D%2B%5Cdfrac%7B1%7D%7B13%5Ctau%5E%7B13%7D%7D...%2B%5Cdfrac%7B1%7D%7B%5Ctau%5E2%7D-%5Cdfrac%7B1%7D%7B3%5Ctau%5E6%7D%2B%5Cdfrac%7B1%7D%7B5%5Ctau%5E%7B10%7D%7D-%5Cdfrac%7B1%7D%7B7%5Ctau%5E%7B14%7D%7D...%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi=4\\left(\\dfrac{1}{\\tau}-\\dfrac{1}{3\\tau^3}+\\dfrac{1}{5\\tau^5}-\\dfrac{1}{7\\tau^7}+\\dfrac{1}{9\\tau^9}-\\dfrac{1}{11\\tau^{11}}+\\dfrac{1}{13\\tau^{13}}...+\\dfrac{1}{\\tau^2}-\\dfrac{1}{3\\tau^6}+\\dfrac{1}{5\\tau^{10}}-\\dfrac{1}{7\\tau^{14}}...\\right)")

Gathering terms in order of their exponents we get:  
![\\pi=4\\left(\\dfrac{1}{\\tau}+\\dfrac{1}{\\tau^2}-\\dfrac{1}{3\\tau^3}+\\dfrac{1}{5\\tau^5}-\\dfrac{1}{3\\tau^6}-\\dfrac{1}{7\\tau^7}+\\dfrac{1}{9\\tau^9}+\\dfrac{1}{5\\tau^{10}}-\\dfrac{1}{11\\tau^{11}}+\\dfrac{1}{13\\tau^{13}}-\\dfrac{1}{7\\tau^{14}}...\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%3D4%5Cleft%28%5Cdfrac%7B1%7D%7B%5Ctau%7D%2B%5Cdfrac%7B1%7D%7B%5Ctau%5E2%7D-%5Cdfrac%7B1%7D%7B3%5Ctau%5E3%7D%2B%5Cdfrac%7B1%7D%7B5%5Ctau%5E5%7D-%5Cdfrac%7B1%7D%7B3%5Ctau%5E6%7D-%5Cdfrac%7B1%7D%7B7%5Ctau%5E7%7D%2B%5Cdfrac%7B1%7D%7B9%5Ctau%5E9%7D%2B%5Cdfrac%7B1%7D%7B5%5Ctau%5E%7B10%7D%7D-%5Cdfrac%7B1%7D%7B11%5Ctau%5E%7B11%7D%7D%2B%5Cdfrac%7B1%7D%7B13%5Ctau%5E%7B13%7D%7D-%5Cdfrac%7B1%7D%7B7%5Ctau%5E%7B14%7D%7D...%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi=4\\left(\\dfrac{1}{\\tau}+\\dfrac{1}{\\tau^2}-\\dfrac{1}{3\\tau^3}+\\dfrac{1}{5\\tau^5}-\\dfrac{1}{3\\tau^6}-\\dfrac{1}{7\\tau^7}+\\dfrac{1}{9\\tau^9}+\\dfrac{1}{5\\tau^{10}}-\\dfrac{1}{11\\tau^{11}}+\\dfrac{1}{13\\tau^{13}}-\\dfrac{1}{7\\tau^{14}}...\\right)")

One notices that all except the fourth powers are represented. One can
compactly express this as:  
![\\pi=\\displaystyle 4\\sum\_{n=1}^{\\infty}
\\dfrac{a\[n\]}{n\\tau^n}](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdisplaystyle+4%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7Ba%5Bn%5D%7D%7Bn%5Ctau%5En%7D&bg=ffffff&fg=333333&s=0
"\\pi=\\displaystyle 4\\sum_{n=1}^{\\infty} \\dfrac{a[n]}{n\\tau^n}")  
Here the cyclic sequence
![a\[n\]](https://s0.wp.com/latex.php?latex=a%5Bn%5D&bg=ffffff&fg=333333&s=0
"a[n]") is defined thus:  
![a\[n\]=1, a\[n+1\]=2\\cdot (-1)^{m-1}, a\[n+2\]=-1, a\[n+3\]=0;
n=4(m-1)+1; m=1,2,3... a\[n\]=1, 2, -1, 0, 1, -2, -1, 0, 1, 2, -1,
0...](https://s0.wp.com/latex.php?latex=a%5Bn%5D%3D1%2C+a%5Bn%2B1%5D%3D2%5Ccdot+%28-1%29%5E%7Bm-1%7D%2C+a%5Bn%2B2%5D%3D-1%2C+a%5Bn%2B3%5D%3D0%3B+n%3D4%28m-1%29%2B1%3B+m%3D1%2C2%2C3...+a%5Bn%5D%3D1%2C+2%2C+-1%2C+0%2C+1%2C+-2%2C+-1%2C+0%2C+1%2C+2%2C+-1%2C+0...&bg=ffffff&fg=333333&s=0
"a[n]=1, a[n+1]=2\\cdot (-1)^{m-1}, a[n+2]=-1, a[n+3]=0; n=4(m-1)+1; m=1,2,3... a[n]=1, 2, -1, 0, 1, -2, -1, 0, 1, 2, -1, 0...")

Using this series to calculate
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") results in reasonably fast convergence with a nearly linear
increase in the correct digits after the decimal point with every 4
terms. Thus, with 200 terms we get
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") correct to 53 places after the decimal point (Figure 4).
However, we should keep in mind that
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
actually includes a null term which removes every 4th powers; hence, the
real number of terms is lower by
![\\tfrac{n}{4}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Bn%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{n}{4}").

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribo_pi.png?w=640&h=504)](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribo_pi.png)Figure
4

Using just the first 3 terms we get an approximation of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") that works as well as
![\\tfrac{22}{7}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B22%7D%7B7%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{22}{7}") as:

![\\pi \\approx 4
\\left(\\dfrac{3\\tau^2+3\\tau-1}{3\\tau^2+3\\tau+3}\\right)](https://s0.wp.com/latex.php?latex=%5Cpi+%5Capprox+4+%5Cleft%28%5Cdfrac%7B3%5Ctau%5E2%2B3%5Ctau-1%7D%7B3%5Ctau%5E2%2B3%5Ctau%2B3%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi \\approx 4 \\left(\\dfrac{3\\tau^2+3\\tau-1}{3\\tau^2+3\\tau+3}\\right)")

We can further compare this to the famous single angle
![\\arctan](https://s0.wp.com/latex.php?latex=%5Carctan&bg=ffffff&fg=333333&s=0
"\\arctan") infinite series for
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") provided by Mādhava using bhūta-saṃkhya (the Hindu numerical
code):

vyāse vāridhi-nihate rūpa-hṛte vyāsa-sāgarābhihate |  
tri-śarādi-viṣama-saṃkhyā-bhaktaṃ ṛṇaṃ svaṃ pṛthak kramāt kuryāt ||  
In the diameter multiplied by the oceans (4) and divided by the form
(1), subtraction and addition \[of terms\] should be repeatedly done of
the diameter multiplied by the oceans (4) and divided respectively by 3,
the arrows (5) and so on of odd numbers.

In modern notation that would be:

![\\pi=\\displaystyle 4\\sum\_{n=1}^{\\infty}
\\dfrac{1}{2n-1}](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdisplaystyle+4%5Csum_%7Bn%3D1%7D%5E%7B%5Cinfty%7D+%5Cdfrac%7B1%7D%7B2n-1%7D&bg=ffffff&fg=333333&s=0
"\\pi=\\displaystyle 4\\sum_{n=1}^{\\infty} \\dfrac{1}{2n-1}")

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_pi_madhava.png?w=640&h=504)](https://manasataramgini.files.wordpress.com/2019/07/narayana_pi_madhava.png)Figure
5

This series converges very slowly and in an oscillatory fashion (Figure
5) reaching just 2 correct digits after the decimal point after
computing 200 terms. The oscillatory convergence features an alternation
of better and worse approximations, with the latter showing a curious
feature. For example, with 25 terms we encounter 3.1815 which is
“correct” up to 4 places after the point (3.1415) except for the wrong
8 in the second place. With 50 terms we get 3.12159465, which is correct
to 8 places (3.14159465) after the point except for the wrong 2 at the
second place. More such instances can be found as we go along the
expansion. For example at 500 terms we get:  
3.141592653589793238  
3.139592655589783238

This is correct to 18 places except for 4 wrong places. Late J. Borwein
and colleagues have reported an occurrence of this phenomenon even in a
calculation of ![5 \\times
10^6](https://s0.wp.com/latex.php?latex=5+%5Ctimes+10%5E6&bg=ffffff&fg=333333&s=0
"5 \\times 10^6") terms of this series.

Thus, the double angle series based on
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") fares way better than the basic single angle Mādhava series for
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). Of course, Mādhava was well aware that it converged very
slowly. Hence, he and others in his school like the Nampūtiri-s, the
great Nilakaṇṭha Somayājin, Jyeṣṭadeva and Citrabhānu, devised some
terminal correction terms to derive alternative series to speed up
convergence and obtained approximations of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") that had good accuracy for those times. Two of their series
which were mediocre in convergence speed are in modern notation:

![\\pi=\\displaystyle 4\\left(\\dfrac{3}{4}+\\sum\_{n=1}^\\infty
\\dfrac{-1^{n+1}}{(2n+1)^3-(2n+1)}\\right)](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdisplaystyle+4%5Cleft%28%5Cdfrac%7B3%7D%7B4%7D%2B%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B-1%5E%7Bn%2B1%7D%7D%7B%282n%2B1%29%5E3-%282n%2B1%29%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\pi=\\displaystyle 4\\left(\\dfrac{3}{4}+\\sum_{n=1}^\\infty \\dfrac{-1^{n+1}}{(2n+1)^3-(2n+1)}\\right)")

This sequence produces ![\\pi \\approx
3.1415926](https://s0.wp.com/latex.php?latex=%5Cpi+%5Capprox+3.1415926&bg=ffffff&fg=333333&s=0
"\\pi \\approx 3.1415926") after 200 terms.

![\\pi=\\displaystyle\\sum\_{n=1}^\\infty \\dfrac{-1^{n+1} \\cdot
16}{(2n-1)^5+4(2n-1)}](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdisplaystyle%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B-1%5E%7Bn%2B1%7D+%5Ccdot+16%7D%7B%282n-1%29%5E5%2B4%282n-1%29%7D&bg=ffffff&fg=333333&s=0
"\\pi=\\displaystyle\\sum_{n=1}^\\infty \\dfrac{-1^{n+1} \\cdot 16}{(2n-1)^5+4(2n-1)}")

This one works better than the above and produces ![\\pi \\approx
3.141592653589](https://s0.wp.com/latex.php?latex=%5Cpi+%5Capprox+3.141592653589&bg=ffffff&fg=333333&s=0
"\\pi \\approx 3.141592653589") after 200 terms

The third uses
![\\tan\\left(\\tfrac{\\pi}{3}\\right)](https://s0.wp.com/latex.php?latex=%5Ctan%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B3%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"\\tan\\left(\\tfrac{\\pi}{3}\\right)") as a multiplicand:

![\\pi=\\displaystyle\\sum\_{n=1}^\\infty \\dfrac{-1^{x-1}\\cdot
2\\sqrt{3}}{3^{n-1}(2n-1)}](https://s0.wp.com/latex.php?latex=%5Cpi%3D%5Cdisplaystyle%5Csum_%7Bn%3D1%7D%5E%5Cinfty+%5Cdfrac%7B-1%5E%7Bx-1%7D%5Ccdot+2%5Csqrt%7B3%7D%7D%7B3%5E%7Bn-1%7D%282n-1%29%7D&bg=ffffff&fg=333333&s=0
"\\pi=\\displaystyle\\sum_{n=1}^\\infty \\dfrac{-1^{x-1}\\cdot 2\\sqrt{3}}{3^{n-1}(2n-1)}")

This series fares much better and produces 97 correct digits after the
decimal point with 200 terms. This is quite impressive because it
outdoes the above double angle series based on ![\\tau,
\\tau^2](https://s0.wp.com/latex.php?latex=%5Ctau%2C+%5Ctau%5E2&bg=ffffff&fg=333333&s=0
"\\tau, \\tau^2"). It is quite likely that Mādhava and Citrabhānu used
this series for around 20-25 terms to obtain approximations such as the
below (expressed in bhūta-saṃkhya):

vibudha-netra-gajāhi-hutāśana-triguṇa-veda-bha-vāraṇa-bāhavaḥ |  
nava-nikharva-mite vṛtti-vistare paridhimānam idaṃ jagadur budhāḥ ||  
The gods (33), eyes (2), elephants (8), snakes (8), the fires thrice
(333), the veda-s (4), the asterisms (27), the elephants (8), the hands
(2) is the measure of the circumference of a circle with diameter of ![9
\\times 10^{11}
](https://s0.wp.com/latex.php?latex=9+%5Ctimes+10%5E%7B11%7D+&bg=ffffff&fg=333333&s=0
"9 \\times 10^{11} "), so had stated the mathematicians:

![\\pi \\approx \\dfrac{2827433388233}{900000000000} \\approx
3.14159265359](https://s0.wp.com/latex.php?latex=%5Cpi+%5Capprox+%5Cdfrac%7B2827433388233%7D%7B900000000000%7D+%5Capprox+3.14159265359&bg=ffffff&fg=333333&s=0
"\\pi \\approx \\dfrac{2827433388233}{900000000000} \\approx 3.14159265359")

In addition to approximations of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") derived from studies on
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") series we also see that Mādhava’s successors, if not
himself, were also using a sequence of continued fraction convergents of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi"). These were probably inspired by the ability to initially
calculate good approximations using series derived from the
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") series such as the above. Of these a large one is
explicitly stated by Śankara-vāriyar and Nārāyaṇa Nampūtiri in their
work the Kriyākramakarī:

vṛtta-vyāse hate nāga-veda-vahny-abdhi-khendubhiḥ |  
tithy-aśvi-vibudhair bhakte susūkṣmaḥ paridhir bhavet ||  
Multiplying the diameter of a circle by snakes(8), veda-s(4), the fires
(3), the oceans (4), the space (0), the moon (1) and dividing it by the
tithi-s (15), Aśvin-s (2), gods (33) one may get the circumference to
good accuracy.

![\\pi \\approx \\dfrac{104348}{33215} \\approx
3.141592653](https://s0.wp.com/latex.php?latex=%5Cpi+%5Capprox+%5Cdfrac%7B104348%7D%7B33215%7D+%5Capprox+3.141592653&bg=ffffff&fg=333333&s=0
"\\pi \\approx \\dfrac{104348}{33215} \\approx 3.141592653")

The
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") sequence remained a workhorse for calculating
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") long after the heroics of Mādhava’s school. A particularly
famous double angle formula was obtained by Euler with a [simple
geometric
proof](https://manasataramgini.wordpress.com/2017/04/20/eulers-squares/):

![\\arctan\\left(\\dfrac{1}{2}\\right)+\\arctan\\left(\\dfrac{1}{3}\\right)=\\dfrac{\\pi}{4}](https://s0.wp.com/latex.php?latex=%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B2%7D%5Cright%29%2B%5Carctan%5Cleft%28%5Cdfrac%7B1%7D%7B3%7D%5Cright%29%3D%5Cdfrac%7B%5Cpi%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\arctan\\left(\\dfrac{1}{2}\\right)+\\arctan\\left(\\dfrac{1}{3}\\right)=\\dfrac{\\pi}{4}")

Using this formula we get we get a rather good convergence and reach 122
correct places after the decimal point with 200 terms.

**Tailpiece: From
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") via
![\\arcsin(x)](https://s0.wp.com/latex.php?latex=%5Carcsin%28x%29&bg=ffffff&fg=333333&s=0
"\\arcsin(x)")**  
We may conclude by noting that the while
![\\tau](https://s0.wp.com/latex.php?latex=%5Ctau&bg=ffffff&fg=333333&s=0
"\\tau") relates to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") via the
![\\arctan(x)](https://s0.wp.com/latex.php?latex=%5Carctan%28x%29&bg=ffffff&fg=333333&s=0
"\\arctan(x)") function, the Golden ratio
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") relates to
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") via the
![\\arcsin(x)](https://s0.wp.com/latex.php?latex=%5Carcsin%28x%29&bg=ffffff&fg=333333&s=0
"\\arcsin(x)") function. This stems from the special relationship
between
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") and the sines of the angles
![\\tfrac{3\\pi}{10}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B3%5Cpi%7D%7B10%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{3\\pi}{10}") and
![\\tfrac{\\pi}{10}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B10%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{10}"). In the Jyotpatti appendix of his
Siddhānta-śiromaṇi’s Bhāskara-II specifically presents the values of
the sines of these angles as common knowledge of the pūrvācārya-s. We
reproduce below his account of the angles, the closed forms of whose
sines were know to them (Note that old Hindus used Rsine instead of
modern
![\\sin(x)](https://s0.wp.com/latex.php?latex=%5Csin%28x%29&bg=ffffff&fg=333333&s=0
"\\sin(x)"); hence the technical term “trijyā” for
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R").
Originally, Āryabhaṭa had set ![R=\\tfrac{60\\times 180}{\\pi} \\approx
3438'](https://s0.wp.com/latex.php?latex=R%3D%5Ctfrac%7B60%5Ctimes+180%7D%7B%5Cpi%7D+%5Capprox+3438%27&bg=ffffff&fg=333333&s=0
"R=\\tfrac{60\\times 180}{\\pi} \\approx 3438'"), i.e. corresponding
approximately to a radian measure in minutes. Below we take it to be 1
to correspond to our modern
![\\sin(x)](https://s0.wp.com/latex.php?latex=%5Csin%28x%29&bg=ffffff&fg=333333&s=0
"\\sin(x)")):

trijyārdhaṃ rāśijyā tat koṭijyā ca ṣaṣṭi-bhāgānām |  
trijyā-vargārdha-padaṃ śaravedāṃśa-jyakā bhavati ||  
Half the
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R") is
the zodiacal sine (i.e.
![\\tfrac{360^o}{12}=30^o](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B360%5Eo%7D%7B12%7D%3D30%5Eo&bg=ffffff&fg=333333&s=0
"\\tfrac{360^o}{12}=30^o")). Its cosine (i.e. of
![\\cos(30^o)](https://s0.wp.com/latex.php?latex=%5Ccos%2830%5Eo%29&bg=ffffff&fg=333333&s=0
"\\cos(30^o)")) will be the sine of
![60^o](https://s0.wp.com/latex.php?latex=60%5Eo&bg=ffffff&fg=333333&s=0
"60^o"). The square root of half the square of the
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
becomes the sine of arrows (5) and veda-s (4) degrees ( i.e.
![\\sin(45^o)=\\tfrac{1}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=%5Csin%2845%5Eo%29%3D%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"\\sin(45^o)=\\tfrac{1}{\\sqrt{2}}"))

trijyā-kṛti+iṣughātāt trijyā kṛti-varga-paṅcaghātasya |  
mūlonād aṣṭa-hṛtān mūlaṃ ṣaṭ-triṃśad-aṃśajyā ||  
From arrow (5) times the square of the
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
subtract the square root of 5 times the
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R") to
the power of 4. Divide what remains from above by 8; the square root of
that gives
![\\sin(36^o)](https://s0.wp.com/latex.php?latex=%5Csin%2836%5Eo%29&bg=ffffff&fg=333333&s=0
"\\sin(36^o)") (i.e.
![\\sin(36^o)=\\sqrt{\\tfrac{5-\\sqrt{5}}{8}}](https://s0.wp.com/latex.php?latex=%5Csin%2836%5Eo%29%3D%5Csqrt%7B%5Ctfrac%7B5-%5Csqrt%7B5%7D%7D%7B8%7D%7D&bg=ffffff&fg=333333&s=0
"\\sin(36^o)=\\sqrt{\\tfrac{5-\\sqrt{5}}{8}}"))

Bhāskara then goes on to give an approximation for it as fraction:

gaja-haya-gajeṣu nighnī tribhajīvā vā ‘yutena saṃbhaktā |  
ṣaṭ-triṃśad-aṃśa-jīvā tat koṭijyā kṛteṣuṇām ||  
The ![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0
"R") multiplied by elephants (8), horses (7), elephants (8), arrows (5)
and divided by
![10^4](https://s0.wp.com/latex.php?latex=10%5E4&bg=ffffff&fg=333333&s=0
"10^4") gives the sine of
![36^o](https://s0.wp.com/latex.php?latex=36%5Eo&bg=ffffff&fg=333333&s=0
"36^o"). Its cosine is the sine of 4 and arrows (5) (i.e.
![\\sin(54^o)](https://s0.wp.com/latex.php?latex=%5Csin%2854%5Eo%29&bg=ffffff&fg=333333&s=0
"\\sin(54^o)")).

With this approximation we get ![\\sin(54^o) \\approx
0.80901](https://s0.wp.com/latex.php?latex=%5Csin%2854%5Eo%29+%5Capprox+0.80901&bg=ffffff&fg=333333&s=0
"\\sin(54^o) \\approx 0.80901") correct to 5 places after the decimal
point (one would not it is
![\\tfrac{\\phi}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cphi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\phi}{2}")) and implies that Bhāskara was using an
approximation of
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") correct to 4 places after the decimal point.

trijyā-kṛti+iṣu-ghātān mūlaṃ trijyonitaṃ caturbhaktaṃ |  
aṣṭadaśa-bhāgānāṃ jīvā spaṣṭā bhavaty evam ||  
From the square root of the product of the square of
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
and the arrows (5) subtract
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
and divide what is left by 4. This indeed becomes the exact sine of
![18^o](https://s0.wp.com/latex.php?latex=18%5Eo&bg=ffffff&fg=333333&s=0
"18^o") (i.e.
![\\sin(18^o)=\\tfrac{\\sqrt{5}-1}{4}](https://s0.wp.com/latex.php?latex=%5Csin%2818%5Eo%29%3D%5Ctfrac%7B%5Csqrt%7B5%7D-1%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\sin(18^o)=\\tfrac{\\sqrt{5}-1}{4}")).

These basic sines emerge from the first 3 constructible regular
polygons: the equilateral triangle yielding ![\\sin(30^o),
\\sin(60^o)](https://s0.wp.com/latex.php?latex=%5Csin%2830%5Eo%29%2C+%5Csin%2860%5Eo%29&bg=ffffff&fg=333333&s=0
"\\sin(30^o), \\sin(60^o)"); the square yielding
![\\sin(45^o)](https://s0.wp.com/latex.php?latex=%5Csin%2845%5Eo%29&bg=ffffff&fg=333333&s=0
"\\sin(45^o)") and finally the pentagon yields
![\\sin(18^o)](https://s0.wp.com/latex.php?latex=%5Csin%2818%5Eo%29&bg=ffffff&fg=333333&s=0
"\\sin(18^o)") and its multiples (Figure 6).

[![](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig6.png?w=640&h=418)](https://manasataramgini.files.wordpress.com/2019/07/narayana_tribonacci_fig6.png)Figure
6.

Thus, from the geometry of the regular pentagon (the proof is obvious in
Figure 6) it is seen that these values are rather easily obtained and
can be expressed in terms of the Golden ratio
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi"), which emerges in the diagonal to side ratio (Figure 6). Thus,
we have:

![\\sin\\left(\\dfrac{\\pi}{10}\\right)=\\dfrac{1}{2\\phi}](https://s0.wp.com/latex.php?latex=%5Csin%5Cleft%28%5Cdfrac%7B%5Cpi%7D%7B10%7D%5Cright%29%3D%5Cdfrac%7B1%7D%7B2%5Cphi%7D&bg=ffffff&fg=333333&s=0
"\\sin\\left(\\dfrac{\\pi}{10}\\right)=\\dfrac{1}{2\\phi}")

![\\sin\\left(\\dfrac{3\\pi}{10}\\right)=\\dfrac{\\phi}{2}](https://s0.wp.com/latex.php?latex=%5Csin%5Cleft%28%5Cdfrac%7B3%5Cpi%7D%7B10%7D%5Cright%29%3D%5Cdfrac%7B%5Cphi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sin\\left(\\dfrac{3\\pi}{10}\\right)=\\dfrac{\\phi}{2}")

Thus, we can use the first angle in the infinite series for
![\\arcsin(x)](https://s0.wp.com/latex.php?latex=%5Carcsin%28x%29&bg=ffffff&fg=333333&s=0
"\\arcsin(x)") to obtain the series for
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") in terms of
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") as:

![\\pi= 10 \\displaystyle \\sum\_{n=0}^\\infty \\dfrac{(2n)\!}{(2n+1)
\\cdot
2^{4n+1}(n\!)^2\\phi^{2n+1}}](https://s0.wp.com/latex.php?latex=%5Cpi%3D+10+%5Cdisplaystyle+%5Csum_%7Bn%3D0%7D%5E%5Cinfty+%5Cdfrac%7B%282n%29%21%7D%7B%282n%2B1%29+%5Ccdot+2%5E%7B4n%2B1%7D%28n%21%29%5E2%5Cphi%5E%7B2n%2B1%7D%7D&bg=ffffff&fg=333333&s=0
"\\pi= 10 \\displaystyle \\sum_{n=0}^\\infty \\dfrac{(2n)!}{(2n+1) \\cdot 2^{4n+1}(n!)^2\\phi^{2n+1}}")

This series fares excellently in computing
![\\pi](https://s0.wp.com/latex.php?latex=%5Cpi&bg=ffffff&fg=333333&s=0
"\\pi") — with the same 200 terms as used in the above experiments we
get the value correct 208 places after the decimal point.

Now, instead of
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") if we resort to the angle
![\\tfrac{\\pi}{6}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B6%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{6}") from the geometry of the equilateral triangle, we
get the below infinite series:

![\\pi=6 \\displaystyle \\sum\_{n=0}^\\infty
\\dfrac{(2n)\!}{(2n+1)\\cdot
2^{4n+1}(n\!)^2}](https://s0.wp.com/latex.php?latex=%5Cpi%3D6+%5Cdisplaystyle+%5Csum_%7Bn%3D0%7D%5E%5Cinfty+%5Cdfrac%7B%282n%29%21%7D%7B%282n%2B1%29%5Ccdot+2%5E%7B4n%2B1%7D%28n%21%29%5E2%7D&bg=ffffff&fg=333333&s=0
"\\pi=6 \\displaystyle \\sum_{n=0}^\\infty \\dfrac{(2n)!}{(2n+1)\\cdot 2^{4n+1}(n!)^2}")

This is obviously worse than the above series with
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") and yields 124 correct places after the point with 200 terms.
Thus, it is only marginally better than the Eulerian double angle
![\\arctan](https://s0.wp.com/latex.php?latex=%5Carctan&bg=ffffff&fg=333333&s=0
"\\arctan") series in its performance.
