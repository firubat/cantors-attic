---
title: Fast-growing hierarchy
permalink: Fast-growing_hierarchy
---











The fast-growing hierarchy is a family of increasing functions
\((f_\alpha:\mathbb N\rightarrow\mathbb N)_{\alpha<\mu}\)
where \(\mu\) is a large countable ordinal such that a fundamental
sequence is assigned for each limit ordinal less than \(\mu\). It
maps countable ordinals to certain functions. The fast-growing hierarchy
is defined as follows:

-   \(f_0(n)=n+1\)
-   \(f_{\alpha+1}(n)=f^n_\alpha(n)\)
-   \(f_\alpha(n)=f_{\alpha\[n\]}(n)\) if and only if
    \(\alpha\) is a limit ordinal,

where:

-   \(f^n\) denotes function iteration i.e. \(f_\alpha^0(n)=n\)
    and \(f_\alpha^{m+1}(n)=f_\alpha(f_\alpha^{m}(n))\)
-   \(\alpha\[n\]\) denotes the \(n\)th element of the fundamental
    sequence assigned to the limit ordinal \(\alpha\)

Every nonzero ordinal
\(\alpha<\varepsilon_0=\min\{\beta\|\beta=\omega^\beta\}\)
can be represented in a unique Cantor normal form
\(\alpha=\omega^{\beta_{1}}+
\omega^{\beta_{2}}+\cdots+\omega^{\beta_{k-1}}+\omega^{\beta_{k}}\)
where
\(\alpha>\beta_1\geq\beta_2\geq\cdots\geq\beta_{k-1}\geq\beta_k\).

If \(\beta_k>0\) then \(\alpha\) is a limit and we can assign
to it a fundamental sequence as follows

\(\alpha\[n\]=\omega^{\beta_{1}}+
\omega^{\beta_{2}}+\cdots+\omega^{\beta_{k-1}}+\left\{\begin{array}{lcr}
\omega^\gamma n \text{ if } \beta_k=\gamma+1\\
\omega^{\beta_k\[n\]} \text{ if } \beta_k \text{ is a limit.}\\
\end{array}\right.\)

  
If \(\alpha=\varepsilon_0\) then \(\alpha\[0\]=0\) and
\(\alpha\[n+1\]=\omega^{\alpha\[n\]}\).

This system of fundamental sequences gives us so-called Wainer hierarchy
- the most well-known example of fast-growing hierarchy. There are much
stronger systems of fundamental sequences you can see on the following
pages:

-   <a href="http://googology.wikia.com/wiki/List_of_systems_of_fundamental_sequences" class="external text">List of systems of fundamental sequences</a>
-   [Madore's ψ
    function](Madore%27s_%CF%88_function "Madore's ψ function")
-   [Buchholz's ψ
    functions](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions")
-   [Jäger's ψ
    functions](J%C3%A4ger%27s_collapsing_functions_and_%CF%81-inaccessible_ordinals "Jäger's collapsing functions and ρ-inaccessible ordinals")
-   [Collapsing functions based on a weakly Mahlo
    cardinal](User_blog:Denis_Maksudov/Ordinal_functions_collapsing_the_least_weakly_Mahlo_cardinal;_a_system_of_fundamental_sequences "User blog:Denis Maksudov/Ordinal functions collapsing the least weakly Mahlo cardinal; a system of fundamental sequences")

## Values

These calculations are based on
[Diagonalization](Diagonalization "Diagonalization").
There are a few things to note: "\(\uparrow\)" means [Knuth's
up-arrow
notation](Knuth%27s_up-arrow_notation "Knuth's up-arrow notation").
"\(\lbrace\rbrace\)" means
[BAN](Bird%27s_array_notation "Bird's array notation").

\begin{eqnarray*} f_0(n) &=& n + 1 \\ f_1(n) &=& f_0^n(n) = (
\cdots ((n + 1) + 1) + \cdots + 1) = n + n = 2n \\ f_2(n) &=&
f_1^n(n) = 2(2(\ldots 2(2n))) = 2^n n > 2 \uparrow n \\ f_3(n)
&>& 2\uparrow\uparrow n \\ f_4(n) &>&
2\uparrow\uparrow\uparrow n \\ f_m(n) &>& 2\uparrow^{m-1} n
\\ f_\omega(n) &>& 2\uparrow^{n-1} n = Ack(n) \\
f_{\omega+1}(n) &>& \lbrace n,n,1,2 \rbrace \\
f_{\omega+2}(n) &>& \lbrace n,n,2,2 \rbrace \\
f_{\omega+m}(n) &>& \lbrace n,n,m,2 \rbrace \\ f_{\omega2}(n)
&>& \lbrace n,n,n,2 \rbrace \\ f_{\omega3}(n) &>& \lbrace
n,n,n,3 \rbrace \\ f_{\omega m}(n) &>& \lbrace n,n,n,m \rbrace
\\ f_{\omega^2}(n) &>& \lbrace n,n,n,n \rbrace \\
f_{\omega^3}(n) &>& \lbrace n,n,n,n,n \rbrace \\
f_{\omega^m}(n) &>& \lbrace n,m+2 \[2\] 2 \rbrace \\
f_{\omega^{\omega}}(n) &>& \lbrace n,n+2 \[2\] 2 \rbrace >
\lbrace n,n \[2\] 2 \rbrace \\ f_{\omega^{\omega}+1}(n) &>&
\lbrace n,n,2 \[2\] 2 \rbrace \\ f_{\omega^{\omega}+2}(n) &>&
\lbrace n,n,3 \[2\] 2 \rbrace \\ f_{\omega^{\omega}+m}(n) &>&
\lbrace n,n,m+1 \[2\] 2 \rbrace \\ f_{\omega^{\omega}+\omega}(n)
&>& \lbrace n,n,n+1 \[2\] 2 \rbrace > \lbrace n,n,n \[2\] 2
\rbrace \\ f_{\omega^{\omega}+\omega+1}(n) &>& \lbrace
n,n,1,2 \[2\] 2 \rbrace \\ f_{\omega^{\omega}+\omega2}(n) &>&
\lbrace n,n,n,2 \[2\] 2 \rbrace \\
f_{\omega^{\omega}+\omega^2}(n) &>& \lbrace n,n,n,n \[2\] 2
\rbrace \\ f_{ {\omega^{\omega}}2}(n) &>& \lbrace n,n \[2\] 3
\rbrace \\ f_{ {\omega^{\omega}}3}(n) &>& \lbrace n,n \[2\] 4
\rbrace \\ f_{ {\omega^{\omega}}m}(n) &>& \lbrace n,n \[2\] m+1
\rbrace \\ f_{\omega^{\omega+1}}(n) &>& \lbrace n,n \[2\] n+1
\rbrace > \lbrace n,n \[2\] n \rbrace \\
f_{\omega^{\omega+2}}(n) &>& \lbrace n,n \[2\] n,n \rbrace \\
f_{\omega^{\omega+3}}(n) &>& \lbrace n,n,n \[2\] n,n,n \rbrace
\\ f_{\omega^{\omega+m}}(n) &>& \lbrace n,m \[2\] 1 \[2\] 2
\rbrace \\ f_{\omega^{\omega2}}(n) &>& \lbrace n,n \[2\] 1
\[2\] 2 \rbrace = \lbrace n,2 \[3\] 2 \rbrace \\
f_{\omega^{\omega3}}(n) &>& \lbrace n,n \[2\] 1 \[2\] 1 \[2\] 2
\rbrace = \lbrace n,3 \[3\] 2 \rbrace \\ f_{\omega^{\omega
m}}(n) &>& \lbrace n,m \[3\] 2 \rbrace \\
f_{\omega^{\omega^2}}(n) &>& \lbrace n,n \[3\] 2 \rbrace \\
f_{\omega^{\omega^3}}(n) &>& \lbrace n,n \[4\] 2 \rbrace \\
f_{\omega^{\omega^m}}(n) &>& \lbrace n,n \[m+1\] 2 \rbrace \\
f_{\omega^{\omega^\omega}}(n) &>& \lbrace n,n \[n+1\] 2 \rbrace
= \lbrace n,n \[1,2\] 2 \rbrace \\ f_{^4{\omega}}(n) &>&
\lbrace n,n \[1 \[2\] 2\] 2 \rbrace \\ f_{^5{\omega}}(n) &>&
\lbrace n,n \[1 \[1,2\] 2\] 2 \rbrace \\ f_{^6{\omega}}(n) &>&
\lbrace n,n \[1 \[1 \[2\] 2\] 2\] 2 \rbrace \\
f_{\varepsilon_0}(n) &>& \lbrace n,n \[ \[1\]\] 2 \rbrace \\
f_{\varepsilon_02}(n) &>& \lbrace n,n \[ \[1\]\] 3 \rbrace \\
f_{\varepsilon_0m}(n) &>& \lbrace n,n \[ \[1\]\] m+1 \rbrace
\\ f_{\varepsilon_0\omega}(n) &>& \lbrace n,n \[ \[1\]\] n+1
\rbrace \\ f_{\varepsilon_0{\omega^{\omega}}}(n) &>& \lbrace
n,n \[ \[1\]\] 1 \[2\] 2 \rbrace \\
f_{\varepsilon_0{\omega^{\omega^{\omega}}}}(n) &>& \lbrace n,n
\[ \[1\]\] 1 \[1,2\] 2 \rbrace \\
f_{\varepsilon_0{\omega^{\omega^{\omega^{\omega}}}}}(n) &>&
\lbrace n,n \[ \[1\]\] 1 \[1 \[2\] 2\] 2 \rbrace \\
f_{\varepsilon_0^2}(n) &>& \lbrace n,n \[ \[1\]\] 1 \[ \[1\]\] 2
\rbrace \\ f_{\varepsilon_0^3}(n) &>& \lbrace n,n \[ \[1\]\] 1
\[ \[1\]\] 1 \[ \[1\]\] 2 \rbrace \\
f_{\varepsilon_0^{\omega}}(n) &>& \lbrace n,n \[ \[2\]\] 2
\rbrace \\ f_{\varepsilon_0^{\omega^{\omega}}}(n) &>&
\lbrace n,n \[ \[1,2\]\] 2 \rbrace \\
f_{\varepsilon_0^{\omega^{\omega^{\omega}}}}(n) &>& \lbrace
n,n \[\[1 \[2\] 2\]\] 2 \rbrace \\
f_{\varepsilon_0^{\varepsilon_0}}(n) &>& \lbrace n,n \[\[1 \[
\[1\]\] 2\]\] 2 \rbrace \\
f_{\varepsilon_0^{\varepsilon_0^{\varepsilon_0}}}(n) &>&
\lbrace n,n \[\[1 \[ \[1\]\] 1 \[ \[1\]\] 2\]\] 2 \rbrace \\
f_{\varepsilon_0^{\varepsilon_0^{\varepsilon_0^{\varepsilon_0}}}}(n)
&>& \lbrace n,n \[\[1 \[\[1 \[ \[1\]\] 2\]\] 2\]\] 2 \rbrace \\
f_{\varepsilon_1}(n) &>& \lbrace n,n \[\[\[1\]\]\] 2 \rbrace
\\ f_{\varepsilon_2}(n) &>& \lbrace n,n \[\[\[ \[1\]\]\]\] 2
\rbrace \\ f_{\varepsilon_{\omega}}(n) &>& \lbrace n,n
\[1\backslash1,2\] 2 \rbrace \\ f_{\varepsilon_{\omega^2}}(n)
&>& \lbrace n,n \[1\backslash1,1,2\] 2 \rbrace \\
f_{\varepsilon_{\omega^{\omega}}}(n) &>& \lbrace n,n
\[1\backslash1 \[2\] 2\] 2 \rbrace \\
f_{\varepsilon_{\omega^{\omega^{\omega}}}}(n) &>& \lbrace n,n
\[1\backslash1 \[1,2\] 2\] 2 \rbrace \\
f_{\varepsilon_{\varepsilon_0}}(n) &>& \lbrace n,n
\[1\backslash1 \[ \[1\]\] 2\] 2 \rbrace \\
f_{\varepsilon_{\varepsilon_{\varepsilon_0}}}(n) &>& \lbrace
n,n \[1\backslash1 \[1\backslash1 \[ \[1\]\] 2\] 2\] 2 \rbrace \\
f_{\zeta_0}(n) &>& \lbrace n,n \[1\backslash1\backslash2\] 2
\rbrace \\ f_{\zeta_0^{\zeta_0}}(n) &>& \lbrace n,n \[1
\[1\backslash1\backslash2\] 2\backslash1\backslash2\] 2 \rbrace
\\ f_{\varepsilon_{\zeta_0+1}}(n) &>& \lbrace n,n
\[1\backslash2\backslash2\] 2 \rbrace \\
f_{\varepsilon_{\zeta_0+2}}(n) &>& \lbrace n,n
\[1\backslash3\backslash2\] 2 \rbrace \\
f_{\varepsilon_{\varepsilon_{\zeta_0+1}}} &>& \lbrace n,n
\[1\backslash1 \[1\backslash2\backslash2\] 2\backslash2\] 2 \rbrace
\\ f_{\zeta_1}(n) &>& \lbrace n,n \[1\backslash1\backslash3\]
2 \rbrace \\ f_{\zeta_2}(n) &>& \lbrace n,n
\[1\backslash1\backslash4\] 2 \rbrace \\
f_{\zeta_{\zeta_0}}(n) &>& \lbrace n,n
\[1\backslash1\backslash1 \[1\backslash1\backslash2\] 2\] 2 \rbrace
\\ f_{\eta_0}(n) &>& \lbrace n,n
\[1\backslash1\backslash1\backslash2\] 2 \rbrace \\
f_{\varphi(4,0)}(n) &>& \lbrace n,n
\[1\backslash1\backslash1\backslash1\backslash2\] 2 \rbrace \\
f_{\varphi(\omega,0)}(n) &>& \lbrace n,n \[1 \[2\]\backslash2\]
2 \rbrace \\ f_{\varphi(\varphi(\omega,0),0)}(n) &>& \lbrace
n,n \[1 \[1 \[1 \[2\]\backslash2\]\backslash2\] 2\] 2 \rbrace \\
f_{\Gamma_0}(n) &>& \lbrace n,n \[1/2\] 2 \rbrace \\
f_{\varphi(1,0,0,0)}(n) &>& \lbrace n,n \[1 \[1\neg4\] 2\] 2
\rbrace \\ f_{\vartheta(\Omega^{\omega})}(n) &>& \lbrace n,n
\[1 \[1\neg1,2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega^{\Omega})}(n) &>& \lbrace n,n \[1
\[1\neg1\neg2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega^{\Omega^{\Omega}})}(n) &>& \lbrace n,n \[1
\[1 \[1\backslash_33\] 2\] 2\] 2 \rbrace \\
f_{\vartheta(\vartheta_1(1))}(n) &>& \lbrace n,n \[1 \[1\sim3\]
2\] 2 \rbrace \\ f_{\vartheta(\vartheta_1(2))}(n) &>& \lbrace
n,n \[1 \[1\sim1\sim2\] 2\] 2 \rbrace \\
f_{\vartheta(\vartheta_1(\omega))}(n) &>& \lbrace n,n \[1 \[1
\[2/_32\] 2\] 2\] 2 \rbrace \\
f_{\vartheta(\vartheta_1(\Omega))}(n) &>& \lbrace n,n \[1 \[1
\[1/2/_32\] 2\] 2\] 2 \rbrace \\ f_{\vartheta(\Omega_2)}(n)
&>& \lbrace n,n \[1 \[1 \[1\sim2/_32\] 2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega_3)}(n) &>& \lbrace n,n \[1 \[1 \[1
\[1/_32/_42\] 2\] 2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\omega})}(n) &>& \lbrace n,n
\[1\bullet2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\varepsilon_0})}(n) &>& \lbrace n,n \[1
\[2/_{1 \[1\backslash2\] 2}2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\Gamma_0})}(n) &>& \lbrace n,n \[1
\[2/_{1 \[1/2\] 2}2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\vartheta(\Omega_2)})}(n) &>& \lbrace
n,n \[1 \[2/_{1 \[1 \[1 \[1\sim2/_32\] 2\] 2\] 2}2\] 2\] 2 \rbrace
\\ f_{\vartheta(\Omega_{\vartheta(\Omega_3)})}(n) &>&
\lbrace n,n \[1 \[2/_{1 \[1 \[1 \[1 \[1/_32/_42\] 2\] 2\] 2\] 2}2\]
2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\vartheta(\Omega_{\omega})})}(n) &>&
\lbrace n,n \[1 \[2/_{1 \[1\bullet2\] 2}2\] 2\] 2 \rbrace \\
f_{\vartheta(\Omega_{\vartheta(\Omega_{\vartheta(\Omega_{\omega})})})}(n)
&>& \lbrace n,n \[1 \[2/_{1 \[2/_{1 \[1\bullet2\] 2}2\] 2}2\] 2\]
2 \rbrace \end{eqnarray*}

## The relationship with other hierarhies

For \(\alpha<\varepsilon_0\) the fast-growing hierarchy relates
to the [Hardy
hierarchy](Hardy_hierarchy "Hardy hierarchy")
as follows

\(f_\alpha(n)=H_{\omega^\alpha}(n)\)

and at \(\varepsilon_0\) the Hardy hierarchy "catches up" to the
fast-growing hierarchy i.e.

\(f_{\varepsilon_0}(n-1) ≤ H_{\varepsilon_0}(n) ≤
f_{\varepsilon_0}(n+1)\) for all \(n ≥ 1\).

The [slow-growing
hierarchy](Slow-growing_hierarchy "Slow-growing hierarchy")
"catches up" to the fast-growing hierarchy at
\(\psi_0(\Omega_\omega)\), using [Buchholz's ψ
functions](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions").


