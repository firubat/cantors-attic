---
title: Diagonalization
permalink: Diagonalization
---











Diagonalization is a process that helps to directly compute values of
hierarchies without having to go from the bottom. Each ordinal that is
not a sucsessor has a fundemental sequence that helps. When we say some
ordinal diagonalized to some finite number, we use: some
ordinal\[number\] to express. You can replace any ordinal with the
(whatever number you are diagonalizing to)th of the fundemental
sequence.

# Sequences

The sequence for \(\omega\) is \(\lbrace 1,2,\cdots \rbrace\).

The sequence for \(\omega2\) is \(\lbrace
\omega+1,\omega+2,\cdots \rbrace\).

The sequence for \(\omega3\) is \(\lbrace
\omega2+1,\omega2+2,\cdots \rbrace\).

\(\cdots\cdots\)

The sequence for \(\omega^2\) is \(\lbrace
\omega,\omega2,\omega3,\cdots \rbrace\).

From now on, we just replace a loose \(\omega\) with the number we
are diagonalizing to, and replace something like \(\omega3\) with
\(\omega2+\omega\).

The sequence for \(\omega^{\omega}\) is \(\lbrace
\omega,\omega^2,\omega^3,\cdots \rbrace\).

The sequence for \(\omega^{\omega^{\omega}}\) is \(\lbrace
\omega^{\omega},\omega^{\omega^2},\omega^{\omega^3},\cdots
\rbrace\)

\(\cdots\)

The sequence for \(\varepsilon_0\) is \(\lbrace
1,\omega,\omega^{\omega},\omega^{\omega^{\omega}},\omega^{\omega^{\omega^{\omega}}},\cdots
\rbrace\)

The sequence for \(\varepsilon_1\) is \(\lbrace
\omega^{\varepsilon_0+1},\omega^{\omega^{\varepsilon_0+1}},\omega^{\omega^{\omega^{\varepsilon_0+1}}},\cdots
\rbrace\)

The sequence for \(\varepsilon_2\) is \(\lbrace
\omega^{\varepsilon_1+1},\omega^{\omega^{\varepsilon_1+1}},\omega^{\omega^{\omega^{\varepsilon_1+1}}},\cdots
\rbrace\)

\(\cdots\cdots\)

The sequence for \(\varepsilon_{\omega}\) is \(\lbrace
\varepsilon_1,\varepsilon_2,\varepsilon_3,\cdots \rbrace\)

We can even replace loose ordinals with the thing it is supposed to turn
into if it is alone.

The sequence for \(\varepsilon_{\varepsilon_0}\) is \(\lbrace
\varepsilon_1,\varepsilon_{\omega},\varepsilon_{\omega^{\omega}},\cdots
\rbrace\)

The sequence for \(\varepsilon_{\varepsilon_{\varepsilon_0}}\)
is \(\lbrace
\varepsilon_{\varepsilon_1},\varepsilon_{\varepsilon_{\omega}},\varepsilon_{\varepsilon_{\omega^{\omega}}},\cdots
\rbrace\)

\(\cdots\)

The sequence for \(\zeta_0\) is \(\lbrace
\varepsilon_0,\varepsilon_{\varepsilon_0},\varepsilon_{\varepsilon_{\varepsilon_0}},\varepsilon_{\varepsilon_{\varepsilon_{\varepsilon_0}}},\cdots
\rbrace\)

The sequence for \(\eta_0\) is \(\lbrace
\zeta_0,\zeta_{\zeta_0},\zeta_{\zeta_{\zeta_0}},\zeta_{\zeta_{\zeta_{\zeta_0}}},\cdots
\rbrace\)

Now we introduce the Veblen function, which is defined as follows:

1\. \(\varphi_0(0)=1\)

2\. If \(\alpha\) is a succsessor, then
\(\varphi_\alpha(0)\[n\]=\varphi_{\alpha-1}^n(0)\) and
\(\varphi_\alpha(a)\[n\]=\varphi_{\alpha-1}^n(\varphi_\alpha(a-1)+1)\).

3\. If \(\beta\) is a limit ordinal, then
\(\varphi_\beta(0)\[n\]=\varphi_n(0)\) and
\(\varphi_\beta(a)\[n\]=\varphi_n(\varphi_\beta(a-1)+1)\).

The sequence for \(\varphi_4(0)\) is \(\lbrace
\eta_0,\eta_{\eta_0},\eta_{\eta_{\eta_0}},\eta_{\eta_{\eta_{\eta_0}}},\cdots
\rbrace\)

The sequence for \(\varphi_\omega(0)\) is \(\lbrace
\varepsilon_0,\zeta_0,\eta_0,\varphi_4(0),\cdots \rbrace\)

\(\cdots\cdots\)

The sequence for \(\Gamma_0=\varphi(1,0,0)\) is \(\lbrace
1,\varphi_1(0),\varphi_{\varphi_1(0)}(0),\cdots \rbrace\)

Now we encounter large countable ordinals that can only be expressed
with the [Extended Veblen
function](Extended_Veblen_function "Extended Veblen function").

The sequence for \(\Gamma_1=\varphi(1,0,1)\) is \(\lbrace
\varphi_{\Gamma_0+1}(0),\varphi_{\varphi_{\Gamma_0+1}(0)}(0),\cdots
\rbrace\)

\(\cdots\cdots\)

The sequence for
\(\Gamma_{\Gamma_{\Gamma_\ddots}}=\varphi(1,1,0)\) is
\(\lbrace stuck\)

Well, that's about it. The Wainer hierarchy only lasts up to the limit
of the \(\Gamma\) function.

## ψ function sequences

In [Madore's ψ
function](Madore%27s_%CF%88_function "Madore's ψ function"),
there is a thing called \(\Omega\).

The sequence for \(\psi(\Omega^\omega+\Omega^3\omega2+\Omega)\)
is

\(\{\psi(0),\psi(\Omega^\omega+\Omega^3\omega2+\psi(0)),\psi(\Omega^\omega+\Omega^3\omega2+\psi(\Omega^\omega+\Omega^3\omega2+\psi(0))),\psi(\Omega^\omega+\Omega^3\omega2+\psi(\Omega^\omega+\Omega^3\omega2+\psi(\Omega^\omega+\Omega^3\omega2+\psi(0)))),\cdots\}\)

Well, it's like this.


