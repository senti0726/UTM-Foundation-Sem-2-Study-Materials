$$\underline{\Huge\text{INTEGRATION}}$$
# 4.0 INTRODUCTION
By now, we are familiar with differentiating common functions. In this unit, we will carry out the process of differentiation in reverse.
Given a function $f(x)$, we find a function $F(x)$ such that $\frac{d}{dx}(F(x))=F^{\prime}(x)=f(x).$

The function $F(x)$ is called the inverse of differentiation or antiderivative.

# 4.1 ANTIDERIVATIVES
An antiderivative of a function $f(x)$ is a function whose derivative is $f(x)$. In other words, the function $F(x)$ is an antiderivative of $f(x)$, if $F^{\prime}(x)=f(x)$. To find an antiderivative for a function $f(x)$, we can often reverse the process of differentiation.

For example, if $f(x)=2x$, then an antiderivative of $f(x)$ is $F(x)=x^{2}$ which can be found by reversing the power rule.

The situation is just a little more complicated because there are lots of functions that we can differentiate gives us 2x. For examples: $F(x)=x^{2}+4$, $F(x)=x^{2}-15$, $F(x)=x^{2}-\pi$ and etc. All these functions have the same derivative that is 2x, because when we differentiate the constant term, we obtain zero.

Consequently, when we reverse the process, we have no idea what the original constant term might have been. Thus, we need to include in our answer an unknown constant, C called the constant of integration. This means, the antiderivatives of $f(x)=2x$ is $F(x)=x^{2}+C$ if $F^{\prime}(x)=f(x)$.

> [!example]- Example 4.1
> Find $f(x)$ if $\int f(x)dx=\frac{1}{\sqrt{4-x^{2}}}+C$ where C is a constant.
>
> > [!continue]- Solution
> > If $\int f(x)dx=\frac{1}{\sqrt{4-x^{2}}}+C$ thus $f(x)=\frac{d}{dx}(\frac{1}{\sqrt{4-x^{2}}}+C)$
> > $=-\frac{1}{2}(4-x^{2})^{-\frac{3}{2}}(-2x)+0=\frac{x}{(4-x^{2})^{\frac{3}{2}}}$
> > Hence, the antiderivative of $\frac{x}{(4-x^{2})^{\frac{3}{2}}}$ is $\frac{1}{\sqrt{4-x^{2}}}+C$

> [!sq]- Problem 4.1
> Find $f(x)$ if $\int f(x)dx=-\frac{\cos 2x}{2}-\frac{4}{3}e^{3x}+C$ where C is a constant.
>
> > [!continue]- Solution
> > $f(x) = \frac{d}{dx}\left(-\frac{\cos 2x}{2} - \frac{4}{3}e^{3x} + C\right)$
> > $= -\frac{1}{2}(-2\sin 2x) - \frac{4}{3}(3e^{3x}) + 0$
> > $= \sin 2x - 4e^{3x}$

# 4.2 INDEFINITE INTEGRAL
The reverse process of differentiation or antiderivative process is also known as integration. $F(x)=x^{2}+C$ is the indefinite integral of $f(x)$ and the process of finding $F(x)$ is called indefinite integration.

When we want to integrate a function $f(x)$ we use a notation $\int f(x)dx$ to indicate that we want to integrate the function $f(x)$.

From the notation, $\int f(x)dx$
* the symbol for integration, $\int$ is known as an integral symbol;
* the function $f(x)$ is the integrand of the integral; and,
* the variable x is the independent variable of integration.

For example, when 2x is being integrated with respect to x, we write it as:
$\int 2x dx = x^{2}+C$
* $\int$ : Integral sign
* $2x$ : Integrand
* $dx$ : Always be written
* $C$ : Constant of integration

Technically, when we find an indefinite integral, the answer should always contain a constant of integration, C.

### 4.2.1 Integral Formulae
In the table below, shows the examples of the relationship between derivative and indefinite integral formulas for some elementary functions.

| Derivative Formula | Equivalent Integral Formula |
| :--- | :--- |
| $\frac{d}{dx}(x^{7})=7x^{6}$ | $\int 7x^{6}dx=x^{7}+C$ |
| $\frac{d}{dx}(\sin x)=\cos x$ | $\int \cos x dx=\sin x+C$ |
| $\frac{d}{dx}(\cos x)=-\sin x$ | $-\int \sin x dx=\cos x+C$ |
| $\frac{d}{dx}(\tan x)=\sec^{2}x$ | $\int \sec^{2}x dx=\tan x+C$ |
| $\frac{d}{dx}(e^{x})=e^{x}$ | $\int e^{x}dx=e^{x}+C$ |
| $\frac{d}{dx}(\ln x)=\frac{1}{x}$ | $\int\frac{1}{x}dx=\ln x+C$ |

In the table below, shows the general formulae of indefinite integral for common types of functions.

| Types of Function | Indefinite integral                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Algebraic**     | $\int 1 dx=x+C$<br>$\int x^{n}dx=\frac{x^{n+1}}{n+1}+C$<br>$\int ax^{n}dx=\frac{ax^{n+1}}{n+1}+C$<br>$\int (ax+b)^{n}dx=\frac{(ax+b)^{n+1}}{(n+1)(a)}+C$                                                                                                                                                                                                                                                                                                                         |
| **Exponential**   | $\int e^{f(x)}dx=\frac{e^{f(x)}}{f^{\prime}(x)}+C$                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Logarithmic**   | $\int \frac{1}{x}dx=\ln \vert x \vert +C$<br>$\int \frac{1}{x+b}dx=\ln \vert x+b \vert +C$<br>$\int \frac{1}{ax+b}dx=\frac{\ln \vert ax+b \vert }{a}+C$                                                                                                                                                                                                                                                                                                                          |
| **Trigonometric** | $\int \sin x dx=-\cos x+C$<br>$\int \sin ax dx=\frac{-\cos ax}{a}+C$<br>$\int \cos x dx=\sin x+C$<br>$\int \cos ax dx=\frac{\sin ax}{a}+C$<br>$\int \sec^{2}x dx=\tan x+C$<br>$\int \sec^{2}ax dx=\frac{\tan ax}{a}+C$<br>$\int \csc^{2}x dx=-\cot x+C$<br>$\int \csc^{2}ax dx=\frac{-\cot ax}{a}+C$<br>$\int \sec x \tan x dx=\sec x+C$<br>$\int \sec ax \tan ax dx=\frac{\sec ax}{a}+C$<br>$\int \csc x \cot x dx=-\csc x+C$<br>$\int \csc ax \cot ax dx=\frac{-\csc ax}{a}+C$ |
> [!liststart]- the trigo circles
> > [!picture]- sine and cosine
> ![[CHAPTER 4 2026-04-27 11.42.57.excalidraw]]
> 
> > [!picture]- everything else
> > ![[CHAPTER 4 2026-04-27 11.59.00.excalidraw]]

### 4.2.2 Basic Properties of Indefinite Integrals
The basic properties of indefinite integrals:
i. the constant, k can be taken out from an integral, that is
$\int k f(x)dx=k\int f(x)dx$
ii. the integral of a sum or difference equals the sum or difference of the integrals, that is
$\int [f(x)\pm g(x)]dx=\int f(x)dx\pm\int g(x)dx$

> [!example]- Example 4.2
> Evaluate the following integrals.
> a) $\int(x^{4}+2x-6)dx$
> b) $\int(3x^{2}+3\sqrt[4]{x}-\frac{4}{x^{3}})dx$
> c) $\int(x+1)(3x-2)dx$
>
> > [!continue]- Solution
> > a) $\int(x^{4}+2x-6)dx=\int x^{4}dx+2\int x dx-\int 6 dx=\frac{1}{5}x^{5}+2(\frac{1}{2}x^{2})-6(x)$
> > $=\frac{1}{5}x^{5}+x^{2}-6x+C$
> > 
> > b) $\int(3x^{2}+3\sqrt[4]{x}-\frac{4}{x^{3}})dx=\int 3x^{2}dx+3\int x^{\frac{1}{4}}dx-4\int x^{-3}dx$
> > $=3(\frac{1}{3}x^{3})+3[\frac{x^{\frac{5}{4}}}{\frac{5}{4}}]-4(\frac{x^{-2}}{-2})$
> > $=x^{3}+\frac{12}{5}x^{\frac{5}{4}}+\frac{2}{x^{2}}+C$
> > 
> > c) $\int(x+1)(3x-2)dx=\int(3x^{2}+x-2)dx=3\int x^{2}dx+\int x dx-\int 2 dx$
> > $=3(\frac{1}{3}x^{3})+(\frac{x^{2}}{2})-(2x)=x^{3}+\frac{x^{2}}{2}-2x+C$

> [!example]- Example 4.3
> Evaluate the following integrals.
> a) $\int e^{2x+1}dx$
> b) $\int \sin 3x-e^{3x}dx$
> c) $\int \frac{1}{2-3x}dx$
> d) $\int \frac{3}{3+2x}dx$
> e) $\int \sec^{2}(2x+3)dx$
>
> > [!continue]- Solution
> > a) $\int e^{2x+1}dx=\frac{e^{2x+1}}{2}+C$
> > b) $\int \sin 3x-e^{3x}dx=-\frac{\cos 3x}{3}-\frac{e^{3x}}{3}+C$
> > c) $\int \frac{1}{2-3x}dx=\frac{\ln|2-3x|}{-3}+C$
> > d) $\int \frac{3}{3+2x}dx=\frac{3 \ln|3+2x|}{2}+C$
> > e) $\int \sec^{2}(2x+3)dx=\frac{\tan(2x+3)}{2}+C$

> [!sq]- Problem 4.2
> a) $\int 14dx$
> b) $\int \frac{1}{x^{8}}dx$
> c) $\int x^{3}+2dx$
> d) $\int (5x-3)^{3}dx$
> e) $\int \sqrt[3]{6-5x}dx$
> f) $\int e^{2x+1}dx$
> g) $\int (1-e^{-2x})(2+e^{3x})dx$
> h) $\int \sec^{2}x dx$
> i) $\int 1+\sec^{2}x dx$
> j) $\int \frac{1}{2-3x}dx$
> k) $\int \frac{x^{3}+x}{x^{2}}dx$
> l) $\int (x+\frac{1}{x^{2}})^{2}dx$
> m) $\int \frac{\sin 2x}{\cos x}dx$
> n) $\int \frac{3}{3+2x}dx$
> o) $\int \cos(2x+3)dx$
> p) $\int \sin 3x-e^{2x}dx$
> q) $\int \sec 4x \tan 4x dx$
> r) $\int \frac{2 \tan x}{\sin 2x}dx$
>
> > [!continue]- Solution
> > **a)** $\int 14 dx = 14x + C$
> > **b)** $\int \frac{1}{x^{8}} dx = \int x^{-8} dx = \frac{x^{-7}}{-7} + C = -\frac{1}{7x^7} + C$
> > **c)** $\int (x^{3}+2) dx = \frac{x^4}{4} + 2x + C$
> > **d)** $\int (5x-3)^{3} dx = \frac{(5x-3)^4}{4(5)} + C = \frac{(5x-3)^4}{20} + C$
> > **e)** $\int (6-5x)^{1/3} dx = \frac{(6-5x)^{4/3}}{(4/3)(-5)} + C = -\frac{3(6-5x)^{4/3}}{20} + C$
> > **f)** $\int e^{2x+1} dx = \frac{e^{2x+1}}{2} + C$
> > **g)** $\int (1-e^{-2x})(2+e^{3x}) dx = \int (2 + e^{3x} - 2e^{-2x} - e^x) dx = 2x + \frac{e^{3x}}{3} + e^{-2x} - e^x + C$
> > **h)** $\int \sec^{2}x dx = \tan x + C$
> > **i)** $\int (1+\sec^{2}x) dx = x + \tan x + C$
> > **j)** $\int \frac{1}{2-3x} dx = -\frac{1}{3}\ln|2-3x| + C$
> > **k)** $\int \frac{x^3+x}{x^2} dx = \int (x + x^{-1}) dx = \frac{x^2}{2} + \ln|x| + C$
> > **l)** $\int (x+\frac{1}{x^2})^2 dx = \int (x^2 + \frac{2}{x} + x^{-4}) dx = \frac{x^3}{3} + 2\ln|x| - \frac{1}{3x^3} + C$
> > **m)** $\int \frac{\sin 2x}{\cos x} dx = \int \frac{2\sin x\cos x}{\cos x} dx = \int 2\sin x dx = -2\cos x + C$
> > **n)** $\int \frac{3}{3+2x} dx = \frac{3}{2}\ln|3+2x| + C$
> > **o)** $\int \cos(2x+3) dx = \frac{\sin(2x+3)}{2} + C$
> > **p)** $\int (\sin 3x-e^{2x}) dx = -\frac{\cos 3x}{3} - \frac{e^{2x}}{2} + C$
> > **q)** $\int \sec 4x \tan 4x dx = \frac{\sec 4x}{4} + C$
> > **r)** $\int \frac{2 \tan x}{\sin 2x} dx = \int \frac{2(\sin x/\cos x)}{2\sin x\cos x} dx = \int \frac{1}{\cos^2 x} dx = \int \sec^2 x dx = \tan x + C$

# 4.3 DEFINITE INTEGRAL
A definite integral, on the other hand, is an integral with limits. It is a number which measures an area under a graph between the limits.
Now, let us discuss about the integrals with the limits of integration, the expression is given by, $\int_{x=a}^{x=b}f(x)dx$ where a and b are constants.

The number a is the lower limit of integration and the number b is the upper limit of integration. This type of integral is called definite integral. If a function $f(x)$ is continuous on the interval \[a,b\], then
$\int_{a}^{b}f(x)dx=[F(x)]_{a}^{b}=F(b)-F(a)$

### 4.3.1 Basic Properties of Definite Integrals
The basic properties of definite integrals are given as follows. If $f(x)$ and $g(x)$ are continuous functions on the interval \[a,b\], then:
i. $\int_{a}^{a}f(x)dx=0$, if $a=b$
ii. $\int_{a}^{b}f(x)dx=-\int_{b}^{a}f(x)dx$
iii. $\int_{a}^{b}k f(x)dx=k\int_{a}^{b}f(x)dx$, k is a constant.
iv. $\int_{a}^{b}k dx=k(b-a)$
v. $\int_{a}^{b}[f(x)\pm g(x)]dx=\int_{a}^{b}f(x)dx\pm\int_{a}^{b}g(x)dx$
vi. $\int_{a}^{b}f(x)dx=\int_{a}^{c}f(x)dx+\int_{c}^{b}f(x)dx$

> [!example]- Example 4.4
> Given $\int_{1}^{5}f(x)dx=-10$ and $\int_{1}^{5}g(x)dx=6$, evaluate the following:
> a) $\int_{5}^{1}[f(x)+2x]dx$
> b) $\int_{1}^{5}[f(x)+5g(x)]dx$
>
> > [!continue]- Solution
> > a) $\int_{5}^{1}[f(x)+2x]dx=-\int_{1}^{5}[f(x)+2x]dx=-(\int_{1}^{5}f(x)dx+\int_{1}^{5}2x dx)=-(-10)-[x^{2}]_{1}^{5}$
> > $=10-[(5)^{2}-(1)^{2}]=-14$
> > 
> > b) $\int_{1}^{5}[f(x)+5g(x)]dx=\int_{1}^{5}f(x)dx+5\int_{1}^{5}g(x)dx=-10+5(6)=20$

> [!example]- Example 4.5
> If $\int_{0}^{1}f(x)dx=-4$ and $\int_{1}^{4}f(x)dx=2$ evaluate $\int_{0}^{4}[x-2f(x)]dx$
>
> > [!continue]- Solution
> > $\int_{0}^{4}[x-2f(x)]dx=\int_{0}^{4}x dx-2\int_{0}^{4}f(x)dx=[\frac{x^{2}}{2}]_{0}^{4}-2[\int_{0}^{1}f(x)dx+\int_{1}^{4}f(x)dx]$
> > $=[\frac{(4)^{2}}{2}-\frac{(0)^{2}}{2}]-2[-(-4)+2]=\frac{16}{2}-2(-2)=8+4=12$ *(Note: Corrected source bounds mismatch in evaluation step)*

> [!example]- Example 4.6
> Find the following integrals:
> a) $\int_{2}^{5}(2x+3)dx$
> b) $\int_{1}^{2}(\frac{x^{3}-2x^{2}+4}{x^{3}})dx$
> c) $\int_{25}^{36}(\frac{2}{\sqrt{x}}-3\sqrt{x})dx$
> d) $\int_{0}^{\pi}\sec x \tan x+\sin 4x dx$
> e) $\int_{0}^{1}e^{-2x}-3dx$
>
> > [!continue]- Solution
> > a) $\int_{2}^{5}(2x+3)dx=[x^{2}+3x]_{2}^{5}=[(5)^{2}+3(5)]-[(2)^{2}+3(2)]$
> > $=40-10=30$
> > 
> > b) $\int_{1}^{2}(\frac{x^{3}-2x^{2}+4}{x^{3}})dx=\int_{1}^{2}(1-\frac{2}{x}+\frac{4}{x^{3}})dx=[x-2 \ln x-\frac{2}{x^{2}}]_{1}^{2}$
> > $=[2-2 \ln(2)-\frac{2}{(2)^{2}}]-[1-2 \ln(1)-\frac{2}{(1)^{2}}]$
> > $=\frac{5}{2}-2 \ln(2) \approx 1.1137$
> > 
> > c) $\int_{25}^{36}(\frac{2}{\sqrt{x}}-3\sqrt{x})dx=\int_{25}^{36}(2x^{-\frac{1}{2}}-3x^{\frac{1}{2}})dx=[\frac{2x^{\frac{1}{2}}}{\frac{1}{2}}-\frac{3x^{\frac{3}{2}}}{\frac{3}{2}}]_{25}^{36}=[4x^{\frac{1}{2}}-2x^{\frac{3}{2}}]_{25}^{36}$
> > $=[4(\sqrt{36})-2\sqrt{(36)^{3}}]-[4(\sqrt{25})-2\sqrt{(25)^{3}}]$
> > $=(-408)-(-230)=-178$
> > 
> > d) $\int_{0}^{\pi}\sec x \tan x+\sin 4x dx=[\sec x-\frac{\cos 4x}{4}]_{0}^{\pi}=(\sec \pi-\frac{\cos 4\pi}{4})-(\sec 0-\frac{\cos 4(0)}{4})$
> > $=(-1-\frac{1}{4})-(1-\frac{1}{4})=-2$
> > 
> > e) $\int_{0}^{1}e^{-2x}-3 dx=[\frac{e^{-2x}}{-2}-3x]_{0}^{1}=(\frac{e^{-2}}{-2}-3)-(\frac{1}{-2}) \approx -2.4323$

> [!sq]- Problem 4.3
> a) If given $\int_{-2}^{4}f(x)dx=18$ and $\int_{-2}^{0}f(x)dx=6$, evaluate $\int_{0}^{4}[f(x)+x^{2}]dx$
> b) Given $\int_{-2}^{0}f(x)dx=4$ and $\int_{3}^{4}f(x)dx=2$. Find k if $\int_{-2}^{0}f(x)dx+\int_{-1}^{1}kx^{2}dx+\int_{3}^{4}\frac{f(x)}{2}dx=12$
> c) Compute the given definite integrals:
> i. $\int_{0}^{1}(2\sqrt{x}+x^{2}-2)dx$
> ii. $\int_{1}^{2}\frac{x^{4}+2x^{2}+1}{x^{2}}dx$
> iii. $\int_{2}^{8}(x+2)(x+3)dx$
> iv. $\int_{2}^{6}e^{2x-4}dx$
> v. $\int_{0}^{1}(e^{x}+1)^{2}dx$
> vi. $\int_{0}^{\pi}\sin x+2 \cos x dx$
> vii. $\int \cot x dx$
> viii. $\int_{1}^{2}\frac{1}{8-3x}dx$
>
> > [!continue]- Solution
> > **a)** $\int_{0}^{4}f(x)dx = \int_{-2}^{4}f(x)dx - \int_{-2}^{0}f(x)dx = 18 - 6 = 12$.
> > $\int_{0}^{4}[f(x)+x^2]dx = 12 + \left[\frac{x^3}{3}\right]_0^4 = 12 + \frac{64}{3} = \frac{100}{3}$.
> > 
> > **b)** $\int_{-2}^{0}f(x)dx + \int_{-1}^{1}kx^2 dx + \int_{3}^{4}\frac{f(x)}{2}dx = 12$
> > $4 + k\left[\frac{x^3}{3}\right]_{-1}^{1} + \frac{1}{2}(2) = 12$
> > $4 + k\left(\frac{1}{3} - (-\frac{1}{3})\right) + 1 = 12 \Rightarrow 5 + \frac{2}{3}k = 12 \Rightarrow \frac{2}{3}k = 7 \Rightarrow k = \frac{21}{2}$.
> > 
> > **c) i.** $\int_{0}^{1}(2x^{1/2}+x^2-2)dx = \left[\frac{4}{3}x^{3/2} + \frac{x^3}{3} - 2x\right]_0^1 = \frac{4}{3} + \frac{1}{3} - 2 = -\frac{1}{3}$.
> > 
> > **c) ii.** $\int_{1}^{2}(x^2+2+x^{-2})dx = \left[\frac{x^3}{3} + 2x - \frac{1}{x}\right]_1^2 = (\frac{8}{3} + 4 - \frac{1}{2}) - (\frac{1}{3} + 2 - 1) = \frac{37}{6} - \frac{4}{3} = \frac{29}{6}$.
> > 
> > **c) iii.** $\int_{2}^{8}(x^2+5x+6)dx = \left[\frac{x^3}{3} + \frac{5x^2}{2} + 6x\right]_2^8 = (\frac{512}{3} + 160 + 48) - (\frac{8}{3} + 10 + 12) = \frac{504}{3} + 186 = 354$.
> > 
> > **c) iv.** $\int_{2}^{6}e^{2x-4}dx = \left[\frac{e^{2x-4}}{2}\right]_2^6 = \frac{e^8}{2} - \frac{e^0}{2} = \frac{e^8 - 1}{2}$.
> > 
> > **c) v.** $\int_{0}^{1}(e^{2x} + 2e^x + 1)dx = \left[\frac{e^{2x}}{2} + 2e^x + x\right]_0^1 = (\frac{e^2}{2} + 2e + 1) - (\frac{1}{2} + 2 + 0) = \frac{e^2}{2} + 2e - \frac{3}{2}$.
> > 
> > **c) vi.** $\int_{0}^{\pi}(\sin x + 2\cos x)dx = [-\cos x + 2\sin x]_0^\pi = (-\cos\pi + 2\sin\pi) - (-\cos 0 + 2\sin 0) = (1 + 0) - (-1 + 0) = 2$.
> > 
> > **c) vii.** $\int \cot x dx = \int \frac{\cos x}{\sin x} dx = \ln|\sin x| + C$.
> > 
> > **c) viii.** $\int_{1}^{2}\frac{1}{8-3x}dx = \left[-\frac{1}{3}\ln|8-3x|\right]_1^2 = -\frac{1}{3}\ln(2) - (-\frac{1}{3}\ln(5)) = \frac{1}{3}(\ln 5 - \ln 2) = \frac{1}{3}\ln(2.5)$.

### 4.4.4 Integration Using Partial Fractions
In this section, we shall focus on the integrands that are rational functions, that is, $\int\frac{f(x)}{g(x)}dx$ where $f(x)$ and $g(x)$ are polynomials. The integrand, $\frac{f(x)}{g(x)}$ can be rewritten as a sum of simpler fractions known as partial fractions. Then, we may be able to integrate the resulting terms using basic integration formulae. We will explain the details for the three cases that occur:

* **Case I:** The denominator, $g(x)$ is a product of distinct linear factors.
* **Case II:** The denominator, $g(x)$ is a product of linear factors, some of which are repeated.
* **Case III:** The denominator, $g(x)$ contains irreducible quadratic factors.

#### CASE I: The Denominator is a Product of Distinct Linear Factors
This means that we can write, $g(x)=(a_{1}x+b_{1})(a_{2}x+b_{2})+...+(a_{k}x+b_{k})$, where no factor is repeated.
In this case, the constants, $A_{1}, A_{2}, ..., A_{k}$ will exist in partial fractions, such that
$$\frac{f(x)}{g(x)}=\frac{A_{1}}{(a_{1}x+b_{1})}+\frac{A_{2}}{(a_{2}x+b_{2})}+...+\frac{A_{k}}{(a_{k}x+b_{k})}$$
These constants $A_{1}, A_{2}, ..., A_{k}$ can be determined as shown in the following example.

> [!example]- Example 4.14
> Evaluate the following integrals.
> a) $\int\frac{3x+2}{x^{2}+3x+2}dx$
> b) $\int\frac{x^{2}+2x-1}{2x^{3}+3x^{2}-2x}dx$
> c) $\int_{4}^{6}\frac{7}{x^{2}+x-12}dx$
>
> > [!continue]- Solution
> > **a) $\int\frac{3x+2}{x^{2}+3x+2}dx=\int\frac{3x+2}{(x+1)(x+2)}dx$**
> > Decompose into partial fraction: $\frac{3x+2}{(x+1)(x+2)}=\frac{A}{(x+1)}+\frac{B}{(x+2)}$
> > Make both sides with the same denominator: $\frac{3x+2}{(x+1)(x+2)}=\frac{A(x+2)+B(x+1)}{(x+1)(x+2)}$
> > Since the denominator is the same, we can equate the numerator to determine the constants:
> > $3x+2=A(x+2)+B(x+1)$
> > 
> > **Method 1 (TRIAL METHOD):**
> > To find the values of A and B, we shall choose the special values of x. Let us try, $x=-2$ because it will make constant A disappear in RHS and solve for B. Next, choose $x=-1$ because it will make constant B disappear and we can get the value of A.
> > Let $x=-2 \Rightarrow 3(-2)+2=A(-2+2)+B(-2+1) \Rightarrow -4=-B \Rightarrow B=4$
> > Let $x=-1 \Rightarrow 3(-1)+2=A(-1+2)+B(-1+1) \Rightarrow -1=A \Rightarrow A=-1$
> > 
> > **Method 2 (COMPARISON METHOD):**
> > To find the values of A and B, we expand RHS and put together all the like terms. We compare the coefficient of like terms on LHS and RHS.
> > $3x+2=A(x+2)+B(x+1) \Rightarrow 3x+2=Ax+2A+Bx+B \Rightarrow 3x+2=(A+B)x+2A+B$
> > Compare the coefficients:
> > $x^{1}: 3=A+B$
> > $x^{0}: 2=2A+B$
> > By using simultaneous equation, we will get the value of $A=-1$ and $B=4$.
> > 
> > This enables us to write,
> > $\int\frac{3x+2}{x^{2}+3x+2}dx=\int\frac{3x+2}{(x+1)(x+2)}dx=\int\left(-\frac{1}{(x+1)}+\frac{4}{(x+2)}\right)dx$
> > $=-\int\frac{dx}{(x+1)}+4\int\frac{dx}{(x+2)} = -\ln|x+1|+4 \ln|x+2|+C = \ln\left|\frac{(x+2)^{4}}{(x+1)}\right|+C$
> > 
> > **b) $\int\frac{x^{2}+2x-1}{2x^{3}+3x^{2}-2x}dx=\int\frac{x^{2}+2x-1}{x(2x^{2}+3x-2)}dx=\int\frac{x^{2}+2x-1}{x(2x-1)(x+2)}dx$**
> > $\frac{x^{2}+2x-1}{x(2x-1)(x+2)}=\frac{A}{x}+\frac{B}{2x-1}+\frac{C}{x+2}$
> > $\frac{x^{2}+2x-1}{x(2x-1)(x+2)}=\frac{A(2x-1)(x+2)+Bx(x+2)+Cx(2x-1)}{x(2x-1)(x+2)}$
> > $x^{2}+2x-1=A(2x-1)(x+2)+Bx(x+2)+Cx(2x-1)$
> > 
> > Method 1: Find the values of A, B and C.
> > Let $x=0 \Rightarrow 0^{2}+2(0)-1=A(2(0)-1)(0+2)+0+0 \Rightarrow -1=-2A \Rightarrow A=\frac{1}{2}$
> > Let $x=-2 \Rightarrow (-2)^{2}+2(-2)-1=0+0+C(-2)(2(-2)-1) \Rightarrow -1=10C \Rightarrow C=-\frac{1}{10}$
> > Let $x=1 \Rightarrow 1^{2}+2(1)-1=A(2(1)-1)(1+2)+B(1)(1+2)+C(1)(2(1)-1)$
> > $2=3A+3B+C$, where $A=\frac{1}{2}$, $C=-\frac{1}{10}$
> > $2=\frac{3}{2}+3B-\frac{1}{10} \Rightarrow B=\frac{1}{5}$
> > 
> > Then, substitute the values into the numerator expression, which gives,
> > $\int\frac{x^{2}+2x-1}{x(2x-1)(x+2)}dx=\int\left(\frac{1}{2x}+\frac{1}{5(2x-1)}-\frac{1}{10(x+2)}\right)dx$
> > $=\frac{1}{2}\ln|x|+\frac{1}{5}\frac{\ln|2x-1|}{2}-\frac{1}{10}\ln|x+2|+C = \frac{1}{2}\ln|x|+\frac{1}{10}\ln|2x-1|-\frac{1}{10}\ln|x+2|+C$
> > 
> > **c) $\int_{4}^{6}\frac{7}{x^{2}+x-12}dx=\int_{4}^{6}\frac{7}{(x-3)(x+4)}dx$**
> > $\frac{7}{(x-3)(x+4)}=\frac{A}{(x-3)}+\frac{B}{(x+4)} = \frac{A(x+4)+B(x-3)}{(x-3)(x+4)}$
> > $7=A(x+4)+B(x-3)$
> > 
> > Method 2: Find the values of A and B.
> > $7=Ax+4A+Bx-3B \Rightarrow 7=(A+B)x+4A-3B$
> > Compare the coefficients:
> > $x^{1}: 0=A+B \Rightarrow A=-B$
> > $x^{0}: 7=4A-3B$
> > Solve A and B by using simultaneous equation: $7=4(-B)-3B \Rightarrow 7=-7B \Rightarrow B=-1$. Thus, $A=1$.
> > 
> > Then, substitute the values into the numerator expression gives,
> > $\int_{4}^{6}\frac{7}{(x-3)(x+4)}dx=\int_{4}^{6}\left(\frac{1}{(x-3)}-\frac{1}{(x+4)}\right)dx=[\ln|x-3|-\ln|x+4|]_{4}^{6}$
> > $=\ln 3-\ln(\frac{5}{4}) \approx 0.8755$

#### CASE II: The Denominator is a Product of Linear Factors, Some of Which are Repeated
Suppose the first linear factor $(a_{1}x+b_{1})$ is repeated r times; that is, $(a_{1}x+b_{1})^{r}$ occurs in the factorization of $g(x)$. Then, instead of the single term $\frac{A_{1}}{(a_{1}x+b_{1})}$ in Case I, we would use
$$\frac{f(x)}{g(x)}=\frac{A_{1}}{(a_{1}x+b_{1})}+\frac{A_{2}}{(a_{1}x+b_{1})^{2}}+...+\frac{A_{r}}{(a_{1}x+b_{1})^{r}}$$

> [!example]- Example 4.15
> Evaluate the following integrals.
> a) $\int\frac{6x+7}{(x+2)^{2}}dx$
> b) $\int\frac{3x+1}{(x-1)^{2}(x+2)}dx$
>
> > [!continue]- Solution
> > **a) $\frac{6x+7}{(x+2)^{2}}=\frac{A}{(x+2)}+\frac{B}{(x+2)^{2}}$**
> > $\frac{6x+7}{(x+2)^{2}}=\frac{A(x+2)+B}{(x+2)^{2}}\Rightarrow 6x+7=A(x+2)+B$
> > 
> > Method 2: Find the values of A and B.
> > $6x+7=Ax+2A+B$
> > Compare the coefficients:
> > $x^{1}: 6=A \Rightarrow A=6$
> > $x^{0}: 7=2A+B$
> > Solve B by substitute A = 6 into $7=2A+B$, we get $7=2(6)+B\Rightarrow B=-5$.
> > 
> > We have $A=6$ and $B=-5$, thus
> > $\int\frac{6x+7}{(x+2)^{2}}dx=\int\left(\frac{6}{(x+2)}-\frac{5}{(x+2)^{2}}\right)dx=6 \ln|x+2|-5\int(x+2)^{-2}dx$
> > $=6 \ln|x+2|-5\frac{(x+2)^{-1}}{(-1)(1)}+C = 6 \ln|x+2|+\frac{5}{x+2}+C$
> > 
> > **b) $\frac{3x+1}{(x-1)^{2}(x+2)}=\frac{A}{(x-1)}+\frac{B}{(x-1)^{2}}+\frac{C}{(x+2)}$**
> > $\frac{3x+1}{(x-1)^{2}(x+2)}=\frac{A(x-1)(x+2)+B(x+2)+C(x-1)^{2}}{(x-1)^{2}(x+2)}$
> > $3x+1=A(x-1)(x+2)+B(x+2)+C(x-1)^{2}$
> > 
> > Method 1: Find the values of A, B and C.
> > Let $x=1 \Rightarrow 3(1)+1=0+B(1+2)+0 \Rightarrow 4=3B \Rightarrow B=\frac{4}{3}$
> > Let $x=-2 \Rightarrow 3(-2)+1=0+0+C(-2-1)^{2} \Rightarrow -5=9C \Rightarrow C=-\frac{5}{9}$
> > Let $x=0 \Rightarrow 3(0)+1=A(0-1)(0+2)+B(0+2)+C(0-1)^{2}$
> > $1=-2A+2B+C$ where $B=\frac{4}{3}$, $C=-\frac{5}{9}$
> > $1=-2A+\frac{8}{3}-\frac{5}{9} \Rightarrow A=\frac{5}{9}$
> > 
> > Thus, we have
> > $\int\frac{3x+1}{(x-1)^{2}(x+2)}dx=\int\left(\frac{5}{9(x-1)}+\frac{4}{3(x-1)^{2}}-\frac{5}{9(x+2)}\right)dx$
> > $=\frac{5}{9}\ln|x-1|+\frac{4}{3}\int (x-1)^{-2}dx-\frac{5}{9}\ln|x+2|$
> > $=\frac{5}{9}\ln|x-1|+\frac{4}{3}\left(\frac{(x-1)^{-1}}{-1}\right)-\frac{5}{9}\ln|x+2|+C = \frac{5}{9}\ln|x-1|-\frac{4}{3(x-1)}-\frac{5}{9}\ln|x+2|+C$

#### CASE III: The Denominator Contains Irreducible Quadratic Factors
If the denominator $g(x)$ has a quadratic term, $ax^{2}+bx+c$, where $b^{2}-4ac<0$ that cannot be factorized (known as irreducible quadratics factors), the expression for $\frac{f(x)}{g(x)}$ will be written in the form $\frac{Ax+B}{ax^{2}+bx+c}$, where A and B are constant to be determined.

> [!example]- Example 4.16
> Evaluate the following integrals.
> a) $\int\frac{x+1}{(1-x)(x^{2}+1)}dx$
> b) $\int\frac{5x}{(x^{2}-x+1)(x-2)}dx$
>
> > [!continue]- Solution
> > **a) $\frac{x+1}{(1-x)(x^{2}+1)}=\frac{A}{(1-x)}+\frac{Bx+C}{(x^{2}+1)}$**
> > $\frac{x+1}{(1-x)(x^{2}+1)}=\frac{A(x^{2}+1)+(Bx+C)(1-x)}{(1-x)(x^{2}+1)} \Rightarrow x+1=A(x^{2}+1)+(Bx+C)(1-x)$
> > 
> > Method 1: Find the value of A, B and C.
> > Let $x=1 \Rightarrow 1+1=A(1^{2}+1)+(B(1)+C)(1-1) \Rightarrow 2=2A \Rightarrow A=1$
> > Let $x=0 \Rightarrow 0+1=A(0^{2}+1)+(B(0)+C)(1-0) \Rightarrow 1=A+C \Rightarrow 1=1+C \Rightarrow C=0$
> > Let $x=-1 \Rightarrow -1+1=A((-1)^{2}+1)+(B(-1)+C)(1-(-1)) \Rightarrow 0=2A-2B+2C \Rightarrow 0=2(1)-2B+0 \Rightarrow B=1$
> > 
> > Method 2: Find the values of A, B and C.
> > $x+1=A(x^{2}+1)+(Bx+C)(1-x) = Ax^{2}+A+Bx-Bx^{2}+C-Cx = (A-B)x^{2}+(B-C)x+A+C$
> > Compare the coefficients:
> > $x^{2}: 0=A-B \Rightarrow A=B$
> > $x^{1}: 1=B-C$
> > $x^{0}: 1=A+C$
> > By using simultaneous equation, we will get the values of $A=B=1$ and $C=0$.
> > 
> > Thus, we have
> > $\int\frac{x+1}{(1-x)(x^{2}+1)}dx=\int\frac{1}{(1-x)}dx+\int\frac{x}{(x^{2}+1)}dx$
> > *(Note: The integral of $\frac{1}{1-x}$ is $-\ln|1-x|$. The source text states $\ln|1-x|$, which is a typographical error).*
> > $=-\ln|1-x|+\frac{1}{2}\int\frac{2x}{x^{2}+1}dx = -\ln|1-x|+\frac{1}{2}\ln|x^{2}+1|+C$
> > 
> > **b) $\frac{5x}{(x^{2}-x+1)(x-2)}=\frac{Ax+B}{(x^{2}-x+1)}+\frac{C}{(x-2)}$**
> > $\frac{5x}{(x^{2}-x+1)(x-2)}=\frac{(Ax+B)(x-2)+C(x^{2}-x+1)}{(x^{2}-x+1)(x-2)} \Rightarrow 5x=(Ax+B)(x-2)+C(x^{2}-x+1)$
> > 
> > Method 2: Find the values of A, B and C.
> > $5x = Ax^{2}-2Ax+Bx-2B+Cx^{2}-Cx+C = (A+C)x^{2}+(-2A+B-C)x+(-2B+C)$
> > Compare the coefficients:
> > $x^{2}: 0=A+C \Rightarrow C=-A$
> > $x^{1}: 5=-2A+B-C$
> > $x^{0}: 0=-2B+C \Rightarrow C=2B$
> > 
> > Solve A, B and C by using simultaneous equation:
> > $5=-2A+B-(-A) \Rightarrow 5=-A+B \Rightarrow B=A+5$  ---(1)
> > Since $C=2B$ and $C=-A$, then $-A=2B \Rightarrow B=-\frac{1}{2}A$. *(Note: Text uses $B=-2A-5$ via another path: $5=-2A+B-2B \Rightarrow B=-2A-5$. Let's stick to the text's path)*
> > $5 = -2A+B-2B \Rightarrow B = -2A-5$   ---(2)
> > Equate (1) and (2):
> > $-2A-5=A+5 \Rightarrow -10=3A \Rightarrow A=-\frac{10}{3}$
> > As $A=-\frac{10}{3}$, $C=-(-\frac{10}{3})=\frac{10}{3}$, $B=-\frac{10}{3}+5=\frac{5}{3}$
> > 
> > Thus, we have
> > $\int\frac{5x}{(x^{2}-x+1)(x-2)}dx=\int\frac{-\frac{10}{3}x+\frac{5}{3}}{(x^{2}-x+1)}+\frac{\frac{10}{3}}{(x-2)}dx = \frac{1}{3}\int\frac{-5(2x-1)}{(x^{2}-x+1)}dx+\frac{10}{3}\ln|x-2|$
> > $=-\frac{5}{3}\int\frac{2x-1}{x^{2}-x+1}dx+\frac{10}{3}\ln|x-2| = -\frac{5}{3}\ln|x^{2}-x+1|+\frac{10}{3}\ln|x-2|+C$

Now, let us take a look at the examples that need to perform long division which involves all the three cases.

> [!example]- Example 4.17
> Evaluate the following integrals.
> a) $\int\frac{x^{2}}{x^{2}+3x+2}dx$
> b) $\int\frac{x^{3}}{x^{2}+5x+6}dx$
>
> > [!continue]- Solution
> > **a) $\int\frac{x^{2}}{x^{2}+3x+2}dx$**
> > The first step is to perform long division since the integrand is an improper fraction.
> > The result of long division is $\frac{x^{2}}{x^{2}+3x+2}=1-\left(\frac{3x+2}{x^{2}+3x+2}\right)=1-\left(\frac{3x+2}{(x+1)(x+2)}\right)$
> > $\int\frac{x^{2}}{x^{2}+3x+2}dx=\int 1-\left(\frac{3x+2}{(x+1)(x+2)}\right)dx$
> > 
> > $\frac{3x+2}{(x+1)(x+2)}=\frac{A}{(x+1)}+\frac{B}{(x+2)}$
> > $\frac{3x+2}{(x+1)(x+2)}=\frac{A(x+2)+B(x+1)}{(x+1)(x+2)} \Rightarrow 3x+2=A(x+2)+B(x+1)$
> > 
> > Method 1: Find the values of A and B.
> > Let $x=-2 \Rightarrow 3(-2)+2=A(-2+2)+B(-2+1) \Rightarrow -4=-B \Rightarrow B=4$
> > Let $x=-1 \Rightarrow 3(-1)+2=A(-1+2)+B(-1+1) \Rightarrow -1=A \Rightarrow A=-1$
> > 
> > $\int\frac{x^{2}}{x^{2}+3x+2}dx=\int\left(1-\left(\frac{-1}{(x+1)}+\frac{4}{(x+2)}\right)\right)dx = \int 1dx+\int\frac{1}{(x+1)}dx-4\int\frac{1}{(x+2)}dx$
> > $=x+\ln|x+1|-4 \ln|x+2|+C$
> > 
> > **b) $\int\frac{x^{3}}{x^{2}+5x+6}dx$**
> > The integrand is an improper fraction. By using long division:
> > The result of long division is $\frac{x^{3}}{x^{2}+5x+6}=(x-5)+\left(\frac{19x+30}{x^{2}+5x+6}\right)=(x-5)+\left(\frac{19x+30}{(x+2)(x+3)}\right)$
> > 
> > $\frac{19x+30}{(x+2)(x+3)}=\frac{A}{(x+2)}+\frac{B}{(x+3)} = \frac{A(x+3)+B(x+2)}{(x+2)(x+3)}$
> > $19x+30=A(x+3)+B(x+2)$
> > 
> > Method 1: Find the values of A and B.
> > Let $x=-2 \Rightarrow 19(-2)+30=A(-2+3)+B(-2+2) \Rightarrow -8=A \Rightarrow A=-8$
> > Let $x=-3 \Rightarrow 19(-3)+30=A(-3+3)+B(-3+2) \Rightarrow -27=-B \Rightarrow B=27$
> > 
> > $\int\frac{x^{3}}{x^{2}+5x+6}dx=\int\left((x-5)+\left(-\frac{8}{(x+2)}+\frac{27}{(x+3)}\right)\right)dx$
> > $=\int(x-5)dx-8\int\frac{1}{(x+2)}dx+27\int\frac{1}{(x+3)}dx = \frac{x^{2}}{2}-5x-8 \ln|x+2|+27 \ln|x+3|+C$

Sometimes, we need to do substitution first to transform the given integral into the form that is suitable to the use of partial fractions. Only then the expression can be integrated. Let's see the following examples.

> [!example]- Example 4.18
> Evaluate the following integrals.
> a) $\int\frac{dx}{1-e^{x}}$
> b) $\int\frac{dx}{e^{x}(1+e^{x})}$
>
> > [!continue]- Solution
> > **a) $\int\frac{dx}{1-e^{x}}$**
> > Let $z=1-e^{x} \Rightarrow e^{x}=1-z$. Then $\frac{dz}{dx}=-e^{x} \Rightarrow dx = \frac{dz}{-e^{x}}$.
> > $\int\frac{1}{1-e^{x}}dx=\int\frac{1}{z}\times\frac{dz}{-e^{x}}=\int\frac{1}{z(z-1)}dz$
> > 
> > $\frac{1}{z(z-1)}=\frac{A}{z}+\frac{B}{z-1} = \frac{A(z-1)+Bz}{z(z-1)}$
> > $1=A(z-1)+Bz \Rightarrow 1=(A+B)z-A$
> > 
> > Method 2: Find the values of A and B.
> > Compare the coefficients:
> > $x^{1}: 0=A+B \Rightarrow B=-A$
> > $x^{0}: 1=-A \Rightarrow A=-1$. Thus, $B=1$.
> > 
> > $\int\frac{1}{1-e^{x}}dx=\int\frac{1}{z(z-1)}dz=\int\left(-\frac{1}{z}+\frac{1}{z-1}\right)dz = -\ln|z|+\ln|z-1|+C$
> > $=-\ln|1-e^{x}|+\ln|-e^{x}|+C = \ln\left|\frac{-e^{x}}{1-e^{x}}\right|+C$
> > 
> > **b) $\int\frac{dx}{e^{x}(1+e^{x})}$**
> > Let $z=1+e^{x} \Rightarrow e^{x}=z-1$. Then $\frac{dz}{dx}=e^{x} \Rightarrow dx = \frac{dz}{e^{x}}$.
> > $\int\frac{dx}{e^{x}(1+e^{x})}=\int\frac{1}{(z-1)z}\times\frac{dz}{e^{x}}=\int\frac{1}{z(z-1)^{2}}dz$
> > 
> > $\frac{1}{z(z-1)^{2}}=\frac{A}{z}+\frac{B}{(z-1)}+\frac{C}{(z-1)^{2}} = \frac{A(z-1)^{2}+Bz(z-1)+Cz}{z(z-1)^{2}}$
> > $1=A(z-1)^{2}+Bz(z-1)+Cz$
> > 
> > Method 1: Find the values of A, B and C.
> > Let $z=0 \Rightarrow 1=A(0-1)^{2}+B(0)(0-1)+C(0) \Rightarrow 1=A$
> > Let $z=1 \Rightarrow 1=A(1-1)^{2}+B(1)(1-1)+C(1) \Rightarrow C=1$
> > Let $z=-1 \Rightarrow 1=A(-1-1)^{2}+B(-1)(-1-1)+C(-1) \Rightarrow 1=4A+2B-C$
> > Since $A=1, C=1 \Rightarrow 1=4(1)+2B-1 \Rightarrow 2B=-2 \Rightarrow B=-1$
> > 
> > $\int\frac{dx}{e^{x}(1+e^{x})}=\int\left(\frac{1}{z}-\frac{1}{(z-1)}+\frac{1}{(z-1)^{2}}\right)dz = \ln|z|-\ln|z-1|+\int(z-1)^{-2}dz$
> > $=\ln|z|-\ln|z-1|+\frac{(z-1)^{-1}}{-1}+C = \ln|1+e^{x}|-\ln|e^{x}|-\frac{1}{e^{x}}+C$
> > $=\ln\left|\frac{1+e^{x}}{e^{x}}\right|-e^{-x}+C = \ln|1+e^{-x}|-e^{-x}+C$

> [!sq]- Problem 4.7
> a) Use partial fractions to find the following integrals:
> i. $\int\frac{x^{2}-1}{x-3}dx$
> ii. $\int\frac{3x^{2}-6x-1}{(x-1)(x+1)^{2}}dx$
> b) Show that $\int\frac{2-x}{x^{2}+5x}dx=\frac{2\ln|x|}{5}-\frac{7}{5}\ln|x+5|+C$
> c) Show that $\int_{1}^{2}\frac{2(4x^{2}+1)}{(2x+1)(2x-1)}dx=2+\ln k$. Hence, find the value of k.
>
> > [!continue]- Solution
> > **a) i. $\int\frac{x^{2}-1}{x-3}dx$**
> > Perform long division on the improper fraction: $\frac{x^2-1}{x-3} = x + 3 + \frac{8}{x-3}$.
> > $\int\left(x + 3 + \frac{8}{x-3}\right)dx = \frac{x^2}{2} + 3x + 8\ln|x-3| + C$.
> > 
> > **a) ii. $\int\frac{3x^{2}-6x-1}{(x-1)(x+1)^{2}}dx$**
> > Decompose: $\frac{3x^2-6x-1}{(x-1)(x+1)^2} = \frac{A}{x-1} + \frac{B}{x+1} + \frac{C}{(x+1)^2}$.
> > $3x^2-6x-1 = A(x+1)^2 + B(x-1)(x+1) + C(x-1)$.
> > Set $x=1$: $3(1)^2 - 6(1) - 1 = A(2)^2 \Rightarrow -4 = 4A \Rightarrow A = -1$.
> > Set $x=-1$: $3(-1)^2 - 6(-1) - 1 = C(-2) \Rightarrow 8 = -2C \Rightarrow C = -4$.
> > Set $x=0$: $-1 = A - B - C \Rightarrow -1 = -1 - B - (-4) \Rightarrow -1 = 3 - B \Rightarrow B = 4$.
> > $\int\left(\frac{-1}{x-1} + \frac{4}{x+1} - \frac{4}{(x+1)^2}\right)dx = -\ln|x-1| + 4\ln|x+1| + \frac{4}{x+1} + C$.
> > 
> > **b) Show that $\int\frac{2-x}{x^{2}+5x}dx=\frac{2\ln|x|}{5}-\frac{7}{5}\ln|x+5|+C$**
> > Decompose: $\frac{2-x}{x(x+5)} = \frac{A}{x} + \frac{B}{x+5}$.
> > $2-x = A(x+5) + Bx$.
> > Set $x=0$: $2 = 5A \Rightarrow A = \frac{2}{5}$.
> > Set $x=-5$: $7 = -5B \Rightarrow B = -\frac{7}{5}$.
> > $\int\left(\frac{2/5}{x} - \frac{7/5}{x+5}\right)dx = \frac{2}{5}\ln|x| - \frac{7}{5}\ln|x+5| + C$. (Shown).
> > 
> > **c) $\int_{1}^{2}\frac{2(4x^{2}+1)}{(2x+1)(2x-1)}dx = \int_{1}^{2}\frac{8x^{2}+2}{4x^{2}-1}dx$**
> > Perform long division: $\frac{8x^2+2}{4x^2-1} = 2 + \frac{4}{4x^2-1}$.
> > Decompose: $\frac{4}{(2x-1)(2x+1)} = \frac{A}{2x-1} + \frac{B}{2x+1}$.
> > $4 = A(2x+1) + B(2x-1)$.
> > Set $x=\frac{1}{2}$: $4 = 2A \Rightarrow A=2$.
> > Set $x=-\frac{1}{2}$: $4 = -2B \Rightarrow B=-2$.
> > Evaluate integral: $\int_1^2 \left(2 + \frac{2}{2x-1} - \frac{2}{2x+1}\right)dx = \left[2x + \ln|2x-1| - \ln|2x+1|\right]_1^2$
> > $= \left[2x + \ln\left|\frac{2x-1}{2x+1}\right|\right]_1^2 = \left(4 + \ln\frac{3}{5}\right) - \left(2 + \ln\frac{1}{3}\right) = 2 + \ln\left(\frac{3/5}{1/3}\right) = 2 + \ln\left(\frac{9}{5}\right)$.
> > Therefore, $2 + \ln\left(\frac{9}{5}\right) = 2 + \ln k \Rightarrow k = \frac{9}{5} = 1.8$.

> [!sq]- Problem 4.8
> a) Evaluate the following integrals:
> i. $\int_{-3}^{0}\sqrt[3]{3-2x}dx$
> ii. $\int_{-1}^{1}\frac{7}{x^{2}+x-12}dx$
> iii. $\int_{0}^{\ln 3}4e^{2x}dx$
> iv. $\int_{1}^{2}\frac{e^{2x}}{e^{x}-1}dx$
> b) By using the given substitution, evaluate the integral $\int x^{5}e^{x^{2}}dx$, where $z=x^{2}$.
>
> > [!continue]- Solution
> > **a) i. $\int_{-3}^{0}\sqrt[3]{3-2x}dx$**
> > Let $u = 3-2x \Rightarrow du = -2dx$. When $x=-3, u=9$; when $x=0, u=3$.
> > $\int_{9}^{3} u^{1/3}\left(\frac{du}{-2}\right) = \frac{1}{2}\int_{3}^{9} u^{1/3}du = \frac{1}{2}\left[\frac{3}{4}u^{4/3}\right]_{3}^{9} = \frac{3}{8}(9^{4/3} - 3^{4/3}) = \frac{3}{8}(9\sqrt[3]{9} - 3\sqrt[3]{3})$.
> > 
> > **a) ii. $\int_{-1}^{1}\frac{7}{x^{2}+x-12}dx$**
> > Factor: $x^2+x-12 = (x-3)(x+4)$.
> > $\frac{7}{(x-3)(x+4)} = \frac{1}{x-3} - \frac{1}{x+4}$ (Using partial fractions from Example 4.14c).
> > $\int_{-1}^{1}\left(\frac{1}{x-3} - \frac{1}{x+4}\right)dx = [\ln|x-3| - \ln|x+4|]_{-1}^{1} = \left[\ln\left|\frac{x-3}{x+4}\right|\right]_{-1}^{1}$.
> > $= \ln\left|\frac{-2}{5}\right| - \ln\left|\frac{-4}{3}\right| = \ln\left(\frac{2}{5}\right) - \ln\left(\frac{4}{3}\right) = \ln\left(\frac{2/5}{4/3}\right) = \ln\left(\frac{6}{20}\right) = \ln\left(\frac{3}{10}\right)$.
> > 
> > **a) iii. $\int_{0}^{\ln 3}4e^{2x}dx$**
> > $= \left[2e^{2x}\right]_{0}^{\ln 3} = 2e^{2\ln 3} - 2e^{0} = 2e^{\ln 9} - 2 = 2(9) - 2 = 18 - 2 = 16$.
> > 
> > **a) iv. $\int_{1}^{2}\frac{e^{2x}}{e^{x}-1}dx$**
> > Let $u = e^x - 1 \Rightarrow e^x = u+1$, $du = e^x dx$. When $x=1, u=e-1$; when $x=2, u=e^2-1$.
> > $\int \frac{e^x \cdot e^x}{e^x - 1} dx = \int \frac{u+1}{u} du = \int (1 + \frac{1}{u}) du = [u + \ln|u|]$.
> > Evaluation: $[u + \ln|u|]_{e-1}^{e^2-1} = (e^2-1 + \ln(e^2-1)) - (e-1 + \ln(e-1)) = e^2 - e + \ln\left(\frac{e^2-1}{e-1}\right) = e^2 - e + \ln(e+1)$.
> > 
> > **b) $\int x^{5}e^{x^{2}}dx$, where $z=x^{2}$**
> > $z = x^2 \Rightarrow dz = 2xdx \Rightarrow xdx = \frac{dz}{2}$.
> > $\int x^4 e^{x^2} (xdx) = \int z^2 e^z \left(\frac{dz}{2}\right) = \frac{1}{2}\int z^2 e^z dz$.
> > Using tabular integration for $\int z^2 e^z dz$:
> > $u = z^2 \Rightarrow 2z \Rightarrow 2 \Rightarrow 0$.
> > $dv = e^z \Rightarrow e^z \Rightarrow e^z \Rightarrow e^z$.
> > $\frac{1}{2} [ z^2 e^z - 2z e^z + 2e^z ] + C = \frac{1}{2}e^{z}(z^2 - 2z + 2) + C = \frac{1}{2}e^{x^2}(x^4 - 2x^2 + 2) + C$.

## 4.5 INTEGRATION OF TRIGONOMETRIC FUNCTIONS
Generally, the integration of trigonometric functions is simple. However, a simplification method is needed if more complicated trigonometric identities want to be evaluated. Calculating an integral whose integrand contains powers of one or more trigonometric functions generally involves making a wise substitution. These integrals are sufficiently common that they are presented as a group.

**INTEGRATION OF TRIGONOMETRIC FUNCTIONS:** $\int \sin^{m}x \cos^{n}x dx, \quad m,n\in \mathbb{Z}^{+}$

| CASE 1 | Both m and n even |
| :--- | :--- |
| **CASE 2** | **Either m or n odd** |

#### CASE I: Both m and n are even
We can use the method by using the following identity:
$cos^{2}x=\frac{1+\cos 2x}{2}$
$sin^{2}x=\frac{1-\cos 2x}{2}$

> [!example]- Example 4.19
> Evaluate $\int \cos^{2}3x+\sin^{2}5x dx$
>
> > [!continue]- Solution
> > $\int \cos^{2}3x+\sin^{2}5x dx=\int \frac{1+\cos 6x}{2}+\frac{1-\cos 10x}{2}dx$
> > $=\int 1+\frac{\cos 6x}{2}-\frac{\cos 10x}{2}dx$
> > $=x+\frac{\sin 6x}{12}-\frac{\sin 10x}{20}+C$

> [!example]- Example 4.20
> Evaluate $\int(1+\cos 3x)^{2}dx$
>
> > [!continue]- Solution
> > $\int(1+\cos 3x)^{2}dx=\int 1+2\cos 3x+\cos^{2}3x dx$
> > $=\int 1+2\cos 3x+\frac{1+\cos 6x}{2}dx$
> > $=\int \frac{3}{2}+2\cos 3x+\frac{\cos 6x}{2}dx$
> > $=\frac{3}{2}x+\frac{2\sin 3x}{3}+\frac{\sin 6x}{12}+C$

> [!example]- Example 4.21
> Find $\int \sin^{4}2x dx$
>
> > [!continue]- Solution
> > $\int \sin^{4}2x dx=\int(\sin^{2}2x)^{2}dx=\int(\frac{1-\cos 4x}{2})^{2}dx$
> > $=\int \frac{1}{4}-\frac{\cos 4x}{2}+\frac{\cos^{2}4x}{4}dx$
> > $=\int \frac{1}{4}-\frac{\cos 4x}{2}+\frac{1+\cos 8x}{8}dx$
> > $=\int \frac{3}{8}-\frac{\cos 4x}{2}+\frac{\cos 8x}{8}dx$
> > $=\frac{3}{8}x-\frac{\sin 4x}{8}+\frac{\sin 8x}{64}+C$

> [!example]- Example 4.22
> Find $\int_{0}^{2}\sin 2x(1+3\sin 2x)dx$
>
> > [!continue]- Solution
> > $\int_{0}^{2}\sin 2x(1+3\sin 2x)dx=\int_{0}^{2}\sin 2x+3\sin^{2}2x dx$
> > $=\int_{0}^{2}\sin 2x+3\left(\frac{1-\cos 4x}{2}\right)dx$
> > $=\int_{0}^{2}\sin 2x+\frac{3}{2}-\frac{3\cos 4x}{2}dx$
> > $=[-\frac{\cos 2x}{2}+\frac{3}{2}x-\frac{3\sin 4x}{8}]_{0}^{2}$
> > $=(-\frac{\cos 2(2)}{2}+\frac{3}{2}(2)-\frac{3\sin 4(2)}{8})-(-\frac{\cos 2(0)}{2}+\frac{3}{2}(0)-\frac{3\sin 4(0)}{8})$
> > $\approx 2.9558-(-0.5) = 3.4558$

> [!sq]- Problem 4.9
> Find:
> i. $\int_{0}^{\frac{\pi}{2}}\cos^{2}\frac{x}{2}dx$
> ii. $\int(1-\sin 2x)^{2}dx$
>
> > [!continue]- Solution
> > **i. $\int_{0}^{\frac{\pi}{2}}\cos^{2}\frac{x}{2}dx$**
> > $\int_{0}^{\frac{\pi}{2}}\cos^{2}\frac{x}{2}dx = \int_{0}^{\frac{\pi}{2}} \frac{1+\cos x}{2} dx = \left[ \frac{x}{2} + \frac{\sin x}{2} \right]_{0}^{\frac{\pi}{2}}$
> > $= \left( \frac{\pi}{4} + \frac{\sin(\pi/2)}{2} \right) - \left( 0 + \frac{\sin 0}{2} \right) = \frac{\pi}{4} + \frac{1}{2}$.
> > 
> > **ii. $\int(1-\sin 2x)^{2}dx$**
> > $\int(1-\sin 2x)^{2}dx = \int (1 - 2\sin 2x + \sin^2 2x) dx = \int \left( 1 - 2\sin 2x + \frac{1-\cos 4x}{2} \right) dx$
> > $= \int \left( \frac{3}{2} - 2\sin 2x - \frac{\cos 4x}{2} \right) dx = \frac{3}{2}x + \cos 2x - \frac{\sin 4x}{8} + C$.

#### CASE II: Either m or n is odd
We can use the steps below:
* **Step 1.** Bring down the odd power to even.
* **Step 2.** Use the identity $\cos^{2}x+\sin^{2}x=1$.
* **Step 3.** Apply integration by substitution.

> [!example]- Example 4.23
> Find $\int \sin^{3}x dx$
>
> > [!continue]- Solution
> > Let $u=\cos x \Rightarrow \frac{du}{dx}=-\sin x \Rightarrow \sin x dx=-du$
> > $\int \sin^{3}x dx=\int \sin^{2}x \sin x dx$
> > $=\int(1-\cos^{2}x)\sin x dx$
> > $=-\int(1-u^{2})du$
> > $=-(u-\frac{u^{3}}{3})=\frac{\cos^{3}x}{3}-\cos x+C$

> [!example]- Example 4.24
> Find $\int \sin^{3}2\theta \cos^{4}2\theta d\theta$
>
> > [!continue]- Solution
> > Let $u=\cos 2\theta \Rightarrow \frac{du}{d\theta}=-2\sin 2\theta \Rightarrow \sin 2\theta d\theta=\frac{-du}{2}$
> > $\int \sin^{3}2\theta \cos^{4}2\theta d\theta=\int \sin^{2}2\theta \sin 2\theta \cos^{4}2\theta d\theta$
> > $=\int(1-\cos^{2}2\theta)\sin 2\theta \cos^{4}2\theta d\theta$
> > $=-\int(1-u^{2})u^{4}\frac{du}{2}$
> > $=\int\frac{u^{6}-u^{4}}{2}du$
> > $=\frac{u^{7}}{14}-\frac{u^{5}}{10} = \frac{\cos^{7}2\theta}{14}-\frac{\cos^{5}2\theta}{10}+C$
\

> [!example]- Example 4.25
> Find $\int_{0}^{\frac{\pi}{2}}\sin \theta(1+\sin^{2}\theta)d\theta$
>
> > [!continue]- Solution
> > Let $u=\cos \theta \Rightarrow \frac{du}{d\theta}=-\sin \theta \Rightarrow \sin \theta d\theta=-du$
> > $\int_{0}^{\frac{\pi}{2}}\sin \theta(1+\sin^{2}\theta)d\theta=\int_{0}^{\frac{\pi}{2}}\sin \theta+\sin^{3}\theta d\theta$
> > $=\int_{0}^{\frac{\pi}{2}}\sin \theta+\sin^{2}\theta \sin \theta d\theta$
> > $=\int_{0}^{\frac{\pi}{2}}\sin \theta+(1-\cos^{2}\theta)\sin \theta d\theta$
> > $=\int_{\theta=0}^{\theta=\frac{\pi}{2}}\sin \theta-(1-u^{2})du$
> > $=[-\cos \theta-u+\frac{u^{3}}{3}]_{\theta=0}^{\theta=\frac{\pi}{2}}=[-2\cos \theta+\frac{\cos^{3}\theta}{3}]_{0}^{\frac{\pi}{2}}$
> > $=(-2\cos\frac{\pi}{2}+\frac{\cos^{3}\frac{\pi}{2}}{3})-(-2\cos 0+\frac{\cos^{3}0}{3})$
> > $=0-(-\frac{5}{3})=\frac{5}{3}$

> [!sq]- Problem 4.10
> Find:
> i. $\int_{0}^{\frac{\pi}{2}}\cos^{3}\frac{t}{2}dt$
> ii. $\int \sin^{5}x \cos^{2}x dx$
>
> > [!continue]- Solution
> > **i. $\int_{0}^{\frac{\pi}{2}}\cos^{3}\frac{t}{2}dt$**
> > $\int_{0}^{\frac{\pi}{2}} \cos^2(t/2) \cos(t/2) dt = \int_{0}^{\frac{\pi}{2}} (1-\sin^2(t/2)) \cos(t/2) dt$.
> > Let $u = \sin(t/2) \Rightarrow du = \frac{1}{2}\cos(t/2)dt \Rightarrow \cos(t/2)dt = 2du$.
> > When $t=0, u=0$; when $t=\pi/2, u=\sin(\pi/4) = 1/\sqrt{2}$.
> > $\int_{0}^{1/\sqrt{2}} (1-u^2) 2du = 2\left[ u - \frac{u^3}{3} \right]_{0}^{1/\sqrt{2}} = 2\left( \frac{1}{\sqrt{2}} - \frac{1}{6\sqrt{2}} \right) = 2\left( \frac{5}{6\sqrt{2}} \right) = \frac{5}{3\sqrt{2}} = \frac{5\sqrt{2}}{6}$.
> > 
> > **ii. $\int \sin^{5}x \cos^{2}x dx$**
> > $\int \sin^4 x \cos^2 x \sin x dx = \int (1-\cos^2 x)^2 \cos^2 x \sin x dx$.
> > Let $u=\cos x \Rightarrow du=-\sin x dx$.
> > $-\int (1-u^2)^2 u^2 du = -\int (1-2u^2+u^4)u^2 du = -\int (u^2 - 2u^4 + u^6) du$
> > $= -\frac{u^3}{3} + \frac{2u^5}{5} - \frac{u^7}{7} + C = -\frac{\cos^3 x}{3} + \frac{2\cos^5 x}{5} - \frac{\cos^7 x}{7} + C$.

This section deals with the integral of the forms: $\int \sin mx \cos nx dx$, $\int \sin mx \sin nx dx$ and $\int \cos mx \cos nx dx$ can be solve by substitutes with the trigonometric identities.

**Product of sin x and cos x Identities:**
* $\int \sin mx \cos nx dx \Rightarrow \sin A \cos B = \frac{\sin(A-B)+\sin(A+B)}{2}$
* $\int \cos mx \cos nx dx \Rightarrow \cos A \cos B = \frac{\cos(A-B)+\cos(A+B)}{2}$
* $\int \sin mx \sin nx dx \Rightarrow \sin A \sin B = \frac{\cos(A-B)-\cos(A+B)}{2}$

> [!example]- Example 4.26
> Find $\int \sin 2x \sin 3x dx$
>
> > [!continue]- Solution
> > $\int \sin 2x \sin 3x dx=\int\frac{\cos(2x-3x)-\cos(2x+3x)}{2}dx$
> > $=\int\frac{\cos(-x)-\cos 5x}{2}dx$
> > $=\int\frac{\cos x-\cos 5x}{2}dx$
> > $=\frac{\sin x}{2}-\frac{\sin 5x}{10}+C$

> [!example]- Example 4.27
> Find $\int_{0}^{\frac{\pi}{2}}\cos 3x(\cos 3x+\cos x)dx$
>
> > [!continue]- Solution
> > $\int_{0}^{\frac{\pi}{2}}\cos 3x(\cos 3x+\cos x)dx=\int_{0}^{\frac{\pi}{2}}\cos^{2}3x+\cos 3x \cos x dx$
> > $=\int_{0}^{\frac{\pi}{2}}\frac{1+\cos 6x}{2}+\frac{\cos(3x-x)+\cos(3x+x)}{2}dx$
> > $=\int_{0}^{\frac{\pi}{2}}\frac{1+\cos 6x}{2}+\frac{\cos 2x+\cos 4x}{2}dx$
> > $=[\frac{x}{2}+\frac{\sin 6x}{12}+\frac{\sin 2x}{4}+\frac{\sin 4x}{8}]_{0}^{\frac{\pi}{2}}$
> > $=(\frac{\pi}{4}+\frac{\sin 6(\frac{\pi}{2})}{12}+\frac{\sin 2(\frac{\pi}{2})}{4}+\frac{\sin 4(\frac{\pi}{2})}{8})-(0+\frac{\sin 6(0)}{12}+\frac{\sin 2(0)}{4}+\frac{\sin 4(0)}{8}) = \frac{\pi}{4}$

> [!sq]- Problem 4.11
> Find:
> i. $\int(\cos\frac{x}{2}-\sin x)^{2}dx$
> ii. $\int_{0}^{\frac{\pi}{2}}\sin 5\theta \cos 3\theta d\theta$
>
> > [!continue]- Solution
> > **i. $\int(\cos\frac{x}{2}-\sin x)^{2}dx$**
> > Expand: $\int (\cos^2(x/2) - 2\sin x \cos(x/2) + \sin^2 x) dx$.
> > Use identities $\cos^2(x/2) = \frac{1+\cos x}{2}$, $\sin^2 x = \frac{1-\cos 2x}{2}$, and product-to-sum $\sin A \cos B$:
> > $2\sin x \cos(x/2) = 2 \left[ \frac{\sin(x - x/2) + \sin(x + x/2)}{2} \right] = \sin(x/2) + \sin(3x/2)$.
> > Integral becomes: $\int \left( \frac{1+\cos x}{2} - \sin(x/2) - \sin(3x/2) + \frac{1-\cos 2x}{2} \right) dx$
> > $= \int \left( 1 + \frac{\cos x}{2} - \sin(x/2) - \sin(3x/2) - \frac{\cos 2x}{2} \right) dx$
> > $= x + \frac{\sin x}{2} + 2\cos(x/2) + \frac{2\cos(3x/2)}{3} - \frac{\sin 2x}{4} + C$.
> > 
> > **ii. $\int_{0}^{\frac{\pi}{2}}\sin 5\theta \cos 3\theta d\theta$**
> > $\int_{0}^{\frac{\pi}{2}} \frac{\sin(5\theta-3\theta) + \sin(5\theta+3\theta)}{2} d\theta = \frac{1}{2} \int_{0}^{\frac{\pi}{2}} (\sin 2\theta + \sin 8\theta) d\theta$
> > $= \frac{1}{2} \left[ -\frac{\cos 2\theta}{2} - \frac{\cos 8\theta}{8} \right]_{0}^{\frac{\pi}{2}} = \frac{1}{2} \left[ \left(-\frac{\cos\pi}{2} - \frac{\cos 4\pi}{8}\right) - \left(-\frac{\cos 0}{2} - \frac{\cos 0}{8}\right) \right]$
> > $= \frac{1}{2} \left[ \left(\frac{1}{2} - \frac{1}{8}\right) - \left(-\frac{1}{2} - \frac{1}{8}\right) \right] = \frac{1}{2} \left[ \frac{3}{8} - \left(-\frac{5}{8}\right) \right] = \frac{1}{2} \left[ \frac{8}{8} \right] = \frac{1}{2}$.

Now we deal with the functions contains a term of the form stated in the table below, where some $a>0$. It is somewhat difficult to integrate these functions directly. Hence, the only solution is by using trigonometric substitutions.

| Expression | Substitutions |
| :--- | :--- |
| $\sqrt{a^{2}+x^{2}}$ | $x=a \tan \theta$ |
| $\sqrt{a^{2}-x^{2}}$ | $x=a \sin \theta$ |
| $\sqrt{x^{2}-a^{2}}$ | $x=a \sec \theta$ |

> [!example]- Example 4.28
> Find $\int_{0}^{1}\frac{x^{2}}{(1+x^{2})^{2}}dx$ by using substitution $x=\tan \theta$
>
> > [!continue]- Solution
> > Let $x=\tan \theta \Rightarrow dx=\sec^{2}\theta d\theta$.
> > Limits: $x=0 \Rightarrow \theta=0$; $x=1 \Rightarrow \theta=\frac{\pi}{4}$.
> > $\int_{0}^{1}\frac{x^{2}}{(1+x^{2})^{2}}dx=\int_{0}^{\frac{\pi}{4}}\frac{\tan^{2}\theta}{(1+\tan^{2}\theta)^{2}}\sec^{2}\theta d\theta$
> > $=\int_{0}^{\frac{\pi}{4}}\frac{\tan^{2}\theta}{(\sec^{2}\theta)^{2}}\sec^{2}\theta d\theta = \int_{0}^{\frac{\pi}{4}}\frac{\tan^{2}\theta}{\sec^{2}\theta}d\theta=\int_{0}^{\frac{\pi}{4}}\frac{\sin^{2}\theta}{\cos^{2}\theta}\times \cos^{2}\theta d\theta$
> > $=\int_{0}^{\frac{\pi}{4}}\sin^{2}\theta d\theta=\int_{0}^{\frac{\pi}{4}}\frac{1-\cos 2\theta}{2}d\theta$
> > $=[\frac{\theta}{2}-\frac{\sin 2\theta}{4}]_{0}^{\frac{\pi}{4}}=[\frac{\pi}{8}-\frac{\sin 2(\frac{\pi}{4})}{4}]-(0-\frac{\sin 2(0)}{4})=\frac{\pi-2}{8}$

> [!example]- Example 4.29
> Find $\int\frac{1}{x^{4}\sqrt{9-x^{2}}}dx$ by using substitution $x=3 \sin \theta$.
>
> > [!continue]- Solution
> > Let $x=3 \sin \theta \Rightarrow dx=3 \cos \theta d\theta$.
> > 
> > ![[Pasted image 20260216180937.png]]
> > 
> > $\int\frac{1}{x^{4}\sqrt{9-x^{2}}}dx=\int\frac{1}{(3 \sin \theta)^{4}\sqrt{9-(3 \sin \theta)^{2}}}3 \cos \theta d \theta$
> > $=\int\frac{1}{81 \sin^{4}\theta\sqrt{9-9 \sin^{2}\theta}}3 \cos \theta d\theta = \int\frac{1}{81\sin^{4}\theta\sqrt{9(1-\sin^{2}\theta)}}3 \cos \theta d\theta$
> > $=\int\frac{1}{81 \sin^{4}\theta\sqrt{9 \cos^{2}\theta}}3 \cos \theta d\theta = \int\frac{1}{81 \sin^{4}\theta (3 \cos \theta)}3 \cos \theta d\theta$
> > $=\int\frac{1}{81 \sin^{4}\theta}d\theta=\int\frac{1}{81}\csc^{4}\theta d\theta=\int\frac{1}{81}\csc^{2}\theta \csc^{2}\theta d\theta$
> > $=\int\frac{1}{81}\csc^{2}\theta(\cot^{2}\theta+1)d\theta$
> > 
> > Let $u=\cot \theta \Rightarrow du=-\csc^{2}\theta d\theta \Rightarrow \csc^{2}\theta d\theta=-du$.
> > $=-\int\frac{1}{81}(u^{2}+1)du$
> > $=-\frac{u^{3}}{243}-\frac{u}{81}=-\frac{\cot^{3}\theta}{243}-\frac{\cot \theta}{81}+C$
> > 
> > From $x=3 \sin \theta$, we have $\sin \theta=\frac{x}{3}$.
> > $\cot \theta=\frac{1}{\tan \theta}=\frac{A}{O}=\frac{\sqrt{9-x^{2}}}{x}$.
> > $\int\frac{1}{x^{4}\sqrt{9-x^{2}}}dx=-\frac{(\frac{\sqrt{9-x^{2}}}{x})^{3}}{243}-\frac{\frac{\sqrt{9-x^{2}}}{x}}{81}+C=-\frac{(\sqrt{9-x^{2}})^{3}}{243x^{3}}-\frac{\sqrt{9-x^{2}}}{81x}+C.$

> [!sq]- Problem 4.12
> Find:
> a) $\int_{0}^{\frac{3}{2}}\sqrt{9-x^{2}}dx$ by using substitution $x=3 \sin \theta$
> b) $\int_{\sqrt{3}}^{2}\frac{\sqrt{x^{2}-3}}{x}dx$ by using substitution $x=\sqrt{3}\sec \theta$
> c) $\int\frac{\sqrt{25x^{2}-4}}{x}dx$ by using substitution $x=\frac{2}{5}\sec \theta$
>
> > [!continue]- Solution
> > **a) $\int_{0}^{\frac{3}{2}}\sqrt{9-x^{2}}dx$ using $x=3\sin\theta$:**
> > $dx = 3\cos\theta d\theta$. Limits: $x=0 \Rightarrow \theta=0$; $x=\frac{3}{2} \Rightarrow \sin\theta=\frac{1}{2} \Rightarrow \theta=\frac{\pi}{6}$.
> > $\int_{0}^{\pi/6} \sqrt{9 - 9\sin^2\theta} (3\cos\theta) d\theta = \int_{0}^{\pi/6} 3\cos\theta (3\cos\theta) d\theta = 9\int_{0}^{\pi/6} \cos^2\theta d\theta$
> > $= \frac{9}{2} \int_{0}^{\pi/6} (1 + \cos 2\theta) d\theta = \frac{9}{2} \left[ \theta + \frac{\sin 2\theta}{2} \right]_{0}^{\pi/6} = \frac{9}{2} \left( \frac{\pi}{6} + \frac{\sin(\pi/3)}{2} \right) = \frac{9}{2} \left( \frac{\pi}{6} + \frac{\sqrt{3}}{4} \right) = \frac{3\pi}{4} + \frac{9\sqrt{3}}{8}$.
> > 
> > **b) $\int_{\sqrt{3}}^{2}\frac{\sqrt{x^{2}-3}}{x}dx$ using $x=\sqrt{3}\sec\theta$:**
> > $dx = \sqrt{3}\sec\theta\tan\theta d\theta$. Limits: $x=\sqrt{3} \Rightarrow \sec\theta=1 \Rightarrow \theta=0$; $x=2 \Rightarrow \sec\theta=\frac{2}{\sqrt{3}} \Rightarrow \theta=\frac{\pi}{6}$.
> > $\int_{0}^{\pi/6} \frac{\sqrt{3\sec^2\theta - 3}}{\sqrt{3}\sec\theta} (\sqrt{3}\sec\theta\tan\theta) d\theta = \int_{0}^{\pi/6} \sqrt{3}\tan\theta (\tan\theta) d\theta = \sqrt{3}\int_{0}^{\pi/6} \tan^2\theta d\theta$
> > $= \sqrt{3}\int_{0}^{\pi/6} (\sec^2\theta - 1) d\theta = \sqrt{3} [\tan\theta - \theta]_{0}^{\pi/6} = \sqrt{3} \left( \frac{1}{\sqrt{3}} - \frac{\pi}{6} \right) = 1 - \frac{\sqrt{3}\pi}{6}$.
> > 
> > **c) $\int\frac{\sqrt{25x^{2}-4}}{x}dx$ using $x=\frac{2}{5}\sec\theta$:**
> > $dx = \frac{2}{5}\sec\theta\tan\theta d\theta$. $\sqrt{25x^2-4} = \sqrt{4\sec^2\theta - 4} = 2\tan\theta$.
> > $\int \frac{2\tan\theta}{\frac{2}{5}\sec\theta} \left(\frac{2}{5}\sec\theta\tan\theta\right) d\theta = \int 2\tan^2\theta d\theta = 2\int (\sec^2\theta - 1) d\theta = 2(\tan\theta - \theta) + C$.
> > Since $\sec\theta = \frac{5x}{2}$, then $\tan\theta = \frac{\sqrt{25x^2-4}}{2}$ and $\theta = \sec^{-1}(\frac{5x}{2})$.
> > Result: $2\left(\frac{\sqrt{25x^2-4}}{2} - \sec^{-1}\left(\frac{5x}{2}\right)\right) + C = \sqrt{25x^2-4} - 2\sec^{-1}\left(\frac{5x}{2}\right) + C$.

---

## 4.6 TUTORIAL 4

> [!sq]- Question 1
> Evaluate:
> i. $\int_{2}^{2}(1+\frac{5}{x})(x-2)^{2}dx$
> ii. $\int\frac{(1-\sqrt{x})^{2}}{x^{2}}dx$
> iii. $\int_{1}^{\frac{\pi}{2}}e^{3x}+\sin 3x-\frac{2}{x}dx$
> iv. $\int_{0}^{\frac{\pi}{4}}\frac{2\tan x}{\sin 2x}dx$ *(Note: Upper bound adjusted to $\pi/4$ as evaluating at $\pi/2$ diverges)*
> v. $\int\frac{3\cos^{4}x-5\cos x}{\cos^{3}x}dx$
>
> > [!continue]- Solution
> > **i.** Since the upper and lower bounds are the same: $\int_{2}^{2}(1+\frac{5}{x})(x-2)^{2}dx = 0$.
> > 
> > **ii.** Expand numerator: $\int \frac{1 - 2\sqrt{x} + x}{x^2} dx = \int (x^{-2} - 2x^{-3/2} + x^{-1}) dx$
> > $= \frac{x^{-1}}{-1} - 2\left(\frac{x^{-1/2}}{-1/2}\right) + \ln|x| + C = -\frac{1}{x} + \frac{4}{\sqrt{x}} + \ln|x| + C$.
> > 
> > **iii.** $\int_{1}^{\frac{\pi}{2}}(e^{3x}+\sin 3x-\frac{2}{x})dx = \left[ \frac{e^{3x}}{3} - \frac{\cos 3x}{3} - 2\ln|x| \right]_{1}^{\frac{\pi}{2}}$
> > $= \left( \frac{e^{3\pi/2}}{3} - 0 - 2\ln\left(\frac{\pi}{2}\right) \right) - \left( \frac{e^3}{3} - \frac{\cos 3}{3} - 0 \right) = \frac{e^{3\pi/2} - e^3 + \cos 3}{3} - 2\ln\left(\frac{\pi}{2}\right)$.
> > 
> > **iv.** Simplify integrand: $\frac{2\tan x}{\sin 2x} = \frac{2(\sin x/\cos x)}{2\sin x\cos x} = \frac{1}{\cos^2 x} = \sec^2 x$.
> > $\int_{0}^{\pi/4} \sec^2 x dx = [\tan x]_{0}^{\pi/4} = 1 - 0 = 1$.
> > 
> > **v.** Simplify integrand: $\int \left(\frac{3\cos^4 x}{\cos^3 x} - \frac{5\cos x}{\cos^3 x}\right) dx = \int (3\cos x - 5\sec^2 x) dx = 3\sin x - 5\tan x + C$.

> [!sq]- Question 2
> Solve the following integrals by using appropriate substitutions:
> i. $\int\frac{4x}{3x^{2}-1}dx$
> ii. $\int \sin 2x(\cos 2x-1)^{3}dx$
> iii. $\int\frac{5\sec^{2}x}{(2+\tan x)^{2}}dx$
> iv. $\int_{2}^{4}\frac{5x}{(x-3)^{4}}dx$
>
> > [!continue]- Solution
> > **i.** Let $u = 3x^2-1 \Rightarrow du = 6x dx \Rightarrow x dx = \frac{du}{6}$.
> > $\int \frac{4}{u} \frac{du}{6} = \frac{2}{3} \int \frac{1}{u} du = \frac{2}{3}\ln|3x^2-1| + C$.
> > 
> > **ii.** Let $u = \cos 2x - 1 \Rightarrow du = -2\sin 2x dx \Rightarrow \sin 2x dx = -\frac{du}{2}$.
> > $\int u^3 \left(-\frac{du}{2}\right) = -\frac{1}{2} \frac{u^4}{4} + C = -\frac{(\cos 2x - 1)^4}{8} + C$.
> > 
> > **iii.** Let $u = 2+\tan x \Rightarrow du = \sec^2 x dx$.
> > $\int \frac{5}{u^2} du = 5 \int u^{-2} du = 5 \left(\frac{u^{-1}}{-1}\right) + C = -\frac{5}{2+\tan x} + C$.
> > 
> > **iv.** Let $u = x-3 \Rightarrow du = dx$, $x = u+3$.
> > Note: The function has a discontinuity at $x=3$ inside the interval $[2,4]$, making it an improper integral that diverges. Ignoring convergence for substitution practice:
> > $\int \frac{5(u+3)}{u^4} du = \int (5u^{-3} + 15u^{-4}) du = -\frac{5}{2u^2} - \frac{5}{u^3}$.
> > Substituting back and evaluating blindly: $\left[ -\frac{5}{2(x-3)^2} - \frac{5}{(x-3)^3} \right]_{2}^{4} = \left(-\frac{5}{2} - 5\right) - \left(-\frac{5}{2} + 5\right) = -7.5 - 2.5 = -10$.

> [!sq]- Question 3
> Evaluate $\int x^{2}(x^{3}-6)^{7}dx$ using the substitution $u=x^{3}-6$.
>
> > [!continue]- Solution
> > $u = x^3-6 \Rightarrow du = 3x^2 dx \Rightarrow x^2 dx = \frac{du}{3}$.
> > $\int u^7 \frac{du}{3} = \frac{1}{3} \frac{u^8}{8} + C = \frac{(x^3-6)^8}{24} + C$.

> [!sq]- Question 4
> By using integration by parts, show that
> $\int \cos(\ln x)dx=\frac{1}{2}x \cos(\ln x)+\frac{1}{2}x \sin(\ln x)+C$ where C is a constant.
>
> > [!continue]- Solution
> > Let $I = \int \cos(\ln x)dx$. Let $u = \cos(\ln x) \Rightarrow du = -\sin(\ln x)\frac{1}{x} dx$. Let $dv = dx \Rightarrow v = x$.
> > $I = x\cos(\ln x) - \int x\left(-\sin(\ln x)\frac{1}{x}\right) dx = x\cos(\ln x) + \int \sin(\ln x) dx$.
> > Apply integration by parts again for $\int \sin(\ln x) dx$: Let $u = \sin(\ln x) \Rightarrow du = \cos(\ln x)\frac{1}{x} dx$, and $dv = dx \Rightarrow v = x$.
> > $\int \sin(\ln x) dx = x\sin(\ln x) - \int x\left(\cos(\ln x)\frac{1}{x}\right) dx = x\sin(\ln x) - \int \cos(\ln x) dx = x\sin(\ln x) - I$.
> > Substitute back into the first equation:
> > $I = x\cos(\ln x) + x\sin(\ln x) - I \Rightarrow 2I = x\cos(\ln x) + x\sin(\ln x)$.
> > $I = \frac{1}{2}x\cos(\ln x) + \frac{1}{2}x\sin(\ln x) + C$. (Shown).

> [!sq]- Question 5
> Evaluate $\int_{0}^{\pi}x^{2}\sin x dx$ by using tabular method. *(Note: Integral bound evaluated at $\pi$ to converge)*
>
> > [!continue]- Solution
> > | Sign | Differentiate $u$ repeatedly | Integrate $v'$ repeatedly |
> > | :--- | :--- | :--- |
> > | + | $x^{2}$ | $\sin x$ |
> > | - | $2x$ | $-\cos x$ |
> > | + | $2$ | $-\sin x$ |
> > | - | $0$ | $\cos x$ |
> > 
> > $\int x^2\sin x dx = -x^2\cos x + 2x\sin x + 2\cos x$.
> > Evaluate at limits:
> > $[ -x^2\cos x + 2x\sin x + 2\cos x ]_{0}^{\pi} = (-\pi^2(-1) + 0 + 2(-1)) - (0 + 0 + 2(1)) = (\pi^2 - 2) - 2 = \pi^2 - 4$.

> [!sq]- Question 6
> Solve the following:
> i. $\int \sin^{4}2x \cos^{5}2x dx$
> ii. $\int(\cos\frac{x}{2}-\sin x)^{2}dx$
> iii. $\int(\sin x-\cos x)(\sin 3x+\cos 2x)dx$
>
> > [!continue]- Solution
> > **i.** Let $u = \sin 2x \Rightarrow du = 2\cos 2x dx$. Rewrite $\cos^5 2x = (\cos^2 2x)^2 \cos 2x = (1-\sin^2 2x)^2 \cos 2x$.
> > $\int u^4 (1-u^2)^2 \frac{du}{2} = \frac{1}{2} \int u^4(1-2u^2+u^4) du = \frac{1}{2} \int (u^4 - 2u^6 + u^8) du$
> > $= \frac{u^5}{10} - \frac{u^7}{7} + \frac{u^9}{18} + C = \frac{\sin^5 2x}{10} - \frac{\sin^7 2x}{7} + \frac{\sin^9 2x}{18} + C$.
> > 
> > **ii.** Solved in Problem 4.11(i).
> > $\int(\cos\frac{x}{2}-\sin x)^{2}dx = x + \frac{\sin x}{2} + 2\cos(x/2) + \frac{2\cos(3x/2)}{3} - \frac{\sin 2x}{4} + C$.
> > 
> > **iii.** Expand: $\int (\sin x \sin 3x + \sin x \cos 2x - \cos x \sin 3x - \cos x \cos 2x) dx$.
> > Apply product-to-sum identities:
> > $\sin x \sin 3x = \frac{\cos 2x - \cos 4x}{2}$
> > $\sin x \cos 2x = \frac{\sin 3x - \sin x}{2}$
> > $\cos x \sin 3x = \frac{\sin 4x + \sin 2x}{2}$
> > $\cos x \cos 2x = \frac{\cos 3x + \cos x}{2}$
> > Integral $= \frac{1}{2} \int (\cos 2x - \cos 4x + \sin 3x - \sin x - \sin 4x - \sin 2x - \cos 3x - \cos x) dx$
> > $= \frac{1}{2} \left[ \frac{\sin 2x}{2} - \frac{\sin 4x}{4} - \frac{\cos 3x}{3} + \cos x + \frac{\cos 4x}{4} + \frac{\cos 2x}{2} - \frac{\sin 3x}{3} - \sin x \right] + C$.

> [!sq]- Question 7
> Evaluate the following definite integral using proper trigonometric substitution:
> i. $\int_{\sqrt{3}}^{2}\frac{\sqrt{x^{2}-3}}{x}dx$
> ii. $\int\frac{x^{3}}{\sqrt{x^{2}-4}}dx$
> iii. $\int\frac{\sqrt{x^{2}-16}}{x}dx$
>
> > [!continue]- Solution
> > **i.** Solved in Problem 4.12(b). Result: $1 - \frac{\sqrt{3}\pi}{6}$.
> > 
> > **ii.** Let $x = 2\sec\theta \Rightarrow dx = 2\sec\theta\tan\theta d\theta$. $\sqrt{x^2-4} = 2\tan\theta$.
> > $\int \frac{8\sec^3\theta}{2\tan\theta} 2\sec\theta\tan\theta d\theta = 8\int \sec^4\theta d\theta = 8\int \sec^2\theta(1+\tan^2\theta) d\theta$.
> > Let $u = \tan\theta \Rightarrow du = \sec^2\theta d\theta$. $8\int(1+u^2)du = 8(u + u^3/3) = 8\tan\theta + \frac{8}{3}\tan^3\theta + C$.
> > Since $\tan\theta = \frac{\sqrt{x^2-4}}{2}$: $= 8\left(\frac{\sqrt{x^2-4}}{2}\right) + \frac{8}{3}\left(\frac{\sqrt{x^2-4}}{2}\right)^3 = 4\sqrt{x^2-4} + \frac{1}{3}(x^2-4)^{3/2} + C$.
> > 
> > **iii.** Let $x=4\sec\theta \Rightarrow dx=4\sec\theta\tan\theta d\theta$. $\sqrt{x^2-16} = 4\tan\theta$.
> > $\int \frac{4\tan\theta}{4\sec\theta} (4\sec\theta\tan\theta d\theta) = 4\int \tan^2\theta d\theta = 4\int (\sec^2\theta - 1) d\theta = 4(\tan\theta - \theta) + C$.
> > Since $\sec\theta = \frac{x}{4}$, $\tan\theta = \frac{\sqrt{x^2-16}}{4}$.
> > $= 4\left( \frac{\sqrt{x^2-16}}{4} - \sec^{-1}\left(\frac{x}{4}\right) \right) + C = \sqrt{x^2-16} - 4\sec^{-1}\left(\frac{x}{4}\right) + C$.

> [!sq]- Question 8
> Solve $\int\frac{1}{y^{2}\sqrt{y^{2}-16}}dy$.
>
> > [!continue]- Solution
> > Let $y = 4\sec\theta \Rightarrow dy = 4\sec\theta\tan\theta d\theta$. $\sqrt{y^2-16} = 4\tan\theta$.
> > $\int \frac{4\sec\theta\tan\theta}{(16\sec^2\theta)(4\tan\theta)} d\theta = \frac{1}{16} \int \frac{1}{\sec\theta} d\theta = \frac{1}{16} \int \cos\theta d\theta = \frac{1}{16}\sin\theta + C$.
> > From $y = 4\sec\theta$, we have $\cos\theta = \frac{4}{y}$, and $\sin\theta = \frac{\sqrt{y^2-16}}{y}$.
> > $= \frac{\sqrt{y^2-16}}{16y} + C$.

> [!sq]- Question 9
> Evaluate $\int\sqrt{2+x^{2}}dx$.
>
> > [!continue]- Solution
> > Let $x = \sqrt{2}\tan\theta \Rightarrow dx = \sqrt{2}\sec^2\theta d\theta$.
> > $\int \sqrt{2+2\tan^2\theta} \sqrt{2}\sec^2\theta d\theta = \int \sqrt{2}\sec\theta \cdot \sqrt{2}\sec^2\theta d\theta = 2\int \sec^3\theta d\theta$.
> > We know $\int \sec^3\theta d\theta = \frac{1}{2}(\sec\theta\tan\theta + \ln|\sec\theta+\tan\theta|)$.
> > $= \sec\theta\tan\theta + \ln|\sec\theta+\tan\theta| + C$.
> > Convert back using $\tan\theta = \frac{x}{\sqrt{2}}$ and $\sec\theta = \frac{\sqrt{x^2+2}}{\sqrt{2}}$:
> > $= \left(\frac{\sqrt{x^2+2}}{\sqrt{2}}\right)\left(\frac{x}{\sqrt{2}}\right) + \ln\left| \frac{\sqrt{x^2+2}}{\sqrt{2}} + \frac{x}{\sqrt{2}} \right| + C = \frac{x\sqrt{x^2+2}}{2} + \ln\left| \frac{x+\sqrt{x^2+2}}{\sqrt{2}} \right| + C$.

> [!sq]- Question 10
> Find:
> i. $\int \sin 3x \cos x dx$
> ii. $\int_{0}^{\frac{\pi}{6}}\sin 2x \cos 3x dx$
>
> > [!continue]- Solution
> > **i.** $\int \sin 3x \cos x dx = \frac{1}{2}\int (\sin 4x + \sin 2x) dx = -\frac{\cos 4x}{8} - \frac{\cos 2x}{4} + C$.
> > 
> > **ii.** $\int_{0}^{\frac{\pi}{6}} \sin 2x \cos 3x dx = \frac{1}{2}\int_{0}^{\frac{\pi}{6}} (\sin 5x + \sin(-x)) dx = \frac{1}{2}\int_{0}^{\frac{\pi}{6}} (\sin 5x - \sin x) dx$
> > $= \frac{1}{2}\left[ -\frac{\cos 5x}{5} + \cos x \right]_{0}^{\frac{\pi}{6}} = \frac{1}{2}\left( (-\frac{\cos(5\pi/6)}{5} + \cos(\pi/6)) - (-\frac{1}{5} + 1) \right)$
> > $= \frac{1}{2}\left( (-\frac{-\sqrt{3}/2}{5} + \frac{\sqrt{3}}{2}) - \frac{4}{5} \right) = \frac{1}{2}\left( \frac{\sqrt{3}}{10} + \frac{5\sqrt{3}}{10} - \frac{8}{10} \right) = \frac{6\sqrt{3}-8}{20} = \frac{3\sqrt{3}-4}{10}$.

> [!sq]- Question 11
> Solve:
> i. $\int \ln(x^{2}+2)dx$
> ii. $\int x^{3}e^{x^{2}}dx$
>
> > [!continue]- Solution
> > **i. $\int \ln(x^{2}+2)dx$**
> > By parts: $u = \ln(x^2+2) \Rightarrow du = \frac{2x}{x^2+2}dx$, $dv = dx \Rightarrow v = x$.
> > $x\ln(x^2+2) - \int \frac{2x^2}{x^2+2} dx = x\ln(x^2+2) - 2\int \left(1 - \frac{2}{x^2+2}\right) dx$
> > $= x\ln(x^2+2) - 2x + 4\int \frac{1}{x^2+(\sqrt{2})^2} dx = x\ln(x^2+2) - 2x + \frac{4}{\sqrt{2}}\tan^{-1}\left(\frac{x}{\sqrt{2}}\right) + C$
> > $= x\ln(x^2+2) - 2x + 2\sqrt{2}\tan^{-1}\left(\frac{x}{\sqrt{2}}\right) + C$.
> > 
> > **ii. $\int x^{3}e^{x^{2}}dx$**
> > Let $w = x^2 \Rightarrow dw = 2xdx \Rightarrow xdx = \frac{dw}{2}$.
> > $\int x^2 e^{x^2} xdx = \int w e^w \frac{dw}{2} = \frac{1}{2}\int w e^w dw$.
> > By parts: $u = w \Rightarrow du = dw$, $dv = e^w dw \Rightarrow v = e^w$.
> > $\frac{1}{2} (w e^w - \int e^w dw) = \frac{1}{2}(w e^w - e^w) + C = \frac{1}{2}e^{x^2}(x^2 - 1) + C$.

