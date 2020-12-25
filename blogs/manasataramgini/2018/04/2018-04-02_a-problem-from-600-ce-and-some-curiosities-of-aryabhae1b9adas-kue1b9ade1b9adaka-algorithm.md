+++
title = "A problem from 600 CE and some curiosities of Āryabhaṭa’s kuṭṭaka algorithm"

+++
Around 600 CE in the examinations of one of the Hindu schools of
mathematics and astronomy one might have encountered a problem such as
below (given by Bhāskara-I in his commentary on Āryabhaṭa’s
Āryabhaṭīya):

dvayādyaiḥ ṣaṭ-paryantair ekāgraḥ yo ‘vaśiṣyate rāśiḥ |  
saptabhir eva sa śuddho vada śīghraṃ ko bhaved gaṇaka ||

Quickly say, O mathematician, which number when divided by the numbers
starting with 2 and ending in 6 (i.e 2:6) leaves 1 as the remainder, and
is exactly divisible by 7?

This problem was given to illustrate the use of the kuṭṭaka algorithm
first provided by Āryabhaṭa. Before we actually solve the above problem
we will briefly examine the kuṭṭaka. The kuṭṭaka is a general algorithm
deployed to obtain integer solutions for the indeterminate linear
equations of the form
![ax-by=c](https://s0.wp.com/latex.php?latex=ax-by%3Dc&bg=ffffff&fg=333333&s=0
"ax-by=c"), where ![a, b,
c](https://s0.wp.com/latex.php?latex=a%2C+b%2C+c&bg=ffffff&fg=333333&s=0
"a, b, c") are positive integers. Thus, it is essentially the problem of
finding the coordinates of the the integer lattice point through which
the line
![ax-by=c](https://s0.wp.com/latex.php?latex=ax-by%3Dc&bg=ffffff&fg=333333&s=0
"ax-by=c") passes. Of the three constants in the equation,
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and ![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0
"b") are given;
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c") is
not given but we have to find the smallest
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
for which the equation can be solved in integers. From that we can build
other valid
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
For computational simplicity (with no loss of generality) we take
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") to
be the bigger number and
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b") to
be the smaller number. The below presentation of it follows the matrix
representation of Āryabhaṭa’s operation given by the mathematician
Avinash Sathye:

Let us consider as an example the following equation
![95x-25y=c](https://s0.wp.com/latex.php?latex=95x-25y%3Dc&bg=ffffff&fg=333333&s=0
"95x-25y=c"). From
![a=95](https://s0.wp.com/latex.php?latex=a%3D95&bg=ffffff&fg=333333&s=0
"a=95") and
![b=25](https://s0.wp.com/latex.php?latex=b%3D25&bg=ffffff&fg=333333&s=0
"b=25") we can generate the below matrix which is the result of the
kuṭṭaka procedure. We have written a function ‘kuṭṭaka’ in the R
language that computes this matrix and few other details given
![a,b](https://s0.wp.com/latex.php?latex=a%2Cb&bg=ffffff&fg=333333&s=0
"a,b").

![K=\\begin{bmatrix} 19 & 4 & 95 & NA \\\\ 5 & 1 & 25 & 3 \\\\ 4 & 1 &
20 & 1 \\\\ 1 & 0 & 5 & 4 \\\\ 0 & 1 & 0 & NA \\\\
\\end{bmatrix}](https://s0.wp.com/latex.php?latex=K%3D%5Cbegin%7Bbmatrix%7D+19+%26+4+%26+95+%26+NA+%5C%5C+5+%26+1+%26+25+%26+3+%5C%5C+4+%26+1+%26+20+%26+1+%5C%5C+1+%26+0+%26+5+%26+4+%5C%5C+0+%26+1+%26+0+%26+NA+%5C%5C+%5Cend%7Bbmatrix%7D&bg=ffffff&fg=333333&s=0
"K=\\begin{bmatrix} 19 & 4 & 95 & NA \\\\ 5 & 1 & 25 & 3 \\\\ 4 & 1 & 20 & 1 \\\\ 1 & 0 & 5 & 4 \\\\ 0 & 1 & 0 & NA \\\\ \\end{bmatrix}")

The process is initiated with column
![K\[,3\]](https://s0.wp.com/latex.php?latex=K%5B%2C3%5D&bg=ffffff&fg=333333&s=0
"K[,3]"). Write
![K\[1,3\]=a](https://s0.wp.com/latex.php?latex=K%5B1%2C3%5D%3Da&bg=ffffff&fg=333333&s=0
"K[1,3]=a") and
![K\[2,3\]=b](https://s0.wp.com/latex.php?latex=K%5B2%2C3%5D%3Db&bg=ffffff&fg=333333&s=0
"K[2,3]=b"). Kuṭṭaka in Sanskrit means ‘to powder’, common translated as
‘pulverizer’. We start ‘pulverizing’
![a=95](https://s0.wp.com/latex.php?latex=a%3D95&bg=ffffff&fg=333333&s=0
"a=95") with
![b=25](https://s0.wp.com/latex.php?latex=b%3D25&bg=ffffff&fg=333333&s=0
"b=25"), which means finding the ![K\[3,3\]=K\[1,3\] \\mod
K\[2,3\]](https://s0.wp.com/latex.php?latex=K%5B3%2C3%5D%3DK%5B1%2C3%5D+%5Cmod+K%5B2%2C3%5D&bg=ffffff&fg=333333&s=0
"K[3,3]=K[1,3] \\mod K[2,3]"). Then ![K\[4,3\]=K\[2,3\] \\mod
K\[3,3\]](https://s0.wp.com/latex.php?latex=K%5B4%2C3%5D%3DK%5B2%2C3%5D+%5Cmod+K%5B3%2C3%5D&bg=ffffff&fg=333333&s=0
"K[4,3]=K[2,3] \\mod K[3,3]"). We iterate this procedure until we get
![K\[n,3\]=0](https://s0.wp.com/latex.php?latex=K%5Bn%2C3%5D%3D0&bg=ffffff&fg=333333&s=0
"K[n,3]=0"); that completes the column
![K\[,3\]](https://s0.wp.com/latex.php?latex=K%5B%2C3%5D&bg=ffffff&fg=333333&s=0
"K[,3]"). We call
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n") as
the number of iterations for convergence. Thus, the matrix will have
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
rows and 4 columns. The quotient of the division of ![K\[1,3\] \\div
K\[2,3\]=3](https://s0.wp.com/latex.php?latex=K%5B1%2C3%5D+%5Cdiv+K%5B2%2C3%5D%3D3&bg=ffffff&fg=333333&s=0
"K[1,3] \\div K[2,3]=3") is written as
![K\[2,4\]](https://s0.wp.com/latex.php?latex=K%5B2%2C4%5D&bg=ffffff&fg=333333&s=0
"K[2,4]"), that of ![K\[2,3\] \\div
K\[3,3\]=1](https://s0.wp.com/latex.php?latex=K%5B2%2C3%5D+%5Cdiv+K%5B3%2C3%5D%3D1&bg=ffffff&fg=333333&s=0
"K[2,3] \\div K[3,3]=1") as
![K\[3,4\]](https://s0.wp.com/latex.php?latex=K%5B3%2C4%5D&bg=ffffff&fg=333333&s=0
"K[3,4]"), so on till convergence. Thus, the cells
![K\[4,1\]](https://s0.wp.com/latex.php?latex=K%5B4%2C1%5D&bg=ffffff&fg=333333&s=0
"K[4,1]") and
![K\[4,n\]](https://s0.wp.com/latex.php?latex=K%5B4%2Cn%5D&bg=ffffff&fg=333333&s=0
"K[4,n]") will always be empty (NA in the R language).

Then we fill in
![K\[n,2\]=1](https://s0.wp.com/latex.php?latex=K%5Bn%2C2%5D%3D1&bg=ffffff&fg=333333&s=0
"K[n,2]=1") and
![K\[n-1,2\]=0](https://s0.wp.com/latex.php?latex=K%5Bn-1%2C2%5D%3D0&bg=ffffff&fg=333333&s=0
"K[n-1,2]=0"). There after we compute the remaining elements of this
column working upwards from
![K\[n-2,2\]](https://s0.wp.com/latex.php?latex=K%5Bn-2%2C2%5D&bg=ffffff&fg=333333&s=0
"K[n-2,2]") with the formula:

![K\[j,2\]=K\[j+1,2\]\\cdot
K\[j+1,4\]+K\[j+2,2\]](https://s0.wp.com/latex.php?latex=K%5Bj%2C2%5D%3DK%5Bj%2B1%2C2%5D%5Ccdot+K%5Bj%2B1%2C4%5D%2BK%5Bj%2B2%2C2%5D&bg=ffffff&fg=333333&s=0
"K[j,2]=K[j+1,2]\\cdot K[j+1,4]+K[j+2,2]")

We then fill in
![K\[n,1\]=0](https://s0.wp.com/latex.php?latex=K%5Bn%2C1%5D%3D0&bg=ffffff&fg=333333&s=0
"K[n,1]=0") and
![K\[n-1,1\]=1](https://s0.wp.com/latex.php?latex=K%5Bn-1%2C1%5D%3D1&bg=ffffff&fg=333333&s=0
"K[n-1,1]=1") and complete the column starting
![K\[n-2,1\]](https://s0.wp.com/latex.php?latex=K%5Bn-2%2C1%5D&bg=ffffff&fg=333333&s=0
"K[n-2,1]") upwards with the formula:

![K\[j,1\]=K\[j+1,1\]\\cdot
K\[j+1,4\]+K\[j+2,1\]](https://s0.wp.com/latex.php?latex=K%5Bj%2C1%5D%3DK%5Bj%2B1%2C1%5D%5Ccdot+K%5Bj%2B1%2C4%5D%2BK%5Bj%2B2%2C1%5D&bg=ffffff&fg=333333&s=0
"K[j,1]=K[j+1,1]\\cdot K[j+1,4]+K[j+2,1]")

With that we have our kuṭṭaka matrix
![K](https://s0.wp.com/latex.php?latex=K&bg=ffffff&fg=333333&s=0 "K")
and all the needfull stuff to solve the said indeterminate equation:  
1\) The greatest common divisor
![\\textrm{GCD}(a,b)=K\[n-1,3\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BGCD%7D%28a%2Cb%29%3DK%5Bn-1%2C3%5D&bg=ffffff&fg=333333&s=0
"\\textrm{GCD}(a,b)=K[n-1,3]"). This is also the smallest positive
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
for which our indeterminate equation has integer solutions.  
2\) The least common multiple ![\\textrm{LCM}(a,b)=K\[1,1\]\\cdot
K\[2,1\]\\cdot
K\[n-1,3\]](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLCM%7D%28a%2Cb%29%3DK%5B1%2C1%5D%5Ccdot+K%5B2%2C1%5D%5Ccdot+K%5Bn-1%2C3%5D&bg=ffffff&fg=333333&s=0
"\\textrm{LCM}(a,b)=K[1,1]\\cdot K[2,1]\\cdot K[n-1,3]")  
3\) The integer lattice points through which the line passes are
obtained from
![(K\[2,2\],K\[1,2\])](https://s0.wp.com/latex.php?latex=%28K%5B2%2C2%5D%2CK%5B1%2C2%5D%29&bg=ffffff&fg=333333&s=0
"(K[2,2],K[1,2])") by assigning the appropriate signs. Thus, for the
above equation we have the solution ![95\\times(-1)-25\\times (-4) =
5](https://s0.wp.com/latex.php?latex=95%5Ctimes%28-1%29-25%5Ctimes+%28-4%29+%3D+5&bg=ffffff&fg=333333&s=0
"95\\times(-1)-25\\times (-4) = 5"). Thus,
![95x-25y=5](https://s0.wp.com/latex.php?latex=95x-25y%3D5&bg=ffffff&fg=333333&s=0
"95x-25y=5") will pass through the integer lattice at the point
![(-1,-4)](https://s0.wp.com/latex.php?latex=%28-1%2C-4%29&bg=ffffff&fg=333333&s=0
"(-1,-4)")  
4\) If we enforce the need for positive solutions then we can use
![(K\[2,1\]-K\[2,2\],
K\[1,1\]-K\[1,2\])](https://s0.wp.com/latex.php?latex=%28K%5B2%2C1%5D-K%5B2%2C2%5D%2C+K%5B1%2C1%5D-K%5B1%2C2%5D%29&bg=ffffff&fg=333333&s=0
"(K[2,1]-K[2,2], K[1,1]-K[1,2])") to obtain the minimal integer
solution: ![95 \\times 4 -25 \\times 15
=5](https://s0.wp.com/latex.php?latex=95+%5Ctimes+4+-25+%5Ctimes+15+%3D5&bg=ffffff&fg=333333&s=0
"95 \\times 4 -25 \\times 15 =5"). Thus,
![95x-25y=5](https://s0.wp.com/latex.php?latex=95x-25y%3D5&bg=ffffff&fg=333333&s=0
"95x-25y=5") will pass through the integer lattice at the point
![(4,15)](https://s0.wp.com/latex.php?latex=%284%2C15%29&bg=ffffff&fg=333333&s=0
"(4,15)") in the first quadrant.  
5\) We can write the following relationship, which helps us to more
generally get the lattice points through which the line
![ax-by=c](https://s0.wp.com/latex.php?latex=ax-by%3Dc&bg=ffffff&fg=333333&s=0
"ax-by=c") passes even if the values of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and ![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0
"b") are interchanged or for
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c")
other than the minimal
![c](https://s0.wp.com/latex.php?latex=c&bg=ffffff&fg=333333&s=0 "c"):

![b(K\[1,1\]\\cdot p+K\[1,2\] \\cdot q)-a(K\[2,1\]\\cdot p
+K\[2,2\]\\cdot q)=K\[n-1,3\]\\cdot
q](https://s0.wp.com/latex.php?latex=b%28K%5B1%2C1%5D%5Ccdot+p%2BK%5B1%2C2%5D+%5Ccdot+q%29-a%28K%5B2%2C1%5D%5Ccdot+p+%2BK%5B2%2C2%5D%5Ccdot+q%29%3DK%5Bn-1%2C3%5D%5Ccdot+q&bg=ffffff&fg=333333&s=0
"b(K[1,1]\\cdot p+K[1,2] \\cdot q)-a(K[2,1]\\cdot p +K[2,2]\\cdot q)=K[n-1,3]\\cdot q")

Thus, if we set ![p=-1,
q=1](https://s0.wp.com/latex.php?latex=p%3D-1%2C+q%3D1&bg=ffffff&fg=333333&s=0
"p=-1, q=1"), we get
![(-4,-15)](https://s0.wp.com/latex.php?latex=%28-4%2C-15%29&bg=ffffff&fg=333333&s=0
"(-4,-15)") as further lattice points through which the line
![95x-25y=5](https://s0.wp.com/latex.php?latex=95x-25y%3D5&bg=ffffff&fg=333333&s=0
"95x-25y=5") passes.

Now we can tackle the original problem: Since it says that 7 divides the
number ![r](https://s0.wp.com/latex.php?latex=r&bg=ffffff&fg=333333&s=0
"r") perfectly it can be written as
![r=7y](https://s0.wp.com/latex.php?latex=r%3D7y&bg=ffffff&fg=333333&s=0
"r=7y") where
![y](https://s0.wp.com/latex.php?latex=y&bg=ffffff&fg=333333&s=0 "y")
will the y-coordinate of the lattice point. The numbers 2, 3, 4, 5, 6
leave a remainder of 1. Of them 4 is divisible by 2, and 6 by both 2 and
3. So all we need to consider are the numbers 4, 5, 6. Using the above
kuṭṭaka or any other means we can show that
![\\textrm{LCM}(4,5)=20](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLCM%7D%284%2C5%29%3D20&bg=ffffff&fg=333333&s=0
"\\textrm{LCM}(4,5)=20") and
![\\textrm{LCM}(20,6)=60](https://s0.wp.com/latex.php?latex=%5Ctextrm%7BLCM%7D%2820%2C6%29%3D60&bg=ffffff&fg=333333&s=0
"\\textrm{LCM}(20,6)=60"). Thus, we can write
![7y=60x+1](https://s0.wp.com/latex.php?latex=7y%3D60x%2B1&bg=ffffff&fg=333333&s=0
"7y=60x+1"), where
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
will the
![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0 "x")
coordinate of the integer lattice. Using kuṭṭaka on the equation
![7y-60x=1](https://s0.wp.com/latex.php?latex=7y-60x%3D1&bg=ffffff&fg=333333&s=0
"7y-60x=1") we get the matrix:

![K=\\begin{bmatrix} 60 & 17 & 60 & NA\\\\ 7 & 2 & 7 & 8\\\\ 4 & 1 & 4 &
1\\\\ 3 & 1 & 3 & 1\\\\ 1 & 0 & 1 & 3\\\\ 0 & 1 & 0 & NA\\\\
\\end{bmatrix}](https://s0.wp.com/latex.php?latex=K%3D%5Cbegin%7Bbmatrix%7D+60+%26+17+%26+60+%26+NA%5C%5C+7+%26+2+%26+7+%26+8%5C%5C+4+%26+1+%26+4+%26+1%5C%5C+3+%26+1+%26+3+%26+1%5C%5C+1+%26+0+%26+1+%26+3%5C%5C+0+%26+1+%26+0+%26+NA%5C%5C+%5Cend%7Bbmatrix%7D&bg=ffffff&fg=333333&s=0
"K=\\begin{bmatrix} 60 & 17 & 60 & NA\\\\ 7 & 2 & 7 & 8\\\\ 4 & 1 & 4 & 1\\\\ 3 & 1 & 3 & 1\\\\ 1 & 0 & 1 & 3\\\\ 0 & 1 & 0 & NA\\\\ \\end{bmatrix}")

From this we can compose ![(60-17) \\times 7 - (7-2) \\times 60 =
1](https://s0.wp.com/latex.php?latex=%2860-17%29+%5Ctimes+7+-+%287-2%29+%5Ctimes+60+%3D+1&bg=ffffff&fg=333333&s=0
"(60-17) \\times 7 - (7-2) \\times 60 = 1"). Thus, our number is ![r= 43
\\times 7 =
301](https://s0.wp.com/latex.php?latex=r%3D+43+%5Ctimes+7+%3D+301&bg=ffffff&fg=333333&s=0
"r= 43 \\times 7 = 301"), which is divisible by 7 but leaves a remainder
of 1 for all integers from 2:6. More generally, if we say that ![r \\mod
2:6 \\equiv
1](https://s0.wp.com/latex.php?latex=r+%5Cmod+2%3A6+%5Cequiv+1&bg=ffffff&fg=333333&s=0
"r \\mod 2:6 \\equiv 1") then we can use
![K](https://s0.wp.com/latex.php?latex=K&bg=ffffff&fg=333333&s=0 "K") to
compose the negative solutions ![r=-17 \\times
7=-119](https://s0.wp.com/latex.php?latex=r%3D-17+%5Ctimes+7%3D-119&bg=ffffff&fg=333333&s=0
"r=-17 \\times 7=-119") or ![r=-77 \\times 7
=-539](https://s0.wp.com/latex.php?latex=r%3D-77+%5Ctimes+7+%3D-539&bg=ffffff&fg=333333&s=0
"r=-77 \\times 7 =-539"). Such triplets of solutions correspond to
symmetric lattice points along the line.

In the final part of this note we shall consider the following
operation: Take a number
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
and perform the kuṭṭaka operation with it (i.e.
![a=n](https://s0.wp.com/latex.php?latex=a%3Dn&bg=ffffff&fg=333333&s=0
"a=n")) and all integers lesser than or equal to it (i.e.
![b=1:n](https://s0.wp.com/latex.php?latex=b%3D1%3An&bg=ffffff&fg=333333&s=0
"b=1:n")). Then we count the number of iterations it takes with each of
these integers to reach convergence. From above it is clear that the
minimum number of iterations for convergence will always be 3. We term
the result the kuṭṭaka spectrum of a number and plot this spectrum for
the numbers 120, 123, 127 and 128.

[![kuTTaka\_spectrum](https://manasataramgini.files.wordpress.com/2018/04/kuttaka_spectrum.png?w=640)](https://manasataramgini.files.wordpress.com/2018/04/kuttaka_spectrum.png)Figure
1

The kuṭṭaka spectrum displays several notable features:  
1\) It is pseudo-symmetric about the mid-point, i.e. either side of
![a/2](https://s0.wp.com/latex.php?latex=a%2F2&bg=ffffff&fg=333333&s=0
"a/2") is an approximate mirror image of the other side but they differ
in “height” by one iteration.

2\) The number of times the kuṭṭaka spectrum hits a minimum (i.e.
converges in 3 iterations) is equal to the number of divisors of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"),
![D(n)](https://s0.wp.com/latex.php?latex=D%28n%29&bg=ffffff&fg=333333&s=0
"D(n)"). Thus, for a highly composite number, as defined by Ramanujan,
we get the record number of minima in the kuṭṭaka spectrum for any
number less than it. Thus, in our example the highly composite number
![a=120](https://s0.wp.com/latex.php?latex=a%3D120&bg=ffffff&fg=333333&s=0
"a=120") has 16 minima with the first six integers 1:6 giving a run of 6
successive minima. A minimally composite number like ![a=123=3 \\times
41](https://s0.wp.com/latex.php?latex=a%3D123%3D3+%5Ctimes+41&bg=ffffff&fg=333333&s=0
"a=123=3 \\times 41") in our figure we get 4 minima, namely 1 and the
number itself and its two prime factors. The prime number in our figure,
![a=127](https://s0.wp.com/latex.php?latex=a%3D127&bg=ffffff&fg=333333&s=0
"a=127"), as expected has only 2 minima.

3\) The more composite a number the lower its mean value of iterations
(red line in Figure 1) than other integers in its immediate
neighborhood. Thus, the highly composite number 120 has the lowest mean
value in our set. In contrast, the primes have higher mean values than
the integers in their immediate neighborhood. This is can be seen with
![a=127](https://s0.wp.com/latex.php?latex=a%3D127&bg=ffffff&fg=333333&s=0
"a=127") in Figure 1.

4\) A curious feature of the spectrum are the maxima, i.e. the value of
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
for which the maximum number of iterations are required for pulverizing
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") to
convergence. For example the spectrum of
![a=128](https://s0.wp.com/latex.php?latex=a%3D128&bg=ffffff&fg=333333&s=0
"a=128") shows 2 maxima:
![b=79](https://s0.wp.com/latex.php?latex=b%3D79&bg=ffffff&fg=333333&s=0
"b=79") pulverizes it via the pathway: 128, 79, 49, 30, 19, 11, 8, 3, 2,
1, 0. The other one
![b=81](https://s0.wp.com/latex.php?latex=b%3D81&bg=ffffff&fg=333333&s=0
"b=81") via 128, 81, 47, 34, 13, 8, 5, 3, 2, 1, 0. One immediately
notices that the convergence in each of these two cases enters the
Golden ratio convergent sequence. This feature can be investigated
further by examining the distribution of the values of
![a/b](https://s0.wp.com/latex.php?latex=a%2Fb&bg=ffffff&fg=333333&s=0
"a/b") for those
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
which result in maxima in the kuṭṭaka spectrum for a given
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
In order to have have clear discrimination of these fractional values of
![a/b](https://s0.wp.com/latex.php?latex=a%2Fb&bg=ffffff&fg=333333&s=0
"a/b") corresponding to the spectral maxima we chose a set of relatively
large ![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0
"a"), namely all integers from 500 to 1000. We then determined the
kuṭṭaka spectrum for each of those numbers and extracted the maxima
for each
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and plotted a distribution of the
![a/b](https://s0.wp.com/latex.php?latex=a%2Fb&bg=ffffff&fg=333333&s=0
"a/b") values (Figure 2).

[![kuTTaka\_maxima](https://manasataramgini.files.wordpress.com/2018/04/kuttaka_maxima.png?w=640)](https://manasataramgini.files.wordpress.com/2018/04/kuttaka_maxima.png)Figure
2.

First, the maxima always occur in second half of the spectrum (Figure
2), i.e.
![b\>\\tfrac{a}{2}](https://s0.wp.com/latex.php?latex=b%3E%5Ctfrac%7Ba%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"b\>\\tfrac{a}{2}"). This makes sense because smaller
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
would reach close to
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") in
the first division itself and could pulverize it to a relative small
number. However,
![b\>\\tfrac{a}{2}](https://s0.wp.com/latex.php?latex=b%3E%5Ctfrac%7Ba%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"b\>\\tfrac{a}{2}") would fit only once in
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
and could leave a relatively large remainder that could need more steps
for pulverizing. Second, strikingly, the dominant peak in this
distribution is the Golden ratio
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") (Figure 2), suggesting the maxima tend to occur where
![\\tfrac{a}{b} \\approx
\\phi](https://s0.wp.com/latex.php?latex=%5Ctfrac%7Ba%7D%7Bb%7D+%5Capprox+%5Cphi&bg=ffffff&fg=333333&s=0
"\\tfrac{a}{b} \\approx \\phi"). Indeed in our above example
![\\tfrac{128}{79}=1.620253](https://s0.wp.com/latex.php?latex=%5Ctfrac%7B128%7D%7B79%7D%3D1.620253&bg=ffffff&fg=333333&s=0
"\\tfrac{128}{79}=1.620253"). This can be intuitively understood as the
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
which generates a maximum may be seen as a Golden cut of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"):
if
![b\>\\tfrac{a}{2}](https://s0.wp.com/latex.php?latex=b%3E%5Ctfrac%7Ba%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"b\>\\tfrac{a}{2}") is too big then the remainder generated will be
small and might be pulverized quickly. If
![b\>\\tfrac{a}{2}](https://s0.wp.com/latex.php?latex=b%3E%5Ctfrac%7Ba%7D%7B2%7D&bg=ffffff&fg=333333&s=0
"b\>\\tfrac{a}{2}") is too small then it will leave a big remainder
relative to
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
which might be quickly pulverized in the next step. Thus, the
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") could give you the cut that is just right. The next dominant
peak is at ![3-\\phi \\approx
1.381966](https://s0.wp.com/latex.php?latex=3-%5Cphi+%5Capprox+1.381966&bg=ffffff&fg=333333&s=0
"3-\\phi \\approx 1.381966"). This is similar to
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") in its operation. These two are marked by a red dashed line in
Figure 2.

There are further peaks in the distribution corresponding to other
fractions on either side of
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") following a certain pattern of declining heights. Further they
show the same symmetry as
![\\phi](https://s0.wp.com/latex.php?latex=%5Cphi&bg=ffffff&fg=333333&s=0
"\\phi") and
![3-\\phi](https://s0.wp.com/latex.php?latex=3-%5Cphi&bg=ffffff&fg=333333&s=0
"3-\\phi"), with each peak
![m](https://s0.wp.com/latex.php?latex=m&bg=ffffff&fg=333333&s=0 "m")
having a counterpart
![3-m](https://s0.wp.com/latex.php?latex=3-m&bg=ffffff&fg=333333&s=0
"3-m"). We have thus far not been able to determine a more  
general expression describing all these peaks or prove why they should
be peaks but we were able to account for a subset of them as
corresponding to other quadratic irrational numbers (marked by grey
dashed lines in Figure 2). These include:

![\\sqrt{35/11} \\approx 1.783765, 3-\\sqrt{35/11} \\approx
1.216235](https://s0.wp.com/latex.php?latex=%5Csqrt%7B35%2F11%7D+%5Capprox+1.783765%2C+3-%5Csqrt%7B35%2F11%7D+%5Capprox+1.216235&bg=ffffff&fg=333333&s=0
"\\sqrt{35/11} \\approx 1.783765, 3-\\sqrt{35/11} \\approx 1.216235")  
![\\sqrt{3} \\approx 1.732051, 3-\\sqrt{3} \\approx
1.267949](https://s0.wp.com/latex.php?latex=%5Csqrt%7B3%7D+%5Capprox+1.732051%2C+3-%5Csqrt%7B3%7D+%5Capprox+1.267949&bg=ffffff&fg=333333&s=0
"\\sqrt{3} \\approx 1.732051, 3-\\sqrt{3} \\approx 1.267949")  
![\\sqrt{24/9} \\approx 1.632993, 3-\\sqrt{24/9} \\approx
1.367007](https://s0.wp.com/latex.php?latex=%5Csqrt%7B24%2F9%7D+%5Capprox+1.632993%2C+3-%5Csqrt%7B24%2F9%7D+%5Capprox+1.367007&bg=ffffff&fg=333333&s=0
"\\sqrt{24/9} \\approx 1.632993, 3-\\sqrt{24/9} \\approx 1.367007")  
![\\sqrt{2} \\approx 1.414214, 3-\\sqrt{2} \\approx
1.585786](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D+%5Capprox+1.414214%2C+3-%5Csqrt%7B2%7D+%5Capprox+1.585786&bg=ffffff&fg=333333&s=0
"\\sqrt{2} \\approx 1.414214, 3-\\sqrt{2} \\approx 1.585786")

Of these the pair ![\\sqrt{2},
3-\\sqrt{2}](https://s0.wp.com/latex.php?latex=%5Csqrt%7B2%7D%2C+3-%5Csqrt%7B2%7D&bg=ffffff&fg=333333&s=0
"\\sqrt{2}, 3-\\sqrt{2}"), especially the former is not the best fit to
the peak but given the breadth of that peak it is possible that more
than one attractor fraction is merged in that peak. It would be a good
mathematical quest to discover the general expression for the peaks,
their dominance and prove why they tend to be peaks. There might be a
subtle fractal structure to them that might become apparent at large
values of
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a").
