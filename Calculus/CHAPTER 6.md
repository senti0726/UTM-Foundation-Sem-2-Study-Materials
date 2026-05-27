$$\underline{\Huge\text{ORDINARY DIFFERENTIAL EQUATION}}$$

# 6.0 INTRODUCTION
A differential equation is an equation with a function and one or more of its derivatives.

> [!formula]
> $\frac{dy}{dx} + y = 5x$

Such equations are extremely important in all branches of science; mathematics, physics, chemistry, biochemistry, economics. Typical examples are:

Newton's law of cooling which states that the rate of change of temperature is proportional to the temperature difference between it and that of its surroundings.
$\frac{dT}{dt}=k(T-T_{0})$.
where $T(t)$ is the temperature of the body at a time t, $T_{0}$ is the temperature of the surroundings and k is a constant of proportionally.

The example has unknown function, $T(t)$ depending on one variable, t and the relation involves the derivative $\frac{dT}{dt}$.

The unknown function is called the dependent variable and the variable or variables on which it depends are the independent variables.

A solution of a differential equation is an expression for the dependent variable in terms of the independent variable/s which satisfies the relation.

# 6.1 BASIC CONCEPTS
An ordinary differential equation (ODE) contains differentials with respect to only one independent variable. While a partial differential equation (PDE) contains differentials with respect to several independent variables.

| ODE | PDE |
| :--- | :--- |
| $\frac{dy}{dx}=x \sin(x^{2})\cos y$ | $\frac{\partial u}{\partial x}+\frac{\partial u}{\partial y}+u=e^{x-y}$ |
| $\frac{dy}{dx}=y \csc x+e^{x}$ | $3\frac{\partial^{2} u}{\partial x^{2}}+7\frac{\partial^{2} u}{\partial x\partial y}+6\frac{\partial^{2} u}{\partial y^{2}}=0$ |
| $\frac{d^{2}y}{dx^{2}}+4xy\frac{dy}{dx}+5y=0$ | $\frac{\partial v}{\partial t}-k\frac{\partial^{2} v}{\partial x^{2}}=v$ |

The order of a differential equation is the order of the highest derivative that occurs in the equation.

| Example | Order |
| :--- | :--- |
| $\frac{d^{2}y}{dx^{2}}+x=0$ | Second |
| $\frac{dx}{dt}+\frac{dy}{dt}=0$ | First |
| $\frac{d^{2}x}{dt^{2}}+2\frac{dx}{dt}+x=0$ | Second |

In this chapter we only deal with first order ordinary differential equations. The method to solve the first order ordinary differential equations which is either separable or linear.

# 6.2 FIRST ORDER ORDINARY DIFFERENTIAL EQUATIONS

![[Pasted image 20260216180539.png]]

## 6.2.1 Initial Value Problem
A differential equation together with one or more initial values is called an initial-value problem. This problem can be solved by using the initial data and plug it into the general solution and solve for C.

For example, we have $y^{\prime}=x^{2}-4x+3-6e^{x}$ and $y(0)=8$. First take the antiderivative of both sides of the differential equation to get y. Then, substitute $x=0$ and $y=8$ into the resulting equation and solve for C. Thus, we get $y=\frac{x^{3}}{3}-2x^{2}+3x-6e^{x}+14.$

## 6.2.2 Separable Equations
Suppose given $f(x,y)=\frac{dy}{dx}$. Hence, this is become a separable equation if it can write as,
$\frac{dy}{dx}=u(x)v(y)$
$\frac{1}{v(y)}dy=u(x)dx$

The method of solution is to integrate both sides, that is
> [!formula]
> $\int\frac{1}{v(y)}dy=\int u(x)dx$

> [!example]- Example 6.1
> Solve the following equation if $\frac{dy}{dx}=\frac{y \cos x}{1+2y^{2}}.$
>
> > [!continue]- Solution
> > $\frac{1+2y^{2}}{y}dy=\cos x dx$
> > $\int\frac{1+2y^{2}}{y}dy=\int \cos x dx$
> > $\int\left(\frac{1}{y}+2y\right)dy=\int \cos x dx$
> > $\ln|y|+y^{2}=\sin x+C$

> [!example]- Example 6.2
> Solve the following equation if $e^{x+2y}\frac{dy}{dx}=3$.
>
> > [!continue]- Solution
> > $e^{2y}dy=\frac{3}{e^{x}}dx$
> > $\int e^{2y}dy=\int 3e^{-x}dx$
> > $\frac{e^{2y}}{2}=-3e^{-x}+C$

> [!example]- Example 6.3
> Solve the following equation if $(x^{2}+1)\cos^{3}y\frac{dy}{dx}=x.$
>
> > [!continue]- Solution
> > $\cos^{3}y dy=\frac{x}{x^{2}+1}dx$
> > $\int \cos^{3}y dy=\int\frac{x}{x^{2}+1}dx$
> > $\int \cos^{2}y \cos y dy=\int\frac{x}{x^{2}+1}dx$
> > Let $u=\sin y \Rightarrow du=\cos y dx$ for LHS.
> > Let $w=x^{2}+1 \Rightarrow dw=2xdx \Rightarrow xdx=\frac{dw}{2}$ for RHS.
> > $\int(1-\sin^{2}y)\cos y dy=\int\frac{1}{w}\frac{dw}{2}$
> > $\int(1-u^{2})du=\frac{1}{2}\int\frac{1}{w}dw \Rightarrow u-\frac{u^{3}}{3}=\frac{\ln|w|}{2}$
> > $\sin y-\frac{\sin^{3}y}{3}=\frac{\ln|x^{2}+1|}{2}+C$

> [!example]- Example 6.4
> Solve the following equation if $(x+2)\frac{dy}{dx}=y-3$.
>
> > [!continue]- Solution
> > $\frac{1}{y-3}dy=\frac{1}{x+2}dx$
> > $\int\frac{1}{y-3}dy=\int\frac{1}{x+2}dx$
> > $\ln|y-3|=\ln|x+2|+C$
> > $\ln|y-3|=\ln|x+2|+\ln A$ (Let $C = \ln A$)
> > $y-3=A(x+2)$

> [!example]- Example 6.5
> Solve the initial value problem $\frac{dy}{dx}=xy^{2}e^{-x}$ and $y(0)=2$.
>
> > [!continue]- Solution
> > $\frac{1}{y^{2}}dy=xe^{-x}dx$
> > $\int y^{-2}dy=\int xe^{-x}dx$
> > Using tabular integration for RHS:
> > 
> > | Sign | $u$ | $v^{\prime}$ |
> > | :--- | :--- | :--- |
> > | + | $x$ | $e^{-x}$ |
> > | - | $1$ | $-e^{-x}$ |
> > | + | $0$ | $e^{-x}$ |
> > 
> > $-\frac{1}{y}=-xe^{-x}-e^{-x}+C$
> > When $y(0)=2$,
> > $-\frac{1}{2}=-(0)e^{-0}-e^{-0}+C \Rightarrow -\frac{1}{2} = -1 + C \Rightarrow C=\frac{1}{2}$
> > $-\frac{1}{y}=-xe^{-x}-e^{-x}+\frac{1}{2} \Rightarrow -\frac{1}{y} = \frac{-2xe^{-x}-2e^{-x}+1}{2}$
> > $y=\frac{2}{2e^{-x}(x+1)-1}$

> [!sq]- Problem 6.1
> 1. Solve the following first order ordinary differential equations:
> i. $(x^{2}+1)\frac{dy}{dx}=xy$
> ii. $r \tan \theta\frac{dr}{d\theta}=(4+r^{2})\sec^{2}\theta$
> iii. $(y+1)(x^{3}+x+1)dy=(y-y^{2})(6x^{2}+2)dx$
> 
> 2. Solve the following differential equation which satisfies the given initial value problem:
> $\frac{dy}{\sqrt{y+3}}-xe^{2x}dx=0$ when $y(0)=1$
>
> > [!continue]- Solution
> > **1. i. $(x^{2}+1)\frac{dy}{dx}=xy$**
> > $\frac{1}{y}dy = \frac{x}{x^2+1}dx$
> > $\int \frac{1}{y} dy = \int \frac{x}{x^2+1} dx \Rightarrow \ln|y| = \frac{1}{2}\ln(x^2+1) + C$
> > $\ln|y| = \ln\sqrt{x^2+1} + \ln A \Rightarrow y = A\sqrt{x^2+1}$.
> > 
> > **1. ii. $r \tan \theta\frac{dr}{d\theta}=(4+r^{2})\sec^{2}\theta$**
> > $\frac{r}{4+r^2}dr = \frac{\sec^2\theta}{\tan\theta}d\theta$
> > $\int \frac{r}{4+r^2} dr = \int \frac{\sec^2\theta}{\tan\theta} d\theta$
> > $\frac{1}{2}\ln(4+r^2) = \ln|\tan\theta| + C \Rightarrow \ln\sqrt{4+r^2} = \ln|A\tan\theta| \Rightarrow \sqrt{4+r^2} = A\tan\theta$.
> > 
> > **1. iii. $(y+1)(x^{3}+x+1)dy=(y-y^{2})(6x^{2}+2)dx$**
> > $\frac{y+1}{y-y^2}dy = \frac{6x^2+2}{x^3+x+1}dx \Rightarrow \frac{y+1}{y(1-y)}dy = \frac{2(3x^2+1)}{x^3+x+1}dx$.
> > Using partial fractions for LHS: $\frac{y+1}{y(1-y)} = \frac{1}{y} + \frac{2}{1-y}$.
> > $\int \left(\frac{1}{y} + \frac{2}{1-y}\right)dy = \int \frac{2(3x^2+1)}{x^3+x+1}dx$
> > $\ln|y| - 2\ln|1-y| = 2\ln|x^3+x+1| + C \Rightarrow \ln\left|\frac{y}{(1-y)^2}\right| = \ln(x^3+x+1)^2 + \ln A$
> > $\frac{y}{(1-y)^2} = A(x^3+x+1)^2$.
> > 
> > **2. $\frac{dy}{\sqrt{y+3}}-xe^{2x}dx=0$ when $y(0)=1$**
> > $(y+3)^{-1/2}dy = xe^{2x}dx$
> > $\int (y+3)^{-1/2}dy = \int xe^{2x}dx$
> > $2(y+3)^{1/2} = \frac{x}{2}e^{2x} - \frac{1}{4}e^{2x} + C$.
> > Apply initial condition $y(0)=1$:
> > $2(1+3)^{1/2} = \frac{0}{2}e^{0} - \frac{1}{4}e^{0} + C \Rightarrow 2(2) = -\frac{1}{4} + C \Rightarrow 4 = -\frac{1}{4} + C \Rightarrow C = \frac{17}{4}$.
> > Solution: $2\sqrt{y+3} = \frac{x}{2}e^{2x} - \frac{1}{4}e^{2x} + \frac{17}{4}$.

## 6.2.3 Linear Equations
Suppose given the differential equation in the form of,
$a(x)\frac{dy}{dx}+b(x)y=c(x)$,
where $a(x)$, $b(x)$ and $c(x)$ are constants or continuous functions of x. When the above equation is divided by $a(x)$, gives:
$\frac{dy}{dx}+\frac{b(x)}{a(x)}y=\frac{c(x)}{a(x)}$
Or it can be rewrite in the form of $y^{\prime}+P(x)=Q(x)$, where $P(x)=\frac{b(x)}{a(x)}$ and $Q(x)=\frac{c(x)}{a(x)}$.

Thus, the equation is known as linear equation. The method of solution are as follows:
* **Step 1.** Rewrite the given equations in the form of $y^{\prime}+P(x)=Q(x)$, with the coefficient of $\frac{dy}{dx}$ must be equal to 1.
* **Step 2.** Determine $P(x)$ and $Q(x)$
* **Step 3.** Find the integrating factor, $\mu(x)=e^{\int P(x)dx}$
* **Step 4.** Write in the form of $\frac{d}{dx}[y\mu(x)]=Q(x)\mu(x)$
* **Step 5.** Solve $y\mu(x)=\int Q(x)\mu(x)dx$ and find the general solution.

> [!example]- Example 6.6
> Solve the differential equation $(x^{4}+2y)dx-xdy=0$.
>
> > [!continue]- Solution
> > Rewrite in the form of $y^{\prime}+P(x)=Q(x);$
> > $x\frac{dy}{dx}=x^{4}+2y$
> > $\frac{dy}{dx}=x^{3}+\frac{2}{x}y$
> > $\frac{dy}{dx}-\frac{2}{x}y=x^{3}$
> > $P(x)=-\frac{2}{x}$, $Q(x)=x^{3}$
> > $\mu(x)=e^{\int-\frac{2}{x}dx}=e^{-2 \ln|x|}=e^{\ln|x^{-2}|}=x^{-2}$
> > $yx^{-2}=\int x^{3}x^{-2}dx=\int x dx$
> > $yx^{-2}=\frac{x^{2}}{2}+C$
> > $y=\frac{x^{4}}{2}+Cx^{2}$

> [!example]- Example 6.7
> Solve the differential equation $(x+2)\frac{dy}{dx}+2y=3(x+2)^{2}$ and given $y(0)=1$.
>
> > [!continue]- Solution
> > Rewrite in the form of $y^{\prime}+P(x)=Q(x);$
> > $\frac{dy}{dx}+\frac{2}{x+2}y=3(x+2)$
> > $P(x)=\frac{2}{x+2}$, $Q(x)=3(x+2)$
> > $\mu(x)=e^{\int\frac{2}{x+2}dx}=e^{2 \ln|x+2|}=e^{\ln|(x+2)^{2}|}=(x+2)^{2}$
> > $y(x+2)^{2}=\int 3(x+2)(x+2)^{2}dx = \int 3(x+2)^{3}dx$
> > $y(x+2)^{2}=\frac{3(x+2)^{4}}{(4)(1)}+C$
> > $y=\frac{3(x+2)^{2}}{4}+C(x+2)^{-2}$
> > When $y(0)=1$, $1=\frac{3(0+2)^{2}}{4}+C(0+2)^{-2} \Rightarrow 1 = 3 + \frac{C}{4} \Rightarrow \frac{C}{4} = -2 \Rightarrow C=-8$
> > $y=\frac{3(x+2)^{2}}{4}-8(x+2)^{-2}$

> [!example]- Example 6.8
> Solve the differential equation $x\frac{dy}{dx}+y=\frac{\ln x}{x}$
>
> > [!continue]- Solution
> > Rewrite in the form of $y^{\prime}+P(x)=Q(x)$:
> > $\frac{dy}{dx}+\frac{1}{x}y=\frac{\ln x}{x^{2}}$
> > $P(x)=\frac{1}{x}$
> > $Q(x)=\frac{\ln x}{x^{2}}$
> > $\mu(x)=e^{\int\frac{1}{x}dx}=e^{\ln|x|}=x$
> > $yx=\int\frac{\ln x}{x}dx$
> > $u=\ln x$, $v^{\prime}=\frac{1}{x}dx$
> > $du=\frac{1}{x}dx$, $v=\ln x$
> > $\int\frac{\ln x}{x}dx=(\ln x)^{2}-\int\frac{\ln x}{x}dx$
> > $2\int\frac{\ln x}{x}dx=(\ln x)^{2}$
> > $\int\frac{\ln x}{x}dx=\frac{(\ln x)^{2}}{2}$
> > $yx=\frac{(\ln x)^{2}}{2}+C$
> > $y=\frac{(\ln x)^{2}}{2x}+\frac{C}{x}$

> [!example]- Example 6.9
> Solve the initial value problem $x\frac{dy}{dx}=y+x^{2}\sin x$ and given $y(\pi)=0$.
> 
> > [!tip]- Textbook Factual error: The text rewrites the equation as $\frac{dy}{dx}+\frac{1}{x}y=x\sin x$. However, dividing the original equation $x\frac{dy}{dx} = y + x^2\sin x$ by $x$ and rearranging actually yields $\frac{dy}{dx}-\frac{1}{x}y=x\sin x$. Consequently, the integrating factor should be $x^{-1}$, not $x$. The source proceeds with the incorrect sign. The steps below reproduce the source text exactly.
>
> > [!continue]- Solution
> > Rewrite in the form of $y^{\prime}+P(x)=Q(x)$:
> > $\frac{dy}{dx}+\frac{1}{x}y=x \sin x$
> > $P(x)=\frac{1}{x}$
> > $Q(x)=x \sin x$
> > $\mu(x)=e^{\int\frac{1}{x}dx}=e^{\ln|x|}=x$
> > $\frac{y}{x}=\int \sin x dx$ *(Note: Integrand should be $x \cdot x \sin x = x^2\sin x$ based on $Q(x)\cdot \mu(x)$, source omits $x^2$ here)*
> > $\frac{y}{x}=-\cos x+C$
> > When $y(\pi)=0$
> > $0=-\cos \pi+C \Rightarrow C=-1$
> > $y=-x \cos x-x$

> [!sq]- Problem 6.2
> 1. Solve the following first order ordinary differential equations:
> a) $\frac{dy}{dx}-2y=xe^{4x}$
> b) $\frac{dy}{dx}-y \tan x=\sin x$
> c) $(x+1)dy-3ydx=(x+1)^{4}dx$
> 
> 2. Solve the following differential equation which satisfies the given initial value problem:
> $x\frac{dy}{dx}-2y=x^{3}e^{4x-1}$ when $y(\frac{1}{4})=1$
>
> > [!continue]- Solution
> > **1. a) $\frac{dy}{dx}-2y=xe^{4x}$**
> > $P(x) = -2$, $Q(x) = xe^{4x}$.
> > Integrating factor $\mu(x) = e^{\int -2 dx} = e^{-2x}$.
> > Multiply equation by $\mu(x)$: $\frac{d}{dx}(y e^{-2x}) = x e^{4x} e^{-2x} = x e^{2x}$.
> > $y e^{-2x} = \int x e^{2x} dx$.
> > Using integration by parts: $u=x \Rightarrow du=dx$; $dv=e^{2x}dx \Rightarrow v=\frac{1}{2}e^{2x}$.
> > $y e^{-2x} = \frac{1}{2}x e^{2x} - \int \frac{1}{2}e^{2x} dx = \frac{1}{2}x e^{2x} - \frac{1}{4}e^{2x} + C$.
> > $y = \frac{1}{2}x e^{4x} - \frac{1}{4}e^{4x} + C e^{2x}$.
> > 
> > **1. b) $\frac{dy}{dx}-y \tan x=\sin x$**
> > $P(x) = -\tan x$, $Q(x) = \sin x$.
> > $\mu(x) = e^{\int -\tan x dx} = e^{\ln|\cos x|} = \cos x$.
> > $\frac{d}{dx}(y \cos x) = \sin x \cos x$.
> > $y \cos x = \int \sin x \cos x dx = \frac{1}{2}\sin^2 x + C$.
> > $y = \frac{\sin^2 x}{2\cos x} + \frac{C}{\cos x} = \frac{1}{2}\sin x \tan x + C \sec x$.
> > 
> > **1. c) $(x+1)dy-3ydx=(x+1)^{4}dx$**
> > Divide by $(x+1)dx$: $\frac{dy}{dx} - \frac{3}{x+1}y = (x+1)^3$.
> > $P(x) = -\frac{3}{x+1}$, $Q(x) = (x+1)^3$.
> > $\mu(x) = e^{\int -\frac{3}{x+1} dx} = e^{-3\ln|x+1|} = (x+1)^{-3}$.
> > $\frac{d}{dx}(y(x+1)^{-3}) = (x+1)^3 (x+1)^{-3} = 1$.
> > $y(x+1)^{-3} = \int 1 dx = x + C$.
> > $y = (x+1)^3(x + C)$.
> > 
> > **2. $x\frac{dy}{dx}-2y=x^{3}e^{4x-1}$ when $y(\frac{1}{4})=1$**
> > Divide by $x$: $\frac{dy}{dx} - \frac{2}{x}y = x^2 e^{4x-1}$.
> > $P(x) = -\frac{2}{x}$, $Q(x) = x^2 e^{4x-1}$.
> > $\mu(x) = e^{\int -\frac{2}{x} dx} = e^{-2\ln|x|} = x^{-2}$.
> > $\frac{d}{dx}(y x^{-2}) = (x^2 e^{4x-1})(x^{-2}) = e^{4x-1}$.
> > $y x^{-2} = \int e^{4x-1} dx = \frac{1}{4}e^{4x-1} + C$.
> > $y = \frac{1}{4}x^2 e^{4x-1} + C x^2$.
> > Apply initial condition $y(1/4)=1$:
> > $1 = \frac{1}{4}(\frac{1}{4})^2 e^{4(1/4)-1} + C(\frac{1}{4})^2 \Rightarrow 1 = \frac{1}{64}e^0 + \frac{C}{16} \Rightarrow 1 = \frac{1}{64} + \frac{4C}{64}$.
> > $64 = 1 + 4C \Rightarrow 4C = 63 \Rightarrow C = \frac{63}{4}$.
> > $y = \frac{1}{4}x^2 e^{4x-1} + \frac{63}{4}x^2$.

# 6.3 APPLICATIONS OF DIFFERENTIAL EQUATIONS
Now we will apply the methods learnt in the previous sections to the solution of some practical situations.

## 6.3.1 Population Growth Model
The simplest growth model has a constant relative growth rate. If we denote the population, we are considering by $P(t)$, then the rate of change of the population is $\frac{dP}{dt}$.

To say that the rate of change is proportional to the population is just saying that there is a constant of proportionality k such that,
> [!formula]
> $\frac{dP}{dt}=kP$

Since k is a constant, this can be immediately separated and integrated to yield:
$\frac{dP}{dt}=kP$
$\int\frac{1}{P}dP=\int k dt$
$\ln P=kt+C$
$P=e^{kt+C}$
$P=Ce^{kt}$

> [!example]- Example 6.10
> Suppose that a bacteria dish contains 6 000 bacteria at 9:00pm and 10 000 bacteria at 11:00pm. How many of the bacteria were there at 7:00pm? Given $\frac{dN}{dt}=kN$, where $N(t)$ is the number of bacteria present at any time, t.
>
> > [!continue]- Solution
> > $\frac{dN}{dt}=kN$
> > $\int\frac{1}{N}dN=\int k dt$
> > $\ln N=kt+C$
> > $N=e^{kt+C} \Rightarrow N=Ce^{kt}$
> > 
> > Let 9:00pm be $t=0$. When $t=0$, $N=6000$
> > $6000=Ce^{0} \Rightarrow C=6000$
> > $N=6000e^{kt}$
> > 
> > 11:00pm corresponds to $t=2$. When $t=2$, $N=10000$
> > $10000=6000e^{2k} \Rightarrow e^{2k}=\frac{5}{3}$
> > $k=\frac{\ln\frac{5}{3}}{2}=0.2554$
> > $N=6000e^{0.2554t}$
> > 
> > To find bacteria at 7:00pm, we use $t=-2$:
> > When $t=-2$, $N=6000e^{0.2554(-2)}=3600$

## 6.3.2 Radioactive Decay Model
Radioactive decay models, on the other hand, are very accurate over long periods of time. They are the primary method for determining age of ancient artifacts. If we denote the decay, we are considering by $M(t)$, then the decreasing rate of the decay is $\frac{dM}{dt}$.

To say that the decreasing rate is proportional to the decay is just saying that there is a constant of proportionality k such that
> [!formula]
> $\frac{dM}{dt}=-kM$

Since k is a constant, this can be immediately separated and integrated to yield:
$\frac{dM}{dt}=-kM$
$\int\frac{1}{M}dM=\int-k dt$
$\ln M=-kt+C$
$M=e^{-kt+C}$
$M=Ce^{-kt}$

> [!example]- Example 6.11
> 5g of a certain radioactive isotope decay to 3g in 100 years. After how many more years will there be just 1g? Given $\frac{dM}{dt}=-kM$, where $M(t)$ is the amount of radioactive present at any time, t.
>
> > [!continue]- Solution
> > $\frac{dM}{dt}=-kM$
> > $\int\frac{1}{M}dM=\int-k dt$
> > $\ln M=-kt+C$
> > $M=e^{-kt+C} \Rightarrow M=Ce^{-kt}$
> > 
> > When $t=0$, $M=5$
> > $5=Ce^{0} \Rightarrow C=5$
> > $M=5e^{-kt}$
> > 
> > When $t=100$, $M=3$
> > $3=5e^{-k(100)} \Rightarrow e^{-100k}=\frac{5}{3}$ *(Note: Should be $3/5$, but text evaluates k properly with a negative denominator)*
> > $k=\frac{\ln\frac{5}{3}}{-100}=0.0051.$ *(Note: Text uses $\ln(5/3)/-100$, implying $e^{100k}=5/3$, so $k=\ln(5/3)/100=0.0051$)*
> > $M=5e^{-0.0051t}.$
> > 
> > When $M=1$,
> > $1=5e^{-0.0051t} \Rightarrow e^{-0.0051t}=\frac{1}{5}$
> > $-0.0051t=\ln\frac{1}{5}$
> > $t=\frac{\ln\frac{1}{5}}{-0.0051}=315.6\text{ years}$

## 6.3.3 Newton's Law Model
When an object has a temperature greater than the constant temperature, it cools according to Newton's Law of cooling which states that the rate of cooling is proportional to the difference in the temperatures, that is
$\frac{dT}{dt}=-k(T-T_{c})$, where $T(t)$ is the temperature of the object at any time, t and $T_{c}$ is the constant temperature. The solution to this separable differential equation is:
$\frac{dT}{dt}=-k(T-T_{c})$
$\int\frac{1}{T-T_{c}}dT=\int-k dt$
$\ln|T-T_{c}|=-kt+C$
$T-T_{c}=e^{-kt+C} \Rightarrow T=Ce^{-kt}+T_{c}$

> [!example]- Example 6.12
> A turkey is taken from the oven at $300^{\circ}\text{F}$ and placed at room temperature of $70^{\circ}\text{F}$. In $t=2$ minutes, the turkey's temperature is $200^{\circ}\text{F}$. Find how long it takes the turkey to cool to $150^{\circ}\text{F}$.
>
> > [!continue]- Solution
> > $\frac{dT}{dt}=-k(T-T_{c})$
> > $\int\frac{1}{T-T_{c}}dT=\int-k dt$
> > $\ln|T-T_{c}|=-kt+C$
> > $T-T_{c}=e^{-kt+C} \Rightarrow T=Ce^{-kt}+T_{c}$
> > 
> > When $t=0$, $T=300$, $T_c=70$
> > $300=Ce^{0}+70 \Rightarrow C=210$
> > $T=210e^{-kt}+70$
> > 
> > When $t=2$, $T=200$
> > $200=210e^{-2k}+70$
> > $e^{-2k}=\frac{130}{210}=\frac{13}{21}$
> > $-2k=\ln\frac{13}{21}$
> > $k=\frac{\ln\frac{13}{21}}{-2}=0.2398$
> > $T=210e^{-0.2398t}+70$
> > 
> > When $T=150$,
> > $150=210e^{-0.2398t}+70$
> > $e^{-0.2398t}=\frac{80}{210}=\frac{8}{21}$
> > $t=\frac{\ln\frac{8}{21}}{-0.2398}=4.0245\approx4\text{ minutes}$

## 6.3.4 Electric Circuits Model
An electromotive force (usually a battery or generator) produces a voltage of $E(t)$ volts and a current of $I(t)$ amperes (A) at time, t. The electric circuit also contains a resistor with a resistance of R ohms, $\Omega$ and an inductor with an inductance of L, Henries (H). Ohm's law gives the drop in voltage due to the resistor as $RI$. The voltage drop due to the inductor is $L(\frac{dI}{dt})$.

One of the Kirchhoff's laws say that the sum of the voltage drop is equal to the supplied voltage $E(t)$. Thus, 
> [!formula]
> $L(\frac{dI}{dt})+RI=E(t)$

> [!example]- Example 6.13
> A series RL circuit is given by
> $L(\frac{di}{dt})+Ri=E(t)$
> where L in inductance (henry, H), R is resistance (ohms, $\Omega$), i is current (amp, A), and $E(t)$ is voltage supplied (volt, V). The circuit has a resistant of $20\text{ohms}$, an inductance of $0.2\text{henry}$, and an impressed voltage of $12\text{volts}$. Find the current equation, $i(t)$ if the initial current is zero.
>
> > [!continue]- Solution
> > $L(\frac{di}{dt})+Ri=E(t)$
> > $0.2(\frac{di}{dt})+20i=12$
> > Divide by 0.2:
> > $\frac{di}{dt}+100i=60$ 
> > $P(t)=100$, $Q(t)=60$
> > $\mu(t)=e^{\int100 dt}=e^{100t}$
> > $i e^{100t}=\int 60e^{100t}dt$
> > $i e^{100t}=\frac{60e^{100t}}{100}+C \Rightarrow i=\frac{3}{5}+Ce^{-100t}$
> > 
> > When $t=0$, $i=0$
> > $0=\frac{3}{5}+Ce^{0} \Rightarrow C=-\frac{3}{5}$
> > $i=\frac{3}{5}-\frac{3}{5}e^{-100t}$

> [!sq]- Problem 6.3
> 1. A town had a population of 10 000 in 2014. The population has increased to 12 000 in 2019. Assuming an exponential growth model is given by $\frac{dP}{dt}=kP$, estimate the year when the population will be 25 000.
> 2. A radioactive substance decomposes at a rate proportional to the amount present is given by $\frac{dM}{dt}=-kM$. The initial mass is 100mg and the mass is reduced to half after 25 days. How long will it take for the substance mass left only 80mg?
> 3. A cup of tea with a temperature of $100^{\circ}\text{C}$ is placed in a room with a constant temperature of $20^{\circ}\text{C}$ and it cools to $70^{\circ}\text{C}$ in 2 minutes. Find $T(t)$ if given $\frac{dT}{dt}=-k(T-T_{c})$ where T is the temperature present at any time t, is constant temperature and k is a constant. How long will it take for the tea to reach a temperature of $50^{\circ}\text{C}$?
> 4. An electric circuit satisfies a differential equation $L\frac{di}{dt}+Ri=E$. Find the amount of current, $i(t)$ that passes through the circuit for $E=30\text{V}$, $R=50\Omega$ and $L=0.5\text{H}$. Given the initial condition that is $i(0)=0$.
>
> > [!continue]- Solution
> > **1.** Population $P(t) = Ce^{kt}$. Let $t=0$ be year 2014.
> > $P(0) = 10000 \Rightarrow C = 10000$.
> > $P(5) = 12000 \Rightarrow 12000 = 10000e^{5k} \Rightarrow e^{5k} = 1.2 \Rightarrow k = \frac{\ln 1.2}{5} \approx 0.03646$.
> > To find $t$ for $P(t) = 25000$: $25000 = 10000e^{0.03646t} \Rightarrow 2.5 = e^{0.03646t} \Rightarrow t = \frac{\ln 2.5}{0.03646} \approx 25.13\text{ years}$.
> > Estimated year: $2014 + 25 = 2039$.
> > 
> > **2.** Mass $M(t) = Ce^{-kt}$. 
> > $M(0) = 100 \Rightarrow C = 100$.
> > $M(25) = 50 \Rightarrow 50 = 100e^{-25k} \Rightarrow e^{-25k} = 0.5 \Rightarrow k = \frac{-\ln 0.5}{25} \approx 0.0277$.
> > To find $t$ for $M(t) = 80$: $80 = 100e^{-0.0277t} \Rightarrow 0.8 = e^{-0.0277t} \Rightarrow t = \frac{-\ln 0.8}{0.0277} \approx 8.05\text{ days}$.
> > 
> > **3.** Temperature $T(t) = T_c + Ce^{-kt}$. $T_c = 20$.
> > $T(0) = 100 \Rightarrow 100 = 20 + C \Rightarrow C = 80$. Thus $T(t) = 20 + 80e^{-kt}$.
> > $T(2) = 70 \Rightarrow 70 = 20 + 80e^{-2k} \Rightarrow 50 = 80e^{-2k} \Rightarrow e^{-2k} = \frac{5}{8} \Rightarrow k = \frac{-\ln(5/8)}{2} \approx 0.235$.
> > Function: $T(t) = 20 + 80e^{-0.235t}$.
> > Time for $T(t) = 50$: $50 = 20 + 80e^{-0.235t} \Rightarrow 30 = 80e^{-0.235t} \Rightarrow \frac{3}{8} = e^{-0.235t} \Rightarrow t = \frac{-\ln(3/8)}{0.235} \approx 4.17\text{ minutes}$.
> > 
> > **4.** Circuit equation: $0.5\frac{di}{dt} + 50i = 30 \Rightarrow \frac{di}{dt} + 100i = 60$.
> > Integrating factor $\mu(t) = e^{\int 100 dt} = e^{100t}$.
> > $i(t)e^{100t} = \int 60e^{100t} dt = 0.6e^{100t} + C$.
> > $i(t) = 0.6 + Ce^{-100t}$.
> > Initial condition $i(0) = 0 \Rightarrow 0 = 0.6 + C \Rightarrow C = -0.6$.
> > Current equation: $i(t) = 0.6(1 - e^{-100t})$.

# 6.4 TUTORIAL 6

> [!sq]- Question 1
> Determine the solution of $\frac{dy}{dx}+\frac{4y}{x}=6x-5$, $x>0$ subject to the boundary condition is $y(1)=1$.
>
> > [!continue]- Solution
> > Linear equation with $P(x) = \frac{4}{x}$ and $Q(x) = 6x - 5$.
> > $\mu(x) = e^{\int \frac{4}{x} dx} = e^{4\ln x} = x^4$.
> > Multiply by $\mu(x)$: $\frac{d}{dx}(y x^4) = x^4(6x - 5) = 6x^5 - 5x^4$.
> > Integrate: $y x^4 = \int (6x^5 - 5x^4) dx = x^6 - x^5 + C$.
> > General solution: $y = x^2 - x + C x^{-4}$.
> > Apply condition $y(1) = 1$: $1 = 1^2 - 1 + C(1)^{-4} \Rightarrow 1 = 1 - 1 + C \Rightarrow C = 1$.
> > Particular solution: $y = x^2 - x + \frac{1}{x^4}$.

> [!sq]- Question 2
> Find the solution for $x\frac{dy}{dx}=\sqrt{y^{2}+1}$, $x>0$ with $y(2)=0$.
>
> > [!continue]- Solution
> > Separable equation: $\frac{dy}{\sqrt{y^2+1}} = \frac{dx}{x}$.
> > Integrate both sides: $\int \frac{dy}{\sqrt{y^2+1}} = \int \frac{dx}{x}$.
> > $\ln|y + \sqrt{y^2+1}| = \ln|x| + C$.
> > Apply condition $y(2) = 0$: $\ln|0 + \sqrt{0+1}| = \ln|2| + C \Rightarrow \ln(1) = \ln 2 + C \Rightarrow 0 = \ln 2 + C \Rightarrow C = -\ln 2$.
> > $\ln(y + \sqrt{y^2+1}) = \ln x - \ln 2 = \ln\left(\frac{x}{2}\right)$.
> > $y + \sqrt{y^2+1} = \frac{x}{2}$.
> > $\sqrt{y^2+1} = \frac{x}{2} - y \Rightarrow y^2 + 1 = \left(\frac{x}{2} - y\right)^2 \Rightarrow y^2 + 1 = \frac{x^2}{4} - xy + y^2$.
> > $1 = \frac{x^2}{4} - xy \Rightarrow xy = \frac{x^2}{4} - 1 \Rightarrow y = \frac{x}{4} - \frac{1}{x}$.

> [!sq]- Question 3
> In some chemical reactions, the rate at which the amount of a substance changes with time is proportional to the amount present. For the change of chemical A into chemical B is given as, $\frac{dy}{dt}=-0.6y$ when t is measured in hours. If there are 100gm of chemical A present when $t=0$ how many grams will be left after the first hour?
>
> > [!continue]- Solution
> > $\frac{dy}{dt} = -0.6y \Rightarrow \int \frac{dy}{y} = \int -0.6 dt \Rightarrow \ln y = -0.6t + C \Rightarrow y(t) = C e^{-0.6t}$.
> > $y(0) = 100 \Rightarrow C = 100$.
> > $y(t) = 100 e^{-0.6t}$.
> > Amount left after first hour ($t=1$):
> > $y(1) = 100 e^{-0.6(1)} = 100 e^{-0.6} \approx 100(0.5488) = 54.88\text{gm}$.

> [!sq]- Question 4
> Suppose that electricity is draining from a capacitor at a rate that is proportional to the voltage V across its terminal and that, if t is measured in seconds, $\frac{dV}{dt}=-\frac{1}{40}V$. Solve the equation to find where when $t=0$, V is denotes as $V_{0}$. How long will it take the voltage to drop to 10% of its original value?
>
> > [!continue]- Solution
> > $\frac{dV}{dt} = -\frac{1}{40}V \Rightarrow \int \frac{dV}{V} = \int -\frac{1}{40} dt \Rightarrow \ln V = -\frac{1}{40}t + C$.
> > $V(t) = Ce^{-t/40}$.
> > When $t=0$, $V=V_0 \Rightarrow V_0 = Ce^0 \Rightarrow C = V_0$.
> > $V(t) = V_0 e^{-t/40}$.
> > To drop to 10% of original value, $V(t) = 0.1V_0$:
> > $0.1V_0 = V_0 e^{-t/40} \Rightarrow 0.1 = e^{-t/40} \Rightarrow \ln(0.1) = -\frac{t}{40}$.
> > $t = -40\ln(0.1) = -40(-2.3026) \approx 92.1\text{ seconds}$.

> [!sq]- Question 5
> A hot metal with an initial temperature of $120^{\circ}\text{C}$ is left to cool in a room with a constant temperature of $25^{\circ}\text{C}$. The rate of decrease of the temperature of the metal is proportional to the difference in temperature between the metal and the room. If the metal cools down to $80^{\circ}\text{C}$ in 20 minutes. Given that $\frac{dT}{dt}=-k(T-T_{0})$. Find:
> a) the expression for T,
> b) T when $t=30$ minutes,
> c) the time taken for the object to cool down to $50^{\circ}\text{C}$.
>
> > [!continue]- Solution
> > **a) Expression for T:**
> > $\frac{dT}{dt} = -k(T - T_0)$ where $T_0 = 25$.
> > $\int \frac{dT}{T - 25} = \int -k dt \Rightarrow \ln|T - 25| = -kt + C \Rightarrow T - 25 = e^{-kt+C} = A e^{-kt}$.
> > $T(t) = 25 + A e^{-kt}$.
> > Initial condition $T(0) = 120$: $120 = 25 + Ae^0 \Rightarrow A = 95$.
> > $T(t) = 25 + 95e^{-kt}$.
> > Second condition $T(20) = 80$: $80 = 25 + 95e^{-20k} \Rightarrow 55 = 95e^{-20k} \Rightarrow e^{-20k} = \frac{55}{95} = \frac{11}{19}$.
> > $k = \frac{-\ln(11/19)}{20} \approx 0.0273$.
> > $T(t) = 25 + 95e^{-0.0273t}$.
> > 
> > **b) T when $t=30$ minutes:**
> > $T(30) = 25 + 95e^{-0.0273(30)} = 25 + 95e^{-0.819} \approx 25 + 95(0.4409) = 25 + 41.88 = 66.88^{\circ}\text{C}$.
> > 
> > **c) Time taken for the object to cool down to $50^{\circ}\text{C}$:**
> > $50 = 25 + 95e^{-0.0273t} \Rightarrow 25 = 95e^{-0.0273t} \Rightarrow \frac{25}{95} = e^{-0.0273t} \Rightarrow \frac{5}{19} = e^{-0.0273t}$.
> > $t = \frac{-\ln(5/19)}{0.0273} = \frac{1.335}{0.0273} \approx 48.9\text{ minutes}$.