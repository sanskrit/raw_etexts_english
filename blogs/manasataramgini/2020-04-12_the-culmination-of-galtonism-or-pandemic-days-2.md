+++
title = "The culmination of Galtonism or pandemic days-2"

+++
Ensconced in the apparent safety of the 4 walls the mind looks out into
the completely silent streets with hardly a soul or even a passing ratha
— a mere 120 days have made the world look and sound different. With
that realization, we place here the 3rd in this series of notes
recording these times. This note will cover some very basic stuff on
visualizing disease progression in a population which we used to explain
things to laypeople (bālabodhana).

We hear laypeople express surprise over things like: (1) “Just a few
weeks ago there were just 10s of cases of the Wuhan disease now it has
just exploded.” (2) “What is the point in staying at home? How can it
reduce the disease?” (3) “There are all these predictions of millions of
people dying and now it has come down to tens of thousand. There must be
some over-reaction due to X or Y.” As long as the person is willing to
have a patient discussion we found that we could explain the basics
relating to these using some illustrations which don’t use any
sophisticated mathematics and just a simple program which we wrote for
the purpose. One can easily reproduce similar illustrations with ones
own assumptions in whichever is the language of ones choice. When we try
to clarify point (3) we tell people that what we are showing them is not
like any of the complex models that they hear of in the news. We explain
to them, extrapolating from our simple program, that the forecasting
models have many, many ways in which they can be parameterized. We do
not know the correct values of several of these parameters and as result
of that there can be tremendous diversity of outcomes due to the
combinatorial interaction of the alternative values of parameters.
Hence, we simply cannot be certain which forecast of the model is going
to actually play out. However, the simple program does explain some of
the essential outcomes that a layperson needs to understand.

Our model for how disease can progress in a population is a very simple
one: (1) It assumes a population starting a certain fixed size
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n"),
which undergoes decrement from deaths due to infection but beyond that
there are no other factors changing its size. This simple assumption is
good enough for a fast-moving epidemic like the one we are saddled with.
In what we illustrate below
![n=40000](https://s0.wp.com/latex.php?latex=n%3D40000&bg=ffffff&fg=333333&s=0
"n=40000"). (2) We initiate the disease with a single infected
individual introduced into the population and let the disease run for a
certain maximum number of time units. One can take them to be days if
one wants; ![m =
25](https://s0.wp.com/latex.php?latex=m+%3D+25&bg=ffffff&fg=333333&s=0
"m = 25") in our example. (3) If a person in the population catches the
disease he remains infectious for 7 days, i.e., can transmit it to
someone who is in the vicinity. Within that period the infected
individuals can die with a certain probability;
![d=.02](https://s0.wp.com/latex.php?latex=d%3D.02&bg=ffffff&fg=333333&s=0
"d=.02") in our below illustration. (4) After that period if the person
has not died he is considered as recovered and is immune to reinfection.
This again is a reasonable assumption for a fast-moving disease. Thus,
our process features 4 states for individuals in the population:
Uninfected; Infected; Recovered; Dead. These are respectively shown in
different colors: white; brown; green; black. (5) Not every person who
has gotten the infection spreads it uniformly to others in the vicinity.
Here, we assume a power-law distribution of the capacity of an infected
individual to infect others in the vicinity in an encounter. One example
goes thus; an infected person in an encounter infects:  
0 persons 0.747475 of the times  
1 persons 0.204900 of the times  
2 persons 0.025200 of the times  
3 persons 0.008725 of the times  
4 persons 0.004550 of the times and so on till,  
124 persons 0.000025 of the times. They all add up to 1.  
This assumption captures the fact that most encounters do not actually
result in an infection but some rare people are “super-spreaders” so
they infect a large number of people in an encounter.

In its default state, people in our population randomly move at each
time unit with little restriction on movement. Infection is transmitted
with the power-law-defined frequency to
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
neighbors when they encounter an infected individual. This goes on till
the set maximum of time units
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m") is
attained. But we can set a restriction parameter, which decides how
freely the people in the population can randomly move to encounter
others. The greater this restriction parameter the less they can move
about to bump into others.

For each run, the upper panel shows the actual numbers of the 4 states
in the population at each time unit of the simulation. The lower panels
illustrates the state of the population at each of the 25 time units as
1 dot per person, colored based on the individual’s state.

[![disease\_prog1](https://manasataramgini.files.wordpress.com/2020/04/disease_prog1.png?w=630&h=1008)](https://manasataramgini.files.wordpress.com/2020/04/disease_prog1.png)

Figure 1 shows a run where there is essentially no restriction on
movement. It begins innocuously with most of the population in the
uninfected state and within 25 time units the entire population goes
through infection and ends up as recovered or dead. This helps bring
home to a layperson how the disease progresses: the initial stages
always look innocuous and how an explosion happens by exponentiation and
can overwhelm any treatment system. An analogy can also be made to a
fire: as long as there is fuel it continues to burn but as the fuel
decreases there is a down turn in the burn rate and finally the fire
ends.

[![disease\_prog2](https://manasataramgini.files.wordpress.com/2020/04/disease_prog2.png?w=592&h=947)](https://manasataramgini.files.wordpress.com/2020/04/disease_prog2.png)

Figure 2 shows a run where right from early on free-movement of the
population is somewhat restricted. Here, we see some mitigation of the
deaths and infections. Still majority of the population gets infected.

[![disease\_prog3](https://manasataramgini.files.wordpress.com/2020/04/disease_prog3.png?w=629&h=1006)](https://manasataramgini.files.wordpress.com/2020/04/disease_prog3.png)

Figure 3 shows a situation where much stronger restriction is imposed on
the free movement of people. Here, a considerable fraction of the
population is uninfected, deaths are considerably reduced and the
infection can be brought to zero in the end.

The latter two scenarios illustrate to the layperson the value of early
mitigation measures in the form of restriction of social interactions or
free movement in controlling such epidemics. Of course, this is a very
simple illustration and in no way should be taken as a forecasting
model. However, as noted above forecasting models suffer from great
parametric uncertainty and a combinatorial increase in search space when
the multiplicity of alternatives are taken into account. Thus, a simple
model like this, which provides some basic qualitative understanding of
what seems puzzling to laypeople is good enough for them to get some
intuitive feel for the situation.
