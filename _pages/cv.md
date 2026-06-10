---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/example_pdf.pdf
toc:
  sidebar: left
---

## Education

**Texas A&M University** – College Station, TX  
M.S. in Electrical Engineering (May 2028)

**University of Washington** – Seattle, WA  
B.S. in Electrical and Computer Engineering (June 2026)  
Major GPA: 3.80/4.00

**Relevant Coursework:** Intro to VLSI, Automated VLSI Design, Computer Architecture, Advanced Embedded Systems Design, Systems Programming, Design of Digital Systems, Data Structures and Algorithms, Electronics I & II, Analog Circuit Design, Applied E&M, Antennas

## Experience

**Embedded Systems Engineering Intern** – Jun. 2026 – Aug. 2026  
Delta Electronics, Taipei, Taiwan

**Firmware Engineering Intern** – Jul. 2025 – Sep. 2025  
Asia Vital Components Co., Ltd., Taipei, Taiwan

- Collaborated with a team of 8 engineers to optimize BLDC motor boards' thermal solutions in computation devices.
- Researched and analyzed FOC, 6-step commutation, and sensorless estimation algorithms for BLDC and PMSM efficiency in ODrive 0.5.6 open source codebase; built/flashed firmware on legacy STM32F4 ODrive v3.6 boards.
- Implemented CAN 2.0B stack with 500 kbps transmission, retry mechanism, and error handling via STM32 bxCAN.
- Developed Mongoose HTTP server with WebSocket for ADC/PWM/UART data on NUCLEO-H563ZI, enabling REST API for state reflection, firmware upgrades, and control of water pump components (LED, PWM, and servo).

**Embedded Systems Developer** – Oct. 2022 – Jun. 2026  
Husky Robotics, University of Washington, Seattle, United States

- Configured CAN packets at 500 kbps between 10 ODrive S1 boards and custom STM32 PCB with custom protocols.
- Utilized ODrive GUI for real-time tuning of motor control parameters and scripted automation tasks with odrivetool in Python for configuring, calibrating, and testing ODrive S1 boards during integration for robotic arm and mobility.
- Developed firmware in Infineon PSoC Creator to control BLDC motors using PWM signals, receiving real-time position, velocity, and torque commands over CAN2.0 while achieving accuracy within a 5% error margin.

**Undergraduate Researcher** – Oct. 2024 – Present  
Laboratory of Photonic Devices, University of Washington, Seattle, United States

- Designed programmable PID controller PCB in Altium Designer using STM32 for firmware, with feedback loops, voltage adders, programmable gain, and LT1028 op-amp voltage feedback for photonics and LiDAR applications.
- Modified Wishbone-compliant I2C controller IP core with multi-master arbitration using Intel NIOS II soft cores.
- Implemented UART, I2C, and SPI interfaces between TI TDC7200 Time-to-Digital Converter and DE2-115 Cyclone IV FPGA, enabling precise timing measurements for LiDAR/Photonics applications in time-of-flight sensing systems.

## Projects

**16x13 Register File Layout Design**

- Designed a 16-bit, 13-entry register file in Cadence Virtuoso with one write port and two asynchronous read ports utilizing static CMOS logic; verified schematic-level timing and functionality using HSPICE with a 40 fF loading.
- Created custom IC layout of 40 µm × 70 µm area with M1–6 routing layers, using bit-cell pitch for efficient routing.
- Performed parasitic extraction (C+CC) and post-layout simulation to evaluate PPA, achieving DRC/LVS-clean results, functional correctness at ≥ 3 GHz operation, and top 3 ranking out of 24 teams for power, performance, and area.

## Technical Skills

**Languages:** C, C++, Python, SystemVerilog, Verilog, Rust, Java, TypeScript, MATLAB, ARM/x86 Asm, Bash

**Software Tools:** STM32CubeIDE, Intel Quartus, ModelSim, Xilinx Vivado, LTSpice, Infineon PSoC Creator, Cadence Virtuoso, Altium Designer, KiCAD, ROS2, Ansys HFSS, Matlab Simulink, Git, Linux

**Hardware Tools:** Logic Analyzer, Oscilloscope, Function Generator, RF Spectrum Analyzer, Power Supply, JTAG/SWD
