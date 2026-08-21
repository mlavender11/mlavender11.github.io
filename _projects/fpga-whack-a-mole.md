---
layout: page
title: FPGA-Based Whack-A-Mole Game
description: A Verilog game deployed to a Xilinx Artix-7 FPGA.
importance: 2
category: hardware
---

Created and implemented a whack-a-mole game in RTL Verilog, deployed on a Xilinx Artix-7 FPGA using the Nexys 4 DDR development board.

## Highlights

- Designed a finite-state machine to manage game timing, a multiplexed seven-segment display, and player scoring.
- Implemented 16 parallel edge-detection debouncer circuits with a Verilog generate loop for reliable switch input registration.
- Used a 16-bit linear-feedback shift register, seeded from a user-sampled free-running clock counter, to produce pseudorandom LED activation sequences.
- Simulated and verified the modular design with behavioral Verilog testbenches.

## Tools

Verilog, Xilinx Vivado, Nexys 4 DDR, and the Xilinx Artix-7 FPGA.