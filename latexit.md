LaTeX Snippets
==============

This file contains the LaTeX snippets which the [OmniGraffle
document](abstract-algebra-cheatsheet.graffle) includes
via [LaTeXiT](http://www.chachatelier.fr/latexit/). Unless noted otherwise, the
font size in LaTeXiT is 9 pt.

### Algebra

    \begin{tabular}{ll}
    \textsc{Algebra} & $\langle S,\Phi \rangle$\\
    \textsc{Carrier Set} & $S$\\
    \textsc{Operator Set} & $\Phi = \{f_1,\ldots,f_n\}$\\
    \textsc{Operator} & $f_i: S^m \to S$\\
    \textsc{Arity} & $m \in \mathbb{N}_0$\\
    %\textsc{Arity} & $\mathbb{A}(f_i) = m \in \mathbb{N}_0$\\
    %\textsc{Signature} & $\{\mathbb{A}(f_i) \mid f_i \in \Phi\}$
    \end{tabular}

Font size: 12pt

### Magma

    &\langle S,\{\circ\}\rangle\\
    &\circ:S\times S \to S\\
    %&\mathbb{A}(\circ) = 2

### Associativity

    \centering
    \textsc{Associativity}\\
    $(x \circ y) \circ z = x \circ (y \circ z)$

### Identity

    \centering
    \textsc{Identity}\\
    $1 \circ x = x \circ 1 = x$

### Inverse

    \centering
    \textsc{inverse}\\
    ${-x} \circ x = x \circ {-x} = 1$

### Commutativity

    \centering
    \textsc{Commutativity}\\
    $x \circ y = y \circ x$

### Semiring

    &\langle S, \{\oplus,\odot\} \rangle\\
    &\oplus: S \times S \to S\\
    &\odot: S \times S \to S\\
    %&\mathbb{A}(\oplus) = 2\\
    %&\mathbb{A}(\odot) = 2

    1.\; & \textsc{Commutative Monoid}\;\langle S, \oplus\rangle\\ 
         &\textsc{Additive Identity}\;0\in S\\ 
    2.\; & \textsc{Monoid}\;\langle S, \odot\rangle\\
         &\textsc{Multiplicative Identity}\;1\in S\\ 
    3.\; & \textsc{Distributivity}\\
    & x \odot (y \oplus z) = (x \odot y) \oplus (x \odot z)\\
    & (y \oplus z) \odot x = (y \odot z) \oplus (z \odot x) \\

### Semiring -> Ring

    \centering
    \textsc{Commutative Group}\\
    $\langle S, \oplus \rangle$

### Ring -> Commutative Ring

    \centering
    \textsc{Commutative Monoid}\\
    $\langle S, \odot \rangle$

### Commutative Ring -> Integral Domain

    \centering
    \textsc{No Zero Divisors}\\
    $\forall x,y \in S\setminus\{0\}: xy \ne 0$

### Ring -> Field

    \centering
    \textsc{Commutative Group}\\
    $\langle S, \odot \rangle$

