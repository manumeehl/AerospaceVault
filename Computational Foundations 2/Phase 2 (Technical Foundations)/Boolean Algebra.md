##### The boolean identity
ℬ = { 𝑥 ∈ ℤ: 𝑥 ⋅ 𝑥 = }
ℬ = {0,1}

##### The AND-Operator
X = 𝑥 ∧ 𝑦 := xy

##### The NOT-Operator
X = ¬ 𝑥 = 1 − 𝑥

##### The OR-Operator
OR can be represented by AND and NOT as follows:
a OR b = 𝑎 ∨ 𝑏 = 𝑥 + 𝑦 − 𝑥𝑦 = ¬(¬𝑎 ⋅ ¬𝑏)

##### The XOR-Operator
𝐴 XOR 𝐵 = 𝐴 ⊕ B
𝑥 ⊕ 𝑦 = (𝑥 ∧ ¬𝑦) ∨ (𝑦 ∧ ¬𝑥)

---

##### Boolean Functions
"A Boolean function is a function of sets ℬ 𝑛 → ℬ 𝑚 mapping a set of inputs 𝑎, 𝑏, 𝑐, 𝑑, … ∈ ℬ 𝑛 to a set of outputs 𝑓1 𝑎, 𝑏, 𝑐, 𝑑, … , 𝑓2 𝑎, 𝑏, 𝑐, 𝑑, … ∈ ℬ 𝑚."

- For every Boolean functions exists a truth table with all combinations of inputs and outputs
- A function with n inputs has 2 𝑛 distinct input vectors

The output space dimensions can be considered individually (e.g., the function can be decomposed into multiple functions ℬ 𝑛 → ℬ of the from 𝑓𝑖 𝑎, 𝑏, 𝑐, 𝑑, … 

---
##### Minterms
Minterm is the product of various different literals in which each literal occurs exactly once. The output result of the minterm functions is 1. It is represented by m. To represent a function, we perform a sum of minterms also called the Sum Of Products (SOP).

##### Maxterm
Maxterm is the sum of various different literals in which each literal occurs exactly once. The output result of the maxterm functions is 0. It is represented by M. To represent a function, we perform product of maxterms also called Product of Sum (POS).

Minterms and maxterms are fundamental concepts used to represent and simplify Boolean functions, as they provide a systematic way to express logical expressions.

##### When to use SOPs or POSs
- SOP expressions are used when minimizing expressions for functions with mainly 1s
- POS expressions are used when optimizing functions with mainly 0s

---

### Implicants
An mplicant is a product/minterm term in Sum of Products (SOP) or maxterm in a Product of Sums (POS) of a Boolean function.

##### Prime Implicants
A prime implicant is an implicant that cannot be further reduced or combined with other implicants while still covering all the minterms (input combinations) for which the Boolean function is true. Prime implicants are important in the process of logical minimization.

##### Essential Prime Implicants
Essential Prime implicants When a Prime Implicant (PI) contains at least one complete conjunction (a '1' field) which is not part of another PI, then this PI is called an "Essential (or Core) Prime Implicant