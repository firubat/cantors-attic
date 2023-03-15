---
title: Ramsey cardinal
permalink: Ramsey
redirect_from:
  - Filter_property
  - Iterable
---


Ramsey cardinals were introduced by Erdős and Hajnal in
{% cite Erdoes1962 %}. Their consistency strength lies
strictly between $0^\sharp$ and measurable cardinals.

There are many Ramsey-like cardinals with strength between weakly
compact and measurable cardinals inclusively. 
{% cite Feng1990 Gitman2011 Sharpe2011 Holy2018 Nielsen2018 %}


## Ramsey cardinals

### Definitions

A cardinal $\kappa$ is Ramsey if it has the partition property
$\kappa\rightarrow (\kappa)^{\lt\omega}_2$.

For infinite cardinals $\kappa$ and $\lambda$, the [partition
property](Partition_property "Partition property")
$\kappa\to(\lambda)^n_\gamma$ asserts that for every function
$F:\[\kappa\]^n\to\gamma$ there is $H\subseteq\kappa$ with
$\|H\|=\lambda$ such that $F\upharpoonright\[H\]^n$ is constant. Here
$\[X\]^n$ is the set of all $n$-elements subsets of $X$. The more
general partition property
$\kappa\to(\lambda)^{\lt\omega}_\gamma$ asserts that for every
function $F:\[\kappa\]^{\lt\omega}\to\gamma$ there is
$H\subseteq\kappa$ with $\|H\|=\lambda$ such that
$F\upharpoonright\[H\]^n$ is constant for every $n$, although the value
of $F$ on $\[H\]^n$ may be different for different $n$. Indeed, if
$\kappa$ is Ramsey, then $\kappa\rightarrow
(\kappa)^{\lt\omega}_\lambda$ for every $\lambda<\kappa$.
Ramsey cardinals were named in honor of Frank Ramsey, whose Ramsey
theorem for partition properties of $\omega$ motivated the
generalizations of these to uncountable cardinals. A Ramsey cardinal
$\kappa$ is exactly the
[$\kappa$-Erdős](Erdos "Erdos")
cardinal.

Ramsey cardinals have a number of other characterizations. They may be
characterized model theoretically through the existence of
$\kappa$-sized sets of indiscernibles for models meeting the criteria
discussed below, as well as through the existence of $\kappa$-sized
models of set theory without power set with iterable
[ultrapowers](Ultrapower "Ultrapower").

**Indiscernibles**: Suppose $\mathcal A=(A,\ldots)$ is a model of a
language $\mathcal L$ of size less than $\kappa$ whose universe $A$
contains $\kappa$ as a subset.

If a cardinal $\kappa$ is Ramsey, then every such model $\mathcal A$
has a $\kappa$-sized set of indiscernibles $H\subseteq\kappa$, that
is, for every formula $\varphi(\overline x)$ of $\mathcal L$ and
every pair of tuples $\overline \alpha$ and $\overline \beta$ of
elements of $H$, we have $\mathcal A\models\varphi (\overline
\alpha)\leftrightarrow \varphi(\overline \beta)$.
{% cite Jech2003 %}

**Good sets of indiscernibles**: Suppose $A\subseteq\kappa$ and
$L_\kappa\[A\]$ denotes the $\kappa^{\text{th}}$-level of the
universe constructible using a predicate for $A$. A set
$I\subseteq\kappa$ is a good set of indiscernibles for the model
$\langle L_\kappa\[A\],A\rangle$ if for all $\gamma\in I$,

-   $\langle L_\gamma\[A\cap \gamma\],A\cap \gamma\rangle\prec
    \langle L_\kappa\[A\], A\rangle$,
-   $I\setminus\gamma$ is a set of indiscernibles for the model
    $\langle L_\kappa\[A\], A,\xi\rangle_{\xi\in\gamma}$.

A cardinal $\kappa$ is Ramsey if and only if for every
$A\subseteq\kappa$, there is a $\kappa$-sized good set of
indiscernibles for the model $\langle L_\kappa\[A\], A\rangle$.
{% cite Dodd1981 %}

**$M$-<a href="Ultrafilter" class="mw-redirect" title="Ultrafilter">ultrafilters</a>**:
Suppose a transitive $M\models {\rm ZFC}^-$, the theory ${\rm ZFC}$
without the power set axiom (and using collection and separation rather
than merely replacement) and $\kappa$ is a cardinal in $M$. We call
$U\subseteq P(\kappa)^M$ an $M$-ultrafilter if the model $\langle
M,U\rangle\models$“$U$ is a normal ultrafilter on $\kappa$”. In the
case when the $M$-ultrafilter is not an element of $M$, the model
$\langle M,U\rangle$ of $M$ together with a predicate for $U$ often
fails to satisfy much of ${\rm ZFC}$. An $M$-ultrafilter $U$ is said to
be weakly amenable (to $M$) if for every $A\in M$ of size $\kappa$ in
$M$, the intersection $A\cap U$ is an element of $M$. An
$M$-ultrafilter $U$ is countably complete if every countable sequence
(possibly external to $M$) of elements of $U$ has a non-empty
intersection (even if the intersection is not itself an element of $M$).
A weak $\kappa$-model is a transitive set $M\models {\rm ZFC}^- $ of
size $\kappa$ and containing $\kappa$ as an element. A modified
ultrapower construction using only functions on $\kappa$ that are
elements of $M$ can be carried out with an $M$-ultrafilter. If the
$M$-ultrafilter happens to be countably complete, then the standard
argument shows that the ultrapower is well-founded. If the
$M$-ultrafilter is moreover weakly amenable, then a weakly amenable
ultrafilter on the image of $\kappa$ in the well-founded ultrapower can
be constructed from images of the pieces of $U$ that are in $M$. The
ultrapower construction may be iterated in this manner, taking direct
limits at limit stages, and in this case the countable completeness of
the $M$-ultrafilter ensures that every stage of the iteration produces a
well-founded model. {% cite Kanamori2009 %} (Ch.
19)

A cardinal $\kappa$ is Ramsey if and only if every $A\subseteq\kappa$
is contained in a weak $\kappa$-model $M$ for which there exists a
weakly amenable countably complete $M$-ultrafilter on $\kappa$.
{% cite Dodd1981 %}

### Ramsey cardinals and the constructible universe

Ramsey cardinals imply that
<a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^\sharp$</a>
exists and hence there cannot be Ramsey cardinals in $L$.
{% cite Kanamori2009 %}

### Relations with other large cardinals

-   [Measurable](Measurable "Measurable")
    cardinals are Ramsey and stationary limits of Ramsey cardinals.
    {% cite Erdoes1962 %}
-   Ramsey cardinals are
    [unfoldable](Unfoldable "Unfoldable")
    (using the $M$-ultrafilters characterization) and stationary limits
    of unfoldable cardinals (as they are stationary limits of
    $\omega_1$-iterable cardinals).
-   Ramsey cardinals are stationary limits of
    <a href="Completely_ineffable" class="mw-redirect" title="Completely ineffable">completely ineffable</a>
    cardinals, they are
    <a href="Weakly_ineffable" class="mw-redirect" title="Weakly ineffable">weakly ineffable</a>,
    but the least Ramsey cardinal is not ineffable. Ineffable Ramsey
    cardinals are limits of Ramsey cardinals, because ineffable
    cardinals are $Π^1_2$-indescribable and being Ramsey is a
    $Π^1_2$-statement.{% cite Gitman2011 %}
-   There are stationarily many completely ineffable, [greatly
    Erdős](Erdos "Erdos")
    cardinals below any Ramsey
    cardinal.{% cite Sharpe2011 %}

Weaker Ramsey-like:

-   The existence of a Ramsey cardinal is stronger than the existence of
    a proper class of almost Ramsey cardinals.
-   The Ramsey cardinals are precisely the
    [Erdős](Erdos "Erdos")
    almost Ramsey cardinals and also precisely the [weakly
    compact](Weakly_compact "Weakly compact")
    almost Ramsey cardinals.
-   A Ramsey cardinal is $\omega_1$-iterable and a stationary limit of
    $\omega_1$-iterable cardinals. This is already true of an
    $\omega_1$-[Erdős](Erdos "Erdos")
    cardinal. {% cite Sharpe2011 %}
-   A virtually Ramsey cardinal that is [weakly
    compact](Weakly_compact "Weakly compact")
    is already Ramsey. If $κ$ is Ramsey, then there is a forcing
    extension destroying this, while preserving that $κ$ is virtually
    Ramsey. It is open whether virtually Ramsey cardinals are weaker
    than Ramsey
    cardinals. {% cite Gitman2011a Gitman %}

Stronger Ramsey-like:

-   If $κ$ is $Π_1$-Ramsey, then the set of Ramsey cardinals less then
    $κ$ is in the $Π_1$-Ramsey filter on
    $κ$.{% cite Feng1990 %}
-   Strongly Ramsey cardinals are Ramsey and stationary limits of Ramsey
    cardinals.{% cite Gitman2011 %}
-   Mahlo–Ramsey cardinals are a direct strengthening of
    Ramseyness.{% cite Sharpe2011 %}

### Ramsey cardinals and forcing

-   Ramsey cardinals are preserved by small forcing.
    {% cite Kanamori2009 %}
-   Ramsey cardinals $\kappa$ are preserved by the canonical forcing of
    the ${\rm GCH}$, by fast function forcing, and by the forcing to
    add a slim $\kappa$-Kurepa tree.
    {% cite Gitman %}
-   If $\kappa$ is Ramsey, there is a forcing extension in which
    $\kappa$ remains Ramsey and
    $2^\kappa\gt\kappa$. {% cite Gitman Cody2015 %}
    -   If the ${\rm GCH}$ holds and $F$ is a class function on the
        regular cardinals having a closure point at $\kappa$ and
        satisfying $F(\alpha)\leq F(\beta)$ for $\alpha<\beta$
        and $\text{cf}(F(\alpha))>\alpha$, then there is a
        cofinality preserving forcing extension in which $\kappa$
        remains Ramsey and $2^\delta=F(\delta)$ for every regular
        cardinal $\delta$.
        {% cite Cody2015 %}
    -   There is a forcing extension in which $κ$ is the first cardinal
        at which the $\mathrm{GCH}$ fails.
        {% cite Gitman %}
-   If the existence of Ramsey cardinals is consistent with ZFC, then
    there is a model of ZFC in which $\kappa$ is not Ramsey, but
    becomes Ramsey in a forcing extension.
    {% cite Gitman %}

## Completely Romsey cardinals etc.

(All information in this section are from
{% cite Feng1990 %} unless otherwise noted)

### Basic definitions

-   $\mathcal{P}(x)$ is the powerset (set of all subsets) of $x$.
    $\mathcal{P}_k(x)$ is the set of all subsets of $x$ with exactly
    $k$ elements.
-   $f:\mathcal{P}_k(λ) \to λ$ is regressive iff for all $A \in
    \mathcal{P}_k(λ)$, we have $f(A) < \min(A)$.
-   $E$ is $f$-homogenous iff $E \subseteq λ$ and for all $B,C \in
    \mathcal{P}_k(E)$, we have $f(B) = f(C)$.

### $Π_α$-Ramsey and completely Ramsey

Suppose that $κ$ is a regular uncountable cardinal and $I \supseteq
\mathcal{P}_{<κ}(κ)$ is an ideal on $κ$. For every $X \subseteq
$κ, $X \in \mathcal{R}^+(I)$ iff for every regressive function
$f:\mathcal{P}_{<ω}(κ) \to κ$, for every club $C \subseteq κ$,
there is a $Y \in I^+f$ such that $Y \subseteq X \cap C$ and $Y$ is
homogeneous for $f$.

$\mathcal{R}(I) = \mathcal{P}(κ) - \mathcal{R}^+(I)$

$\mathcal{R}^*(I) = \{ X \subseteq κ : κ - X \in \mathcal{R}(I)
\}$

A regular uncountable cardinal $κ$ is Ramsey iff $κ \not\in
\mathcal{R}(\mathcal{P}_{<κ}(κ))$. If it is Ramsey, we call
$\mathcal{R}(\mathcal{P}_{<κ}(κ))$ *the Ramsey
<a href="Ideal" class="mw-redirect" title="Ideal">ideal</a>*
on $κ$, its dual $\mathcal{R}^*(\mathcal{P}_{<κ}(κ))$ *the Ramsey
[filter](Filter "Filter")*
and every element of $\mathcal{R}^+(\mathcal{P}_{<κ}(κ))$ *a
Ramsey subset* of $κ$.

For a regular uncountable cardinal $κ$, we define

-   $I_{-2}^κ = \mathcal{P}_{<κ}(κ)$
-   $I_{-1}^κ = NS_κ$ (the set of non-stationary subsets of $κ$)
-   for $n < ω$, $I_n^κ = \mathcal{R}(I_{n-2}^κ)$
-   for $α \geq ω$, $I_{α+1}^κ = \mathcal{R}(I_α^κ)$
-   for limit ordinal $γ$, $I_γ^κ = \bigcup_{β<γ}
    \mathcal{R}(I_β^κ)$

Regular uncountable cardinal $κ$ is **$Π_α$-Ramsey** iff $κ \not\in
I_α^κ$ and **completely Ramsey** iff for all $α$, $κ \not\in I_α^κ$.

If $κ$ is $Π_α$-Ramsey, we call $I_α^κ$ *the $Π_α$-Ramsey ideal* on
$κ$, its dual *the $Π_α$-Ramsey filter* and every subset of $κ$ not in
$I_α^κ$ *a $Π_α$-Ramsey subset*. If $κ$ is completely Ramsey, we call
$I_{θ_κ}^κ$ *the completely Ramsey ideal* on $κ$, its dual *the
completely Ramsey filter* and every subset of $κ$ not in $I_{θ_κ}^κ$
*a completely Ramsey subset*. ($θ_κ$ is the least $α$ such that $I_α^κ
= I_{α+1}^κ$ — it must exist before $(2^κ)^+$ <span class="small">for
every regular uncountable $κ$ — even if the ideals are trivial</span>)

### $α$-hyper completely Ramsey and super completely Ramsey

A sequence $⟨f_α:α<κ^+⟩$ of elements of $^κκ$ is a *canonical
sequence* on $κ$ if both

-   for all $α, β\in κ$, $α < β$ implies $f_α < f_β$.
-   and for any other sequence $⟨g_α:α<κ^+⟩$ of elements of $κ^κ$
    such that $\forall_{α < β < κ^κ} g_α < g_β$, we have
    $\forall_{α < κ^+} f_α < g_α$.

Note four facts:

-   If $⟨f_α:α<κ^+⟩$ and $⟨g_α:α<κ^+⟩$ both are canonical
    sequences on $κ$, then for all $α < κ^+$ there is a club $C_α
    \subseteq κ$ such that $\forall_{γ \in C_α} f_α(γ) = g_α(γ)$.
    (*All pairs of corresponding elements of two sequences of functions
    are equal on a club.*)
-   There are canonical sequences on each regular uncountable cardinal.
-   If $⟨h_α:α<κ^+⟩$ is a canonical sequence on $κ$, then for all $α
    < κ^+$ there is a club $C_α \subseteq κ$ such that
    $\forall_{η \in C_α} h_α(η) < \|η\|^+$. (*Each function in a
    sequence takes on a club values with cardinality not greater then
    argument's.*)
-   For all $β < κ^+$ there is a club $C_β \subseteq κ$ such that
    for all uncountable regular $λ \in C_β$, the set $\{ γ < λ :
    f^λ_{f^κ_β(λ)}(γ) = f^κ_β(γ) \}$ contains a club in $λ$, where
    $\vec {f^λ}$ and $\vec {f^κ}$ are canonical sequences on $λ$ and
    $κ$ respectively.

For a regular uncountable cardinal $κ$, let $\vec f = ⟨f_α:α<κ^+⟩$
be the canonical sequence on $κ$.

-   $κ$ is **0-hyper completely Ramsey** iff $κ$ is completely Ramsey.
-   For $α<κ^+$, $κ$ is **$α+1$-hyper completely Ramsey** iff $κ$ is
    $α$-hyper completely Ramsey and there is a completely Ramsey subset
    $X$ such that for all $λ \in X$, $λ$ is $f_α(λ)$-hyper completely
    Ramsey.
-   For $γ \leq κ^+$, $κ$ is **$γ$-hyper completely Ramsey** iff $κ$ is
    $β$-hyper completely Ramsey for all $β<γ$.
-   $κ$ is **super completely Ramsey** iff $κ$ is $κ^+$-hyper completely
    Ramsey.

### Terminology

(This subsection compares (Sharpe&Welch, 2011) and (Feng, 1990))

$Π_α$-Ramsey cardinals correspond to $α$-Ramsey and $α$-Ramsey$^s$ in
{% cite Sharpe2011 Holy2018 %}
(The “$^s$” stands for
“stationary”.{% cite Sharpe2011 %})

$Π_{2 n}$-Ramsey cardinals are Sharpe-Welch $n$-Ramsey and $Π_{2 n +
1}$-Ramsey cardinals are $n$-Ramsey$^s$.

For infinite $α$, $Π_α$-Ramsey, Sharpe-Welch $α$-Ramsey and
$α$-Ramsey$^s$ are identical.

### Results

Absoluteness:

-   All this properties (being Ramsey itself, $Π_α$-Ramsey, completely
    Ramsey, $α$-hyper completely Ramsey and super completely Ramsey) are
    downwards absolute to the Dodd-Jensen [core
    model](Core_model "Core model").

Hierarchy:

-   There are stationary many $Π_n$-Ramsey cardinals below each
    $Π_{n+1}$-Ramsey cardinal.
-   If $κ$ is $Π_{α+1}$-Ramsey and $α < κ^+$, then the set of
    $Π_α$-Ramsey cardinals less then $κ$ is in the $Π_{α+1}$-Ramsey
    filter on $κ$.

Upper limit of consistency strength:

-   Any
    [measurable](Measurable "Measurable")
    cardinal is super completely Ramsey and a stationary limit of super
    completely Ramsey cardinals.

Indescribability:

-   If $κ$ is $Π_n$-Ramsey, then $κ$ is
    $Π_{n+1}^1$-[indescribable](Indescribable "Indescribable").
    If $X \subseteq κ$ is a $Π_n$-Ramsey subset, then $X$ is
    $Π_{n+1}^1$-indescribable.
-   For infinite $α$, if $κ$ is $Π_α$-Ramsey, then $κ$ is $Π^1_{2
    ·(1+β)+ 1}$-indescribable for each $β < \min \{α, κ^+\}$
    (Transfinite $Π^1_α$-indescribable is defined via finite
    games.).{% cite Sharpe2011 %}
-   If $κ$ is completely Ramsey, then $κ$ is
    $Π_1^2$-[indescribable](Indescribable "Indescribable").{% cite Holy2018 %}

Equivalence:

-   A cardinal is completely Ramsey iff it is $ω$-very
    Ramsey. {% cite Sharpe2011 Nielsen2018 %}

Relation with other variants of Ramseyness:

-   Strongly Ramsey cardinals are limits of completely Ramsey cardinals,
    but are not necessarily completely Ramsey
    themselves.{% cite Gitman2011a %}
-   Every $(ω+1)$-Ramsey cardinal is a completely Ramsey stationary
    limit of completely Ramsey
    cardinals.{% cite Nielsen2018 %}
-   Any $\Pi_2$-Ramsey cardinal is $α$-Mahlo–Ramsey for all $α <
    κ^+$. {% cite Sharpe2011 %}

## Almost Ramsey cardinal

cf. (Vickers&Welch, 2001)

An uncountable cardinal $\kappa$ is **almost Ramsey** if and only if
$\kappa\rightarrow(\alpha)^{<\omega}$ for every
$\alpha<\kappa$. Equivalently:

-   $\kappa\rightarrow(\alpha)^{<\omega}_\lambda$ for every
    $\alpha,\lambda<\kappa$
-   For every structure $\mathcal{M}$ with language of size
    $<\kappa$, there is are sets of indiscernibles
    $I\subseteq\kappa$ for $\mathcal{M}$ of any size $<\kappa$.
-   For every $\alpha<\kappa$, $\eta_\alpha$ exists and
    $\eta_\alpha<\kappa$.
-   $\kappa=\text{sup}\{\eta_\alpha:\alpha<\kappa\}$

($\eta_\alpha$ is the
[$\alpha$-Erdős](Erdos "Erdos")
cardinal.)

Every almost Ramsey cardinal is a [$\beth$-fixed
point](Beth "Beth"), but
the least almost Ramsey cardinal, if it exists, has cofinality
$\omega$. In fact, the least almost Ramsey cardinal is not
<a href="Weakly_inaccessible" class="mw-redirect" title="Weakly inaccessible">weakly inaccessible</a>,
[worldly](Worldly "Worldly"),
or
<a href="Correct" class="mw-redirect" title="Correct">correct</a>.
However, if the least almost Ramsey cardinal exists, it is larger than
the least
[$\omega_1$-Erdős](Erdos "Erdos")
cardinal. Any regular almost Ramsey cardinal is worldly, and any worldly
almost Ramsey cardinal $\kappa$ has $\kappa$ almost Ramsey cardinals
below it.

The existence of a worldly almost Ramsey cardinal is stronger than the
existence of a proper class of almost Ramsey cardinals. Therefore, the
existence of a Ramsey cardinal is stronger than the existence of a
proper class of almost Ramsey cardinals. The existence of a proper class
of almost Ramsey cardinals is equivalent to the existence of
$\eta_\alpha$ for every $\alpha$. The existence of an almost Ramsey
cardinal is stronger than the existence of an $\omega_1$-Erdős
cardinal.

The existence of an almost Ramsey cardinal is equivalent to the
existence of $\eta^n(\omega)$ for every $n<\omega$. On one hand,
if a almost Ramsey cardinal $\kappa$ exists, then $\omega<\kappa$.
Then, $\eta_\omega$ is less than $\kappa$. Then,
$\eta_{\eta_\omega}$ exists and is less than $\kappa$, and so on.
On the other hand, if $\eta^n(\omega)$ exists for every
$n<\omega$, then $\text{sup}\{\eta^n(\omega):n<\omega\}$ is
almost Ramsey, and in fact the least almost Ramsey cardinal. Note that
such a set exists by replacement and has a supremum by union.

The Ramsey cardinals are precisely the
[Erdős](Erdos "Erdos")
almost Ramsey cardinals and also precisely the [weakly
compact](Weakly_compact "Weakly compact")
almost Ramsey cardinals.

If $κ$ is a $2$-weakly Erdős cardinal, then $κ$ is almost
Ramsey.{% cite Sharpe2011 %}

## Strongly Ramsey cardinal

Strongly Ramsey cardinals were introduced by Gitman in
{% cite Gitman2011 %} (all information from
there unless otherwise noted). They strengthen the $M$-ultrafilters
characterization of Ramsey cardinals from weak $\kappa$-models to
$\kappa$-models.

A cardinal $\kappa$ is **strongly Ramsey** if every
$A\subseteq\kappa$ is contained in a $\kappa$-model $M$ for which
there exists a weakly amenable $M$-ultrafilter on $\kappa$. An
$M$-ultrafilter for a $\kappa$-model $M$ is automatically countably
complete since $\langle M,U\rangle$ satisfies that it is
$\kappa$-complete and it must be correct about this since $M$ is closed
under sequences of length less than $\kappa$.

Properties:

-   Super Ramsey cardinals are strongly Ramsey limits of strongly Ramsey
    cardinals.
-   Strongly Ramsey cardinals are limits of completely Ramsey cardinals,
    but are not necessarily completely Ramsey
    themselves.{% cite Gitman2011a %}
-   Every strongly Ramsey cardinal is a stationary limit of almost fully
    Ramseys.{% cite Nielsen2018 %}
-   Strongly Ramsey cardinals are Ramsey and stationary limits of Ramsey
    cardinals.
-   The least strongly Ramsey cardinal is not
    [ineffable](Ineffable "Ineffable").
-   Forcing related properties of strongly Ramsey cardinals are the same
    as those of Ramsey cardinals described above.
    {% cite Gitman %}
-   Strong Ramseyness is downward absolute to $K$.
    {% cite Gitman2011a %}

## Super Ramsey cardinal

Super Ramsey cardinals were introduced by Gitman in
{% cite Gitman2011 %} (all information from
there unless otherwise noted). They strengthen one definition of strong
Ramseyness.

A weak $\kappa$-model $M$ is a $\kappa$-model if additionally
$M^{\lt\kappa}\subseteq M$.

A cardinal $\kappa$ is **super Ramsey** if and only if for every
$A\subseteq\kappa$, there is some $\kappa$-model $M$ with
$A\subseteq M\prec H_{\kappa^+}$ such that there is some $N$ and
some $\kappa$-powerset preserving nontrivial elementary embedding
$j:M\prec N$.

The following are some facts about super Ramsey cardinals:

-   [Measurable](Measurable "Measurable")
    cardinals are super Ramsey limits of super Ramsey cardinals.
-   Fully Ramsey cardinals are super Ramsey limits of super Ramsey
    cardinals.{% cite Holy2018 %}
-   Super Ramsey cardinals are strongly Ramsey limits of strongly Ramsey
    cardinals.
-   Super Ramseyness is downward absolute to $K$.
    {% cite Gitman2011a %}
-   The required $M$ for a super Ramsey embedding is stationarily
    correct.

## $\alpha$-iterable cardinal

The $\alpha$-iterable cardinals for $1\leq\alpha\leq\omega_1$ were
introduced by Gitman in
{% cite Gitman2011a %}. They form a
hierarchy of large cardinal notions strengthening [weakly
compact](Weakly_compact "Weakly compact")
cardinals, while weakening the $M$-ultrafilter characterization of
Ramsey cardinals. Recall that if $\kappa$ is Ramsey, then every
$A\subseteq\kappa$ is contained in a weak $\kappa$-model $M$ for
which there exists an $M$-ultrafilter, the ultrapower construction with
which may be iterated through all the ordinals. Suppose $M$ is a weak
$\kappa$-model and $U$ is an $M$-ultrafilter on $\kappa$. Define that:

-   $U$ is $0$-good if the ultrapower is well-founded,
-   $U$ is 1-good if it is 0-good and weakly amenable,
-   for an ordinal $\alpha>1$, $U$ is $\alpha$-good, if it produces
    at least $\alpha$-many well-founded iterated ultrapowers.

Using a theorem of Gaifman
{% cite Gaifman1974 %}, if an
$M$-ultrafilter is $\omega_1$-good, then it is already $\alpha$-good
for every ordinal $\alpha$.

For $1\leq\alpha\leq\omega_1$, a cardinal $\kappa$ is
**$\alpha$-iterable** if every $A\subseteq\kappa$ is contained in a
weak $\kappa$-model $M$ for which there exists an $\alpha$-good
$M$-ultrafilter on $\kappa$.

The $\alpha$-iterable cardinals form a hierarchy of strength above
weakly compact cardinals and below Ramsey cardinals.

The $1$-iterable cardinals are sometimes called the **weakly Ramsey**
cardinals.

### Results

Lower limit:

-   $1$-iterable cardinals are
    <a href="Weakly_ineffable" class="mw-redirect" title="Weakly ineffable">weakly ineffable</a>
    and stationary limits of
    <a href="Completely_ineffable" class="mw-redirect" title="Completely ineffable">completely ineffable</a>
    cardinals. The least $1$-iterable cardinal is not ineffable.
    {% cite Gitman2011 %}
-   Super weakly Ramsey cardinals are weakly Ramsey (=$1$-iterable)
    limits of weakly Ramsey cardinals.

Upper limit:

-   A Ramsey cardinal is $\omega_1$-iterable and a stationary limit of
    $\omega_1$-iterable cardinals. This is already true of an
    $\omega_1$-[Erdős](Erdos "Erdos")
    cardinal. {% cite Sharpe2011 %}
-   If $C ∈ V\[H\]$, a forcing extension by $\mathrm{Coll}(ω, V_κ)$,
    is a club in $κ$ of generating indiscernibles for $V_κ$ of
    order-type $κ$ (like in the definition of
    <a href="Silver_cardinal" class="mw-redirect" title="Silver cardinal">Silver cardinals</a>),
    then each $ξ ∈ C$ is $<
    ω_1$-iterable.{% cite Gitmana %}
-   $ω_1$-iterable cardinals are
    <a href="Strongly_unfoldable" class="mw-redirect" title="Strongly unfoldable">strongly unfoldable</a>
    in $L$.{% cite Gitman2011a %}

Hierarchy:

-   An $\alpha$-iterable cardinal is $\beta$-iterable and a stationary
    limit of $\beta$-iterable cardinals for every $\beta<\alpha$.
    {% cite Gitman2011a %}
-   For $β > 0$, every $(α, β)$-Ramsey is a $β$-iterable stationary
    limit of $β$-iterables.
-   It is consistent from an
    $\omega$-[Erdős](Erdos "Erdos")
    cardinal that for every $n\in\omega$, there is a proper class of
    $n$-iterable cardinals.
-   For an additively indecomposable ordinal $λ ≤ ω_1$, $η_λ$ (the
    least $λ$-Erdős cardinal) is a limit of $λ$-iterable cardinals and
    if there is a $λ + 1$-iterable cardinal, then there is a $λ$-Erdős
    cardinal below
    it.{% cite Gitmana %}
-   A [virtually
    $n$-huge*](Huge "Huge")
    cardinal is an $n+1$-iterable limit of $n+1$-iterable cardinals. If
    $κ$ is $n+2$-iterable, then $V_κ$ is a model of proper class many
    virtually $n$-huge*
    cardinals.{% cite Gitmana %}
-   Every virtually rank-into-rank cardinal is an
    $ω$-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>
    limit of $ω$-iterable
    cardinals.{% cite Gitmana %}

Between $1$- and $2$-iterable:

-   A $2$-iterable cardinal implies the consistency of a
    [remarkable](Remarkable "Remarkable")
    cardinal: Every $2$-iterable cardinal is a limit of remarkable
    cardinals. {% cite Gitman2011a %}
-   Remarkable cardinals imply the consistency of $1$-iterable
    cardinals: If there is a remarkable cardinal, then there is a
    countable transitive model of ZFC with a proper class of
    $1$-iterable cardinals.
    {% cite Gitman2011a %}
-   If $κ$ is $2$-iterable, then $V_κ$ is a model of proper class many
    [virtually
    $C^{(n)}$-extendible](Extendible "Extendible")
    cardinals for every $n < ω$, of proper class many
    <a href="Shelah" class="mw-redirect" title="Shelah">virtually Shelah for supercompactness</a>
    cardinals{% cite Gitmana %} and
    of proper class many
    <a href="Completely_remarkable" class="mw-redirect" title="Completely remarkable">completely remarkable</a>
    cardinals.{% cite Bagaria2017a %}
-   Virtually extendible cardinals are 1-iterable limits of 1-iterable
    cardinals.{% cite Gitmana %}

Absoluteness:

-   $\omega_1$-iterable cardinals imply that
    <a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^\sharp$</a>
    exists and hence there cannot be $\omega_1$-iterable cardinals in
    $L$. For $L$-countable $\alpha$, the $\alpha$-iterable cardinals
    are downward absolute to $L$. In fact, if
    <a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^\sharp$</a>
    exists, then every Silver indiscernible is $\alpha$-iterable in $L$
    for every $L$-countable $\alpha$.
    {% cite Gitman2011a %}
-   $\alpha$-iterable cardinals $\kappa$ are preserved by small
    forcing, by the canonical forcing of the ${\rm GCH}$, by fast
    function forcing, and by the forcing to add a slim $\kappa$-Kurepa
    tree. If $\kappa$ is $\alpha$-iterable, there is a forcing
    extension in which $\kappa$ remains $\alpha$-iterable and
    $2^\kappa\gt\kappa$.
    {% cite Gitman %}

## Mahlo–Ramsey cardinals

The property of being Mahlo–Ramsey (MR) is a slight strengthening of
Ramseyness introduced in analogy to
[Mahlo](Mahlo "Mahlo")
cardinals in {% cite Sharpe2011 %} (all
information from there).

For a regular cardinal $κ$ and a sequence of canonical functions $⟨ f_α
: α < κ^+ ⟩$

-   $κ$ is $0$-MR iff it is Ramsey.
-   $κ$ is $(α + 1 )$-MR iff for any $g : \mathcal{P}_{<ω}(κ) → 2$
    there is an $X ∈ NS^+_κ$ such that $X$ is homogeneous for $g$ and
    $∀_{μ ∈ X} \text{$μ$ is $f_α (μ)$-MR}$.
-   $κ$ is $δ$-MR for limit $δ < κ^+$ iff it is $α$-MR for all $α
    < δ$.

Any $\Pi_2$-Ramsey cardinal is $α$-MR for all $α < κ^+$.

## Very Ramsey cardinals

For $X ⊆ κ$ and ordinal $α$, $G_R(X, α)$ is a certain game for two
players with finitely many moves defined in (Sharpe&Welch11). $X$ is
Sharpe-Welch $\alpha$-Ramsey iff (II) wins $G_R(X, α)$. $G_r(X, α)$
(also defined there) is a modification of the game allowing $1+α$ moves.
$X$ is **$\alpha$-very Ramsey** iff (II) has a winning strategy in
$G_r(X, α)$.{% cite Sharpe2011 %}

For $n < ω$, the games $G_R(X, n)$ and $G_r(X, n)$
coincide.{% cite Sharpe2011 %}

In analogy to coherent $<α$-very Ramsey, one can define coherent
$<α$-very Ramsey cardinals. $α$-very Ramsey cardinals are equivalent
to coherent $<α$-very Ramsey cardinals for limit $α$ and to
$<(α+1)$-very Ramsey cardinals in general. (This just allows to
“subtract one” for successor
ordinals.){% cite Nielsen2018 %}

Results:

-   A cardinal is completely Ramsey iff it is $ω$-very
    Ramsey. {% cite Sharpe2011 Nielsen2018 %}
-   If $κ$ is a
    [measurable](Measurable "Measurable")
    cardinal, then $κ$ is $κ$-very
    Ramsey.{% cite Sharpe2011 %}
-   If a cardinal is $ω_1$-very Ramsey (=strategic $ω_1$-Ramsey
    cardinal), then it is measurable in the [core
    model](Core_model "Core model")
    unless
    <a href="Zero_pistol" class="mw-redirect" title="Zero pistol">$0^\P$</a>
    exists and an inner model with a
    [Woodin](Woodin "Woodin")
    cardinal exists. {% cite Sharpe2011 Nielsen2018 %} 

Additional results from
{% cite Nielsen2018 %}:

-   For limit ordinal $α$, every coherent $<ωα$-Ramsey is $ωα$-very
    Ramsey.
-   For any ordinal $α$, every coherent $<α$-very Ramsey is coherent
    $<α$-Ramsey.
-   For limit ordinal $α$, $κ$ is $ωα$-very Ramsey iff it is coherent
    $<ωα$-Ramsey.
-   $κ$ is $λ$-very Ramsey iff it is strategic $λ$-Ramsey for any $λ$
    with uncountable cofinality.

## Virtually Ramsey cardinal

Virtually Ramsey cardinals were introduced by Sharpe and Welch in
{% cite Sharpe2011 %}. They weaken the good
indiscernibles characterization of Ramsey cardinals and were motivated
by finding an upper bound on the consistency strength of a variant of
Chang's Conjecture studied in
{% cite Sharpe2011 %}. For
$A\subseteq\kappa$, define that $\mathscr
I=\{\alpha<\kappa\mid$ there is an unbounded good set of
indiscernibles $I_\alpha\subseteq\alpha$ for $\langle
L_\kappa\[A\],A\rangle\}$. A cardinal $\kappa$ is virtually Ramsey
if for every $A\subseteq\kappa$, the set $\mathscr I$ contains a club
of $\kappa$.

Virtually Ramsey cardinals are
[Mahlo](Mahlo "Mahlo") and
a virtually Ramsey cardinal that is [weakly
compact](Weakly_compact "Weakly compact")
is already Ramsey. If $κ$ is Ramsey, then there is a forcing extension
destroying this, while preserving that $κ$ is virtually Ramsey. It is
open whether virtually Ramsey cardinals are weaker than Ramsey
cardinals. {% cite Gitman2011a Gitman %} 

If κ is virtually Ramsey then κ is [greatly
Erdős](Erdos "Erdos").{% cite Sharpe2011 %}

## Super weakly Ramsey cardinal

(All from {% cite Holy2018 %})

A cardinal $κ$ is **super weakly Ramsey** iff every $A ⊆ κ$ is
contained, as an element, in a weak
κ-[model](Model "Model") $M
≺ H(κ^+)$ for which there exists a $κ$-powerset preserving elementary
embedding $j∶ M → N$.

Strength:

-   Super weakly Ramsey cardinals are weakly Ramsey (=$1$-iterable)
    limits of weakly Ramsey cardinals.
-   Super weakly Ramsey cardinals are
    [ineffable](Ineffable "Ineffable").
-   $ω$-Ramsey cardinals are super weakly Ramsey limits of super weakly
    Ramsey cardinals.

## $α$-Ramsey cardinal etc.

### $α$-Ramsey cardinal for cardinal $α$

(All from {% cite Holy2018 %})

For regular cardinal $α ≤ κ$, $κ$ is $α$-Ramsey iff for arbitrarily
large regular cardinals $θ$, every $A ⊆ κ$ is contained, as an element,
in some weak $κ$-model $M ≺ H(θ)$ which is closed under
$<α$-sequences, and for which there exists a $κ$-powerset preserving
elementary embedding $j∶ M → N$.

Note that, in the case $α = κ$, a weak $κ$-model closed under
$<κ$-sequences is exactly a $κ$-model.

Alternate characterisation:

-   For regular uncountable cardinal $α ≤ κ$, $κ$ is $α$-Ramsey iff $κ =
    κ^{<κ}$ has the $α$-filter property.
-   $κ$ is $ω$-Ramsey iff $κ = κ^{<κ}$ has the well-founded
    $ω$-filter property.

This characterisation works better for singular alpha $α$ (the original
one would imply being $α^+$-Ramsey; well-founded $α$-filter property is
better for countable cofinality).

### Games for definitions

(from {% cite Nielsen2018 %} unless otherwise
noted)

For a weak
$κ$-[model](Model "Model")
$\mathcal{M}$, $μ$ is an
*$\mathcal{M}$-<a href="Measure" class="mw-redirect" title="Measure">measure</a>*
iff $(\mathcal{M}, \in, μ) \models \text{“$μ$ is a $κ$-complete
ultrafilter on $κ$”}$.

Games $G_1$ and $G_2$ are *equivalent* when each of two players has a
winning strategy in $G_1$ if and only if he has one in $G_2$.

The $α$-Ramsey cardinals are based upon *well-founded filter
games*{% cite Holy2018 %}
$wfG^θ_γ(κ)$ (full definition in sources).

-   Player I
    (*challenger*{% cite Holy2018 %})
    gives $\subseteq$-increasing $κ$-models $\mathcal{M}_α ≺ H_θ$,
-   player II
    (*judge*{% cite Holy2018 %}) gives
    $\subseteq$-increasing filters $μ_α$ that are
    $\mathcal{M}_α$-measures
-   and II wins iff after $γ$ rounds $μ$ is an $\mathcal{M}$-normal
    good $\mathcal{M}$-measure for $μ = \bigcup_{α<γ} μ_α$ and
    $\mathcal{M} = \bigcup_{α<γ} \mathcal{M}_α$.

The games $wfG^{θ_0}_γ(κ)$ and $wfG^{θ_1}_γ(κ)$ are equivalent for
any $γ$ with $\mathrm{cof}(γ) \neq ω$ and any regular $θ_0, θ_1 <
κ$.

$\mathcal{G}^θ_γ(κ, ζ)$ is a similar family of games (again full
definition in sources).

-   Each of them lasts up to $γ+1$ rounds
-   and player II wins when he does not have to end the game before
    $γ+1$ rounds pass
-   (I gives $\subseteq$-increasing weak $κ$-models
-   and II must give normal $\mathcal{M}_α$-measures with additional
    requirements for limit $α$ (eg. $μ_α$ is $ζ$-good) and for the last
    move).

For convenience

-   $\mathcal{G}^θ_γ(κ) := \mathcal{G}^θ_γ(κ, 0)$
-   $\mathcal{G}_γ(κ) := \mathcal{G}^θ_γ(κ)$ whenever
    $\mathrm{cof}(γ) \neq ω$ as again the existence of winning
    strategies in these games does not depend upon a specific $θ$.

$\mathcal{G}^θ_γ(κ)$, $\mathcal{G}^θ_γ(κ, 1)$ and $wfG^θ_γ(κ)$ are
all equivalent for all limit ordinals $γ \leq κ$. $\mathcal{G}^θ_γ(κ,
ζ)$ is equivalent to $\mathcal{G}^θ_γ(κ)$ whenever $\mathrm{cof}(γ)
> ω$.

### Generalisations

(from {% cite Nielsen2018 %})

Now we can define $γ$-Ramsey cardinals for any ordinal $γ$ and other
variants: Let $κ$ be a cardinal and $γ \leq κ$ an ordinal:

-   $κ$ is **$γ$-Ramsey** iff player I does not have a winning strategy
    in $\mathcal{G}^θ_γ(κ)$ for all regular $θ > κ$.
-   $κ$ is **strategic $γ$-Ramsey** iff player II does have a winning
    strategy in $\mathcal{G}^θ_γ(κ)$ for all regular $θ > κ$.
-   **(Strategic) genuine $γ$-Ramseys** and **(strategic) normal
    $γ$-Ramseys** are defined analogously, with the additional
    requirement for the last measure $μ_γ$ to be genuine and normal,
    respectively.
-   $κ$ is $<γ$-Ramsey iff it is $α$-Ramsey for every $α < γ$.
-   $κ$ is **almost fully Ramsey** iff it is $<κ$-Ramsey.
-   $κ$ is **fully Ramsey** iff it is $κ$-Ramsey.
-   $κ$ is **coherent $<γ$-Ramsey** iff it is strategic
    $<γ$-Ramsey and a single strategy works for player II in
    $\mathcal{G}_α(κ)$ for every $α < γ$.
    -   I.e., in a choice of strategies for each $α$, strategies for
        greater $α$ contain strategies for lesser $α$. Full definition
        in {% cite Nielsen2018 %}.

(Some of the notions defined in
{% cite Nielsen2018 %} were not new, but
gained more convenient names.)

### Filter property

(from {% cite Holy2018 %})

$κ$ has the **filter property** iff for every subset $X$ of
$\mathcal{P}(κ)$ of size $≤κ$, there is a $<κ$-complete filter $F$
on $κ$ which measures $X$. For normal filter we talk about *normal
filter property*.

Strengthenings:

-   $κ$ has the **$γ$-filter property** iff player I does not have a
    winning strategy in $G^θ_γ(κ)$.
-   $κ$ has the **strategic $γ$-filter property** iff player II does
    have a winning strategy in $G^θ_γ(κ)$.
-   $κ$ has the **well-founded $(γ, θ)$-filter property** iff player I
    does not have a winning strategy in $wfG^θ_γ(κ)$.
-   $κ$ has the **well-founded $γ$-filter property** iff it has the
    well-founded $(γ, θ)$-filter property for all regular $θ > κ$.

For $γ_1 > γ_0$, the $γ_1$-filter property implies the
$γ_0$-filter property.

### Results

Results in the finite case (for $n <
ω$):{% cite Nielsen2018 %}

-   For a cardinal $κ=κ^{<κ}$
    -   $κ$ is [weakly
        compact](Weakly_compact "Weakly compact")
        iff it is 0-Ramsey;
    -   $κ$ is
        <a href="Weakly_ineffable" class="mw-redirect" title="Weakly ineffable">weakly ineffable</a>
        iff it is genuine 0-Ramsey;
    -   $κ$ is
        [ineffable](Ineffable "Ineffable")
        iff it is normal 0-Ramsey. (An uncountable cardinal κ has the
        normal filter property iff it is
        ineffable.{% cite Holy2018 %})
-   Every $n$-Ramsey $κ$ is $Π^1_{2 n+1}$-indescribable. This is
    optimal, as $n$-Ramseyness can be described by a $Π^1_{2
    n+2}$-formula.
-   Every $<ω$-Ramsey cardinal is $∆^2_0$-indescribable.
-   Every normal $n$-Ramsey $κ$ is $Π^1_{2 n+2}$-indescribable. This is
    optimal, as normal $n$-Ramseyness can be described by a $Π^1_{2
    n+3}$-formula.
-   Every $n+1$-Ramsey is a normal $n$-Ramsey stationary limit of normal
    $n$-Ramseys and every normal $n$-Ramsey is an $n$-Ramsey stationary
    limit of $n$-Ramseys.
-   Genuine- and normal $n$-Ramseys are downwards absolute to $L$.
-   Every $(n+1)$-Ramsey is normal $n$-Ramsey in $L$. Therefore,
    $<ω$-Ramseys are downwards absolute to $L$.

Results for
$ω$-Ramsey:{% cite Holy2018 %}

-   $ω$-Ramsey cardinals are super weakly Ramsey limits of super weakly
    Ramsey cardinals.
-   $ω$-Ramsey cardinals are limits of cardinals with the $ω$-filter
    property (=completely
    [ineffable](Ineffable "Ineffable"){% cite Nielsen2018 %}).
-   $ω$-Ramsey cardinals are downwards absolute to $L$. If
    <a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^♯$</a>
    exists, then all Silver indiscernibles are $ω$-Ramsey in $L$.

Results for strategic
$ω$-Ramsey:{% cite Nielsen2018 %}

-   <a href="Virtually_measurable" class="mw-redirect" title="Virtually measurable">Virtually measurable</a>
    cardinals, strategic $ω$-Ramsey cardinals and
    [remarkable](Remarkable "Remarkable")
    cardinals are equiconsistent.
    -   Every virtually measurable cardinal is strategic $ω$-Ramsey, and
        every strategic $ω$-Ramsey cardinal is virtually measurable in
        $L$.
    -   If $κ$ is virtually measurable, then either $κ$ is
        [remarkable](Remarkable "Remarkable")
        in $L$ or $L_κ \models \text{“there is a proper class of
        virtually measurables”}$.
    -   Remarkable cardinals are strategic $ω$-Ramsey limits of
        $ω$-Ramsey cardinals.
-   Therefore, if $κ$ is a strategic ω-Ramsey cardinal then $L_κ
    \models \text{“there is a proper class of $ω$-Ramseys”}$.

Equiconsistency with the
[measurable](Measurable "Measurable")
cardinal:

-   The existence of a strategic $(ω+1)$-Ramsey cardinal (and of
    strategic fully Ramsey cardinal) is equiconsistent with the
    existence of a measurable
    cardinal.{% cite Nielsen2018 %}
-   If $κ$ is a measurable cardinal, then $κ$ is $κ$-very Ramsey. If a
    cardinal is $ω_1$-very Ramsey (=strategic $ω_1$-Ramsey cardinal),
    then it is measurable in the [core
    model](Core_model "Core model")
    unless
    <a href="Zero_pistol" class="mw-redirect" title="Zero pistol">$0^\P$</a>
    exists and an inner model with a
    [Woodin](Woodin "Woodin")
    cardinal exists. {% cite Sharpe2011 Nielsen2018 %}
-   If $κ$ is uncountable, $κ = κ^{<κ}$ and $2^κ = κ^+$, then the
    following are
    equivalent:{% cite Holy2018 %}
    -   $κ$ is measurable.
    -   $κ$ satisfies the $κ^+$-filter property.
    -   $κ$ satisfies the strategic $κ^+$-filter property.
-   On the other hand, starting from a $κ^{++}$-tall cardinal $κ$, it is
    consistent that there is a cardinal $κ$ with the strategic
    $κ^+$-filter property, however $κ$ is not measurable.

Being downwards absolute to the [core
model](Core_model "Core model"):{% cite Nielsen2018 %}

-   If
    <a href="Zero_pistol" class="mw-redirect" title="Zero pistol">$0^\P$</a>
    does not exist:
    -   If $α$ is a limit ordinal with uncountable cofinality, then
        being $α$-Ramsey is downwards absolute to $\mathbf{K}$.
    -   If $α$ is a limit ordinal, then genuine $α$-Ramseyness and
        normal $α$-Ramseyness are both downwards absolute to
        $\mathbf{K}$.
    -   if $α$ is a limit of limit ordinals, then $<α$-Ramseyness is
        downwards absolute to $\mathbf{K}$.

Strategic $α$-Ramsey (including coherent $<α$-Ramsey) and $α$-very
Ramsey:{% cite Nielsen2018 %}

-   For limit ordinal $α$, every coherent $<ωα$-Ramsey is $ωα$-very
    Ramsey.
-   For any ordinal $α$, every coherent $<α$-very Ramsey is coherent
    $<α$-Ramsey.
-   For limit ordinal $α$, $κ$ is $ωα$-very Ramsey iff it is coherent
    $<ωα$-Ramsey.
-   $κ$ is $λ$-very Ramsey iff it is strategic $λ$-Ramsey for any $λ$
    with uncountable cofinality.

Hierarchy:{% cite Holy2018 %}

-   If $ω ≤ α_0 < α_1 ≤ κ$, both $α_0$ and $α_1$ are cardinals,
    and $κ$ is $α_1$-Ramsey, then there is a proper class of
    $α_0$-Ramsey cardinals in $V_κ$. If $α_0$ is regular, then $κ$ is
    a limit of $α_0$-Ramsey cardinals.
-   If $α ≤ κ$ are both cardinals and $κ$ is $α$-Ramsey, then $κ$ has a
    well-founded $α$-filter sequence.
-   If $ω ≤ α < β ≤ κ$ are cardinals and $κ$ has a $β$-filter
    sequence, then there is a proper class of $α$-Ramsey cardinals in
    $V_κ$. If $α$ is regular, then $κ$ is a limit of $α$-Ramsey
    cardinals.

Other:

-   Every $(ω+1)$-Ramsey cardinal is a completely Ramsey stationary
    limit of completely Ramsey
    cardinals.{% cite Nielsen2018 %}
-   Every strongly Ramsey cardinal is a stationary limit of almost fully
    Ramseys.{% cite Nielsen2018 %}
-   Fully Ramsey cardinals are super Ramsey limits of super Ramsey
    cardinals.{% cite Holy2018 %}
-   [Measurable](Measurable "Measurable")
    cardinals are limits of fully Ramsey
    cardinals.{% cite Holy2018 %}

### $(α, β)$-Ramsey cardinals

(All information from {% cite Nielsen2018 %})

$κ$ is **$(α, β)$-Ramsey** iff player I has no winning strategy in
$\mathcal{G}^θ_α(κ, β)$ for all regular $θ > κ$.

Of course, this notion is interesting only for $\mathrm{cof}(α) = ω$.

$α$-Ramsey cardinals are by definition equivalent to $(α, 0)$-Ramsey
cardinals.

Position in the hierarchy of
[Erdős](Erdos "Erdos") and
iterable cardinals:

-   For $β > 0$, every $(α, β)$-Ramsey is a $β$-iterable stationary
    limit of $β$-iterables.
-   For additively closed $ω \leq α \leq ω_1$, any $α$-Erdős cardinal
    is a limit of $(ω, α)$-Ramsey cardinals.

This means also that $(ω, α)$-Ramsey cardinals are consistent with $V =
L$ if $α < ω_1^L$ and that they are not if $α = ω_1$ .

### $(γ, θ)$-Ramsey cardinals

$κ$ is **$(γ, θ)$-Ramsey** iff player I has no winning strategy in
$\mathcal{G}^θ_γ(κ)$ (i.e. $κ$ is $γ$-Ramsey iff it is $(γ, θ)$-Ramsey
for every $θ > κ$). Not much is known about them in
general.{% cite Nielsen2018 %}

## M-rank

(from {% cite Carmody2016 %})

M-rank for Ramsey and Ramsey-like cardinals is analogous to [Mitchell
rank](Mitchell_rank "Mitchell rank").
A difference is that M-rank for Ramsey-like cardinals can be at most
$\kappa^+$ (because an ultrapower of a weak $κ$-model has size at most
$κ$) and Mitchell rank for
[measurable](Measurable "Measurable")
cardinals can be at most $(2^\kappa)^+$.

Definition of the M-order: For $κ$ having a large-cardinal property
$\mathscr{P}$ with an embedding characterisation and for two witness
collections $\mathcal{U}$ and $\mathcal{W}$ of
$\mathscr{P}$-measures, we say that $U⊳W$ if

-   for every $W∈\mathcal{W}$ and $A⊆κ$ in the ultrapower $N_W$ of
    $M_W$ by $W$, there is an $A$-good $U∈ \mathcal{U} ∩ N_W$ such
    that $N_W \models \text{“$\mathcal{U}$ is an $A$-good
    $\mathscr{P}$-measure on $κ$”}$.
-   $\mathcal{U} ⊆ ⋃_{W∈\mathcal{W}} N_W$.

Results:

-   Any strongly Ramsey cardinal $κ$ has Ramsey M-rank $κ^+$,
-   any super Ramsey cardinal $κ$ has strongly Ramsey M-rank $κ^+$
-   and any measurable cardinal $κ$ has super Ramsey M-rank $κ^+$.

Ramsey and Ramsey-like M-orders can be softly killed (Rank $α$ can be
turned into rank $β$ for any $β < α$) using cofinality-preserving
forcing extension.
