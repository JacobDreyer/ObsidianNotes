#### Question 1
Mod n questions
1. Fix an integer n ≥. Let x1, x2, y1, y2 be any integers.Assume that x1 ≡ x2 mod n and y1 ≡ y2 mod n. Prove the following.
	1. x1 + y1 ≡ x2 + y2 mod n
	2. x1y1 ≡ x2y2 mod n.

##### 1.1.1
$$ x_1\equiv x_2\; mod\; n\qquad n|(x_1-x_2) $$
$$ y_1\equiv y_2\; mod\; n\qquad n|(y_1-y_2) $$
$$ (x_1+y_1)\equiv(x_2+y_2)\; mod\; n\qquad n|[(x_1+y_1)-(x_2+y_2)] $$
$$ n|[(x_1-x_2)+(y_1-y_2)] $$
if $n|(x_1-x_2)$ and $n|(y_1-y_2)$ then $n|[(x_1-x_2)+(y_1-y_2)]$
Therefore:
$$ x_1+y_1\equiv(x_2+y_2)\; mod\; n $$
##### 1.1.2
$$ x_1\equiv x_2\; mod\; n\qquad y_1 \equiv y_2\; mod\; n $$
$$ n|(x_1-x_2)\qquad n|(y_1-y_2) $$
$$ n|(x_1-x_2)y_1\qquad n|x_2(y_1-y_2) $$
$$ n|(x_1y_1-x_2y_2) $$
$$ x_1y_1\equiv x_2y_2\; mod\; n $$
$$ n|(x_1y_1-x_2y_2) $$
Therefore $x_1y_1\equiv x_2y_2\; mod\; n$
2. Consider the following equations.
	1. 4x ≡ 1 mod 15 where x ∈ Z. Find a solution 0 ≤ x ≤ 14 if a solution exists or explain why it does not exist.
	2. Consider th equation 7x ≡ 1 mod 49 Find a solution 0 ≤ x ≤ 48 or explain why it does not exist.
	3. Consider th equation 5x ≡ 1 mod 15 Find a solution 0 ≤ x ≤ 48 or explain why it does not exist.

##### 1.2.1
$$ x = \frac{1+k15}{4} $$
$$ k = 1 $$
$$ x = 4 $$

##### 1.2.2
$$1 \mod 49 = 1 = 7x$$
$$ \frac17 = x $$
##### 1.2.3
$$ 5x = 1\mod 15 $$
$$ 1\mod 15 = 1 $$
$$ 1 = 5x $$
$$ x = \frac15 $$

#### Question 2
Divisibility questions Let a, b, c be integers.
1. Show that if a | b and b | c then a | c.
2. Show that if a | b and a | (b + c) then a | c.
3. Show that if a | 1 then a = 1 or a = −1. (Easy question! Your solution should be 2 lines.)
4. Show that if gcd(a, b) = d then gcd(a/d, b/d) = 1.

2.1
let k be some integer
$$ a|b\quad =>\quad b=ak_1 $$
$$ b|c\quad =>\quad c=bk_2 = ak_1k_2 = ak_3 $$
Therefore $a|c$ becomes $a|ak_3$ so c is divisible by a

2.2
Let k be some integer
$$ a|(b+c)\quad => \quad (a|b) + (a|c) $$
Therefore in order for a to divide $a|(b+c)$ a must divide c

2.3
The greatest divisor of 1 is 1 (and therefore -1) and 1 cannot be divided by zero so the only solutions are a=1 and a=-1

2.4
let k, m, and n be some integers
$$ a = dk_1\qquad b = dk_2 $$
$$ d = \gcd(a,b) = ma + nb = mk_1d + nk_2d $$
$$ 1 = mk_1 + nk_2 $$
$$ \frac ad = k_1\qquad \frac bd = k_2 $$
$$ 1 = \gcd(\frac ad, \frac bd) = \gcd(k_1, k_2) $$
$$ 1 = mk_1 + nk_2 $$

#### Question 3
Let a, b be integers with a, b relatively prime. Let 0 ≤ r ≤ b − 1. Show that there is an integer x with [ax]b = [r]b. Hint: If you get stuck look over the lecture notes for things that may help.

since a cannot be divided by b:
$$ a = bk + r $$
because of this there is also a solution where
$$ ax = bk + r $$
sub in
$$ a = bk+r = \frac{bk+r}{x} $$
$$ x = \frac{bk+r}{bk+r} = 1 $$
$\therefore$ x = 1 is a solution


#### Question 4
Prove that there are infinitely many prime numbers using the following hints. Assume for a contradiction that there are finitely many primes. Since you have finitely many primes, you can list them out,say we let p1, p2, . . . , pn be the finitely many primes. Now let N = p1...pn. That is, N is the product of all the finitely many primes. Now consider 1 + N. This is some integer, so 1 + N is a product of primes q1...qs by the Fundamental theorem of arithmetic. As each of the qi is prime we have q1 = pj for some j because p1, ..., pn is every single prime number by our assumption.

Assume there are finite amount of prime numbers

let N be the product of all primes p1-pn
Let M = N+1 be the product of all primes p1-pn + 1 or q1-qs

M must have a prime factor meanins that there is a $p_i$ what divides M

However if thats the case it must also divide $N - p_1\cdot \cdots\cdot p_n  = 1$ however this is impossible because any $p_i$ is unable to divide 1

#### Question 5
Choose your favorite programming language. Write down an implementation of the Euclidean algorithm. That is, write down an Algorithm that takes as input two integers a, b ≥ 1 and outputs gcd(a, b). You may use a recursive algorithm, or a loop. But you may not call a function that computes the gcd for you

Use your algorithm to compute gcd(348238, 4598723) and answer the following question. Is there an integer x such that

Yes there is an x that exists
$$  $$

Explain why you know gcd(2138148, 253928) $\neq$ 1 before doing any computation. Then compute using your algorithm gcd(2138148, 253928) and verify that it is not 1.

I can tell that there is a number greater than 1 because both numbers are even so 2 at least is a gcd

![[Pasted image 20221106165643.png]]