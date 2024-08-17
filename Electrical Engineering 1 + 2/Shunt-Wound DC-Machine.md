#Component 
### General Information
A Shunt-Wound Machine (dt. Gleichstromnebenschlussmaschine) is a type of [[DC-Machines|DC-Machine]] which supplies both the armature and the excitation windings from the same [[Electric Energy Sources|power source]]. ![[Nebenschlussmaschine.svg]]
As one can see, the fact that the excitation and armature windings are connected in parallel is the decisive design feature, hence *Nebenschluss*.
![[Screenshot 2024-08-08 at 15.13.08.png]]
__Note:__ It is assumed that: $k_T \cdot \Phi_E = const$, $\Phi_E = const$, and typically $k_V \cdot \Phi_E = const$

----
### Operating Properties
The starting armature [[Current]] is: 
$$
I_{A,st} = \frac{V_A}{R_A}
$$
Since the induced [[Voltage]] $V_i$ is zero (this can be obtained by the [[DC-Network-Analysis|mesh equation]] for the circuit).
The starting torque is: 
$$
T_{e, st}= k_T \cdot \Phi_E \cdot I_{A, st}
$$
The no-load speed ($I_A = 0$, $V_i = V_A$) is: 
$$
n_0 = \frac{V_A}{k_V \cdot \Phi_E}
$$
These equations lead to the following equation for torque and operating modes: 
$$
T_e = T_{e, st} \cdot \left(1- \frac{n_m}{n_0}\right)
$$
![[Screenshot 2024-08-08 at 15.26.44.png]]
The properties of Shunt-Wound Machine can be altered by the following means: 
![[Screenshot 2024-08-08 at 15.31.52.png]]
Increasing the armature resistance is not desirable since it decreases efficiency. To increase the no-load speed and decrease torque one can decrease the excitation flux. The best choice for the operation of a shunt-wound machine is the armature voltage, by changing it one can choose a corresponding starting torque and no-load speed pair at will.