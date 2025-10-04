# KADARIVENU_RISC-V-WEEK-2# BabySoC – Fundamentals of SoC Design

## Objective

The goal of this exercise is to build a solid understanding of System-on-Chip (SoC) fundamentals and practice functional modelling of the **BabySoC** using simulation tools such as **Icarus Verilog** and **GTKWave**.

---

## What is a System-on-Chip (SoC)?

A **System-on-Chip (SoC)** is an integrated circuit that consolidates all the essential components of a complete computer system into a single chip. Instead of having separate chips for CPU, memory, and peripherals, an SoC integrates them into one compact and power-efficient package.

SoCs are widely used in smartphones, embedded devices, IoT systems, and consumer electronics due to their optimized performance, size, and cost efficiency.

---

## Components of a Typical SoC

A standard SoC design typically includes the following building blocks:

1. **CPU (Processor Core):**

   * Executes instructions and controls the system.
   * Can be a general-purpose processor (ARM, RISC-V) or an application-specific core.

2. **Memory:**

   * Includes on-chip SRAM/DRAM and cache.
   * Stores instructions, data, and temporary results.

3. **Peripherals:**

   * Interfaces for external communication and control (UART, GPIO, timers, I2C, SPI, etc.).
   * Provide connectivity to sensors, displays, or other hardware modules.

4. **Interconnect (Bus/Fabric):**

   * The communication backbone of the SoC.
   * Connects CPU, memory, and peripherals. Examples: AMBA (AHB/AXI), Wishbone.

---

## Why BabySoC?

**BabySoC** is a simplified SoC model designed as a **learning platform**. It abstracts away the complexity of industrial SoC designs and allows beginners to focus on:

* Understanding how different blocks (CPU, memory, peripherals) interact.
* Building intuition about interconnect and data flow.
* Gaining hands-on practice in simulation before tackling full-scale SoC projects.

This makes BabySoC an excellent stepping stone for students and engineers starting their SoC design journey.

---

## Role of Functional Modelling

Before moving into **RTL design** and **physical implementation**, functional modelling plays a crucial role:

* **Early Verification:** Ensures system behavior is correct before committing to hardware.
* **Architecture Exploration:** Helps evaluate different design choices and trade-offs.
* **Faster Iteration:** Easier to debug and refine system-level functionality at this stage.
* **Foundation for RTL:** Provides a working reference model for the later hardware design process.

By simulating BabySoC with tools like **Icarus Verilog** and visualizing waveforms in **GTKWave**, we can validate the functional behavior of the system and strengthen our grasp of SoC fundamentals.

---

## Summary

* A **System-on-Chip (SoC)** integrates CPU, memory, peripherals, and interconnect into one chip.
* **BabySoC** is a simplified SoC model created for educational purposes, allowing learners to explore SoC concepts in a manageable environment.
* **Functional modelling** is a vital step before RTL and physical design, ensuring correctness, enabling rapid exploration, and laying the groundwork for real hardware design.

This exercise marks the first step in the **SoC learning journey** by bridging theory and hands-on simulation.

---
