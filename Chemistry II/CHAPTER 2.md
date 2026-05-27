$$\underline{\Huge\text{CHEMICAL KINETICS}}$$
# 2.1 Fundamentals of Reaction Rates

## Definition of Reaction Rate

> [!definition]- Chemical Kinetics
> The study of the rate (speed) at which chemical reactions occur.

> [!definition]- Reaction Rate
> The change in the amount (concentration) of reactants or products with time.
> * Reactants are $\color{orange}i$ over time.
> * Products are $\color{orange}ii$ over time.
> 
> > [!blank]- $\color{orange}i$
> > consumed (concentration decreases)
> 
> > [!blank]- $\color{orange}ii$
> > formed (concentration increases)

> [!formula]- Average Rate
> $Rate = \frac{\Delta [Concentration]}{\Delta Time} = \frac{[A]_{final} - [A]_{initial}}{t_{final} - t_{initial}}$
> > [!unit]- $[A]$
> > Concentration of substance A in $mol\,L^{-1}$ or $M$
> 
> > [!unit]- $t$
> > Time in seconds ($s$), minutes, etc.

> [!liststart]- Graph rates
> > [!graph]- Concentration to reaction time
> > ![[Pasted image 20260205154936.png]]
> > > [!continue]- Reactant Curve
> > > Slopes ||downwards|| (negative slope). Concentration decreases.
> > 
> > > [!continue]- Product Curve
> > > Slopes ||upwards|| (positive slope). Concentration increases.
> > 
> > > [!continue]- Instantaneous Rate
> > > The rate at a specific moment in time.
> > > It is equal to the ||slope of the tangent|| to the curve at time $t$.
> 
> > [!graph]- Relation between rate and reaction time
> > ![[Pasted image 20260205155428.png]]
> > > [!continue]- Forward Reaction Curve
> > > Slopes ||downwards|| (negative slope). 
> > > Rate of forward reaction ||decreases|| over time
> > 
> > > [!continue]- Reverse Reaction Curve
> > > Slopes ||upwards|| (positive slope). The rate of reverse reaction ||increases|| over time.
> > 
> > > [!continue]- At equilibrium
> > > The rate at a specific moment in time.
> > > the rate of reactants $=$ rate of products

## Rate Expressions & Stoichiometry

> [!formula]- General Rate Expression
> For a generic reaction: $aA + bB \rightarrow cC + dD$
> The overall rate of reaction is related to the rates of individual species by their stoichiometric coefficients.
> > [!formula]- Rate of reduction of reactant $A$
> > $R_{A}=\frac{[A]_\text{final}-[A]_\text{initial}}{t_\text{final}-t_\text{initial}}=\frac{[A]_{t}-[A]_{o}}{\Delta t}=- \frac{d[A]}{dt}$
> > > [!unit]- $[A]$
> > > the concentration of $A$
> > 
> > > [!unit]- $t$
> > > time in $t$
> > 
> > > [!unit]- $-$
> > > decrease in value
> 
> > [!formula]- Rate of increase of product $B$
> > $R_{B}=\frac{[B]_\text{final}-[B]_\text{initial}}{t_\text{final}-t_\text{initial}}=+\frac{d[B]}{dt}$
> > > [!unit]- $[B]$
> > > the concentration of $B$
> > 
> > > [!unit]- $+$
> > > increase in value
> 
> > [!formula]- Overall rate of reaction
> > $R=-\frac{1}{a} \frac{d[A]}{dt}=+\frac{1}{b} \frac{d[B]}{dt}$
> 
> > [!formula]- For complex reactions
> > $\ce{aA +bB->cC +dD}$
> 
> > [!formula]- Overall rate
> > $R= - \frac{1}{a} \frac{d[A]}{dt}=- \frac{1}{b} \frac{d[B]}{dt}=+\frac{1}{c} \frac{d[C]}{dt}=+\frac{1}{d} \frac{d[D]}{dt}$
> 
> > [!info]- Signs
> > * **Negative (-):** Indicates rate of ||disappearance/reduction|| (Reactants).
> > * **Positive (+):** Indicates rate of ||appearance/formation|| (Products).

> [!sq]- Sample Problem A: Generic Reaction
> Reaction: $2A + B \rightarrow C + 3D$.
> Given: Rate of reduction of A is $2.6 \times 10^{-4}\,M\,s^{-1}$.
> ($-\frac{d[A]}{dt} = 2.6 \times 10^{-4}$)
> > [!continue]- (i) Determine the rate of reaction.
> > $Rate = \frac{1}{2} \times (\text{Rate of reduction of A})$
> > $Rate = \frac{1}{2} (2.6 \times 10^{-4})$
> > $\enclose{box}{Rate = 1.3 \times 10^{-4}\,M\,s^{-1}}$
> 
> > [!continue]- (ii) Determine the rate of formation of D.
> > Rate of formation of D $= \frac{d[D]}{dt}$.
> > From stoichiometry: $Rate = \frac{1}{3} \frac{d[D]}{dt}$
> > $\frac{d[D]}{dt} = 3 \times Rate = 3 \times (1.3 \times 10^{-4})$
> > $\enclose{box}{\text{Rate of D} = 3.9 \times 10^{-4}\,M\,s^{-1}}$
> 
> > [!continue]- (iii) Time for A to reduce from 0.5 M to 0.49 M.
> > $\Delta [A] = 0.49 - 0.50 = -0.01\,M$.
> > Rate of reduction of A $= -\frac{\Delta [A]}{\Delta t} = 2.6 \times 10^{-4}$.
> > $\frac{0.01}{\Delta t} = 2.6 \times 10^{-4}$
> > $\Delta t = \frac{0.01}{2.6 \times 10^{-4}}$
> > $\enclose{box}{t \approx 38.5\,s}$

> [!sq]- Sample Problem B: Rate Calculation
> Reaction: $A + B \rightarrow 2C$.
> Given: Rate of reaction $= 2.5 \times 10^{-5}\,M\,s^{-1}$. Initial $[A]_0 = 0.5\,M$.
> > [!continue]- (i) Rate of formation of C.
> > $Rate = \frac{1}{2} \frac{d[C]}{dt}$
> > $\frac{d[C]}{dt} = 2 \times Rate = 2(2.5 \times 10^{-5})$
> > $\enclose{box}{5.0 \times 10^{-5}\,M\,s^{-1}}$
> 
> > [!continue]- (ii) Concentration of A after 1 minute.
> > $t = 60\,s$.
> > Rate of reduction of A $= -\frac{\Delta [A]}{\Delta t} = 2.5 \times 10^{-5}$ (Coefficient is 1).
> > Change in $[A] = -(Rate \times t) = -(2.5 \times 10^{-5} \times 60) = -0.0015\,M$.
> > $[A]_{final} = [A]_0 + \Delta [A] = 0.5 - 0.0015$
> > $\enclose{box}{[A]_{final} = 0.4985\,M}$

# 2.2 Rate Laws & Order of Reaction

> [!definition]- The Rate Law
> An equation that relates the reaction rate to the concentrations of reactants.

> [!formula]- The Rate Law
> $Rate = k[A]^x[B]^y$
> > [!unit]- **$k$**: Rate constant (depends on temperature).
> 
> > [!unit]- $x$
> > Order with respect to reactant $A$.
> 
> > [!unit]- $y$
> > Order with respect to reactant $B$
> 
> > [!unit]- $x+y$
> > Overall order of the reaction

> [!info]- Important Note
> Rate laws are determined by $\color{orange}i$ and are not necessarily related to the $\color{orange}ii$ of the balanced equation.
> > [!blank]- $\color{orange}i$
> > experiment
> 
> > [!blank]- $\color{orange}ii$
> > stoichiometry

## Method of Initial Rates

> [!procedure]- Determining Rate Law from Data
> 1.  Identify two experiments where the concentration of **one reactant changes** while the others stay **constant**.
> 2.  Compare the ratio of rates to the ratio of concentrations to find the order ($x$ or $y$).
>       $(\frac{Rate_2}{Rate_1}) = (\frac{[A]_2}{[A]_1})^x$
> 3.  Repeat for other reactants.
> 4.  Substitute values from any experiment into the rate law to solve for $k$.

> [!sq]- Example: $2NO(g) + Br_2(g) \rightarrow 2NOBr$
> **Data provided:**
> * Exp 1: [NO]=0.1, [Br2]=0.1, Rate=12
> * Exp 2: [NO]=0.1, [Br2]=0.2, Rate=24
> * Exp 3: [NO]=0.2, [Br2]=0.1, Rate=48
> 
> > [!continue]- Step 1: Find order for $Br_2$ ($y$)
> > Compare Exp 1 & 2 ([NO] is constant).
> > $\frac{Rate_2}{Rate_1} = \frac{24}{12} = 2$.
> > $\frac{[Br_2]_2}{[Br_2]_1} = \frac{0.2}{0.1} = 2$.
> > $2 = 2^y \implies y = 1$.
> > Order with respect to $Br_2$ is ||1||.
> 
> > [!continue]- Step 2: Find order for $NO$ ($x$)
> > Compare Exp 1 & 3 ([Br2] is constant).
> > $\frac{Rate_3}{Rate_1} = \frac{48}{12} = 4$.
> > $\frac{[NO]_3}{[NO]_1} = \frac{0.2}{0.1} = 2$.
> > $4 = 2^x \implies 2^2 = 2^x \implies x = 2$.
> > Order with respect to $NO$ is ||2||.
> 
> > [!continue]- Step 3: Write Rate Law
> > $\enclose{box}{Rate = k[NO]^2[Br_2]}$
> > Overall order $= 2 + 1 =$ ||3||.
> 
> > [!continue]- Step 4: Calculate Rate Constant ($k$)
> > Using Exp 1: $12 = k(0.1)^2(0.1)$.
> > $12 = k(0.001)$.
> > $k = \frac{12}{0.001} = 1.2 \times 10^4$.
> > Units: $Rate / (M^2 \cdot M) = M\,s^{-1} / M^3 = M^{-2}\,s^{-1}$.
> > $\enclose{box}{k = 1.2 \times 10^4\,M^{-2}\,s^{-1}}$

> [!sq]- Calculation: Rate at New Concentration
> Calculate rate when $[NO] = 0.013\,M$ and $[Br_2] = 0.075\,M$.
> > [!continue]- Solution
> > $Rate = k[NO]^2[Br_2]$
> > $Rate = (1.2 \times 10^4)(0.013)^2(0.075)$
> > $Rate = (12000)(0.000169)(0.075)$
> > $\enclose{box}{Rate = 0.15\,M\,s^{-1}}$

# 2.3 Integrated Rate Laws (Concentration vs Time)

> [!info]- Context
> While the **Rate Law** tells us how rate depends on concentration ($Rate \propto [A]$), the **Integrated Rate Law** tells us how concentration depends on $\color{orange}i$.
> > [!blank]- $\color{orange}i$
> > time

## First Order Reaction

> [!definition]- Definition
> A reaction where the rate depends on the concentration of a single reactant raised to the first power.
> $Rate = k[A]^1$

> [!formula]- Derivation
> Starting from the differential rate law:
> $-\frac{d[A]}{dt} = k[A] \implies \frac{1}{[A]} d[A] = -k dt$
> Integrating from $t=0$ to $t$:
> $\int_{[A]_0}^{[A]_t} \frac{1}{[A]} d[A] = -k \int_{0}^{t} dt$

> [!formula]- Integrated Rate Equation (First Order)
> $\ln[A]_t - \ln[A]_0 = -kt$
> > [!formula]- Alternative Forms
> > $\ln\left(\frac{[A]_t}{[A]_0}\right) = -kt$
> > $\ln[A]_t = -kt + \ln[A]_0$ (Linear Form $y = mx + c$)
> 
> > [!unit]- $[A]_t$
> > Concentration at time $t$
> 
> > [!unit]- $[A]_0$
> > Initial concentration ($t=0$)
> 
> > [!unit]- $k$
> > Rate constant ($unit: s^{-1}$)
> 
> > [!unit]- $t$
> > Time elapsed

> [!graph]- First Order Plot
> ![[Pasted image 20260205184318.png]]
> > [!continue]- Axes
> > Plot $\ln[A]_t$ (y-axis) versus $t$ (x-axis).
> 
> > [!continue]- Slope
> > The graph is a straight line with a negative slope.
> > $Slope = -k$
> 
> > [!continue]- Y-Intercept
> > The intercept is $\ln[A]_0$.

> [!formula]- Half-Life ($t_{1/2}$)
> The time required for the concentration to reduce to half its initial value ($[A]_t = \frac{1}{2}[A]_0$).
> Substituting into the integrated law:
> $\ln\left(\frac{0.5[A]_0}{[A]_0}\right) = -kt_{1/2} \implies \ln(0.5) = -kt_{1/2}$
> > [!formula]- Equation
> > $t_{1/2} = \frac{0.693}{k}$
> > 
> > > [!info]- Characteristic
> > > For 1st order, half-life is **independent** of ||initial concentration||.

## Second Order Reaction

> [!definition]- Definition
> A reaction where the rate depends on the reactant concentration raised to the second power.
> $Rate = k[A]^2$

> [!formula]- Integrated Rate Equation (Second Order)
> Starting from $-\frac{d[A]}{dt} = k[A]^2$:
> $\frac{1}{[A]_t} - \frac{1}{[A]_0} = kt$
> > [!formula]- Linear Form
> > $\frac{1}{[A]_t} = kt + \frac{1}{[A]_0}$ ($y = mx + c$)
> 
> > [!unit]- $[A]_t$
> > Concentration at time $t$
> 
> > [!unit]- $k$
> > Rate constant ($unit: M^{-1}s^{-1}$)

> [!graph]- Second Order Plot
> ![[Pasted image 20260205184607.png]]
> > [!continue]- Axes
> > Plot $\frac{1}{[A]_t}$ (y-axis) versus $t$ (x-axis).
> 
> > [!continue]- Slope
> > The graph is a straight line with a positive slope.
> > $Slope = +k$
> 
> > [!continue]- Y-Intercept
> > The intercept is $\frac{1}{[A]_0}$.

> [!formula]- Half-Life ($t_{1/2}$)
> Substituting $[A]_t = \frac{1}{2}[A]_0$:
> $\frac{1}{0.5[A]_0} - \frac{1}{[A]_0} = kt_{1/2} \implies \frac{2}{[A]_0} - \frac{1}{[A]_0} = kt_{1/2}$
> > [!formula]- Equation
> > $t_{1/2} = \frac{1}{k[A]_0}$
> > 
> > > [!info]- Characteristic
> > > Half-life is **inversely proportional** to ||initial concentration||. (Higher conc = shorter half-life).

## Zero Order Reaction

> [!definition]- Definition
> A reaction where the rate is independent of the concentration of the reactant.
> $Rate = k[A]^0 = k$

> [!formula]- Integrated Rate Equation (Zero Order)
> $[A]_t - [A]_0 = -kt$
> > [!formula]- Linear Form
> > $[A]_t = -kt + [A]_0$
> > 
> > > [!unit]- $k$
> > > Rate constant ($unit: M\,s^{-1}$)

> [!graph]- Zero Order Plot
> > [!continue]- Axes
> > Plot $[A]_t$ versus $t$.
> 
> > [!continue]- Slope
> > Straight line with negative slope.
> > $Slope = -k$

> [!formula]- Half-Life ($t_{1/2}$)
> $t_{1/2} = \frac{[A]_0}{2k}$
> > [!info]- Characteristic
> > Half-life is **directly proportional** to ||initial concentration||.

> [!sq]- Problem: Determine rate law expression
> The rate constant for the decomposition of $\ce{N_{2}O_{5}}$ is $5.1\times 10^{-4}\,s ^{-1}$ at $318K$. The reaction is $1^{st}$ order with respect to $\ce{N_{2}O_{5}}$
> > [!continue]- What is the rate law expression?
> 
> > [!continue]- If the initial concentration of $\ce{N_{2}O_{5}}$ is $1.0\times 10^{-2}mol\,L^{-1}$, what will the concentration be after $10.0\,min$?
## Sample Problems

> [!sq]- Problem: First Order Decomposition
> Reaction: $2N_2O_5 \rightarrow 4NO_2 + O_2$.
> Given: $k = 5.1 \times 10^{-4}\,s^{-1}$, $[A]_0 = 1.0 \times 10^{-2}\,M$.
> > [!continue]- (a) Rate Law Expression
> > Since it is first order:
> > $Rate = k[N_2O_5]^1 = (5.1 \times 10^{-4})[N_2O_5]$
> 
> > [!continue]- (b) Concentration after 10.0 minutes
> > $t = 10.0\,min = 600\,s$.
> > Using integrated law: $\ln[A]_t = -kt + \ln[A]_0$
> > $\ln[A]_t = -(5.1 \times 10^{-4})(600) + \ln(1.0 \times 10^{-2})$
> > $\ln[A]_t = -0.306 + (-4.605) = -4.911$
> > $[A]_t = e^{-4.911}$
> > $\enclose{box}{[A]_t = 7.36 \times 10^{-3}\,M}$

> [!sq]- Problem: Determining Order from Data (Calculation Method)
> Data provided for concentration $(a-x)$ at different times.
> 
> | Time (minutes) | 0    | 4    | 6    | 10   | 15   | 20   |
> | :--------------: | :----: | :----: | :----: | :----: | :----: | :----: |
> | $(a-x)(M)$     | 8.04 | 5.30 | 4.58 | 3.50 | 2.74 | 2.22 |
> 
> > [!continue]- (i) Prove reaction is Second Order
> > Use the formula $k = \frac{1}{t}(\frac{1}{[A]_t} - \frac{1}{[A]_0})$ for each point.
> > * **At t=4:** $k_1 = \frac{1}{4}(\frac{1}{5.30} - \frac{1}{8.04}) \approx 1.6 \times 10^{-2}$
> > * **At t=6:** $k_2 = \frac{1}{6}(\frac{1}{4.58} - \frac{1}{8.04}) \approx 1.6 \times 10^{-2}$
> > * **At t=10:** $k_3 = \frac{1}{10}(\frac{1}{3.50} - \frac{1}{8.04}) \approx 1.6 \times 10^{-2}$
> > Since $k$ is constant, the reaction is ||second order||.
> 
> > [!continue]- (ii) Determine Rate Constant
> > Average $k = \frac{1.6 + 1.6 + 1.6}{3} \times 10^{-2}$
> > $\enclose{box}{k = 1.6 \times 10^{-2}\,M^{-1}min^{-1}}$

> [!sq]- Problem: Determining Order from Data (Graphical Method)
> Dimerization of $C_4H_6$. Data given for $[C_4H_6]$ vs Time.
> 
> | $\ce{[C_{4}H_{6}]}(M)$ | Time $(s)$ |
> | ---------------------- | ---------- |
> | 0.01000                | 0          |
> | 0.00625                | 1000       |
> | 0.00476                | 1800       |
> | 0.00370                | 2800       |
> | 0.00313                | 3600       |
> | 0.00270                | 4400       |
> | 0.00241                | 5200       |
> | 0.00208                | 6200       |
> 
> > [!continue]- (i) Determine Order
> > 
> > | $\ce{[C_{4}H_{6}]}(M)$ | $\frac{1}{[\ce{C_{4}H_{6}}]}(M^{-1})$ | $\ln \ce{[C_{4}H_{6}]}$ | Time $(s)$ |
> > | ---------------------- | ------------------------------------- | ----------------------- | ---------- |
> > | 0.01000                | 100                                   | -4.605                  | 0          |
> > | 0.00625                | 160                                   | -5.075                  | 1000       |
> > | 0.00476                | 210                                   | -5.348                  | 1800       |
> > | 0.00370                | 270                                   | -5.599                  | 2800       |
> > | 0.00313                | 320                                   | -5.767                  | 3600       |
> > | 0.00270                | 370                                   | -5.915                  | 4400       |
> > | 0.00241                | 415                                   | -6.028                  | 5200       |
> > | 0.00208                | 481                                   | -6.175                  | 6200       |
> > 
> > > [!graph]- Plot $\ln[\ce{C_{4}H_{6}}]$
> > > ![[Pasted image 20260205191438.png]]
> > 
> > > [!graph]- Plot $\frac{1}{\ce{[C_{4}H_{6}]}}$ against time
> > > ![[Pasted image 20260205191508.png]]
> 
> > [!continue]- (ii) Value of Rate Constant
> > $k = Slope$ of the $\frac{1}{[A]}$ vs $t$ graph.
> > From data points (e.g., $t=0, y=100$; $t=6200, y=481$).
> > $Slope = \frac{481 - 100}{6200 - 0} = \frac{381}{6200}$
> > $\enclose{box}{k \approx 6.15 \times 10^{-2}\,M^{-1}s^{-1}}$
> 
> > [!continue]- (iii) What is the half-life of the reaction?
> > Half-life, $t_{\frac{1}{2}}=\frac{1}{k[A]_{0}}$
> > $t_{\frac{1}{2}}=\frac{1}{(6.25\times 10^{-2}M^{-1}s ^{-1})(0.01M)}$
> > $\enclose{box}{t_{\frac{1}{2}}=1600s}$

# 2.4 Collision Theory & Factors Affecting Rate

> [!definition]- Collision Theory
> For molecules to react, they must:
> 1.  Experience $\color{orange}i$ collision.
> 2.  Have the right amount of $\color{orange}ii$.
> 3.  Have the right $\color{orange}iii$.
> 
> > [!blank]- $\color{orange}i$
> > effective
> 
> > [!blank]- $\color{orange}ii$
> > energy (Activation Energy, $E_a$)
> 
> > [!blank]- $\color{orange}iii$
> > geometry (orientation)

> [!mnemonic]- Factors Influencing Rate
> $\textcolor[RGB]{255,0,255}{\text{Con}}$nie $\textcolor[RGB]{255,0,255}{\text{Temp}}$ts $\textcolor[RGB]{255,0,255}{\text{Surf}}$ing $\textcolor[RGB]{255,0,255}{\text{Cat}}$s
> > [!mnemonic-points]- $\mathbf{\textcolor[RGB]{255,255,0}{\text{Con}}}$nie
> > **${\textcolor[RGB]{255,0,255}{\textbf{Con}}}$centration**
> > Increasing concentration (of gases/solutions) allows for:
> > * More ||collisions||.
> > * More ||correct geometry|| instances.
>
> > [!mnemonic-points]- $\mathbf{\textcolor[RGB]{255,255,0}{\text{Temp}}}$ts
> > **${\textcolor[RGB]{255,0,255}{\textbf{Temp}}}$erature**
> > > [!graph]- Energy profile diagram
> > > ![[Pasted image 20260205191927.png]]
> >
> > Increasing temperature increases:
> > * The ||frequency|| of collisions.
> > * The ||energy|| of collisions.
>
> > [!mnemonic-points]- $\mathbf{\textcolor[RGB]{255,255,0}{\text{Surf}}}$ing
> > **${\textcolor[RGB]{255,0,255}{\textbf{Surf}}}$ace Area**
> > Increasing surface area (of solids) allows for:
> > * More ||contact|| between reacting materials.
> > * Better chance for ||correct geometry||.
>
> > [!mnemonic-points]- $\mathbf{\textcolor[RGB]{255,255,0}{\text{Cat}}}$s
> > **${\textcolor[RGB]{255,0,255}{\textbf{Cat}}}$alyst**
> > > [!graph]- Energy profile diagram
> > > ![[Pasted image 20260205191958.png]]
> >
> > A substance that increases rate but is not consumed.
> > * It lowers the ||activation energy|| ($E_a$).
> > * Molecules collide at a ||lower minimum energy||.

> [!graph]- Reaction Profiles
> > [!graph]- Exothermic Profile
> > ![[Pasted image 20260205191927.png]]
> > > [!continue]- Energy Change
> > > Products have ||lower|| energy than reactants.
> > 
> > > [!continue]- Activation Energy ($E_a$)
> > > The ||minimum collision energy|| required for reaction.
> 
> > [!graph]- Catalyst Effect
> > ![[Pasted image 20260205191958.png]]
> > > [!continue]- Mechanism
> > > Catalyst provides an alternative path with ||lower $E_a$||.

# 2.5 The Arrhenius Equation

> [!definition]- Arrhenius Equation
> Relates collision frequency, activation energy, and temperature to the rate constant.

> [!formula]- Exponential Form
> $k = Ae^{-(E_a/RT)}$
> > [!unit]- $k$
> > Rate constant
> 
> > [!unit]- $A$
> > Frequency factor (collision frequency)
> 
> > [!unit]- $E_a$
> > Activation Energy in $J\,mol^{-1}$
> 
> > [!unit]- $R$
> > Gas constant ($8.314\,J\,mol^{-1}\,K^{-1}$)
> 
> > [!unit]- $T$
> > Temperature in Kelvin ($K$)

> [!formula]- Linear Form (Arrhenius Plot)
> $\ln k = -\frac{E_a}{RT} + \ln A$
> > [!graph]- Plot of $\ln k$ vs $1/T$
> > ![[Pasted image 20260205192528.png]]
> > > [!continue]- Slope
> > > $Slope = -\frac{E_a}{R}$
> > 
> > > [!continue]- Y-Intercept
> > > $Intercept = \ln A$

> [!formula]- Two-Point Form
> Used to calculate $E_a$ or $k$ at a different temperature.
> $\ln\left(\frac{k_2}{k_1}\right) = \frac{E_a}{R} \left( \frac{T_2 - T_1}{T_1 T_2} \right)$
> > [!unit]- $k_1, k_2$
> > Rate constants at $T_1$ and $T_2$

> [!sq]- Sample Problem A: Calculating $k$ at different T
> Reaction: $2N_2O_5 \rightarrow 4NO_2 + O_2$.
> Given: $k_1 = 5.1 \times 10^{-4}\,s^{-1}$ at $T_1 = 318\,K$. $E_a = 100\,kJ\,mol^{-1}$.
> Find $k_2$ at $T_2 = 400\,K$.
> > [!continue]- Solution
> > **Step 1: Setup Equation**
> > $\ln\left(\frac{k_2}{5.1 \times 10^{-4}}\right) = \frac{100 \times 10^3}{8.314} \left( \frac{400 - 318}{400 \times 318} \right)$
> > 
> > **Step 2: Calculate Right Side**
> > $\frac{100,000}{8.314} \times \frac{82}{127,200} = 12027.9 \times 0.0006446 \approx 7.75$
> > 
> > **Step 3: Solve for $k_2$**
> > $\ln(k_2) - \ln(5.1 \times 10^{-4}) = 7.75$
> > $\ln(k_2) - (-7.58) = 7.75 \implies \ln(k_2) = 0.17$
> > $k_2 = e^{0.17} \approx 1.19\,s^{-1}$ (Check magnitude: Higher T should give higher k. $1.19 \gg 10^{-4}$. Correct).

> [!sq]- Sample Problem B: Calculating $E_a$ and $A$
> Given: $t_{1/2} = 60\,min$ at $30^\circ C$ ($303\,K$) and $30\,min$ at $35^\circ C$ ($308\,K$).
> Reaction is **Second Order** ($A \rightarrow B + C$). $P_A^0 = 0.1\,atm$.
> > [!continue]- (i) Calculate $E_a$
> > **Step 1: Find Rate Constants ($k$)**
> > For 2nd order: $t_{1/2} = \frac{1}{k[A]_0}$. Thus $k \propto \frac{1}{t_{1/2}}$.
> > $k_1 = \frac{1}{60[A]_0}$, $k_2 = \frac{1}{30[A]_0}$.
> > Ratio $\frac{k_2}{k_1} = \frac{60}{30} = 2$.
> > 
> > **Step 2: Arrhenius Equation**
> > $\ln(2) = \frac{E_a}{8.314} \left( \frac{308 - 303}{308 \times 303} \right)$
> > $0.693 = \frac{E_a}{8.314} \left( \frac{5}{93324} \right)$
> > $E_a = \frac{0.693 \times 8.314 \times 93324}{5} = 107,532\,J/mol$
> > $\enclose{box}{E_a = 107.5\,kJ/mol}$
> 
> > [!continue]- (ii) Calculate $A$
> > Using $T_1 = 303\,K$ and $k_1$:
> > need actual value of $k_1$.
> > $[A]_0 \propto P_A^0 = 0.1\,atm$. PV=nRT $\implies [A] = P/RT$.
> > $[A]_0 = \frac{0.1}{(0.0821)(303)} \approx 0.004\,M$.
> > $k_1 = \frac{1}{60(0.004)} \approx 4.16\,M^{-1}min^{-1}$.
> > $\ln(4.16) = \ln A - \frac{107532}{8.314(303)}$
> > $1.42 = \ln A - 42.69$
> > $\ln A = 44.11 \implies A = e^{44.11} \approx 1.4 \times 10^{19}$

# 2.6 Reaction Mechanisms

> [!definition]- Reaction Mechanism
> The set of steps by which a chemical reaction proceeds.
> * **Elementary Step:** A step describing an actual single collision between molecules.
> * **Intermediate:** A species formed in one step and consumed in another (does not appear in overall equation).

> [!definition]- Rate Determining Step (RDS)
> The ||slowest|| step in the mechanism. It determines the rate of the ||overall reaction||.

> [!sq]- Example: $2NO + 2H_2 \rightarrow N_2 + 2H_2O$
> **Mechanism:**
> 1.  $2NO \rightarrow N_2O_2$ (Fast)
> 2.  $N_2O_2 + H_2 \rightarrow N_2O + H_2O$ (Slow / RDS)
> 3.  $N_2O + H_2 \rightarrow N_2 + H_2O$ (Fast)
> 
> > [!continue]- Intermediates
> > $N_2O_2$ and $N_2O$ (Produced then consumed).
> 
> > [!continue]- Rate Law
> > Based on Slow Step: $Rate = k_2 [N_2O_2][H_2]$.
> > Since $N_2O_2$ is an intermediate, use equilibrium from Step 1:
> > $[N_2O_2] = K_{eq}[NO]^2$.
> > Substitute: $Rate = k'[NO]^2[H_2]$.