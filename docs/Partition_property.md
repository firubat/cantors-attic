---
title: Partition property
permalink: Partition_property
---

A partition property is an infinitary combinatorical principle in set
theory. Partition properties are best associated with various [large
cardinal
axioms](Upper_attic "Upper attic")
(all of which are below
[measurable](Measurable "Measurable")),
but can also be associated with infinite graphs.

The **pigeonhole principle** famously states that if there are $n$
pigeons in $n-m$ holes, then at least one hole contains at least $m$
pigeons. Partition properties are best motivated as generalizations of
the pigeonhole principle to infinite cardinals. For example, if there
are $\aleph_1$ pigeons and there are $\aleph_0$ many holes, then at
least one hole contains $\aleph_1$ pigeons.

## Definitions

There are quite a few definitions involved with partition properties. In
fact, partition calculus, the study of partition properties, almost
completely either comprisse or describes most of infinitary
combinatorics itself, so it would make sense that the terminology
involved with it is quite unique.

### Square Bracket Notation

The square bracket notation is somewhat simple and easy to grasp (and
used in many other places). Let $X$ be a set of ordinals. $\[X\]^\beta$
for some ordinal $\beta$ is the set of all subsets $x\subseteq X$ such
that $(x,<)$ has order-type $\beta$; that is, there is a bijection
$f$ from $x$ to $\beta$ such that $f(a)<f(b)$ iff $a<b$ for each
$a$ and $b$ in $x$. Such a bijection is often called an
order-isomorphism.

$\[X\]^{<\beta}$ for some ordinal $\beta$ is simply defined as the
union of all $\[X\]^{\alpha}$ for $\alpha<\beta$, the set of all
subsets $x\subseteq X$ with order-type less than $\beta$. In the case
of $\omega$, $\[X\]^{<\omega}$ is the set of all finite subsets of
$X$.

### Homogeneous Sets

Let $f:\[\kappa\]^\beta\rightarrow\lambda$ be a function (in this
study, such functions are often called partitions). A set
$H\subseteq\kappa$ is then called **homogeneous for $f$** when for any
two subsets $h_0,h_1\subseteq H$ of order type $\beta$,
$f(h_0)=f(h_1)$. This is equivalent to $f$ being constant on
$\[H\]^\beta$.

In another case, let $f:\[\kappa\]^{<\omega}\rightarrow\lambda$
be a function. A set $H\subseteq\kappa$ is then called **homogeneous
for $f$** when for any two finite subsets $h_0,h_1\subseteq H$ of the
same size, $f(h_0)=f(h_1)$.

### The Various Partition Properties

Let $\kappa$ and $\lambda$ be cardinals and let $\alpha$ and $\beta$
be ordinals. Then, the following notations are used for the partition
properties:

-   $\kappa\rightarrow (\alpha)_\lambda^\beta$ iff for every
    function $f:\[\kappa\]^\beta\rightarrow\lambda$, there is set
    $H$ of order-type $\alpha$ which is homogeneous for $f$. If
    $\alpha$ is a cardinal (which it most often is), then the
    requirement on $H$ can be loosened to $H$ having cardinality
    $\alpha$ and being homogeneous for $f$ without loss of generality.
    {% cite Kanamori2009 %}
-   A common abbreviation for $\kappa\rightarrow (\alpha)_2^n$ is
    $\kappa\rightarrow (\alpha)^n$.
-   $\kappa\rightarrow (\alpha)_\lambda^{<\omega}$ iff for
    every function $f:\[\kappa\]^{<\omega}\rightarrow\lambda$,
    there is set $H$ of order-type $\alpha$ which is homogeneous for
    $f$. If $\alpha$ is a cardinal (which it most often is), then the
    requirement on $H$ can be loosened to $H$ having cardinality
    $\alpha$ and being homogeneous for $f$ without loss of generality.
    {% cite Kanamori2009 %}

Let $\nu$ be a cardinal. The **square bracket partition properties**
are defined as follows:

-   $\kappa\rightarrow \[\alpha\]_\lambda^\beta$ iff for every
    function $f:\[\kappa\]^\beta\rightarrow\lambda$, there is set
    $H$ of order-type $\alpha$ and an ordinal $\gamma<\lambda$
    such that $f(h)\neq\gamma$ for any $h\in \[H\]^\beta$.
-   $\kappa\rightarrow \[\alpha\]_\lambda^{<\omega}$ iff for
    every function $f:\[\kappa\]^{<\omega}\rightarrow\lambda$,
    there is set $H$ of order-type $\alpha$ and an ordinal
    $\gamma<\lambda$ such that $f(h)\neq\gamma$ for any finite
    subset $h$ of $H$.
-   $\kappa\rightarrow \[\alpha\]_{\lambda,<\nu}^\beta$ iff
    for every function $f:\[\kappa\]^\beta\rightarrow\lambda$, there
    is set $H$ of order-type $\alpha$ such that $f$ restricted to
    $\[H\]^\beta$ yields less than $\nu$-many distinct outputs. Note
    that $\kappa\rightarrow\[\alpha\]_{\lambda,<2}^\beta$ iff
    $\kappa\rightarrow(\alpha)_\lambda^\beta$.
-   $\kappa\rightarrow \[\alpha\]_{\lambda,<\nu}^{<\omega}$
    iff for every function
    $f:\[\kappa\]^{<\omega}\rightarrow\lambda$, there is set $H$
    of order-type $\alpha$ such that $f$ restricted to
    $\[H\]^{<\omega}$ yields less than $\nu$-many distinct outputs.

## Theorems and Large Cardinal Axioms

There are several theorems in the study of partition calculus. Namely:

-   Ramsey's theorem, which states that $\aleph_0\rightarrow
    (\omega)_m^n$ for each finite $m$ and $n$.
    {% cite Jech2003 %}
-   $2^\kappa\not\rightarrow (\kappa^+)^2$
    {% cite Jech2003 %}
-   The Erdős-Rado theorem, which states that
    $\beth_n(\kappa)^+\rightarrow (\kappa^+)_\kappa^{n+1}$.
    {% cite Kanamori2009 %}
-   $\kappa\not\rightarrow(\omega)_2^\omega$
    {% cite Kanamori2009 %}
-   For any finite nonzero $n$ and ordinals $\alpha$ and $\beta$,
    there is a $\kappa$ such that
    $\kappa\rightarrow(\alpha)_\beta^n$.
    {% cite Kanamori2009 %}
-   The Gödel-Erdős-Kakutani theorem, which states that
    $2^\kappa\not\rightarrow (3)^2_\kappa$.
    {% cite Kanamori2009 %}
-   $\kappa\not\rightarrow \[\kappa\]_\kappa^\omega$.
    {% cite Kanamori2009 %}
-   $\lambda^+\not\rightarrow\[\lambda+1\]^2_{\lambda,<\lambda}$
    {% cite Kanamori2009 %}
-   $\lambda\not\rightarrow\[\lambda\]^1_{\mathrm{cf}(\lambda),<\mathrm{cf}(\lambda)}$
    {% cite Kanamori2009 %}
-   For any regular $\kappa$,
    $\kappa^+\not\rightarrow\[\kappa^+\]^2_{\kappa^+}$.
    {% cite Kanamori2009 %}
-   For any
    [inaccessible](Inaccessible "Inaccessible")
    cardinal $\kappa$, $\kappa\rightarrow(\lambda)_\lambda^2$ for
    any $\lambda<\kappa$ {% cite Drake1974 %} .
    However, this may not be an equivalence; if the
    <a href="Continuum_hypothesis" class="mw-redirect" title="Continuum hypothesis">continuum hypothesis</a>
    holds at $\kappa$, then
    $(\kappa^{++})\rightarrow(\lambda)^2_\kappa$ for any
    $\lambda<\kappa^{++}$.

In terms of large cardinal axioms, many can be described using a
partition property. Here are those which can be found on this website:

-   Although not a large cardinal itself, [Chang's
    conjecture](Chang%27s_conjecture "Chang's conjecture")
    holds iff
    $\aleph_2\rightarrow\[\omega_1\]^{<\omega}_{\aleph_1,<\aleph_1}$,
    iff
    $\aleph_2\rightarrow\[\omega_1\]^{n}_{\aleph_1,<\aleph_1}$
    for some $n$, iff
    $\aleph_2\rightarrow\[\omega_1\]^{n}_{\aleph_1,<\aleph_1}$
    for every finite $n$. {% cite Kanamori2009 %}
-   A cardinal $\kappa$ is
    [Ramsey](Ramsey "Ramsey")
    iff $\kappa\rightarrow(\kappa)_\lambda^{<\omega}$ for some
    $\lambda>1$, iff
    $\kappa\rightarrow(\kappa)_\lambda^{<\omega}$ for every
    $\lambda<\kappa$.
    {% cite Kanamori2009 Jech2003 %}
-   A cardinal $\kappa$ is the
    [$\alpha$-Erdős](Erdos "Erdos")
    cardinal iff it is the smallest $\kappa$ such that
    $\kappa\rightarrow(\alpha)^{<\omega}$.
-   A cardinal $\kappa$ is defined to be
    [$\nu$-Rowbottom](Rowbottom "Rowbottom")
    iff
    $\kappa\rightarrow\[\kappa\]_{\lambda,<\nu}^{<\omega}$
    for every $\lambda<\kappa$.
-   A cardinal $\kappa$ is
    [Jónsson](Jonsson "Jonsson")
    iff $\kappa\rightarrow\[\kappa\]_\kappa^{<\omega}$.
    {% cite Kanamori2009 %}
-   A cardinal $\kappa$ is [weakly
    compact](Weakly_compact "Weakly compact")
    iff $\kappa\rightarrow(\kappa)^2_\lambda$ for some
    $\lambda>1$, iff $\kappa\rightarrow(\kappa)^2_\lambda$ for
    every $\lambda<\kappa$. {% cite Jech2003 %}
