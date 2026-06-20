---
layout: post
title: 64-bit Five-Stage Pipelined ARM CPU
date: 2025-12-01
description: SystemVerilog implementation of a 64-bit pipelined processor with LEGv8 instruction set
categories: hardware-design
---

## Overview

Designed and implemented a 64-bit pipelined processor with a five-stage architecture using SystemVerilog, supporting the LEGv8 instruction set with complete register file, ALU, forwarding unit, and memory operations.

## Key Features

- **Architecture:** Five-stage pipeline (IF, ID, EX, MEM, WB)
- **Language:** SystemVerilog
- **Instruction Set:** LEGv8
- **Components:** Register file, ALU, forwarding unit, memory operations
- **Hazard Management:** Data forwarding, hazard detection, and branch prediction logic

## Accomplishments

- Designed and implemented a complete 64-bit pipelined processor with LEGv8 instruction set support
- Added data forwarding, hazard detection, and branch prediction logic to resolve dependencies and minimize hazards
- Validated functionality through SystemVerilog testbenches and ModelSim simulation for comprehensive debugging and verification
- Achieved robust dependency resolution and hazard minimization through advanced pipeline control techniques
