---
layout: post
title: 16x13 Register File Layout Design
date: 2025-11-29
description: Custom IC layout design in Cadence Virtuoso with HSPICE verification achieving top 3 PPA ranking
categories: ic-design
---

## Overview

Designed a 16-bit, 13-entry register file in Cadence Virtuoso with one write port and two asynchronous read ports utilizing static CMOS logic. Custom IC layout with comprehensive parasitic extraction and post-layout simulation achieved top 3 ranking for power, performance, and area optimization.

## Design Specifications

- **Configuration:** 16-bit, 13-entry register file
- **Read Ports:** 2 asynchronous read ports
- **Write Ports:** 1 write port
- **Logic Type:** Static CMOS
- **Layout Area:** 40 µm × 70 µm
- **Routing Layers:** M1–6 metal layers

## Accomplishments

- Designed 16-bit, 13-entry register file in Cadence Virtuoso with one write port and two asynchronous read ports utilizing static CMOS logic
- Verified schematic-level timing and functionality using HSPICE with 40 fF loading conditions
- Created custom IC layout of 40 µm × 70 µm area with M1–6 routing layers using efficient bit-cell pitch for routing optimization
- Performed parasitic extraction (C+CC) and post-layout simulation to evaluate power, performance, and area (PPA)
- Achieved DRC/LVS-clean results with functional correctness verified at ≥3 GHz operation
- **Ranked in top 3 out of 24 teams** for overall power, performance, and area optimization
