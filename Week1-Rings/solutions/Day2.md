To show that $N$ forms a subring of $R$, we need to verify that $N$ is nonempty, $N$ is closed under addition and multiplication, and $N$ has additive inverses. The zero element is nilpotent since $0^1=0$, so $N$ is non-empty. For any $a,b\in N$, we must show that $a+b$ is also nilpotent. Since $a$ and $b$ are nilpotent, there exist positive integers $m$ and $n$ such that $a^m=0$ and $b^n=0$. Using the binomial theorem,

$$(a+b)^k=\sum_{i=0}^k {k \choose i} a^ib^{k-i}.$$

For each term $a^i b^{k-i}$, if $i\geq m$, then $a^i=0$ because $a^m=0$, and if $k-i\geq n$, then $b^{k-i}=0$ because $b^n=0$. Set $k=m+n-1$ so that when $i<m$,

$$k-i=(m+n-1)-i= n+(m-i)-1\geq n+1-1 = n.$$

Then all terms in the expansion become zero, and $(a+b)^k=0$. Hence $a+b$ is nilpotent. We must also show that $ab$ is nilpotent. Since $a^m=0$ and $b^n=0$, 

$$(ab)^{m+n}=a^{m+n}b^{m+n}=a^ma^nb^mb^n=0\cdot a^nb^m\cdot 0=0$$

because any multiple of zero is zero. Thus, $ab$ is nilpotent. Finally, we must show that $-a$ is also nilpotent. Since $a^n=0$,

$$(-a)^n=(-1)^n a^n=(-1)^n\cdot 0=0.$$

Thus, $-a$ is nilpotent. Since all subring criteria are satisfied, $N$ is indeed a subring of $R$.


