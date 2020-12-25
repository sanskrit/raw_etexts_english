+++
title = "Make your own sky map"

+++
We live in the age of photo-realism, be it for maps of the world or of
the sky – it is a realism that not long ago was beyond the reach of even
our vision. That is why even though we have such a photo-realistic sky
map just a click away we still have a deep nostalgia for the days before
it. This is part of the reason we finally bit the bullet and wrote our
own latest iteration of a good quality sky map. There is another reason
which we shall come to later but for now we shall wander as part of
recording our own memoirs into its biographical precedence. In our early
childhood we were introduced to astronomy by our father from book which
impressed upon us the great size of the sun relative to earth or even
Jupiter and also introduced us to some constellations wherein shone
stars that made the sun look small. To our luck the northern horizon was
almost completely cleared by the demolition of a building leaving a
space that was not built up for ten years due to the typical ways of the
municipality in those days. Even before we had the book, we could see
Ursa Major from our balcony and we had also internalized the
unmistakable Pleiades and Orion. The said book had few more famous
constellations like Leo which we learnt thereafter. Those days of
halcyon youth were marked by relatively dark skies in our city with the
occasional boon of complete power-cuts which brought the even greater
darkness that we desired. It was then that it became apparent that a
vast starry realm lay above above with more stars than our book ever
showed. Beholding that, the idea took root in us to draw our own sky map
marking all the stars based purely on visual observation. This endeavor
went or for about an year or so after which for reasons unclear to us
our interest in astronomy faded and the said book vanished.

But then as we have alluded to before, almost 4 years later our
astronomical interests resurfaced with a vengeance and this was in the
year before the apparition of the Halley’s comet. Then we obtained
another book with slightly better maps and also embarked on making our
own telescopes. This showed us that the maps in the book were woefully
inadequate and the quest for new ones began. It was then that we found a
kindred spirit a schoolmate from the 3rd varṇa from the Lāṭa-Ānarta
country who was possessed with all the correct lakṣaṇa-s of his varṇa.
He, with his mahādhana, procured a set of deep sky maps of Japanese
provenance. To our eyes these charts had a great beauty in addition to
their accuracy. Their symbols made a deep impression on our young minds
distinguishing variable stars, planetary nebulae, globular clusters,
open clusters, galaxies and other nebulosities with their own symbols.
Armed with these we were among the first lay people in our city who
caught sight of the Halley’s comet when it came out from behind the Sun.
We wrote about this to our local news paper and our names and photos
appeared in it. But the summer of the apparition of the comet had much
more in store for us. Those maps led us to many observations of deep sky
objects and variable stars as also in the subsequent year the great
supernova of the Tarantula nebula. We caught sight of that on a single
day close to the southern horizon when the weather cooperated. It was in
this phase that the urge to sky maps surfaced again for our precious
photocopies of the Japanese maps did not cover the whole sky. Our
parents took us to an astronomer in a nearby city and we showed him our
maps of drawn for the observations of the great supernova. He kindly
commended the accuracy of our maps and showed those from a well-known
American collection of maps for comparison. He wondered how we
determined the relative positions of stars and we remarked that we had a
fairly good memory of the sky and also used the time-honored instrument
the yaṣṭi-yantra for getting various relative positions.

However, that American collection was way too expensive for us to afford
and the Japanese copies were wearing away from use and recopying made
them only fainter. Simultaneously, the skies were deteriorating in our
city and new constructions were coming up in front of our house
completely blocking our view. But the Tarantula nebula supernova and our
improving mathematics initiated us into a new line of study – one of a
more theoretical type. It amazed us that a blue supergiant had gone
supernova – this was unlike what the stellar evolution theories of the
date had postulated. Hence, we compensated for the loss of the skies
with more theoretical pursuits. Yet, as we occasionally taught astronomy
to a few people the urge of making star charts remained alive
recaptitulating the by now dead Japanese maps. We got poorer substitutes
from a planetarium in our birth city but they were still only that. We
had also made a planisphere. We then ran into an elderly brāhmaṇa man
from the small-town Karṇāṭa country who was an autodidactic astronomer.
He was a poor man who tried to make some money by selling planispheres,
tops and some other objects he made by himself but hardly anyone bought
them. He also remarked that there was hardly any one who was interested
in studying astronomy in his midst though he tried hard to popularize
it. He had a deep astronomical knowledge, had observed the sky for long,
and made his planispheres with some ingenuity but his fate had some
emotional impact on us. We saw a grim image of him gazing heavenwards
from a dark spot with silhouette of a once glorious but now abandoned
Hoysala shrine behind him. He shared with us a drive for astronomical
study but it was enormously difficult for him to get new information
which he desired too. We had read that the Hipparcos project had been
completed and told him about it. Against this backdrop it hit us that
there was no use sharing a fate like his, something that easily could
have been ours too. We were essentially not of any consequence, even as
amateur astronomers, simply outpaced by the instrumentation possessed by
the amateurs in richer parts of the world. We had other passions too;
hence, we turned towards them away from astronomy, and the urge for
making star charts vanished. When our astronomy rose back yet again like
the god Vaiśvānara who lay smoldering it was already a thing of the past
as we were born again in the era of electronic sky maps.

But a parallel thread ran in our lives. As we were studying the śruti,
it was becoming increasingly clear that, much to our Yajurveda teacher’s
chagrin, we lacked the conviction in the central pillar of mīmāṃsā – the
doctrine of apauruṣeyatva. Instead we became very much intrigued by the
question of the age of śruti or the various layers therein. There were
numerous obvious astronomical references that were catching our ears,
leave alone the less-obvious ones. It was then that we studied the great
leader of the Hindus Lokamanya Tilak, the poorly known Kameshvara Ayyar
and Shankar Dixit all of whom had used similar techniques to arrive a
plausible date for the composition of various vaidika texts. This idea
fascinated us and colluded with our star-chart making urge. One of the
things that was sorely lacking was a nakṣatra-based map which divided
the ecliptic into the nakṣatra-s and showed the sky using a
nakṣatra-based ecliptic grid. For this purpose we wrote a primitive
program which interfaced either with our paper star charts or in the
last 21 years with an existing program to visualize the sky as usual.

Recently, an interlocutor on the internet expressed the wish of
incorporating a nakṣatra grid in the open-source program sky map
software Stellarium (something we have been using for several years for
our regular observing needs) and asked some questions in that regard. It
was in this context that our desire to make our own sky map resurfaced
and we finally implemented something which recaptitulates the aesthetic
of those old Japanese maps. Of course today we have loads of raw
material available a click away so the task was nowhere as complex as it
might have been before. We outline that below so that anyone with some
computer skills can make their own in a straight-forward way:

1\) We conceived our map as fitting in a 33×24 sq.inch (83.82 x 60.96
sq.cm) rectangle and covering the whole sky. The idea was to produce it
in png, pdf and svg format for use on the web or for printing in large
format.

2\) We implemented it in the R because it was one of the easiest to use,
open-source languages supporting vector operations. It is good for
generating graphical outputs such as this and has a preexisting library
for computing projections (see below). The code for plotting was written
in base R and special fonts were imported and embedded using the R
extrafont library. The conversion of coordinates from ecliptic to
equatorial were done using a converter function that we wrote based on
code written by Arnab Chakraborty in the AstrolibR package.

3\) After some experimentation we chose the Eisenlohr projection for our
map. This rather remarkable projection was introduced by German
mathematician and physicist Friedrich Eisenlohr in 1870 (Incidentally
his brother was the chemist and Egyptologist who studied the famous
Rhind Papyrus). It has advantages over all the rest but was not used
commonly perhaps because its formula was intensive on calculations in
the pre-computer era.

Let ![\\lambda \\in
\[-\\pi,\\pi\]](https://s0.wp.com/latex.php?latex=%5Clambda+%5Cin+%5B-%5Cpi%2C%5Cpi%5D&bg=ffffff&fg=333333&s=0
"\\lambda \\in [-\\pi,\\pi]") be the longitude; ![\\phi \\in
\[-\\tfrac{\\pi}{2},\\tfrac{\\pi}{2}\]](https://s0.wp.com/latex.php?latex=%5Cphi+%5Cin+%5B-%5Ctfrac%7B%5Cpi%7D%7B2%7D%2C%5Ctfrac%7B%5Cpi%7D%7B2%7D%5D&bg=ffffff&fg=333333&s=0
"\\phi \\in [-\\tfrac{\\pi}{2},\\tfrac{\\pi}{2}]") be the latitude and
![R](https://s0.wp.com/latex.php?latex=R&bg=ffffff&fg=333333&s=0 "R")
the radius of the globe which we wish to project. Then the Eisenlohr
projection in terms of the x and y coordinates on the x-y plane is given
by:  
![S\_1=\\sin\\left(\\dfrac{\\lambda}{2}\\right)](https://s0.wp.com/latex.php?latex=S_1%3D%5Csin%5Cleft%28%5Cdfrac%7B%5Clambda%7D%7B2%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"S_1=\\sin\\left(\\dfrac{\\lambda}{2}\\right)")

![C\_1=\\cos\\left(\\dfrac{\\lambda}{2}\\right)](https://s0.wp.com/latex.php?latex=C_1%3D%5Ccos%5Cleft%28%5Cdfrac%7B%5Clambda%7D%7B2%7D%5Cright%29&bg=ffffff&fg=333333&s=0
"C_1=\\cos\\left(\\dfrac{\\lambda}{2}\\right)")

![T=\\dfrac{\\sin\\left(\\dfrac{\\phi}{2}\\right)}{\\cos\\left(\\dfrac{\\phi}{2}\\right)+C\_1
\\sqrt{2
\\cos(\\phi)}}](https://s0.wp.com/latex.php?latex=T%3D%5Cdfrac%7B%5Csin%5Cleft%28%5Cdfrac%7B%5Cphi%7D%7B2%7D%5Cright%29%7D%7B%5Ccos%5Cleft%28%5Cdfrac%7B%5Cphi%7D%7B2%7D%5Cright%29%2BC_1+%5Csqrt%7B2+%5Ccos%28%5Cphi%29%7D%7D&bg=ffffff&fg=333333&s=0
"T=\\dfrac{\\sin\\left(\\dfrac{\\phi}{2}\\right)}{\\cos\\left(\\dfrac{\\phi}{2}\\right)+C_1 \\sqrt{2 \\cos(\\phi)}}")

![V=\\sqrt{\\dfrac{cos\\left(\\dfrac{\\phi}{2}\\right)+(C\_1+S\_1)\\sqrt{\\dfrac{\\cos(\\phi)}{2}}}{\\cos\\left(\\dfrac{\\phi}{2}\\right)+(C\_1-S\_1)\\sqrt{\\dfrac{\\cos(\\phi)}{2}}}}](https://s0.wp.com/latex.php?latex=V%3D%5Csqrt%7B%5Cdfrac%7Bcos%5Cleft%28%5Cdfrac%7B%5Cphi%7D%7B2%7D%5Cright%29%2B%28C_1%2BS_1%29%5Csqrt%7B%5Cdfrac%7B%5Ccos%28%5Cphi%29%7D%7B2%7D%7D%7D%7B%5Ccos%5Cleft%28%5Cdfrac%7B%5Cphi%7D%7B2%7D%5Cright%29%2B%28C_1-S_1%29%5Csqrt%7B%5Cdfrac%7B%5Ccos%28%5Cphi%29%7D%7B2%7D%7D%7D%7D&bg=ffffff&fg=333333&s=0
"V=\\sqrt{\\dfrac{cos\\left(\\dfrac{\\phi}{2}\\right)+(C_1+S_1)\\sqrt{\\dfrac{\\cos(\\phi)}{2}}}{\\cos\\left(\\dfrac{\\phi}{2}\\right)+(C_1-S_1)\\sqrt{\\dfrac{\\cos(\\phi)}{2}}}}")

![C=\\sqrt{\\dfrac{2}{1+T^2}}](https://s0.wp.com/latex.php?latex=C%3D%5Csqrt%7B%5Cdfrac%7B2%7D%7B1%2BT%5E2%7D%7D&bg=ffffff&fg=333333&s=0
"C=\\sqrt{\\dfrac{2}{1+T^2}}")

![x=(3+\\sqrt{8})\\cdot R \\cdot
\\left(-2\\log(V)+C\\left(V-\\dfrac{1}{V}\\right)\\right)](https://s0.wp.com/latex.php?latex=x%3D%283%2B%5Csqrt%7B8%7D%29%5Ccdot+R+%5Ccdot+%5Cleft%28-2%5Clog%28V%29%2BC%5Cleft%28V-%5Cdfrac%7B1%7D%7BV%7D%5Cright%29%5Cright%29&bg=ffffff&fg=333333&s=0
"x=(3+\\sqrt{8})\\cdot R \\cdot \\left(-2\\log(V)+C\\left(V-\\dfrac{1}{V}\\right)\\right)")

![y=(3+\\sqrt{8})\\cdot R \\cdot\\left(-2 \\arctan(T)+C T
\\left(V+\\dfrac{1}{V}
\\right)\\right)](https://s0.wp.com/latex.php?latex=y%3D%283%2B%5Csqrt%7B8%7D%29%5Ccdot+R+%5Ccdot%5Cleft%28-2+%5Carctan%28T%29%2BC+T+%5Cleft%28V%2B%5Cdfrac%7B1%7D%7BV%7D+%5Cright%29%5Cright%29&bg=ffffff&fg=333333&s=0
"y=(3+\\sqrt{8})\\cdot R \\cdot\\left(-2 \\arctan(T)+C T \\left(V+\\dfrac{1}{V} \\right)\\right)")

It has the following notable features: i) it has no singularities so
every point on the globe can be simultaneously represented; ii) it is
completely conformal, i.e., it preserves angles across the globe
completely; iii) it has the narrowest scale range for a conformal
projection of ![1 : 3+2\\sqrt{2}=1 :
5.83](https://s0.wp.com/latex.php?latex=1+%3A+3%2B2%5Csqrt%7B2%7D%3D1+%3A+5.83&bg=ffffff&fg=333333&s=0
"1 : 3+2\\sqrt{2}=1 : 5.83"); iv) it has a constant scale along the
boundary colures. Thus, even though we get some size distortion near the
boundaries its preservation of conformality is a useful feature for
astronomical depiction especially when we want to highlight the ecliptic
which lies close to the equatorial aspect. Given the above formula
provided by the US Geographical Survey, we wrote our own function for
the Eisenlohr projection but we also implemented projection using the
projection function from the R Mapproj library (which has several
different projections) in the event we wished to try out alternative
projections in the future.

4\) For the plotted data we chose the following (the source is: Vizier
unless specified otherwise): (i) The venerable Yale Bright Star Catalog
with 9096 stars which is for practical purposes complete in its coverage
till visual magnitude
![m\_V=7](https://s0.wp.com/latex.php?latex=m_V%3D7&bg=ffffff&fg=333333&s=0
"m_V=7"). It also provides variability and double star data; (ii) For
the background shading of the Milky Way we chose a catalog of 18693 of
the brightest stars from the Milky Way; (iii) For the Milky Way and
Magellanic cloud boundaries a set of 1073 positions giving the
boundaries and constellation lines, i.e. stars to be connected, made
available in electronic format by professor Dan Burton based on his
article, which I think appeared in Sky & Telescope; (iv) Boundaries for
all 88 constellations defined by the International Astronomical Union;
(v) shading in and around the Magellanic clouds obtained from 526 bright
electromagnetic sources in those regions; (vi) we extracted 196 deep sky
objects from the NGC. It covers all genuine Messier objects and other
brighter objects that are accessible to telescopes in the 6-10 inch
range (e.g. the Centaurus A galaxy).

5\) The sky map distinguishes variable and doubles stars recorded in the
YBSC using a bull’s eye symbol and a dash passing through the star
respectively, which we inherited from our old Japanese maps. The deep
sky objects are shown thus: galaxies are marked with an ellipse;
planetary nebulae with a fish eye symbol; globular clusters with a many
pronged burst; open clusters with a circle and cross; other nebulosities
with a dotted circle; miscellaneous objects with an empty circle. All
these symbols are obtained using the unicode Symbola font made freely
available by George Douros. Unfortunately, none of the Devanagari fonts
render correctly for conjunct akṣara-s other than in the png format. The
star-color was computed using the [difference of the B and V band
magnitudes](https://manasataramgini.wordpress.com/2016/08/08/some-astronomical-experiments/)
wherever available.

6\) Finally, one of the key motivations for making this map was to have
the nakṣatra division on the ecliptic. But how does one get the nakṣatra
divisions? While it is clear from the Vedāṅga Jyotiṣa that the early
Hindus did conceive the ecliptic as having fixed nakṣatra divisions,
these have not come down to us. Over the ages starting from the Vedic
period the nakṣatra divisions were named [according to
yogatārā-s.](https://manasataramgini.wordpress.com/2017/07/01/a-note-on-the-asterisms-forming-the-nak%e1%b9%a3atra-s/)
The root yuj in this term might be taken to mean junction stars i.e.,
stars marking the divisions of the nakṣatra-s or it might be taken to
mean stars united with a given nakṣatra division. Making note of the
asterisms defined by the yogatārā-s over the ages, we feel that the
latter definition is more likely and sensible. It seems that the
yogatārā-s are a remnant of an early observational phase in Hindu
astronomy where they were a rough guide to locate the moon within a
nakṣatra division. This observation was likely carried out using a rod
(yaṣṭi-yantra) which was projected against the cusps of the Moon to see
which yogatārā they were aligned with. Based on that the Moon’s nakṣatra
division was then assigned. However, as predictive algorithms improved
starting [with the
VJ](https://manasataramgini.wordpress.com/2006/12/02/vedanga-jyotisha-and-other-ramblings-on-early-hindu-calenders/)
gradually the lay Hindu practitioner lost touch with the nakṣatra-s as
actually asterisms, i.e. the yogatārā-s. The situation was so bad among
the astrologers that in when in the 1800s the great historian of Hindu
astronomy, Shankar Dixit, asked several astrologers if they could
identify the nakShatra-s, not one of them could correctly point even a
few out in the sky. This knowledge, however, survived among the rare
śrauta ritualists. Dixit encountered one from near Kolaba who was able
to correctly point out all of them in the sky. He further cited an
incantation from tradition that went as below:

khau kha jā trī gu cu gai co cho bhū yuk  
cha hi trī ku cū che ko dvi yuk  
ṅau kha chā ṅī ku ghu tri yuk  
kha jā ku cū ghe gho

`  102 112 128 140 153 156 183 196 197 217 232 240 252 266 277 291 305 312 327 345 351 354 12  28  51
 66  74  94 `  
This contains the above code in the kaṭapayādi system with the vowels
(a, ā, i, ī, u, ū, e, ai, o, au) being 1:9 and 0. To determine the
rising point of the ecliptic from the nakṣatra asterism at the meridian
at midnight one does the following: the first is Aśvayuji. If it is at
meridian then the rising point of ecliptic is 102 degrees on the
ecliptic. Thus, the separation of the rising point is given for each
nakṣatra (note they are taking Betelguese to be Ārdra and it comes
really close to Mṛgaśīrṣa. This illustrates that the Hindus were clearly
aware of the positions of the yogatārā-s in ecliptic coordinates and
that they were unevenly positioned. However, the nakṣatra divisions
themselves are a regular ![13
\\tfrac{1}{3}^o](https://s0.wp.com/latex.php?latex=13+%5Ctfrac%7B1%7D%7B3%7D%5Eo&bg=ffffff&fg=333333&s=0
"13 \\tfrac{1}{3}^o") (800 minutes of an arc) since the removal of
abhijit; so the question remains where to start them. One could use the
above incantation to calculate one such starting point. That was for the
1800s. Somewhat later, following up on the monumental work of Shankar
Dixit, his acquaintance, the great patriot, BG Tilak, proposed that
there should be a pan-Indian astro-calendrical reform the use of modern
astronomical calculations to determine the pañcāṅga and fixing of
nakṣatra divisions in a standard way across Hindudom. This project was
taken up after the English tyrants left by the calender committee
constituted under the great physicist Meghnad Saha and the jyautiṣa
Lahiri. They produced a nakṣatra division recommendation, which while
not exactly equivalent to the ancient division, is an entirely usable as
a modern substitute. They began with with the premise of having the star
Spica (Citra; ![\\alpha \\;
Virginis](https://s0.wp.com/latex.php?latex=%5Calpha+%5C%3B+Virginis&bg=ffffff&fg=333333&s=0
"\\alpha \\; Virginis")) in middle of the citra division of the nakṣtra
in ecliptic coordinates for 1956 CE. This resulted in the equinoctial
colure passing through uttara-proShTapada. Examining this proposal we
find that it has issues with respect to the yogatārā-s at Ārdra, which
we have argued was originally Sirius, Uttarāṣāḍa, and Śroṇa but it is
clear that some such issues will be there irrespective of the juggling
of boundaries one might do. Hence, we took these divisions and converted
them to the J2000 coordinates currently used in astronomy. This gives us
the start of the Revati division at ![9.112253
^o](https://s0.wp.com/latex.php?latex=9.112253+%5Eo&bg=ffffff&fg=333333&s=0
"9.112253 ^o") in decimal ecliptic coordinates. Starting from there we
took 27 divisions of 800 minutes of an arc each.

With the nakṣatra divisions in place we created 2 types of maps – one
with the nakṣatra points as defining ecliptic longitudes and another
with the same defining equatorial longitudes. Finally, one could also
use the AstrolibR or any equivalent in your favorite system to get the
positions of the Moon and plot it on the map as a visual pañcāṇga if you
like.

Finally one may ask why write so much and make such ado about just
plotting a bunch of points from coordinate files. Yes, that is all there
is to this exercise but do it yourself and if you are a mere mortal like
us you might find the process interesting.

The maps in PDF format(view with high magnification 150% or more):  
1\) [Ecliptic
longitudes](https://app.box.com/s/b75vo9jduf2b9jb4l013z48ov7dsfcxc)  
2\) [Equatorial
longitudes](https://app.box.com/s/r27myqikr3639g2eahk7xwkvx9gr6lsh)  
3\) [With Full moon(filled) of Sep 6 2017 and New Moon (empty) of
Sept 21 2017 plotted on the
map](https://app.box.com/s/0qpv8fzctkul7vu3grwtm7mzsng158ji).
