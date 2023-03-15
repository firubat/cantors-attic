---
title: Reflecting cardinals
permalink: Reflecting
redirect_from:
  - Correct
  - Inaccessible_reflecting_cardinal
  - Reflection_theorem
---


Reflection is a fundamental motivating concern in set theory. The theory
of ZFC can be equivalently axiomatized over the very weak
[Kripke-Platek](Kripke-Platek "Kripke-Platek")
set theory by the addition of the reflection theorem scheme, below,
since instances of the replacement axiom will follow from an instance of
$\Delta_0$-separation after reflection down to a $V_\alpha$
containing the range of the defined function. Several philosophers have
advanced philosophical justifications of large cardinals based on ideas
arising from reflection.


## Reflection theorem

The Reflection theorem is one of the most important theorems in Set
Theory, being the basis for several large cardinals. The Reflection
theorem is in fact a "meta-theorem," a theorem about proving theorems.
The Reflection theorem intuitively encapsulates the idea that we can
find sets resembling the class $V$ of all sets.

**Theorem (Reflection):** For every set $M$ and formula
$\phi(x_0...x_n,p)$ ($p$ is a parameter) there exists some limit
ordinal $\alpha$ such that $V_\alpha\supseteq M$ such that
$\phi^{V_\alpha}(x_0...x_n,p)\leftrightarrow \phi(x_0...x_n,p)$
(We say $V_\alpha$ reflects $\phi$). Assuming the Axiom of Choice, we
can find some countable $M_0\supseteq M$ that reflects
$\phi(x_0...x_n,p)$.

Note that by conjunction, for any finite family of formulas
$\phi_0...\phi_n$, as $V_\alpha$ reflects $\phi_0...\phi_n$ if
and only if $V_\alpha$ reflects $\phi_0\land...\land\phi_n$.
Another important fact is that the truth predicate for $\Sigma_n$
formulas is $\Sigma_{n+1}$, and so we can find a (Club class of)
ordinals $\alpha$ such that
$(V_\alpha,\in)\prec_{ {T_{\Sigma_n}}\restriction{V_\alpha}}
(V,\in)$, where $T_{\Sigma_n}$ is the truth predicate for
$\Sigma_n$ and so $ZFC\vdash Con(ZFC(\Sigma_n))$ for every $n$,
where $ZFC(\Sigma_n)$ is $ZFC$ with Replacement and Separation
restricted to $\Sigma_n$.

**Lemma:** If $W_\alpha$ is a cumulative hierarchy, there are
arbitrarily large limit ordinals $\alpha$ such that
$\phi^{W_\alpha}(x_0...x_n,p)\leftrightarrow
\phi^W(x_0...x_n,p)$.

## Reflection and correctness

For any class $\Gamma$ of formulas, an inaccessible cardinal $\kappa$
is *$\Gamma$-reflecting* if and only if $H_\kappa\prec_\Gamma V$,
meaning that for any $\varphi\in\Gamma$ and $a\in H_\kappa$ we
have $V\models\varphi\[a\]\iff H_\kappa\models\varphi\[a\]$. For
example, an inaccessible cardinal is *$\Sigma_n$-reflecting* if and
only if $H_\kappa\prec_{\Sigma_n} V$. In the case that $\kappa$
is not necessarily inaccessible, we say that $\kappa$ is
*$\Gamma$-correct* if and only if $H_\kappa\prec_\Gamma V$*.*

-   A simple Löwenheim-Skolem argument shows that every infinite
    cardinal $\kappa$ is $\Sigma_1$-correct.
-   For each natural number $n$, the $\Sigma_n$-correct cardinals form
    a closed unbounded proper class of cardinals, as a consequence of
    the
    <a href="Reflection_theorem" class="mw-redirect" title="Reflection theorem">reflection theorem</a>.
    This class is sometimes denoted by $C^{(n)}$ and the
    $\Sigma_n$-correct cardinals are also sometimes referred to as the
    $C^{(n)}$-cardinals.
-   Every $\Sigma_2$-correct cardinal is a
    <a href="Beth_fixed_point" class="mw-redirect" title="Beth fixed point">$\beth$-fixed point</a>
    and a limit of such $\beth$-fixed points, as well as an
    [$\aleph$-fixed
    point](Aleph "Aleph")
    and a limit of such. Consequently, we may equivalently define for
    $n\geq 2$ that $\kappa$ is $\Sigma_n$-correct if and only if
    $V_\kappa\prec_{\Sigma_n} V$.

A cardinal $\kappa$ is *correct*, written $V_\kappa\prec V$, if it
is $\Sigma_n$-correct for each $n$. This is not expressible by a
single assertion in the language of set theory (since if it were, the
least such $\kappa$ would have to have a smaller one inside
$V_\kappa$ by elementarity). Nevertheless, $V_\kappa\prec V$ is
expressible as a scheme in the language of set theory with a parameter
(or constant symbol) for $\kappa$.

Although it may be surprising, the existence of a correct cardinal is
equiconsistent with ZFC. This can be seen by a simple compactness
argument, using the fact that the theory ZFC+"$\kappa$ is correct" is
finitely consistent, if ZFC is consistent, precisely by the observation
about $\Sigma_n$-correct cardinals above.

$C^{(n)}$ are the classes of $\Sigma_n$-ordinals. These classes are
clubs (closed unbounded). $C^{(0)}$ is the class of all ordinals.
$C^{(1)}$ is precisely the class of all uncountable cardinals $α$ such
that $V_α = H(α)$. References to the $C^{(n)}$ classes (different from
just the requirement that the cardinal belongs to $C^{(n)}$) can
sometimes make larger cardinal properties stronger (for example
$C^{(n)}$-[superstrong](Superstrong "Superstrong"),
$C^{(n)}$-[extendible](Extendible "Extendible"),
$C^{(n)}$-[huge](Huge "Huge")
and
$C^{(n)}$-<a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">I3</a>
and
$C^{(n)}$-<a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">I1 cardinals</a>).
On the other hand, every
[measurable](Measurable "Measurable")
cardinal is $C^{(n)}$-measurable for all $n$ and every
($λ$-)[strong](Strong "Strong")
cardinal is ($λ$-)$C^{(n)}$-strong for all
$n$. {% cite Bagaria2012 %}

A cardinal $\kappa$ is *reflecting* if it is inaccessible and correct.
Just as with the notion of correctness, this is not first-order
expressible as a single assertion in the language of set theory, but it
is expressible as a scheme (*Lévy scheme*). The existence of such a
cardinal is equiconsistent to the assertion [ORD is
Mahlo](ORD_is_Mahlo "ORD is Mahlo").

If there is a pseudo
[uplifting](Uplifting "Uplifting")
cardinal, or indeed, merely a pseudo $0$-uplifting cardinal $\kappa$,
then there is a transitive set model of ZFC with a reflecting cardinal
and consequently also a transitive model of ZFC plus
<a href="Ord_is_Mahlo" class="mw-redirect" title="Ord is Mahlo">Ord is Mahlo</a>.
You can get this by taking some $\lambda\gt\kappa$ such that
$V_\kappa\prec V_\lambda$.

## $\Sigma_2$ correct cardinals

The $\Sigma_2$-correct cardinals are a particularly useful and robust
class of cardinals, because of the following characterization: $\kappa$
is $\Sigma_2$-correct if and only if for any $x\in V_\kappa$ and
any formula $\varphi$ of any complexity, whenever there is an ordinal
$\alpha$ such that $V_\alpha\models\varphi\[x\]$, then there is
$\alpha\lt\kappa$ with $V_\alpha\models\varphi\[x\]$. The reason
this is equivalent to $\Sigma_2$-correctness is that assertions of the
form $\exists \alpha\ V_\alpha\models\varphi(x)$ have complexity
$\Sigma_2(x)$, and conversely all $\Sigma_2(x)$ assertions can be
made in that form.

It follows, for example, that if $\kappa$ is $\Sigma_2$-correct, then
any feature of $\kappa$ or any larger cardinal than $\kappa$ that can
be verified in a large $V_\alpha$ will reflect below $\kappa$. So if
$\kappa$ is $\Sigma_2$-reflecting, for example, then there must be
unboundedly many inaccessible cardinals below $\kappa$. Similarly, if
$\kappa$ is $\Sigma_2$-reflecting and measurable, then there must be
unboundedly many measurable cardinals below $\kappa$.

## The Feferman theory

This is the theory, expressed in the language of set theory augmented
with a new unary class predicate symbol $C$, asserting that $C$ is a
closed unbounded class of cardinals, and every $\gamma\in C$ has
$V_\gamma\prec V$. In other words, the theory consists of the
following scheme of assertions: $$\forall\gamma\in C\ \forall x\in
V_\gamma\ \bigl\[\varphi(x)\iff\varphi^{V_\gamma}(x)\bigr\]$$
as $\varphi$ ranges over all formulas. Thus, the Feferman theory
asserts that the universe $V$ is the union of a chain of elementary
substructures $$V_{\gamma_0}\prec V_{\gamma_1}\prec\cdots\prec
V_{\gamma_\alpha}\prec\cdots \prec V$$ Although this may appear
at first to be a rather strong theory, since it seems to imply at the
very least that each $V_\gamma$ for $\gamma\in C$ is a model of ZFC,
this conclusion would be incorrect. In fact, the theory does *not* imply
that any $V_\gamma$ is a model of ZFC, and does not prove
$\text{Con}(\text{ZFC})$; rather, the theory implies for each axiom of
ZFC separately that each $V_\gamma$ for $\gamma\in C$ satisfies it.
Since the theory is a scheme, there is no way to prove from that theory
that any particular $\gamma\in C$ has $V_\gamma$ satisfying more
than finitely many axioms of ZFC. In particular, a simple compactness
argument shows that the Feferman theory is consistent provided only that
ZFC itself is consistent, since any finite subtheory of the Feferman
theory is true by the
<a href="Reflection_theorem" class="mw-redirect" title="Reflection theorem">reflection theorem</a>
in any model of ZFC. It follows that the Feferman theory is actually
conservative over ZFC, and proves with ZFC no new facts about sets that
is not already provable in ZFC alone.

The Feferman theory was proposed as a natural theory in which to
undertake the category-theoretic uses of
<a href="Grothendieck_universe" class="mw-redirect" title="Grothendieck universe">Grothendieck universes</a>,
but without the large cardinal penalty of a proper class of inaccessible
cardinals. Indeed, the Feferman theory offers the advantage that the
universes are each elementary substructures of one another, which is a
feature not generally true under the
<a href="Universe_axiom" class="mw-redirect" title="Universe axiom">universe axiom</a>.

## Maximality Principle

The existence of an inaccessible reflecting cardinal is equiconsistent
with the boldface maximality principle $\text{MP}(\mathbb{R})$, which
asserts of any statement $\varphi(r)$ with parameter $r\in\mathbb{R}$
that if $\varphi(r)$ is forceable in such a way that it remains true in
all subsequent forcing extensions, then it is already true; in short,
$\text{MP}(\mathbb{R})$ asserts that every possibly necessary
statement with real parameters is already true. Hamkins showed that if
$\kappa$ is an inaccessible reflecting cardinal, then there is a
forcing extension with $\text{MP}(\mathbb{R})$, and conversely,
whenever $\text{MP}(\mathbb{R})$ holds, then there is an inner model
with an inaccessible reflecting cardinal.
