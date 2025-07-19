# Bin Packing in MIPS

A simple MIPS Assembly program that solves the Bin Packing Problem using:

- First Fit (FF)
- Best Fit (BF)

## Features
- Menu-based interface
- Reads item sizes from a file
- Supports FF and BF algorithms
- Saves results to an output file

## How to Run
1. Open \`main.asm\` in MARS.
2. Run the program.
3. Follow the menu to load input, choose a method, and view/save results.

## Algorithms
**First Fit (FF):** Places each item in the first bin that has enough space. If no bin fits, a new bin is created.

**Best Fit (BF):** Places each item in the bin with the least remaining space that still fits the item. If no bin fits, a new bin is created.

## Input Format
A text file with item sizes (0.0 to 1.0), separated by spaces or newlines.

Example:

**Items:** 0.4 0.8 0.1 0.4 0.2 0.1

**Bin capacity:** 1.0 

###First Fit (FF)
Bin 1: [0.4, 0.1, 0.4, 0.1] 

Bin 2: [0.8, 0.2] 

###Best Fit (BF)
Bin 1: [0.4, 0.4, 0.2] 

Bin 2: [0.8, 0.1, 0.1]


