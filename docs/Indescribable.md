---
title: Indescribable cardinal
permalink: Indescribable
redirect_from:
  - Totally_indescribable
---

![The Structure of Indescribability in Consistency Strength](assets/img/IndescribableStructure.png)

A cardinal $\kappa$ is *indescribable* if it holds the reflection
theorem up to a certain point. This is important to mathematics because
of the concern for the reflection theorem. In more detail, a cardinal
$\kappa$ is $\Pi_{m}^n$-indescribable if and only if for every
$\Pi_{m}$ first-order sentence $\phi$:

$$\forall S\subseteq V_{\kappa}(\langle
V_{\kappa+n};\in,S\rangle\models\phi\rightarrow\exists\alpha<\kappa(\langle
V_{\alpha+n};\in,S\cap V_{\alpha}\rangle\models\phi))$$

Likewise for $\Sigma_{m}^n$-indescribable cardinals.

Here are some other equivalent definitions:

-   A cardinal $\kappa$ is $\Pi_m^n$-indescribable for $n>0$ iff
    for every $\Pi_m$ first-order unary formula $\phi$:

$$\forall S\subseteq
V_\kappa(V_{\kappa+n}\models\phi(S)\rightarrow\exists\alpha<\kappa(V_{\alpha+n}\models\phi(S\cap
V_\alpha)))$$

-   A cardinal $\kappa$ is $\Pi_m^n$-indescribable iff for every
    $\Pi_m$ $n+1$-th-order sentence $\phi$:

$$\forall S\subseteq V_\kappa(\langle
V_\kappa;\in,S\rangle\models\phi\rightarrow\exists\alpha<\kappa(\langle
V_\alpha;\in,S\cap V_\alpha\rangle\models\phi))$$

In other words, if a cardinal is $\Pi_{m}^n$-indescribable, then every
$n+1$-th order logic statement that is $\Pi_m$ expresses the
reflection of $V_{\kappa}$ onto $V_{\alpha}$. This exercises the
fact that these cardinals are so large they almost resemble the order of
$V$ itself. This definition is similar to that of
[shrewd](Shrewd "Shrewd")
cardinals, an extension of indescribable cardinals.

## Variants

*Totally indescribable* cardinals are $\Pi_m^n$-indescribable for
every natural $m$ and $n$ (equivalently $\Sigma_m^n$-indescribable for
every natural m and n, equivalently $\Delta_m^n$-indescribable for
every natural $m$ and $n$). This means that every (finitary) formula
made from quantifiers, $\in$ and a subset of $V_{\kappa}$ reflects
from $V_{\kappa}$ onto a smaller rank.

*$Q$-indescribable* cardinals are those which have the property that for
every $Q$-sentence $\phi$:

$$\forall S\subseteq V_\kappa(\langle
V_\kappa;\in,S\rangle\models\phi\rightarrow\exists\alpha<\kappa(\langle
V_\alpha;\in,S\cap V_\alpha\rangle\models\phi))$$

*$\beta$-indescribable* cardinals are those which have the property
that for every first order sentence $\phi$:

$$\forall S\subseteq V_\kappa(\langle
V_{\kappa+\beta};\in,S\rangle\models\phi\rightarrow\exists\alpha<\kappa(\langle
V_{\alpha+\beta};\in,S\cap V_\alpha\rangle\models\phi))$$

There is no $\kappa$ which is $\kappa$-indescribable. A cardinal is
$\Pi_{<\omega}^m$-indescribable iff it is $m$-indescribable for
finite $m$. Every $\omega$-indescribable cardinal is totally
indescribable.

## Facts

Here are some known facts about indescribability:

$\Pi_2^0$-indescribability is equivalent to [strong
inaccessibility](Inaccessible "Inaccessible"),
$\Sigma_1^1$-indescribablity, $\Pi_n^0$-indescribability given any
$n>1$, and
$\Pi_0^1$-indescribability.{% cite Kanamori2009 %}
$\Pi_1^1$-indescribability is equivalent to [weak
compactness](Weakly_compact "Weakly compact").
{% cite Jech2003 Kanamori2009 %}

$\Pi_n^m$-indescribablity is equivalent to $m$-$\Pi_n$-shrewdness
(similarly with $\Sigma_n^m$).
{% cite Rathjen2006 %}

[Ineffable](Ineffable "Ineffable")
cardinals are $\Pi^1_2$-indescribable and limits of totally
indescribable cardinals. {% cite Jensen1969 %}

$\Pi_n^1$-indescribability is equivalent to
$\Sigma_{n+1}^1$-Indescribability.
{% cite Kanamori2009 %}

If $m>1$, $\Pi_{n+1}^m$-indescribability is stronger
(consistency-wise) than $\Sigma_n^m$ and $\Pi_n^m$-indescribability;
every $\Pi_{n+1}^m$-indescribable cardinal is also both $\Sigma_n^m$
and $\Pi_n^m$-indescribable and a stationary limit of such for
$m>1$.{% cite Kanamori2009 %} If $m>1$, the
least $\Pi_n^m$-indescribable cardinal is less than the least
$\Sigma_n^m$-indescribable cardinal, which is in turn less than the
least $\Pi_{n+1}^m$-indescribable
cardinal.{% cite Kanamori2009 %}

If $\kappa$ is
$Π_n$-[Ramsey](Ramsey "Ramsey"),
then $\kappa$ is $Π_{n+1}^1$-indescribable. If $X\subseteq\kappa$ is
a $Π_n$-Ramsey subset, then $X$ is in the $Π_{n+1}^1$-indescribable
filter.{% cite Feng1990 %} If $\kappa$ is
completely Ramsey, then $κ$ is
$Π_1^2$-indescribable.{% cite Holy2018 %}

Every $n$-Ramsey $κ$ is $Π^1_{2 n+1}$-indescribable. This is optimal,
as $n$-Ramseyness can be described by a
$Π^1_{2n+2}$-formula.{% cite Nielsen2018 %}
Every $<ω$-Ramsey cardinal is
$∆^2_0$-indescribable.{% cite Nielsen2018 %}
Every normal $n$-Ramsey $κ$ is $Π^1_{2 n+2}$-indescribable. This is
optimal, as normal $n$-Ramseyness can be described by a $Π^1_{2
n+3}$-formula.{% cite Nielsen2018 %}

Every
[measurable](Measurable "Measurable")
cardinal is $\Pi_1^2$-indescribable. Although, the least measurable is
$\Sigma_1^2$-describable. {% cite Jech2003 %}

Every critical point of a nontrivial elementary embedding
$j:M\rightarrow M$ for some transitive inner model $M$ of
[ZFC](ZFC "ZFC") is totally
indescribable in $M$. (For example,
<a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">rank-into-rank</a>
cardinals,
<a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^{\#}$</a>
cardinals, and
<a href="Zero_dagger" class="mw-redirect" title="Zero dagger">$0^{\dagger}$</a>
cardinals). {% cite Jech2003 %}

If $2^\kappa\neq\kappa^+$ for some $\Pi_1^2$-indescribable
cardinal, then there is a smaller $\lambda$ such that
$2^\lambda\neq\lambda^+$. However, assuming the consistency of the
existence of a $\Pi_n^1$-indescribable cardinal $\kappa$, it is
consistent for $\kappa$ to be the least cardinal such that
$2^\kappa\neq\kappa^+$.
{% cite Hauser1991 %}

  
Transfinite $Π^1_α$-indescribable has been defined via finite games and
it turns out that for infinite $α$, if $κ$ is
$Π_α$-[Ramsey](Ramsey "Ramsey"),
then $κ$ is $Π^1_{2 ·(1+β)+ 1}$-indescribable for each $β < \min
\{α, κ^+\}$.{% cite Sharpe2011 %}
