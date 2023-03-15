---
title: Ackermann function
permalink: Ackermann_function
---











The Ackermann function, expressed as \\(A(a,b)\\), is a function for
expressing extremely large numbers.

## Defination

The Ackermann function is defined as follows:

\\begin{array}{l}
    A(0,b)=b+1 \\\\ 
    A(a,0)=A(a-1,1) \\\\ 
    A(a,b)=A(a-1,A(a,b-1))
\\end{array}

## Example

\\begin{eqnarray*} 
A(4,3) &=& A(3, A(4, 2)) \\\\ 
       &=& A(3, A(3, A(4, 1))) \\\\ 
       &=& A(3, A(3, A(3, A(4, 0)))) \\\\ 
       &=& A(3, A(3, A(3, A(3, 1)))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(3, 0))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(2, 1))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, A(2, 0)))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, A(1, 1)))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, A(0, A(1, 0))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, A(0, A(0, 1))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, A(0, 2)))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(1, 3))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(1, 2)))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(0, A(1, 1))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(0, A(0, A(1, 0)))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(0, A(0, A(0, 1)))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(0, A(0, 2))))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, A(0, 3)))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, A(0, 4))))) \\\\ 
       &=& A(3, A(3, A(3, A(2, 5)))) 
\\end{eqnarray*}

## Explicit formula

We now prove that \\(A(a, b) = 2 \uparrow^{a - 2} (b + 3) - 3\\) for \\(a>2\\).

\\begin{eqnarray*} 
A(0, b) &=& b + 1 \\\\ 
A(1, b) &=& A(0, A(1, b - 1)) \\\\ 
        &=& A(1, b - 1) + 1 \\\\ 
        &=& A(1, b - 2) + 2 \\\\ 
        &=& \cdots \\\\ 
        &=& A(1, b - b) + b \\\\ 
        &=& b + 2 \\\\ 
A(2, b) &=& A(1, A(2, b - 1)) \\\\ 
        &=& A(2, b - 1) + 2\\times 1 \\\\ 
        &=& A(2, b - 2) + 2\\times 2 \\\\ 
        &=& \cdots \\\\ 
        &=& A(2, b - b) + 2b \\\\ 
        &=& 2b + 3 \\\\ 
        &=& 2(b + 3) - 3 \\\\ 
A(3, b) &=& A(2, A(3, b - 1)) \\\\ 
        &=& 2(A(3, b - 1) + 3) - 3 \\\\ 
        &=& 2^2(A(3, b - 2) + 3) - 3 \\\\ 
        &=& \cdots \\\\ 
        &=& 2^b(A(3, 0) + 3) - 3 \\\\ 
        &=& 2^{b + 3} - 3
\\end{eqnarray*} 

Assuming that this holds true for \\(a=k\\), for \\(a=k+1\\):

\\begin{eqnarray*} 
A(k + 1, b) &=& A(k, A(k + 1, b - 1)) \\\\ 
            &=& 2 \uparrow^{k - 2} (A(k, A(k + 1, b - 2) + 3) - 3 \\\\ 
            &=& \cdots \\\\ 
            &=& \underbrace{2 \uparrow^{k - 2} 2 \uparrow^{k - 2} \cdots}_\text{b 2's} \uparrow^{k - 2} (A(k + 1, 0) + 3) - 3 \\\\ 
            &=& \underbrace{2 \uparrow^{k - 2} 2 \uparrow^{k - 2} \cdots \uparrow^{k - 2} 2 \uparrow^{k - 2} 2}_\text{b+3 2's} - 3 \\\\ 
            &=& 2 \uparrow^{k - 1} (b + 3) - 3
\\end{eqnarray*} 

QED.


