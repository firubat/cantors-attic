---
title: Weakly compact cardinal
permalink: Weakly_compact
---

Weakly compact cardinals lie at the focal point of a number of diverse
concepts in infinite combinatorics, admitting various characterizations
in terms of these concepts. If $\kappa^{ {<}\kappa} = \kappa$, then
the following are equivalent:

Weak compactness   
A cardinal $\kappa$ is weakly compact if and only if it is
<a href="Uncountable" class="mw-redirect" title="Uncountable">uncountable</a>
and every $\kappa$-satisfiable theory in an
[$\mathcal{L}_{\kappa,\kappa}$](Infinitary_logic "Infinitary logic")
language of size at most $\kappa$ is satisfiable.

Extension property   
A cardinal $\kappa$ is weakly compact if and only if for every
$A\subset V_\kappa$, there is a transitive structure $W$ properly
extending $V_\kappa$ and $A^*\subset W$ such that $\langle
V_\kappa,{\in},A\rangle\prec\langle W,{\in},A^*\rangle$.

Tree property   
A cardinal $\kappa$ is weakly compact if and only if it is
[inaccessible](Inaccessible "Inaccessible")
and has the [tree
property](Tree_property "Tree property").

Filter property   
A cardinal $\kappa$ is weakly compact if and only if whenever $M$ is a
set containing at most $\kappa$-many subsets of $\kappa$, then there
is a $\kappa$-[complete nonprincipal
filter](Filter "Filter")
$F$ measuring every set in $M$.

Weak embedding property   
A cardinal $\kappa$ is weakly compact if and only if for every
$A\subset\kappa$ there is a transitive set $M$ of size $\kappa$ with
$\kappa\in M$ and a transitive set $N$ with an
[embedding](Elementary_embedding "Elementary embedding")
$j:M\to N$ with
<a href="Critical_point" class="mw-redirect" title="Critical point">critical point</a>
$\kappa$.

Embedding characterization   
A cardinal $\kappa$ is weakly compact if and only if for every
transitive set $M$ of size $\kappa$ with $\kappa\in M$ there is a
transitive set $N$ and an embedding $j:M\to N$ with critical point
$\kappa$.

Normal embedding characterization   
A cardinal $\kappa$ is weakly compact if and only if for every
$\kappa$-model $M$ there is a $\kappa$-model $N$ and an embedding
$j:M\to N$ with critical point $\kappa$, such that $N=\{\
j(f)(\kappa)\mid f\in M\ \}$.

Hauser embedding characterization   
A cardinal $\kappa$ is weakly compact if and only if for every
$\kappa$-model $M$ there is a $\kappa$-model $N$ and an embedding
$j:M\to N$ with critical point $\kappa$ such that $j,M\in N$.

Partition property   
A cardinal $\kappa$ is weakly compact if and only if the [partition
property](Partition_property "Partition property")
$\kappa\to(\kappa)^2_2$ holds.

Indescribability property   
A cardinal $\kappa$ is weakly compact if and only if it is
$\Pi_1^1$-[indescribable](Indescribable "Indescribable").

Skolem Property   
A cardinal $\kappa$ is weakly compact if and only if $\kappa$ is
inaccessible and every $\kappa$-unboundedly satisfiable
$\mathcal{L}_{\kappa,\kappa}$-theory $T$ of size at most $\kappa$
has a model of size at least $\kappa$. A theory $T$ is
$\kappa$-unboundedly satisfiable if and only if for any
$\lambda<\kappa$, there exists a model $\mathcal{M}\models T$
with $\lambda\leq\|M\|<\kappa$. For more info see
<a href="https://mathoverflow.net/questions/309896/a-weakening-of-cardinal-compactness-is-it-equivalent/309937#309937" class="external text">here</a>.

Weakly compact cardinals first arose in connection with (and were named
for) the question of whether certain [infinitary
logics](Infinitary_logic "Infinitary logic")
satisfy the compactness theorem of first order logic. Specifically, in a
language with a signature consisting, as in the first order context, of
a set of constant, finitary function and relation symbols, we build up
the language of $\mathcal{L}_{\kappa,\lambda}$ formulas by closing
the collection of formulas under infinitary conjunctions
$\wedge_{\alpha<\delta}\varphi_\alpha$ and disjunctions
$\vee_{\alpha<\delta}\varphi_\alpha$ of any size
$\delta<\kappa$, as well as infinitary quantification
$\exists\vec x$ and $\forall\vec x$ over blocks of variables $\vec
x=\langle x_\alpha\mid\alpha<\delta\rangle$ of size less than
$\kappa$. A theory in such a language is *satisfiable* if it has a
model under the natural semantics. A theory is *$\theta$-satisfiable*
if every subtheory consisting of fewer than $\theta$ many sentences of
it is satisfiable. First order logic is precisely
$L_{\omega,\omega}$, and the classical Compactness theorem asserts
that every $\omega$-satisfiable $\mathcal{L}_{\omega,\omega}$
theory is satisfiable. A uncountable cardinal $\kappa$ is *[strongly
compact](Strongly_compact "Strongly compact")*
if every $\kappa$-satisfiable $\mathcal{L}_{\kappa,\kappa}$ theory
is satisfiable. The cardinal $\kappa$ is *weakly compact* if every
$\kappa$-satisfiable $\mathcal{L}_{\kappa,\kappa}$ theory, in a
language having at most $\kappa$ many constant, function and relation
symbols, is satisfiable.

Next, for any cardinal $\kappa$, a *$\kappa$-tree* is a tree of height
$\kappa$, all of whose levels have size less than $\kappa$. More
specifically, $T$ is a *tree* if $T$ is a partial order such that the
predecessors of any node in $T$ are well ordered. The $\alpha^{\rm
th}$ level of a tree $T$, denoted $T_\alpha$, consists of the nodes
whose predecessors have order type exactly $\alpha$, and these nodes
are also said to have *height* $\alpha$. The height of the tree $T$ is
the first $\alpha$ for which $T$ has no nodes of height $\alpha$. A
""$\kappa$-branch"" through a tree $T$ is a maximal linearly ordered
subset of $T$ of order type $\kappa$. Such a branch selects exactly one
node from each level, in a linearly ordered manner. The set of
$\kappa$-branches is denoted $\[T\]$. A $\kappa$-tree is an
*Aronszajn* tree if it has no $\kappa$-branches. A cardinal $\kappa$
has the *tree property* if every $\kappa$-tree has a $\kappa$-branch.

A transitive set $M$ is a $\kappa$-model of set theory if
$\|M\|=\kappa$, $M^{\lt\kappa}\subset M$ and $M$ satisfies ZFC$^-$,
the theory ZFC without the power set axiom (and using collection and
separation rather than merely replacement). For any infinite cardinal
$\kappa$ we have that $H_{\kappa^+}$ models ZFC$^-$, and further, if
$M\prec H_{\kappa^+}$ and $\kappa\subset M$, then $M$ is
transitive. Thus, any $A\in H_{\kappa^+}$ can be placed into such an
$M$. If $\kappa^{\lt\kappa}=\kappa$, one can use the downward
Löwenheim-Skolem theorem to find such $M$ with $M^{\lt\kappa}\subset
M$. So in this case there are abundant $\kappa$-models of set theory
(and conversely, if there is a $\kappa$-model of set theory, then
$2^{\lt\kappa}=\kappa$).

The partition property $\kappa\to(\lambda)^n_\gamma$ asserts that
for every function $F:\[\kappa\]^n\to\gamma$ there is
$H\subset\kappa$ with $\|H\|=\lambda$ such that
$F\upharpoonright\[H\]^n$ is constant. If one thinks of $F$ as coloring
the $n$-tuples, the partition property asserts the existence of a
*monochromatic* set $H$, since all tuples from $H$ get the same color.
The partition property $\kappa\to(\kappa)^2_2$ asserts that every
partition of $\[\kappa\]^2$ into two sets admits a set
$H\subset\kappa$ of size $\kappa$ such that $\[H\]^2$ lies on one
side of the partition. When defining $F:\[\kappa\]^n\to\gamma$, we
define $F(\alpha_1,\ldots,\alpha_n)$ only when
$\alpha_1<\cdots<\alpha_n$.

## Weakly compact cardinals and the constructible universe

Every weakly compact cardinal is weakly compact in
[$L$](Constructible_universe "Constructible universe").
{% cite Jech2003 %}

Nevertheless, the weak compactness property is not generally downward
absolute between transitive models of set theory.

  

## Weakly compact cardinals and forcing

-   Weakly compact cardinals are invariant under small forcing.
    <a href="http://www.math.csi.cuny.edu/~fuchs/IndestructibleWeakCompactness.pdf" class="external autonumber">[1]</a>
-   Weakly compact cardinals are preserved by the canonical forcing of
    the GCH, by fast function forcing and many other forcing notions \[
    [*citation
    needed*](Library "Library")
    \].
-   If $\kappa$ is weakly compact, there is a forcing extension in
    which $\kappa$ remains weakly compact and $2^\kappa\gt\kappa$ \[
    [*citation
    needed*](Library "Library")
    \].
-   If the existence of weakly compact cardinals is consistent with ZFC,
    then there is a model of ZFC in which $\kappa$ is not weakly
    compact, but becomes weakly compact in a forcing extension
    {% cite Kunen1978 %}.

## Indestructibility of a weakly compact cardinal

*To expand using
<a href="https://arxiv.org/abs/math/9907046" class="external autonumber">[2]</a>*

## Relations with other large cardinals

-   Every weakly compact cardinal is
    [inaccessible](Inaccessible "Inaccessible"),
    [Mahlo](Mahlo "Mahlo"),
    hyper-Mahlo, hyper-hyper-Mahlo and more.
-   [Measurable](Measurable "Measurable")
    cardinals,
    [Ramsey](Ramsey "Ramsey")
    cardinals, and [totally
    indescribable](Indescribable "Indescribable")
    cardinals are all weakly compact and a stationary limit of weakly
    compact cardinals.
-   Assuming the consistency of a
    <a href="Strongly_unfoldable" class="mw-redirect" title="Strongly unfoldable">strongly unfoldable</a>
    cardinal with ZFC, it is also consistent for the least weakly
    compact cardinal to be the least
    [unfoldable](Unfoldable "Unfoldable")
    cardinal.
    {% cite Cody2013 %}
-   If GCH holds, then the least weakly compact cardinal is not [weakly
    measurable](Weakly_measurable "Weakly measurable").
    However, if there is a
    [measurable](Measurable "Measurable")
    cardinal, then it is consistent for the least weakly compact
    cardinal to be weakly measurable.
    {% cite Cody2013 %}
-   If it is consistent for there to be a [nearly
    supercompact](Nearly_supercompact "Nearly supercompact"),
    then it is consistent for the least weakly compact cardinal to be
    nearly supercompact.
    {% cite Cody2013 %}
-   For a cardinal $κ=κ^{<κ}$, $κ$ is weakly compact iff it is
    0-[Ramsey](Ramsey "Ramsey").
    {% cite Nielsen2018 %}

## $\Sigma_n$-weakly compact etc.

An inaccessible cardinal $κ$ is $Σ_n$-weakly compact iff it reflects
$Π_1^1$ sentences with $Σ_n$-predicates, i.e. for every $R ⊆ V_κ$
which is definable by a $Σ_n$ formula (with parameters) over $V_κ$ and
every $Π_1^1$ sentence $Φ$, if $\langle V_κ , ∈, R \rangle \models
Φ$ then there is $α < κ$ (equivalently, unboundedly-many $α < κ$)
such that $\langle V_α , ∈, R ∩ V_α \rangle \models Φ$. Analogously
for $Π_n$ and $∆_n$. $κ$ is $Σ_ω$-weakly compact iff it is
$Σ_n$-weakly compact for all $n < ω$.

$κ$ is $Σ_n$-weakly compact $\iff$ $κ$ is $Π_n$-weakly compact
$\iff$ $κ$ is $∆_{n+1}$-weakly compact $\iff$ For every $Π_1^1$
formula $Φ(x_0 , ..., x_k)$ in the language of set theory and every
$a_0 , ..., a_k ∈ V_κ$, if $V κ \models Φ(a_0 , ..., a_k )$, then
there is $λ ∈ I_n := \{λ < κ : λ$ is inaccessible and $V_λ
\preccurlyeq_n V_κ\}$ such that $V_λ \models Φ(a_0 , ..., a_k)$.

In {% cite Bosch2006 %} it is shown
that every $Σ_ω$-w.c. cardinal is
$Σ_ω$-[Mahlo](Mahlo "Mahlo")
and the set of $Σ_ω$-Mahlo cardinals below a $Σ_ω$-w.c. cardinal is
$Σ_ω$-stationary, but if κ is $Π_{n+1}$-Mahlo, then the set of
$Σ_n$-w.c. cardinals below $κ$ is $Π_{n+1}$-stationary.

These properties are connected with some forms of absoluteness. For
example, the existence of a $Σ_ω$-w.c. cardinal is equiconsistent with
the
<a href="index.php?title=Generic_absoluteness_axiom&amp;action=edit&amp;redlink=1" class="new" title="Generic absoluteness axiom (page does not exist)">generic absoluteness axiom</a>
$\mathcal{A}(L(\mathbb{R}), \underset{\sim}{Σ}_ω , Γ)$ where $Γ$ is
the class of projective ccc forcing notions.

This section
from {% cite Leshem2000 Bagaria2006 %}
