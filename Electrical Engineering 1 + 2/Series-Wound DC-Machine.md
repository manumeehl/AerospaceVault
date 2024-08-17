#Component 
### General Information
A Series-Wound Machine (dt. Gleichstromreihenschlussmaschine) is a type of [[DC-Machines|DC-Machine]] which supplies both the armature and the excitation windings from the same [[Electric Energy Sources|power source]]. ![[Reihenschlussmaschine.svg]]
In contrast to the [[Shunt-Wound DC-Machine]], the fact that the excitation and armature windings are connected in series is the main design feature, hence *Reihenschluss*.
![[Screenshot 2024-08-08 at 15.48.11.png]]
__Note:__ It is assumed that: $k_\Phi = const$

----
### Operating Properties
The excitation flux is calculated by: 
$$
\Phi_E = k_\Phi \cdot I_E
$$
And the excitation current by: 
$$
I_E = k_E \cdot I_A
$$
Where the excitation constant is: 
$$
k_E = \frac{R_p}{R_E + R_p} \ ; R_p = 0 \implies k_E= 0, R_p \rightarrow \infty \implies k_E = 1
$$
![[Screenshot 2024-08-08 at 15.58.56.png]]
In contrast to the [[Shunt-Wound DC-Machine]] the torque of a series-wound machine is proportional to to the square of the armature current: 
$$
T_e = k_T k_\Phi k_E \cdot I_A^2
$$
The $T_e$-$n_m$-Diagram looks like this:
![[Screenshot 2024-08-08 at 16.03.02.png]]
The starting torque can be calculated with: 
$$
T_{e, st} = k_T K_\Phi k_E \cdot \left( \frac{V_A}{R_A}\right)^2
$$
The equation for extreme speed operation is: 
$$
n_{m, ex} = - \frac{R_A}{k_V k_\Phi k_E}
$$
This also demonstrates the danger of using a series-wound machine without a load torque as then $R_A \rightarrow 0$ which leads to a runaway and eventual catastrophic destruction of the machine.
To modify the operational behaviour of the machine one has the following options: 
![[Screenshot 2024-08-08 at 16.09.05.png]]
Changing the the excitation flux makes little sense as the impact is limited. By far the best option, again, is changing the armature [[Voltage]]. Alternatively one can change the armature series resistance to increase the torque at low rotational speeds. 
$$
R_A = R_{A, winding} + R_{AS}
$$
