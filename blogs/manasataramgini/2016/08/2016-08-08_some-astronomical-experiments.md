+++
title = "Some astronomical experiments"

+++
Our interest in stellar evolution began sometime in the 8th year of our
life after reading an old but very readable account by the famed Russian
scientist George Gamow. It captivated us beyond words but we had to wait
until the 12th year of our life when our mathematics came up to speed
for a major astronomical renaissance. We spent every clear night
observing stars in particular certain variables and recorded their
magnitudes hoping to re-live the excitement of the astronomers of the
past. The excitement hit a peak as we caught a fading R Coronae Borealis
and the out-bursts of SS Cygni when it reached the range of our homemade
telescope. Those were the heady days when the Hipparcos-Tycho project
was in preparation and it was to be a great bonanza of astronomical data
once complete. We read of the launch of the satellite and hoped that
some day we could directly play with the Hipparcos data doing some
trivial things for our own edification. Now years down the line the
successor of Hipparcos, Gaia is in the sky and has already completed the
second year of observations with the data release scheduled for next
month. Gaia is of a much vaster scale than Hipparcos. It is set to
survey a billion stars and that number is still just one hundredth of
the number of stars in Milky Way. So at least before that happens we
decided to put out the little examination of some trivial things in the
Hipparcos data. When the Hipparcos data first came out the computers we
possessed or had easy access in Bhārata were not powerful enough to
handle the data of about 118322 stars. Today with the R language on our
laptops we can quite easily deal with that. That said, we must reiterate
that we are just presenting here some trivial stuff, which people have
done over and over again, but we are doing it for ourselves just because
there is no substitute to pratyakṣa when it comes to science.

One of the main objective of the Hipparcos project was the measurement
of parallax of stars. The concept of parallax (Sanskrit: lambana) was
first discovered by early ārya (among whom it was believe that it was
taught by Sūrya himself to the demon Maya) and yavana astronomers like
Hipparkhos. This trigonometric principle allows you to compute the
distance of an astronomical object by measuring its angular shift from
two positions separated by known distance against an even more distant
background. It was first used to find the distance of a star (61 Cygni)
other than the sun by the astronomer and mathematician Friedrich Bessel,
one of the greatest intellectuals of all times.

So having downloaded the 118322 stars of the Hipparcos project we
cleaned up the data to remove those stars with 0 or negative parallax.
We also removed those stars that lacked the visual magnitude or
B-magnitude, i.e. magnitude measured using a blue filter (with
wavelength midpoint of filter being 445 nm). Thus we ended up with a
total of 112823 stars to work with. Of course this still includes some
stars with bad parallax measurement which result in unusual results but
we are not bothered too much by that for we are mainly looking only at
the bulk data and we have a great deal of reasonable measurement
therein.

All parallax in the Hipparcos dataset is measured as milliarc seconds.
Hence, we first we calculate distance of the stars in parsecs using
formula:

![d=\\dfrac{1000}{p}](https://s0.wp.com/latex.php?latex=d%3D%5Cdfrac%7B1000%7D%7Bp%7D&bg=ffffff&fg=333333&s=0
"d=\\dfrac{1000}{p}");1 parsec=3.26156 light years.

![All\_stars\_distance](https://manasataramgini.files.wordpress.com/2016/08/all_stars_distance.png?w=640)

If we plot a histogram of the distance of the stars in the Hipparcos
data we get a strongly right-skewed distribution with a distinct peak.
The median distance is 208.7 parsecs with the peak of the distance
distribution being 100-150 parsecs. The median value is \~.007 times the
diameter of the Milky Way showing that large as the number of stars are
Hipparcos has merely explored a very local neighborhood of the Milky
Way. But the arms of our barred spiral galaxy being quite similar in
general terms, and we being located midway from the center to the outer
arms, we can consider our sample fairly representative for the arms. Of
course some of extreme values of distance in the data are likely the
result of defective parallax determination; hence we truncate the curve
at a 1000 parsecs.

Once we have computed the distance of the star, given that the project
has measured the visual magnitude (m) of the star in addition, we can
next calculate its absolute magnitude (M). The absolute magnitude of a
star is the magnitude with which it would shine if it were placed at 10
parsecs (\~32.6 light years away).

![M=m-5(log\_{10}(d)-1)](https://s0.wp.com/latex.php?latex=M%3Dm-5%28log_%7B10%7D%28d%29-1%29&bg=ffffff&fg=333333&s=0
"M=m-5(log_{10}(d)-1)"); where d is parsecs

![All\_stars\_absolute\_magnitude](https://manasataramgini.files.wordpress.com/2016/08/all_stars_absolute_magnitude.png?w=640)

While the Sun blazes away in our sky its absolute magnitude is a dim
4.83, which would require us to retire to dark skies in order to see it
if it were 10 parsecs away. In contrast Deneb
(![\\alpha](https://s0.wp.com/latex.php?latex=%5Calpha&bg=ffffff&fg=333333&s=0
"\\alpha") Cygni) would blaze away at the magnitude of about -8.4 from
the same distance and would be seen in broad daylight. The plot of M is
revealing in more than one way. The Sun lies at the beginning of the dim
tail of the distribution considerably dimmer than the median M of 1.54 –
that would be about as bright as
![\\epsilon](https://s0.wp.com/latex.php?latex=%5Cepsilon&bg=ffffff&fg=333333&s=0
"\\epsilon") Canis Major appears in our sky and just a bit dimmer than
the absolute magnitude of Sirius A. The distribution has a clear peak
around 1 and a bit of a shoulder around 3. The bottom line is we are on
dim side, in the 4th quartile of the distribution, keeping with the the
yellow dwarf standing of our star.

The absolute magnitude is a measure of the luminosity\*(L) of the star.
Hence we can represent the same data directly as luminosity in terms of
Sun units i.e. L(Sun)=1 using the formula:  
![L=\\left(10\\right)^{\\frac{4.83-M}{\\sqrt\[5\]{100}}}](https://s0.wp.com/latex.php?latex=L%3D%5Cleft%2810%5Cright%29%5E%7B%5Cfrac%7B4.83-M%7D%7B%5Csqrt%5B5%5D%7B100%7D%7D%7D&bg=ffffff&fg=333333&s=4
"L=\\left(10\\right)^{\\frac{4.83-M}{\\sqrt[5]{100}}}")

![All\_stars\_luminosity](https://manasataramgini.files.wordpress.com/2016/08/all_stars_luminosity.png?w=640&h=373)

This is obviously a similar distribution with a median luminosity around
11 Suns and peak distribution of stars with the luminosity of 13-15
Suns. The shoulder occurs at the luminosity of around 5 Suns. A big
caveat for the absolute magnitude and luminosity data from Hipparcos is
that it mostly measured only bright stars. Thus, the very numerous dim
red dwarfs and even dimmer smoldering brown dwarfs are vastly
under-represented in this data, thereby artificially moving the peak to
the bright side. Just to give a feel for this the nearest star to the
Sun is Proxima Centauri, which shines at a dim 11.05 magnitude while
being a mere 4.25 light years away. Thus, it is unsurprising that
Hipparcos does not have many of them.

The Hipparcos project also obtained the B magnitudes for the stars thus
we have the B-V values which is the difference in magnitude with a blue
filter and the visual magnitude. The stars with negative B-V are the
blue stars and those with high B-V values are the red stars. The Sun,
which is an archetypal yellow star, has a B-V value of 0.656.

![All\_stars\_BV](https://manasataramgini.files.wordpress.com/2016/08/all_stars_bv.png?w=640)

This distribution is interesting in showing two prominent well-separated
peaks in the middle flanked by shoulders. The higher peak is at B-V=.5,
which contains the stars with a whitish yellow color, but to our eyes
simply appear white. The lower peak is at B-V=1 which contains the
orange stars. Between them is the valley at around B-V=.8. Thus the deep
yellow stars are generally under-represented. The prominent first
shoulder (almost a mini-peak) is at B-V=0 and contains the white stars.
The second shoulder is at B-V=1.5-1.6 and represents the red stars. The
dominance of the shoulder at B-V=0 and peak at B-V=.5 is why most stars
in the sky look white to us. Here again the paucity of red dwarfs in the
data has shifted the color plot in the direction of whiteness.

We can then calculate the approximate surface temperature of a star from
its B-V value. While there are multiple formulae to do this we shall use
the Ballesteros formula. While hardly perfect, it gives a better
approximation among the simple formulae that just use B-V:  
![T=4600\*\\left(\\dfrac{1}{.92\\left(B-V\\right)+1.7}+\\dfrac{1}{.92\\left(B-V\\right)+.62}\\right)](https://s0.wp.com/latex.php?latex=T%3D4600%2A%5Cleft%28%5Cdfrac%7B1%7D%7B.92%5Cleft%28B-V%5Cright%29%2B1.7%7D%2B%5Cdfrac%7B1%7D%7B.92%5Cleft%28B-V%5Cright%29%2B.62%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"T=4600*\\left(\\dfrac{1}{.92\\left(B-V\\right)+1.7}+\\dfrac{1}{.92\\left(B-V\\right)+.62}\\right)")

![all\_stars\_Temperature](https://manasataramgini.files.wordpress.com/2016/08/all_stars_temperature.png?w=640)

The distribution of temperatures shows 3 distinct peaks. The first and
the lowest is around 3600-3700K, the second and the highest around 4600K
and the 3rd is around 6400K. The Sun by this method gets T=5766K which
is quite a good approximation of the typically cited T=5777K. The
distribution is strongly right-skewed with a fat tail of hot stars. We
can check a few other stars to see how this formula performs using the
Hipparcos data with respect to commonly reported temperatures:

|            |           |            |
| ---------- | --------- | ---------- |
| Star       | T/Formula | T/Reported |
| Betelgeuse | 3793K     | 3650K      |
| Aldebaran  | 3737K     | 3910K      |
| Sun        | 5766K     | 5777K      |
| Sirius     | 10014K    | 9940K      |
| Rigel      | 10515K    | 12100K     |
| Bellatrix  | 14192K    | 22000K     |

The inaccuracy seems to rise with increasingly lower B-V values. Thus,
the actual distribution onf the right tail is likely to be more
stretched out rightwards.

Once we have the temperature and luminosity of a star we can next
calculate its radius in Sun radius units using the formula:  
![R=\\sqrt{\\dfrac{L}{(T/5766)^2}}](https://s0.wp.com/latex.php?latex=R%3D%5Csqrt%7B%5Cdfrac%7BL%7D%7B%28T%2F5766%29%5E2%7D%7D&bg=ffffff&fg=333333&s=0
"R=\\sqrt{\\dfrac{L}{(T/5766)^2}}")

![All\_stars\_radius](https://manasataramgini.files.wordpress.com/2016/08/all_stars_radius.png?w=640&h=373)

The radius mostly corrects itself despite the issues with temperature we
encounter with the above formula. The distribution is bimodal with
median radius of \~3 Sun radii, again illustrating the bias towards
larger stars as opposed to the tiny dwarfs in the Hipparcos survey. The
first and higher peak is close to 2 Sun radii and second and lower peak
is around 10 Sun radii thus separating the dwarfs from the giants.

With temperature and luminosity at hand we can also generate different
Hertzsprung-Russell diagrams for the Hipparcos data. The first of these
uses absolute magnitude and scales the points as a positively correlated
function of the diameter. Second of these uses luminosity and does not
scale the stars so as to give an an unobstructed view of the basic H-R
diagram.

![All\_stars\_HR\_M\_Dscaled](https://manasataramgini.files.wordpress.com/2016/08/all_stars_hr_m_dscaled.png?w=640&h=520)![All\_stars\_HR\_luminosity\_T](https://manasataramgini.files.wordpress.com/2016/08/all_stars_hr_luminosity_t.png?w=640)

In both of these the main sequence, where majority of stars lie, comes
out very clearly. The other prominent feature that comes out is a branch
that emerges from the main sequence and climbs upwards between 6-5000K.
This the orange-red giant branch with a prominent “red clump” which
comprises of stars close to 5000K and absolute magnitude \~0-.5 which
are fusing helium in their cores. This red clump population seems to be
clearly common in our general galactic vicinity. The diameter-scaled
plot gives allows to visualize the several groups of relatively rare
giants and supergiants that lie above the main sequence and the few
white dwarfs below it. Overall the H-R diagrams we have plotted here are
similar to those with much larger number of stars which have just come
in from Gaia. This suggests that for the Milky Way this can be
considered a fairly representative H-R (barring the dim, small stars).
One of the densest areas of this H-R diagram is the general area around
which the Sun lies in it. Newer data from Kepler and Gaia are beginning
to tell us the distribution of planets around such stars but I do not
fully understand it. However, it does seem like there should be a great
abundance of stars with earth-like planets and I am of the opinion
contrary to some others that life should be rather common on those.

The Hipparcos data also has a large number of variable stars identified.
Hence we shall next extract the variable stars from the data and plot at
H-R diagram from just the variables. On extraction we get a dataset of
10312 variable stars. The H-R diagram for this dataset with stars scaled
as a positively correlated function of diameter is shown below.

![variables\_HR\_M](https://manasataramgini.files.wordpress.com/2016/08/variables_hr_m.png?w=640&h=580)

One thing that becomes rather apparent from this plot is the
proclivity for giants as opposed to lower main-sequence stars to be
variable. In particular, the red giants and supergiants are particularly
enriched in intrinsic variables, as is well-known to anyone with an
elementary knowledge of astronomy. Among the red giants/supergiants we
have several different types of variables: 1) Mira-type long period
variables, which are the so-called asymptotic branch giants, the stars
that have left the main sequence and bloated up to become red giants in
the later period of their lives; 2) the semi-regular variables like
Betelgeuse with low amplitude pulsations; 3) irregular variables like
Aldebaran.

On the upper side of the yellow-orange main-sequence we have the T Tauri
variables, which are young stars often showing protoplanetary disks.
Among the white and light yellow supergiants we have the famed Cepheid
or
![\\delta](https://s0.wp.com/latex.php?latex=%5Cdelta&bg=ffffff&fg=333333&s=0
"\\delta") Cephei variables. Below them all the way from the white to
lighter yellow just above the main-sequence to giants we have several
similarly pulsating stars like the RR Lyrae, W Virginis and
![\\delta](https://s0.wp.com/latex.php?latex=%5Cdelta&bg=ffffff&fg=333333&s=0
"\\delta") Scuti variables. Further upwards on the plot among the yellow
supergiants we have the RV Tauri variables. These “Cepheid-like”
variables have various positively-correlated relationships between their
periods and luminosity, which allow them to be used to measure
distances. Interestingly, while classic Cepheids tend to occur only
along the equatorial plane of the galaxy the RR Lyrae variables are
common at all latitudes and in globular clusters. On the blue end near
the main-sequence and giants we have the
![\\beta](https://s0.wp.com/latex.php?latex=%5Cbeta&bg=ffffff&fg=333333&s=0
"\\beta") Cephei and slowly pulsating blue variables.

Now we shall use the data to do a simplistic exercise of trying to get
the data on Hyades and Pleiades clusters to compare them on the H-R
diagram. For isolating the Hyades approximately we choose the star HIP
20484 from the cluster and take all stars in a circular 3 degree field
around it from the Hipparcos data. Then we clean up the data compute all
the above described values. We then plot our stars as rough star map to
check if we have got it right. As one can see below the Hyades comes out
suggesting that we have got the approximate field right.

![Hyades\_map](https://manasataramgini.files.wordpress.com/2016/08/hyades_map.png?w=640)

Next we plot the distances of the stars in our field and notice a peak
around 40-52 parsecs which is where the actual Hyades members are
located.

![hyades\_distance](https://manasataramgini.files.wordpress.com/2016/08/hyades_distance.png?w=640)

We can see that Aldebaran lies much closer to us and is not physically
part of the Hyades cluster. Once we have the distance of the actual
Hyades stars we can isolate them as a separate data set.

Now for the Pleiades we take our central star as Alcyone
(![\\eta](https://s0.wp.com/latex.php?latex=%5Ceta&bg=ffffff&fg=333333&s=0
"\\eta") Tauri) and do the same procedure as above. Upon plotting the
rough star map we get the below picture showing that we are generally on
the right track.

![Pleiades\_map](https://manasataramgini.files.wordpress.com/2016/08/pleiades_map.png?w=640)

Then we make a similar distance plot to note that according to the
Hipparcos data the Pleiades \~115-120 parsecs.

![Pleiades\_distance](https://manasataramgini.files.wordpress.com/2016/08/pleiades_distance.png?w=640)

This distance resulted in one of most famous controversies in modern
astronomy. It was much lower than what was thought to be the real
distance of the Pleiades. After much discussion the astronomers do think
that the distance of 136.2 parsecs is likely the correct distance,
embarrassingly pointing to some systematic error in Hipparcos data.
Hopefully, the final verdict will be given by Gaia in the coming year or
two. However, for our experiment let us continue with the Hipparcos data
keeping in mind that it would imply a dimmer Pleiades cluster. Using the
above inferred distance we extract the Pleiades members as we did for
the Hyades.

With all this in place we can now can now make a combined H-R diagram of
the Hyades and Pleiades which we have extracted from the Hipparcos data.
The stars of the Hyades are shown in empty circles and those of the
Pleiades are shown in filled circles. The circles are scaled according
to the diameter of the stars.

![Pleiades\_Hyades\_HR2](https://manasataramgini.files.wordpress.com/2016/08/pleiades_hyades_hr2.png?w=640&h=373)

We can see right away that together they generally recapitulate the
overall H-R diagram with most stars lying on the main sequence and a few
moving into the red giant branch with 4 prominent red clump stars from
the Hyades. As is visually apparently the Pleiades are in general bluer
and hotter than the Hyades (this would be even more accentuated if the
Hipparcos distance is an underestimate) with its prominent stars
occupying the blue giant end of the main sequence. Of course with the
Hipparcos data we do not have the dim red stars of the Pleiades. Notably
the Hyades have more stars in the Sun-like region of the H-R diagram
including some quite Sun-like stars. Thus, in a very general sense in
the long-past days the sun could have been part of a Hyades-like cluster
when it was about \~13% its current age. Of course with a more
comprehensive collection of members of these cluster we could get a more
complete picture.
