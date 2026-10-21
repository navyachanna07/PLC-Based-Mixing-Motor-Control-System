# PLC-Based Mixing Motor Control System

## Overview
The PLC-Based Mixing Motor Control System demonstrates industrial automation using a Mitsubishi FX5U Programmable Logic Controller (PLC). The system is programmed using Ladder Diagram (LD) logic in MELSOFT GX Works3 to control outputs according to input conditions and timer instructions.

## Objectives
- Develop PLC-based control logic using Ladder Diagram programming.
- Implement a start and holding circuit using internal relay M0.
- Control outputs Y0, Y1, and Y2 using programmed logic.
- Implement timer-based control using T0.
- Monitor and understand PLC program execution.

## Technologies Used

### 1. Mitsubishi FX5U Programmable Logic Controller (PLC)
The Mitsubishi FX5U PLC is the central control unit of the system. It processes input signals, executes the programmed instructions, manages internal devices, and updates the output states according to the ladder logic. PLC-based control provides a structured and programmable approach to industrial automation.

### 2. MELSOFT GX Works3
MELSOFT GX Works3 is the engineering software used to develop and configure the PLC program. It supports ladder-logic programming, device configuration, program verification, and monitoring. The software helps users inspect the execution of contacts, internal relays, timer instructions, and output coils.

### 3. Ladder Diagram (LD) Programming
Ladder Diagram is a graphical PLC programming language based on electrical relay-control concepts. It uses normally open and normally closed contacts, coils, branches, and other instructions to represent control conditions. In this project, ladder logic defines the relationship between input conditions, internal relay operation, timer functions, and output switching.

### 4. Internal Relay Control
Internal relays are PLC memory devices used to represent and maintain logical control states. The project uses internal relay M0 in the start and holding circuit. This arrangement demonstrates how internal control logic can maintain an operating state according to the programmed conditions.

### 5. Timer-Based Control
The timer instruction T0 introduces time-dependent behavior into the ladder program. Its operation depends on the configured timer instruction, enabling conditions, and preset value. The program screenshot displays a preset of K100; the corresponding time duration depends on the applicable PLC timer configuration.

### 6. Digital Input and Output Control
Digital input devices represented by X0, X1, X2, and X3 provide conditions for the PLC program. Output coils Y0, Y1, and Y2 are controlled according to the programmed contact and timer logic. Their physical functions depend on the actual hardware wiring and I/O assignments.

## Working Principle
The PLC processes the input conditions and executes the programmed ladder logic. Internal relay M0 provides a holding path in the start-control rung. Outputs Y0, Y1, and Y2 respond to their associated contact and timer conditions. Timer T0 introduces time-dependent control into the program. The actual physical operation depends on the PLC configuration, hardware connections, and output assignments.

## Applications
- Industrial motor control
- Mixing and blending processes
- Batch-processing automation
- Manufacturing systems
- PLC programming and automation laboratories

## Future Enhancements
- Implement a complete automatic mixing sequence.
- Integrate an HMI for operator control and monitoring.
- Add fault detection and alarm indication.
- Integrate suitable process sensors.
- Implement industrial communication and SCADA monitoring.
- Improve safety through appropriate electrical protection and interlocks.

## Software Requirements
- Mitsubishi MELSOFT GX Works3
- Compatible Mitsubishi FX5U PLC configuration

## Authors
- Navyashri C
- Drashti Shetty
- Riya Singh
- Shruti Thakur
