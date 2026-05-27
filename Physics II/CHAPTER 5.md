$$\underline{\Huge\text{MAGNETISM}}$$

# 5.1 Magnets and Magnetic Fields

> [!liststart]- Properties of Magnets
> > [!continue]- Poles
> > Magnets have two ends called **north (N)** and **south (S)** poles.
> > > [!info]- Interaction
> > > * **Like poles** ($N-N$ or $S-S$) repel.
> > > * **Unlike poles** ($N-S$) attract.
> 
> > [!continue]- Monopoles
> > Single magnetic poles **do not exist**. Cutting a magnet in half creates two smaller magnets, each with a N and S pole.

> [!definition]- Magnetic Field, $\vec{B}$
> A region around a magnet or moving charge where a magnetic force can be experienced.
> > [!continue]- Sources
> > > [!continue]- **Stationary charge:** 
> > > Produces Electric field only.
> > 
> > > [!continue]- **Moving charge:** 
> > > Produces Electric field **and** Magnetic field.

> [!liststart]- Magnetic Field Lines
> ![[Pasted image 20260131171246.png]]
> > [!continue]- Direction
> > By convention, lines leave the $\color{orange}i$ pole and enter the $\color{orange}ii$ pole.
> > > [!blank]- $\color{orange}i$
> > > North
> > 
> > > [!blank]- $\color{orange}ii$
> > > South
> 
> > [!continue]- Tangent
> > The tangent to a field line at any point indicates the direction of the magnetic field $\vec{B}$ at that point.
> 
> > [!continue]- Loops
> > Magnetic field lines form closed loops (passing through the magnet from S to N inside).

> [!picture]- Earth's Magnetic Field
> ![[Drawing 2026-02-01 15.43.22.excalidraw]]
> > [!continue]- Fill in the blanks
> > > [!blank]- $\color{orange}i$
> > > North geographic pole ("True north")
> > 
> > > [!blank]- $\color{orange}ii$
> > > Rotation axis
> > 
> > > [!blank]- $\color{orange}iii$
> > > Declination
> > 
> > > [!blank]- $\color{orange}iv$
> > > Magnetic pole
> > 
> > > [!blank]- $\color{orange}v$
> > > Compass
> > 
> > > [!blank]- $\color{orange}vi$
> > > Magnetic pole
> > 
> > > [!blank]- $\color{orange}vii$
> > > South geographic pole
> 
> > [!info]- Note
> > The Earth's "North Geographic Pole" behaves like a **South Magnetic Pole** (since the north pole of a compass is attracted to it).

> [!procedure]- Methods to determine magnetic field pattern
> > [!continue]- Compass needles
> > ![[Pasted image 20260201155403.png]]
> 
> > [!continue]- Sprinkling iron fillings on paper
> > ![[Pasted image 20260201155423.png]]

> [!liststart]- Various pattern of magnetic field lines around the magnets
> > [!picture]- Bar magnet
> > ![[Pasted image 20260201155611.png]]
> 
> > [!picture]- Horseshow or U magnet
> > ![[Pasted image 20260201155633.png]]
> 
> > [!picture]- Two bar magnets (unlike pole)
> > ![[Pasted image 20260201155706.png]]
> 
> > [!picture]- Two bar magnets (like poles)
> > ![[Pasted image 20260201155743.png]]
> > > [!info]- That empty point in the middle is called
> > > neutral point (point where the resultant magnetic force is zero)
# 5.2 Ampere's Law

> [!definition]- Ampere (Unit Definition)
> One ampere is defined as the current flowing in each of two long parallel wires $1\,m$ apart, which results in a force of exactly $2\times 10^{-7}\,N$ per meter of length of each wire.

> [!formula]- Ampere's Law
> Relates the magnetic field around a closed loop to the total current flowing through the loop.
> ![[Pasted image 20260201160938.png]]
> $\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{encl}$
> > [!unit]- $\mu_0$
> > Permeability of free space ($4\pi \times 10^{-7}\,T\,m\,A^{-1}$)
> 
> > [!unit]- $I_{encl}$
> > Net current enclosed by the path

> [!procedure]- Solving problems using Ampère's Law
> > [!continue]- Ampère's law is only useful for
> > soling the problems when there is a great deal of symmetry. Identify the symmetry
> 
> > [!continue]- Choose
> > an integration path that reflects the symmetry (typically, the path is along lines where the field is constant and perpendicular to the field where it is changing).
> 
> > [!continue]- Use the symmetry to
> > determine the direction of the field.
> 
> > [!continue]- Determine
> > the enclosed current

> [!sq]- Example 5-1: Field inside and outside a wire
> A long straight cylindrical wire of radius $R$ carries a uniform current $I$. Determine the magnetic field:
> ![[Pasted image 20260131173038.png]]
> ![[Pasted image 20260201161430.png]]
> > [!formula]- $a)$ Points outside the conductor ($r > R$)
> > Using Ampere's law on a circular path of radius $r$:
> > $\oint B \cdot dl = \mu_0 I_{encl}$
> > $B(2\pi r) = \mu_0 I$
> > $\enclose{box}{B = \frac{\mu_0 I}{2\pi r}}$
>
> > [!formula]- $b)$ Points inside the conductor ($r < R$)
> > Current density $J = \frac{I}{\pi R^2}$
> > Enclosed current $I_{encl} = J(\pi r^2) = \frac{I}{\pi R^2}(\pi r^2) = I \frac{r^2}{R^2}$
> >
> > Apply Ampere's Law:
> > $B(2\pi r) = \mu_0 I \frac{r^2}{R^2}$
> > $B = \frac{\mu_0 I r}{2\pi R^2}$
> > $\enclose{box}{B \propto r}$
>
> > [!continue]- $c)$ Calculation
> > Given $R=2.0\,mm$, $I=60\,A$.
> > > [!continue]- $i)$ At $r=1.0\,mm$ ($r < R$)
> > > $B = \frac{(4\pi \times 10^{-7})(60)(1\times 10^{-3})}{2\pi (2\times 10^{-3})^2}$
> > > $\enclose{box}{B = 3.0 \times 10^{-3}\,T}$
> > 
> > > [!continue]- $ii)$ At $r=3.0\,mm$ ($r > R$)
> > > $B = \frac{(4\pi \times 10^{-7})(60)}{2\pi (3\times 10^{-3})}$
> > > $\enclose{box}{B = 4.0 \times 10^{-3}\,T}$
# 5.3 Source of Magnetic Field

## 5.3.1 Straight Wire
> [!formula]- Magnetic Field of a Long Straight Wire
> ![[Pasted image 20260201161002.png]]
> $B = \frac{\mu_0 I}{2\pi r}$
> > [!unit]- $B$
> > magnitude of magnetic flux intensity in $T\,A^{-1}$
> 
> > [!unit]- $r$
> > Perpendicular distance from the wire in $m$

> [!liststart]- Right Hand Grip Rule (Straight Wire)
> ![[Pasted image 20260201161735.png]]
> > [!continue]- Thumb
> > Direction of Current, $I$
> 
> > [!continue]- Fingers
> > Direction of Magnetic Field, $\vec{B}$ (wrap around)

> [!liststart]- Identifying current direction using symbols
> > [!continue]- directed out of the page
> > ${\Huge\circ}\hspace{-0.46em}^{\tiny_{_{{^{\bullet}}}}}$
> > ![[Pasted image 20260201163848.png]]
> 
> > [!continue]- Directed into the page
> > $\enclose{circle}{\text{X}}$
> > ![[Pasted image 20260201164302.png]]

> [!sq]- Example 5-2: Calculation of B near a wire
> A vertical wire carries a current of $25\,A$ upward. What is the magnetic field at point P, $10\,cm$ due north?
> ![[Pasted image 20260201164407.png]]
> > [!continue]- Solution
> > $I = 25\,A$, $r = 0.1\,m$
> > $B = \frac{\mu_0 I}{2\pi r} = \frac{(4\pi \times 10^{-7})(25)}{2\pi (0.1)}$
> > $\enclose{box}{B = 5.0 \times 10^{-5}\,T}$
> > **Direction:** Using RHR (Thumb up), fingers curl. At North point, B points **West** (Into the page relative to the diagram in slides).

> [!sq]- Example 5-3: Magnetic field midway between two currents
> Two parallel wires $10.0\,cm$ apart. $I_1 = 5.0\,A$ (out), $I_2 = 7.0\,A$ (in). Find B at the midpoint.
> ![[Pasted image 20260201164428.png]]
> > [!continue]- Solution
> > Distance to midpoint $r = 5.0\,cm = 0.05\,m$.
> >
> > **Wire 1 ($I_1$ Out):**
> > $B_1 = \frac{\mu_0 I_1}{2\pi r} = \frac{(4\pi \times 10^{-7})(5)}{2\pi (0.05)} = 2.0 \times 10^{-5}\,T$
> > Direction: Counter-clockwise $\implies$ At midpoint, $B_1$ is **Up**.
> >
> > **Wire 2 ($I_2$ In):**
> > $B_2 = \frac{\mu_0 I_2}{2\pi r} = \frac{(4\pi \times 10^{-7})(7)}{2\pi (0.05)} = 2.8 \times 10^{-5}\,T$
> > Direction: Clockwise $\implies$ At midpoint, $B_2$ is **Up**.
> >
> > **Total Field:**
> > $\vec{B}_{net} = B_1 + B_2 = (2.0 + 2.8) \times 10^{-5}$
> > $\enclose{box}{B_{net} = 4.8 \times 10^{-5}\,T \text{ (Upward)}}$

> [!sq]- Example 4: Parallel Wires
> Wire X ($50\,A$) and Wire Y ($10\,A$) are $5.0\,cm$ apart, currents in **same** direction.
> > [!continue]- $a)$ B at midpoint
> > $r = 0.025\,m$.
> > $B_X = \frac{\mu_0 (50)}{2\pi (0.025)} = 4.0 \times 10^{-4}\,T$
> > $B_Y = \frac{\mu_0 (10)}{2\pi (0.025)} = 0.8 \times 10^{-4}\,T$
> > Since currents are same direction, fields at midpoint oppose.
> > $B_{net} = B_X - B_Y = 3.2 \times 10^{-4}\,T$
>
> > [!continue]- $b)$ Zero field point
> > Let point be distance $r$ from X.
> > $B_X = B_Y$
> > $\frac{\mu_0 I_X}{2\pi r} = \frac{\mu_0 I_Y}{2\pi (d - r)}$
> > $\frac{50}{r} = \frac{10}{0.05 - r}$
> > $5(0.05 - r) = r \implies 0.25 - 5r = r \implies 0.25 = 6r$
> > $r = \frac{0.25}{6}$
> > $\enclose{box}{r = 0.042\,m \text{ from X}}$

## 5.3.2 Solenoid
> [!definition]- Solenoid
> is an electrical device in which a long wire has been wound into a succession of closely spaced loops with geometry of a helix.

> [!formula]- Magnetic Field of a Solenoid
> > [!formula]- Magnitude of magnetic field intensity at the centre (mid-point/inside) of $N$ turn solenoid
> > $B = \frac{\mu_0 N I}{l} = \mu_0 n I$
> > > [!unit]- $n$
> > > Number of turns per unit length ($N/l$)
> > 
> > > [!unit]- $N$
> > > Total number of turns
> > 
> > > [!unit]- $l$
> > > Length of solenoid
>
> > [!formula]- magnitude of magnetic field intensity at the end of $N$ turn solenoid is given by
> > $B = \frac{1}{2}\mu_0 n I$

> [!liststart]- Right Hand Grip Rule (Solenoid)
> ![[Pasted image 20260201164933.png]]
> > [!continue]- Fingers
> > Direction of Current, $I$
> 
> > [!continue]- Thumb
> > Direction of Magnetic North Pole

> [!sq]- Example 5-4: Field inside a solenoid
> A $10\,cm$ long solenoid has $400$ turns and carries $2.0\,A$. Calculate field inside near center.
> > [!continue]- Solution
> > $l = 0.1\,m$, $N = 400$, $I = 2.0\,A$.
> > Turns per unit length $n = \frac{N}{l} = \frac{400}{0.1} = 4000\,m^{-1}$
> > $B = \mu_0 n I$
> > $B = (4\pi \times 10^{-7})(4000)(2.0)$
> > $B = 32\pi \times 10^{-4}$
> > $\enclose{box}{B \approx 1.0 \times 10^{-2}\,T}$

# 5.4 Magnetic Force

## 5.4.1 Force on a current-carrying conductor in a uniform magnetic field
> [!continue]- A magnet exerts a force on a current-carrying wire. The direction of the force is
> given by a right-hand hand rule.

> [!formula]- Magnetic Force on a Wire
> The force depends on the current, length, magnetic field, and orientation.
> $F = I l B \sin\theta$
> > [!formula]- Vector Notation
> > $\vec{F} = I(\vec{l} \times \vec{B})$
>
> > [!unit]- $F$
> > Magnetic force in Newtons ($N$)
> 
> > [!unit]- $I$
> > Current in Amperes ($A$)
> 
> > [!unit]- $l$
> > Length of the wire in the magnetic field in meters ($m$)
> 
> > [!unit]- $B$
> > Magnetic field strength in Tesla ($T$) or $Wb\,m^{-2}$
> > > [!unit]- Conversion
> > > $1\,T = 1\,N\,A^{-1}\,m^{-1}$
> > > $1\,Gauss\,(G) = 10^{-4}\,T$
> 
> > [!unit]- $\theta$
> > Angle between the direction of current $I$ (or length vector $\vec{l}$) and magnetic field $\vec{B}$

> [!liststart]- Scenarios for Force Magnitude
> > [!continue]- Maximum Force
> > When wire is perpendicular to field ($\theta = 90^\circ$).
> > $F_{max} = IlB \sin 90^\circ = IlB$
> > ![[Pasted image 20260201165400.png]]
> 
> > [!continue]- Zero Force
> > When wire is parallel to field ($\theta = 0^\circ$).
> > $F = IlB \sin 0^\circ = 0$
> > ![[Pasted image 20260201165430.png]]

> [!liststart]- Determining Direction (Hand Rules)
> > [!continue]- Fleming's Left Hand Rule
> > ![[Pasted image 20260201165529.png]]
> > > [!continue]- Thumb
> > > direction of Force, $\vec{F}$
> > 
> > > [!continue]- First finger
> > > direction of Field, $\vec{B}$
> > 
> > > [!continue]- Second finger
> > > direction of Current, $I$
> 
> > [!continue]- Right Hand Palm Rule
> > ![[Pasted image 20260201165550.png]]
> > > [!continue]- Thumb
> > > Direction of Force, $\vec{F}$
> > 
> > > [!continue]- First finger
> > > Direction of current, $I$
> > 
> > > [!continue]- Second finger
> > > Direction of field, $\vec{B}$

> [!sq]- Example 5-5: Magnetic Force on a current-carrying wire
> A wire carrying a $30\,A$ current has a length $l=12\,cm$ between the pole faces of a magnet at an angle $\theta=60^{\circ}$. The magnetic field is approximately uniform at $0.90\,T$.
> ![[Pasted image 20260201174606.png]]
> > [!continue]- Solution
> > $I = 30\,A$
> > $l = 12\,cm = 0.12\,m$
> > $B = 0.90\,T$
> > $\theta = 60^\circ$
> >
> > $F = IlB \sin\theta$
> > $F = (30)(0.12)(0.90) \sin 60^\circ$
> > $\enclose{box}{F = 2.81\,N}$

> [!sq]- Example 6: Force Calculation
> A wire of $100\,cm$ long is placed perpendicular to the magnetic field of $1.20\,Wb\,m^{-2}$.
> > [!continue]- $a)$ Magnitude of force when current is $15\,A$.
> > $l=1.00\,m$, $B=1.20\,T$, $\theta=90^\circ$, $I=15\,A$.
> > $F = IlB \sin 90^\circ = (15)(1.00)(1.20)(1)$
> > $\enclose{box}{F = 18\,N}$
>
> > [!continue]- $b)$ Force if length is extended to $150\,cm$.
> > $l=1.50\,m$.
> > $F = (15)(1.50)(1.20)(1)$
> > $\enclose{box}{F = 27\,N}$
>
> > [!continue]- $c)$ Find B if force is $60 \times 10^{-2}\,N$ and current is $12\,A$.
> > $F = 0.60\,N$, $I=12\,A$, $l=1.50\,m$.
> > $0.60 = (12)(1.50)B$
> > $0.60 = 18B$
> > $B = \frac{0.60}{18}$
> > $\enclose{box}{B = 3.33 \times 10^{-2}\,T}$

> [!sq]- Example 5-6: Measuring a magnetic field
> A rectangular loop hangs vertically. The horizontal portion $ab$ (length $10.0\,cm$) is in a magnetic field directed out of the page. A downward magnetic force of $F=3.48 \times 10^{-2}\,N$ is measured when $I=0.245\,A$.
> ![[Pasted image 20260201174629.png]]
> > [!continue]- Solution
> > $l = 10.0\,cm = 0.10\,m$
> > $F = 3.48 \times 10^{-2}\,N$
> > $I = 0.245\,A$
> > Since field is perpendicular to wire, $\theta = 90^\circ$.
> >
> > $F = IlB \sin 90^\circ$
> > $3.48 \times 10^{-2} = (0.245)(0.10) B$
> > $3.48 \times 10^{-2} = 0.0245 B$
> > $B = \frac{3.48 \times 10^{-2}}{0.0245}$
> > $\enclose{box}{B = 1.42\,T}$

## 5.4.2 Force on an Electric Charge Moving in a Magnetic Field
> [!continue]- Conditions for Force
> > [!continue]- A stationary charge, $v=0$, experiences
> > no magnetic force
> 
> > [!continue]- A moving charge, $v\neq 0$, experiences
> > magnetic force

> [!formula]- Magnetic Force on a Moving Charge
> $\vec{F} = q(\vec{v} \times \vec{B})$
> $F = qvB \sin\theta$
> > [!unit]- $F$
> > Magnetic force
> 
> > [!unit]- $B$
> > magnetic flux density
> 
> > [!unit]- $q$
> > Magnitude of charge in Coulombs ($C$)
> 
> > [!unit]- $v$
> > Velocity of charge in $m\,s^{-1}$
> 
> > [!unit]- $\theta$
> > Angle between velocity vector $\vec{v}$ and magnetic field $\vec{B}$

> [!liststart]- Determining Direction (Moving Charge)
> > [!continue]- Positive Charge ($+q$)
> > ![[Pasted image 20260201170425.png]]
> > Use **Fleming's Left Hand Rule** (or Right Hand Palm Rule).
> > Direction of current $I$ corresponds to direction of velocity $\vec{v}$.
> 
> > [!continue]- Negative Charge ($-q$)
> > ![[Pasted image 20260201170441.png]]
> > Use **Right Hand Rule** (simulate opposite of positive).
> > > [!continue]- Thumb
> > > Direction of Force, $\vec{F}$
> > 
> > > [!continue]- First finger
> > > direction of Field, $\vec{B}$
> > 
> > > [!continue]- Second finger
> > > direction of velocity, $v$

> [!continue]- Motion of Charge in Uniform B-Field
> If a charged particle moves perpendicular to a uniform magnetic field ($\theta=90^\circ$), its path is a **circle**.
> ![[Pasted image 20260201174730.png]]
> > [!formula]- Radius of Circular Path
> > Magnetic force provides centripetal force: $F_B = F_c$
> > $qvB = \frac{mv^2}{r}$
> > $\enclose{box}{r = \frac{mv}{Bq}}$
> > > [!unit]- $m$
> > > Mass of particle in $kg$
> > 
> > > [!unit]- $r$
> > > Radius of path in $m$
> > 
> > > [!unit]- $v$
> > > velocity in $m\,s^{-1}$
> > 
> > > [!unit]- $q$
> > > magnitude of the charged particle

> [!sq]- Example 5-7: Magnetic force on a proton
> A force of $8.0 \times 10^{-14}\,N$ toward the West acts on a proton moving vertically upward at $5.0 \times 10^6\,m/s$. When moving horizontally North, the force is zero.
> > [!continue]- Solution
> > **Direction Analysis:**
> > * Moving North ($v$) $\implies F=0$. Thus $\vec{v} \parallel \vec{B}$. $\vec{B}$ must be North or South.
> > * Moving Up ($v$) $\implies F$ is West. Using Left Hand Rule:
> >     * Force (Thumb) = West
> >     * Velocity (Middle) = Up
> >     * Field (Index) = **North** (Into the page relative to a vertical map, or horizontally North).
> >
> > **Magnitude Calculation:**
> > $\vec{v}$ is Up, $\vec{B}$ is North (horizontal). Angle $\theta = 90^\circ$.
> > $F = qvB \sin 90^\circ$
> > $8.0 \times 10^{-14} = (1.6 \times 10^{-19})(5.0 \times 10^6) B$
> > $8.0 \times 10^{-14} = 8.0 \times 10^{-13} B$
> > $B = \frac{8.0 \times 10^{-14}}{8.0 \times 10^{-13}}$
> > $\enclose{box}{B = 0.1\,T \text{ (North)}}$

> [!sq]- Example 9: Force Calculation
> Proton ($q=1.6\times 10^{-19}\,C$) travelling at $5.0 \times 10^7\,m/s$ in $B=1.5\,T$.
> > [!continue]- $a)$ Velocity perpendicular to field
> > $F = qvB \sin 90^\circ$
> > $F = (1.6 \times 10^{-19})(5 \times 10^7)(1.5)(1)$
> > $\enclose{box}{F = 1.2 \times 10^{-11}\,N}$
>
> > [!continue]- $b)$ Velocity at $50^\circ$ to field
> > $F = qvB \sin 50^\circ$
> > $F = (1.2 \times 10^{-11}) \sin 50^\circ$
> > $\enclose{box}{F = 9.19 \times 10^{-12}\,N}$

> [!sq]- Example 11: Electron's path
> Electron ($m=9.11 \times 10^{-31}\,kg$) travels at $2.0 \times 10^7\,m/s$ perpendicular to $B=0.010\,T$. Find radius.
> > [!continue]- Solution
> > $r = \frac{mv}{Bq}$
> > $r = \frac{(9.11 \times 10^{-31})(2.0 \times 10^7)}{(0.010)(1.6 \times 10^{-19})}$
> > $\enclose{box}{r = 1.14 \times 10^{-2}\,m = 1.14\,cm}$

# 5.5 Force Between Two Parallel Wires

> [!continue]- Interaction
> Wire 1 and Wire 2 are two parallel wires with flowing currents. The magnetic field produced by Wire 1 exerts a force on Wire 2 (and vice versa).

> [!formula]- Force per unit length
> $B_1 = \frac{\mu_0 I_1}{2\pi d}$ (Field from Wire 1 at Wire 2)
> $F_2 = I_2 l B_1 = I_2 l \left( \frac{\mu_0 I_1}{2\pi d} \right)$
> $\enclose{box}{\frac{F}{l} = \frac{\mu_0 I_1 I_2}{2\pi d}}$
> > [!unit]- $d$
> > Distance between wires in $m$
> 
> > [!unit]- $F/l$
> > Force per unit length in $N\,m^{-1}$
> 
> > [!tip]- If two different $l$ are given
> > use the overlapping length (or the shortest if it's highest point and lowest point is in between of the longer wire)

> [!liststart]- Direction of Force
> 
> > [!continue]- Same Direction (Parallel)
> > ![[Pasted image 20260201171522.png]]
> > Currents $I_1$ and $I_2$ flow in same direction $\implies$ **Attraction**.
> 
> > [!continue]- Opposite Direction (Anti-parallel)
> > ![[Pasted image 20260201171539.png]]
> > Currents flow in opposite directions $\implies$ **Repulsion**.

> [!sq]- Example 10: Force between two current-carrying wires
> The two wires of a $2.0m$ long appliance cord are $3.0mm$ apart and carry a current of $8.0\,A$ dc.
> Calculate the force one wire exerts on the other.
> > [!continue]- Solution
$$F = \frac{(4\pi \times 10^{-7})(8.0)(8.0)(2.0)}{2\pi (0.003)} = 8.53 \times 10^{-3}\text{ N}$$

> [!sq]- Example 12: Parallel Wires
> Two wires $0.25\,m$ apart carrying $2.4\,A$ each in the same direction.
> > [!continue]- $b)$ Force per unit length
> > $\frac{F}{l} = \frac{\mu_0 I_1 I_2}{2\pi d}$
> > $\frac{F}{l} = \frac{(4\pi \times 10^{-7})(2.4)^2}{2\pi (0.25)}$
> > $\frac{F}{l} = \frac{(2 \times 10^{-7})(5.76)}{0.25}$
> > $\enclose{box}{\frac{F}{l} = 4.61 \times 10^{-6}\,N\,m^{-1} \text{ (Attractive)}}$
>
> > [!continue]- $c)$ Changing current
> > $I_1$ reduced to $0.64\,A$. Find new $I_2$ to maintain same force.
> > $4.61 \times 10^{-6} = \frac{(4\pi \times 10^{-7})(0.64) I_2}{2\pi (0.25)}$
> > $4.61 \times 10^{-6} = \frac{(2 \times 10^{-7})(0.64) I_2}{0.25}$
> > $I_2 = \frac{4.61 \times 10^{-6} \times 0.25}{1.28 \times 10^{-7}}$
> > $\enclose{box}{I_2 = 9.0\,A}$

> [!sq]- Example 5-11: Suspending a wire
> Horizontal wire ($I_1 = 80\,A$). Second wire below it ($d=20\,cm$) with mass density $0.12\,g/m$. How much current $I_2$ is needed to suspend it against gravity?
> ![[Pasted image 20260201171736.png]]
> > [!continue]- Solution
> > Gravity Force downwards: $F_g = mg$.
> >
> > **Force Balance:** $F_B = F_g$
> > For unit length ($l=1\,m$):
> > $\frac{\mu_0 I_1 I_2}{2\pi d} = (m/l)g$
> >
> > **Given:**
> > $m/l = 0.12\,g/m = 1.2 \times 10^{-4}\,kg/m$
> > $d = 0.2\,m$
> > $I_1 = 80\,A$
> >
> > $\frac{(4\pi \times 10^{-7})(80) I_2}{2\pi (0.2)} = (1.2 \times 10^{-4})(9.81)$
> > $\frac{(2 \times 10^{-7})(80) I_2}{0.2} = 1.18 \times 10^{-3}$
> > $80 \times 10^{-6} I_2 = 1.18 \times 10^{-3}$
> > $I_2 = \frac{1.18 \times 10^{-3}}{80 \times 10^{-6}}$
> > $\enclose{box}{I_2 = 14.75\,A}$
