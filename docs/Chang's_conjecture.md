---
title: Chang's conjecture
permalink: Chang's_conjecture
---











Chang's conjecture is a model theoretic assertion which implies many
structures of a certain variety have elementary substructures of another
variety. Chang's conjecture was originally formulated in 1963 by Chen
Chung Chang and Vaught.

Chang's conjecture is equiconsistent over $\text{ZFC}$ to the existence
of the
[$\omega_1$-Erdős](Erdos "Erdos")
cardinal. In particular, if you collapse an $\omega_1$-Erdős cardinal
to $\omega_2$ with the Silver collapse, then in the resulting model
Chang's conjecture holds. On the other hand, if Chang's conjecture is
true, then $\omega_2$ is $\omega_1$-Erdős in a transitive inner
model of $\text{ZFC}$.
{% cite Donder1989 %}

Chang's conjecture implies $0^{\\#}$ exists.
{% cite Kanamori2009 %}

## Definition

The notation $(\kappa,\lambda)\twoheadrightarrow(\nu,\mu)$ is the
assertion that every structure $\mathfrak{A}=(A;R^A...)$ with a
countable language such that $\|A\|=\kappa$ and $\|R^A\|=\lambda$ has
a [proper elementary
substructure](Elementary_embedding "Elementary embedding")
$\mathfrak{B}=(B;R^B...)$ with $\|B\|=\nu$ and $\|R^B\|=\mu$.

This notation is somewhat intertwined with the [square bracket partition
properties](Partition_property "Partition property").
Namely, letting $\kappa\geq\lambda$ and
$\kappa\geq\mu\geq\nu>\omega$, the partition property
$\kappa\rightarrow\[\mu\]^{<\omega}_{\lambda,<\nu}$ is
equivalent to the existence of some $\rho<\nu$ such that
$(\kappa,\lambda)\twoheadrightarrow(\mu,\rho)$.
{% cite Kanamori2009 %}

As a result, some large cardinal axioms and partition properties can be
described with this notation. In particular:

-   $\kappa$ is
    [Rowbottom](Rowbottom "Rowbottom")
    if and only if $\kappa>\aleph_1$ and for any uncountable
    $\lambda<\kappa$,
    $(\kappa,\lambda)\twoheadrightarrow(\kappa,\aleph_0)$.
    {% cite Jech2003 %}
-   $\kappa$ is
    [Jónsson](Jonsson "Jonsson")
    if and only if for any $\lambda\leq\kappa$, there is some
    $\nu\leq\kappa$ such that
    $(\kappa,\lambda)\twoheadrightarrow(\kappa,\nu)$.
    {% cite Jech2003 %}

**Chang's conjecture** is precisely
$(\aleph_2,\aleph_1)\twoheadrightarrow(\aleph_1,\aleph_0)$.
Chang's conjecture is equivalent to the [partition
property](Partition_property "Partition property")
$\omega_2\rightarrow\[\omega_1\]_{\aleph_1,<\aleph_1}^{<\omega}$.
{% cite Kanamori2009 %}

## Variants

There are many stronger variants of Chang's conjecture. Here are a few
and their upper bounds for consistency strength (all can be found in
{% cite Eskrew2016 %}):

-   Assuming the consistency of a $\kappa$ which is
    [$\kappa^{++}$-supercompact](Supercompact "Supercompact"),
    it is consistent that there is a proper class of cardinals
    $\lambda$ such that
    $(\lambda^{+++},\lambda^{++})\twoheadrightarrow(\lambda^+,\lambda)$.
-   Assuming the consistency of a $\kappa$ which is
    [$\kappa^{++}$-supercompact](Supercompact "Supercompact"),
    it is consistent that there is a proper class of cardinals $\kappa$
    such that
    $(\lambda^{+\omega+2},\lambda^{+\omega+1})\twoheadrightarrow(\lambda^+,\lambda)$.
-   Assuming the consistency of a cardinal $\kappa$ which is
    [$\kappa^{+\omega+1}$-supercompact](Supercompact "Supercompact"),
    it is consistent that
    $(\aleph_{\omega+1},\aleph_\omega)\twoheadrightarrow(\aleph_1,\aleph_0)$.
-   Assuming the consistency of a
    [huge](Huge "Huge")
    cardinal, it is consistent that
    $(\kappa^{++},\kappa^+)\twoheadrightarrow(\mu^+,\mu)$ for every
    $\kappa$ and $\mu<\kappa^+$.
-   It is unknown whether or not it is consistent that
    $(\aleph_{\omega_1+1},\aleph_{\omega_1})\twoheadrightarrow(\aleph_{\omega+1},\aleph_\omega)$.
