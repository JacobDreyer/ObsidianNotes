How do we compute gcd(a,b)
1. input integers a,b $\geq 1$
2. if a < b swap a,b
3. write $a = q_1b+r_1$
4. if $r_1 = 0$ return b
5. Otherwise compute gcd(b,$r_1$) recursively