+++
title = "Wisdom from a tag system"

+++
The case of the mathematician Emil Post, like that of several others,
indicates how the boundary between mania and mathematics can be a thin
one. Nevertheless, Post discovered some rather interesting things that
were to have fundamental implications the theory of computation. One of
his discoveries was an interesting class of systems that have come to be
termed as tag systems. In its simplest form such a system might be
defined thus: We start with a string of the form
![gx\_1x\_2...x\_n](https://s0.wp.com/latex.php?latex=gx_1x_2...x_n&bg=ffffff&fg=333333&s=0
"gx_1x_2...x_n") where
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g") is
a specific string. If it is encountered at the beginning of the string
then we apply the rule:  
![gx\_1x\_2...x\_n\\rightarrow
x\_2...x\_nx\_{n+1}h](https://s0.wp.com/latex.php?latex=gx_1x_2...x_n%5Crightarrow+x_2...x_nx_%7Bn%2B1%7Dh&bg=ffffff&fg=333333&s=0
"gx_1x_2...x_n\\rightarrow x_2...x_nx_{n+1}h")  
What it means is that we cut
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g")
and some specified number of elements from the start of the string (in
this case 1 element in addition to
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g"))
and paste string
![h](https://s0.wp.com/latex.php?latex=h&bg=ffffff&fg=333333&s=0 "h") at
the end of string along with a specified number of elements (again 1) in
this case.

As a concrete example let us consider the below tag system with three
rules (said to be devised by de Mol):  
![h(a)=bc](https://s0.wp.com/latex.php?latex=h%28a%29%3Dbc&bg=ffffff&fg=333333&s=0
"h(a)=bc")  
![h(b)=a](https://s0.wp.com/latex.php?latex=h%28b%29%3Da&bg=ffffff&fg=333333&s=0
"h(b)=a")  
![h(c)=aaa](https://s0.wp.com/latex.php?latex=h%28c%29%3Daaa&bg=ffffff&fg=333333&s=0
"h(c)=aaa")  
![v=2](https://s0.wp.com/latex.php?latex=v%3D2&bg=ffffff&fg=333333&s=0
"v=2")  
Here the first three rules specify the
![h](https://s0.wp.com/latex.php?latex=h&bg=ffffff&fg=333333&s=0 "h")
that should be pasted at the end of the string if
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g") is
respectively
![a,b,c](https://s0.wp.com/latex.php?latex=a%2Cb%2Cc&bg=ffffff&fg=333333&s=0
"a,b,c"). The fourth
![v=2](https://s0.wp.com/latex.php?latex=v%3D2&bg=ffffff&fg=333333&s=0
"v=2") specifies that for every
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g")
that is cut at the beginning of the string we additionally remove one
more element i.e. a total of two elements from the beginning of the
string. Moreover, it also indicates that if the string length falls
below 2 we can no longer remove 2 elements hence the process halts. As
an example we can consider a simple starting string
![aaa](https://s0.wp.com/latex.php?latex=aaa&bg=ffffff&fg=333333&s=0
"aaa") and start applying the above rules:

![aaa \\rightarrow abc \\rightarrow cbc \\rightarrow caaa \\rightarrow
aaaaa \\rightarrow \\\\ aaabc \\rightarrow abcbc \\rightarrow cbcbc
\\rightarrow cbcaaa \\rightarrow caaaaaa \\rightarrow \\\\ aaaaaaaa
\\rightarrow aaaaaabc \\rightarrow aaaabcbc \\rightarrow aabcbcbc
\\rightarrow bcbcbcbc \\rightarrow \\\\ bcbcbca \\rightarrow bcbcaa
\\rightarrow bcaaa \\rightarrow aaaa \\rightarrow aabc \\rightarrow \\\\
bcbc \\rightarrow bca \\rightarrow aa \\rightarrow bc \\rightarrow
a](https://s0.wp.com/latex.php?latex=aaa+%5Crightarrow+abc+%5Crightarrow+cbc+%5Crightarrow+caaa+%5Crightarrow+aaaaa+%5Crightarrow+%5C%5C+aaabc+%5Crightarrow+abcbc+%5Crightarrow+cbcbc+%5Crightarrow+cbcaaa+%5Crightarrow+caaaaaa+%5Crightarrow+%5C%5C+aaaaaaaa+%5Crightarrow+aaaaaabc+%5Crightarrow+aaaabcbc+%5Crightarrow+aabcbcbc+%5Crightarrow+bcbcbcbc+%5Crightarrow+%5C%5C+bcbcbca+%5Crightarrow+bcbcaa+%5Crightarrow+bcaaa+%5Crightarrow+aaaa+%5Crightarrow+aabc+%5Crightarrow+%5C%5C+bcbc+%5Crightarrow+bca+%5Crightarrow+aa+%5Crightarrow+bc+%5Crightarrow+a&bg=ffffff&fg=333333&s=0
"aaa \\rightarrow abc \\rightarrow cbc \\rightarrow caaa \\rightarrow aaaaa \\rightarrow \\\\ aaabc \\rightarrow abcbc \\rightarrow cbcbc \\rightarrow cbcaaa \\rightarrow caaaaaa \\rightarrow \\\\ aaaaaaaa \\rightarrow aaaaaabc \\rightarrow aaaabcbc \\rightarrow aabcbcbc \\rightarrow bcbcbcbc \\rightarrow \\\\ bcbcbca \\rightarrow bcbcaa \\rightarrow bcaaa \\rightarrow aaaa \\rightarrow aabc \\rightarrow \\\\ bcbc \\rightarrow bca \\rightarrow aa \\rightarrow bc \\rightarrow a")

Thus the system evolves for 25 cycles before coming to a halt as the
string length drops to 1 at
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
We can further plot this as a graph where each string is presented as a
height as the system evolves(Figure 1).

[![tag\_a3](https://manasataramgini.files.wordpress.com/2017/08/tag_a3.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/tag_a3.png)

[![tag\_a3\_entropy](https://manasataramgini.files.wordpress.com/2017/08/tag_a3_entropy.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/tag_a3_entropy.png)Figure
1 and Figure 2 (lower panel)

The evolution of the system presents two interesting features: 1) a
step-wise growth, peaking and decay of the length of the string. 2) The
complexity of the string which can be measured by its entropy rises and
falls periodically. The entropy of the string is calculated using the
famous equation of Claude Shannon:  
![H=\\displaystyle -\\sum\_{j=1}^n
p\_i\\log\_2(p\_i)](https://s0.wp.com/latex.php?latex=H%3D%5Cdisplaystyle+-%5Csum_%7Bj%3D1%7D%5En+p_i%5Clog_2%28p_i%29&bg=ffffff&fg=333333&s=0
"H=\\displaystyle -\\sum_{j=1}^n p_i\\log_2(p_i)"),  
Where
![p\_i](https://s0.wp.com/latex.php?latex=p_i&bg=ffffff&fg=333333&s=0
"p_i") is the probability of the
![i^{th}](https://s0.wp.com/latex.php?latex=i%5E%7Bth%7D&bg=ffffff&fg=333333&s=0
"i^{th}") character appearing in the string. For each cycle this is
plotted in Figure 2.

This plot shows the entropy minimal whenever the string falls to the
lowest complexity in the form of all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").

Now let us seed the same system with the starting string
![aaaaaaaaa](https://s0.wp.com/latex.php?latex=aaaaaaaaa&bg=ffffff&fg=333333&s=0
"aaaaaaaaa") i.e. 9 successive
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and see it evolve. Here it evolves for 153 cycles before finally halting
(Figure 3, 4).

[![Tag\_a9](https://manasataramgini.files.wordpress.com/2017/08/tag_a9.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/tag_a9.png)[![Tag\_a9\_entropy](https://manasataramgini.files.wordpress.com/2017/08/tag_a9_entropy.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/tag_a9_entropy.png)Figure
3 and Figure 4 (lower panel)

This longer evolution is accompanied by greater number of higher order
cycles of rises and falls. Yet the overall structure is similar to the
previous case where it evolved for only 25 cycles. Notably, we see a
similar pattern of entropy evolution of the strings.The rise to maximal
string length in the form of all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
string results in an entropy minimum followed by complexification at
same length to reach paired maxima separated by a central dip in
entropy. This is followed by change in string length with the entropy
showing a similar cycle for this new string length. A closer look at the
strings in the first example suggests that we reach minimal entropy with
all ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a") strings with respectively 3, 5, 8, 4, 2, 1
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")-s.
In the second example we have all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
strings with 9, 14, 7, 17, 26, 13, 20, 10, 5, 8, 4, 2, 1
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")-s.
Remarkably this pattern of the number of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
reveals that the tag system is actually computing the famous Collatz
sequence or hailstone sequence. This sequence is defined thus for any
integer
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n"):

![x\_{n+1}=\\dfrac{x\_n}{2}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{2}"), if
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") is even

![x\_{n+1}=\\dfrac{3x\_n+1}{2}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B3x_n%2B1%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{3x_n+1}{2}"), if
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") is odd

Thus far all tested integers which have subjected to the above Collatz
map finally reach 1 (the Collatz conjecture), which is essentially
equivalent to the above tag system coming to a halt. Thus, there is a
certain nesting of structure in the these sequences, which is also
evident in the plots of the above tag systems strings. Both the
![aaa](https://s0.wp.com/latex.php?latex=aaa&bg=ffffff&fg=333333&s=0
"aaa") and
![aaaaaaaaa](https://s0.wp.com/latex.php?latex=aaaaaaaaa&bg=ffffff&fg=333333&s=0
"aaaaaaaaa") strings have 5, 8, 4, 2, 1 as the lengths of the set of the
last 5 all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
strings in their evolution. Thus, part of the evolution of the former is
identically recapitulated in the latter.

Interestingly, say we start with a string which is not all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"),
like say
![aaaacaaa](https://s0.wp.com/latex.php?latex=aaaacaaa&bg=ffffff&fg=333333&s=0
"aaaacaaa"), then for 23 cycles the system evolves through diversified
strings until we hit
![aaaaaaaaaa](https://s0.wp.com/latex.php?latex=aaaaaaaaaa&bg=ffffff&fg=333333&s=0
"aaaaaaaaaa") which pulls the evolution into the Collatzian process.
Thus, there is tendency for channelization into the Collatzian
convergence for this tag system even for non-all
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
strings. Of course certain strings can wander for even longer number of
cycle in a high entropy realm before falling into the Collatz trap. For
example, a system initiated with the string
![abcbcaabccababc](https://s0.wp.com/latex.php?latex=abcbcaabccababc&bg=ffffff&fg=333333&s=0
"abcbcaabccababc") wanders in a high entropy realm for 94 cycles before
being channeled into the Collatz process by a
14-![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
string appearing at cycle 95 (Figure 5).

[![tag\_cycle](https://manasataramgini.files.wordpress.com/2017/08/tag_cycle.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/tag_cycle.png)Figure
5

Finally, if we initiate evolution with the string
![abcbcaabc](https://s0.wp.com/latex.php?latex=abcbcaabc&bg=ffffff&fg=333333&s=0
"abcbcaabc") the system does not halt. Rather it settles into a 40 step
meta-cycle coming back to the same string at every 41st cycle. In each
of the 39 following cycles the string length is longer than the starter
string. Thus, this starter string being the minimal string-length in the
meta-cycle neatly helps define it. Hence, evolution initiated with this
string or any of the other 39 strings which occur in the meta-cycle
escapes the standard Collatzian route to extinction. This behavior is
more like the extension of the Collatz function to the complex plane
where in addition to the convergences to 1 at the integers there are
other cyclic traps for negative and complex numbers. Thus, if we write
the Collatz function as the following map we get the below Julia-set
like fractal upon color-coding by the number of iterations required to
escape to infinity (Figure 6).

![z\_{n+1} \\rightarrow \\dfrac{1}{4}(1+4z\_n-(1+2z\_n)\\cos(\\pi
z\_n))](https://s0.wp.com/latex.php?latex=z_%7Bn%2B1%7D+%5Crightarrow+%5Cdfrac%7B1%7D%7B4%7D%281%2B4z_n-%281%2B2z_n%29%5Ccos%28%5Cpi+z_n%29%29&bg=ffffff&fg=333333&s=0
"z_{n+1} \\rightarrow \\dfrac{1}{4}(1+4z_n-(1+2z_n)\\cos(\\pi z_n))")

[![Collatz\_escape\_01](https://manasataramgini.files.wordpress.com/2017/08/collatz_escape_01.png?w=640)](https://manasataramgini.files.wordpress.com/2017/08/collatz_escape_01.png)Figure
6

Though the Collatz conjecture is simple to describe, mathematicians
since Paul Erdős have been saying that “mathematics is not yet ready”
for proving it. Thus, along with the Goldbach conjecture it is one of
those simple to state but baffling problems that lurk at the foundations
of the mathematics. Remarkably, a simple tag system as this one provides
a model for how a relatively simple mechanism to perform a computation
can be devised. Indeed, it is systems such as this that provide
analogies to think about computation achieved in nature by the action of
relatively unintelligent systems as long as they can run for a large
number of steps. In a more general sense systems such as this that tend
halt after a finite number of steps also reminds one of the system of
sage PĀṆINI for Sanskrit. Here the process halts when it has formed a
valid Sanskrit word.

Finally, this tag system also suggests an analogy for the process of the
rise and fall of clades of life. Its three rules can be analogized with
the the processes of diversification, local extinction and
proliferation. Further, the replacement of the two elements is
suggestive of the replacement of older lineages by new ones. Thus, under
these reasonable models of low level processes we can see a clade
increase in number(string length), diversity (entropy increase), go
through ups and downs of these and ultimately become extinct or settle
into an endless repeating cycle of the same process. This does provide a
way of thinking about the fate of certain lineages like the trilobites.
They went through many cycles of rise and fall over ![270 \\times
10^6](https://s0.wp.com/latex.php?latex=270+%5Ctimes+10%5E6&bg=ffffff&fg=333333&s=0
"270 \\times 10^6") years, remaining a dominant arthropod clade through
much of this period before a final decline and complete extinction. This
makes one wonder if such final extinctions are a generally unavoidable
end for systems evolving as analogs of such tag systems. This might even
extend to civilizations in human history much as thinkers like Spengler
saw them growing, maturing senescing and dying out.
