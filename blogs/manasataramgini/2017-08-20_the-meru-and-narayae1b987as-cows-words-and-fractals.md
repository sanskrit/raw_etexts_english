+++
title = "The Meru and Nārāyaṇa’s cows: Words and fractals"

+++
The fractals described herein are based on and inspired by the work of
the mathematicians Rauzy, Mendes-France, Monnerot and Knuth. Some their
works, especially the first of them, are dense with formalism. Here we
present in simple terms the means of generating and visualizing these
remarkable objects which anyone with high-school mathematics and
computer skills can reproduce and enjoy.

The “prehistory” of these objects goes back to their discovery among the
Hindus. Old Indo-Aryan hieratic and epic poetry primarily utilized
meters which were based on the count of the syllables. Thus, the famous
gāyatrī meter had 8 syllables in each of its three feet amounting to a
total of 24. Alongside these meters which conserved syllable count there
were other meters which conserved total syllable length or duration in
temporal terms. These appear to have originally been primarily used in
secular poetry and maxims though later are witnessed more widely in
different types of texts. Syllables come in two lengths or morae — short
(laghu) and long (guru). Thus, in these meters their count of morae had
to add up to a constant. Let us denote laghu by 0 (=1 mora) and guru by
1 (=2 morae). If we had a meter/metrical unit of just one mora then it
had to be just 0; for two morae units we can have: 1 or 00; for three
morae units we have: 10, 01, 000; for four morae units we have: 11, 100,
010, 001, 0000. If we write it the traditional Hindu way we get:  
![\\begin{matrix} & & & & 1 & & & & &\\\\ & & & 1 & & 00 & & & &\\\\ & &
10& & 01 & 000 & & & &\\\\ & & 11&100 & 010& 001 & 0000 & & &\\\\
110&011&101&1000 & &0100 & 0010 & 0001 & 00000 &\\\\
\\end{matrix}](https://s0.wp.com/latex.php?latex=%5Cbegin%7Bmatrix%7D+%26+%26+%26+%26+1+%26+%26+%26+%26+%26%5C%5C+%26+%26+%26+1+%26+%26+00+%26+%26+%26+%26%5C%5C+%26+%26+10%26+%26+01+%26+000+%26+%26+%26+%26%5C%5C+%26+%26+11%26100+%26+010%26+001+%26+0000+%26+%26+%26%5C%5C+110%26011%26101%261000+%26+%260100+%26+0010+%26+0001+%26+00000+%26%5C%5C+%5Cend%7Bmatrix%7D&bg=ffffff&fg=333333&s=0
"\\begin{matrix} & & & & 1 & & & & &\\\\ & & & 1 & & 00 & & & &\\\\ & & 10& & 01 & 000 & & & &\\\\ & & 11&100 & 010& 001 & 0000 & & &\\\\ 110&011&101&1000 & &0100 & 0010 & 0001 & 00000 &\\\\ \\end{matrix}")

This arrangement of the combinations for each mora-length was seen as
resembling a mountain and duly termed Meru by the ancient Hindus. They
also noted that the total number of permutations for each mora-length
forms a sequence (1, 2, 3, 5, 8…) which is the famous Meru-średhi.

This idea can be extended to generate Meru words. One way of doing so is
using the following substitution rules: ![0 \\rightarrow 01;
1\\rightarrow
0](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+01%3B+1%5Crightarrow+0&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 01; 1\\rightarrow 0"). To make the word we start with
the initial word 1 and recursively apply the above substitution rules.
Thus we get:  
1  
0  
01  
010  
01001  
01001010  
0100101001001  
010010100100101001010

We notice that length of the Meru word grows as the Meru-średhi towards
infinity. If we observe the pattern within each word we notice that it
is not periodic yet there is a structure to it. Importantly,

![\\displaystyle \\lim\_{n \\to
\\infty}\\dfrac{N(0)}{N(1)}=\\phi](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+%5Clim_%7Bn+%5Cto+%5Cinfty%7D%5Cdfrac%7BN%280%29%7D%7BN%281%29%7D%3D%5Cphi&bg=ffffff&fg=333333&s=0
"\\displaystyle \\lim_{n \\to \\infty}\\dfrac{N(0)}{N(1)}=\\phi")

The ratio of 0s to 1s in the Meru word converges to the Golden ratio.
For example for the 22nd Meru word we have 10946 0s and 6765 1s which
approximates the
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") correctly to 8 decimal places. But to get a better picture of
the structure of the word we perform the following operation:

1\) Take a Meru word. Start of by drawing a segment in the horizontal
direction.  
2\) If you encounter a laghu syllable in the word, i.e. a 0 then draw
another segment in the same direction as the current one.  
3\) If instead you encounter a guru syllable in the word i.e. a 1 then
check if the syllable is at an even or odd position.  
4\) If 1 is at an even position then turn counter-clockwise by some
angle, say
![\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{2}"), and draw the segment.  
5\) If 1 is at an odd position then turn clockwise by the same angle as
above and draw the segment.  
6\) Continue thus till the end of the word.

Figure 1 shows the result of this operation on the 22nd Meru word of
length 17711 with angle of rotation as ![\\pm
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Cpm+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\pm \\tfrac{\\pi}{2}").

[![Meru\_simple\_rule](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_rule.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_rule.png)Figure
1

The result is a striking fractal curve that is tightly folded but never
crosses itself. The aligment of the folds give the impression of “lines”
forming kites and arrowheads with angles of ![\\tfrac{\\pi}{4},
\\tfrac{3\\pi}{4},
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B%5Cpi%7D%7B4%7D%2C+%5Ctfrac%7B3%5Cpi%7D%7B4%7D%2C+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\tfrac{\\pi}{4}, \\tfrac{3\\pi}{4}, \\tfrac{\\pi}{2}") passing through
the fractal. We can also visualize this as the process of folding a
“polymeric” string made up of segment monomers of the length of a Meru
number of segments. The monomers either continue in the same direction
or turn by a given angle in one direction or the opposite as per the
sequence. Instead of turning
![90^o](https://s0.wp.com/latex.php?latex=90%5Eo&bg=ffffff&fg=333333&s=0
"90^o") we can turn by other angles too.

[![meru\_simple\_hexagon](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_hexagon.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_hexagon.png)Figure
2. Turning by ![\\pm
60^o](https://s0.wp.com/latex.php?latex=%5Cpm+60%5Eo&bg=ffffff&fg=333333&s=0
"\\pm 60^o")

This results in fractal that is superficially reminiscent of the famous
von Koch curve but is clearly different from it. It has a core
“hexagonal” symmetry which can be simulated by drawing hexagons at the
vertices of a core hexagon and repeating it.

[![meru\_simple\_pentago](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_pentago.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_simple_pentago.png)Figure
3. Turning by ![\\pm
72^o](https://s0.wp.com/latex.php?latex=%5Cpm+72%5Eo&bg=ffffff&fg=333333&s=0
"\\pm 72^o")

This operation is similar to the above one but by virtue of its angle
generates a “pentagonal” symmetry. These examples establish the innate
fractal structure of the Meru words.

We had seen earlier that given a quadratic surd
![q](https://s0.wp.com/latex.php?latex=q&bg=ffffff&fg=333333&s=0 "q") we
can perform the following operation:  
![s=\\left \\lfloor{(n+1)q}\\right \\rfloor - \\left \\lfloor{nq}\\right
\\rfloor, \\; n \\in
\\mathbb{N}](https://s0.wp.com/latex.php?latex=s%3D%5Cleft+%5Clfloor%7B%28n%2B1%29q%7D%5Cright+%5Crfloor+-+%5Cleft+%5Clfloor%7Bnq%7D%5Cright+%5Crfloor%2C+%5C%3B+n+%5Cin+%5Cmathbb%7BN%7D&bg=ffffff&fg=333333&s=0
"s=\\left \\lfloor{(n+1)q}\\right \\rfloor - \\left \\lfloor{nq}\\right \\rfloor, \\; n \\in \\mathbb{N}")

It generates a sequence which can be represented as a word in a two
letter alphabet (i.e in 0 and 1). For a quadratic surd but not
transcendental number we can even figure out a substitution rule which
generates that pattern. For the Golden ratio the pattern is the same as
what we get by the above substitution operation to generate the Meru
word. The words for
![\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}") or
![\\sqrt{3}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{3}") when subject to the above drawing mechanism, unlike that
for the Golden ratio do not generate a fractal pattern. However, we
discovered words generated in a 3-letter alphabet that encode
![\\sqrt{3}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{3}") or
![\\sin(\\tfrac{\\pi}{3})](https://s0.wp.com/latex.php?latex=%5Csin%28%5Ctfrac%7B%5Cpi%7D%7B3%7D%29&bg=ffffff&fg=333333&s=0
"\\sin(\\tfrac{\\pi}{3})") which can result in fractal curves (see
below). In any case, sticking to the 2-letter alphabet for now, a
substitution rule which generates words where the ratio of 0s to 1s
converges to
![1+\\sqrt{2}](https://s0.wp.com/latex.php?latex=1%2B%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"1+\\sqrt{2}"), also called the Silver ratio, generates a fractal curve
with an underlying bifurcating pattern symmetry (Figure 4).

[![meru\_root2plus1\_word](https://manasataramgini.files.wordpress.com/2017/08/meru_root2plus1_word.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_root2plus1_word.png)Figure
4. Rule: ![0 \\rightarrow 001;\\; 1\\rightarrow
0](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+001%3B%5C%3B+1%5Crightarrow+0&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 001;\\; 1\\rightarrow 0"), Silver ratio.

Notably, a rule which generates 0s and 1s in 1:1 ratio also generates a
fractal, which is equivalent to that generated by iterative removal of a
rectangle from a half-square isoceles triangle (Figure 5).

[![Meru\_1isto1\_rule](https://manasataramgini.files.wordpress.com/2017/08/meru_1isto1_rule.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_1isto1_rule.png)Figure
5. Rule: ![0 \\rightarrow 011;\\; 1 \\rightarrow
010](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+011%3B%5C%3B+1+%5Crightarrow+010&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 011;\\; 1 \\rightarrow 010")

We can generate Meru words by yet another method: Start with
![w\_1=0,\\;
w\_2=1](https://s0.wp.com/latex.php?latex=w_1%3D0%2C%5C%3B+w_2%3D1&bg=ffffff&fg=333333&s=0
"w_1=0,\\; w_2=1"). Then concatenate the current word with the previous
one to get the next word:
![w\_{n+1}=w\_{n}w\_{n-1}](https://s0.wp.com/latex.php?latex=w_%7Bn%2B1%7D%3Dw_%7Bn%7Dw_%7Bn-1%7D&bg=ffffff&fg=333333&s=0
"w_{n+1}=w_{n}w_{n-1}"). This generates the words (
![w\_1:w\_5](https://s0.wp.com/latex.php?latex=w_1%3Aw_5&bg=ffffff&fg=333333&s=0
"w_1:w_5") shown):  
0  
1  
01  
101  
01101

One will notice a relationship of these words with a particular
mora-count of the Hindu metrical system (0 and 1 inverted). Meru words
generated by this mechanism will have the ratio of 1s to 0s converge to
the Golden ratio. Applying the above drawing procedure results in a
non-crossing fractal related to, but distinct from, the Meru curve
obtained by the above procedure (Figure 6).

[![Meru\_concat](https://manasataramgini.files.wordpress.com/2017/08/meru_concat.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_concat.png)Figure
6. Concatenated Meru curve, rule: ![w\_1=0,\\;
w\_2=1](https://s0.wp.com/latex.php?latex=w_1%3D0%2C%5C%3B+w_2%3D1&bg=ffffff&fg=333333&s=0
"w_1=0,\\; w_2=1")

If we start with ![w\_1=0,\\;
w\_2=001](https://s0.wp.com/latex.php?latex=w_1%3D0%2C%5C%3B+w_2%3D001&bg=ffffff&fg=333333&s=0
"w_1=0,\\; w_2=001") and apply the same procedure then we get words
which have ratio of 0s to 1s converging to the square of the Golden
ratio
![\\phi^2](https://s0.wp.com/latex.php?latex=%5Cphi%5E2&bg=ffffff&fg=333333&s=0
"\\phi^2").

Now instead of a 2-letter alphabet we can next try a 3-letter alphabet
(0,1,2). Here, instead of the even-odd evaluation for turning we can
instead use 0 as an injunction to continue in the same direction, 1 to
turn counter-clockwise by a given angle and 2 to turn clockwise by the
same angle. We discovered that a series of rules which generate words
where the ratio of 0s to 1s and 2s converges to
![\\sqrt{3}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{3}") generate a wide range of distinct fractal curves (angle
![\\pm
\\tfrac{\\pi}{2}](https://s0.wp.com/latex.php?latex=%5Cpm+%5Ctfrac%7B%5Cpi%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\pm \\tfrac{\\pi}{2}")):

[![meru\_3letter.1](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-1.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-1.png)Figure
7. Rule ![0 \\rightarrow 210; \\; 1 \\rightarrow 020; \\; 2 \\rightarrow
10](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+210%3B+%5C%3B+1+%5Crightarrow+020%3B+%5C%3B+2+%5Crightarrow+10&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 210; \\; 1 \\rightarrow 020; \\; 2 \\rightarrow 10")

[![meru\_3letter.2](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-2.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-2.png)Figure
8. Rule ![0 \\rightarrow 120; 1\\rightarrow 020; \\; 2\\rightarrow
10](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+120%3B+1%5Crightarrow+020%3B+%5C%3B+2%5Crightarrow+10&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 120; 1\\rightarrow 020; \\; 2\\rightarrow 10")

[![meru\_3letter.3](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-3.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-3.png)Figure
9. ![0 \\rightarrow 120; 1\\rightarrow 020; \\; 2\\rightarrow
01](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+120%3B+1%5Crightarrow+020%3B+%5C%3B+2%5Crightarrow+01&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 120; 1\\rightarrow 020; \\; 2\\rightarrow 01")

[![meru\_3letter.4](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-4.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-4.png)Figure
10. ![0 \\rightarrow 012; 1\\rightarrow 200; \\; 2\\rightarrow
10](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+012%3B+1%5Crightarrow+200%3B+%5C%3B+2%5Crightarrow+10&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 012; 1\\rightarrow 200; \\; 2\\rightarrow 10")

[![meru\_3letter.5](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-5.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_3letter-5.png)Figure
11. ![0 \\rightarrow 210; 1\\rightarrow 020; \\; 2\\rightarrow
10](https://s0.wp.com/latex.php?latex=0+%5Crightarrow+210%3B+1%5Crightarrow+020%3B+%5C%3B+2%5Crightarrow+10&bg=ffffff&fg=333333&s=0
"0 \\rightarrow 210; 1\\rightarrow 020; \\; 2\\rightarrow 10")

There are more of these curves which potentially deserve a more
systematic study. We have merely provided some of the visually most
interesting examples. The first four of these curves are non-crossing
curves.

Such curves might also be generated using an analogy drawn from
biochemistry. The sequences nucleic acids are in a 4-letter alphabet.
These (specifically that of RNA) is translated by the ribosome into
proteins which are in a 20-letter alphabet. To encode a 20-letter
alphabet with just a 4 letter alphabet you have to assign a mapping to
strings of length greater than 2 in the 4-letter nucleic acid alphabet
to the letters in the 20-letter alphabet of proteins. This mapping is
the genetic code. We can thus map the Meru word in a 2-letter alphabet
on to a 3-letter alphabet of 0,1,2 by making 2-letter strings in the
Meru word encode letters in the 3-letter space. Thus, we get translated
words. As in the above 3-letter alphabet case while folding the
translated word we simply interpret the 0 as a directive to draw a
segment in the same direction, 1 as a counter-clockwise turn by a given
angle and 2 as a clockwise turn by the same angle. By applying this
folding rule we can now generate curves with different translation
rules:

[![meru\_dense.1](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-1.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-1.png)Figure
12. Rule ![00 \\rightarrow 0; \\; 01 \\rightarrow 1; \\; 10 \\rightarrow
2](https://s0.wp.com/latex.php?latex=00+%5Crightarrow+0%3B+%5C%3B+01+%5Crightarrow+1%3B+%5C%3B+10+%5Crightarrow+2&bg=ffffff&fg=333333&s=0
"00 \\rightarrow 0; \\; 01 \\rightarrow 1; \\; 10 \\rightarrow 2"). This
simple translation produces an armless svastika-like curve.

[![meru\_dense.2](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-2.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-2.png)Figure
13. Rule ![00 \\rightarrow 12; \\; 01 \\rightarrow 1; \\; 10
\\rightarrow
2](https://s0.wp.com/latex.php?latex=00+%5Crightarrow+12%3B+%5C%3B+01+%5Crightarrow+1%3B+%5C%3B+10+%5Crightarrow+2&bg=ffffff&fg=333333&s=0
"00 \\rightarrow 12; \\; 01 \\rightarrow 1; \\; 10 \\rightarrow 2") This
translation produces a crossing curve with some resemblance to the loops
in the sand/flour alaṃkāra patterns.

[![meru\_dense.3](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-3.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-3.png)Figure
14. Rule ![00 \\rightarrow 21; \\; 01 \\rightarrow 02; \\; 10
\\rightarrow
10](https://s0.wp.com/latex.php?latex=00+%5Crightarrow+21%3B+%5C%3B+01+%5Crightarrow+02%3B+%5C%3B+10+%5Crightarrow+10&bg=ffffff&fg=333333&s=0
"00 \\rightarrow 21; \\; 01 \\rightarrow 02; \\; 10 \\rightarrow 10")
This a svastika-like non-crossing pattern.

[![meru\_dense.5](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-5.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/meru_dense-5.png)Figure
15. Rule ![00 \\rightarrow 210; \\; 01 \\rightarrow 010; \\; 10
\\rightarrow
20](https://s0.wp.com/latex.php?latex=00+%5Crightarrow+210%3B+%5C%3B+01+%5Crightarrow+010%3B+%5C%3B+10+%5Crightarrow+20&bg=ffffff&fg=333333&s=0
"00 \\rightarrow 210; \\; 01 \\rightarrow 010; \\; 10 \\rightarrow 20")
This a stepped variant of the basic Meru curve.

Now the question arises as to whether we can generate words
corresponding to Nārāyaṇa’s classic dhenu sequence just as we did with
the Meru sequence. It turns out that we can generate a set of simple
substitution rules in a 3-letter alphabet (we use 1,2,3 here simply for
some plotting conveniences) along the lines of the Meru sequence: ![1
\\rightarrow 12; \\; 2 \\rightarrow 3; \\; 3 \\rightarrow
1](https://s0.wp.com/latex.php?latex=1+%5Crightarrow+12%3B+%5C%3B+2+%5Crightarrow+3%3B+%5C%3B+3+%5Crightarrow+1&bg=ffffff&fg=333333&s=0
"1 \\rightarrow 12; \\; 2 \\rightarrow 3; \\; 3 \\rightarrow 1").
Application of these rules on
![w\_0=1](https://s0.wp.com/latex.php?latex=w_0%3D1&bg=ffffff&fg=333333&s=0
"w_0=1") gives us the following set of dhenu words (up to
![w\_6](https://s0.wp.com/latex.php?latex=w_6&bg=ffffff&fg=333333&s=0
"w_6")):  
1  
12  
123  
1231  
123112  
123112123

We note that the length of these words is the classic dhenu sequence, 1,
2, 3, 4, 6, 9… Further, in these words the ratio of 1s to 2s and 2s to
3s converges to Nārāyaṇa’s convergent
![N\_c=1.46557123](https://s0.wp.com/latex.php?latex=N_c%3D1.46557123&bg=ffffff&fg=333333&s=0
"N_c=1.46557123"). The ratio of 1s to 3s converges to
![N\_c^2](https://s0.wp.com/latex.php?latex=N_c%5E2&bg=ffffff&fg=333333&s=0
"N_c^2").

In the previous article we noted (see Figure 2) that the Hofstadter
sequence, which is related to the dhenu sequence, has a fixed bandwidth
when rectified. Moreover, the individual oscillations have a range of
fixed amplitudes but the pattern of oscillations is not periodic despite
showing some pattern. Indeed, the pattern of 1, 2, and 3 in the dhenu
words is again not periodic but shows a peculiar pattern which can be
captured by making circles of diameter 1, 2 and 3 and plotting them
based on the dhenu words (shown below for ![w\_{12}; \\;
l=88](https://s0.wp.com/latex.php?latex=w_%7B12%7D%3B+%5C%3B+l%3D88&bg=ffffff&fg=333333&s=0
"w_{12}; \\; l=88")):

[![nArAyaNa\_circles](https://manasataramgini.files.wordpress.com/2017/08/narayana_circles.jpg?w=640)](https://manasataramgini.files.wordpress.com/2017/08/narayana_circles.jpg)Figure
16.

Lurking within this pattern is a deep fractal structure that can be
unpacked by using Rauzy’s analysis of such words. The first step for
this involves construction of a matrix which captures the dhenu word
generator. The matrix is a ![3\\times
3](https://s0.wp.com/latex.php?latex=3%5Ctimes+3&bg=ffffff&fg=333333&s=0
"3\\times 3") matrix because we have a 3-letter alphabet with 3
substitution rules — the rows are for the substitutions and the columns
for the alphabets.  
\-The first rule ![1 \\rightarrow
12](https://s0.wp.com/latex.php?latex=1+%5Crightarrow+12&bg=ffffff&fg=333333&s=0
"1 \\rightarrow 12") puts one element in the first and one in the second
alphabet column.  
\-the second rule ![2 \\rightarrow
3](https://s0.wp.com/latex.php?latex=2+%5Crightarrow+3&bg=ffffff&fg=333333&s=0
"2 \\rightarrow 3") puts one element in the third alphabet column.  
\-the third rule ![3 \\rightarrow
1](https://s0.wp.com/latex.php?latex=3+%5Crightarrow+1&bg=ffffff&fg=333333&s=0
"3 \\rightarrow 1") puts one element in the first alphabet column. Thus
we can write out the matrix:

![M= \\begin{bmatrix} 1 & 1 & 0\\\\ 0 & 0 & 1\\\\ 1 & 0 & 0\\\\
\\end{bmatrix}](https://s0.wp.com/latex.php?latex=M%3D+%5Cbegin%7Bbmatrix%7D+1+%26+1+%26+0%5C%5C+0+%26+0+%26+1%5C%5C+1+%26+0+%26+0%5C%5C+%5Cend%7Bbmatrix%7D&bg=ffffff&fg=333333&s=0
"M= \\begin{bmatrix} 1 & 1 & 0\\\\ 0 & 0 & 1\\\\ 1 & 0 & 0\\\\ \\end{bmatrix}")

The eigenvalues of our matrix are: 1.465571, -0.23278+0.79255i,
-0.23278-0.79255i, the solutions of
![x^3-x^2-1=0](https://s0.wp.com/latex.php?latex=x%5E3-x%5E2-1%3D0&bg=ffffff&fg=333333&s=0
"x^3-x^2-1=0") which we encountered in the previous article in the
context of the dhenu sequence. The one real value is
![N\_c](https://s0.wp.com/latex.php?latex=N_c&bg=ffffff&fg=333333&s=0
"N_c"). The other two values indicate that
![N\_c](https://s0.wp.com/latex.php?latex=N_c&bg=ffffff&fg=333333&s=0
"N_c") is a Pisot-Vijayaraghavan number.

In the next step we find the eigenvectors of the matrix. Recall that if
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A") is
a ![n \\times
n](https://s0.wp.com/latex.php?latex=n+%5Ctimes+n&bg=ffffff&fg=333333&s=0
"n \\times n") matrix then
![(A-\\lambda)\\vec{v}=0](https://s0.wp.com/latex.php?latex=%28A-%5Clambda%29%5Cvec%7Bv%7D%3D0&bg=ffffff&fg=333333&s=0
"(A-\\lambda)\\vec{v}=0"), where
![\\lambda](https://s0.wp.com/latex.php?latex=%5Clambda&bg=ffffff&fg=333333&s=0
"\\lambda") is an eigenvalue of the matrix and
![\\vec{v}](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv%7D&bg=ffffff&fg=333333&s=0
"\\vec{v}") is the corresponding eigenvector. For our above matrix we
get the three eigenvectors as:  
![\\vec{v\_1}=\\langle -0.77098, -0.35894,
-0.52606\\rangle](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_1%7D%3D%5Clangle+-0.77098%2C+-0.35894%2C+-0.52606%5Crangle&bg=ffffff&fg=333333&s=0
"\\vec{v_1}=\\langle -0.77098, -0.35894, -0.52606\\rangle")  
![\\vec{v\_2} =\\langle -0.39162-0.25177i, 0.68232, -0.15883+0.54078i
\\rangle](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_2%7D+%3D%5Clangle+-0.39162-0.25177i%2C+0.68232%2C+-0.15883%2B0.54078i+%5Crangle&bg=ffffff&fg=333333&s=0
"\\vec{v_2} =\\langle -0.39162-0.25177i, 0.68232, -0.15883+0.54078i \\rangle")  
![\\vec{v\_3}=\\langle -0.39162+0.25177i, 0.68232, -0.15883-0.54078i
\\rangle](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_3%7D%3D%5Clangle+-0.39162%2B0.25177i%2C+0.68232%2C+-0.15883-0.54078i+%5Crangle&bg=ffffff&fg=333333&s=0
"\\vec{v_3}=\\langle -0.39162+0.25177i, 0.68232, -0.15883-0.54078i \\rangle")

The eigenvector
![\\vec{v\_1}](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_1%7D&bg=ffffff&fg=333333&s=0
"\\vec{v_1}") has all real-valued components; hence, we drop it. The
next two eigenvectors have one real-valued component which is equal to
the rectification value of the Hofstader H sequence which we encountered
in the previous article. The remaining two values are complex and also
conjugates of each other between the two eigenvectors. Hence, we may use
either vector for the next step.

The next step involves first taking a long dhenu word
![w\_j](https://s0.wp.com/latex.php?latex=w_j&bg=ffffff&fg=333333&s=0
"w_j") (e.g. ![w\_{28}; \\;
l=39865](https://s0.wp.com/latex.php?latex=w_%7B28%7D%3B+%5C%3B+l%3D39865&bg=ffffff&fg=333333&s=0
"w_{28}; \\; l=39865")). We define a sub-word of a
![w\_{j,k}](https://s0.wp.com/latex.php?latex=w_%7Bj%2Ck%7D&bg=ffffff&fg=333333&s=0
"w_{j,k}"), which means the first
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
letters of word
![w\_j](https://s0.wp.com/latex.php?latex=w_j&bg=ffffff&fg=333333&s=0
"w_j"). We start with the first sub-word which includes all 3 letters of
the alphabet. That would be
![w\_{j,3}=123](https://s0.wp.com/latex.php?latex=w_%7Bj%2C3%7D%3D123&bg=ffffff&fg=333333&s=0
"w_{j,3}=123"). From there we increment
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k") by
1 until we reach the end of the word
![w\_j](https://s0.wp.com/latex.php?latex=w_j&bg=ffffff&fg=333333&s=0
"w_j"). Now for each such sub-word
![w\_{j,k}](https://s0.wp.com/latex.php?latex=w_%7Bj%2Ck%7D&bg=ffffff&fg=333333&s=0
"w_{j,k}") we calculate the frequency of 1s, 2s and 3s; respectively
denoted as
![f\_1,f\_2,f\_3](https://s0.wp.com/latex.php?latex=f_1%2Cf_2%2Cf_3&bg=ffffff&fg=333333&s=0
"f_1,f_2,f_3"). Then we multiple these frequencies by the corresponding
component of the eigenvector (in our case
![\\vec{v\_2}](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_2%7D&bg=ffffff&fg=333333&s=0
"\\vec{v_2}") or
![\\vec{v\_3}](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_3%7D&bg=ffffff&fg=333333&s=0
"\\vec{v_3}") and sum up the three values:

![\\displaystyle S\_k=\\sum\_{n=1}^3 f\_n\\cdot v\_{2,n} = f\_1\\cdot
v\_{2,1}+f\_2\\cdot v\_{2,2}+f\_3\\cdot
v\_{2,3}](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+S_k%3D%5Csum_%7Bn%3D1%7D%5E3+f_n%5Ccdot+v_%7B2%2Cn%7D+%3D+f_1%5Ccdot+v_%7B2%2C1%7D%2Bf_2%5Ccdot+v_%7B2%2C2%7D%2Bf_3%5Ccdot+v_%7B2%2C3%7D&bg=ffffff&fg=333333&s=0
"\\displaystyle S_k=\\sum_{n=1}^3 f_n\\cdot v_{2,n} = f_1\\cdot v_{2,1}+f_2\\cdot v_{2,2}+f_3\\cdot v_{2,3}")

The same may be done with
![\\vec{v\_3}](https://s0.wp.com/latex.php?latex=%5Cvec%7Bv_3%7D&bg=ffffff&fg=333333&s=0
"\\vec{v_3}") too. The result of each sum will be a complex number and
as we traverse the word
![w\_j](https://s0.wp.com/latex.php?latex=w_j&bg=ffffff&fg=333333&s=0
"w_j") we will get a set of
![l(w\_j)-3](https://s0.wp.com/latex.php?latex=l%28w_j%29-3&bg=ffffff&fg=333333&s=0
"l(w_j)-3") complex numbers in our case. If the
![k^{th}](https://s0.wp.com/latex.php?latex=k%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"k^{th}") letter is a 1 then we assign then we assign color red for the
set of complex numbers derived at that letter; if it is a 2 we assign
color blue; if it is a 3 we assign color green. The sizes of these three
color sets will be in the proportion of
![N\_c](https://s0.wp.com/latex.php?latex=N_c&bg=ffffff&fg=333333&s=0
"N_c") and
![N\_c^2](https://s0.wp.com/latex.php?latex=N_c%5E2&bg=ffffff&fg=333333&s=0
"N_c^2") to each other. Remarkably, when we plot each of these three
sets we find that they neatly segregate into three similar fractals.
Even more remarkably, the three distinctly colored copies define a
fractal tiling of the complex plane (Figure 17).

[![nArAyaNa\_word\_Rauzy](https://manasataramgini.files.wordpress.com/2017/08/narayana_word_rauzy.png?w=570&h=570)](https://manasataramgini.files.wordpress.com/2017/08/narayana_word_rauzy.png)

Figure 17.

Seeing this fractal tiling manifest from the dhenu words we were
reminded of the ideas of our ancestors on words manifesting form.
