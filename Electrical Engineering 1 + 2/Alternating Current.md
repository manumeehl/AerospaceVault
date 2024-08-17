#Knowledge 
### General Information
Alternating [[Current]] is a current which is alternating in direction, changing constantly between a positive and negative maximum value. This mean the signal are time dependent and therefore denoted by lowercase letters, i. e. $v(t)$ or $i(t)$.

----
### Properties of Periodic Signals
The alternating [[Voltage]] below is described by the sinusoidal function: 
$$
v(t) = \hat{V} \cdot sin(\omega t+\gamma_0)
$$
![[Screenshot 2024-08-10 at 18.42.37.png]]

| __Variable__         | __Definition__                            | __Unit__ |
| -------------------- | ----------------------------------------- | -------- |
| $v(t)$               | instantaneous value                       | $V$      |
| $\hat{V}$            | amplitude, peak value                     | $V$      |
| $V_{PP}$             | peak to peak value (twice the amplitude)  | $V$      |
| $\omega$             | angular frequency                         | $rad/s$  |
| $f$                  | frequency                                 | $Hz$     |
| $T$                  | period                                    | $s$      |
| $\gamma_0$           | phase zero (offset of the sinus function) | $rad$    |
| $\omega t +\gamma_0$ | phase angle                               | $rad$    |
One should also know the following two helpful identities: 
$$
\omega = 2\pi f
$$
$$
T = \frac{1}{f}
$$
----
### Electrical Components in AC
It is also important to look at how components behave in an AC-setting, specifically the [[Resistor]], [[Capacitor]], and [[Inductor]]. Firstly, an overview: 

| __Component__           | *Resistor*                         | *Capacitor*                        | *Inductance*                        |
| ----------------------- | ---------------------------------- | ---------------------------------- | ----------------------------------- |
| __[[Impedance]]__       | $Z_R = R$                          | $Z_C = \frac{1}{\omega C}$         | $Z_L = \omega L$                    |
| __Frequency dependent__ | no                                 | yes                                | yes                                 |
| __Phase Difference__    | $\varphi_R = 0$                    | $\varphi_C = -\frac{\pi}{2}$       | $\varphi_L = \frac{\pi}{2}$         |
| __Phase__               | $i_R(t)$ and $v_R(t)$ are in phase | $v_C(t)$ lags $i_C(t)$ by $\pi /2$ | $v_C(t)$ leads $i_C(t)$ by $\pi /2$ |
| __Behavior__            | ohmic                              | reactive                           | reactive                            |
Here the phase difference can be calculated by:
$$
\varphi = \varphi_V  -  \varphi_I
$$
*Resistor:*
![[Screenshot 2024-08-10 at 19.03.50.png]]
*Capacitor:*
![[Screenshot 2024-08-10 at 19.04.17.png]]
*Inductor:*
![[Screenshot 2024-08-10 at 19.04.48.png]]
Expressed in complex numbers [[Current]] and [[Voltage]] can be expressed in polar coordinates: 
$$
\underline{V} = V_{RMS} \cdot e^{j\varphi_V}
$$
$$
\underline{I} = I_{RMS} \cdot e^{j\varphi_I}
$$
Where the $RMS$ (root mean square) are the [[Power in AC|effective values]] of current and voltage.