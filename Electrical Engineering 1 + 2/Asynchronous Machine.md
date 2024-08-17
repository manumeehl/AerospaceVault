#Component 
![[Screenshot 2024-08-12 at 13.57.02.png]]
Like the [[Non-Salient Pole Synchronous Machine]], the asynchronous machine has a stator and a rotor. The stator is connected to a [[3-Phase AC Systems|3-phase AC power source]] and thereby generates a [[Magnetic Field|rotating magnetic field]]. The rotor contains windings on which a [[Current]] is [[Faraday's Law of Induction|induced]] by the magnetic field. This current the causes the rotor to spin due to the [[Lorentz Force]]. This also means that the motor is self starting and that the stable operating frequency is determined by the load torque. Since the the rotor will spin as fast (no-load) or slower than the magnetic field, the machine is called asynchronous. 
$$
n_m < n_{syn}
$$
The slip describes how much the rotor lags behind the magnetic field and is defined as: 
$$
s = \frac{n_{syn} - m_m}{n_{syn}}
$$
The speed can also be calculated from the slip: 
$$
n = (1- s_{po}) \cdot n_{syn}
$$
The speed torque-speed-characteristic of the induction machine look very similar to the one of the synchronous machine. Here __1__ is the torque when the machine is stationary. __2__ is the pull-out torque. __3__ is the no-load speed. Note that at standstill the slip is $s = 1$ and at no load the the slip is $s = 1$.
![[Screenshot 2024-08-12 at 14.34.53.png]]
In a Y-$\Delta$-connection the torque from the switchover is related in the following way: 
$$
T_{e, \Delta} = 3 \cdot T_{e, Y}
$$
