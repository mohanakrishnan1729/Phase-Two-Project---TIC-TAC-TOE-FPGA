# FPGA Implementation of a Tic Tac Toe Game Emulator

## 🎯 Project Overview
This project focuses on implementing a Tic Tac Toe game emulator using an FPGA board. The design integrates a simple user interface through switches and LEDs, and the game logic is developed using Verilog HDL. The emulator uses custom hardware logic to simulate player turns, win conditions, and draw scenarios, providing an engaging, hardware-based gaming experience.

## 🕹️ Features
- 3×3 grid game logic implemented in hardware
- Player turns tracked using internal state logic
- Win/draw detection system
- Switch-based input and LED-based output
- Real-time interaction through the ZedBoard’s I/O peripherals

## 🛠️ Tools & Technologies
- **Hardware Description Language:** Verilog HDL
- **Design & Simulation Suite:** Xilinx Vivado
- **Target Hardware:** ZedBoard (Xilinx Zynq-7000 series)

## 🧠 Methodology
The system was designed with a modular architecture:
- **Game Controller Module**: Handles player inputs, game flow, and win/draw logic.
- **Grid Encoder Module**: Maps switch inputs to grid coordinates.
- **Display Module**: Controls LED output based on game state.

The game supports two players who take alternate turns using dedicated switches. Each move updates the internal state of the board, and the game logic evaluates win or draw conditions after every move.

## 📁 Folder Structure (To Be Added)
