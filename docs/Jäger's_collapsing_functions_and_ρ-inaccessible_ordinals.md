---
title: Jäger's collapsing functions and ρ-inaccessible ordinals
permalink: Jäger's_collapsing_functions_and_ρ-inaccessible_ordinals
---

Jäger's collapsing functions are a hierarchy of single-argument ordinal
functions \(\psi_\pi\) introduced by German mathematician Gerhard
Jäger in 1984. This is an extension of [Buchholz's
notation](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions").

### Basic Notions

\(M_0\) is the least Mahlo cardinal, small Greek letters denote
ordinals less than \(M_0\). Each ordinal \(\alpha\) is identified
with the set of its predecessors
\(\alpha=\{\beta\|\beta<\alpha\}\).

\(L\) denotes the set of all limit ordinals less than \(M_0\).

An ordinal \(\alpha\) is an additive principal number if
\(\alpha>0\) and \(\xi+\eta<\alpha\) for all
\(\xi,\eta<\alpha\). Let \(P\) denote the set of all additive
principal numbers less than \(M_0\).

\(\alpha=_{NF}\alpha _{1}+\cdots +\alpha _{n}:\Leftrightarrow
\alpha =\alpha _{1}+\cdots +\alpha _{n}\wedge \alpha _{1}\geq
\cdots \geq \alpha _{n}\wedge \alpha _{1},... ,\alpha _{n}\in
P\)

Cofinality \(\text{cof}(\alpha)\) of an ordinal \(\alpha\) is the
least \(\beta\) such that there exists a function
\(f:\beta\rightarrow\alpha\) with \(\text{sup}\{f(\xi )\|\xi
<\beta \}=\alpha\). An ordinal \(\alpha\) is regular, if
\(\alpha\) is a limit ordinal and \(\text{cof}(\alpha)=\alpha\).
Let \(R\) denote the set of all regular ordinals \(\in(\omega,
M_0)\).

An ordinal \(\alpha\) is (weakly) inaccessible if \(\alpha\) is a
regular limit cardinal larger than \(\omega\).

Enumeration function \(F\) of class of ordinals \(X\) is the unique
increasing function such that
\(X=\{F(\alpha)\|\alpha\in\text{dom}(F)\}\) where domain of
\(F\), \(\text{dom}(F)\) is an ordinal number. We use
\(\text{Enum}(X)\) to donate \(F\).

### Veblen function

\(\varphi_\alpha=\text{Enum}(\{\beta\in
P\|\forall\gamma<\alpha(\varphi_\gamma(\beta)=\beta)\})\)

Normal form

\(\alpha=_{NF}\varphi_\beta(\gamma):\Leftrightarrow\alpha=\varphi_\beta(\gamma)\wedge\beta,\gamma<\alpha\)

An ordinal \(\alpha\) is a strongly critical if
\(\varphi(\alpha,0)=\alpha\). Let \(S\) denote the set of all
strongly critical ordinals less than \(M_0\).

Definition of \(S(\gamma)\) for arbitrary \(\gamma\).

\(S(\gamma)=\{\gamma\}\) if \(\gamma\in S\cup\{0\}\)

\(S(\gamma)=\{\alpha_1,...,\alpha_n\}\) if
\(\gamma=_{NF}\alpha_1+\cdots+\alpha_n\notin P\)

\(S(\gamma)=\{\alpha,\beta\}\) if
\(\gamma=_{NF}\varphi_\alpha(\beta)\notin S\)

### \(\rho\)-Inaccessible Ordinals

An ordinal is \(\rho\)-inaccessible if it is a regular cardinal and
limit of \(\alpha\)-inaccessible ordinals for all
\(\alpha<\rho\). So the 0-inaccessible ordinals are exactly the
regular cardinals \(>\omega\), the 1-inaccessible ordinals are the
inaccessible ordinals. Functions \(I_\rho:M_0 \rightarrow M_0\)
enumerate the \(\rho\)-inaccessible ordinals less than \(M_0\) and
their limits.

\(I_\alpha=\text{Enum}(\{\beta\in
R\|\forall\gamma<\alpha(I_\gamma(\beta)=\beta)\}) \)

Normal form

\(\alpha=_{NF}I_\beta(\gamma):\Leftrightarrow\alpha=I_\beta(\gamma)\wedge\gamma\notin
L\)

Definition of \(\gamma^{-}\) for \(\gamma\in R\).

\(\gamma^{-}=0\) if \(\gamma=_{NF}I_\alpha(0)\)

\(\gamma^{-}=I_\alpha(\beta)\) if
\(\gamma=_{NF}I_\alpha(\beta+1)\)

**Properties**

| Veblen function                                                                                            | \(\rho\)-Inaccessible Ordinals                                                      |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| \(\varphi_\alpha(\beta)\in P\)                                                                      | \(I_\alpha(0), I_\alpha(\beta+1)\in R\)                                        |
| \(\gamma<\alpha\Rightarrow\varphi_\gamma(\varphi_\alpha(\beta))=\varphi_\alpha(\beta)\) | \(\gamma<\alpha\Rightarrow I_\gamma(I_\alpha(\beta))=I_\alpha(\beta)\) |
| \(\beta<\gamma\Rightarrow\varphi_\alpha(\beta)<\varphi_\alpha(\gamma)\)                 | \(\beta<\gamma\Rightarrow I_\alpha(\beta)<I_\alpha(\gamma)\)          |
| \(\alpha<\beta\Rightarrow\varphi_\alpha(0)<\varphi_\beta(0)\)                             | \(\alpha<\beta\Rightarrow I_\alpha(0)<I_\beta(0)\)                      |

### The Ordinal Functions \(\psi_\kappa\)

Every \(\psi_\kappa\) is a function from \(M_0\) to
\(\kappa\) which "collapses" the elements of \(M_0\) below
\(\kappa\). By the Greek letters \(\kappa\) and \(\pi\) we
shall denote uncountable regular cardinals less than \(M_0\).

**Inductive Definition** of \(C_\kappa(\alpha)\) and
\(\psi_\kappa(\alpha)\).

\(\{\kappa^{-}\}\cup\kappa^{-}\subset C_\kappa^n(\alpha)\)

\(S(\gamma)\subset C_\kappa^n(\alpha)\Rightarrow\gamma\in
C_\kappa^{n+1}(\alpha)\)

\(\beta,\gamma\in C_\kappa^n(\alpha)\Rightarrow
I_\beta(\gamma)\in C_\kappa^{n+1}(\alpha)\)

\(\gamma<\pi<\kappa\wedge\pi\in
C_\kappa^n(\alpha)\Rightarrow \gamma\in
C_\kappa^{n+1}(\alpha)\)

\(\gamma<\alpha\wedge\gamma,\pi\in
C_\kappa^n(\alpha)\wedge\gamma\in C_\pi(\gamma)\Rightarrow
\psi_\pi(\gamma)\in C_\kappa^{n+1}(\alpha)\)

\(C_\kappa(\alpha)=\cup\{C_\kappa^n(\alpha)\|n<\omega\}\)

\(\psi_\kappa(\alpha)=\text{min}\{\xi\|\xi\notin
C_\kappa(\alpha)\}\)

Normal form

\(\alpha=_{NF}\psi_\kappa(\beta):\Leftrightarrow\alpha=\psi_\kappa(\beta)\wedge\beta\in
C_\kappa(\beta)\)

## Fundamental sequences

The fundamental sequence for an ordinal number \(\alpha\) with
cofinality \(\text{cof}(\alpha)=\beta\) is a strictly increasing
sequence \((\alpha\[\eta\])_{\eta<\beta}\) with length
\(\beta\) and with limit \(\alpha\), where \(\alpha\[\eta\]\)
is the \(\eta\)-th element of this sequence.

**Inductive Definition** of \(T\).

-   \(0 \in T\)
-   \(\alpha=_{NF}\alpha _{1}+\cdots +\alpha _{n}\wedge \alpha
    _{1},... ,\alpha _{n}\in T\Rightarrow\alpha\in T\)
-   \(\alpha=_{NF}\varphi_\beta(\gamma)\wedge\beta,\gamma\in
    T\Rightarrow\alpha\in T\)
-   \(\alpha=_{NF}I_\beta(\gamma)\wedge\beta,\gamma\in
    T\Rightarrow\alpha\in T\)
-   \(\alpha=_{NF}\psi_\kappa(\beta)\wedge\kappa, \beta\in
    T\Rightarrow\alpha\in T\)

Below we write \(I(\alpha,\beta)\) for \(I_\alpha(\beta)\) and
\(\varphi(\alpha,\beta)\) for \(\varphi_\alpha(\beta)\)

For non-zero ordinals \(\alpha\in T\) we define the fundamental
sequences as follows:

-   If \(\alpha=\varphi(0,\beta+1)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[\eta\]=\varphi(0,\beta)\times\eta\)
-   If \(\alpha=\varphi(\beta+1,0)\) then
    \(\text{cof}(\alpha)=\omega\) and \(\alpha\[0\]=0\) and
    \(\alpha\[\eta+1\]=\varphi(\beta,\alpha\[\eta\])\)
-   If \(\alpha=\varphi(\beta+1,\gamma+1)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[0\]=\varphi(\beta+1,\gamma)+1\) and
    \(\alpha\[\eta+1\]=\varphi(\beta,\alpha\[\eta\])\)
-   If \(\alpha=\varphi(\beta,0)\) and \(\beta\in L\) then
    \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=\varphi(\beta\[\eta\],0)\)
-   If \(\alpha=\varphi(\beta,\gamma+1)\) and \(\beta\in L\)
    then \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=\varphi(\beta\[\eta\],\varphi(\beta,\gamma)+1)\)
-   If \(\alpha=\varphi(\beta,\gamma)\) and \(\gamma\in L\)
    then \(\text{cof}(\alpha)=\text{cof}(\gamma)\) and
    \(\alpha\[\eta\]=\varphi(\beta,\gamma\[\eta\])\)

  

-   If \(\alpha=\psi_{I(0,0)}(0)\) then
    \(\text{cof}(\alpha)=\omega\) and \(\alpha\[0\]=0\) and
    \(\alpha\[\eta+1\]=\varphi(\alpha\[\eta\],0)\)
-   If \(\alpha=\psi_{I(0,\beta+1)}(0)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[0\]=I(0,\beta)+1\) and
    \(\alpha\[\eta+1\]=\varphi(\alpha\[\eta\],0)\)
-   If \(\alpha=\psi_{I(0,\beta)}(\gamma+1)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[0\]=\psi_{I(0,\beta)}(\gamma)+1\) and
    \(\alpha\[\eta+1\]=\varphi(\alpha\[\eta\],0)\)

  

-   If \(\alpha=\psi_{I(\beta+1,0)}(0)\) then
    \(\text{cof}(\alpha)=\omega\) and \(\alpha\[0\]=0\) and
    \(\alpha\[\eta+1\]=I(\beta,\alpha\[\eta\])\)
-   If \(\alpha=\psi_{I(\beta+1,\gamma+1)}(0)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[0\]=I(\beta+1,\gamma)+1\) and
    \(\alpha\[\eta+1\]=I(\beta,\alpha\[\eta\])\)
-   If \(\alpha=\psi_{I(\beta+1,\gamma)}(\delta+1)\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[0\]=\psi_{I(\beta+1,\gamma)}(\delta)+1\) and
    \(\alpha\[\eta+1\]=I(\beta,\alpha\[\eta\])\)

  

-   If \(\alpha=\psi_{I(\beta,0)}(0)\) and \(\beta\in L\) then
    \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=I(\beta\[\eta\],0)\)
-   If \(\alpha=\psi_{I(\beta,\gamma+1)}(0)\) and \(\beta\in
    L\) then \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=I(\beta\[\eta\],I(\beta,\gamma)+1)\)
-   If \(\alpha=\psi_{I(\beta,\gamma)}(\delta+1)\) and
    \(\beta\in L\) then
    \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=I(\beta\[\eta\],\psi_{I(\beta,\gamma)}(\delta)+1)\)

  

-   If \(\alpha=\alpha_1+\alpha_2+\cdots+\alpha_n\) with
    \(n\geq 2\) then
    \(\text{cof}(\alpha)=\text{cof}(\alpha_n)\) and
    \(\alpha\[\eta\]=\alpha_1+\alpha_2+\cdots+(\alpha_n\[\eta\])\)
-   If \(\alpha=\varphi(0,0)\) then
    \(\text{cof}(\alpha)=\alpha=1\) and \(\alpha\[0\]=0\)
-   If \(\alpha=I(\beta,0)\) or \(\alpha=I(\beta,\gamma+1)\)
    then \(\text{cof}(\alpha)=\alpha\) and
    \(\alpha\[\eta\]=\eta\)
-   If \(\alpha=I(\beta,\gamma)\) and \(\gamma\in L\) then
    \(\text{cof}(\alpha)=\text{cof}(\gamma)\) and
    \(\alpha\[\eta\]=I(\beta,\gamma\[\eta\])\)
-   If \(\alpha=\psi_\pi(\beta)\) and
    \(\omega\le\text{cof}(\beta)<\pi\) then
    \(\text{cof}(\alpha)=\text{cof}(\beta)\) and
    \(\alpha\[\eta\]=\psi_\pi(\beta\[\eta\])\)
-   If \(\alpha=\psi_\pi(\beta)\) and
    \(\text{cof}(\beta)=\rho\geq\pi\) then
    \(\text{cof}(\alpha)=\omega\) and
    \(\alpha\[\eta\]=\psi_\pi(\beta\[\gamma\[\eta\]\])\) with
    \(\gamma\[0\]=1\) and
    \(\gamma\[\eta+1\]=\psi_{\rho}(\beta\[\gamma\[\eta\]\])\)

  
Limit of this notation \(\lambda\). If \(\alpha=\lambda\) then
\(\text{cof}(\alpha)=\omega\) and \(\alpha\[0\]=0\) and
\(\alpha\[\eta+1\]=I(\alpha\[\eta\],0)\)

  

## See also

Other ordinal collapsing functions:

[Madore's ψ
function](Madore%27s_%CF%88_function "Madore's ψ function")

[Buchholz's ψ
functions](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions")

[collapsing functions based on a weakly Mahlo
cardinal](User_blog:Denis_Maksudov/Ordinal_functions_collapsing_the_least_weakly_Mahlo_cardinal;_a_system_of_fundamental_sequences "User blog:Denis Maksudov/Ordinal functions collapsing the least weakly Mahlo cardinal; a system of fundamental sequences")

  

## References

1\. W.Buchholz. A New System of Proof-Theoretic Ordinal Functions.
Annals of Pure and Applied Logic (1986),32

2\. M.Jäger. \(\rho\)-inaccessible ordinals, collapsing functions and
a recursive notation system. Arch. Math. Logik Grundlagenforsch
(1984),24


