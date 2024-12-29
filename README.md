# 101 Sequence Detector using Mealy and Moore FSMs

## Project Information

**Name**: Madhavi Aradhyula  
**Company**: CodTech IT Solutions  
**ID**: CT08DOW  
**Domain**: VLSI  
**Duration**: December 2024 to January 2024  
**Mentor**: Sravani Gouni  

---

## Overview  

This project focuses on implementing a **101 sequence detector** using two common types of finite state machines (FSMs): **Mealy** and **Moore**. Both implementations detect the binary sequence "101" with overlapping support, meaning the detector can reuse bits from a previous sequence for subsequent detections.  

---

## Key Objectives  

1. To implement both **Mealy** and **Moore** state machines for the same sequence detection task and highlight the differences in their behavior.  
2. To simulate and verify the designs in a Verilog environment.  
3. To optionally synthesize the designs for FPGA implementation.  

---

## Key Features  

### Mealy Machine  
- Outputs depend on both the **current state** and the **input**.  
- Typically has **fewer states** compared to Moore.  
- Faster response as the output changes with the input during the **same clock cycle**.  

### Moore Machine  
- Outputs depend only on the **current state**.  
- Easier to debug and simulate due to its **state-dependent output**.  

---

## Application  

The project demonstrates how different FSM designs can achieve the same functionality while showcasing trade-offs in terms of **state complexity** and **timing**. This is useful in applications like:  

- **Digital Signal Processing**  
- **Control Systems**  
- **Pattern Matching in Hardware**  

By comparing the Mealy and Moore designs, this project serves as a **learning experience** for FSM design and optimization in digital systems.  

 
#**Simulation Results**
**101 Sequence Detector using Melay FSM(Overlapping)**
![Screenshot (1341)](https://github.com/user-attachments/assets/f972bd27-9366-4731-8553-120a234fcc6b)

**101 Sequence Detector using Moore FSM(Overlapping)**
![Screenshot (1343)](https://github.com/user-attachments/assets/72c8885e-1ecf-42b8-820e-e351283d7d22)


