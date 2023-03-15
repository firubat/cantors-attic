---
title: Extendible cardinal
permalink: Extendible
redirect_from:
  - Completely_remarkable
  - N-remarkable
---


A cardinal $\kappa$ is *$\eta$-extendible* for an ordinal $\eta$ if
and only if there is an [elementary
embedding](Elementary_embedding "Elementary embedding")
$j:V_{\kappa+\eta}\to V_\theta$, with critical point $\kappa$,
for some ordinal $\theta$. The cardinal $\kappa$ is *extendible* if
and only if it is $\eta$-extendible for every ordinal $\eta$.
Equivalently, for every ordinal $\alpha$ there is a nontrivial
elementary embedding $j:V_{\kappa+\alpha+1}\to
V_{j(\kappa)+j(\alpha)+1}$ with critical point $\kappa$.



## Alternative definition

Given cardinals $\lambda$ and $\theta$, a cardinal
$\kappa\leq\lambda,\theta$ is *jointly $\lambda$-supercompact and
$\theta$-superstrong* if there exists a nontrivial elementary embedding
$j:V\to M$ for some transitive class $M$ such that
$\mathrm{crit}(j)=\kappa$, $\lambda<j(\kappa)$,
$M^\lambda\subseteq M$ and $V_{j(\theta)}\subseteq M$. That is, a
single embedding witnesses both
$\lambda$-[supercompactness](Supercompact "Supercompact")
and (a strengthening of)
[superstrongness](Superstrong "Superstrong")
of $\kappa$. The least supercompact is never jointly
$\lambda$-supercompact and $\theta$-superstrong for any
$\lambda$,$\theta\geq\kappa$.

A cardinal is extendible if and only if it is jointly supercompact and
$\kappa$-superstrong, i.e. for every $\lambda\geq\kappa$ it is
jointly $\lambda$-supercompact and $\kappa$-superstrong.
<a href="http://logicatorino.altervista.org/slides/150619tsaprounis.pdf" class="external autonumber">[1]</a>
One can show that extendibility of $\kappa$ is in fact equivalent to
"for all $\lambda$,$\theta\geq\kappa$, $\kappa$ is jointly
$\lambda$-supercompact and $\theta$-superstrong". A similar
characterization of $C^{(n)}$-extendible cardinals exists.

The
[ultrahuge](Huge "Huge")
cardinals are defined in a way very similar to this, and one can (very
informally) say that "ultrahuge cardinals are to superhuges what
extendibles are to supercompacts". These cardinals are superhuge (and
stationary limits of superhuges) and strictly below almost 2-huges in
consistency strength.

*To be expanded: Extendibility Laver Functions*

## Relation to Other Large Cardinals

Extendible cardinals are related to various kinds of measurable
cardinals.

Hyper-[huge](Huge "Huge")
cardinals are extendible limits of extendible
cardinals.{% cite Usuba2019 %}

### Supercompactness

Extendibility is connected in strength with
[supercompactness](Supercompact "Supercompact").
Every extendible cardinal is supercompact, since from the embeddings
$j:V_\lambda\to V_\theta$ we may extract the induced
supercompactness measures $X\in\mu\iff j''\delta\in j(X)$ for
$X\subset \mathcal{P}_\kappa(\delta)$, provided that
$j(\kappa)\gt\delta$ and $\mathcal{P}_\kappa(\delta)\subset
V_\lambda$, which one can arrange. On the other hand, if $\kappa$ is
$\theta$-supercompact, witnessed by $j:V\to M$, then $\kappa$ is
$\delta$-extendible inside $M$, provided $\beth_\delta\leq\theta$,
since the restricted elementary embedding $j\upharpoonright
V_\delta:V_\delta\to j(V_\delta)=M_{j(\delta)}$ has size at
most $\theta$ and is therefore in $M$, witnessing
$\delta$-extendibility there.

Although extendibility itself is stronger and larger than
[supercompactness](Supercompact "Supercompact"),
$\eta$-supercompacteness is not necessarily too much weaker than
$\eta$-extendibility. For example, if a cardinal $\kappa$ is
$\beth_{\eta}(\kappa)$-supercompact (in this case, the same as
$\beth_{\kappa+\eta}$-supercompact) for some $\eta<\kappa$,
then there is a normal measure $U$ over $\kappa$ such that
$\{\lambda<\kappa:\lambda\text{ is
}\eta\text{-extendible}\}\in U$.

### Strong Compactness

Interestingly, extendibility is also related to [strong
compactness](Strongly_compact "Strongly compact").
A cardinal $\kappa$ is strongly compact iff the infinitary language
$\mathcal{L}_{\kappa,\kappa}$ has the $\kappa$-compactness
property. A cardinal $\kappa$ is extendible iff the infinitary language
$\mathcal{L}_{\kappa,\kappa}^n$ (the infinitary language but with
$(n+1)$-th order logic) has the $\kappa$-compactness property for every
natural number $n$. {% cite Kanamori2009 %}

Given a logic $\mathcal{L}$, the minimum cardinal $\kappa$ such that
$\mathcal{L}$ satisfies the $\kappa$-compactness theorem is called the
**strong compactness cardinal** of $\mathcal{L}$. The strong
compactness cardinal of $\omega$-th order finitary logic (that is, the
union of all $\mathcal{L}_{\omega,\omega}^n$ for natural $n$) is the
least extendible cardinal.

## Variants

### $C^{(n)}$-extendible cardinals

(Information in this subsection from
{% cite Bagaria2012 %} unless noted otherwise)

A cardinal $κ$ is called **$C^{(n)}$-extendible** if for all $λ > κ$
it is $λ$-$C^{(n)}$-extendible, i.e. if there is an ordinal $µ$ and an
elementary embedding $j : V_λ → V_µ$, with $\mathrm{crit(j)} = κ$,
$j(κ) > λ$ and $j(κ) ∈ C^{(n)}$.

For $λ ∈ C^{(n)}$, a cardinal $κ$ is $λ$-$C^{(n)+}$-extendible iff it is
$λ$-$C^{(n)}$-extendible, witnessed by some $j : V_λ → V_µ$ which
(besides $j(κ) > λ$ and $j(κ) ∈ C(n)$) satisfies that $µ ∈ C^{(n)}$.

$κ$ is $C^{(n)+}$-extendible iff it is $λ$-$C^{(n)+}$-extendible for
every $λ > κ$ such that $λ ∈ C^{(n)}$.

Properties:

-   The notions of $C^{(n)}$-extendible cardinals and
    $C^{(n)+}$-extendible cardinals are
    equivalent.{% cite Gitman2018 %}
-   Every extendible cardinal is $C^{(1)}$-extendible.
-   If $κ$ is $C^{(n)}$-extendible, then $κ ∈ C^{(n+2)}$.
-   For every $n ≥ 1$, if $κ$ is $C^{(n)}$-extendible and
    $κ+1$-$C^{(n+1)}$-extendible, then the set of $C^{(n)}$-extendible
    cardinals is unbounded below $κ$.
    -   Hence, the first $C^{(n)}$-extendible cardinal $κ$, if it
        exists, is not $κ+1$-$C^{(n+1)}$-extendible.
    -   In particular, the first extendible cardinal $κ$ is not
        $κ+1$-$C^{(2)}$-extendible.
-   For every $n$, if there exists a $C^{(n+2)}$-extendible cardinal,
    then there exist a proper class of $C^{(n)}$-extendible cardinals.
-   The existence of a $C^{(n+1)}$-extendible cardinal $κ$ (for $n ≥ 1$)
    does not imply the existence of a $C^{(n)}$-extendible cardinal
    greater than $κ$. For if $λ$ is such a cardinal, then $V_λ
    \models$“κ is $C^{(n+1)}$-extendible”.
-   If $κ$ is $κ+1$-$C^{(n)}$-extendible and belongs to $C^{(n)}$, then
    $κ$ is
    $C^{(n)}$-[superstrong](Superstrong "Superstrong")
    and there is a $κ$-complete normal
    <a href="Ultrafilter" class="mw-redirect" title="Ultrafilter">ultrafilter</a>
    $U$ over $κ$ such that the set of $C^{(n)}$-superstrong cardinals
    smaller than $κ$ belongs to $U$.
-   For $n ≥ 1$, the following are equivalent ($VP$ — [Vopěnka's
    principle](Vopenka "Vopenka")):
    -   $VP(Π_{n+1})$
    -   $VP(κ, \mathbf{Σ_{n+2}})$ for some $κ$
    -   There exists a $C(n)$-extendible cardinal.
-   “For every $n$ there exists a $C(n)$-extendible cardinal.” is
    equivalent to the full Vopěnka's principle.
-   Assuming [$\mathrm{I3}(κ,
    δ)$](Rank_into_rank "Rank into rank"),
    if $δ$ is a limit cardinal (instead of a successor of a limit
    cardinal – Kunen’s Theorem excludes other cases), it is equal to
    $sup\{j^m(κ) : m ∈ ω\}$ where $j$ is the elementary embedding.
    Then $κ$ and $j^m(κ)$ are $C^{(n)}$-extendible (inter alia) in
    $V_δ$, for all $n$ and $m$.

### $(\Sigma_n,\eta)$-extendible cardinals

There are some variants of extendible cardinals because of the
interesting jump in consistency strength from $0$-extendible cardinals
to $1$-extendibles. These variants specify the elementarity of the
embedding.

A cardinal $\kappa$ is $(\Sigma_n,\eta)$-extendible, if there is a
$\Sigma_n$-elementary embedding $j:V_{\kappa+\eta}\to V_\theta$
with critical point $\kappa$, for some ordinal $\theta$. These
cardinals were introduced by Bagaria, Hamkins, Tsaprounis and Usuba
{% cite Bagaria2013 %}.

### $\Sigma_n$-extendible cardinals

The special case of $\eta=0$ leads to a much weaker notion.
Specifically, a cardinal $\kappa$ is *$\Sigma_n$-extendible* if it is
$(\Sigma_n,0)$-extendible, or more simply, if
$V_\kappa\prec_{\Sigma_n} V_\theta$ for some ordinal $\theta$.
Note that this does not necessarily imply that $\kappa$ is
inaccessible, and indeed the existence of $\Sigma_n$-extendible
cardinals is provable in ZFC via the reflection theorem. For example,
every [$\Sigma_n$
correct](Reflecting#Reflection_and_correctness "Reflecting")
cardinal is $\Sigma_n$-extendible, since from
$V_\kappa\prec_{\Sigma_n} V$ and $V_\lambda\prec_{\Sigma_n}
V$, where $\kappa\lt\lambda$, it follows that
$V_\kappa\prec_{\Sigma_n} V_\lambda$. So in fact there is a
closed unbounded class of $\Sigma_n$-extendible cardinals.

Similarly, every Mahlo cardinal $\kappa$ has a stationary set of
inaccessible $\Sigma_n$-extendible cardinals $\gamma<\kappa$.

$\Sigma_3$-extendible cardinals cannot be Laver indestructible.
Therefore
$\Sigma_3$-<a href="Correct" class="mw-redirect" title="Correct">correct</a>,
$\Sigma_3$-[reflecting](Reflecting "Reflecting"),
$0$-extendible,
(pseudo-)[uplifting](Uplifting "Uplifting"),
<a href="Weakly_superstrong" class="mw-redirect" title="Weakly superstrong">weakly superstrong</a>,
strongly uplifting,
[superstrong](Superstrong "Superstrong"),
extendible, (almost)
[huge](Huge "Huge") or
<a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">rank-into-rank</a>
cardinals also
cannot.{% cite Bagaria2013 %}

### $A$-extendible cardinals

(this subsection from
{% cite Hamkins2016 %})

Definitions:

-   A cardinal $κ$ is **$A$-extendible**, for a class $A$, iff for every
    ordinal $λ > κ$ there is an ordinal $θ$ such that there is an
    elementary embedding
    $j : \langle V_λ , ∈, A ∩ V_λ \rangle → \langle V_θ , ∈, A ∩
    V_θ \rangle$
    with critical point $κ$ (such that $λ < j(κ)$ — *removing this
    does not change, what cardinals are extendible*).
    -   $λ$ is called the degree of $A$-extendibility of an embedding.
-   A cardinal $κ$ is **$(Σ_n)$-extendible**, iff it is $A$-extendible,
    where $A$ is the $Σ_n$-truth predicate. (This is a different notion
    than $\Sigma_n$-extendible
    cardinals.){% cite Gitman2018 %}

Results:

-   The [Vopěnka
    principle](Vopenka "Vopenka")
    is equivalent over GBC to both following statements:
    -   For every class $A$, there is an $A$-extendible cardinal.
    -   For every class $A$, there is a stationary proper class of
        $A$-extendible cardinals.
-   ......

### Virtually extendible cardinals

Definitions:

-   A cardinal $κ$ is (weakly? strongly? ......) **virtually
    extendible** iff for every $α > κ$, in a set-forcing extension
    there is an elementary embedding $j : V_α → V_β$ with
    $\mathrm{crit(j)} = κ$ and $j(κ) > α$.
    -   **$C^{(n)}$-virtually extendible** cardinals require
        additionally that $j(κ)$ has property $C^{(n)}$ (i.e.
        $\Sigma_n$-<a href="Correct" class="mw-redirect" title="Correct">correctness</a>).{% cite Gitmana %}
-   A cardinal $κ$ is **(weakly) virtually $A$-extendible**, for a class
    $A$, iff for every ordinal $λ > κ$ there is an ordinal $θ$ such
    that in a set-forcing extension, there is an elementary embedding
    $j : \langle V_λ , ∈, A ∩ V_λ \rangle → \langle V_θ , ∈, A ∩
    V_θ \rangle$
    with critical point $κ$.
    -   For **(strongly) virtually $A$-extendible** $κ$, we require
        additionally $λ <
        j(κ)$.{% cite Gitman2018 %}
-   A cardinal $κ$ is
    **$n$-[remarkable](Remarkable "Remarkable")**,
    for $n > 0$, iff for every $η > κ$ in
    <a href="Correct" class="mw-redirect" title="Correct">$C^{(n)}$</a>
    , there is $α<κ$ also in $C^{(n)}$ such that in $V^{Coll(ω, <
    κ)}$, there is an elementary embedding $j : V_α → V_η$ with
    $j(\mathrm{crit}(j)) = κ$.
    -   A cardinal is **completely remarkable** iff it is $n$-remarkable
        for all $n >
        0$.{% cite Bagaria2017a %}
-   A cardinal κ is weakly or strongly virtually $(Σ_n)$-extendible,
    iff it is respectively weakly or strongly virtually $A$-extendible,
    where $A$ is the $Σ_n$-truth
    predicate.{% cite Gitman2018 %}

Equivalence and hierarchy:

-   $1$-remarkability is equivalent to remarkability. A cardinal is
    virtually $C^{(n)}$-extendible iff it is $n + 1$-remarkable
    (virtually extendible cardinals are virtually
    $C^{(1)}$-extendible).{% cite Bagaria2017a %}
-   Weakly and strongly $A$-extendible cardinal are non-equivalent,
    although in the non-virtual context, the weak and strong forms of
    $A$-extendibility
    coincide.{% cite Gitman2018 %}
-   It is relatively consistent with GBC that every class $A$ admits a
    (weakly) virtually $A$-extendible cardinal (and so the generic
    Vopěnka principle holds), but no class $A$ admits a (strongly)
    virtually $A$-extendible
    cardinal.{% cite Gitman2018 %}
-   Every $n$-remarkable cardinal is in
    $C^{(n+1)}$.{% cite Bagaria2017a %}
-   Every $n+1$-remarkable cardinal is a limit of $n$-remarkable
    cardinals.{% cite Bagaria2017a %}

Upper limits for strength:

-   If $κ$ is
    <a href="Shelah" class="mw-redirect" title="Shelah">virtually Shelah for supercompactness</a>
    or 2-iterable, then $V_κ$ is a model of proper class many virtually
    $C^{(n)}$-extendible cardinals for every $n <
    ω$.{% cite Gitmana %}
-   If $κ$ is [virtually
    huge*](Huge "Huge"),
    then $V_κ$ is a model of proper class many virtually extendible
    cardinals.{% cite Gitmana %}
-   Completely remarkable cardinals can exist in
    $L$.{% cite Bagaria2017a %}
-   For a
    $2$-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>
    cardinal $κ$, $V_κ$ is a model of proper class many completely
    remarkable
    cardinals.{% cite Bagaria2017a %}
-   If $0^\\#$ exists, then every
    <a href="Silver_indiscernible" class="mw-redirect" title="Silver indiscernible">Silver indiscernible</a>
    is in $L$ completely remarkable and virtually $A$-extendible for
    every definable class
    $A$. {% cite Gitman2018 Bagaria2017a %} 

Lower limit for strength:

-   Virtually extendible cardinals are
    [remarkable](Remarkable "Remarkable")
    limits of remarkable cardinals and
    1-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>
    limits of 1-iterable
    cardinals.{% cite Gitmana %}

In relation to
<a href="Generic_Vop%C4%9Bnka%27s_Principle" class="mw-redirect" title="Generic Vopěnka&#39;s Principle">Generic Vopěnka's Principle</a>:(from
{% cite Bagaria2017a %} unless
noted otherwise)

-   The following are equiconsistent
    -   $gVP(Π_n)$
    -   $gVP(κ, \mathbf{Σ_{n+1}})$ for some $κ$
    -   There is an $n$-remarkable cardinal.
-   The following are equiconsistent
    -   $gVP(\mathbf{Π_n})$
    -   $gVP(κ, \mathbf{Σ_{n+1}})$ for a proper class of $κ$
    -   There is a proper class of $n$-remarkable cardinals.
-   $κ$ is the least for which $gVP^∗(κ, \mathbf{Σ_{n+1}})$ holds.
    $\iff κ$ is the least $n$-remarkable cardinal.
-   If $gVP^∗(Π_n)$, then there is an $n$-remarkable cardinal.
-   If $gVP^∗(\mathbf{Π_n})$ holds, then there is a proper class of
    $n$-remarkable cardinals.
-   If there is a proper class of $n$-remarkable cardinals, then
    $gVP(Σ_{n+1})$
    holds.{% cite Gitman2018 %}
-   If $gVP(Σ_{n+1})$ holds, then either there is a proper class of
    $n$-remarkable cardinals or there is a proper class of
    <a href="Rank-into-rank" class="mw-redirect" title="Rank-into-rank">virtually rank-into-rank</a>
    cardinals.{% cite Gitman2018 %}
-   The generic Vopěnka scheme is equivalent over ZFC to the scheme
    asserting of every definable class $A$ that there is a proper class
    of weakly virtually $A$-extendible
    cardinals.{% cite Gitman2018 %}
-   Open problems: Must there be an $n$-remarkable cardinal
    -   if $gVP(κ, \mathbf{Σ_{n+1}})$ holds for some $κ$.
    -   if $gVP(Π_n)$ holds.

......

## In set-theoretic geology

If $κ$ is extendible then the
$κ$-<a href="Mantle" class="mw-redirect" title="Mantle">mantle</a>
of $V$ is its smallest ground (so of course the mantle is a ground of
V).{% cite Usuba2019 %}

  

        This article is a stub. Please help us to improve Cantor's Attic by adding information.
