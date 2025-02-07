# Segmentation Fault in Assembly Code

This repository demonstrates a common error in assembly programming: a segmentation fault caused by accessing memory outside the allocated bounds.

The `bug.asm` file contains the erroneous code, resulting in the segmentation fault. The `bugSolution.asm` file provides a corrected version.

## Bug Description
The issue lies in the memory access instruction that calculates the memory address incorrectly. This leads to accessing a memory location the program isn't allowed to use, resulting in a segmentation fault.

## How to Reproduce
Assemble and run the `bug.asm` file. It will likely crash with a segmentation fault.

## Solution
The `bugSolution.asm` file corrects the memory address calculation to access valid memory locations, preventing the segmentation fault.

## Learning Points
- Assembly programming requires careful attention to memory management and address calculations.
- Off-by-one errors and incorrect pointer arithmetic are frequent causes of segmentation faults.
- Thorough testing and debugging are critical to prevent such errors.