# FPGA-TANG-NANO-9KThis 
FPGA Logic Gates with Button Inputs
Overview

This repository contains Verilog code for implementing basic logic gates (AND, OR, NOT, etc.), as well as the NAND gate, on an FPGA board. The logic gates are designed to take inputs from buttons on the FPGA board and provide corresponding outputs to LEDs.
Contents

    src/: This directory contains the Verilog source code for the logic gates and button input functionality.
        and_gate.v: Verilog code for an AND gate.
        or_gate.v: Verilog code for an OR gate.
        not_gate.v: Verilog code for a NOT gate.
        nand_gate.v: Verilog code for a NAND gate.
    constraints/: This directory contains constraint files specifying the pin assignments for the FPGA board.
        constraints.xdc: Xilinx Design Constraints (XDC) file specifying the pin assignments for the buttons and LEDs.
    README.md: This file provides an overview of the repository and instructions for running the code.

How to Use
    Open in FPGA Development Environment: Open the project in your FPGA development environment (e.g., Xilinx Vivado or Intel Quartus).

    Synthesize and Implement: Synthesize and implement the Verilog code on your FPGA board.

    Test the Logic Gates: Use the buttons on the FPGA board to provide inputs to the logic gates. Observe the corresponding outputs on the LEDs.

Contributing

Contributions to this repository are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
