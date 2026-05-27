$$\underline{\Huge\text{DIFFERENTIATION}}$$
# 2.0 INTRODUCTION
We have covered the concept of limit for a function. Now, we will use the limits to find derivatives of a function in first principle.

The knowledge of derivatives of functions is important because it is widely used in science, engineering, computer science and business and economy.

# 2.1 FIRST PRINCIPLE

## 2.1.1 The Geometrical Meaning of Differentiation
Let $f(x)$ be a function, and let $P(x,f(x))$ and $Q(x+h,f(x+h))$ be two points on the graph of the function that are close to each other. The graph is shown below:

![[Pasted image 20260216163141.png]]

Joining the points P and Q with a straight line gives us the secant line on the graph of the function, and in the gradient of the line is given by:

> [!formula]
> $m_{secant} = \frac{\text{changes in } y}{\text{changes in } x} = \frac{\Delta y}{\Delta x} = \frac{f(x+h)-f(x)}{(x+h)-x} = \frac{f(x+h)-f(x)}{h}.$

In limiting proses, when Q approaches P, h becomes really small, almost close to zero, that is $h\rightarrow0$. Thus, $\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$.

As Q approaches P, the secant PQ tends to be a tangent line at P for the curve $y=f(x)$.
Thus, the limiting becomes the slope of the tangent at P for $y=f(x)$. We denote that $\lim_{h\rightarrow0}\frac{\Delta y}{\Delta x}=\frac{dy}{dx}$ and $\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}=f^{\prime}(x)$.

Therefore, $\frac{dy}{dx}=f^{\prime}(x)=m$, where m is the slope or gradient of the tangent at P for $f(x)$, that is $m=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$. We shall discuss the steps involved in obtaining the derivatives of the functions using this definition.

Let $y=f(x)$ is a function of x. The derivative of a function f with respect to x, denotes by $f^{\prime}(x)$, is defined by: 
$f^{\prime}(x)=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$ where the limit exists.

The procedure is known as the differentiation from the First Principle or differentiation using definition.
* **Step 1:** Given $y=f(x)$, write the expression $f(x+h)$.
* **Step 2:** Obtain the expression $f(x+h)-f(x)$.
* **Step 3:** Simplify the expression $\frac{f(x+h)-f(x)}{h}$.
* **Step 4:** Find $f^{\prime}(x)=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$.

## 2.1.2 Notation
The notation of differentiation with respect of x, we may see it written in the following ways:
$f^{\prime}(x), \quad y^{\prime}, \quad \frac{dy}{dx}, \quad \frac{d[f(x)]}{dx}, \quad \frac{d}{dx}[f(x)]$

> [!example]- Example 2.1
> By using differentiation from the first principle, find the derivative of the following functions:
> a) $f(x)=2x+3$
> b) $f(x)=2x^{2}$
> c) $y=\frac{1}{x}$
> d) $y=\frac{x}{1-3x}$
> e) $y=\sqrt{x}$
> d) $f(x)=\frac{1}{\sqrt{4x-2}}$ *(Note: Enumeration kept as d) as per the source text)*
>
> > [!continue]- Solution
> > **a) $f(x)=2x+3$**
> > $f^{\prime}(x)=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$
> > $=\lim_{h\rightarrow0}\frac{2(x+h)+3-(2x+3)}{h}$
> > $=\lim_{h\rightarrow0}\frac{2x+2h+3-2x-3}{h}$
> > $=\lim_{h\rightarrow0}\frac{2h}{h}=\lim_{h\rightarrow0}2=2$
> > 
> > **b) $f(x)=2x^{2}$**
> > $f(x+h)=2(x+h)^{2} = 2x^{2}+2h^{2}+4xh$
> > $f(x+h)-f(x)=2x^{2}+2h^{2}+4xh-(2x^{2}) = 2h^{2}+4xh$
> > $\frac{f(x+h)-f(x)}{h}=\frac{2h^{2}+4xh}{h}=2h+4x$
> > $f^{\prime}(x)=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h} = \lim_{h\rightarrow0}2h+4x = 2(0)+4x = 4x$
> > 
> > **c) $y=\frac{1}{x}$**
> > $\frac{dy}{dx}=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h} = \lim_{h\rightarrow0}\frac{\frac{1}{x+h}-\frac{1}{x}}{h}$
> > $=\lim_{h\rightarrow0}\frac{x-(x+h)}{x(x+h)}\times\frac{1}{h}$
> > $=\lim_{h\rightarrow0}\frac{-h}{x^{2}+xh}\times\frac{1}{h}$
> > $=\lim_{h\rightarrow0}\frac{-1}{x^{2}+xh} = \frac{-1}{x^{2}+x(0)} = -\frac{1}{x^{2}}$
> > 
> > **d) $y=\frac{x}{1-3x}$**
> > $\frac{dy}{dx}=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h} = \lim_{h\rightarrow0}\frac{\frac{x+h}{1-3(x+h)}-\frac{x}{1-3x}}{h}$
> > $=\lim_{h\rightarrow0}\frac{(x+h)(1-3x)-x(1-3x-3h)}{(1-3x-3h)(1-3x)}\times\frac{1}{h}$
> > $=\lim_{h\rightarrow0}\frac{x-3x^{2}+h-3xh-x+3x^{2}+3xh}{h(1-3x-3h)(1-3x)}$
> > $=\lim_{h\rightarrow0}\frac{h}{h(1-3x-3h)(1-3x)} = \lim_{h\rightarrow0}\frac{1}{(1-3x-3h)(1-3x)}$
> > $=\frac{1}{(1-3x-3(0))(1-3x)} = \frac{1}{(1-3x)^{2}}$
> > 
> > **e) $y=\sqrt{x}$**
> > $\frac{dy}{dx}=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h} = \lim_{h\rightarrow0}\frac{\sqrt{x+h}-\sqrt{x}}{h}$
> > $=\lim_{h\rightarrow0}\frac{\sqrt{x+h}-\sqrt{x}}{h}\times\frac{\sqrt{x+h}+\sqrt{x}}{\sqrt{x+h}+\sqrt{x}}$
> > $=\lim_{h\rightarrow0}\frac{x+h-x}{h(\sqrt{x+h}+\sqrt{x})} = \lim_{h\rightarrow0}\frac{h}{h(\sqrt{x+h}+\sqrt{x})} = \lim_{h\rightarrow0}\frac{1}{\sqrt{x+h}+\sqrt{x}}$
> > $=\frac{1}{\sqrt{x+0}+\sqrt{x}} = \frac{1}{2\sqrt{x}}$
> > 
> > **d) $f(x)=\frac{1}{\sqrt{4x-2}}$** *(Note: Enumeration kept as d)*
> > $f^{\prime}(x)=\lim_{h\rightarrow0}\frac{f(x+h)-f(x)}{h} = \lim_{h\rightarrow0}\frac{\frac{1}{\sqrt{4(x+h)-2}}-\frac{1}{\sqrt{4x-2}}}{h}$
> > $=\lim_{h\rightarrow0}\frac{\sqrt{4x-2}-\sqrt{4x+4h-2}}{h(\sqrt{4x+4h-2})(\sqrt{4x-2})}\times\frac{\sqrt{4x-2}+\sqrt{4x+4h-2}}{\sqrt{4x-2}+\sqrt{4x+4h-2}}$
> > $=\lim_{h\rightarrow0}\frac{(4x-2)-(4x+4h-2)}{h(\sqrt{4x+4h-2})(\sqrt{4x-2})(\sqrt{4x-2}+\sqrt{4x+4h-2})}$
> > $=\lim_{h\rightarrow0}\frac{-4h}{h(\sqrt{4x+4h-2})(\sqrt{4x-2})(\sqrt{4x-2}+\sqrt{4x+4h-2})}$
> > $=\lim_{h\rightarrow0}\frac{-4}{(\sqrt{4x+4h-2})(\sqrt{4x-2})(\sqrt{4x-2}+\sqrt{4x+4h-2})}$
> > $=\frac{-4}{(\sqrt{4x+4(0)-2})(\sqrt{4x-2})(\sqrt{4x-2}+\sqrt{4x+4(0)-2})}$
> > $=\frac{-4}{(4x-2)(2\sqrt{4x-2})} = \frac{-2}{(4x-2)^{\frac{3}{2}}}$

> [!sq]- Problem 2.1
> Using the definition of differentiation, find $f^{\prime}(x)$
> a) $f(x)=\frac{x-2}{x+1}$
> b) $f(x)=\frac{2}{(x+1)^{2}}$
> c) $f(x)=\frac{2}{\sqrt{3x-1}}$
> d) $f(x)=\frac{1}{\sqrt{x+1}}$ at $x=3$
>
> > [!continue]- Solution
> > **a) $f(x)=\frac{x-2}{x+1}$**
> > $f^{\prime}(x) = \lim_{h\to0} \frac{\frac{x+h-2}{x+h+1} - \frac{x-2}{x+1}}{h} = \lim_{h\to0} \frac{(x+h-2)(x+1) - (x-2)(x+h+1)}{h(x+h+1)(x+1)}$
> > Numerator expands to: $(x^2 + x + hx + h - 2x - 2) - (x^2 + hx + x - 2x - 2h - 2) = 3h$.
> > $f^{\prime}(x) = \lim_{h\to0} \frac{3h}{h(x+h+1)(x+1)} = \lim_{h\to0} \frac{3}{(x+h+1)(x+1)} = \frac{3}{(x+1)^2}$.
> > 
> > **b) $f(x)=\frac{2}{(x+1)^{2}}$**
> > $f^{\prime}(x) = \lim_{h\to0} \frac{\frac{2}{(x+h+1)^2} - \frac{2}{(x+1)^2}}{h} = \lim_{h\to0} \frac{2(x+1)^2 - 2(x+h+1)^2}{h(x+h+1)^2(x+1)^2}$
> > Numerator expands to: $2(x^2+2x+1) - 2(x^2+h^2+1+2xh+2x+2h) = -2h^2 - 4xh - 4h = h(-2h - 4x - 4)$.
> > $f^{\prime}(x) = \lim_{h\to0} \frac{h(-2h - 4x - 4)}{h(x+h+1)^2(x+1)^2} = \frac{-4x - 4}{(x+1)^4} = \frac{-4(x+1)}{(x+1)^4} = -\frac{4}{(x+1)^3}$.
> > 
> > **c) $f(x)=\frac{2}{\sqrt{3x-1}}$**
> > $f^{\prime}(x) = \lim_{h\to0} \frac{\frac{2}{\sqrt{3(x+h)-1}} - \frac{2}{\sqrt{3x-1}}}{h} = \lim_{h\to0} \frac{2\sqrt{3x-1} - 2\sqrt{3x+3h-1}}{h\sqrt{3x+3h-1}\sqrt{3x-1}}$
> > Multiply by the conjugate $(2\sqrt{3x-1} + 2\sqrt{3x+3h-1})$:
> > Numerator: $4(3x-1) - 4(3x+3h-1) = -12h$.
> > $f^{\prime}(x) = \lim_{h\to0} \frac{-12h}{h\sqrt{3x+3h-1}\sqrt{3x-1}(2\sqrt{3x-1} + 2\sqrt{3x+3h-1})} = \frac{-12}{(3x-1)(4\sqrt{3x-1})} = -\frac{3}{(3x-1)^{3/2}}$.
> > 
> > **d) $f(x)=\frac{1}{\sqrt{x+1}}$ at $x=3$**
> > $f^{\prime}(3) = \lim_{h\to0} \frac{f(3+h) - f(3)}{h} = \lim_{h\to0} \frac{\frac{1}{\sqrt{4+h}} - \frac{1}{2}}{h} = \lim_{h\to0} \frac{2 - \sqrt{4+h}}{2h\sqrt{4+h}}$
> > Multiply by the conjugate $(2 + \sqrt{4+h})$:
> > Numerator: $4 - (4+h) = -h$.
> > $f^{\prime}(3) = \lim_{h\to0} \frac{-h}{2h\sqrt{4+h}(2+\sqrt{4+h})} = \frac{-1}{2(2)(4)} = -\frac{1}{16}$.

# 2.2 DIFFERENTIATION RULES
The method of finding the derivative of a function using the first principle is quite long and tedious working steps. In this section, we shall study the differentiation rules which will make finding the derivative of a function much simpler.

## 2.2.1 Constant Rule
Consider the function $y=a$ where a is a constant. The equation, $y=a$ represents a straight line parallel to the x-axis and the gradient is zero.
Thus, its derivative is given by: $y^{\prime}=\frac{d}{dx}(a)=0$.

## 2.2.2 Power Rule
Now, we want to differentiate a function of x to the power of something that is, $y=x^{n}$. To find its derivative, we need to bring the power in front, write back the variable and reduce the power by one, which will give $nx^{n-1}$.
Thus, if $y=x^{n}$, the derivative is given as,
> [!formula]
> $y^{\prime}=\frac{d}{dx}(x^{n})=nx^{n-1}.$

If we have a constant, k in front of x that is, $y=kx^{n}$. Then, its derivative is,
> [!formula]
> $y^{\prime}=\frac{d}{dx}(kx^{n})=knx^{n-1}.$

Remember, the power rule works for any powers: a positive, a negative, or a fraction.

## 2.2.3 Sums and Differences Rule
The terms made up of sums and differences can be differentiated term by term. If $y=u(x)\pm v(x)$, then its derivative is given by,
> [!formula]
> $y^{\prime}=\frac{d}{dx}u(x)\pm\frac{d}{dx}v(x)=u^{\prime}(x)\pm v^{\prime}(x)$.

> [!example]- Example 2.2
> Find the derivative of the following functions:
> a) $x^{6}$
> b) $\frac{2}{x^{3}}$
> c) $6x^{4}$
> d) $3x^{5}-x+4$
> e) $x^{3}+\sqrt{x}-\frac{6}{x}+8x-7$
>
> > [!continue]- Solution
> > a) $\frac{d}{dx}(x^{6})=6x^{6-1}=6x^{5}$
> > 
> > b) $\frac{d}{dx}(\frac{2}{x^{3}})=2\frac{d}{dx}(x^{-3})=2(-3x^{-3-1})=-6x^{-4}$
> > 
> > c) $\frac{d}{dx}(6x^{4})=6\frac{d}{dx}(x^{4})=6(4x^{4-1})=24x^{3}$
> > 
> > d) $\frac{d}{dx}(3x^{5}-x+4)=\frac{d}{dx}(3x^{5})-\frac{d}{dx}(x)+\frac{d}{dx}(4)=15x^{4}-1$
> > 
> > e) $\frac{d}{dx}(x^{3}+\sqrt{x}-\frac{6}{x}+8x-7)=\frac{d}{dx}(x^{3})+\frac{d}{dx}(x^{\frac{1}{2}})-\frac{d}{dx}(6x^{-1})+\frac{d}{dx}(8x)-\frac{d}{dx}(8)$
> > $=3x^{2}+\frac{1}{2\sqrt{x}}+\frac{6}{x^{2}}+8$

## 2.2.4 Chain Rule
As a motivation for the chain rule, consider we have functions such as $(x+1)^{3}$, $(1-x^{2})^{-2}$ and $\sqrt{2+x^{3}}$ which can be stated in the form of $f \circ g(x)$. These functions are known as composite functions.
How can we find its derivative? We can find its derivative by using chain rule formula,
> [!formula]
> $\frac{dy}{dx}=\frac{dy}{du}\times\frac{du}{dx}$

Let $y=f(g(x))$ and $u=g(x)$, therefore $y=f(u)$. Next, find $\frac{dy}{du}$ and $\frac{du}{dx}$ respectively, then substitute both into the chain rule formula. Then, we will get the answer in terms of u which we need to substitute back $u=g(x)$ to get the answer in terms of x.

Alternatively, if we have $y=[g(x)]^{n}$, we can use the formula below to find its derivative:
> [!formula]
> $y^{\prime}=n[g(x)]^{n-1}\times g^{\prime}(x)$.

> [!example]- Example 2.3
> Differentiate the following functions with respect to x.
> a) $y=(3x^{2}+x)^{2}$
> b) $y=\frac{1}{(x^{3}+6)^{2}}$
>
> > [!continue]- Solution
> > **a)** Let $y=(3x^{2}+x)^{2}$ with $u=3x^{2}+x\Rightarrow y=u^{2}$ gives $\frac{du}{dx}=6x+1$ and $\frac{dy}{du}=2u$
> > $\frac{dy}{dx}=\frac{dy}{du}\times\frac{du}{dx}$
> > $=(2u)(6x+1)$
> > $=2(3x^{2}+x)(6x+1)$ (Substitute $u=3x^{2}+x$)
> > $=(12x+2)(3x^{2}+x)$
> > 
> > **b)** Let $y=\frac{1}{(x^{3}+6)^{2}}=(x^{3}+6)^{-2}$ with $u=x^{3}+6\Rightarrow y=u^{-2}$ gives $\frac{du}{dx}=3x^{2}$ and $\frac{dy}{du}=-2u^{-3}$.
> > $\frac{dy}{dx}=\frac{dy}{du}\times\frac{du}{dx}$
> > $=(-2u^{-3})(3x^{2})$
> > $=\frac{-6x^{2}}{u^{3}}$
> > $=-\frac{6x^{2}}{(x^{3}+6)^{3}}$ (Substitute $u=x^{3}+6$)

## 2.2.5 Product Rule
The product rule must be utilized when the derivative of a product of two functions is to be taken.
Suppose we have $y=f(x)g(x)$, where $f(x)$ and $g(x)$ are both differentiable, then, the derivative of y is given by,
> [!formula]
> $y^{\prime}=f(x)g^{\prime}(x)+g(x)f^{\prime}(x)$.

Alternatively, from $y=f(x)g(x)$, let $u=f(x)$ and $v=g(x)$. Next, find $u^{\prime}$ and $v^{\prime}$ by differentiate u and v with respect to x. Then, substitute $u^{\prime}$ and $v^{\prime}$ into the product rule formula gives,
> [!formula]
> $y^{\prime}=uv^{\prime}+vu^{\prime}$

The product rule says that the derivative of a product of two functions is the first function times the derivative of the second function plus the second function times the derivative of the first function.

> [!example]- Example 2.4
> Differentiate the following functions with respect to x.
> a) $y=(x^{3}-1)(3x^{2}+x)$
> b) $y=x^{3}(x-2)^{-2}$
> c) $y=x^{2}(2x+1)^{\frac{1}{2}}$
>
> > [!continue]- Solution
> > **a) $y=(x^{3}-1)(3x^{2}+x)$**
> > $\frac{dy}{dx}=uv^{\prime}+vu^{\prime}$
> > $u=x^{3}-1 \quad v=3x^{2}+x$
> > $u^{\prime}=3x^{2} \quad v^{\prime}=6x+1$
> > $=(x^{3}-1)(6x+1)+(3x^{2}+x)(3x^{2})$
> > $=6x^{4}+x^{3}-6x-1+9x^{4}+3x^{3}$
> > $=15x^{4}+4x^{3}-6x-1$
> > 
> > **b) $y=x^{3}(x-2)^{-2}$**
> > $\frac{dy}{dx}=uv^{\prime}+vu^{\prime}$
> > $u=x^{3} \quad v=(x-2)^{-2}$
> > $u^{\prime}=3x^{2} \quad v^{\prime}=-2(x-2)^{-3}(1)$
> > $=(x^{3})(-2(x-2)^{-3})+((x-2)^{-2})(3x^{2})$
> > $=\frac{-2x^{3}}{(x-2)^{3}}+\frac{3x^{2}}{(x-2)^{2}}$
> > 
> > **c) $y=x^{2}(2x+1)^{\frac{1}{2}}$**
> > $\frac{dy}{dx}=uv^{\prime}+vu^{\prime}$
> > $u=x^{2} \quad v=(2x+1)^{\frac{1}{2}}$
> > $u^{\prime}=2x \quad v^{\prime}=\frac{1}{2}(2x+1)^{-\frac{1}{2}}(2) = (2x+1)^{-\frac{1}{2}}$ *(Note: Formula corrected based on standard derivation)*
> > $=(x^{2})((2x+1)^{-\frac{1}{2}})+((2x+1)^{\frac{1}{2}})(2x)$
> > $=\frac{x^{2}}{\sqrt{2x+1}}+2x\sqrt{2x+1}$

> [!sq]- Problem 2.2
> Find the derivatives for each of the following. Simplify your answer.
> a) $y=x\sqrt{9-4x^{2}}$
> b) $y=(x+4)^{3}(x^{2}-x+5)^{3}$
> c) $y=(x+4)^{4}\sqrt{x^{2}+4}$
> d) $y=\frac{1}{\sqrt{x+1}}$
>
> > [!continue]- Solution
> > **a) $y=x\sqrt{9-4x^{2}}$**
> > Let $u=x$, $v=(9-4x^2)^{1/2}$.
> > $u'=1$, $v'=\frac{1}{2}(9-4x^2)^{-1/2}(-8x) = -4x(9-4x^2)^{-1/2}$.
> > $y^{\prime} = u'v + uv' = 1(9-4x^2)^{1/2} + x(-4x(9-4x^2)^{-1/2}) = \sqrt{9-4x^2} - \frac{4x^2}{\sqrt{9-4x^2}} = \frac{9-4x^2 - 4x^2}{\sqrt{9-4x^2}} = \frac{9-8x^2}{\sqrt{9-4x^2}}$.
> > 
> > **b) $y=(x+4)^{3}(x^{2}-x+5)^{3}$**
> > Let $u=(x+4)^3$, $v=(x^2-x+5)^3$.
> > $u'=3(x+4)^2$, $v'=3(x^2-x+5)^2(2x-1)$.
> > $y^{\prime} = u'v + uv' = 3(x+4)^2(x^2-x+5)^3 + (x+4)^3(3)(x^2-x+5)^2(2x-1)$
> > Factor out $3(x+4)^2(x^2-x+5)^2$:
> > $y^{\prime} = 3(x+4)^2(x^2-x+5)^2 [ (x^2-x+5) + (x+4)(2x-1) ]$
> > Expand the bracket: $(x^2-x+5) + (2x^2+7x-4) = 3x^2+6x+1$.
> > $y^{\prime} = 3(x+4)^2(x^2-x+5)^2(3x^2+6x+1)$.
> > 
> > **c) $y=(x+4)^{4}\sqrt{x^{2}+4}$**
> > Let $u=(x+4)^4$, $v=(x^2+4)^{1/2}$.
> > $u'=4(x+4)^3$, $v'=x(x^2+4)^{-1/2}$.
> > $y^{\prime} = u'v + uv' = 4(x+4)^3(x^2+4)^{1/2} + (x+4)^4 x(x^2+4)^{-1/2}$.
> > Factor out $(x+4)^3(x^2+4)^{-1/2}$:
> > $y^{\prime} = (x+4)^3(x^2+4)^{-1/2} [ 4(x^2+4) + x(x+4) ] = \frac{(x+4)^3}{\sqrt{x^2+4}} [ 4x^2+16 + x^2+4x ] = \frac{(x+4)^3(5x^2+4x+16)}{\sqrt{x^2+4}}$.
> > 
> > **d) $y=\frac{1}{\sqrt{x+1}}$**
> > Rewrite as $y = (x+1)^{-1/2}$. Apply the power/chain rule:
> > $y^{\prime} = -\frac{1}{2}(x+1)^{-3/2}(1) = -\frac{1}{2(x+1)^{3/2}}$.

## 2.2.6 Quotient Rule
The quotient rule must be utilized when the derivative of a quotient of two functions is to be taken.
Suppose we have $y=\frac{f(x)}{g(x)}$, where $f(x)$ and $g(x)$ are both differentiable functions and $g(x)\ne0$, then the derivative of y is given as,
> [!formula]
> $y^{\prime}=\frac{g(x)f^{\prime}(x)-f(x)g^{\prime}(x)}{[g(x)]^{2}}.$

Alternatively, from $y=\frac{f(x)}{g(x)}, g(x)\ne0,$ let $u=f(x)$ and $v=g(x)$. Next, find $u^{\prime}$ and $v^{\prime}$ by differentiating u and v with respect to x. Then, substitute $u^{\prime}$ and $v^{\prime}$ into the quotient formula, which gives
> [!formula]
> $y^{\prime}=\frac{vu^{\prime}-uv^{\prime}}{v^{2}}$

The quotient rule says that the derivative of a quotient is the denominator times the derivative of the numerator minus the numerator times the derivative of the denominator, all divided by the square of the denominator.

> [!example]- Example 2.5
> Differentiate the following function with respect to x.
> a) $y=\frac{x+2}{x+3}$
> b) $y=\frac{2x^{2}-1}{x^{2}+2}$
> c) $y=\frac{1+\sqrt{x}}{1-\sqrt{x}}$
>
> > [!continue]- Solution
> > **a) $y=\frac{x+2}{x+3}$**
> > $u=x+2$ \quad $u^{\prime}=1$
> > $v=x+3$ \quad $v^{\prime}=1$
> > $\frac{dy}{dx}=\frac{vu^{\prime}-uv^{\prime}}{v^{2}}$
> > $=\frac{(x+3)(1)-(x+2)(1)}{(x+3)^{2}}$
> > $=\frac{1}{(x+3)^{2}}$
> > 
> > **b) $y=\frac{2x^{2}-1}{x^{2}+2}$**
> > $u=2x^{2}-1$ \quad $u^{\prime}=4x$
> > $v=x^{2}+2$ \quad $v^{\prime}=2x$
> > $\frac{dy}{dx}=\frac{vu^{\prime}-uv^{\prime}}{v^{2}}$
> > $=\frac{(x^{2}+2)(4x)-(2x^{2}-1)(2x)}{(x^{2}+2)^{2}}$
> > $=\frac{10x}{(x^{2}+2)^{2}}$
> > 
> > **c) $y=\frac{1+\sqrt{x}}{1-\sqrt{x}}$**
> > $u=1+\sqrt{x}$ \quad $u^{\prime}=\frac{1}{2\sqrt{x}}$
> > $v=1-\sqrt{x}$ \quad $v^{\prime}=-\frac{1}{2\sqrt{x}}$
> > $\frac{dy}{dx}=\frac{vu^{\prime}-uv^{\prime}}{v^{2}}$
> > $=\frac{(1-\sqrt{x})(\frac{1}{2\sqrt{x}})-(1+\sqrt{x})(-\frac{1}{2\sqrt{x}})}{(1-\sqrt{x})^{2}}$
> > $=\frac{2}{2\sqrt{x}(1-\sqrt{x})^{2}}=\frac{1}{\sqrt{x}(1-\sqrt{x})^{2}}$

> [!sq]- Problem 2.3
> Differentiate the following function with respect to x.
> a) $y=\frac{x+1}{1-2x}$
> b) $y=\frac{x^{2}+x+1}{x^{2}-x+1}$
> c) $y=\frac{3x^{2}+1}{(1-3x)^{2}}$
>
> > [!continue]- Solution
> > **a) $y=\frac{x+1}{1-2x}$**
> > $u = x+1 \Rightarrow u' = 1$
> > $v = 1-2x \Rightarrow v' = -2$
> > $y' = \frac{(1-2x)(1) - (x+1)(-2)}{(1-2x)^2} = \frac{1-2x + 2x + 2}{(1-2x)^2} = \frac{3}{(1-2x)^2}$
> > 
> > **b) $y=\frac{x^{2}+x+1}{x^{2}-x+1}$**
> > $u = x^2+x+1 \Rightarrow u' = 2x+1$
> > $v = x^2-x+1 \Rightarrow v' = 2x-1$
> > $y' = \frac{(x^2-x+1)(2x+1) - (x^2+x+1)(2x-1)}{(x^2-x+1)^2}$
> > $= \frac{(2x^3 - 2x^2 + 2x + x^2 - x + 1) - (2x^3 + 2x^2 + 2x - x^2 - x - 1)}{(x^2-x+1)^2}$
> > $= \frac{(2x^3 - x^2 + x + 1) - (2x^3 + x^2 + x - 1)}{(x^2-x+1)^2} = \frac{-2x^2 + 2}{(x^2-x+1)^2}$
> > 
> > **c) $y=\frac{3x^{2}+1}{(1-3x)^{2}}$**
> > $u = 3x^2+1 \Rightarrow u' = 6x$
> > $v = (1-3x)^2 \Rightarrow v' = 2(1-3x)(-3) = -6(1-3x)$
> > $y' = \frac{(1-3x)^2(6x) - (3x^2+1)(-6(1-3x))}{(1-3x)^4} = \frac{6(1-3x)[x(1-3x) + (3x^2+1)]}{(1-3x)^4}$
> > $= \frac{6[x - 3x^2 + 3x^2 + 1]}{(1-3x)^3} = \frac{6(x+1)}{(1-3x)^3}$

> [!sq]- Problem 2.4
> Find $f^{\prime}(x)$ for each of the following. Simplify your answer.
> a) $f(x)=\frac{\sqrt{x+1}}{3-2x}$
> b) $f(x)=\frac{2}{\sqrt{x}+3}$
>
> > [!continue]- Solution
> > **a) $f(x)=\frac{\sqrt{x+1}}{3-2x}$**
> > $u = (x+1)^{1/2} \Rightarrow u' = \frac{1}{2\sqrt{x+1}}$
> > $v = 3-2x \Rightarrow v' = -2$
> > $f'(x) = \frac{(3-2x)(\frac{1}{2\sqrt{x+1}}) - \sqrt{x+1}(-2)}{(3-2x)^2} = \frac{\frac{3-2x}{2\sqrt{x+1}} + 2\sqrt{x+1}}{(3-2x)^2}$
> > $= \frac{(3-2x) + 4(x+1)}{2\sqrt{x+1}(3-2x)^2} = \frac{3-2x+4x+4}{2\sqrt{x+1}(3-2x)^2} = \frac{2x+7}{2\sqrt{x+1}(3-2x)^2}$
> > 
> > **b) $f(x)=\frac{2}{\sqrt{x}+3}$**
> > Using the chain rule: $f(x) = 2(x^{1/2}+3)^{-1}$
> > $f'(x) = -2(x^{1/2}+3)^{-2}(\frac{1}{2}x^{-1/2}) = -\frac{1}{\sqrt{x}(\sqrt{x}+3)^2}$

# 2.3 DIFFERENTIATION OF TRIGONOMETRIC, EXPONENTIAL AND LOGARITHMIC FUNCTIONS
It is possible to find the derivative of trigonometric functions. Here is a list of the derivatives that we need to know:

## **I - Derivative of Trigonometric Functions**
i. $\frac{d}{dx}(\sin x)=\cos x$
ii. $\frac{d}{dx}(\cos x)=-\sin x$
iii. $\frac{d}{dx}(\tan x)=\sec^{2}x$
iv. $\frac{d}{dx}(\sec x)=\sec x \tan x$
v. $\frac{d}{dx}(\csc x)=-\csc x \cot x$
vi. $\frac{d}{dx}(\cot x)=-\csc^{2}x$
(Note: Cosecant is usually abbreviated as cosec or csc)

The product rule and quotient rule can be also applied here. In the case of finding the derivatives of trigonometric function to the $n^{th}$ power, the formula is:
If $y=\tan^{n}u$, then $y^{\prime}=n \tan^{n-1}u \sec^{2}u \frac{d}{dx}(u)$ where u can be any function of x.

> [!example]- Example 2.6
> Differentiate the following functions with respect to x.
> a) $y=\sin 3x$
> b) $f(x)=\sec 4x$
> c) $y=\sin(\frac{1}{2}x+4)$
> d) $f(x)=\cos(2-x)$
> e) $y=6\tan\frac{1}{3}x$
> f) $y=\tan^{4}(3x-2)$
> g) $y=\frac{\cos x}{1-\cos x}$
>
> > [!continue]- Solution
> > a) $\frac{dy}{dx}=[\frac{d}{dx}(\sin 3x)][\frac{d}{dx}(3x)]=(\cos 3x)(3)=3\cos 3x$
> > 
> > b) $f^{\prime}(x)=[\frac{d}{dx}(\sec 4x)][\frac{d}{dx}(4x)]=(\sec 4x \tan 4x)(4)=4\sec 4x \tan 4x$
> > 
> > c) $\frac{dy}{dx}=[\frac{d}{dx}(\sin(\frac{1}{2}x+4))][\frac{d}{dx}(\frac{1}{2}x+4)]=[\cos(\frac{1}{2}x+4)](\frac{1}{2})=\frac{1}{2}\cos(\frac{1}{2}x+4).$
> > 
> > d) $f^{\prime}(x)=[\frac{d}{dx}(\cos(2-x))][\frac{d}{dx}(2-x)]=[-\sin(2-x)](-1)=\sin(2-x)$
> > 
> > e) $\frac{dy}{dx}=[\frac{d}{dx}(6\tan\frac{1}{3}x)][\frac{d}{dx}(\frac{1}{3}x)]=[6(\sec^{2}\frac{1}{3}x)](\frac{1}{3})=2\sec^{2}\frac{1}{3}x$
> > 
> > f) $\frac{dy}{dx}=[\frac{d}{dx}(\tan^{4}(3x-2))][\frac{d}{dx}(3x-2)]=12\tan^{3}(3x-2)\sec^{2}(3x-2)$
> > 
> > g) $\frac{dy}{dx}=\frac{(1-\cos x)(-\sin x)-\cos x(\sin x)}{(1-\cos x)^{2}}=-\frac{\sin x}{(1-\cos x)^{2}}$

> [!sq]- Problem 2.5
> Find $\frac{dy}{dx}$ for the following functions with respect to x:
> a) $y=\cos(x^{2}+\sin x)$
> b) $y=\frac{\sin x}{2+\sin 2x}$
> c) $y=\sec(\frac{x+1}{1+x^{2}})$
>
> > [!continue]- Solution
> > **a) $y=\cos(x^{2}+\sin x)$**
> > $\frac{dy}{dx} = -\sin(x^2+\sin x) \cdot \frac{d}{dx}(x^2+\sin x) = -\sin(x^2+\sin x)(2x+\cos x)$
> > 
> > **b) $y=\frac{\sin x}{2+\sin 2x}$**
> > $u = \sin x \Rightarrow u' = \cos x$
> > $v = 2+\sin 2x \Rightarrow v' = 2\cos 2x$
> > $\frac{dy}{dx} = \frac{(2+\sin 2x)(\cos x) - (\sin x)(2\cos 2x)}{(2+\sin 2x)^2} = \frac{2\cos x + \sin 2x\cos x - 2\sin x\cos 2x}{(2+\sin 2x)^2}$
> > 
> > **c) $y=\sec(\frac{x+1}{1+x^{2}})$**
> > Let $u = \frac{x+1}{1+x^2} \Rightarrow u' = \frac{(1+x^2)(1) - (x+1)(2x)}{(1+x^2)^2} = \frac{1+x^2-2x^2-2x}{(1+x^2)^2} = \frac{1-2x-x^2}{(1+x^2)^2}$
> > $\frac{dy}{dx} = \sec(\frac{x+1}{1+x^2})\tan(\frac{x+1}{1+x^2}) \cdot (\frac{1-2x-x^2}{(1+x^2)^2})$

## **II - Derivative of Exponential Functions**
If we have a function $y=e^{f(x)}$, first, we let $u=f(x)$ which gives $y=e^{u}$. Thus, the derivative is given as below,
> [!formula]
> $y^{\prime}=\frac{d}{dx}(e^{u})=e^{u}\times\frac{du}{dx}$

Let us begin with the simplest exponential function, $y=e^{x}$. To find its derivative,
$y^{\prime}=e^{x}\times\frac{d}{dx}(x)=e^{x}\times 1=e^{x}$
Remember this, so that we do not need to derive it again next time.

> [!example]- Example 2.7
> Differentiate the following functions with respect to x.
> a) $y=e^{3x}$
> b) $y=e^{-2x+3}$
> c) $y=e^{x^{2}-2}$
> d) $y=e^{5x+\cos x}$
> e) $y=\cos x(e^{\sin x})$
> f) $y=\frac{e^{-x}}{\sin 3x}$
>
> > [!continue]- Solution
> > a) $\frac{dy}{dx}=\frac{d}{dx}(e^{3x})=(e^{3x})\times\frac{d}{dx}(3x)=3e^{3x}$
> > 
> > b) $\frac{dy}{dx}=\frac{d}{dx}(e^{-2x+3})=(e^{-2x+3})\times\frac{d}{dx}(-2x+3)=-2e^{-2x+3}$
> > 
> > c) $\frac{dy}{dx}=\frac{d}{dx}(e^{x^{2}-2})=(e^{x^{2}-2})\times\frac{d}{dx}(x^{2}-2)=2xe^{x^{2}-2}$ *(Note: Corrected $3x^{2}$ to $2x$ and $e^{x^{3}-2}$ to $e^{x^{2}-2}$ from source text to match question).*
> > 
> > d) $\frac{dy}{dx}=\frac{d}{dx}(e^{5x+\cos x})=(e^{5x+\cos x})\times\frac{d}{dx}(5x+\cos x)=(5-\sin x)(e^{5x+\cos x})$
> > 
> > e) $\frac{dy}{dx}=\frac{d}{dx}(\cos x(e^{\sin x}))=\cos x(\cos x e^{\sin x})+e^{\sin x}(-\sin x)=e^{\sin x}(\cos^{2}x-\sin x)$
> > 
> > f) $\frac{dy}{dx}=\frac{d}{dx}(\frac{e^{-x}}{\sin 3x})=\frac{\sin 3x(-e^{-x})-e^{-x}(3\cos 3x)}{\sin^{2}3x}=\frac{e^{-x}(-\sin 3x-3\cos 3x)}{\sin^{2}3x}$

> [!sq]- Problem 2.6
> a) Find $\frac{dy}{dx}$ for the following functions with respect to x:
> i. $y=\tan^{3}(\frac{x}{e^{x}})$
> ii. $y=\frac{xe^{x}}{1+x^{2}}$
> b) If $y=\frac{e^{-x}}{1+x^{2}}$ show that $(1+x^{2})y^{\prime}+(1+x)^{2}y=0$.
>
> > [!continue]- Solution
> > **a) i. $y=\tan^{3}(\frac{x}{e^{x}})$**
> > Let $u = xe^{-x}$. $u' = 1(e^{-x}) + x(-e^{-x}) = e^{-x}(1-x)$.
> > $\frac{dy}{dx} = 3\tan^2(xe^{-x}) \sec^2(xe^{-x}) \cdot (e^{-x}(1-x))$.
> > 
> > **a) ii. $y=\frac{xe^{x}}{1+x^{2}}$**
> > $u = xe^x \Rightarrow u' = 1(e^x) + x(e^x) = e^x(1+x)$.
> > $v = 1+x^2 \Rightarrow v' = 2x$.
> > $\frac{dy}{dx} = \frac{(1+x^2)(e^x(1+x)) - xe^x(2x)}{(1+x^2)^2} = \frac{e^x[(1+x^2)(1+x) - 2x^2]}{(1+x^2)^2} = \frac{e^x[1+x+x^2+x^3-2x^2]}{(1+x^2)^2} = \frac{e^x(x^3-x^2+x+1)}{(1+x^2)^2}$.
> > 
> > **b) If $y=\frac{e^{-x}}{1+x^{2}}$, show $(1+x^{2})y^{\prime}+(1+x)^{2}y=0$**
> > $y' = \frac{(1+x^2)(-e^{-x}) - e^{-x}(2x)}{(1+x^2)^2} = \frac{-e^{-x}(1+x^2+2x)}{(1+x^2)^2} = \frac{-e^{-x}(1+x)^2}{(1+x^2)^2}$.
> > Substitute $y$ and $y'$ into LHS:
> > $(1+x^2)\left[\frac{-e^{-x}(1+x)^2}{(1+x^2)^2}\right] + (1+x)^2 \left[\frac{e^{-x}}{1+x^2}\right]$
> > $= \frac{-e^{-x}(1+x)^2}{1+x^2} + \frac{e^{-x}(1+x)^2}{1+x^2} = 0 = \text{RHS}$. Shown.

## **III - Derivative of Logarithmic Functions**
Derivatives of logarithmic functions are mainly based on the chain rule. Here, we only focus on logarithmic functions to the base e and is called natural logarithms. Usually, we write the natural logarithms using $\ln$. For example, $\ln x=\log_{e}x$ that is log to the base e.

If we have a function $y=\ln[f(x)]$. First, we let $u=f(x)$ gives $y=\ln[u]$. Thus, the derivative is given as, $y^{\prime}=\frac{d}{dx}[\ln(u)]=\frac{1}{u}\times\frac{du}{dx}.$

Let us begin with the simplest exponential function, $y=\ln x$. To find its derivative, $y^{\prime}=\frac{1}{x}\times\frac{d}{dx}(x)=\frac{1}{x}\times 1=\frac{1}{x}$. Remember this, so that we do not need to derive it again next time.

> [!example]- Example 2.8
> Differentiate the following function with respect to x.
> a) $y=\ln(3x)$
> b) $y=\ln(3+4x)$
> c) $y=\ln(x^{2}+2x)$
> d) $y=\ln(1+3x)^{2}$
> e) $y=\ln(x^{2}+\sin x)$
> f) $y=\ln(\frac{3-x}{3+x})^{\frac{1}{2}}$
>
> > [!continue]- Solution
> > a) $\frac{d}{dx}(\ln 3x)=\frac{1}{3x}\times\frac{d}{dx}(3x)=\frac{1}{x}$
> > 
> > b) $\frac{d}{dx}(\ln(3+4x))=\frac{1}{3+4x}\times\frac{d}{dx}(3+4x)=\frac{4}{3+4x}$
> > 
> > c) $\frac{d}{dx}(\ln(x^{2}+2x))=\frac{1}{x^{2}+2x}\times\frac{d}{dx}(x^{2}+2x)=\frac{2x+2}{x^{2}+2x}$
> > 
> > d) $\frac{d}{dx}(\ln(1+3x)^{2})=\frac{d}{dx}[2\ln(1+3x)]=\frac{2}{1+3x}\times\frac{d}{dx}(1+3x)=\frac{6}{1+3x}$
> > 
> > e) $\frac{d}{dx}(\ln(x^{2}+\sin x))=\frac{1}{x^{2}+\sin x}\times\frac{d}{dx}(x^{2}+\sin x)=\frac{2x+\cos x}{x^{2}+\sin x}$
> > 
> > f) $\frac{d}{dx}[\ln(\frac{3-x}{3+x})^{\frac{1}{2}}]=\frac{d}{dx}[\frac{1}{2}[\ln(3-x)-\ln(3+x)]]=\frac{1}{2}[\frac{1}{3-x}(-1)-\frac{1}{3+x}(1)]$
> > $=\frac{1}{2}[\frac{-3-x-3+x}{(3-x)(3+x)}] = \frac{1}{2}[\frac{-6}{9-x^2}] = \frac{-3}{9-x^2} = \frac{3}{x^{2}-9}$

> [!example]- Example 2.9
> Given $y=\ln(x\sin 2x)$, find $\frac{dy}{dx}$. Give your answer in the simplest form.
>
> > [!continue]- Solution
> > $\frac{dy}{dx}=\frac{1}{x\sin 2x}\times\frac{d}{dx}(x\sin 2x)$
> > $u=x$, $v=\sin 2x \Rightarrow u^{\prime}=1$, $v^{\prime}=2\cos 2x$. Using $\frac{dy}{dx}=uv^{\prime}+vu^{\prime}$:
> > $\frac{d}{dx}(x\sin 2x) = (x)(2\cos 2x)+(\sin 2x)(1) = 2x\cos 2x+\sin 2x$
> > $\frac{dy}{dx}=\frac{1}{x\sin 2x}(2x\cos 2x+\sin 2x)$
> > $=\frac{2x\cos 2x+\sin 2x}{x\sin 2x}$
> > $=\frac{2x\cos 2x}{x\sin 2x}+\frac{\sin 2x}{x\sin 2x}$
> > $=2\cot 2x+\frac{1}{x}$

> [!example]- Example 2.10
> If $f(x)=\ln(x^{2}e^{x})$, find and simplify $f^{\prime}(x)$.
>
> > [!continue]- Solution
> > $f^{\prime}(x)=\frac{1}{x^{2}e^{x}}\times\frac{d}{dx}(x^{2}e^{x})$
> > $u=x^{2}$, $v=e^{x} \Rightarrow u^{\prime}=2x$, $v^{\prime}=e^{x}$. Using $\frac{dy}{dx}=uv^{\prime}+vu^{\prime}$:
> > $\frac{d}{dx}(x^{2}e^{x}) = (x^{2})(e^{x})+(e^{x})(2x) = x^{2}e^{x}+2xe^{x}$
> > $f^{\prime}(x)=\frac{1}{x^{2}e^{x}}(x^{2}e^{x}+2xe^{x})$
> > $=\frac{x^{2}e^{x}+2xe^{x}}{x^{2}e^{x}}$
> > $=\frac{x^{2}e^{x}}{x^{2}e^{x}}+\frac{2xe^{x}}{x^{2}e^{x}}=1+\frac{2}{x}$

> [!sq]- Problem 2.7
> Find $\frac{dy}{dx}$ for the following functions with respect to x:
> a) $y=2x^{2}e^{\sin 3x}$
> b) $y=\ln(x^{3}\sin e^{2x})$
> c) $f(x)=\sec(\frac{x+1}{1+x^{2}})$
> d) $f(x)=\frac{\ln x}{3-2x}$
> e) $y=x^{2}\ln x$
> f) $y=\frac{\ln 4x}{2x^{2}+1}$
>
> > [!continue]- Solution
> > **a) $y=2x^{2}e^{\sin 3x}$**
> > $y' = 4x e^{\sin 3x} + 2x^2 e^{\sin 3x}(\cos 3x)(3) = 2xe^{\sin 3x}(2 + 3x\cos 3x)$
> > 
> > **b) $y=\ln(x^{3}\sin e^{2x})$**
> > Using log properties: $y = \ln(x^3) + \ln(\sin e^{2x}) = 3\ln x + \ln(\sin e^{2x})$.
> > $y' = 3(\frac{1}{x}) + \frac{1}{\sin e^{2x}}(\cos e^{2x})(2e^{2x}) = \frac{3}{x} + 2e^{2x}\cot(e^{2x})$
> > 
> > **c) $f(x)=\sec(\frac{x+1}{1+x^{2}})$**
> > Let $u = \frac{x+1}{1+x^2} \Rightarrow u' = \frac{(1+x^2)(1) - (x+1)(2x)}{(1+x^2)^2} = \frac{1-2x-x^2}{(1+x^2)^2}$.
> > $f'(x) = \sec(\frac{x+1}{1+x^2})\tan(\frac{x+1}{1+x^2}) \cdot (\frac{1-2x-x^2}{(1+x^2)^2})$
> > 
> > **d) $f(x)=\frac{\ln x}{3-2x}$**
> > $f'(x) = \frac{(3-2x)(\frac{1}{x}) - (\ln x)(-2)}{(3-2x)^2} = \frac{\frac{3-2x}{x} + 2\ln x}{(3-2x)^2} = \frac{3-2x+2x\ln x}{x(3-2x)^2}$
> > 
> > **e) $y=x^{2}\ln x$**
> > $y' = 2x(\ln x) + x^2(\frac{1}{x}) = 2x\ln x + x = x(2\ln x + 1)$
> > 
> > **f) $y=\frac{\ln 4x}{2x^{2}+1}$**
> > $y' = \frac{(2x^2+1)(\frac{1}{4x}\cdot 4) - (\ln 4x)(4x)}{(2x^2+1)^2} = \frac{\frac{2x^2+1}{x} - 4x\ln 4x}{(2x^2+1)^2} = \frac{2x^2+1 - 4x^2\ln 4x}{x(2x^2+1)^2}$

> [!sq]- Problem 2.8
> If $y=x^{n}\ln x$ show that $xy^{\prime}=ny+x^{n}$.
>
> > [!continue]- Solution
> > First, find $y'$ using product rule on $y = x^n \ln x$:
> > $y' = (nx^{n-1})(\ln x) + (x^n)(\frac{1}{x}) = nx^{n-1}\ln x + x^{n-1}$.
> > Now, substitute $y'$ into the left-hand side (LHS):
> > $LHS = x y' = x(nx^{n-1}\ln x + x^{n-1}) = nx^n\ln x + x^n$.
> > Since $y = x^n\ln x$, substitute this into the equation:
> > $LHS = n(y) + x^n = ny + x^n = RHS$. Shown.

# 2.4 HIGHER ORDER DIFFERENTIATIONS
Suppose we have $y=f(x)$. When differentiating y with respect to x, we will get $\frac{dy}{dx}=\frac{d}{dx}[f(x)]=f^{\prime}(x)$, which is known as the first derivative of f.
Then, we differentiate $\frac{dy}{dx}$ with respect to x, to obtain the second derivative of f which can be written as $\frac{d}{dx}(\frac{dy}{dx})=\frac{d^{2}y}{dx^{2}}=f^{\prime\prime}(x)$.
The third derivative, denoted by $\frac{d^{3}y}{dx^{3}}$ or $f^{\prime\prime\prime}(x)$ is obtained by differentiating $\frac{d^{2}y}{dx^{2}}$ with respect to x. This process can be continued to find the higher order differentiations.

We can write the order of differentiation of $f(x)$ as follows:
$\frac{dy}{dx}=\frac{d}{dx}[f(x)]=f^{\prime}(x)$
$\frac{d^{2}y}{dx^{2}}=\frac{d}{dx}(\frac{dy}{dx})=f^{\prime\prime}(x)$
$\frac{d^{3}y}{dx^{3}}=\frac{d}{dx}[\frac{d}{dx}(\frac{dy}{dx})]=f^{\prime\prime\prime}(x)$
$\frac{d^{4}y}{dx^{4}}=\frac{d}{dx}[\frac{d}{dx}[\frac{d}{dx}(\frac{dy}{dx})]]=f^{(4)}(x)$
$\frac{d^{5}y}{dx^{5}}=\frac{d}{dx}[\frac{d}{dx}[\frac{d}{dx}[\frac{d}{dx}(\frac{dy}{dx})]]]=f^{(5)}(x)$

> [!example]- Example 2.11
> If $f(x)=4x^{4}-2x^{3}+3$ find its first five derivatives.
>
> > [!continue]- Solution
> > $f^{\prime}(x)=16x^{3}-6x^{2}$
> > $f^{\prime\prime}(x)=48x^{2}-12x$
> > $f^{\prime\prime\prime}(x)=96x-12$
> > $f^{(4)}(x)=96$
> > $f^{(5)}(x)=0$

> [!example]- Example 2.12
> Find $y^{\prime}$ and $y^{\prime\prime}$ for $y=(x^{3}+5)(3x+2)$.
>
> > [!continue]- Solution
> > $y=(x^{3}+5)(3x+2)$
> > $y^{\prime}=(x^{3}+5)(3)+(3x+2)(3x^{2})$
> > $=12x^{3}+6x^{2}+15$
> > $y^{\prime\prime}=\frac{d}{dx}[12x^{3}+6x^{2}+15]=36x^{2}+12x$

> [!example]- Example 2.13
> If $y=\frac{x^{2}}{x-2}$ find $y^{\prime}$ and $y^{\prime\prime}$. Give your answer in the simplest form.
>
> > [!continue]- Solution
> > $y^{\prime}=\frac{d}{dx}[y]=\frac{d}{dx}[\frac{x^{2}}{x-2}]$
> > $u=x^{2} \Rightarrow u^{\prime}=2x$, $v=x-2 \Rightarrow v^{\prime}=1$
> > $=\frac{(x-2)(2x)-(x^{2})(1)}{(x-2)^{2}}=\frac{x^{2}-4x}{(x-2)^{2}}$
> > 
> > $y^{\prime\prime}=\frac{d}{dx}[y^{\prime}]=\frac{d}{dx}[\frac{x^{2}-4x}{(x-2)^{2}}]$
> > $u=x^{2}-4x \Rightarrow u^{\prime}=2x-4$, $v=(x-2)^{2} \Rightarrow v^{\prime}=2(x-2)$
> > $=\frac{(x-2)^{2}(2x-4)-(x^{2}-4x)(2)(x-2)}{[(x-2)^{2}]^{2}}$
> > $=\frac{(x-2)[(x-2)(2x-4)-(x^{2}-4x)(2)]}{(x-2)^{4}}=\frac{8}{(x-2)^{3}}$

> [!sq]- Problem 2.9
> Find the second deriv byative of each of the following functions.
> a) $y=2x^{3}+\frac{1}{x}$
> b) $y=\sqrt{x^{2}-2x}$
> c) $y=\frac{1}{\sqrt{2x^{2}-1}}$
>
> > [!continue]- Solution
> > **a) $y=2x^{3}+\frac{1}{x}$**
> > Rewrite as $y = 2x^3 + x^{-1}$.
> > First derivative: $\frac{dy}{dx} = 6x^2 - x^{-2}$.
> > Second derivative: $\frac{d^2y}{dx^2} = 12x + 2x^{-3} = 12x + \frac{2}{x^3}$.
> > 
> > **b) $y=\sqrt{x^{2}-2x}$**
> > Rewrite as $y = (x^2-2x)^{1/2}$.
> > First derivative: $\frac{dy}{dx} = \frac{1}{2}(x^2-2x)^{-1/2}(2x-2) = (x-1)(x^2-2x)^{-1/2}$.
> > Second derivative (using product rule):
> > Let $u = x-1 \Rightarrow u' = 1$.
> > Let $v = (x^2-2x)^{-1/2} \Rightarrow v' = -\frac{1}{2}(x^2-2x)^{-3/2}(2x-2) = -(x-1)(x^2-2x)^{-3/2}$.
> > $\frac{d^2y}{dx^2} = u'v + uv' = (1)(x^2-2x)^{-1/2} + (x-1)[-(x-1)(x^2-2x)^{-3/2}]$
> > $= \frac{1}{\sqrt{x^2-2x}} - \frac{(x-1)^2}{(x^2-2x)^{3/2}} = \frac{(x^2-2x) - (x^2-2x+1)}{(x^2-2x)^{3/2}} = -\frac{1}{(x^2-2x)^{3/2}}$.
> > 
> > **c) $y=\frac{1}{\sqrt{2x^{2}-1}}$**
> > Rewrite as $y = (2x^2-1)^{-1/2}$.
> > First derivative: $\frac{dy}{dx} = -\frac{1}{2}(2x^2-1)^{-3/2}(4x) = -2x(2x^2-1)^{-3/2}$.
> > Second derivative (using product rule):
> > Let $u = -2x \Rightarrow u' = -2$.
> > Let $v = (2x^2-1)^{-3/2} \Rightarrow v' = -\frac{3}{2}(2x^2-1)^{-5/2}(4x) = -6x(2x^2-1)^{-5/2}$.
> > $\frac{d^2y}{dx^2} = u'v + uv' = -2(2x^2-1)^{-3/2} + (-2x)[-6x(2x^2-1)^{-5/2}]$
> > $= \frac{-2}{(2x^2-1)^{3/2}} + \frac{12x^2}{(2x^2-1)^{5/2}} = \frac{-2(2x^2-1) + 12x^2}{(2x^2-1)^{5/2}} = \frac{8x^2+2}{(2x^2-1)^{5/2}}$.

> [!sq]- Problem 2.10
> If $y=3x^{2}-5x$ show that $y\frac{d^{2}y}{dx^{2}}+\frac{dy}{dx}-6y+5=6x$.
>
> > [!continue]- Solution
> > Find the first and second derivatives of $y = 3x^2 - 5x$:
> > $\frac{dy}{dx} = 6x - 5$
> > $\frac{d^2y}{dx^2} = 6$
> > 
> > Substitute $y$, $\frac{dy}{dx}$, and $\frac{d^2y}{dx^2}$ into the left-hand side (LHS) of the equation:
> > LHS = $y\left(\frac{d^2y}{dx^2}\right) + \frac{dy}{dx} - 6y + 5$
> > $= (3x^2 - 5x)(6) + (6x - 5) - 6(3x^2 - 5x) + 5$
> > $= 18x^2 - 30x + 6x - 5 - 18x^2 + 30x + 5$
> > Group the terms:
> > $= (18x^2 - 18x^2) + (-30x + 30x + 6x) + (-5 + 5)$
> > $= 6x$.
> > Since LHS = RHS, it is shown.

## 2.5 IMPLICIT DIFFERENTIATIONS
To this point we have done quite a few derivatives, but they have all been derivatives of functions of the form $y=f(x)$. Unfortunately, not all the functions that we are going to look at will fall into this form, but rather in a more complicated form, which is difficult or impossible to express y explicitly in terms of x.

Such functions are called implicit functions. For examples:
$x^{2}+y^{2}+2y-3x+5=0$ and $xy+\ln(x^{2}+y^{2})=0$.

To find the derivatives of implicit functions, we will use the same concepts and rules as we differentiate the functions of x with respect to x, but we must remember one rule. Every time we are differentiating the functions of y with respect to x, we need to multiply with $\frac{dy}{dx}$ because we treat y as a function of x.

There are three steps involved to do implicit differentiation:
* **Step 1:** Differentiate with respect to x.
* **Step 2:** Collect all $\frac{dy}{dx}$ terms on one side.
* **Step 3:** Solve for $\frac{dy}{dx}$.

> [!example]- Example 2.15
> Find $\frac{dy}{dx}$ for the following functions.
> a) $4x+y^{3}=2y+x^{2}+8$
> b) $y^{2}+xy-x^{2}=2$
> c) $\sin(x+y)=x^{6}+3xy$
>
> > [!continue]- Solution
> > **a) From $4x+y^{3}=2y+x^{2}+8$, we are differentiating implicitly with respect to x,**
> > $\frac{d}{dx}(4x)+\frac{d}{dx}(y^{3})=\frac{d}{dx}(2y)+\frac{d}{dx}(x^{2})+\frac{d}{dx}(8)$
> > $4+3y^{2}\frac{dy}{dx}=2\frac{dy}{dx}+2x$
> > $3y^{2}\frac{dy}{dx}-2\frac{dy}{dx}=2x-4$
> > $\frac{dy}{dx}(3y^{2}-2)=2x-4 \Rightarrow \frac{dy}{dx}=\frac{2x-4}{3y^{2}-2}$
> > 
> > **b) From $y^{2}+xy-x^{2}=2$, we are differentiating implicitly with respect to x,**
> > $\frac{d}{dx}(y^{2})+\frac{d}{dx}(xy)-\frac{d}{dx}(x^{2})=\frac{d}{dx}(2)$
> > $2y\frac{dy}{dx}+(x\frac{dy}{dx}+y)-2x=0$
> > $2y\frac{dy}{dx}+x\frac{dy}{dx}=2x-y$
> > $\frac{dy}{dx}(2y+x)=2x-y \Rightarrow \frac{dy}{dx}=\frac{2x-y}{2y+x}$
> > 
> > **c) From $\sin(x+y)=x^{6}+3xy$, we are differentiating implicitly with respect to x,**
> > $\frac{d}{dx}(\sin(x+y))=\frac{d}{dx}(x^{6})+\frac{d}{dx}(3xy)$
> > $\cos(x+y)\left(1+\frac{dy}{dx}\right)=6x^{5}+\left(3x\frac{dy}{dx}+3y\right)$
> > $\cos(x+y)+\cos(x+y)\frac{dy}{dx}=6x^{5}+3x\frac{dy}{dx}+3y$
> > $\cos(x+y)\frac{dy}{dx}-3x\frac{dy}{dx}=6x^{5}+3y-\cos(x+y)$
> > $\frac{dy}{dx}[\cos(x+y)-3x]=6x^{5}+3y-\cos(x+y) \Rightarrow \frac{dy}{dx}=\frac{6x^{5}+3y-\cos(x+y)}{\cos(x+y)-3x}$

> [!sq]- Problem 2.11
> Find $\frac{dy}{dx}$ for $2y\ln x^{2}+3x^{2}=2\tan(x-y)-e^{x^{2}}$ by using implicit differentiation.
>
> > [!continue]- Solution
> > Let's simplify the first term: $2y\ln x^2 = 4y\ln x$.
> > Differentiate both sides with respect to x:
> > $\frac{d}{dx}(4y\ln x) + \frac{d}{dx}(3x^2) = \frac{d}{dx}(2\tan(x-y)) - \frac{d}{dx}(e^{x^2})$
> > Apply product rule and chain rule:
> > $\left(4y\cdot\frac{1}{x} + 4\ln x \frac{dy}{dx}\right) + 6x = 2\sec^2(x-y)\left(1 - \frac{dy}{dx}\right) - 2xe^{x^2}$
> > $\frac{4y}{x} + 4\ln x \frac{dy}{dx} + 6x = 2\sec^2(x-y) - 2\sec^2(x-y)\frac{dy}{dx} - 2xe^{x^2}$
> > Collect $\frac{dy}{dx}$ terms on one side:
> > $4\ln x \frac{dy}{dx} + 2\sec^2(x-y)\frac{dy}{dx} = 2\sec^2(x-y) - 2xe^{x^2} - 6x - \frac{4y}{x}$
> > $\frac{dy}{dx} \left(4\ln x + 2\sec^2(x-y)\right) = 2\sec^2(x-y) - 2xe^{x^2} - 6x - \frac{4y}{x}$
> > $\frac{dy}{dx} = \frac{2\sec^2(x-y) - 2xe^{x^2} - 6x - \frac{4y}{x}}{4\ln x + 2\sec^2(x-y)} = \frac{\sec^2(x-y) - xe^{x^2} - 3x - \frac{2y}{x}}{2\ln x + \sec^2(x-y)}$.

> [!sq]- Problem 2.12
> Find $\frac{dy}{dx}$ for $y^{3}+4x\ln(2y)=e^{2y}+\sin^{2}x$ by using implicit differentiation.
>
> > [!continue]- Solution
> > Differentiate both sides with respect to x:
> > $\frac{d}{dx}(y^3) + \frac{d}{dx}(4x\ln(2y)) = \frac{d}{dx}(e^{2y}) + \frac{d}{dx}(\sin^2 x)$
> > $3y^2 \frac{dy}{dx} + \left(4x \cdot \frac{1}{2y} \cdot 2\frac{dy}{dx} + 4\ln(2y)\right) = e^{2y} \cdot 2\frac{dy}{dx} + 2\sin x \cos x$
> > $3y^2 \frac{dy}{dx} + \frac{4x}{y}\frac{dy}{dx} + 4\ln(2y) = 2e^{2y}\frac{dy}{dx} + \sin(2x)$
> > Collect $\frac{dy}{dx}$ terms:
> > $3y^2 \frac{dy}{dx} + \frac{4x}{y}\frac{dy}{dx} - 2e^{2y}\frac{dy}{dx} = \sin(2x) - 4\ln(2y)$
> > $\frac{dy}{dx} \left(3y^2 + \frac{4x}{y} - 2e^{2y}\right) = \sin(2x) - 4\ln(2y)$
> > $\frac{dy}{dx} = \frac{\sin(2x) - 4\ln(2y)}{3y^2 + \frac{4x}{y} - 2e^{2y}} = \frac{y\sin(2x) - 4y\ln(2y)}{3y^3 + 4x - 2ye^{2y}}$.

> [!sq]- Problem 2.13
> By taking natural logarithm for both sides, find $\frac{dy}{dx}$ for $y=x^{x}$.
>
> > [!continue]- Solution
> > Take the natural logarithm of both sides:
> > $\ln y = \ln(x^x) \Rightarrow \ln y = x \ln x$
> > Differentiate implicitly with respect to x:
> > $\frac{1}{y} \frac{dy}{dx} = x\left(\frac{1}{x}\right) + (\ln x)(1)$
> > $\frac{1}{y} \frac{dy}{dx} = 1 + \ln x$
> > $\frac{dy}{dx} = y(1 + \ln x)$
> > Substitute back $y = x^x$:
> > $\frac{dy}{dx} = x^x(1 + \ln x)$.

> [!sq]- Problem 2.14
> By taking natural logarithm for both sides, find $\frac{dy}{dx}$ for $y=x^{\sin x}$.
>
> > [!continue]- Solution
> > Take the natural logarithm of both sides:
> > $\ln y = \ln(x^{\sin x}) \Rightarrow \ln y = (\sin x)(\ln x)$
> > Differentiate implicitly with respect to x using the product rule:
> > $\frac{1}{y} \frac{dy}{dx} = (\sin x)\left(\frac{1}{x}\right) + (\ln x)(\cos x)$
> > $\frac{dy}{dx} = y \left( \frac{\sin x}{x} + \cos x \ln x \right)$
> > Substitute back $y = x^{\sin x}$:
> > $\frac{dy}{dx} = x^{\sin x} \left( \frac{\sin x}{x} + \cos x \ln x \right)$.

> [!sq]- Problem 2.15
> If $y=\frac{A\cos 2x+B\sin 2x}{x}$, where A and B are constant, show that $x\frac{d^{2}y}{dx^{2}}+2\frac{dy}{dx}+4xy=0$.
>
> > [!continue]- Solution
> > First, rewrite the equation to avoid the quotient rule:
> > $xy = A\cos 2x + B\sin 2x$.
> > Differentiate implicitly with respect to x:
> > $x\frac{dy}{dx} + y(1) = -2A\sin 2x + 2B\cos 2x$.
> > Differentiate again with respect to x:
> > $\left(x\frac{d^2y}{dx^2} + \frac{dy}{dx} \cdot 1\right) + \frac{dy}{dx} = -4A\cos 2x - 4B\sin 2x$.
> > Simplify the left side:
> > $x\frac{d^2y}{dx^2} + 2\frac{dy}{dx} = -4(A\cos 2x + B\sin 2x)$.
> > Notice that the term in the parenthesis is equal to $xy$:
> > $x\frac{d^2y}{dx^2} + 2\frac{dy}{dx} = -4(xy)$.
> > Rearrange the equation:
> > $x\frac{d^2y}{dx^2} + 2\frac{dy}{dx} + 4xy = 0$. Shown.

> [!sq]- Problem 2.16
> Find $\frac{dy}{dx}$ for the following functions:
> a) $y^{2}+xy-x^{2}=2$
> b) $\sin x+\cos y=2x^{3}$
> c) $e^{2x}=\sin(x+3y)$
> d) $\ln(x+y)=e^{x}$
>
> > [!continue]- Solution
> > **a) $y^{2}+xy-x^{2}=2$**
> > $2y \frac{dy}{dx} + \left(x \frac{dy}{dx} + y(1)\right) - 2x = 0$
> > $\frac{dy}{dx}(2y + x) = 2x - y \Rightarrow \frac{dy}{dx} = \frac{2x - y}{2y + x}$.
> > 
> > **b) $\sin x+\cos y=2x^{3}$**
> > $\cos x - \sin y \frac{dy}{dx} = 6x^2$
> > $-\sin y \frac{dy}{dx} = 6x^2 - \cos x \Rightarrow \frac{dy}{dx} = \frac{\cos x - 6x^2}{\sin y}$.
> > 
> > **c) $e^{2x}=\sin(x+3y)$**
> > $2e^{2x} = \cos(x+3y) \cdot \left(1 + 3\frac{dy}{dx}\right)$
> > $\frac{2e^{2x}}{\cos(x+3y)} = 1 + 3\frac{dy}{dx}$
> > $3\frac{dy}{dx} = \frac{2e^{2x}}{\cos(x+3y)} - 1 \Rightarrow \frac{dy}{dx} = \frac{1}{3}\left(\frac{2e^{2x}}{\cos(x+3y)} - 1\right)$.
> > 
> > **d) $\ln(x+y)=e^{x}$**
> > $\frac{1}{x+y} \cdot \left(1 + \frac{dy}{dx}\right) = e^x$
> > $1 + \frac{dy}{dx} = e^x(x+y) \Rightarrow \frac{dy}{dx} = e^x(x+y) - 1$.

## 2.6 DIFFERENTIATION OF PARAMETRIC FUNCTIONS
In some cases, implicit functions can be expressed in terms of parameters. Now, we say that the relationship between the variables x and y is defined in a parametric form using two equations, that is $x=f(t)$ and $y=g(t)$ where the variable t is called a parameter. We will concentrate on how to differentiate these functions using parametric differentiation.

As we already know the chain rule of derivatives,
$\frac{dy}{dx}=\frac{dy}{du}\times\frac{du}{dx}$
or we can rewrite in the form of
$\frac{dy}{dt}=\frac{dy}{dx}\times\frac{dx}{dt},$ where $\frac{dx}{dt}\ne0$.

Thus, find $\frac{dy}{dx}$ by rearranging the expression $\frac{dy}{dt}=\frac{dy}{dx}\times\frac{dx}{dt}$ to get
> [!formula]
> $\frac{dy}{dx}=\frac{\frac{dy}{dt}}{\frac{dx}{dt}}=\frac{dy}{dt}\times\frac{dt}{dx}$

Hence, the above expression is the first derivative of parametric functions. Parametric differentiation can be extended to determination of the second derivative which has the following formula:
> [!formula]
> $\frac{d^{2}y}{dx^{2}}=\frac{d}{dx}\left(\frac{dy}{dx}\right)=\frac{\frac{d}{dt}\left(\frac{dy}{dx}\right)}{\frac{dx}{dt}}=\left[\frac{d}{dt}\left(\frac{dy}{dx}\right)\right]\times\frac{dt}{dx}$

> [!example]- Example 2.16
> Find $\frac{dy}{dx}$ given a curve of parametric equations, $x=2t$ and $y=4-4t-4t^{2}$.
>
> > [!continue]- Solution
> > $x=2t \Rightarrow \frac{dx}{dt}=2$
> > $y=4-4t-4t^{2} \Rightarrow \frac{dy}{dt}=-4-8t$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx}$
> > $=(-4-8t)\times\frac{1}{2}$
> > $=-2-4t$

> [!example]- Example 2.17
> Find $\frac{dy}{dx}$ for the following parametric equations:
> a) $x=t^{3}-t, \quad y=4-t^{2}$
> b) $x=t^{3}, \quad y=t^{2}-t$
>
> > [!continue]- Solution
> > **a)** $\frac{dx}{dt}=3t^{2}-1$
> > $\frac{dy}{dt}=-2t$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx} = -2t\times\frac{1}{3t^{2}-1}=\frac{-2t}{3t^{2}-1}$
> > 
> > **b)** $\frac{dx}{dt}=3t^{2}$
> > $\frac{dy}{dt}=2t-1$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx} = (2t-1)\times\frac{1}{3t^{2}}=\frac{2t-1}{3t^{2}}$

> [!example]- Example 2.18
> Find $\frac{d^{2}y}{dx^{2}}$ for the following parametric equations:
> a) $x=t^{2}, \quad y=t^{3}$
> b) $x=t^{3}+3t^{2}, \quad y=t^{4}-8t^{2}$
>
> > [!continue]- Solution
> > **a) $x=t^{2}, \quad y=t^{3}$**
> > $\frac{dx}{dt}=2t \quad \frac{dy}{dt}=3t^{2}$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx} = 3t^{2}\times\frac{1}{2t}=\frac{3}{2}t$
> > $\frac{d^{2}y}{dx^{2}}=\left[\frac{d}{dt}\left(\frac{dy}{dx}\right)\right]\times\frac{dt}{dx} = \left[\frac{d}{dt}\left(\frac{3}{2}t\right)\right]\times\frac{1}{2t} = \frac{3}{2}\times\frac{1}{2t}=\frac{3}{4t}$
> > 
> > **b) $x=t^{3}+3t^{2}, \quad y=t^{4}-8t^{2}$**
> > $\frac{dx}{dt}=3t^{2}+6t \quad \frac{dy}{dt}=4t^{3}-16t$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx} = (4t^{3}-16t)\times\frac{1}{3t^{2}+6t} = \frac{4t(t^{2}-4)}{3t(t+2)} = \frac{4t(t-2)(t+2)}{3t(t+2)} = \frac{4(t-2)}{3} = \frac{4t-8}{3}$
> > $\frac{d^{2}y}{dx^{2}}=\left[\frac{d}{dt}\left(\frac{dy}{dx}\right)\right]\times\frac{dt}{dx} = \left[\frac{d}{dt}\left(\frac{4t-8}{3}\right)\right]\times\frac{1}{3t^{2}+6t} = \frac{4}{3}\times\frac{1}{3t^{2}+6t}=\frac{4}{9t^{2}+18t}$

> [!example]- Example 2.19
> A curve is given by parametric equations $x=\frac{t-3}{t}$ and $y=\frac{t^{2}+4}{t}$. Evaluate $\frac{dy}{dx}$ and $\frac{d^{2}y}{dx^{2}}$ at $t=1$.
>
> > [!continue]- Solution
> > $x=\frac{t-3}{t} \Rightarrow \frac{dx}{dt}=\frac{t(1)-(t-3)(1)}{t^{2}} = \frac{3}{t^{2}}$
> > $y=\frac{t^{2}+4}{t} \Rightarrow \frac{dy}{dt}=\frac{t(2t)-(t^{2}+4)(1)}{t^{2}} = \frac{t^{2}-4}{t^{2}}$
> > $\frac{dy}{dx}=\frac{dy}{dt}\times\frac{dt}{dx} = \frac{t^{2}-4}{t^{2}}\times\frac{t^{2}}{3} = \frac{t^{2}-4}{3}$
> > $\frac{d^{2}y}{dx^{2}}=\left[\frac{d}{dt}\left(\frac{dy}{dx}\right)\right]\times\frac{dt}{dx} = \frac{d}{dt}\left(\frac{t^{2}-4}{3}\right)\times\frac{t^{2}}{3}=\frac{2t}{3}\times\frac{t^{2}}{3}=\frac{2t^{3}}{9}$
> > When $t=1$, $\frac{dy}{dx}=\frac{1^{2}-4}{3}=-1$, and $\frac{d^{2}y}{dx^{2}}=\frac{2(1)^{3}}{9}=\frac{2}{9}$.

> [!sq]- Problem 2.17
> Find $\frac{dy}{dx}$ for the curve with parametric equations, $x=3t^{2}-3t^{3}$ and $y=t(t^{2}+3)$.
>
> > [!continue]- Solution
> > $x = 3t^2 - 3t^3 \Rightarrow \frac{dx}{dt} = 6t - 9t^2$.
> > $y = t(t^2+3) = t^3 + 3t \Rightarrow \frac{dy}{dt} = 3t^2 + 3$.
> > $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{3t^2 + 3}{6t - 9t^2} = \frac{3(t^2 + 1)}{3(2t - 3t^2)} = \frac{t^2 + 1}{2t - 3t^2}$.

> [!sq]- Problem 2.18
> Find $\frac{dy}{dx}$ for the given value of $t=2$ if given parametric equations, $x=\frac{3t}{1+t^{3}}$ and $y=\frac{3t^{2}}{1+t^{3}}$.
>
> > [!continue]- Solution
> > Using quotient rule for $\frac{dx}{dt}$:
> > $\frac{dx}{dt} = \frac{(1+t^3)(3) - (3t)(3t^2)}{(1+t^3)^2} = \frac{3 + 3t^3 - 9t^3}{(1+t^3)^2} = \frac{3 - 6t^3}{(1+t^3)^2}$.
> > At $t=2$, $\frac{dx}{dt} = \frac{3 - 6(8)}{(1+8)^2} = \frac{3 - 48}{81} = \frac{-45}{81} = -\frac{5}{9}$.
> > 
> > Using quotient rule for $\frac{dy}{dt}$:
> > $\frac{dy}{dt} = \frac{(1+t^3)(6t) - (3t^2)(3t^2)}{(1+t^3)^2} = \frac{6t + 6t^4 - 9t^4}{(1+t^3)^2} = \frac{6t - 3t^4}{(1+t^3)^2}$.
> > At $t=2$, $\frac{dy}{dt} = \frac{6(2) - 3(16)}{(1+8)^2} = \frac{12 - 48}{81} = \frac{-36}{81} = -\frac{4}{9}$.
> > 
> > $\frac{dy}{dx} \text{ at } t=2 = \frac{dy/dt}{dx/dt} = \frac{-4/9}{-5/9} = \frac{4}{5}$.

> [!sq]- Problem 2.19
> A curve has parametric equations $x=3t^{2}+1$ and $y=t^{3}-2t^{2}$. Evaluate $\frac{d^{2}y}{dx^{2}}$ at $t=\frac{1}{4}$.
>
> > [!continue]- Solution
> > $\frac{dx}{dt} = 6t$ and $\frac{dy}{dt} = 3t^2 - 4t$.
> > $\frac{dy}{dx} = \frac{3t^2 - 4t}{6t} = \frac{t(3t - 4)}{6t} = \frac{3t - 4}{6} = \frac{1}{2}t - \frac{2}{3}$.
> > $\frac{d^2y}{dx^2} = \frac{\frac{d}{dt}\left(\frac{dy}{dx}\right)}{\frac{dx}{dt}} = \frac{\frac{d}{dt}\left(\frac{1}{2}t - \frac{2}{3}\right)}{6t} = \frac{1/2}{6t} = \frac{1}{12t}$.
> > At $t=\frac{1}{4}$, $\frac{d^{2}y}{dx^{2}} = \frac{1}{12(1/4)} = \frac{1}{3}$.

## 2.7 TUTORIAL 2

> [!sq]- Question 1
> Given $f(x)=\frac{2}{(x+2)^{2}}$. Find $f^{\prime}(x)$ by using the definition of derivative.
>
> > [!continue]- Solution
> > $f^{\prime}(x) = \lim_{h\to0} \frac{f(x+h) - f(x)}{h} = \lim_{h\to0} \frac{\frac{2}{(x+h+2)^2} - \frac{2}{(x+2)^2}}{h}$.
> > Make a common denominator:
> > $= \lim_{h\to0} \frac{2(x+2)^2 - 2(x+h+2)^2}{h(x+h+2)^2(x+2)^2}$.
> > Expand the numerators:
> > Numerator $= 2(x^2+4x+4) - 2(x^2+h^2+4+2xh+4x+4h)$
> > $= -2h^2 - 4xh - 8h = h(-2h - 4x - 8)$.
> > Substitute back into the limit:
> > $f^{\prime}(x) = \lim_{h\to0} \frac{h(-2h - 4x - 8)}{h(x+h+2)^2(x+2)^2} = \lim_{h\to0} \frac{-2h - 4x - 8}{(x+h+2)^2(x+2)^2}$
> > $= \frac{-4x - 8}{(x+2)^2(x+2)^2} = \frac{-4(x+2)}{(x+2)^4} = -\frac{4}{(x+2)^3}$.

> [!sq]- Question 2
> By using the first principle of derivative, find $f^{\prime}(x)$ for $\frac{1}{\sqrt{3x-2}}$.
>
> > [!continue]- Solution
> > $f'(x) = \lim_{h\to0} \frac{\frac{1}{\sqrt{3(x+h)-2}} - \frac{1}{\sqrt{3x-2}}}{h} = \lim_{h\to0} \frac{\sqrt{3x-2} - \sqrt{3x+3h-2}}{h\sqrt{3x+3h-2}\sqrt{3x-2}}$.
> > Multiply numerator and denominator by the conjugate $(\sqrt{3x-2} + \sqrt{3x+3h-2})$:
> > $= \lim_{h\to0} \frac{(\sqrt{3x-2} - \sqrt{3x+3h-2})(\sqrt{3x-2} + \sqrt{3x+3h-2})}{h\sqrt{3x+3h-2}\sqrt{3x-2}(\sqrt{3x-2} + \sqrt{3x+3h-2})}$
> > $= \lim_{h\to0} \frac{(3x-2) - (3x+3h-2)}{h\sqrt{3x+3h-2}\sqrt{3x-2}(\sqrt{3x-2} + \sqrt{3x+3h-2})}$
> > $= \lim_{h\to0} \frac{-3h}{h\sqrt{3x+3h-2}\sqrt{3x-2}(\sqrt{3x-2} + \sqrt{3x+3h-2})}$
> > $= \lim_{h\to0} \frac{-3}{\sqrt{3x+3h-2}\sqrt{3x-2}(\sqrt{3x-2} + \sqrt{3x+3h-2})}$
> > $= \frac{-3}{\sqrt{3x-2}\sqrt{3x-2}(\sqrt{3x-2} + \sqrt{3x-2})} = \frac{-3}{(3x-2)(2\sqrt{3x-2})} = -\frac{3}{2(3x-2)^{3/2}}$.

> [!sq]- Question 3
> Find the first derivative of the following functions:
> a) $y=\ln^{2}(x+e^{3x})$
> b) $y=\sqrt[4]{7-x^{3}}$
> c) $y=e^{5x}\tan x$
> d) $y=\cos\left(\frac{3-x}{3+x}\right)$
>
> > [!continue]- Solution
> > **a) $y=[\ln(x+e^{3x})]^2$**
> > $y' = 2\ln(x+e^{3x}) \cdot \frac{d}{dx}(\ln(x+e^{3x})) = 2\ln(x+e^{3x}) \cdot \frac{1}{x+e^{3x}} \cdot (1+3e^{3x}) = \frac{2(1+3e^{3x})\ln(x+e^{3x})}{x+e^{3x}}$.
> > 
> > **b) $y=(7-x^3)^{1/4}$**
> > $y' = \frac{1}{4}(7-x^3)^{-3/4} \cdot \frac{d}{dx}(7-x^3) = \frac{1}{4}(7-x^3)^{-3/4}(-3x^2) = -\frac{3x^2}{4(7-x^3)^{3/4}}$.
> > 
> > **c) $y=e^{5x}\tan x$**
> > $y' = (e^{5x})'(\tan x) + (e^{5x})(\tan x)' = 5e^{5x}\tan x + e^{5x}\sec^2 x = e^{5x}(5\tan x + \sec^2 x)$.
> > 
> > **d) $y=\cos\left(\frac{3-x}{3+x}\right)$**
> > Let $u = \frac{3-x}{3+x} \Rightarrow u' = \frac{(3+x)(-1) - (3-x)(1)}{(3+x)^2} = \frac{-3-x-3+x}{(3+x)^2} = \frac{-6}{(3+x)^2}$.
> > $y' = -\sin\left(\frac{3-x}{3+x}\right) \cdot u' = -\sin\left(\frac{3-x}{3+x}\right) \cdot \left(\frac{-6}{(3+x)^2}\right) = \frac{6}{(3+x)^2}\sin\left(\frac{3-x}{3+x}\right)$.

> [!sq]- Question 4
> Find $\frac{dy}{dx}$ for $xy+3x^{2}=2\cos(x+y)-e^{3y}$ by using implicit differentiation.
>
> > [!continue]- Solution
> > Differentiate implicitly with respect to x:
> > $\left(1\cdot y + x\frac{dy}{dx}\right) + 6x = -2\sin(x+y)\left(1 + \frac{dy}{dx}\right) - 3e^{3y}\frac{dy}{dx}$
> > $y + x\frac{dy}{dx} + 6x = -2\sin(x+y) - 2\sin(x+y)\frac{dy}{dx} - 3e^{3y}\frac{dy}{dx}$
> > Move all $\frac{dy}{dx}$ terms to the left side:
> > $x\frac{dy}{dx} + 2\sin(x+y)\frac{dy}{dx} + 3e^{3y}\frac{dy}{dx} = -y - 6x - 2\sin(x+y)$
> > $\frac{dy}{dx}\left(x + 2\sin(x+y) + 3e^{3y}\right) = -(y + 6x + 2\sin(x+y))$
> > $\frac{dy}{dx} = \frac{-(y + 6x + 2\sin(x+y))}{x + 2\sin(x+y) + 3e^{3y}}$.

> [!sq]- Question 5
> Let y be the function of x such that $3\ln(x^{2}y)=2x^{2}+\sqrt{2x+y^{2}}$. Find $\frac{dy}{dx}$ by using implicit differentiation.
>
> > [!continue]- Solution
> > First, simplify the logarithmic term: $3\ln(x^2y) = 3(\ln(x^2) + \ln y) = 6\ln x + 3\ln y$.
> > Equation becomes: $6\ln x + 3\ln y = 2x^2 + (2x+y^2)^{1/2}$.
> > Differentiate implicitly with respect to x:
> > $\frac{6}{x} + \frac{3}{y}\frac{dy}{dx} = 4x + \frac{1}{2}(2x+y^2)^{-1/2}\left(2 + 2y\frac{dy}{dx}\right)$
> > $\frac{6}{x} + \frac{3}{y}\frac{dy}{dx} = 4x + \frac{1}{\sqrt{2x+y^2}} + \frac{y}{\sqrt{2x+y^2}}\frac{dy}{dx}$
> > Group $\frac{dy}{dx}$ terms:
> > $\frac{dy}{dx}\left(\frac{3}{y} - \frac{y}{\sqrt{2x+y^2}}\right) = 4x + \frac{1}{\sqrt{2x+y^2}} - \frac{6}{x}$
> > $\frac{dy}{dx} = \frac{4x + \frac{1}{\sqrt{2x+y^2}} - \frac{6}{x}}{\frac{3}{y} - \frac{y}{\sqrt{2x+y^2}}}$.

> [!sq]- Question 6
> Let $y=A\cos 2t$ where A is a constant. Find the value of A such that $\frac{d^{2}y}{dt^{2}}-3y=9\cos 2t$ for all values of t. *(Note: Text incorrectly uses $dx^{2}$ in the denominator; evaluated as $dt^{2}$ based on variables provided).*
>
> > [!continue]- Solution
> > Find the first and second derivatives of $y$ with respect to $t$:
> > $\frac{dy}{dt} = -2A\sin 2t$
> > $\frac{d^2y}{dt^2} = -4A\cos 2t$
> > Substitute $y$ and $\frac{d^2y}{dt^2}$ into the given differential equation:
> > $(-4A\cos 2t) - 3(A\cos 2t) = 9\cos 2t$
> > $-7A\cos 2t = 9\cos 2t$
> > $-7A = 9 \Rightarrow A = -\frac{9}{7}$.

> [!sq]- Question 7
> A curve has a parametric equation $x=2t^{3}-1$ and $y=t^{4}-t^{3}$. Evaluate $\frac{d^{2}y}{dx^{2}}$ at $t=-\frac{1}{2}$.
>
> > [!continue]- Solution
> > $\frac{dx}{dt} = 6t^2 \quad \text{and} \quad \frac{dy}{dt} = 4t^3 - 3t^2$
> > $\frac{dy}{dx} = \frac{4t^3 - 3t^2}{6t^2} = \frac{t^2(4t - 3)}{6t^2} = \frac{4t - 3}{6} = \frac{2}{3}t - \frac{1}{2}$
> > $\frac{d^2y}{dx^2} = \frac{\frac{d}{dt}\left(\frac{dy}{dx}\right)}{\frac{dx}{dt}} = \frac{\frac{d}{dt}\left(\frac{2}{3}t - \frac{1}{2}\right)}{6t^2} = \frac{2/3}{6t^2} = \frac{1}{9t^2}$
> > Evaluate at $t=-\frac{1}{2}$:
> > $\frac{d^2y}{dx^2} = \frac{1}{9(-1/2)^2} = \frac{1}{9(1/4)} = \frac{1}{9/4} = \frac{4}{9}$.

> [!sq]- Question 8
> Given $x=\frac{2}{\sqrt{2+t^{2}}}$ and $y=\frac{\sqrt{2+t^{2}}}{t}$ are the parametric equation of a curve, where t is a non - zero parameter. Determine the value of $\frac{d^{2}y}{dx^{2}}$ at $t=1$.
>
> > [!continue]- Solution
> > Rewrite x and y: $x = 2(2+t^2)^{-1/2}$, $y = t^{-1}(2+t^2)^{1/2}$.
> > $\frac{dx}{dt} = 2(-\frac{1}{2})(2+t^2)^{-3/2}(2t) = -2t(2+t^2)^{-3/2}$.
> > $\frac{dy}{dt} = -t^{-2}(2+t^2)^{1/2} + t^{-1}(\frac{1}{2})(2+t^2)^{-1/2}(2t) = -\frac{\sqrt{2+t^2}}{t^2} + \frac{1}{\sqrt{2+t^2}} = \frac{-(2+t^2) + t^2}{t^2\sqrt{2+t^2}} = \frac{-2}{t^2(2+t^2)^{1/2}}$.
> > $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{\frac{-2}{t^2(2+t^2)^{1/2}}}{\frac{-2t}{(2+t^2)^{3/2}}} = \frac{-2}{t^2(2+t^2)^{1/2}} \cdot \frac{(2+t^2)^{3/2}}{-2t} = \frac{2+t^2}{t^3} = 2t^{-3} + t^{-1}$.
> > $\frac{d}{dt}\left(\frac{dy}{dx}\right) = -6t^{-4} - t^{-2} = \frac{-6-t^2}{t^4}$.
> > $\frac{d^2y}{dx^2} = \frac{\frac{-6-t^2}{t^4}}{-2t(2+t^2)^{-3/2}} = \frac{-(6+t^2)}{t^4} \cdot \frac{(2+t^2)^{3/2}}{-2t} = \frac{(6+t^2)(2+t^2)^{3/2}}{2t^5}$.
> > Evaluate at $t=1$: $\frac{d^2y}{dx^2} = \frac{(6+1^2)(2+1^2)^{3/2}}{2(1)^5} = \frac{7(3)^{3/2}}{2} = \frac{21\sqrt{3}}{2}$.

> [!sq]- Question 9
> Use appropriate rules to find $\frac{dy}{dx}$ for each of the following:
> a) $y=e^{3x^{2}}\sin 2x$
> b) $y=\ln(\cos^{2}2x)$
> c) $y=-\ln|\cos x|$
> d) $y=\frac{\sin 3x}{e^{x^{3}}}$
>
> > [!continue]- Solution
> > **a) $y=e^{3x^{2}}\sin 2x$**
> > Product Rule: $y' = (e^{3x^2})'(\sin 2x) + (e^{3x^2})(\sin 2x)'$
> > $= (6x e^{3x^2})\sin 2x + (e^{3x^2})(2\cos 2x) = 2e^{3x^2}(3x\sin 2x + \cos 2x)$.
> > 
> > **b) $y=\ln(\cos^{2}2x)$**
> > Simplify: $y = 2\ln|\cos 2x|$.
> > $y' = 2 \cdot \frac{1}{\cos 2x} \cdot (-\sin 2x) \cdot 2 = -\frac{4\sin 2x}{\cos 2x} = -4\tan 2x$.
> > 
> > **c) $y=-\ln|\cos x|$**
> > $y' = - \frac{1}{\cos x} \cdot (-\sin x) = \frac{\sin x}{\cos x} = \tan x$.
> > 
> > **d) $y=\frac{\sin 3x}{e^{x^{3}}}$**
> > Quotient Rule: $y' = \frac{e^{x^3}(3\cos 3x) - (\sin 3x)(3x^2 e^{x^3})}{(e^{x^3})^2} = \frac{3e^{x^3}(\cos 3x - x^2\sin 3x)}{e^{2x^3}} = \frac{3(\cos 3x - x^2\sin 3x)}{e^{x^3}}$.

> [!sq]- Question 10
> If $x^{2}y=\cos x$, show that $x^{2}\frac{d^{2}y}{dx^{2}}+4x\frac{dy}{dx}+(x^{2}+2)y=0$.
>
> > [!continue]- Solution
> > $x^2 y = \cos x$.
> > Differentiate implicitly with respect to x (Product Rule):
> > $2x y + x^2 \frac{dy}{dx} = -\sin x$.
> > Differentiate again with respect to x:
> > $\left(2(1)y + 2x\frac{dy}{dx}\right) + \left(2x\frac{dy}{dx} + x^2\frac{d^2y}{dx^2}\right) = -\cos x$.
> > Combine like terms:
> > $x^2 \frac{d^2y}{dx^2} + 4x\frac{dy}{dx} + 2y = -\cos x$.
> > Since $x^2 y = \cos x$, substitute $-\cos x$ with $-x^2 y$:
> > $x^2 \frac{d^2y}{dx^2} + 4x\frac{dy}{dx} + 2y = -x^2 y$.
> > $x^2 \frac{d^2y}{dx^2} + 4x\frac{dy}{dx} + x^2 y + 2y = 0$.
> > $x^2 \frac{d^2y}{dx^2} + 4x\frac{dy}{dx} + (x^2+2)y = 0$. Shown.

> [!sq]- Question 11
> Given $\sin(xy)=2y^{3}+\ln x$ and find $\frac{dy}{dx}$ at point (1,0). *(Note: Text says point (0,0) but x=0 is undefined for natural log. Assuming valid evaluation point (1,0) based on equation mapping: $\sin(0) = 2(0) + \ln 1 \Rightarrow 0 = 0$)*
>
> > [!continue]- Solution
> > Differentiate implicitly with respect to x:
> > $\cos(xy) \cdot \left(1\cdot y + x\frac{dy}{dx}\right) = 6y^2 \frac{dy}{dx} + \frac{1}{x}$.
> > Substitute $x=1$ and $y=0$:
> > $\cos(0) \cdot \left(0 + 1 \cdot \frac{dy}{dx}\right) = 6(0)^2 \frac{dy}{dx} + \frac{1}{1}$.
> > $(1) \cdot \left(\frac{dy}{dx}\right) = 0 + 1$.
> > $\frac{dy}{dx} = 1$.

> [!sq]- Question 12
> Find $\frac{dy}{dx}$ if the parametric equations are given as $x=5\cos^{3}t$ and $y=7\sin^{3}t$.
>
> > [!continue]- Solution
> > $\frac{dx}{dt} = 5 \cdot 3\cos^2 t (-\sin t) = -15\cos^2 t \sin t$.
> > $\frac{dy}{dt} = 7 \cdot 3\sin^2 t (\cos t) = 21\sin^2 t \cos t$.
> > $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{21\sin^2 t \cos t}{-15\cos^2 t \sin t} = -\frac{7\sin t}{5\cos t} = -\frac{7}{5}\tan t$.

> [!sq]- Question 13
> A curve has parametric equations as $x=t-\frac{1}{t}$ and $y=t+\frac{1}{t}$ where $t\ne0$. Find the coordinates of the points when $\frac{dy}{dx}=0$.
>
> > [!continue]- Solution
> > $\frac{dx}{dt} = 1 - (-1)t^{-2} = 1 + \frac{1}{t^2} = \frac{t^2+1}{t^2}$.
> > $\frac{dy}{dt} = 1 + (-1)t^{-2} = 1 - \frac{1}{t^2} = \frac{t^2-1}{t^2}$.
> > $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{\frac{t^2-1}{t^2}}{\frac{t^2+1}{t^2}} = \frac{t^2-1}{t^2+1}$.
> > Set $\frac{dy}{dx} = 0$:
> > $\frac{t^2-1}{t^2+1} = 0 \Rightarrow t^2 - 1 = 0 \Rightarrow t^2 = 1 \Rightarrow t = \pm 1$.
> > Find the coordinates:
> > When $t = 1$: $x = 1 - 1/1 = 0$, $y = 1 + 1/1 = 2$. Point is $(0, 2)$.
> > When $t = -1$: $x = -1 - (-1) = 0$, $y = -1 + (-1) = -2$. Point is $(0, -2)$.
> > The coordinates are $(0, 2)$ and $(0, -2)$.

> [!sq]- Question 14
> Find $\frac{dy}{dx}$ in terms of $\theta$ for a curve with parametric equations $x=\cos \theta$ and $y=\sin \theta$. Hence, evaluate $\frac{dy}{dx}$ and $\frac{d^{2}y}{dx^{2}}$ when $\theta=\frac{\pi}{4}$.
>
> > [!continue]- Solution
> > $\frac{dx}{d\theta} = -\sin \theta$.
> > $\frac{dy}{d\theta} = \cos \theta$.
> > $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{\cos \theta}{-\sin \theta} = -\cot \theta$.
> > 
> > Evaluate $\frac{dy}{dx}$ at $\theta = \frac{\pi}{4}$:
> > $\frac{dy}{dx} = -\cot\left(\frac{\pi}{4}\right) = -1$.
> > 
> > Find $\frac{d^2y}{dx^2}$:
> > $\frac{d^2y}{dx^2} = \frac{\frac{d}{d\theta}\left(\frac{dy}{dx}\right)}{\frac{dx}{d\theta}} = \frac{\frac{d}{d\theta}(-\cot \theta)}{-\sin \theta} = \frac{\csc^2 \theta}{-\sin \theta} = -\csc^3 \theta$.
> > 
> > Evaluate $\frac{d^2y}{dx^2}$ at $\theta = \frac{\pi}{4}$:
> > $\frac{d^2y}{dx^2} = -\csc^3\left(\frac{\pi}{4}\right) = -(\sqrt{2})^3 = -2\sqrt{2}$.

