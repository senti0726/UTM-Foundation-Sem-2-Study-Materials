$$\underline{\Huge\text{NUMERICAL METHOD}}$$
# 7.0 INTRODUCTION
Numerical methods are the area of Mathematics and Computer Science concerned with the solution of mathematical problems using standard procedure.

In this chapter, we shall discuss the methods of finding a real root (solution) of nonlinear using Numerical Methods and calculating the numerical value of a definite integral.

# 7.1 NONLINEAR EQUATIONS
An equation is said to be nonlinear when it involves terms of degree higher than one in the unknown quantity. Nonlinear equations cannot in general be solved analytically.

In this case, therefore, the solutions of the equations (also called a root of the equation) must be approached using iterative methods.

## 7.1.1 Roots of Nonlinear Equations
Mathematics models in science and engineering can be formulated into equation of the form $f(x)=0$. The values of x that satisfy this equation are known as roots.

Since the function $f(x)$ becomes zero at this value, they are also known as zeros of the function $f(x)$.

![[Pasted image 20260216181314.png]]

## 7.1.2 Intermediate Value Theorem
Let $f(x)$ be a nonlinear equation. If $f(x)$ is continuous for all x in $[a,b]$ and we can show that $f(a)f(b)<0$ then there exists at least one root of $f(x)$ in the interval $(a,b)$.

> [!example]- Example 7.1
> Use Intermediate Value Theorem to verify that the root of $4 \sin x = e^{-x}$ is in the interval $[0, \frac{3}{2}]$.
>
> > [!continue]- Solution
> > Let $f(x) = 4 \sin x - e^{-x}$ and $[a,b] = [0, \frac{3}{2}]$.
> > $f(0) = 4 \sin 0 - e^{-(0)} = -1$
> > $f(\frac{3}{2}) = 4 \sin(\frac{3}{2}) - e^{-(\frac{3}{2})} = 3.7668$
> > $f(0)f(\frac{3}{2}) = -3.7668 < 0$
> > Thus, we have $f(0)f(\frac{3}{2}) < 0$. Therefore, there exist at least a root in interval $[0, \frac{3}{2}]$.

> [!example]- Example 7.2
> Given $e^{2x} + 4x = 5$. Use Intermediate Value Theorem to verify that there exists a real root for the equation in the interval $[0,1]$.
>
> > [!continue]- Solution
> > Let $f(x) = e^{2x} + 4x - 5$ and $[a,b] = [0,1]$. Thus, we have:
> > $f(0) = e^{2(0)} + 4(0) - 5 = -4$
> > $f(1) = e^{2(1)} + 4(1) - 5 = 6.3891$
> > $f(0)f(1) = -25.5562 < 0$
> > Therefore, there exist at least a root in interval $[0,1]$.

> [!example]- Example 7.3
> Verify that the root of the equation $\ln x = 4 - x$ lies in the interval $[2.9,3]$.
>
> > [!continue]- Solution
> > Let $f(x) = \ln x - 4 + x$, and $[a,b] = [2.9,3]$. Thus, we have:
> > $f(2.9) = \ln(2.9) - 4 + (2.9) = -0.0353$
> > $f(3) = \ln(3) - 4 + (3) = 0.0986$
> > $f(2.9)f(3) = -0.0035 < 0$
> > Therefore, there exist at least a root in interval $[2.9,3]$.

> [!sq]- Problem 7.1
> 1. Use Intermediate Value Theorem to determine which of the following interval may contain the root of the continuous equation, $\cos 2x + x^{2} = 6$:
> i. $[1,2]$
> ii. $[2,3]$
> 2. Show that the equation $2 - e^{x} = 4x$ has a solution in the interval $[0,1]$.
>
> > [!continue]- Solution
> > **1.** Let $f(x) = \cos 2x + x^2 - 6$.
> > **i. Interval $[1,2]$:**
> > $f(1) = \cos(2) + 1^2 - 6 = -0.4161 + 1 - 6 = -5.4161$
> > $f(2) = \cos(4) + 2^2 - 6 = -0.6536 + 4 - 6 = -2.6536$
> > Since $f(1)f(2) > 0$, we cannot determine if a root exists in this interval using the Intermediate Value Theorem.
> > **ii. Interval $[2,3]$:**
> > $f(2) = -2.6536$
> > $f(3) = \cos(6) + 3^2 - 6 = 0.9602 + 9 - 6 = 3.9602$
> > Since $f(2)f(3) < 0$, there exists at least one root in the interval $[2,3]$.
> > 
> > **2.** Let $f(x) = 2 - e^x - 4x$.
> > $f(0) = 2 - e^0 - 4(0) = 2 - 1 = 1$.
> > $f(1) = 2 - e^1 - 4(1) = 2 - 2.7183 - 4 = -4.7183$.
> > Since $f(0)f(1) < 0$, by the Intermediate Value Theorem, there is a solution in $[0,1]$.

## 7.1.3 Fixed Point Iteration
Fixed point iteration method is simple method for finding real root of nonlinear equation by successive approximation. It requires only one initial guess to start.

In this method, the given equation, $f(x)=0$ can be rewrite to the fixed-point equation, $x=g(x)$. These two equations are equivalent, means a root of the second equation is also a root of the first equation.

Let $x=x_{0}$, where $x_{0}$ be the initial approximation to the root $x^*$, then the first approximation $x_{1}$ is given by $x_{1}=g(x_{0})$, the second approximation $x_{2}$ is given by $x_{2}=g(x_{1})$ the third approximation $x_{3}$ is given by $x_{3}=g(x_{2})$ and so on. In general, the iterative formula for fixed-point method is given as:
> [!formula]
> $x_{i+1}=g(x_{i})$, for $i=0,1,2,...$

The iteration process can be repeated until $|f(x_{i})|<\epsilon$ or $|x_{i}-x_{i-1}|<\epsilon$ for some value of i, and specified tolerance small number $\epsilon$ and then take the desired root as $x^* = x_i$.

This method is simple; however, it may not always converge. The condition to be satisfied for convergence to the correct root $x^* \in [a,b]$ by $|g^{\prime}(x)| < 1$ or $-1 < g^{\prime}(x) < 1$ for all $x \in [a,b]$.

If the initial approximation, $x_{0}$ is very closed to root $x^* \in [a,b]$ then is sufficient to choose $g(x)$ such that $|g^{\prime}(x)| < 1$ or $-1 < g^{\prime}(x) < 1$ to ensure the convergence of the fixed point method.

If we want to estimate the root, $x^*$ of the nonlinear equation $f(x)=0$ using fixed point iteration method, then we need the following steps.
* **Step 1:** Choose a value $x_{0}$ reasonably close to the root, $x^*$.
* **Step 2:** Rearrange the equation $f(x)=0$ to the equivalent form $x=g(x)$.
* **Step 3:** Write the iteration formula, $x_{i+1}=g(x_{i})$, for $i=0,1,2,...$ where $|g^{\prime}(x)| < 1$ for all $x \in (a,b)$. Assume that $x^* \in (a,b)$.
* **Step 4:** Stop the iteration when $|f(x_{i})| < \epsilon$ or $|x_{i}-x_{i-1}| < \epsilon$ where $\epsilon$ was the specified value.

Remarks:
i. If $|g^{\prime}(x)| < 1$ for all $x \in (a,b)$, then the iterative sequence will converge to the root of the equation $x=g(x)$ or $f(x)=0$.
ii. $|g^{\prime}(x)| > 1$ for all $x \in (a,b)$, the iterative sequence will diverge.
iii. Usually we choose $x=x_{0}$ where $x_{0} \in (a,b)$, to ensure the convergence we must show $|g^{\prime}(x)| < 1$ or $-1 < g^{\prime}(x) < 1$.

> [!example]- Example 7.4
> If $e^{-x}-x=0$ have a root, $x^*$ in $[0,1]$
> a) Show that the equation can be rewrite in the form $x=g(x)$ as $x=\frac{e^{-x}+x}{2}.$
> b) Show that $g(x)$ satisfies the convergence condition for $x_{0}=1$ in $[0,1]$.
> c) Hence, find the root, $x^*$ using fixed point method. Use 4 decimal places in all calculation and use the stopping criteria $|x_{i}-x_{i-1}|<\epsilon$.
>
> > [!continue]- Solution
> > **a)** $x=e^{-x}$
> > Add $x$ to both sides: $2x = e^{-x} + x$
> > Divide by 2: $x = \frac{e^{-x}+x}{2} = g(x)$
> > 
> > **b)** $g^{\prime}(x) = \frac{-e^{-x}+1}{2}$
> > $|g^{\prime}(1)| = \left|\frac{-e^{-1}+1}{2}\right| = 0.3161 < 1$
> > Since $|g^{\prime}(x)| < 1$ then $g(x)$ satisfies the convergence condition.
> > 
> > **c)** The iterative process can write as $x_{i+1}=g(x_{i})=\frac{e^{-x_{i}}+x_{i}}{2}$ for $i=0,1,2,....$
> > Calculation in 4 decimal places and then let $\epsilon=0.0005$. Let $x_{0}=1$ be the initial approximation to the root $x^*$. Construct a table as below:
> > 
> > | $i$ | $x_i$ | $|x_i - x_{i-1}|$ |
> > | :--- | :--- | :--- |
> > | 0 | $x_0 = 1$ | - |
> > | 1 | $x_1 = g(x_0) = \frac{e^{-1}+1}{2} = 0.6839$ | $|0.6839 - 1| = 0.3161$ |
> > | 2 | $x_2 = g(x_1) = \frac{e^{-0.6839}+0.6839}{2} = 0.5943$ | $|0.5943 - 0.6839| = 0.0896$ |
> > | 3 | $x_3 = g(x_2) = \frac{e^{-0.5943}+0.5943}{2} = 0.5731$ | $|0.5731 - 0.5943| = 0.0212$ |
> > | 4 | $x_4 = g(x_3) = \frac{e^{-0.5731}+0.5731}{2} = 0.5684$ | $|0.5684 - 0.5731| = 0.0047$ |
> > | 5 | $x_5 = g(x_4) = \frac{e^{-0.5684}+0.5684}{2} = 0.5674$ | $|0.5674 - 0.5684| = 0.0010$ |
> > | 6 | $x_6 = g(x_5) = \frac{e^{-0.5674}+0.5674}{2} = 0.5672$ | $|0.5672 - 0.5674| = 0.0002$ |
> > 
> > Since $|x_6 - x_5| = 0.0002 < 0.0005$ hence $x^* = x_6 = 0.5672$.
> > To check your answer: $e^{-0.5672} - 0.5672 = -0.00009 \approx 0$.

> [!sq]- Problem 7.2
> Write the following equation $f(x)=0$ into fixed point equation $x=g(x)$ as given. Hence, use fixed point iteration to find the root of $f(x)=0$ in given interval and starting with the given $x_{0}$. Show all your calculation in 4 decimal places. Use the stopping criteria $|x_{i}-x_{i-1}|<\epsilon$ (Assume $\epsilon = 0.0005$).
> i. $x-\tan x=0$, $x=\frac{1}{\tan x}-\frac{1}{x}+x$, $[4,5]$, $x_{0}=4$
> ii. $3x^{2}-e^{x}=0$, $x=\frac{e^{x}+2x}{3x+2}$, $[0,1]$, $x_{0}=0$
> iii. $x^{3}+x^{2}-1=0$, $x=\frac{1}{\sqrt{1+x}}$, $[0,1]$, $x_{0}=0$
>
> > [!continue]- Solution
> > **i.** $x_{i+1} = \frac{1}{\tan x_i} - \frac{1}{x_i} + x_i$. Let $x_0 = 4$ (in radians).
> > $x_1 = \frac{1}{\tan(4)} - \frac{1}{4} + 4 = 0.8637 - 0.2500 + 4 = 4.6137$. Diff: $0.6137$
> > $x_2 = \frac{1}{\tan(4.6137)} - \frac{1}{4.6137} + 4.6137 = 0.0898 - 0.2167 + 4.6137 = 4.4868$. Diff: $0.1269$
> > $x_3 = \frac{1}{\tan(4.4868)} - \frac{1}{4.4868} + 4.4868 = 0.2223 - 0.2229 + 4.4868 = 4.4862$. Diff: $0.0006$
> > $x_4 = \frac{1}{\tan(4.4862)} - \frac{1}{4.4862} + 4.4862 = 0.2230 - 0.2229 + 4.4862 = 4.4863$. Diff: $0.0001 < 0.0005$.
> > Root is approximately $4.4863$.
> > 
> > **ii.** $x_{i+1} = \frac{e^{x_i}+2x_i}{3x_i+2}$. Let $x_0 = 0$.
> > $x_1 = \frac{1+0}{0+2} = 0.5000$. Diff: $0.5000$
> > $x_2 = \frac{e^{0.5}+1}{1.5+2} = \frac{2.6487}{3.5} = 0.7568$. Diff: $0.2568$
> > $x_3 = \frac{e^{0.7568}+2(0.7568)}{3(0.7568)+2} = \frac{2.1314+1.5136}{4.2704} = 0.8535$. Diff: $0.0967$
> > $x_4 = \frac{e^{0.8535}+2(0.8535)}{3(0.8535)+2} = \frac{2.3478+1.7070}{4.5605} = 0.8891$. Diff: $0.0356$
> > $x_5 = \frac{e^{0.8891}+2(0.8891)}{3(0.8891)+2} = \frac{2.4329+1.7782}{4.6673} = 0.9023$. Diff: $0.0132$
> > $x_6 = \frac{e^{0.9023}+2(0.9023)}{3(0.9023)+2} = \frac{2.4653+1.8046}{4.7069} = 0.9072$. Diff: $0.0049$
> > $x_7 = \frac{e^{0.9072}+2(0.9072)}{3(0.9072)+2} = \frac{2.4774+1.8144}{4.7216} = 0.9089$. Diff: $0.0017$
> > $x_8 = \frac{e^{0.9089}+2(0.9089)}{3(0.9089)+2} = \frac{2.4816+1.8178}{4.7267} = 0.9096$. Diff: $0.0007$
> > $x_9 = \frac{e^{0.9096}+2(0.9096)}{3(0.9096)+2} = 0.9099$. Diff: $0.0003 < 0.0005$.
> > Root is approximately $0.9099$.
> > 
> > **iii.** $x_{i+1} = \frac{1}{\sqrt{1+x_i}}$. Let $x_0 = 0$.
> > $x_1 = 1/\sqrt{1} = 1.0000$. Diff: $1.0000$
> > $x_2 = 1/\sqrt{2} = 0.7071$. Diff: $0.2929$
> > $x_3 = 1/\sqrt{1.7071} = 0.7654$. Diff: $0.0583$
> > $x_4 = 1/\sqrt{1.7654} = 0.7526$. Diff: $0.0128$
> > $x_5 = 1/\sqrt{1.7526} = 0.7554$. Diff: $0.0028$
> > $x_6 = 1/\sqrt{1.7554} = 0.7548$. Diff: $0.0006$
> > $x_7 = 1/\sqrt{1.7548} = 0.7549$. Diff: $0.0001 < 0.0005$.
> > Root is approximately $0.7549$.

## 7.1.4 Newton Raphson Method
Newton Raphson method using tangent to find better estimation to the root nonlinear equation $f(x)=0$. Here is a picture to demonstrate what Newton Raphson method actually does:

![[Pasted image 20260216182433.png]]

The tangent line at the point $(x_{0}, f(x_{0}))$ is given by, $y-f(x_{0}) = f^{\prime}(x_{0})(x-x_{0})$. The new improved approximation for the root is $x_{1}$ where the tangent line at $(x_{0}, f(x_{0}))$ crosses x-axis $(y=0)$, then we have $0-f(x_{0}) = f^{\prime}(x_{0})(x_{1}-x_{0})$ given:
> [!formula]
> $x_{1}=x_{0}-\frac{f(x_{0})}{f^{\prime}(x_{0})}$

This process is repeated to obtain $x_{2}, x_{3}, x_{4}$ and so on. Thus, the general formula for Newton Raphson method is given by,
> [!formula]
> $x_{i+1}=x_{i}-\frac{f(x_{i})}{f^{\prime}(x_{i})}, \quad i=0,1,2,3,...$ provided $f^{\prime}(x_{i}) \ne 0$ for all i.

The iteration process can be repeated until $|f(x_{i})| < \epsilon$ or $|x_{i}-x_{i-1}| < \epsilon$ for some value of i, and specified tolerance small number $\epsilon$ and then take the desired root as $x^* = x_{i}$.

Newton Raphson method can be written as follows:
* **Step 1:** Choose a $x_{0}$ reasonably close to the root, $x^*$.
* **Step 2:** Compute $f(x_{0})$ and $f^{\prime}(x_{0})$.
* **Step 3:** If $f(x_{0}) \ne 0$ and $f^{\prime}(x_{0}) \ne 0$, then $x_{1}=x_{0}-\frac{f(x_{0})}{f^{\prime}(x_{0})}$.
* **Step 4:** For $i=0,1,2,3,... \quad x_{i+1}=x_{i}-\frac{f(x_{i})}{f^{\prime}(x_{i})}$.
* **Step 5:** Stop the iteration when $|f(x_{i})| < \epsilon$ or $|x_{i}-x_{i-1}| < \epsilon$ where $\epsilon$ was the specified value.

> [!example]- Example 7.5
> Solve the equation $e^{-x}-x=0$ for $[0,1]$ using Newton Raphson method. Use 4 decimal places for all calculation. Use the stopping $|f(x_{i})|<\epsilon$ where $\epsilon=0.0005$.
>
> > [!continue]- Solution
> > $f(x) = e^{-x}-x$
> > $f^{\prime}(x) = -e^{-x}-1$
> > Let $x_{0}=1$ be the initial approximation to the root, $x^*$. The formula is $x_{i+1} = x_{i} - \frac{e^{-x_{i}}-x_{i}}{-e^{-x_{i}}-1}$
> > Calculation in 4 decimal places and then let $\epsilon=0.0005$. Construct a table as below:
> > 
> > | $i$ | $x_i$ | $f(x_i)$ | $f^{\prime}(x_i)$ | $\frac{f(x_i)}{f^{\prime}(x_i)}$ | $x_{i+1} = x_i - \frac{f(x_i)}{f^{\prime}(x_i)}$ | $|x_{i+1} - x_i|$ |
> > | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
> > | 0 | 1 | $e^{-1}-1 = -0.6321$ | $-e^{-1}-1 = -1.3679$ | $0.4621$ | $1 - 0.4621 = 0.5379$ | $|0.5379 - 1| = 0.4621$ |
> > | 1 | 0.5379 | $0.0461$ | $-1.5840$ | $-0.0291$ | $0.5379 - (-0.0291) = 0.5670$ | $|0.5670 - 0.5379| = 0.0291$ |
> > | 2 | 0.5670 | $0.0002$ | - | - | - | - |
> > 
> > Since $|f(x_2)| = 0.0002 < 0.0005$ hence $x^* = x_2 = 0.5670$. To check your answer: $e^{-0.5670} - 0.5670 = 0.0002 \approx 0$.

> [!sq]- Problem 7.3
> 1. Use Newton Raphson method to find the root of $f(x)=0$ in given interval. Show all your calculation in 4 decimal places. Use the stopping criteria $|f(x_{i})|<\epsilon$ (Assume $\epsilon = 0.0005$).
> i. $x-\cos x=0$, $[0,\frac{\pi}{2}]$, $x_{0}=0$
> ii. $x-0.8-0.2\sin x=0$, $[0,\frac{\pi}{2}]$, $x_{0}=0$
> 2. Use Newton Raphson method to find the root of $x^{3}=6x-4$ in $[0,1]$. Show all your calculation in 3 significance figures. Use the stopping criteria $|x_{i}-x_{i-1}|<\epsilon$ (Assume $\epsilon = 0.005$).
>
> > [!continue]- Solution
> > **1. i.** $f(x) = x - \cos x = 0$, $x_0 = 0$. $f^{\prime}(x) = 1 + \sin x$.
> > $x_1 = 0 - \frac{0 - \cos 0}{1 + \sin 0} = 0 - \frac{-1}{1} = 1.0000$.
> > $x_2 = 1.0000 - \frac{1.0000 - \cos 1}{1 + \sin 1} = 1 - \frac{0.4597}{1.8415} = 0.7504$.
> > $x_3 = 0.7504 - \frac{0.7504 - \cos 0.7504}{1 + \sin 0.7504} = 0.7504 - \frac{0.0189}{1.6819} = 0.7391$.
> > $f(0.7391) = 0.7391 - \cos 0.7391 = 0.0000$. $|f(x_3)| < 0.0005$.
> > Root is approximately $0.7391$.
> > 
> > **1. ii.** $f(x) = x - 0.8 - 0.2\sin x = 0$, $x_0 = 0$. $f^{\prime}(x) = 1 - 0.2\cos x$.
> > $x_1 = 0 - \frac{-0.8}{1 - 0.2} = \frac{0.8}{0.8} = 1.0000$.
> > $x_2 = 1.0000 - \frac{1 - 0.8 - 0.2\sin 1}{1 - 0.2\cos 1} = 1 - \frac{0.0317}{0.8919} = 0.9645$.
> > $x_3 = 0.9645 - \frac{0.9645 - 0.8 - 0.2\sin 0.9645}{1 - 0.2\cos 0.9645} = 0.9645 - \frac{0.0002}{0.8859} = 0.9643$.
> > $f(0.9643) = 0.0000$. $|f(x_3)| < 0.0005$.
> > Root is approximately $0.9643$.
> > 
> > **2.** $f(x) = x^3 - 6x + 4 = 0$, $x_0 = 1$. $f^{\prime}(x) = 3x^2 - 6$.
> > $x_1 = 1 - \frac{1^3 - 6(1) + 4}{3(1^2) - 6} = 1 - \frac{-1}{-3} = 0.667$. Diff: $0.333$
> > $x_2 = 0.667 - \frac{0.667^3 - 6(0.667) + 4}{3(0.667^2) - 6} = 0.667 - \frac{0.295}{-4.665} = 0.667 + 0.063 = 0.730$. Diff: $0.063$
> > $x_3 = 0.730 - \frac{0.730^3 - 6(0.730) + 4}{3(0.730^2) - 6} = 0.730 - \frac{0.009}{-4.401} = 0.730 + 0.002 = 0.732$. Diff: $0.002 < 0.005$.
> > Root is approximately $0.732$ (to 3 significant figures).

# 7.2 NUMERICAL INTEGRATION
The method involved in approximation definite integral $\int_{a}^{b}f(x)dx$ using a numerical technique is known as numerical integration. There are essentially two situations where numerical integration is required, that is:
1. The values of function $f(x)$ are known but the function is unknown.
2. The function to be integrate is complicated and therefore it is difficult to integrate.

If $f(x)$ continuous on interval $[a,b]$ and $f(x) \ge 0$ for all $x \in [a,b]$, then definite integral $\int_{a}^{b}f(x)dx$ can be represented by as area under graph $y=f(x)$ bounded by x-axis, y-axis, line $x=a$ and line $x=b$ as shown in figure below. The problem of integration is simply reduced to the problem of finding the shaded area.

![[Pasted image 20260216182526.png]]

In general, a numerical integration formula approximates a definite integral by a weighted sum of values at points within the interval of integration.

![[Pasted image 20260216182541.png]]

## 7.2.1 Trapezoidal Rule
Trapezium rule is the simplest numerical integration method of finding the area under the curve $f(x)$, it uses the polynomial of order one (straight line) to approximate the function $f(x)$. The trapezium rule can be improved by dividing the interval into a small interval and applying the rule to each of these subintervals.

Apply the trapezoidal rule on these subintervals gives,
$\int_{a}^{b}f(x)dx=\int_{a=x_{0}}^{x_{1}}f(x)dx+\cdot\cdot\cdot+\int_{x_{N-1}}^{b=x_{N}}f(x)dx$

In general,
> [!formula]
> $\int_{a}^{b}f(x)dx\approx\frac{h}{2}[(f_{0}+f_{N})+2(f_{1}+\cdot\cdot\cdot+f_{N-1})]$ 
> $h=\frac{b-a}{N}$

where N is the number of strips and h is width of the strips and known as Trapezoidal Rule formula with $N>1$.

> [!example]- Example 7.6
> Use Trapezoidal rule to estimate the values of $\int_{0}^{1}x(1-x^{2})dx$ with the width of the strips, $h=0.25$.
>
> > [!continue]- Solution
> > Find the number of strips, $N=\frac{b-a}{h}=\frac{1-0}{0.25}=4$ and given the width of the strips, $h=0.25$.
> > Then $\int_{0}^{1}x(1-x^{2})dx\approx\frac{0.25}{2}[(f_{0}+f_{4})+2(f_{1}+f_{2}+f_{3})]$. We need to construct a table below:
> > 
> > | $i$ | $x_i$ | $f(x_i) = x_i(1-x_i^2)$ | |
> > | :--- | :--- | :--- | :--- |
> > | 0 | 0 | 0 | |
> > | 1 | 0.25 | | 0.2344 |
> > | 2 | 0.50 | | 0.3750 |
> > | 3 | 0.75 | | 0.3281 |
> > | 4 | 1.00 | 0 | |
> > | **TOTAL** | | **0** | **0.9375** |
> > 
> > $\int_{0}^{1}x(1-x^{2})dx \approx \frac{0.25}{2}[(0)+2(0.9375)] = 0.2344$. 
> > The exact value of $\int_{0}^{1}x(1-x^{2})dx$ is 0.25.
> > REMARKS: For a better approximation can be obtained by increasing the number of strips.

![[Pasted image 20260216182553.png]]

> [!sq]- Problem 7.4
> 1. Estimate $\int_{1}^{5}2e^{-2x}dx$ into 5 equal parts using Trapezoidal rule method.
> 2. Use Trapezoidal rule to approximate the value of $\int_{0}^{\frac{\pi}{2}}\sqrt{1+\cos x}dx$ with $N=6$.
> 3. Find the value of $\int_{0}^{\pi}e^{\sin x}dx$ by using Trapezoidal rule with $h=\frac{\pi}{4}$.
> 4. Evaluate $\int_{0}^{1}\frac{x}{\sqrt{x+1}}dx$ with $h=0.25$ by using Trapezoidal rule method. Use 4 decimal places for all calculation. *(Note: Bounds assumed to be 0 and 1 based on step size $h=0.25$ with standard 4 strips)*
> 5. Use Trapezoidal rule to approximate the value of $\int_{3}^{5}\sqrt{1+x}dx$ by dividing into 4 strips.
>
> > [!continue]- Solution
> > **1.** $N=5$, $h = \frac{5-1}{5} = 0.8$.
> > $x$ values: 1, 1.8, 2.6, 3.4, 4.2, 5
> > $f(x) = 2e^{-2x}$. Endpoints $f(1)+f(5) = 0.27067 + 0.00009 = 0.27076$.
> > Midpoints sum: $f(1.8)+f(2.6)+f(3.4)+f(4.2) = 0.05465 + 0.01103 + 0.00222 + 0.00045 = 0.06835$.
> > $\int \approx \frac{0.8}{2}[0.27076 + 2(0.06835)] = 0.4(0.40746) \approx 0.1630$.
> > 
> > **2.** $N=6$, $h = \frac{\pi/2}{6} = \frac{\pi}{12}$.
> > $x$ values: $0, \frac{\pi}{12}, \frac{2\pi}{12}, \frac{3\pi}{12}, \frac{4\pi}{12}, \frac{5\pi}{12}, \frac{6\pi}{12}$.
> > Endpoints $f(0)+f(\pi/2) = \sqrt{2} + \sqrt{1} = 1.4142 + 1 = 2.4142$.
> > Midpoints sum: $1.4021 + 1.3660 + 1.3066 + 1.2247 + 1.1220 = 6.4214$.
> > $\int \approx \frac{\pi/12}{2}[2.4142 + 2(6.4214)] = \frac{\pi}{24}(15.257) \approx 1.9971$.
> > 
> > **3.** $h = \frac{\pi}{4}$.
> > $x$ values: $0, \frac{\pi}{4}, \frac{\pi}{2}, \frac{3\pi}{4}, \pi$.
> > Endpoints $f(0)+f(\pi) = 1 + 1 = 2$.
> > Midpoints sum: $e^{\sin(\pi/4)} + e^{\sin(\pi/2)} + e^{\sin(3\pi/4)} = 2.0281 + 2.7183 + 2.0281 = 6.7745$.
> > $\int \approx \frac{\pi/4}{2}[2 + 2(6.7745)] = \frac{\pi}{8}(15.549) \approx 6.106$.
> > 
> > **4.** $\int_{0}^{1}\frac{x}{\sqrt{x+1}}dx$, $h=0.25$.
> > Endpoints $f(0)+f(1) = 0 + \frac{1}{\sqrt{2}} = 0.7071$.
> > Midpoints sum: $f(0.25)+f(0.5)+f(0.75) = 0.2236 + 0.4082 + 0.5669 = 1.1987$.
> > $\int \approx \frac{0.25}{2}[0.7071 + 2(1.1987)] = 0.125(3.1045) \approx 0.3881$.
> > 
> > **5.** $N=4$, $h = \frac{5-3}{4} = 0.5$.
> > Endpoints $f(3)+f(5) = \sqrt{4} + \sqrt{6} = 2 + 2.4495 = 4.4495$.
> > Midpoints sum: $f(3.5)+f(4)+f(4.5) = 2.1213 + 2.2361 + 2.3452 = 6.7026$.
> > $\int \approx \frac{0.5}{2}[4.4495 + 2(6.7026)] = 0.25(17.8547) \approx 4.4637$.

## 7.2.2 Simpson's Rule
Simpson's rule using polynomial quadratic (parabolic) for approximation the function, $f(x)$.
The Simpson's rule can be improved by dividing the interval into a small interval and applying the rule to each of these subintervals. Apply the Simpson's rule on these subintervals gives,
$\int_{a}^{b}f(x)dx=\int_{a=x_{0}}^{x_{2}}f(x)dx+\int_{x_{2}}^{x_{4}}f(x)dx+\cdot\cdot\cdot+\int_{x_{N-2}}^{b=x_{N}}f(x)dx$

In general,
> [!formula]
> $\int_{a}^{b}f(x)dx\approx\frac{h}{3}[(f_{0}+f_{N})+4(f_{1}+f_{3}+\cdot\cdot\cdot+f_{N-1})+2(f_{2}+f_{4}+\cdot\cdot\cdot+f_{N-2})],$
> $h=\frac{b-a}{N}$,

where N is the number of strips and h is width of the strips and known as Simpson's Rule formula with $N>2$ and N is even subinterval.

The Trapezoidal Rule does not give accurate value as Simpson's Rule when the underlying function is smooth. It is because Simpson's Rule uses the quadratic approximation instead of linear approximation. Both Simpson's Rule and Trapezoidal Rule give the approximation value, but Simpson's Rule results in even more accurate approximation value of the integrals.

> [!example]- Example 7.7
> Use Simpson's rule to estimate the values of $\int_{0}^{1}x(1-x^{2})dx$ with the width of the strips, $h=0.25$.
>
> > [!continue]- Solution
> > Find the number of strips, $N=\frac{b-a}{h}=\frac{1-0}{0.25}=4$ and given the width of the strips, $h=0.25$.
> > Then, $\int_{0}^{1}x(1-x^{2})dx\approx\frac{0.25}{3}[(f_{0}+f_{4})+4(f_{1}+f_{3})+2(f_{2})].$ We need to construct a table below:
> > 
> > | $i$ | $x_i$ | $f(x_i) = x_i(1-x_i^2)$ (Ends/Evens) | $f(x_i) = x_i(1-x_i^2)$ (Odds) |
> > | :--- | :--- | :--- | :--- |
> > | 0 | 0 | 0 | |
> > | 1 | 0.25 | | 0.2344 |
> > | 2 | 0.50 | 0.3750 | |
> > | 3 | 0.75 | | 0.3281 |
> > | 4 | 1.00 | 0 | |
> > | **TOTAL** | | **0.3750** (Wait, ends=0, evens=0.375) | **0.5625** |
> > 
> > $\int_{0}^{1}x(1-x^{2})dx \approx \frac{0.25}{3}[(0)+4(0.5625)+2(0.3750)] = 0.25$.
> > This value is the same as the exact value where $\int_{0}^{1}x(1-x^{2})dx=0.25$.

> [!sq]- Problem 7.5
> 1. Estimate $\int_{0}^{0.4}\sqrt[3]{1+x^{2}}dx$ with 8 subintervals using Simpson's rule method.
> 2. Evaluate $\int_{0}^{1}\frac{x}{\sqrt{x+1}}dx$ with $h=0.25$ by using Simpson's rule method. Use 4 decimal places for all calculations. *(Note: Bounds assumed to be 0 and 1 based on h=0.25 step size matching earlier problems)*
> 3. Find the value of $\int_{0}^{\frac{\pi}{4}}\cos^{4}xdx$ by using 5 ordinates.
>
> > [!continue]- Solution
> > **1.** $N=8$, $h = \frac{0.4}{8} = 0.05$.
> > $x$ values: 0, 0.05, 0.10, 0.15, 0.20, 0.25, 0.30, 0.35, 0.40.
> > Endpoints: $f(0)+f(0.4) = 1 + 1.0507 = 2.0507$.
> > Odds: $f(0.05)+f(0.15)+f(0.25)+f(0.35) = 1.0008 + 1.0074 + 1.0204 + 1.0393 = 4.0679$.
> > Evens: $f(0.10)+f(0.20)+f(0.30) = 1.0033 + 1.0132 + 1.0291 = 3.0456$.
> > $\int \approx \frac{0.05}{3}[2.0507 + 4(4.0679) + 2(3.0456)] = \frac{0.05}{3}(24.4135) \approx 0.4069$.
> > 
> > **2.** $h=0.25 \Rightarrow N=4$. $x$ values: 0, 0.25, 0.5, 0.75, 1.
> > Endpoints: $f(0)+f(1) = 0 + 0.7071 = 0.7071$.
> > Odds: $f(0.25)+f(0.75) = 0.2236 + 0.5669 = 0.7905$.
> > Evens: $f(0.5) = 0.4082$.
> > $\int \approx \frac{0.25}{3}[0.7071 + 4(0.7905) + 2(0.4082)] = \frac{0.25}{3}(4.6855) \approx 0.3905$.
> > 
> > **3.** 5 ordinates means $N=4$ strips. $h = \frac{\pi/4}{4} = \frac{\pi}{16}$.
> > Endpoints: $f(0)+f(\pi/4) = 1 + 0.2500 = 1.2500$.
> > Odds: $f(\pi/16)+f(3\pi/16) = 0.9254 + 0.4632 = 1.3886$.
> > Evens: $f(2\pi/16) = f(\pi/8) = 0.7500$.
> > $\int \approx \frac{\pi/16}{3}[1.2500 + 4(1.3886) + 2(0.7500)] = \frac{\pi}{48}(8.3044) \approx 0.5435$.

## 7.3 TUTORIAL 7

> [!sq]- Question 1
> Show the equation $f(x)=x^{4}+x^{2}-3$ has a root between $x=1$ and $x=1.3$.
>
> > [!continue]- Solution
> > $f(1) = 1^4 + 1^2 - 3 = -1$.
> > $f(1.3) = (1.3)^4 + (1.3)^2 - 3 = 2.8561 + 1.69 - 3 = 1.5461$.
> > Since $f(1)f(1.3) < 0$ and $f(x)$ is continuous on $[1, 1.3]$, by the Intermediate Value Theorem, there exists at least one root in $(1, 1.3)$.

> [!sq]- Question 2
> Sketch the graph $f(x)=x^{3}-4x+2$. Show that $f(x)=x^{3}-4x+2$ has roots in the interval $(-3,-2), (0,1)$ and $(1,2)$.
>
> > [!continue]- Solution
> > $f(-3) = (-3)^3 - 4(-3) + 2 = -27 + 12 + 2 = -13$.
> > $f(-2) = (-2)^3 - 4(-2) + 2 = -8 + 8 + 2 = 2$.
> > $f(-3)f(-2) < 0$, so a root exists in $(-3, -2)$.
> > 
> > $f(0) = 0^3 - 4(0) + 2 = 2$.
> > $f(1) = 1^3 - 4(1) + 2 = -1$.
> > $f(0)f(1) < 0$, so a root exists in $(0, 1)$.
> > 
> > $f(1) = -1$.
> > $f(2) = 2^3 - 4(2) + 2 = 8 - 8 + 2 = 2$.
> > $f(1)f(2) < 0$, so a root exists in $(1, 2)$.

> [!sq]- Question 3
> Use Intermediate Value Theorem to verify that the root of the equation $4 \sin x = e^{-x}$ is in the interval $(0, 1.5)$.
>
> > [!continue]- Solution
> > Let $f(x) = 4\sin x - e^{-x}$.
> > $f(0) = 4\sin(0) - e^0 = -1$.
> > $f(1.5) = 4\sin(1.5) - e^{-1.5} \approx 4(0.9975) - 0.2231 = 3.990 - 0.2231 = 3.7669$.
> > Since $f(0)f(1.5) < 0$ and the function is continuous, there is a root in $(0, 1.5)$.

> [!sq]- Question 4
> Given that $e^{2x}+4x=5$. Use Intermediate Value Theorem to verify that there exists a real root for the equation in the interval $(0,1)$.
>
> > [!continue]- Solution
> > Let $f(x) = e^{2x} + 4x - 5$.
> > $f(0) = e^0 + 4(0) - 5 = 1 - 5 = -4$.
> > $f(1) = e^2 + 4(1) - 5 = e^2 - 1 \approx 7.389 - 1 = 6.389$.
> > Since $f(0)f(1) < 0$ and $f(x)$ is continuous, there is a real root in $(0, 1)$.

> [!sq]- Question 5
> Verify that the root of the equation $\ln x = 4-x$ lies in the interval $(2.9,3)$.
>
> > [!continue]- Solution
> > Let $f(x) = \ln x + x - 4$.
> > $f(2.9) = \ln(2.9) + 2.9 - 4 \approx 1.0647 - 1.1 = -0.0353$.
> > $f(3) = \ln(3) + 3 - 4 \approx 1.0986 - 1 = 0.0986$.
> > Since $f(2.9)f(3) < 0$, a root exists in $(2.9, 3)$.

> [!sq]- Question 6
> Use Intermediate Value Theorem to determine which of the following interval may contain the root of the continuous equation $\cos 2x+x^{2}=6$.
> i. $(1,2)$.
> ii. $(2,3)$.
>
> > [!continue]- Solution
> > Let $f(x) = \cos 2x + x^2 - 6$.
> > **i.** $f(1) = \cos(2) + 1^2 - 6 = -0.4161 - 5 = -5.4161$.
> > $f(2) = \cos(4) + 2^2 - 6 = -0.6536 - 2 = -2.6536$.
> > Since $f(1)f(2) > 0$, we cannot confirm a root in $(1,2)$.
> > 
> > **ii.** $f(2) = -2.6536$.
> > $f(3) = \cos(6) + 3^2 - 6 = 0.9602 + 3 = 3.9602$.
> > Since $f(2)f(3) < 0$, the interval $(2,3)$ contains the root.

> [!sq]- Question 7
> After we know locating of the root, now we try to compute the root using fixed-point iteration and Newton-Raphson method.
> a) Verify that the equation $x^{3}+x^{2}-1=0$ has a root in the interval $(0,1)$.
> b) Show that the equation $x^{3}+x^{2}-1=0$ can be rearranged as,
> i. $x=\frac{1}{\sqrt{x+1}}$
> ii. $x=\frac{1}{x}-x^{2}$
> iii. $x=\sqrt{1-x^{3}}$ *(Note: Adjusted the expression to satisfy the original equation logically)*
>
> > [!continue]- Solution
> > **a)** Let $f(x) = x^3 + x^2 - 1$.
> > $f(0) = -1$.
> > $f(1) = 1 + 1 - 1 = 1$.
> > Since $f(0)f(1) < 0$, a root exists in $(0, 1)$.
> > 
> > **b)** > > **i.** $x^3 + x^2 - 1 = 0 \Rightarrow x^2(x + 1) = 1 \Rightarrow x^2 = \frac{1}{x+1} \Rightarrow x = \frac{1}{\sqrt{x+1}}$.
> > **ii.** $x^3 + x^2 - 1 = 0 \Rightarrow x^2 = 1 - x^3$. Divide by $x$: $x = \frac{1}{x} - x^2$.
> > **iii.** $x^3 + x^2 - 1 = 0 \Rightarrow x^2 = 1 - x^3 \Rightarrow x = \sqrt{1 - x^3}$.

> [!sq]- Question 8
> Show that the equation $e^{x}-4x^{3}=0$ can be written as $x=\ln 4+3 \ln x$. Furthermore, use the fixed-point iteration method with $g(x)=\ln 4+3 \ln x$ to find a root for the above equation starting with $x_{0}=7$. Stop the iteration when $|x_{i}-x_{i-1}|<0.005$ for $i=1,2,3,...$
>
> > [!continue]- Solution
> > $e^x - 4x^3 = 0 \Rightarrow e^x = 4x^3$.
> > Take the natural log of both sides: $\ln(e^x) = \ln(4x^3) \Rightarrow x = \ln 4 + \ln(x^3) \Rightarrow x = \ln 4 + 3\ln x$. (Shown).
> > Iteration $x_{i+1} = \ln 4 + 3\ln x_i$:
> > $x_0 = 7$
> > $x_1 = \ln 4 + 3\ln 7 = 1.3863 + 5.8377 = 7.2240$, Diff: $0.2240$
> > $x_2 = \ln 4 + 3\ln 7.2240 = 1.3863 + 5.9322 = 7.3185$, Diff: $0.0945$
> > $x_3 = \ln 4 + 3\ln 7.3185 = 1.3863 + 5.9712 = 7.3575$, Diff: $0.0390$
> > $x_4 = \ln 4 + 3\ln 7.3575 = 1.3863 + 5.9872 = 7.3735$, Diff: $0.0160$
> > $x_5 = \ln 4 + 3\ln 7.3735 = 1.3863 + 5.9937 = 7.3800$, Diff: $0.0065$
> > $x_6 = \ln 4 + 3\ln 7.3800 = 1.3863 + 5.9963 = 7.3826$, Diff: $0.0026 < 0.005$.
> > The root is approximately $7.38$.

> [!sq]- Question 9
> Apply Newton-Raphson method to find the root of the equation $x^{3}=6x-4$ correct to three significant figures, starting with $x_{0}=1$.
>
> > [!continue]- Solution
> > $f(x) = x^3 - 6x + 4 = 0$. $f^{\prime}(x) = 3x^2 - 6$.
> > $x_{i+1} = x_i - \frac{x_i^3 - 6x_i + 4}{3x_i^2 - 6}$.
> > $x_0 = 1$
> > $x_1 = 1 - \frac{1 - 6 + 4}{3 - 6} = 1 - \frac{-1}{-3} = 0.667$
> > $x_2 = 0.667 - \frac{0.667^3 - 6(0.667) + 4}{3(0.667)^2 - 6} = 0.667 - \frac{0.295}{-4.665} = 0.667 + 0.063 = 0.730$
> > $x_3 = 0.730 - \frac{0.730^3 - 6(0.730) + 4}{3(0.730)^2 - 6} = 0.730 - \frac{0.009}{-4.401} = 0.730 + 0.002 = 0.732$
> > $x_4 = 0.732 - \frac{0.732^3 - 6(0.732) + 4}{3(0.732)^2 - 6} = 0.732$
> > The root correct to three significant figures is $0.732$.

> [!sq]- Question 10 & 11
> 10. Use Trapezoidal rule to estimate the value of $\int_{0}^{0.6}\sqrt{1+x+x^{2}}dx$ with the width of strips $h=0.1$.
> 11. Estimate $\int_{0}^{\pi}e^{\sin x}dx$ using Trapezoidal rule with the width is $h=\frac{\pi}{5}$.
>
> > [!continue]- Solution
> > **10. $\int_{0}^{0.6}\sqrt{1+x+x^{2}}dx$, $h=0.1$**
> > $x$ values: 0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6.
> > Endpoints: $f(0) + f(0.6) = 1 + \sqrt{1.96} = 1 + 1.4 = 2.4000$.
> > Midpoints: $\sqrt{1.11} + \sqrt{1.24} + \sqrt{1.39} + \sqrt{1.56} + \sqrt{1.75} = 1.0536 + 1.1136 + 1.1790 + 1.2490 + 1.3229 = 5.9181$.
> > $\int \approx \frac{0.1}{2} [2.4000 + 2(5.9181)] = 0.05(14.2362) = 0.7118$.
> > 
> > **11. $\int_{0}^{\pi}e^{\sin x}dx$, $h=\frac{\pi}{5}$**
> > $x$ values: $0, \frac{\pi}{5}, \frac{2\pi}{5}, \frac{3\pi}{5}, \frac{4\pi}{5}, \pi$.
> > Endpoints: $f(0) + f(\pi) = e^0 + e^0 = 1 + 1 = 2$.
> > Midpoints: $e^{\sin(\pi/5)} + e^{\sin(2\pi/5)} + e^{\sin(3\pi/5)} + e^{\sin(4\pi/5)} = e^{0.5878} + e^{0.9511} + e^{0.9511} + e^{0.5878} = 1.8000 + 2.5885 + 2.5885 + 1.8000 = 8.7770$.
> > $\int \approx \frac{\pi/5}{2} [2 + 2(8.7770)] = \frac{\pi}{10}(19.554) = 6.143$.

> [!sq]- Question 12
> Estimate $\int_{0}^{2}\frac{1}{x^{2}+x+1}dx$ to four decimal places, dividing the range of integration into eight parts using Simpson's rule.
>
> > [!continue]- Solution
> > $N=8$, $h = \frac{2-0}{8} = 0.25$.
> > $x$ values: 0, 0.25, 0.50, 0.75, 1.00, 1.25, 1.50, 1.75, 2.00.
> > Endpoints: $f(0) + f(2) = 1 + \frac{1}{7} = 1.1429$.
> > Odds: $f(0.25) + f(0.75) + f(1.25) + f(1.75) = \frac{1}{1.3125} + \frac{1}{2.3125} + \frac{1}{3.8125} + \frac{1}{5.8125} = 0.7619 + 0.4324 + 0.2623 + 0.1720 = 1.6286$.
> > Evens: $f(0.50) + f(1.00) + f(1.50) = \frac{1}{1.75} + \frac{1}{3} + \frac{1}{4.75} = 0.5714 + 0.3333 + 0.2105 = 1.1152$.
> > $\int \approx \frac{0.25}{3} [1.1429 + 4(1.6286) + 2(1.1152)] = \frac{0.25}{3}[1.1429 + 6.5144 + 2.2304] = \frac{0.25}{3}(9.8877) = 0.8240$.

> [!sq]- Question 13
> Use Simpsons' rule with eight strips to obtain an estimate value of $\int_{2}^{3}\cos(x-2)\ln x dx$.
>
> > [!continue]- Solution
> > $N=8$, $h = \frac{3-2}{8} = 0.125$.
> > $x$ values: 2, 2.125, 2.250, 2.375, 2.500, 2.625, 2.750, 2.875, 3.
> > Endpoints: $f(2) + f(3) = (\cos 0)(\ln 2) + (\cos 1)(\ln 3) = 0.6931 + 0.5403(1.0986) = 0.6931 + 0.5936 = 1.2867$.
> > Odds: $f(2.125) + f(2.375) + f(2.625) + f(2.875) = \cos(0.125)\ln(2.125) + \cos(0.375)\ln(2.375) + \cos(0.625)\ln(2.625) + \cos(0.875)\ln(2.875) = (0.9922)(0.7538) + (0.9305)(0.8650) + (0.8110)(0.9651) + (0.6410)(1.0561) = 0.7479 + 0.8049 + 0.7827 + 0.6769 = 3.0124$.
> > Evens: $f(2.250) + f(2.500) + f(2.750) = \cos(0.25)\ln(2.25) + \cos(0.5)\ln(2.5) + \cos(0.75)\ln(2.75) = (0.9689)(0.8109) + (0.8776)(0.9163) + (0.7317)(1.0116) = 0.7857 + 0.8041 + 0.7402 = 2.3300$.
> > $\int \approx \frac{0.125}{3} [1.2867 + 4(3.0124) + 2(2.3300)] = \frac{0.125}{3}[1.2867 + 12.0496 + 4.6600] = \frac{0.125}{3}(17.9963) \approx 0.7498$.

