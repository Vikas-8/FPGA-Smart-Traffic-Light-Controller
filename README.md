# Design and Implementation of Smart Traffic Light Controller with Emergency Vehicle Detection on FPGA

## Project Overview

This project focuses on designing and implementing an intelligent traffic light controller using FPGA technology and Verilog HDL.

The system aims to improve traffic management by combining IR-based vehicle density detection with RFID-based emergency vehicle identification. It uses a Finite State Machine (FSM) to control traffic signals dynamically based on traffic conditions and emergency vehicle presence.

Unlike conventional fixed-time traffic signals, the proposed system provides adaptive traffic control and prioritizes emergency vehicles such as ambulances and fire engines.

## Key Features

- IR sensor-based traffic density detection.
- RFID-based emergency vehicle identification.
- FPGA-based traffic signal control.
- Finite State Machine (FSM) architecture.
- Adaptive green signal timing based on traffic density.
- Emergency vehicle priority handling.
- Multi-lane traffic management.

## Hardware and Technologies

- FPGA development platform.
- Verilog HDL.
- IR sensors.
- RFID reader and tags.
- Finite State Machine (FSM).
- Xilinx Vivado.

## Working Principle

### 1. Traffic Density Detection

IR sensors are used to detect vehicle presence and estimate traffic density across different lanes.

### 2. Emergency Vehicle Detection

The RFID system identifies emergency vehicles approaching the intersection.

### 3. Traffic Signal Control

The FSM processes the sensor inputs and determines the appropriate traffic signal sequence.

### 4. Emergency Vehicle Prioritization

When an emergency vehicle is detected, the controller prioritizes its corresponding lane and provides a green signal for emergency passage.

### 5. Adaptive Traffic Management

When no emergency vehicle is present, the controller allocates green signal timing according to the detected traffic density.

After emergency vehicle clearance, normal traffic management resumes.

## Simulation and Results

The design was implemented using Verilog HDL and evaluated through simulation.

The project includes:

- RTL schematic of the traffic light controller.
- Simulation waveform under normal traffic conditions.
- Simulation waveform with an emergency vehicle detected in the south lane.
- Traffic control workflow illustrating the decision-making process.

## Applications

- Intelligent transportation systems.
- Smart city traffic management.
- Emergency vehicle prioritization.
- FPGA-based real-time control systems.
- Multi-lane traffic intersections.

## Future Scope

- Integration of additional traffic density sensors.
- Simultaneous emergency vehicle handling.
- V2V communication integration.
- Machine learning-based traffic prediction.
- Large-scale multi-intersection traffic management.

## Conclusion

This project demonstrates an FPGA-based intelligent traffic light controller integrating IR-based traffic density detection and RFID-based emergency vehicle prioritization. The design explores how hardware-based FSM control can improve traffic responsiveness and support efficient emergency vehicle movement.
