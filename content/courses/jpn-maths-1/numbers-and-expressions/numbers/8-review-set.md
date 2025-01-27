---
title: "Review: Absolute Values and Roots"
slug: review-3
description: Review questions for absolute values and square roots.

date: 2020-08-31 21:07:32.960 +1000
lastMod: 2020-12-19 19:55:30.013 +1100

type: docs
toc: false
math: true
draft: false

tags:
  - real number
  - square root
  - absolute value
  - algebra

menu:
  math1:
    parent: Real Numbers
    name: ✏️ Review 3
    weight: 18

weight: 18
---

1. Express the value of $0.\dot{1}\dot{2} \times 0.\dot{2}\dot{7}$ as a simplified fraction. {{% mn ref1 refs %}}From Shinshu Univ.{{% /mn %}}

{{% details title="Answer" %}}
1. $\dfrac{4}{121}$

{{% note Solution %}}
{{% mn 36 %}}Refer to [Converting decimals to fractions](../types-of-numbers/#converting-decimals-to-fractions) for more help.{{% /mn %}}If we set $x=0.\dot{1}\dot{2}$, $100x=12.\dot{1}\dot{2}$ and then

$$\begin{array}{rrll}
  & 100x & = 12.1212 \cdots & \\\\[0.2em]
 -(& x & = \phantom{0}0.1212 \cdots & ) \\\\[0.2em]
  \hline \\\\[-0.9em]
  & 99x & = 12. &&
\end{array}$$

Thus $x=\dfrac{12}{99} = \dfrac{4}{33}$.

Likewise, if we set $y=0.\dot{2}\dot{7}$, $100y=27.\dot{2}\dot{7}$ and

$$\begin{array}{rrll}
  & 100y & = 27.2727\cdots & \\\\[0.2em]
 -(& y & = \phantom{0}0.2727\cdots & ) \\\\[0.2em]
  \hline \\\\[-0.9em]
  & 99y & = 27. &&
\end{array}$$

Thus $y=\dfrac{27}{99} = \dfrac{3}{11}$. Therefore

$$
  0.\dot{1}\dot{2} \times 0.\dot{2}\dot{7} = \frac{4}{\bcancel{33}^{11}} \times \frac{\bcancel{3}}{11} = \boldsymbol{ \frac{4}{121}. }
$$

{{% /details %}}

2. Find the values of the following expressions, without using a calculator.
    1. $\sqrt{1.21}$
    2. $\sqrt{0.0256}$
    3. $\dfrac{\sqrt{12}\sqrt{20}}{\sqrt{15}}$

{{% details title="Answer" %}}
2. 
    1. $1.1$
    2. $0.16$
    3. $4$

{{% note Solution %}}
Use the [basic properties of square roots](../square-roots/#basic-identities-of-square-roots).

{{% enum a %}}
{{% mn q2a tips %}}
(1) $\sqrt{\dfrac{a}{b}}$ $=\dfrac{\sqrt{a}}{\sqrt{b}}$
{{% /mn %}}
\begin{align*}
  \sqrt{1.21} &= \sqrt{\frac{121}{100}} \tag{1} \cr
  &= \frac{11}{10} = \boldsymbol{ 1.1. }
\end{align*}
{{% enum b %}}
\begin{align*}
  \sqrt{0.0256} &= \sqrt{\frac{256}{10000}} \cr
  &= \frac{16}{100} = \boldsymbol{ 0.16. }
\end{align*}
{{% enum c %}}
\begin{align*}
  \frac{\sqrt{12}\sqrt{20}}{\sqrt{15}} &= \sqrt{\frac{12\cdot \bcancel{20}^4}{\bcancel{15}^3}} \cr
  &= \sqrt{\frac{\bcancel{12}^4 \cdot 4}{\bcancel{3}}} \cr
  &= \sqrt{4^2} = \boldsymbol{ 4. }
\end{align*}

{{% /details %}}

3. When $a\gt 0, b\lt 0, c\lt 0$, simplify:
    1. $\sqrt{4a^2} + \sqrt{b^2}$
    2. $\sqrt{(a^2bc^3)^3}$

{{% details title="Answer" %}}
3. 
    1. $2a - b$
    2. $-a^3bc^4 \sqrt{bc}$

{{% note Solution %}}
{{% mn 105 %}}Refer to [Square root of a polynomial](../removing-roots-2/#square-root-of-a-polynomial) for more help.{{% /mn %}}Think carefully whether the expressions are positive or negative. Remember, $\sqrt{a^2}$ is *not* equal to $a$, but $|a|$.

{{% enum a %}}
{{% mn q3a tips %}}
(1) Because $a>0$ and $b<0$, $|2a|=2a$ and $|b|=-b$.
{{% /mn %}}
\begin{alignat*}{2}
  &\sqrt{4a^2} + \sqrt{b^2} \cr
  &= \sqrt{(2a)^2} + \sqrt{b^2} \cr
  &= |2a| + |b| \cr
  &= \boldsymbol{ 2a - b. } \tag{1}
\end{alignat*}
{{% enum b %}}
{{% mn q3b tips %}}
(2) Because $a$ is positive and $b, c$ are negative, $a^3bc^4$ has five negative numbers ($bc^4$) multiplied, and hence is negative.
{{% /mn %}}
\begin{alignat*}{2}
  &\sqrt{(a^2bc^3)^3} \cr
  &= \sqrt{a^6b^3c^9} \cr
  &= \sqrt{\left(a^3bc^4\right)^2\cdot bc} \cr
  &= \boldsymbol{ -a^3bc^4 \sqrt{bc} . } \tag{2}
\end{alignat*}

{{% /details %}}

4. The following 'proves' that $8=-8$. Find where the error occurred, and explain why. {{% mn ref4 refs %}}From Miyazaki Univ.{{% /mn %}}
\begin{align*}
  8 &= \sqrt{64} = \sqrt{2^6} = \sqrt{(-2)^6} \cr
  &= \sqrt{\left\\{ (-2)^3\right\\}^2 } = (-2)^3 = -8.
\end{align*}

{{% details title="Answer" %}}

4. $\sqrt{\left\\{ (-2)^3\right\\}^2 }=(-2)^3$ is wrong, because $(-2)^3=-8$ is a negative number. The correct answer is 

\begin{align*}
  \sqrt{\{ (-2)^3 \}^2 } = \sqrt{(-8)^2} = \hl{|-8|} = 8.
\end{align*}

{{% /details %}}

5. Calculate the following expressions.
    1. $\sqrt{200}+\sqrt{98}-3\sqrt{72}$
    2. $\sqrt{48}-\sqrt{27}+5\sqrt{12}$
    3. $\big(1+\sqrt{3}\big)^3$
    4. $\big(2\sqrt{6}+\sqrt{3}\big)\big(\sqrt{6}-4\sqrt{3}\big)$
    5. $\big(1-\sqrt{7}+\sqrt{3}\big)\big(1+\sqrt{7}+\sqrt{3}\big)$
    6. $\big(\sqrt{2}-2\sqrt{3}-3\sqrt{6}\big)^2$

{{% details title="Answer" %}}
5. 
    1. $-\sqrt{2}$
    2. $11\sqrt{3}$
    3. $10 + 6\sqrt{3}$
    4. $-21\sqrt{2}$
    5. $2\sqrt{3} - 3$
    6. $68 + 36\sqrt{2} - 12\sqrt{3} - 4\sqrt{6}$

{{% note Solution %}}
Use the [basic identities of square roots](../square-roots/#basic-identities-of-square-roots) and [polynomial identities](../../polynomials/expanding-identities/) to simplify the expressions.

{{% enum a %}}
{{% mn q5a tips %}}
(1) Use the identity that $\sqrt{a^2x} = a\sqrt{x}$ when $a$ is positive.
{{% /mn %}}
\begin{align*}
  \sqrt{200}+\sqrt{98}-3\sqrt{72} &= \sqrt{2\cdot 10^2} + \sqrt{2 \cdot 7^2} - 3\sqrt{2 \cdot 6^2} \tag{1} \cr
  &= 10\sqrt{2} + 7\sqrt{2} - 18\sqrt{2} \cr
  &= \boldsymbol{ -\sqrt{2}. }
\end{align*}
{{% enum b %}}
{{% mn q5b tips %}}
(2) Use the identity that $\sqrt{a^2x} = a\sqrt{x}$ when $a$ is positive.
{{% /mn %}}
\begin{align*}
  \sqrt{48}-\sqrt{27}+5\sqrt{12} &= \sqrt{3 \cdot 4^2} - \sqrt{3\cdot 3^2} + 5\sqrt{3 \cdot 2^2} \tag{2} \cr
  &= 4\sqrt{3} - 3\sqrt{3} + 10\sqrt{3} \cr
  &= \boldsymbol{ 11\sqrt{3}. }
\end{align*}
{{% enum c %}}
{{% mn q5c tips %}}
(3) Polynomial identity 5: $(a+b)^3$ $= a^3 + 3a^2b + 3ab^2 + b^3$
{{% /mn %}}
\begin{align*}
  \big(1+\sqrt{3}\big)^3 &= 1 + 3\sqrt{3} + 3\sqrt{3}^2 + \sqrt{3}^3 \tag{3} \cr
  &= 1 + 3\sqrt{3} + 3\cdot 3 + 3\sqrt{3} \cr
  &= \boldsymbol{ 10 + 6\sqrt{3}. }
\end{align*}
{{% enum d %}}
{{% mn q5d tips %}}
(4) Polynomial identity 3: $(ax+b)(cx+d)$ $=acx^2 + (ad+bc)x + bd$
{{% /mn %}}
\begin{align*}
  \big(2\sqrt{6}+\sqrt{3}\big)\big(\sqrt{6}-4\sqrt{3}\big) &= 2\cdot 6 + (-8+1)\sqrt{3}\sqrt{6} - 4\cdot 3 \tag{4} \cr
  &= 12 - 7\sqrt{18} - 12 \cr
  &= -7\sqrt{18} \cr
  &= \boldsymbol{ -21\sqrt{2}. }
\end{align*}

***Alternative solution.*** You can factorise $\sqrt{3}$ first to make the calculation bit easier:
\begin{align*}
  \big(2\sqrt{6}+\sqrt{3}\big)\big(\sqrt{6}-4\sqrt{3}\big) &= \sqrt{3}\big(2\sqrt{2}+1\big)\times \sqrt{3}\big(\sqrt{2}-4\big) \cr
  &= 3\big(2\sqrt{2}+1\big)\big(\sqrt{2}-4\big) \cr
  &= 3\big(2\cdot 2 - 7\sqrt{2} - 4\big) \cr
  &= 3\cdot \big(-7\sqrt{2}\big) \cr
  &= \boldsymbol{ -21\sqrt{2}. }
\end{align*}

{{% enum e %}}
{{% mn q5e tips %}}
(5) $(A+B)(A-B)$ form
{{% /mn %}}
\begin{align*}
  & \big(1-\sqrt{7}+\sqrt{3}\big)\big(1+\sqrt{7}+\sqrt{3}\big) \cr
  &= \big\\{ \big(1+\sqrt{3}\big) - \sqrt{7} \big\\}\big\\{ \big(1+\sqrt{3}\big) + \sqrt{7} \big\\} \tag{5}\\
  &= \big(1+\sqrt{3}\big)^2 - 7 \cr
  &= 1 + 2\sqrt{3} + 3 - 7 \cr
  &= \boldsymbol{ 2\sqrt{3} - 3 .}
\end{align*}

{{% enum f %}}
{{% mn q5f tips %}}
(6) $(a+b+c)^2$ $= a^2+b^2+c^2$ $+$ $2ab+2bc+2ca$
{{% /mn %}}
\begin{align*}
  & \big(\sqrt{2}-2\sqrt{3}-3\sqrt{6}\big)^2 \cr
  &= \sqrt{2}^2 + \big(-2\sqrt{3}\big)^2 + \big(-3\sqrt{6}\big)^2 \cr
  &\phantom{=}+ 2\sqrt{2}\cdot\big(-2\sqrt{3}\big) + 2\big(-2\sqrt{3}\big)\cdot\big(-3\sqrt{6}\big) + 2\big(-3\sqrt{6}\big)\cdot\sqrt{2} \tag{6} \cr
  &= 2 + 12 + 54 -4\sqrt{6} + 12\sqrt{18} -6\sqrt{12} \cr
  &= \boldsymbol{ 68 - 4\sqrt{6} + 36\sqrt{2} - 12\sqrt{3}. }
\end{align*}

{{% /details %}}

6. Rationalise the denominators and simplify the fractions.
    1. $\dfrac{1}{\sqrt{3}-\sqrt{5}}$
    2. $\dfrac{\sqrt{3}}{1+\sqrt{6}}-\dfrac{\sqrt{2}}{4+\sqrt{6}}$
    3. $\dfrac{1}{\sqrt{2}+1}+\dfrac{1}{\sqrt{3}+\sqrt{2}}+\dfrac{1}{\sqrt{4}+\sqrt{3}}+\dfrac{1}{\sqrt{5}+\sqrt{4}}$
    4. $\dfrac{1}{\sqrt{2}+\sqrt{3}+\sqrt{5}}+\dfrac{1}{\sqrt{2}-\sqrt{3}-\sqrt{5}}$

{{% details title="Answer" %}}
6. 
    1. $-\dfrac{\sqrt{3}+\sqrt{5}}{2}$
    2. $\dfrac{\sqrt{2}}{5}$
    3. $\sqrt{5}-1$
    4. $\dfrac{ 3\sqrt{2}-\sqrt{30}}{6}$

{{% note Solution %}}
Use different [rationalising strategies](../removing-roots-1/#rationalising-the-denominators) to remove the square roots in the denominators.

{{% enum a %}}
{{% mn q6a tips %}}
(1) Note the end result is negative, because $\sqrt{3}-\sqrt{5}$ is negative.
{{% /mn %}}
\begin{align*}
  \frac{1}{\sqrt{3}-\sqrt{5}} &= \frac{\big(\sqrt{3}+\sqrt{5}\big)}{\big(\sqrt{3}-\sqrt{5}\big)\big(\sqrt{3}+\sqrt{5}\big)} \cr
  &= \frac{\sqrt{3}+\sqrt{5}}{3-5} \cr
  &= \boldsymbol{ -\frac{\sqrt{3}+\sqrt{5}}{2} . } \tag{1}
\end{align*}
{{% enum b %}}
{{% mn q6b tips %}}
(2) We multiply the first fraction with $\sqrt{6}-1$ instead of $1-\sqrt{6}$, which is negative.
{{% /mn %}}
\begin{align*}
  & \dfrac{\sqrt{3}}{1+\sqrt{6}}-\dfrac{\sqrt{2}}{4+\sqrt{6}} \cr
  &= \dfrac{\sqrt{3}\big(\sqrt{6}-1\big)}{\big(\sqrt{6}+1\big)\big(\sqrt{6}-1\big)}-\dfrac{\sqrt{2}\big(4-\sqrt{6}\big)}{\big(4+\sqrt{6}\big)\big(4-\sqrt{6}\big)} \tag{2} \cr
  &= \dfrac{\sqrt{18}-\sqrt{3}}{6-1} - \dfrac{4\sqrt{2} - \sqrt{12}}{16-6} \cr
  &= \dfrac{3\sqrt{2}-\sqrt{3}}{5} - \dfrac{4\sqrt{2} - 2\sqrt{3}}{10} \cr
  &= \dfrac{6\sqrt{2}-2\sqrt{3}}{10} + \dfrac{-4\sqrt{2} + 2\sqrt{3}}{10} \cr
  &= \dfrac{2\sqrt{2}}{10} \cr
  &= \boldsymbol{ \dfrac{\sqrt{2}}{5}. }
\end{align*}
{{% enum c %}}
{{% mn q6c tips %}}
(3) First rationalise the denominators.
{{% /mn %}}
\begin{align*}
  & \dfrac{1}{\sqrt{2}+1}+\dfrac{1}{\sqrt{3}+\sqrt{2}}+\dfrac{1}{\sqrt{4}+\sqrt{3}}+\dfrac{1}{\sqrt{5}+\sqrt{4}} \tag{3} \cr
  &= \big(\sqrt{2}-1\big) + \big(\sqrt{3}-\sqrt{2}\big) + \big(\sqrt{4}-\sqrt{3}\big) + \big(\sqrt{5}-\sqrt{4}\big) \cr
  &= \boldsymbol{ \sqrt{5}-1. }
\end{align*}

{{% enum d %}} We can rationalise each fraction and combine the result. Note that because $\sqrt{2}^2+\sqrt{3}^2=\sqrt{5}^2$, it is more convenient to split the square roots as $(\sqrt{2}+\sqrt{3})$ and $\sqrt{5}$.

\begin{align*}
  \dfrac{1}{\big(\sqrt{2}+\sqrt{3}\big)+\sqrt{5}}
  &= \dfrac{\big(\sqrt{2}+\sqrt{3}\big)-\sqrt{5}}{\big\\{\big(\sqrt{2}+\sqrt{3}\big)+\sqrt{5}\big\\}\big\\{\big(\sqrt{2}+\sqrt{3}\big)-\sqrt{5}\big\\}} \cr
  &= \dfrac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{\big(\sqrt{2}+\sqrt{3}\big)^2 - 5} \cr
  &= \dfrac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{2 + 2\sqrt{6} + 3 - 5} \cr
  &= \dfrac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}},
\end{align*}

\begin{align*}
  \dfrac{1}{\big(\sqrt{2}-\sqrt{3}\big)-\sqrt{5}}
  &= \dfrac{\big(\sqrt{2}-\sqrt{3}\big)+\sqrt{5}}{\big\\{\big(\sqrt{2}-\sqrt{3}\big)-\sqrt{5}\big\\}\big\\{\big(\sqrt{2}-\sqrt{3}\big)+\sqrt{5}\big\\}} \cr
  &= \dfrac{\sqrt{2}-\sqrt{3}+\sqrt{5}}{\big(\sqrt{2}-\sqrt{3}\big)^2 - 5} \cr
  &= \dfrac{\sqrt{2}-\sqrt{3}+\sqrt{5}}{2 - 2\sqrt{6} + 3 - 5} \cr
  &= \dfrac{\sqrt{2}-\sqrt{3}+\sqrt{5}}{-2\sqrt{6}} \cr
  &= \dfrac{-\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}}.
\end{align*}

Then
{{% mn q6d tips %}}
(4) Rationalise the denominator.
{{% /mn %}}
\begin{align*}
  & \dfrac{1}{\sqrt{2}+\sqrt{3}+\sqrt{5}}+\dfrac{1}{\sqrt{2}-\sqrt{3}-\sqrt{5}} \cr
  &= \dfrac{\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}} + \dfrac{-\sqrt{2}+\sqrt{3}-\sqrt{5}}{2\sqrt{6}} \cr
  &= \dfrac{2\sqrt{3}-2\sqrt{5}}{2\sqrt{6}} \cr
  &= \dfrac{\sqrt{3}-\sqrt{5}}{\sqrt{6}} \cr
  &= \dfrac{\sqrt{18}-\sqrt{30}}{6} \tag{4} \cr
  &= \boldsymbol{ \dfrac{3\sqrt{2}-\sqrt{30}}{6}. }
\end{align*}

***Alternative solution.***
{{% mn q6d2 tips %}}
(5) Reduce the fractions to the common denominator, and add them together.<br>
(6) Rationalise the denominator.
{{% /mn %}}
\begin{align*}
  & \dfrac{1}{\sqrt{2}+\big(\sqrt{3}+\sqrt{5}\big)}+\dfrac{1}{\sqrt{2}-\sqrt{3}-\sqrt{5}} \cr
  &= \dfrac{1}{\hl{\sqrt{2}+\big(\sqrt{3}+\sqrt{5}\big)}}+\dfrac{1}{\hl{\sqrt{2}-\big(\sqrt{3}+\sqrt{5}\big)}} \cr
  &= \dfrac{\sqrt{2}-\big(\sqrt{3}+\sqrt{5}\big)}{\big\\{\sqrt{2}+\big(\sqrt{3}+\sqrt{5}\big)\big\\}\big\\{\sqrt{2}-\big(\sqrt{3}+\sqrt{5}\big)\big\\}} \cr
  &\phantom{=}+\dfrac{\sqrt{2}+\big(\sqrt{3}+\sqrt{5}\big)}{\big\\{\sqrt{2}-\big(\sqrt{3}+\sqrt{5}\big)\big\\}\big\\{\sqrt{2}+\big(\sqrt{3}+\sqrt{5}\big)\big\\}} \tag{5} \cr
  &= \dfrac{2\sqrt{2}}{\sqrt{2}^2-\big(\sqrt{3}+\sqrt{5}\big)^2} \cr
  &= \dfrac{2\sqrt{2}}{2 - 3 - 2\sqrt{15} - 5} \cr
  &= \dfrac{2\sqrt{2}}{-6-2\sqrt{15}} \cr
  &= \dfrac{-\sqrt{2}}{3+\sqrt{15}} \cr
  &= \dfrac{-\sqrt{2}\big(\sqrt{15}-3\big)}{\big(3+\sqrt{15}\big)\big(\sqrt{15}-3\big)} \tag{6} \cr
  &= \dfrac{-\sqrt{30}+3\sqrt{2}}{15-9} \cr
  &= \boldsymbol{ \dfrac{ 3\sqrt{2}-\sqrt{30}}{6}. }
\end{align*}

{{% /details %}}

7. When $A=\sqrt{x^2-6x+9}-\sqrt{x^2+6x+9}$, find all possible values of $A$.

{{% details title="Answer" %}}

7. $$
A=\begin{cases}
6, & \text{when $x<-3$,} \cr
-2x, & \text{when $-3\le x<3$,} \cr
-6, & \text{when $x\ge 3$.}
\end{cases}
$$

{{% note Solution %}}
{{% mn 362 %}} See [Square root of a polynomial](../removing-roots-2/#square-root-of-a-polynomial) for more help.{{% /mn %}}
Let's complete the square first:

\begin{align*}
  A &= \sqrt{x^2-6x+9}-\sqrt{x^2+6x+9} \cr
  &= \sqrt{(x-3)^2}-\sqrt{(x+3)^2} \cr
  &= |x-3| - |x+3|. 
\end{align*}

We can see, the value of $A$ would change when the signs of $x-3$ or $x+3$ change.
  - When $x\ge 3$, both $x-3$ and $x+3$ are positive, and $$ A = x-3 - (x+3) = \boldsymbol{ -6. } $$
  - When $-3\le x<3$, $x-3$ is negative but $x+3$ is positive, and $$ A = -(x-3) - (x+3) = \boldsymbol{ -2x. } $$
  - When $x<-3$, both $x-3$ and $x+3$ are negative, and $$ A = -(x-3) + (x+3) = \boldsymbol{ 6. } $$

{{% /details %}}


8. Solve the double square roots and simplify the expressions. {{% mn ref8 refs %}}a. From Tokyo Univ. of Marine Science and Technology.<br>b. From Polytechnic Univ.<br>c. From Tokyo Denki Univ.{{% /mn %}}
    1. $\sqrt{11+4\sqrt{6}}$
    2. $\dfrac{1}{\sqrt{7-4\sqrt{3}}}$
    3. $\sqrt{3+\sqrt{5}}+\sqrt{3-\sqrt{5}}$

{{% details title="Answer" %}}
8. 
    1. $2\sqrt{2} + \sqrt{3}$
    2. $2+\sqrt{3}$
    3. $\sqrt{10}$

{{% note Solution %}}
Refer to [Double square roots](../removing-roots-2/#double-square-roots) for more help.

{{% enum a %}}
{{% mn q8a tips %}}
(1) $4\sqrt{6}$ $=2\cdot 2\sqrt{6}$ $=2\cdot\sqrt{2^2\cdot 6}$ $=2\sqrt{24}$<br>
(2) $a + b + 2\sqrt{ab}$ $=\big(\sqrt{a}+\sqrt{b}\big)^2$
{{% /mn %}}
\begin{align*}
  \textstyle\sqrt{11+4\sqrt{6}} &= \textstyle\sqrt{11+2\sqrt{24}} \tag{1} \cr
  &= \textstyle\sqrt{8 + 3 + 2\sqrt{8}\sqrt{3}} \cr
  &= \textstyle\sqrt{\big(\sqrt{8}+\sqrt{3}\big)^2} \tag{2} \cr
  &= \sqrt{8} + \sqrt{3} \cr
  &= \boldsymbol{ 2\sqrt{2} + \sqrt{3}. }
\end{align*}

{{% enum b %}} The denominator of the expression is
{{% mn q8b tips %}}
(3) $4\sqrt{3}$ $=2\cdot 2\sqrt{3}$ $=2\cdot\sqrt{2^2\cdot 3}$ $=2\sqrt{12}$<br>
(4) This is ***not*** equal to $\sqrt{3}-\sqrt{4}$, which is a negative number.
{{% /mn %}}

\begin{align*}
  \textstyle\sqrt{7-4\sqrt{3}} &= \textstyle\sqrt{7-2\sqrt{12}} \tag{3} \cr
  &= \textstyle\sqrt{3 + 4 - 2\sqrt{3}\sqrt{4}} \cr
  &= \textstyle\sqrt{\big(\sqrt{4}-\sqrt{3}\big)^2} \cr
  &= \sqrt{4}-\sqrt{3} \tag{4} \cr
  &= 2 - \sqrt{3}.
\end{align*}

Therefore
{{% mn q8b2 tips %}}
(5) Rationalising the denominator.
{{% /mn %}}
\begin{align*}
  \dfrac{1}{\sqrt{7-4\sqrt{3}}} &= \dfrac{1}{2-\sqrt{3}} \cr
  &= \dfrac{2+\sqrt{3}}{4-3} \tag{5} \cr
  &= \boldsymbol{ 2+\sqrt{3}. }
\end{align*}

{{% enum c %}} We will multiply and divide the double square roots by $\sqrt{2}$ to complete the square:
{{% mn q8c tips %}}
(6) Note that $\sqrt{\smash{(\sqrt{1}-\sqrt{5})^2}\vphantom{\sqrt{5}}}$ does ***not*** equal $1-\sqrt{5}$, which is negative.
{{% /mn %}}

\begin{align*}
  & \textstyle\sqrt{3+\sqrt{5}}+\textstyle\sqrt{3-\sqrt{5}} \cr
  &= \hl{\dfrac{\sqrt{6+2\sqrt{5}}}{\sqrt{2}}}+\hl{\dfrac{\sqrt{6-2\sqrt{5}}}{\sqrt{2}}} \cr
  &= \dfrac{\sqrt{1+5+2\sqrt{\smash{1}\vphantom{5}}\sqrt{5}}}{\sqrt{2}}+\dfrac{\sqrt{1+5-2\sqrt{\smash{1}\vphantom{5}}\sqrt{5}}}{\sqrt{2}} \cr
  &= \dfrac{1+\sqrt{5}}{\sqrt{2}} + \dfrac{\hl{\sqrt{5}-1}}{\sqrt{2}} \tag{6} \cr
  &= \dfrac{2\sqrt{5}}{\sqrt{2}} \cr
  &= \dfrac{2\sqrt{10}}{2} \cr
  &= \boldsymbol{ \sqrt{10}. }
\end{align*}

{{% /details %}}

9. Simplify the following expressions. {{% mn ref9 refs %}}a. From Osaka Sangyo Univ.<br>b. From Hokkaido College of Pharmacy.{{% /mn %}}
    1. $\sqrt{9+4\sqrt{4+2\sqrt{3}}}$
    2. $\sqrt{7-\sqrt{21+\sqrt{80}}}$

{{% details title="Answer" %}}
9. 
    1. $1+2\sqrt{3}$
    2. $2$

{{% note Solution %}}
First remove the inner square root, and then try removing the outer one.

{{% enum a %}}
{{% mn q9a tips %}}
(1) $\sqrt{12}$ $=\sqrt{2^2\cdot 3}$ $=2\sqrt{3}$
{{% /mn %}}
\begin{align*}
  &\textstyle\sqrt{9+4\sqrt{4+2\sqrt{3}}} \cr
  &= \textstyle\sqrt{9+4\sqrt{1+3+2\sqrt{\smash{1}\vphantom{3}}\sqrt{3}}} \cr
  &= \textstyle\sqrt{9+4\sqrt{\big(1+\sqrt{3}\big)^2}} \cr
  &= \textstyle\sqrt{9+4\big(1+\sqrt{3}\big)} \cr
  &= \textstyle\sqrt{13+4\sqrt{3}} \cr
  &= \textstyle\sqrt{13+2\sqrt{12}} \tag{1} \cr
  &= \textstyle\sqrt{1+12+2\sqrt{1}\sqrt{12}} \cr
  &= \textstyle\sqrt{\big(1+\sqrt{12}\big)^2} \cr
  &= 1+\sqrt{12} \cr
  &= \boldsymbol{ 1+2\sqrt{3} }.
\end{align*}
{{% enum b %}}
{{% mn q9b tips %}}
(2) $\sqrt{5}-1>0$
{{% /mn %}}
\begin{align*}
  &\textstyle\sqrt{7-\sqrt{21+\sqrt{80}}} \cr
  &= \textstyle\sqrt{7-\sqrt{21+2\sqrt{20}}} \cr
  &= \textstyle\sqrt{7-\sqrt{1+20+2\sqrt{1}\sqrt{20}}} \cr
  &= \textstyle\sqrt{7-\sqrt{(1+\sqrt{20})^2}} \cr
  &= \textstyle\sqrt{7-(1+\sqrt{20})} \cr
  &= \textstyle\sqrt{6-\sqrt{20}} \cr
  &= \textstyle\sqrt{6-2\sqrt{5}} \cr
  &= \textstyle\sqrt{1+5-2\sqrt{1}\sqrt{5}} \cr
  &= \textstyle\sqrt{(1-\sqrt{5})^2} \cr
  &= \boldsymbol{ \sqrt{5}-1 }. \tag{2}
\end{align*}

{{% /details %}}


10. When $x=\dfrac{1}{\sqrt{3}-\sqrt{2}}$ and $y=\dfrac{1}{\sqrt{3}+\sqrt{2}}$, find $x^3+x^2y+xy^2+y^3$. {{% mn ref10 refs %}}From Konan Univ.{{% /mn %}}

{{% details title="Answer" %}}
10. $20\sqrt{2}$

{{% note Solution %}}
Note the expression is [symmetric](../expressions-square-roots-2/#symmetric-expressions) in $x$ and $y$. So we can express the expression in terms of $x+y$ and $xy$. Let's calculate the values of $x+y$ and $xy$ first:

\begin{align*}
  x+y &= \frac{1}{\sqrt{3}-\sqrt{2}} + \frac{1}{\sqrt{3}+\sqrt{2}} \cr
  &= \frac{\big(\sqrt{3}+\sqrt{2}\big)+\big(\sqrt{3}-\sqrt{2}\big)}{\big(\sqrt{3}-\sqrt{2}\big)\big(\sqrt{3}+\sqrt{2}\big)} \cr
  &= \frac{2\sqrt{3}}{3-2} \cr
  &= 2\sqrt{3}
\end{align*}
and
\begin{align*}
  xy &= \dfrac{1}{\big(\sqrt{3}-\sqrt{2}\big)\big(\sqrt{3}+\sqrt{2}\big)} \cr
  &= \dfrac{1}{3-2} \cr
  &= 1.
\end{align*}

Then,
{{% mn q10 tips %}}
(1) $x^2+y^2$ $= (x+y)^2 - 2xy$
{{% /mn %}}
\begin{align*}
  x^3+x^2y+xy^2+y^3 &= x^2(x+y)+y^2(x+y) \cr
  &= (x+y)(x^2+y^2) \cr
  &= (x+y)\{ (x+y)^2 - 2xy \} \tag{1} \cr
  &= 2\sqrt{3}\big\\{ \big(2\sqrt{3}\big)^2 - 2\cdot 1 \big\\} \cr
  &= 2\sqrt{3}(12-2) \cr
  &= \boldsymbol{ 20\sqrt{2} }.
\end{align*}

{{% /details %}}

11. When $a=\dfrac{2}{3-\sqrt{5}}$, find: {{% mn ref11 refs %}}From Kagoshima Univ.{{% /mn %}}
    1. $a+\dfrac{1}{a}$
    2. $a^2+\dfrac{1}{a^2}$
    3. $a^5+\dfrac{1}{a^5}$

{{% details title="Answer" %}}
11. 
    1. $3$
    2. $7$
    3. $123$

{{% note Solution %}}
Note that we can use the answer to Part (a) to solve Parts (b) and (c).

{{% enum a %}}
\begin{align*}
  a+\frac{1}{a} &= \frac{2}{3-\sqrt{5}} + \frac{3-\sqrt{5}}{2} \cr
  &= \frac{2\big(3+\sqrt{5}\big)}{3^2-5} + \frac{3-\sqrt{5}}{2} \cr
  &= \frac{2\big(3+\sqrt{5}\big)}{4} + \frac{3-\sqrt{5}}{2} \cr
  &= \frac{3+\sqrt{5}}{2} + \frac{3-\sqrt{5}}{2} \cr
  &= \boldsymbol{ 3 }.
\end{align*}

{{% enum b %}}
\begin{align*}
  a^2+\dfrac{1}{a^2} &= \left( a + \dfrac{1}{a} \right)^2 - 2 \cr
  &= 3^2 - 2 \cr
  &= \boldsymbol{ 7 }.
\end{align*}

{{% enum c %}} We will find the value of $a^3+\dfrac{1}{a^3}$ first:

\begin{align*}
  a^3 + \dfrac{1}{a^3} &= \left(a+\dfrac{1}{a}\right)^3 - 3\left(a+\dfrac{1}{a}\right) \cr
  &= 3^3 - 3\cdot 3 \cr
  &= 18.
\end{align*}

Then, because
\begin{align*}
  &\left(a^3+\dfrac{1}{a^3}\right)\left(a^2+\dfrac{1}{a^2}\right) \cr
  &= \hl{a^5} + a + \frac{1}{a} + \hl{\frac{1}{a^5}},
\end{align*}

\begin{align*}
  &a^5 + \frac{1}{a^5} \cr
  &= \left(a^3+\dfrac{1}{a^3}\right)\left(a^2+\dfrac{1}{a^2}\right) - \left(a+\frac{1}{a}\right) \cr
  &= 18\cdot 7 - 3 \cr
  &= \boldsymbol{ 123 }.
\end{align*}

{{% /details %}}


12. Let the decimal part of $\sqrt{9+4\sqrt{5}}$ be $a$. Find:
    1. $a^2-\dfrac{1}{a^2}$
    2. $a^3$
    3. $a^4-2a^2+1$

{{% details title="Answer" %}}
12. 
    1. $-8\sqrt{5}$
    2. $17\sqrt{5} - 38$
    3. $144 - 64\sqrt{5}$

{{% note Solution %}}
We will first solve the [double square root](../removing-roots-2/#double-square-roots) of $a$ first.

\begin{align*}
  \textstyle\sqrt{9+4\sqrt{5}} &= \textstyle\sqrt{9+2\sqrt{20}} \cr
  &= \textstyle\sqrt{4+5+2\sqrt{20}} \cr
  &= \textstyle\sqrt{(2+\sqrt{5})^2} \cr
  &= 2+\sqrt{5}.
\end{align*}

Because $\sqrt{5}$ is greater than $2(=\sqrt{4})$ but smaller than $3(=\sqrt{9})$, $$ 4 \le 2+\sqrt{5} \lt 5. $$ Hence its decimal part is

\begin{align*}
  a &= 2+\sqrt{5}-4 = \sqrt{5}-2.
\end{align*}

{{% enum a %}} Because $$ a^2 - \frac{1}{a^2} = \left(a+\frac{1}{a}\right)\left(a-\frac{1}{a}\right), $$ let's find the value of $\dfrac{1}{a}$ first:

\begin{align*}
  \frac{1}{a} &= \frac{1}{\sqrt{5}-2} \cr
  &= \frac{\sqrt{5}+2}{5-2^2} \cr
  &= \sqrt{5}+2.
\end{align*}

Thus
\begin{align*}
  a^2 - \frac{1}{a^2} &= \left(a+\frac{1}{a}\right)\left(a-\frac{1}{a}\right) \cr
  &= \big\\{ \big(\sqrt{5}-2\big)+\big(\sqrt{5}+2\big) \big\\}\big\\{ \big(\sqrt{5}-2\big)-\big(\sqrt{5}+2\big) \big\\} \cr
  &= \big( 2\sqrt{5} \big)\cdot( -4 ) \cr
  &= \boldsymbol{ -8\sqrt{5} }.
\end{align*}

{{% enum b %}}
{{% mn q12b tips %}}
(1) $(a-b)^3$ $=a^3-3a^2b+3ab^2-b^3$
{{% /mn %}}
\begin{align*}
  a^3 &= \big(\sqrt{5}-2\big)^3 \cr
  &= \sqrt{5}^3 - 3\sqrt{5}^2\cdot 2 + 3\sqrt{5}\cdot 2^2 - 2^3 \tag{1} \cr
  &= 5\sqrt{5} - 30 + 12\sqrt{5} - 8 \cr
  &= \boldsymbol{ 17\sqrt{5} - 38 }.
\end{align*}

{{% enum c %}} We will factorise the expression first before substituting.
{{% mn q12c tips %}}
(2) $A^2-2A+1$ $=(A-1)^2$, where $A=a^2$.
{{% /mn %}}

\begin{align*}
  a^4-2a^2+1 &= (a^2-1)^2 \tag{2} \cr
  &= \{ (a+1)(a-1) \}^2 \cr
  &= \big\\{ \big(\sqrt{5}-2+1\big)\big(\sqrt{5}-2-1\big) \big\\}^2 \cr
  &= \big\\{ \big(\sqrt{5}-1\big)\big(\sqrt{5}-3\big) \big\\}^2 \cr
  &= \big( 5 - 4\sqrt{5} + 3 \big)^2 \cr
  &= \big(8-4\sqrt{5}\big)^2 \cr
  &= 8^2 - 2\cdot 8\cdot 4\sqrt{5} + \big(4\sqrt{5}\big)^2 \cr
  &= 64 - 64\sqrt{5} + 80 \cr
  &= \boldsymbol{ 144 - 64\sqrt{5} }.
\end{align*}

{{% /details %}}