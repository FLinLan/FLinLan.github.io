---
layout: post
title: FPGA Taiko No Tatsujin Rhythm Game
date: 2025-11-27
description: FPGA-based rhythm game with synchronized VGA display and state machine logic
categories: fpga-projects
---

## Project Overview

Developed an FPGA-based rhythm game on the DE1-SoC platform, rendering scrolling musical notes from ROM-preloaded frames synchronized to song rhythm via VGA display. Implemented sophisticated algorithmic state machine, key synchronization with edge detection, and combinatorial collision detection for scoring on 7-segment displays.

## Technical Specifications

- **Platform:** DE1-SoC FPGA board
- **Display:** VGA output with scrolling note rendering
- **Audio Sync:** ROM-preloaded frames synchronized to song rhythm
- **Display Output:** 7-segment displays for scoring
- **HDL:** SystemVerilog/Verilog

## Key Features

- **State Machine:** Algorithmic state management for gameplay flow and note tracking
- **Key Synchronization:** Edge detection for precise timing of player inputs
- **Collision Detection:** Combinatorial logic for scoring based on hit accuracy
- **Graphics Rendering:** ROM-based note frame preloading and VGA scrolling implementation
- **Score Display:** Real-time score output on 7-segment display arrays

## Accomplishments

- Developed FPGA-based rhythm game on DE1-SoC with real-time VGA rendering
- Implemented ROM-preloaded frame scrolling synchronized to song rhythm for smooth gameplay
- Designed sophisticated state machine for comprehensive gameplay state management
- Created edge detection logic for precise key input synchronization with note timing
- Implemented combinatorial collision detection algorithm for dynamic scoring based on hit accuracy
- Successfully integrated multiple hardware components: VGA controller, ROM memory, and 7-segment display drivers
