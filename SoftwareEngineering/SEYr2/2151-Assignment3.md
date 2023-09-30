##### Name: Jacob Dreyer
##### Student Number: 251241714
## Q1
Let n be an integer and $f(n) = 1 + 3 + 5 + · · · + 2n − 1 = \sum^n_{k=1}2k-1$
be the sum of the first n odd numbers. Use induction to show that $f(n) = n^2$ for all integers n ≥ 1.

##### Base Step:
$n=1$
$$ 2(1)-1 = 1^2 $$
$$ 1 = 1 $$
$n=2$
$$ 2(1) - 1 + 2(2)-1 = 2^2 $$
$$ 1+3 = 4 $$
$$ 4=4 $$
##### Assume:
$f(n) = n^2$
$f(n+1) = (n+1)^2 = n^2+2n+1$

##### Conclusion:
$$ f(n+1)-f(n) = (1+3+\cdots+2n-1+2(n+1)-1)-(1+3+\cdots+2n-1) $$
$$ = 2n+1 $$
$$ f(n+1) = f(n) + 2n+1 $$
$$ f(n+1) = n^2+2n+1 $$
Therefore $f(n) = n^2$

## Q2
Let n ≥ 1 be an integer. Recall the following definitions.

Definition 1.1. We say that n is a prime number if n > 1 and there is no factorization n = ab where a, b > 1 are integers.

Idea 1.2. If n > 1 is an integer and n is NOT prime. Then there are integers a, b > 1 with n = ab.

Now prove the following theorem using strong induction.

Theorem 1.3. Let n > 1 be an integer. Then there is a prime number p and an integer k ≥ 1 with pk = n

Here is a potential outline for the proof. You may come up with a different argument if you wish. It may help to let S(n) be the statement ”there is a prime number p and an integer k with pk = n”. Then we want to prove that S(n) is true for all n ≥ 2.

1. Determine what the base case is, and show that the theorem is true in that case. Do not over think think part, it is not complicated.
	$n = 2 = 2\cdot 1$
1. 2. Let n > 2 and assume that the theorem is true for all m < n. This means we make the following inductive hypothesis: If 2 ≥ m < n then there is an integer k such that pk = m. Now consider two cases.
	1. Assume that n is prime. Prove the theorem directly. By this I mean find a prime p and an integer k ≥ 1 with pk = n. You may have done this already on assignment two
		 n = prime
		 $$ n = pk = n\cdot 1 $$
	2. Assume that n is not prime. Use the idea I described earlier and the inductive hypothesis to show that there is prime number p and an integer k with pk = n. Hint: If n = ab and a = pq for some prime p and integer q ≥ 1 then
$$ n = ab = (pq)b = p(qb) $$
		    So $n = pk$ with $k = bq$
Assume the theorem holds for all numbers up to n-1
$$ n = ab = (pq)b = p(qb) $$
and p is prime so n can be represented as a multiple of a prime number. Thus result holds

## Q3
Let A, U be sets with A ⊆ U. Show that U / (U / A) = A.
$$ x\in A\qquad\therefore x\in U $$
$$ x \notin (U/A) \qquad\therefore x\in U/(U/A) $$
Because x is in U and not $U/A$, $x$ is in $U/(U/A)$

Therefore any value in A must be in $U/(U/A)$
$$ x\notin A\qquad x\in U $$
$$ x\in U/A \qquad\therefore x\notin U/(U/A) $$
Therefore any value x not in A is not in $U/(U/A)$

Therefore A is equal to $U/(U/A)$

## Q4
Let S = {a, b, c, d} Write down the power set P(S).
$$ P(S) = \{\phi, \{a\},\{b\},\{c\},\{d\},\{a,b\},\{a,c\},\{a,d\},\{b,c\},\{b,d\},\{c,d\}, $$
$$ \{a,b,c\},\{a,c,d\},\{a,b,d\},\{b,c,d\},\{a,b,c,d\}\} $$
