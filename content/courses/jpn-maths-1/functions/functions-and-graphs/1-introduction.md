---
title: "Introduction to Functions"
slug: introduction
description: "Definition of functions, domain and range."

date: 2021-03-27 22:36:21.268 +1100
lastMod: 2021-03-27 22:36:21.268 +1100

toc: true
type: docs
math: true
draft: false

tags:
  - functions
  - domain
  - range

menu:
  math1-func:
    name: Introduction
    parent: Functions and Graphs
    weight: 11

weight: 11
---

## Introduction

In this lesson, we will:

- Review the definition of mathematical functions.
- Evaluate a function at a given point.
- Find the domain of a function.
- Derive the range of a function given its domain.


## Functions

{{% mn %}}{{% img loc="sidenote" src="courses/jpn-maths-1/functions/function_machine2.svg" %}} The function acting as a 'black box'. Figure by [Wvbailey](https://en.wikipedia.org/wiki/Function_(mathematics)#/media/File:Function_machine2.svg) via Wikipedia. {{% /mn %}}
The word *function* comes from the Latin word meaning *to perform*. Following its name, a mathematical function *acts on* a number to do certain calculations. {{% sn 35 %}}Also, the traditional Chinese/Japanese translation of functions is "函数", which means *box numbers*. I think this translation encapsulates the nature of a function as a 'black box' so well!{{% /sn %}}

{{% box %}}

{{% note Definition %}} Suppose two variables $x$ and $y$. When the value of $x$ *uniquely* determines the value of $y$, $y$ is a *function* of $x$.

*Note.* The common notation for a function (of $x$) is $f(x)$. For example, the value of $y$ when $x=1$ is $f(1)$.

{{% /box %}}

Let me elaborate the above sentence a little more. Think a function as a hard-working robot. Each time you give the robot a number, it will return a number. Here are the two important properties it must have:

- it must not return more than one outputs for a single input.
- it must always return some output when given an input.

From the first property, we know that such robots are *consistent*. If a robot exchanges $2$ with $1$, it should *always* give you $1$ whenever you put a $2$ in. Functions are like that: $f(2)$ must always equal $f(2)$.

{{% box %}}

{{% note Example %}} The following are functions.

- $f(x) = 2x$
- $f(x)$ is the sign of $x$ (the sign function, $\text{sgn}(x)$).

The following are NOT functions.

- $f(x)$ is the outcome of throwing $x$ coins (the result changes every time).
- $f(x)$ is the square root of $x$ (there are two square roots for a single $x$).

{{% /box %}}

Let's practice some algebra now.

{{% box %}}

{{% note Example %}}

1. When $f(x) = 4x-3$, evaluate:
    1. $f\left(\dfrac{3}{2}\right)$
    2. $f(-2)$
    3. $f(a+2)$
2. When $g(x) = -3x^2+2x$, evaluate:
    1. $g(3a)$
    2. $g(a-2)$
    3. $g(a^2)$

{{% note Solution %}}

1. The key to evaluating functions is to substitute whatever is inside the bracket into $x$.
\begin{align}
  \text{a.} \quad f\left(\dfrac{3}{2}\right) &= 4\cdot \hl{\dfrac{3}{2}} - 3 \\\\
  &= 6 - 3 = \boldsymbol{ 3 }.
\end{align}
\begin{align}
  \text{b.} \quad f(-2) &= 4\cdot \hl{(-2)} - 3 \\\\
  &= -8-3 = \boldsymbol{ -11 }.
\end{align}
With $\text{(c)}$, substitute $x=a+2$ into $f(x)$:
\begin{align}
  \text{c.} \quad f(a+2) &= 4 \hl{(a+2)} - 3 \\\\
  &= 4a + 8 - 3 = \boldsymbol{ 4a - 5 }.
\end{align}

2. Likewise, we will substitute $x=3a$, $x=a-2$ and $x=a^2$, respectively. 
\begin{align}
  \text{a.} \quad g(3a) &= -3\hl{(3a)}^2+2\hl{(3a)} \\\\
  &= \boldsymbol{ -27a^2 + 6a }.
\end{align}
\begin{align}
  \text{b.} \quad g(a-2) &= -3\hl{(a-2)}^2+2\hl{(a-2)} \\\\
  &= -3(a^2 - 4a + 4) + 2a - 4 \\\\
  &= -3a^2 + 12a - 12 + 2a - 4 \\\\
  &= \boldsymbol{ -3a^2 + 14a - 16 }.
\end{align}
\begin{align}
  \text{c.} \quad g(a^2) &= -3\hl{\left(a^2\right)}^2+2\hl{\left(a^2\right)} \\\\
  &= \boldsymbol{ -3a^4 + 2a^2 }.
\end{align}

{{% /box %}}

{{% note Questions %}} Try [Practice Question](#practice-questions) 1.


## Domain and Range of a Function

### Domain

Do you remember I said a function must give an output? For some functions it is not a problem. For example, we can always calculate the square of any real numbers, so functions like $ f(x) = x^2 $ can easily satisfy this rule. However, functions like $$ g(x) = \sqrt{x} $$ cannot take negative numbers. This is why we need to *specify the set of inputs* for each function, which we call the *domain* of the function.

{{% box %}}

{{% note Definition %}} The *domain* of a function $f$ is the set of $x$ at which $f(x)$ is defined.

{{% note Example %}}
- The domain of $f(x) = x^2$ is the set of real numbers $\mathbb{R}$.
- The domain of $g(x) = \sqrt{x}$ is the set of non-negative real numbers: $\\{ x \\, | \\, x \in \mathbb{R}, x\ge 0 \\}.${{% sn 130 %}}Using the [interval notation](https://en.wikipedia.org/wiki/Interval_(mathematics)#Notations_for_intervals), you can also say the domain is $[0, \infty)${{% /sn %}}
- The domain of $h(x) = \dfrac{1}{x}$ is the set of real numbers except zero, $\mathbb{R}-\\{ 0 \\}$.

{{% /box %}}

The domains we listed above naturally follow from the nature of the functions. We call these domains as *natural domains*. We can also artificially limit the domain to be smaller than the function's natural domain.

{{% box %}}

{{% note Example %}} When the domain of $f(x) = 2x+1$ is $\mathbb{N}$, the possible values of $f(x)$ are $f(1) = 3$, $f(2) = 5$, $f(3) = 7$, and so on.

<p></p>

{{% /box %}}

### Range

The *range* of the function is the set of all outputs from a function, and the range depends on the choice of your domain!

{{% box %}}

{{% note Definition %}} The *range* of a function $f$ is the set of all $f(x)$.

{{% note Example %}}

- The range of $f(x) = x^2$ is the set of non-negative real numbers $\\{ x \\, | \\, x\ge 0 \\}.$
- The range of $g(x) = \dfrac{1}{x} + 3$ is the set of real numbers except $3$, $\mathbb{R}-\\{ 3 \\}$.
- The range of $h(x) = 2x+3,$ $0\le x \lt 5$ is $\\{ y \\, | \\, 3 \le y \lt 13 \\}.$

{{% /box %}}



## Practice Questions

1. When $f(x)=-3x+2$ and $g(x)=x^2-3x+2$, find:
    1. $f(0)$
    2. $f(-1)$
    3. $f(a+1)$
    4. $g(2)$
    5. $g(2a-1)$

{{% details title="Answer" %}}

1. 
    1. $2$
    2. $5$
    3. $-3a-1$
    4. $0$
    5. $4a^2 - 10a + 7$

{{% note Solution %}} 

\begin{align}
  \text{a.} \quad f(0) &= -3\cdot 0 + 2 = \boldsymbol{ 2 }.
\end{align}
\begin{align}
  \text{b.} \quad f(-1) &= -3\cdot (-1) + 2 = \boldsymbol{ 5 }.
\end{align}
\begin{align}
  \text{c.} \quad f(a+1) &= -3\cdot (a+1) + 2 \\\\
  &= -3a - 3 + 2 = \boldsymbol{ -3a - 1 }.
\end{align}
\begin{align}
  \text{d.} \quad g(2) &= 2^2 - 3\cdot 2 + 2 \\\\
  &= 4 - 6 + 2 = \boldsymbol{ 0 }.
\end{align}
\begin{align}
  \text{e.} \quad g(2a-1) &= (2a-1)^2 -3(2a-1) + 2 \\\\
  &= 4a^2 - 4a + 1 - 6a + 3 + 2 \\\\
  &= \boldsymbol{ 4a^2 -10a + 7 }.
\end{align}

{{% /details %}}

2. State the domain and range of $f(x) = \sqrt{x+4}$.

{{% details title="Answer" %}}

2. The domain is $x \ge -4$, and the range is $y \ge 0$.

{{% /details %}}

3. Find the range of the following functions.
    1. $y = 5x-2, \\, 0\le x\le 3$
    2. $y = -3x+1, \\, -1<x\le 2$

{{% details title="Answer" %}}

3. 
    1. $-2\le y \le 13$
    2. $-5\le y < 4$

{{% note Solution %}}

$\hspace{0.5em} \text{a.} \quad$ When $x=0$, $y = -2$, and when $x=3$, $y=13$. Because the domain includes both $0$ and $3$, the range is $\boldsymbol{ -2\le y \le 13 }$.

$\hspace{0.5em} \text{b.} \quad$ When $x=-1$, $y=4$, and when $x=2$, $y=-5$. Because the domain only includes $2$, the range is $\boldsymbol{ -5\le y < 4 }$.

{{% /details %}}