# Automated Conveyor Sorting System

## Overview

This portfolio project demonstrates the design and implementation of a small industrial conveyor sorting system using **EPLAN Electric P8** and **CODESYS V3**.

The project combines electrical design, PLC I/O mapping, terminal strip design and PLC programming to simulate a conveyor with automatic product detection and reject functionality.

---

## Tools Used

* EPLAN Electric P8
* CODESYS V3.5
* Structured Text (ST)
* IEC 61131-3

---

## Project Features

### Electrical Design

* Power distribution circuit
* Three-phase motor control
* 24 VDC control power supply
* PLC input/output assignment
* Terminal strip design
* Cross-referencing
* Generated terminal reports

### PLC Programming

* Start / Stop control
* Emergency stop monitoring
* Motor overload monitoring
* Product detection
* Reject request handling
* Conveyor sorting logic
* Alarm management
* HMI visualization

---

## PLC Inputs

| Address | Signal            |
| ------- | ----------------- |
| I0.0    | Start Pushbutton  |
| I0.1    | Stop Pushbutton   |
| I0.2    | Emergency Stop    |
| I0.3    | Motor Overload OK |
| I0.4    | Product Sensor    |
| I0.5    | Reject Request    |
| I0.6    | Phase Monitor OK  |

---

## PLC Outputs

| Address | Signal            |
| ------- | ----------------- |
| Q0.0    | Motor Contactor   |
| Q0.1    | Diverter Solenoid |
| Q0.2    | Run Lamp          |
| Q0.3    | Yellow Lamp       |
| Q0.4    | Fault Lamp        |
| Q0.5    | Buzzer            |

---

## Project Documentation

### Power Distribution

![Power Distribution](Images/01_Power_Distribution.png)

### Control Circuit

![Control Circuit](Images/02_Control_Circuit.png)

### PLC I/O Assignment

![PLC I/O Assignment](Images/03_PLC_IO_Assignment.png)

### PLC Outputs

![PLC Outputs](Images/04_PLC_Outputs.png)

### PLC Visualization - Normal Operation

![PLC Visualization](Images/05_Codesys_Normal_Operation.png)

### PLC Visualization - Reject Operation

![PLC Visualization Reject](Images/06_Codesys_Reject_Operation.png)

---

## Skills Demonstrated

* Industrial Automation
* PLC Programming
* Structured Text (ST)
* Electrical Design
* Motor Control
* Terminal Design
* I/O Mapping
* Industrial Documentation
* EPLAN Electric P8
* CODESYS

---

## Author

**Ali Yaghutiniat**

Electrical & Automation Engineer

Aarhus, Denmark
