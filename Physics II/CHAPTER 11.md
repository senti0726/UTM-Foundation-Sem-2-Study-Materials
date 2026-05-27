$$\begin{align}
&\underline{\Huge\text{EARLY QUANTUM THEORY}} \\
&\underline{\Huge\text{AND MODELS OF THE ATOM}}
\end{align}$$
# 11.1 Blackbody Radiation

> [!continue]- Thermal Radiation
> All objects emit radiation whose total intensity is proportional to the $\color{orange}i$ of their temperature. This is called $\color{orange}ii$.
> > [!blank]- $\color{orange}i$
> > fourth power ($T^4$)
>
> > [!blank]- $\color{orange}ii$
> > thermal radiation

> [!definition]- Blackbody
> An object that emits ||thermal radiation|| only (and absorbs all radiation falling on it, reflecting none).

> [!continue]- Spectrum Characteristics
> ![[Pasted image 20260203112253.png]]
> The spectrum of blackbody radiation shows that:
> * The frequency of peak intensity increases ||linearly|| with temperature.
> * As temperature increases, the peak wavelength ($\lambda_P$) shifts to ||shorter|| wavelengths (higher frequencies).
> * The total energy emitted (area under curve) ||increases|| rapidly with temperature.

> [!formula]- Wien's Displacement Law
> Relates the temperature of a blackbody to the wavelength at which it emits the most intensity ($\lambda_P$).
> $\lambda_P T = 2.90 \times 10^{-3}\,m\cdot K$
> > [!unit]- $\lambda_P$
> > Peak wavelength in meters ($m$)
>
> > [!unit]- $T$
> > Temperature in Kelvin ($K$)
>
> > [!unit]- $2.90 \times 10^{-3}$
> > Wien's displacement constant in $m\cdot K$

> [!sq]- Example 11-1: The Sun's surface temperature
> Estimate the temperature of the surface of our Sun, given that the Sun emits light whose peak intensity occurs in the visible spectrum at around $500\,nm$.
> > [!continue]- Solution
> > **Given:**
> > $\lambda_P = 500\,nm = 500 \times 10^{-9}\,m$
> >
> > **Calculation:**
> > $\lambda_P T = 2.90 \times 10^{-3}$
> > $(500 \times 10^{-9}) T = 2.90 \times 10^{-3}$
> > $T = \frac{2.90 \times 10^{-3}}{500 \times 10^{-9}}$
> > $T = \frac{2.90 \times 10^{-3}}{5.0 \times 10^{-7}}$
> > $\enclose{box}{T = 5800\,K}$

## Planck's Quantum Theory

> [!continue]- The Problem (Ultraviolet Catastrophe)
> ![[Pasted image 20260203112744.png]]
> Classical physics (Rayleigh-Jeans law) predicted that intensity would go to infinity at short wavelengths (high frequencies). This disagreed with experimental data.
> * Wien's theory worked for ||short|| wavelengths.
> * Rayleigh-Jeans theory worked for ||long|| wavelengths.

> [!continue]- Planck's Hypothesis (1900)
> Max Planck proposed that the energy of atomic oscillations within atoms cannot have an arbitrary value; it is $\color{orange}i$.
> > [!blank]- $\color{orange}i$
> > quantized (related to the frequency of the emitted light, $f$)

> [!formula]- Quantization of Energy
> The energy of an oscillator is an integral multiple of $hf$.
> $E = nhf$
> > [!unit]- $E$
> > Energy in Joules ($J$)
>
> > [!unit]- $n$
> > Quantum number (integer: $1, 2, 3, \dots$)
> > > [!note]- Quantum means ||discrete amount|| as opposed to ||continuous||
> 
>
> > [!unit]- $h$
> > Planck's constant ($6.63 \times 10^{-34}\,J\cdot s$)
>
> > [!unit]- $f$
> > Frequency of the oscillation in Hertz ($Hz$)

> [!formula]- Energy of a Quantum (Photon)
> The minimum energy packet (quantum) for radiation of frequency $f$.
> $E = hf = \frac{hc}{\lambda}$
> > [!unit]- $E$
> > Energy of a photon in Joules ($J$)
>
> > [!unit]- $h$
> > Planck's constant ($6.63 \times 10^{-34}\,J\cdot s$)
>
> > [!unit]- $f$
> > Frequency in Hertz ($Hz$)
>
> > [!unit]- $c$
> > Speed of light ($3.00 \times 10^8\,m\,s^{-1}$)
>
> > [!unit]- $\lambda$
> > Wavelength in meters ($m$)

> [!continue]- Relationship
> The quantum of energy $E$ is $\color{orange}i$ proportional to its wavelength $\lambda$.
> > [!blank]- $\color{orange}i$
> > inversely

# 11.2 Photon Theory of Light and the Photoelectric Effect

## Energy Units and Photons

> [!definition]- Electron-Volt ($eV$)
> A convenient unit of energy for atomic physics. It is defined as the kinetic energy gained by an electron in being accelerated by a potential difference of 1 volt.
> > [!formula]- Conversion
> > $1\,eV = 1.60 \times 10^{-19}\,J$

> [!continue]- Einstein's Proposal (1905)
> Albert Einstein extended Planck's idea by proposing that electromagnetic radiation is itself quantized. It consists of particle-like packets of energy called $\color{orange}i$.
> > [!blank]- $\color{orange}i$
> > photons

> [!definition]- Photon
> A particle with $\color{orange}i$ mass consisting of a quantum of electromagnetic radiation where its energy is concentrated.
> * Travels at the speed of light ($c$).
> * Regarded as a unit of energy equal to ||$hf$||.
> > [!blank]- $\color{orange}i$
> > zero

> [!table]- Comparison: EM Wave vs Photon
> | Feature | Electromagnetic Wave | Photon |
> | :--- | :--- | :--- |
> | **Energy Source** | Depends on Intensity ($I \propto A^2$). | Depends on Frequency ($E \propto f$). |
> | **Distribution** | Energy is continuously spread out. | Energy is discrete (packets). |

> [!formula]- Planck's Radiation Formula
> Planck found the constants by fitting blackbody curves to this formula:
> $I(\lambda, T) = \frac{2\pi h c^2 \lambda^{-5}}{e^{hc/\lambda kT} - 1}$
> > [!unit]- $h$
> > Planck's constant ($6.626 \times 10^{-34}\,J\cdot s$)
> 
> > [!unit]- $k$
> > Boltzmann's constant

> [!sq]- Example 3: Green Light Photon
> A photon of green light has a wavelength of $740\,nm$.
> > [!continue]- $a)$ Calculate the photon's frequency.
> > **Given:**
> > $\lambda = 740\,nm = 740 \times 10^{-9}\,m$
> > $c = 3.00 \times 10^8\,m\,s^{-1}$
> >
> > **Calculation:**
> > $c = f\lambda \implies f = \frac{c}{\lambda}$
> > $f = \frac{3 \times 10^8}{740 \times 10^{-9}}$
> > $\enclose{box}{f = 4.05 \times 10^{14}\,Hz}$
>
> > [!continue]- $b)$ Calculate the energy in Joules and eV.
> > **In Joules:**
> > $E = hf = (6.63 \times 10^{-34})(4.05 \times 10^{14})$
> > $\enclose{box}{E = 2.69 \times 10^{-19}\,J}$
> >
> > **In Electron-Volts:**
> > $E_{eV} = \frac{2.69 \times 10^{-19}\,J}{1.60 \times 10^{-19}\,J/eV}$
> > $\enclose{box}{E = 1.68\,eV}$

> [!sq]- Example 4: Gamma Radiation
> Gamma radiation has wavelength $\lambda = 4.62 \times 10^{-12}\,m$. Calculate the energy in $eV$.
> > [!continue]- Solution
> > **Step 1: Energy in Joules**
> > $E = \frac{hc}{\lambda} = \frac{(6.63 \times 10^{-34})(3 \times 10^8)}{4.62 \times 10^{-12}}$
> > $E = 4.305 \times 10^{-14}\,J$
> >
> > **Step 2: Energy in eV**
> > $E = \frac{4.305 \times 10^{-14}}{1.60 \times 10^{-19}}$
> > $\enclose{box}{E = 2.69 \times 10^5\,eV}$

## The Photoelectric Effect

> [!definition]- Photoelectric Effect
> The emission of electrons (called **photoelectrons**) from the surface of a metal when electromagnetic radiation (light) of sufficiently high frequency strikes it.
> ![[Pasted image 20260203120625.png]]

> [!definition]- Photoelectron
> an electron emitted from the surface of the metal when the EM radiation (light) strikes its surface

> [!liststart]- Predictions: Wave Theory vs Particle Theory
> > [!continue]- Wave Theory (Classical) Predictions
> > * **Intensity:** Increasing intensity should increase the $\color{orange}i$ of electrons.
> > * **Frequency:** Frequency should $\color{orange}ii$. Any light should work if bright enough.
> > 
> > > [!blank]- $\color{orange}i$
> > > energy (and number)
> > 
> > > [!blank]- $\color{orange}ii$
> > > not matter
>
> > [!continue]- Particle Theory (Experimental) Facts
> > * **Intensity:** Increasing intensity increases the ||number|| of electrons, but NOT their ||energy||.
> > * **Frequency:** Kinetic energy increases ||linearly|| with frequency.
> > * **Cutoff:** There is a ||cutoff frequency ($f_0$)|| below which no electrons are emitted, regardless of intensity.
> 
> > [!graph]- Conclusion
> > ![[Pasted image 20260203122047.png]]
> > This shows clear agreement with photon theory, not with wave theory. (no electrons are emitted if $f<f_{0}$)
> > > [!note]- The particle theory assumes that
> > > an electron absorbs a single proton
> 

> [!definition]- Work Function, $W_0$
> The minimum energy required to emit an electron from the surface of a specific metal.

> [!formula]- Work function
> $W_0 = hf_0 = \frac{hc}{\lambda_0}$
> > [!unit]- $W_0$
> > Work function in Joules ($J$) or $eV$
> 
> > [!unit]- $f_0$
> > Threshold frequency (minimum f required) in $Hz$
> 
> > [!unit]- $\lambda_0$
> > Threshold wavelength (maximum $\lambda$ allowed) in $m$

> [!table]- Work functions of several elements
> | Element   | Work function $(eV)$ |
> | --------- | -------------------- |
> | Aluminium | 4.3                  |
> | Sodium    | 2.3                  |
> | Copper    | 4.9                  |
> | Gold      | 5.1                  |
> | Silver    | 4.3                  |

> [!formula]- Einstein's Photoelectric Equation
> Conservation of energy: Photon Energy = Work Function + Kinetic Energy
> $E = W_0 + K_{max}$
> $hf = W_0 + \frac{1}{2}mv_{max}^2$
> > [!unit]- $h$
> > Planck's constant ($6.63 \times 10^{-34}\,J\cdot s$)
> 
> > [!unit]- $f$
> > Frequency of incident light in $Hz$
> 
> > [!unit]- $W_0$
> > Work function of the metal in $J$
> 
> > [!unit]- $K_{max}$
> > Maximum kinetic energy of emitted photoelectron in $J$
> 
> > [!unit]- $m$
> > Mass of an electron ($9.11 \times 10^{-31}\,kg$)
> 
> > [!unit]- $v_{max}$
> > Maximum speed of emitted electron in $m\,s^{-1}$

> [!liststart]- Emission Conditions
> > [!continue]- Case 1: $hf > W_0$
> > ![[Pasted image 20260203123411.png]]
> > Electron emitted with ||excess kinetic energy|| ($K_{max} > 0$).
>
> > [!continue]- Case 2: $hf = W_0$
> > ![[Pasted image 20260203123436.png]]
> > Electron emitted with ||zero kinetic energy|| ($K_{max} = 0$). This defines the threshold.
>
> > [!continue]- Case 3: $hf < W_0$
> > ![[Pasted image 20260203123457.png]]
> > ||No electron|| is emitted.

> [!sq]- Example 11-2: Photon energy
> Calculate the energy of a photon of bluelight, $\lambda=450nm$ in air (or vacuum)
> > [!continue]- Solution
> > $\lambda=450nm=450\times 10^{-9}m$
> > $E=\frac{hc}{\lambda}=\frac{(6.64\times 10^{-14})(3\times 10^{8})}{450\times 10^{-9}}=44.2J$

> [!sq]- Example 11-3: Photons from a lightbulb
> Estimate how many visible light photons a $100\text{-}W$ lightbulb emits per second. Assume 3% efficiency and average $\lambda = 500\,nm$.
> > [!continue]- Solution
> > **Given:**
> > Power $P_{in} = 100\,W$
> > Efficiency $= 0.03$
> > Light Power $P_{light} = 0.03 \times 100 = 3\,J/s$
> > $\lambda = 500 \times 10^{-9}\,m$
> >
> > **Energy of 1 Photon:**
> > $E = \frac{hc}{\lambda} = \frac{(6.63 \times 10^{-34})(3 \times 10^8)}{500 \times 10^{-9}} = 3.98 \times 10^{-19}\,J$
> >
> > **Number of Photons ($n$):**
> > Total Energy = $n \times E_{photon}$
> > $3\,J = n (3.98 \times 10^{-19})$
> > $n = \frac{3}{3.98 \times 10^{-19}}$
> > $\enclose{box}{n \approx 7.5 \times 10^{18}\,\text{photons/sec}}$

> [!sq]- Example 11-4: Photoelectron speed
> What is the kinetic energy and speed of an electron ejected from sodium ($W_0 = 2.28\,eV$) by $410\,nm$ light?
> > [!continue]- Solution
> > **Given:**
> > $W_0 = 2.28\,eV$
> > $\lambda = 410 \times 10^{-9}\,m$
> >
> > **Step 1: Photon Energy ($E$)**
> > $E = \frac{hc}{\lambda} = \frac{(6.63 \times 10^{-34})(3 \times 10^8)}{410 \times 10^{-9}}$
> > $E = 4.85 \times 10^{-19}\,J$
> > Convert to eV: $E = \frac{4.85 \times 10^{-19}}{1.60 \times 10^{-19}} = 3.03\,eV$
> >
> > **Step 2: Check Condition**
> > $E (3.03\,eV) > W_0 (2.28\,eV)$. Electrons are emitted.
> >
> > **Step 3: Maximum Kinetic Energy ($K_{max}$)**
> > $K_{max} = E - W_0 = 3.03 - 2.28$
> > $\enclose{box}{K_{max} = 0.75\,eV}$
> > Convert to Joules: $K_{max} = 0.75 \times 1.60 \times 10^{-19} = 1.2 \times 10^{-19}\,J$
> >
> > **Step 4: Maximum Speed ($v_{max}$)**
> > $K_{max} = \frac{1}{2}mv^2$
> > $1.2 \times 10^{-19} = 0.5 (9.11 \times 10^{-31}) v^2$
> > $v^2 = \frac{1.2 \times 10^{-19}}{4.555 \times 10^{-31}} = 2.63 \times 10^{11}$
> > $v = \sqrt{2.63 \times 10^{11}}$
> > $\enclose{box}{v \approx 5.13 \times 10^5\,m\,s^{-1}}$

# 11.3 Energy, Mass, and Momentum of a Photon

> [!continue]- Momentum of a Photon
> A photon travels at the speed of light ($c$). Although it has zero mass, it carries $\color{orange}i$ and $\color{orange}ii$.
> > [!blank]- $\color{orange}i$
> > energy
> 
> > [!blank]- $\color{orange}ii$
> > momentum

> [!formula]- Photon Momentum, $p$
> Derived from the relativistic energy-momentum relation ($E^2 = p^2c^2 + m^2c^4$ with $m=0$).
> $p = \frac{E}{c} = \frac{hf}{c} = \frac{h}{\lambda}$
> > [!unit]- $p$
> > Momentum in $kg\,m\,s^{-1}$ or $N\,s$
> 
> > [!unit]- $E$
> > Energy in Joules ($J$)
> 
> > [!unit]- $c$
> > Speed of light ($3.00 \times 10^8\,m\,s^{-1}$)
> 
> > [!unit]- $h$
> > Planck's constant ($6.63 \times 10^{-34}\,J\cdot s$)
> 
> > [!unit]- $\lambda$
> > Wavelength in meters ($m$)

> [!sq]- Example 11-5: Photon momentum and force
> Suppose $10^{19}$ photons are emitted per second from a $100\text{-}W$ lightbulb (assuming all are focused and absorbed). Assume $\lambda = 500\,nm$.
> > [!continue]- $a)$ Calculate the momentum of one photon.
> > **Given:**
> > $\lambda = 500\,nm = 500 \times 10^{-9}\,m$
> >
> > **Calculation:**
> > $p = \frac{h}{\lambda} = \frac{6.63 \times 10^{-34}}{500 \times 10^{-9}}$
> > $\enclose{box}{p = 1.33 \times 10^{-27}\,kg\,m\,s^{-1}}$
>
> > [!continue]- $b)$ Estimate the force exerted on the paper.
> > **Concept:**
> > Force is the rate of change of momentum ($F = \frac{\Delta P}{\Delta t}$).
> > Since photons are absorbed, $\Delta p_{photon} = p_{final} - p_{initial} = 0 - p = -p$.
> > Magnitude of force $F = n \times \frac{p}{t}$ (where $n$ is photons per second).
> >
> > **Calculation:**
> > $n = 10^{19}\,s^{-1}$
> > $F = (10^{19})(1.33 \times 10^{-27})$
> > $\enclose{box}{F \approx 1.33 \times 10^{-8}\,N}$

# 11.4 Wave-Particle Duality

> [!continue]- The Dilemma
> We have phenomena like diffraction and interference that show light is a $\color{orange}i$. We also have the photoelectric effect and Compton effect that show light is a $\color{orange}ii$.
> > [!blank]- $\color{orange}i$
> > wave
> 
> > [!blank]- $\color{orange}ii$
> > particle

> [!definition]- Principle of Complementarity
> Proposed by Niels Bohr. It states that both the wave and particle aspects of light are fundamental to its nature.
> * Light is ||dualistic|| in nature.
> * It behaves as a wave in some situations and as a particle in others.

> [!table]- Evidence for Wave-Particle Duality
> | Wave Nature Evidence | Particle Nature Evidence |
> | :--- | :--- |
> | Young's double slit experiment | Photoelectric effect |
> | Diffraction experiment | Compton effect |
> | Polarization | Blackbody radiation |

## de Broglie Wavelength

> [!continue]- de Broglie's Hypothesis (1924)
> Louis de Broglie argued that if light can behave as a particle, then particles (like electrons) might also have $\color{orange}i$ properties.
> > [!blank]- $\color{orange}i$
> > wave

> [!formula]- de Broglie Wavelength, $\lambda$
> The wavelength associated with a material particle of momentum $p$.
> ${\overbrace{\textcolor[RGB]{255,255,0}\lambda}^{\text{wave aspect}}}=\frac{h}{\underbrace{\textcolor[RGB]{255,255,0}{p}}_{\text{particle aspect}}}=\frac{h}{mv}$
> > [!unit]- $\lambda$
> > de Broglie wavelength in meters ($m$)
> 
> > [!unit]- $h$
> > Planck's constant ($6.63 \times 10^{-34}\,J\cdot s$)
> 
> > [!unit]- $p$
> > Momentum in $kg\,m\,s^{-1}$
> 
> > [!unit]- $m$
> > Mass of the particle in $kg$
> 
> > [!unit]- $v$
> > Velocity of the particle in $m\,s^{-1}$

> [!sq]- Example 11-6: Wavelength of a ball
> Calculate the de Broglie wavelength of a $0.20\text{-}kg$ ball moving with a speed of $15\,m/s$.
> > [!continue]- Solution
> > **Given:**
> > $m = 0.20\,kg$
> > $v = 15\,m\,s^{-1}$
> >
> > **Calculation:**
> > $\lambda = \frac{h}{mv}$
> > $\lambda = \frac{6.63 \times 10^{-34}}{(0.20)(15)}$
> > $\lambda = \frac{6.63 \times 10^{-34}}{3.0}$
> > $\enclose{box}{\lambda = 2.21 \times 10^{-34}\,m}$
> > (This is extremely small, which is why we don't see wave effects for macroscopic objects).

> [!sq]- Example 11-7: Wavelength of an electron
> Determine the wavelength of an electron accelerated through a potential difference of $100\,V$.
> > [!continue]- Solution
> > **Step 1: Find Velocity**
> > Kinetic Energy gained = Electric Potential Energy
> > $\frac{1}{2}mv^2 = eV$
> > $v = \sqrt{\frac{2eV}{m}}$
> > $v = \sqrt{\frac{2(1.60 \times 10^{-19})(100)}{9.11 \times 10^{-31}}}$
> > $v = \sqrt{\frac{3.2 \times 10^{-17}}{9.11 \times 10^{-31}}} \approx 5.93 \times 10^6\,m\,s^{-1}$
> >
> > **Step 2: Find Wavelength**
> > $\lambda = \frac{h}{mv}$
> > $\lambda = \frac{6.63 \times 10^{-34}}{(9.11 \times 10^{-31})(5.93 \times 10^6)}$
> > $\enclose{box}{\lambda \approx 1.23 \times 10^{-10}\,m = 0.123\,nm}$
> > (This is comparable to atomic spacing, so electrons can diffract!).

> [!sq]- Example 8: Photoelectric Momentum
> Light ($\lambda = 550\,nm$) is incident on sodium. Determine momentum and energy of the photon.
> > [!continue]- Solution
> > **Given:**
> > $\lambda = 550 \times 10^{-9}\,m$
> >
> > **Momentum:**
> > $p = \frac{h}{\lambda} = \frac{6.63 \times 10^{-34}}{550 \times 10^{-9}}$
> > $\enclose{box}{p = 1.21 \times 10^{-27}\,kg\,m\,s^{-1}}$
> >
> > **Energy:**
> > $E = pc$ (or $E = hf$)
> > $E = (1.21 \times 10^{-27})(3.00 \times 10^8)$
> > $\enclose{box}{E = 3.63 \times 10^{-19}\,J}$

> [!sq]- Example 9: Jogger vs Electron
> Calculate de Broglie wavelength for:
> > [!continue]- $a)$ A jogger ($m=77\,kg$) running at $4.1\,m/s$.
> > $\lambda = \frac{h}{mv} = \frac{6.63 \times 10^{-34}}{(77)(4.1)}$
> > $\lambda = \frac{6.63 \times 10^{-34}}{315.7}$
> > $\enclose{box}{\lambda \approx 2.10 \times 10^{-36}\,m}$
>
> > [!continue]- $b)$ An electron ($m=9.11 \times 10^{-31}\,kg$) moving at $3.25 \times 10^5\,m/s$.
> > $\lambda = \frac{6.63 \times 10^{-34}}{(9.11 \times 10^{-31})(3.25 \times 10^5)}$
> > $\lambda = \frac{6.63 \times 10^{-34}}{2.96 \times 10^{-25}}$
> > $\enclose{box}{\lambda \approx 2.24 \times 10^{-9}\,m}$

# 11.5 Wave Nature of Matter

> [!continue]- Significance
> The wave nature of matter becomes important for very light particles such as the $\color{orange}ii$.
> * Electron wavelengths can be on the order of $\color{orange}i$.
> * Therefore, electrons can be $\color{orange}ii$ by crystals, just as X-rays can.
> 
> > [!blank]- $\color{orange}i$
> > $10^{-10}m$
>  
> > [!blank]- $\color{orange}ii$
> > electron
> 
> > [!blank]- $\color{orange}iii$
> > diffracted

