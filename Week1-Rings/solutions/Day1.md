## Day 1

Let $R$ be a ring and let $(a,b)$, $(c,d)$, and $(e,f)$ be elements in $R \times R$. To show that $R \times R$ with the given operations forms a ring, we need to verify that the set together with these operations satisfies the ring axioms. Since addition in $R$ is associative and commutative, the same holds for $R \times R$. The additive identity is $(0,0)$, and the additive inverse of $(a,b)$ is $(-a,-b)$. As for multiplication,

$$
\begin{align*}
    \[(a,b)(c,d)](e,f) &= (ac - bd, ad + bc)(e,f) \\
    &= ((ac - bd)e - (ad + bc)f, (ac - bd)f + (ad + bc)e) \\
    &= (ace - bde - adf - bcf, acf - bdf + ade + bce),
\end{align*}
$$

and, similarly,

$$
\begin{align*}
    (a,b)\[(c,d)(e,f)] &= (a,b)(ce - df, cf + de) \\
    &= (a(ce - df) - b(cf + de), a(cf + de) + b(ce - df)) \\
    &= (ace - adf - bcf - bde, acf + ade + bce - bdf).
\end{align*}
$$

Therefore, $\[(a,b)(c,d)](e,f) = (a,b)[(c,d)(e,f)]$; in other words, multiplication is associative. The multiplicative identity is $(1,0)$, because

$$
(a,b)(1,0) = (a \cdot 1 - b \cdot 0, a \cdot 0 + b \cdot 1) = (a, b)
$$

and

$$
(1,0)(a,b) = (1 \cdot a - 0 \cdot b, 1 \cdot b + 0 \cdot a) = (a, b).
$$

All that remains to be shown are the distributive laws:

$$
\begin{align*}
    (a,b)\[(c,d) + (e,f)] &= (a,b)(c + e, d + f) \\
    &= (a(c + e) - b(d + f), a(d + f) + b(c + e)) \\
    &= (ac + ae - bd - bf, ad + af + bc + be) \\
    &= ((ac - bd) + (ae - bf), (ad + bc) + (af + be)) \\
    &= (ac - bd, ad + bc) + (ae - bf, af + be) \\
    &= (a,b)(c,d) + (a,b)(e,f)
\end{align*}
$$

and

$$
\begin{align*}
    \[(a,b) + (c,d)](e,f) &= (a + c, b + d)(e,f) \\
    &= ((a + c)e - (b + d)f, (a + c)f + (b + d)e) \\
    &= (ae - bf + ce - df, af + be + cf + de) \\
    &= ((ae - bf) + (ce - df), (af + be) + (cf + de)) \\
    &= (ae - bf, af + be) + (ce - df, cf + de) \\
    &= (a,b)(e,f) + (c,d)(e,f).
\end{align*}
$$

With these operations, $R \times R$ is a ring. When $R =$ℝ, the ring $R \times R$ with these operations is *isomorphic* to the ring of complex numbers ℂ. The elements $(a,b)$ correspond to the complex numbers $a + bi$, and the operations are equivalent to complex addition and multiplication.
