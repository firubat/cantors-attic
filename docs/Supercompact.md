---
title: Supercompact cardinal
permalink: Supercompact
---

Supercompact cardinals are best motivated as a generalization of
[measurable](Measurable "Measurable")
cardinals, particularly the characterization of measurable cardinals in
terms of [elementary
embeddings](Elementary_embedding "Elementary embedding")
and strong closure properties. The notion of supercompactness and its
consequences was initially developed by Solovay and Reinhardt and
further elaborated on by Magidor and Gitik, among many others. Assuming
the existence of a supercompact is a very strong assumption and the
large cardinal strength of supercompact cardinals is seen in a wide (and
bewildering) array of set-theoretic contexts, especially the development
of strong forcing axioms and establishing regularity properties of sets
of reals. The inner model program has yet to reach the level of a
supercompact cardinal and this is considered a prominent open problem in
the program itself. Curiously, by results of Woodin, should the inner
program reach the level of a supercompact, there is a sense in which it
will have reached all greater large cardinals, a startling contrast to
previous advances in the program.

## Formal definition and equivalent characterizations

Generalizing the [elementary
embedding](Elementary_embedding "Elementary embedding")
characterization of measurable cardinal, a cardinal $\kappa$ is
*$\theta$-supercompact* if there is an elementary embedding $j:V\to M$
with $M$ a transitive class, such that $j$ has critical point $\kappa$
and $M^\theta\subset M$, i.e. $M$ is closed under arbitrary sequences
of length $\theta$. Under the
<a href="Axiom_of_choice" class="mw-redirect" title="Axiom of choice">axiom of choice</a>,
one may assume without loss of generality that $j(\kappa)\gt\theta$.
$\kappa$ is then said to be *supercompact* if it is
$\theta$-supercompact for all $\theta$. It is worth noting that, using
this formulation, $H_{\theta^+}$ must be contained in the transitive
class $M$.

There is an alternative formulation that is expressible in $\text{ZFC}$
using certain
<a href="Ultrafilter" class="mw-redirect" title="Ultrafilter">ultrafilters</a>
with somewhat technical properties: for $\theta\geq\kappa$, $\kappa$
if $\theta$-supercompact if there is a normal fine measure on
$\mathcal{P}_\kappa(\theta)$. $\kappa$ is supercompact if for every
set $A$ with $\|A\|\geq\kappa$, there is a normal fine measure on
$\mathcal{P}_\kappa(A)$.

One can see the equivalence of the two formulations by first considering
the ultrafilter $U$ arising from the
[seed](Seed "Seed")
$j''\theta$, so that $X\in U\iff j''\theta\in j(X)$. It is easy to
check that $U$ is a normal fine measure on
$\mathcal{P}_\kappa(\theta)$. Conversely, the ultrapower by a normal
fine measure $U$ on $\mathcal{P}_\kappa(\theta)$ gives rise to an
embedding $j:V\to M$ (here $M$ is identified with the transitive
collapse of the ultrapower by $U$). It is then straightforward to check
that $\theta$ is the critical point of this embedding and that $M$ is
sufficiently closed, thus witnessing $\theta$-supercompactness of
$\kappa$.

A third characterization was given by Magidor \[Mag71\] in terms of
elementary embeddings from initial segments of $V$ into other (larger)
initial segments of $V$, but in this characterization, the supercompact
cardinal $\kappa$ is the *image* of the critical point of this
embedding, rather than the critical point itself: $\kappa$ is
supercompact if and only if for every $\eta>\kappa$ there is
$\alpha<\kappa$ such that there exists a nontrivial elementary
embedding $j:V_\alpha\to V_\eta$ such that
$j(\mathrm{crit}(j))=\kappa$.
([Remarkable](Remarkable "Remarkable")
cardinals could be called virtually supercompact, because one of their
definitions is an exact analogue of this one (with forcing
extension)){% cite Gitmana %}

## Properties

If $\kappa$ is supercompact, then there are $2^{2^\kappa}$ [normal
fine
measures](Filter "Filter")
on $\kappa$, also for every $\lambda\geq\kappa$ there are
$2^{2^{\lambda^{<\kappa}}}$ normal fine measures on
$\mathcal{P}_\kappa(\lambda)$.

Every supercompact has
<a href="Mitchell_order" class="mw-redirect" title="Mitchell order">Mitchell order</a>
$(2^\kappa)^+\geq\kappa^{++}$.

If $\kappa$ is $\lambda$-supercompact then it is also
$\mu$-supercompact for every $\mu<\lambda$. If
$\lambda\geq\kappa$ is regular, $\kappa$ is $\lambda$-supercompact,
then every $\alpha<\kappa$ that is $\gamma$-supercompact for all
$\gamma<\kappa$ (if any exists) is also $\lambda$-supercompact. In
the same vein, for every cardinals $\kappa<\lambda$, if $\lambda$
is supercompact and $\kappa$ is $\gamma$-supercompact for all
$\gamma<\lambda$, then $\kappa$ is also supercompact.

*Laver's theorem* asserts that if $\kappa$ is supercompact, there
exists a function $f:\kappa\to V_\kappa$ such that for every $x$ and
$\lambda\geq\kappa$ with $\|tc(x)\|\leq\lambda$ there exists a
normal fine measure $U$ on $\mathcal{P}_\kappa(\lambda)$ such that
$j_U(f)(\kappa)=x$, where $j_U$ is the elementary embedding generated
from $U$. Here $tc(x)$ is the *transitive closure* of $x$ (i.e. the
smallest transitive set containing $x$), and $f$ is called a *Laver
function*.

## Supercompact cardinals and forcing

### The continuum hypothesis and supercompact cardinals

If $\kappa$ is $\lambda$-supercompact and $2^\alpha=\alpha^{+}$ for
every $\alpha<\kappa$, then $2^\alpha=\alpha^{+}$ for every
$\alpha\leq\lambda$. Consequently, if the
<a href="GCH" class="mw-redirect" title="GCH">generalized continuum hypothesis</a>
holds below a supercompact cardinal, then it holds everywhere.

The existence of a supercompact implies the consistency of the failure
of the *singular cardinal hypothesis*, i.e. it is consistent that the
generalized continuum hypothesis fails at a strong limit singular
cardinal. It also implies the consistency of the failure of the
$\text{GCH}$ at a measurable cardinal.

By combining results of Magidor, Shelah and Gitik, one can show that the
existence of a supercompact also implies the existence of a [generic
extension](Forcing "Forcing")
in which $2^{\aleph_\alpha}<\aleph_{\omega_1}$ for all
$\alpha<\omega_1$, but also
$2^{\aleph_{\omega_1}}>\aleph_{\omega_1+\alpha+1}$ for any
prescribed $\alpha<\omega_2$. Similarly, one can have a generic
extension in which the $\text{GCH}$ holds below $\aleph_\omega$ but
$2^{\aleph_\omega}>\aleph_{\omega+\alpha+1}$ for any
prescribed $\alpha<\omega_1$.

Woodin and Cummings furthermore showed that if there exists a
supercompact, then there is a generic extension in which
$2^\kappa=\kappa^{++}$ for *every* cardinal $\kappa$, i.e. the
$\text{GCH}$ fails *everywhere*(!).

The
<a href="Ultrapower_axiom" class="mw-redirect" title="Ultrapower axiom">ultrapower axiom</a>,
if consistent with a supercompact, implies that the $\text{GCH}$ holds
above the least supercompact.

### Laver preparation

*Indestructibility, including the Laver diamond.*

### Proper forcing axiom

Baumgartner proved that if there is a supercompact cardinal, then the
<a href="Proper_forcing_axiom" class="mw-redirect" title="Proper forcing axiom">proper forcing axiom</a>
holds in a
[forcing](Forcing "Forcing")
extension. $\text{PFA}$'s strengthening, $\text{PFA}^{+}$, is also
consistent relative to the existence of a supercompact cardinal.

### Martin's Maximum

## Relation to other large cardinals

Every cardinal $\kappa$ that is $2^\kappa$-supercompact is a
stationary limit of
[superstrong](Superstrong "Superstrong")
cardinals, but need not be superstrong itself. In fact
$2^\kappa$-supercompact are stationary limits of quasicompacts,
themselves stationary limits of
1-[extendibles](Extendible "Extendible").

If $\theta=\beth_\theta$ then every $\theta$-supercompact cardinal
is
[$\theta$-strong](Strong "Strong").
This is because $H_{\theta^+}\in M$ so $H_{\theta^+}\subset M$ by
transitivity and $V_\theta\subset H_\theta\in M$ so
$V_\theta\subset M$, as desired.

If a cardinal $\theta$-supercompact then it also $\theta$-[strongly
compact](Strongly_compact "Strongly compact").
Consequently, every supercompact cardinal is also strongly compact. It
is consistent with $\text{ZFC}$ that every strongly compact cardinal is
also supercompact, but it is not currently known whether the existence
of a strongly compact cardinal is equiconsistent with the existence of a
supercompact cardinal. The
<a href="Ultrapower_axiom" class="mw-redirect" title="Ultrapower axiom">ultrapower axiom</a>
gives a positive answer to this, but itself isn't known to be consistent
with the existence of a supercompact in the first place. If $\kappa$ is
supercompact, then there is a forcing extension in which $\kappa$
remains supercompact and is also the least strongly compact cardinal. If
there exists a measurable cardinal that is a limit of strongly compact
cardinals, then the least such cardinal is strongly compact but not
supercompact, in fact not even $2^\kappa$-supercompact.

Under the [axiom of
determinacy](Axiom_of_determinacy "Axiom of determinacy"),
$\omega_1$ is <$\Theta$-supercompact, where $\Theta$ is at least
an
<a href="Aleph_fixed_point" class="mw-redirect" title="Aleph fixed point">aleph fixed point</a>,
and under $V=L(\mathbb{R})$ is even weakly
hyper-[Mahlo](Mahlo "Mahlo").
The existence of a supercompact cardinals also implies the axiom
$\text{AD}^{L(\mathbb{R})}$.

If $\kappa$ is $\|V_{\kappa+\eta}\|$-supercompact with
$\eta<\kappa$ then it is preceeded by a stationary set of
$\eta$-[extendible](Extendible "Extendible")
cardinals. If $\kappa$ is $(\eta+2)$-extendible then it is
$\|V_{\kappa+\eta}\|$-supercompact. The least supercompact is not
1-extendible, in fact any cardinal that is both supercompact and
1-extendible is preceeded by a stationary set of cardinals that are both
supercompact and limits of supercompact cardinals.

The least supercompact is larger than the least
[huge](Huge "Huge")
cardinal (if such a cardinal exists). It is also larger than the least
n-huge cardinal, for all n. If $\kappa$ is supercompact and there is an
n-huge cardinal above $\kappa$, then there are $\kappa$-many n-huge
cardinals below $\kappa$.

From {% cite Bagaria2012 %}:

-   If κ is $2^κ$-supercompact and belongs to $C^{(n)}$, then there is a
    $κ$-complete normal
    <a href="Ultrafilter" class="mw-redirect" title="Ultrafilter">ultrafilter</a>
    $U$ over $κ$ such that the set of
    $C^{(n)}$-[superstrong](Superstrong "Superstrong")
    cardinals smaller than $κ$ belongs to $U$.
-   $VP(Π_1) \iff VP(κ, Σ_2)$ for some $κ \iff$ There exists a
    supercompact cardinal. ($VP$ — [Vopěnka's
    principle](Vopenka "Vopenka"))
-   $VP(\mathbf{Π_1}) \iff VP(κ, \mathbf{Σ_2})$ for a proper class
    of cardinals $κ \iff$ There is a proper class of supercompact
    cardinals.

  

        This article is a stub. Please help us to improve Cantor's Attic by adding information.
