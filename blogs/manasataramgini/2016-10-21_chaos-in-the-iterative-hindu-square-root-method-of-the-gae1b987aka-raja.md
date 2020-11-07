+++
title = "Chaos in the iterative Hindu square root method of the gaṇaka-rāja"

+++
For Hindus big numbers always mattered and our mathematics is quite
reflection of this fascination. Since the earliest times, Hindus devised
various methods to obtain square roots of numbers, especially
approximations of irrational roots correct to multiple decimal places.
The earliest of these methods involving a series of terms is seen
encoded in the altars for the Soma rituals specified in the saṃhitā-s of
the Yajurveda and explicitly spelled out in their the śulbasūtra-s.
Indeed, we have evidence that development of these methods continued in
the Yajurvaidika tradition as indicated by Rāma dīkṣita’s commentary on
Kātyāyana where he provides a tradition regarding a further term to the
approximation to get
![\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}") correct to 7 decimal places. A similar improvement was
likely used in the procedure preserved by Sundararāja dīkṣita in the
Āpastamba tradition for an approximate squaring of the circle based on
![\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}").

By the last few centuries before the common era the Hindus had already
discovered a method similar to what is today known in the west as the
first term Newton-Raphson approximation. We also see the exact algorithm
for both square roots and cube roots of ācārya Āryabhaṭa further
explained for the lay by Bhāskara-I. But the high point of the Hindu
tradition of iterative methods is seen in the text of the brāḥmaṇa
Chajjaka-putra gaṇaka-rāja probably from Mārtikāvati (unfortunately
named Bakshali manuscript: BM), which gives a glimpse of just what Hindu
knowledge has been lost over the ages. While this method was
misunderstood by the earlier white indological translator of the BM, the
sophistication of the gaṇaka-rāja’s method has only more recently become
clear. This has been explained and commented upon in detail by the
computer scientists Bailey and Borwein in their excellent work on the
same. We shall here comment upon an interesting aspect we discovered of
the functions involved in the method .

While the method has already been discussed in detail by Bailey and
Borwein, we shall go over it here for introducing the system. In order
the find the square root of a number
![q](https://s0.wp.com/latex.php?latex=q&bg=ffffff&fg=333333&s=0 "q")
the BM suggests the following procedure:  
Take some starting number: ![x\_n =
x\_0](https://s0.wp.com/latex.php?latex=x_n+%3D+x_0&bg=ffffff&fg=333333&s=0
"x_n = x_0")  
![x\_{n+1}=\\dfrac{q-x\_n^2}{2x\_n}](https://s0.wp.com/latex.php?latex=x_%7Bn%2B1%7D%3D%5Cdfrac%7Bq-x_n%5E2%7D%7B2x_n%7D&bg=ffffff&fg=333333&s=0
"x_{n+1}=\\dfrac{q-x_n^2}{2x_n}")  
![y\_n=x\_n+x\_{n+1}-\\dfrac{x\_{n+1}^2}{2(x\_n+x\_{n+1})}](https://s0.wp.com/latex.php?latex=y_n%3Dx_n%2Bx_%7Bn%2B1%7D-%5Cdfrac%7Bx_%7Bn%2B1%7D%5E2%7D%7B2%28x_n%2Bx_%7Bn%2B1%7D%29%7D&bg=ffffff&fg=333333&s=0
"y_n=x_n+x_{n+1}-\\dfrac{x_{n+1}^2}{2(x_n+x_{n+1})}")

Then ![y\_n \\approx
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y_n+%5Capprox+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y_n \\approx \\sqrt{q}"). Now if we take
![x\_n=y\_n](https://s0.wp.com/latex.php?latex=x_n%3Dy_n&bg=ffffff&fg=333333&s=0
"x_n=y_n") and iterate the above procedure we get increasingly accurate
approximations of
![\\sqrt{q}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{q}").

As a example let us take ![q =
5](https://s0.wp.com/latex.php?latex=q+%3D+5&bg=ffffff&fg=333333&s=0
"q = 5") and
![x\_0=0.1](https://s0.wp.com/latex.php?latex=x_0%3D0.1&bg=ffffff&fg=333333&s=0
"x_0=0.1"). Then we have the following:  
![1)\\; 12.6248003992015985\\\\ 2) \\; 3.6392111847990769\\\\ 3) \\;
2.2506636482615887\\\\ 4) \\; 2.2360679780006203\\\\ 5) \\;
2.2360679774997898](https://s0.wp.com/latex.php?latex=1%29%5C%3B+12.6248003992015985%5C%5C+2%29+%5C%3B+3.6392111847990769%5C%5C+3%29+%5C%3B+2.2506636482615887%5C%5C+4%29+%5C%3B+2.2360679780006203%5C%5C+5%29+%5C%3B+2.2360679774997898&bg=ffffff&fg=333333&s=0
"1)\\; 12.6248003992015985\\\\ 2) \\; 3.6392111847990769\\\\ 3) \\; 2.2506636482615887\\\\ 4) \\; 2.2360679780006203\\\\ 5) \\; 2.2360679774997898")  
Thus, in iteration 3 the value of
![\\sqrt{5}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B5%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{5}") correct to 1 decimal place, in iteration 4 it is correct to
8 decimal places and in iteration 5 it is correct to at least 16 decimal
places, in line with the Hindu love for big numbers.

Now if we instead take
![x\_0=2](https://s0.wp.com/latex.php?latex=x_0%3D2&bg=ffffff&fg=333333&s=0
"x_0=2") because we know that
![\\sqrt{5}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B5%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{5}") should lie somewhere in the vicinity of 2 then we get:  
![1) \\; 2.2361111111111112\\\\ 2) \\;
2.2360679774997898](https://s0.wp.com/latex.php?latex=1%29+%5C%3B+2.2361111111111112%5C%5C+2%29+%5C%3B+2.2360679774997898&bg=ffffff&fg=333333&s=0
"1) \\; 2.2361111111111112\\\\ 2) \\; 2.2360679774997898")  
Thus, with this close value right in the first iteration we get it
correct to 3 decimal places and in the second to at least 16 decimal
places\! As Bailey and Borwein had shown it quartically converges on the
square root. Now if we take a negative number for
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") it then converges similarly to
![-\\sqrt{q}](https://s0.wp.com/latex.php?latex=-%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"-\\sqrt{q}").

![hindu\_figure1](https://manasataramgini.files.wordpress.com/2016/10/hindu_figure1.png?w=640)Figure
1

Now consider the following alternative procedure where instead of
plugging
![x\_n=y\_n](https://s0.wp.com/latex.php?latex=x_n%3Dy_n&bg=ffffff&fg=333333&s=0
"x_n=y_n") we plug ![x\_n=
x\_{n+1}](https://s0.wp.com/latex.php?latex=x_n%3D+x_%7Bn%2B1%7D&bg=ffffff&fg=333333&s=0
"x_n= x_{n+1}") and thus generate for each iteration
![(x\_{n+1},y\_n)](https://s0.wp.com/latex.php?latex=%28x_%7Bn%2B1%7D%2Cy_n%29&bg=ffffff&fg=333333&s=0
"(x_{n+1},y_n)"). On plotting the map of
![(x\_{n+1},y\_n)](https://s0.wp.com/latex.php?latex=%28x_%7Bn%2B1%7D%2Cy_n%29&bg=ffffff&fg=333333&s=0
"(x_{n+1},y_n)") we see the points fall on an interesting curve (Figure
1). This curve has two boat-shaped branches which are respectively
tangential to the lines ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}"). The region of tangency is peculiar in that the
curve lingers in the proximity of ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}") over a wide x-interval.

![hindu\_figure2](https://manasataramgini.files.wordpress.com/2016/10/hindu_figure2.png?w=640)

Figure 2

The actual map of the points obtained by the above procedure displays an
interesting feature: they are spread all over the two branches of the
curve above but fall most frequently in the vicinity of the two root
lines. They notably decrease in frequency as one moves away from those
lines but we do get to see extreme points far away from the two root
lines. Thus, ![\\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"\\pm \\sqrt{q}") serve as the peaks (Figure 2) for the distribution of
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") with a clear decline for greater and lesser allowed values
respectively. However, the tails of their distribution are prominent
enough that we seen multiple extreme values. The median value for the
negative side of the distribution is ![\\approx
-2.3](https://s0.wp.com/latex.php?latex=%5Capprox+-2.3&bg=ffffff&fg=333333&s=0
"\\approx -2.3") and for the positive side is ![\\approx
2.3](https://s0.wp.com/latex.php?latex=%5Capprox+2.3&bg=ffffff&fg=333333&s=0
"\\approx 2.3"), illustrating the dominance of the values close to
![\\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"\\pm \\sqrt{q}"). In line with this, for a large enough number of
iterations with a given
![x\_0](https://s0.wp.com/latex.php?latex=x_0&bg=ffffff&fg=333333&s=0
"x_0") the overall median value of
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") comes out as ![\\pm \\sqrt{q}
](https://s0.wp.com/latex.php?latex=%5Cpm+%5Csqrt%7Bq%7D+&bg=ffffff&fg=333333&s=0
"\\pm \\sqrt{q} "). However, below is an examination of the extreme
values reached by
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") for a run initiated with
![q=5](https://s0.wp.com/latex.php?latex=q%3D5&bg=ffffff&fg=333333&s=0
"q=5"),
![x\_0=0.1](https://s0.wp.com/latex.php?latex=x_0%3D0.1&bg=ffffff&fg=333333&s=0
"x_0=0.1") for 2000 iterations:  
Minimum:
![-438.98149](https://s0.wp.com/latex.php?latex=-438.98149&bg=ffffff&fg=333333&s=0
"-438.98149")  
Maximum:
![133.19996](https://s0.wp.com/latex.php?latex=133.19996&bg=ffffff&fg=333333&s=0
"133.19996")  
This shows that
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") explores values over 50-100 times the median values in course of
the iterations.

To understand this map better let us look at it geometrically (Figure
3). The two expressions that are deployed successively by Chajjaka-putra
to get the square root represent the below functions:  
![f(t)= \\dfrac{q-t^2}{2t}\\\\
g\\left(t\\right)=t+f\\left(t\\right)-\\dfrac{f\\left(t\\right)^2}{2\\left(t+f\\left(t\\right)\\right)}\\\\\[10pt\]
\\therefore
g\\left(t\\right)=\\dfrac{q^2+6qt^2+t^4}{4qt+4t^3}](https://s0.wp.com/latex.php?latex=f%28t%29%3D+%5Cdfrac%7Bq-t%5E2%7D%7B2t%7D%5C%5C+g%5Cleft%28t%5Cright%29%3Dt%2Bf%5Cleft%28t%5Cright%29-%5Cdfrac%7Bf%5Cleft%28t%5Cright%29%5E2%7D%7B2%5Cleft%28t%2Bf%5Cleft%28t%5Cright%29%5Cright%29%7D%5C%5C%5B10pt%5D+%5Ctherefore+g%5Cleft%28t%5Cright%29%3D%5Cdfrac%7Bq%5E2%2B6qt%5E2%2Bt%5E4%7D%7B4qt%2B4t%5E3%7D&bg=ffffff&fg=333333&s=0
"f(t)= \\dfrac{q-t^2}{2t}\\\\ g\\left(t\\right)=t+f\\left(t\\right)-\\dfrac{f\\left(t\\right)^2}{2\\left(t+f\\left(t\\right)\\right)}\\\\[10pt] \\therefore g\\left(t\\right)=\\dfrac{q^2+6qt^2+t^4}{4qt+4t^3}")

![hindu\_figure3](https://manasataramgini.files.wordpress.com/2016/10/hindu_figure3.png?w=640)

Figure 3

We see that
![f(t)](https://s0.wp.com/latex.php?latex=f%28t%29&bg=ffffff&fg=333333&s=0
"f(t)") is a hyperbola with the y-axis as one of its asymptotes.
![g(t)](https://s0.wp.com/latex.php?latex=g%28t%29&bg=ffffff&fg=333333&s=0
"g(t)") is a quartic curve, which has ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}") as the as its tangents with the points of tangency
being
![(\\sqrt{q},\\sqrt{q})](https://s0.wp.com/latex.php?latex=%28%5Csqrt%7Bq%7D%2C%5Csqrt%7Bq%7D%29&bg=ffffff&fg=333333&s=0
"(\\sqrt{q},\\sqrt{q})") and
![(-\\sqrt{q},-\\sqrt{q})](https://s0.wp.com/latex.php?latex=%28-%5Csqrt%7Bq%7D%2C-%5Csqrt%7Bq%7D%29&bg=ffffff&fg=333333&s=0
"(-\\sqrt{q},-\\sqrt{q})"). This curve has a very “flat” type of
tangency, i.e. it lingers in the proximity of ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}") over an extended x-range. This is the secret of the
gaṇaka-rāja’s method firmly “pulling” things to the vicinity of required
square root. Thus, the parametric curve
![(f(t),g(t))](https://s0.wp.com/latex.php?latex=%28f%28t%29%2Cg%28t%29%29&bg=ffffff&fg=333333&s=0
"(f(t),g(t))") is the one on which the points of the above-described map
based on gaṇaka-rāja’s two expressions lie (Figure 1, 3). This curve as
noted from the above map has ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}") as its tangents with the point of tangency at
![(0,0)](https://s0.wp.com/latex.php?latex=%280%2C0%29&bg=ffffff&fg=333333&s=0
"(0,0)"), but like
![g(t)](https://s0.wp.com/latex.php?latex=g%28t%29&bg=ffffff&fg=333333&s=0
"g(t)") it lingers over a wide x-range close to the point of tangency.
This explains why the map tends to concentrate the points in the
vicinity of ![y=\\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y=\\pm \\sqrt{q}").

Now, if we look at the positions of actual points of the map on
![(f(t),g(t))](https://s0.wp.com/latex.php?latex=%28f%28t%29%2Cg%28t%29%29&bg=ffffff&fg=333333&s=0
"(f(t),g(t))") an interesting observation becomes apparent: while
tending to cluster in the vicinity of ![y= \\pm
\\sqrt{q}](https://s0.wp.com/latex.php?latex=y%3D+%5Cpm+%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"y= \\pm \\sqrt{q}"), successive points are not necessarily proximal to
each other on the curve. Rather they jump about the curve in a chaotic
fashion (Figure 3) either on the same branch or between the two
branches. This becomes even rather apparent if we plot a run of
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") against iteration number
![n=1..2000](https://s0.wp.com/latex.php?latex=n%3D1..2000&bg=ffffff&fg=333333&s=0
"n=1..2000") (Figure 4; The gaps in the plot are where the
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") jumped outside the range of ![\\pm
50](https://s0.wp.com/latex.php?latex=%5Cpm+50&bg=ffffff&fg=333333&s=0
"\\pm 50") which we set for good visualization). What is notable is that
the rarer values in addition to appearing chaotically are also rather
extreme: the sum of positive
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") for 2000 iterations with
![x\_0=0.1](https://s0.wp.com/latex.php?latex=x_0%3D0.1&bg=ffffff&fg=333333&s=0
"x_0=0.1") is
![4578.39](https://s0.wp.com/latex.php?latex=4578.39&bg=ffffff&fg=333333&s=0
"4578.39"); of this just 12 values add up to
![1005.48](https://s0.wp.com/latex.php?latex=1005.48&bg=ffffff&fg=333333&s=0
"1005.48"), which is ![\\approx
22](https://s0.wp.com/latex.php?latex=%5Capprox+22&bg=ffffff&fg=333333&s=0
"\\approx 22") percent of the total sum. Each of these 12 extreme values
is over 20 times the median value of positive
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n"). The picture is roughly symmetric for the negative values.

![hindu\_figure4](https://manasataramgini.files.wordpress.com/2016/10/hindu_figure4.png?w=640)

Figure 4

Importantly, this chaotic behavior of
![y\_n](https://s0.wp.com/latex.php?latex=y_n&bg=ffffff&fg=333333&s=0
"y_n") is very sensitive to the initial values of
![x\_n](https://s0.wp.com/latex.php?latex=x_n&bg=ffffff&fg=333333&s=0
"x_n") with which we start the map. This is dramatically illustrated by
two points close to root of
![q=5](https://s0.wp.com/latex.php?latex=q%3D5&bg=ffffff&fg=333333&s=0
"q=5"),
![2.2](https://s0.wp.com/latex.php?latex=2.2&bg=ffffff&fg=333333&s=0
"2.2") and
![2.21](https://s0.wp.com/latex.php?latex=2.21&bg=ffffff&fg=333333&s=0
"2.21") (Figure 5): while for the first 9 iterations the evolution of
the two initial values is the same in direction though not magnitude,
iteration 10 and beyond they go completely out of synchrony in both
direction and magnitude.

![hind\_figure5](https://manasataramgini.files.wordpress.com/2016/10/hind_figure5.png?w=640)

Figure 5

In conclusion this map provides an analogy to think about certain
processes in nature and historical events. First, it provides a
potential model for foraging behavior of variety of organisms. In this
model the clustering around the root values represents what might be
called the base-line or ordinary foraging and the extreme jumps
represent the drastic forays away from their local patch to distant
locales. Such behavior may be seen in animals among herbivores moving to
new feeding grounds far from their usual feeding areas or certain
carnivores like sharks seeking new hunting waters far from their their
current zone. This kind of behavior is also seen in certain ciliates
like Halteria in the microscopic realm. In the world of protein
sequences we see a similar tendency to keep to a tightly constrained
space of diversity under purifying selection within which there is a
low-radius exploration under neutral drift. This is punctuated by huge
saltations that result from strong positive selection for new functional
niches. This might happen within a family of proteins or in the proteome
of an organism with some proteins showing big saltations in sequence
space.

The great mathematician Benoit Mandelbrot, the pioneer in the study of
chaos, has brought home the importance of distributions with rare events
with extreme values. The role of such events in systems like financial
markets has been recently explained at length by Nassim Taleb. In this
context, the above-described map provides an analogy for one type of
historical evolution of systems. Even with same basic parameter (
![\\sqrt{q}](https://s0.wp.com/latex.php?latex=%5Csqrt%7Bq%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{q}")), clearly predictable bulk statistics (e.g. median and
range of most frequent values) and similar starting values we see: 1)
clear differences in long term evolution with non-overlapping chaotic
extreme events different in both magnitude and direction. 2) Extreme
events that can disproportionately contribute to the total numerical
measure of the events in the series. A historical system evolving under
such a model shows us how with very similar starting material and bulk
behavior we can have a great difference in actual events and outcomes.
This might be similar to actually observed phenomena like the fall
empires or the sudden extinction of long-lasting lineages. This is a
theme which we might explore further with examples of some other such
systems which have been studied for their chaos.
