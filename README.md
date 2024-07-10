## Introduction
The FIFO module is designed to handle asynchronous data communication between different parts of a digital system. It supports parameterized data width and depth, allowing for customization based on specific requirements.

## Features
- Parameterized data width and depth
- Full and empty flags for status indication
- Supports simultaneous push and pop operations
- Synchronous design with clock and reset signals

## Parameters
- `DATA_W`: Width of the data in bits (default: 8)
- `DEPTH`: Depth of the FIFO (default: 4)

## Ports
- `clk` (input): Clock signal
- `reset` (input): Reset signal (active high)
- `push_i` (input): Push enable signal
- `push_data_i` (input): Data to be pushed into the FIFO
- `pop_i` (input): Pop enable signal
- `pop_data_o` (output): Data popped from the FIFO
- `full_o` (output): Full flag
- `empty_o` (output): Empty flag

## Conclusion
This project demonstrates the implementation of a parameterized FIFO in Verilog. The module supports configurable data width and depth, making it a flexible solution for various digital system designs. The provided testbench and simulation instructions enable easy verification of the FIFO's functionality.