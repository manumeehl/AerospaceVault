#Component 
### Introduction
![[Gleichstrommaschine.svg]]

A DC-Machine can be used to either as a motor or as a [[Electric Energy Sources|generator]]. It consists of a magnet and an armature. Either the magnet or the armature is rotating. As current is passing through the armature (dt. Anker) the [[Lorentz Force]] will cause the rotor to spin until it reaches an equilibrium point. However, when it reaches that equilibrium point the commutator (dt. Stromwender) will switch the [[Current|current direction]] and thereby cause the motor to keep spinning. The simple motor shown above can, especially in low speed operation with little inertia, align magnetically with the stator, causing a deadlock. Therefore motors in practice have at least two coils, as one will see in the chapters on the different types of machines. When used as a generator the DC-Machine will produce a pulsating DC-current.  

__See if you can derive the direction of rotation using the [[Lorentz Force]].__
![[Animation_einer_Gleichstrommaschine_(Variante).gif]]

----
### Electro-mechanical [[Energy]] Conversion
![[Screenshot 2024-08-08 at 10.24.16.png]]
The [[Magnetic Flux]] of a conductor loop in a [[Magnetic Field]] is described by: 
$$
\Phi_{loop}(t) = B \cdot A(t) = B \cdot l\cdot d\cdot cos\alpha(t) = \hat{\Phi}_{loop}\cdot cos\alpha(t)
$$
With $\hat{\Phi}_{loop}$ being the amplitude: 
$$
\hat{\Phi}_{loop} = B \cdot l\cdot d
$$
The angle $\alpha$ is the angle between the magnetic field lines and the normal vector of the area. This also explains the movement of the coil when installed in a DC-Machine: 
![[JPEG image-478A-91A5-6E-0.jpeg]]
Should the coil have several turn $N$ the magnetic flux linkage, as defined by [[Faraday's Law of Induction]], is used instead of the [[Magnetic Flux]]:
$$
\Psi_{coil}(t) = N \cdot \Phi_{loop}(t)  = \hat{\Psi}_{coil}\cdot cos\alpha(t)
$$
And the amplitudes: 
$$
\hat{\Psi}_{coil} = N \cdot \hat{\Phi}_{loop}
$$
$$
\hat{\Phi}_{loop} = B \cdot l\cdot d
$$
When the coil rotates with a __constant__ angular frequency $\omega_m$ the induced [[Voltage]], as can be derived by [[Faraday's Law of Induction]], is: 
$$
\hat{V}_{i, coil} = \omega_m \cdot \hat{\Psi}_{coil}
$$
![[Screenshot 2024-08-08 at 11.04.35.png]]
If the coil carries a [[Current]] $i(t)$ which causes a [[Lorentz Force]] to act on the coils sides: 
$$
F(t) = N \cdot i(t) \cdot l \cdot B
$$
The rotationally tangential force components can be calculated by the following equation: 
$$
F_t(t) = F(t) \cdot cos\alpha (t)
$$
This also explains why $F_t = 0$ for $\alpha = 90°$.
![[Screenshot 2024-08-08 at 11.11.06.png]]
Concisely speaking, the fixed flux $\vec{B}$ and the rotatable flux $\vec{B}_{coil}$ want to align which leads to the rotating motion $\omega_m$.
![[Screenshot 2024-08-08 at 11.12.01.png]]
The torque $T_{e, coil}$ can be calculated by: 
$$
T_{e, coil}(t) = \hat{\Psi}_{coil} \cdot i(t) \cdot cos\alpha(t)
$$
With the power balance: 
$$
p_m = p_{el, i}
$$
Where the $p_m$ is the mechanical power and $p_{el, i}$ is the electrical power the following relationship is derived: 
$$
T_{e, coil}(t) = \frac{p_{el, i}(t)}{\omega_m} = \frac{v_{i, coil} \ \cdot i(t)}{\omega_m} = \frac{p_{m}(t)}{\omega_m}
$$
----
### DC-Machine Fundamentals
Below one can see a two-pole $(p=1)$ DC-Machine. 
![[Screenshot 2024-08-08 at 11.23.59.png]]
![[Screenshot 2024-08-08 at 11.24.54.png]]
Since the effect of the [[Inductor|inductors]] in the excitation and armature circuit have decayed in steady-state operation, one can simplify the circuits in the following way: 
![[Screenshot 2024-08-08 at 12.23.30.png]]
__Note:__ There are no [[Inductor|inductors]] installed in these circuits, rather the winding of the coils themselves causes them to have the properties of an inductor.

This circuit leads to the following equations:
$$
V_A = R_A  \ \cdot I_A + V_i
$$
$$
V_E = R_E  \ \cdot I_E
$$
The induced voltage in the armature winding is calculated with the following formula: 
$$
V_{i, conductor} = 2p \ \cdot \Phi_E \cdot n_m
$$
Where $\Phi_E$ is the the magnetic flux per pole: 
$$
\Phi_E = \frac{\pi \cdot D_A}{2p} \cdot l_a \cdot B_E
$$
And $n_m$ is the rotational speed: 
$$
n_m = 2\pi \cdot \omega_m
$$
The induced [[Voltage|voltage]] on the whole armature winding is: 
$$
V_i = k_V \cdot \Phi_E \cdot n_m
$$
The machine constant for voltage is: 
$$
k_V = 4p \cdot N_A
$$
The torque on the entire rotor can be calculated by: 
$$
T_e = k_T \cdot \Phi_E \cdot I_A
$$
With machine constant for the torque being: 
$$
k_T = \frac{k_V}{2\pi}
$$

----
### Types of DC-Machines
Typical DC-Machines are usually based on one of these three fundamental circuits: Separately Excited DC-Machine, [[Shunt-Wound DC-Machine]], or the [[Series-Wound DC-Machine]].
![[Screenshot 2024-08-08 at 14.41.06.png]]
The terms "Separately Excited DC-Machine" and "Shunt-Wound DC-Machine" are often used interchangeably. Strictly speaking the two configurations only have the same meaning if $V_A \neq f(I_A + I_E)$

----
### Control of DC-Drives
A shunt wound machine can be fed by a DC/DC converter. By varying the armature [[Voltage]] the speed of the motor can be controlled: 
![[Screenshot 2024-08-08 at 16.24.42.png]]
The motor can also be controlled by varying the [[Resistance]] of the motors armature which leads to the following operating curves: 
![[Screenshot 2024-08-08 at 16.36.50.png]]
The torque drops after $n_base$ because in the constant power region the [[Current]] and [[Voltage]] must be constant and thereby the increased speed causes a reduced excitation flux and therefore reduced torque. 