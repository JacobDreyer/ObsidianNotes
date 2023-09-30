### The Idea
The Bank sends out public keys so that everyone can "talk" with them

The Bank has a private key that decodes the public key

This means that no one can see what other people send to the bank because only the bank can decode the message

### How It Works
The bank picks two primes p and q and computes Z = pq

This hides p,q from the public

If p,q are huge primes its hard to factor p,q

now set $\phi = (p-1)(q-1)$ and pick n such that

$\gcd(n,\phi) = 1$ 
- usually n is prime ???

the pair (Z, n) is made public by the bank. This pair is the public key

to send a number:
user1 computes $c = a^n\mod Z$ and sends c


The bank knows Z = pq and $\phi = (p-1)(q-1)$
So the bank knows $\exists$ a unique $0<s<\phi$ such that:
$ns\equiv 1\mod \phi$

the bank has c and s
$$ c^s\equiv a^{ns}\mod Z $$
$$ a^{ns} = a\mod Z = a $$
The bank computes:
$$ c^s\equiv (a^n)^s \equiv a^{ns}\equiv a\mod Z $$
- c = number sent by user
- n = a (public) number such that $\gcd(n,\phi) = 1$
	- $\phi$ = a (private) number such that $\phi = (p-1)(q-1)$
- s = a (private) number such that $ns = 1\mod\phi$
- Z = a (private) number
$$ a^n = c $$

### Simplified from ChatGPT
$p, q$ = Large primes

$n = pq$ : called the modulus : defines encryption/decryption : in public key

$\gcd(e, (p-1)(q-1)) = 1$ : e is the public exponent : used in pubic key

$ed = 1\mod (p-1)(q-1)$ : d is the private exponent : used in private key
- what number e * d provides a remainder 1 when divided by (p-1)(q-1)

$m$ = code/number to be encrypted



The sender computes:
$$ c = m^e\mod n $$
c is the encrypted message. it is what is sent

Recepient computes:
$$ m = c^d\mod n $$




