---
title: "Review: Inequalities"
slug: review-4
description: Review of inequalities and their applications.

date: 2021-03-08 10:33:10.000 +1100
lastMod: 2021-03-08 10:33:10.000 +1100

type: docs
toc: false
math: true
draft: false

tags:
  - inequality
  - linear equation
  - absolute value
  - algebra

menu:
  math1:
    parent: Linear Inequalities
    name: ✏️ Review 4
    weight: 18

# previous/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 18
---

1. If you divide a certain integer by 20 and round the result to the nearest whole, the answer is 17. Find the smallest and largest possible values for that integer.

{{% details title="Solution" %}}

1. Smallest value is 330, largest value is 349.

{{% note Solution %}}
Let the integer be $n$. Then, the range of $n\div 20$ should be $$ 16.5 \le \dfrac{n}{20} < 17.5 $$ because it should round to $17.$ Then
\begin{align*}
  16.5 \le \dfrac{n}{20} < 17.5 &\iff 16.5 \times 20 \le n < 17.5 \times 20 \cr
  &\iff 330 \le n < 350.
\end{align*}

Therefore, the lowest value for $n$ is $ \boldsymbol{ 330 }$ and the highest value is $ \boldsymbol{ 349 }$.

{{% /details %}}

2. Solve the following inequalities.
    1. $2(x-3)\le -x+8$
    2. $\dfrac{1}{3}x > \dfrac{3}{5}x - 2$
    3. $\dfrac{5x+1}{3}-\dfrac{3+2x}{4}\ge \dfrac{1}{6}(x-5)$
    4. $0.3x - 7.2>0.5(x-2)$

{{% details title="Answer" %}}

2. 
    1. $x \le \dfrac{14}{3}$
    2. $x < \dfrac{15}{2}$
    3. $x \ge -\dfrac{12}{5}$
    4. $x < -31$

{{% note Solution %}} 

{{% enum a %}}
\begin{align*}
  & 2(x-3)\le -x+8 \cr
  & \iff 2x - 6 \le -x + 8 \cr
  & \iff 3x \le 14 \cr
  & \iff \boldsymbol{ x \le \dfrac{14}{3} }.
\end{align*}
{{% enum b %}}
\begin{align*}
  & \dfrac{1}{3}x > \dfrac{3}{5}x - 2 \cr
  & \iff 2 > \dfrac{3}{5}x - \dfrac{1}{3}x \cr
  & \iff 2 > \dfrac{4}{15}x \cr
  & \iff 2\cdot \dfrac{15}{4} > x \cr
  & \iff \boldsymbol{ x < \dfrac{15}{2} }. 
\end{align*}
{{% enum c %}}
{{% mn q2c tips %}}
(1) Multiplied both sides by the LCM of 3, 4, 6 (12).
{{% /mn %}}
\begin{align*}
  & \dfrac{5x+1}{3}-\dfrac{3+2x}{4}\ge \dfrac{1}{6}(x-5) \cr
  & \iff 4(5x+1) - 3(3+2x) \ge 2(x-5) \tag{1} \cr
  & \iff 20x + 4 - 9 - 6x \ge 2x - 10 \cr
  & \iff 12x \ge -5 \cr
  & \iff \boldsymbol{ x \ge -\dfrac{12}{5} }.
\end{align*}
{{% enum d %}}
\begin{align*}
   & 0.3x - 7.2>0.5(x-2) \cr
  & \iff 0.3x - 7.2 > 0.5x - 1 \cr
  & \iff -6.2 > 0.2x \cr
  & \iff -6.2 \cdot 5 > x \cr
  & \iff \boldsymbol{ x < -31 }.
\end{align*}

{{% /details %}}

3. Solve the following inequalities.{{% mn ref3 %}}a. From Kurashiki Univ. of Sci. and the Arts.{{% /mn %}}
    1. $\displaystyle \begin{cases} 6(x+1)>2x-5 \cr\\ 25-\dfrac{6-x}{2}\le 3x \end{cases}$
    2. $\dfrac{5(x-1)}{2}\le 2(2x+1) < \dfrac{7(x-1)}{4}$


{{% details title="Answer" %}}

3. 
    1. $x \ge \dfrac{44}{5}$
    2. $-3 \le x < -\dfrac{5}{3}$

{{% note Solution %}} 

{{% enum a %}}
From the first inequality,

\begin{align*}
  & 6(x+1)>2x-5 \cr
  & \iff 6x + 6 > 2x - 5 \cr
  & \iff 4x > -11 \cr
  & \iff x > -\dfrac{11}{4}, \tag{$\cdots\tcirc{1}$}
\end{align*}

and from the second inequality,
\begin{align*}
  & 25-\dfrac{6-x}{2}\le 3x \cr
  & \iff 50 - (6-x) \le 6x \cr
  & \iff 50 -6 + x \le 6x \cr
  & \iff 44 \le 5x \cr
  & \iff x \ge \dfrac{44}{5}. \tag{$\cdots\tcirc{2}$}
\end{align*}

The intersection of $\tcirc{1}$ and $\tcirc{2}$ is $\boldsymbol{ x \ge \dfrac{44}{5} }.$

{{% enum b %}}
The given inequality is equivalent to
$\begin{dcases}
  \dfrac{5(x-1)}{2}\le 2(2x+1), \cr\\
  2(2x+1) < \dfrac{7(x-1)}{4}.
\end{dcases}$

From the first inequality,
\begin{align*}
  & \dfrac{5(x-1)}{2}\le 2(2x+1) \cr
  & \iff 5(x-1) \le 4(2x+1) \cr
  & \iff 5x-5 \le 8x + 4 \cr
  & \iff -9 \le 3x \cr
  & \iff x \ge -3. \tag{$\cdots\tcirc{3}$}
\end{align*}

From the second inequality,
\begin{align*}
  & 2(2x+1) < \dfrac{7(x-1)}{4} \cr
  & \iff 8(2x+1) < 7(x-1) \cr
  & \iff 16x + 8 < 7x - 7 \cr
  & \iff 9x < -15 \cr
  & \iff x < -\dfrac{5}{3}.  \tag{$\cdots\tcirc{4}$}
\end{align*}

The intersection of $\tcirc{3}$ and $\tcirc{4}$ is $\boldsymbol{ -3 \le x < -\dfrac{5}{3} }.$

{{% /details %}}

4. For the simultaneous inequality $\displaystyle \begin{cases} x>3a+1 \cr\\ 2x-1>6(x-2)\end{cases}$, find the range of $a$ that satisfies the following conditions. {{% mn ref4 refs %}}From Kobe Gakuin Univ.{{% /mn %}}
    1. There does not exist any solutions.
    2. 2 is a solution.
    3. There are exactly three integer solutions.

{{% details title="Answer" %}}

4. 
    1. $a \ge \dfrac{7}{12}$
    2. $a < \dfrac{1}{3}$
    3. $-\dfrac{2}{3} \le a < -\dfrac{1}{3}$

{{% note Solution %}}
Let's first solve the inequalities in terms of $x$. The first inequality is already solved, and we will name it as $\tcirc{1}$. The second inequality leads to
\begin{align*}
  & 2x-1>6(x-2) \cr
  & \iff 2x-1>6x-12 \cr
  & \iff 11>4x \cr
  & \iff x<\dfrac{11}{4}. \tag{$\cdots\tcirc{2}$}
\end{align*}

{{% enum a %}}
{{% mn q4a tips %}}
{{% img-raw loc="sidenote" src="courses/jpn-maths-1/numbers-and-expressions/ineq-rev-4a.png" %}} Diagram for (a).
{{% /mn %}}
 For $\tcirc{1}$ and $\tcirc{2}$ to share no common range, we must have $ 3a+1 \ge \dfrac{11}{4} $. Thus
\begin{align*}
  & 3a+1 \ge \dfrac{11}{4} \cr
  & \iff 3a \ge \dfrac{7}{4} \cr
  & \iff \boldsymbol{ a \ge \dfrac{7}{12} }.
\end{align*}

{{% enum b %}}
{{% mn q4b tips %}}
{{% img-raw loc="sidenote" src="courses/jpn-maths-1/numbers-and-expressions/ineq-rev-4b.png" %}} Diagram for (b).
{{% /mn %}}
 In order to have 2 as a solution, $\tcirc{1}$ must also include 2 in their range. Thus
\begin{align*}
  & 3a + 1 < 2 \cr
  & \iff 3a < 1 \cr
  & \iff \boldsymbol{ a < \dfrac{1}{3} }.
\end{align*}

{{% enum c %}}
{{% mn q4c tips %}}
{{% img-raw loc="sidenote" src="courses/jpn-maths-1/numbers-and-expressions/ineq-rev-4c.png" %}} Diagram for (c).
{{% /mn %}}
 Because $2 < \dfrac{11}{4} < 3$, the largest integer that can be part of the solution is 2. Then the smallest integer solution must be 0, which $\tcirc{1}$ should include.
\begin{align*}
  & -1 \le 3a+1 < 0 \cr
  & \iff -2 \le 3a < -1 \cr
  & \iff \boldsymbol{ -\dfrac{2}{3} \le a < -\dfrac{1}{3}}.
\end{align*}

<hr style="visibility:hidden" />

{{% /details %}}

5. If $a$ and $b$ are constants, solve $ax > 3x - b$.

{{% details title="Answer" %}}

5. $\begin{cases} 
x > \dfrac{b}{3-a} & \text{if $a>3$}, \cr\\
x < \dfrac{b}{3-a} & \text{if $a<3$}, \cr\\
\text{any real number} & \text{if $a=3$ and $b>0$}, \cr\\
\text{no solution} & \text{if $a=3$ and $b<0$}.
\end{cases}$

{{% note Solution %}}
From the inequality we find $(a-3)x > -b$. We then need to consider the possible signs of $a-3$.

{{% ol i %}}
{{% li %}}
When $a-3>0$, $x > -\dfrac{b}{a-3}.$
{{% /li %}}
{{% li %}}
When $a-3<0$, $x < -\dfrac{b}{a-3}.$
{{% /li %}}
{{% li %}}
When $a-3=0$, the equality becomes $0 > -b$. This inequality is true if $ b>0 $.
{{% /li %}}
{{% /ol %}}

Combining the above, we conclude

$$\begin{cases} 
\boldsymbol{ x > \dfrac{b}{3-a} } & \textbf{if $\boldsymbol{ a>3 }$}, \cr
\boldsymbol{ x < \dfrac{b}{3-a} } & \textbf{if $\boldsymbol{ a<3 }$}, \cr
\textbf{any real number} & \textbf{if $\boldsymbol{ a=3 }$ and $\boldsymbol{ b>0 }$}, \cr
\textbf{no solution} & \textbf{if $\boldsymbol{ a=3 }$ and $\boldsymbol{ b<0 }$}.
\end{cases}$$

{{% /details %}}

6. Sarah needs to get to the station 1.5 km away from her house within 12 minutes. If she can walk at 60 m/min and run at 180 m/min, at least how many metres does she run for?

*Hint: distance = speed x time.*

{{% details title="Answer" %}}

6. 1170 m

{{% note Solution %}}
If we set the distance Sarah runs as $d$ metres, Sarah can walk $1500 - d$ metres. The time she spends running is thus $\dfrac{d}{180}$ minutes and the time she spends walking is $\dfrac{1500-d}{60} minutes.{{% sn q5 %}}$\text{(time)}$ $=\dfrac{\text{(distance)}}{\text{(speed)}}$.{{% /sn %}} Then
{{% mn q5 tips %}}
(1) Multiply 180 on both sides
{{% /mn %}}
\begin{align*}
  & \dfrac{d}{180} + \dfrac{1500-d}{60} \le 12 \tag{1} \cr
  & \iff d + 3(1500-d) \le 12 \cdot 180 \cr
  & \iff d + 4500 - 3d \le 2160 \cr
  & \iff 2340 \le 2d \cr
  & \iff d \ge 1170.
\end{align*}

Therefore, she needs to run at least $\textbf{1170 m}.$

{{% /details %}}

7. Kim mixes 8% saltwater with 800 g of 5% saltwater. If she wants to set the concentration in between 6% and 6.5%, how much 8% saltwater does she need to add?

*Hint:* $\text{concentration(\\%)} = \dfrac{\text{(amount of salt)}}{\text{(amount of salt water)}}\times 100 \\% $

{{% details title="Answer" %}}

7. more than 400 g and less than 800 g

{{% note Solution %}}
Let the mass of 8% salt water be $m$ g. The amount of salt in 500 g of 5% saltwater is
$$ \text{800 g} \times 0.05 = \text{40 g}, $$
and the amount of salt in $m$ g of 8% saltwater is
$$ \text{$m$ g} \times 0.08 = \text{$0.08m$ g}. $$
Then the total amount of salt is $ (40 + 0.08m)$ g, and the total mass of the saltwater is $ (800 + m) $ g. Because the concentration needs to be in between 6% and 6.5%,
\begin{align*}
  & 6 < \dfrac{40 + 0.08 m}{800 + m} \times 100 < 6.5 \cr
  & \iff 6(800+m) < 100(40+0.08m) < 6.5(800+m) \cr
  & \iff 4800 + 6m < 4000 + 8m < 5200 + 6.5m.
\end{align*}

From the first inequality,
\begin{align*}
  & 4800 + 6m < 4000 + 8m \cr
  &\iff 800 < 2m \cr
  &\iff m > 400,
\end{align*}

and from the second inequality,
\begin{align*}
  & 4000 + 8m < 5200 + 6.5m \cr
  &\iff 1.5m < 1200 \cr
  &\iff m < 1200 \times \dfrac{2}{3} \cr
  &\iff m < 800.
\end{align*}

Therefore, Kim needs to add $\textbf{more than 400 g and less than 800 g}$ of 8% saltwater.

{{% /details %}}

8. Solve the following equations and inequalities. {{% mn ref8 refs %}}a. From Tohoku Fukushi Univ.<br>c. From Aichi Gakusen Univ.{{% /mn %}}
    1. $ |x-3|+|2x-3| = 9 $
    2. $ \big||x-2|-4\big| = 3x$
    3. $ |2x-3| \le |3x+2| $
    4. $ 2|x+2| + |x-4| < 15 $

{{% details title="Answer" %}}

8. 
    1. $ x= -1, 5 $
    2. $ x=1 $
    3. $ x\le -5 \text{ or } x \ge \dfrac{1}{5} $
    4. $ -5 < x < 5 $

{{% note Solution %}}

{{% enum a %}}
We need to divide the ranges of $x$ at $x=3$ and $x=\dfrac{3}{2}$.

{{% ol i %}}
{{% li %}}
When $x<\dfrac{3}{2}$,
\begin{align*}
  & |x-3|+|2x-3| = 9 \cr
  &\iff -(x-3)-(2x-3) = 9 \cr
  &\iff -x+3 -2x+3 = 9 \cr
  &\iff -3x + 6 = 9 \cr
  &\iff x = -1.
\end{align*}

This answer is within the range of our assumption of $x < \dfrac{3}{2}$.
{{% /li %}}
{{% li %}}
When $\dfrac{3}{2} \le x < 3$,
\begin{align*}
  &|x-3|+|2x-3| = 9 \cr
  &\iff -(x-3)+(2x-3) = 9 \cr
  &\iff -x+3 +2x-3 = 9 \cr
  &\iff x = 9
\end{align*}

This is not a solution because $x=9$ is outside $\dfrac{3}{2} \le x < 3$.
{{% /li %}}
{{% li %}}
When $x\ge 3$,
\begin{align*}
  &|x-3|+|2x-3| = 9 \cr
  &\iff (x-3)+(2x-3) = 9 \cr
  &\iff x-3 +2x-3 = 9 \cr
  &\iff 3x-6 = 9 \cr
  &\iff x = 5.
\end{align*}

This answer is within the range of our assumption of $x\ge 3$.
{{% /li %}}
{{% /ol %}}

Therefore, the solution to the equation is $\boldsymbol{ x= -1, 5 }.$

{{% enum b %}}
Let's first assume $x\ge 2$ and remove the inner absolute value.
\begin{align*}
  &\big||x-2|-4\big| = 3x \cr
  &\iff |(x-2) -4| = 3x \cr
  &\iff |x-6| = 3x.
\end{align*}

{{% ol i %}}
{{% li %}}
When $x \ge 6$,
\begin{align*}
  &|x-6| = 3x \cr
  &\iff x-6 = 3x \cr
  &\iff -6 = 2x \cr
  &\iff x = -3.
\end{align*}

This is outside our assumed range of $x$.
{{% /li %}}
{{% li %}}
When $2 \le x < 6$,
\begin{align*}
  &|x-6| = 3x \cr
  &\iff -(x-6) = 3x \cr
  &\iff -x+6 = 3x \cr
  &\iff 6 = 4x \cr
  &\iff x = \dfrac{3}{2}.
\end{align*}

This is outside our assumed range of $x$.
{{% /li %}}
{{% /ol %}}

Thus, we find there are no solutions if we assume $x\ge 2$.

Let's then assume $x< 2$.
\begin{align*}
  &\big||x-2|-4\big| = 3x \cr
  &\iff |-(x-2) -4| = 3x \cr
  &\iff |-x-2| = 3x \cr
  &\iff |x+2| = 3x.
\end{align*}

{{% ol i 3 %}}
{{% li %}}
When $-2 \le x < 2$,
\begin{align*}
  & |x+2| = 3x \cr
  &\iff x+2 = 3x \cr
  &\iff 2 = 2x \cr
  &\iff x = 1.
\end{align*}

This solution satisfies our assumption.
{{% /li %}}
{{% li %}}
When $x < -2$,
\begin{align*}
  & |x+2| = 3x \cr
  &\iff -(x+2) = 3x \cr
  &\iff -x-2 = 3x \cr
  &\iff -2 = 4x \cr
  &\iff x = -\dfrac{1}{2}.
\end{align*}

This is outside our assumed range of $x$.
{{% /li %}}
{{% /ol %}}

Therefore, we conclude that the solution to the equation is $\boldsymbol{ x=1 }.$

{{% enum c %}}
We need to divide the cases at $x=\dfrac{3}{2}$ and $x=-\dfrac{2}{3}$.

{{% ol i %}}
{{% li %}}
When $x < -\dfrac{2}{3}$,
\begin{align*}
  |2x-3| \le |3x+2| &\iff -(2x-3) \le -(3x+2) \cr
  &\iff 2x-3 \ge 3x+2 \cr
  &\iff -5 \ge x.
\end{align*}

The intersection with our assumption $x \le -\dfrac{2}{3}$ is $$x \le -5. \quad \cdots\tcirc{1}$$
{{% /li %}}
{{% li %}}
When $-\dfrac{2}{3} \le x < \dfrac{3}{2}$,
\begin{align*}
  |2x-3| \le |3x+2| &\iff -(2x-3) \le (3x+2) \cr
  &\iff -2x + 3 \le 3x + 2 \cr
  &\iff 1 \le 5x \cr
  &\iff x \ge \dfrac{1}{5}.
\end{align*}

The intersection with our assumption $-\dfrac{2}{3} < x \le \dfrac{3}{2}$ is 
$$\dfrac{1}{5} \le x < \dfrac{3}{2}. \quad\cdots\tcirc{2}$$
{{% /li %}}
{{% li %}}
When $x \ge \dfrac{3}{2}$,
\begin{align*}
|2x-3| \le |3x+2| &\iff (2x-3) \le (3x+2) \cr
&\iff -5 \le x.
\end{align*}

The intersection with our assumption $x \ge \dfrac{3}{2}$ is $$x \ge \dfrac{3}{2}. \quad \cdots \tcirc{3} $$
{{% /li %}}
{{% /ol %}}

The complete range of $x$ that satisfies the inequality is the union of $\tcirc{1}$, $\tcirc{2}$ and $\tcirc{3}$. Therefore $\boldsymbol{ x\le -5 \textbf{ or } x \ge \dfrac{1}{5}}.$

{{% enum d %}}
We need to divide the range of $x$ at $x=-2$ and $x=4$. 

{{% ol i %}}
{{% li %}}
When $x < -2$,
\begin{align*}
  2|x+2| + |x-4| < 15 &\iff -2(x+2) -(x-4) < 15 \cr
  &\iff -2x-4 -x+4 < 15 \cr
  &\iff -3x < 15 \cr
  &\iff x > -5.
\end{align*}

Since we assumed $x<-2$, we find
$$-5 < x <-2. \quad \cdots\tcirc{1} $$
{{% /li %}}
{{% li %}}
When $-2 \le x < 4$,
\begin{align*}
  2|x+2| + |x-4| < 15 &\iff 2(x+2) -(x-4) < 15 \cr
  &\iff 2x + 4 -x + 4 < 15 \cr
  &\iff x < 7.
\end{align*}

Since we assumed $-2 \le x < 4$, we find 
$$-2 \le x < 4. \quad\cdots\tcirc{2}$$
{{% /li %}}
{{% li %}}
When $x \ge 4$,
\begin{align*}
  2|x+2| + |x-4| < 15 &\iff 2(x+2) +(x-4) < 15 \cr
  &\iff 2x+4 +x-4 < 15 \cr
  &\iff 3x < 15 \cr
  &\iff x<5.
\end{align*}

Since we assumed $x \ge 4$, we find
$$4 \le x < 5. \quad\cdots\tcirc{3}$$
{{% /li %}}
{{% /ol %}}

From $\tcirc{1}$, $\tcirc{2}$ and $\tcirc{3}$, we conclude that $\boldsymbol{ -5 < x < 5 }.$

{{% /details %}}