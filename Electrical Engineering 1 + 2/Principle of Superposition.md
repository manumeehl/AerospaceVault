#Method 
![[Screenshot 2024-05-14 at 12.34.58.png]]
To solve systems like the one above the superposition principle is used. For this we turn of all [[Voltage]]/[[Current]] sources one by one and superimpose the results for each simplified network.
- [[Voltage]] Sources $\rightarrow$ replaced by an ideal wire
- [[Current]] Sources $\rightarrow$ replace by air gap
![[Screenshot 2024-05-14 at 12.44.07.png]]
The short circuit [[Current]] $I_{sc}$ is calculated in the above example in the following way:
$$
I_{sc} = \sum_{n}I_{sc, n} = \frac{V_{01}}{R_{1}} + \frac{V_{02}}{R_{2}}
$$
The no-load [[Voltage]] $V_{nl}$ is calculated in above example the following way:
$$
V_{nl} = \sum_{n}V_{nl, n} = V_{AB, 01} + V_{AB, 02} = V_{01}\frac{R_{2}}{R_{1}+R_{2}} + V_{02}\frac{R_{1}}{R_{1}+R_{2}}
$$
The internal [[Resistance]] is then trivial to calculate: 
$$
R_{i} = \frac{V_{nl}}{I_{sc}} = \frac{R_{1}R_{2}}{R_{1}+R_{2}}
$$
The load [[Current]] is calculated with: 
$$
I_{load}= \frac{V_{nl}}{R_{i}+ R_{load}}
$$
The load [[Power]] can be calculated with the following formula:
$$
P_{load} = R_{load} \ \cdot \ I_{load}^2 = \frac{R_{load}}{(R_{i}+R_{load})^2} \cdot V_{nl}^2
$$
For $R_{load} = R_{i}$ the maximum load [[Power]] is: 
$$
P_{load, max} = \frac{V_{0}^2}{4R_{i}}
$$
The relative load [[Power]] can be calculated by: 
$$
\frac{P_{load}}{P_{load,max}}=\frac{4\cdot\frac{R_{load}}{R_i}}{(1+\frac{R_{load}}{R_i})^2}
$$
The efficiency $\eta$ is expressed as: 
$$
\eta = \frac{\frac{R_{load}}{R_i}}{1+\frac{R_{load}}{R_i}}
$$