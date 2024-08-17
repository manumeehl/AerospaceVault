#Method
1. __Calculation of the Number of Nodal and Mesh Equation__
	1. Number of Nodes $k \implies$ number of nodal equations $N = k - 1$
	2. Number of Branches (Elements) $z \implies$ number of meshes/mesh equations $M = z - k + 1$ 
2. __Define Voltage and Current Directions__
	1. Draw arrows at each component for [[Voltage]] and [[Current]], it is sensible to draw them in the [[Current Direction|Technical Current Direction]] 
3. __Mesh Equations__
	1. Evaluate the meshes according to [[Kirchhoff's Voltage Law]], any voltage against the mesh is counted negatively
4. __Nodal Equations__
	1. Evaluate the nodes according to [[Kirchhoff's Current Law]], any [[Current]] going into the node is positive and any [[Current]] going out negative
5. __(Number of Equations)__
	1. Count the number of unknowns $N_{ukn}$
	2. $N_{ukn} - N - M \implies$ Number of [[Ohm's Law]] Equations needed for [[Resistor|Resistors]]
6. __Calculation of Currents or Voltages__
	1. Use the mesh equations to find expressions for the [[Current|Currents]] with [[Ohm's Law]]
	2. Insert these into the nodal equations and solve for the first [[Current]]
	3. Then use this [[Current]] to solve the rest of the equations