#Knowledge 
### General Information
3-Phase [[Alternating Current]] (dt. Drehstrom) is an electrical system used by most power grids and industrial settings. 0. This technology is defined by three single AC circuits with their respective voltages shifted in time by one third of a period with respect to each other. 
![[Screenshot 2024-08-11 at 11.14.35.png]]
Where:
$$
\underline{V}_1 + \underline{V}_2 + \underline{V}_3  =0
$$
### Wye- and Delta-Connection
![[Screenshot 2024-08-11 at 11.17.50.png]]
In both cases no return wires are necessary as the currents at the centre point of the Wye-circuit and the in entirety of the delta connection cancel out. However, in practice a neutral wire is attached to the centre of the Wye- and to one of the corners of the Delta-connection as a safety precaution in case of an imbalanced grid. It is assumed that the systems are symmetrical, i. e. that the amplitudes of the voltages are all the same, that the impedances are the same, etc..
The connection mainly vary in how the [[Current]] and [[Voltage]] of the lines behave in relation to the current and voltage of the branches. For the Wye-connection the terminal values (suffix $L$ or $LL$) and the load values (suffix $Br$) are in the following relationship: 
$$
V_{Br} = \frac{V_{LL}}{\sqrt{3}}
$$
$$
I_{Br} = I_{L}
$$
For the Delta-connection inverse is true: 
$$
V_{Br} = V_{LL}
$$
$$
I_{Br} = \frac{I_{LL}}{\sqrt{3}}
$$
### [[Power]] of 3-Phase AC-Connections
The [[Power in AC|apparent power]] is equal to: 
$$
\underline{S} = \sqrt{3} \cdot V_{LL} \cdot I_L \cdot e^{j\varphi} = P + jQ
$$
Or in real values: 
$$
S = 3 \cdot V_{Br} \cdot I_{Br}
$$
The active and passive power can hence be calculated by: 
$$
P = \sqrt{3} \cdot V_{LL} \cdot I_L \cdot cos(\varphi)
$$
$$
Q = \sqrt{3} \cdot V_{LL} \cdot I_L \cdot sin(\varphi)
$$