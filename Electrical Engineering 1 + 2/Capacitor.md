#Component 
### General Information
A capacitor is an electrical component which stores electrical [[Energy]] by accumulating [[Charge]] on two surfaces insulated from each other. 
The charge stored in a capacitor can be calculated by:
$$
Q = C \cdot V \iff q_c(t) = C \cdot v_c(t)
$$
---
### Charging of a Capacitor 

![[Screenshot 2024-05-23 at 17.01.51.png]]
When the capacitor is charged the switch is in position (1). [[Charge]] starts to flow from the [[Electric Energy Sources|Current Source]] to the capacitor where it accumulates. 
[[Voltage]] and [[Current]] are described by the following functions: 
$$
v_c(t) = V_0\cdot (1-e^{-\frac{t}{\tau}})
$$
$$
i(t) = \frac{V_0}{R} \cdot e^{-\frac{t}{\tau}}
$$
Where $\tau$ is the time constant: 
$$
\tau = R \cdot C
$$
![[Screenshot 2024-05-23 at 17.09.26.png]]

---- 
### Discharging of a Capacitor 
![[Screenshot 2024-05-23 at 17.10.52.png]]

When the capacitor is discharged the switch is in position (2). [[Charge]] starts to flow from the negatively charged plate to the positively charged one.
[[Voltage]] and [[Current]] are described by the following functions:
$$
v_c(t) = V_0\cdot e^{-\frac{t}{\tau}}
$$
$$
i(t) = -\frac{V_0}{R} \cdot e^{-\frac{t}{\tau}}
$$
Where $\tau$ is the time constant: 
$$
\tau = R \cdot C
$$
![[Screenshot 2024-05-23 at 17.14.11.png]]

--- 
### Formula for Energy and Forces
The change in [[Energy]] when charging a capacitor from $V_1$ to $V_2$ in \[$t_1,t_2$]:
$$
\Delta W_{el12} = \frac{1}{2} \cdot C \cdot (V_2^2-V_1^2)
$$
The [[Energy]] content of a capacitor is: 
$$
W_{el} = \frac{1}{2} \cdot C\cdot V^2= \frac{1}{2} \cdot\epsilon \cdot \frac{A}{d} \cdot V^2
 $$
 The volumetric [[Energy]] density is: 
$$
 w_{el} = \frac{1}{2} \cdot E \cdot D
$$
##### Field Path Perpendicular to the Boundary Surface 
![[Screenshot 2024-05-23 at 17.29.49.png]]
Mechanical Force: 
$$
F = \frac{1}{2} \cdot Q \cdot (E_1-E_2)
$$
Mechanical Force Density: 
$$
\sigma_\perp = \frac{1}{2} \cdot (\epsilon_2 - \epsilon_1) \cdot \frac{\epsilon_1}{\epsilon_2} \cdot E_\perp^2
$$
##### Field Path Parallel to the Boundary Surface

![[Screenshot 2024-05-23 at 17.30.21.png]]
Mechanical Force: 
$$
F = \frac{1}{2} \cdot V^2 \cdot (\epsilon_2-\epsilon_1) \cdot \frac{a}{d}
$$
Mechanical Force Density: 
$$
\sigma_{||} = \frac{1}{2} \cdot (\epsilon_2 - \epsilon_1)  \cdot E_{||}^2
$$

---- 
### The Capacitor as a Real Component 
- (De-) centralised energy storage
- Short charging and discharging times
- Covering of power peaks
- Operational protection of the vehicle power net
- Safe energy supply for safety-critical components