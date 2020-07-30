+++
title = "Cricket in pictures"

+++
We may say that cricket has nearly passed us by. In our youth we played
and watched the game quite a bit. While in secondary school we were
fairly interested in cricket statistics. The sources for statistics were
not easily available those days. We would obtain them bit by bit from
the occasional sports magazine our father might purchase, or from a
cricket magazine at our local English library, or from sports quizzes on
television, or they might stream in from acquaintances and certain
relatives. But as we grew older this interest waned. When we were in
college, our brother was passing through a similar phase of interest,
which re-ignited ours and also now we sought to see it through the lens
of statistical distributions and probability. However, those experiments
were generally tedious and not the most exciting thing we had on our
hands. As we aged into young adulthood and beyond, cricket kept
increasingly passing out of our focus. Thus, we had reasonable
familiarity with the heroics of Kapil Dev, Gavaskar, Shrikant,
Tendulkar, Dravid, Sehwag and Laxman, less-so with Dhoni, and even less
so with Kohli. Still, we say it has only nearly passed us by because,
though we do not watch it anymore, we still have it streaming to us once
in a way from friends and colleagues.

Due to such impingements we recently wondered about re-visiting certain
statistical distributions in cricket. This urge finally precipitated due
some discussion on Twitter regarding cricket statistics. We would like
to acknowledge those discussions for inducing us to write this note that
many might perceive as an unnecessary endeavor but a man should always
pay attention to distributions and statistical properties for they can
might help him in other walks of life. Here we take a look a some such
for batting performances in Test cricket for we believe that it is the
highest and the most satisfying form of the game. The sources of
statistics for the below meanderings are the following: 1) A compilation
of 73 top batsmen from the HowzStat Cricket Database; 2) A compilation
of 301 batsmen scoring 2000 runs or more from Cricinfo; 3) A large data
collection for all batsmen for all international matches, which was
prepared by and kindly provided as a convenient csv file by [Anupam
Singh](https://twitter.com/anupampom). The first two were leached from
html and converted to csv files. The third file needed some
post-processing for removing duplicates and null records. That said let
us look at the data.

**Basic features of batting in test matches**

[![Figure1\_Tests\_summary](https://manasataramgini.files.wordpress.com/2018/12/Figure1_Tests_summary.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure1_Tests_summary.png)Figure
1

In the first panel of Figure 1 we see the frequency distribution of runs
scored by the bat in an innings of a test match. It is a left truncated,
right skewed distribution with a clear central tendency: a modal peak
around 220 runs and a median of 239 runs. The second panel shows the
frequency distribution of the number of fours in a given test innings.
It again shows a similar distribution shape as the total number of runs
scored by the bat in an innings. It has a modal peak at around 22-23
fours and a median value of 26 fours. That translates to a median value
of 104 runs in a test innings being scored by fours. When we compare
this to the first graph we can say that speaking in terms of central
tendency about
![44\\%](https://s0.wp.com/latex.php?latex=44%5C%25&bg=ffffff&fg=333333&s=0
"44\\%") of the innings is scored by fours.

Sixes are much rarer in test cricket and their distribution is shown in
panel 3 of Figure 1: the fraction of innings with ![n=0, 1, 2,
3...](https://s0.wp.com/latex.php?latex=n%3D0%2C+1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0
"n=0, 1, 2, 3...") sixes. This shows a non-linear decay law which might
be approximated by an exponential function of the form
![y=ae^{-bx}](https://s0.wp.com/latex.php?latex=y%3Dae%5E%7B-bx%7D&bg=ffffff&fg=333333&s=0
"y=ae^{-bx}"). While this works in the range 1..14 sixes, it fails to
captures the maximal 0 sixes fraction or the more extreme values. The
Poisson distribution and power-law also do not approximate it well.

The strike rate of a batsman is defined as the ratio the number of runs
scored to the number of balls faced expressed as as a percentage. In the
fourth panel we have the frequency distribution of the mean strike rates
for test batsmen computed for all scores greater than 10. It shows a
strong central tendency close of
![50\\%](https://s0.wp.com/latex.php?latex=50%5C%25&bg=ffffff&fg=333333&s=0
"50\\%").

[![Figure2\_innings\_run\_scored](https://manasataramgini.files.wordpress.com/2018/12/Figure2_innings_run_scored.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure2_innings_run_scored.png)Figure
2

This sets the baseline for some further analysis. In Figure 2 we look at
the frequency distribution of the scores for each innings. We did expect
to see the median score fall with each innings. However, the non-linear
nature of the fall and the changing shape of the distribution is
notable. The first two innings have an almost triangular distribution,
while the third innings is more of a skewed bell-shaped distribution.
Obtaining functions that approximate these will be a problem of
interest. The fourth innings has the lowest scores. This is due to two
reasons: it is the innings of the final chase to win the match. Now, if
the final total needed for a win is small then the forth innings scores
would be low. Further, as the pitch deteriorates through the match
fourth innings will favor the batsmen the least and the bowlers the
most. This was even more in the past when the pitches were not protected
overnight. However, this decline does suggests that barring special
weather conditions, winning the toss and batting first gives the team
which does so an advantage in the match.

[![Figure3\_fourssixes\_bigscores](https://manasataramgini.files.wordpress.com/2018/12/Figure3_fourssixes_bigscores.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure3_fourssixes_bigscores.png)Figure
3

In Figure 3 we look at frequency distribution of what fraction of big
individual scores of a batsmen, i.e those of 50, 100, 150, 200 or
greater are scored by fours and sixes. These are roughly normally
distributed with a mean close to 0.5: thus, on an average about half of
a big individual score in tests is attained by shots touching or
clearing the fence.

[![Figure4\_poisson100s](https://manasataramgini.files.wordpress.com/2018/12/Figure4_poisson100s.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure4_poisson100s.png)Figure
4

We then analyzed the probability of a test inning containing a century.
We found that the fraction of test innings containing ![n=0, 1, 2,
3...](https://s0.wp.com/latex.php?latex=n%3D0%2C+1%2C+2%2C+3...&bg=ffffff&fg=333333&s=0
"n=0, 1, 2, 3...") innings can be well-described by a Poisson
distribution. We empirically determined the ![\\lambda=
0.485](https://s0.wp.com/latex.php?latex=%5Clambda%3D+0.485&bg=ffffff&fg=333333&s=0
"\\lambda= 0.485") for this Poisson distribution. The ![p\\approx
1](https://s0.wp.com/latex.php?latex=p%5Capprox+1&bg=ffffff&fg=333333&s=0
"p\\approx 1") for Poisson-predicted frequencies matching observed
frequencies by the
![\\chi^2](https://s0.wp.com/latex.php?latex=%5Cchi%5E2&bg=ffffff&fg=333333&s=0
"\\chi^2") test. In figure 3 the hatched bars are the predicted values
and the blue bars are the observed values.

![Figure5\_all100\_distribution](https://manasataramgini.files.wordpress.com/2018/12/Figure5_all100_distribution.png?w=640)Figure
5

In Figure 5 we analyzed the frequency distribution of individual scores
of batsmen that are ![\\ge
100](https://s0.wp.com/latex.php?latex=%5Cge+100&bg=ffffff&fg=333333&s=0
"\\ge 100"). It shows a clear-cut decay law. This steep decay is best
captured by a power law of the form
![y=kx^a](https://s0.wp.com/latex.php?latex=y%3Dkx%5Ea&bg=ffffff&fg=333333&s=0
"y=kx^a"), indicated by the blue line in Figure 5 (goodness of fit
deviation fraction: 0.96). However, for scores ![\\ge
130](https://s0.wp.com/latex.php?latex=%5Cge+130&bg=ffffff&fg=333333&s=0
"\\ge 130") an exponential decay fits the observed distribution at least
as well as a power law (Red curve in Figure 5; goodness of fit deviation
fraction: 0.94). Overall, it is fair to say that a power-law
distribution approximately describes the distribution of scores ![\\ge
100](https://s0.wp.com/latex.php?latex=%5Cge+100&bg=ffffff&fg=333333&s=0
"\\ge 100").

**Apprehending the great batsmen**  
For this analysis we used a dataset of 301 batsmen who have scored over
2000 runs and have had an average career strike rate of ![\\ge
20](https://s0.wp.com/latex.php?latex=%5Cge+20&bg=ffffff&fg=333333&s=0
"\\ge 20"). This dataset records the number of innings played, number of
times the player is unbeaten, total runs scored, highest score, career
average, career strike rate, and 100s, 50s and 0s scored. We performed a
principle component analysis using a subset of the numerical variables
in this dataset for which good records are available (Highest score,
number of 100s, number of 50s, career average, and strike rate) after
scaling and centering. The first two components which together account
for ![\\approx
\\tfrac{3}{4}](https://s0.wp.com/latex.php?latex=%5Capprox+%5Ctfrac%7B3%7D%7B4%7D&bg=ffffff&fg=333333&s=0
"\\approx \\tfrac{3}{4}") of the variation, and their plot is show in
Figure 6.

[![Figure6\_PCA\_great\_batsmen](https://manasataramgini.files.wordpress.com/2018/12/Figure6_PCA_great_batsmen.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure6_PCA_great_batsmen.png)Figure
6

There is not much clumping but a set of “greatest” batsmen can be simply
separated by choosing those with a first axis value ![\\le
-2.3](https://s0.wp.com/latex.php?latex=%5Cle+-2.3&bg=ffffff&fg=333333&s=0
"\\le -2.3") (red dots in Figure 6). At the extreme end of this this
axis lie Tendulkar, Bradman and Lara (circled in green in Figure 6), who
have quite unequivocally be mentioned as being among the greatest
players. In this set two players are clearly separated from the rest
(circled in dark red in Figure 6): Sehwag and Vivian Richards. These are
two great batsmen marked by the rapid scoring rates and were a delight
for the spectator. The one other Indian player who was notable for his
scoring rate when I was young was Kapil Dev, who lies to the right side
(circled in blue). While possessing a notable strike rate, as we can
see, he was far too inconsistent to make it anywhere close to the great
batsmen region. Finally, we may list this set of “greatest” batsmen:  
1\. V Sehwag (INDIA); 2. IVA Richards (WI); 3. BC Lara (WI); 4. ML
Hayden (AUS); 5. GC Smith (SA); 6. RT Ponting (AUS); 7. DG Bradman
(AUS); 8. MJ Clarke (AUS); 9. SPD Smith (AUS); 10. AB de Villiers (SA);
11. KC Sangakkara (SL); 12. SR Tendulkar (INDIA); 13. Inzamam-ul-Haq
(PAK); 14. GS Sobers (WI); 15. Younis Khan (PAK); 16. GS Chappell (AUS);
17. DPMD Jayawardene (SL); 18. HM Amla (SA); 19. VVS Laxman (INDIA); 20.
GA Gooch (ENG); 21. SR Waugh (AUS); 22. AN Cook (ENG); 23. Javed Miandad
(PAK); 24. JH Kallis (SA); 25. SM Gavaskar (INDIA); 26. S Chanderpaul
(WI); 27. R Dravid (INDIA); 28. KF Barrington (ENG); 29. MA Taylor
(AUS); 30. AR Border (AUS); 31. WR Hammond (ENG); 32. L Hutton (ENG)

![Figure7\_bestbmen\_stats](https://manasataramgini.files.wordpress.com/2018/12/Figure7_bestbmen_stats.png?w=640)Figure
7

For this group of test batsmen we can visualize the distribution of
their average and strike rate (panel 1 and 2 of Figure 7). We observed
that both show a reasonable fit for a normal distribution: Average:
Shapiro-Wilk
![p=0.5866](https://s0.wp.com/latex.php?latex=p%3D0.5866&bg=ffffff&fg=333333&s=0
"p=0.5866"); strike rate: Shapiro-Wilk
![p=0.1437](https://s0.wp.com/latex.php?latex=p%3D0.1437&bg=ffffff&fg=333333&s=0
"p=0.1437"). Thus, assuming a normal distribution of averages among top
batsmen we can calculate the probability of a batsmen having an average
like Bradman by chance alone to be a vanishingly small ![p=1.99 \\times
10^{-11}](https://s0.wp.com/latex.php?latex=p%3D1.99+%5Ctimes+10%5E%7B-11%7D&bg=ffffff&fg=333333&s=0
"p=1.99 \\times 10^{-11}"). One may say that Bradman lived in a very
different era when Australia’s main opponent was England and the other
teams like India were not particularly strong. Yet, his record is
unusually deviant and points to some special biological ability in him
which might be likened to that possessed by a Ramanujan in mathematics.
As evidence one might point to facts such as his surviving serious
illness, his long lucid life and success in investing. Thus, he can be
seen as the father of Australia itself.

Using the same distributions we can infer that the probability of a
batsmen with Sehwag’s career strike-rate emerging by chance alone in
this set of top batsmen is
![p=0.00015](https://s0.wp.com/latex.php?latex=p%3D0.00015&bg=ffffff&fg=333333&s=0
"p=0.00015"). When we combine it with his average we can infer that the
chance of a Sehwag emerging by chance alone among these top players is a
minuscule ![p=2.3 \\times
10^{-5}](https://s0.wp.com/latex.php?latex=p%3D2.3+%5Ctimes+10%5E%7B-5%7D&bg=ffffff&fg=333333&s=0
"p=2.3 \\times 10^{-5}").

From this set of 301 batsmen we can get a smaller set of 73 top batsmen
based on the fact that they convert 50s to 100s at a rate of
![40\\%](https://s0.wp.com/latex.php?latex=40%5C%25&bg=ffffff&fg=333333&s=0
"40\\%") or higher. For this set we find that there is a strong linear
correlation between the 100s they score and the number of innings they
have played (
![r^2=0.84](https://s0.wp.com/latex.php?latex=r%5E2%3D0.84&bg=ffffff&fg=333333&s=0
"r^2=0.84"); Figure 7, panel 3). As ever, Bradman stands apart from the
rest. From this we can calculated that this creamy layer of batsmen
score a test century once every 7.8 innings (median value;
![\\mu=8.27](https://s0.wp.com/latex.php?latex=%5Cmu%3D8.27&bg=ffffff&fg=333333&s=0
"\\mu=8.27")) or approximately once in every four matches (Figure 7,
panel 4).

[![Figure8\_Batsmen\_great](https://manasataramgini.files.wordpress.com/2018/12/Figure8_Batsmen_great.png?w=595&h=655)](https://manasataramgini.files.wordpress.com/2018/12/Figure8_Batsmen_great.png)

Figure 8

Finally, for this set of 73 batsmen we can look the distributions of the
fraction of the innings in which they have remained not out and their
highest test scores (Figure 8). These two metrics bring out two of the
greatest men in my cricket-watching days: 1) Kallis, perhaps the second
greatest all-rounder to date (the first being Sobers whom we have never
watched). He has remained unbeaten unusually high number of times. 2)
Lara, the only man who score a 400 in test cricket. He was the last of
the great black emperors of the Caribbean: what more needs to be said of
him?

**Some notable Indian test batsmen**  
We next took a closer look at some of the notable Indian batsmen whose
innings we have watched in our career as a spectator of the game: 1)
Sehwag, 2) Tendulkar, 3) Dravid, 4) Laxman, 5) Kohli, 6) Ganguly.

[![Figure9\_score\_density](https://manasataramgini.files.wordpress.com/2018/12/Figure9_score_density.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure9_score_density.png)Figure
9

Figure 6 shows the probability density distribution of the scores of
these 6 batsmen along with their career average. Kohli is still playing
so his result will change in the future. The propensity for low scores
is higher in Laxman and Ganguly, whose effect is seen in the form of
their lower averages. The most notable features are: 1) Sehwag’s far-out
right tail with secondary elevations in that region: he was clearly that
man who could reach the big scores which balanced out his low scores.
![7.7\\%](https://s0.wp.com/latex.php?latex=7.7%5C%25&bg=ffffff&fg=333333&s=0
"7.7\\%") of his innings are adorned by scores of 150 or more. In
contrast, the right tails of Tendulkar, Kohli, and Ganguly terminate
more quickly, and Laxman and Dravid are in between. 2) However, both
Tendulkar and Kohli have fat right tails keeping with their tendency to
score numerous hundreds. Kohli in particular, displays a secondary peak
around 100 which is consistent with the fact that he has 10 scores
between 100 and 130. 3) Laxman’s peculiarity is a shoulder between 45
and 75. This comes from the fact in 49 of his 225 innings ( ![\\approx
22\\%](https://s0.wp.com/latex.php?latex=%5Capprox+22%5C%25&bg=ffffff&fg=333333&s=0
"\\approx 22\\%")) he has scored runs in this range.

[![Figure10\_strikerate6](https://manasataramgini.files.wordpress.com/2018/12/Figure10_strikerate6.png?w=640)](https://manasataramgini.files.wordpress.com/2018/12/Figure10_strikerate6.png)Figure
10

We next look at the strike rates of these same 6 players for all innings
where they have not scored a 0. As noted above, the ferocity of Sehwag’s
batting stands out in this metric with a mean of 84.5 (Figure 7). On the
other end, Dravid’s role as the slow-moving defensive formation in the
battle array is displayed by his mean of 40.1, which is way below the
average for tests (Figure 1). Most of these players have an
approximately normally distributed strike rate. However, Kohli’s profile
hints a bimodality which suggests that he has played some defensive
innings like Dravid and also more attacking ones. But his central peak
indicates that he has one characteristic strike rate (Figure 7).

![Figure11\_batsmen\_strikerate\_angle](https://manasataramgini.files.wordpress.com/2018/12/Figure11_batsmen_strikerate_angle.png?w=640)Figure
11

We devised another way of visualizing the same: a scatter plot of runs
scored in an innings versus balls faced. On this scatter plot, using all
innings where the player faced 50 or more balls, we plot the minimal and
maximal angles corresponding the least and highest strike rate for the
innings meeting this criterion. The difference between these two is the
characteristic strike rate angle (SRA) of the batsman. We also plot the
angle corresponding to the median strike rate for innings meeting the
above criterion of balls faced. Sehwag stands out right away: He has the
maximum median angle and the narrowest SRA (Figure 8). This means that
he was consistently the fastest of these great Indian batsmen in tests.
In contrast, Dravid has the lowest median angle and the widest SRA. The
former value indicates that he was the slowest of these great batsmen
but the wide angle indicates that he was capable of fast innings on
occasion. Kohli and Tendulkar have similar median angles that are larger
than the remaining batsmen other than Sehwag. However, Kohli has a much
narrower SRA closer to Sehwag. This suggests that, while Tendulkar and
Kohli score(d) at the same overall rate Kohli is more consistent in
scoring at that rate. Tendulkar, however, tended to score at very
different rates in different innings. On the whole these features affirm
Sehwag’s uniqueness in the constellation of great batsmen.

The laws of distributions hold their strong sway but once in a way a man
of superhuman capacity might emerge. However, they used to say: “Cricket
is a funny game.” It indeed is. Some might have the potential for
greatness but, like the Khans passing away into the grasses of the
steppe without history recording ever recording their name, they might
stumble as an IR Bell or a DI Gower on the brink of greatness. On the
other hand, others like a Gooch or SR Waugh, while lacking genius, might
still make it to the club of greatness by their bulldog-like stickiness.
