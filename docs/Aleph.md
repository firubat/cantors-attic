---
title: The aleph numbers, $\aleph_\alpha$
permalink: Aleph
redirect_from:
  - Aleph_fixed_point
  - Aleph_one
  - Cofinality
  - Singular
---


The aleph function, denoted $\aleph$, provides a 1 to 1 correspondence
between the [ordinal](Ordinal "Ordinal") and the [cardinal](Cardinal "Cardinal")
numbers. In fact, it is the only order-isomorphism between the ordinals
and cardinals, with respect to membership. It is a strictly [monotone](Monotone "Monotone")
ordinal function which can be defined via transfinite recursion in the
following manner:

$\aleph_0 = \omega$

$\aleph_{n+1} = \bigcap \{ x \in \operatorname{On} : \| \aleph_n \| \lt \|x\| \}$

$\aleph_a = \bigcup_{x \in a} \aleph_x$ where $a$ is a limit
[ordinal](Ordinal "Ordinal").

To translate the formalism, $\aleph_{n+1}$ is the smallest ordinal
whose cardinality is greater than the previous aleph. $\aleph_a$ is
the limit of the sequence $\{ \aleph_0 , \aleph_1 , \aleph_2 ,
\ldots \}$ until $\aleph_a$ is reached when $a$ is a limit ordinal.

$\aleph_0$ is the smallest
<a href="Infinite" class="mw-redirect" title="Infinite">infinite</a>
[cardinal](Cardinal "Cardinal").



## Aleph one

$\aleph_1$ is the first
<a href="Uncountable" class="mw-redirect" title="Uncountable">uncountable</a>
cardinal.

  

## The continuum hypothesis

The *continuum hypothesis* is the assertion that the set of real numbers
$\mathbb{R}$ have cardinality $\aleph_{1}$. Gödel showed the
consistency of this assertion with ZFC, while Cohen showed using
[forcing](Forcing "Forcing")
that if ZFC is consistent then ZFC+$\aleph_1l\t;\|\mathbb R\|$ is
consistent.

## Equivalent Forms

The cardinality of the power set of $\aleph_{0}$ is $\aleph_{1}$

The is no set with cardinality $\alpha$ such that $\aleph_{0} <
\alpha < \aleph_{1}$

## Generalizations

The *generalized continuum hypothesis* (GCH) states that if an infinite
set's cardinality lies between that of an infinite set *S* and that of
the
<a href="index.php?title=Power_set&amp;action=edit&amp;redlink=1" class="new" title="Power set (page does not exist)">power set</a>
of *S*, then it either has the same cardinality as the set *S* or the
same cardinality as the power set of *S*. That is, for any
<a href="index.php?title=Infinite_set&amp;action=edit&amp;redlink=1" class="new" title="Infinite set (page does not exist)">infinite</a>
<a href="index.php?title=Cardinal_number&amp;action=edit&amp;redlink=1" class="new" title="Cardinal number (page does not exist)">cardinal</a>
\(\lambda\) there is no cardinal \(\kappa\) such that \(\lambda
<\kappa <2^{\lambda}.\) GCH is equivalent to:
\[\aleph_{\alpha+1}=2^{\aleph_\alpha}\] for every
<a href="index.php?title=Ordinal_number&amp;action=edit&amp;redlink=1" class="new" title="Ordinal number (page does not exist)">ordinal</a>
\(\alpha.\) (occasionally called **Cantor's aleph hypothesis**)

For more,see
<a href="https://en.wikipedia.org/wiki/Continuum_hypothesis" class="external free">https://en.wikipedia.org/wiki/Continuum_hypothesis</a>

## Aleph two

$\aleph_2$ is the second
<a href="Uncountable" class="mw-redirect" title="Uncountable">uncountable</a>
[cardinal](Cardinal "Cardinal").

  

## Aleph hierarchy

The $\aleph_\alpha$ hierarchy of cardinals is defined by transfinite
recursion:

-   $\aleph_0$ is the smallest infinite cardinal.
-   $\aleph_{\alpha+1}=\aleph_\alpha^+$, the
    <a href="Successor" class="mw-redirect" title="Successor">successor</a>
    cardinal to $\aleph_\alpha$.
-   $\aleph_\lambda=\sup_{\alpha\lt\lambda}\aleph_\alpha$ for
    [limit
    ordinals](Limit_ordinal "Limit ordinal")
    $\lambda$.

Thus, $\aleph_\alpha$ is the $\alpha^{\rm th}$ infinite cardinal.
In ZFC the sequence $$\aleph_0,
\aleph_1,\aleph_2,\ldots,\aleph_\omega,\aleph_{\omega+1},\ldots,\aleph_\alpha,\ldots$$
is an exhaustive list of all infinite cardinalities. Every infinite set
is bijective with some $\aleph_\alpha$.

  

## Aleph omega

The cardinal $\aleph_\omega$ is the smallest instance of an <a href="Uncountable" class="mw-redirect" title="Uncountable">uncountable</a> <a href="Singular" class="mw-redirect" title="Singular">singular</a> [cardinal](Cardinal "Cardinal") number, since it is larger than every $\aleph_n$, but is the supremum of the [countable](Countable "Countable") set $\{\aleph_0,\aleph_1,\ldots,\aleph_n,\ldots\mid n\lt\omega\}$.

  

## Aleph fixed point

A cardinal $\kappa$ is an *$\aleph$-fixed point when
$\kappa=\aleph_\kappa$. In this case, $\kappa$ is the
$\kappa^{\rm th}$ infinite cardinal. Every
[inaccessible](Inaccessible "Inaccessible")
cardinal is an $\aleph$-fixed point, and a limit of such fixed points
and so on. Indeed, every
[worldly](Worldly "Worldly")
cardinal is an $\aleph$-fixed point and a limit of such.*

One may easily construct an $\aleph$-fixed point above any ordinal
$\beta$: simply let $\beta_0=\beta$ and
$\beta_{n+1}=\aleph_{\beta_n}$; it follows that
$\kappa=\sup_n\beta_n=\aleph_{\aleph_{\aleph_{\aleph_{\ddots}}}}$
is an $\aleph$-fixed point, since
$\aleph_\kappa=\sup_{\alpha\lt\kappa}\aleph_\alpha=\sup_n\aleph_{\beta_n}=\sup_n\beta_{n+1}=\kappa$.
By continuing the recursion to any ordinal, one may construct
$\aleph$-fixed points of any desired cofinality. Indeed, the class of
$\aleph$-fixed points forms a closed unbounded class of cardinals.


