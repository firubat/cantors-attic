---
title: The ordinals of infinite time Turing machines
permalink: Infinite_time_Turing_machines
---











  
The theory of infinite time Turing machines extends the operation of
ordinary Turing machines into transfinite ordinal time. At successor
stages of computations, the machines compute as expected, according to
the rigid instructions of their finite programs, writing on the tape,
moving the head to the left or right and changing to a new state. At
limit stages, the information the computation was producing is preserved
in a sense: each cell of the tape assumes the limsup of its values going
into that limit; the head is reset to the left-most cell and the state
is placed in the *limit* state, a distinguished state like the *start*
state and the *halt* state.

A real is *writable* by such machines if there is a program which on
trivial input can write that real on the output tape and then halt. A
real is *eventually writable* if there is a program that on trivial
input can write the real on the output tape in such a way that from some
point on, the output tape exhibits that real as its final stabilized
value, even if the machine does not halt. A real is *accidently
writable* if it appears on one of the tapes during the course of a
computation of a program on trivial input. See 
{% cite Hamkins2000 Hamkins2002 Hamkins2004 %}

Similarly, an ordinal is writable or eventually writable or accidentally
writable if it is the order type of a relation coded by such a kind of
real.

-   $\lambda=$ the supremum of the writable ordinals
-   $\zeta=$ the supremum of the eventually writable ordinals
-   $\Sigma=$ the supremum of the accidentally writable ordinals

Hamkins and Lewis {% cite Hamkins2000 %}
showed that $\lambda\lt\zeta\lt\Sigma$, and while $\lambda$ and
$\zeta$ are
[admissible](Admissible "Admissible")
ordinals and [computably
inaccessible](Admissible#Computably_inaccessible_ordinal "Admissible"),
$\Sigma$ is not admissible.

Welch {% cite Welch2000 %} proved the $\lambda-\zeta-\Sigma$
theorem, asserting that
$L_\lambda\prec_{\Sigma_1}L_\zeta\prec_{\Sigma_2}L_\Sigma$,
and furthermore $\lambda$ is the least ordinal such that $L_\lambda$
has a $\Sigma_1$-elementary end-extension, and $\zeta$ is least such
that $L_\zeta$ has a $\Sigma_2$-elementary end-extension.
