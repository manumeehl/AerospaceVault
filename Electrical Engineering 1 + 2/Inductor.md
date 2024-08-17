#Component 
### General Information
An inductor is a coil that has a certain [[Inductance]]. It is used to temporarily store [[Energy]] or smooth out [[Current|currents]] or [[Voltage|voltages]]. Its inductance can be calculated by: 
$$
L = \frac{N^2}{R_m}
$$

----
### Charging of an Inductor 
![[Screenshot 2024-05-25 at 19.34.54.png]]
When the inductor is charged the switch is in position (1). [[Current]] starts to flow and a [[Magnetic Field]] is spawned in the inductor. 
[[Current]] and [[Voltage]] are described by the following functions: 
$$
i(t) = I_0 \cdot (1-e^{-\frac{t}{\tau}})
$$
$$
v_L(t) = V_0 \cdot e^{-\frac{t}{\tau}}
$$
Where $\tau$ is the time constant: 
$$
\tau = \frac{L}{R}
$$
![[Screenshot 2024-05-25 at 19.41.39.png]]

----
### Discharging of a Capacitor 
![[Screenshot 2024-05-25 at 19.43.33.png]]
When the inductor is discharged the switch is in position (2). [[Current]] starts to flow due to the [[Faraday's Law of Induction|self-induced]] voltage $v_L$. 
[[Current]] and [[Voltage]] are described by the following functions: 
$$
i(t) = I_0 \cdot e^{-\frac{t}{\tau}}
$$
$$
v_L(t) = -V_0 \cdot e^{-\frac{t}{\tau}}
$$
Where $\tau$ is the time constant: 
$$
\tau = \frac{L}{R}
$$
![[Screenshot 2024-05-25 at 19.48.16.png]]
