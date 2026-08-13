# AXI4-Lite Slave with UART Interface

## Overview
Brief description of the project.

## Architecture
- AXI4-Lite Interface
- Write Controller
- Read Controller
- Register File
- UART TX
- UART RX

## Features
- AXI4-Lite Read/Write transactions
- Memory-mapped Register File
- Address decoding and alignment checking
- Access permissions
- WSTRB byte-level writes
- Error handling and read timeout
- UART TX/RX
- Multi-byte data transmission

## Project Structure
```text
src/
├── write_controller.v
├── read_controller.v
├── register_file.v
├── uart_tx.v
└── uart_rx.v

tb/
└── testbench.v

Simulation

The design was verified using ModelSim.

Implementation

The RTL design was synthesized and implemented using Xilinx Vivado.

Tools
Verilog HDL
ModelSim
Xilinx Vivado
