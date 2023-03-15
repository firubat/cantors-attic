---
title: $\exists j:L(V_{\lambda+1})\to L(V_{\lambda+1})$
permalink: L_of_V_lambda+1
---

*See first: [rank into rank
axioms](Rank_into_rank "Rank into rank")*

The axiom **I0**, the large cardinal axiom of the title, asserts that
some nontrivial elementary embedding $j:V_{\lambda+1}\to
V_{\lambda+1}$ extends to a nontrivial elementary embedding
$j:L(V_{\lambda+1})\to L(V_{\lambda+1})$, where
$L(V_{\lambda+1})$ is the transitive proper class obtained by starting
with $V_{\lambda+1}$ and forming the constructible hierarchy over
$V_{\lambda+1}$ in the usual fashion (see [constructible
universe](Constructible_universe "Constructible universe")).
An alternate, but equivalent formulation asserts the existence of some
nontrivial elementary embedding $j:L(V_{\lambda+1})\to
L(V_{\lambda+1})$ with $\mathrm{crit}(j) < \lambda$. The critical
point assumption is essential for the large cardinal strength as
otherwise the axiom would follow from the existence of some measurable
cardinal above $\lambda$. The axiom is of [rank into
rank](Rank_into_rank "Rank into rank")
type, despite its formulation as an embedding between proper classes,
and embeddings witnessing the axiom known as $\text{I0}$ embeddings.

Originally formulated by Woodin in order to establish the relative
consistency of a strong
<a href="Determinacy" class="mw-redirect" title="Determinacy">determinacy</a>
hypothesis, it is now known to be obsolete for this purpose (it is far
stronger than necessary). Nevertheless, research on the axiom and its
variants is still widely pursued and there are numerous intriguing open
questions regarding the axiom and its variants, see
{% cite Kanamori2009 %}.

The axiom subsumes a hierarchy of the strongest large cardinals not
known to be inconsistent with $\text{ZFC}$ and so is seen as "straining
the limits of consistency" {% cite Kanamori2009 %}.
An immediate observation due to the [Kunen
inconsistency](Kunen_inconsistency "Kunen inconsistency")
is that, under the $\text{I0}$ axiom, $L(V_{\lambda+1})$ *cannot*
satisfy the axiom of choice.

## The $L(V_{\lambda+1})$ Hierarchy

## Relation to the I1 Axiom

## Ultrapower Reformulation

Despite the class language formulation of $I_0$, there is a first-order
formulation in terms of normal ultrafilters: define, for
$j:L(V_{\lambda + 1})\prec L(V_{\lambda+1})$, an ultrafilter $U_j$
as the collection of sets $X\in
L(V_{\lambda+1})\cap\{k:L(V_{\lambda+1})\prec
L(V_{\lambda+1})\}$ where $$X\in U_j \Leftrightarrow
j\restriction V_\lambda \in jX.$$ Note that $U_j$ is a normal
non-principal $L(V_{\lambda+1})$ ultrafilter over $V_{\lambda+1}$,
hence the ultrafilter $Ult(L(V_{\lambda+1}),
j)=\big(L(V_{\lambda+1}^{\mathcal{E}(V_{\lambda+1})})\cap
L(V_{\lambda+1})\big)/U_j$ is well-defined and well-founded. It is
important to note that $U_j$ contains only elementary embeddings from
$L(V_{\lambda+1})$ to itself which are contructible from
$V_{\lambda+1}$ and parameters from this set. As \(I0\) is therefore
equivalent to the existence of a normal non-principle
$L(V_{\lambda+1})$ ultrafilter over $V_{\lambda+1}$, the assertion
$\kappa$ is $I0$ is $\Sigma_2$ and every critical point of $k:
V_{\lambda+2}\prec V_{\lambda+2}$ is $I0$. Unfortunately, this
requires $DC_{\lambda}$ to get ultrapower.

An equivalent second-order formulation is: there is some
$j:V_\lambda\prec V_\lambda$ and a proper class of ordinals $C$
such that $\alpha_0<\alpha_1<\dots< \alpha_n$ all
elements of $C$ and $A\in V_{\lambda+1}$ with
$$L_{\alpha_n}(V_{\lambda+1}, \in, \alpha_0, \alpha_1, \dots,
\alpha_{n-1})\models \Phi(A)\leftrightarrow \Phi(jA).$$

## Similarities with $L(\mathbb{R})$ under Determinacy

The axiom $I0$ was originally formulated by Woodin to establish the
consistency of the Axiom of Determinancy. What Woodin established was
that $AD^{L(\mathbb R)}$ follows from the existence of an $I0$ cardinal
{% cite Kanamori2009 %}. It is now known that this
is a massive overkill; namely, $AD$, $AD^{L(\mathbb R)}$, and
infinitely many Woodin cardinals are equiconsistent, and furthermore,
$AD^{L(\mathbb R)}$ follows from infinitely many Woodin cardinals with
a measurable above them all
{% cite Kanamori2009 %}. This seems like it should
be the end of it; $I0$ was simply an axiom to strong for the purpose for
which it was created. But there are deeper connections between
$AD^{L(\mathbb R)}$ and $I0$.

First off, under $V=L(\mathbb R)$, if $AD$ holds then so does
$DC\leftrightarrow DC_\omega$. Similarly, under $I0$ $DC_\lambda$
holds in $L(\mathbb R)$. Furthermore, if $AD$ holds then $\omega_1$
is measurable in $L(\mathbb R)$. Similarly, if $X\subseteq
V_{\lambda+1}$ and there is some $j: L(X,V_{\lambda+1})\prec
L(X,V_{\lambda+1})$, then $\lambda^+$ is measurable. The connections
between $I0$ and determinancy are still not fully
understand.{% cite Dimonte2017 %}

\[WIP\]

## Strengthenings of $\text{I0}$ and Woodin's $E_\alpha(V_{\lambda+1})$ Sequence

We call a set $X ⊆ V_{λ+1}$ an **Icarus set** if there is an elementary
embedding $j : L(X, V_{λ+1}) ≺ L(X, V_{λ+1})$ with $\mathrm{crit}(j)
< λ$. In particular, “$(V_{λ+1})^{(n+1)♯}$ is Icarus” strongly
implies “$(V_{λ+1})^{n♯}$ is Icarus”, but above the first $ω$ sharps it
becomes more
difficult. {% cite Dimonte2017  Woodin2011 %}

*to complete*
  

        This article is a stub. Please help us to improve Cantor's Attic by adding information.


