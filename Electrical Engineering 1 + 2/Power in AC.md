#Knowledge 
### General Information
The instantaneous [[Power]] for [[Alternating Current|AC loads]] works the same as the power in DC: 
$$
P = v(t) \cdot i(t)
$$
In AC, the power at a resistor is positive all the time whereas for [[Capacitor|capacitors]] and [[Inductor|inductors]] the power is positive or negative. This leads to an average power of zero for these components. The average power is defined as: 
$$
P_{avg} = \frac{1}{T}\int_0^T p(t) dt = \frac{1}{2\pi}\int_0^{2\pi} p(\omega t) d \omega t
$$
This leads to the root-mean-square values of [[Current]] and [[Voltage]]: 
$$
P_{avg} = V_{RMS} \ \cdot I_{RMS} 
$$
These correspond to the DC voltage and current which would convert the same [[Energy|electrical energy]] at a [[Resistor]].
For sinusoidal quantities it holds: 
$$
I_{RMS} = \frac{\hat{I}}{\sqrt{2}}
$$
$$
V_{RMS} = \frac{\hat{V}}{\sqrt{2}}
$$
----
### Active Power 
The active power or *Wirkleistung* is the amount of power that is actually used or average power over one $T$. It can be calculated with: 
$$
P = V_{RMS} \ \cdot I_{RMS} \cdot cos(\varphi)
$$
#### [[Power|Watt]] \[$J/s$]
----
### Reactive Power
The reactive power or *Blindleistung* is the total amount of [[Energy]] that alternates between the generator and the load and is not converted into another form of energy. It can be positive (inductive) or negative (capacitive): 
$$
Q = V_{RMS} \ \cdot I_{RMS} \cdot sin(\varphi)
$$
#### [[Voltage|Volt]] [[Current|Ampère]] reactive \[VAr]
----
### Apparent Power
The apparent power or *Scheinleistung* is combination of active and reactive power. 
$$
S = V_{RMS} \ \cdot I_{RMS} = \sqrt{P^2 + Q^2}
$$
#### [[Voltage|Volt]] [[Current|Ampère]] \[VA]
