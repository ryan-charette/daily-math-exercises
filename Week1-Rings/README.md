## Definition of Ring

A *ring* is a nonempty set $R$ equipped with two binary operations, (usually written as addition and multiplication), such that for all $a,b,c$ in $R$:
1. (Addition is commutative) $a+b=b+a$.
2. (Addition is associative) $(a+b)+c=a+(b+c)$.
3. (Additive has identity) There is an element $0$ in $R$ such that $a+0=a$ for every $a$ in $R$.
4. (Addition is invertible) There exists an element $-a$ in $R$ such that $a+(-a)=0$. 
5. (Multiplication is associative) $a(bc)=(ab)c$. 
6. (Multiplication distributes over addition) $a(b+c)=ab+ac$ and $(a+b)c=ac+bc$.

If it is further true that mulitiplication is commutative (that is, if $ab=ba$ for all $a,b\in R$), then we say that $R$ is *commutative* and call $R$ a *commutative ring*.

The element $0$ is called the *additive identity*, and the element $-a$ is called the *additive inverse* of $a$. 

## Definition of Subring
Let $R$ be a ring and let $S$ be a subset of $R$. If $S$ is itself a ring under the addition and multiplication in $R$, then we say that $S$ is a *subring* of $R$. 

## Definition of Nilpotent
An element $a$ of a ring is *nilpotent* if $a^n=0$ for some positive integer $n$.

## The Binomial Thereom

Let $R$ be a commutative ring and let $a,b\in R$. Then for every positive integer $k$,

$$
(a+b)^k=\sum_{i=0}^k {k \choose i} a^ib^{k-i}
$$

where ${k \choose i}$ denotes the number $\displaystyle\frac{k!}{i!(k-1)!}$. The proof is by induction on $k$.
