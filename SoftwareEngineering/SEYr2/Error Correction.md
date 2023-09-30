$\mathbb F^n_2$ = n bit binary numbers. each bit is an element in a vector
$\vec x, \vec y$ = elements in $\mathbb F_2^n$ 

If $\vec x, \vec y \in \mathbb F_2^n$ set $d(\vec x, \vec y)$ = # of coordinates where $x_i \neq y_i$

$h(\vec x) = d(\vec x, \vec 0)$ where $h(\vec x)$ is called the [[Hamming Weight]]
- Basically # of coordinates that don't equal 0

### [[Code]]
![[Code]]

### [[Nearest Neighbor Decoding]]
![[Nearest Neighbor Decoding]]

### [[Generator Matrix]]
![[Generator Matrix]]

### [[Parity Matrix]]
![[Parity Matrix]]
///////////////////////////////////////////////////////////////////////////////////////
///////////////////////////////////////////////////////////////////////////////////////
///////////////////////////////////////////////////////////////////////////////////////


$$ \mathbb F_2^n = \{(x_1,x_2,\cdots,x_n): x_i=[n_i]_2\} $$
$\mathbb F_2^n$ = all vectors $x_1, x_2,\cdots,x_n$ with $x_i$ = 0 or = 1. $1\leq i\leq n$

$$\vec x = (x_1,\cdots, x_n)\qquad \vec y=(y_1,\cdots,y_n)$$

$d(\vec x, \vec y) =$ # of coordinates where $x_i\neq y_i$ 

##### The Hamming Weight:
$h(\vec x) =$ # of coordinates $x_i$ with $x_i \neq 0$  

A code C is any non-empty [[subset]] of $\mathbb F_2^n$ 

We say that C has length $n$

#### Nearest Neighbor Decoding

We say that a code C is t-error encoding if for any $\vec w \in \mathbb F_2^n$ there is a unique $\vec c\in C$ such that $d(\vec c, \vec w)\leq t$

Ex. suppose that Alice wants to talk to Bob, Alice will send messages to bob, but the messsage must travel through a noisy channel. Alice sends messages as binary vectors namely elements $\vec x\in\mathbb F_2^n$.

As $\vec x$ passes through the noisy channel there can be errors as the message degrades. This means that as $\vec x$ passes through the noisy channel some bits are flipped. Ex. (1101)$\to$(0,111)

To correct errors Alice and Bob select a t-error correcting code. The number t is chosen so its unlikely that there are more than t-errors when a message passes through the noisy channel. So if the noisy channel produces lots of errors, Bob and Alice pick a better code

==A Code C is t error correcting if and only if: ==
$$ h(c) \geq zt+1 $$

==A binary code C is a code C such that if:==
$$ \vec x,\vec y\in C $$
then:
$$ \vec x + \vec y\in C $$
Ex. 
$\{(1,0),(0,1)\}$ is not a linear code because $(1,0)+(1,0)=(1+1),(0+0)=(0,0)\notin C$ 

whereas

$\{(1,0,0,1),(1,0,0,0),(0,0,0,1),(0,0,0,0)\}$ is a linear code

#### [[Basis of a Linear Code]]
![[Basis of a Linear Code]]

#### [[Generator Matrix]]
![[Generator Matrix]]

#### [[Parity Matrix]]
![[Parity Matrix]]

