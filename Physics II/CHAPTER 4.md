$$\underline{\Huge\text{DC CIRCUITS}}$$

# 4.1 EMF and Terminal Voltage

> [!continue]- Electric circuits need a battery or generator to produce current
> these are called sources of $\color{orange}i$.
> > [!blank]- $\color{orange}i$
> > emf (electromotive force)

> [!definition]- Electromotive Force (emf), $\mathcal{E}$
> The energy provided by the source (battery/cell) to each unit charge that flows through the external and internal resistances.

> [!definition]- Terminal Potential Difference (Voltage), $V_{ab}$
> The work done in bringing a unit (test) charge from the negative to the positive terminals of the battery through the external resistance only.

> [!formula]- Relationship between EMF and Terminal Voltage
> Batteries have a small internal resistance ($r$) which reduces the actual voltage.
> $V_{ab} = \mathcal{E} - Ir$
> > [!formula]- Rearranged
> > $\mathcal{E} = V_{ab} + Ir = I(R + r)$
>
> > [!unit]- $\mathcal{E}$
> > Electromotive force in Volts ($V$)
>
> > [!unit]- $V_{ab}$
> > Terminal voltage in Volts ($V$)
>
> > [!unit]- $I$
> > Current in Amperes ($A$)
>
> > [!unit]- $r$
> > Internal resistance of the battery in Ohms ($\Omega$)
>
> > [!unit]- $R$
> > Total external resistance in Ohms ($\Omega$)
>
> > [!unit]- $Ir$
> > Internal voltage drop

> [!picture]- Internal Resistance Model
> ![[Pasted image 20260131142409.png]]

> [!sq]- Example 1: Basic EMF Calculation
> A battery has an emf of $9.0\,V$ and an internal resistance of $6.0\,\Omega$.
> > [!continue]- $a)$ Determine the potential difference across its terminals when it is supplying a current of $0.50\,A$.
> > $\mathcal{E} = 9.0\,V$, $r = 6.0\,\Omega$, $I = 0.50\,A$
> > $V = \mathcal{E} - Ir$
> > $V = 9.0 - (0.50)(6.0)$
> > $V = 9.0 - 3.0$
> > $\enclose{box}{V = 6.0\,V}$
>
> > [!continue]- $b)$ Determine the maximum current which the battery could supply.
> > Current is maximum when external resistance $R=0$ (short circuit).
> > $\mathcal{E} = I_{max}(r)$
> > $I_{max} = \frac{\mathcal{E}}{r} = \frac{9.0}{6.0}$
> > $\enclose{box}{I_{max} = 1.5\,A}$

> [!sq]- Example 4.1: Battery with internal resistance
> A $65.0\,\Omega$ resistor is connected to the terminals of a battery whose emf is $12.0\,V$ and whose internal resistance is $0.5\,\Omega$.
> ![[Pasted image 20260131150203.png]]
> > [!continue]- $a)$ Calculate the current in the circuit.
> > $R = 65.0\,\Omega$, $\mathcal{E} = 12.0\,V$, $r = 0.5\,\Omega$
> > $\mathcal{E} = I(R + r)$
> > $I = \frac{\mathcal{E}}{R + r} = \frac{12.0}{65.0 + 0.5}$
> > $I = \frac{12.0}{65.5}$
> > $\enclose{box}{I = 0.183\,A}$
>
> > [!continue]- $b)$ Calculate the terminal voltage of the battery, $V_{ab}$.
> > $V_{ab} = \mathcal{E} - Ir$
> > $V_{ab} = 12.0 - (0.1832)(0.5)$
> > $\enclose{box}{V_{ab} = 11.9\,V}$
> > *Alternative:* $V_{ab} = IR = (0.1832)(65.0) = 11.9\,V$
>
> > [!continue]- $c)$ Calculate the power dissipated in the resistor $R$ and in the battery's internal resistance $r$.
> > **In Resistor R:**
> > $P_R = I^2 R = (0.1832)^2 (65.0)$
> > $\enclose{box}{P_R = 2.18\,W}$
> >
> > **In Internal Resistance r:**
> > $P_r = I^2 r = (0.1832)^2 (0.5)$
> > $\enclose{box}{P_r = 0.017\,W}$

# 4.2 Resistors in Series and Parallel

## Resistors in Series
> [!info]- Symbol of resistor
> $\bullet\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.12em}^{\tiny\text{/}}\hspace{-0.em}\hspace{-0.14em}\text{\\}\hspace{-0.14em}/\hspace{-0.14em}\text{\\}\hspace{-0.14em}/\hspace{-0.14em}\text{\\}\hspace{-0.14em}/\hspace{-0.14em}\text{\\}\hspace{-0.14em}/\hspace{-0.14em}\text{\\}\hspace{-0.14em}/\hspace{-0.14em}\text{\\}\hspace{-0.12em}_{^{\text{/}}}\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}\bullet$ or $\bullet\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.1em}\enclose{box}{‎ \hspace{4em}}\hspace{-0.3em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}-\hspace{-0.4em}\bullet$

> [!liststart]- Characteristics of resistors in series
> ![[Pasted image 20260131145458.png]]
> > [!continue]- Current
> > The same current flows through each resistor.
> > $I = I_1 = I_2 = I_3$
>
> > [!continue]- Voltage
> > The total potential difference is the sum of the potential differences across each resistor.
> > $V = V_1 + V_2 + V_3$

> [!formula]- Effective Resistance (Series)
> $R_{eff} = R_1 + R_2 + R_3 + \dots + R_n$

## Resistors in Parallel


> [!liststart]- Characteristics of resistors in parallel
> ![[Pasted image 20260131145733.png]]
> > [!continue]- Voltage
> > The potential difference across each resistor is the same.
> > $V = V_1 = V_2 = V_3$
>
> > [!continue]- Current
> > The total current is the sum of the currents through each branch.
> > $I = I_1 + I_2 + I_3$

> [!formula]- Effective Resistance (Parallel)
> $\frac{1}{R_{eff}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + \dots + \frac{1}{R_n}$

> [!tip]- For voltage understanding
> The electron wears out after hitting here and there, causing the voltage drop. In a series, a single electron has to go through both journey of hitting everywhere, while in a parallel, since electron splits, it only go through once on the journey of hitting it's head everywhere

> [!continue]- Water Analogy
> 
> The water (current) splits into two streams; each falls the same height (voltage), and the total current is the sum of the two.

> [!sq]- Example 4.2: Circuit with series and parallel resistors
> How much current is drawn from the battery shown?
> ![[Pasted image 20260131145943.png]]
> > [!continue]- Solution
> > **Step 1: Simplify Parallel Block ($500\,\Omega$ and $700\,\Omega$)**
> > $\frac{1}{R_p} = \frac{1}{500} + \frac{1}{700}$
> > $\frac{1}{R_p} = 0.002 + 0.00143 = 0.00343$
> > $R_p = \frac{1}{0.00343} = 291.5\,\Omega$
> >
> > **Step 2: Combine with Series Resistor ($400\,\Omega$)**
> > $R_{eq} = 400 + R_p$
> > $R_{eq} = 400 + 291.5$
> > $R_{eq} = 691.5\,\Omega$
> >
> > **Step 3: Calculate Total Current**
> > $I = \frac{V}{R_{eq}} = \frac{12.0}{691.5}$
> > $\enclose{box}{I = 0.0174\,A = 17.4\,mA}$

> [!sq]- Example 4.3: Current in one branch
> What is the current through the $500\,\Omega$ resistor in the previous problem?
> > [!continue]- Solution
> > Total Current $I = 17.35\,mA$.
> >
> > **Step 1: Find Voltage across Parallel Block ($V_{bc}$)**
> > First, find voltage drop across the series resistor ($400\,\Omega$):
> > $V_{ab} = IR = (17.35 \times 10^{-3})(400) = 6.94\,V$
> > Voltage remaining for parallel block:
> > $V_{bc} = V_{total} - V_{ab} = 12.0 - 6.94 = 5.06\,V$
> >
> > **Step 2: Calculate Current in $500\,\Omega$ branch**
> > $I_{500} = \frac{V_{bc}}{R_{500}} = \frac{5.06}{500}$
> > $\enclose{box}{I_{500} = 1.01 \times 10^{-2}\,A = 10.1\,mA}$

> [!sq]- Example 4: Mixed Circuit Calculation
> For the circuit shown (Figure 4), calculate:
> ![[Pasted image 20260131150055.png]]
> > [!continue]- $a)$ The effective resistance of the circuit.
> > **Parallel Part:**
> > $\frac{1}{R_p} = \frac{1}{12} + \frac{1}{2} = \frac{1}{12} + \frac{6}{12} = \frac{7}{12}$
> > $R_p = \frac{12}{7} = 1.71\,\Omega$
> >
> > **Total Resistance:**
> > $R_{eff} = 4.0 + 1.71$
> > $\enclose{box}{R_{eff} = 5.71\,\Omega}$
>
> > [!continue]- $b)$ The current passing through the $12\,\Omega$ resistor.
> > **Total Current:**
> > $I_{total} = \frac{V}{R_{eff}} = \frac{8.0}{5.71} = 1.40\,A$
> >
> > **Voltage across Parallel Part:**
> > $V_p = I_{total} \times R_p = (1.40)(1.71) = 2.39\,V$
> >
> > **Current in $12\,\Omega$:**
> > $I_{12} = \frac{V_p}{12} = \frac{2.39}{12}$
> > $\enclose{box}{I_{12} = 0.20\,A}$
>
> > [!continue]- $c)$ The potential difference across the $4.0\,\Omega$ resistor.
> > $V_4 = I_{total} \times 4.0 = (1.40)(4.0)$
> > $\enclose{box}{V_4 = 5.6\,V}$
>
> > [!continue]- $d)$ The power delivered by the battery.
> > $P = I_{total} \times V_{total} = (1.40)(8.0)$
> > $\enclose{box}{P = 11.2\,W}$

> [!sq]- Example 4.4: A two-speed fan
> A fan motor draws $5.0\,A$ when connected to $12\,V$.
> > [!continue]- $a)$ What series resistor should be used to reduce the current to $2.0\,A$?
> > **Step 1: Find Motor Resistance ($R_m$)**
> > $R_m = \frac{V}{I_{initial}} = \frac{12}{5.0} = 2.4\,\Omega$
> >
> > **Step 2: Find Total Resistance needed for $2.0\,A$**
> > $R_{total} = \frac{12}{2.0} = 6.0\,\Omega$
> >
> > **Step 3: Calculate Series Resistor ($R_s$)**
> > $R_s = R_{total} - R_m = 6.0 - 2.4$
> > $\enclose{box}{R_s = 3.6\,\Omega}$
>
> > [!continue]- $b)$ What power rating should the resistor have?
> > $P = I^2 R_s$
> > $P = (2.0)^2 (3.6) = 4(3.6)$
> > $\enclose{box}{P = 14.4\,W}$

# 4.3 Kirchhoff's Rules
> [!continue]- Some circuits cannot be broken down into simple series and parallel connections.
> For these circuits, we use **Kirchhoff's Rules**.

> [!definition]- Kirchhoff's First Law (Junction Rule)
> The algebraic sum of the currents entering any junction in a circuit must equal the algebraic sum of the currents leaving that junction.
> > [!formula]- Conservation of Charge
> > $\sum I_{in} = \sum I_{out}$
> 
> > [!example]- 
> > ![[Pasted image 20260131150718.png]]

> [!definition]- Kirchhoff's Second Law (Loop Rule)
> The algebraic sum of the changes in potential around any closed loop is zero.
> > [!formula]- Conservation of Energy
> > $\sum \mathcal{E} = \sum IR$
> 
> > [!picture]- 
> > ![[Pasted image 20260131150904.png]]

> [!liststart]- Sign Conventions for Loop Rule
> > [!continue]- EMF ($\mathcal{E}$)
> > > [!continue]- Positive (+$\mathcal{E}$)
> > > Traversing source from $-$ to $+$.
> > > ![[Pasted image 20260131151205.png]]
> > 
> > > [!continue]- Negative (-$\mathcal{E}$)
> > > Traversing source from $+$ to $-$.
> > > ![[Pasted image 20260131151230.png]]
>
> > [!continue]- IR Product
> > > [!continue]- Positive (+$IR$)
> > > Traversing resistor in the **same** direction as the current.
> > > ![[Pasted image 20260131151450.png]]
> > 
> > > [!continue]- Negative (-$IR$)
> > > Traversing resistor in the **opposite** direction to the current.
> > > ![[Pasted image 20260131151517.png]]
> > > > [!info]- Note
> > > > The textbook uses $\sum \mathcal{E} = \sum IR$. In this convention:
> > > > * If loop direction matches EMF direction ($- \to +$): $\mathcal{E}$ is positive.
> > > > * If loop direction matches Current direction through R: $IR$ is positive.

> [!liststart]- Problem Solving Strategy
> > [!continue]- 1. Label currents
> > Draw currents in each branch ($I_1, I_2, \dots$) and assign arbitrary directions.
>
> > [!continue]- 2. Identify unknowns
> > Determine what you need to solve for ($I, V, R$).
>
> > [!continue]- 3. Apply Rules
> > * Apply **Junction Rule** at one or more junctions.
> > * Apply **Loop Rule** to closed loops (Need as many independent equations as unknowns).
>
> > [!continue]- 4. Solve Equations
> > Solve the simultaneous equations.
> > * If a solution for a current is **negative**, the actual direction is **opposite** to the chosen direction.

> [!example]- For example, consider a circuit
> ![[Pasted image 20260131151816.png]]
> > [!continue]- At junction $A$ or $D$
> > applying the Kirchhoff's first law
> > $\sum I_\text{in}=\sum I_\text{out}$
> > $I_{1}=I_{2}+I_{3}$
> 
> > [!continue]- For the closed loop (either clockwise or anticlockwise)
> > Apply the Kirchhoff's second law
> > > [!continue]- From Loop 1 $\implies\;FEDAF$
> > > $\sum\mathcal{E}=\sum IR$
> > > $\mathcal{E_{1}}+\mathcal{E_{2}}=I_{2}R_{2}+I_{1}R_{1}$
> > 
> > > [!continue]- From Loop 2 $\implies\;ABCDA$
> > > $\sum\mathcal{E}=\sum IR$
> > > $\mathcal{E_{2}}-\mathcal{E_{3}}=I_{2}R_{2}-I_{3}R_{3}$

> [!sq]- Example 4.5: Using Kirchhoff's rules
> Calculate the currents $I_1$, $I_2$, and $I_3$ in the three branches of the circuit.
> ![[Pasted image 20260131150827.png]]
> > [!continue]- Solution
> > **Step 1: Apply Junction Rule (at junction a)**
> > Currents entering = Currents leaving
> > $I_3 = I_1 + I_2$  --- (Eq. 1)
> >
> > **Step 2: Apply Loop Rule to Loop 1 (Top Loop: a-h-d-c-b-a)**
> > Loop Direction: Clockwise
> > $\sum \mathcal{E} = \sum IR$
> > $\mathcal{E}_2 = I_1(30) + I_3(40) + I_3(1)$
> > $45 = 30I_1 + 41I_3$ --- (Eq. 2)
> >
> > **Step 3: Apply Loop Rule to Loop 2 (Bottom Loop: a-b-c-d-e-f-g-a)**
> > Loop Direction: Clockwise
> > $\mathcal{E}_1 + \mathcal{E}_2 = I_3(1) + I_3(40) + I_2(1) + I_2(20)$
> > $80 + 45 = 41I_3 + 21I_2$
> > $125 = 41I_3 + 21I_2$ --- (Eq. 3)
> >
> > **Step 4: Solve Simultaneous Equations**
> > Substitute (1) into (2):
> > $45 = 30I_1 + 41(I_1 + I_2) \implies 45 = 71I_1 + 41I_2$
> > Substitute (1) into (3):
> > $125 = 41(I_1 + I_2) + 21I_2 \implies 125 = 41I_1 + 62I_2$
> >
> > Solving these yields:
> > $\enclose{box}{I_1 = -0.87\,A}$ (Direction is opposite)
> > $\enclose{box}{I_2 = 2.6\,A}$
> > $\enclose{box}{I_3 = 1.7\,A}$

> [!sq]- Example 6: Single Loop Analysis
> Determine the current and its direction in the circuit.
> ![[Pasted image 20260131152409.png]]
> > [!continue]- Solution
> > **Apply Loop Rule (Anticlockwise)**
> > $\sum \mathcal{E} = \sum IR$
> > $\mathcal{E}_1 + \mathcal{E}_2 = I(R_1 + R_2 + R_3 + R_4 + R_5)$
> > $11.5 + 15.1 = I(8.5 + 4 + 15.1 + 6.22 + 2)$
> > $26.6 = I(35.82)$
> > $I = \frac{26.6}{35.82}$
> > $\enclose{box}{I = 0.74\,A}$
> > **Direction:** Anticlockwise (since $I$ is positive).

> [!sq]- Example 7: Two-Loop Circuit
> For the circuit shown, determine:
> ![[Pasted image 20260131152427.png]]
> > [!continue]- $a)$ The currents $I_1$, $I_2$, and $I$.
> > **Junction Rule:** $I_1 + I_2 = I$ --- (1)
> >
> > **Loop 1 (Left, Clockwise):**
> > $12 = I_1(3.9) + I(1.2) + I_1(9.8)$
> > $12 = 13.7I_1 + 1.2I$ --- (2)
> >
> > **Loop 2 (Right, Counter-Clockwise):**
> > $9 = I_2(6.7) + I(1.2)$ --- (3)
> >
> > **Solving:**
> > From (2): $I_1 = \frac{12 - 1.2I}{13.7}$
> > From (3): $I_2 = \frac{9 - 1.2I}{6.7}$
> > Substitute into (1):
> > $\frac{12 - 1.2I}{13.7} + \frac{9 - 1.2I}{6.7} = I$
> > $0.876 - 0.088I + 1.343 - 0.179I = I$
> > $2.219 = 1.267I$
> > $\enclose{box}{I = 1.75\,A}$
> >
> > Substitute back:
> > $I_1 = \frac{12 - 1.2(1.75)}{13.7} = \enclose{box}{0.72\,A}$
> > $I_2 = \frac{9 - 1.2(1.75)}{6.7} = \enclose{box}{1.03\,A}$
>
> > [!continue]- $b)$ The potential difference across the $6.7\,\Omega$ resistor.
> > $V = I_2 R = (1.03)(6.7)$
> > $\enclose{box}{V = 6.9\,V}$
>
> > [!continue]- $c)$ The power dissipated from the $1.2\,\Omega$ resistor.
> > $P = I^2 R = (1.75)^2 (1.2)$
> > $\enclose{box}{P = 3.68\,W}$

# 4.4 Circuits Containing Resistor and Capacitor (RC Circuits)
## Charging a Capacitor
> [!continue]- When the switch is closed
> The capacitor begins to charge.
> > [!continue]- Voltage across capacitor
> > increases
> 
> > [!continue]- Current through the resistor
> > decreases

> [!formula]- Charging Formulas
> > [!formula]- Charge, $Q$
> > $Q = Q_0\left( 1 - e^{-\frac{t}{RC}} \right) = C\mathcal{E}\left( 1 - e^{-\frac{t}{RC}} \right)$
> > > [!unit]- $Q_0$
> > > Maximum charge ($C\mathcal{E}$)
>
> > [!formula]- Voltage, $V_C$
> > $V_C = \mathcal{E}\left( 1 - e^{-\frac{t}{RC}} \right) = V_0\left( 1 - e^{-\frac{t}{RC}} \right)$
>
> > [!formula]- Current, $I$
> > $I = I_0 e^{-\frac{t}{RC}}$
> > > [!unit]- $I_0$
> > > Maximum current ($\mathcal{E}/R$)

> [!definition]- Time Constant, $\tau$
> The quantity $RC$ is called the time constant. It measures how quickly the capacitor charges or discharges.
> $\tau = RC$
> > [!unit]- $\tau$
> > Time constant in seconds ($s$)
> > > [!info]- At $t = \tau$ (1 time constant)
> > > * **Charging:** Charge reaches $63\%$ of max ($0.63 Q_0$).
> > > * **Discharging:** Voltage drops to $37\%$ of initial ($0.37 V_0$).

> [!picture]- Charging Graphs
> > [!continue]- $V$ vs $t$
> > ![[Pasted image 20260131154526.png]]
> 
> > [!continue]- $I$ vs $t$
> > ![[Pasted image 20260131154549.png]]

## Discharging a Capacitor
> [!continue]- When a charged capacitor is connected across a resistor
> It discharges.
> * Charge and Voltage **decrease** exponentially.
> * Current flows in the **opposite** direction.

> [!formula]- Discharging Formulas
> > [!formula]- Charge, $Q$
> > $Q = Q_0 e^{-\frac{t}{RC}}$
>
> > [!formula]- Voltage, $V_C$
> > $V_C = V_0 e^{-\frac{t}{RC}}$
>
> > [!formula]- Current, $I$
> > $I = -I_0 e^{-\frac{t}{RC}}$
> > > [!info]- Negative Sign
> > > Indicates current direction is opposite to its direction when the capacitor was being charged.

> [!picture]- Discharging Graphs
> ![[Pasted image 20260131154358.png]]

> [!sq]- Example 4.6: RC circuit with EMF (Charging)
> $C=0.30\,\mu F$, $R=20\,k\Omega$, $\mathcal{E}=12\,V$.
> > [!continue]- $a)$ Determine the time constant $\tau$.
> > $\tau = RC = (20 \times 10^3)(0.30 \times 10^{-6})$
> > $\enclose{box}{\tau = 6.0 \times 10^{-3}\,s = 6\,ms}$
>
> > [!continue]- $b)$ The maximum charge $Q_0$.
> > $Q_0 = C\mathcal{E} = (0.30 \times 10^{-6})(12)$
> > $\enclose{box}{Q_0 = 3.6 \times 10^{-6}\,C = 3.6\,\mu C}$
>
> > [!continue]- $c)$ Time to reach 99% of max charge.
> > $Q = 0.99 Q_0$
> > $0.99 Q_0 = Q_0(1 - e^{-t/\tau})$
> > $0.99 = 1 - e^{-t/\tau} \implies e^{-t/\tau} = 0.01$
> > $-t/\tau = \ln(0.01)$
> > $t = -\tau \ln(0.01) = -(6 \times 10^{-3})(-4.605)$
> > $\enclose{box}{t = 0.028\,s}$
>
> > [!continue]- $d)$ Current when charge is half max ($Q = 0.5 Q_0$).
> > Using Kirchhoff's Loop: $\mathcal{E} = IR + V_C$
> > $12 = I(20k) + \frac{0.5 Q_0}{C}$
> > $12 = I(20k) + 0.5(12)$
> > $6 = I(20k)$
> > $\enclose{box}{I = 3.0 \times 10^{-4}\,A}$
>
> > [!continue]- $e)$ Maximum current $I_0$.
> > Occurs at $t=0$ (Capacitor acts as short circuit).
> > $I_0 = \frac{\mathcal{E}}{R} = \frac{12}{20 \times 10^3}$
> > $\enclose{box}{I_0 = 6.0 \times 10^{-4}\,A}$
>
> > [!continue]- $f)$ Charge when current is $0.2 I_0$.
> > $I = 0.2 I_0 = 1.2 \times 10^{-4}\,A$
> > $\mathcal{E} = IR + \frac{Q}{C}$
> > $12 = (1.2 \times 10^{-4})(20 \times 10^3) + \frac{Q}{0.3 \mu}$
> > $12 = 2.4 + \frac{Q}{0.3 \mu}$
> > $9.6 = \frac{Q}{0.3 \mu}$
> > $\enclose{box}{Q = 2.88 \times 10^{-6}\,C}$

> [!sq]- Example 4.7: Discharging RC circuit
> Battery emf $20.0\,V$ fully charges capacitor $C=1.02\,\mu F$. At $t=0$, switch connects to resistor $R$. Current drops to $0.50 I_0$ in $40\,\mu s$.
> > [!continue]- $a)$ Value of charge $Q$ at $t=0$.
> > Initial charge $Q_0 = C\mathcal{E}$
> > $Q_0 = (1.02 \times 10^{-6})(20)$
> > $\enclose{box}{Q_0 = 2.04 \times 10^{-5}\,C}$
>
> > [!continue]- $b)$ Value of resistance $R$.
> > Discharging current: $I = I_0 e^{-t/RC}$
> > $0.5 I_0 = I_0 e^{-40\mu / R(1.02\mu)}$
> > $0.5 = e^{-39.2/R}$
> > $\ln(0.5) = -\frac{39.2}{R}$
> > $-0.693 = -\frac{39.2}{R}$
> > $\enclose{box}{R = 56.6\,\Omega}$
>
> > [!continue]- $c)$ Charge $Q$ at $t=60\,\mu s$.
> > $Q = Q_0 e^{-t/RC}$
> > $RC = (56.6)(1.02 \times 10^{-6}) = 57.7\,\mu s$
> > $Q = (2.04 \times 10^{-5}) e^{-60/57.7}$
> > $Q = (2.04 \times 10^{-5})(0.353)$
> > $\enclose{box}{Q = 7.24 \times 10^{-6}\,C}$