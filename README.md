PLC Traffic Light Controller - Engineering Project

This repository contains the complete engineering report, ladder logic draft, and final PLC program for a 4-way intersection traffic light controller.

**The full engineering report for this project is available in the repo (`Control Engineering Proyect (1).pdf`) .**


1. Project Analysis & State Design

The project began with an analysis of a real-world intersection in Pécs, Hungary (Szabadság u. & József Attila u.). All 18 traffic and pedestrian lights were identified

Due to the intersection's symmetry, the problem was simplified into 6 primary logic groups. A complete 18 state table was then developed to manage the timing and logic for the entire intersection.

<img width="794" height="770" alt="image" src="https://github.com/user-attachments/assets/3c0579ac-38d9-48fb-8910-07acc42fc3b8" />


2. I/O Mapping & Logic Drafting

The logical states (C0-C17) were then mapped to the physical PLC outputs (Y0-Y15).

As a first step before programming, the initial ladder logic was drafted by hand to translate the state table into control rungs. This draft (Page 6 of the report) served as the foundation for the digital program .

<img width="541" height="806" alt="image" src="https://github.com/user-attachments/assets/71f39c88-ba90-4a53-84e7-70a575e379cb" />

 
3. Final Implementation (Do-more Designer)

The hand-drawn logic was implemented and optimized in the Do-more Designer software. The program includes both a "Normal Mode" (`X0`) and a "Maintenance / Night Mode" (`X1`).

<img width="1891" height="770" alt="image" src="https://github.com/user-attachments/assets/e8e375d6-9ed7-47f1-acdb-7e846dfcb1a8" />
<img width="1892" height="780" alt="image" src="https://github.com/user-attachments/assets/dc33ba32-8c32-4563-8fed-4957480c411d" />



## 4. HMI Simulation

The program was verified using the Do-more Simulator to ensure all states and timings were correct and safe.

![Simulation](https://github.com/user-attachments/assets/fefe1cb3-8057-463b-8804-361465fe3cc5)
