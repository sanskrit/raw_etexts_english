+++
title = "Chaos, eruptions and root-convergence in one-dimensional maps based on metallic-sequence generating functions"

+++
[bronze\_bouncer](https://manasataramgini.files.wordpress.com/2019/08/bronze_bouncer.pdf "bronze_bouncer")

Over the years we have observed or encountered certain natural phenomena
that are characterized by rare, sudden eruptive behavior occurring
against a background of very low amplitude fluctuations. We first
encountered this in astronomy: most remarkably, in the constellation of
Corona Borealis there are two stars that exhibit this kind of behavior
albeit in opposite directions. There is T Coronae Borealis, which for
most part remains fluctuating rather dimly in a narrow magnitude band
between 9.9 and 10.6, well below naked eye visibility, and then once in
a century or so (e.g. in 1866 and 1946) explosively blazes forth at
magnitude of 2-3 ( ![\\approx 1000
\\times](https://s0.wp.com/latex.php?latex=%5Capprox+1000+%5Ctimes&bg=ffffff&fg=333333&s=0
"\\approx 1000 \\times") brighter) changing the shape of the visible
constellation. On the other side, we have the equally charismatic R
Coronae Borealis, which for most part very mildly fluctuates around the
magnitude of 6 at barely naked eye visibility and then suddenly once in
several years suddenly drops to the magnitude of 14 or lower (
![\\approx 1500
\\times](https://s0.wp.com/latex.php?latex=%5Capprox+1500+%5Ctimes&bg=ffffff&fg=333333&s=0
"\\approx 1500 \\times") dimmer), beyond the reach of even a typical
amateur telescope.

It has become increasingly clear that versions of such behaviors are
observed across the domains of science. In biology, recent studies in
foraging behavior have shown that diverse animals follow a pattern of
foraging movements, which are characterized by routine small movements
punctuated by the rare large movements. This kind of behavior allows the
escaping of local resource limitations by episodic saltations to reach
distant resource-rich regions. An unrelated phenomenon, earthquakes,
also displays similar behavior, where small low-magnitude tremors are
punctuated by rare episodes of major earthquakes with noticeable
effects. This might also be seen in sociology/geopolitics where long
periods of low intensity conflicts are interrupted by the rare cases of
major warfare. The world wars could be seen as such manifestations
against a background of low intensity conflict. This is relevant to the
clash between the thinkers Taleb and Pinker regarding whether there is a
real trend of the world having become more peaceful or not.

One of the great mathematicians of our age Benoît Mandelbrot provided a
framework to understand these disparate phenomena under the rubric of
random walks. He called a regular random walk, where the step sizes are
normally distributed, as the Rayleigh flights. In contrast, if they
instead show some distribution that has a tail with a slower than
exponential decay then he defined them as Lévy flights after the
mathematician Lévy. One example, of this is the so called Cauchy flight
which results from the steps of the walk showing the famous Cauchy
distribution (originally discovered by Poisson but attributed to
Cauchy). Such random walks are characterized by typical steps that are
smaller in magnitude more common than the typical steps under a normal
distribution and the extreme steps are rarer than under a normal
distribution but way more in magnitude than one would see under a normal
distribution. Thus, they capture the eruptive behavior quite well.

We have been long interested in creating simple mathematical analogies
for such behaviors observed in nature. Given that a random walk can be
reduced to its simplest form, i.e. a one dimensional change in
magnitude, we have been interested in one-dimensional maps that can
display such behaviors. We describe below a class of one-dimensional
maps, which we discovered, that show such a behavior. They are all
related to quadratic roots known as metallic ratios.

**The metallic ratios and generating functions of the metallic
sequences**  
Metallic ratios can be defined as irrationals which are produced by the
following formula:

![m\_n=\\dfrac{\\left(n+\\sqrt{n^2+4}\\right)}{2}; n =1, 2,
3...](https://s0.wp.com/latex.php?latex=m_n%3D%5Cdfrac%7B%5Cleft%28n%2B%5Csqrt%7Bn%5E2%2B4%7D%5Cright%29%7D%7B2%7D%3B+n+%3D1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0
"m_n=\\dfrac{\\left(n+\\sqrt{n^2+4}\\right)}{2}; n =1, 2, 3...")

They are called “metallic” after the smallest of them, the famous Golden
ratio. As we have noted before the first few metallic ratios are
“interesting” because they appear in various unrelated contexts but
the larger ones do not seem to do so.
![m\_n](https://s0.wp.com/latex.php?latex=m_n&bg=ffffff&fg=333333&s=0
"m_n") and its conjugate
![m\_n'](https://s0.wp.com/latex.php?latex=m_n%27&bg=ffffff&fg=333333&s=0
"m_n'") are root of a quadratic equation of the form:

![x^2 \\pm nx
-1=0](https://s0.wp.com/latex.php?latex=x%5E2+%5Cpm+nx+-1%3D0&bg=ffffff&fg=333333&s=0
"x^2 \\pm nx -1=0")

The two roots are opposite in sign but correspond to ![m\_n,
m\_n'](https://s0.wp.com/latex.php?latex=m_n%2C+m_n%27&bg=ffffff&fg=333333&s=0
"m_n, m_n'"), which show the relationship:

![m\_n'=\\dfrac{1}{m\_n}](https://s0.wp.com/latex.php?latex=m_n%27%3D%5Cdfrac%7B1%7D%7Bm_n%7D&bg=ffffff&fg=333333&s=0
"m_n'=\\dfrac{1}{m_n}")

Accordingly, they count among the the so-called Pisot-Vijayaraghavan
numbers. We use
![m\_n](https://s0.wp.com/latex.php?latex=m_n&bg=ffffff&fg=333333&s=0
"m_n") for the larger and
![m\_n'](https://s0.wp.com/latex.php?latex=m_n%27&bg=ffffff&fg=333333&s=0
"m_n'") for the smaller root in absolute magnitude. Below are the first
few metallic ratios, which may assigned special symbols as below:

![bouncer\_table1](https://manasataramgini.files.wordpress.com/2019/08/bouncer_table1.png?w=640)

They are called ratios because they are the convergents of integer
sequences which are specified by the rule:

![f\[n\]=k \\cdot f\[n-1\]+f\[n-2\]; k=1, 2, 3...; f\[1\]=1,
f\[2\]=f\[1\]+k](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3Dk+%5Ccdot+f%5Bn-1%5D%2Bf%5Bn-2%5D%3B+k%3D1%2C+2%2C+3...%3B+f%5B1%5D%3D1%2C+f%5B2%5D%3Df%5B1%5D%2Bk&bg=ffffff&fg=333333&s=0
"f[n]=k \\cdot f[n-1]+f[n-2]; k=1, 2, 3...; f[1]=1, f[2]=f[1]+k")  
With
![k=1](https://s0.wp.com/latex.php?latex=k%3D1&bg=ffffff&fg=333333&s=0
"k=1") we get: **1, 2, 3, 5, 8, 13, 21…**  
With
![k=2](https://s0.wp.com/latex.php?latex=k%3D2&bg=ffffff&fg=333333&s=0
"k=2") we get: **1, 3, 7, 17, 41, 99…**  
With
![k=3](https://s0.wp.com/latex.php?latex=k%3D3&bg=ffffff&fg=333333&s=0
"k=3") we get: **1, 4, 13, 43, 142, 469…**  
With
![k=4](https://s0.wp.com/latex.php?latex=k%3D4&bg=ffffff&fg=333333&s=0
"k=4") we get: **1, 5, 21, 89, 377, 1597…**

Notably these sequences are related to the quadratics whose roots they
are via certain generating functions. For a function
![y=f(x)](https://s0.wp.com/latex.php?latex=y%3Df%28x%29&bg=ffffff&fg=333333&s=0
"y=f(x)") the series expansion of
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0
"f(x)") at the value of
![x=a](https://s0.wp.com/latex.php?latex=x%3Da&bg=ffffff&fg=333333&s=0
"x=a") is given by:

![y=f(a)+\\dfrac{f'(a)(x-a)}{1\!}+\\dfrac{f''(a)(x-a)^2}{2\!}+\\dfrac{f'''(a)(x-a)^3}{3\!}....+\\dfrac{f^n{'}(a)(x-a)^n}{n\!}...](https://s0.wp.com/latex.php?latex=y%3Df%28a%29%2B%5Cdfrac%7Bf%27%28a%29%28x-a%29%7D%7B1%21%7D%2B%5Cdfrac%7Bf%27%27%28a%29%28x-a%29%5E2%7D%7B2%21%7D%2B%5Cdfrac%7Bf%27%27%27%28a%29%28x-a%29%5E3%7D%7B3%21%7D....%2B%5Cdfrac%7Bf%5En%7B%27%7D%28a%29%28x-a%29%5En%7D%7Bn%21%7D...&bg=ffffff&fg=333333&s=0
"y=f(a)+\\dfrac{f'(a)(x-a)}{1!}+\\dfrac{f''(a)(x-a)^2}{2!}+\\dfrac{f'''(a)(x-a)^3}{3!}....+\\dfrac{f^n{'}(a)(x-a)^n}{n!}...")

Now, for instance, consider the function:

![y=\\dfrac{x}{x^2+x-1}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7Bx%7D%7Bx%5E2%2Bx-1%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{x}{x^2+x-1}")

For
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0
"x=0") its series expansion becomes:

![y= -(x + x^2 + 2 x^3 + 3 x^4 + 5 x^5 +
8x^5...)](https://s0.wp.com/latex.php?latex=y%3D+-%28x+%2B+x%5E2+%2B+2+x%5E3+%2B+3+x%5E4+%2B+5+x%5E5+%2B+8x%5E5...%29&bg=ffffff&fg=333333&s=0
"y= -(x + x^2 + 2 x^3 + 3 x^4 + 5 x^5 + 8x^5...)")

We notice that the coefficients of the expansion polynomial are ![1, 1,
2, 3, 5,
8...](https://s0.wp.com/latex.php?latex=1%2C+1%2C+2%2C+3%2C+5%2C+8...&bg=ffffff&fg=333333&s=0
"1, 1, 2, 3, 5, 8..."). Thus, this expansion becomes the generating
function of the Golden sequence. Similarly, if we take:

![y=\\dfrac{2x-1}{x^2+3x-1}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7B2x-1%7D%7Bx%5E2%2B3x-1%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{2x-1}{x^2+3x-1}")

For
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0
"x=0") we get the series expansion:

![y=1 + x + 4x^2 + 13x^3 + 43x^4 +
142x^5...](https://s0.wp.com/latex.php?latex=y%3D1+%2B+x+%2B+4x%5E2+%2B+13x%5E3+%2B+43x%5E4+%2B+142x%5E5...&bg=ffffff&fg=333333&s=0
"y=1 + x + 4x^2 + 13x^3 + 43x^4 + 142x^5...")

Here, the coefficients of the expansion polynomial correspond to the
Bronze sequence. The functions of the above type are tripartite curves
with two parallel asymptotes at
![x=-m\_n](https://s0.wp.com/latex.php?latex=x%3D-m_n&bg=ffffff&fg=333333&s=0
"x=-m_n") and
![x=m\_n'](https://s0.wp.com/latex.php?latex=x%3Dm_n%27&bg=ffffff&fg=333333&s=0
"x=m_n'") (Figure 1). The central branch of the curve is bounded between
these parallel asymptotes. The left and the right hyperbolic branches
are bounded respectively on the right and left sides by the two
asymptotes.

[![golden\_bouncer\_Fig1](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer_fig1.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer_fig1.png)Figure
1

**One dimensional maps based on the metallic sequence generating
functions**  
The above type of functions specify our one-dimensional maps. The maps
operate by using the well-known cobweb construction used in the study of
chaotic maps (Figure 1). Figure 1 shows the process for
![y=f(x)=\\tfrac{2x+1}{x^2+x-1}](https://s0.wp.com/latex.php?latex=y%3Df%28x%29%3D%5Ctfrac%7B2x%2B1%7D%7Bx%5E2%2Bx-1%7D&bg=ffffff&fg=333333&s=0
"y=f(x)=\\tfrac{2x+1}{x^2+x-1}"), which has the series expansion at
![x=0](https://s0.wp.com/latex.php?latex=x%3D0&bg=ffffff&fg=333333&s=0
"x=0") as ![y=-(1 + 3x + 4x^2 + 7 x^3 + 11 x^4
+18x^5+29x^6...)](https://s0.wp.com/latex.php?latex=y%3D-%281+%2B+3x+%2B+4x%5E2+%2B+7+x%5E3+%2B+11+x%5E4+%2B18x%5E5%2B29x%5E6...%29&bg=ffffff&fg=333333&s=0
"y=-(1 + 3x + 4x^2 + 7 x^3 + 11 x^4 +18x^5+29x^6...)"). The convergent
of the coefficients of this expansion polynomial is the Golden ratio. We
start with an initial point
![X\_0](https://s0.wp.com/latex.php?latex=X_0&bg=ffffff&fg=333333&s=0
"X_0"). We then project the point on the the curve
![f(x)](https://s0.wp.com/latex.php?latex=f%28x%29&bg=ffffff&fg=333333&s=0
"f(x)") defined by one such metallic sequence generating function to
obtain point
![Y\_1](https://s0.wp.com/latex.php?latex=Y_1&bg=ffffff&fg=333333&s=0
"Y_1"). We then project
![Y\_1](https://s0.wp.com/latex.php?latex=Y_1&bg=ffffff&fg=333333&s=0
"Y_1") on the line
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") to obtain point
![X\_1](https://s0.wp.com/latex.php?latex=X_1&bg=ffffff&fg=333333&s=0
"X_1"). We then repeat the above procedure with
![X\_1](https://s0.wp.com/latex.php?latex=X_1&bg=ffffff&fg=333333&s=0
"X_1"). The resulting projection segments are plotted as a cobweb
diagram (Figure 1). In algebraic terms the map is expressed as
![x\_{n+1}=f(x\_n)](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3Df%28x_n%29&bg=ffffff&fg=333333&s=0
"x_{n+1}=f(x_n)"). Our empirical examination revealed that not all maps
of this type produce interesting behavior — they simply converge to a
single fixed attractor value. Moreover, we did not observe interesting
behavior with other small quadratic Pisot-Vijayaraghavan roots, e.g.:
![x^2-3x+1=0; x= 1+\\phi,
1-\\phi'](https://s0.wp.com/latex.php?latex=x%5E2-3x%2B1%3D0%3B+x%3D+1%2B%5Cphi%2C+1-%5Cphi%27&bg=ffffff&fg=333333&s=0
"x^2-3x+1=0; x= 1+\\phi, 1-\\phi'") or ![x^2-2x-2; x=1\\pm
\\sqrt{3}](https://s0.wp.com/latex.php?latex=x%5E2-2x-2%3B+x%3D1%5Cpm+%5Csqrt%7B3%7D&bg=ffffff&fg=333333&s=0
"x^2-2x-2; x=1\\pm \\sqrt{3}").

In our exploration we found the following maps to show interesting
behaviors.  
1\) Golden-ratio-based:  
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2Bx_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+x_n-1}")

![x\_{n+1}=\\dfrac{x\_n}{x\_n^2-x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2-x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2-x_n-1}")

![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2Bx_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+x_n-1}")

2\) Silver-ratio-based:  
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+2x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B2x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+2x_n-1}")

![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+2x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2B2x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+2x_n-1}")

3\) Bronze-ratio-based:  
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+3x_n-1}")

![x\_{n+1}=\\dfrac{2x\_n-1}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n-1%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n-1}{x_n^2+3x_n-1}")

![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+3x_n-1}")

3\) Copper-ratio-based:  
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+4x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B4x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+4x_n-1}")

![x\_{n+1}=\\dfrac{2x\_n-1}{x\_n^2+4x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n-1%7D%7Bx_n%5E2%2B4x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n-1}{x_n^2+4x_n-1}")

One point to note regarding these maps is the high degree of numerical
instability of most of them. Hence, we have to use high precision
numbers to study the evolution of a starting value under the map. We
found that one needs a precision of 1500 bits in order to obtain a
proper evolutionary trajectory for 20000 iterations of the map. The
investigations discussed below are with this precision and number of
iterations. Evolution under these maps can be classified into 4 distinct
types and we shall discuss examples of each of the distinct types of
behaviors in greater detail below.

**Type-1: Chaotic and eruptive behavior**  
The archetypal member of this type is Golden-ratio-based map:  
![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2Bx_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+x_n-1}").

[![Golden\_bouncer3\_Fig2](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig2-2.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig2-2.png)Figure
2.

Figure 2 shows the evolution of
![x\_0=\\tfrac{1}{4}](https://s0.wp.com/latex.php?latex=x_0%3D%5Ctfrac%7B1%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"x_0=\\tfrac{1}{4}") under this map. It is immediately apparent that it
is characterized by predominantly low amplitude movements interrupted by
rare episodes of extreme eruptions that can be several orders of
magnitude of the typical values. A feel for this can be obtained via the
below table.

![\\begin{tabular}{|l|c|} \\hline Quantile & Value \\\\ \\hline Minimum
& -6114.33 \\\\ Octile 0.125 & -2.406 \\\\ Octile 0.25 & -0.995 \\\\
Octile 0.375 & -0.413 \\\\ Median & 0.0036 \\\\ Mean & 1.75 \\\\ Octile
0.625 & -0.418 \\\\ Octile 0.75 & 1.003 \\\\ Octile 0.875 & 2.418 \\\\
Maximum & 35903.36 \\\\ \\hline \\end{tabular}
](https://s0.wp.com/latex.php?latex=%5Cbegin%7Btabular%7D%7B%7Cl%7Cc%7C%7D+%5Chline+Quantile+%26+Value+%5C%5C+%5Chline+Minimum+%26+-6114.33+%5C%5C+Octile+0.125+%26+-2.406+%5C%5C+Octile+0.25+%26+-0.995+%5C%5C+Octile+0.375+%26+-0.413+%5C%5C+Median+%26+0.0036+%5C%5C+Mean+%26+1.75+%5C%5C+Octile+0.625+%26+-0.418+%5C%5C+Octile+0.75+%26+1.003+%5C%5C+Octile+0.875+%26+2.418+%5C%5C+Maximum+%26+35903.36+%5C%5C+%5Chline+%5Cend%7Btabular%7D+&bg=ffffff&fg=333333&s=0
"\\begin{tabular}{|l|c|} \\hline Quantile & Value \\\\ \\hline Minimum & -6114.33 \\\\ Octile 0.125 & -2.406 \\\\ Octile 0.25 & -0.995 \\\\ Octile 0.375 & -0.413 \\\\ Median & 0.0036 \\\\ Mean & 1.75 \\\\ Octile 0.625 & -0.418 \\\\ Octile 0.75 & 1.003 \\\\ Octile 0.875 & 2.418 \\\\ Maximum & 35903.36 \\\\ \\hline \\end{tabular} ")

We observe that
![75\\%](https://s0.wp.com/latex.php?latex=75%5C%25&bg=ffffff&fg=333333&s=0
"75\\%") ot the values are in rather narrow band of ![\\pm
2.41](https://s0.wp.com/latex.php?latex=%5Cpm+2.41&bg=ffffff&fg=333333&s=0
"\\pm 2.41"); however, the extremes are roughly 2500-15000 times greater
than that band. Thus, we see what is plainly eruptive behavior. It is
also rather obvious from these values that the distribution of the
values attained under this map are dramatically different from a normal
distribution with comparable dispersion. The rarity and the magnitude of
the extreme values results in the mean being greatly different from the
median.

[![Golden\_bouncer3\_Fig3](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig3.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig3.png)Figure
3.

To get a better look at the nature of the movements as
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") evolves under this map we plot the same on the
![\\mathrm{arcsinh}(x)](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh}(x)") scale (Figure 3). The central blue line
corresponds to
![0](https://s0.wp.com/latex.php?latex=0&bg=ffffff&fg=333333&s=0 "0").
It is flanked on either side by two red lines which correspond to ![\\pm
0.2](https://s0.wp.com/latex.php?latex=%5Cpm+0.2&bg=ffffff&fg=333333&s=0
"\\pm 0.2"). In this case ![\\approx
12.5\\%](https://s0.wp.com/latex.php?latex=%5Capprox+12.5%5C%25&bg=ffffff&fg=333333&s=0
"\\approx 12.5\\%") of the
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") lie in this band. The green lines correspond to the Golden ratios
![\\phi',
-\\phi](https://s0.wp.com/latex.php?latex=%5Cphi%27%2C+-%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi', -\\phi"). The cases where ![x\_n \\ge
100](https://s0.wp.com/latex.php?latex=x_n+%5Cge+100&bg=ffffff&fg=333333&s=0
"x_n \\ge 100"), which is
![0.64\\%](https://s0.wp.com/latex.php?latex=0.64%5C%25&bg=ffffff&fg=333333&s=0
"0.64\\%") of the values, are marked with red points. We observe that:  
1\) The evolution of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") follows a chaotic course.  
2\) The eruptions are triggered in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") when
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") approaches ![\\phi',
-\\phi](https://s0.wp.com/latex.php?latex=%5Cphi%27%2C+-%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi', -\\phi") (Blue points in figure 3). This is illustrated at
greater magnification in Figure 4. The reason for this is rather obvious
from the equation of the map — if ![x\_n=\\phi',
-\\phi](https://s0.wp.com/latex.php?latex=x_n%3D%5Cphi%27%2C+-%5Cphi&bg=ffffff&fg=333333&s=0
"x_n=\\phi', -\\phi") then
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") will explode to
![\\infty](https://s0.wp.com/latex.php?latex=%5Cinfty&bg=ffffff&fg=333333&s=0
"\\infty"): thus, closer
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") gets to
![\\phi',-\\phi](https://s0.wp.com/latex.php?latex=%5Cphi%27%2C-%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi',-\\phi") greater is the eruption in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}"). If the value of ![x\_n\>\\phi',
-\\phi](https://s0.wp.com/latex.php?latex=x_n%3E%5Cphi%27%2C+-%5Cphi&bg=ffffff&fg=333333&s=0
"x_n\>\\phi', -\\phi") when approaching it then the eruption in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") will positive, if
![x\_n\<\\phi',\\phi](https://s0.wp.com/latex.php?latex=x_n%3C%5Cphi%27%2C%5Cphi&bg=ffffff&fg=333333&s=0
"x_n\<\\phi',\\phi") the eruption will be negative.

[![Golden\_bouncer3\_Fig4](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig4.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig4.png)Figure
4.

3\) Because the map tends to mostly produce small absolute values
![\\approx 50\\%\\; x\_n \\in \\pm
1](https://s0.wp.com/latex.php?latex=%5Capprox+50%5C%25%5C%3B+x_n+%5Cin+%5Cpm+1&bg=ffffff&fg=333333&s=0
"\\approx 50\\%\\; x_n \\in \\pm 1") it is obvious that the smaller root
![\\phi'](https://s0.wp.com/latex.php?latex=%5Cphi%27&bg=ffffff&fg=333333&s=0
"\\phi'") triggers more eruptions than
![-\\phi](https://s0.wp.com/latex.php?latex=-%5Cphi&bg=ffffff&fg=333333&s=0
"-\\phi").  
4\) From Figure 4 one also observes a peculiar motif in the form of runs
of relatively low amplitude fluctuations in the vicinity of ![\\phi,
\\tfrac{-\\phi'}{2}](https://s0.wp.com/latex.php?latex=%5Cphi%2C+%5Ctfrac%7B-%5Cphi%27%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\phi, \\tfrac{-\\phi'}{2}") (marked as dark green horizontal lines).

Because of the rather dramatic dispersion of the values of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n"), we studied their distribution in the
![\\mathrm{arcsinh(x)}](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh(x)}") scale (Figure 5).

[![Golden\_bouncer3\_Fig5](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig5.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig5.png)Figure
5.

We observe that the distribution is symmetric about 0, as we would
expect from the above quantile distributions of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n"). The blue curve shows an attempt to fit a Cauchy distribution to
the observed frequencies. We see that it does not capture the
distribution too well. The more general form of such a distribution, the
t-distribution, also does not perfectly capture the observed
frequencies. However, taking inspiration from that we were able to
derive a curve that fits the histogram better than any of these
distributions. It is defined by a shape function with 4 parameters ![a,
b, r,
s](https://s0.wp.com/latex.php?latex=a%2C+b%2C+r%2C+s&bg=ffffff&fg=333333&s=0
"a, b, r, s") of the form (red curve in Figure 5):

![y=\\dfrac{1}{1+a|x|^r+b|x|^s}](https://s0.wp.com/latex.php?latex=y%3D%5Cdfrac%7B1%7D%7B1%2Ba%7Cx%7C%5Er%2Bb%7Cx%7C%5Es%7D&bg=ffffff&fg=333333&s=0
"y=\\dfrac{1}{1+a|x|^r+b|x|^s}")

Another map belonging to this type is similar one based on the Silver
ratio (Figure 6):  
![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+2x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2B2x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+2x_n-1}")

[![Silver\_bouncer2\_Fig6](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer2_fig6.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer2_fig6.png)Figure
6.

It displays the same type of chaotic movements as the above map with
episodes of major eruptions.

[![Silver\_bouncer2\_Fig7](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer2_fig7.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer2_fig7.png)Figure
7.

The zoom in Figure 7 shows that the eruptions in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") are in this triggered by
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") approaching the Silver ratio and its conjugate (light green
lines). Like the above map, here too there are motifs comprised of short
runs of low amplitude oscillations around two values: ![4-2\\sqrt{2},
-1+\\tfrac{1}{\\sqrt{2}}](https://s0.wp.com/latex.php?latex=4-2%5Csqrt%7B2%7D%2C+-1%2B%5Ctfrac%7B1%7D%7B%5Csqrt%7B2%7D%7D&bg=ffffff&fg=333333&s=0
"4-2\\sqrt{2}, -1+\\tfrac{1}{\\sqrt{2}}") (Figure 7).

**Type-2: low amplitude oscillations punctuated with destabilization and
eruptions**  
The maps exhibiting the second type of behavior are:

![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2Bx_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+x_n-1}");
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2-x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2-x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2-x_n-1}");
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+2x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B2x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+2x_n-1}");

![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+3x_n-1}");
![x\_{n+1}=\\dfrac{2x\_n+1}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n%2B1%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n+1}{x_n^2+3x_n-1}");
![x\_{n+1}=\\dfrac{x\_n}{x\_n^2+4x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bx_n%7D%7Bx_n%5E2%2B4x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{x_n}{x_n^2+4x_n-1}")

[![bouncers3\_Fig8](https://manasataramgini.files.wordpress.com/2019/08/bouncers3_fig8.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/bouncers3_fig8.png)Figure
8.

Figure 8 shows examples of the evolution of the same
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") under three of these maps based on the Golden, Silver and Bronze
ratios. At first sight the eruptions are comparable to what we saw in
the Type-1 maps — they are rare episodes and huge in magnitude relative
to the rest of the movements under the map. However, these maps are
distinct, in that other than the larger magnitude instability just
before major eruptions the background movements are not even registered.
To get a better look at what is happening we plot one of the examples
(the map based on the Golden ratio) in the
![\\mathrm{arcsinh(x)}](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh(x)}") scale (Figure 9).

[![Golden\_bouncer2\_Fig9](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer2_fig9.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer2_fig9.png)Figure
9.

Here we can see that, as in the Type-1 maps, the eruptions are triggered
when
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") passes close to ![-\\phi',
\\phi](https://s0.wp.com/latex.php?latex=-%5Cphi%27%2C+%5Cphi&bg=ffffff&fg=333333&s=0
"-\\phi', \\phi") (blue points in Figure 9 prior to the red points
marking the eruptions greater than 100). But quite strikingly, even in
the
![\\mathrm{arcsinh(x)}](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh(x)}") scale, the background movements under the map
are barely visible. Hence, we zoom in on a particular region of the
![\\mathrm{arcsinh(x)}](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh(x)}") scale plot (Figure 10).

[![Golden\_bouncer2\_Fig10](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer2_fig10.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer2_fig10.png)Figure
10.

Only here we observe that the map is for most part characterized by a
very quiet behavior, which, unlike the Type-1 maps, takes the form of
regular low-amplitude oscillations that asymptotically build up till
they near one of the Golden ratio roots at which point they show
unstable behavior leading to an eruption. After a major eruption the
evolution settles in a very low amplitude oscillation as seen in the
right part of Figure 10. Accordingly we get a paradoxical distribution
of ![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") values on the
![\\mathrm{arcsinh(x)}](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%28x%29%7D&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh(x)}") scale with a very sharp peak and a heavy tail
Fig 11. This distribution might also be described by some form the shape
equation specified in the above type.

[![Golden\_bouncer3\_Fig11](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig11.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/golden_bouncer3_fig11.png)Figure
11.

These maps may also be used to describe a feature common to all these
maps, i.e. extreme sensitivity to the initial conditions (Figure 12,
13). Even a difference of
![10^{-8}](https://s0.wp.com/latex.php?latex=10%5E%7B-8%7D&bg=ffffff&fg=333333&s=0
"10^{-8}") in the starting
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") results in completely different evolutionary trajectories. This
is why we need to use extremely high precision numbers to get numerical
stable evolution: e.g. 450-600 decimal digits.

[![bronze\_bouncer\_Fig12](https://manasataramgini.files.wordpress.com/2019/08/bronze_bouncer_fig12.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/bronze_bouncer_fig12.png)Figure
12.

An example based on the Bronze ratio.

[![silver\_bouncer\_Fig13](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer_fig13.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/silver_bouncer_fig13.png)Figure
13.

An example based on the Silver ratio. The second example illustrates how
eruptive behavior can return after an extremely long phase of
quiescence.

**Type-3: Convergent root-seeking behavior after eruptions and
instability**  
This is an interesting behavior prototyped by the Bronze ratio-based
map:  
![x\_{n+1}=\\dfrac{2x\_n-1}{x\_n^2+3x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n-1%7D%7Bx_n%5E2%2B3x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n-1}{x_n^2+3x_n-1}")

Here, the map tends to show oscillatory behavior with occasional
eruptions as in the above type. However, after 1 or a few eruptions
associated with some chaotic instability the map settles to a fixed
behavior where it cycles between a small set of values that gradually
converge to roots of a certain polynomial equation (Figure 14, 15).

[![rootseeker\_r1\_Fig14](https://manasataramgini.files.wordpress.com/2019/08/rootseeker_r1_fig14.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/rootseeker_r1_fig14.png)Figure
14.

In this case after 2 large eruptions within the first 400 iterations it
eventually converges to cycling between the three roots of the equation:

![P\_1: y=x^3-3x+1; \\;
\\overbrace{x\_1=2\\sin\\left(\\dfrac{\\pi}{18}\\right) \\rightarrow
x\_2=-2\\cos\\left(\\dfrac{\\pi}{9}\\right) \\rightarrow
x\_3=2\\cos\\left(\\dfrac{2\\pi}{9}\\right)}](https://s0.wp.com/latex.php?latex=P_1%3A+y%3Dx%5E3-3x%2B1%3B+%5C%3B+%5Coverbrace%7Bx_1%3D2%5Csin%5Cleft%28%5Cdfrac%7B%5Cpi%7D%7B18%7D%5Cright%29+%5Crightarrow+x_2%3D-2%5Ccos%5Cleft%28%5Cdfrac%7B%5Cpi%7D%7B9%7D%5Cright%29+%5Crightarrow+x_3%3D2%5Ccos%5Cleft%28%5Cdfrac%7B2%5Cpi%7D%7B9%7D%5Cright%29%7D&bg=ffffff&fg=333333&s=0
"P_1: y=x^3-3x+1; \\; \\overbrace{x_1=2\\sin\\left(\\dfrac{\\pi}{18}\\right) \\rightarrow x_2=-2\\cos\\left(\\dfrac{\\pi}{9}\\right) \\rightarrow x_3=2\\cos\\left(\\dfrac{2\\pi}{9}\\right)}")

Here too, we notice that the eruption occur in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") (red dots) when ![x\_n \\approx \\beta',
-\\beta](https://s0.wp.com/latex.php?latex=x_n+%5Capprox+%5Cbeta%27%2C+-%5Cbeta&bg=ffffff&fg=333333&s=0
"x_n \\approx \\beta', -\\beta") (blue dots close to blue lines), i.e.
the bronze ratios. The map makes multiple attempts to settle into
cycling between the roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") (brown horizontal lines) but each time slips away nears either
![-\\beta](https://s0.wp.com/latex.php?latex=-%5Cbeta&bg=ffffff&fg=333333&s=0
"-\\beta") or
![\\beta'](https://s0.wp.com/latex.php?latex=%5Cbeta%27&bg=ffffff&fg=333333&s=0
"\\beta'") and then erupts. Between 600 and 700 iterations the map
settles into what seems a permanent cycling between the roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") and by 800 iterations approaches within
![10^-6](https://s0.wp.com/latex.php?latex=10%5E-6&bg=ffffff&fg=333333&s=0
"10^-6") of those roots. Iteration of the map for an additional 100000
iterations showed no further eruptive behavior suggesting final
convergence to the roots; however, we have not been able to prove this
is indeed case.

[![rootseeker\_r2\_Fig15](https://manasataramgini.files.wordpress.com/2019/08/rootseeker_r2_fig15.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/rootseeker_r2_fig15.png)Figure
15.

In this case the map makes multiple attempts to cycle between the roots
of ![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") and the roots of a second polynomial
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") before finally converging to cycling between the roots of the
latter (brown horizontal lines):

![P\_2: y= x^4+7x^3-6x^2-2x+1\\\\\[8pt\] \\left.\\begin{aligned} x\_1 =
\\dfrac{-7 + 3\\sqrt{5} + \\sqrt{150 - 66\\sqrt{5}}}{4}\\\\\[8pt\] x\_2
= \\dfrac{-7 - 3\\sqrt{5} - \\sqrt{150 + 66\\sqrt{5}}}{4}\\\\\[8pt\]
x\_3 = \\dfrac{-7 + 3\\sqrt{5} - \\sqrt{150 -
66\\sqrt{5}}}{4}\\\\\[8pt\] x\_4 = \\dfrac{-7 - 3\\sqrt{5} + \\sqrt{150
+ 66\\sqrt{5}}}{4}
\\end{aligned}\\right\\}](https://s0.wp.com/latex.php?latex=P_2%3A+y%3D+x%5E4%2B7x%5E3-6x%5E2-2x%2B1%5C%5C%5B8pt%5D+%5Cleft.%5Cbegin%7Baligned%7D+x_1+%3D+%5Cdfrac%7B-7+%2B+3%5Csqrt%7B5%7D+%2B+%5Csqrt%7B150+-+66%5Csqrt%7B5%7D%7D%7D%7B4%7D%5C%5C%5B8pt%5D+x_2+%3D+%5Cdfrac%7B-7+-+3%5Csqrt%7B5%7D+-+%5Csqrt%7B150+%2B+66%5Csqrt%7B5%7D%7D%7D%7B4%7D%5C%5C%5B8pt%5D+x_3+%3D+%5Cdfrac%7B-7+%2B+3%5Csqrt%7B5%7D+-+%5Csqrt%7B150+-+66%5Csqrt%7B5%7D%7D%7D%7B4%7D%5C%5C%5B8pt%5D+x_4+%3D+%5Cdfrac%7B-7+-+3%5Csqrt%7B5%7D+%2B+%5Csqrt%7B150+%2B+66%5Csqrt%7B5%7D%7D%7D%7B4%7D+%5Cend%7Baligned%7D%5Cright%5C%7D&bg=ffffff&fg=333333&s=0
"P_2: y= x^4+7x^3-6x^2-2x+1\\\\[8pt] \\left.\\begin{aligned} x_1 = \\dfrac{-7 + 3\\sqrt{5} + \\sqrt{150 - 66\\sqrt{5}}}{4}\\\\[8pt] x_2 = \\dfrac{-7 - 3\\sqrt{5} - \\sqrt{150 + 66\\sqrt{5}}}{4}\\\\[8pt] x_3 = \\dfrac{-7 + 3\\sqrt{5} - \\sqrt{150 - 66\\sqrt{5}}}{4}\\\\[8pt] x_4 = \\dfrac{-7 - 3\\sqrt{5} + \\sqrt{150 + 66\\sqrt{5}}}{4} \\end{aligned}\\right\\}")

There is one obvious static
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") which remains unchanged under this map, namely the real root of
the equation:
![x^3+3x^2-3x+1=0](https://s0.wp.com/latex.php?latex=x%5E3%2B3x%5E2-3x%2B1%3D0&bg=ffffff&fg=333333&s=0
"x^3+3x^2-3x+1=0"):

![x\_s =
-1-2^{1/3}-2^{2/3}](https://s0.wp.com/latex.php?latex=x_s+%3D+-1-2%5E%7B1%2F3%7D-2%5E%7B2%2F3%7D&bg=ffffff&fg=333333&s=0
"x_s = -1-2^{1/3}-2^{2/3}")

If ![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") is exactly this
![x\_s](https://s0.wp.com/latex.php?latex=x_s&bg=ffffff&fg=333333&s=0
"x_s") then it will return itself under the map. Even a point very close
to ![x\_s](https://s0.wp.com/latex.php?latex=x_s&bg=ffffff&fg=333333&s=0
"x_s") is unstable and will not remain there for too long, eventually
converging to
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") or
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2"). For example, a
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") that was identical to
![x\_s](https://s0.wp.com/latex.php?latex=x_s&bg=ffffff&fg=333333&s=0
"x_s") till 600 places after the decimal point slid away from
![x\_s](https://s0.wp.com/latex.php?latex=x_s&bg=ffffff&fg=333333&s=0
"x_s") by iteration 705 of map and within the next 20 iterations was on
its way to converge to the roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1"). Thus, all other points under this map eventually converge to
either the roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") or of
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") (Figure 16).

[![bouncer\_covergence.\_Figure16](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence._figure16.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence._figure16.png)Figure
16.

The
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") are sampled in the interval
![(-15,15)](https://s0.wp.com/latex.php?latex=%28-15%2C15%29&bg=ffffff&fg=333333&s=0
"(-15,15)") in steps of .025. The red
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") converge to roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1"), while the green
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") converge to roots of
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2"). The roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") are marked by blue vertical lines and those of
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") by orange lines. Notably, it seems that they converge to
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") less often than
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") such the ratio
![P\_2:P\_1](https://s0.wp.com/latex.php?latex=P_2%3AP_1&bg=ffffff&fg=333333&s=0
"P_2:P_1") appears to converge to
![\\beta'](https://s0.wp.com/latex.php?latex=%5Cbeta%27&bg=ffffff&fg=333333&s=0
"\\beta'") (is there a way to formally test this conjecture?).
Interestingly, immediately below ![P\_2:
x\_2](https://s0.wp.com/latex.php?latex=P_2%3A+x_2&bg=ffffff&fg=333333&s=0
"P_2: x_2") there is a region where every
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") converges to
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1"). There is a pseudo-symmetric region above ![P\_2:
-x\_2](https://s0.wp.com/latex.php?latex=P_2%3A+-x_2&bg=ffffff&fg=333333&s=0
"P_2: -x_2") where they all converge to
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1"). Overall, this convergence plot shows a strange pseudo-symmetry
in terms of the iterations to convergence required by
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") (Figure 16).

These roots show some interesting properties:  
![P\_1: x\_1+x\_2+x\_3=0; \\; \\dfrac{1}{x\_1}+x\_2=1; \\;
\\dfrac{1}{x\_2}+x\_3=1;\\; x\_1 \\cdot x\_2 \\cdot
x\_3=-1](https://s0.wp.com/latex.php?latex=P_1%3A+x_1%2Bx_2%2Bx_3%3D0%3B+%5C%3B+%5Cdfrac%7B1%7D%7Bx_1%7D%2Bx_2%3D1%3B+%5C%3B+%5Cdfrac%7B1%7D%7Bx_2%7D%2Bx_3%3D1%3B%5C%3B+x_1+%5Ccdot+x_2+%5Ccdot+x_3%3D-1&bg=ffffff&fg=333333&s=0
"P_1: x_1+x_2+x_3=0; \\; \\dfrac{1}{x_1}+x_2=1; \\; \\dfrac{1}{x_2}+x_3=1;\\; x_1 \\cdot x_2 \\cdot x_3=-1")

Further, the roots of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") are connected to an interesting three-seeded Nārāyaṇa-like
sequence with a subtraction rather than a sum:  
![f\[n\]=3f\[n-1\]-f\[n-3\];\\; f\[1\]=0, f\[2\]=1,
f\[3\]=3](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D3f%5Bn-1%5D-f%5Bn-3%5D%3B%5C%3B+f%5B1%5D%3D0%2C+f%5B2%5D%3D1%2C+f%5B3%5D%3D3&bg=ffffff&fg=333333&s=0
"f[n]=3f[n-1]-f[n-3];\\; f[1]=0, f[2]=1, f[3]=3")

This yields: **0, 1, 3, 9, 26, 75, 216, 622, 1791, 5157, 14849, 42756,
123111, 354484, 1020696, 2938977…**

The convergent of this sequence is
![1+2\\cos\\left(\\tfrac{\\pi}{9}\\right)=1-x\_2 \\approx
2.8793852](https://s0.wp.com/latex.php?latex=1%2B2%5Ccos%5Cleft%28%5Ctfrac%7B%5Cpi%7D%7B9%7D%5Cright%29%3D1-x_2+%5Capprox+2.8793852&bg=ffffff&fg=333333&s=0
"1+2\\cos\\left(\\tfrac{\\pi}{9}\\right)=1-x_2 \\approx 2.8793852"). In
principle, this could be used to construct approximations of a regular
nonagon. The terms of this series are provided by a generating function
which is reciprocal of
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1"). Its series expansion at 0 is:

![\\dfrac{1}{x^3-3x+1}=1 + 3x + 9x^2 + 26x^3 + 75x^4 + 216x^5 + 622x^6 +
1791x^7 + 5157x^8 + 14849x^9
+...](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7Bx%5E3-3x%2B1%7D%3D1+%2B+3x+%2B+9x%5E2+%2B+26x%5E3+%2B+75x%5E4+%2B+216x%5E5+%2B+622x%5E6+%2B+1791x%5E7+%2B+5157x%5E8+%2B+14849x%5E9+%2B...&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{x^3-3x+1}=1 + 3x + 9x^2 + 26x^3 + 75x^4 + 216x^5 + 622x^6 + 1791x^7 + 5157x^8 + 14849x^9 +...")

For the second polynomial we have:  
![P\_2: x\_1+x\_2+x\_3+x\_4=-7;\\; \\dfrac{1}{x\_1}+\\dfrac{1}{x\_3}=1;
\\; \\dfrac{1}{x\_2}+\\dfrac{1}{x\_4}=1; \\; x\_1\\cdot x\_2\\cdot x\_3
\\cdot
x\_4=1](https://s0.wp.com/latex.php?latex=P_2%3A+x_1%2Bx_2%2Bx_3%2Bx_4%3D-7%3B%5C%3B+%5Cdfrac%7B1%7D%7Bx_1%7D%2B%5Cdfrac%7B1%7D%7Bx_3%7D%3D1%3B+%5C%3B+%5Cdfrac%7B1%7D%7Bx_2%7D%2B%5Cdfrac%7B1%7D%7Bx_4%7D%3D1%3B+%5C%3B+x_1%5Ccdot+x_2%5Ccdot+x_3+%5Ccdot+x_4%3D1&bg=ffffff&fg=333333&s=0
"P_2: x_1+x_2+x_3+x_4=-7;\\; \\dfrac{1}{x_1}+\\dfrac{1}{x_3}=1; \\; \\dfrac{1}{x_2}+\\dfrac{1}{x_4}=1; \\; x_1\\cdot x_2\\cdot x_3 \\cdot x_4=1")

These roots are similarly related to 2 sequences. The first is:  
![f\[n\]=7f\[n-1\]+6f\[n-2\]-2f\[n-3\]-f\[n-4\];\\; f\[1\]=-1, f\[2\]=0,
f\[3\]=1,
f\[4\]=2](https://s0.wp.com/latex.php?latex=f%5Bn%5D%3D7f%5Bn-1%5D%2B6f%5Bn-2%5D-2f%5Bn-3%5D-f%5Bn-4%5D%3B%5C%3B+f%5B1%5D%3D-1%2C+f%5B2%5D%3D0%2C+f%5B3%5D%3D1%2C+f%5B4%5D%3D2&bg=ffffff&fg=333333&s=0
"f[n]=7f[n-1]+6f[n-2]-2f[n-3]-f[n-4];\\; f[1]=-1, f[2]=0, f[3]=1, f[4]=2")

This yields: **-1, 0, 1, 2, 21, 157, 1220, 9438, 73051, 565388, 4375926,
33868270, 262129619, 2028799713, 15702263239, 121530513443…**

The convergent of this sequence is ![P\_2: -x\_2 \\approx
7.739681318](https://s0.wp.com/latex.php?latex=P_2%3A+-x_2+%5Capprox+7.739681318&bg=ffffff&fg=333333&s=0
"P_2: -x_2 \\approx 7.739681318").

The second sequence is:  
![\\displaystyle f\[n\]=7f\[n-2\]+f\[\]n-1\]-\\sum\_{j=1}^{n-4} f\[j\]);
\\; f\[1\]=-1, f\[2\]=0, f\[3\]=1,
f\[4\]=2](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+f%5Bn%5D%3D7f%5Bn-2%5D%2Bf%5B%5Dn-1%5D-%5Csum_%7Bj%3D1%7D%5E%7Bn-4%7D+f%5Bj%5D%29%3B+%5C%3B+f%5B1%5D%3D-1%2C+f%5B2%5D%3D0%2C+f%5B3%5D%3D1%2C+f%5B4%5D%3D2&bg=ffffff&fg=333333&s=0
"\\displaystyle f[n]=7f[n-2]+f[]n-1]-\\sum_{j=1}^{n-4} f[j]); \\; f[1]=-1, f[2]=0, f[3]=1, f[4]=2")

This yields: **-1, 0, 1, 2, 10, 25, 95, 268, 921, 2760, 9075, 27995,
90199, 282083, 900320, 2833750, 9004640…**

The convergent of this series is ![P\_2: \\dfrac{1}{x\_1} \\approx
3.165352](https://s0.wp.com/latex.php?latex=P_2%3A+%5Cdfrac%7B1%7D%7Bx_1%7D+%5Capprox+3.165352&bg=ffffff&fg=333333&s=0
"P_2: \\dfrac{1}{x_1} \\approx 3.165352")

Notably, the terms of this sequence can be produced using the reciprocal
of ![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") as the generating function. Its series expansion at 0 is:

![\\dfrac{1}{x^4+7x^3-6x^2-2x+1}=1 + 2 x + 10 x^2 + 25 x^3 + 95 x^4 +
268 x^5 + 921 x^6 + 2760 x^7 + 9075 x^8 + 27995 x^9
+...](https://s0.wp.com/latex.php?latex=%5Cdfrac%7B1%7D%7Bx%5E4%2B7x%5E3-6x%5E2-2x%2B1%7D%3D1+%2B+2+x+%2B+10+x%5E2+%2B+25+x%5E3+%2B+95+x%5E4+%2B+268+x%5E5+%2B+921+x%5E6+%2B+2760+x%5E7+%2B+9075+x%5E8+%2B+27995+x%5E9+%2B...&bg=ffffff&fg=333333&s=0
"\\dfrac{1}{x^4+7x^3-6x^2-2x+1}=1 + 2 x + 10 x^2 + 25 x^3 + 95 x^4 + 268 x^5 + 921 x^6 + 2760 x^7 + 9075 x^8 + 27995 x^9 +...")

Thus, this map function has a peculiar property with respect to the
roots of the polynomials
![P\_1](https://s0.wp.com/latex.php?latex=P_1&bg=ffffff&fg=333333&s=0
"P_1") and
![P\_2](https://s0.wp.com/latex.php?latex=P_2&bg=ffffff&fg=333333&s=0
"P_2") in that applying it one root yields another in cyclic fashion.
Given that for both these polynomials there is a root close to
![\\beta'](https://s0.wp.com/latex.php?latex=%5Cbeta%27&bg=ffffff&fg=333333&s=0
"\\beta'"), these can “capture” the
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") approaching it and drive them into a cycle. Thus, these might be
seen as stable examples of the motifs encountered in the Type-1
behavior.

**Type-4: Convergence to bounded bands after initial eruptions and
instability**  
This type of behavior is exhibited by the Copper ratio-based map:  
![x\_{n+1}=\\dfrac{2x\_n-1}{x\_n^2+4x\_n-1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7B2x_n-1%7D%7Bx_n%5E2%2B4x_n-1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{2x_n-1}{x_n^2+4x_n-1}")

Evolution under this map has parallels to the Type-3 behavior. Like in
Type-3, after initial instability, which might include some eruptions
and chaotic fluctuations, the evolution under the map settles to cycling
between specific bounded bands. Within those bands it wanders
quasi-chaotically, i.e. with some discernible patterns, but never leaves
those bands. Number iterations taken by different
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") to converge to cycling within those bands can vary greatly
(Figure 17).

[![bouncer\_covergence\_Fig17](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence_fig17.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence_fig17.png)Figure
17.

Here,
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") are sampled in the interval
![(-40,40)](https://s0.wp.com/latex.php?latex=%28-40%2C40%29&bg=ffffff&fg=333333&s=0
"(-40,40)") in steps of .01. The plot shows a pattern with zones of
rapid convergence interspersed with clusters of much longer convergence
times. When we zoom in on a region with a cluster of slowly converging
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") we see that the number of iterations to converge to the
band-cycle shows a fractal pattern (Figure 18).

[![bouncer\_covergence\_Fig18](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence_fig18.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/bouncer_covergence_fig18.png)Figure
18.

Here, the
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") are sampled in the interval
![(-4,4)](https://s0.wp.com/latex.php?latex=%28-4%2C4%29&bg=ffffff&fg=333333&s=0
"(-4,4)") at steps of .001. In both these cases a pseudo-symmetry
similar to the iterations-to-convergence plot for the Type-3 behavior
(Figure 16) is observed. Here too there is a static point ![x\_s
\\approx
-4.68577952...](https://s0.wp.com/latex.php?latex=x_s+%5Capprox+-4.68577952...&bg=ffffff&fg=333333&s=0
"x_s \\approx -4.68577952..."), which is the real root of
![x^3+4x^2-3x+1=0](https://s0.wp.com/latex.php?latex=x%5E3%2B4x%5E2-3x%2B1%3D0&bg=ffffff&fg=333333&s=0
"x^3+4x^2-3x+1=0"); it returns itself under the map. Unless one is
exactly at
![x\_s](https://s0.wp.com/latex.php?latex=x_s&bg=ffffff&fg=333333&s=0
"x_s") which has a very complicated closed form, any other
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") in the vicinity continues to converge to the band-cycle.

[![band\_convergence\_Fig19](https://manasataramgini.files.wordpress.com/2019/08/band_convergence_fig19.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/band_convergence_fig19.png)Figure
19.

To examine this type of behavior more closely we consider the evolution
of
![x\_0=4.37](https://s0.wp.com/latex.php?latex=x_0%3D4.37&bg=ffffff&fg=333333&s=0
"x_0=4.37") (Figure 19), which is particularly slowly converging in
Figure 17. We find that there is a massive eruption little after
![n=150](https://s0.wp.com/latex.php?latex=n%3D150&bg=ffffff&fg=333333&s=0
"n=150") (eruptions
![\>20](https://s0.wp.com/latex.php?latex=%3E20&bg=ffffff&fg=333333&s=0
"\>20") are marked with red points), which is lodged in the midst of
generally chaotic behavior which lasts till close to
![n=260](https://s0.wp.com/latex.php?latex=n%3D260&bg=ffffff&fg=333333&s=0
"n=260") (see lower panel in
![\\mathrm{arcsinh}(x)](https://s0.wp.com/latex.php?latex=%5Cmathrm%7Barcsinh%7D%28x%29&bg=ffffff&fg=333333&s=0
"\\mathrm{arcsinh}(x)") scale). Not surprisingly, within this region, we
observe that, as in the previous types of behavior, the eruptions occur
in
![x\_{n+1}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}") when
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") (marked with blue points) approaches ![\\kappa',
-\\kappa](https://s0.wp.com/latex.php?latex=%5Ckappa%27%2C+-%5Ckappa&bg=ffffff&fg=333333&s=0
"\\kappa', -\\kappa") (marked with blue horizontal lines). However, the
striking feature of this type is that sometime after this region the map
settles into a more regular cycling behavior and never leaves it to
degree we have tested these maps
![(n=100000)](https://s0.wp.com/latex.php?latex=%28n%3D100000%29&bg=ffffff&fg=333333&s=0
"(n=100000)"). We examine this cyclic behavior more closely in Figure
20.

[![band\_convergence\_points\_Fig20](https://manasataramgini.files.wordpress.com/2019/08/band_convergence_points_fig20.png?w=640)](https://manasataramgini.files.wordpress.com/2019/08/band_convergence_points_fig20.png)Figure
20.

Here, we plot the evolution of
![x\_0=4.37](https://s0.wp.com/latex.php?latex=x_0%3D4.37&bg=ffffff&fg=333333&s=0
"x_0=4.37") for
![n=300..3000](https://s0.wp.com/latex.php?latex=n%3D300..3000&bg=ffffff&fg=333333&s=0
"n=300..3000"). We find that the
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") falls in very specific bands:  
1\) A very narrow middle band centered at
![\\frac{2}{5+\\sqrt{5}}\\approx
0.276393...](https://s0.wp.com/latex.php?latex=%5Cfrac%7B2%7D%7B5%2B%5Csqrt%7B5%7D%7D%5Capprox+0.276393...&bg=ffffff&fg=333333&s=0
"\\frac{2}{5+\\sqrt{5}}\\approx 0.276393...") (Figure 20, red points).

2\) A lower band bounded by ![\\left(-2 -\\frac{\\sqrt{5}}{2}\\approx
-3.118033, -2 -\\frac{1}{\\sqrt{5}} \\approx -2.447213
\\right)](https://s0.wp.com/latex.php?latex=%5Cleft%28-2+-%5Cfrac%7B%5Csqrt%7B5%7D%7D%7B2%7D%5Capprox+-3.118033%2C+-2+-%5Cfrac%7B1%7D%7B%5Csqrt%7B5%7D%7D+%5Capprox+-2.447213+%5Cright%29&bg=ffffff&fg=333333&s=0
"\\left(-2 -\\frac{\\sqrt{5}}{2}\\approx -3.118033, -2 -\\frac{1}{\\sqrt{5}} \\approx -2.447213 \\right)")
(Figure 20, violet points).

3\) An upper band bounded by ![\\left(\\sqrt{5}-1 \\approx 1.236067,
\\frac{20+4\\sqrt{5}}{15} \\approx
1.929618\\right)](https://s0.wp.com/latex.php?latex=%5Cleft%28%5Csqrt%7B5%7D-1+%5Capprox+1.236067%2C+%5Cfrac%7B20%2B4%5Csqrt%7B5%7D%7D%7B15%7D+%5Capprox+1.929618%5Cright%29&bg=ffffff&fg=333333&s=0
"\\left(\\sqrt{5}-1 \\approx 1.236067, \\frac{20+4\\sqrt{5}}{15} \\approx 1.929618\\right)")
(Figure 20, blue points).

In the state of convergence the map cycles from the middle band to the
upper to the lower band over 3 successive
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n"). Beyond these bands, there are two lines:  
1\) in the lower band corresponding to ![\\frac{2577-1221 \\sqrt{5}}{58}
\\approx
-2.6420517](https://s0.wp.com/latex.php?latex=%5Cfrac%7B2577-1221+%5Csqrt%7B5%7D%7D%7B58%7D+%5Capprox+-2.6420517&bg=ffffff&fg=333333&s=0
"\\frac{2577-1221 \\sqrt{5}}{58} \\approx -2.6420517")

2\) in the upper band corresponding to
![\\frac{5-\\sqrt{5}}{2}](https://s0.wp.com/latex.php?latex=%5Cfrac%7B5-%5Csqrt%7B5%7D%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"\\frac{5-\\sqrt{5}}{2}")

It is notable that the above band-bounds and lines are all related to
![\\sqrt{5}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B5%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{5}") which is the surd in ![\\kappa,
\\kappa'](https://s0.wp.com/latex.php?latex=%5Ckappa%2C+%5Ckappa%27&bg=ffffff&fg=333333&s=0
"\\kappa, \\kappa'"). They are indicated by horizontal lines in the
plot. From the two lines within the bands the points appear to
alternately wander towards the upper and lower bounds of the upper and
lower bands. As the map evolves, once they reach close the bounds the
process repeats again starting from those lines (Figure 20). Each round
of wandering is largely symmetric between the upper and lower bands but
each round is different from the previous one. In this, type as in
Type-3 it appears that
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") is captured into the band cycle as it approaches
![\\kappa'](https://s0.wp.com/latex.php?latex=%5Ckappa%27&bg=ffffff&fg=333333&s=0
"\\kappa'") which is close to the central band defined by
![\\frac{2}{5+\\sqrt{5}}](https://s0.wp.com/latex.php?latex=%5Cfrac%7B2%7D%7B5%2B%5Csqrt%7B5%7D%7D&bg=ffffff&fg=333333&s=0
"\\frac{2}{5+\\sqrt{5}}").

**Tailpiece**  
There are several open questions (for us) regarding these
investigations. Is there a formal way of deriving which roots a map may
converge to if it shows a Type-3 behavior? Is there a way to formally
establish the bands of convergence for Type-4 behavior? Is there way to
say whether a map would go the way of Type-1 or Type-2 from its
equation?

Whatever the case, the maps discussed here are most remarkable because
they can produce complex behavior similar to that observed in natural
systems with very simple underlying equations. They illustrate cases of
long quiescence (Type-1 and Type-2) with eruptive behavior. These
behavior suggests that prolonged low amplitude oscillations or secular
changes do not guarantee the absence of sudden eruptions. This is
important in realizing that situations like prolonged peace do not mean
that there would no major catastrophic conflict. This suddenly emerges
as the system moves towards a superficially unremarkable low magnitude
state that in reality is something like the metallic ratio trigger seen
in these maps. Then we have the reverse behavior where after an initial
chaotic phase the map settles into a more regular behavior from which it
never emerges due to being captured by certain similarly superficially
unremarkable values (Type-3 and Type-4). In history we see that the
dramatic movements that occur early in a civilization are never
reproduced in the later stages from which it might be unable to break
out.
