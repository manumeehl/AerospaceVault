#Component 
![[Screenshot 2024-04-20 at 18.51.25.png]]
[[Resistor|Resistors]] connected in parallel have the following properties:
$$
V_{1} = V_{2} = \ ... \ = V_{n} = V
$$
$$
I_{tot} = \sum_{\nu = 1}^{n}I_{\nu}=\sum_{\nu = 1}^{n}\frac{V}{R_{\nu}}=\frac{V}{R_{tot}} \implies I_{\nu} = \frac{V}{R_{\nu}}
$$
$$
\frac{1}{R_{tot}}
 = \sum_{\nu = 1}^{n}\frac{1}{R_{\nu}}$$

### Application: The [[Current]] Divider
![[Screenshot 2024-04-20 at 19.03.11.png]]
1. __Fundamental Approach__
	1. $\frac{1}{R_{tot}}= \frac{1}{R_{1}} + \frac{1}{R_{2}} \implies R_{tot} = \frac{R_{1}R_{2}}{R_{1}+R_{2}}$
	2. $V = R_{tot} \cdot I_{0}$
	3. With [[Ohm's Law]]: $I_{2} = \frac{V}{R_{2}} = I_{0}\frac{R_{tot}}{R_{2}}$
2. __Direct Approach__
$$
\frac{I_{\nu}}{I_{tot}}=\frac{R_{tot}}{R_{\nu}} \implies \frac{I_{2}}{I_{0}}=\frac{R_{tot}}{R_{2}}
$$
with $I_{tot} = I_{0}$
