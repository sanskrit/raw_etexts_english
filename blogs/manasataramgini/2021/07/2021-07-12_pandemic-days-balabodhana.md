+++
title = "Pandemic days: bālabodhana"
date = "2021-07-12"

+++
As the pandemic grinds to a close or at least to a pause in some parts
of the world, there is a certain fear from new mutants threaten that
threaten break current the status quo. The strain that arose in the deś
is a case in point. This short note is some bālabodhana on how
understand some of the basics of the mutational process.

At the most fundamental level, biology is written in a 4 letter alphabet
— the four nucleotides (A, G, C, T/U). A RNA virus, like SARS-CoV-2, has
U, whereas cellular DNA genomes have T instead. Any biological word,
i.e. string of nucleotides, occupies a node in a graph (network). This
graph might be seen as multi-layered where in each layer
![l_i](https://s0.wp.com/latex.php?latex=l_i&bg=ffffff&fg=333333&s=0&c=20201002)
contains all words of length
![L](https://s0.wp.com/latex.php?latex=L&bg=ffffff&fg=333333&s=0&c=20201002).
In the subgraph corresponding to any given layer 2 nodes are connected
by an edge if they differ by a single letter, i.e. a single substitution
can change the word corresponding to a node to that corresponding to the
node to which it is connected by an edge. Thus, there are 4 words of a
single nucleotide
![(l_1)](https://s0.wp.com/latex.php?latex=%28l_1%29&bg=ffffff&fg=333333&s=0&c=20201002)
which are all connected to each other, i.e. a tetrahedral graph.

[![Mutation_network](https://manasataramgini.files.wordpress.com/2021/07/mutation_network.png?w=406&h=361)](https://manasataramgini.files.wordpress.com/2021/07/mutation_network.png)

With 2 letters (dinucleotides)
![l_2](https://s0.wp.com/latex.php?latex=l_2&bg=ffffff&fg=333333&s=0&c=20201002)
we have ![4 \\times 4 =
16](https://s0.wp.com/latex.php?latex=4+%5Ctimes+4+%3D+16&bg=ffffff&fg=333333&s=0&c=20201002)
possible words and the graph is way more complicated as each node can be
connected to 6 other nodes.

[![Mutation_network2](https://manasataramgini.files.wordpress.com/2021/07/mutation_network2.png?w=539&h=425)](https://manasataramgini.files.wordpress.com/2021/07/mutation_network2.png)

One can easily see that
![l_1](https://s0.wp.com/latex.php?latex=l_1&bg=ffffff&fg=333333&s=0&c=20201002)
will define a tetrahedron in 3D Euclidean space. However, any biological
word of ![L \\ge
2](https://s0.wp.com/latex.php?latex=L+%5Cge+2&bg=ffffff&fg=333333&s=0&c=20201002)
cannot be faithfully visualized in our everyday 3D space, as it will
require many more dimensions to render it with real edge-lengths. Thus,
as Martin Nowak stated, biological words are rich in dimensions but
short on distance. For simplicity, we draw our graphs in whatever
dimensions are easily grasped by us (i.e. 2D as above) and simply take
each edge of the graph to be measured as a non-Euclidean length. In
reality, not just the topology of the graph but also the length of the
edges matter. Nucleotides are more likely to mutate to the same type (
pyrimidine (U/T)
![\\leftrightarrow](https://s0.wp.com/latex.php?latex=%5Cleftrightarrow&bg=ffffff&fg=333333&s=0&c=20201002)
pyrimidine (C), purine (A)
![\\leftrightarrow](https://s0.wp.com/latex.php?latex=%5Cleftrightarrow&bg=ffffff&fg=333333&s=0&c=20201002)
purine (G)) rather than a different type (i.e. purine
![\\leftrightarrow](https://s0.wp.com/latex.php?latex=%5Cleftrightarrow&bg=ffffff&fg=333333&s=0&c=20201002)
pyrimidine). Thus, the lengths of edges corresponding to heterotypic
substitutions are longer than those corresponding to homotypic edges.
However, for convenience we shall simplify the situation by taking all
edges to be of length 1. Thus, the distance between two nodes will be
length along the graph: in the dinucleotide example shown above the
distance between AA and AG will be 1, while that between AA and GG will
be 2. Thus, for
![L=2](https://s0.wp.com/latex.php?latex=L%3D2&bg=ffffff&fg=333333&s=0&c=20201002),
while paths of various lengths are possible, from one node you can reach
every other node with path of at most length 2. This shortest distance
along the graph,
![D](https://s0.wp.com/latex.php?latex=D&bg=ffffff&fg=333333&s=0&c=20201002),
between 2 nodes is no different from the so called Manhattan metric or
Hamming distance.

Some of the nodes on a given layer
![l_i](https://s0.wp.com/latex.php?latex=l_i&bg=ffffff&fg=333333&s=0&c=20201002)
are connected nodes on
![l\_{i+1}](https://s0.wp.com/latex.php?latex=l_%7Bi%2B1%7D&bg=ffffff&fg=333333&s=0&c=20201002)
by an edge too because by the addition or subtraction of a nucleotide
you go from a sequence of length
![L](https://s0.wp.com/latex.php?latex=L&bg=ffffff&fg=333333&s=0&c=20201002)
to
![L+1](https://s0.wp.com/latex.php?latex=L%2B1&bg=ffffff&fg=333333&s=0&c=20201002)
and vice versa. However, given that you can have in a single step such
additions and deletions of arbitrary length you can also connect
sequences of various lengths by these length 1 edges coming from the
so-called deletions and insertions. For this simple examination we shall
ignore those types of mutations.

The basic, necessary process of life may be defined as the copying of an
biological word, in its maximal form a genome, by a nucleic acid
polymerase. All polymerases are prone to error when they make new copy
of the genome from the existing template. We may define this error by
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0&c=20201002),
the probability of single nucleotide substitution at a arbitrary
position in the genome. Then
![1-u](https://s0.wp.com/latex.php?latex=1-u&bg=ffffff&fg=333333&s=0&c=20201002)
is the probability of the genome being copied correctly. This leads us
to a key equation that measures mutation in the genome, i.e. probability
![p\_{ij}](https://s0.wp.com/latex.php?latex=p_%7Bij%7D&bg=ffffff&fg=333333&s=0&c=20201002)
that the copying of genome
![i](https://s0.wp.com/latex.php?latex=i&bg=ffffff&fg=333333&s=0&c=20201002)
results in a mutant genome
![j](https://s0.wp.com/latex.php?latex=j&bg=ffffff&fg=333333&s=0&c=20201002):

![p\_{ij}=u^{D\_{ij}}(1-u)^{L-D\_{ij}}](https://s0.wp.com/latex.php?latex=p_%7Bij%7D%3Du%5E%7BD_%7Bij%7D%7D%281-u%29%5E%7BL-D_%7Bij%7D%7D&bg=ffffff&fg=333333&s=0&c=20201002)

Here,
![D\_{ij}](https://s0.wp.com/latex.php?latex=D_%7Bij%7D&bg=ffffff&fg=333333&s=0&c=20201002)
is the shortest distance along the graph between sequences ![i,
j](https://s0.wp.com/latex.php?latex=i%2C+j&bg=ffffff&fg=333333&s=0&c=20201002)
and
![L](https://s0.wp.com/latex.php?latex=L&bg=ffffff&fg=333333&s=0&c=20201002)
is the length of the genome. Wrapped into this are two simplifying
assumptions: 1)
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0&c=20201002)
is constant throughout the genome and 2) it is independent of mutations
at other sites.

I could not find a proper estimate of
![u](https://s0.wp.com/latex.php?latex=u&bg=ffffff&fg=333333&s=0&c=20201002)
for SARS-CoV-2. However, a closely related coronavirus, with a
similar-sized genome, the Mouse Hepatitis Virus RNA-dependent RNA
polymerase has
![u=10^{-6}](https://s0.wp.com/latex.php?latex=u%3D10%5E%7B-6%7D&bg=ffffff&fg=333333&s=0&c=20201002).
The same may be safely used for SARS-CoV-2. Hence, the probability that
the viral polymerase makes a copy with no mutation at all, with ![L
\\approx 3 \\times
10^4](https://s0.wp.com/latex.php?latex=L+%5Capprox+3+%5Ctimes+10%5E4&bg=ffffff&fg=333333&s=0&c=20201002),
is given as:

![(1-u)^L=0.97](https://s0.wp.com/latex.php?latex=%281-u%29%5EL%3D0.97&bg=ffffff&fg=333333&s=0&c=20201002)

For a comparison, the HIV-1 virus reverse transcriptase has
![u=3\\times10^{-5}](https://s0.wp.com/latex.php?latex=u%3D3%5Ctimes10%5E%7B-5%7D&bg=ffffff&fg=333333&s=0&c=20201002)
and
![L=9400](https://s0.wp.com/latex.php?latex=L%3D9400&bg=ffffff&fg=333333&s=0&c=20201002);
thus
![(1-u)^L=0.75](https://s0.wp.com/latex.php?latex=%281-u%29%5EL%3D0.75&bg=ffffff&fg=333333&s=0&c=20201002).
Therefore, HIV-1 is a far more mutation-prone virus, which copies its
genome without a mutation only 3/4th of the times. The higher fidelity
of replication of the coronavirus is a consequence of its distinctive
proofreading 3′-5′ exoribonuclease, which the HIV-1 reverse
transcriptase lacks. This increased fidelity is keeping with its ![3.19
\\times
](https://s0.wp.com/latex.php?latex=3.19+%5Ctimes+&bg=ffffff&fg=333333&s=0&c=20201002)latex
larger genome, coding for several more proteins than HIV-1.

Conversely, consider the probability that a specific point mutant arises
upon replication of the coronavirus genome. For example, the mutation in
the Spike protein E484K can confer resistance to some of the typical
antibodies made against the wild type Wuhan strain. This is a
substitution of K for E which can arise from a single ![A \\to
G](https://s0.wp.com/latex.php?latex=A+%5Cto+G&bg=ffffff&fg=333333&s=0&c=20201002)
point mutation. This probability can be calculated using the above
formula with
![D\_{ij}=1](https://s0.wp.com/latex.php?latex=D_%7Bij%7D%3D1&bg=ffffff&fg=333333&s=0&c=20201002);
hence,

![u(1-u)^{L-1}=9.7\\times
10^{-7}](https://s0.wp.com/latex.php?latex=u%281-u%29%5E%7BL-1%7D%3D9.7%5Ctimes+10%5E%7B-7%7D&bg=ffffff&fg=333333&s=0&c=20201002)

When a virus infects a cell, it makes numerous copies of itself and
these “burst” out eventually resulting in the death of the cell. The
number of such copies that emerge out from the cell on an average is
termed the burst size. To our knowledge, there are no recent studies on
burst size estimates for coronaviruses. However, a study in 1976 by N.
Hirano et al estimated it to be about 600-700 virus particles, again
using the Mouse Hepatitis Virus in a tissue culture system. By taking a
burst size of 650, one would need ![\\approx
1585](https://s0.wp.com/latex.php?latex=%5Capprox+1585&bg=ffffff&fg=333333&s=0&c=20201002)
successfully infected cells producing bursts of this size for a specific
point mutation, like the above mentioned one in the spike protein, to
emerge. During peak SARS-CoV-2 infection, an individual is estimated as
carrying ![\\approx
10^{10}](https://s0.wp.com/latex.php?latex=%5Capprox+10%5E%7B10%7D&bg=ffffff&fg=333333&s=0&c=20201002)
virus particles based on calculations of Sender et al. Hence, a
particular point mutation can emerge in an infected individual
![\\approx
9704](https://s0.wp.com/latex.php?latex=%5Capprox+9704&bg=ffffff&fg=333333&s=0&c=20201002)
times.

If a point mutation confers some selective advantage, like the
above-mentioned immune escape mutation, then even with the low error
replication of coronaviruses relative to HIV-1, they have ample
potential for developing escape mutations. Consistent with this
estimate, we saw the E484K mutation repeatedly emerge in different
lineages that showed antibody escape, such as the B.1.351 variant that
arose in South Africa, the P.1 variant that arose in Brazil and the
within the B.1.1.7 lineage in the UK. Finally, a serial passaging
experiment by Andreano et al of the virus with plasma from a recovered
patient found that for 7 passages the plasma neutralized the virus;
thereafter point mutations emerged that allowed escape and eventually
complete resistance to the plasma. One of these was the E484K. The
evolutionary history of SARS-CoV-2, assuming that it broke out in Wuhan,
China, in November 2019 was one of relative stasis for about an year
followed by emergence of several mutants that allowed immune escape. The
among these were the multiple emergences of E384 point mutations. This
suggests that for the first year the virus was rampaging through a
relatively immunologically naïve population with little advantage for
specific point mutations. However, as pandemic response measures and the
virus load in the population greatly increased, there was an advantage
for specific mutants. The above numbers show that point mutations were
the easiest path to this, as seen with the emergence of variants with
mutations such as D614G, E484K etc.

Yet, we see that the vaccination programs have played a big role in
bringing the pandemic under control in several parts of the world. Why
has it worked, given the above? For this let us take a closer look at
the antibody response to SARS-CoV-2.

[![CoronaSpike](https://manasataramgini.files.wordpress.com/2021/07/coronaspike.png?w=448&h=504)](https://manasataramgini.files.wordpress.com/2021/07/coronaspike.png)

Roughly
![90\\%](https://s0.wp.com/latex.php?latex=90%5C%25&bg=ffffff&fg=333333&s=0&c=20201002)
of the antibodies against this virus are directed at the Spike (S)
protein. The above picture shows the spike with the top part being the
surface which it contacts the ACE2 receptor on the host. Within the
spike protein the residues that are targeted by 5 distinct classes of
antibodies are marked in different colors on a single monomer colored
cyan, while the other two monomers of the trimer are shown in
transparent light yellow. The majority of antibodies target the Receptor
Binding Domain (RBD), while the minority target the N-terminal
galectin-like domain (dark violet). First, since, there are at least 5
distinct classes of antibodies, the escape via a point mutation could be
compensated by the binding of one of the other classes. Second, the
titer of antibodies seems to matter a lot in terms of immunity.
Individuals with high titer seem to be able to overcome much of the
escape by single mutants like E484K. Third, there is the cellular
immunity. Thus, the vaccine are in most part likely generating high
enough titers of antibodies of different classes to make up for escape
by single point mutations and a reasonable cellular immunity.

Now, to escape a whole class of antibodies one might typically need 3 or
more point mutations. We can compute the probability of 3 point
mutations arising from one replication of the virus as
![u^3(1-u)^{L-3}=9.7 \\times
10^{-19}](https://s0.wp.com/latex.php?latex=u%5E3%281-u%29%5E%7BL-3%7D%3D9.7+%5Ctimes+10%5E%7B-19%7D&bg=ffffff&fg=333333&s=0&c=20201002).
This means it is very unlikely to ever arise in a single person in
single replication ![(p \\approx 9.7 \\times
10^{-9})](https://s0.wp.com/latex.php?latex=%28p+%5Capprox+9.7+%5Ctimes+10%5E%7B-9%7D%29&bg=ffffff&fg=333333&s=0&c=20201002).
For a comparison, the probability of a round of replication producing a
triple mutation in HIV-1 is ![2.03 \\times
10^{-14}](https://s0.wp.com/latex.php?latex=2.03+%5Ctimes+10%5E%7B-14%7D&bg=ffffff&fg=333333&s=0&c=20201002).
On a given day, an infected person carries about ![2 \\times
10^{10}](https://s0.wp.com/latex.php?latex=2+%5Ctimes+10%5E%7B10%7D&bg=ffffff&fg=333333&s=0&c=20201002)
HIV-1 particles; hence a person has only a ![4.1\\times
10^{-4}](https://s0.wp.com/latex.php?latex=4.1%5Ctimes+10%5E%7B-4%7D&bg=ffffff&fg=333333&s=0&c=20201002)
of developing a triple mutant in a single replication. However, 1 in
every 2455 persons infected with HIV-1 can develop such a mutant in
single round of replication. Hence, it has not been possible to
vaccinate against it. However, as the serial passage experiment
illustrated, in successive rounds of selection for individual point
mutations one could eventually get to total resistance with SARS-CoV-2.
The B.1.617.2
![(\\delta)](https://s0.wp.com/latex.php?latex=%28%5Cdelta%29&bg=ffffff&fg=333333&s=0&c=20201002)
variant has already shown the capacity to partially break through the
commonly used Pfizer and Astra-Zeneca vaccines in the least. In theory
it is possible that a strain that is entirely resistant to the
antibodies generated by the vaccine could arise in the relatively near
future. Fortunately, antibodies are not the only aspect of immunity as
they can also trigger cellular immunity. Hence, at least for the near
future, with all aspects of immunity put together, the vaccines are
likely to provide some level of protection. However, the strong
selection pressure they are imposing on the S protein could result in
the emergence of more consequential escape mutants. Hence, there is a
lingering danger of the disease persisting in some form.
