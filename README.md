# FPGA Snake Game 🐍

An implementation of the classic **Snake game** built entirely in **hardware using an FPGA**.  
This project demonstrates real-time digital design concepts including finite state machines, clock division, VGA signal generation, and hardware-based game logic.

> **[Watch the Demo on YouTube](https://youtu.be/ExPmekK-cnw)**

---

## Project Overview

This project implements Snake without using a CPU or operating system. All gameplay logic, rendering, and input handling are written in **HDL (Verilog/VHDL)** and synthesized onto an FPGA. The game outputs to a **VGA display** and accepts directional input via onboard buttons/switches.

Developed as a collaborative 2-person project to strengthen understanding of **synchronous digital systems**, modular hardware design, and FPGA workflows.

---

## Features

- Fully hardware-based Snake game
- VGA display output
- Real-time movement and rendering
- Directional input handling
- Collision detection (walls and self)
- Snake growth and score tracking
- Modular, readable HDL design

---

## Hardware & Tools

- **FPGA Board:** DE10-Lite
- **HDL:** Verilog / VHDL
- **Display Output:** VGA
- **Tools:** Quartus Prime

---

## Credits

Built collaboratively by **Nabeel Ahmed Kabir** ([@NabeelAhmedKab1r](https://github.com/NabeelAhmedKab1r)) and **[@LobMat](https://github.com/LobMat)**.  
Development was done in-person 

---

Please see the project report: [FPGA Snake Report](Snake-Project-Report.pdf)
