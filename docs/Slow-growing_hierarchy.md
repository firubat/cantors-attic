---
title: Slow-growing hierarchy
permalink: Slow-growing_hierarchy
---











The slow-growing hierarchy is a family of functions
\((g_\alpha:\mathbb N\rightarrow\mathbb N)_{\alpha<\mu}\)
where \(\mu\) is a large countable ordinal such that a fundamental
sequence is assigned for each limit ordinal less than \(\mu\).

The slow-growing hierarchy is defined as follows:

\(g_0(n)=0 \\ g_{\alpha+1}(n)=g_\alpha(n)+1\)

\(g_\alpha(n)=g_{\alpha\[n\]}(n)\) if and only if \(\alpha\) is
a limit ordinal,

where \(\alpha\[n\]\) denotes the \(n\)th element of the
fundamental sequence assigned to the limit ordinal \(\alpha\).

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

  
If \(\alpha=\varepsilon_0\) then \(\alpha\[0\]=1\) and
\(\alpha\[n+1\]=\omega^{\alpha\[n\]}\).

Using this system of fundamental sequences we can define the
slow-growing hierarchy up to \(\varepsilon_0\) and we have
\(g_{\varepsilon_0}(n) = n \uparrow\uparrow n \)

There are much stronger systems of fundamental sequences you can see on
the following pages:

-   <a href="http://googology.wikia.com/wiki/List_of_systems_of_fundamental_sequences" class="external text">List of systems of fundamental sequences</a>
-   [Madore's ψ
    function](Madore%27s_%CF%88_function "Madore's ψ function")
-   [Buchholz's ψ
    functions](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions")
-   [Jäger's ψ
    functions](J%C3%A4ger%27s_collapsing_functions_and_%CF%81-inaccessible_ordinals "Jäger's collapsing functions and ρ-inaccessible ordinals")
-   [Collapsing functions based on a weakly Mahlo
    cardinal](User_blog:Denis_Maksudov/Ordinal_functions_collapsing_the_least_weakly_Mahlo_cardinal;_a_system_of_fundamental_sequences "User blog:Denis Maksudov/Ordinal functions collapsing the least weakly Mahlo cardinal; a system of fundamental sequences")

The slow-growing hierarchy "catches up" to the [fast-growing
hierarchy](Fast-growing_hierarchy "Fast-growing hierarchy")
at \(\psi_0(\Omega_\omega)\), using [Buchholz's ψ
functions](Buchholz%27s_%CF%88_functions "Buchholz's ψ functions").

## Values

\(g_0(n) = 0\)

\(g_1(n) = 1\)

\(g_2(n) = 2\)

\(g_m(n) = m\)

\(g_\omega(n) = n\)

\(g_{\omega+1}(n) = n+1 = f_0(n)\)

\(g_{\omega2}(n) = f_1(n)\)

\(g_{\omega^{\omega}}(n) = n^n \approx f_2(n)\)

\(g_{\omega^{\omega^{\omega}}}(n) = n^{n^n}\)

\(g_{\varepsilon_0}(n) = n \uparrow\uparrow n \approx f_3(n)\)

\(g_{\varepsilon_1}(n) \approx n \uparrow\uparrow (2n)\)

\(g_{\varepsilon_2}(n) \approx n \uparrow\uparrow (3n)\)

\(g_{\varepsilon_{\omega}}(n) \approx n \uparrow\uparrow
(n^2)\)

\(g_{\varepsilon_{\omega^2}}(n) \approx n \uparrow\uparrow
(n^3)\)

\(g_{\varepsilon_{\omega^3}}(n) \approx n \uparrow\uparrow
(n^4)\)

\(g_{\varepsilon_{\omega^{\omega}}}(n) \approx n
\uparrow\uparrow (n^n)\)

\(g_{\varepsilon_{\varepsilon_0}}(n) \approx n \uparrow\uparrow
(n \uparrow\uparrow n)\)

\(g_{\zeta_0}(n) \approx n \uparrow\uparrow\uparrow n \approx
f_4(n)\)

\(g_{\varepsilon_{\zeta_0+1}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow n\)

\(g_{\varepsilon_{\zeta_0+2}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (2n)\)

\(g_{\varepsilon_{\zeta_0 2}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n) \approx n \uparrow\uparrow\uparrow
(n+1)\)

\(g_{\varepsilon_{\zeta_0 3}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (2(n
\uparrow\uparrow\uparrow n))\)

\(g_{\varepsilon_{\zeta_0 4}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (3(n
\uparrow\uparrow\uparrow n))\)

\(g_{\varepsilon_{\zeta_0 \omega}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (n(n
\uparrow\uparrow\uparrow n))\)

\(g_{\varepsilon_{\zeta_0^2}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow ({(n
\uparrow\uparrow\uparrow n)}^2)\)

\(g_{\varepsilon_{\zeta_0^{\zeta_0}}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow ({(n
\uparrow\uparrow\uparrow n)}^{n \uparrow\uparrow\uparrow n})\)

\(g_{\varepsilon_{\varepsilon_{\zeta_0+1}}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow ((n
\uparrow\uparrow\uparrow n) \uparrow\uparrow n)\)

\(g_{\varepsilon_{\varepsilon_{\zeta_0 2}}}(n) \approx (n
\uparrow\uparrow\uparrow n) \uparrow\uparrow ((n
\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n)) \approx n \uparrow\uparrow\uparrow
(n+2)\)

\(g_{\varepsilon_{\varepsilon_{\varepsilon_{\zeta_0+1}}}}(n)
\approx (n \uparrow\uparrow\uparrow n) \uparrow\uparrow ((n
\uparrow\uparrow\uparrow n) \uparrow\uparrow ((n
\uparrow\uparrow\uparrow n) \uparrow\uparrow n))\)

\(g_{\zeta_1}(n) \approx n \uparrow\uparrow\uparrow 2n\)

\(g_{\zeta_2}(n) \approx n \uparrow\uparrow\uparrow 3n\)

\(g_{\zeta_\omega}(n) \approx n \uparrow\uparrow\uparrow n^2\)

\(g_{\zeta_{\omega^\omega}}(n) \approx n
\uparrow\uparrow\uparrow n^n\)

\(g_{\zeta_{\varepsilon_0}}(n) \approx n
\uparrow\uparrow\uparrow (n \uparrow\uparrow n)\)

\(g_{\zeta_{\varepsilon_{\varepsilon_0}}}(n) \approx n
\uparrow\uparrow\uparrow (n \uparrow\uparrow (n \uparrow\uparrow
n))\)

\(g_{\zeta_{\zeta_0}}(n) \approx n \uparrow\uparrow\uparrow (n
\uparrow\uparrow\uparrow n)\)

\(g_{\zeta_{\zeta_{\zeta_0}}}(n) \approx n
\uparrow\uparrow\uparrow (n \uparrow\uparrow\uparrow (n
\uparrow\uparrow\uparrow n\)))

\(g_{\eta_0}(n) \approx n \uparrow\uparrow\uparrow\uparrow n
\approx f_5(n)\)

\(g_{\varepsilon_{\eta_0+1}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow n\)

\(g_{\varepsilon_{\eta_0+2}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow 2n\)

\(g_{\varepsilon_{\eta_0+\omega}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow n^2\)

\(g_{\varepsilon_{\eta_0+\omega^\omega}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow n^n\)

\(g_{\varepsilon_{\eta_0+\varepsilon_0}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0+\varepsilon_{\varepsilon_0}}}(n)
\approx (n \uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow
(n \uparrow\uparrow n \uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0+\zeta_0}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0+\zeta_1}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow 2n)\)

\(g_{\varepsilon_{\eta_0+\zeta_\omega}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n^2)\)

\(g_{\varepsilon_{\eta_0+\zeta_{\omega^\omega}}}(n) \approx
(n \uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n^n)\)

\(g_{\varepsilon_{\eta_0+\zeta_{\zeta_0}}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow n \uparrow\uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0 2}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow (n
\uparrow\uparrow\uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0 3}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow 2(n
\uparrow\uparrow\uparrow\uparrow n)\)

\(g_{\varepsilon_{\eta_0 \omega}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow n-1(n
\uparrow\uparrow\uparrow\uparrow n)\)

\(g_{\zeta_{\eta_0+1}}(n) \approx (n
\uparrow\uparrow\uparrow\uparrow n) \uparrow\uparrow\uparrow n\)

\(g_{\varphi(4,0)}(n) \approx n
\uparrow\uparrow\uparrow\uparrow\uparrow n \approx f_6(n)\)

\(g_{\varphi(5,0)}(n) \approx n
\uparrow\uparrow\uparrow\uparrow\uparrow\uparrow n \approx
f_7(n)\)

\(g_{\varphi(\omega,0)}(n) \approx \{n,n,n\} \approx
f_\omega(n)\)

\(g_{\varphi(\omega^\omega,0)}(n) \approx \{n,n,n^n\}\)

\(g_{\varphi(\varepsilon_0,0)}(n) \approx \{n,n,n
\uparrow\uparrow n\}\)

\(g_{\varphi(\zeta_0,0)}(n) \approx \{n,n,n
\uparrow\uparrow\uparrow n\}\)

\(g_{\varphi(\eta_0,0)}(n) \approx \{n,n,n
\uparrow\uparrow\uparrow\uparrow n\}\)

\(g_{\varphi(\varphi(\omega,0),0)}(n) \approx
\{n,n,\{n,n,n\}\}\)

\(g_{\varphi(\varphi(\varphi(\omega,0),0),0)}(n) \approx
\{n,n,\{n,n,\{n,n,n\}\}\}\)

\(g_{\Gamma_0}(n) \approx \{n,n,1,2\} < f_{\omega+1}(n)\)

\(g_{\varphi(\Gamma_0,1)}(n) \approx \{n,n+1,1,2\}\)

\(g_{\varphi(\varphi(\Gamma_0,1),0)}(n) \approx
\{n,n+2,1,2\}\)

\(g_{\Gamma_1}(n) \approx \{n,2n,1,2\}\)

\(g_{\Gamma_2}(n) \approx \{n,3n,1,2\}\)

\(g_{\Gamma_\omega}(n) \approx \{n,(n+1)n,1,2\}\)

\(g_{\Gamma_{\omega^2}}(n) \approx \{n,(n^2+1)n,1,2\}\)

\(g_{\Gamma_{\omega^\omega}}(n) \approx
\{n,(n^{n-1}+1)n,1,2\}\)

\(g_{\Gamma_{\omega^{\omega^\omega}}}(n) \approx
\{n,(n^{n^n-1}+1)n,1,2\}\)

\(g_{\Gamma_{\varepsilon_0}}(n) \approx \{n,n \uparrow\uparrow
n,1,2\}\)

\(g_{\Gamma_{\zeta_0}}(n) \approx \{n,n
\uparrow\uparrow\uparrow n,1,2\}\)

\(g_{\Gamma_{\eta_0}}(n) \approx \{n,n
\uparrow\uparrow\uparrow\uparrow n,1,2\}\)

\(g_{\Gamma_{\varphi(\omega,0)}}(n) \approx
\{n,\{n,n,n+1\},1,2\}\)

\(g_{\Gamma_{\Gamma_0}}(n) \approx \{n,\{n,n,1,2\},1,2\}\)

\(g_{\Gamma_{\Gamma_{\Gamma_0}}}(n) \approx
\{n,\{n,\{n,n,1,2\},1,2\},1,2\}\)

\(g_{\varphi(1,1,0)}(n) \approx \{n,n,2,2\} <
f_{\omega+2}(n)\)

\(g_{\varphi(1,2,0)}(n) \approx \{n,n,3,2\} <
f_{\omega+3}(n)\)

\(g_{\varphi(1,\omega,0)}(n) \approx \{n,n,n,2\} <
f_{\omega2}(n)\)

\(g_{\varphi(1,\Gamma_0,0)}(n) \approx
\{n,n,\{n,n,1,2\},2\}\)

\(g_{\varphi(1,\varphi(1,\Gamma_0,0),0)}(n) \approx
\{n,n,\{n,n,\{n,n,1,2\},2\},2\}\)

\(g_{\varphi(2,0,0)}(n) \approx \{n,n,1,3\} <
f_{\omega2+1}(n)\)

\(g_{\varphi(3,0,0)}(n) \approx \{n,n,1,4\} <
f_{\omega3+1}(n)\)

\(g_{\varphi(\omega,0,0)}(n) \approx \{n,n,1,n+1\}\)

\(g_{\varphi(\Gamma_0,0,0)}(n) \approx
\{n,n,1,\{n,n,1,2\}+1\}\)

\(g_{\varphi(1,0,0,0)}(n) \approx \{n,n,1,1,2\} <
f_{\omega^2+1}(n)\)

\(g_{\varphi(1,0,0,0,0)}(n) \approx \{n,n,1,1,1,2\} <
f_{\omega^3+1}(n)\)

\(g_{\varphi(1,0,0,0,0,0)}(n) \approx \{n,n,1,1,1,1,2\} <
f_{\omega^4+1}(n)\)

\(g_{\vartheta(\Omega^\omega)}(n) \approx \{n,n+2(1)2\} <
f_{\omega^\omega}(n)\)

\(g_{\vartheta(\Omega^{\omega+1})}(n) \approx \{n,n+3(1)2\}\)

\(g_{\vartheta(\Omega^{\omega 2})}(n) \approx \{n,2n(1) 2\}\)

\(g_{\vartheta(\Omega^{\omega 3})}(n) \approx \{n,3n(1) 2\}\)

\(g_{\vartheta(\Omega^{\omega^2})}(n) \approx \{n,n^2(1) 2\}\)

\(g_{\vartheta(\Omega^{\omega^\omega})}(n) \approx \{n,n^n(1)
2\}\)

\(g_{\vartheta(\Omega^{\varepsilon_0})}(n) \approx
\{n,n\uparrow\uparrow n(1) 2\}\)

\(g_{\vartheta(\Omega^{\Gamma_0})}(n) \approx
\{n,\{n,n,1,2\}(1)2\}\)

\(g_{\vartheta(\Omega^{\Omega})}(n) \approx \{n,n,2(1)2\} <
f_{\omega^\omega+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega}+1)}(n) \approx \{n,n,3(1)2\} <
f_{\omega^\omega+2}(n)\)

\(g_{\vartheta(\Omega^{\Omega}+\omega)}(n) \approx
\{n,n,n(1)2\} < f_{\omega^\omega+\omega}(n)\)

\(g_{\vartheta(\Omega^{\Omega}+\Omega)}(n) \approx
\{n,n,1,2(1)2\} < f_{\omega^\omega+\omega+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega}+\Omega \omega)}(n) \approx
\{n,n,n,n(1)2\} < f_{\omega^\omega+\omega^2}(n)\)

\(g_{\vartheta(\Omega^{\Omega}+\Omega^\omega)}(n) \approx
\{n,n(1)3\} < f_{\omega^\omega2}(n)\)

\(g_{\vartheta(\Omega^{\Omega} 2)}(n) \approx \{n,n,2(1)3\} <
f_{\omega^\omega2+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega} 2+\Omega^\omega)}(n) \approx
\{n,n(1)4\} < f_{\omega^\omega3}(n)\)

\(g_{\vartheta(\Omega^{\Omega} \omega)}(n) \approx \{n,n(1)n\}
< f_{\omega^{\omega+1}}(n)\)

\(g_{\vartheta(\Omega^{\Omega + 1})}(n) \approx \{n,n(1)1,2\}
< f_{\omega^{\omega+1}+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega 2})}(n) \approx \{n,n(1)(1)2\}
< f_{\omega^{\omega2}}(n)\)

\(g_{\vartheta(\Omega^{\Omega 3})}(n) \approx \{n,n(1)(1)(1)2\}
< f_{\omega^{\omega3}}(n)\)

\(g_{\vartheta(\Omega^{\Omega \omega})}(n) \approx \{n,n(2)2\}
< f_{\omega^{\omega^2}}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2})}(n) \approx \{n,n,2(2)2\} <
f_{\omega^{\omega^2}+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2}+\Omega^{\Omega \omega})}(n)
\approx \{n,n(2)3\} < f_{\omega^{\omega^2}2}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2}\omega)}(n) \approx \{n,n(2)n\}
< f_{\omega^{\omega^2+1}}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2 + 1})}(n) \approx \{n,n(2)1,2\}
< f_{\omega^{\omega^2+1}+1}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2 + \omega})}(n) \approx
\{n,n(2)(1)2\} < f_{\omega^{\omega^2+\omega}}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2 + \Omega\omega})}(n) \approx
\{n,n(2)(2)2\} < f_{\omega^{\omega^22}}(n)\)

\(g_{\vartheta(\Omega^{\Omega^2\omega})}(n) \approx \{n,n(3)2\}
< f_{\omega^{\omega^3}}(n)\)

\(g_{\vartheta(\Omega^{\Omega^3})}(n) \approx \{n,n,2(3)2\} <
f_{\omega^{\omega^3}+1}(n)\)

## See also

[Fast-growing
hierarchy](Fast-growing_hierarchy "Fast-growing hierarchy")

[Hardy
hierarchy](Hardy_hierarchy "Hardy hierarchy")

## References

1\. Georg Moser and Andreas Weiermann.Relating derivation lengths with
the slow-growing hierarchy directly. (2003) REWRITING TECNIQUES AND
APPLICATIONS, PROCEEDINGS. 2706. p.296-310


