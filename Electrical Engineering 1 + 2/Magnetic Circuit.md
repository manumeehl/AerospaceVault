#Component 
![[Screenshot 2024-05-25 at 18.07.10.png]]
A setup with coils which create a [[Magnetic Field]] and different materials through which the magnetic field runs can be simplified into a circuit. This is an analog to the electric circuits. 

The direction of the [[Magnetic Flux]] can be be found with right hand rule. The [[Magnetomotive Force]] then acts in the opposite direction. 

Whenever the geometry (i. e. cross section) or the material (i. e. $\mu_r$) itself changes, a new [[Magnetic Resistance]] must be introduced. 

The analog versions of the Kirchhoff laws as well as [[Ohm's Law]] can then be used to solve the circuit: 
#### [[Ohm's Law]]
$$
\Theta = R_m \cdot \Phi
$$
#### [[Kirchhoff's Current Law]]
$$
\Phi_1 + \Phi_2 + \Phi_3 = 0
$$
#### [[Kirchhoff's Voltage Law]]
$$
\Theta_1 - \Theta_2 = R_{m1} \cdot \Phi_1 - R_{m2} \cdot \Phi_2
$$
$$
\Theta_2 - \Theta_3 = R_{m2} \cdot \Phi_2 - R_{m3} \cdot \Phi_3
$$
----
### Magnetic Coupling: Transformer

![[Screenshot 2024-05-26 at 11.08.15.png]]
With a winding ratio $n$ it holds: 
$$
n = \frac{N_1}{N_2} = \frac{v_1(t)}{v_2(t)} = \frac{i_2(t)}{i_1(t)} 
$$
The Load resistance transferred on the primary side: 
$$
R^{'}_{load} = n^2 \cdot R_{load}
$$
