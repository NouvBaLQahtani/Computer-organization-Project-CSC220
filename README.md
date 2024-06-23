# 8-bit Function Unit
This project is part of the Computer organization course under my bachelor's degree in software engineerin

The aim of this project is to design an 8-bit Function Unit that combines an Arithmetic Logic Unit (ALU) and a Shifter. The unit can perform the following operations:

## Table of Operations

| S3 | S2 | S1 | S0 | Operation |
| --- | --- | --- | --- | --- |
| 0 | 0 | 0 | 0 | `G = X + Y` |
| 0 | 0 | 0 | 1 | `G = X + Y + 1` |
| 0 | 0 | 1 | 0 | `G = X + Y'` |
| 0 | 0 | 1 | 1 | `G = X - Y` |
| 0 | 1 | 0 | 0 | `G = 2X` |
| 0 | 1 | 0 | 1 | `G = 2X + 1` |
| 0 | 1 | 1 | 0 | `G = X` |
| 0 | 1 | 1 | 1 | `G = X + 1` |
| 1 | 0 | 0 | 0 | `G = X AND Y'` |
| 1 | 0 | 0 | 1 | `G = X OR Y'` |
| 1 | 0 | 1 | 0 | `G = X XOR Y` |
| 1 | 0 | 1 | 1 | `G = X'` |
| 1 | 1 | 0 | 0 | `G = Y` |
| 1 | 1 | 0 | 1 | `G = Switch Tail Right Y` |
| 1 | 1 | 1 | 0 | `G = Arithmetic Shift Right Y` |
| 1 | 1 | 1 | 1 | `G = Logical Shift Left Y` |

## Implementation
The implementation of the 8-bit Function Unit is done using VHDL (VHSIC Hardware Description Language). The design includes the following components:

1. Arithmetic Logic Unit (ALU)
2. Shifter
3. Control Unit

The ALU performs the arithmetic and logical operations, while the Shifter handles the shift operations. The Control Unit manages the selection of the operations based on the input selection codes.

<img width="743" alt="Screenshot 2024-06-23 at 4 03 10 AM" src="https://github.com/NouvBaLQahtani/Computer-organization-Project-CSC220/assets/106460665/cbcc85fe-76a0-4f3e-86db-d755c83f032b">
## Testing
The designed Function Unit has been thoroughly tested with various input combinations, and the results have been verified against the expected outputs. The test cases cover all the operations listed in the table above.


## Conclusion
The 8-bit Function Unit combines the capabilities of an ALU and a Shifter, allowing for a wide range of arithmetic and logical operations to be performed on 8-bit inputs. The design is modular and can be easily integrated into larger digital systems.

## Contact

If you have any questions, feedback, or inquiries regarding this project, please feel free to reach out to me through my Email: NouvAlqahtani@gmail.com .
