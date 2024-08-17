#Knowledge 
Semiconductors are materials that can conduct and insulate. The [[Conductivity]] is between those of conductors and insulators: 

| Category      | Material     | Conductivity in \[$(\Omega m)^{-1}$] |
| ------------- | ------------ | ------------------------------------ |
| Conductor     | Silver       | $62 \cdot 10^6$                      |
| __--__        | Copper       | $58 \cdot 10^6$                      |
| Semiconductor | Silicon      | $1 \cdot 10^{-2}$ to $1\cdot 10^2$   |
| Insulator     | Quartz glass | $1 \cdot 10^{-13}$                   |

----
### Valence and Conduction Band

![[Screenshot 2024-05-26 at 11.29.02.png]]
Silicon has four valence electrons. At 0$K$, all electrons are in the valence band $\rightarrow$ not conductive.
If the silicon crystal is heated, an electron can be lifted into the conduction band (1,1 eV) making it available for [[Charge]] transport.

At any give temperature there exists an equilibrium of electrons leaving the valence band (generation) and filling the hole again (recombination).

![[Screenshot 2024-05-26 at 11.34.17.png]]
_There are also so called wide-gap semiconductors at $W_g \approx 3 \ eV$_

----
### Doping 
#### n-doped Semiconductors 
![[Screenshot 2024-05-26 at 11.38.38.png]]
Silicon in the lattice replaced with pentavalent atom (e. g. phosphorus), so that fifth electron only has a small band gap. 

$\implies$ More free electrons than holes
$\implies$ Electrons are majority charge carriers, holes are minority charge carriers
#### p-doped Semiconductors
![[Screenshot 2024-05-26 at 11.40.43.png]]
Silicon in the lattice replaced with trivalent atom (e. g. boron), so that the band gap is very small, so an electron is easily absorbed. 

$\implies$ More holes than free electrons 
$\implies$ Holes are majority charge carriers, electrons minority charge carriers

----
### Drift and Diffusion [[Current]]
When electrons or holes can move freely in the semiconductor a current $I$ can flow. 
The [[Electrical Current Density|current density]] then is: 
$$
s = \frac{I}{A}
$$
The total current density then is the algebraic sum of the electron and hole current densities: 
$$
s = s_n + s_p
$$
#### Drift Current
![[Screenshot 2024-05-26 at 11.49.15.png]]
If an [[Electric Field]] $E$ is applied to a semiconductor the electrons are accelerated against the field direction and the holes move in the direction of the field. 
At lower [[Electrical Field Strength|field strengths]] the acceleration is roughly proportional. At higher field strengths, temperature, and doping density this effect is decreased due to scattering in the lattice.  

#### Diffusion Current 
Free moving charge carriers move, on average, from a region of higher concentration to a region of lower concentration. This is independent of the [[Electric Field]] or the [[Charge]] of the particles. 

----

### The p-n Junction 
![[rSjj0 1.jpg]]
If a [[Semiconductors#p-doped Semiconductors|p-doped semiconductor]] and a [[Semiconductors#n-doped Semiconductors|n-doped semiconductor]] are connected, the electrons of the p-doped region diffuse to the n-doped region and the holes from the n-doped region to the p-doped region. This leaves negatively charged depletion layer in the p-type and a positive depletion layer in the n-type. The [[Electric Field]] that is created eventually counteracts the diffusion current $\rightarrow$ equilibrium. 

----
### Materials 
- The predominant semiconductor material is silicon due to wide availability and processing properties
- There are materials with better properties $\rightarrow$ wider band gap
- Most advanced materials: silicon-carbide (SiC) and gallium-nitride (GaN)

![[Screenshot 2024-05-26 at 14.58.03.png]]
- High critical field $\implies$ work at high voltage
- High electron mobility $\implies$ work at high switching frequencies
- High thermal conductivity $\implies$ work with high power density

