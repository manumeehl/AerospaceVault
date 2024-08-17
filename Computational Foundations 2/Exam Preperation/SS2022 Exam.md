##### Task 1: Multiple Choice Questions
1. IEEE standard for floating point numbers (754) supports certain special values like infinity.
	- **True** - IEEE 754 supports special values like infinity and NaN (Not a Number).
2. A 4-bit signed integer ranges from including -7 to including 8.
	-  **False** - A 4-bit signed integer ranges from -8 to 7.
3. hen adding two 8-bit numbers, the result can be held in 9 bits.
	- **True** - When adding two 8-bit numbers, the result can be held in a 9-bit number to accommodate overflow.
4. For computing the shortest path between all nodes of a graph,  one typically runs Dijkstra with each node as the starting point
	- For computing the shortest path between all nodes, Floyd-Warshall  or A* is typically used. Running Dijkstra from each node is less efficient.
6. Binary Search is performing a search on ordered datasets by looking at the (approximately) middle data and continuing in each iteration with only (roughly) half of the array size.
	- **True** - Binary Search involves looking at the middle element and continuing the search in half of the array.
7. The SPI bus is a communication system for connecting devices  
using 4 lanes (𝑆𝐶𝐿𝐾, 𝐶𝑆, 𝑀𝐼𝑆𝑂, 𝑀𝑂𝑆𝐼)
	- **True** - The SPI bus uses 4 lanes: SCLK, CS, MISO, and MOSI.
8. In merge sort, the data is first cut into pieces for being sorted and the sorted pieces are assembled to a sorted version of the data
- **True** - In merge sort, the data is divided into pieces, sorted, and then merged back together.

##### Task 4
Analog Digital Conversion converts analogous signals into a digital representation. Explain the following two aspects each in one sentence:

**a. Quantization:** Quantization is the process of converting the continuous amplitude of an analog signal into a discrete value within a predefined range, effectively rounding the signal to the nearest available digital level.

**b. Sampling:** Sampling involves taking discrete measurements of the analog signal at regular intervals, capturing snapshots of the signal's amplitude over time.

##### Task 5
A state machine is a programming model in which two combinatorial circuits are  
combined with a state memory in order to achieve very complex behaviour.  
a. Give names or very short descriptions for the two combinatorial circuit:

1. **Next State Logic:** This circuit determines the next state of the state machine based on the current state and the input signals.
2. **Output Logic:** This circuit generates the output signals of the state machine based on the current state and potentially also the input signals.
