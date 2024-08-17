#Größe 
### General Information
Impedance is a type of complex [[Resistance]] which is used in [[Alternating Current|AC circuits]]. It comprises of the real-valued [[Resistance]] $R$ (dt. *Wirkwiderstand*) and the imaginary reactance $jX$ (dt. Blindwiderstand). The absolute value of impedance $Z$ or $|\underline{Z}|$ is called *Scheinwiderstand* in German. 
In polar form it is represented as: 
$$
\underline{Z} = |\underline{Z}|\cdot e^{j\varphi}
$$
Where $\varphi$ is the [[Alternating Current|phase angle]].
The combinatory effects of impedance and reactance or more tangible in the cartesian coordinate system: 
$$
\underline{Z} = R + jX
$$
This mean that the *Scheinwiderstand* can therefore be calculated using the Pythagorean theorem: 
$$
Z = \sqrt{R^2+X^2}
$$
![[Widerstand_Zeiger.svg]]
The complex-valued impedance is used in calculations with the complex-valued [[Current]] and [[Voltage]]. This leads to the following variant of [[Ohm's Law]]:
$$
\underline{Z} = \frac{\underline{v}}{\underline{i}}
$$
The *Scheinwiderstand* can be used when dealing with the real-valued amplitudes $\hat{V}$ and $\hat{I}$ or the [[Power in AC|effective values]] $V_{RMS}$ and $I_{RMS}$ :
$$
Z = \frac{\hat{V}}{\hat{I}} = \frac{V_{RMS}}{I_{RMS}}
$$
----
### The Impedance of Components
In [[Alternating Current|AC circuits]] the impedances of series connected components are simply added together: 
$$
\underline{Z}_{tot} = \sum_{\nu = 1}^k \underline{Z}_\nu
$$
Note that one has to pay attention to the phase angle, a [[Resistor]] and [[Capacitor]] connected in series leads to: 
$$
\underline{Z} = R \ - \ j\frac{1}{\omega C}
$$
Whereas a [[Resistor]] and [[Inductor]] have an impedance of: 
$$
\underline{Z} = R \ + \ j\omega L
$$
Components connected in parallel work analogously to [[Resistor Parallel Connection|resistors connected in parallel]], i. e. for two impedances: 
$$
\underline{Z}_{tot} = \frac{\underline{Z}_1 \cdot \underline{Z}_2}{\underline{Z}_1 + \underline{Z}_2}
$$
