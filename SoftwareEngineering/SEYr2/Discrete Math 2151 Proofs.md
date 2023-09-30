## List of Proofs to Know

#### Prove that $\sqrt p$ is Irrational
p is a prime number

Proof by contradiction:
assume that $\sqrt p$ is rational
let a and b be integers in lowest terms:
$$ \sqrt p = \frac ab $$
$$ p = \frac{a^2}{b^2} $$
$$ pb^2 = a^2 $$
$\therefore\; a^2$ is a multiple of $p$
$\therefore\; a$ is a multiple of $p$ (by the dividing lemma)
$\therefore\; a = pk$
$$ pb^2 = p^2k^2 $$
$$ b^2 = pk^2 $$
$\therefore\; b^2$ is a multiple of $p$
$\therefore\; b$ is a multiple of $p$ (by the dividing lemma)
$\therefore$ there is a contradiction because a and b were said to be in lowest terms yet they are both divisible by $p$
$\therefore$ $\sqrt p$, where $p$ is a prime number, is irrational

#### 2
Let $G$ be a graph with $n$ vertices $v_1, v_2, \cdots, v_n$ and $m$ edges prove that 
$$ \sum_{i=1}^n \delta(v_i) = 2m $$

m must have 2 vertices (one on either end). for every connection on one end of the edge there is a connection on the other. so for every edge there are 2 connections. connections contribute to the degree of their respective vertex and also the total degree. therefore for every edge there are 2 connections. and the total degree of all vertcies is made up of connections where each connection contributes 1 to the degree. So m edges * 2 connection * add 1 to the degree = 2m.

#### 3
Let $n_1, n_2$ be coprime integers and $a_1, a_2$ integers
- Prove that there is an integer $b\equiv a_1\mod n_1$ and $b\equiv a_2\mod n_2$
- Suppose that $b_1, b_2$ are integers and $b_1\equiv a_1\mod n_1$ and $b_1\equiv a_2\mod n_2$ and $b_2\equiv a_1\mod n_1$ and $b_2\equiv a_2\mod n_2$.
	- Prove that $b_1\equiv b_2\mod n_1n_2$


##### Part 1
$\gcd(n_1, n_2) = 1$
So there is no integer ($b$) that divides both $n_1, n_2$

$b = a_1 + n_1k$
$b = a_2 + n_2k$

$\therefore$ the remainders ($a_1, a_2$) must be different

Assume divisor
$\gcd(n_1, n_2) = d$
$\gcd(dk_1, dk_2) = d$

$b = a_1 + n_1k_3$
$b = a_2 + n_2k_4$

$b = a_1 + dk_1k_3$
$b = a_2 + dk_2k_4$

$b = a_1 + dk_5$
$b = a_2 + dk_6$

$b \equiv a_1 \mod d$
$b = a_2 \mod d$

$\therefore a_1 = a_2$
$\therefore$ $n_1, n_2$ must be coprime to have 2 different integers $a_1, a_2$

##### Part 2


#### 5
Let $H_{n,2}$ be the graph whose vertices are n-bit strings of 0s and 1s. There is an edge between 2 n-bit strings if the distance between the strings is 2. So for example $H_{2,2}$ has vertices 00,01,11,10 and there is an edge between 00 and 11 and an edge between 10 and 01 and no other edges. 
Prove that for all $n\geq 2$ that $H_{n,2}$ is not connected

Consider the 2 vertices 11...11 and 00...00 in $H_{n,2}$. The 2 vertices have a distance of n which is greater than 2. meaning there is no edge between them.

Therefore there is no path between 2 vertices when the distance between the 2 is greater than 2. so the graph must not be connected

#### 6
Prove that there are infinitely many prime numbers using contradiction

Let N be the product of all primes $p_1 \cdots p_n$

Let M = N+1 be the product of all prrimes $p_1 \cdots p_n$ + 1 or $q_1\cdots q_s$

M must have a prime factor meaning that there is a $p_i$ that divides M.

However if thats the case it must also divide $N - p_1\cdots p_n = 1$ however this is imposibble because there is no prime number able to divide 1

#### 7
Proof by induction

If number is prime we are done (num * 1)

Base Case: 
2 = 2\*1

Inductive Case:
If number is prime we are done (num * 1)

If it isnt we can show it as
$(k+1) = ab$
where a and b are $2\leq a,b\leq k$

a,b are less than k therefore we have already proven they are product of primes therefore k+1 can be represented as a product of primes

#### 8
Let a,b be integers with $\gcd(a,b) = 1$. Show that the equation $ax\equiv 1\mod b$ has an integer solution

Use Pidgeon hole Principle:

Assume there is no solution:
so there is no $1\leq i \leq (b-1)$ with $ai\equiv 1\mod b$ 

so there is b pidgeons and they fly into b-1 holes so some hole has 2 pidgeons.

This means that there are $i\neq j$ and $0\leq i,j \leq b-1$ with $ai\equiv aj\mod b$

Then b|(ai-aj) = a(i-j) so b|a(i-j) so by the improved euclid lemma we have b|i-j which says $i\equiv j\mod b$

a contradiction

#### 9
Possible # of vertices = $2^n$
Possible neighbors = $n$

$\therefore \sum \delta(v) = n2^n$
$\sum \delta(v) = 2e$

by handshake lemma

$n2^n = 2e$
$n2^{n-1} = e$

#### 10
We know:
$\sum \delta(v) = 2e$

$2e$ is even
$\therefore \sum \delta(v)$ is even

$\sum \delta(v) =$ edges of even deg * # of edges + edges of add deg * # of edges 
First will be even

$\therefore$ second must be even
$\therefore$ # of edges must be even
$\therefore$ k is even





