Let $n_1, n_2$ be relatively prime integers

There is an integer x with
$$ x\equiv a_1\mod n_1 $$
$$ x \equiv a_2\mod n_2 $$
for any integers $a_1, a_2$ 

if y is an integer:
$$  y \equiv a_1\mod n_1  $$
$$  y \equiv a_1\mod n_2  $$
then:
$$ x\equiv y\mod n_1n_2 $$

#### Basic Algorithm for Solution
Start with a System:
$$ x\equiv a_i\mod n_i $$
- $1\leq i\leq k$
##### Step 1
If k = 2 solve system using:
$$ n_1y_1-n_2y_2 = a_2-a_1 $$
##### Step 2
if $k\geq 3$:

Solve system recursively:
Solve $x\equiv a_i\mod n_i$ to obtain a solution $b\equiv a_i\mod n_i$ 
Looks like:
$$ b = n_1y_1+a_1 = n_2y_2+a_2 $$

##### Step 3
Using k=2 method:

solve $x\equiv b\mod n_1\cdots n_{k-1}$ and $x\equiv a_k\mod n_k$ to obtain c

Looks Like:
$$ c = n_1n_2z_1 + b=z_2n_3+a_3 $$

return c as total solution
