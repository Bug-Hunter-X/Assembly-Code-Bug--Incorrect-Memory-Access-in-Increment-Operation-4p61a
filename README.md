# Assembly Code Bug: Incorrect Memory Access in Increment Operation

This repository demonstrates a common bug in assembly code: incorrect memory access during an increment operation.

The `bug.asm` file contains the erroneous code. The `bugSolution.asm` file provides the corrected version.

## Bug Description
The buggy code attempts to increment a value at a memory location. However, it reads from the wrong memory location, leading to potential data corruption or unexpected behavior.

## Bug Solution
The solution corrects the memory access to read and write from the intended memory location.