$$\underline{\Huge\text{Normal Distribution}}$$
# 5.0 INTRODUCTION 
In this section, we will focus on the distributions associated with continuous random variable: 
![[Pasted image 20260216171223.png]]

# 5.1 CONTINUOUS UNIFORM DISTRIBUTIONS 
A continuous random variable X is said to have a uniform distribution on interval $[a,b]$ if its density function $f(x)$ has a constant value on the interval and zero elsewhere.  The graph of $y=f(x)$ is given as below which the area under $f(x)$ must be 1. 

![[Pasted image 20260216171234.png]]

In general, the probability density function of uniform distribution on interval, $[a,b]$ is defined by: 
> [!formula] Formula
> $f(x)=\begin{cases}\frac{1}{b-a}&,&a\le x\le b\\ 0&,&elsewhere\end{cases}$ 

If X is a continuous random variable with a uniform distribution, we write the distribution as where a and b are the constant representing the minimum and maximum values of the random variable. 

Then, the probability on the interval $[a,b]$ can be found by: 
> [!formula] Formula
> $P(c\le X\le d)=\int_{c}^{d}f(x)dx=\int_{c}^{d}\frac{1}{b-a}dx=\frac{d-c}{b-a}$  *(Note: Corrected typo from source $\frac{1}{b-c}$ to $\frac{1}{b-a}$)*

> [!example]- Example 5.1 
> X is a uniform distributed continuous random variable such that $X\sim R(3,8)$. Find: 
> a) the probability density function of X, $f(x)$, 
> b) $P(3.5\le X\le7)$. 
> c) $P(X>5)$. 
>
> > [!continue]- Solution 
> > a) $f(x)=\begin{cases}\frac{1}{5}&,&3\le x\le8\\ 0&,&elsewhere\end{cases}$ 
> > b) $P(3.5\le X\le7)=\int_{3.5}^{7}\frac{1}{8-3}dx=\frac{7-3.5}{5}=0.7.$ 
> > c) $P(X>5)=\int_{5}^{8}\frac{1}{8-3}dx=\frac{8-5}{5}=0.6.$ 

## 5.1.1 Expected Value and Variance 
Suppose X is a continuous uniform random variable, then the 
i. Expectation, $E(X)=\sum xP(X=x)=\frac{A+B}{2}$ 
ii. Variance, $Var(X)=E(X^{2})-[E(X)]^{2}=\frac{(B-A+1)^{2}-1}{12}$  
> [!tip]- Textbook Factual error: The variance formula provided in the text $\frac{(B-A+1)^{2}-1}{12}$ is for a discrete uniform distribution. The correct formula for a continuous uniform distribution is $\frac{(b-a)^2}{12}$. Example 5.2 below correctly utilizes the continuous formula.

> [!example]- Example 5.2 
> If $X\sim R(2,5)$, write down the probability density function of X. Then, find: 
> a) $E(X)$. 
> b) $Var(X)$. 
>
> > [!continue]- Solution 
> > a) $E(X)=\frac{2+5}{2}=\frac{7}{2}.$ 
> > b) $Var(X)=\frac{(5-2)^{2}}{12}=\frac{3}{4}.$ 

> [!example]- Example 5.3 
> X is a uniformly distributed continuous random variable such that $X\sim R(-1.3,2.5).$ Then, find: 
> a) the probability density function, X, $f(x)$ 
> b) $E(X)$. 
> c) $Var(2X)$ 
> d) $P(0\le X\le1)$ 
>
> > [!continue]- Solution 
> > a) $f(x)=\begin{cases}\frac{1}{3.8}=\frac{5}{19},&-1.3\le X\le2.5\\ 0&,&elsewhere\end{cases}$  *(Note: Corrected $f^{\prime}(x)$ to $f(x)$)*
> > b) $E(X)=\frac{-1.3+2.5}{2}=\frac{3}{5}$ 
> > c) $Var(X)=E(X^{2})-[E(X)]^{2}$ 
> > $=\int_{-1.3}^{2.5}x^{2}(\frac{5}{19})dx-(\frac{3}{5})^{2}=[\frac{x^{3}}{11.4}]_{-1.3}^{2.5}-\frac{9}{25}=\frac{361}{300}.$ 
> > $Var(2X)=4(\frac{361}{300})=4.8133.$ 
> > d) $P(0\le X\le1)=\int_{0}^{1}\frac{5}{19}dx=[\frac{5x}{19}]_{0}^{1}=0.2632.$ 

# 5.2 NORMAL DISTRIBUTIONS 
The normal distribution is the most important continuous probability distribution in statistics because it fits many natural phenomena.  For example, heights, blood pressure, measurement error, and IQ scores follow the normal distribution.  The normal distribution is a probability function that describes how the values of a variable are normally distributed. 

For example, the graph shown is approximately the distribution of the number of heads from 16-coin tosses.  We can see from the graph; it is a normal distribution. 

![[Pasted image 20260216171319.png]]S

A normal probability distribution is a bell-shaped curve with the following characteristics: 
a) The total area under the curve is 1. 


![[Pasted image 20260216171335.png]]



b) The curve is symmetric about the mean, $\mu$. 

![[Pasted image 20260216171416.png]]

c) The two tails of the curve extend infinitely, with the x-axis as its asymptotes. 

![[Pasted image 20260216171426.png]]

d) The function of the curve is, 
> [!formula] Formula
> $f(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{1}{2}(\frac{x-\mu}{\sigma})^{2}},$ 
> $-\infty<x<\infty$.  *(Note: Added the required negative sign in the exponent)*

The parameters of the distribution are $\mu$ and $\sigma^{2}$, where $\mu$ is the mean and $\sigma^{2}$ is the variance of the distribution. 
The distribution of X is written as $X\sim N(\mu,\sigma^{2})$ which denotes the random variables X has a normal distribution with parameters $\mu$ and $\sigma^{2}$.  The mean represents the central point of the distribution, while the variance describes the width of the distribution. 

Since $\mu$ and $\sigma^{2}$ are the parameters of the normal distribution, by given the values of two parameters, we can find the area under a normal curve for any interval.  There are a family of normal distribution curves.  Each different set of values of $\mu$ and $\sigma^{2}$, will gives a different normal curve. 

As an illustration, the three normal distribution curves below have the same mean but different standard deviations. 


![[Pasted image 20260216171455.png]]

We can interpret from the diagram above, there is more area in the tails and lower peak when the standard deviation is greater. 

As an illustration, the two normal distribution curves below have the same standard deviations but different means. 

![[Pasted image 20260216171508.png]]

We can interpret that these two curves are identical in shape but are centred at different positions. 

As this discussion reveals that the shape of normal curve depends on the values of $\mu$ and $\sigma^{2}$. 

## 5.2.1 Calculating Probabilities Using the Normal Distribution 
Once we can show that the distribution of a variable follows a normal, we use the normal distribution function to calculate probabilities about that variable. 
For calculating probabilities of continuous variables, we can use the cumulative distribution function, $F(x)$ is given by: 
> [!formula] Formula
> $F(x)=\int_{-\infty}^{x}f(x)dx=\frac{1}{\sigma\sqrt{2\pi}}\int_{-\infty}^{x}e^{-\frac{1}{2}(\frac{x-\mu}{\sigma})^{2}}dx.$  *(Note: Added the required negative sign in the exponent)*

As we can see this function is very complicated and in fact is impossible to solve directly.  However, for this calculation we will use one particular normal distribution called the Standard Normal Distribution (normal distribution of standardized values). 

# 5.3 STANDARD NORMAL DISTRIBUTIONS 
The standard normal distribution is a special case of the normal distribution.  For the standard normal distribution, the value of mean is equal to zero and the value of variance is equal to one.  The standard normal distribution is denoted by Z and called as Z scores.  The standard normal distribution is written as $Z\sim N(0,1)$ for the distribution with mean is equal to 0 and variance is equal to 1. 

## 5.3.1 Standardizing a Normal Distribution 
The procedure to convert the given normal distribution to the standard normal distribution is called standardizing a normal distribution.  The normal distribution is denoted by x and the standard normal distribution is denoted by z. 
For a normal distribution, x can be converted to a standard normal, z value by using the formula below, 
> [!formula] Formula
> $z=\frac{x-\mu}{\sigma}$ 

By replacing the value for Z in the normal probability density function, the equation gives 
> [!formula] Formula
> $f(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{1}{2}(\frac{x-\mu}{\sigma})^{2}}$ 

becomes
> [!formula] Formula
> $f(z)=\frac{1}{\sqrt{2\pi}}e^{-\frac{1}{2}z^{2}}$  *(Note: Removed $\sigma$ from denominator as $\sigma=1$ and added negative sign to exponent)*

The curve still has the same basic shape (bell-shaped) but is now symmetrical about y-axis with mean, $\mu=0$ and variance, $\sigma^{2}=1$. 

The standard normal distribution curve 

![[Pasted image 20260216171531.png]]

![[Pasted image 20260216171547.png]]


The characteristics of the tables of the standard normal distribution, $Z\sim N(0,1)$ are: 

$P(Z>a)$ is the area of the shaded region in the above diagram. 

![[Pasted image 20260216171638.png]]

Total area = 1 
$P(-\infty<Z<\infty)=1$ 

![[Pasted image 20260216171647.png]]

$P(Z>0)=P(Z<0)=0.5$ 

![[Pasted image 20260216171659.png]]

$P(Z>a)=P(Z<-a)$
![[Pasted image 20260216171754.png]]

## 5.3.2 Standard Normal Distribution Table
The standard normal tables can be used to find the area under the standard normal curve (probability). The tables give the cumulative distribution values, $P(Z>a)$. Notice that the $z-$ values given in the table are rounded to two decimal places. The first decimal place of each z - value is listed in the left column, with the second decimal place in the top row.

How to read the Z-table:
1) The column headings define the Z-score to the hundredth's place. The row headings define the Z-score to the tenth's place.
2) Each value in the table is the area between $Z=0$ and the Z-score of the given value, which represents the probability that a data point will lie within the referenced region in the standard normal distribution.

Refer to page 190. For example, if we want to find $P(Z>0.90)$, in the statistical table and go to the left column choose 0.9 row in the table and look at the top row headed to 0.00 column, so we have $P(Z>0.90)=0.1841$.

Graphically, $P(Z>0.90)$ is shown below:

![[Pasted image 20260216171810.png]]

Because there are various Z-table, it is important to pay attention to the given Z-table to know what area is being referenced.

**The following table:**

| Z | .00 | .01 | .02 | .03 | .04 | .05 | .06 | .07 | .08 | .09 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0.0 | .5000 | .4960 | .4920 | .4880 | .4840 | .4801 | .4761 | .4721 | .4681 | .4641 |
| 0.1 | .4602 | .4562 | .4522 | .4483 | .4443 | .4404 | .4364 | .4325 | .4286 | .4247 |
| 0.2 | .4207 | .4168 | .4129 | .4090 | .4052 | .4013 | .3974 | .3936 | .3897 | .3859 |
| 0.3 | .3821 | .3783 | .3745 | .3707 | .3669 | .3632 | .3594 | .3557 | .3520 | .3483 |
| 0.4 | .3446 | .3409 | .3372 | .3336 | .3300 | .3264 | .3228 | .3192 | .3156 | .3121 |
| 0.5 | .3085 | .3050 | .3015 | .2981 | .2946 | .2912 | .2877 | .2843 | .2810 | .2776 |
| 0.6 | .2743 | .2709 | .2676 | .2643 | .2611 | .2578 | .2546 | .2514 | .2483 | .2451 |
| 0.7 | .2420 | .2389 | .2358 | .2327 | .2296 | .2266 | .2236 | .2206 | .2177 | .2148 |
| 0.8 | .2119 | .2090 | .2061 | .2033 | .2005 | .1977 | .1949 | .1922 | .1894 | .1867 |
| 0.9 | .1841 | .1814 | .1788 | .1762 | .1736 | .1711 | .1685 | .1660 | .1635 | .1611 |

### For Positive Values of Z 
a) $P(Z>z)=Q(z)$ 
![[Pasted image 20260216171948.png]]

b) $P(Z>0)=0.5$ 
![[Pasted image 20260216172006.png]]

c) $P(0<Z<z)=P(Z>0)-P(Z>z)=0.5-P(Z>z)$.
![[Pasted image 20260216172020.png]]

d) $P(z_{1}<Z<z_{2})=P(Z>z_{1})-P(Z>z_{2})$.
![[Pasted image 20260216172029.png]]

e) $P(Z<z)=1-P(Z>z)$.
![[Pasted image 20260216172041.png]]

### For Negative Values of Z 
a) $P(Z<0)=P(Z>0)=0.5$.
![[Pasted image 20260216172052.png]]

b) $P(Z<-z)=P(Z>z)$.
![[Pasted image 20260216172102.png]]


c) $P(-z<Z<0)=P(0<Z<z)=P(Z>0)-P(Z>z)$.
![[Pasted image 20260216172119.png]]

d) $P(-z_{2}<Z<-z_{1})=P(z_{1}<Z<z_{2})$. 
![[Pasted image 20260216172210.png]]

e) $P(Z>-z)=1-P(Z<-z)=1-P(Z>z)$.
![[Pasted image 20260216172224.png]]

### For Positive and Negative Values of Z 
a) $P(-z_{2}<Z<z_{1})=1-P(Z<-z_{2})-P(Z>z_{1})$
$=1-P(Z>z_{2})-P(Z>z_{1})$.
![[Pasted image 20260216172235.png]]

### For Modulus of Z 
a) $P(|Z|>a)$ means $P(Z>a)$ or $P(Z<-a)=P(Z>a)+P(Z<-a)$
$=P(Z>a)+P(Z>a) = 2P(Z>a)$.
![[Pasted image 20260216172250.png]]

b) $P(|Z|<a)$ means $P(-a<Z<a)$
$P(-a<Z<a)=1-P(Z<-a)-P(Z>a)$
$=1-P(Z>a)-P(Z>a) = 1-2P(Z>a)$.
![[Pasted image 20260216172307.png]]

> [!example]- Example 5.4
> If the continuous random variable Z has a standard normal distribution, use the table to find:
> a) $P(Z>0)$ 
> b) $P(0<Z<0.14)$ 
> c) $P(0<Z<2.14)$ 
> d) $P(Z=2.14)$ 
> e) $P(Z<0)$ 
> f) $P(-0.14<Z<0)$ 
> g) $P(-2.14<Z<0)$ 
> h) $P(Z=-2.14)$ 
>
> > [!continue]- Solution
> > a) $P(Z>0)=0.5$.
> > b) $P(0<Z<0.14)=P(Z>0)-P(Z>0.14)$
> > $=0.5-0.4443=0.0557$.
> > c) $P(0<Z<2.14)=P(Z>0)-P(Z>2.14)$
> > $=0.5-0.0162=0.4838$.
> > d) $P(Z=2.14)=0$.
> > e) $P(Z<0)=0.5$.
> > f) $P(-0.14<Z<0)=P(0<Z<0.14)$
> > $=P(Z>0)-P(Z>0.14)$
> > $=0.5-0.4443=0.0557$.
> > g) $P(-2.14<Z<0)=P(0<Z<2.14)$
> > $=P(Z>0)-P(Z>2.14)$
> > $=0.5-0.0162=0.4838$.
> > h) $P(Z=-2.14)=0$.

> [!example]- Example 5.5
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> a) $P(Z>1.83)$.
> b) $P(Z<-0.64)$.
>
> > [!continue]- Solution
> > a) $P(Z>1.83)=0.0336$.
> > b) $P(Z<-0.64)=P(Z>0.64)=0.2611$.

> [!example]- Example 5.6
> If the continuous random variable Z has a standard normal distribution, use tables to find
> $P(1.19<Z<2.12)$.
>
> > [!continue]- Solution
> > $P(1.19<Z<2.12)=P(Z>1.19)-P(Z>2.12)$
> > $=0.117-0.017=0.1$.

> [!example]- Example 5.7
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> $P(-2.12<Z<-1.19)$.
>
> > [!continue]- Solution
> > $P(-2.12<Z<-1.19)=P(1.19<Z<2.12)$
> > $=P(Z>1.19)-P(Z>2.12)$
> > $=0.117-0.017=0.1$.

> [!example]- Example 5.8
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> a) $P(-1.56<Z<2.13)$.
> b) $P(|z|<2.13)$.
>
> > [!continue]- Solution
> > a) $P(-1.56<Z<2.13)=1-P(Z>1.56)-P(Z>2.13)$
> > $=1-0.0594-0.0166=0.9240$.
> > 
> > ![[Pasted image 20260216172341.png]]
> > b) $P(|Z|<2.13)=P(-2.13<Z<2.13)$
> > $=1-2P(Z>2.13)$
> > $=1-2(0.0228)=0.9544$.

> [!example]- Example 5.9
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> $P(Z>-0.75)$.
>
> > [!continue]- Solution
> > $P(Z>-0.75)=1-P(Z<-0.75)$
> > $=1-P(Z>0.75)$
> > $=1-0.2266=0.7734$.

> [!example]- Example 5.10
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> $P(Z<0.75)$.
>
> > [!continue]- Solution
> > $P(Z<0.75)=1-P(Z>0.75)=1-0.2266=0.7734$.

> [!sq]- Problem 5.1
> If the continuous random variable Z has a standard normal distribution, use tables to find:
> a) $P(Z<1.75)$.
> b) $P(Z<-1.85)$.
> c) $P(0<Z<0.62)$.
> d) $P(-2.3<Z<0)$.
> e) $P(0.94<Z<2.70)$.
> f) $P(-0.36<Z<3.20)$.
> g) $P(Z>-0.49)$.
>
> > [!continue]- Solution
> > **a) $P(Z<1.75)$:**
> > $P(Z<1.75) = 1 - P(Z>1.75) = 1 - 0.0401 = 0.9599$.
> > 
> > **b) $P(Z<-1.85)$:**
> > $P(Z<-1.85) = P(Z>1.85) = 0.0322$.
> > 
> > **c) $P(0<Z<0.62)$:**
> > $P(0<Z<0.62) = P(Z>0) - P(Z>0.62) = 0.5 - 0.2676 = 0.2324$.
> > 
> > **d) $P(-2.3<Z<0)$:**
> > $P(-2.3<Z<0) = P(0<Z<2.30) = P(Z>0) - P(Z>2.30) = 0.5 - 0.0107 = 0.4893$.
> > 
> > **e) $P(0.94<Z<2.70)$:**
> > $P(0.94<Z<2.70) = P(Z>0.94) - P(Z>2.70) = 0.1736 - 0.0035 = 0.1701$.
> > 
> > **f) $P(-0.36<Z<3.20)$:**
> > $P(-0.36<Z<3.20) = 1 - P(Z>0.36) - P(Z>3.20) = 1 - 0.3594 - 0.0007 = 0.6399$.
> > 
> > **g) $P(Z>-0.49)$:**
> > $P(Z>-0.49) = 1 - P(Z<-0.49) = 1 - P(Z>0.49) = 1 - 0.3121 = 0.6879$.

### 5.3.3 Finding Z-Score When Given Area Under a Normal Curve
A z-score is a measure of position that indicates the number of standard deviations a data value lies from the mean. It is the horizontal scale of a standard normal distribution. We will look at reversing the use of the z-table. Instead of finding an area given a z-score, we are going to work backwards and find a z-score given area.

> [!formula] Formula
> $P(Z>Z_{\alpha})=\alpha$


![[Pasted image 20260216172504.png]]

For instance, find $P(Z>Z_{\alpha})=0.30$. Refer the table, find $\alpha=0.30$. When $\alpha=0.30$, $Z_{\alpha}=0.5244$. Thus, $P(Z>0.5244)=0.30$.

> [!example]- Example 5.11
> The variable Z has a standard normal distribution $Z\sim N(0,1)$. Using the standard normal distribution table, find the value of $Z_{\alpha}$ if,
> a) $P(Z>Z_{\alpha})=0.1230$.
> b) $P(Z<Z_{\alpha})=0.7580$.
> c) $P(Z>Z_{\alpha})=0.8485$.
> d) $P(Z<Z_{\alpha})=0.1922$.
> e) $P(0<Z<Z_{\alpha})=0.2257$.
> f) $P(-Z_{\alpha}<Z<0)=0.33$.
> g) $P(-Z_{\alpha}<Z<Z_{\alpha})=0.8244.$
>
> > [!continue]- Solution
> > a) From the standard normal distribution table,
> > $P(Z>1.16)=0.1230$
> > $Z_{\alpha}=1.16.$
> > 
> > ![[Pasted image 20260216172518.png]]
> > 
> > b) $P(Z<Z_{\alpha})=0.7580$
> > $P(Z>Z_{\alpha})=1-0.758$
> > $P(Z>0.7)=0.242$.
> > From the standard normal distribution table,
> > $P(Z>0.7)=0.242$
> > $Z_{\alpha}=0.7$
> > 
> > ![[Pasted image 20260216172534.png]]
> > 
> > c) $P(Z>Z_{\alpha})=0.8485$
> > $P(Z<Z_{\alpha})=1-P(Z>Z_{\alpha})$
> > $P(Z<Z_{\alpha})=1-0.8485=0.1515$
> > $P(Z>-Z_{\alpha})=0.1515$
> > From the standard normal distribution table,
> > $P(Z>1.03)=0.1515$
> > $-Z_{\alpha}=1.03$
> > $Z_{\alpha}=-1.03$.
> > 
> > ![[Pasted image 20260216172557.png]]
> > 
> > d) $P(Z<Z_{\alpha})=0.1922$
> > $P(Z>-Z_{\alpha})=0.1922$.
> > From the standard normal distribution table,
> > $P(Z>0.87)=0.1922$
> > $-Z_{\alpha}=0.87$
> > $Z_{\alpha}=-0.87.$
> > 
> > ![[Pasted image 20260216172615.png]]
> > 
> > e) $P(0<Z<Z_{\alpha})=0.2257$
> > $P(Z>0)-P(Z>Z_{\alpha})=0.2257$
> > $0.5-P(Z>Z_{\alpha})=0.2257$
> > $P(Z>Z_{\alpha})=0.2743$.
> > From the standard normal distribution table,
> > $P(Z>Z_{\alpha})=0.2743$
> > $Z_{\alpha}=0.6$.
> > 
> > ![[Pasted image 20260216172631.png]]
> > 
> > f) $P(-Z_{\alpha}<Z<0)=0.33$
> > $1-P(Z<-Z_{\alpha})-P(Z>0)=0.33$
> > $1-P(Z<-Z_{\alpha})-0.5=0.33$
> > $P(Z>Z_{\alpha})=0.17$.
> > From the standard normal distribution table,
> > $P(Z>Z_{\alpha})=0.17$
> > $Z_{\alpha}=0.95$.
> > 
> > ![[Pasted image 20260216172646.png]]
> > 
> > g) $P(-Z_{\alpha}<Z<Z_{\alpha})=0.8244$
> > $1-P(Z<-Z_{\alpha})-P(Z>Z_{\alpha})=0.8244$
> > $1-2P(Z>Z_{\alpha})=0.8244$
> > $P(Z>Z_{\alpha})=\frac{1-0.8244}{2}=0.0878.$
> > From the standard normal distribution table,
> > $P(Z>1.35)=0.0878$
> > $Z_{\alpha}=1.35$.
> > 
> > ![[Pasted image 20260216172703.png]]

> [!sq]- Problem 5.2
> Find $Z_{\alpha}$ if given the area under normal curve:
> a) $P(Z_{\alpha}<Z<0)=0.4175$.
> b) $P(Z<Z_{\alpha})=0.0188$.
> c) $P(Z>Z_{\alpha})=0.8962$.
> d) $P(Z>Z_{\alpha})=0.033$.
> e) $P(Z<Z_{\alpha})=0.068$.
> f) $P(Z>Z_{\alpha})=0.880$.
>
> > [!continue]- Solution
> > **a)** $P(Z_{\alpha}<Z<0) = 0.4175 \Rightarrow P(0<Z<-Z_{\alpha}) = 0.4175 \Rightarrow 0.5 - P(Z>-Z_{\alpha}) = 0.4175 \Rightarrow P(Z>-Z_{\alpha}) = 0.0825$. 
> > From table, $-Z_{\alpha} \approx 1.39 \Rightarrow Z_{\alpha} = -1.39$.
> > 
> > **b)** $P(Z<Z_{\alpha}) = 0.0188 \Rightarrow P(Z>-Z_{\alpha}) = 0.0188$.
> > From table, $-Z_{\alpha} = 2.08 \Rightarrow Z_{\alpha} = -2.08$.
> > 
> > **c)** $P(Z>Z_{\alpha}) = 0.8962 \Rightarrow 1 - P(Z<-Z_{\alpha}) = 0.8962 \Rightarrow P(Z<-Z_{\alpha}) = 0.1038 \Rightarrow P(Z>-Z_{\alpha}) = 0.1038$.
> > From table, $-Z_{\alpha} = 1.26 \Rightarrow Z_{\alpha} = -1.26$.
> > 
> > **d)** $P(Z>Z_{\alpha}) = 0.033$.
> > From table, $Z_{\alpha} \approx 1.84$.
> > 
> > **e)** $P(Z<Z_{\alpha}) = 0.068 \Rightarrow P(Z>-Z_{\alpha}) = 0.068$.
> > From table, $-Z_{\alpha} \approx 1.49 \Rightarrow Z_{\alpha} = -1.49$.
> > 
> > **f)** $P(Z>Z_{\alpha}) = 0.880 \Rightarrow 1 - P(Z<-Z_{\alpha}) = 0.880 \Rightarrow P(Z<-Z_{\alpha}) = 0.120 \Rightarrow P(Z>-Z_{\alpha}) = 0.120$.
> > From table, $-Z_{\alpha} \approx 1.175 \Rightarrow Z_{\alpha} = -1.175$.

> [!example]- Example 5.12
> Find the value of $Z_{\alpha}$ if
> a) 98.87% of the area under the distribution curve lies to the right of it.
> b) 70% of the area under the distribution curve lies to the left of it.
>
> > [!continue]- Solution
> > a) $P(Z>Z_{\alpha})=0.9887$
> > $1-P(Z<Z_{\alpha})=0.9887$
> > $P(Z<Z_{\alpha})=0.0113$
> > $P(Z>-Z_{\alpha})=0.0113.$
> > From the standard normal distribution table,
> > $P(Z>-Z_{\alpha})=0.0113$
> > $-Z_{\alpha}=2.2904$
> > $Z_{\alpha}=-2.2904$
> > 
> > ![[Pasted image 20260216172724.png]]
> > 
> > b) $P(Z<Z_{\alpha})=0.70$
> > $1-P(Z>Z_{\alpha})=0.70$
> > $P(Z>Z_{\alpha})=0.30$
> > From the standard normal distribution table,
> > $P(Z>0.5244)=0.30$
> > $Z_{\alpha}=0.5244.$
> > 
> > ![[Pasted image 20260216172740.png]]

> [!example]- Example 5.13
> Find the two values of $Z_{\alpha}$, one positive and one negative, so that the areas in the two tails total 10%.
>
> > [!continue]- Solution
> > For the total area 0.10, there will be area 0.05 for each tail.
> > For positive value, $P(Z>Z_{\alpha})=0.05$. Thus, $Z_{\alpha}=1.6449$.
> > For negative value, $P(Z<Z_{\alpha})=0.05$. We know that, $P(Z<Z_{\alpha})=P(Z>-Z_{\alpha})=0.05$.
> > Thus, $Z_{\alpha}=-1.6449$.

> [!example]- Example 5.14
> Given $X\sim N(40,25)$, find the value of k if:
> a) $P(X>k)=0.1251$.
> b) $P(X<k)=0.7823$.
> c) $P(k<X<40)=0.3023$.
>
> > [!continue]- Solution
> > a) $P(X>k)=0.1251$
> > $P(Z>\frac{k-40}{\sqrt{25}})=0.1251$
> > From the standard normal distribution table,
> > $P(Z>1.15)=0.1251$
> > $\frac{k-40}{\sqrt{25}}=1.15$
> > $k=45.75$
> > 
> > ![[Pasted image 20260216172826.png]]
> > 
> > b) $P(X<k)=0.7823$
> > $P(Z>\frac{k-40}{\sqrt{25}})=1-0.7823$
> > $=0.2177$
> > From the standard normal distribution table,
> > $P(Z>0.78)=0.2177$
> > $\frac{k-40}{\sqrt{25}}=0.78$
> > $k=43.9$
> > 
> > ![[Pasted image 20260216172845.png]]
> > 
> > c) $P(-k<X<40)=0.3023$
> > $P(-\frac{k-40}{\sqrt{25}}<Z<\frac{40-40}{\sqrt{25}})=0.3023$
> > $P(-\frac{k-40}{\sqrt{25}}<Z<0)=0.3023$
> > $1-P(Z<-\frac{k-40}{\sqrt{25}})-P(Z>0)=0.3023$
> > $1-P(Z<-\frac{k-40}{\sqrt{25}})-0.5=0.3023$
> > $P(Z<-\frac{k-40}{\sqrt{25}})=0.1977$
> > $P(Z>-\frac{k-40}{\sqrt{25}})=0.1977$
> > From the standard normal distribution table,
> > $P(Z>0.85)=0.1977$
> > $-(\frac{k-40}{\sqrt{25}})=0.85$
> > $k=35.75$
> > 
> > ![[Pasted image 20260216172859.png]]

> [!sq]- Problem 5.3
> Given $X\sim N(40,25)$, find the value of k if:
> a) $P(X>k)=0.7673$.
> b) $P(X<k)=0.2611$.
> c) $P(40<X<k)=0.2995$.
> d) $P(-k<X<40)=0.3023$.
> e) $P(-k<X<k)=0.8968$.
>
> > [!continue]- Solution
> > $X \sim N(40, 25)$ implies $\mu=40$ and $\sigma=5$.
> > 
> > **a)** $P(X>k) = 0.7673 \Rightarrow P(Z > \frac{k-40}{5}) = 0.7673 \Rightarrow 1 - P(Z < -\frac{k-40}{5}) = 0.7673 \Rightarrow P(Z > \frac{40-k}{5}) = 0.2327$.
> > From table, $\frac{40-k}{5} = 0.73 \Rightarrow 40-k = 3.65 \Rightarrow k = 36.35$.
> > 
> > **b)** $P(X<k) = 0.2611 \Rightarrow P(Z < \frac{k-40}{5}) = 0.2611 \Rightarrow P(Z > \frac{40-k}{5}) = 0.2611$.
> > From table, $\frac{40-k}{5} = 0.64 \Rightarrow 40-k = 3.2 \Rightarrow k = 36.8$.
> > 
> > **c)** $P(40<X<k) = 0.2995 \Rightarrow P(0 < Z < \frac{k-40}{5}) = 0.2995 \Rightarrow 0.5 - P(Z > \frac{k-40}{5}) = 0.2995 \Rightarrow P(Z > \frac{k-40}{5}) = 0.2005$.
> > From table, $\frac{k-40}{5} = 0.84 \Rightarrow k-40 = 4.2 \Rightarrow k = 44.2$.
> > 
> > **d)** (Assuming $P(k<X<40)=0.3023$ based on Example 5.14c):
> > $P(k<X<40) = 0.3023 \Rightarrow P(\frac{k-40}{5} < Z < 0) = 0.3023 \Rightarrow P(0 < Z < \frac{40-k}{5}) = 0.3023 \Rightarrow 0.5 - P(Z > \frac{40-k}{5}) = 0.3023 \Rightarrow P(Z > \frac{40-k}{5}) = 0.1977$.
> > From table, $\frac{40-k}{5} = 0.85 \Rightarrow 40-k = 4.25 \Rightarrow k = 35.75$.
> > 
> > **e)** (Assuming $P(|X-40|<k) = 0.8968$, or $P(40-k<X<40+k)=0.8968$):
> > $P(-k/5 < Z < k/5) = 0.8968 \Rightarrow 1 - 2P(Z > k/5) = 0.8968 \Rightarrow 2P(Z > k/5) = 0.1032 \Rightarrow P(Z > k/5) = 0.0516$.
> > From table, $k/5 \approx 1.63 \Rightarrow k = 8.15$.

### 5.3.4 Standard Normal Distribution Probabilities
When we have normal distribution, $X\sim N(\mu,\sigma^{2})$, the probabilities involving X are computed by standardizing. And, the standardized variable is $\frac{x-\mu}{\sigma}$.

A value from any normal distribution with mean, $\mu$ and standard deviation, $\sigma$ can be transformed into its corresponding value on a standard normal distribution using the following formula, $Z=\frac{x-\mu}{\sigma}$.

Z is the value on the standard normal distribution, X is the value on the original distribution, $\mu$ is the mean of the original distribution, and $\sigma$ is the standard deviation of the original distribution.

For example, what portion of a normal distribution with a mean of 50 and a standard deviation of 10 is below 26?
Applying the formula, we obtain $Z=\frac{x-\mu}{\sigma}=\frac{26-50}{10}=-2.4$.

The graph of Z can be illustrate as below. Then, look up in statistical table, $P(Z<-2.4)=P(Z>2.4)$ and we get that the area $P(Z>2.4)=0.0082$ or 0.82%.

![[Pasted image 20260216172928.png]]

> [!example]- Example 5.15
> Given $X\sim N(2,4)$, find $P(-3<X<3)$.
>
> > [!continue]- Solution
> > From $X\sim N(2,4)$, we have $\mu$ is 2 and $\sigma^{2}$ is 4. By standardizing, $Z\sim N(0,1)$. we use the formula, $Z=\frac{x-\mu}{\sigma}$
> > $P(-3<X<3)=P(\frac{-3-2}{2}<Z<\frac{3-2}{2})=P(-2.5<Z<0.5)$
> > $=1-P(Z>2.5)-P(Z>0.5)$
> > $=1-0.0062-0.3085$
> > $=0.6853$

> [!sq]- Problem 5.4
> Let X be a continuous random variable that is normally distributed with mean 25 and standard deviation 4. Find:
> a) $P(25<X<32)$
> b) $P(X<35)$
> c) $P(X>15)$
>
> > [!continue]- Solution
> > $X \sim N(25, 4^2)$. $\mu = 25$, $\sigma = 4$.
> > 
> > **a) $P(25<X<32)$:**
> > $P(25<X<32) = P(\frac{25-25}{4} < Z < \frac{32-25}{4}) = P(0 < Z < 1.75)$
> > $= 0.5 - P(Z>1.75) = 0.5 - 0.0401 = 0.4599$.
> > 
> > **b) $P(X<35)$:**
> > $P(X<35) = P(Z < \frac{35-25}{4}) = P(Z < 2.5) = 1 - P(Z>2.5) = 1 - 0.0062 = 0.9938$.
> > 
> > **c) $P(X>15)$:**
> > $P(X>15) = P(Z > \frac{15-25}{4}) = P(Z > -2.5) = 1 - P(Z>2.5) = 1 - 0.0062 = 0.9938$.

> [!example]- Example 5.16
> Given that the heights of a population with where $\mu=170cm$ and $\sigma=10cm$ are distributed normally. What is the probability that the height of a randomly selected person
> a) is greater than 185cm,
> b) lies between 175cm and 185cm.
>
> > [!continue]- Solution
> > Let X be the height and $X\sim N(170,10^{2})$. Then, X is standardized to $Z\sim N(0,1)$.
> > a) $P(X>185)=P(Z>\frac{185-170}{10})=P(Z>1.5)=0.0668.$
> > 
> > b) $P(175<X<185)=P(\frac{175-170}{10}<Z<\frac{185-170}{10})=P(0.5<Z<1.5)$
> > $=P(Z>0.5)-P(Z>1.5)$
> > $=0.3085-0.0668$
> > $=0.2417.$

> [!example]- Example 5.17
> A machine produces components whose thickness is normally distributed with a mean of 0.4cm and a standard deviation of 0.01cm. Components are rejected if the thickness is outside the range of 0.38cm to 0.41cm.
> a) What percentage of components are rejected?
> b) Show that the percentage rejected will be reduced if the mean is changed to 0.395cm.
>
> > [!continue]- Solution
> > Let X be the thickness of the component and $X\sim N(0.4,0.01^{2})$. Then, X is standardized to $Z\sim N(0,1)$.
> > 
> > a) $P(0.38<X<0.41)=P(\frac{0.38-0.40}{0.01}<Z<\frac{0.41-0.40}{0.01})=P(-2<Z<1)$
> > $=1-P(-2<Z<1)$  *(Note: This line from the source is confusingly written, it intends to calculate the complement for rejection)*
> > $=1-P(Z>2)-P(Z>1)$
> > $=1-0.0228-0.1587$
> > $=0.8185$.
> > The percentage of component rejected,
> > $=100\%-81.85\%=18.15\%$ *(Note: Corrected from 18.1% in source text)*.
> > 
> > b) $\mu=0.395$
> > $P(\frac{0.38-0.395}{0.01}<Z<\frac{0.41-0.395}{0.01})=P(-1.5<Z<1.5)$ *(Note: Corrected $0.39$ to $0.38$ based on context)*
> > $=1-P(Z<-1.5)-P(Z>1.5)$
> > $=1-P(Z>1.5)-P(Z>1.5)$
> > $=1-2P(Z>1.5)=1-2(0.0668)=0.8664$ *(Note: Corrected from $1-0.1336=0.8664$ based on table values, $P(Z>1.5)=0.0668$)*.
> > The percentage of component rejected,
> > $=100\%-86.64\%$
> > $=13.36\%$.
> > Therefore, the percentage of components rejected is reduced.

> [!example]- Example 5.18
> Guest at a large hotel stay for an average of 8 days with a standard deviation of 2 days. Among 100 guests, how many can be expected to stay? Assuming that the length of stay is normally distributed.
> a) less than 7 days, 
> b) more than 14 days, 
> c) between 7 and 14 days.
> 
> > [!tip]- Textbook Factual error: In part b, the question asks for "more than 14 days", but the solution in the text computes $P(X<14)$. However, the standard normal table value used ($0.00135$) actually corresponds to $P(Z>3)$, meaning the final result correctly evaluates "more than 14 days" despite the typo.
>
> > [!continue]- Solution
> > Let X be the number of days a guest stayed in the hotel, $X\sim N(8,2^{2})$. Then, X is standardized to $Z\sim N(0,1)$.
> > a) $P(X<7)=P(Z<\frac{7-8}{2})=P(Z<-0.5)=P(Z>0.5)=0.3085$
> > $\mu=E(X) = np = 100(0.3085)=30.85\approx31$
> > 
> > b) $P(X>14)=P(Z>\frac{14-8}{2})=P(Z>3)=0.00135.$ *(Note: Corrected typo $P(X<14)$ from source)*
> > $\mu=E(X) = np = 100(0.00135)=0.135\approx0$
> > 
> > c) $P(7<X<14)=P(\frac{7-8}{2}<Z<\frac{14-8}{2})=P(-0.5<Z<3)$
> > $=1-P(Z<-0.5)-P(Z>3)$
> > $=1-P(Z>0.5)-P(Z>3)$
> > $=1-0.3085-0.00135=0.69015 \approx 0.6902.$
> > $\mu=E(X) = np = 100(0.6902)=69.02\approx69$

> [!example]- Example 5.19
> It has been observed that the annual rainfall in a town follows a normal distribution due to the varying patterns of depressions and anti-cyclones. The mean annual rainfall is 65cm, and historical records indicate that 15% of the years receive more than 85cm of rainfall.
> a) Determine the standard deviation of the annual rainfall.
> b) What percentage of the years will experience rainfall below 50cm?
> 
> > [!tip]- Textbook Factual error: The text sets up the equation as $P(X<85) = 0.15$ but the problem states "more than 85cm". The correct setup should be $P(X>85) = 0.15$. The mathematical steps provided in the source evaluate the right tail regardless.
>
> > [!continue]- Solution
> > Let X represent the annual rainfall, $X\sim N(65,\sigma^{2})$. Then, X is standardized to $Z\sim N(0,1)$.
> > a) $P(X>85)=P(Z>\frac{85-65}{\sigma})=0.15$
> > For the right tail of 0.15, $Z=1.04$.
> > Thus, $\frac{85-65}{\sigma}=1.04$
> > $\sigma=19.23 \approx 19.2$
> > 
> > b) $X\sim N(65,19.2^{2})$.
> > $P(X<50)=P(Z<\frac{50-65}{19.2})$ *(Note: Corrected from 19.5 in source)*
> > $=P(Z<-0.78)$
> > $=P(Z>0.78)$
> > $=0.2177.$
> > Thus, 21.77% of years have a rainfall less than 50cm.

> [!example]- Example 5.20
> In a company, the wages of a certain grade of staff are normally distributed with a standard deviation of RM 400. If 20.05% of staff earn less than RM 300 a week,
> a) What is the average wage?
> b) What percentage of staff earns more than RM 500 a week?
>
> > [!continue]- Solution
> > Let X represent the wages of staff and $X\sim N(\mu,400^{2}).$ Then, X is standardized to $Z\sim N(0,1)$.
> > a) $P(X<300)=P(Z<\frac{300-\mu}{400})=0.2005.$
> > From the standard normal distribution table,
> > $P(Z>0.84)=0.2005$. Therefore, $P(Z<-0.84)=0.2005$.
> > $\frac{300-\mu}{400}=-0.84$
> > $\mu=636$
> > 
> > b) $P(X>500)=P(Z>\frac{500-636}{400})$
> > $=P(Z>-0.34)$
> > $=1-P(Z<-0.34)$
> > $=1-P(Z>0.34)$
> > $=1-0.3669=0.6331$
> > Thus, percentage of staff earning more than RM $500=63.31\%$.

> [!example]- Example 5.21
> The height of adult males is normally distributed with a mean of 172cm and a standard deviation of 8cm. If 99% of adult males taller than a specific height, what is this height?
>
> > [!continue]- Solution
> > Let h be the minimum value of the height of these adult males.
> > $P(X>h)=P(Z>\frac{h-172}{8})=0.99$
> > From the standard normal distribution table,
> > $P(Z>2.33)=P(Z<-2.33)=0.01$. Therefore, $P(Z>-2.33)=0.99$.
> > $\frac{h-172}{8}=-2.33$
> > $h=153.36 \approx 153.4$. Thus, 99% of adult males exceed the height of 153.4cm.

> [!sq]- Problem 5.5
> The average annual salary for all U.S. teachers is RM47 750. Assume that the distribution is normal and the standard deviation is RM5 680. Find the probability that a randomly selected teacher earns
> a) Between RM35 000 and RM45 000 a year.
> b) More than RM40 000 a year.
>
> > [!continue]- Solution
> > Let X be the annual salary. $X \sim N(47750, 5680^2)$.
> > 
> > **a) Between RM35 000 and RM45 000:**
> > $P(35000 < X < 45000) = P(\frac{35000-47750}{5680} < Z < \frac{45000-47750}{5680})$
> > $= P(-2.24 < Z < -0.48)$
> > $= P(Z > 0.48) - P(Z > 2.24)$
> > $= 0.3156 - 0.0125 = 0.3031$.
> > 
> > **b) More than RM40 000:**
> > $P(X > 40000) = P(Z > \frac{40000-47750}{5680}) = P(Z > -1.36)$
> > $= 1 - P(Z > 1.36) = 1 - 0.0869 = 0.9131$.

> [!sq]- Problem 5.6
> Given $X\sim N(37.4,20.25)$, find:
> i. $P(X<45)$
> ii. $P(30<X<40)$.
>
> > [!continue]- Solution
> > $X \sim N(37.4, 20.25)$ implies $\mu = 37.4$ and $\sigma = \sqrt{20.25} = 4.5$.
> > 
> > **i. $P(X<45)$:**
> > $P(X < 45) = P(Z < \frac{45-37.4}{4.5}) = P(Z < 1.69) = 1 - P(Z>1.69) = 1 - 0.0455 = 0.9545$.
> > 
> > **ii. $P(30<X<40)$:**
> > $P(30 < X < 40) = P(\frac{30-37.4}{4.5} < Z < \frac{40-37.4}{4.5})$
> > $= P(-1.64 < Z < 0.58) = 1 - P(Z>1.64) - P(Z>0.58)$
> > $= 1 - 0.0505 - 0.2810 = 0.6685$.

> [!sq]- Problem 5.7
> An average number of calories in a blueberry cupcake is 225kcal. Suppose that the distribution of calories is approximately normal with the standard deviation of 10kcal.
> a) Find the probability that a randomly selected blueberry cupcake will have less than 200kcal calories.
> b) Find the probability that a randomly selected blueberry cupcake is between 209kcal calories and 216kcal calories.
> c) If 45% of that cupcakes have the calories at most K kcal, find the value of K.
>
> > [!continue]- Solution
> > Let X be the number of calories. $X \sim N(225, 10^2)$.
> > 
> > **a) Less than 200kcal:**
> > $P(X < 200) = P(Z < \frac{200-225}{10}) = P(Z < -2.5) = P(Z > 2.5) = 0.0062$.
> > 
> > **b) Between 209kcal and 216kcal:**
> > $P(209 < X < 216) = P(\frac{209-225}{10} < Z < \frac{216-225}{10}) = P(-1.6 < Z < -0.9)$
> > $= P(Z > 0.9) - P(Z > 1.6) = 0.1841 - 0.0548 = 0.1293$.
> > 
> > **c) Value of K:**
> > $P(X \le K) = 0.45 \Rightarrow P(Z \le \frac{K-225}{10}) = 0.45$.
> > Since $0.45 < 0.5$, the z-score must be negative. $P(Z > -z) = 0.55 \Rightarrow P(Z > z) = 0.45$.
> > From the standard normal table, the closest area to $0.45$ is $0.4483$ at $Z=0.13$. So, $z \approx -0.13$.
> > $\frac{K-225}{10} = -0.13 \Rightarrow K - 225 = -1.3 \Rightarrow K = 223.7$.

# 5.4 NORMAL APPROXIMATIONS
The normal distribution $X\sim N(\mu,\sigma^{2})$ can be used to approximate the binomial distribution, $X\sim B(n,p)$ where $n>30$ and $np\ge5$ with $\mu=np$ and $\sigma^{2}=npq$. Two conditions need to be met to use normal approximation. Thus, from $X\sim B(n,p)$ approximate to $X\sim N(np,npq)$ where $\mu=np$ and $\sigma^{2}=npq$
> [!formula] Formula
> $\mu=np$
> $\sigma=\sqrt{npq}$

![[Pasted image 20260216173154.png]]

Under certain circumstances, normal distribution, $X\sim N(\mu,\sigma^{2})$ also can be used as an approximation to the Poisson distribution, $X\sim P_{o}(\lambda)$ with parameters $\mu=\lambda$ and $\sigma^{2}=\lambda$ if $\lambda$ is greater than 30 that is $\lambda>30$. Thus, from $X\sim P_{o}(\lambda)$ approximate to $X\sim N(\lambda,\lambda)$ where $\mu=\sigma^{2}=\lambda$.

Since the binomial and Poisson distribution applies to discrete random variables, whereas the normal distribution applies to continuous random variable, so we need to make some corrections for continuity.

## 5.4.1 Continuity Corrections
The binomial and Poisson distributions are discrete random variables, whereas the normal distribution is continuous. We need to take this into account when we are using the normal distribution to approximate a binomial or Poisson using a continuity correction.

1) If we have to find $P(X=7)$, it becomes $P(6.5<X<7.5)$ and the graph is as below:

![[Pasted image 20260216173209.png]]

2) If we have to find $P(X\ge7)$ it becomes $P(X>6.5)$ and the graph is as below:

![[Pasted image 20260216173259.png]]

3) If we have to find $P(X>7)$, it becomes $P(X>7.5)$ and the graph is as below:

![[Pasted image 20260216173309.png]]

4) If we have to find $P(X\le7)$, it becomes $P(X\le7.5)$ and the graph is as below:

![[Pasted image 20260216173323.png]]

5) If we have to find $P(X<7)$, it becomes $P(X<6.5)$ and the graph is as below:

![[Pasted image 20260216173333.png]]

In general, if $x_{1}$ and $x_{2}$ are two integers:

| Probability of X being... | Discrete | Normal |
| :--- | :--- | :--- |
| Equal | $P(X=x)$ | $P(x-\frac{1}{2}<X<x+\frac{1}{2})$ |
| At most | $P(X\le x)$ | $P(X<x+\frac{1}{2})$ |
| Less than/Fewer than | $P(X<x)$ | $P(X\le x-\frac{1}{2})$ |
| At least | $P(X\ge x)$ | $P(X>x-\frac{1}{2})$ |
| More than / Exceed | $P(X>x)$ | $P(X\ge x+\frac{1}{2})$ |
| In between | $P(x_{1}<X<x_{2})$ | $P(x_{1}+\frac{1}{2}\le X\le x_{2}-\frac{1}{2})$ |
| In between (inclusive) | $P(x_{1}\le X\le x_{2})$ | $P(x_{1}-\frac{1}{2}<X<x_{2}+\frac{1}{2})$ |

**Steps for using the binomial distribution to approximate the normal distribution.**
* **Step 1:** Check to see whether the normal approximation can be used.
* **Step 2:** Find the mean and variance.
* **Step 3:** Write the problem in the probability notation using X.
* **Step 4:** Perform the continuity correction.
* **Step 5:** Use the standardisation formula to determine the value of Z. $Z=\frac{X-\mu}{\sigma}$.
* **Step 6:** Find the solution.

> [!example]- Example 5.22
> Supposed a fair coin is tossed 60 times. Find the probability between 28- and 33-times head will appear.
>
> > [!continue]- Solution
> > Let X be the random variable the number of times head will appear, $X \sim B(60,\frac{1}{2})$.
> > Since, $np=60\times\frac{1}{2}=30$ ($\ge 5$), we may approximate X to the normal random variable, where:
> > $\mu=np=30$ and $\sigma^{2}=npq=np(1-p)=30\times\frac{1}{2}\times(1-\frac{1}{2})=30\times\frac{1}{2}\times\frac{1}{2}=15.$
> > Therefore $X \sim N(30,15)$.
> > $P(28<X<33) \xrightarrow{cc} P(28+\frac{1}{2}\le X\le33-\frac{1}{2})=P(28.5\le X\le32.5)$
> > $=P(\frac{28.5-30}{\sqrt{15}}\le Z\le\frac{32.5-30}{\sqrt{15}})$
> > $=P(-0.39\le Z\le0.65)$
> > $=1-P(Z\le-0.39)-P(Z\ge0.65)$
> > $=1-P(Z\ge0.39)-P(Z\ge0.65)$
> > $=1-0.3483-0.2578=0.3579$

> [!example]- Example 5.23
> Supposed in average 100 visitors are recorded to visit a local museum in a month. Calculate the probability there will be more than 95 visitors in a month.
>
> > [!continue]- Solution
> > Let X be the number of visitors in a month. Thus X may be regarded as a Poisson variable with mean $\lambda=100$, $X\sim P_{o}(100)$.
> > Since X has a Poisson mean, $\lambda=100$ which exceeds 30, therefor X can be approximated to $X\sim N(100,100)$.
> > $P(X>95) \xrightarrow{cc} P(X\ge95+\frac{1}{2})=P(X\ge95.5)$
> > $=P(Z\ge\frac{95.5-100}{\sqrt{100}})$
> > $=P(Z\ge-0.45)$
> > $=1-P(Z\le-0.45)$
> > $=1-P(Z\ge0.45)$
> > $=1-0.3264=0.6736$

As a conclusion,

![[Pasted image 20260216173400.png]]

---

# EXERCISE 5

> [!sq]- Question 1
> Given that the height of a population with $\mu=170cm$ and $\sigma=10$ are distributed normally, what is the probability that the height of a randomly selected person
> i. Greater than 185cm?
> ii. Lies between 175cm and 185cm?
> 
> > [!continue]- Solution
> > Let X be the height. $X \sim N(170, 10^2)$.
> > **i. Greater than 185cm:**
> > $P(X > 185) = P(Z > \frac{185-170}{10}) = P(Z > 1.5) = 0.0668$.
> > 
> > **ii. Lies between 175cm and 185cm:**
> > $P(175 < X < 185) = P(\frac{175-170}{10} < Z < \frac{185-170}{10}) = P(0.5 < Z < 1.5) = P(Z > 0.5) - P(Z > 1.5) = 0.3085 - 0.0668 = 0.2417$.

> [!sq]- Question 2
> Guests at a resort stay for an average of 8 days with a standard deviation of 2 days. Among 100 guests, how many can be expected to stay
> i. less than 7 days,
> ii. between 7 and 14 days?
> 
> > [!continue]- Solution
> > Let X be the length of stay. $X \sim N(8, 2^2)$. $n = 100$.
> > **i. Less than 7 days:**
> > $P(X < 7) = P(Z < \frac{7-8}{2}) = P(Z < -0.5) = P(Z > 0.5) = 0.3085$.
> > Expected number $= 100 \times 0.3085 = 30.85 \approx 31$ guests.
> > 
> > **ii. Between 7 and 14 days:**
> > $P(7 < X < 14) = P(\frac{7-8}{2} < Z < \frac{14-8}{2}) = P(-0.5 < Z < 3) = 1 - P(Z > 0.5) - P(Z > 3) = 1 - 0.3085 - 0.00135 = 0.69015$.
> > Expected number $= 100 \times 0.69015 = 69.015 \approx 69$ guests.

> [!sq]- Question 3
> The medical leave duration of employees in company Z in a year is normally distributed with a mean of 4 days and a standard deviation of 0.8 days.
> i. What is the probability that the medical leave duration of employees is at least 6 days.
> ii. 95% of the employee taking a medical leave within the "normal range" of number of days. Determine the minimum and maximum number of days for medical leave considered as outside the "normal range".
> 
> > [!continue]- Solution
> > Let X be the medical leave duration. $X \sim N(4, 0.8^2)$.
> > **i. At least 6 days:**
> > $P(X \ge 6) = P(Z \ge \frac{6-4}{0.8}) = P(Z \ge 2.5) = 0.0062$.
> > 
> > **ii. Outside the "normal range":**
> > "Normal range" containing 95% is symmetrically around the mean: $P(|X - 4| < k) = 0.95$.
> > This implies $P(-z < Z < z) = 0.95$, leaving 5% in the two tails, or 2.5% ($0.025$) in each tail.
> > $P(Z > z) = 0.025 \Rightarrow z = 1.96$.
> > The margin $k = z \cdot \sigma = 1.96 \times 0.8 = 1.568$.
> > Minimum days = $4 - 1.568 = 2.432$.
> > Maximum days = $4 + 1.568 = 5.568$.
> > Medical leave outside the "normal range" is fewer than 2.432 days or more than 5.568 days.

> [!sq]- Question 4
> Most graduate schools of business require applicants for admission to take the Graduate Management Admission Council's GMAT examination. Scores on the GMAT are roughly normally distributed with a mean of 527 and a standard deviation of 112.
> i. What is the probability of an individual scoring above 500 on the GMAT?
> ii. How high must an individual score on the GMAT to score in the highest 5%?
> 
> > [!continue]- Solution
> > Let X be the GMAT score. $X \sim N(527, 112^2)$.
> > **i. Scoring above 500:**
> > $P(X > 500) = P(Z > \frac{500-527}{112}) = P(Z > -0.24) = 1 - P(Z > 0.24) = 1 - 0.4052 = 0.5948$.
> > 
> > **ii. Highest 5%:**
> > We need $K$ such that $P(X > K) = 0.05$.
> > $P(Z > z) = 0.05 \Rightarrow z = 1.645$.
> > $K = \mu + z\sigma = 527 + 1.645(112) = 527 + 184.24 = 711.24$.

> [!sq]- Question 5
> A survey reports that forty-eight percent of Malaysian citizens own washing machines. 45 citizens are randomly selected and asked whether he or she owns a washing machine. What is the probability that exactly 10 say yes?
> 
> > [!continue]- Solution
> > Let X be the number of citizens who own washing machines. $X \sim B(45, 0.48)$.
> > Since $n \ge 30$ and $np = 45(0.48) = 21.6 \ge 5$, we can approximate to a normal distribution.
> > $\mu = 21.6$, $\sigma^2 = npq = 45(0.48)(0.52) = 11.232$, $\sigma = \sqrt{11.232} \approx 3.351$.
> > With continuity correction:
> > $P(X = 10) \xrightarrow{cc} P(9.5 < X_{norm} < 10.5)$
> > $= P(\frac{9.5-21.6}{3.351} < Z < \frac{10.5-21.6}{3.351}) = P(-3.61 < Z < -3.31)$
> > $= P(Z > 3.31) - P(Z > 3.61) \approx 0.0004 - 0.0001 = 0.0003$.

> [!sq]- Question 6
> A pyramid with a tetrahedral shape has its faces labeled A, B, C, and D is tossed 200 times. Find the probability of obtaining
> i. more than 60 times the letter A,
> ii. at most 50 times the letter B,
> iii. exactly 50 times the letter C.
> 
> > [!continue]- Solution
> > The probability of landing on any specific letter is $p = \frac{1}{4} = 0.25$. Number of tosses $n = 200$.
> > Let X be the occurrences of a specific letter. $X \sim B(200, 0.25)$.
> > $np = 200(0.25) = 50$, $\sigma^2 = 50(0.75) = 37.5$, $\sigma = \sqrt{37.5} \approx 6.124$.
> > Approximate $X \sim N(50, 37.5)$.
> > 
> > **i. More than 60 times letter A:**
> > $P(X > 60) \xrightarrow{cc} P(X \ge 60.5) = P(Z \ge \frac{60.5-50}{6.124}) = P(Z \ge 1.71) = 0.0436$.
> > 
> > **ii. At most 50 times letter B:**
> > $P(X \le 50) \xrightarrow{cc} P(X \le 50.5) = P(Z \le \frac{50.5-50}{6.124}) = P(Z \le 0.08) = 1 - 0.4681 = 0.5319$.
> > 
> > **iii. Exactly 50 times letter C:**
> > $P(X = 50) \xrightarrow{cc} P(49.5 \le X \le 50.5) = P(\frac{49.5-50}{6.124} \le Z \le \frac{50.5-50}{6.124}) = P(-0.08 \le Z \le 0.08)$
> > $= 1 - 2P(Z \ge 0.08) = 1 - 2(0.4681) = 1 - 0.9362 = 0.0638$.

> [!sq]- Question 7
> A type of flowering seed is sold in small boxes of about 800 seeds. It is known that 45% will produce red flowers and 55% purple flowers. If 100 of these seeds are planted, estimate the probability that
> i. At least 32 seeds will produce red flowers.
> ii. More than 60 seeds will produce purple flowers.
> iii. Between 40 to 50 seeds will produce red flowers.
> 
> > [!continue]- Solution
> > Let R be seeds producing red flowers, $R \sim B(100, 0.45)$. Normal approx: $\mu_R = 45, \sigma_R^2 = 45(0.55) = 24.75, \sigma_R \approx 4.975$.
> > Let P be seeds producing purple flowers, $P \sim B(100, 0.55)$. Normal approx: $\mu_P = 55, \sigma_P^2 = 55(0.45) = 24.75, \sigma_P \approx 4.975$.
> > 
> > **i. At least 32 seeds produce red:**
> > $P(R \ge 32) \xrightarrow{cc} P(R \ge 31.5) = P(Z \ge \frac{31.5-45}{4.975}) = P(Z \ge -2.71) = 1 - P(Z \ge 2.71) = 1 - 0.0034 = 0.9966$.
> > 
> > **ii. More than 60 seeds produce purple:**
> > $P(P > 60) \xrightarrow{cc} P(P \ge 60.5) = P(Z \ge \frac{60.5-55}{4.975}) = P(Z \ge 1.11) = 0.1335$.
> > 
> > **iii. Between 40 to 50 seeds produce red (exclusive):**
> > $P(40 < R < 50) \xrightarrow{cc} P(40.5 \le R \le 49.5) = P(\frac{40.5-45}{4.975} \le Z \le \frac{49.5-45}{4.975}) = P(-0.90 \le Z \le 0.90) = 1 - 2(0.1841) = 0.6318$.
> > *(Note: If inclusive "$40 \le R \le 50$", the cc would be $P(39.5 \le R \le 50.5)$ yielding $P(-1.11 \le Z \le 1.11) = 0.7330$. The wording "between" typically implies exclusivity in continuous contexts, but can be inclusive in discrete).*

> [!sq]- Question 8
> Reading from the satellite shows the average number of forest fire starting points in every 100 square kilometers is 45 points. Find the probability:
> i. At least 120 forest fire starting points in 240 square kilometers.
> ii. From 215 to 230 forest fire starting points in 500 square kilometers.
> 
> > [!continue]- Solution
> > **i. At least 120 in 240 sq km:**
> > Mean $\lambda = 45 \times \frac{240}{100} = 108$. $X \sim P_o(108)$.
> > Since $\lambda > 30$, approximate $X \sim N(108, 108)$, $\sigma = \sqrt{108} \approx 10.392$.
> > $P(X \ge 120) \xrightarrow{cc} P(X \ge 119.5) = P(Z \ge \frac{119.5-108}{10.392}) = P(Z \ge 1.11) = 0.1335$.
> > 
> > **ii. From 215 to 230 in 500 sq km:**
> > Mean $\lambda = 45 \times \frac{500}{100} = 225$. $Y \sim P_o(225)$.
> > Approximate $Y \sim N(225, 225)$, $\sigma = \sqrt{225} = 15$.
> > $P(215 \le Y \le 230) \xrightarrow{cc} P(214.5 \le Y \le 230.5) = P(\frac{214.5-225}{15} \le Z \le \frac{230.5-225}{15}) = P(-0.70 \le Z \le 0.37)$
> > $= 1 - P(Z \ge 0.70) - P(Z \ge 0.37) = 1 - 0.2420 - 0.3557 = 0.4023$.

> [!sq]- Question 9
> On average, 48 vehicles per day arrive at a certain workshop. Find the probability,
> i. Exactly 65 vehicles arrived at the workshop in a day.
> ii. Less than 350 vehicles arrived at the workshop in a week.
> iii. More than 415 vehicles arrived at the workshop in 10 days.
> 
> > [!continue]- Solution
> > **i. Exactly 65 vehicles in a day:**
> > $\lambda = 48$. $X \sim P_o(48)$. Approximate $X \sim N(48, 48)$, $\sigma = \sqrt{48} \approx 6.928$.
> > $P(X = 65) \xrightarrow{cc} P(64.5 \le X \le 65.5) = P(\frac{64.5-48}{6.928} \le Z \le \frac{65.5-48}{6.928}) = P(2.38 \le Z \le 2.53)$
> > $= P(Z \ge 2.38) - P(Z \ge 2.53) = 0.0087 - 0.0057 = 0.0030$.
> > 
> > **ii. Less than 350 vehicles in a week (7 days):**
> > $\lambda = 48 \times 7 = 336$. $Y \sim P_o(336)$. Approximate $Y \sim N(336, 336)$, $\sigma = \sqrt{336} \approx 18.330$.
> > $P(Y < 350) \xrightarrow{cc} P(Y \le 349.5) = P(Z \le \frac{349.5-336}{18.330}) = P(Z \le 0.74) = 1 - 0.2296 = 0.7704$.
> > 
> > **iii. More than 415 vehicles in 10 days:**
> > $\lambda = 48 \times 10 = 480$. $W \sim P_o(480)$. Approximate $W \sim N(480, 480)$, $\sigma = \sqrt{480} \approx 21.909$.
> > $P(W > 415) \xrightarrow{cc} P(W \ge 415.5) = P(Z \ge \frac{415.5-480}{21.909}) = P(Z \ge -2.94) = 1 - P(Z \ge 2.94) = 1 - 0.0016 = 0.9984$.

> [!sq]- Question 10
> A gene for a rare blood disorder is known to occur in 0.0025 of the population. A random sample of 40000 individuals is screened for this gene.
> i. Calculate the probability that in this sample, more than 115 individuals will be carrying this gene.
> ii. Find the least value of k such that the probability that there are at most k individuals carrying this gene is greater than 5%.
> 
> > [!continue]- Solution
> > $n = 40000$, $p = 0.0025$. $X \sim B(40000, 0.0025)$.
> > $np = 100$. Since $n \ge 30$ and $np \ge 5$, use normal approximation $X \sim N(100, 99.75)$, $\sigma = \sqrt{99.75} \approx 9.987$.
> > 
> > **i. More than 115 individuals:**
> > $P(X > 115) \xrightarrow{cc} P(X \ge 115.5) = P(Z \ge \frac{115.5-100}{9.987}) = P(Z \ge 1.55) = 0.0606$.
> > 
> > **ii. Least value of k:**
> > $P(X \le k) > 0.05 \xrightarrow{cc} P(X \le k + 0.5) > 0.05 \Rightarrow P(Z \le \frac{k+0.5-100}{9.987}) > 0.05$.
> > From standard normal tables, $P(Z \le -1.645) = 0.05$.
> > $\frac{k-99.5}{9.987} > -1.645 \Rightarrow k - 99.5 > -16.429 \Rightarrow k > 83.07$.
> > The least integer value for k is 84.

