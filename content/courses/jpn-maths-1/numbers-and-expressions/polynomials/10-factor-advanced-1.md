---
title: "Advanced Techniques for Factorising 1"
description: "How to use substitution for factorising. How to factorise expressions quadratic in two variables, and bi-quartic polynomials."
slug: "advanced-factorising-1"

date: 2020-06-03 18:09:08 +1000
lastMod: 2020-12-13 07:54:54.499 +1100

type: docs
toc: true
math: true
draft: false

tags:
  - algebra
  - polynomial
  - factorisation

menu:
  math1:
    parent: Polynomials
    name: "Advanced Factorising 1"
    weight: 20

weight: 20
---

## Introduction

Now that we have all the basic tools for factorisation, we will look into a few different techniques for factorising polynomial expressions in this lesson.

## Factorising by Substitution

In the past, [we used substitution](../advanced-expanding/#expanding-by-substitution) to help expand complex expressions. The basic theory is the same: whenever you see similar parts, substitute them, and see if you can factorise the expression.

{{% hbox %}}
{{% note Example %}}
Factorise $2(x-1)^2 - 11(x-1) + 15$.

{{% note Solution %}} You can easily see $x-1$ is repeating. If we let $x-1=A$,

\begin{align*}
& 2(x-1)^2 - 11(x-1) + 15 \cr
& =2A^2 - 11A + 15.
\end{align*}

We can then use [the cross-multiplication method](../factorising-quadratic-identities/#general-cases) to factorise this expression:

$$ 2A^2 - 11A + 15 =  (2A-5)(A-3) \\\\[0.5em]
\rlap{\kern1.1em\raisebox{0.65em}{$\huge\times$} }
\begin{array}{rcrrr}
  2 && -5 & \rightarrow & -5 \\\\[0.7em]
  1 && -3 & \rightarrow & -6 \\\\[0.2em]
  \hline \\\\[-0.9em]
  &&&& \boldsymbol{ -11 }
\end{array}
$$

We cannot go any further, so we substitute $A=x-1$ back and complete the factorisation.

\begin{align*}
& (2A-5)(A-3) \cr
&=\left\\{ 2(x-1) - 5\right\\}\left\\{ (x-1) -3\right\\} \cr
&= \boldsymbol{ (2x-7)(x-4) .}
\end{align*}

{{% /hbox %}}

The example below is the classic "one step back, two steps forward" situation -- you sometimes need to expand the expression first before factorising it!

{{% hbox %}}
{{% note Example %}}
Factorise $(x^2 + x - 5)(x^2 + x - 7) + 1$.

{{% note Solution %}}
If we substitute $x^2 + x$ with $A$,
\begin{align*}
& (x^2 + x - 5)(x^2 + x - 7) + 1 \cr
&= (A-5)(A-7) + 1.
\end{align*}

We cannot factorise this as is, but what happens if we expand it first?
\begin{align*}
\dots &= A^2 - 12A + 35 + 1 \cr
&= A^2 - 12A + 36 \cr
&= (A-6)^2 \cr
&= (x^2 + x - 6)^2.
\end{align*}

We found a perfect square! Note that you can factorise $x^2 + x - 6$ further:
\begin{align*}
\dots &=\left\\{ (x-2)(x+3)\right\\}^2 \cr
&= \boldsymbol{ (x-2)^2(x+3)^2 }.
\end{align*}

{{% /hbox %}}

What if we cannot find any common parts? Look for the patterns first!

{{% hbox %}}
{{% note Example %}}
Factorise $x^2 - y^2 + 4y - 4$.

{{% note Solution %}}
The last three terms look quite like a perfect square, so we factorise them first.

\begin{align*}
& x^2 - y^2 + 4y - 4 \cr
&= x^2 \hl{ -(y^2 - 4y + 4) } \cr
&= x^2 - (y-2)^2.
\end{align*}

It looks like they are in $\square^2 - \triangle^2$ form, so we can apply one of the identities:

\begin{align*}
& x^2 - (\underline{y-2})^2 \cr
&= \{x+(\underline{y-2})\}\{x-(\underline{y-2})\} \cr
&= \boldsymbol{ (x+y-2)(x-y+2) }.
\end{align*}

{{% /hbox %}}

{{% hbox %}}

{{% note Example %}}
Factorise $(x+1)(x+2)(x+3)(x+4)-24$.

{{% note Solution %}}
Do you remember [this example](../advanced-expanding/#create-patterns-for-the-identities)? We grouped the terms so that we create a common part out of them. If we do that trick to this question,
\begin{align*}
& (x+1)(x+2)(x+3)(x+4)-24 \cr
&= \hl{ (x+1)(x+4) \times (x+2)(x+3) } - 24 \cr
&= (x^2 + 5x + 4) \times (x^2 + 5x + 6) - 24.
\end{align*}

We found a common part! Let's expand them first so that we can re-factorise with the extra constant term.
{{% mn 140 tips %}}
(1) $(\Box + 4)(\Box + 6)$ $= \Box^2 + 10\Box + 24$<br>
(2) $\Box^2 + 10\Box$ form
{{% /mn %}}
\begin{align*}
\dots &= \{ (\underline{x^2 + 5x}) + 4 \} \times \{ (\underline{x^2 + 5x}) + 6 \} - 24 \cr
&= (\underline{x^2 + 5x})^2 + 10(\underline{x^2 + 5x}) + 24 - 24 \tag{1} \cr
&= (x^2 + 5x)^2 + 10(x^2 + 5x) \cr
&= \hl{(x^2 + 5x)}(x^2 + 5x + 10) \tag{2} \cr
&= \boldsymbol{ x(x + 5)(x^2 + 5x + 10). }
\end{align*}

Always check if we can factorise any of the expressions further! Luckily, $x^2 + 5x + 10$ cannot be factorised anymore, so we stop here.

{{% /hbox %}}

{{% note Questions %}}
Try [Practice Questions](#practice-questions) 1 and 2 before moving on.

## Rearranging the Polynomials

Say we want to factorise a polynomial like this one, $$ x^3 - x^2y - xz^2 + yz^2. $$ We see [the degree of the polynomial](../terms-and-polynomials/#degree-of-a-polynomial) is 3 in $x$, 1 in $y$, and 2 in $z$, which means that $y$ is going to be the easiest to factorise. So we can try [rearranging the polynomial](../terms-and-polynomials/#arranging-polynomials) in terms of $y$ before factorisation!

{{% hbox %}}
{{% note Example %}}
Factorise $ x^3 - x^2y - xz^2 + yz^2 $.

{{% note Solution %}}
If we rearrange the polynomial in descending order in $y$,
{{% mn 170 tips %}}
(1) Rearranging in terms of $y$
{{% /mn %}}
\begin{align*}
& x^3 - x^2y - xz^2 + yz^2 \cr
&= (z^2-x^2)\hl{y} + x^3 - xz^2 \tag{1} \cr
&= (z^2-x^2)\hl{y} - x(z^2-x^2) \cr
&= (z^2-x^2)(y-x) \cr
&= (z+x)(z-x)(y-x) \cr
&= \boldsymbol{ (x-y)(x-z)(x+z) }.
\end{align*}

{{% /hbox %}}

{{% details title="Can't we substitute?" %}}
We certainly can! For the example above, you see a common factor of $(x-y)$:

\begin{align*}
& x^3 - x^2y - xz^2 + yz^2 \cr
&= x^2(\underline{x-y}) - z^2(\underline{x-y}) \cr
&= (x^2-z^2)(\underline{x-y}) \cr
&= \boldsymbol{ (x+z)(x-z)(x-y) }.
\end{align*}

In general, the more terms you are given to factorise, the easier it is to rearrange them first. However, it is up to you!

{{% /details %}}

This is another example.

{{% hbox %}}
{{% note Example %}}
Factorise $9b^2 + 3ab - 2a - 4$.

{{% note Solution %}}
The polynomial has degree of 1 in $a$ and 2 in $b$, so we rearrange it in terms of $a$.
\begin{align*}
& 9b^2 + 3ab - 2a - 4 \cr
&= (3b-2)\hl{a} + 9b^2 - 4 \cr
&= (3b-2)\hl{a} + (3b)^2 - 2^2 \cr
&= (\underline{3b-2})\hl{a} + (3b+2)(\underline{3b-2}) \cr
&= \boldsymbol{ (3b-2)(a+3b+2)}.
\end{align*}

{{% /hbox %}}

## Practice Questions

1. Factorise the following expressions.
    1. $6(2x+1)^2 + 5(2x+1)-4$
    2. $(x^2 - 2x)^2 - 11(x^2-2x) + 24$
    3. $(x^2-2x-16)(x^2-2x-14)+1$
    4. $(x+y+1)^4 - (x+y)^4$

{{% details title="Answer" %}}

1.  
    1. $(4x+1)(6x+7)$
    2. $(x+1)(x+2)(x-3)(x-4)$
    3. $(x-5)^2(x+3)^2$
    4. $(2x^2 + 4xy + 2y^2 + 2x + 2y + 1)(2x + 2y + 1)$

{{% note Solution %}}

{{% enum a %}} The common part we will substitute is $2x+1$.
{{% mn q1a tips %}}
(1) $A$ $=2x+1$<br>
(2)<br>
{{% img-raw src="courses/jpn-maths-1/numbers-and-expressions/poly-9q1a.JPG" alt="cross-multiplication" %}}
{{% /mn %}}

\begin{align*}
& 6(2x+1)^2 + 5(2x+1)-4 \cr
&= \hl{6A^2 + 5A - 4} \tag{1} \cr
&= (2A - 1)(3A + 4) \tag{2} \cr
&= \{ 2(2x+1) - 1 \}\{ 3(2x+1) + 4 \} \cr
&= \boldsymbol{ (4x+1)(6x+7) }.
\end{align*}

{{% enum b %}} The common part we will substitute is $x^2-2x$.
{{% mn q1b tips %}}
(3) $A=x^2-2x$
{{% /mn %}}

\begin{align*}
& (x^2 - 2x)^2 - 11(x^2-2x) + 24 \cr
&= \hl{A^2 - 11A + 24} \tag{3} \cr
&= (A-8)(A-3) \cr
&= (x^2-2x-8)\times(x^2-2x-3) \cr
&= (x+2)(x-4)\times(x-3)(x+1) \cr
&= \boldsymbol{ (x+1)(x+2)(x-3)(x-4) }.
\end{align*}

{{% enum c %}} The common part is $x^2-2x$, but it will make the calculation a little messy because we need to calculate $16 \times 14$. We will substitute $x^2-2x-14$ instead for convenience.
{{% mn q1c tips %}}
(4) $A=x^2-2x-14$
{{% /mn %}}

\begin{align*}
& (x^2-2x-16)(x^2-2x-14)+1 \cr
&= \hl{ (A-2)A+1 } \tag{4} \cr
&= A^2 - 2A + 1 \cr
&= (A-1)^2 \cr
&= (x^2-2x-15)^2 \cr
&= \{ (x-5)(x+3) \}^2 \cr
&= \boldsymbol{ (x-5)^2(x+3)^2 }.
\end{align*}

{{% enum d %}} We can group $x+y$.
{{% mn q1d tips %}}
(5) $A=x^2-2x-14$<br>
(6)(7) Identity 2: $a^2-b^2$ $=(a+b)(a-b)$
{{% /mn %}}

\begin{align*}
& (x+y+1)^4 - (x+y)^4 \cr
&= \hl{ (A+1)^4 - A^4 } \tag{5} \cr
&=\left\\{ (A+1)^2\right\\}^2 - \left(A^2 \right)^2 \cr
&=\left\\{ (A+1)^2 + A^2\right\\}\left\\{ (A+1)^2 - A^2\right\\} \tag{6} \cr
&=\left\\{ (A+1)^2 + A^2\right\\} \{ (A+1) + A \} \{ (A+1) - A \} \tag{7} \cr
&=\left\\{ (A+1)^2 + A^2\right\\} (2A+1) \cr
&= ( A^2 + 2A + 1 + A^2)(2A + 1) \cr
&= ( 2A^2 + 2A + 1)(2A + 1).
\end{align*}

From here, we will substitute $x+y$ back and see if we can factorise any further.

\begin{align*}
\dots &= \{ 2(x+y)^2 + 2(x+y) + 1 \} \{ 2(x+y) + 1 \} \cr
&= \boldsymbol{ (2x^2 + 4xy + 2y^2 + 2x + 2y + 1)(2x + 2y + 1) }.
\end{align*}

{{% /details %}}

2. Factorise the following expressions.
    1. $4x^2 - 9y^2 + 28x + 49$
    2. $a^2 + b^2 + ac - bc - 2ab$
    3. $(x+1)(x-5)(x^2-4x+6)+18$
    4. $(x-1)(x-3)(x-5)(x-7) - 9$

{{% details title="Answer" %}}

2. 
    1. $(2x+3y+7)(2x-3y+7) $
    2. $(a-b)(a-b+c)$
    3. $(x-2)^2(x^2-4x-3)$
    4. $(x^2-8x+10)(x-2)(x-6)$

{{% note Solution %}}

{{% enum a %}} We will complete the perfect square regarding $x$ first.
{{% mn q2a tips %}}
(1) Identity 1: $a^2+2ab+b^2$ $=(a+b)^2$<br>
(2) Identity 2: $a^2-b^2$ $=(a+b)(a-b)$
{{% /mn %}}

\begin{align*}
& 4x^2 - 9y^2 + 28x + 49 \cr
&= \hl{ 4x^2 + 28x + 49 } - 9y^2 \cr
&= (2x + 7)^2 - 9y^2 \tag{1} \cr
&= (2x+7)^2 - (3y)^2 \cr
&= \boldsymbol{ (2x+3y+7)(2x-3y+7)}. \tag{2}
\end{align*}

{{% enum b %}} If we complete the perfect square and factorise the rest, we can find another common factor $(x-y)$.
{{% mn q2b tips %}}
(3) Identity 1: $a^2-2ab+b^2$ $=(a-b)^2$
{{% /mn %}}

\begin{align*}
& a^2 + b^2 + ac - bc - 2ab \cr
&= \hl{ a^2 - 2ab + b^2 + ac - bc } \cr
&= (a-b)^2 + c(a-b) \tag{3} \cr
&= \boldsymbol{ (a-b)(a-b+c) .}
\end{align*}

{{% enum c %}} Multiply the left two brackets together and we can find the common factor $x^2 - 4x$.
{{% mn q2c tips %}}
(4) $A=$ $x^2-4x$<br>
(5) Identity 1: $a^2-2ab+b^2$ $=(a-b)^2$
{{% /mn %}}

\begin{align*}
& (x+1)(x-5)(x^2-4x+6)+18 \cr
&= \hl{ (x^2 - 4x - 5)}(x^2 - 4x + 6) + 18 \cr
&= (A-5)(A+6) + 18 \tag{4} \cr
&= A^2 + A - 30 + 18 \cr
&= A^2 + A - 12 \cr
&= (A+4)(A-3) \cr
&= (x^2-4x+4)(x^2-4x-3) \cr
&= \boldsymbol{ (x-2)^2(x^2-4x-3) .} \tag{5}
\end{align*}

{{% enum d %}} If swap the order of multiplication, we can find a common factor $x^2-8x$.
{{% mn q2d tips %}}
(6) $A=$ $x^2-8x+7$
{{% /mn %}}

\begin{align*}
& (x-1)(x-3)(x-5)(x-7) + 15 \cr
&= \hl{ (x-1)(x-7) \times (x-3)(x-5) } + 15 \cr
&= (x^2 - 8x + 7) \times (x^2-8x + 15) + 15 \cr
&= A(A+8) + 15 \tag{6} \cr
&= A^2 + 8A + 15 \cr
&= (A+3)(A+5) \cr
&= (x^2 - 8x + 10)(x^2 - 8x + 12) \cr
&= \boldsymbol{ (x^2-8x+10)(x-2)(x-6) }.
\end{align*}

{{% /details %}}

3. Factorise the following polynomials.
    1. $a^2 + ab + bc + ca$
    2. $x^2 - 2xy + 2y - 1$
    3. $a^3b + 16 - 4ab - 4a^2$
    4. $x^3y + x^2 - xyz^2 - z^2$

{{% details title="Answer" %}}

3. 
    1. $(a+c)(a+b)$
    2. $(x-1)(x-2y+1)$
    3. $(a+2)(a-2)(ab-4)$
    4. $(x+z)(x-z)(xy+1)$

{{% note Solution %}}

{{% enum a %}} We sort the polynomial in terms of $b$.

\begin{align*}
& a^2 + ab + bc + ca \cr
&= (a+c)\hl{b} + a^2 + ca \cr
&= (\underline{a+c})b + (\underline{a+c})a \cr
&= \boldsymbol{ (a+c)(a+b) .}
\end{align*}

{{% enum b %}} We sort the polynomial in terms of $y$.

\begin{align*}
& x^2 - 2xy + 2y - 1 \cr
&= (2-2x)\hl{y} + x^2 - 1 \cr
&= -2y(\underline{x-1}) + (x+1)(\underline{x-1}) \cr
&= \boldsymbol{ (x-1)(x-2y+1) .}
\end{align*}

{{% enum c %}} We sort the polynomial in terms of $b$.

\begin{align*}
& a^3b + 16 - 4ab - 4a^2 \cr
&= (a^3 - 4a)\hl{b} + 16 - 4a^2 \cr
&= (\underline{a^2-4})ab - 4(\underline{a^2-4}) \cr
&= (\underline{a^2-4})(ab-4) \cr
&= \boldsymbol{ (a+2)(a-2)(ab-4) .}
\end{align*}

{{% enum d %}} We sort the polynomial in terms of $y$.

\begin{align*}
& x^3y + x^2 - xyz^2 - z^2 \cr
& (x^3 - xz^2)\hl{y} + x^2 - z^2 \cr
&= (\underline{x^2 - z^2})xy + \underline{x^2 - z^2} \cr
&= (\underline{x^2 - z^2})(xy+1) \cr
&= \boldsymbol{ (x+z)(x-z)(xy+1) .}
\end{align*}

{{% /details %}}

4. Factorise the following.
    1. $x^2 + 2xy + 3x + 4y + 2$
    2. $a^3 + ab^2 + b^2 + 1$
    3. $6x^2 - yz + 2xz - 3xy$
    4. $3x^2 - 2z^2 + 4yz + 2xy + 5xz$

{{% details title="Answer" %}}

4. 
    1. $(x+2)(x+2y+1)$
    2. $(a+1)(a^2 + b^2 - a + 1)$
    3. $(2x-y)(3x+z)$
    4. $(x+2z)(3x+2y-z)$

{{% note Solution %}}

{{% enum a %}} We rearrange the polynomial in terms of $y$.

\begin{align*}
& x^2 + 2xy + 3x + 4y + 2 \cr
&= (2x+4)\hl{y} + x^2 + 3x + 2 \cr
&= 2y(\underline{x+2}) + (x+1)(\underline{x+2}) \cr
&= \boldsymbol{ (x+2)(x+2y+1) .}
\end{align*}

{{% enum b %}} We rearrange the polynomial in terms of $b$.
{{% mn q4b tips %}}
(1) Identity 5: $a^3 + b^3$ $= (a+b)(a^2 - ab + b^2)$
{{% /mn %}}

\begin{align*}
& a^3 + ab^2 + b^2 + 1 \cr
&= (a+1)\hl{b^2} + a^3 + 1 \tag{1} \cr
&= (a+1)b^2 + (a+1)(a^2 - a + 1) \cr
&= \boldsymbol{ (a+1)(a^2 + b^2 - a + 1) .}
\end{align*}

{{% enum c %}} We rearrange the polynomial in terms of $z$ (you can also choose $y$).

\begin{align*}
& 6x^2 - yz + 2xz - 3xy \cr
&= (2x-y)\hl{z} + 6x^2 - 3xy \cr
&= (\underline{2x-y})z + 3x(\underline{2x-y}) \cr
&= \boldsymbol{ (2x-y)(3x+z) .}
\end{align*}

{{% enum d %}} We rearrange the polynomial in terms of $y$.
{{% mn q4d tips %}}
(2)<br>
{{% img-raw src="courses/jpn-maths-1/numbers-and-expressions/poly-9q4d.JPG" alt="cross-multiplication" %}}
{{% /mn %}}

\begin{align*}
& 3x^2 - 2z^2 + 4yz + 2xy + 5xz \cr
&= (4z+2x)\hl{y} + 3x^2 + 5xz - 2z^2 \tag{2} \cr
&= 2y(\underline{x+2z}) + (3x-z)(\underline{x+2z}) \cr
&= \boldsymbol{ (x+2z)(3x+2y-z) .}
\end{align*}

{{% hr %}}

{{% /details %}}
