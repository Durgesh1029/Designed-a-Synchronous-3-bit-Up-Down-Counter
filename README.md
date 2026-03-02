# 🔢 3-Bit Synchronous Up-Down Counter (Verilog HDL)

## 📌 Project Overview

This project implements a **3-bit Synchronous Up-Down Counter** using **JK Flip-Flops** in **Verilog HDL**.

The counter is capable of counting in both:
- 🔼 UP mode
- 🔽 DOWN mode

👉 Learn how a 3-bit synchronous up-down counter works:  
📺 https://youtu.be/ayIqhFLpM9g?si=e98Gb2GWdARjbKQP

---

## 🛠️ Key Features

- ✅ Designed a 3-bit Synchronous Up-Down Counter
- ✅ Implemented using JK Flip-Flops
- ✅ Written in Verilog HDL
- ✅ Developed a Testbench for verification
- ✅ Verified functionality using additional Combinational Logic in Python
- ✅ Successfully simulated and validated waveform output

---

## ⚙️ Functional Description

### Inputs:
- `clk` → Clock signal
- `reset` → Asynchronous reset
- `up_down` → Mode control
    - `1` → Up Count
    - `0` → Down Count

### Output:
- `Q[2:0]` → 3-bit Counter Output

---

## 🔄 Counting Sequence

### UP Mode:
000 → 001 → 010 → 011 → 100 → 101 → 110 → 111 → 000

### DOWN Mode:
000 → 111 → 110 → 101 → 100 → 011 → 010 → 001 → 000

---

## 🧠 Design Approach

- Derived JK excitation equations.
- Designed synchronous toggle logic.
- Eliminated ripple delay (all flip-flops triggered simultaneously).
- Verified design using simulation tools.
- Cross-validated logic using Python combinational modeling.

---

## 📂 Files Included

- `counter.v` → Main Verilog Design
- `testbench.v` → Testbench File
- `validation.py` → Python Logic Validation
- `waveform.png` → Simulation Output

---

## 🚀 Applications

- Digital Counters
- Frequency Dividers
- Sequential Circuit Design Practice
- FPGA/ASIC Learning Projects

---
## 👨‍💻 Author
Durgesh Dongre-
Designed and implemented as part of Digital IC Design and Verilog HDL practice.

