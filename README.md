# Traffic Light Controller using Verilog HDL

## Project Overview
This project implements a Traffic Light Controller using Verilog HDL. The design is based on a Finite State Machine (FSM) that controls the sequence of traffic signals: RED, GREEN, and YELLOW. The controller automatically transitions between states according to predefined timing conditions to ensure safe and efficient traffic flow.

## Features
- FSM-based traffic signal control
- Sequential transition between RED, GREEN, and YELLOW lights
- Synchronous design using clock and reset signals
- Behavioral simulation and verification using Xilinx Vivado
- Modular and scalable RTL design

## Tools Used
- Verilog HDL
- Xilinx Vivado
- RTL Simulation

## Project Structure
Traffic_Light_Controller
├── traffic_light_controller.v
├── traffic_light_tb.v
├── README.md

## Simulation
The design was verified through behavioral simulation in Vivado. The waveform confirms the correct sequence of traffic light transitions:

RED → GREEN → YELLOW → RED

## Learning Outcomes
- Finite State Machine (FSM) Design
- Sequential Circuit Design
- Verilog HDL Coding
- Testbench Development
- Waveform Analysis and Verification

## Applications
- Road Traffic Management Systems
- Smart City Infrastructure
- Automated Signal Control Systems
