+++
title = "A layman’s overview of the arithmetic of encryption"

+++
**Life as an encryption-decryption cycle**  
Encryption is a concept as old as life itself. The sequence of proteins,
the primary purveyors of function in life as we know it, is encrypted
within nucleic acids. It is decrypted by this remarkable machine known
as the ribosome along with tRNAs, whose origin lie close to the origin
of life itself. The encryption itself is relatively simple with a 4
symbol nucleic acid alphabet encoding a (usually) 20 symbol protein
alphabet. This is done by having three letter words in the nucleic acid
alphabet specify 1 letter in the protein alphabet. Thus, with a four
letter alphabet one has ![4 \\times 4 \\times 4
=64](https://s0.wp.com/latex.php?latex=4+%5Ctimes+4+%5Ctimes+4+%3D64&bg=ffffff&fg=333333&s=0
"4 \\times 4 \\times 4 =64") words with 3 letters in the nucleic acid
alphabet to specific just 20 letters in the protein alphabet. Thus, this
encoding system necessarily has degeneracy, meaning multiple 3-letter
words in the nucleic acid alphabet encode the same letter in the protein
alphabet, e.g. ![(TTT, TTC) \\rightarrow F; (CGT, CGC, CGA, CGG, AGA,
AGG) \\rightarrow
R](https://s0.wp.com/latex.php?latex=%28TTT%2C+TTC%29+%5Crightarrow+F%3B+%28CGT%2C+CGC%2C+CGA%2C+CGG%2C+AGA%2C+AGG%29+%5Crightarrow+R&bg=ffffff&fg=333333&s=0
"(TTT, TTC) \\rightarrow F; (CGT, CGC, CGA, CGG, AGA, AGG) \\rightarrow R").
In addition, some of these 3-letter nucleic acid words encode a stop of
the protein-word, i.e. the end of the protein sequence: usually ![(UAA,
UAG, UGA) \\rightarrow
STOP](https://s0.wp.com/latex.php?latex=%28UAA%2C+UAG%2C+UGA%29+%5Crightarrow+STOP&bg=ffffff&fg=333333&s=0
"(UAA, UAG, UGA) \\rightarrow STOP").

**Encryption by humans**  
In terms of human language, encrypting messages is probably as old as
human language itself. The rest of this note is about how one of the
most important modern forms of human encryption and decryption is
carried out. What we are going to talk about in here is nothing original
or new. One can find accounts of it in books dealing with higher
arithmetic (like I first did) or on the internet. However, when we first
learned of it in our youth, at least in our circles, it was not very
well-known. We were so charmed by it then that we eagerly demonstrated
it to a friend and acquaintances who suffered the outpourings of our
meditations. About 28 years since that time, a gentleman asked me why
prime numbers had any value at all and I explained this encryption
mechanism to him. Hence, I thought I would record it, as I often record
private teaching devices I might have used. Again, I must reiterate,
this is not an area of my expertise. I am simply recording the beautiful
mathematical device it uses in simplified form and in lay language
without much of the jargon specific to this subject.

Encryption, however complex, has depended on using some form of key.
This key was quite literally like the “Rosetta Stone”, which had allowed
the decoding of the old Egyptian writing. With complex encodings, if the
key is lost then decoding of the encrypted message can be difficult. The
Harappan script is one such example, which has no such Rosetta Stone,
and it is likely that the language which it encoded is largely lost;
hence, we cannot make sense of what is encoded in its strings of
symbols. In any case, the idea of the key can be simply illustrated. Say
we take the key to be
![k=13](https://s0.wp.com/latex.php?latex=k%3D13&bg=ffffff&fg=333333&s=0
"k=13"), the language to be English, the script to be standard Roman and
the basic numerical encoding to be of the form ![a \\equiv 1; b \\equiv
2; c \\equiv 3 ... z\\equiv
26](https://s0.wp.com/latex.php?latex=a+%5Cequiv+1%3B+b+%5Cequiv+2%3B+c+%5Cequiv+3+...+z%5Cequiv+26&bg=ffffff&fg=333333&s=0
"a \\equiv 1; b \\equiv 2; c \\equiv 3 ... z\\equiv 26"). Let us say we
want to use our key to encode the message “kill tonight”. Then we first
write the numerical equivalent of “kill tonight” without space between
the words: 11 9 12 12 20 15 14 9 7 8 20. Then we multiply each letter by
the key
![k=13](https://s0.wp.com/latex.php?latex=k%3D13&bg=ffffff&fg=333333&s=0
"k=13") to get: 143 117 156 156 260 195 182 117 91 104 260. This is our
encrypted message. Anyone with the key can decode this message by
reversing the procedure i.e. by division. The general version of
technique gūḍha-yojya in Hindu cryptographic tradition. Of course this
is a simple encryption. In addition to anyone who gets the key by some
means, it might also be broken quite easily by an amateur code-breaker.

One can also imagine a slightly more complex encryption such as this:

1\) The message to be encrypted is the same: “kill tonight” written
without spaces as “killtonight”.

2\) We choose a keyword, let us say “mrtyu” and repeat it as many times
as to cover the message to encode:

    killtonight
    mrtyumrtyum

This latter word is the transformer.

3\) We then convert “killtonight” to its direct numeric equivalent as
described in the earlier example: 11 9 12 12 20 15 14 9 7 8 20.
Likewise, we convert the transformer into its numeric equivalent: 13 18
20 25 21 13 18 20 25 21 13.

4\) We then add the each number of the message to be encoded to the
corresponding number in the transformer to get the coding: 24 27 32 37
41 28 32 29 32 29 33.

5\) We then subtract 26 from all those numbers in this coding that are
greater than 26. Thus we get: 24 1 6 11 15 2 6 3 6 3 7.

6\) We then convert it back to letters to get our encrypted message:
“xafkobfcfcg”.

This is a more serious encoding and would need more effort to break
unless one gets hold of the keyword by some means. Then one can use the
keyword to reverse the procedure and get the original message.

**Diffie, Hellman and Merkle**  
While the above two examples differ considerably in their complexity and
difficulty in terms of being broken by a code-breaker, they still share
a common feature, namely symmetry: both the sender of the encrypted
message and its intended receiver need to have same key and keyword.
That they have to somehow share this secret is the primary problem of
this form of encryption. If the key is intercepted while being shared
then the interceptor can read all the messages between the sender and
the intended receiver. This would mean that the key should be changed
from time to time but multiple changes only mean multiple key transfers
which could result in further susceptibility to interception. Further,
if there are multiple people in the network of encrypted information
sharing it might increase the vulnerability of the key to being
intercepted or it would impose the problem of managing the sharing of a
large number of distinct keys. This remained the situation from the
beginning of human encryption until the mid-1970s when Diffie, Hellman
and Merkle showed that in principle it was possible to use a
mathematical trick for two or more communicating parties to arrive at a
common encryption key without having to share it. Thus, the sender and
the receiver need not transmit a shared secret key. All they have to do
is to share a public key, which by itself does not reveal to the
interceptor the secret key they use to encrypt or decrypt message. The
secret key used for encryption is not transmitted but is independently
derived on either side from the information shared by the interlocutors
and an asymmetric private key that is never shared with anyone.

The basic idea of Diffie, Hellman and Merkle depends on an arithmetic
concept known as the primitive root modulo of a prime number
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p"):
for an integer
![g\<p](https://s0.wp.com/latex.php?latex=g%3Cp&bg=ffffff&fg=333333&s=0
"g\<p") if one obtains every integer from ![n=1, 2,3 ...
p-1](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C3+...+p-1&bg=ffffff&fg=333333&s=0
"n=1, 2,3 ... p-1") when one takes the modulo to
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") of
all
![g^m](https://s0.wp.com/latex.php?latex=g%5Em&bg=ffffff&fg=333333&s=0
"g^m"), where
![m=0,1,2...p-1](https://s0.wp.com/latex.php?latex=m%3D0%2C1%2C2...p-1&bg=ffffff&fg=333333&s=0
"m=0,1,2...p-1"), then
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g") is
the primitive root modulo
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p").
As an example consider
![p=11](https://s0.wp.com/latex.php?latex=p%3D11&bg=ffffff&fg=333333&s=0
"p=11") and
![g=2](https://s0.wp.com/latex.php?latex=g%3D2&bg=ffffff&fg=333333&s=0
"g=2"), then we have:  
![2^0 \\mod 11 = 2^{10} \\mod 11=1; 2^1 \\mod 11=2; 2^2 \\mod 11= 4; 2^3
\\mod 11=8; 2^4 \\mod 11= 5; 2^5 \\mod 11= 10; 2^6 \\mod 11= 9; 2^7
\\mod 11= 7; 2^8 \\mod 11= 3; 2^9 \\mod 11=
6](https://s0.wp.com/latex.php?latex=2%5E0+%5Cmod+11+%3D+2%5E%7B10%7D+%5Cmod+11%3D1%3B+2%5E1+%5Cmod+11%3D2%3B+2%5E2+%5Cmod+11%3D+4%3B+2%5E3+%5Cmod+11%3D8%3B+2%5E4+%5Cmod+11%3D+5%3B+2%5E5+%5Cmod+11%3D+10%3B+2%5E6+%5Cmod+11%3D+9%3B+2%5E7+%5Cmod+11%3D+7%3B+2%5E8+%5Cmod+11%3D+3%3B+2%5E9+%5Cmod+11%3D+6&bg=ffffff&fg=333333&s=0
"2^0 \\mod 11 = 2^{10} \\mod 11=1; 2^1 \\mod 11=2; 2^2 \\mod 11= 4; 2^3 \\mod 11=8; 2^4 \\mod 11= 5; 2^5 \\mod 11= 10; 2^6 \\mod 11= 9; 2^7 \\mod 11= 7; 2^8 \\mod 11= 3; 2^9 \\mod 11= 6").  
Thus, we get all the numbers ![n=1, 2,
3...10](https://s0.wp.com/latex.php?latex=n%3D1%2C+2%2C+3...10&bg=ffffff&fg=333333&s=0
"n=1, 2, 3...10") for the operation ![2^m \\mod
11](https://s0.wp.com/latex.php?latex=2%5Em+%5Cmod+11&bg=ffffff&fg=333333&s=0
"2^m \\mod 11") for ![m=0, 1,
2...10](https://s0.wp.com/latex.php?latex=m%3D0%2C+1%2C+2...10&bg=ffffff&fg=333333&s=0
"m=0, 1, 2...10"). Hence, 2 is a primitive root modulo 11.

To use this to derive an encryption key, without directly transmitting
it, the following operation is performed. Let us call the two men who
wish to exchange encrypted messages as K and C.

1\) First K and C share a public key in the form of prime number say
![p=37](https://s0.wp.com/latex.php?latex=p%3D37&bg=ffffff&fg=333333&s=0
"p=37") and one of its primitive roots
![g=5](https://s0.wp.com/latex.php?latex=g%3D5&bg=ffffff&fg=333333&s=0
"g=5").

2\) Then K selects a secret integer say
![a=7](https://s0.wp.com/latex.php?latex=a%3D7&bg=ffffff&fg=333333&s=0
"a=7") and transmits ![A=g^a \\mod
p](https://s0.wp.com/latex.php?latex=A%3Dg%5Ea+%5Cmod+p&bg=ffffff&fg=333333&s=0
"A=g^a \\mod p"), i.e. ![A=5^7 \\mod 37 =
18](https://s0.wp.com/latex.php?latex=A%3D5%5E7+%5Cmod+37+%3D+18&bg=ffffff&fg=333333&s=0
"A=5^7 \\mod 37 = 18") to C.

3\) Likewise C selects a secret integer say
![b=3](https://s0.wp.com/latex.php?latex=b%3D3&bg=ffffff&fg=333333&s=0
"b=3") and transmits ![B=g^b \\mod
p](https://s0.wp.com/latex.php?latex=B%3Dg%5Eb+%5Cmod+p&bg=ffffff&fg=333333&s=0
"B=g^b \\mod p"), i.e. ![B=5^3 \\mod
37=14](https://s0.wp.com/latex.php?latex=B%3D5%5E3+%5Cmod+37%3D14&bg=ffffff&fg=333333&s=0
"B=5^3 \\mod 37=14") to K .

4\) Thus, one notices that K and C have not exchanged the same
information beyond the public key. However they can use the numbers they
have exchanged for the following computation on either side: K computes
![k=B^a \\mod
p](https://s0.wp.com/latex.php?latex=k%3DB%5Ea+%5Cmod+p&bg=ffffff&fg=333333&s=0
"k=B^a \\mod p"), i.e. ![k=14^7 \\mod 37=105413504 \\mod 37
=23](https://s0.wp.com/latex.php?latex=k%3D14%5E7+%5Cmod+37%3D105413504+%5Cmod+37+%3D23&bg=ffffff&fg=333333&s=0
"k=14^7 \\mod 37=105413504 \\mod 37 =23"). Similarly, C computes ![k=A^b
\\mod
p](https://s0.wp.com/latex.php?latex=k%3DA%5Eb+%5Cmod+p&bg=ffffff&fg=333333&s=0
"k=A^b \\mod p"), i.e. ![k=18^3 \\mod 37 = 5832 \\mod 37 =
23](https://s0.wp.com/latex.php?latex=k%3D18%5E3+%5Cmod+37+%3D+5832+%5Cmod+37+%3D+23&bg=ffffff&fg=333333&s=0
"k=18^3 \\mod 37 = 5832 \\mod 37 = 23"). Thus, now both K and C are in
possession of a common key
![k=23](https://s0.wp.com/latex.php?latex=k%3D23&bg=ffffff&fg=333333&s=0
"k=23"), which they can use for encryption by some means without ever
having shared it directly. The logic behind this is simple: The
computation they perform on their respective sides results in ![k=g^{ab}
\\mod p = g^{ba} \\mod
p](https://s0.wp.com/latex.php?latex=k%3Dg%5E%7Bab%7D+%5Cmod+p+%3D+g%5E%7Bba%7D+%5Cmod+p&bg=ffffff&fg=333333&s=0
"k=g^{ab} \\mod p = g^{ba} \\mod p").

Now, a snoop (let us call him R) will be in possession of the public key
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p")
and ![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0
"g") used by K and C. R will also be able to intercept the numbers
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
and ![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0
"B") that K and C exchanged just as any worthy snoop would do. With
these numbers would R be able to determine
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") or
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b"),
which is what he would need to get hold of the encryption key? Given the
prime ![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0
"p"), ![g^x \\mod
p](https://s0.wp.com/latex.php?latex=g%5Ex+%5Cmod+p&bg=ffffff&fg=333333&s=0
"g^x \\mod p") can assume a value
![1..p-1](https://s0.wp.com/latex.php?latex=1..p-1&bg=ffffff&fg=333333&s=0
"1..p-1"), one of which will
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A") or
![B](https://s0.wp.com/latex.php?latex=B&bg=ffffff&fg=333333&s=0 "B").
In our example with
![p=37](https://s0.wp.com/latex.php?latex=p%3D37&bg=ffffff&fg=333333&s=0
"p=37") it can assume a value 1..36. R will have to find out plugging in
which ![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x") in the operation ![g^x \\mod
p](https://s0.wp.com/latex.php?latex=g%5Ex+%5Cmod+p&bg=ffffff&fg=333333&s=0
"g^x \\mod p") would yield
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A").
That ![x](https://s0.wp.com/latex.php?latex=x&bg=ffffff&fg=333333&s=0
"x") will be
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"),
which was secretly used by K. Likewise for
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b").
This problem is known as the discrete logarithm problem. In our example,
since there are only 36 values to check, R could simply figure out
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") or
![b](https://s0.wp.com/latex.php?latex=b&bg=ffffff&fg=333333&s=0 "b")
through brute force and nearly instantaneously on a modern computer.
However, note the following: The sequence of ![5^{0..36} \\mod
37](https://s0.wp.com/latex.php?latex=5%5E%7B0..36%7D+%5Cmod+37&bg=ffffff&fg=333333&s=0
"5^{0..36} \\mod 37") is plotted in the first panel of Figure 1. In the
second panel we plot ![5^{0..107} \\mod
107](https://s0.wp.com/latex.php?latex=5%5E%7B0..107%7D+%5Cmod+107&bg=ffffff&fg=333333&s=0
"5^{0..107} \\mod 107") where
![p=107](https://s0.wp.com/latex.php?latex=p%3D107&bg=ffffff&fg=333333&s=0
"p=107") is a safe prime. Similarly, we also plot the sequences of one
of their respective primitive roots
![g](https://s0.wp.com/latex.php?latex=g&bg=ffffff&fg=333333&s=0 "g")
raised to all
![n=0..p-1](https://s0.wp.com/latex.php?latex=n%3D0..p-1&bg=ffffff&fg=333333&s=0
"n=0..p-1") modulo
![p=113](https://s0.wp.com/latex.php?latex=p%3D113&bg=ffffff&fg=333333&s=0
"p=113") a Sophie Germain prime and modulo
![p=127](https://s0.wp.com/latex.php?latex=p%3D127&bg=ffffff&fg=333333&s=0
"p=127") a Mersenne prime.

[![RSA\_Fig1\_primroot\_pow\_modp](https://manasataramgini.files.wordpress.com/2018/10/rsa_fig1_primroot_pow_modp.png?w=640)](https://manasataramgini.files.wordpress.com/2018/10/rsa_fig1_primroot_pow_modp.png)Figure
1.

We observe that the sequences of ![g^n \\mod
p](https://s0.wp.com/latex.php?latex=g%5En+%5Cmod+p&bg=ffffff&fg=333333&s=0
"g^n \\mod p") for each of the primes has a great deal of irregularity
and appears to be mostly random. Thus, there is no pattern to where the
![A](https://s0.wp.com/latex.php?latex=A&bg=ffffff&fg=333333&s=0 "A")
derived from a given
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a")
might be found be found. This illustrates nature of the discrete
logarithm problem: there is currently no effective method to solve it
and it is not even known if any effective method can be devised in
principle. As such, one essentially needs to search much of the space of
![g^n \\mod
p](https://s0.wp.com/latex.php?latex=g%5En+%5Cmod+p&bg=ffffff&fg=333333&s=0
"g^n \\mod p") for a prime
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") to
find a solution. Thus, rather than
![p=37](https://s0.wp.com/latex.php?latex=p%3D37&bg=ffffff&fg=333333&s=0
"p=37") if one were to use an enormous prime then there is no effective
method to solve the problem of finding
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"),
given ![A, g,
p](https://s0.wp.com/latex.php?latex=A%2C+g%2C+p&bg=ffffff&fg=333333&s=0
"A, g, p") in sufficient time. For example, 512 bit. i.e. 154..155 digit
decimal base primes were widely used. However, it was recently shown
that by precomputing and storing all ![g^n \\mod
p](https://s0.wp.com/latex.php?latex=g%5En+%5Cmod+p&bg=ffffff&fg=333333&s=0
"g^n \\mod p") for some widely reused primes (an expensive and
time-consuming operation) encryption based on them might be compromised.
It is also believed that given the resources of the 5-eyes mleccha-s
together with the prathamonmatta-s, their praṇidhi-s have similarly
broken through the even stronger commonly used 1024 bit i.e. 308..309
digit primes through expensive pre-computation.

Just for the feel of it here is a 155 digit number that is probably a
prime just to give you a sense of how many values one would need to
search to break encryption based on such a
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p"):  
`10000000000000000369475456880582265409809179829842688451922778552150543659 347219597216513109705408327446511753687232667314337003349573404171046192448274699`  
**Rivest, Shamir and Adleman**  
In the year following Diffie and Hellman’s publication, Rivest, Shamir
and Adleman published their asymmetric public private key system, which
again uses a clever mathematical device. We outline below with a mock
example the idea behind what is now famous as the RSA system:

1\) As usual consider the two interlocutors K and C. One of them, say K,
selects two primes
![p\_1](https://s0.wp.com/latex.php?latex=p_1&bg=ffffff&fg=333333&s=0
"p_1") and
![p\_2](https://s0.wp.com/latex.php?latex=p_2&bg=ffffff&fg=333333&s=0
"p_2"). In our mock example we shall take
![p\_1=37](https://s0.wp.com/latex.php?latex=p_1%3D37&bg=ffffff&fg=333333&s=0
"p_1=37") and
![p\_2=47](https://s0.wp.com/latex.php?latex=p_2%3D47&bg=ffffff&fg=333333&s=0
"p_2=47"). K multiplies the two to get
![p\_k=p\_1p\_2=1739](https://s0.wp.com/latex.php?latex=p_k%3Dp_1p_2%3D1739&bg=ffffff&fg=333333&s=0
"p_k=p_1p_2=1739").

2\) K then calculates
![p\_l=(p\_1-1)(p\_2-1)=1656](https://s0.wp.com/latex.php?latex=p_l%3D%28p_1-1%29%28p_2-1%29%3D1656&bg=ffffff&fg=333333&s=0
"p_l=(p_1-1)(p_2-1)=1656"). He then chooses a number which is mutually
prime with 1656, let us say
![q=5](https://s0.wp.com/latex.php?latex=q%3D5&bg=ffffff&fg=333333&s=0
"q=5"). He then shares ![p\_k,
q](https://s0.wp.com/latex.php?latex=p_k%2C+q&bg=ffffff&fg=333333&s=0
"p_k, q") as the public key with C.

3\) C can now use this information to encrypt a number
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k")
(for example a key to be shared for future communication) and send it to
K. For our example we will take
![k=24](https://s0.wp.com/latex.php?latex=k%3D24&bg=ffffff&fg=333333&s=0
"k=24"). What C does is to compute ![a= k^q \\mod p\_k= 24^5 \\mod
1739=1482](https://s0.wp.com/latex.php?latex=a%3D+k%5Eq+%5Cmod+p_k%3D+24%5E5+%5Cmod+1739%3D1482&bg=ffffff&fg=333333&s=0
"a= k^q \\mod p_k= 24^5 \\mod 1739=1482") and send
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") to
K.
![a=1482](https://s0.wp.com/latex.php?latex=a%3D1482&bg=ffffff&fg=333333&s=0
"a=1482") is the encrypted information sent by C to K

4\) To decrypt
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a"), K
has to do the following computation. He has to first find a number
![d](https://s0.wp.com/latex.php?latex=d&bg=ffffff&fg=333333&s=0 "d")
such that ![qd \\mod p\_l=
1](https://s0.wp.com/latex.php?latex=qd+%5Cmod+p_l%3D+1&bg=ffffff&fg=333333&s=0
"qd \\mod p_l= 1"). This means we have to find some integer
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
such that we get an integer solution
![d=\\tfrac{np\_l+1}{q}](https://s0.wp.com/latex.php?latex=d%3D%5Ctfrac%7Bnp_l%2B1%7D%7Bq%7D&bg=ffffff&fg=333333&s=0
"d=\\tfrac{np_l+1}{q}"). In our case K has to solve ![5l \\mod 1656
=1](https://s0.wp.com/latex.php?latex=5l+%5Cmod+1656+%3D1&bg=ffffff&fg=333333&s=0
"5l \\mod 1656 =1"). Since 1656 ends in 6 if he multiplies it by 4 and
adds 1 to the result he will get a number divisible by
![q=5](https://s0.wp.com/latex.php?latex=q%3D5&bg=ffffff&fg=333333&s=0
"q=5"). Thus he gets
![d=1325](https://s0.wp.com/latex.php?latex=d%3D1325&bg=ffffff&fg=333333&s=0
"d=1325").

5\) Next K has to compute ![a^d \\mod
p\_k](https://s0.wp.com/latex.php?latex=a%5Ed+%5Cmod+p_k&bg=ffffff&fg=333333&s=0
"a^d \\mod p_k") to decode the encrypted number C has sent him. In our
example that will be ![1482^{1325} \\mod
1739](https://s0.wp.com/latex.php?latex=1482%5E%7B1325%7D+%5Cmod+1739&bg=ffffff&fg=333333&s=0
"1482^{1325} \\mod 1739"). This looks like a daunting thing to do but it
can be broken by the following trick. First one writes
![d=1325](https://s0.wp.com/latex.php?latex=d%3D1325&bg=ffffff&fg=333333&s=0
"d=1325") in terms of powers of 2:

![1325=1024 + 256 + 32 + 8 + 4 + 1\\\\\[10pt\] \\therefore 1482^{1325}
=1482^{1024 + 256 + 32 + 8 + 4 + 1} = 1482^{1024} \\times
1482^{256}\\times 1482^{32} \\times 1482^{8} \\times 1482^{4} \\times
1482^{1}](https://s0.wp.com/latex.php?latex=1325%3D1024+%2B+256+%2B+32+%2B+8+%2B+4+%2B+1%5C%5C%5B10pt%5D++%5Ctherefore+1482%5E%7B1325%7D+%3D1482%5E%7B1024+%2B+256+%2B+32+%2B+8+%2B+4+%2B+1%7D+%3D+1482%5E%7B1024%7D+%5Ctimes+1482%5E%7B256%7D%5Ctimes+1482%5E%7B32%7D+%5Ctimes+1482%5E%7B8%7D+%5Ctimes+1482%5E%7B4%7D+%5Ctimes+1482%5E%7B1%7D&bg=ffffff&fg=333333&s=0
"1325=1024 + 256 + 32 + 8 + 4 + 1\\\\[10pt]  \\therefore 1482^{1325} =1482^{1024 + 256 + 32 + 8 + 4 + 1} = 1482^{1024} \\times 1482^{256}\\times 1482^{32} \\times 1482^{8} \\times 1482^{4} \\times 1482^{1}")

Since modulo is multiplicative we then take modulo by parts:

![1482 \\mod 1739 =1482\\\\ 1482^4 \\mod 1739 =1089\\\\ 1482^8=1482^4
\\times 1482^4 \\mod 1739 =(1089 \\times 1089) \\mod 1739 = 1662\\\\
1482^{32}= (1482^8)^4 \\mod 1739 = 1662^4 \\mod 1739 = 895\\\\
1482^{256}=(1482^{32})^8 \\mod 1739 = (895^4 \\times 895^4 ) \\mod 1739
=(1661 \\times 1661) \\mod 1739=867\\\\ 1482^{1024} \\mod 1739 = 867^4
\\mod 1739= 1452\\\\ \\therefore 1482^{1325} \\mod 1739 = (1482 \\times
1089 \\times 1662) \\mod 1739 \\times (895 \\times 867 \\times 1452)
\\mod 1739 = (533 \\times 1341) \\mod 1739
=24](https://s0.wp.com/latex.php?latex=1482+%5Cmod+1739+%3D1482%5C%5C++1482%5E4+%5Cmod+1739+%3D1089%5C%5C++1482%5E8%3D1482%5E4+%5Ctimes+1482%5E4+%5Cmod+1739+%3D%281089+%5Ctimes+1089%29+%5Cmod+1739+%3D+1662%5C%5C++1482%5E%7B32%7D%3D+%281482%5E8%29%5E4+%5Cmod+1739+%3D+1662%5E4+%5Cmod+1739+%3D+895%5C%5C++1482%5E%7B256%7D%3D%281482%5E%7B32%7D%29%5E8+%5Cmod+1739+%3D+%28895%5E4+%5Ctimes+895%5E4+%29+%5Cmod+1739+%3D%281661+%5Ctimes+1661%29+%5Cmod+1739%3D867%5C%5C++1482%5E%7B1024%7D+%5Cmod+1739+%3D+867%5E4+%5Cmod+1739%3D+1452%5C%5C++%5Ctherefore+1482%5E%7B1325%7D+%5Cmod+1739+%3D+%281482+%5Ctimes+1089+%5Ctimes+1662%29+%5Cmod+1739+%5Ctimes+%28895+%5Ctimes+867+%5Ctimes+1452%29+%5Cmod+1739+%3D+%28533+%5Ctimes+1341%29+%5Cmod+1739+%3D24&bg=ffffff&fg=333333&s=0
"1482 \\mod 1739 =1482\\\\  1482^4 \\mod 1739 =1089\\\\  1482^8=1482^4 \\times 1482^4 \\mod 1739 =(1089 \\times 1089) \\mod 1739 = 1662\\\\  1482^{32}= (1482^8)^4 \\mod 1739 = 1662^4 \\mod 1739 = 895\\\\  1482^{256}=(1482^{32})^8 \\mod 1739 = (895^4 \\times 895^4 ) \\mod 1739 =(1661 \\times 1661) \\mod 1739=867\\\\  1482^{1024} \\mod 1739 = 867^4 \\mod 1739= 1452\\\\  \\therefore 1482^{1325} \\mod 1739 = (1482 \\times 1089 \\times 1662) \\mod 1739 \\times (895 \\times 867 \\times 1452) \\mod 1739 = (533 \\times 1341) \\mod 1739 =24")

Thus, at the end of this calculation, which can be easily achieved with
a computer, K decodes the number C sent him without ever having
exchanged a symmetric secret key. The reason this trick works is because
of an arithmetic function discovered by Leonhard Euler known as Euler’s
totient function
![\\varphi(n)](https://s0.wp.com/latex.php?latex=%5Cvarphi%28n%29&bg=ffffff&fg=333333&s=0
"\\varphi(n)") and a theorem proved by him in that regard. Apparently,
Rivest, the discoverer of the RSA method got the clue for this method of
encryption while reading about modular arithmetic in a book. We will not
attempt to go into the higher arithmetic concerning the proof of Euler
regarding
![\\varphi(n)](https://s0.wp.com/latex.php?latex=%5Cvarphi%28n%29&bg=ffffff&fg=333333&s=0
"\\varphi(n)") but merely demonstrate how it applies to the RSA
encryption.

Euler’s
![\\varphi(n)](https://s0.wp.com/latex.php?latex=%5Cvarphi%28n%29&bg=ffffff&fg=333333&s=0
"\\varphi(n)") is defined as the number of integers ![1 \\le m \\le
n](https://s0.wp.com/latex.php?latex=1+%5Cle+m+%5Cle+n&bg=ffffff&fg=333333&s=0
"1 \\le m \\le n"), which are relatively prime (coprime) with
![n](https://s0.wp.com/latex.php?latex=n&bg=ffffff&fg=333333&s=0 "n")
i.e.
![GCD(n,m)=1](https://s0.wp.com/latex.php?latex=GCD%28n%2Cm%29%3D1&bg=ffffff&fg=333333&s=0
"GCD(n,m)=1"). Thus, ![\\varphi(8)=
\\\#(1,3,5,7)=4](https://s0.wp.com/latex.php?latex=%5Cvarphi%288%29%3D+%5C%23%281%2C3%2C5%2C7%29%3D4&bg=ffffff&fg=333333&s=0
"\\varphi(8)= \\#(1,3,5,7)=4"). For a prime
![p](https://s0.wp.com/latex.php?latex=p&bg=ffffff&fg=333333&s=0 "p") it
is easy to see that the value of
![\\varphi(p)=p-1](https://s0.wp.com/latex.php?latex=%5Cvarphi%28p%29%3Dp-1&bg=ffffff&fg=333333&s=0
"\\varphi(p)=p-1") for every other number below it will be relatively
prime to it by definition. Thus, ![\\varphi(p\_k)=\\varphi(p\_1\\cdot
p\_2)=(p\_1-1)(p\_2-1)](https://s0.wp.com/latex.php?latex=%5Cvarphi%28p_k%29%3D%5Cvarphi%28p_1%5Ccdot+p_2%29%3D%28p_1-1%29%28p_2-1%29&bg=ffffff&fg=333333&s=0
"\\varphi(p_k)=\\varphi(p_1\\cdot p_2)=(p_1-1)(p_2-1)"). This is the
number
![p\_l](https://s0.wp.com/latex.php?latex=p_l&bg=ffffff&fg=333333&s=0
"p_l") used in calculating the second number
![q](https://s0.wp.com/latex.php?latex=q&bg=ffffff&fg=333333&s=0 "q") of
the public key. Thus, from the above account one can see that the
decoding calculation is essentially: ![k^{dq} \\mod
p\_k](https://s0.wp.com/latex.php?latex=k%5E%7Bdq%7D+%5Cmod+p_k&bg=ffffff&fg=333333&s=0
"k^{dq} \\mod p_k"). From step 4 of above we have
![dq=np\_l+1=n\\varphi(p\_1p\_2)+1
=n\\varphi(p\_k)+1](https://s0.wp.com/latex.php?latex=dq%3Dnp_l%2B1%3Dn%5Cvarphi%28p_1p_2%29%2B1+%3Dn%5Cvarphi%28p_k%29%2B1&bg=ffffff&fg=333333&s=0
"dq=np_l+1=n\\varphi(p_1p_2)+1 =n\\varphi(p_k)+1"). Therefore, the
decoding operation is ![(k^{n\\varphi(p\_k)+1}) \\mod p\_k=(k\\cdot
k^{n\\varphi(p\_k)}) \\mod p\_k= k (\\cdot k^{n\\varphi(p\_k)} \\mod
p\_k)](https://s0.wp.com/latex.php?latex=%28k%5E%7Bn%5Cvarphi%28p_k%29%2B1%7D%29+%5Cmod+p_k%3D%28k%5Ccdot+k%5E%7Bn%5Cvarphi%28p_k%29%7D%29+%5Cmod+p_k%3D+k+%28%5Ccdot+k%5E%7Bn%5Cvarphi%28p_k%29%7D+%5Cmod+p_k%29&bg=ffffff&fg=333333&s=0
"(k^{n\\varphi(p_k)+1}) \\mod p_k=(k\\cdot k^{n\\varphi(p_k)}) \\mod p_k= k (\\cdot k^{n\\varphi(p_k)} \\mod p_k)").
By Euler’s theorem ![k^{\\varphi(p\_k)} \\mod
p\_k=1](https://s0.wp.com/latex.php?latex=k%5E%7B%5Cvarphi%28p_k%29%7D+%5Cmod+p_k%3D1&bg=ffffff&fg=333333&s=0
"k^{\\varphi(p_k)} \\mod p_k=1"). Thus, our expression evaluates to
![k](https://s0.wp.com/latex.php?latex=k&bg=ffffff&fg=333333&s=0 "k").

Now, the snooper R would have in his possession the public key ![p\_k,
q](https://s0.wp.com/latex.php?latex=p_k%2C+q&bg=ffffff&fg=333333&s=0
"p_k, q") and would obtain
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") by
intercepting the exchange between C and K. Hence, to decode
![a](https://s0.wp.com/latex.php?latex=a&bg=ffffff&fg=333333&s=0 "a") he
would need to have
![p\_l=(p\_1-1)(p\_2-1)](https://s0.wp.com/latex.php?latex=p_l%3D%28p_1-1%29%28p_2-1%29&bg=ffffff&fg=333333&s=0
"p_l=(p_1-1)(p_2-1)"). The only way he can get that is by factorizing
![p\_k](https://s0.wp.com/latex.php?latex=p_k&bg=ffffff&fg=333333&s=0
"p_k") to obtain
![p\_1](https://s0.wp.com/latex.php?latex=p_1&bg=ffffff&fg=333333&s=0
"p_1") and
![p\_2](https://s0.wp.com/latex.php?latex=p_2&bg=ffffff&fg=333333&s=0
"p_2"). In our example
![p\_k=1739](https://s0.wp.com/latex.php?latex=p_k%3D1739&bg=ffffff&fg=333333&s=0
"p_k=1739") can be factorized by a modern computer in a jiffy. However,
in practice
![p\_1](https://s0.wp.com/latex.php?latex=p_1&bg=ffffff&fg=333333&s=0
"p_1") and
![p\_2](https://s0.wp.com/latex.php?latex=p_2&bg=ffffff&fg=333333&s=0
"p_2") are chosen to be giant numbers like 155 digits each. For example
here are two probable prime numbers of 155 digits each:

![p\_1=](https://s0.wp.com/latex.php?latex=p_1%3D&bg=ffffff&fg=333333&s=0
"p_1=")
`10000000000000000369475456880582265409809179829842688451922778552150543659 347219597216513109705408327446511753687232667314337003349573404171046192448274699`

![p\_2=](https://s0.wp.com/latex.php?latex=p_2%3D&bg=ffffff&fg=333333&s=0
"p_2=")
`10000000000000000369475456880582265409809179829842688451922778552150543659 347219597216513109705408327446511753687232667314337003349573404171046192448275667`

I can multiply them on any ordinary laptop nearly instantaneously to get
a 309 digit behemoth:

![p\_k=](https://s0.wp.com/latex.php?latex=p_k%3D&bg=ffffff&fg=333333&s=0
"p_k=")
`10000000000000000738950913761164544470829683371185866006812890654888707392 10920108053653415662434024612881790955097216386704787165762913381353272856133610 92747866891044947194561369772249369066504008239030777919045965752486653372812632 286420484529615670829121768709047243844587015197251118254241456911693449233`

However, if we were to give a behemoth number of that magnitude for
factorization, without telling you how we generated it, then it would
not be possible with the realm of our current computation to factorize
it. When we last checked the biggest product of two primes which was
factorized was a 232 digit number and it was no quick or easy task.
Nobody in the public domain knows to date knows if there is any
efficient algorithm to factorize big numbers or whether it is even
possible to device one. It is on this premise the RSA encryption hangs.
Finally, it should be noted that both DHM and RSA are not really
efficient methods for direct encryption of a large amount of
information. Instead they are used to encrypt a key which can then be
used to encrypt the actual message.
