Things to think about

1. What does $\text{Lie}(SU(n) \otimes SU(m))$ looks like? maybe $\mathfrak{su}(n) \otimes \mathfrak{su}(m)$?

The answer is no $\text{Lie}(SU(n) \otimes SU(m))$ is not $\mathfrak{su}(n) \otimes \mathfrak{su}(m)$?. I think the tensor product of the Lie algbra makes the resulting exponential too large. So the quest continues...

KRONCKER SUM is the answer!!! The Kronecker sum is the matrix sum defined by 

$$A \oplus B = A \otimes I_b + I_a \otimes B$$

where $A, B$ are square matrices of order $a, b$ respectively. The Kronecker sum satisfies the **nice** property

$$\exp(A) \otimes \exp(B) = \exp(A\oplus B)$$

So in our case, $SU(n) \otimes SU(m) = \exp(\mathfrak{su}(n)) \otimes \exp(\mathfrak{su}(n)) = \exp(\mathfrak{su}(n) \oplus \mathfrak{su}(m))$

So $\text{Lie}(SU(n) \otimes SU(m)) = \mathfrak{su}(n) \oplus \mathfrak{su}(m)$!

2. Two decomposition is isomorphic if $P\ell_iP^\dagger$ and $Pm_iP^\dagger$. Can I rederive the magic basis?

3. If $\mathfrak{h}, \mathfrak{h}^\prime$ are two maximal abelian subalgebra of $\mathfrak{m}$ can the intersection $\mathfrak{h} \cap \mathfrak{h}^\prime$ be bigger than {0}

4. See if I can make any progress on $\dim(\mathfrak{m}) - \dim(\mathfrak{h}) \leq \dim(\mathfrak{k})$
