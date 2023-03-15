---
title: Rank into rank axioms
permalink: Rank_into_rank
redirect_from:
  - Rank-into-rank
---

A nontrivial [elementary
embedding](Elementary_embedding "Elementary embedding")
$j:V_\lambda\to V_\lambda$ for some infinite ordinal $\lambda$ is
known as a *rank into rank embedding* and the axiom asserting that such
an embedding exists is usually denoted by $\text{I3}$, $\text{I2}$,
$\text{I1}$, $\mathcal{E}(V_\lambda)\neq \emptyset$ or some
variant thereof. The term applies to a hierarchy of such embeddings
increasing in large cardinal strength reaching toward the [Kunen
inconsistency](Kunen_inconsistency "Kunen inconsistency").
The axioms in this section are in some sense a technical restriction
falling out of Kunen's proof that there can be no nontrivial elementary
embedding $j:V\to V$ in $\text{ZFC}$). An analysis of the proof shows
that there can be no nontrivial $j:V_{\lambda+2}\to V_{\lambda+2}$
and that if there is some ordinal $\delta$ and nontrivial rank to rank
embedding $j:V_\delta\to V_\delta$ then necessarily $\delta$ must
be a strong limit cardinal of cofinality $\omega$ or the successor of
one. By standing convention, it is assumed that rank into rank
embeddings are not the identity on their domains.

There are really two cardinals relevant to such embeddings: The large
cardinal is the critical point of $j$ (sometimes it is called just an
$\mathrm{I}n$ cardinal ($n=0,1,2,3$), but sometimes such a name is
avoided), often denoted $\mathrm{crit}(j)$ or sometimes $\kappa_0$,
and the other (not quite so large) cardinal is $\lambda$. In order to
emphasize the two cardinals, the axiom is sometimes written as
$E(\kappa,\lambda)$ (or $\text{I3}(\kappa,\lambda)$, etc.) as in
{% cite Kanamori2009 %}. The cardinal $\lambda$ is
determined by defining the *critical sequence of $j$*. Set $\kappa_0 =
\mathrm{crit}(j)$ and $\kappa_{n+1}=j(\kappa_n)$. Then $\lambda =
\sup \langle \kappa_n : n <\omega\rangle$ and is the first
fixed point of $j$ that occurs above $\kappa_0$. Note that, unlike
many of the other large cardinals appearing in the literature, the
ordinal $\lambda$ is *not* the first target of the critical point; it
is the $\omega^{th}$ $j$-iterate of the critical point.

As a result of the strong closure properties of rank into rank
embeddings, their critical points are
[huge](Huge "Huge") and in
fact $n$-huge for every $n$. This aspect of the large cardinal property
is often called $\omega$-hugeness and the term *$\omega$-huge
cardinal* is sometimes used to refer to the critical point of some rank
into rank embedding.


## The $\text{I3}$ Axiom

The $\text{I3}$ axiom asserts, generally, that there is some embedding
$j:V_\lambda\to V_\lambda$.

$\text{I3}$ is also denoted as
$\mathcal{E}(V_\lambda)\neq\emptyset$ where
$\mathcal{E}(V_\lambda)$ is the set of all elementary embeddings from
$V_\lambda$ to $V_\lambda$, or sometimes even
$\text{I3}(\kappa,\lambda)$ when mention of the relevant cardinals is
necessary.

In its general form, the axiom asserts that the embedding preserves all
first-order structure but fails to specify how much second-order
structure is preserved by the embedding. The case that *no* second-order
structure is preserved is also sometimes denoted by $\text{I3}$. In
this specific case $\text{I3}$ denotes the weakest kind of rank into
rank embedding and so the $\text{I3}$ notation for the axiom is
somewhat ambiguous. To eliminate this ambiguity we say $j$ is
$E_0(\lambda)$ when $j$ preserves only first-order structure.

### $E_n$ axioms

The axiom can be strengthened and refined in a natural way by asserting
that various degrees of second-order correctness are preserved by the
embeddings. A rank into rank embedding $j$ is said to be $\Sigma^1_n$
or *$\Sigma^1_n$ correct* if, for every $\Sigma^1_n$ formula $\Phi$
and $A\subseteq V_\lambda$ the elementary schema holds for $j,\Phi$,
and $A$: $$V_\lambda\models\Phi(A) \Leftrightarrow
V_\lambda\models\Phi(j(A)).$$

The more specific axiom $E_n(\lambda)$ asserts that some
$j\in\mathcal{E}(V_\lambda)$ is $\Sigma^1_{2n}$.

The “$2n$” subscript in the axiom $E_n(\lambda)$ is incorporated so
that the axioms $E_m(\lambda)$ and $E_n(\lambda)$ where $m<n$ are
strictly increasing in strength. This is somewhat subtle. For $n$ odd,
$j$ is $\Sigma^1_n$ if and only if $j$ is $\Sigma^1_{n+1}$ (shown by
Donald Martin). However, for $n$ even, $j$ being $\Sigma^1_{n+1}$ is
*significantly* stronger than a $j$ being
$\Sigma^1_n${% cite Laver1997 %}.

$E_{n+1}$ strongly implies $E_n$. It also implies the consistency of
$E_n$ strengthened by adding “with an arbitrarily large first
target”.{% cite Kentaro2007 %}

Notes:{% cite Bagaria2012 %}

-   $\kappa$ is $\mathrm{I3}$, i.e. $E_0$, i.e. the critical point of
    an elementary embedding $j : V_\delta \to V_\delta$, if and
    only if $\kappa$ is the critical point of an embedding $j^+ :
    V_{\delta+1} \to V_{\delta+1}$ which is $\Sigma_0$ elementary
    (preserves truth for bounded formulas) with parameters.
    -   $j$ extends uniquely to $j^+$ with $j^+(A) =
        \bigcup_{\alpha\lt\delta} j(A \cap V_\alpha)$ for all $A
        \subseteq V_\delta$.
-   An embedding $j : V_{\delta+1} \to V_{\delta+1}$ is
    $\Sigma_i$ elementary if and only if its restriction to
    $V_\delta$ is $\Sigma^1_i$ elementary.
    -   A formula is $Σ^1_i$ if it is a second order formula which
        begins with exactly $i$-many alternating second-order
        quantifiers, beginning with an existential one, and the rest of
        the formula has only first-order quantifiers.
-   For each $i \ge 1$, the formula „$k : V_\beta \to V_\beta$ is
    $\Sigma^1_i$ elementary” is $\Pi_{i+1}$ expressible in
    $V_{\delta+1}$ in the parameters $k$ and $\beta$.
-   Alternative terminology: A cardinal $\kappa$ is called an $E_i$
    cardinal, if it is a critical point of a $\Sigma_i$ elementary
    embedding $j : V_{\delta+1} \to V_{\delta+1}$.
    -   In this terminology $E_i$ is connected with $\Sigma_i$, not
        $\Sigma_{2 i}$, so only even $i$ need to be considered.
    -   $E_1$ in both terminologies coincide with each other and with
        $E_2$ in this one.

### Weaker axioms

The $\mathrm{I3}$ axiom implies the
<a href="Wholeness_axiom" class="mw-redirect" title="Wholeness axiom">wholeness axiom</a>.
<a href="I4" class="mw-redirect" title="I4">Axioms $\mathrm{I}_4^n$</a>
for natural numbers $n$ are an attempt to measure the gap between
$\mathrm{I}_3$ and
$\mathrm{WA}$.{% cite Corazza2003 %}

## The $\text{I2}$ Axiom

The $\text{I2}$ axiom asserts the existence of some elementary
embedding $j:V\to M$ with $V_\lambda\subseteq M$ where $\lambda$ is
defined as the $\omega^{th}$ $j$-iterate of the critical point.

Although this axiom asserts the existence of a *class* embedding with a
very strong closure property, it is in fact equivalent to an embedding
$j:V_\lambda\to V_\lambda$ with $j^+$ preserving well-founded
relations on $V_\lambda$.

So this axioms preserves *some* second-order structure of $V_\lambda$
and is in fact equivalent to $E_1(\lambda)$ in the hierarchy defined
above.

### The $IE$ axiom

A specific property of $\text{I2}$ embeddings is that they are
*iterable* (i.e. the direct limit of directed system of embeddings is
well-founded). In the literature (D. Martin, Infinite games, in: Proc.
ICM, Helsinki, 1978), $IE(\lambda)$ asserts that $j:V_\lambda\to
V_\lambda$ is iterable and $IE(\lambda)$ falls strictly between
$E_0(\lambda)$ and $E_1(\lambda)$.

In other words, $IE$ asserts that there is $e : V_\delta \prec
V_\delta$ whose $\alpha$-th iteration is well-founded for all
$\alpha \in \mathrm{Ord}$.{% cite Kentaro2007 %}

$IE^\omega$ asserts that there is a non-trivial elementary embedding $e
: V_\delta \prec V_\delta$ with $crit(e) = \kappa$ such that the
direct limit of $\langle e^{(n)} : V_\delta ≺ V_\delta \| n \in
\omega \rangle$ is well
founded.{% cite Kentaro2007 %}

### Ultrapowers

As a result of the strong closure property of $\text{I2}$, the
equivalence mentioned above cannot be through an analysis of some
ultrapower embedding. Instead, the equivalence is established by
constructing a directed system of embeddings of various ultrapowers and
using reflection properties of the critical points of the embeddings.
The direct limit is well-founded since well-founded relations are
preserved by $j^+$. The use of both direct and indirect limits, in
conjunction with reflection arguments, is typical for establishing the
properties of rank into rank embeddings.

### Other results

An $\mathrm{I2}$ cardinal can be forced to be the $\omega$-time target
of an $\mathrm{I3}$ cardinal.{% cite Kentaro2007 %}

## The $\text{I1}$ Axiom

$\text{I1}$ asserts the existence of a nontrivial elementary embedding
$j:V_{\lambda+1}\to V_{\lambda+1}$.

This axiom is sometimes denoted
$\mathcal{E}(V_{\lambda+1})\neq\emptyset$.

Any such embedding preserves all second-order properties of
$V_\lambda$ and so is $\Sigma^1_n$ for all $n$. To emphasize the
preservation of second-order properties, the axiom is also sometimes
written as $E_\omega(\lambda)$. In this case, restricting the
embedding to $V_\lambda$ and forming $j^+$ as above yields the
original embedding.

### Strenghtenings

Strengthening this axiom in a natural way leads to the $\text{I0}$
axiom, i.e. asserting that embeddings of the form
[$j:L(V_{\lambda+1})\to
L(V_{\lambda+1})$](L_of_V_lambda%2B1 "L of V lambda+1")
exist.

There are also other natural strengthenings of $\text{I1}$, though it
is not entirely clear how they relate to the $\text{I0}$ axiom. For
example, one can assume the existence of elementary embeddings
satisfying $\text{I1}$ which extend to embeddings $j:M\to M$ where $M$
is a transitive class inner model and add various requirements to $M$.
These requirements must not entail that $M$ satisfies the axiom of
choice by the Kunen inconsistency. Requirements that have been
considered include assuming $M$ contains $V_{\lambda+1}$, $M$
satisfies $DC_\lambda$, $M$ satisfies replacement for formulas
containing $j$ as a parameter, $j(\mathrm{crit}(j))$ is arbitrarily
large in $M$, etc.

## Virtually rank-into-rank

(Information in this subsection from
{% cite Gitmana %} unless noted
otherwise)

A cardinal $\kappa$ is **virtually rank-into-rank** iff in a
set-forcing extension it is the critical point of an elementary
embedding $j : V_λ → V_λ$ for some $λ > \kappa$.

This notion does not require stratification, because Kunen’s
Inconsistency does not hold for virtual embeddings.

Results:

-   Every virtually rank-into-rank cardinal is a [virtually
    $n$-huge*](Huge "Huge")
    limit of virtually $n$-huge* cardinals for every $n < \omega$.
-   The least
    $\omega$-<a href="Erd%C5%91s" class="mw-redirect" title="Erdős">Erdős</a>
    cardinal $η_\omega$ is a limit of virtually rank-into-rank
    cardinals.
-   Every virtually rank-into-rank cardinal is an
    $\omega$-<a href="Iterable" class="mw-redirect" title="Iterable">iterable</a>
    limit of $\omega$-iterable cardinals.
-   Every element of a club $C$ witnessing that $\kappa$ is a
    <a href="Silver_cardinal" class="mw-redirect" title="Silver cardinal">Silver cardinal</a>
    is virtually rank-into-rank.
-   If [$gVP(Σ_{n+1})$
    holds](Vopenka "Vopenka"),
    then either there is a proper class of
    <a href="N-remarkable" class="mw-redirect" title="N-remarkable">$n$-remarkable</a>
    cardinals or there is a proper class of virtually rank-into-rank
    cardinals.{% cite Gitman2018 %}
-   If
    <a href="Zero_sharp" class="mw-redirect" title="Zero sharp">$0^\#$ exists</a>,
    then in $L$ there are numerous virtual rank-into-rank embeddings $j
    : V_θ^L → V_θ^L$, where $θ$ is far above the supremum of the
    critical sequence. (By [elementary-embedding absoluteness
    results](Elementary_embedding#Absoluteness "Elementary embedding").
    The hypothesis can be weakened, because one can chop at off the
    universe at any Silver indiscernible and use
    reflection.){% cite Gitman2018 %}
    -   Therefore every Silver indiscernible is the critical point of
        virtual rank-into-rank embeddings with targets as high as
        desired and fixed points as high above the critical sequence as
        desired.{% cite Gitman2018 %}

## Large Cardinal Properties of Critical Points

The critical points of rank into rank embeddings have many strong
reflection properties. They are measurable, $n$-huge for all $n$ (hence
the terminology $\omega$-huge mentioned in the introduction) and
partially supercompact.

Using $\kappa_0$ as a seed, one can form the ultrafilter
$$U=\{X\subseteq\mathcal{P}(\kappa_0): j\`\`\kappa_0\in
j(X)\}.$$ Thus, $\kappa_0$ is a measurable cardinal.

In fact, for any $n$, $\kappa_0$ is also $n$-huge as witnessed by the
ultrafilter $$U=\{X\subseteq\mathcal{P}(\kappa_n):
j\`\`\kappa_n\in j(X)\}.$$ This motivates the term $\omega$-huge
cardinal mentioned in the introduction.

Letting $j^n$ denote the $n^{th}$ iteration of $j$, then
$$V_\lambda\models \`\`\lambda\text{ is supercompact"}.$$ To see
this, suppose $\kappa_0\leq \theta <\kappa_n$, then
$$U=\{X\subseteq\mathcal{P}_{\kappa_0}(\theta):
j^n\`\`\theta\in j^n(X)\}$$ winesses the $\theta$-compactness of
$\kappa_0$ (in $V_\lambda$). For this last claim, it is enough that
$\kappa_0(j)$ is $<\lambda$-supercompact, i.e. not *fully*
supercompact in $V$. In this case, however, $\kappa_0$ *could* be
fully supercompact.

Critical points of rank-into-rank embeddings also exhibit some
*upward* reflection properties. For example, if $\kappa$ is a
critical point of some embedding witnessing
$\text{I3}(\kappa,\lambda)$, then there must exist another embedding
witnessing $\text{I3}(\kappa',\lambda)$ with critical point *above*
$\kappa$! This upward type of reflection is not exhibited by large
cardinals below
[extendible](Extendible "Extendible")
cardinals in the large cardinal hierarchy.

## Algebras of elementary embeddings

If $j,k\in\mathcal{E}_{\lambda}$, then
$j^+(k)\in\mathcal{E}_{\lambda}$ as well. We therefore define a
binary operation $*$ on $\mathcal{E}_{\lambda}$ called application
defined by $j*k=j^{+}(k)$. The binary operation $*$ together with
composition $\circ$ satisfies the following identities:

1\. $(j\circ k)\circ l=j\circ(k\circ l),\,j\circ k=(j*k)\circ
j,\,j*(k*l)=(j\circ k)*l,\,j*(k\circ l)=(j*k)\circ(j*l)$

2\. $j*(k*l)=(j*k)*(j*l)$ (self-distributivity).

Identity 2 is an algebraic consequence of the identities in 1.

If $j\in\mathcal{E}_{\lambda}$ is a nontrivial elementary embedding,
then $j$ freely generates a subalgebra of
$(\mathcal{E}_{\lambda},*,\circ)$ with respect to the identities in
1, and $j$ freely generates a subalgebra of
$(\mathcal{E}_{\lambda},*)$ with respect to the identity 2.

If $j_{n}\in\mathcal{E}_{\lambda}$ for all $n\in\omega$, then
$\sup\{\textrm{crit}(j_{0}*\dots*j_{n})\mid
n\in\omega\}=\lambda$ where the implied parentheses a grouped on the
left (for example, $j*k*l=(j*k)*l$).

Suppose now that $\gamma$ is a limit ordinal with
$\gamma<\lambda$. Then define an equivalence relation
$\equiv^{\gamma}$ on $\mathcal{E}_{\lambda}$ where
$j\equiv^{\gamma}k$ if and only if $j(x)\cap V_{\gamma}=k(x)\cap
V_{\gamma}$ for each $x\in V_{\gamma}$. Then the equivalence
relation $\equiv^{\gamma}$ is a congruence on the algebra
$(\mathcal{E}_{\lambda},*,\circ)$. In other words, if
$j_{1},j_{2},k\in \mathcal{E}_{\lambda}$ and
$j_{1}\equiv^{\gamma}j_{2}$ then $j_{1}\circ k\equiv^{\gamma}
j_{2}\circ k$ and $j_{1}*k\equiv^{\gamma}j_{2}*k$, and if
$j,k_{1},k_{2}\in\mathcal{E}_{\lambda}$ and
$k_{1}\equiv^{\gamma}k_{2}$ then $j\circ
k_{1}\equiv^{\gamma}j\circ k_{2}$ and
$j*k_{1}\equiv^{j(\gamma)}j*k_{2}$.

If $\gamma<\lambda$, then every finitely generated subalgebra of
$(\mathcal{E}_{\lambda}/\equiv^{\gamma},*,\circ)$ is finite.

## $C^{(n)}$ variants

(section from {% cite Bagaria2012 %}, including 2019
arXiv extended version)

$\mathrm{I3}$ and other $C^{(n)}$ variants:

-   Assuming $\mathrm{I3}(\kappa,\delta)$, if $\delta$ is a limit
    cardinal (instead of a successor of a limit cardinal – Kunen’s
    Theorem excludes other cases), it is equal to
    $sup\{j^m(\kappa):m\lt \omega\}$ where $j$ is the elementary
    embedding. Then $\kappa$ and $j^m(\kappa)$ are
    $C^{(n)}$-[superstrong](Superstrong "Superstrong"),
    $C^{(n)}$-[supercompact](Supercompact "Supercompact"),
    $C^{(n)}$-[extendible](Extendible "Extendible"),
    $C^{(n)}$-$m$-[huge](Huge "Huge")
    and $C^{(n)}$-superhuge in $V_\delta$, for all $n$ and $m$.

Definitions of $C^{(n)}$ variants of rank-into-rank cardinals:

-   $\kappa$ is called
    **<a href="Correct" class="mw-redirect" title="Correct">$C^{(n)}$-$\mathrm{I3}$ cardinal</a>**
    if it is an $\mathrm{I3}$ cardinal, witnessed by some elementary
    embedding $j: V_\delta\rightarrow V_\delta$, with
    $j(\kappa)\in C^{(n)}$ (i.e. ($1$-)$C^{(n)}$-$E_0$).
-   $\kappa$ is called **$C^{(n)+}$-$\mathrm{I3}$ cardinal** if it is
    an $\mathrm{I3}$ cardinal, witnessed by some elementary embedding
    $j : V_\delta\rightarrow V_\delta$, with $\delta\in C^{(n)}$
    (i.e. $\omega$-$C^{(n)}$-$E_0$).
    -   Note: For every $n\ge 1$, if $\delta$ is a limit ordinal and
        $j : V_\delta\rightarrow V_\delta$ witnesses that $\kappa$
        is $\mathrm{I3}$, then
        $(\forall_{m\lt\omega}j^m(\kappa)\in
        C^{(n)})\iff\delta\in C^{(n)}$.
        -   $E_i$ cardinals are $E_0$, so this applies to
            $\omega$-$C^{(n)}$-$E_i$ cardinals.
-   $\kappa$ is called **$C^{(n)}$-$\mathrm{I1}$ cardinal** if it is
    an $\mathrm{I1}$ cardinal, witnessed by some elementary embedding
    $j : V_{\delta+1}\rightarrow V_{\delta+1}$, with
    $j(\kappa)\in C^{(n)}$ (i.e. ($1$-)$C^{(n)}$-$E_\omega$).

More generally

-   $\kappa$ is called **$C^{(n)}$-$E_0$ cardinal** if it is an $E_i$
    cardinal, witnessed by some elementary embedding $j :
    V_\delta\rightarrow V_\delta$, with $j(\kappa) \in C^{(n)}$.
-   $\kappa$ is called **$m$-$C^{(n)}$-$E_0$ cardinal** if it is an
    $E_i$ cardinal, witnessed by some elementary embedding $j :
    V_\delta\rightarrow V_\delta$, with $j^{m'}(\kappa) \in
    C^{(n)}$ for all $1 \le m'\le m$.
-   $\kappa$ is called **$\omega$-$C^{(n)}$-$E_0$ cardinal** if it is
    an $E_i$ cardinal, witnessed by some elementary embedding $j :
    V_\delta\rightarrow V_\delta$, with $\delta \in C^{(n)}$.

Even more generally

-   $\kappa$ is called **$C^{(n)}$-$E_i$ cardinal** if it is an $E_i$
    cardinal, witnessed by some $\Sigma_i$ elementary embedding $j :
    V_{\delta+1}\rightarrow V_{\delta+1}$, with $j(\kappa) \in
    C^{(n)}$.
-   $\kappa$ is called **$m$-$C^{(n)}$-$E_i$ cardinal** if it is an
    $E_i$ cardinal, witnessed by some $\Sigma_i$ elementary embedding
    $j : V_{\delta+1}\rightarrow V_{\delta+1}$, with
    $j^{m'}(\kappa) \in C^{(n)}$ for all $1 \le m'\le m$.
-   $\kappa$ is called **$\omega$-$C^{(n)}$-$E_i$ cardinal** if it is
    an $E_i$ cardinal, witnessed by some $\Sigma_i$ elementary
    embedding $j : V_{\delta+1}\rightarrow V_{\delta+1}$, with
    $\delta \in C^{(n)}$.

Of course, $m$-$C^{(n)}$-$E_i$ cardinals for larger $m$, $n$ and $i$
have also this property for smaller parameters. In particular, every
$C^{(n)}$-$\mathrm{I1}$ cardinal is also $C^{(n)}$-$\mathrm{I3}$.

Results about $\mathrm{I3}$:

-   If $\kappa$ is $C^{(n)}$-$\mathrm{I3}$, then $\kappa\in
    C^{(n)}$.
-   Every $\mathrm{I3}$-cardinal is $C^{(1)}$-$\mathrm{I3}$ and
    $C^{(1)+}$-$\mathrm{I3}$.
-   If $\kappa$ is $C^{(n)}$-$\mathrm{I3}$, then it is
    $C^{(n)}$-$m$-huge, for all $m$, and there is a normal
    <a href="Ultrafilter" class="mw-redirect" title="Ultrafilter">ultrafilter</a>
    $\mathcal{U}$ over $\kappa$ such that
    $\{\alpha\lt\kappa: \alpha$ is $C^{(n)}$-$m$-huge for every
    $m\}\in\mathcal{U}$.
-   If $\kappa$ is $m$-$C^{(n)}$-$E_1$, then there is a normal
    ultrafilter $\mathcal{U}$ over $\kappa$ such that the set of
    cardinals $\alpha < \kappa$ that are $m$-$C^{(n)}$-$E_0$
    belongs to $\mathcal{U}$.

Results about $\mathrm{I1}$:

-   If $\kappa$ is $C^{(n)}$-$\mathrm{I1}$, then the least $\delta$
    such that there is an elementary embedding $j: V_{\delta+1} \to
    V_{\delta+1}$ with $crit(j)=\kappa$ and $j(\kappa)\in C^{(n)}$
    is smaller than the first ordinal in $C^{(n+1)}$ greater than
    $\kappa$.

General results:

-   By simple reflection argument: The least $m$-$C^{(n)}$-$E_i$
    cardinal is smaller than the first cardinal in $C^{(n+1)}$ (for all
    $m, i \le \omega$ and $n \ge 1$) and therefore smaller than the
    least $C^{(n+1)}$-$E_0$ cardinal. In particular:
    -   The least $C^{(n)}$-$\mathrm{I3}$ cardinal is not
        $C^{(n+1)}$-$\mathrm{I3}$.
    -   The least $C^{(n)}$-$\mathrm{I1}$ cardinal is not
        $C^{(n+1)}$-$\mathrm{I1}$.
    -   The least $C^{(n)}$-$\mathrm{I1}$ cardinal, if it exists, is
        smaller than the first ordinal in $C^{(n+1)}$.
-   The least $m$-$C^{(n)}$-$E_i$ cardinal is not $(m +
    1)$-$C^{(n)}$-$E_i$ (for all $m \ge 1$, $n \ge 2$ and $i \le
    \omega$).
-   If $\kappa$ is an $m$-$C^{(n)}$-$E_{i+2}$ cardinal (for $i, n <
    \omega$ and $m \le \omega$), then the set of $m$-$C^{(n)}$-$E_i$
    cardinals is unbounded below $\kappa$.

## $B$-$E_n$, $P$-$E_n$, and $W$-$E_n$ cardinals

(Section from {% cite Kentaro2007 %})

-   $\kappa$ is $B$-$E_n$ if and only if $E_n(\kappa)$; i.e. there
    is some $j: V_\lambda\prec V_\lambda$ such that $j^+$ preserves
    $\Sigma_{2n}^1$-properties.
-   $\kappa$ is $W$-$E_n$ if and only if for every $f:
    \kappa\rightarrow\kappa$, there is some $\alpha\lt\kappa$ such
    that $f"\alpha\subseteq\alpha$ and $E_n(\alpha)$
-   $\kappa$ is $P$-$E_n$ if and only if for every $\gamma$, there is
    some $j: V_\lambda\prec V_\lambda$ witnessing $E_n(\kappa)$
    such that $j(\kappa)\gt\kappa+\gamma$.

**Results:**

-   The consistency strength of some $\kappa$ that satisfies $W$-$E_n$
    is above $E_n$.
-   If $\kappa$ is $P$-$E_n$ then $\kappa$ is $W$-$E_n$.
-   The consistency strength of some $\kappa$ that satisfies
    $B$-$E_{n+1}$ is above $P$-$E_n$.

## Relations with [$\omega$-fold variants](N-fold_variants "N-fold variants")

(Section from {% cite Kentaro2007 %})

-   For any $n \in \omega$, $\mathrm{I3}$ is equivalent to the
    existence of an $\omega$-fold $n$-extendible cardinal.
-   An $\omega$-fold extendible cardinal $\kappa$ is the $\kappa$-th
    $\mathrm{I3}$ cardinal ($\kappa$-th critical point of an
    elementary embedding $j : V_\delta \to V_\delta$).
    -   The assertion that “there is an $\omega$-fold extendible
        cardinal” implies the consistency of “the $\mathrm{I3}$
        cardinals form a proper class”.
-   If $e : V_\delta \prec V_\delta$ witnesses $IE^\omega$ with
    $crit(e) = \kappa$, then
    -   $\kappa$ is $\omega$-fold Vopěnka,
    -   $\{\alpha < \kappa \| V_\kappa \models$ “$\alpha$ is
        $\omega$-fold Vopěnka”$\} \in \{x \subset \kappa \|
        \kappa \in e(x)\}$ and
    -   $\{\alpha < \kappa \| \alpha$ is $\omega$-fold
        Vopěnka$\} \in \{x \subset \kappa \| \kappa \in e(x)\}$.
    -   The critical point $\kappa$ of a witness of $IE^\omega$ is the
        $\kappa$-th $\omega$-fold Vopěnka cardinal.
    -   $IE^\omega$ implies consistency of “$\omega$-fold Vopěnka
        cardinals form a proper class”.
-   $\omega$-fold superstrong (=$\omega$-fold Shelah) is equivalent to
    $\mathrm{I2}$.
    -   Weaker than $\omega$-fold Woodin (details in [n-fold
        variants](N-fold_variants "N-fold variants")).
-   $E_2$ (with $\Sigma_4$) implies consistency of “$\omega$-fold
    strong cardinals form a proper class”.
