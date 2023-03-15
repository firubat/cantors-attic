---
title: Bird's array notation
permalink: Bird's_array_notation
---


Bird's array notation is a parallel notation to
[BEAF](BEAF "BEAF").

# Linear arrays

-   **Rule 1**. With one or two entries, we have \(\{a\} = a\),
    \(\{a,b\} = a^b\).
-   **Rule 2**. If the last entry is 1, it can be removed:
    \(\{\\#,1\} = \{\\#\}\).
-   **Rule 3**. If the second entry is 1, the value is just the first
    entry: \(\{a,1 \\#\} = a\).
-   **Rule 4**. If the third entry is 1:
    \(\{a,b,\underbrace{1,1,\cdots,1,1}_n,c \\#\} =
    \{\underbrace{a,a,a,a,\cdots,a}_{n+1},\{a,b-1,\underbrace{1,1,\cdots,1,1}_n,c
    \\#\},c-1 \\#\}\)
-   **Rule 5**. Otherwise:
    \(\{a,b,c \\#\} = \{a,\{a,b-1,c \\#\},c-1 \\#\}\)

Limit: \(\{n,n\[2\]2\}\) has growth rate \(\omega^\omega\)

## Example

\begin{eqnarray*} \{3,3,1,2\} &=& \{3,3,\{3,2,1,2\},1\} \\ &=&
\{3,3,\{3,3,\{3,1,1,2\},1\}\} \\ &=& \{3,3,\{3,3,3\}\} \\
&=& \{3,3,\{3,\{3,2,3\},2\}\} \\ &=&
\{3,3,\{3,\{3,\{3,1,3\},2\},2\}\} \\ &=&
\{3,3,\{3,\{3,3,2\},2\}\} \\ &=&
\{3,3,\{3,\{3,\{3,2,2\},1\},2\}\} \\ &=&
\{3,3,\{3,\{3,\{3,\{3,1,2\},1\}\},2\}\} \\ &=&
\{3,3,\{3,\{3,\{3,3\}\},2\}\} \\ &=&
\{3,3,\{3,7625597484987,2\}\} \\ &=&
3\uparrow^{3\uparrow\uparrow7625597484987}3 \end{eqnarray*}

# Multidimentional arrays

-   **Rule M1**. If there are only two entries, \(\{a, b\} = a^b\).
-   **Rule M2**. If \(m < n\), we have \(\{\\# \[m\] 1 \[n\]
    \\#^*\} = \{\\# \[n\] \\#^*\}\). (This also removes ones
    from the end of an array.)
-   **Rule M3**. If the second entry is 1, we have \(\{a,1 \\#\} =
    a\).
-   **Rule M4**. If there is a non-zero entry immediately after batch of
    unfilled separators:
    \(\{a,b \[m_1\] 1 \[m_2\] \cdots 1 \[m_x\] c \\#\} = \{a
    \langle m_1-1 \rangle b \[m_1\] a \langle m_2-1 \rangle b
    \[m_2\] \cdots a \langle m_x-1 \rangle b \[m_x\] (c-1)
    \\#\}\)
-   **Rule M5**. If there is a non-zero entry after batch of unfilled
    separators and a 1.
    \(\{a,b \[m_1\] 1 \[m_2\] \cdots 1 \[m_x\] 1,c \\#\} = \{a
    \langle m_1-1 \rangle b \[m_1\] a \langle m_2-1 \rangle b
    \[m_2\] \cdots a \langle m_x-1 \rangle b \[m_x\] \{a,b-1
    \[m_1\] 1 \[m_2\] \cdots 1 \[m_x\] 1,c \\#\},c-1 \\#\}\)
-   **Rule M6**. Rules M1-M5 don't apply.
    \(\{a,b,c \\#\} = \{a,\{a,b-1,c \\#\},c-1 \\#\}\)
-   **Rule A1**. If \(c = 0\), we have \(\textrm\` a \langle 0
    \rangle b = a \textrm'\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle c
    \rangle 1 = a \textrm'\).
-   **Rule A3**. Otherwise, \(\textrm\` a \langle c \rangle b
    \textrm' = \textrm\` \underbrace{a \langle c-1 \rangle b \[c\]
    \cdots \[c\] a \langle c-1 \rangle b}_b \textrm'\).

Limit: \(\{n,n\[1,2\]2\}\) has growth rate
\(\omega^{\omega^\omega}\)

## Example

\begin{eqnarray*} \{3,2\[3\]2\} &=& \{3 \langle 2 \rangle
2\[3\]1\} \\ &=& \{3 \langle 1 \rangle 2\[2\]3 \langle 1 \rangle
2\} \\ &=& \{3,3\[2\]3,3\} \\ &=& \{3,3,3\[2\]2,3\} \\ &=&
\{3,\{3,2,3\[2\]2,3\},2\[2\]2,3\} \\ &=&
\{3,\{3,3,2\[2\]2,3\},2\[2\]2,3\} \\ &=&
\{3,\{3,\{3,2,2\[2\]2,3\}\[2\]2,3\},2\[2\]2,3\} \\ &=&
\{3,\{3,\{3,3\[2\]2,3\}\[2\]2,3\},2\[2\]2,3\} \\ &=&
\{3,\{3,\{3,\{3,\{3,3\[2\]1,3\}\[2\]1,3\},2\[2\]1,3\}\[2\]2,3\},2\[2\]2,3\}
\end{eqnarray*}

# Hyperdimentional arrays

-   **Rule M1**. If there are only two entries, \(\{a, b\} = a^b\).
-   **Rule M2**. If \(m < n\), we have \(\{\\# \[m\] 1 \[n\]
    \\#^*\} = \{\\# \[n\] \\#^*\}\). (This also removes ones
    from the end of an array.)
-   **Rule M3**. If the second entry is 1, we have \(\{a,1 \\#\} =
    a\).
-   **Rule M4**. If there is a non-zero entry immediately after batch of
    unfilled separators:
    \(\{a,b \[m_1 \\#_1\] 1 \[m_2 \\#_2\] \cdots 1 \[m_x
    \\#_x\] c \\#\} = \{a \langle m_1-1 \\#_1 \rangle b \[m_1
    \\#_1\] a \langle m_2-1 \\#_2 \rangle b \[m_2 \\#_2\]
    \cdots a \langle m_x-1 \\#_x \rangle b \[m_x \\#_x\] (c-1)
    \\#\}\)
-   **Rule M5**. If there is a non-zero entry after batch of unfilled
    separators and a 1.
    \(\{a,b \[m_1 \\#_1\] 1 \[m_2 \\#_2\] \cdots 1 \[m_x
    \\#_x\] 1,c \\#\}\)  
    \(= \{a \langle m_1-1 \\#_1 \rangle b \[m_1 \\#_1\] a
    \langle m_2-1 \\#_2 \rangle b \[m_2 \\#_2\] \cdots a
    \langle m_x-1 \\#_x \rangle b \[m_x \\#_x\] \{a,b-1 \[m_1
    \\#_1\] 1 \[m_2 \\#_2\] \cdots 1 \[m_x \\#_x\] 1,c
    \\#\},c-1 \\#\}\)
-   **Rule M6**. Rules M1-M5 don't apply.
    \(\{a,b,c \\#\} = \{a,\{a,b-1,c \\#\},c-1 \\#\}\)
-   **Rule A1**. If \(c = 0\), we have \(\textrm\` a \langle 0
    \rangle b = a \textrm'\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle A
    \rangle 1 = a \textrm'\).
-   **Rule A3**. If the first entry in the angle brackets is zero, and
    there exists a non-zero entry after it:
    \(\textrm\` a \langle 0,\underbrace{1,1,\cdots,1,1}_n,c \\#
    \rangle b \textrm' = \textrm\` a \langle
    \underbrace{b,b,b,\cdots,b,b}_{n+1},c-1 \\# \rangle b
    \textrm'\)
-   **Rule A4**. Otherwise, \(\textrm\` a \langle c \\# \rangle b
    \textrm' = \textrm\` \underbrace{a \langle c-1 \\# \rangle b
    \[c \\#\] \cdots \[c \\#\] a \langle c-1 \\# \rangle b}_b
    \textrm'\).

Limit: \(\{n,n\[1\[2\]2\]2\}\) has growth rate \(^4 \omega\)

## Example

\begin{eqnarray*} \{3,2\[1,1,2\]2\} &=& \{3 \langle 0,1,2 \rangle
2\} \\ &=& \{3 \langle 2,2 \rangle 2\} \\ &=& \{3 \langle 1,2
\rangle 2\[2,2\]3 \langle 1,2 \rangle 2\} \\ &=&
\{3,3\[2\]3,3\[1,2\]3,3\[2\]3,3\[2,2\]3,3\[2\]3,3\[1,2\]3,3\[2\]3,3\}
\end{eqnarray*}

# Nested arrays

Main rules will remain the same forever.

-   **Rule A1**. If \(c = 0\), we have \(\textrm\` a \langle 0
    \rangle b = a \textrm'\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle A
    \rangle 1 = a \textrm'\).
-   **Rule A3**. If \(\[A\] < \[B\]\), \(\textrm\` a \langle
    \\# \[A\] 1 \[B\] \\#^* \rangle b \textrm' = \textrm\` a
    \langle \\# \[B\] \\#^* \rangle b \textrm'\).
-   **Rule A4**. If the first entry in the angle brackets is zero, and
    there exists a non-zero entry after it:
    \(\textrm\` a \langle 0 \[x_1 \\#_1\] 1 \[x_2 \\#_2\]
    \cdots 1 \[x_n \\#_n\] c \\# \rangle b \textrm' = \textrm\`
    a \langle b \langle x_1-1 \\#_1 \rangle b \[x_1 \\#_1\] b
    \langle x_2-1 \\#_2 \rangle b \[x_2 \\#_2\] \cdots b
    \langle x_n-1 \\#_n \rangle b \[x_n \\#_n\] c-1 \\#
    \rangle b \textrm'\)
-   **Rule A5**. Otherwise, \(\textrm\` a \langle c \\# \rangle b
    \textrm' = \textrm\` \underbrace{a \langle c-1 \\# \rangle b
    \[c \\#\] \cdots \[c \\#\] a \langle c-1 \\# \rangle b}_b
    \textrm'\).

Limit: \(\{n,n\[1\backslash2\]2\}\) has growth rate
\(\varepsilon_0\)

## Example

\begin{eqnarray*} \{3,2\[1\[2\]2\]2\} &=& \{3 \langle 0\[2\]2
\rangle 2\} \\ &=& \{3 \langle 2 \langle 1 \rangle 2 \rangle
2\} \\ &=& \{3 \langle 2,2 \rangle 2\} \\ &=&
\{3,3\[2\]3,3\[1,2\]3,3\[2\]3,3\[2,2\]3,3\[2\]3,3\[1,2\]3,3\[2\]3,3\}
\end{eqnarray*}

# Hyper-Nested arrays

-   **Rule A1**. If \(c = 0\), we have \(\textrm\` a \langle 0
    \rangle b \textrm' = \textrm\` a \textrm'\) and \(\textrm\` a
    \langle 0 \rangle \backslash b \textrm' = \textrm\` a
    \textrm'\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle A
    \rangle 1 \textrm' = \textrm\` a \textrm'\) and \(\textrm\` a
    \langle A \rangle \backslash 1 \textrm' = \textrm\` a
    \textrm'\).
-   **Rule A3**. If \(\[A\] < \[B\]\), \(\textrm\` a \langle
    \\# \[A\] 1 \[B\] \\#^* \rangle b \textrm' = \textrm\` a
    \langle \\# \[B\] \\#^* \rangle b \textrm'\) and
    \(\textrm\` a \langle \\# \[A\] 1 \[B\] \\#^* \rangle
    \backslash b \textrm' = \textrm\` a \langle \\# \[B\] \\#^*
    \rangle \backslash b \textrm'\).
-   **Rule A4**. If the first entry in the angle brackets is zero, and
    there exists a non-zero entry after it:
    \(\textrm\` a \langle 0 \[x_1 \\#_1\]\backslash 1 \[x_2
    \\#_2\]\backslash \cdots 1 \[x_m \\#_m\]\backslash 1 \[y_1
    \\#^*_1\] 1 \[y_2 \\#^*_2\] \cdots \[y_n \\#^*_n\] c
    \\# \rangle b \textrm'\)  
    \(= \textrm\` a \langle b \langle x_1-1 \\#_1 \rangle
    \backslash b \[x_1 \\#_1\]\backslash b \langle x_2-1 \\#_2
    \rangle \backslash b \[x_2 \\#_2\]\backslash \cdots b
    \langle x_n-1 \\#_n \rangle \backslash b \[x_n
    \\#_n\]\backslash b \langle y_1-1 \\#^*_1 \rangle b \[y_1
    \\#^*_1\] b \langle y_2-1 \\#^*_2 \rangle b \[y_2
    \\#^*_2\] \cdots b \langle y_n-1 \\#^*_n \rangle b \[y_n
    \\#^*_n\] c-1 \\# \rangle b \textrm'\).
    \(\textrm\` a \langle 0 \[x_1 \\#_1\]\backslash 1 \[x_2
    \\#_2\]\backslash \cdots 1 \[x_m \\#_m\]\backslash 1 \[y_1
    \\#^*_1\] 1 \[y_2 \\#^*_2\] \cdots \[y_n \\#^*_n\] c
    \\# \rangle \backslash b \textrm'\)  
    \(= \textrm\` a \langle b \langle x_1-1 \\#_1 \rangle
    \backslash b \[x_1 \\#_1\]\backslash b \langle x_2-1 \\#_2
    \rangle \backslash b \[x_2 \\#_2\]\backslash \cdots b
    \langle x_n-1 \\#_n \rangle \backslash b \[x_n
    \\#_n\]\backslash b \langle y_1-1 \\#^*_1 \rangle b \[y_1
    \\#^*_1\] b \langle y_2-1 \\#^*_2 \rangle b \[y_2
    \\#^*_2\] \cdots b \langle y_n-1 \\#^*_n \rangle b \[y_n
    \\#^*_n\] c-1 \\# \rangle \backslash b \textrm'\).
-   **Rule A5**. First non-zero entry is prior to a single backslash:
    \(\textrm\` a \langle 0 \[x_1 \\#_1\]\backslash 1 \[x_2
    \\#_2\]\backslash \cdots 1 \[x_n \\#_n\]\backslash 1
    \backslash c \\# \rangle b\textrm'\)  
    \(= \textrm\`a \langle b \langle A_1' \rangle\backslash b
    \[A_1\]\backslash b \langle A_2' \rangle\backslash b
    \[A_2\]\backslash \cdots b \langle A_n' \rangle\backslash b
    \[A_n\]\backslash R_b \backslash c-1 \\# \rangle
    b\textrm'\);
    \(\textrm\` a \langle 0 \[x_1 \\#_1\]\backslash 1 \[x_2
    \\#_2\]\backslash \cdots 1 \[x_n \\#_n\]\backslash 1
    \backslash c \\# \rangle \backslash b\textrm'\)  
    \(= \textrm\`a \langle b \langle A_1' \rangle\backslash b
    \[A_1\]\backslash b \langle A_2' \rangle\backslash b
    \[A_2\]\backslash \cdots b \langle A_n' \rangle\backslash b
    \[A_n\]\backslash R_b \backslash c-1 \\# \rangle \backslash
    b\textrm'\).
-   **Rule A6**. Otherwise, \(\textrm\` a \langle c \\# \rangle b
    \textrm' = \textrm\` \underbrace{a \langle c-1 \\# \rangle b
    \[c \\#\] \cdots \[c \\#\] a \langle c-1 \\# \rangle b}_b
    \textrm'\) and \(\textrm\` a \langle c \\# \rangle
    \backslash b \textrm' = \textrm\` \underbrace{a \langle c-1
    \\# \rangle \backslash b \[c \\#\]\backslash \cdots \[c
    \\#\]\backslash a \langle c-1 \\# \rangle \backslash b}_b
    \textrm'\).

Limit: \(\{n,n\[1/2\]2\}\) has growth rate \(\Gamma_0\).

## Examples

\begin{eqnarray*} \{3 \langle 0 \backslash 2 \rangle 2\} &=& \{3
\langle R_2 \rangle 2\} \\ &=& \{3 \langle 2 \rangle 2\} \\
&=& \{3,3\[2\]3,3\} \\ &=&
\{3,\{3,\{3,\{3,\{3,3,3\[2\]\{3,\{3,\{3,\{3,\{3,3,3\[2\]\{3,\{\underbrace{3,\cdots,3}_{3\uparrow\uparrow\uparrow3}\},2\[2\]2\}\}\[2\]1,2\},2\[2\]1,2\}\[2\]2,3\}\[2\]2,2\},2\}\[2\]1,3\},2\[2\]1,3\}
\end{eqnarray*}

------------------------------------------------------------------------

\begin{eqnarray*} \{3 \langle 0 \[2\]\backslash 2 \rangle 2\} &=&
\{3 \langle 2 \backslash 2 \rangle 2\} \\ &=& \{3,3\[2\]3,3\[1
\backslash 2\]3,3\[2\]3,3\[2 \backslash 2\]3,3\[2\]3,3\[1 \backslash
2\]3,3\[2\]3,3\} \end{eqnarray*}

# Nested Hyper-Nested arrays

This part consists of 2 parts.

## Negations

-   **Rule A1**. \(\textrm\` a \langle 0 \neg \\# \rangle b
    \textrm' = \textrm\` a \textrm'\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle A
    \neg B \rangle 1 \textrm' = \textrm\` a \textrm'\).
-   **Rule A3**. If \(\[A\] < \[B\]\), \(\textrm\` a \langle
    \\# \[A\] 1 \[B\] \\#^* \neg \% \rangle b \textrm' =
    \textrm\` a \langle \\# \[B\] \\#^* \neg \% \rangle b
    \textrm'\).
-   **Rule A4**. If the first entry in the angle brackets is zero:
    \(\textrm\` a \langle 0 \[A_{1,1}\] 1 \[A_{1,2}\] \cdots
    \[A_{1,p_1}\] c_1 \\#_1 \neg \\#^* \rangle b \textrm' =
    \textrm\` a \langle S_1 \neg \\#^* \rangle b \textrm'\).
    Set i to 1.


-   *Rule A4a*. \(\[A_{i,p_i}\] = \[1 \neg 1 \[A_{i+1,1}\] 1
    \[A_{i+1,2}\] \cdots \[A_{i+1,p_{i+1}}\] c_i \\#_i\]\):

\(S_i = \textrm\` b \langle A_{i,1}' \rangle b \[A_{i,1}\] b
\langle A_{i,2}' \rangle b \[A_{i,2}\] \cdots \[A_{i,p_i-1}\] b
\langle b \neg S_{i+1} \rangle b \[A_{i,p_i}\] c_i \\#_i
\textrm'\). Increase i by 1 and follow Rules A4a\~d again.

-   *Rule A4b*. \(\[A_{i,p_i}\] = \backslash\):

\(S_i = \textrm\` R_b \textrm'\),

\(R_n = \textrm\` b \langle A_{i,1}' \rangle b \[A_{i,1}\] b
\langle A_{i,2}' \rangle b \[A_{i,2}\] \cdots \[A_{i,p_i-1}\] b
\langle R_{n-1} \rangle b \[A_{i,p_i}\] c_i-1 \\#_i
\textrm'\),

\(R_1 = \textrm\` 0 \textrm'\).

-   *Rule A4c*. Rule A4b don't apply, \(\[A_{i,p_i}\] = \[1 \neg k
    \\#_{i+1}\] (k>1)\):

\(S_i = \textrm\` b \langle A_{i,1}' \rangle b \[A_{i,1}\] b
\langle A_{i,2}' \rangle b \[A_{i,2}\] \cdots \[A_{i,p_i-1}\] b
\langle R_b \rangle b \[A_{i,p_i}\] c_i-1 \\#_i \textrm'\),

\(R_n = \textrm\` b \langle A_{i,1}' \rangle b \[A_{i,1}\] b
\langle A_{i,2}' \rangle b \[A_{i,2}\] \cdots \[A_{i,p_i-1}\] b
\langle R_{n-1} \rangle b \[A_{i,p_i}\] c_i-1 \\#_i \neg k-1
\\#_{i+1} \textrm'\),

\(R_1 = \textrm\` 0 \textrm'\).

-   *Rule A4d*. Otherwise:

\(S_i = \textrm\` b \langle A_{i,1}' \rangle b \[A_{i,1}\] b
\langle A_{i,2}' \rangle b \[A_{i,2}\] \cdots \[A_{i,p_i-1}\] b
\langle A_{i,p_i}' \rangle b \[A_{i,p_i}\] c_i-1 \\#_i
\textrm'\).

-   **Rule A5**. Otherwise, \(\textrm\` a \langle c \\# \neg
    \\#^* \rangle b \textrm' = \textrm\` \underbrace{a \langle
    c-1 \\# \neg \\#^* \rangle b \[c \\#\] \cdots \[c \\#\] a
    \langle c-1 \\# \neg \\#^* \rangle b}_b \textrm'\).

Note: \(\\#, \\#^*, and \%\) does not contain \(\neg\)s.

Limit: \(\{n,n\[1\[1\neg1\neg2\]2\]2\}\) has growth rate
\(\theta(\Omega^\Omega)\).

### Examples

\begin{eqnarray*} \{3 \langle 0 \[1 \neg 1 \backslash 2\] 2
\rangle 3\} &=& \{3 \langle 3 \langle 3 \neg
3,3\[2\]3,3\[3\]3,3\[2\]3,3 \rangle 3 \rangle 3\} \end{eqnarray*}

------------------------------------------------------------------------

\begin{eqnarray*} \{3 \langle 0 \[1 \neg 4\] 2 \rangle 3\} &=&
\{3 \langle 3 \langle 3 \langle 3 \neg 3 \rangle 3 \neg 3
\rangle 3 \rangle 3\} \end{eqnarray*}

## Hierarchal backslashes

-   **Rule A1**. \(\textrm\` a \langle 0 \backslash_n \\# \rangle
    b \textrm' = \textrm\` a \textrm', n>1\).
-   **Rule A2**. If \(b = 1\), we have \(\textrm\` a \langle \\#
    \rangle 1 \textrm' = \textrm\` a \textrm'\).
-   **Rule A3**. If \(\[A\] < \[B\]\), \(\textrm\` a \langle
    \\# \[A\] 1 \[B\] \\#^* \rangle b \textrm' = \textrm\` a
    \langle \\# \[B\] \\#^* \neg \% \rangle b \textrm'\).
-   **Rule A4**. If the first entry in the angle brackets is zero:
    \(\textrm\` a \langle 0 \[A_{1,1,1}\] 1 \[A_{1,1,2}\] \cdots
    \[A_{1,1,p_{1,1}}\] c_{1,1} \\#_{1,1} \backslash_n \\#^*
    \rangle b \textrm' = \textrm\` a \langle S_{1,1} \backslash_n
    \\#^* \rangle b \textrm', n>1\). Set i and j to 1.


-   *Rule A4a*. \(\[A_{i,1,p_{i,1}}\] = \backslash\):

\(S_{i,1} = \textrm\` R_b \textrm'\),

\(R_n = \textrm\` b \langle A_{i,1,1}' \rangle b \[A_{i,1,1}\] b
\langle A_{i,1,2}' \rangle b \[A_{i,1,2}\] \cdots
\[A_{i,1,p_{i,1}-1}\] b \langle R_{n-1} \rangle b
\[A_{i,1,p_{i,1}}\] c_{i,1}-1 \\#_{i,1} \textrm'\),

\(R_1 = \textrm\` 0 \textrm'\).

-   *Rule A4b*. \(\[A_{i,j,p_{i,1}}\] = \backslash_j, j>1\):

\(S_{i,j} = \textrm\` R_{b,j-1} \textrm'\),

\(R_{n,j-1}\)

\(= \textrm\` b \langle A_{i,j,1}' \rangle b \[A_{i,j,1}\] b
\langle A_{i,j,2}' \rangle b \[A_{i,j,2}\] \cdots b \langle
A_{i,j,p_{i,j}-1}' \rangle b \[A_{i,j,p_{i,j}-1}\] b \langle
A_{i,1,1}' \rangle b \[A_{i,1,1}\] b \langle A_{i,1,2}' \rangle b
\[A_{i,1,2}\] \cdots b \langle A_{i,1,p_{i,1}-1}' \rangle b
\[A_{i,1,p_{i,1}-1}\] b \langle R_{n-1,1} \rangle b
\[A_{i,1,p_{i,1}}\] c_{i,1}-1 \\#_{i,1} \backslash_j c_{i,j}-1
\\#_{i,j} \textrm'\),

\(R_{n,k} = \textrm\` b \langle A_{i,k+1,1}' \rangle b
\[A_{i,k+1,1}\] b \langle A_{i,k+1,2}' \rangle b \[A_{i,k+1,2}\]
\cdots b \langle A_{i,k+1,p_{i,k+1}-1}' \rangle b
\[A_{i,k+1,p_{i,k+1}-1}\] b \langle R_{n,k+1} \rangle b
\[A_{i,k+1,p_{i,k+1}}\] c_{i,k+1}-1 \\#_{i,k+1} \textrm'\)

\(R_{1,1} = \textrm\` 0 \textrm'\).

-   *Rule A4e*. Otherwise:

\(S_i = \textrm\` b \langle A_{i,1,1}' \rangle b \[A_{i,1,1}\] b
\langle A_{i,1,2}' \rangle b \[A_{i,1,2}\] \cdots
\[A_{i,1,p_{i,1}-1}\] b \langle A_{i,1,p_{i,1}}' \rangle b
\[A_{i,1,p_{i,1}}\] c_{i,1}-1 \\#_{i,1} \textrm'\).

-   **Rule A5**. Otherwise, \(\textrm\` a \langle c \\# \rangle b
    \textrm' = \textrm\` \underbrace{a \langle c-1 \\# \rangle b
    \[c \\#\] \cdots \[c \\#\] a \langle c-1 \\# \rangle b}_b
    \textrm'\).

# Hierarchal Hyper-Nested arrays

# Nested Hierarchal Hyper-Nested arrays


