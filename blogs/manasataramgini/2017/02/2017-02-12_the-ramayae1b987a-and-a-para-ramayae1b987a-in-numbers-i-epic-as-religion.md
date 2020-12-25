+++
title = "The Rāmāyaṇa and a para-rāmāyaṇa in numbers-I: epic as religion"

+++
This note may be read as part of our studies on the Rāmāyaṇa and
para-Rāmāyaṇa-s of which [an earlier part is presented
here](https://manasataramgini.wordpress.com/2016/08/12/some-words-on-para-ramaya%e1%b9%87a-s-i/).

A study of the epic in Indo-European tradition suggests that there were
two registers of the old Indo-European religion. While today both of
them survive together with any vigor only among the Hindus, until not
too long ago these registers showed some survival even among their
Iranian cousins. From these it is apparent the first register is the
“high religion” which manifests as śrauta and smārta performance.
Among the ārya-s this further evolved into other manifestations as seen
in the tantra-s of the sectarian traditions. Nevertheless, the Vedic
base remained the model for most of these later developments. On the
other hand the lay manifestation of religion was by the medium of the
epic or itihāsa-s in India. Their religious value elsewhere in the
Indo-European world was apparent in Greece. Indeed, in the classical
Greco-Roman confluence the last attempt of reviving the religion by
emperor Julian, which was being swept away by the “Typhonic” evil of the
preta-moha, involved a focus on the religious facet of the Homeric
epics.

In both India and Greece there are two epics, which have numerous
parallels in their motifs, and resonate even in their overall themes.
However, in India each has a distinct character. The Rāmāyaṇa is what
might be termed “the universal epic of ideals.” The Mahābhārata is on
the other hand our national epic, the epic of the first ārya nation in
India, the foundation on which the modern Hindu nation rests. The
Iranians have a comparable national epic in the form of the
Kśathāya-nāmag and its precursors but apparently lack the universal
epic. Among the Greeks to an extent the Iliad probably played a national
role but tended towards the universal in the later phase. It was the
universal epic, the Rāmāyaṇa, which was the vehicle of the ārya-dharma
beyond boundaries of Jambudvīpa. In its role as the foundation of the
“lay religion” it was remarkably tenacious and withstood the assault
of the other Abrahamistic evil in the form the marūnmāda in Indonesia.
It also served as a means of preserving the ārya-dharma in both India
and in the east against the assault of the Aryan counter-religions
promulgated by the naked-one and the ground-toucher. Indeed, in India
the powerful force of the itihāsa-s was realized by successors of both
these heterodox promulgators, who either attacked the itihāsa-s or tried
to have people not attend their exposition.

The remainder of this note we shall look at the Rāmāyaṇa via numbers,
which was part of my self-discovery of its key religious facet. Most
importantly, it reveals something about the deep layers of the
ārya-dharma and its evolution over time. Before we get started, a few
caveats should be stated upfront: The texts I am using are the so-called
“critical editions” of the Rāmāyaṇa and Mahābhārata for the first
para-Rāmāyaṇa, the Rāmopākhyana of Mārkaṇḍeya. These critical editions
have their faults but are available in electronic form and are thus
amenable to semi-automatic text analysis by regular expression searches.
Almost all of these analysis were performed by means of such. The
Heidelberg system has a very sophisticated text-parsing mechanism for
several Sanskrit works but I did not use it except for one word search
(inspired by an [interlocutor](https://shreevatsa.wordpress.com/) on
Twitter), which will be discussed as part of another note, as it was not
quite compatible with my command line pipeline. So my system could have
some deficiencies but manual checking of the results shows that it is
largely correct and the magnitudes should be taken as genuinely
representative. In general for this activity you need to have a good
knowledge of the various names of the gods, characters and weapons used
in the text. Although not a paṇḍita, being a brāhmaṇa, I believe that I
have a level of command of this as a reasonable representative of my
varṇa should, so the results might be taken as generally reliable.
Finally, I am aware that in white indological circles some work in this
direction has been done by the likes of Brockington. However, I did not
consult his papers as I wanted to have my own unbiased experience of the
data and conclusions from it. More generally, wherever there is
tractable data I believe that an educated man should analyze it himself
rather than wholly relying on hearsay of others.

First we shall look at the gross features of the Rāmāyaṇa (Figure 1):

![ramayana\_stats](https://manasataramgini.files.wordpress.com/2017/02/ramayana_stats.png?w=640)Figure
1

\-The text has seven kāṇḍa-s, which are composed of multiple sarga-s,
which in turn are composed of śloka-s. The Ayodhyā, Yuddha and Uttara
have much more than median number of sarga-s and śloka-s.  
\-However, it is notable that except for Yuddha the other kāṇḍa-s have a
nearly constant median śloka count per sarga (\~24-27). This was the
likely count maintained by Pracetas and his son Vālmīki the original
composers of the Rāmāyaṇa for a typical kāṇḍa, probably aiming to be
around 25 śloka-s. The Yuddha in contrast is longer both in terms of
number of sarga-s and also the number of śloka-s per sarga. Clearly,
this is a distinct composition suggesting that a different style was
adopted on purpose for the military narratives typical of Indo-European
epics. Unlike the median, the mean śloka count per sarga is higher with
anomalies for both the Yuddha and Sundara. We shall take a closer look
at this in Figure 2

![sarga\_length\_ramayana](https://manasataramgini.files.wordpress.com/2017/02/sarga_length_ramayana.png?w=640)

Figure 2.

\-Here we see the actual frequency distribution of the sarga length
across the Rāmāyaṇa and per kāṇḍa in śloka-s: Here the differences are
more apparent.  
\-The first three kāṇḍa-s are “tighter” in distribution with modal sarga
length close to the median length. The Kiṣkindhā shows some divergence
in the form of a fat tail with several sarga-s in of great length (40-70
śloka-s).  
\-The Sundara is most unusual in having a bimodal distribution with
short sarga-s peaking less than 20 in length and longer ones peaking
around 35. This pattern suggests a deliberate compositional shift
perhaps reflecting the peculiar nature of the Sundara as an avenue for
display of poetic beauty.  
\-The Yuddha is clearly distinct with the general peak and median length
being shifted to being between 30 and 40. There is also a sizable
fraction of very long sarga-s above 40 going all the way to well over
80. This again emphasizes the distinctness of the battle narratives
where the long recitations perhaps appealed to the war-like ancient ārya
audience who might have been in similar battles in their own lives.  
\-Finally, Uttara shows a typical median distribution of sarga length
with a major fraction of sarga-s distributed around this value. However,
it is distinct in showing a bimodality with two peaks one with length
between 10-20 śloka-s and another with length between 40-45 śloka-s.
This suggests a certain composite character with the shorter sarga-s
probably representing the several short narratives included in it and
the long ones relating to battle-sequences comparable to the Yuddha.

Now coming to the core issue of religion we shall look at the frequency
of occurrence of the gods in the Rāmāyaṇa (Figure 3)

![deva\_ramayana](https://manasataramgini.files.wordpress.com/2017/02/deva_ramayana.png?w=640)Figure
3

\-It is apparent that Indra is literally the leader of the gods. He
occurs nearly twice as frequently as the next contender Prajāpati or
Brahmā. He is the standard for all comparisons and the hero of the
Rāmāyaṇa is frequently likened to him. Indeed, there is a the tacit
understanding that Indra used his māyā to take the form of a man in
order to slay Rāvaṇa. This is suggested by Mandodarī’s lament upon her
husband’s death:

atha vā rāma-rūpeṇa vāsavaḥ svayam āgataḥ |  
māyāṃ tava vināśāya vidhāyāpratitarkitām || R 6.99.10

Or indeed Indra himself appeared in the form of Rāma,  
for ruining and slaying you using impenetrable illusion.

Thus, it is hinted that Indra, who right in the Ṛgveda is famous for his
māyā, uses it to kill the rakṣas.

Now again, though the core kāṇḍa narrative itself mentions Rāma taking
the weapons of Viṣṇu from Agastya, in the preamble it is mentioned that
they were the weapons of Indra himself.

agastyavacanāc caiva jagrāhaindraṃ śarāsanam |  
khaḍgaṃ ca paramaprītas tūṇī cākṣaya-sāyakau || R 1.1.34c

At Agastya’s words Rāma verily took up Indra’s bow,  
sword and the excellent inexhaustible quiver.

Of course the grand finale of the Yuddhakāṇḍa has Rāma ride the chariot
of Indra steered by Mātali himself and using Indra-s weapons:

sahasrākṣeṇa kākutstha ratho ‘yaṃ vijayāya te |  
dattas tava mahāsattva śrīmāñ śatrunibarhaṇaḥ ||

O descendant of Kakutstha, the slayer of foes, one of great strength and
opulence, the thousand-eyed Indra has given for your victory this
chariot.

idam aindraṃ mahaccāpaṃ kavacaṃ cāgni-saṃnibham |  
śarāś cādityasaṃkāśāḥ śaktiś ca vimalā śitāḥ ||R 6.90.9-6.90.10

\[He has also given\] this great bow of Indra and his armor which glow
like fire,  
as also these arrows blazing like the sun and this bright sharp spear.

Finally, to slay Rāvaṇa he is said to use the missile made by Brahmā.
But even here it is a mighty missile made by Brahmā in the manner of
Tvaṣṭṛ in the Veda for Indra to conquer the three worlds:

brahmaṇā nirmitaṃ pūrvam indrārtham amitaujasā |  
dattaṃ surapateḥ pūrvaṃ triloka-jayakāṅkṣiṇaḥ || R 6.97.5c

\[The missile\] was formerly made by the god Brahmā of immeasurable
might for the sake of Indra. It was given to the lord of the gods
\[Indra\] when he formerly sought to conquer the three worlds.

The missile itself has characteristics that are clearly suggestive of
the vajra of Indra:  
“ratha-nāgāśva-vṛndānāṃ bhedanaṃ kṣiprakāriṇam |R 6.97.8c”  
The swift acting \[missile\] was the smasher of \[entire\] troops of
chariots, elephants and horses.  
“dvārāṇāṃ parighāṇāṃ ca girīṇām api bhedanam |R 6.97.9”  
It was capable of smashing its way through through bar-reinforced doors
and also mountains”

Tellingly it is described as “vajrasāram” (imbued with the essence of
the vajra), and “yama-rūpam” (of the form of Yama). The latter epithet
directly recalls the the first person statement of Indra in the 10th
maṇḍala of the Ṛgveda where he says that he wields a missile that is
like Yama himself.

The deployment of this missile by Rāma on Rāvaṇa is again thus described
thus:

sa vajra iva durdharṣo vajrabāhu-visarjitaḥ |  
kṛtānta iva cāvāryo nyapatad rāvaṇorasi ||

The missile, difficult to defend against like the vajra hurled by the
arm of Indra, unstoppable like the causer of death (Yama), hit Rāvaṇa on
his chest.

Thus struck Rāvaṇa fell:

gatāsur bhīmavegas tu nairṛtendro mahādyutiḥ |  
papāta syandanād bhūmau vṛtro vajrahato yathā || R 6.97.021

His life-breath having departed the lord of the nairṛta-s of fierce
speed and great luster fell from his battle-car to the ground like Vṛtra
struck by the vajra.

Thus, to the ancient ārya audience this recitation would have
immediately evoked the imagery of the Ṛgveda, where Indra’s heroic deeds
in battle are praised in the ritual.  
In conclusion, this makes it is clear that the original Rāmāyaṇa was
composed in a setting where the aindra flavor of the ārya-dharma was the
still the main expression of the religion. It is indeed likely that that
it was tacitly implied that Rāma was a manifestation of Indra in human
form to kill Rāvaṇa.

Now what about the rest of the Vaidika pantheon. Was it like the late
Vedic age or the saṃhitā-s themselves?

\-We see considerable prominence for Sūrya, Vāyu, Viṣṇu, Yama, Rudra in
addition the Prajāpati/Brahmmā. However, the Aśvin-s, the Marut-s, the
distinct āditya-s are not prominent. Agni has a moderate presence
although primarily in the sense of poetic similes. This suggests that
period of composition while still marked by Aindra dominance was one
which was probably positionally distinct and temporally much later than
the saṃhitā period. Of the prominent deities the indistinct solar deity
suggests the rise of the [new Indic solar
cult](https://manasataramgini.wordpress.com/2015/08/12/a-note-on-the-pantheon-of-the-indian-saura-tradition/)
with links to the older Āditya system but certainly very distinct in its
manifestation with parallels to those seen in the Iranian world.

–[The prominence of
Vāyu](https://manasataramgini.wordpress.com/2016/12/11/matters-of-religion-discussion-on-vayavya-offerings/)
is related to his association with Indra in battle against the dānava-s,
a feature which was prominent in both the Veda and the para-Vedic
tradition. The latter is partly reflected in the Rāmāyaṇa and also
relates to the importance of his son, Hanumat in the epic. We should
mention here that in counting Vāyu we have almost entirely avoided
including the incidental occurrence of his name as a epithet of Hanumat.
A similar situation accounts in part of the prominence of Viṣṇu;
however, his story has more which will be further discussed below. If
Indra is identified with Rāma, and the role of Vāyu is taken by Hanumat,
then it is rather obvious that the place of Viṣṇu is taken by Lakṣmaṇa.
The Rāmāyaṇa makes this obvious in the statement:

vikramiṣyati rakṣaḥsu bhartā te saha-lakṣmaṇaḥ|  
yathā śatruṣu śatrughno viṣṇunā saha vāsavaḥ || 6.024.029c

Your husband \[Rāma\] with invade the rakṣas with his brother Lakṣmaṇa
even as the foe-killing Indra against his foes along with Viṣṇu.  
or:

sa dadarśa tato rāmaṃ tiṣṭhantam aparājitam |  
lakṣmaṇena saha bhrātrā viṣṇunā vāsavaṃ yathā || R 6.87.9

He then saw the undefeated Rāma standing with his brother Lakṣmaṇa like
Indra with Viṣṇu.

Like in the Veda the most frequently referred act of Viṣṇu are three
world-conquering strides suggesting that this old motif was still of
great importance in the age of the Rāmāyaṇa rather than later elements
like his incarnations or battles with certain demons. His weapon, the
cakra is frequently mentioned, unlike in the Veda, where other gods are
described as wielding it but not Viṣṇu. This suggests that the Rāmāyaṇa
marks a stage after the saṃhitā period where the cakra became
established as the favored weapon of Viṣṇu. However, it does preserve
the memory of Indra’s cakra mentioned in the śruti in R 1.26.5. Notably,
Viṣṇu is mentioned as killing the demon Naraka in a conflict which was
perhaps coupled with Indra’s battle with Śambara:  
śambaro devarājena narako viṣṇunā yathā | R 6.57.7

Thus is appears possible that this exploit of Viṣṇu was transferred to
his avatāra Kṛṣṇa in a later retelling of the legend. Indeed, the whole
Kārṣṇī retelling has Viṣṇu only thinly veiled by the Yadu hero.

\-Of the other gods, Garuḍa and Kubera despite having a presence in the
Veda are not prominent there beyond specific rituals. Nevertheless, even
there, there is an under-current that they had a role of some note in
household rituals. Their importance clearly comes out in the Rāmāyaṇa.
In particular it is clear that the whole epic has a frame that tries to
highlight the might of Rāvaṇa as the expense of Kubera, implying that he
was an important deity of the time. He is named as one of the great
regal gods along with kings Varuṇa and Yama and his greatness is
repeatedly mentioned. This importance of Kubera, as we have seen before
has a strong para-Rāmāyaṇa tradition too as laid out in the
Rāmopākhyāna. Notably, in that relatively short text he is 3rd most
frequently mentioned deity (Figure 4) suggesting that his importance was
visible throughout the whole early phase of the Rāmāyaṇa tradition.

![deva\_ramopakhyana](https://manasataramgini.files.wordpress.com/2017/02/deva_ramopakhyana.png?w=640)Figure
4

His importance is also implied by his airplane the Puṣpaka playing a
notable role in the epic. His son Nalakūbara is also seen as cursing
Rāvaṇa resulting in the protection of Sitā’s chastity upon her
abduction. Kubera is also described as providing a secret missile to
Lakṣmaṇa in his dream that allowed him to counter the Yama weapon of
Meghanāda in their final encounter.

lakṣmaṇo ‘py ādade bāṇam anyaṃ bhīma-parākramaḥ |  
kubereṇa svayaṃ svapne yad dattam amitātmanā ||

Lakṣmaṇa of fierce valor also deployed another missile, which given \[to
him\] by the incomparable Kubera himself in a dream.

When the two missiles collided a great explosion is said to have taken
place with a fire breaking out as they neutralized each other – in a
sense implying that Kubera is no less than the god of death in his
might.

\-Yama in the Ṛgveda is strictly associated with the context of the
funerary and ancestor rituals. However, there is again the under-current
in the other saṃhitā-s that he was an important deity in regular
existence as the god of death. This role of his in the Rāmāyaṇa is
rather prominent and both in terms of numbers and the way he is referred
to as a great king suggests that he was an important god in the
ārya-dharma of the time. The death-dealing rod of Yama and entering his
abode are common similes.

\-Prajāpati: This deity is hardly present in the core clan-specific
works of Ṛgveda – he is mentioned only twice outside of maṇḍala-10. But
in maṇḍala-10 he has already risen to being the supreme deity in certain
sūkta-s. He is conceived as both the overlord deity as well as the
protogonic “golden-egg”. Now this would suggest that he was a
late-emerging deity, probably specifically in the Indic setting after
the ārya-s had left their ancestral steppe regions. However, we do not
think this is the case. Comparisons with protogonic deities in the Greek
realm suggest that such a deity predated the Greco-Aryan split. Rather
we posit that he was not a key protogonic deity of the normative
Indo-European pantheonic system but was the focus of one of several
Indo-European cults outside the standard polytheism. Some deities who
were part of the standard polytheism were also foci of such
extra-normative cults but others like Prajāpati were solely cultic to
start with. In both India and Greece the proponents of such protogonic
deities started acquiring great prestige and religious centrality. In
India this is reflected in the late Ṛgveda of the maṇḍala-10 and the
brāhmaṇa-s where we witness the meteoric rise of Prajāpati. In the
process of his rise he began to eat into the dominance of Indra, the
head deity of the standard IE model.

In the itihāsa-s his ectype Brahman is likewise prominent as the head of
the pantheon, though he is already beginning to face competition from
the radiations from the cultic foci around Skanda, Rudra and Viṣṇu. What
we see in the Rāmāyaṇa is that he is without any close competitor the
second most frequently mentioned deity (Figure 3). His prominence in
this itihāsa seems to be similar to what we see in the brāhmaṇa-s: As a
deity at the head of the pantheon Brahman shares the position with
Indra, but his prominence is clearly eating into that of Indra. This
suggests two possible scenarios: 1) He was already a prominent figure
from the very beginning of the Rāmāyaṇa tradition and his
“power-sharing” with Indra is reflective of the parallel scenario in
the brāhmaṇa-s were he had already risen to the highest rank. Thus this
would imply that both aindra and prājāpatya memes were already active as
the epic was being composed. 2) The Rāmāyaṇa as proposed above was
primarily an aindra epic and Brahman secondarily encroached on Indra’s
share in an independent replay of what happened in the brāhmaṇa-s.

On historical grounds we favor the second scenario. A comparison of the
nāstika productions of the ground-toucher and the naked-one’s cults
clearly indicate that at their time the prājāpatya strand of the
religion was primarily among brāhmaṇa “intellectuals”. This intellectual
link continued to later times when we see mathematical and scientific
authors like Āryabhaṭa and Brahmagupta invoke Brahman as their deity
(contrast with older scientific tradition in the Caraka-saṃhitā where
Indra is dominant). The rest of the people in large part seem to have
still followed the aindra religion until pretty late in Indian history
with some competition from the other cultic foci mentioned above. This
is indicated by the fact that the two nāstika teachers accepted this
aindra mainstream as their background and mention the prājāpatya
tradition primarily in the context of their brāhmaṇa rivals. Notably, in
the first of the many Rāmāyaṇa of the jaina-s, the Paumacariyaṃ,
Vimalasūri explicit calls out the stupidity of the āstika versions on
grounds of their denigration of the great god Indra. This historical
background would imply that the prājāpatya-s first rose as a dominant
force inside the Vedic intellectual circles. The mark of this rise was
first seen in the brāhmaṇa texts. Then as the prājāpatya-s “conquered”
the intellectual landscape they extended their influence to more
“secular” intellectual activities such as the itihāsa-s and
mathematics/science. This was when Brahman came to prominence in the
Rāmāyaṇa tradition. However, by the time the purāṇa-s started taking
shape in their extant form, the other cultic sectarian foci had radiated
enough to catch up and supersede Brahman. Of the old cultic foci, Skanda
after an initial rise faded away. In contrast, Viṣṇu and Rudra came up
to Brahman and soon overtook him to the point that despite the three of
them being acknowledge as a trinity Brahman sunk to the “junior”
position of the trinity. In part the tale of him having no temples might
reflect the inability of the intellectual-centered Prājāpatya system to
capitalize on the rising āgama-dharma, despite an early attempt hinted
by the Atharvaveda pariśiṣṭa-s.

So what do the numbers from the text tell us? First looking at the
Rāmopākhyāna we find that Brahman/Prajāpati has gone ahead of Indra
(Figure 4). It was created by an author(s) who were clearly Prājāpatya
and did not see any need to emphasize or maintain the position of Indra
beyond what was absolutely unavoidable. What this tells us is that the
Rāmāyaṇa tradition passed through a distinct phase after its original
composition where Prajāpati had become important in it and it was in
this phase that the fork leading to the Rāmopākhyāna was created. More
tellingly, this proposal is supported when we look at the by kāṇḍa
counts of key deities (Figure 5: shown as percentage of verses featuring
particular deva). Here we see that Brahman has a peculiar distribution
that is distinct from that of Indra and Vāyu. While the latter two show
clear kāṇḍa-specific differences, they are more uniformly distributed
across the kāṇḍa-s. In contrast the occurrences of Brahman show a
significantly higher occurrence in the Bāla and Uttara kāṇḍa-s while
being greatly under-represented in the rest. We know that both these
kāṇḍa-s were clearly subject to reshaping after the core epic was
composed because they try to explain things which were not clear
elsewhere in the epic (e.g. the origin of the heroes and villains of the
text). This together with the above observation clinches the case for
the second of the above proposals: after the original epic in an aindra
form was composed the Prājāpatya-s refashioned it by primarily redacting
the first and last kāṇḍa-s.

![deva\_kanda](https://manasataramgini.files.wordpress.com/2017/02/deva_kanda.png?w=640)Figure
5

\-Viṣṇu again: Two other major deities show a similar of kāṇḍa-wise
pattern of distribution as Brahman: Viṣṇu and Rudra. Importantly, they
are minor in their presence in the Rāmopākhyana (Figure 4). This
suggests that the vaiṣṇava and śaiva redaction occurred later than the
forking of the Rāmopākhyāna and acted in manner very similar to the
prājāpatya action before them. That they were also directly in
conflict with each other is suggested by the fight between Rudra and
Viṣṇu which is inserted into the bāla-kāṇḍa. Another key point is
that the vaiṣṇava material show no strong hints of the avatāra doctrine
nor the early pāṅcarātrika tradition which is strong in the Mahābhārata.
This suggests that the vaiṣṇava redaction comes from an early stream of
the sect that underwent further evolution by time of the redaction of
the Bhārata.

\-Rudra: In the Rāmāyaṇa has his characteristic features of being
dark-throated, three-eyed, with braided locks (Kapardin), having a bull
as his banner/vehicle, holding a great bow, having Umā for this wife and
displaying great ferocity. His destruction of the Tripura-s is
frequently mentioned. Additionally, his slaying of Andhaka gets multiple
references. These references frequently come in kāṇḍa-s 2-6 suggesting
that they are indeed the ancient similes involving the deeds of Rudra.
E.g.

sa papāta kharo bhūmau dahyamānaḥ śarāgninā |  
rudreṇaiva vinirdagdhaḥ śvetāraṇye yathāndhakaḥ || R 3.29.27

He, Khara, fell to the ground being burnt by the fire of the missile
even as Andhaka \[fell\] burnt down by Rudra in the White Forest.

Most of these features have direct or indirect reference in the Veda,
often going back to the oldest layers. However, we do not hear of his
exploits made prominent in the purāṇa-s like the killing of Jalandhara
or Śaṅkhacūda. Thus Rudra in the Rāmāyaṇa has not changed in any notable
way from his Vedic form.

\-Finally one may note that in this Kāṇḍa-wise distribution Kubera is
mostly uniform across kāṇḍa except for the uttara – paralleling Vāyu to
an extent. This we believe suggests his ancient and intrinsic importance
to the text with the Uttara merely serving as a receptacle for lore
relating to him and Vāyu.

In conclusion, we can say with some confidence that the great Rāmāyaṇa
of sage Vālmīki was originally an epic encapsulating the popular
register of the Indo-European religion as manifest among the Indians –
the ārya-dharma. Its heroes were set in the mold of the great deities
Indra (Rāma and Vālin), Vāyu (Hanumat), Viṣṇu (Lakṣmaṇa), Kubera
(perhaps some of the Kuberian element transferred to Vibhīṣaṇa), the
opaque popular Āditya (Sugrīva), with simile-linkages to Rudra and the
Maruts (encompassed in Hanumat). Despite the later sectarian redactions
starting from the prājāpatya-s casting it in different light, it
retained this ancient religious spirit of the ārya-dharma. It was this
that erupted forth like the great ape Hanumat to animate the Hindus in
their life and death struggle against the unadulterated evil of
Mohammedanism when they seemed all but lost. That is why a memorial to
the epic should be built at Ayodhyā after destruction of all marūnmatta
elements in the holy city.
