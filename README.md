**VHDL Projects – Digital Systems and FPGA**

This repository contains a collection of projects developed in **VHDL**, focused on practical learning of **digital systems, sequential logic, and embedded systems**.

The projects were implemented with the goal of reinforcing fundamental concepts used in FPGA and digital hardware development.

**Repository Structure**
Each project is organized as a compressed folder (.zip), containing:

**text**
project-name.zip
├── design.vhd        # Circuit implementation
├── testbench.vhd     # Simulation and validation
└── README.txt        # Project description

**Included Projects**

Binary Counter

* 4-bit counter (0 to 15)
* Increment on clock rising edge
* Synchronous reset
* Validation through simulation

Clock Divider

* Reduces the frequency of an input signal
* Implemented using an internal counter
* Demonstrates timing control in hardware


**Simulation**

The projects were simulated using:

* GHDL
* EDA Playground

Validation was performed through terminal output using `report`, allowing observation of signal behavior over time.

**Concepts Covered**

* Combinational and sequential logic
* Clock usage (`rising_edge`)
* Reset in digital systems
* Registers and flip-flops
* Difference between `signal` and `variable`
* Testbench and simulation
* Type conversion (`std_logic_vector`, `unsigned`, `integer`)

**Purpose**

The purpose of this repository is to:

* Reinforce VHDL knowledge
* Build a practical portfolio in embedded systems
* Demonstrate ability to model, simulate, and validate digital hardware

**Technologies Used**

* VHDL
* GHDL (simulator)
* EDA Playground

**Author**

Gabriel Ferreira
Software developer in training with a focus on embedded systems

**Notes**

These projects are educational and focused on clarity and progressive learning.
Improvements and optimizations may be applied as studies evolve.
