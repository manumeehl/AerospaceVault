*Not relevant for exam!*
Example for 1.2:

1. **Sign Bit**: Since 1.2 is positive, the sign bit is `0`.

2. **Convert to Binary**: 
   - The integer part (1) in binary is `1`.
   - The fractional part (0.2) can be converted to binary:
     - 0.2 × 2 = 0.4 → 0
     - 0.4 × 2 = 0.8 → 0
     - 0.8 × 2 = 1.6 → 1
     - 0.6 × 2 = 1.2 → 1
     - 0.2 × 2 = 0.4 → 0 (repeats)
   - Thus, 0.2 in binary is approximately `0.0011...` (repeating).

   Combining these, `1.2` in binary is approximately `1.0011...`.

3. **Normalize**: 
   - Normalize to the form `1.xxxx × 2^n`.
   - `1.0011 × 2^0`.

4. **Exponent**: 
   - The exponent is `0`. In biased representation (bias = 127 for single precision), the biased exponent is `0 + 127 = 127` (which is `01111111` in binary).

5. **Mantissa**: 
   - The mantissa (after the leading 1) is `001100...` (taking the first 23 bits).
   - Thus, mantissa = `00110011001100110011001` (truncated).

6. **Final Representation**:
   - Sign bit: `0`
   - Exponent: `01111111`
   - Mantissa: `00110011001100110011001`

Putting it all together, the IEEE 754 representation of `1.2` is:

```
0 01111111 00110011001100110011001
```

In hexadecimal, this representation is `0x3F19999A`.