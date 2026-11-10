# 4-Bit Synchronous Down Counter

## Overview
Designed and simulated a 4-bit synchronous down-counter using Verilog HDL.

## Features
- 4-bit binary down-counter
- Negative-edge triggered operation
- Synchronous active-high reset
- Counter wraps from 0000 to 1111
- Testbench-based functional verification

## Counting Sequence

```text
1111 → 1110 → 1101 → 1100
1011 → 1010 → 1001 → 1000
0111 → 0110 → 0101 → 0100
0011 → 0010 → 0001 → 0000
```

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave
- VS Code

## Concepts Learned
- Sequential logic
- Clock edge triggering
- Synchronous reset
- Nonblocking assignments
- Binary decrement and modulo-16 arithmetic
