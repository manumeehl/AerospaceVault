#Component 
![[Screenshot 2024-08-12 at 12.10.16.png]]
A synchronous machine consists of a stator with a [[3-Phase AC Systems|3-phase AC winding]] and a rotor which is excited by a DC-current. The rotation is synchronous to the frequency of the [[Magnetic Field|rotating magnetic field]] induced by the stator, hence synchronous machine. At this synchronous speed the torque is constant. The machine can be represented by a [[Alternating Current|1-phase AC]] system: 
![[Screenshot 2024-08-12 at 12.35.36.png]]
Here $R_1$ is the ohmic [[Resistance]] of the stator branch and $X$ is the synchronous [[Impedance|reactance]].
The synchronous machine can operate both as a generator and a motor and either as an over or under-excited machine. 
![[Screenshot 2024-08-12 at 12.44.10.png]]
The branch current is indicative of the operating mode (generator or motor) of the machine: 
$$
\mathfrak{R}(I_{Br}) > 0 \implies motor
$$
$$
\mathfrak{R}(I_{Br}) < 0 \implies generator
$$
From the load angle $\vartheta_0$ one can see whether the machine is over or under-excited. Since $\underline{V}_1$ is always on the real axis the following holds: 
$$
\vartheta_0 = \angle(\underline{V}, \underline{V}_p) \iff \vartheta_0  =arctan\left(\frac{\mathfrak{I}(\underline{V}_p)}{\mathfrak{R}(\underline{V}_p)}\right)
$$
$$
\underline{V}_p < \underline{V}_1 \implies underexcited
$$
$$
\underline{V}_p > \underline{V}_1 \implies overexcited
$$
If the machine is loaded with to high of a load it falls out of step. This torque is called pull-out torque $T_{po}$.
![[Screenshot 2024-08-12 at 13.33.11.png]]
The torque the machine produced/requires can be obtained from the pull-put torque: 
$$
T_e = - T_{po} \cdot sin(\vartheta_0)
$$
The [[Power|electrical power]] of a synchronous machine is the sum of the branch powers and the excitation power: 
$$
P_{el, tot} = \sum P_{el, Br} + P_{el, E}
$$
The *Wirk-* and *Blindleistung* can be calculated with following formulae as well: 
$$
P = S \cdot cos(\varphi_1)
$$
$$
Q = S \cdot sin(\varphi_1)
$$

