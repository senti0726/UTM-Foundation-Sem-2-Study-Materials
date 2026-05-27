$$\underline{\Huge\text{APPLICATION OF INTEGRATION}}$$

# 5.0 INTRODUCTION
In geometry, we have learnt formulae to calculate area and volume of various geometrical figures including triangles, rectangles and circles. Such formulae are fundamental in the applications of mathematics to many real-life problems.

When we wish to find the area under a curve or the volume of revolution of a region about an axis, we will use the concept of definite integrals in previous chapter.

![[Pasted image 20260216182717.png]]

# 5.1 AREA OF A REGION

## 5.1.1 Under A Curve
**Area of a Region Under a Curve: Bounded Entirely Above x - Axis**
If we have the region as shown below,

![[Pasted image 20260216182820.png]]

Then the area under the graph of a curve, $y=f(x)$ with lines $x=a$ and $x=b$ which located above x-axis is equal to the definite integral,

> [!formula]
> $A=\int_{a}^{b}f(x)dx$

> [!example]- Example 5.1
> Find the area of a curve $y=x^{2}+2$ from $x=1$ to $x=2$.
> 
> > [!continue]- Solution
> > $A=\int_{1}^{2}x^{2}+2~dx=\left[\frac{x^{3}}{3}+2x\right]_{1}^{2}=\left(\frac{2^{3}}{3}+2(2)\right)-\left(\frac{1^{3}}{3}+2(1)\right)=\frac{13}{3}\text{ units}^{2}.$

**Area of a Region Under a Curve: Bounded Entirely Below x-Axis**
The region given as in the figure which located below x-axis,

![[Pasted image 20260216182919.png]]

In this case, the definite integral $\int_{a}^{b}f(x)dx$ has a negative value. Since area is always has a positive value, then the area of this region can be written as,

> [!formula]
> $A=\left|\int_{a}^{b}f(x)dx\right|$

> [!example]- Example 5.2
> Find the area of a curve given in the figure below.
> ![[Pasted image 20260216184156.png]]
> 
> > [!continue]- Solution
> > The required area is $A=\left|\int_{a}^{b}f(x)dx\right|$
> > $A=\left|\int_{-1}^{2}x^{2}-4~dx\right|=\left|\left[\frac{x^{3}}{3}-4x\right]_{-1}^{2}\right|$
> > $=\left|\left(\frac{2^{3}}{3}-4(2)\right)-\left(\frac{(-1)^{3}}{3}-4(-1)\right)\right|=|-9|=9\text{ units}^{2}$

**Area of a Region Under a Curve: Part of the Region Bounded Below and Above x-Axis**
The required region is shown in the figure below,

![[Pasted image 20260216184231.png]]

In this case, we have to sum the individual parts, and the area of this region is written as,

> [!formula]
> $A=\left|\int_{a}^{c}f(x)dx\right|+\int_{c}^{b}f(x)dx$

> [!example]- Example 5.3
> What is the area bounded by the curve $y=x^{3}$, x-axis with the line $x=-2$ and $x=1$?
> ![[Pasted image 20260216184250.png]]
> 
> > [!continue]- Solution
> > The area of this region is given by, $A=\left|\int_{a}^{c}f(x)dx\right|+\int_{c}^{b}f(x)dx.$
> > Find the intersection of the curve $y=x^{3}$ and x-axis. We know that, at x-axis, $y=0$. Thus, $x^{3}=0$ and solve for x gives $x=0$.
> > $A=\left|\int_{-2}^{0}x^{3}dx\right|+\int_{0}^{1}x^{3}dx=\left|\left[\frac{x^{4}}{4}\right]_{-2}^{0}\right|+\left[\frac{x^{4}}{4}\right]_{0}^{1}=\left|\frac{0^{4}}{4}-\frac{(-2)^{4}}{4}\right|+\left(\frac{1^{4}}{4}-0\right)=|-4|+\frac{1}{4}=\frac{17}{4}\text{ units}^{2}$

> [!example]- Example 5.4
> Determine the area of the region bounded by the curve $y=\frac{3}{x^{2}}-1$, x-axis with the lines $x=1$ and $x=2$.
> ![[Pasted image 20260216184314.png]]
> 
> > [!continue]- Solution
> > The area of this region is given by, $A=\int_{a}^{c}f(x)dx+\left|\int_{c}^{b}f(x)dx\right|.$
> > Find the intersection of the curve $y=\frac{3}{x^{2}}-1$ and x-axis. Thus, $\frac{3}{x^{2}}-1=0$ and solve for x gives $x=\pm\sqrt{3}$, ignore $x=-\sqrt{3}$.
> > $A=\int_{1}^{\sqrt{3}}\left(\frac{3}{x^{2}}-1\right)dx+\left|\int_{\sqrt{3}}^{2}\left(\frac{3}{x^{2}}-1\right)dx\right|=\left[-\frac{3}{x}-x\right]_{1}^{\sqrt{3}}+\left|\left[-\frac{3}{x}-x\right]_{\sqrt{3}}^{2}\right|$
> > $=\left((-\frac{3}{\sqrt{3}}-\sqrt{3})-(-\frac{3}{1}-1)\right)+\left|(-\frac{3}{2}-2)-(-\frac{3}{\sqrt{3}}-\sqrt{3})\right|$
> > $=(4-2\sqrt{3}) + |2\sqrt{3}-3.5| = (4-2\sqrt{3}) + (3.5-2\sqrt{3}) = 7.5-4\sqrt{3} \approx 0.572\text{ units}^{2}$

**Area of a Region Under a Curve: Bounded Entirely Right or Left y-Axis**
The required region is shown in the figure below,

![[Pasted image 20260216184401.png]]

In this case, it is easier to rewrite the function in terms of y and calculate the area using horizontal elements.
In this case the formula for the area would be,

> [!formula]
> $A=\int_{c}^{d}f(y)dy$

If the region bounded entirely left side of $y-\text{axis}$ thus the formula for the area would be:

> [!formula]
> $A=\left|\int_{c}^{d}f(y)dy\right|$

> [!example]- Example 5.5
> Determine the area of the region bounded by the curve $x=y^{2}+1$, y-axis with the lines $y=1$ and $y=5$.
> ![[Pasted image 20260216184414.png]]
> 
> > [!continue]- Solution
> > In this case, we express the curve in terms of y gives $x=y^{2}+1$. So, the area is given by, $A=\int_{c}^{d}f(y)dy$ .
> > $A=\int_{1}^{5}y^{2}+1dy=\left[\frac{y^{3}}{3}+y\right]_{1}^{5}=\left(\frac{5^{3}}{3}+5\right)-\left(\frac{1^{3}}{3}+1\right)=\frac{136}{3}\text{ units}^{2}$

> [!example]- Example 5.6
> Find the area of the region bounded by the curve $y=x^{3}$ the y-axis and the lines $y=-1$ and $y=8$.
> ![[Pasted image 20260216184451.png]]
> 
> > [!continue]- Solution
> > In this case, we express the curve in terms of y gives $x=\sqrt[3]{y}$. So, the area is given by,
> > $A=\left|\int_{c}^{0}f(y)dy\right|+\int_{0}^{d}f(y)dy.$
> > $A=\left|\int_{-1}^{0}y^{\frac{1}{3}}dy\right|+\int_{0}^{8}y^{\frac{1}{3}}dy=\left|\left[\frac{y^{\frac{4}{3}}}{4/3}\right]_{-1}^{0}\right|+\left[\frac{y^{\frac{4}{3}}}{4/3}\right]_{0}^{8}$
> > $=\left|0-\frac{3}{4}(-1)^{\frac{4}{3}}\right|+\left(\frac{3}{4}(8)^{\frac{4}{3}}-0\right)=\left|-\frac{3}{4}\right|+12=\frac{51}{4}\text{ units}^{2}$

> [!sq]- Problem 5.1
> a) Find the area of A and B where it is bounded by the curve $y=x(x-3)$, the x-axis and the ordinates $x=0$ and $x=5$.
> ![[Pasted image 20260216184510.png]]
> 
> b) Find the area of A which it is bounded by the curve $y=x^{2}+x+4$, about the x-axis and the ordinates $x=1$ and $x=3$.
> ![[Pasted image 20260216184522.png]]
> 
> > [!continue]- Solution
> > **a)** The curve is $y = x^2 - 3x$. The x-intercepts are at $x=0$ and $x=3$.
> > Area A is below the x-axis from $x=0$ to $x=3$:
> > $A = \left|\int_{0}^{3} (x^2 - 3x) dx\right| = \left|\left[\frac{x^3}{3} - \frac{3x^2}{2}\right]_{0}^{3}\right| = \left|\left(9 - \frac{27}{2}\right) - 0\right| = |-4.5| = 4.5$.
> > Area B is above the x-axis from $x=3$ to $x=5$:
> > $B = \int_{3}^{5} (x^2 - 3x) dx = \left[\frac{x^3}{3} - \frac{3x^2}{2}\right]_{3}^{5} = \left(\frac{125}{3} - \frac{75}{2}\right) - \left(-4.5\right) = \left(\frac{250-225}{6}\right) + \frac{9}{2} = \frac{25}{6} + \frac{27}{6} = \frac{52}{6} = \frac{26}{3} \approx 8.667$.
> > Total Area = $4.5 + \frac{26}{3} = \frac{27}{6} + \frac{52}{6} = \frac{79}{6} = 13\frac{1}{6}\text{ units}^2$.
> > 
> > **b)** The curve $y = x^2+x+4$ is entirely above the x-axis.
> > $A = \int_{1}^{3} (x^2 + x + 4) dx = \left[\frac{x^3}{3} + \frac{x^2}{2} + 4x\right]_{1}^{3}$
> > $= \left(\frac{27}{3} + \frac{9}{2} + 12\right) - \left(\frac{1}{3} + \frac{1}{2} + 4\right) = (9 + 4.5 + 12) - \left(\frac{2+3+24}{6}\right) = 25.5 - \frac{29}{6} = \frac{153}{6} - \frac{29}{6} = \frac{124}{6} = \frac{62}{3}\text{ units}^2$.

## 5.1.2 Between Two Curves
A similar technique to the one we have just used can also be employed to find the area sandwiched between curves.

**Area of a Region Between Two Curves: About x-Axis**
Now, we want to determine the area between the curves $y=f(x)$ and $y=g(x)$ on the interval \[a,b\]. We also going to assume that $f(x)\ge g(x)$. The shaded region is given by,

![[Pasted image 20260216184554.png]]

Then, the area of the shaded region is given by, $A=\int_{a}^{b}[f(x)-g(x)]dx$

It is sometimes easy to forget that these always require the first function to be the larger of the two functions. So, we can say that:

> [!formula]
> $A=\int_{a}^{b}(\text{upper function} - \text{lower function}) dx,$ $a\le x\le b$

> [!example]- Example 5.7
> Find the area of shaded region enclosed by the curve $y=5x-x^{2}$ and the line $y=x$. The shaded area is shown in the figure.
> ![[Pasted image 20260216184641.png]]
> 
> > [!continue]- Solution
> > **LUSI method**
> > **L: limits and intersections**
> > $5x-x^{2}=x \Rightarrow x^{2}-4x=0 \Rightarrow x=0, x=4$. Limits: $[0,4]$.
> > **U: upper and lower functions**
> > From $[0,4]$, choose one test value, $x=1$.
> > $y=5(1)-1^{2}=4$
> > $y=1$
> > $y=5x-x^{2}$ is upper function, $y=x$ is lower function.
> > **S: subtract upper function with lower function**
> > $5x-x^{2}-x=4x-x^{2}$
> > **I: integrate**
> > $A=\int_{0}^{4}(4x-x^{2})dx=\left[\frac{4x^{2}}{2}-\frac{x^{3}}{3}\right]_{0}^{4}=\left(2(4)^{2}-\frac{4^{3}}{3}\right)-0=32-\frac{64}{3}=\frac{32}{3}\text{ units}^{2}$

> [!sq]- Problem 5.2
> a) The region shaded is bounded by the two curves, $y=\sqrt{x}$ and $y=x^{2}$ as shown in the figure. Find the area of the shaded region.
> ![[Pasted image 20260216184724.png]]
> 
> b) If the shaded region is bounded by the two curves, $f(x)=9-(\frac{x}{2})^{2}$ and $g(x)=6-x,$ find the area of shaded region.
> ![[Pasted image 20260216184736.png]]
> 
> c) The region shaded, R is bounded by a curve, $y=x^{2}+2$ and a line $x+y=4$. Find:
> a) the coordinates of A and B, and
> b) the area of shaded region, R.
> ![[Pasted image 20260216184750.png]]
> 
> > [!continue]- Solution
> > **a)** Intersections: $x^2 = \sqrt{x} \Rightarrow x^4 = x \Rightarrow x(x^3-1) = 0 \Rightarrow x=0, x=1$.
> > Upper curve: $y=\sqrt{x}$, Lower curve: $y=x^2$.
> > Area $= \int_{0}^{1} (\sqrt{x} - x^2) dx = \left[ \frac{2}{3}x^{3/2} - \frac{x^3}{3} \right]_{0}^{1} = \left(\frac{2}{3} - \frac{1}{3}\right) - 0 = \frac{1}{3}\text{ units}^2$.
> > 
> > **b)** Intersections: $9 - \frac{x^2}{4} = 6 - x \Rightarrow 36 - x^2 = 24 - 4x \Rightarrow x^2 - 4x - 12 = 0 \Rightarrow (x-6)(x+2) = 0 \Rightarrow x=-2, x=6$.
> > Upper curve: $f(x)=9-\frac{x^2}{4}$, Lower curve: $g(x)=6-x$.
> > Area $= \int_{-2}^{6} \left(9 - \frac{x^2}{4} - (6 - x)\right) dx = \int_{-2}^{6} \left(3 + x - \frac{x^2}{4}\right) dx = \left[ 3x + \frac{x^2}{2} - \frac{x^3}{12} \right]_{-2}^{6}$.
> > At $x=6$: $18 + 18 - \frac{216}{12} = 36 - 18 = 18$.
> > At $x=-2$: $-6 + 2 - \frac{-8}{12} = -4 + \frac{2}{3} = -\frac{10}{3}$.
> > Area $= 18 - (-\frac{10}{3}) = \frac{54}{3} + \frac{10}{3} = \frac{64}{3} \approx 21.333\text{ units}^2$.
> > 
> > **c) a)** Line equation: $y = 4-x$. Equate to curve: $x^2+2 = 4-x \Rightarrow x^2+x-2 = 0 \Rightarrow (x+2)(x-1) = 0 \Rightarrow x=-2, x=1$.
> > For $x=-2$, $y=4-(-2)=6 \Rightarrow A(-2,6)$.
> > For $x=1$, $y=4-1=3 \Rightarrow B(1,3)$.
> > **c) b)** Upper curve: $y=4-x$, Lower curve: $y=x^2+2$.
> > Area R $= \int_{-2}^{1} ((4-x) - (x^2+2)) dx = \int_{-2}^{1} (2 - x - x^2) dx = \left[ 2x - \frac{x^2}{2} - \frac{x^3}{3} \right]_{-2}^{1}$.
> > At $x=1$: $2 - \frac{1}{2} - \frac{1}{3} = \frac{7}{6}$.
> > At $x=-2$: $-4 - 2 - (\frac{-8}{3}) = -6 + \frac{8}{3} = -\frac{10}{3} = -\frac{20}{6}$.
> > Area $= \frac{7}{6} - (-\frac{20}{6}) = \frac{27}{6} = \frac{9}{2} = 4.5\text{ units}^2$.

**Area of a Region Between Two Curves: About y-Axis**
This case is almost identical to the first case. Here we are going to determine the area between the curves $x=f(y)$ and $x=g(y)$ on the interval $[c,d]$. We also going to assume that $f(y)\ge g(y)$. The shaded area is given by,

![[Pasted image 20260216184812.png]]S

Then, the area is given by $A=\int_{c}^{d}[f(y)-g(y)]dy$.
It is sometimes easy to forget that these always require the first function to be the larger of the two functions. So, we can say that:

> [!formula]
> $A=\int_{c}^{d}(\text{right function} - \text{left function}) dy, \quad c\le y\le d$

> [!example]- Example 5.8
> Find the area of shaded region enclosed by the curve $x=y^{2}$ and the line $x=y+2$.
> ![[Pasted image 20260216184829.png]]
> 
> > [!continue]- Solution
> > **LUSI method**
> > **L: limits and intersections**
> > $y^{2}=y+2 \Rightarrow y^{2}-y-2=0 \Rightarrow y=2, y=-1$. Limits: $[-1,2]$.
> > **U: right and left functions**
> > From $[-1,2]$, choose one test value, $y=0$.
> > $x=0^{2}=0$
> > $x=0+2=2$
> > $x=y^{2}$ is left function, $x=y+2$ is right function.
> > **S: subtract right function with left function**
> > $(y+2)-y^{2}=-y^{2}+y+2$
> > **I: integrate**
> > $A=\int_{-1}^{2}(-y^{2}+y+2)dy=\left[-\frac{y^{3}}{3}+\frac{y^{2}}{2}+2y\right]_{-1}^{2}$
> > $=\left(-\frac{2^{3}}{3}+\frac{2^{2}}{2}+2(2)\right)-\left(-\frac{(-1)^{3}}{3}+\frac{(-1)^{2}}{2}+2(-1)\right) = \frac{10}{3} - (-\frac{7}{6}) = \frac{9}{2}\text{ units}^{2}$

> [!sq]- Problem 5.3
> a) The region shaded is bounded by the two curves $x=-y^{2}+10$ and $x=(y-2)^{2}$ as shown below. Find the area of the shaded region.
> ![[Pasted image 20260216184844.png]]
> 
> b) The region shaded is bounded by the two curves, $x=\frac{1}{2}y^{2}-3$ and $y=x-1$ as shown below. Find the area of the shaded region.
> ![[Pasted image 20260216184856.png]]
> 
> > [!continue]- Solution
> > **a)** Intersections: $-y^2+10 = (y-2)^2 \Rightarrow -y^2+10 = y^2-4y+4 \Rightarrow 2y^2-4y-6 = 0 \Rightarrow y^2-2y-3 = 0 \Rightarrow (y-3)(y+1) = 0 \Rightarrow y=-1, y=3$.
> > Right curve: $x=-y^2+10$, Left curve: $x=y^2-4y+4$.
> > Area $= \int_{-1}^{3} ((-y^2+10) - (y^2-4y+4)) dy = \int_{-1}^{3} (-2y^2 + 4y + 6) dy = \left[ -\frac{2y^3}{3} + 2y^2 + 6y \right]_{-1}^{3}$.
> > At $y=3$: $-18 + 18 + 18 = 18$.
> > At $y=-1$: $\frac{2}{3} + 2 - 6 = -\frac{10}{3}$.
> > Area $= 18 - (-\frac{10}{3}) = \frac{54}{3} + \frac{10}{3} = \frac{64}{3} \approx 21.333\text{ units}^2$.
> > 
> > **b)** Line equation: $x = y+1$.
> > Intersections: $y+1 = \frac{1}{2}y^2-3 \Rightarrow 2y+2 = y^2-6 \Rightarrow y^2-2y-8 = 0 \Rightarrow (y-4)(y+2) = 0 \Rightarrow y=-2, y=4$.
> > Right curve: $x=y+1$, Left curve: $x=\frac{1}{2}y^2-3$.
> > Area $= \int_{-2}^{4} \left((y+1) - (\frac{1}{2}y^2-3)\right) dy = \int_{-2}^{4} \left(-\frac{1}{2}y^2 + y + 4\right) dy = \left[ -\frac{y^3}{6} + \frac{y^2}{2} + 4y \right]_{-2}^{4}$.
> > At $y=4$: $-\frac{64}{6} + \frac{16}{2} + 16 = -\frac{32}{3} + 24 = \frac{40}{3}$.
> > At $y=-2$: $-\frac{-8}{6} + \frac{4}{2} - 8 = \frac{4}{3} + 2 - 8 = -\frac{14}{3}$.
> > Area $= \frac{40}{3} - (-\frac{14}{3}) = \frac{54}{3} = 18\text{ units}^2$.

## 5.2 VOLUME OF REVOLUTION
In trying to find the volume of a solid, we face the same type of problem as in finding areas. In this section, we will start looking at the volume of a solid of revolution. We should first define just what a solid of revolution is.

If a plane region rotates about a line, then a solid object is generated which is called the solid of revolution. The line about which we rotate the solid is called the axis of revolution.

![[Pasted image 20260216185208.png]]

## 5.2.1 Disk Method
The disk method is used when we rotate a single curve $y=f(x)$ around the x-axis or the y-axis.

**Revolution About the x-Axis**
To get a solid of revolution about x-axis, we start out with a function, $y=f(x)$ on the interval $[a,b]$. Then, we rotate this curve about x-axis to get the surface of the solid of revolution.

![[Pasted image 20260216185220.png]]

The volume of the solid formed by revolving the region bounded by the curve $y=f(x)$ and the x-axis between the lines $x=a$ and $x=b$ revolves $360^{\circ}$ about the x-axis is given by:

> [!formula]
> $V=\pi\int_{a}^{b}[f(x)]^{2}dx$

> [!example]- Example 5.9
> Determine the volume of the solid obtained by rotating the region is revolved about x-axis and bounded by $y=x^{2}-4x+5$ within the interval $[1,4]$.
> 
> > [!continue]- Solution
> > $V=\pi\int_{a}^{b}[f(x)]^{2}dx=\pi\int_{1}^{4}[x^{2}-4x+5]^{2}dx$
> > $=\pi\int_{1}^{4}(x^{4}-8x^{3}+26x^{2}-40x+25)dx$
> > $=\pi\left[\frac{x^{5}}{5}-\frac{8x^{4}}{4}+\frac{26x^{3}}{3}-\frac{40x^{2}}{2}+25x\right]_{1}^{4}$
> > $=\pi\left[ \left(\frac{4^{5}}{5}-2(4)^{4}+\frac{26(4)^{3}}{3}-20(4)^{2}+25(4)\right) - \left(\frac{1^{5}}{5}-2(1)^{4}+\frac{26(1)^{3}}{3}-20(1)^{2}+25(1)\right) \right] = \frac{78}{5}\pi\text{ units}^{3}$

> [!example]- Example 5.10
> Find the volume of the solid formed by rotating the region is revolved about the x-axis and bounded by $f(x)=\frac{1}{x}$ within the interval $[1,2]$.
> ![[Pasted image 20260216185249.png]]
> 
> > [!continue]- Solution
> > $V=\pi\int_{a}^{b}[f(x)]^{2}dx=\pi\int_{1}^{2}\left[\frac{1}{x}\right]^{2}dx$
> > $=\pi\int_{1}^{2}\frac{1}{x^{2}}dx = \pi\left[-\frac{1}{x}\right]_{1}^{2}$
> > $=\pi\left(-\frac{1}{2}-(-1)\right)=\frac{\pi}{2}\text{ units}^{3}$

> [!sq]- Problem 5.4
> a) The region shaded is bounded by a curve, $y=(x-1)^{2}+1$, the x-axis and $x=0$ and $x=4$ as shown in the figure. Find the volume of the shaded region.
> ![[Pasted image 20260216185300.png]]
> 
> b) Find the volume of the solid of revolution formed by rotating the region bounded by the x-axis and the graph of $y=\sqrt{x}$, $x=0$ and $x=1$ about the x-axis.
> 
> > [!continue]- Solution
> > **a)** The region is bounded by $y = (x-1)^2+1 = x^2-2x+2$ between $x=0$ and $x=4$. Revolved about x-axis.
> > $V = \pi \int_{0}^{4} (x^2-2x+2)^2 dx = \pi \int_{0}^{4} (x^4 - 4x^3 + 8x^2 - 8x + 4) dx$
> > $= \pi \left[ \frac{x^5}{5} - x^4 + \frac{8x^3}{3} - 4x^2 + 4x \right]_{0}^{4}$
> > $= \pi \left( \frac{1024}{5} - 256 + \frac{512}{3} - 64 + 16 \right) - 0 = \pi \left( 204.8 - 256 + 170.667 - 48 \right) = \frac{1072\pi}{15}\text{ units}^{3}$.
> > 
> > **b)** The region is bounded by $y=\sqrt{x}$ between $x=0$ and $x=1$. Revolved about x-axis.
> > $V = \pi \int_{0}^{1} (\sqrt{x})^2 dx = \pi \int_{0}^{1} x dx = \pi \left[ \frac{x^2}{2} \right]_{0}^{1} = \pi \left( \frac{1}{2} - 0 \right) = \frac{\pi}{2}\text{ units}^{3}$.

**Revolution About the y-Axis**
To get a solid of revolution about y-axis, we start out with a function, $x=f(y)$ on the interval $[c,d]$. Then, we rotate this curve about y-axis to get the surface of the solid of revolution.
![[Pasted image 20260216185233.png]]

The volume of the solid formed by revolving the region bounded by the curve $x=f(y)$ and the y-axis between the lines $y=c$ and $y=d$ revolves $360^{\circ}$ about the y-axis is given by:

> [!formula]
> $V=\pi\int_{c}^{d}[f(y)]^{2}dy$

> [!example]- Example 5.11
> The region bounded by the graph of $g(y)=\sqrt{4-y}$ and y-axis over the interval $[0,4]$. Find the volume of the shaded region.
> ![[Pasted image 20260216185339.png]]
> 
> > [!continue]- Solution
> > $V=\pi\int_{c}^{d}[f(y)]^{2}dy=\pi\int_{0}^{4}[\sqrt{4-y}]^{2}dy=\pi\int_{0}^{4}(4-y)dy=\pi\left[4y-\frac{y^{2}}{2}\right]_{0}^{4}$
> > $=\pi\left[\left(4(4)-\frac{4^{2}}{2}\right)-0\right]=8\pi\text{ units}^{3}$

> [!example]- Example 5.12
> The region bounded by $x=4+2y-y^{2}$ y-axis and the lines $y=-1$ and $y=3$. Find the volume of the solid generated when the shaded region is rotated about the y-axis.
> ![[Pasted image 20260216185328.png]]
> 
> > [!continue]- Solution
> > $V=\pi\int_{c}^{d}[f(y)]^{2}dy=\pi\int_{-1}^{3}[4+2y-y^{2}]^{2}dy=\pi\int_{-1}^{3}(16+16y-4y^{2}-4y^{3}+y^{4})dy$
> > $=\pi\left[16y+\frac{16y^{2}}{2}-\frac{4y^{3}}{3}-\frac{4y^{4}}{4}+\frac{y^{5}}{5}\right]_{-1}^{3}$
> > $=\pi\left[ \left(16(3)+8(3)^{2}-\frac{4(3)^{3}}{3}-(3)^{4}+\frac{3^{5}}{5}\right) - \left(16(-1)+8(-1)^{2}-\frac{4(-1)^{3}}{3}-(-1)^{4}+\frac{(-1)^{5}}{5}\right) \right]$
> > $=\frac{892}{15}\pi\text{ units}^{3}$

> [!sq]- Problem 5.5
> a) From the diagram below, determine the volume of the solid when the shaded region is revolved about the y-axis.
> ![[Pasted image 20260216185356.png]]
> 
> b) The region R is bounded by y-axis, the lines $y=1$ and $y=3$; and the curve $y=\sqrt{x-1}$. Find the volume of the region when it is revolved about the y-axis.
> ![[Pasted image 20260216185406.png]]
> 
> > [!continue]- Solution
> > **a)** The curve is $x = y^2 - 4y$. The region bounded by the y-axis is from $y=0$ to $y=4$. Revolved about y-axis.
> > $V = \pi \int_{0}^{4} (y^2 - 4y)^2 dy = \pi \int_{0}^{4} (y^4 - 8y^3 + 16y^2) dy$
> > $= \pi \left[ \frac{y^5}{5} - 2y^4 + \frac{16y^3}{3} \right]_{0}^{4} = \pi \left( \frac{1024}{5} - 512 + \frac{1024}{3} \right) - 0$
> > $= \pi \left( \frac{3072 - 7680 + 5120}{15} \right) = \frac{512\pi}{15}\text{ units}^{3}$.
> > 
> > **b)** The curve is $y = \sqrt{x-1} \Rightarrow x = y^2 + 1$. Revolved about y-axis between $y=1$ and $y=3$.
> > $V = \pi \int_{1}^{3} (y^2+1)^2 dy = \pi \int_{1}^{3} (y^4 + 2y^2 + 1) dy = \pi \left[ \frac{y^5}{5} + \frac{2y^3}{3} + y \right]_{1}^{3}$
> > $= \pi \left( \left(\frac{243}{5} + 18 + 3\right) - \left(\frac{1}{5} + \frac{2}{3} + 1\right) \right) = \pi \left( \frac{348}{5} - \frac{28}{15} \right) = \pi \left( \frac{1044 - 28}{15} \right) = \frac{1016\pi}{15}\text{ units}^{3}$.

## 5.2.2 Washer Method
What if we want to find the volume of a solid between two functions or curves about an axis? We can extend the disk method to find the volume of a hollow solid of revolution.

**Revolution About the x-Axis**
Consider two curves $f(x)$ and $g(x)$. The volume of revolution when the region bounded by two curves in the interval $[a,b]$ revolves about x-axis for $360^{\circ}$. Assume $f(x)\ge g(x)$ for all x in $[a,b]$. The required region is shown below:

![[Pasted image 20260216185420.png]]

The volume of the solid formed by revolving the region about the x-axis is:
> [!formula]
> $V=\pi\int_{a}^{b}\left([f(x)]^{2}-[g(x)]^{2}\right)dx$

**Revolution About the y-Axis**
Consider two curves $x=f(y)$ and $x=g(y)$. The volume of revolution when the region bounded by the two curves in the interval $[c,d]$ revolves about y-axis for $360^{\circ}$. Assume $f(y)\ge g(y)$ for all y in $[c,d]$. The required region is shown below:

![[Pasted image 20260216185436.png]]

The volume of the solid formed by revolving the region about the y-axis is:
> [!formula]
> $V=\pi\int_{c}^{d}\left([f(y)]^{2}-[g(y)]^{2}\right)dy$

> [!example]- Example 5.13
> Determine the volume of the solid generated by rotating the region bounded by $y=\sqrt{x}$ and $y=x^{2}$ about the x-axis.
> ![[Pasted image 20260216185459.png]]
> 
> > [!continue]- Solution
> > **LUSI method**
> > **L: limits and intersections**
> > $x^{2}=\sqrt{x} \Rightarrow x=0, x=1$. Limits: $[0,1]$.
> > **U: upper and lower functions**
> > From $[0,1]$, choose one test value, $x=0.5$.
> > Upper: $y=\sqrt{0.5}$, Lower: $y=0.5^{2}$.
> > $y=\sqrt{x}$ is upper function, $y=x^{2}$ is lower function.
> > **S: subtract lower squared from upper squared**
> > $(\sqrt{x})^{2}-(x^{2})^{2}=x-x^{4}$
> > **I: integrate**
> > $V=\pi\int_{0}^{1}(x-x^{4})dx=\pi\left[\frac{x^{2}}{2}-\frac{x^{5}}{5}\right]_{0}^{1}=\pi\left(\frac{1}{2}-\frac{1}{5}\right)-0=\frac{3\pi}{10}\text{ units}^{3}$

> [!example]- Example 5.14
> Determine the volume of the solid generated by rotating the region bounded by $y=\sqrt[3]{x}$ and $y=\frac{x}{4}$ about the y-axis.
> ![[Pasted image 20260216185514.png]]
> 
> > [!continue]- Solution
> > **LUSI method**
> > **L: limits and intersections**
> > Rewrite in terms of y: $x=y^3$ and $x=4y$.
> > $y^{3}=4y \Rightarrow y^{3}-4y=0 \Rightarrow y(y^{2}-4)=0 \Rightarrow y=0, y=-2, y=2$.
> > Based on the graph (1st quadrant), limits are $[0,2]$.
> > **U: right and left functions**
> > From $[0,2]$, choose one test value, $y=1$.
> > Left: $x=1^{3}=1$, Right: $x=4(1)=4$.
> > $x=4y$ is right function, $x=y^{3}$ is left function.
> > **S: subtract left squared from right squared**
> > $(4y)^{2}-(y^{3})^{2}=16y^{2}-y^{6}$
> > **I: integrate**
> > $V=\pi\int_{0}^{2}(16y^{2}-y^{6})dy=\pi\left[\frac{16y^{3}}{3}-\frac{y^{7}}{7}\right]_{0}^{2}=\pi\left(\frac{16(2)^{3}}{3}-\frac{2^{7}}{7}\right)-0=\frac{512\pi}{21}\text{ units}^{3}$

> [!sq]- Problem 5.6
> a) The shaded region is bounded by the curves $x=y^{2}$ and $x=y+2$. Find the volume of the solid generated when the region is revolved about the y-axis.
> 
> b) The shaded region is bounded by the curves $y=x^{2}$ and $x+y=6$. Find the volume of the solid generated when the region is revolved about the x-axis.
> 
> c) The shaded region is bounded by the curves $y^{2}=x+1$ and $y=1-x$. Find the volume of the solid generated when the region is revolved about the y-axis.
> ![[Pasted image 20260216185558.png]]
> 
> > [!continue]- Solution
> > **a)** Intersections: $y^2 = y+2 \Rightarrow y^2-y-2=0 \Rightarrow (y-2)(y+1)=0 \Rightarrow y=-1, 2$.
> > Right curve: $x=y+2$. Left curve: $x=y^2$.
> > $V = \pi \int_{-1}^{2} ((y+2)^2 - (y^2)^2) dy = \pi \int_{-1}^{2} (y^2+4y+4 - y^4) dy$
> > $= \pi \left[ \frac{y^3}{3} + 2y^2 + 4y - \frac{y^5}{5} \right]_{-1}^{2} = \pi \left( \left(\frac{8}{3} + 8 + 8 - \frac{32}{5}\right) - \left(-\frac{1}{3} + 2 - 4 + \frac{1}{5}\right) \right)$
> > $= \pi \left( \frac{184}{15} - \left(-\frac{32}{15}\right) \right) = \frac{216\pi}{15} = \frac{72\pi}{5}\text{ units}^3$.
> > 
> > **b)** Intersections: $x^2 = 6-x \Rightarrow x^2+x-6=0 \Rightarrow (x+3)(x-2)=0 \Rightarrow x=-3, 2$.
> > Upper curve: $y=6-x$. Lower curve: $y=x^2$.
> > $V = \pi \int_{-3}^{2} ((6-x)^2 - (x^2)^2) dx = \pi \int_{-3}^{2} (36 - 12x + x^2 - x^4) dx$
> > $= \pi \left[ 36x - 6x^2 + \frac{x^3}{3} - \frac{x^5}{5} \right]_{-3}^{2} = \pi \left( \left(72 - 24 + \frac{8}{3} - \frac{32}{5}\right) - \left(-108 - 54 - 9 + \frac{243}{5}\right) \right)$
> > $= \pi \left( \frac{664}{15} - \left(-\frac{1836}{15}\right) \right) = \frac{2500\pi}{15} = \frac{500\pi}{3}\text{ units}^3$.
> > 
> > **c)** Rewrite equations in terms of $y$: $x = y^2-1$ and $x = 1-y$.
> > Intersections: $y^2-1 = 1-y \Rightarrow y^2+y-2=0 \Rightarrow (y+2)(y-1)=0 \Rightarrow y=-2, 1$.
> > Right curve: $x=1-y$. Left curve: $x=y^2-1$.
> > $V = \pi \int_{-2}^{1} ((1-y)^2 - (y^2-1)^2) dy = \pi \int_{-2}^{1} (1-2y+y^2 - (y^4-2y^2+1)) dy = \pi \int_{-2}^{1} (-y^4 + 3y^2 - 2y) dy$
> > $= \pi \left[ -\frac{y^5}{5} + y^3 - y^2 \right]_{-2}^{1} = \pi \left( \left(-\frac{1}{5} + 1 - 1\right) - \left(\frac{32}{5} - 8 - 4\right) \right)$
> > $= \pi \left( -\frac{1}{5} - \left(-\frac{28}{5}\right) \right) = \frac{27\pi}{5}\text{ units}^3$.

## 5.3 TUTORIAL 5

> [!sq]- Question 1 with diagrams
> Find the area of shaded region:
> > [!continue]- a) ![[Pasted image 20260216185911.png]]
> > Area bounded by $y=4-x^{2}$ from $x=0$ to $x=2$.
> > Area = $\int_0^2 (4-x^2) dx = \left[4x - \frac{x^3}{3}\right]_0^2 = 8 - \frac{8}{3} = \frac{16}{3}$.
> 
> > [!continue]- b) ![[Pasted image 20260216185918.png]]
> > Area bounded by $y=x$ and $y=\frac{1}{2}x^{2}$.
> > Intersections: $\frac{1}{2}x^2 = x \Rightarrow x^2-2x=0 \Rightarrow x=0, 2$. 
> > Area = $\int_0^2 (x - \frac{1}{2}x^2) dx = \left[\frac{x^2}{2} - \frac{x^3}{6}\right]_0^2 = 2 - \frac{8}{6} = \frac{2}{3}$.
> 
> > [!continue]- c) ![[Pasted image 20260216185928.png]]
> > Area bounded by $y=x^2+2$ and $x+y=4$.
> > Intersections: $x^2+2 = 4-x \Rightarrow x^2+x-2=0 \Rightarrow x=-2, 1$.
> > Area = $\int_{-2}^1 ((4-x) - (x^2+2)) dx = \int_{-2}^1 (2-x-x^2) dx = \left[2x - \frac{x^2}{2} - \frac{x^3}{3}\right]_{-2}^1 = \frac{7}{6} - (-\frac{10}{3}) = \frac{9}{2}$.
> 
> > [!continue]- d) ![[Pasted image 20260216190001.png]]
> > Area bounded by $y=x$ and $x=5y-y^2$.
> > Intersections: $5y-y^2 = y \Rightarrow y^2-4y=0 \Rightarrow y=0, 4$.
> > Area = $\int_0^4 (5y-y^2 - y) dy = \int_0^4 (4y-y^2) dy = \left[2y^2 - \frac{y^3}{3}\right]_0^4 = 32 - \frac{64}{3} = \frac{32}{3}$.
> 
> > [!continue]- e) ![[Pasted image 20260216190015.png]]
> > Area bounded by $y=-x^2+2x+3$ and $y=x^2-4x+3$.
> > Intersections: $-x^2+2x+3 = x^2-4x+3 \Rightarrow 2x^2-6x=0 \Rightarrow x=0, 3$.
> > Area = $\int_0^3 ((-x^2+2x+3) - (x^2-4x+3)) dx = \int_0^3 (-2x^2+6x) dx = \left[-\frac{2x^3}{3} + 3x^2\right]_0^3 = -18 + 27 = 9$.
> 
> > [!continue]- f) ![[Pasted image 20260216190026.png]]
> > Area bounded by $y=\pm\sqrt{2x+6}$ (which is $x=\frac{y^2}{2}-3$) and $y=x-1$ (which is $x=y+1$).
> > Intersections: $y^2/2-3 = y+1 \Rightarrow y^2-2y-8=0 \Rightarrow y=-2, 4$.
> > Area = $\int_{-2}^4 (y+1 - (y^2/2-3)) dy = \int_{-2}^4 (y+4 - y^2/2) dy = \left[\frac{y^2}{2} + 4y - \frac{y^3}{6}\right]_{-2}^4 = \frac{40}{3} - (-\frac{14}{3}) = 18$.
> 
> > [!continue]- g) ![[Pasted image 20260216190040.png]]
> > Area bounded by $y=4-x^2$ and $y=-2x+4$.
> > Intersections: $4-x^2 = -2x+4 \Rightarrow x^2-2x=0 \Rightarrow x=0, 2$.
> > Area = $\int_0^2 (4-x^2 - (-2x+4)) dx = \int_0^2 (2x-x^2) dx = \left[x^2 - \frac{x^3}{3}\right]_0^2 = 4 - \frac{8}{3} = \frac{4}{3}$.
> 
> > [!continue]- h) ![[Pasted image 20260216190055.png]]
> > Area bounded by $x=y^2-4y+2$ and $x=y-2$.
> > Intersections: $y^2-4y+2 = y-2 \Rightarrow y^2-5y+4=0 \Rightarrow y=1, 4$.
> > Area = $\int_1^4 (y-2 - (y^2-4y+2)) dy = \int_1^4 (-y^2+5y-4) dy = \left[-\frac{y^3}{3} + \frac{5y^2}{2} - 4y\right]_1^4 = \frac{8}{3} - (-\frac{11}{6}) = \frac{9}{2}$.

> [!sq]- Question 2
> Find the volume of the shaded region solid generated when the region from Question 1(g) (bounded by $y=4-x^2$ and $y=-2x+4$) is revolved about the y-axis.
> ![[Pasted image 20260216185732.png]]
> 
> > [!continue]- Solution
> > Use the Washer method with respect to y:
> > Right curve: $x = \sqrt{4-y}$. Left curve: $x = \frac{4-y}{2}$. The bounds are from $y=0$ to $y=4$.
> > $V = \pi \int_0^4 \left( (\sqrt{4-y})^2 - \left(\frac{4-y}{2}\right)^2 \right) dy = \pi \int_0^4 \left( 4-y - \frac{16-8y+y^2}{4} \right) dy$
> > $= \pi \int_0^4 \left( 4-y - 4 + 2y - \frac{y^2}{4} \right) dy = \pi \int_0^4 \left( y - \frac{y^2}{4} \right) dy$
> > $= \pi \left[ \frac{y^2}{2} - \frac{y^3}{12} \right]_0^4 = \pi \left( 8 - \frac{64}{12} \right) = \pi \left( 8 - \frac{16}{3} \right) = \frac{8\pi}{3}\text{ units}^3$.

> [!sq]- Question 3
> Find the volume of the shaded region solid generated when the region from Question 1(d) (bounded by $x=5y-y^2$ and $y=x$) is revolved about the x-axis.
> ![[Pasted image 20260216185750.png]]
> 
> > [!continue]- Solution
> > Using the cylindrical shells method with respect to y (as evaluating with washers wrt x is algebraically difficult here):
> > $V = 2\pi \int_0^4 y (\text{right} - \text{left}) dy = 2\pi \int_0^4 y ((5y-y^2) - y) dy$
> > $= 2\pi \int_0^4 y (4y-y^2) dy = 2\pi \int_0^4 (4y^2 - y^3) dy$
> > $= 2\pi \left[ \frac{4y^3}{3} - \frac{y^4}{4} \right]_0^4 = 2\pi \left( \frac{256}{3} - 64 \right) = 2\pi \left( \frac{256 - 192}{3} \right) = 2\pi \left( \frac{64}{3} \right) = \frac{128\pi}{3}\text{ units}^3$.

> [!sq]- Question 4
> The region R is bounded by the curves $x=5-y^{2}$ and $y=x+1$.
> ![[Pasted image 20260216185804.png]]
> a) Find the coordinates of A and B.
> b) Determine the area of the shaded region R.
> 
> > [!continue]- Solution
> > **a)** Line is $x=y-1$. Equate with curve: $5-y^2 = y-1 \Rightarrow y^2+y-6=0 \Rightarrow (y+3)(y-2)=0 \Rightarrow y=-3, 2$.
> > When $y=-3$, $x = -4$. Point A is $(-4, -3)$.
> > When $y=2$, $x = 1$. Point B is $(1, 2)$.
> > 
> > **b)** Area = $\int_{-3}^2 ((5-y^2) - (y-1)) dy = \int_{-3}^2 (6 - y - y^2) dy$
> > $= \left[ 6y - \frac{y^2}{2} - \frac{y^3}{3} \right]_{-3}^2 = \left( 12 - 2 - \frac{8}{3} \right) - \left( -18 - \frac{9}{2} + 9 \right)$
> > $= \frac{22}{3} - \left( -\frac{27}{2} \right) = \frac{44}{6} + \frac{81}{6} = \frac{125}{6}\text{ units}^2$.

> [!sq]- Question 5
> The diagram shows the region R bounded by two functions $y=x^{2}+1$ and $y=x+7$.
> ![[Pasted image 20260216185823.png]]
> a) Find the area of the region R.
> b) Find the volume of the solid obtained by revolving the region R revolves about x-axis.
> 
> > [!continue]- Solution
> > **a)** Intersections: $x^2+1 = x+7 \Rightarrow x^2-x-6=0 \Rightarrow (x-3)(x+2)=0 \Rightarrow x=-2, 3$.
> > Area = $\int_{-2}^3 ((x+7) - (x^2+1)) dx = \int_{-2}^3 (6 + x - x^2) dx = \left[ 6x + \frac{x^2}{2} - \frac{x^3}{3} \right]_{-2}^3$
> > $= \left( 18 + \frac{9}{2} - 9 \right) - \left( -12 + 2 + \frac{8}{3} \right) = \frac{27}{2} - \left( -\frac{22}{3} \right) = \frac{81}{6} + \frac{44}{6} = \frac{125}{6}\text{ units}^2$.
> > 
> > **b)** $V = \pi \int_{-2}^3 ((x+7)^2 - (x^2+1)^2) dx = \pi \int_{-2}^3 (x^2+14x+49 - (x^4+2x^2+1)) dx$
> > $= \pi \int_{-2}^3 (-x^4 - x^2 + 14x + 48) dx = \pi \left[ -\frac{x^5}{5} - \frac{x^3}{3} + 7x^2 + 48x \right]_{-2}^3$
> > $= \pi \left( \left( -\frac{243}{5} - 9 + 63 + 144 \right) - \left( \frac{32}{5} + \frac{8}{3} + 28 - 96 \right) \right)$
> > $= \pi \left( \frac{747}{5} - \left( -\frac{884}{15} \right) \right) = \pi \left( \frac{2241 + 884}{15} \right) = \frac{3125\pi}{15} = \frac{625\pi}{3}\text{ units}^3$.

