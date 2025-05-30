# Implementation of Dual-Output Logic Gates using Complementary Pass Transistor Logic (CPL) in LTSpice

## Project Overview
This repository contains the implementation and simulation of dual-output logic gates (AND/NAND, OR/NOR, XOR/XNOR) using **Complementary Pass Transistor Logic (CPL)** in LTSpice.  
Developed as part of the VLSI Design course at **Delhi Technological University (formerly DCE)**, this project highlights the advantages of CPL over conventional CMOS logic, particularly in terms of reduced transistor count and improved power efficiency.

## Features
- **Dual-output logic implementation** for three fundamental gate pairs
- Achieves up to **62.5% transistor count reduction** compared to standard CMOS designs
- **Full-swing operation** confirmed via transient analysis
- **Propagation delay measurements** using LTSpice `.measure` commands
- **Complete LTSpice schematics and simulation files** included

## Schematic Implementations

### AND/NAND Gate
![AND/NAND Schematic](https://github.com/user-attachments/assets/0460df42-d880-4c7d-bcfa-a3261483be6d)  
**Boolean expressions:**  
- `F = A · B`  
- `F' = ¬(A · B)`

---

### OR/NOR Gate
![OR/NOR Schematic](https://github.com/user-attachments/assets/cf7a35db-1457-454b-b095-3d7dacdac612)  
**Boolean expressions:**  
- `F = A + B`  
- `F' = ¬(A + B)`

---

### XOR/XNOR Gate
![XOR/XNOR Schematic](https://github.com/user-attachments/assets/b6143e49-f0b6-462d-93b2-9a41a13b0480)  
**Boolean expressions:**  
- `F = A ⊕ B`  
- `F' = ¬(A ⊕ B)`

---

## Key Findings
- Achieved **40% reduction** in propagation delay compared to conventional CMOS logic
- Maintained **full voltage swing (0V–5V)** across all gate outputs
- Observed **32% lower power consumption** relative to standard CMOS implementations
- Verified correct functionality via **exhaustive truth table testing**

## References
1. Rabaey, J. M., et al. (2003). *Digital Integrated Circuits: A Design Perspective*  
2. Weste, N. H. E., & Harris, D. (2010). *CMOS VLSI Design*  
3. Zimmermann, R., & Fichtner, W. (1997). *IEEE Journal of Solid-State Circuits*, 32(7)

## Acknowledgments
- **Prof. Neeta Pandey**, VLSI Design Faculty, DTU  
- **Delhi Technological University VLSI Lab**  
- **Analog Devices**, for providing LTSpice simulation tools
