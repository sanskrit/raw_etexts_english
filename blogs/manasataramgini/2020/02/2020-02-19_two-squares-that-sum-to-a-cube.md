+++
title = "Two squares that sum to a cube"

+++
**Introduction**  
This note records an exploration that began in our youth with the simple
arithmetic question: *Sum of the squares of which pair integers yields a
perfect cube?* Some obvious cases immediately come to mind:
![2^2+2^2=2^3;
5^2+10^2=5^3](https://s0.wp.com/latex.php?latex=2%5E2%2B2%5E2%3D2%5E3%3B+5%5E2%2B10%5E2%3D5%5E3&bg=ffffff&fg=333333&s=0
"2^2+2^2=2^3; 5^2+10^2=5^3"). In both these cases we can see that the
addition of a square the to the square of the first number yields its
cube. Hence, we can ask another related question: *Which are the
integers whose squares when added to another perfect square yield their
cubes?* In general terms the answers to these questions are the
non-trivial (i.e. where ![x, y, z \\ne
0](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z+%5Cne+0&bg=ffffff&fg=333333&s=0
"x, y, z \\ne 0")) solutions of the indeterminate equation:

![x^2+y^2=z^3 \\;\\;\\; (\\S
1)](https://s0.wp.com/latex.php?latex=x%5E2%2By%5E2%3Dz%5E3+%5C%3B%5C%3B%5C%3B+%28%5CS+1%29&bg=ffffff&fg=333333&s=0
"x^2+y^2=z^3 \\;\\;\\; (\\S 1)")

Figure 1 shows the first few solutions lying on the surface defined by
![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1"). Due to the 8-fold symmetry we restrict ourselves to positive
solutions such that ![x \\le
y](https://s0.wp.com/latex.php?latex=x+%5Cle+y&bg=ffffff&fg=333333&s=0
"x \\le y") for a given
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z").

[![sqrs\_cube\_xyz\_Fig1](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xyz_fig1.png?w=466&h=437)](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xyz_fig1.png)Figure
1

Since ![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0
"z") is explicitly defined by ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") we can study the solutions of ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") by plotting ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") on the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0
"x-y") plane (Figure 2). At first sight, a mathematically naive person
might perceive only a limited order in this plot of the solutions.
However, as we shall see below, a closer examination and some algebra
reveals a deep structure.

[![sqrs\_cube\_xy\_Fig2](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xy_fig2.png?w=614&h=447)](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xy_fig2.png)Figure
2. Some of the more obvious structure is indicated in different colors
and is discussed below in detail.

**Solution circles, 2 square numbers and Brahmagupta’s identity**  
Some simple algebra can provide an understanding of the structure of the
solutions of ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1"). From ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") it is obvious that all solutions would be lattice points
![(x,y)](https://s0.wp.com/latex.php?latex=%28x%2Cy%29&bg=ffffff&fg=333333&s=0
"(x,y)") on circles of radius
![z^{3/2}](https://s0.wp.com/latex.php?latex=z%5E%7B3%2F2%7D&bg=ffffff&fg=333333&s=0
"z^{3/2}"). Based on this, we can determine a set of ![x, y,
z](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z&bg=ffffff&fg=333333&s=0
"x, y, z") that are to solutions of ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") thus: let
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") be
an integer that is the sum of two perfect squares,
![z=m^2+n^2](https://s0.wp.com/latex.php?latex=z%3Dm%5E2%2Bn%5E2&bg=ffffff&fg=333333&s=0
"z=m^2+n^2"). Then,  
![\\left(m^2+n^2\\right)^3= m^6 + 3m^4n^2 + 3m^2n^4 + n^6\\\\\[6pt\]
=(m^6+2m^4n^2+m^2n^4)+(n^6+2m^2n^4+m^4n^2)\\\\\[6pt\]
=m^2(m^4+2m^2n^2+n^4)+n^2(n^4+2m^2n^2+m^4)\\\\\[6pt\]
=(m(m^2+n^2))^2+(n(m^2+n^2))^2 \\; \\; \\; (\\S
2)](https://s0.wp.com/latex.php?latex=%5Cleft%28m%5E2%2Bn%5E2%5Cright%29%5E3%3D+m%5E6+%2B+3m%5E4n%5E2+%2B+3m%5E2n%5E4+%2B+n%5E6%5C%5C%5B6pt%5D+%3D%28m%5E6%2B2m%5E4n%5E2%2Bm%5E2n%5E4%29%2B%28n%5E6%2B2m%5E2n%5E4%2Bm%5E4n%5E2%29%5C%5C%5B6pt%5D+%3Dm%5E2%28m%5E4%2B2m%5E2n%5E2%2Bn%5E4%29%2Bn%5E2%28n%5E4%2B2m%5E2n%5E2%2Bm%5E4%29%5C%5C%5B6pt%5D+%3D%28m%28m%5E2%2Bn%5E2%29%29%5E2%2B%28n%28m%5E2%2Bn%5E2%29%29%5E2+%5C%3B+%5C%3B+%5C%3B+%28%5CS+2%29&bg=ffffff&fg=333333&s=0
"\\left(m^2+n^2\\right)^3= m^6 + 3m^4n^2 + 3m^2n^4 + n^6\\\\[6pt] =(m^6+2m^4n^2+m^2n^4)+(n^6+2m^2n^4+m^4n^2)\\\\[6pt] =m^2(m^4+2m^2n^2+n^4)+n^2(n^4+2m^2n^2+m^4)\\\\[6pt] =(m(m^2+n^2))^2+(n(m^2+n^2))^2 \\; \\; \\; (\\S 2)")

Thus, if
![z=m^2+n^2](https://s0.wp.com/latex.php?latex=z%3Dm%5E2%2Bn%5E2&bg=ffffff&fg=333333&s=0
"z=m^2+n^2") (i.e. it is a 2 square number) ![\\S
2](https://s0.wp.com/latex.php?latex=%5CS+2&bg=ffffff&fg=333333&s=0
"\\S 2") gives us an expression for
![z^3](https://s0.wp.com/latex.php?latex=z%5E3&bg=ffffff&fg=333333&s=0
"z^3") as the sum of 2 squares. Hence, the valid solutions to ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1") will be all  
![x=m^3+n^2m\\\\\[6pt\] y=n^3+m^2n\\\\\[6pt\]
z=m^2+n^2](https://s0.wp.com/latex.php?latex=x%3Dm%5E3%2Bn%5E2m%5C%5C%5B6pt%5D+y%3Dn%5E3%2Bm%5E2n%5C%5C%5B6pt%5D+z%3Dm%5E2%2Bn%5E2&bg=ffffff&fg=333333&s=0
"x=m^3+n^2m\\\\[6pt] y=n^3+m^2n\\\\[6pt] z=m^2+n^2")

For example, if ![z=5 =
1^2+2^2](https://s0.wp.com/latex.php?latex=z%3D5+%3D+1%5E2%2B2%5E2&bg=ffffff&fg=333333&s=0
"z=5 = 1^2+2^2") we have ![m=1; \\;
n=2](https://s0.wp.com/latex.php?latex=m%3D1%3B+%5C%3B+n%3D2&bg=ffffff&fg=333333&s=0
"m=1; \\; n=2"). Thus, ![x=1^3+2^2\\times
1=5](https://s0.wp.com/latex.php?latex=x%3D1%5E3%2B2%5E2%5Ctimes+1%3D5&bg=ffffff&fg=333333&s=0
"x=1^3+2^2\\times 1=5") and ![y=2^3+1^2\\times 2=
10](https://s0.wp.com/latex.php?latex=y%3D2%5E3%2B1%5E2%5Ctimes+2%3D+10&bg=ffffff&fg=333333&s=0
"y=2^3+1^2\\times 2= 10"). Hence,
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
which belong to the 2 square sequence, i.e. numbers that can be
non-trivially (i.e. one of the terms is not 0) expressed as the sum of 2
perfect squares, are valid solutions: **2, 5, 8, 10, 13, 17, 18, 20, 25,
26…** The corresponding ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") can be derived as above. One also notices from the above
expressions that
![m^2+n^2=z](https://s0.wp.com/latex.php?latex=m%5E2%2Bn%5E2%3Dz&bg=ffffff&fg=333333&s=0
"m^2+n^2=z") is a common factor for ![x, y,
z](https://s0.wp.com/latex.php?latex=x%2C+y%2C+z&bg=ffffff&fg=333333&s=0
"x, y, z") in all such solutions to ![\\S
1](https://s0.wp.com/latex.php?latex=%5CS+1&bg=ffffff&fg=333333&s=0
"\\S 1").

While this method yields ![x=5, \\; y=10, \\;
z=5](https://s0.wp.com/latex.php?latex=x%3D5%2C+%5C%3B+y%3D10%2C+%5C%3B+z%3D5&bg=ffffff&fg=333333&s=0
"x=5, \\; y=10, \\; z=5"), we notice that the same
![z=5](https://s0.wp.com/latex.php?latex=z%3D5&bg=ffffff&fg=333333&s=0
"z=5") also yields a second pair of ![x=2,
y=11](https://s0.wp.com/latex.php?latex=x%3D2%2C+y%3D11&bg=ffffff&fg=333333&s=0
"x=2, y=11"). Now how do we account for these additional pairs and for
what values of
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
they arise?

The most obvious set of these correspond to
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
being equal to special numbers such as **5, 13, 17, 29…** One notices
that these are both 2 square numbers and primes of the form
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1"). Fermat first noticed that such primes are always 2 square
numbers. This attracted the attention of some of the greatest
mathematicians like Euler, Lagrange and Gauss, who proved it to be so by
using different methods. What is important for us is that such primes
are also the karṇā-s (hypotenuses) of primitive bhujā-koṭi-karṇā
triples. Thus, we have
![z=m^2+n^2](https://s0.wp.com/latex.php?latex=z%3Dm%5E2%2Bn%5E2&bg=ffffff&fg=333333&s=0
"z=m^2+n^2") from the fact that they are 2 square numbers and
![z^2=a^2+b^2](https://s0.wp.com/latex.php?latex=z%5E2%3Da%5E2%2Bb%5E2&bg=ffffff&fg=333333&s=0
"z^2=a^2+b^2") from the fact that they are bh-k-k hypotenuses. Hence, we
can write,  
![z^3=z \\cdot z^2 =(m^2+n^2)(a^2+b^2)\\\\\[6pt\] =a^2m^2 + a^2n^2 +
b^2m^2 + b^2n^2\\\\\[6pt\] =(a^2m^2 + b^2n^2 +2am \\cdot bn) + (a^2n^2 +
b^2m^2 - 2am \\cdot bn))\\\\\[6pt\] =(an-bm)^2+(am+bn)^2 \\; \\; \\;
(\\S
3)](https://s0.wp.com/latex.php?latex=z%5E3%3Dz+%5Ccdot+z%5E2+%3D%28m%5E2%2Bn%5E2%29%28a%5E2%2Bb%5E2%29%5C%5C%5B6pt%5D+%3Da%5E2m%5E2+%2B+a%5E2n%5E2+%2B+b%5E2m%5E2+%2B+b%5E2n%5E2%5C%5C%5B6pt%5D+%3D%28a%5E2m%5E2+%2B+b%5E2n%5E2+%2B2am+%5Ccdot+bn%29+%2B+%28a%5E2n%5E2+%2B+b%5E2m%5E2+-+2am+%5Ccdot+bn%29%29%5C%5C%5B6pt%5D+%3D%28an-bm%29%5E2%2B%28am%2Bbn%29%5E2+%5C%3B+%5C%3B+%5C%3B+%28%5CS+3%29&bg=ffffff&fg=333333&s=0
"z^3=z \\cdot z^2 =(m^2+n^2)(a^2+b^2)\\\\[6pt] =a^2m^2 + a^2n^2 + b^2m^2 + b^2n^2\\\\[6pt] =(a^2m^2 + b^2n^2 +2am \\cdot bn) + (a^2n^2 + b^2m^2 - 2am \\cdot bn))\\\\[6pt] =(an-bm)^2+(am+bn)^2 \\; \\; \\; (\\S 3)")

Alternatively,  
![(a^2m^2 + b^2n^2 -2am \\cdot bn) + (a^2n^2 + b^2m^2 + 2am \\cdot
bn)\\\\\[6pt\] (am-bn)^2 + (an+bm)^2 \\; \\; \\; (\\S
4)](https://s0.wp.com/latex.php?latex=%28a%5E2m%5E2+%2B+b%5E2n%5E2+-2am+%5Ccdot+bn%29+%2B+%28a%5E2n%5E2+%2B+b%5E2m%5E2+%2B+2am+%5Ccdot+bn%29%5C%5C%5B6pt%5D+%28am-bn%29%5E2+%2B+%28an%2Bbm%29%5E2+%5C%3B+%5C%3B+%5C%3B+%28%5CS+4%29&bg=ffffff&fg=333333&s=0
"(a^2m^2 + b^2n^2 -2am \\cdot bn) + (a^2n^2 + b^2m^2 + 2am \\cdot bn)\\\\[6pt] (am-bn)^2 + (an+bm)^2 \\; \\; \\; (\\S 4)")

![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0
"\\S 3") and ![\\S
4](https://s0.wp.com/latex.php?latex=%5CS+4&bg=ffffff&fg=333333&s=0
"\\S 4") give us the famous identities of Brahmagupta from which we get
two expressions for
![z^3](https://s0.wp.com/latex.php?latex=z%5E3&bg=ffffff&fg=333333&s=0
"z^3") as the sum of a pair of perfect squares when
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") is
a
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") prime. From ![\\S
3](https://s0.wp.com/latex.php?latex=%5CS+3&bg=ffffff&fg=333333&s=0
"\\S 3") we get:  
![x =|bm-an| \\\\\[6pt\] y = am+bn\\\\\[6pt\] z =
m^2+n^2=\\sqrt{a^2+b^2}](https://s0.wp.com/latex.php?latex=x+%3D%7Cbm-an%7C+%5C%5C%5B6pt%5D+y+%3D+am%2Bbn%5C%5C%5B6pt%5D+z+%3D+m%5E2%2Bn%5E2%3D%5Csqrt%7Ba%5E2%2Bb%5E2%7D&bg=ffffff&fg=333333&s=0
"x =|bm-an| \\\\[6pt] y = am+bn\\\\[6pt] z = m^2+n^2=\\sqrt{a^2+b^2}")

From ![\\S
4](https://s0.wp.com/latex.php?latex=%5CS+4&bg=ffffff&fg=333333&s=0
"\\S 4") we get:  
![x= |am-bn|\\\\\[6pt\] y= an+bm\\\\\[6pt\]
z=m^2+n^2=\\sqrt{a^2+b^2}](https://s0.wp.com/latex.php?latex=x%3D+%7Cam-bn%7C%5C%5C%5B6pt%5D+y%3D+an%2Bbm%5C%5C%5B6pt%5D+z%3Dm%5E2%2Bn%5E2%3D%5Csqrt%7Ba%5E2%2Bb%5E2%7D&bg=ffffff&fg=333333&s=0
"x= |am-bn|\\\\[6pt] y= an+bm\\\\[6pt] z=m^2+n^2=\\sqrt{a^2+b^2}")

For example, if we take
![z=5](https://s0.wp.com/latex.php?latex=z%3D5&bg=ffffff&fg=333333&s=0
"z=5"), we have ![m=1, \\; n= 2, \\; a=3, \\;
b=4](https://s0.wp.com/latex.php?latex=m%3D1%2C+%5C%3B+n%3D+2%2C+%5C%3B+a%3D3%2C+%5C%3B+b%3D4&bg=ffffff&fg=333333&s=0
"m=1, \\; n= 2, \\; a=3, \\; b=4"). From first set of expressions we get
![x=|4-6|=2, \\;
y=3+8=11](https://s0.wp.com/latex.php?latex=x%3D%7C4-6%7C%3D2%2C+%5C%3B+y%3D3%2B8%3D11&bg=ffffff&fg=333333&s=0
"x=|4-6|=2, \\; y=3+8=11"). From the second we get ![x=|3-8|=5; \\; y=
6+4=
10](https://s0.wp.com/latex.php?latex=x%3D%7C3-8%7C%3D5%3B+%5C%3B+y%3D+6%2B4%3D+10&bg=ffffff&fg=333333&s=0
"x=|3-8|=5; \\; y= 6+4= 10"). The second pair ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") is equivalent to what we can get via ![\\S
2](https://s0.wp.com/latex.php?latex=%5CS+2&bg=ffffff&fg=333333&s=0
"\\S 2"). Thus, when
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z") is
a 2 square prime its cube can be expressed as the sum of distinct two
pairs of squares.

Now, one can get a further set of
![z](https://s0.wp.com/latex.php?latex=z&bg=ffffff&fg=333333&s=0 "z")
corresponding to solutions with two pairs of ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") when say
![z=2p](https://s0.wp.com/latex.php?latex=z%3D2p&bg=ffffff&fg=333333&s=0
"z=2p") where
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") is
a
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") prime. Here ![z^3=2p \\cdot
(2p)^2](https://s0.wp.com/latex.php?latex=z%5E3%3D2p+%5Ccdot+%282p%29%5E2&bg=ffffff&fg=333333&s=0
"z^3=2p \\cdot (2p)^2"). From above we can write,

![p=m^2+n^2\\\\\[6pt\] \\therefore 2p=
(m+n)^2+(m-n)^2](https://s0.wp.com/latex.php?latex=p%3Dm%5E2%2Bn%5E2%5C%5C%5B6pt%5D+%5Ctherefore+2p%3D+%28m%2Bn%29%5E2%2B%28m-n%29%5E2&bg=ffffff&fg=333333&s=0
"p=m^2+n^2\\\\[6pt] \\therefore 2p= (m+n)^2+(m-n)^2")

Further,  
![p^2=a^2+b^2\\\\\[6pt\] \\therefore (2p)^2= (2a)^2+(2b)^2\\\\\[6pt\]
\\therefore z^3=
((m+n)^2+(m-n)^2)((2a)^2+(2b)^2)](https://s0.wp.com/latex.php?latex=p%5E2%3Da%5E2%2Bb%5E2%5C%5C%5B6pt%5D+%5Ctherefore+%282p%29%5E2%3D+%282a%29%5E2%2B%282b%29%5E2%5C%5C%5B6pt%5D+%5Ctherefore+z%5E3%3D+%28%28m%2Bn%29%5E2%2B%28m-n%29%5E2%29%28%282a%29%5E2%2B%282b%29%5E2%29&bg=ffffff&fg=333333&s=0
"p^2=a^2+b^2\\\\[6pt] \\therefore (2p)^2= (2a)^2+(2b)^2\\\\[6pt] \\therefore z^3= ((m+n)^2+(m-n)^2)((2a)^2+(2b)^2)")

Thus, from Brahmagupta’s identity we have:  
![x = 2a(m+n)-|2b(m-n)|\\\\\[6pt\] y =
2b(m+n)+|2a(m-n)|](https://s0.wp.com/latex.php?latex=x+%3D+2a%28m%2Bn%29-%7C2b%28m-n%29%7C%5C%5C%5B6pt%5D+y+%3D+2b%28m%2Bn%29%2B%7C2a%28m-n%29%7C&bg=ffffff&fg=333333&s=0
"x = 2a(m+n)-|2b(m-n)|\\\\[6pt] y = 2b(m+n)+|2a(m-n)|")

Alternatively,  
![x=2a(m+n)+|2b(m-n)|\\\\\[6pt\]
y=2b(m+n)-|2a(m-n)|](https://s0.wp.com/latex.php?latex=x%3D2a%28m%2Bn%29%2B%7C2b%28m-n%29%7C%5C%5C%5B6pt%5D+y%3D2b%28m%2Bn%29-%7C2a%28m-n%29%7C&bg=ffffff&fg=333333&s=0
"x=2a(m+n)+|2b(m-n)|\\\\[6pt] y=2b(m+n)-|2a(m-n)|")

For example, if ![z=26= 2 \\times
13](https://s0.wp.com/latex.php?latex=z%3D26%3D+2+%5Ctimes+13&bg=ffffff&fg=333333&s=0
"z=26= 2 \\times 13") then ![m=2, \\; n=3, \\; a=5, \\;
b=12](https://s0.wp.com/latex.php?latex=m%3D2%2C+%5C%3B+n%3D3%2C+%5C%3B+a%3D5%2C+%5C%3B+b%3D12&bg=ffffff&fg=333333&s=0
"m=2, \\; n=3, \\; a=5, \\; b=12"). Thus, ![x=74, \\;
y=110](https://s0.wp.com/latex.php?latex=x%3D74%2C+%5C%3B+y%3D110&bg=ffffff&fg=333333&s=0
"x=74, \\; y=110") or ![x=26, \\;
y=130](https://s0.wp.com/latex.php?latex=x%3D26%2C+%5C%3B+y%3D130&bg=ffffff&fg=333333&s=0
"x=26, \\; y=130"). Similarly, one can derive formulae for ![z=4p,
8p...](https://s0.wp.com/latex.php?latex=z%3D4p%2C+8p...&bg=ffffff&fg=333333&s=0
"z=4p, 8p...")

When ![z=p^2
=a^2+b^2](https://s0.wp.com/latex.php?latex=z%3Dp%5E2+%3Da%5E2%2Bb%5E2&bg=ffffff&fg=333333&s=0
"z=p^2 =a^2+b^2") where
![p=m^2+n^2](https://s0.wp.com/latex.php?latex=p%3Dm%5E2%2Bn%5E2&bg=ffffff&fg=333333&s=0
"p=m^2+n^2") is a
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") (2 square) prime we can show via repeated application of
Brahmagupta’s identity that there 3 possible
![x,y](https://s0.wp.com/latex.php?latex=x%2Cy&bg=ffffff&fg=333333&s=0
"x,y") pairs whose squares can compose
![z^3](https://s0.wp.com/latex.php?latex=z%5E3&bg=ffffff&fg=333333&s=0
"z^3"). We can derive the below formulae for them:  
![x=a^3+b^2a\\\\\[6pt\]
y=b^3+a^2b](https://s0.wp.com/latex.php?latex=x%3Da%5E3%2Bb%5E2a%5C%5C%5B6pt%5D+y%3Db%5E3%2Ba%5E2b&bg=ffffff&fg=333333&s=0
"x=a^3+b^2a\\\\[6pt] y=b^3+a^2b")

Or,  
![x=p(a^2-b^2)\\\\\[6pt\]
y=2pab](https://s0.wp.com/latex.php?latex=x%3Dp%28a%5E2-b%5E2%29%5C%5C%5B6pt%5D+y%3D2pab&bg=ffffff&fg=333333&s=0
"x=p(a^2-b^2)\\\\[6pt] y=2pab")

Or,  
![x= |m (b^2 n + 2 a b m - a^2 n ) - n | a^2m + 2 ab n - b^2 mb| |
\\\\\[6pt\] y= (a m - a n + b m + b n) (a m + a n - b m + b
n)](https://s0.wp.com/latex.php?latex=x%3D+%7Cm+%28b%5E2+n+%2B+2+a+b+m+-+a%5E2+n+%29+-+n+%7C+a%5E2m+%2B+2+ab+n+-+b%5E2+mb%7C+%7C+%5C%5C%5B6pt%5D+y%3D+%28a+m+-+a+n+%2B+b+m+%2B+b+n%29+%28a+m+%2B+a+n+-+b+m+%2B+b+n%29&bg=ffffff&fg=333333&s=0
"x= |m (b^2 n + 2 a b m - a^2 n ) - n | a^2m + 2 ab n - b^2 mb| | \\\\[6pt] y= (a m - a n + b m + b n) (a m + a n - b m + b n)")

As an example, by applying the above formulae we can see that for ![z=25
=
5^2](https://s0.wp.com/latex.php?latex=z%3D25+%3D+5%5E2&bg=ffffff&fg=333333&s=0
"z=25 = 5^2") its cube,
![25^3](https://s0.wp.com/latex.php?latex=25%5E3&bg=ffffff&fg=333333&s=0
"25^3"), can be split up into 3 distinct pairs of squares: ![35^2+120^2
= 44^2 + 117^2 = 75^2
+100^2](https://s0.wp.com/latex.php?latex=35%5E2%2B120%5E2+%3D+44%5E2+%2B+117%5E2+%3D+75%5E2+%2B100%5E2&bg=ffffff&fg=333333&s=0
"35^2+120^2 = 44^2 + 117^2 = 75^2 +100^2").

The nested combinatorial application of Brahmagupta’s formula can thus
result in increasingly complex formations with multiple alternative
partitions of a perfect cube into perfect squares for different
multiples of the 2 square primes. Thus if ![z=50=2 \\times
p^2](https://s0.wp.com/latex.php?latex=z%3D50%3D2+%5Ctimes+p%5E2&bg=ffffff&fg=333333&s=0
"z=50=2 \\times p^2") we get 4 distinct pairs of ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y"); for ![z=125= 5 \\times
5^2](https://s0.wp.com/latex.php?latex=z%3D125%3D+5+%5Ctimes+5%5E2&bg=ffffff&fg=333333&s=0
"z=125= 5 \\times 5^2") we get 5 distinct pairs of ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y").

When a number is product of two distinct
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") primes then its cube can be partitioned into 8 distinct pairs
perfect squares. For instance,  
![65^3= 7^2 + 524^2 = 65^2+ 520^2 = 140^2 + 505^2 = 191^2 + 488^2= 208^2
+ 481^2 = 260^2+ 455^2= 320^2+ 415^2 = 364^2+
377^2](https://s0.wp.com/latex.php?latex=65%5E3%3D+7%5E2+%2B+524%5E2+%3D+65%5E2%2B+520%5E2+%3D+140%5E2+%2B+505%5E2+%3D+191%5E2+%2B+488%5E2%3D+208%5E2+%2B+481%5E2+%3D+260%5E2%2B+455%5E2%3D+320%5E2%2B+415%5E2+%3D+364%5E2%2B+377%5E2&bg=ffffff&fg=333333&s=0
"65^3= 7^2 + 524^2 = 65^2+ 520^2 = 140^2 + 505^2 = 191^2 + 488^2= 208^2 + 481^2 = 260^2+ 455^2= 320^2+ 415^2 = 364^2+ 377^2")  
The same applies to the multiples of these numbers by 2, 4… When a
number is a product of a
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") prime and the square of a distinct
![4n+1](https://s0.wp.com/latex.php?latex=4n%2B1&bg=ffffff&fg=333333&s=0
"4n+1") prime then the cube of that number can be partitioned into 14
different pairs of perfect squares. Thus, ![325=5^2 \\times
13](https://s0.wp.com/latex.php?latex=325%3D5%5E2+%5Ctimes+13&bg=ffffff&fg=333333&s=0
"325=5^2 \\times 13") is the first number whose cube can be thus
partitioned. The next is ![425 = 5^2 \\times
17](https://s0.wp.com/latex.php?latex=425+%3D+5%5E2+%5Ctimes+17&bg=ffffff&fg=333333&s=0
"425 = 5^2 \\times 17"). Figure 3 shows some circles with multiple pairs
of ![x,
y](https://s0.wp.com/latex.php?latex=x%2C+y&bg=ffffff&fg=333333&s=0
"x, y") whose squares sum to the same
![z^3](https://s0.wp.com/latex.php?latex=z%5E3&bg=ffffff&fg=333333&s=0
"z^3").

[![sqrs\_cube\_xy\_Fig3](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xy_fig3.png?w=646&h=540)](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xy_fig3.png)Figure
3

Ramanujan and Landau had independently discovered that the number of
positive integers, ![N(x) \\le
x](https://s0.wp.com/latex.php?latex=N%28x%29+%5Cle+x&bg=ffffff&fg=333333&s=0
"N(x) \\le x"), that can be written as a sum of 2 squares including 0
defines a constant:

![\\displaystyle K\_{RL} = \\lim\_{x \\to \\infty}
N(x)\\dfrac{\\sqrt{\\log(x)}}{x} =
0.7642236535...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle+K_%7BRL%7D+%3D+%5Clim_%7Bx+%5Cto+%5Cinfty%7D+N%28x%29%5Cdfrac%7B%5Csqrt%7B%5Clog%28x%29%7D%7D%7Bx%7D+%3D+0.7642236535...&bg=ffffff&fg=333333&s=0
"\\displaystyle K_{RL} = \\lim_{x \\to \\infty} N(x)\\dfrac{\\sqrt{\\log(x)}}{x} = 0.7642236535...")

Based on this, we can also look at how many unique ![z \\le
x](https://s0.wp.com/latex.php?latex=z+%5Cle+x&bg=ffffff&fg=333333&s=0
"z \\le x"), i.e.
![N(z)](https://s0.wp.com/latex.php?latex=N%28z%29&bg=ffffff&fg=333333&s=0
"N(z)") by defining:

![K=N(z)\\dfrac{\\sqrt{\\log(x)}}{x}](https://s0.wp.com/latex.php?latex=K%3DN%28z%29%5Cdfrac%7B%5Csqrt%7B%5Clog%28x%29%7D%7D%7Bx%7D&bg=ffffff&fg=333333&s=0
"K=N(z)\\dfrac{\\sqrt{\\log(x)}}{x}")

We empirically observe that this ![K \\approx
0.8071](https://s0.wp.com/latex.php?latex=K+%5Capprox+0.8071&bg=ffffff&fg=333333&s=0
"K \\approx 0.8071") (Figure 4). The
![K\_{RL}](https://s0.wp.com/latex.php?latex=K_%7BRL%7D&bg=ffffff&fg=333333&s=0
"K_{RL}") has a closed form which has deep connections to the Riemann
![\\zeta(x)](https://s0.wp.com/latex.php?latex=%5Czeta%28x%29&bg=ffffff&fg=333333&s=0
"\\zeta(x)") and the Dirichlet
![\\beta(x)](https://s0.wp.com/latex.php?latex=%5Cbeta%28x%29&bg=ffffff&fg=333333&s=0
"\\beta(x)"). However, we are not aware of a closed form for the
constant
![K](https://s0.wp.com/latex.php?latex=K&bg=ffffff&fg=333333&s=0 "K") in
our case or even its exact value as ![x \\to
\\infty](https://s0.wp.com/latex.php?latex=x+%5Cto+%5Cinfty&bg=ffffff&fg=333333&s=0
"x \\to \\infty"). This
![K](https://s0.wp.com/latex.php?latex=K&bg=ffffff&fg=333333&s=0 "K")
seems to reach a fairly stable value around that reported above but
![K\_{RL}](https://s0.wp.com/latex.php?latex=K_%7BRL%7D&bg=ffffff&fg=333333&s=0
"K_{RL}") converges very slowly.

[![sqrs\_cube\_RL\_Fig4](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_rl_fig4.png?w=626&h=456)](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_rl_fig4.png)Figure
4

**Solution families on curves**  
In addition to the arrangement of solutions as lattice points on circle
of radius
![z^{3/2}](https://s0.wp.com/latex.php?latex=z%5E%7B3%2F2%7D&bg=ffffff&fg=333333&s=0
"z^{3/2}"), there are also other patterns that become apparent from a
closer look at the solutions in the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0
"x-y") plane (Figure 2). The most obvious is the set of points lying on
the
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") line at the right diagonal boundary of the plot. These are
defined by a family of the form:

![x= y =2n^3; \\; z=
2n^2](https://s0.wp.com/latex.php?latex=x%3D+y+%3D2n%5E3%3B+%5C%3B+z%3D+2n%5E2&bg=ffffff&fg=333333&s=0
"x= y =2n^3; \\; z= 2n^2")

This family defines the sequence of integers twice whose square equals a
perfect cube: **2, 16, 54, 128, 250, 432, 686, 1024 …** (blue line in
Figure 3).

Then we see pairs of regularly positioned points that eventually lie
closer to the right diagonal boundary (emphasized in red and blue in
Figure 3). These are families that lie on one of two parallel curves.
The first is defined by the parametric equations:

![x = 2t^3 + 6t^2 + 3t - 2 \\\\\[6pt\] y = 2t^3 + 12t^2 + 21t +
11](https://s0.wp.com/latex.php?latex=x+%3D+2t%5E3+%2B+6t%5E2+%2B+3t+-+2+%5C%5C%5B6pt%5D+y+%3D+2t%5E3+%2B+12t%5E2+%2B+21t+%2B+11&bg=ffffff&fg=333333&s=0
"x = 2t^3 + 6t^2 + 3t - 2 \\\\[6pt] y = 2t^3 + 12t^2 + 21t + 11")

This curve has a lobe (Figure 5; gray) and generally resembles the shape
of the curve of von Tschirnhaus (see below). The second curve takes the
form:

![x=2t^3+6t^2+9t\\\\\[6pt\]
y=2t^3+12t^2+27t+27](https://s0.wp.com/latex.php?latex=x%3D2t%5E3%2B6t%5E2%2B9t%5C%5C%5B6pt%5D+y%3D2t%5E3%2B12t%5E2%2B27t%2B27&bg=ffffff&fg=333333&s=0
"x=2t^3+6t^2+9t\\\\[6pt] y=2t^3+12t^2+27t+27")

This curve has no lobe and lies inside the divergent arms of the first
one (Figure 5; dark orange).

[![sqrs\_cube\_xyz\_Fig5](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xyz_fig5.png?w=543&h=492)](https://manasataramgini.files.wordpress.com/2020/02/sqrs_cube_xyz_fig5.png)Figure
5

A further family lies on the curve defined by the below parametric
equations (emphasized in red in Figure 3):

![x=3t^2-1\\\\\[6pt\]
y=t^3-3t](https://s0.wp.com/latex.php?latex=x%3D3t%5E2-1%5C%5C%5B6pt%5D+y%3Dt%5E3-3t&bg=ffffff&fg=333333&s=0
"x=3t^2-1\\\\[6pt] y=t^3-3t")

This curve has a single lobe and two divergent arms (Figure 5, light
orange) and is a version of the eponymous curve discovered by Ehrenfried
Walther von Tschirnhaus, the famous German polymath, who among other
things reinvented porcelain in the Occident. It crosses over the above
two curves and proceeds closer to the vertical left boundary of the
![x-y](https://s0.wp.com/latex.php?latex=x-y&bg=ffffff&fg=333333&s=0
"x-y") plot.

Finally, we a family of families lying on the family of curves (shown in
blue in Figures 3, 5) defined by the parametric equations:

![x=kt^2 + k^3\\\\\[6pt\] y= t^3 +
k^2t](https://s0.wp.com/latex.php?latex=x%3Dkt%5E2+%2B+k%5E3%5C%5C%5B6pt%5D+y%3D+t%5E3+%2B+k%5E2t&bg=ffffff&fg=333333&s=0
"x=kt^2 + k^3\\\\[6pt] y= t^3 + k^2t"),  
where ![k=1, 2, 3
...](https://s0.wp.com/latex.php?latex=k%3D1%2C+2%2C+3+...&bg=ffffff&fg=333333&s=0
"k=1, 2, 3 ...")

The first member of each of the new families on this family of curves
starts from where the curve intersect the
![y=x](https://s0.wp.com/latex.php?latex=y%3Dx&bg=ffffff&fg=333333&s=0
"y=x") line. Thus, each starts with the points
![x=y=2k^3](https://s0.wp.com/latex.php?latex=x%3Dy%3D2k%5E3&bg=ffffff&fg=333333&s=0
"x=y=2k^3") (Figure 3). The first of this gives yields the answer to the
second question posed in the introduction. When the square of
![x=n^2+1](https://s0.wp.com/latex.php?latex=x%3Dn%5E2%2B1&bg=ffffff&fg=333333&s=0
"x=n^2+1") is added to the square of
![y=n^3+n](https://s0.wp.com/latex.php?latex=y%3Dn%5E3%2Bn&bg=ffffff&fg=333333&s=0
"y=n^3+n") we get the cube of
![z=n^2+1](https://s0.wp.com/latex.php?latex=z%3Dn%5E2%2B1&bg=ffffff&fg=333333&s=0
"z=n^2+1"), i.e.
![x=z](https://s0.wp.com/latex.php?latex=x%3Dz&bg=ffffff&fg=333333&s=0
"x=z"). It remains unknown to us if there are any further families
beyond these.
