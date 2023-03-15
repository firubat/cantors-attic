---
title: Woodin cardinal
permalink: Woodin
redirect_from:
  - Shelah
---

**Woodin cardinals** (named after W. Hugh Woodin) are a generalization
of the notion of strong cardinals and have been used to calibrate the
exact proof-theoretic strength of the [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy").
They can also be seen as weakenings of *Shelah cardinals*, defined
below. Their exact definition has several equivalent but different
characterizations, each of which is somewhat technical in nature.
Nevertheless, an inner model theory encapsulating infinitely many Woodin
cardinals and slightly beyond has been developed.

## Definition and some properties

We first introduce the concept of *$\gamma$-strongness for $A$*: an
ordinal $\kappa$ is *$\gamma$-strong for $A$* (or
$\gamma$-$A$-strong) if there exists a nontrivial elementary embedding
$j:V\to M$ with critical point $\kappa$ such that
$V_{\kappa+\gamma}\subseteq M$ and $A\cap V_{\kappa+\gamma} =
j(A)\cap V_{\kappa+\gamma}$. Intuitively, $j$ preserves the part of
$A$ that is in $V_{\kappa+\gamma}$. We say that a cardinal $\kappa$
is <$\delta$-$A$-strong if it is $\gamma$-$A$-strong for all
$\gamma<\delta$.

We also introduce *Woodin-ness in $\delta$*: for an infinite ordinal
$\delta$, a set $X\subseteq\delta$ is *Woodin in $\delta$* if for
every function $f:\delta\to\delta$, there is an ordinal $\kappa\in
X$ with $\{f(\beta):\beta<\kappa\}\subseteq\kappa$ ($\kappa$
is closed under $f$), there exists a nontrivial [elementary
embedding](Elementary_embedding "Elementary embedding")
$j:V\to M$ with critical point $\kappa$ such that
$V_{j(f)(\kappa)}\subseteq M$.

An
[inaccessible](Inaccessible "Inaccessible")
cardinal $\delta$ is **Woodin** if any of the following (equivalent)
characterizations holds {% cite Kanamori2009 %}:

-   For any set $A\subseteq V_\delta$, there exists a
    $\kappa<\delta$ that is <$\delta$-$A$-strong.
-   For any set $A\subseteq V_\delta$, the set
    $S=\{\kappa<\delta:\kappa$ is <$\delta$-$A$-strong$\}$
    is
    <a href="Stationary" class="mw-redirect" title="Stationary">stationary</a>
    in $\delta$.
-   The set $F=\{X\subseteq \delta:\delta\setminus X$ is not
    *Woodin in $\delta$*$\}$ is a proper
    [filter](Filter "Filter"),
    the *Woodin filter* over $\delta$.
-   For every function $f:\delta\to\delta$ there exists
    $\kappa<\delta$ such that
    $\{f(\beta):\beta\in\kappa\}\subseteq\kappa$ (that is,
    $\kappa$ is closed under $f$) and there exists a nontrivial
    elementary embedding $j:V\to M$ with critical point $\kappa$ such
    that $V_{j(f)(\kappa)}\subseteq M$.

Let $\delta$ be Woodin, $F$ be the Woodin filter over $\delta$, and
$S=\{\kappa<\delta:\kappa$ is <$\delta$-$A$-strong$\}$. Then
$F$ is normal and $S\in F$.
{% cite Kanamori2009 %} This implies every Woodin
cardinal is
[Mahlo](Mahlo "Mahlo") and
preceeded by a stationary set of
[measurable](Measurable "Measurable")
cardinals, in fact of
<$\delta$-[strong](Strong "Strong")
cardinals. However, the least Woodin cardinal is not [weakly
compact](Weakly_compact "Weakly compact")
as it is not
$\Pi^1_1$-[indescribable](Indescribable "Indescribable").

Woodin cardinals are weaker consistency-wise then
[superstrong](Superstrong "Superstrong")
cardinals. In fact, every superstrong is preceeded by a stationary set
of Woodin cardinals. On the other hand the existence of a Woodin is much
stronger than the existence of a proper class of strong cardinals.

The existence of a Woodin cardinal implies the consistency of
$\text{ZFC}$ + "the [nonstationary
ideal](Filter "Filter") on
$\omega_1$ is $\omega_2$-saturated".
[Huge](Huge "Huge")
cardinals were first invented to prove the consistency of the existence
of a $\omega_2$-saturated $\sigma$-ideal on $\omega_1$, but turned
out to be stronger than required, as a Woodin is enough.

## Shelah cardinals

Shelah cardinals were introduced by Shelah and Woodin as a weakening of
the necessary hypothesis required to show several regularity properties
of sets of reals hold in the model $L(\mathbb{R})$ (e.g., every set of
reals is Lebesgue measurable and has the property of Baire, etc...). In
slightly more detail, Woodin had established that the [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy")
(a hypothesis known to imply regularity properties for sets of reals)
holds in $L(\mathbb{R})$ assuming the existence of a nontrivial
elementary embedding $j:L(V_{\lambda+1})\to L(V_{\lambda+1})$ with
critical point $<\lambda$. This axiom, a
<a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">rank-into-rank</a>
axiom, is known to be very strong and its use was first weakened to that
of the existence of a
[supercompact](Supercompact "Supercompact")
cardinal. Following the work of Foreman, Magidor and Shelah on saturated
ideals on $\omega_1$, Woodin and Shelah subsequently isolated the two
large cardinal hypotheses which bear their name and turn out to be
sufficient to establish the [regularity
properties](Projective#Regularity_properties "Projective")
of sets of reals mentioned above.

Shelah cardinals were the first cardinals to be devised by Woodin and
Shelah. A cardinal $\delta$ is *Shelah* if for every function
$f:\delta\to\delta$ there exists a nontrivial elementary embedding
$j:V\to M$ with critical point $\delta$ such that
$V_{j(f)(\delta)}\subseteq M$. Every Shelah is Woodin, but not every
Woodin is Shelah: indeed, Shelah cardinals are always measurable and in
fact
[strong](Strong "Strong"),
while Woodins are usually not. However, just like Woodins, Shelah
cardinals are weaker consistency-wise than superstrong cardinals.

A related notion is *Shelah-for-supercompactness*, where the closure
condition $V_{j(f)(\delta)}\subseteq M$ is replaced by
$M^{j(f)(\delta)}\subseteq M$, a much stronger condition. The
difference between Shelah and Shelah-for-supercompactness cardinals is
essentially the same as the difference between strong and
[supercompact](Supercompact "Supercompact")
cardinals, or between
[superstrong](Superstrong "Superstrong")
and [huge](Huge "Huge")
cardinals. Also, just like every Shelah is preceeded by a stationary set
of strong cardinals, every Shelah-for-supercompactness cardinal is
preceeded by a stationary set of supercompact cardinals.

Much weaker, consistent with $V=L$ variant: A cardinal $κ$ is
**virtually Shelah for supercompactness** iff for every function $f : κ
→ κ$ there are $λ > κ$ and $\bar{λ}< κ$ such that in a
set-forcing extension there is an elementary embedding $j :
V_{\bar{λ}}→ V_{λ}$ with $j(\mathrm{crit}(j)) = κ$, $\bar{λ} ≥
f(\mathrm{crit}(j))$ and $f ∈ \mathrm{ran}(j)$. If $κ$ is virtually
Shelah for supercompactness, then $V_κ$ is a model of proper class many
virtually
$C^{(n)}$-[extendible](Extendible "Extendible")
cardinals for every $n < ω$ and if κ is
2-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>,
then $V_κ$ is a model of proper class many virtually Shelah for
supercompactness
cardinals.{% cite Gitmana %}

## Woodin for strong compactness

(from {% cite Dimopoulos2019 %} unless
otherwise noted)

A cardinal $δ$ is **Woodin for strong compactness** (or *Woodinised
strongly compact*) iff for every $A ⊆ δ$ there is $κ < δ$ which is
$<δ$-[strongly
compact](Strongly_compact "Strongly compact")
for $A$.

This definition is obviously analogous to one of the characterisations
of Woodin and *Woodin-for-supercompactness* (Perlmutter proved that
{% cite Perlmutter2010 %}
it is equivalent to
[Vopěnkaness](Vopenka "Vopenka"))
cardinals.

Results:

-   Woodin for strong compactness cardinal $δ$ is an
    [inaccessible](Inaccessible "Inaccessible")
    limits of $<δ$-strongly compact cardinals.
-   $κ$ is Woodin and there are unboundedly many $<δ$-supercompact
    cardinals below $δ$, then $δ$ is Woodin for strong compactness.
-   The existence of a Woodin for strong compactness cardinal is at
    least as strong as a proper class of strongly compact cardinals and
    at most as strong as a Woodin limit of supercompact cardinals (which
    lies below an extendible cardinal).

## Woodin cardinals and determinacy

*See also: [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy"),
[axiom of projective
determinacy](Projective#Projective_determinacy "Projective")*

Woodin cardinals are linked to different forms of the [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy")
{% cite Kanamori2009 Larson2013 Koellner2010 %}:

-   $\text{ZF+AD}$, $\text{ZFC+AD}^{L(\mathbb{R})}$, ZFC+"the
    non-stationary ideal over $\omega_1$ is $\omega_1$-dense" and
    $\text{ZFC}$+"there exists infinitely many Woodin cardinals" are
    equiconsistent.
-   Under $\text{ZF+AD}$, the model $\text{HOD}^{L(\mathbb{R})}$
    satisfies $\text{ZFC}$+"$\Theta^{L(\mathbb{R})}$ is a Woodin
    cardinal". {% cite Koellner2010 %} gives many
    generalizations of this result.
-   If there exists infinitely many Woodin cardinals with a measurable
    above them all, then $\text{AD}^{L(\mathbb{R})}$. If there
    assumtion that there is a measurable above those Woodins is removed,
    one still has projective determinacy.
-   In fact projective determinacy is equivalent to "for every
    $n<\omega$, there is a fine-structural, countably iterable inner
    model $M$ such that $M$ satisfies $\text{ZFC}$+"there exists $n$
    Woodin cardinals".
-   For every $n$, if there exists $n$ Woodin cardinals with a
    measurable above them all, then all $\mathbf{\Sigma}^1_{n+1}$
    sets are determined.
-   $\mathbf{\Pi}^1_2$-determinacy is equivalent to "for every
    $x\in\mathbb{R}$, there is a countable ordinal $\delta$ such that
    $\delta$ is a Woodin cardinal in some inner model of $\text{ZFC}$
    containing $x$.
-   $\mathbf{\Delta}^1_2$-determinacy is equivalent to "for every
    $x\in\mathbb{R}$, there is an inner model M such that $x\in M$
    and $M$ satisfies ZFC+"there is a Woodin cardinal".
-   $\text{ZFC}$ + *lightface* $\Delta^1_2$-determinacy implies that
    there many $x$ such that $\text{HOD}^{L\[x\]}$ satisfies
    $\text{ZFC}$+"$\omega_2^{L\[x\]}$ is a Woodin cardinal".
-   $\text{Z}_2+\Delta^1_2$-determinacy is conjectured to be
    equiconsistent with $\text{ZFC}$+"$\text{Ord}$ is Woodin", where
    "$\text{Ord}$ is Woodin" is expressed as an axiom scheme and
    $\text{Z}_2$ is
    <a href="http://en.wikipedia.org/wiki/second-order_arithmetic" class="extiw" title="wikipedia:second-order arithmetic">second-order arithmetic</a>.
-   $\text{Z}_3+\Delta^1_2$-determinacy is provably equiconsistent
    with $\text{NBG}$+"$\text{Ord}$ is Woodin" where $\text{NBG}$ is
    <a href="http://en.wikipedia.org/wiki/Von_Neumann%E2%80%93Bernays%E2%80%93G%C3%B6del_set_theory" class="extiw" title="wikipedia:Von Neumann–Bernays–Gödel set theory">Von Neumann–Bernays–Gödel set theory</a>
    and $\text{Z}_3$ is third-order arithmetic.

## Role in $\Omega$-logic

## Stationary tower forcing
