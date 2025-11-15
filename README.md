# 8-Bit Adder/Subtractor

## Abstract  
This project presents the design and implementation of an **8-bit Arithmetic Logic Unit ALU** using **74LS283 4-bit binary adders** and **74LS86 XOR gates**. The ALU performs **addition and subtraction** on two 8-bit binary numbers, selected through DIP switches, and displays results via LEDs. Subtraction is implemented using the **two’s complement method**, where the B input is inverted through XOR gates and a carry-in is introduced.  

This project demonstrates fundamental principles of digital arithmetic, binary operations, and hardware design using TTL logic ICs. The design was developed in **KiCad**, and the schematic captures both theoretical and practical insights into ALU construction.

---

## Features
- **8-bit Addition**: Direct binary addition of inputs A and B.  
- **8-bit Subtraction**: Implemented using two’s complement arithmetic.  
- **Operation Control**: Single select line to toggle between addition and subtraction.  
- **Inputs**: DIP switches for A and B values.  
- **Outputs**: LEDs displaying result bits.  

---

## Components Used
- **74LS283** – Two 4-bit full adders (to build 8-bit adder/subtractor).  
- **74LS86** – XOR gates (to invert B input during subtraction).  
- **DIP Switches** – User inputs for binary values.  
- **LEDs** – Result output display.  

---

## Circuit Overview
- **Addition Mode**: `Result = A + B`  
- **Subtraction Mode**: `Result = A + (~B) + 1`  

---

## Schematic & Layout  
  

- **8-bit ALU Schematic**  
<img width="1099" height="721" alt="image" src="https://github.com/user-attachments/assets/256f0179-3e47-4b49-8619-bd37e90a4314" />
 

  

---

## Truth Tables  
### Addition  
<img width="1031" height="357" alt="image" src="https://github.com/user-attachments/assets/a3454c7c-b400-4bed-ace9-416237f42087" />
 

### Subtraction  
<img width="994" height="649" alt="image" src="https://github.com/user-attachments/assets/3aa258b0-f2a2-44da-aec6-b188ce11affd" />
  

---

## References  
- Turaga & Vanama. *Design of Low Power 4-bit ALU Using Adiabatic Logic*. [Semantic Scholar](https://www.semanticscholar.org/paper/Design-of-Low-Power-4-bit-ALU-Using-Adiabatic-Logic-Turaga-Vanama/16ab11d6142791a1366e69665849188839128598?p2df)  
- [Eater.net – Computer Engineering Basics](https://eater.net/)  
- [Instructables: 8-bit ALU Project](https://www.instructables.com/8-bit-ALU-Arithmetic-Logic-Unit/)  

---

## Author  
**P Hari Ram Nikil**  
Date: *21/09/2025*  
