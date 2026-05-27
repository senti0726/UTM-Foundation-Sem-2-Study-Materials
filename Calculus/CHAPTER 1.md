$$\underline{\Huge\text{LIMIT AND CONTINUITY}}$$
# 1.0 INTRODUCTION
The concept of the limit is one of the most crucial things to understand in order to prepare for calculus. A limit is a number that a function approaches as the independent variable of the function approaches a given value.

The expression $\lim_{x\rightarrow a}f(x)$, where a is a real number, $a\in\mathbb{R}$, and $f(x)$ is a function, is read as the limit of $f(x)$ as x approaches a. $\lim_{x\rightarrow a}$ is called as limit operator. Hence, it is applied to a function $f(x)$.

$\lim_{x\rightarrow a}f(x)$ is the real number that $f(x)$ approaches as x approaches a, if such a number exists. If $f(x)$ does exist, which $f(x)$ approach to a real number, we denote that number by L (for limit value). Thus, we say the limit exists, and we write it as $\lim_{x\rightarrow a}f(x)=L$ or $f(x)=L$ as $x\rightarrow a$.

# 1.1 LIMITS
If $\lim_{x\rightarrow a}f(x)=L$, this says that the values of $f(x)$ tend to get closer and closer to the number L as x gets closer to the number a (from either side of a). Either side of a means the function approached different values from the left and right of a but $x\ne a$.

A function $f(x)$ has the left limit $L_{1}$ as x approaches a, or $f(x)$ approaches $L_{1}$ as x approaches a from the left side (where values of x are less than a), and we write $\lim_{x\rightarrow a^{-}}f(x)=L_{1}$: "the limit of $f(x)$ as x approaches a from the left equals $L_{1}$".

A function $f(x)$ has the right limit $L_{2}$ as x approaches a, or $f(x)$ approaches $L_{2}$ as x approaches a from the right side (where values of x are more than a), and we write $\lim_{x\rightarrow a^{+}}f(x)=L_{2}$: "the limit of $f(x)$ as x approaches a from the right equals $L_{2}$". Left limit and right limit is known as one sided limit.
## 1.1.1 Existence of Limits
If the limits from the left and right sides of $f(x)$ have the same value such that $\lim_{x\rightarrow a^{-}}f(x)=\lim_{x\rightarrow a^{+}}f(x)=L$, then $\lim_{x\rightarrow a}f(x)$ is exist and it is written as $\lim_{x\rightarrow a}f(x)=L$ (known as two sided limit) and we say the "limit of $f(x)$ as x approaches a equals L".

If either the left limit or right limit does not exist or if $\lim_{x\rightarrow a^{-}}f(x)\ne \lim_{x\rightarrow a^{+}}f(x)$, then $\lim_{x\rightarrow a}f(x)$ does not exist.

It says that a two-sided limit exists if and only if both of the one-sided limits exist and are equal.

> [!example]- Example 1.1
> The graph of a function $g(x)$ is shown below. Use it to state the values (if they exist) of the following:
> ![[Pasted image 20260216162253.png]]
> a) $\lim_{x\rightarrow2^{-}}g(x)$
> b) $\lim_{x\rightarrow2^{+}}g(x)$
> c) $\lim_{x\rightarrow2}g(x)$
> d) $\lim_{x\rightarrow5^{-}}g(x)$
> e) $\lim_{x\rightarrow5^{+}}g(x)$
> f) $\lim_{x\rightarrow5}g(x)$
> g) $g(5)$
>
> > [!continue]- Solution
> > a) 3
> > b) 1
> > c) does not exist
> > d) 2
> > e) 2
> > f) 2
> > g) 1

> [!example]- Example 1.2
> Let $f(x)=\begin{cases}x&,0\le x\le1\\ 3-x&,1<x<2\end{cases}$
> and the graph of $f(x)$ is shown below. Find:
> ![[Pasted image 20260216162331.png]]
> a) $\lim_{x\rightarrow1^{-}}f(x)$
> b) $\lim_{x\rightarrow1^{+}}f(x)$
> c) $\lim_{x\rightarrow1}f(x)$
> d) $f(1)$
> e) $\lim_{x\rightarrow0^{+}}f(x)$
> f) $f(0)$
> g) $\lim_{x\rightarrow2^{-}}f(x)$
> h) $f(2)$
>
> > [!continue]- Solution
> > a) 1
> > b) 2
> > c) does not exist
> > d) 1
> > e) 0
> > f) 0
> > g) 1
> > h) does not exist

> [!sq]- Problem 1.1
> Let $f(x) = \begin{cases} -8, & x \le -6 \\ 3x + 10, & -6 < x < -2 \\ -5, & x = -2 \\ x^2, & -2 < x \le 3 \\ -2x + 9, & x > 3 \end{cases}$
> 
> a) Sketch the graph of $f(x)$.
> b) Show that:
> i. $\lim_{x\rightarrow-6}f(x)=f(-6)$
> ii. $\lim_{x\rightarrow-2}f(x)\ne f(-2)$
> iii. $\lim_{x\rightarrow3}f(x)$ does not exist.
> 
> > [!continue]- Solution
> > **a) Sketch the graph of $f(x)$:**
> > [EditHere - Page 3 Sketch of piecewise function $f(x)$]
> > 
> > **b) i. Show that $\lim_{x\rightarrow-6}f(x)=f(-6)$:**
> > Left limit: $\lim_{x\rightarrow-6^-} f(x) = -8$.
> > Right limit: $\lim_{x\rightarrow-6^+} (3x + 10) = 3(-6) + 10 = -8$.
> > Since left limit = right limit, $\lim_{x\rightarrow-6} f(x) = -8$.
> > Also, $f(-6) = -8$. Therefore, $\lim_{x\rightarrow-6}f(x)=f(-6)$. Shown.
> > 
> > **b) ii. Show that $\lim_{x\rightarrow-2}f(x)\ne f(-2)$:**
> > Left limit: $\lim_{x\rightarrow-2^-} (3x + 10) = 3(-2) + 10 = 4$.
> > Right limit: $\lim_{x\rightarrow-2^+} x^2 = (-2)^2 = 4$.
> > Since left limit = right limit, $\lim_{x\rightarrow-2} f(x) = 4$.
> > However, $f(-2) = -5$. Therefore, $\lim_{x\rightarrow-2}f(x)\ne f(-2)$. Shown.
> > 
> > **b) iii. Show that $\lim_{x\rightarrow3}f(x)$ does not exist:**
> > Left limit: $\lim_{x\rightarrow3^-} x^2 = 3^2 = 9$.
> > Right limit: $\lim_{x\rightarrow3^+} (-2x + 9) = -2(3) + 9 = 3$.
> > Since $\lim_{x\rightarrow3^-} f(x) \ne \lim_{x\rightarrow3^+} f(x)$, the limit $\lim_{x\rightarrow3}f(x)$ does not exist. Shown.

## 1.1.2 Cases of Non-Existence of Limits
Functions can exhibit a number of different behaviours as the input value gets very large value or very small value. In this section, we will take a look at limits whose value is $+\infty$ or $-\infty$ are known as infinite limits.

In general, a fractional function will have an infinite limit if the limit of the denominator is zero and the limit of the numerator is not zero. The sign of the infinite limit is determined by the sign of the quotient of the numerator and the denominator at values close to the number that x is approaching.

The line $x=a$ is a vertical asymptote of the graph $f(x)$ if $\lim_{x\rightarrow a^{-}}f(x)=\pm\infty$ or $\lim_{x\rightarrow a^{+}}f(x)=\pm\infty$. To recognizing an infinite limit, let us took a look of examples.

> [!example]- Example 1.3
> Sketch the graph of $f(x)=\frac{1}{x}$. Evaluate each of the following limits.
> a) $\lim_{x\rightarrow0^{-}}\frac{1}{x}$
> b) $\lim_{x\rightarrow0^{+}}\frac{1}{x}$
> c) $\lim_{x\rightarrow0}\frac{1}{x}$
>
> > [!continue]- Solution
> > The figure below shows the graph of $f(x)=\frac{1}{x}$.
> > ![[Pasted image 20260216174530.png]]
> > We know that, $f(x)=\frac{1}{x}$ is undefined if $x=0$.
> > a) From the graph, as x becomes close to 0 from the left, the value of $f(x)$ becomes smaller and decrease indefinitely. We can conclude that $\lim_{x\rightarrow0^{-}}\frac{1}{x}=-\infty$.
> > b) From the graph, as x becomes close to 0 from the right, the value of $f(x)$ becomes bigger and increase indefinitely. We can conclude that $\lim_{x\rightarrow0^{+}}\frac{1}{x}=+\infty$.
> > c) Since both one-sided limits are not equal, hence, $\lim_{x\rightarrow0}\frac{1}{x}$ does not exist.
> > The line $x=0$ is a vertical asymptote for the graph of $f(x)=\frac{1}{x}$.

In general, we write $\lim_{x\rightarrow a}f(x)=+\infty$ to indicate $f(x)$ tend to become larger and larger as x becomes closer and closer to a. $\lim_{x\rightarrow a}f(x)=+\infty$ is read as "the limit of $f(x)$ approaches a is positive infinity".

A similar sort of limit, for functions that become smaller and smaller as x gets closer to a. The expression is $\lim_{x\rightarrow a}f(x)=-\infty$ and read as "the limit of $f(x)$ approaches a is negative infinity".

> [!example]- Example 1.4
> Find the values of $\lim_{x\rightarrow3^{+}}\frac{2x}{x-3}$ and $\lim_{x\rightarrow3^{-}}\frac{2x}{x-3}$.
>
> > [!continue]- Solution
> > If x is close to 3 but larger than 3, then the denominator $x-3$ is a small positive number and the numerator 2x is close to 6. So, the quotient $\frac{2x}{x-3}$ is a large positive number. Thus, $\lim_{x\rightarrow3^{+}}\frac{2x}{x-3}=+\infty$.
> > 
> > If x is close to 3 but smaller than 3, then the denominator $x-3$ is a small negative number and the numerator 2x is still a positive number that is close to 6. So, the quotient $\frac{2x}{x-3}$ is a large negative number. Thus, $\lim_{x\rightarrow3^{-}}\frac{2x}{x-3}=-\infty$.
> > ![[Pasted image 20260216174558.png]]
> > The graph of $f(x)=\frac{2x}{x-3}$ is shown in the figure below. We can see that the line $x=3$ is the vertical asymptote for the graph of $f(x)=\frac{2x}{x-3}$.

> [!sq]- Problem 1.2
> Determine the infinite limits.
> a) $\lim_{x\rightarrow-3^{+}}\frac{x+2}{x+3}$
> b) $\lim_{x\rightarrow1}\frac{2-x}{(x-1)^{2}}$
> c) $\lim_{x\rightarrow-2^{+}}\frac{x-1}{x^{2}(x+2)}$
> d) $\lim_{x\rightarrow3}\frac{-3}{(x-3)^{2}}$
> e) $\lim_{x\rightarrow1^{-}}\frac{3x}{\sqrt{1-x^{2}}}$
>
> > [!continue]- Solution
> > **a) $\lim_{x\rightarrow-3^{+}}\frac{x+2}{x+3}$**
> > As $x \to -3^+$, the numerator $(x+2) \to -1$. The denominator $(x+3) \to 0^+$. A negative number divided by a small positive number approaches negative infinity. Result: $-\infty$.
> > 
> > **b) $\lim_{x\rightarrow1}\frac{2-x}{(x-1)^{2}}$**
> > As $x \to 1$, the numerator $(2-x) \to 1$. The denominator $(x-1)^2 \to 0^+$ (since it is squared, it's positive from both sides). A positive number divided by a small positive number approaches positive infinity. Result: $+\infty$.
> > 
> > **c) $\lim_{x\rightarrow-2^{+}}\frac{x-1}{x^{2}(x+2)}$**
> > As $x \to -2^+$, the numerator $(x-1) \to -3$. The denominator part $x^2 \to 4$ and $(x+2) \to 0^+$. Thus the denominator $\to 0^+$. Negative divided by positive approaches negative infinity. Result: $-\infty$.
> > 
> > **d) $\lim_{x\rightarrow3}\frac{-3}{(x-3)^{2}}$**
> > As $x \to 3$, numerator is -3. Denominator $(x-3)^2 \to 0^+$. Negative divided by positive approaches negative infinity. Result: $-\infty$.
> > 
> > **e) $\lim_{x\rightarrow1^{-}}\frac{3x}{\sqrt{1-x^{2}}}$**
> > As $x \to 1^-$, numerator $3x \to 3$. Denominator $\sqrt{1-x^2} \to 0^+$. Positive divided by positive approaches positive infinity. Result: $+\infty$.

## 1.1.3 Limits at Infinity
The function $f(x)$ will have a horizontal asymptote at $y=L$ if either of the following are true.
$\lim_{x\rightarrow+\infty}f(x)=L$ and $\lim_{x\rightarrow-\infty}f(x)=L$

> [!example]- Example 1.5
> Evaluate $\lim_{x\rightarrow+\infty}\frac{1}{x}$ and $\lim_{x\rightarrow-\infty}\frac{1}{x}$.
>
> > [!continue]- Solution
> > ![[Pasted image 20260216174625.png]]
> > The graph of $f(x)=\frac{1}{x}$ is sketched in the figure. From the graph, as x approaches $+\infty$, the value of $f(x)=\frac{1}{x}$ tends to zero. Thus, $\lim_{x\rightarrow+\infty}\frac{1}{x}=0$.
> > Similarly, as x approaches $-\infty$, the value of $f(x)=\frac{1}{x}$ tends to zero. Thus, $\lim_{x\rightarrow-\infty}\frac{1}{x}=0$.
> > We can conclude that $y=0$ is a horizontal asymptote of $f(x)=\frac{1}{x}$.

> [!example]- Example 1.6
> Let $f(x)=\frac{x}{x-2}$. Evaluate $\lim_{x\rightarrow+\infty}\frac{x}{x-2}$ and $\lim_{x\rightarrow-\infty}\frac{x}{x-2}$.
>
> > [!continue]- Solution
> > The graph of $f(x)=\frac{x}{x-2}$ is sketched in the figure below. From the graph, as x approaches $+\infty$, the value of $f(x)=\frac{x}{x-2}$ tends to 1. Thus, $\lim_{x\rightarrow+\infty}\frac{x}{x-2}=1$.
> > ![[Pasted image 20260216174644.png]]
> > Similarly, as x approaches $-\infty$, the values of $f(x)=\frac{x}{x-2}$ tends to 1. Thus, $\lim_{x\rightarrow-\infty}\frac{x}{x-2}=1$.
> > We can conclude that $y=1$ is a horizontal asymptote.

> [!sq]- Problem 1.3
> Determine the limit for each of the following.
> a) $\lim_{x\rightarrow\infty}\frac{1}{x-300}$
> b) $\lim_{x\rightarrow\infty}5-\frac{2}{x^{2}}$
> c) $\lim_{x\rightarrow+\infty}\frac{1}{x}-2$
> d) $\lim_{x\rightarrow+\infty}\frac{-4}{x^{2}+3}$
> e) $\lim_{x\rightarrow\infty}\frac{8}{4-x^{2}}$
>
> > [!continue]- Solution
> > **a) $\lim_{x\rightarrow\infty}\frac{1}{x-300}$**
> > As $x \to \infty$, the denominator becomes infinitely large. Result: $0$.
> > 
> > **b) $\lim_{x\rightarrow\infty}5-\frac{2}{x^{2}}$**
> > As $x \to \infty$, $\frac{2}{x^2} \to 0$. Result: $5 - 0 = 5$.
> > 
> > **c) $\lim_{x\rightarrow+\infty}\frac{1}{x}-2$**
> > As $x \to \infty$, $\frac{1}{x} \to 0$. Result: $0 - 2 = -2$.
> > 
> > **d) $\lim_{x\rightarrow+\infty}\frac{-4}{x^{2}+3}$**
> > As $x \to \infty$, the denominator becomes infinitely large. Result: $0$.
> > 
> > **e) $\lim_{x\rightarrow\infty}\frac{8}{4-x^{2}}$**
> > As $x \to \infty$, the denominator becomes infinitely large negative. Result: $0$.

# 1.2 COMPUTATIONAL METHODS OF LIMITS
Previously, we discussed on the interpretation of limits using graph. In this section, we establish properties for calculating limits and learn how to apply these properties. In other words, the limit is $\lim_{x\rightarrow a}f(x)=f(a)$.

## 1.2.1 Limits of Some Basic Functions
At this stage, we focused only on the properties of limits with three basic functions. The properties of limit with basic functions are as below:
Suppose a, k and n are real numbers. The limit of each of these expressions given as follows:

> [!formula]
> i. $\lim_{x\rightarrow a}k=k$, also true for $\lim_{x\rightarrow+\infty}k=k$ and $\lim_{x\rightarrow-\infty}k=k$
> ii. $\lim_{x\rightarrow a}x=a$, also true for $\lim_{x\rightarrow-\infty}x=-\infty$ and $\lim_{x\rightarrow+\infty}x=+\infty$
> iii. $\lim_{x\rightarrow a}x^{n}=a^{n}$

> [!example]- Example 1.7
> Evaluate each of the following limits:
> a) $\lim_{x\rightarrow2}x$
> b) $\lim_{x\rightarrow2}5$
> c) $\lim_{x\rightarrow3}x^{2}$
> d) $\lim_{x\rightarrow-\infty}3$
> e) $\lim_{x\rightarrow+\infty}x^{2}$
>
> > [!continue]- Solution
> > a) $\lim_{x\rightarrow2}x=2$
> > b) $\lim_{x\rightarrow2}5=5$
> > c) $\lim_{x\rightarrow3}x^{2}=9$
> > d) $\lim_{x\rightarrow-\infty}3=3$
> > e) $\lim_{x\rightarrow+\infty}x^{2}=\infty$

## 1.2.2 Basic Properties of Limits
Now, let us discuss theorems that can be used to evaluate the limits with more difficult problems.
Let $f(x)$ and $g(x)$ be two functions of x. If the limits of $f(x)$ and $g(x)$ exist at a particular point. Suppose k and n are real numbers. The limit of each of these expressions are as follows:

> [!formula]
> i. $\lim[k~f(x)]=k~\lim f(x)$
> ii. $\lim[f(x)\pm g(x)]=\lim f(x)\pm \lim g(x)$
> iii. $\lim[f(x)\cdot g(x)]=\lim f(x)\cdot \lim g(x)$
> iv. $\lim\left[\frac{f(x)}{g(x)}\right]=\frac{\lim f(x)}{\lim g(x)} ; \lim g(x)\ne0$
> v. $\lim[f(x)]^{n}=[\lim f(x)]^{n}$
> vi. $\lim \sqrt[n]{f(x)} = \sqrt[n]{\lim f(x)} ; \lim f(x) \ge 0$

> [!example]- Example 1.8
> Evaluate the following limits:
> a) $\lim_{x\rightarrow5}2x^{2}-3x+4$
> b) $\lim_{x\rightarrow-2}\frac{x^{3}+2x^{2}-1}{5-3x}$
> c) $\lim_{x\rightarrow-2}\sqrt{5x^{2}-4}$
> d) $\lim_{x\rightarrow2}\sqrt{4x-1}+4$
> e) $\lim_{t\rightarrow1}\frac{\sqrt{2+t}-\sqrt{3}}{t}$
>
> > [!continue]- Solution
> > a) $\lim_{x\rightarrow5}2x^{2}-3x+4=\lim_{x\rightarrow5}2x^{2}-\lim_{x\rightarrow5}3x+\lim_{x\rightarrow5}4=2(5)^{2}-3(5)+4=39$.
> > b) $\lim_{x\rightarrow-2}\frac{x^{3}+2x^{2}-1}{5-3x}=\frac{(-2)^{3}+2(-2)^{2}-1}{5-3(-2)}=-\frac{1}{11}$.
> > c) $\lim_{x\rightarrow-2}\sqrt{5x^{2}-4}=\sqrt{5(-2)^{2}-4}=4$.
> > d) $\lim_{x\rightarrow2}\sqrt{4x-1}+4=\sqrt{4(2)-1}+4=7$.
> > e) $\lim_{t\rightarrow1}\frac{\sqrt{2+t}-\sqrt{3}}{t}=\frac{\sqrt{2+1}-\sqrt{3}}{1}=0$.

## 1.2.3 Limits of Indeterminate Form
However, not all limits can be evaluated by direct substitution. If we have, $\lim_{x\rightarrow a}\frac{f(x)}{g(x)}=\frac{0}{0}$, which is an indeterminate form, then the function $f(x)$ and $g(x)$ will need to be simplified by either:
i. Factorization method, or
ii. Rationalization method (multiplying with conjugates, if have surd $(\sqrt{})$ form).

Let us look at the following examples.

> [!example]- Example 1.9
> Evaluate the following limits:
> a) $\lim_{x\rightarrow1}\frac{x^{2}-1}{x-1}$
> b) $\lim_{x\rightarrow4}\frac{2x+8}{x^{2}+x-12}$
> c) $\lim_{y\rightarrow1}\frac{1-y}{1-\sqrt{y}}$
> d) $\lim_{x\rightarrow0}\frac{\sqrt{x+3}+2x-\sqrt{3}}{x}$
>
> > [!continue]- Solution
> > a) $\lim_{x\rightarrow1}\frac{x^{2}-1}{x-1}=\frac{0}{0}$
> > $\lim_{x\rightarrow1}\frac{(x-1)(x+1)}{x-1}=\lim_{x\rightarrow1}x+1=1+1=2$.
> > 
> > b) $\lim_{x\rightarrow4}\frac{2x+8}{x^{2}+x-12}=\frac{0}{0}$
> > $\lim_{x\rightarrow4}\frac{2(x+4)}{(x-3)(x+4)}=\frac{2}{(4-3)}=2$. *(Note: The source text shows $\frac{2}{-4-3} = -\frac{2}{7}$ which evaluated the limit approaching -4, but the limit is approaching 4. Corrected evaluated limit based on original question).*
> > 
> > c) $\lim_{y\rightarrow1}\frac{1-y}{1-\sqrt{y}}=\frac{0}{0}$
> > $\lim_{y\rightarrow1}\frac{1-y}{1-\sqrt{y}}\times\frac{1+\sqrt{y}}{1+\sqrt{y}}=\lim_{y\rightarrow1}\frac{(1-y)(1+\sqrt{y})}{1-y}=1+\sqrt{1}=2$.
> > 
> > d) $\lim_{x\rightarrow0}\frac{\sqrt{x+3}+2x-\sqrt{3}}{x}=\frac{0}{0}$
> > $\lim_{x\rightarrow0}\frac{\sqrt{x+3}-\sqrt{3}}{x}+\lim_{x\rightarrow0}2=\lim_{x\rightarrow0}\frac{\sqrt{x+3}-\sqrt{3}}{x}\times\frac{\sqrt{x+3}+\sqrt{3}}{\sqrt{x+3}+\sqrt{3}}+2$
> > $=\lim_{x\rightarrow0}\frac{x}{x(\sqrt{x+3}+\sqrt{3})}+2$
> > $=\frac{1}{(\sqrt{0+3}+\sqrt{3})}+2$
> > $=\frac{1}{2\sqrt{3}}+2$.

## 1.2.4 Limits of Rational Functions as $x\rightarrow+\infty$ or $x\rightarrow-\infty$
To determine the limits of rational functions as $x\rightarrow+\infty$ or $x\rightarrow-\infty$, we have to divide the numerator and denominator by the highest power of x that occurs in the denominator $g(x)$.

> [!example]- Example 1.10
> Evaluate the following limits:
> a) $\lim_{x\rightarrow+\infty}\frac{5x-7}{3x-2}$
> b) $\lim_{x\rightarrow+\infty}\frac{x^{2}+x}{x+2}$
> c) $\lim_{x\rightarrow\infty}\frac{x+2}{x^{2}-2x+1}$
> d) $\lim_{x\rightarrow\infty}\frac{\sqrt{5x^{2}+2x}}{x}$
> e) $\lim_{y\rightarrow\infty}\frac{2+y}{\sqrt{6y^{2}-7}}$
> f) $\lim_{t\rightarrow\infty}\frac{4t-5}{\sqrt{3t^{2}-t}}$
>
> > [!continue]- Solution
> > a) $\lim_{x\rightarrow\infty}\frac{\frac{5x-7}{x}}{\frac{3x-2}{x}}=\lim_{x\rightarrow\infty}\frac{5-\frac{7}{x}}{3-\frac{2}{x}}=\frac{5}{3}$.
> > b) $\lim_{x\rightarrow\infty}\frac{\frac{x^{2}+x}{x}}{\frac{x+2}{x}}=\lim_{x\rightarrow\infty}\frac{x+1}{1+\frac{2}{x}}=\frac{\infty}{1}=\infty$.
> > c) $\lim_{x\rightarrow\infty}\frac{\frac{x+2}{x^{2}}}{\frac{x^{2}-2x+1}{x^{2}}}=\lim_{x\rightarrow\infty}\frac{\frac{1}{x}+\frac{2}{x^{2}}}{1-\frac{2}{x}+\frac{1}{x^{2}}}=\frac{0}{1}=0$.
> > d) $\lim_{x\rightarrow\infty}\frac{\sqrt{5x^{2}+2x}}{x}=\lim_{x\rightarrow\infty}\frac{\sqrt{\frac{5x^{2}+2x}{x^{2}}}}{\frac{x}{x}}=\lim_{x\rightarrow\infty}\frac{\sqrt{5+\frac{2}{x}}}{1}=\sqrt{5}$.
> > e) $\lim_{y\rightarrow\infty}\frac{\frac{2+y}{y}}{\sqrt{\frac{6y^{2}-7}{y^{2}}}}=\lim_{y\rightarrow\infty}\frac{\frac{2}{y}+1}{\sqrt{6-\frac{7}{y^{2}}}}=\frac{1}{\sqrt{6}}$.
> > f) $\lim_{t\rightarrow\infty}\frac{\frac{4t-5}{t}}{\sqrt{\frac{3t^{2}-t}{t^{2}}}}=\lim_{t\rightarrow\infty}\frac{4-\frac{5}{t}}{\sqrt{3-\frac{1}{t}}}=\frac{4}{\sqrt{3}}$.

> [!sq]- Problem 1.4
> Determine the limit for each of the following:
> a) $\lim_{x\rightarrow2}2x$
> b) $\lim_{x\rightarrow-1}\frac{2x}{3x^{2}-1}$
> c) $\lim_{x\rightarrow2}\frac{2-x}{\sqrt{x+2}-\sqrt{3x-2}}$
> d) $\lim_{x\rightarrow2}\frac{2-\sqrt{8-x^{2}}}{x-2}$
> e) $\lim_{x\rightarrow1}\frac{1-\frac{1}{x}}{\sqrt{x}-1}$
> f) $\lim_{x\rightarrow\infty}\frac{4\sqrt{5x^{2}-2}}{\sqrt{5}(x+3)}$
> g) $\lim_{x\rightarrow+\infty}\frac{6x^{2}+1}{\sqrt{9x^{4}-x+1}}$
>
> > [!continue]- Solution
> > **a) $\lim_{x\rightarrow2}2x$**
> > $\lim_{x\rightarrow2}2x = 2(2) = 4$.
> > 
> > **b) $\lim_{x\rightarrow-1}\frac{2x}{3x^{2}-1}$**
> > $\lim_{x\rightarrow-1}\frac{2x}{3x^{2}-1} = \frac{2(-1)}{3(-1)^{2}-1} = \frac{-2}{3-1} = \frac{-2}{2} = -1$.
> > 
> > **c) $\lim_{x\rightarrow2}\frac{2-x}{\sqrt{x+2}-\sqrt{3x-2}}$**
> > This is an indeterminate form of $\frac{0}{0}$. Multiply by the conjugate:
> > $\lim_{x\rightarrow2}\frac{(2-x)(\sqrt{x+2}+\sqrt{3x-2})}{(\sqrt{x+2}-\sqrt{3x-2})(\sqrt{x+2}+\sqrt{3x-2})} = \lim_{x\rightarrow2}\frac{(2-x)(\sqrt{x+2}+\sqrt{3x-2})}{(x+2)-(3x-2)}$
> > $= \lim_{x\rightarrow2}\frac{(2-x)(\sqrt{x+2}+\sqrt{3x-2})}{-2x+4} = \lim_{x\rightarrow2}\frac{(2-x)(\sqrt{x+2}+\sqrt{3x-2})}{2(2-x)}$
> > $= \lim_{x\rightarrow2}\frac{\sqrt{x+2}+\sqrt{3x-2}}{2} = \frac{\sqrt{4}+\sqrt{4}}{2} = \frac{4}{2} = 2$.
> > 
> > **d) $\lim_{x\rightarrow2}\frac{2-\sqrt{8-x^{2}}}{x-2}$**
> > This is an indeterminate form of $\frac{0}{0}$. Multiply by the conjugate:
> > $\lim_{x\rightarrow2}\frac{(2-\sqrt{8-x^{2}})(2+\sqrt{8-x^{2}})}{(x-2)(2+\sqrt{8-x^{2}})} = \lim_{x\rightarrow2}\frac{4-(8-x^{2})}{(x-2)(2+\sqrt{8-x^{2}})} = \lim_{x\rightarrow2}\frac{x^{2}-4}{(x-2)(2+\sqrt{8-x^{2}})}$
> > $= \lim_{x\rightarrow2}\frac{(x-2)(x+2)}{(x-2)(2+\sqrt{8-x^{2}})} = \lim_{x\rightarrow2}\frac{x+2}{2+\sqrt{8-x^{2}}} = \frac{4}{2+\sqrt{4}} = \frac{4}{4} = 1$.
> > 
> > **e) $\lim_{x\rightarrow1}\frac{1-\frac{1}{x}}{\sqrt{x}-1}$**
> > Simplify the numerator: $1-\frac{1}{x} = \frac{x-1}{x}$.
> > $\lim_{x\rightarrow1}\frac{x-1}{x(\sqrt{x}-1)}$. Multiply by conjugate $\sqrt{x}+1$:
> > $= \lim_{x\rightarrow1}\frac{(x-1)(\sqrt{x}+1)}{x(\sqrt{x}-1)(\sqrt{x}+1)} = \lim_{x\rightarrow1}\frac{(x-1)(\sqrt{x}+1)}{x(x-1)} = \lim_{x\rightarrow1}\frac{\sqrt{x}+1}{x} = \frac{2}{1} = 2$.
> > 
> > **f) $\lim_{x\rightarrow\infty}\frac{4\sqrt{5x^{2}-2}}{\sqrt{5}(x+3)}$**
> > Divide numerator and denominator by $x$:
> > $= \lim_{x\rightarrow\infty}\frac{4\sqrt{5 - \frac{2}{x^2}}}{\sqrt{5}(1 + \frac{3}{x})} = \frac{4\sqrt{5}}{\sqrt{5}(1)} = 4$.
> > 
> > **g) $\lim_{x\rightarrow+\infty}\frac{6x^{2}+1}{\sqrt{9x^{4}-x+1}}$**
> > Divide numerator and denominator by the highest power of $x$ in the denominator, which is $\sqrt{x^4} = x^2$:
> > $= \lim_{x\rightarrow+\infty}\frac{\frac{6x^2+1}{x^2}}{\sqrt{\frac{9x^4-x+1}{x^4}}} = \lim_{x\rightarrow+\infty}\frac{6 + \frac{1}{x^2}}{\sqrt{9 - \frac{1}{x^3} + \frac{1}{x^4}}} = \frac{6}{\sqrt{9}} = \frac{6}{3} = 2$.

![[Pasted image 20260216174751.png]]

# 1.3 CONTINUITY
A function $f(x)$ is said to be continuous at $x=a$ if the graph of $f(x)$ is a single unbroken curve. Means the graph is drawing without lifting the pen from the paper. For example, a graph of continuous function is shown below:

## 1.3.1 Continuous at a Point
The definition of continuity of a function is given as: A function $f(x)$ is said to be continuous at a point $x=a$ if the following conditions are satisfied:
i. The function is defined at $x=a$, that is $f(a)$ exist.
ii. $\lim_{x\rightarrow a}f(x)$ is exist.
iii. $\lim_{x\rightarrow a}f(x)=f(a)$

The definition says that $f(x)$ is continuous at $x=a$ if $f(x)$ approaches $f(a)$ as $x$ approaches $a$. If one or more of the conditions is not satisfied, then the function $f(x)$ is said to be not continuous at $x=a$.

If $f(x)$ is not continuous at $x=a$, we say that $f(x)$ is discontinuous at $x=a$ (or has a discontinuity at $x=a$) which can be described in below figures:

![[Pasted image 20260216174807.png]]

If $f(x)$ and $g(x)$ are continuous at $x=a$, then the following functions are also continuous at $x=a$:
a) $f(x)+g(x)$
b) $f(x)-g(x)$
c) $cf(x)$ where c is a constant.
d) $f(x)\cdot g(x)$
e) $\frac{f(x)}{g(x)}, g(x)\ne0$

> [!example]- Example 1.11
> Determine whether the function $f(x)$ is continuous at $x=-2$ such that $f(x)$ is given:
> $f(x)=\begin{cases}\frac{x^{2}-4}{x+2},&x<-2\\ \frac{x}{4}+6,&x\ge-2\end{cases}$
>
> > [!continue]- Solution
> > For $f(x)$ to be continuous at a point $x=-2$, $f(x)$ must satisfied conditions:
> > i. The function is defined at $x=-2$, that is $f(-2)$ exist.
> > Check: $f(-2)=\frac{-2}{4}+6=\frac{11}{2}$ gives $f(-2)$ is defined.
> > 
> > ii. $\lim_{x\rightarrow-2}f(x)$ exist.
> > Check: $\lim_{x\rightarrow-2^{-}}\frac{x^{2}-4}{x+2}=\frac{0}{0}$
> > $\lim_{x\rightarrow-2^{-}}\frac{(x-2)(x+2)}{x+2}=-2-2=-4$
> > $\lim_{x\rightarrow-2^{+}}\frac{x}{4}+6=\frac{-2}{4}+6=\frac{11}{2}$
> > $\lim_{x\rightarrow-2^{+}}f(x)\ne \lim_{x\rightarrow-2^{-}}f(x)$
> > $\lim_{x\rightarrow-2}f(x)$ does not exist.
> > 
> > No need to check third condition, because second conditional already not satisfied. Thus, the function $f(x)$ is discontinuous at $x=-2$.

> [!example]- Example 1.12
> The function $f(x)$ is defined as follows:
> $f(x)=\begin{cases}\frac{3}{x-1}&,&x<4\\ x&,&x=4\\ \frac{x+1}{\sqrt{x^{2}+9}}&,&x>4\end{cases}$
> a) Find:
> i. $\lim_{x\rightarrow3}f(x)$
> ii. $\lim_{x\rightarrow\infty}f(x)$
> b) Determine whether the function $f(x)$ is continuous at $x=4$.
>
> > [!continue]- Solution
> > a) i. $\lim_{x\rightarrow3}\frac{3}{x-1}=\frac{3}{3-1}=\frac{3}{2}$
> > ii. $\lim_{x\rightarrow\infty}\frac{\frac{x+1}{x}}{\sqrt{\frac{x^{2}+9}{x^{2}}}}=\lim_{x\rightarrow\infty}\frac{1+\frac{1}{x}}{\sqrt{1+\frac{9}{x^{2}}}}=\frac{1}{\sqrt{1}}=1$
> > 
> > b) $f(4)=4$
> > $\lim_{x\rightarrow4^{-}}\frac{3}{x-1}=\frac{3}{4-1}=1$
> > $\lim_{x\rightarrow4^{+}}\frac{x+1}{\sqrt{x^{2}+9}}=\frac{4+1}{\sqrt{4^{2}+9}}=1$
> > $\lim_{x\rightarrow4}f(x)=1$
> > $\lim_{x\rightarrow4}f(x)=1\ne f(4)$
> > $\lim_{x\rightarrow4}f(x)$ does not exist. *(Note: The limit does exist and equals 1, but it does not equal $f(4)$)*.
> > Thus, the function $f(x)$ is discontinuous at $x=4$.

> [!example]- Example 1.13
> The function $g(x)$ is defined as follows:
> $g(x)=\begin{cases}mx-2,&x\le2\\ 4x+n,&2<x\le3\\ \frac{x^{2}-9}{x-3},&x>3\end{cases}$
> a) Given that $\lim_{x\rightarrow2}g(x)=6$, find the values of m and n.
> b) Hence, determine whether the function is continuous at $x=3$.
>
> > [!continue]- Solution
> > a) $\lim_{x\rightarrow2^-}g(x) = m(2)-2=6 \Rightarrow 2m = 8 \Rightarrow m=4$
> > $\lim_{x\rightarrow2^+}g(x) = 4(2)+n=6 \Rightarrow 8 + n = 6 \Rightarrow n=-2$
> > 
> > b) $f(3)=4(3)-2=10$
> > $\lim_{x\rightarrow3^{-}}4x-2=4(3)-2=10$
> > $\lim_{x\rightarrow3^{+}}\frac{x^{2}-9}{x-3}=\frac{0}{0}$
> > $\lim_{x\rightarrow3^{+}}\frac{(x-3)(x+3)}{x-3}=3+3=6$
> > $\lim_{x\rightarrow3^{+}}g(x)\ne \lim_{x\rightarrow3^{-}}g(x)$.
> > $\lim_{x\rightarrow3}g(x)$ does not exist.
> > Thus, the function $g(x)$ is discontinuous at $x=3$.

> [!example]- Example 1.14
> The function $f(x)$ is defined as follows:
> $f(x)=\begin{cases}\ln(x-1),&1<x\le2\\ x^{2}-4,&x>2\end{cases}$
> Is $f(x)$ continuous at $x=2$?
>
> > [!continue]- Solution
> > $f(2)=\ln(2-1)=0$
> > $\lim_{x\rightarrow2^{-}}\ln(x-1)=0$
> > $\lim_{x\rightarrow2^{+}}x^{2}-4=0$
> > $\lim_{x\rightarrow2}f(x)=0$, $\lim_{x\rightarrow2}f(x)$ is exist.
> > $\lim_{x\rightarrow2}f(x)=f(2)=0$
> > Thus, the function $f(x)$ is continuous at $x=2$.

> [!sq]- Problem 1.5
> Given that $f(x)=\begin{cases}mx-n,&x<1\\ 5,&x=1\\ 2mx+n,&x>1\end{cases}$
> find the values of m and n so that $f(x)$ is continuous at $x=1$.
>
> > [!continue]- Solution
> > For $f(x)$ to be continuous at $x=1$, the following must hold:
> > $\lim_{x\to1^-} f(x) = \lim_{x\to1^+} f(x) = f(1)$
> > $f(1) = 5$
> > $\lim_{x\to1^-} (mx - n) = m - n$
> > $\lim_{x\to1^+} (2mx + n) = 2m + n$
> > This gives us a system of linear equations:
> > 1) $m - n = 5$
> > 2) $2m + n = 5$
> > Adding equation (1) and (2):
> > $3m = 10 \Rightarrow m = \frac{10}{3}$
> > Substitute $m$ into equation (1):
> > $\frac{10}{3} - n = 5 \Rightarrow n = \frac{10}{3} - \frac{15}{3} = -\frac{5}{3}$.
> > The values are $m = \frac{10}{3}$ and $n = -\frac{5}{3}$.

> [!sq]- Problem 1.6
> Given that $f(x)=\begin{cases}\frac{x^{4}-16}{x+2},&x<-2\\ kx-4,&-2\le x<2\\ \frac{(x-5)^{2}}{x},&x\ge2\end{cases}$ *(Note: Corrected typo $(6-5)^2/x$ to $(x-5)^2/x$ based on standard function behavior)*
> a) Find the value of k such that $\lim_{x\rightarrow-2}f(x)$ exist.
> b) Hence, determine whether the function is continuous at $x=2$.
> c) Evaluate $\lim_{x\rightarrow\infty}f(x)$.
>
> > [!continue]- Solution
> > **a)** For $\lim_{x\rightarrow-2}f(x)$ to exist, the left and right limits at $x=-2$ must be equal.
> > Left limit: $\lim_{x\to-2^-} \frac{x^4-16}{x+2} = \lim_{x\to-2^-} \frac{(x^2-4)(x^2+4)}{x+2} = \lim_{x\to-2^-} \frac{(x-2)(x+2)(x^2+4)}{x+2} = \lim_{x\to-2^-} (x-2)(x^2+4) = (-4)(8) = -32$.
> > Right limit: $\lim_{x\to-2^+} (kx - 4) = -2k - 4$.
> > Equating them: $-2k - 4 = -32 \Rightarrow -2k = -28 \Rightarrow k = 14$.
> > 
> > **b)** With $k=14$, the function for $-2 \le x < 2$ is $14x - 4$.
> > To check continuity at $x=2$, we evaluate the limits and function value:
> > $f(2) = \frac{(2-5)^2}{2} = \frac{(-3)^2}{2} = \frac{9}{2} = 4.5$.
> > Left limit: $\lim_{x\to2^-} (14x - 4) = 14(2) - 4 = 28 - 4 = 24$.
> > Right limit: $\lim_{x\to2^+} \frac{(x-5)^2}{x} = \frac{9}{2} = 4.5$.
> > Since $\lim_{x\to2^-}f(x) \ne \lim_{x\to2^+}f(x)$, the limit does not exist, so $f(x)$ is discontinuous at $x=2$.
> > 
> > **c)** To evaluate $\lim_{x\rightarrow\infty}f(x)$, we use the piece of the function where $x \ge 2$:
> > $\lim_{x\rightarrow\infty} \frac{(x-5)^2}{x} = \lim_{x\rightarrow\infty} \frac{x^2 - 10x + 25}{x} = \lim_{x\rightarrow\infty} (x - 10 + \frac{25}{x}) = \infty - 10 + 0 = \infty$.

# 1.4 TUTORIAL 1

> [!sq]- Question 1
> a) Let $h(x)=\frac{2x^{2}-5x+2}{5x^{2}-10x}$. Find $\lim_{x\rightarrow2}h(x)+\lim_{x\rightarrow\infty}h(x)$.
> b) Calculate $\lim_{x\rightarrow-\infty}\frac{\sqrt{5x^{2}-6x}}{2x-3}$.
>
> > [!continue]- Solution
> > **a)** For $\lim_{x\rightarrow2}h(x)$:
> > $\lim_{x\to2} \frac{2x^2-5x+2}{5x^2-10x} = \lim_{x\to2} \frac{(2x-1)(x-2)}{5x(x-2)} = \lim_{x\to2} \frac{2x-1}{5x} = \frac{2(2)-1}{5(2)} = \frac{3}{10}$.
> > For $\lim_{x\rightarrow\infty}h(x)$:
> > $\lim_{x\to\infty} \frac{2x^2-5x+2}{5x^2-10x} = \lim_{x\to\infty} \frac{2 - \frac{5}{x} + \frac{2}{x^2}}{5 - \frac{10}{x}} = \frac{2}{5}$.
> > Sum: $\frac{3}{10} + \frac{2}{5} = \frac{3}{10} + \frac{4}{10} = \frac{7}{10}$.
> > 
> > **b)** $\lim_{x\rightarrow-\infty}\frac{\sqrt{5x^{2}-6x}}{2x-3}$
> > Divide numerator and denominator by $x$. Since $x \to -\infty$, $x = -\sqrt{x^2}$.
> > $\lim_{x\to-\infty} \frac{\frac{\sqrt{5x^2-6x}}{-\sqrt{x^2}}}{\frac{2x-3}{x}} = \lim_{x\to-\infty} \frac{-\sqrt{5 - \frac{6}{x}}}{2 - \frac{3}{x}} = \frac{-\sqrt{5 - 0}}{2 - 0} = -\frac{\sqrt{5}}{2}$.

> [!sq]- Question 2
> Determine $\lim_{x\rightarrow16}\frac{1-\frac{16}{x}}{\sqrt{x}-4}$.
>
> > [!continue]- Solution
> > Simplify the numerator: $1 - \frac{16}{x} = \frac{x-16}{x}$.
> > $\lim_{x\to16} \frac{\frac{x-16}{x}}{\sqrt{x}-4} = \lim_{x\to16} \frac{x-16}{x(\sqrt{x}-4)}$.
> > Factor $x-16$ as a difference of squares: $x-16 = (\sqrt{x}-4)(\sqrt{x}+4)$.
> > $\lim_{x\to16} \frac{(\sqrt{x}-4)(\sqrt{x}+4)}{x(\sqrt{x}-4)} = \lim_{x\to16} \frac{\sqrt{x}+4}{x} = \frac{\sqrt{16}+4}{16} = \frac{4+4}{16} = \frac{8}{16} = \frac{1}{2}$.

> [!sq]- Question 3
> Evaluate the following limits:
> a) $\lim_{x\rightarrow1}\frac{3x-3}{\sqrt{x+3}-2}$
> b) $\lim_{x\rightarrow\infty}\frac{3x^{3}}{2x^{5}-10}$
> c) $\lim_{x\rightarrow3}\frac{\sqrt{3}-\sqrt{6-x}}{x^{2}-9}$
> d) $\lim_{x\rightarrow3}\frac{x-3}{x^{3}-9x}$
>
> > [!continue]- Solution
> > **a)** $\lim_{x\rightarrow1}\frac{3x-3}{\sqrt{x+3}-2}$
> > Multiply by the conjugate: $\lim_{x\to1} \frac{3(x-1)(\sqrt{x+3}+2)}{(\sqrt{x+3}-2)(\sqrt{x+3}+2)} = \lim_{x\to1} \frac{3(x-1)(\sqrt{x+3}+2)}{(x+3)-4} = \lim_{x\to1} \frac{3(x-1)(\sqrt{x+3}+2)}{x-1} = \lim_{x\to1} 3(\sqrt{x+3}+2) = 3(\sqrt{4}+2) = 3(4) = 12$.
> > 
> > **b)** $\lim_{x\rightarrow\infty}\frac{3x^{3}}{2x^{5}-10}$
> > Divide by highest power $x^5$: $\lim_{x\to\infty} \frac{\frac{3}{x^2}}{2 - \frac{10}{x^5}} = \frac{0}{2-0} = 0$.
> > 
> > **c)** $\lim_{x\rightarrow3}\frac{\sqrt{3}-\sqrt{6-x}}{x^{2}-9}$
> > Multiply by the conjugate: $\lim_{x\to3} \frac{(\sqrt{3}-\sqrt{6-x})(\sqrt{3}+\sqrt{6-x})}{(x-3)(x+3)(\sqrt{3}+\sqrt{6-x})} = \lim_{x\to3} \frac{3 - (6-x)}{(x-3)(x+3)(\sqrt{3}+\sqrt{6-x})} = \lim_{x\to3} \frac{x-3}{(x-3)(x+3)(\sqrt{3}+\sqrt{6-x})} = \lim_{x\to3} \frac{1}{(x+3)(\sqrt{3}+\sqrt{6-x})} = \frac{1}{(3+3)(\sqrt{3}+\sqrt{3})} = \frac{1}{6(2\sqrt{3})} = \frac{1}{12\sqrt{3}}$.
> > 
> > **d)** $\lim_{x\rightarrow3}\frac{x-3}{x^{3}-9x}$
> > Factor the denominator: $\lim_{x\to3} \frac{x-3}{x(x^2-9)} = \lim_{x\to3} \frac{x-3}{x(x-3)(x+3)} = \lim_{x\to3} \frac{1}{x(x+3)} = \frac{1}{3(3+3)} = \frac{1}{18}$.

> [!sq]- Question 4
> Determine $\lim_{x\rightarrow\infty}\frac{\sqrt{x^{6}+5}}{x^{3}-6x}$ and $\lim_{x\rightarrow-\infty}\frac{2x-1}{\sqrt{x^{2}+3x}}$
>
> > [!continue]- Solution
> > **First limit:** $\lim_{x\rightarrow\infty}\frac{\sqrt{x^{6}+5}}{x^{3}-6x}$
> > Divide numerator and denominator by $x^3$ (which is $\sqrt{x^6}$ for $x>0$):
> > $\lim_{x\to\infty} \frac{\sqrt{\frac{x^6+5}{x^6}}}{\frac{x^3-6x}{x^3}} = \lim_{x\to\infty} \frac{\sqrt{1+\frac{5}{x^6}}}{1-\frac{6}{x^2}} = \frac{\sqrt{1+0}}{1-0} = 1$.
> > 
> > **Second limit:** $\lim_{x\rightarrow-\infty}\frac{2x-1}{\sqrt{x^{2}+3x}}$
> > Divide numerator and denominator by $x$. Since $x \to -\infty$, $x = -\sqrt{x^2}$.
> > $\lim_{x\to-\infty} \frac{\frac{2x-1}{x}}{\frac{\sqrt{x^2+3x}}{-\sqrt{x^2}}} = \lim_{x\to-\infty} \frac{2 - \frac{1}{x}}{-\sqrt{1 + \frac{3}{x}}} = \frac{2 - 0}{-\sqrt{1 + 0}} = -2$.

> [!sq]- Question 5
> Evaluate the following:
> a) $\lim_{x\rightarrow0}\frac{2x^{2}-5x-3}{x^{2}-9}$
> b) $\lim_{x\rightarrow\infty}\sqrt{\frac{x^{5}+3x^{2}}{16x^{5}-x}}$
>
> > [!continue]- Solution
> > **a)** $\lim_{x\rightarrow0}\frac{2x^{2}-5x-3}{x^{2}-9}$
> > Direct substitution yields: $\frac{2(0)^2 - 5(0) - 3}{0^2 - 9} = \frac{-3}{-9} = \frac{1}{3}$.
> > 
> > **b)** $\lim_{x\rightarrow\infty}\sqrt{\frac{x^{5}+3x^{2}}{16x^{5}-x}}$
> > Divide inside the square root by $x^5$:
> > $\lim_{x\to\infty} \sqrt{\frac{1 + \frac{3}{x^3}}{16 - \frac{1}{x^4}}} = \sqrt{\frac{1 + 0}{16 - 0}} = \sqrt{\frac{1}{16}} = \frac{1}{4}$.

> [!sq]- Question 6
> Evaluate each of the following limits:
> a) $\lim_{x\rightarrow6}\frac{x^{2}-36}{x^{2}-2x-24}$
> b) $\lim_{x\rightarrow\infty}\frac{3-4x}{\sqrt{2x^{2}+1}}$
>
> > [!continue]- Solution
> > **a)** $\lim_{x\rightarrow6}\frac{x^{2}-36}{x^{2}-2x-24}$
> > Factor numerator and denominator: $\lim_{x\to6} \frac{(x-6)(x+6)}{(x-6)(x+4)} = \lim_{x\to6} \frac{x+6}{x+4} = \frac{6+6}{6+4} = \frac{12}{10} = \frac{6}{5}$.
> > 
> > **b)** $\lim_{x\rightarrow\infty}\frac{3-4x}{\sqrt{2x^{2}+1}}$
> > Divide numerator and denominator by $x$ (which is $\sqrt{x^2}$ for $x>0$):
> > $\lim_{x\to\infty} \frac{\frac{3}{x} - 4}{\sqrt{2 + \frac{1}{x^2}}} = \frac{0 - 4}{\sqrt{2 + 0}} = -\frac{4}{\sqrt{2}} = -2\sqrt{2}$.

> [!sq]- Question 7
> Find the following limits:
> a) $\lim_{x\rightarrow2}\frac{2-x}{x^{2}+2x-8}$
> b) $\lim_{x\rightarrow1}\frac{\sqrt{x^{2}+8}-3}{x-1}$
> c) $\lim_{x\rightarrow3}\frac{12-4x}{x^{2}-2x-3}$
> d) $\lim_{x\rightarrow0}\frac{\sqrt{4+x}-\sqrt{4}}{2x}$
> e) $\lim_{x\rightarrow\infty}\sqrt{\frac{5x^{5}-2}{x^{5}+4x}}$
> f) $\lim_{x\rightarrow5}\frac{x^{2}-5x}{x^{4}-4x^{3}-5x^{2}}$
> g) $\lim_{x\rightarrow4}\frac{4-x}{\sqrt{x+5}-\sqrt{2x+1}}$
> h) $\lim_{x\rightarrow-\infty}\frac{\sqrt{3x^{2}+6}}{5-2x}$
>
> > [!continue]- Solution
> > **a)** $\lim_{x\to2} \frac{2-x}{(x+4)(x-2)} = \lim_{x\to2} \frac{-(x-2)}{(x+4)(x-2)} = \lim_{x\to2} \frac{-1}{x+4} = -\frac{1}{6}$.
> > 
> > **b)** $\lim_{x\to1} \frac{\sqrt{x^2+8}-3}{x-1} \times \frac{\sqrt{x^2+8}+3}{\sqrt{x^2+8}+3} = \lim_{x\to1} \frac{(x^2+8)-9}{(x-1)(\sqrt{x^2+8}+3)} = \lim_{x\to1} \frac{x^2-1}{(x-1)(\sqrt{x^2+8}+3)} = \lim_{x\to1} \frac{(x-1)(x+1)}{(x-1)(\sqrt{x^2+8}+3)} = \frac{1+1}{\sqrt{9}+3} = \frac{2}{6} = \frac{1}{3}$.
> > 
> > **c)** $\lim_{x\to3} \frac{-4(x-3)}{(x-3)(x+1)} = \lim_{x\to3} \frac{-4}{x+1} = \frac{-4}{4} = -1$.
> > 
> > **d)** $\lim_{x\to0} \frac{\sqrt{4+x}-2}{2x} \times \frac{\sqrt{4+x}+2}{\sqrt{4+x}+2} = \lim_{x\to0} \frac{(4+x)-4}{2x(\sqrt{4+x}+2)} = \lim_{x\to0} \frac{x}{2x(\sqrt{4+x}+2)} = \lim_{x\to0} \frac{1}{2(\sqrt{4+x}+2)} = \frac{1}{2(2+2)} = \frac{1}{8}$.
> > 
> > **e)** $\lim_{x\to\infty} \sqrt{\frac{5x^5-2}{x^5+4x}} = \lim_{x\to\infty} \sqrt{\frac{5-\frac{2}{x^5}}{1+\frac{4}{x^4}}} = \sqrt{\frac{5}{1}} = \sqrt{5}$.
> > 
> > **f)** $\lim_{x\to5} \frac{x(x-5)}{x^2(x^2-4x-5)} = \lim_{x\to5} \frac{x(x-5)}{x^2(x-5)(x+1)} = \lim_{x\to5} \frac{1}{x(x+1)} = \frac{1}{5(6)} = \frac{1}{30}$.
> > 
> > **g)** $\lim_{x\to4} \frac{4-x}{\sqrt{x+5}-\sqrt{2x+1}} \times \frac{\sqrt{x+5}+\sqrt{2x+1}}{\sqrt{x+5}+\sqrt{2x+1}} = \lim_{x\to4} \frac{(4-x)(\sqrt{x+5}+\sqrt{2x+1})}{(x+5)-(2x+1)} = \lim_{x\to4} \frac{(4-x)(\sqrt{x+5}+\sqrt{2x+1})}{-x+4} = \lim_{x\to4} (\sqrt{x+5}+\sqrt{2x+1}) = \sqrt{9} + \sqrt{9} = 3+3 = 6$.
> > 
> > **h)** $\lim_{x\to-\infty} \frac{\sqrt{3x^2+6}}{5-2x}$. Divide by $x$ (for numerator, use $-\sqrt{x^2}$):
> > $= \lim_{x\to-\infty} \frac{\frac{\sqrt{3x^2+6}}{-\sqrt{x^2}}}{\frac{5-2x}{x}} = \lim_{x\to-\infty} \frac{-\sqrt{3+\frac{6}{x^2}}}{\frac{5}{x}-2} = \frac{-\sqrt{3}}{-2} = \frac{\sqrt{3}}{2}$.

> [!sq]- Question 8
> Given $f(x)=\begin{cases}6x,&x<\frac{1}{3}\\ 3x^{2}+k,&x\ge\frac{1}{3}\end{cases}$, find k such that $f(x)$ is continuous at $x=\frac{1}{3}$.
>
> > [!continue]- Solution
> > For $f(x)$ to be continuous at $x=\frac{1}{3}$, $\lim_{x\to(1/3)^-} f(x) = \lim_{x\to(1/3)^+} f(x) = f(1/3)$.
> > Left limit: $\lim_{x\to(1/3)^-} 6x = 6(\frac{1}{3}) = 2$.
> > Right limit: $\lim_{x\to(1/3)^+} (3x^2+k) = 3(\frac{1}{9}) + k = \frac{1}{3} + k$.
> > Equating limits: $\frac{1}{3} + k = 2 \Rightarrow k = 2 - \frac{1}{3} = \frac{5}{3}$.

> [!sq]- Question 9
> The function $f(x)$ is defined as follows:
> $f(x)=\begin{cases}\frac{x^{2}+2x-3}{x+3},&x\le-3\\ ax+2,&-3<x<2\\ 7x-8,&x\ge2\end{cases}$
> a) Find a if $\lim_{x\rightarrow-3}f(x)$ exist.
> b) Determine whether $f(x)$ is continuous at $x=2$.
>
> > [!continue]- Solution
> > **a)** For $\lim_{x\to-3} f(x)$ to exist, left and right limits at $x=-3$ must be equal.
> > Left limit: $\lim_{x\to-3^-} \frac{x^2+2x-3}{x+3} = \lim_{x\to-3^-} \frac{(x+3)(x-1)}{x+3} = \lim_{x\to-3^-} (x-1) = -3 - 1 = -4$.
> > Right limit: $\lim_{x\to-3^+} (ax+2) = -3a + 2$.
> > Equating them: $-3a + 2 = -4 \Rightarrow -3a = -6 \Rightarrow a = 2$.
> > 
> > **b)** To check continuity at $x=2$, evaluate limits and function value:
> > Left limit: $\lim_{x\to2^-} (ax+2)$. Since $a=2$, this is $2(2)+2 = 6$.
> > Right limit: $\lim_{x\to2^+} (7x-8) = 7(2)-8 = 14-8 = 6$.
> > Function value: $f(2) = 7(2)-8 = 6$.
> > Since $\lim_{x\to2^-} f(x) = \lim_{x\to2^+} f(x) = f(2) = 6$, $f(x)$ is continuous at $x=2$.

> [!sq]- Question 10
> Given $f(x)=\begin{cases}2x^{2}+5x-3,&x\le\frac{1}{2}\\ 4ax+5,&\frac{1}{2}<x<2\end{cases}$. Find a so that $f(x)$ is continuous at $x=\frac{1}{2}$.
>
> > [!continue]- Solution
> > For $f(x)$ to be continuous at $x=1/2$, $\lim_{x\to(1/2)^-} f(x) = \lim_{x\to(1/2)^+} f(x) = f(1/2)$.
> > Left limit: $\lim_{x\to(1/2)^-} (2x^2+5x-3) = 2(\frac{1}{4}) + 5(\frac{1}{2}) - 3 = \frac{1}{2} + \frac{5}{2} - 3 = 3 - 3 = 0$.
> > Right limit: $\lim_{x\to(1/2)^+} (4ax+5) = 4a(\frac{1}{2}) + 5 = 2a + 5$.
> > Equating them: $2a + 5 = 0 \Rightarrow 2a = -5 \Rightarrow a = -\frac{5}{2}$.

> [!sq]- Question 11
> Let $g(x)=\begin{cases}x^{3}-x,&x<-2\\ a+3x,&-2\le x\le2\\ x^{2}-4,&x>2\end{cases}$.
> a) Find the value of a if $\lim_{x\rightarrow-2}g(x)$ exist.
> b) Determine whether $g(x)$ is continuous at $x=2$.
>
> > [!continue]- Solution
> > **a)** For $\lim_{x\to-2} g(x)$ to exist, left and right limits at $x=-2$ must be equal.
> > Left limit: $\lim_{x\to-2^-} (x^3-x) = (-2)^3 - (-2) = -8 + 2 = -6$.
> > Right limit: $\lim_{x\to-2^+} (a+3x) = a + 3(-2) = a - 6$.
> > Equating them: $a - 6 = -6 \Rightarrow a = 0$.
> > 
> > **b)** Check continuity at $x=2$. Since $a=0$, the middle function is $3x$.
> > Left limit: $\lim_{x\to2^-} (0+3x) = 3(2) = 6$.
> > Right limit: $\lim_{x\to2^+} (x^2-4) = 2^2-4 = 0$.
> > Since $6 \ne 0$, $\lim_{x\to2} g(x)$ does not exist.
> > Therefore, $g(x)$ is not continuous at $x=2$.

> [!sq]- Question 12
> The function $f(x)$ is defined as follows:
> $f(x)=\begin{cases}\frac{x}{x-2},&x\le1\\ (2-m)x,&1<x\le4\\ \frac{m-2}{x^{2}},&x>4\end{cases}$
> a) Find the value of m if $\lim_{x\rightarrow4}f(x)$ exist.
> b) Determine whether $f(x)$ is continuous at $x=1$.
>
> > [!continue]- Solution
> > **a)** For $\lim_{x\to4} f(x)$ to exist, left and right limits at $x=4$ must be equal.
> > Left limit: $\lim_{x\to4^-} (2-m)x = (2-m)(4) = 8 - 4m$.
> > Right limit: $\lim_{x\to4^+} \frac{m-2}{x^2} = \frac{m-2}{16}$.
> > Equating them: $8 - 4m = \frac{m-2}{16} \Rightarrow 128 - 64m = m - 2 \Rightarrow 65m = 130 \Rightarrow m = 2$.
> > 
> > **b)** To check continuity at $x=1$:
> > Left limit: $\lim_{x\to1^-} \frac{x}{x-2} = \frac{1}{1-2} = -1$.
> > Right limit: $\lim_{x\to1^+} (2-m)x$. With $m=2$, this is $\lim_{x\to1^+} (2-2)x = 0$.
> > Since $-1 \ne 0$, $\lim_{x\to1} f(x)$ does not exist.
> > Therefore, $f(x)$ is discontinuous at $x=1$.

> [!sq]- Question 13
> Let $f(x)=\begin{cases}4-kx,&x\le2\\ x^{2}-4,&2<x\le5\\ \frac{21}{6-x},&x>5\end{cases}$.
> a) Find $\lim_{x\rightarrow\infty}f(x)$.
> b) Find the value of k if $\lim_{x\rightarrow2}f(x)$ exist.
> c) Determine whether $f(x)$ is continuous at $x=5$.
>
> > [!continue]- Solution
> > **a)** For $x \to \infty$, we use the piece $x > 5$:
> > $\lim_{x\to\infty} \frac{21}{6-x} = 0$.
> > 
> > **b)** For $\lim_{x\to2} f(x)$ to exist, left and right limits at $x=2$ must be equal.
> > Left limit: $\lim_{x\to2^-} (4-kx) = 4 - 2k$.
> > Right limit: $\lim_{x\to2^+} (x^2-4) = 2^2-4 = 0$.
> > Equating them: $4 - 2k = 0 \Rightarrow 2k = 4 \Rightarrow k = 2$.
> > 
> > **c)** To check continuity at $x=5$:
> > Left limit: $\lim_{x\to5^-} (x^2-4) = 5^2 - 4 = 21$.
> > Right limit: $\lim_{x\to5^+} \frac{21}{6-x} = \frac{21}{6-5} = 21$.
> > Function value: $f(5) = 5^2 - 4 = 21$.
> > Since $\lim_{x\to5^-} f(x) = \lim_{x\to5^+} f(x) = f(5) = 21$, the function $f(x)$ is continuous at $x=5$.