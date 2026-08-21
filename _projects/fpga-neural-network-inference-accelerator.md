---
layout: page
title: FPGA Neural Network Inference Accelerator
description: Quantized MNIST inference on a Xilinx Zynq-7020 SoC.
importance: 1
category: hardware
---

Designed a neural-network inference accelerator in RTL Verilog for deployment on a Xilinx Zynq-7020 SoC using the PYNQ-Z2 development board.

## Highlights

- Integrated a custom multiply-accumulate datapath and control finite-state machine to perform classification directly in FPGA hardware.
- Stored all 101,000 quantized 8-bit weights in on-chip block RAM.
- Trained an MNIST classifier in PyTorch using quantization-aware training with Q1.7 fixed-point simulation.
- Achieved 97.3% test accuracy, compared with 97.9% using FP32 inference.

## Next Steps

Planned additions include real-time webcam digit recognition and an extension from the current network to a convolutional neural network.

## Tools

Verilog, Xilinx Vivado, PyTorch, PYNQ-Z2, and the Xilinx Zynq-7020 SoC.