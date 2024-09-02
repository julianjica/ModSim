---
format: 
    revealjs:
        theme: night
---

## Sequences
### Mathematical Modeling I
#### Konrad Lorenz University
::: {.r-fit-text}
$$ F_{n+2} = F_{n+1} + F_{n}$$ 
:::
---

## Introduction to Sequences

A sequence is an ordered list of numbers or other mathematical objects. Each element in a sequence is called a term.

### Definition:
A sequence can be defined as a function whose domain is the set of natural numbers (or a subset of it).

$a: \mathbb{N} \rightarrow \mathbb{R}$

We often write a sequence as $(a_n)_{n=1}^{\infty}$ or simply $(a_n)$.

---

## Types of Sequences

### Finite Sequences
- Have a fixed number of terms
- Example: $(1, 2, 3, 4, 5)$

### Infinite Sequences
- Continue indefinitely
- Example: $(1, 2, 3, 4, \ldots)$

---

## Representing Sequences

### Explicit Formula
- Defines each term directly
- Example: $a_n = 2n + 1$

### Recursive Formula
- Defines each term based on previous terms
- Example: $a_1 = 1, a_n = a_{n-1} + 3$

## Common Sequences

### Arithmetic Sequence
- Each term differs from the previous by a constant
- Formula: $a_n = a_1 + (n-1)d$, where $d$ is the common difference

### Geometric Sequence
- Each term is a constant multiple of the previous
- Formula: $a_n = a_1 \cdot r^{n-1}$, where $r$ is the common ratio

---

### Fibonacci Sequence
- Each term is the sum of the two preceding terms
- Formula: $F_n = F_{n-1} + F_{n-2}$, with $F_1 = F_2 = 1$

## Properties of Sequences

### Monotonicity
- Increasing: $a_n \leq a_{n+1}$ for all $n$
- Decreasing: $a_n \geq a_{n+1}$ for all $n$

### Boundedness
- Upper bound: $\exists M \in \mathbb{R}$ such that $a_n \leq M$ for all $n$
- Lower bound: $\exists m \in \mathbb{R}$ such that $a_n \geq m$ for all $n$

## Limits of Sequences

### Definition
A sequence $(a_n)$ converges to a limit $L$ if:

$\forall \epsilon > 0, \exists N \in \mathbb{N}$ such that $|a_n - L| < \epsilon$ for all $n > N$

We write: $\lim_{n \to \infty} a_n = L$

### Properties of Limits
- Uniqueness
- Algebra of limits (sum, product, quotient)

## Special Limits

### Squeeze Theorem
If $a_n \leq b_n \leq c_n$ for all $n > N$, and $\lim_{n \to \infty} a_n = \lim_{n \to \infty} c_n = L$, then $\lim_{n \to \infty} b_n = L$

### Important Limits
- $\lim_{n \to \infty} \frac{1}{n} = 0$
- $\lim_{n \to \infty} r^n = 0$ if $|r| < 1$
- $\lim_{n \to \infty} \sqrt[n]{n} = 1$
