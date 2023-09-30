# Practice Midterm
## Part A
A1: Let x, y be real numbers. Determine if
$\forall x,\exists y$ such that $xy = 0$
==True==
A2. Let n ≥ be an integer. Determine if
$$ \forall n\geq 1, n!\geq2^n $$
==false==
A3. Let x, y ∈ Z. Determine if the statement: There are integers x, y such that
$$ 2x+4y=1 $$
==False==
A4. Let p, q, r be propositions such that p is false, q is true and r is false. Determine if
$$ (p\lor q)\lor(p\lor\neg r) $$
==True==
A5. Let p, q, r, s be propositions with p, r both false and q, s both true. Determine if
$$ [(p\land\neg q)\to(q\land r)]\to(s\lor\neg q) $$
==True==
A6.Let p, q be propositions. Consider the statement: (p → q) → r is logically equivalent to p → (q → r). Is this True or False.
==False==
A7. Let p, q be propositions. Consider the statement: (p → q) ∧ (q → r) is logically equivalent to (p → r). Is this True or False?
==False==
A8. : Let S be a non-empty set. Then the power set P(S) has at least two elements. Is this True or False.
==True==
A9 Let A, B, U be sets with A, B ⊆ U. If B ∪ A = U and B ∩ A = ∅ then U \ B = A. True or False
==True==

## Part B
==B1.== Let A, B, C be sets.
- Prove That
$$ (A\cap B)/A = \phi $$
- Give an example of sets A, B, C such that C ∩ B is a proper subset of (A ∪ B) ∩ C. Verify that your example is correct.
- (A ∪ B) ∩ C = B ∩ C. Verify that your example is correct.

1.
Proof: Proof by Contradiction. Assume that $(A\cap B)/A \neq \phi$
There must be an $x\in A\cap B$ with $x\notin A$ but this is impossible because x must be in A in order to be in $A\cap B$

==B2.== Let A, B, C, U be sets sets and assume that A, B, C ⊆ U. Prove that
$$ U/(U/A) = A $$
If $x\in U/(U/A)$ then $x\in U\land x\notin(U/A)$ if x is not in $U/A$ then $x\in A$.

If $x\in A$ then $x\notin U/A$ so $x\in U/(U/A)$

Therefore any value in A must be in $U/(U/A)$ meaning that $U/(U/A)$ is equal to A

==B3== Compute P(∅) ∩ P(P(∅)). Where P(S) is the power set of a set S and ∅ is the emptyset

$P(\phi) = \{\phi\}$ 
Therefore 
$P(P(\phi)) = \{\phi, \{\phi\}\}$
Therefore
$$ P(\phi)\cap P(P(\phi)) = \{\phi\} $$
==I1== Let $1>r>0$ be a real number. Define $f(n) = r^0+r^1+\cdots+r^n = \sum^n_{k=0}r^k$ 
- Compute f(n + 1) − f(n).
- Prove Using induction that $f(n) = \frac{1-r^{n+1}}{1-r}$

$$ f(n) = \cancel{r^0+r^1+\cdots+r^n} $$
$$ f(n+1) = \cancel{r^0+r^1+\cdots+r^n}+r^{n+1} $$
$$ f(n+1)-f(n) = r^{n+1} $$
2.
We know $f(n+1) = \frac{1-r^{n+2}}{1-r}$
So to prove:
$$ f(n+1) = r^0+r^1+\cdots+r^n+r^{n+1} $$
$$ f(n+1) = f(n) + r^{n+1} $$
$$ = \frac{r^{n+1}(1-r)+(1-r^{n+1})}{(1-r)} $$
$$ = \frac{\cancel {r^{n+1}}-r^{n+2}+1\cancel{-r^{n+1}}}{(1-r)} $$
$$ = \frac{1-r^{n+2}}{(1-r)} $$
==P1==
Determine the truth of the following statements. If true, prove it. If false, give a counter example.
1. Let n be an integer. If $n^2$ is an odd integer then n is an odd integer.
Proof by Contra-Positive
If $n$ is even $\to$ $n^2$ is even
$$ n = 2k $$
$$ n^2 = (2k)^2 = 4k^2 = 2(2k^2) $$
$\therefore$ even. $\therefore$ if $n^2$ is odd then n is odd
2. Let n, a, b > 1 be integers. If there is an integer k with nk = ab then there is an integer $q_1$ with n$q_1$ = a or there is an integer $q_2$ with n$q_2$ = b.

$\forall kn,\exists q$ such that $nq = a$ or $nq=b$
$$ 4\cdot1 = 2\cdot 2 $$
There is no integer q such that $q\cdot4 = 2$

==P2==
Recall the defnition of a prime number used earlier. The following is a true statement.

Lemma (Dividing lemma). Let p be a prime number and N ≥ 1 an integer. Suppose that $N^2$ = pq for some integer q. Then there is an integer k with N = pk.

Prove that √p is irrational. You will use the prime dividing lemma. For full marks state precisely where you use the dividing lemma.

Proof by Contradiction. Assume $\sqrt p$ is rational
$\sqrt p = \frac ab$ where a and b are integers in lowest terms
$$ p = \frac{a^2}{b^2} $$
$$ b^2p = a^2 $$
Therefore $a^2$ must be a multiple of p and by the dividing lemma a must be a multiple of p
$$ a = pk $$
$$ b^2p = p^2k^2 $$
$$ b^2 = pk^2 $$
Therefore $b^2$ is a multiple of p and by the dividing lemma b is a multiple of p. However we stated b and a are in lowest terms but showed that they are both multiples of p meaning a contradiction.

==I2==
Let n ≥ 1 be an integer. Recall the following defnitions
- We say that n is a prime number if n > 1 and there is no factorization n = ab where a, b > 1 are integers.
- Note that if n > 1 is an integer and n is NOT prime. Then there are integers a, b > 1 with n = ab. This will be useful.
Let n > 1 be an integer. Using contradiction prove that there is a prime number p and an integer k ≥ 1 with pk = n.

Hint: Towards a contradiction assume that there is an integer n that cannot be written as n = pk where p is prime and k is an integer. Since we have assumed there is one such integer, there is a smallest integer n1 such n1 cannot be written as pk = n1 where p is prime. Now argue by cases: First assume n1 is prime and derive a contradiction. Then assume that n1 is not prime and derive a contradiction using the second bullet point above and the assumption that n1 is the smallest integer that cannot be written as n1 = pk

Let n>1 be any integer
claim: n can be written as n = pk
where p is prime and k is any integer
To prove we use mathmatical induction

Proof by Induction:
1) Base Step
As n> 1, so we take n=2 This is already a prime number So in this case we take p=2 and k=1 hence our result holds in this case

2) Assuming Step:
Suppose result holds for every integer m where 2$\leq$ m < n. i.e  result holds up to n-1

3) conclusion step:
Let in this case n be any integer if n is already a prime number. Then we take p=n and k=1
So with this result holds.
Otherwise if n is composite, then by definition n = ab Where a,b< n
As a,b < n then above result holds for integers.
Hence a can be written as a=pk where p is prime and k is an integer. Thus, n=ab=(pk)b=p(kb)=pk' where p is prime and k' is any integer Thus results hold for this case too.