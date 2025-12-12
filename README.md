# 8-Bit Mini CPU Architecture Design

This repository contains the design and implementation of a custom 8-bit Central Processing Unit (CPU) developed as a final project for the **2110252 Digital Logic and Computer Design** course at Chulalongkorn University (CEDT).

## ⚙️ Architectural Specifications
The CPU is designed with an accumulator-based architecture and features the following specifications:
* **Memory System:** Uses a 12-bit Address Bus allowing for 4,096 memory addresses.
* **Data Path:** Features an 8-bit Data Path for all internal operations.
* **Registers:** Includes a Program Counter (PC), Instruction Register (IR), and an Accumulator (AC).
* **Instruction Format:** Uses an 8-bit instruction format divided into Opcode and Address/Value fields.

## 📜 Instruction Set Architecture (ISA)
The CPU supports 9 essential instructions as defined in the project requirements:
* **Memory Access:** `LOAD` (Load from memory to AC), `STORE` (Store AC to memory).
* **ALU Operations:** `ADD`, `SUB`, `AND`, `OR`.
* **Control Flow:** `JUMP` (Unconditional jump), `JZ` (Jump if AC is zero).
* **System Control:** `HALT` (Terminate execution).

## 📂 Project Structure
* **`/src`**: Contains the `.dig` circuit files for the CPU, ALU, and Control Unit.
* **`/docs`**: Technical documentation and design specifications.
    * [Project_Specifications.pdf](./Mini-CPU-Project/docs/Project_Specifications.pdf) : The official design requirements and testcases.
* **`README.md`**: Project overview and setup instructions.

## 🚀 How to Run
1. Download and install the [Digital Logic Simulator](https://github.com/hneemann/Digital).
2. Clone this repository to your local machine.
3. Open the main circuit file (e.g., `main_cpu.dig`) located in the `/src` folder using the Digital simulator.
4. Load the machine code (Hex/Binary) into the ROM/RAM component.
5. Start the simulation to observe the CPU processing instructions through the PC and Accumulator.

## 🛠 Project Deliverables
As per the course requirements, this project includes:
* **Circuit Design:** Fully functional simulation in Digital software.
* **Technical Report:** Detailed design of the Data Path and Control Unit.
* **Instruction Testing:** Validated against provided testcases to ensure logic accuracy.

---
**Course:** 2110252 Digital Logic and Computer Design  
**Department:** Computer Engineering (CEDT), Chulalongkorn University  
**Developed by:** Pattadon Plubladpho
