#  CMOS Logic Design – VLSI Project

## 📌 Project Overview

This project explores how a simple **Boolean logic expression** can be transformed into a **real CMOS circuit layout** using VLSI design principles.

The logic function implemented in this project is:

**F = AB′ + ACD′**

Starting from the Boolean equation, the design was gradually developed into a **transistor-level CMOS implementation**, followed by a **stick diagram**, and finally a **full custom layout using the Microwind tool**.

The goal of this project was to understand the **complete digital VLSI design flow** — from logic formulation to physical circuit implementation and simulation.

---

## 🎯 What This Project Covers

This project walks through several important concepts in **CMOS VLSI design**, including:

* Understanding and analysing the Boolean function
* Creating the **truth table** for verification
* Designing **Pull-Up (PMOS) and Pull-Down (NMOS) networks**
* Drawing the **transistor-level CMOS schematic**
* Creating a **stick diagram** for layout planning
* Implementing a **full-custom layout in Microwind**
* Studying **CMOS inverter characteristics**
* Measuring **timing parameters and delay**

By the end of this project, the logic function is fully implemented and verified through simulation.

---

## 🛠 Tools & Technology

* **Microwind CAD Tool** – for layout design and simulation
* **CMOS Technology**
* **λ-based VLSI design rules**

---

## ⚙️ Design Flow

The design process followed a typical **VLSI implementation workflow**:

1. Start with the Boolean function
2. Verify the logic using a **truth table**
3. Convert the logic into **CMOS Pull-Up and Pull-Down networks**
4. Draw the **transistor-level schematic**
5. Create a **stick diagram** to plan routing and layout structure
6. Implement the **physical layout using Microwind**
7. Study **CMOS inverter characteristics**
8. Simulate the circuit for different input combinations
9. Analyse **timing parameters and propagation delay**

This process helps demonstrate how **abstract digital logic becomes a physical circuit on silicon**.

---

## 📊 CMOS Inverter Characteristics

During the project, the CMOS inverter was analysed to understand its **voltage transfer characteristics**.

| Parameter               | Value   |
| ----------------------- | ------- |
| Threshold Voltage (Vth) | 0.583 V |
| VOH                     | 1.2 V   |
| VOL                     | 0 V     |
| VIH                     | 0.47 V  |
| VIL                     | 0.68 V  |

These values help determine the **noise margin and reliability** of the digital circuit.

---

## ⚡ Timing Performance

Simulation results from Microwind provided the following timing parameters:

| Parameter         | Value |
| ----------------- | ----- |
| Rise Time         | 80 ps |
| Fall Time         | 20 ps |
| Propagation Delay | 30 ps |

The difference between rise and fall time is mainly due to **different drive strengths of PMOS and NMOS transistors**.

---

## 📐 Transistor Sizing

To maintain balanced switching characteristics:

* **PMOS W/L ratio = 12.5**
* **NMOS W/L ratio = 5**

PMOS transistors are typically made **wider than NMOS transistors** because **hole mobility is lower than electron mobility**.

---

## 📏 Layout Area

Using λ-based design rules:

* λ = **0.06 µm**

Layout dimensions:

* Width = **144λ = 8.64 µm**
* Length = **86λ = 5.16 µm**

**Total Layout Area = 44.58 µm²**

The layout was optimized to reduce area while maintaining correct circuit functionality.

---


Each folder contains diagrams, layout screenshots, simulation results, and project documentation.

---

## 📚 What I Learned

This project helped me understand several important VLSI concepts:

* CMOS logic implementation
* Pull-Up and Pull-Down network design
* Stick diagram planning
* Layout design using Microwind
* CMOS inverter voltage transfer characteristics
* Noise margin concepts
* Timing analysis in digital circuits
* Full VLSI design flow from **Boolean logic to layout**

---

## 🚀 Applications

Concepts from this project are widely used in:

* Digital IC design
* CMOS standard cell design
* Low-power digital circuits
* Microprocessor and ASIC design

---

## 👨‍🎓 Author

**Ravi Patel**
B.Tech – Electronics & Communication Engineering
Institute of Technology, Nirma University

---

## 👨‍🏫 Faculty Guidance

Prof. Vijay Savani
Prof. Purvi Patel

Department of Electronics and Communication
Nirma University

---

## 📜 Note

This project was developed for **academic learning and understanding of CMOS VLSI design concepts**.
