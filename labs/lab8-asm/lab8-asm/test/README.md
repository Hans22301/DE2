# Lab 8: Jan Mucha

### Instruction set

1. Complete the conversion table with selected instructions:

   | **Instruction** | **Binary opcode** | **Hex opcode** | **Compiler Hex opcode** |
   | :-- | :-: | :-: | :-: |
   | `add r24, r0` | 0000	1101	1000	0000 |  |  |
   | `com r26` | 1001	0101	1010	0000 |  |  |
   | `eor r26, r27` | 0010	0111	1010    1011 |  |  |
   | `mul r22, r20` | 1001	111d	0110	rrrr |  |  |
   | `ret` | `1001_0101_0000_1000` | `95 08` |  |

### 4-bit LFSR

2. Complete table with 4-bit LFSR values for different Tap positions:

   | **Tap position** | **Generated values** | **Length** |
   | :-: | :-- | :-: |
   | 4, 3 |  |  |
   | 4, 2 |  |  |
   | 4, 1 |  |  |

### Variable number of short pulses

3. Draw a flowchart of function `void burst_c(uint8_t number)` which generates a variable number of short pulses at output pin. Let the pulse width be the shortest one. The image can be drawn on a computer or by hand. Use clear descriptions of the individual steps of the algorithms.

   ![your figure]()