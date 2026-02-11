📌 Overview

This project implements a Microwave Oven Control System using the PIC16F877A microcontroller. It simulates real-world microwave operations including Micro, Grill, and Convection modes with timer-based control, pause/resume functionality, and stop/reset operations.

The system is developed using Embedded C in MPLAB X IDE and tested using PICSimLab, eliminating the need for physical hardware.

🎯 Features

Micro, Grill, and Convection cooking modes

Timer-based cooking control

Pause and Resume functionality

Stop/Reset operation

LCD display for mode and timer status

Fully simulated without hardware

🛠️ Technologies Used

Microcontroller: PIC16F877A

Programming Language: Embedded C

IDE: MPLAB X IDE

Compiler: XC8

Simulation Tool: PICSimLab

⚙️ Working Principle

User selects the cooking mode.

Cooking time is set using timer controls.

On start, the selected mode activates and countdown begins.

Pause temporarily halts the timer.

Resume continues operation.

Stop resets the system to idle state.

A structured state-machine logic ensures smooth transitions between idle, running, paused, and stopped states.

🧠 Learning Outcomes

Embedded C programming for real-time systems

Timer configuration in PIC16F877A

LCD interfacing

State-machine based system design

Simulation-based testing

🚀 Future Improvements

Buzzer alert on completion

EEPROM-based memory storage

Temperature sensor integration

Hardware prototype implementation
