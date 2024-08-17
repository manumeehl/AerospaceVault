#Component 
Transistor are electrical switches made of [[Semiconductors]] operated by an input [[Voltage]]. There are two main types of transistors: 
1. __BJT__ (Bipolar Junction Transistors)
2. __FET__ (Field Effect Transistor)

----
### Bipolar Junction Resistor
Depending on their structure, a distinction is made between npn- and pnp-types. 
![[Screenshot 2024-05-26 at 13.59.50.png]]
A transistor has three different connections: 
1. Base (B)
2. Collector (C)
3. Emitter (E)
Both the npn-type (left) and the pnp-type (right) can be drawn as equivalent circuit diagrams:
![[Screenshot 2024-05-26 at 14.06.50.png]]

It can further be operated in three ways: 
- __emitter circuit__ (most common, suitable for amplifier circuits)
- __collector circuit__ (high input [[Resistance]], low output [[Resistance]])
- __base circuit__ (low input [[Resistance]], high output [[Resistance]])

![[Screenshot 2024-05-26 at 14.10.30.png]]

----
### How it works
![[BJT_NPN_symbol.svg.png]]A npn-transistor functions in the following way: 
- Initially, there is only a positive [[Voltage]] between the collector (C) and the emitter (E) $V_{CE}$ > 0.
- The transistor is in reverse mode. No [[Current]] can flow through the collector (C) and base (B): $I_C$ = 0.
- If a positive base-emitter (B-E) voltage $V_{BE}$ > 0 is applied, which exceeds the diffusion voltage of the transistor (for silicon transistors at $V_D$ = 0.7 V), a current starts to flow through collector (C) and emitter (E), i. e. the transistor turns conductive.

----
#### Current Behaviour  
- The main characteristic of a BJT transistor can be described as the current multiplication of the base current $I_B$ with the collector current $I_C$
- In normal operation, $I_B \ll I_C$
- The current gain of a transistor corresponds to the ratio of the collector current $I_C$ to the base current $I_B$ and is defined as the gain factor $\beta$
- typical values for $\beta$ range from 10-250
- $V_{CE}$ is assumed to constant
$$
\beta = \frac{dI_C}{dI_B}
$$
The output characteristic field of a transistor can be divided into three areas:![[Screenshot 2024-05-26 at 14.28.00.png]]
- Saturation area
- Linear range
- Breakdown area
$\rightarrow$ When designing a circuit, make sure to operate the transistor in the saturation region

----
### MOSFET 
MOSFET stands for Metal Oxide Semiconductor Field-Effect Transistor. They are distinguished into n-type and p-type according to their internal structure. Their analogous three terminals are labeled differently, however: 
- Emitter $\widehat{=}$ Source
- Collector $\widehat{=}$ Drain
- Base $\widehat{=}$ Gate
![[Screenshot 2024-05-26 at 14.37.27.png]]
- The gate is connected to the doped regions of the transistor via an insulating layer
- When a [[Voltage]] is applied to the gate, the insulated connection effects an electric field between the drain and source, allowing or preventing [[Current]] flow
- At low frequencies at the gate input, the MOSFET hence requires a very low [[Power]]

#### Operating Characteristics
- It also works in three ranges:
	- Ohmic/triode range (I)
	- Saturation range (II and III)
	- Breakdown range (IV)
- The linkage between the drain current $I_D$ and the drain-source voltage $V_{DS}$ for different values of the gate-source voltage $V_{GS}$ can be seen in the following characteristics

![[Screenshot 2024-05-26 at 14.44.39.png]]

----
### IGBT (Insulated-Gate Bipolar Transistor)
- The advantages of BJTs (high reverse [[Voltage|voltages]] with low forward [[Resistance|resistances]]) and MOSFETs (little power required for driving) are combined in the IGBTs
- IGBTs are thus particularly suitable for high-[[Power|power]], high-voltage and high-current applications
- They also have three terminals: Collector (C), Gate (G) and Emitter (E)

The structure of an IGBT consists of a Darlington circuit of a pnp-BJT and a n-channel MOSFET. The Darlington circuit is used when very large currents are to be switched with low powers. The IGBT is controlled via the gate of the MOSFET: If the gate-emitter voltage $V_{GE}$ exceeds the threshold voltage, current flows across the BJT.
![[Screenshot 2024-05-26 at 14.50.27.png]]
#### Operating Characteristics 
The IGBT operates in three ranges:
- Reverse blocking range
- Linear/saturation range
- Active range

![[Screenshot 2024-05-26 at 14.53.20.png]]
![[Screenshot 2024-05-26 at 14.54.04.png]]
