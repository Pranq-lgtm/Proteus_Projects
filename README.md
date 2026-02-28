# 🏗️ Digital Logic Design & Simulation Portfolio
**Focus:** Computer Architecture and Hardware Fundamentals

This repository contains a collection of digital logic simulations designed in **Proteus Design Suite**. The goal of these projects is to demonstrate a bottom-up understanding of computer hardware—starting from individual **transistors** 🔌 and building up to complex **arithmetic circuits** 🧮 like Full Adders.

---

## 🚀 Key Takeaways
* **Schematic Capture & Design:** Developed proficiency in component interfacing, netlist management, and real-time logic verification using Proteus Design Suite.
* **Hardware Fundamentals:** Gained a deep understanding of how physical components like NPN transistors implement abstract Boolean logic.
* **Arithmetic Logic:** Explored the progression from basic gates to the Arithmetic Logic Unit (ALU) building blocks.

---

## 📂 Project Showcase

### 1. Transistor-Level Logic: NAND Gate 🔌
* **Description:** A bottom-up implementation of a NAND gate using NPN transistors to demonstrate switching theory and the physical realization of Boolean logic.
* **Key Concept:** Transistors are operated in **Saturation** (ON) and **Cut-off** (OFF) states to act as digital switches.
* **Logic Expression:** $\text{Output} = \overline{A \cdot B}$

### 2. Logic Gate Verification (AND, OR, NAND, NOR) ✅
* **Description:** Comprehensive testing of standard logic gates against theoretical models using interactive Logic Probes. 
* **Methodology:** Verified each gate using a **Truth Table** to ensure output parity with Boolean algebraic expectations.

### 3. Arithmetic Circuits: Full Adder 🧮
* **Description:** A combinational circuit that performs the addition of three bits ($A$, $B$, and Carry-In). 
* **Logic Equations:** * $\text{Sum} = A \oplus B \oplus C_{in}$
    * $C_{out} = (A \cdot B) + (C_{in} \cdot (A \oplus B))$

#### Full Adder Truth Table
| $A$ | $B$ | $C_{in}$ | **Sum ($S$)** | **$C_{out}$** |
| :---: | :---: | :---: | :---: | :---: |
| 0 | 0 | 0 | **0** | **0** |
| 0 | 0 | 1 | **1** | **0** |
| 0 | 1 | 0 | **1** | **0** |
| 0 | 1 | 1 | **0** | **1** |
| 1 | 0 | 0 | **1** | **0** |
| 1 | 0 | 1 | **0** | **1** |
| 1 | 1 | 0 | **0** | **1** |
| 1 | 1 | 1 | **1** | **1** |

---

## 🛠️ How to Run & Setup
**Prerequisites:**
* Proteus Design Suite (Version 8.0 or higher recommended)

**Steps to Simulate:**
1. Clone this repository to your local machine.
2. Open Proteus and navigate to `File > Open Project`.
3. Select the desired `.pdsprj` file.
4. Click the **Run** button (bottom left corner) to start the interactive simulation.
