# Digital Twin for Level Process

### Real-Time Level Control using Siemens S7-1200 PLC, TIA Portal, Factory I/O and PID Compact
<p align="center">
  <img src="docs/images/digital-twin-demo.png" width="900">
</p>

![GitHub](https://img.shields.io/badge/Project-Digital%20Twin-blue)
![PLC](https://img.shields.io/badge/PLC-Siemens%20S7--1200-green)
![Software](https://img.shields.io/badge/Software-TIA%20Portal-orange)
![Simulation](https://img.shields.io/badge/Simulation-Factory%20I%2FO-red)
![Control](https://img.shields.io/badge/Control-PID%20Compact-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project demonstrates the implementation of a **Digital Twin for a real-time level process** using **Siemens S7-1200 PLC**, **TIA Portal**, and **Factory I/O**.

A virtual industrial tank was developed in Factory I/O and synchronized with the Siemens PLC through Industrial Ethernet. The PLC executes a **PID Compact** controller to regulate the liquid level by continuously comparing the **Set Point (SP)** and **Process Variable (PV)**, thereby achieving real-time closed-loop level control.

The project demonstrates core concepts of **Industrial Automation**, **Digital Twin Technology**, **Process Control**, and **Industry 4.0**.

---

# 🎯 Objectives

- Develop a Digital Twin of a real-time level process.
- Implement PID-based closed-loop level control.
- Integrate Siemens S7-1200 PLC with Factory I/O.
- Establish Industrial Ethernet communication.
- Visualize real-time process behaviour.
- Validate Digital Twin operation using industrial automation tools.

---

# 🛠️ Hardware Used

- Siemens S7-1200 PLC
- PLC Trainer Kit
- Ethernet Communication
- Personal Computer

---

# 💻 Software Used

- Siemens TIA Portal
- Factory I/O
- Siemens PLCSIM
- PID Compact Technology Object

---

# ⚙️ Technologies

- PLC Programming
- PID Control
- Industrial Ethernet
- Digital Twin
- Process Control
- Industry 4.0

---

# 🏗️ System Architecture

```
               +-------------------------+
               |     Siemens PLC         |
               |      S7-1200            |
               +------------+------------+
                            |
                     Industrial Ethernet
                            |
                            |
               +------------v------------+
               |      Factory I/O        |
               |   Virtual Tank Process  |
               +------------+------------+
                            |
                     Level Feedback (PV)
                            |
                            |
               +------------v------------+
               |      PID Compact        |
               +------------+------------+
                            |
                     Fill / Drain Valve
```

---

# 🔄 Working Principle

1. The operator enters the desired **Set Point (SP)**.
2. Factory I/O continuously measures the **Process Variable (PV)**.
3. The Siemens PLC executes the **PID Compact** controller.
4. The controller calculates the control output.
5. Fill and discharge valves regulate the tank level.
6. Factory I/O updates the Digital Twin in real time.
7. The process repeats continuously until the desired level is maintained.

---

# ✨ Key Features

✅ Digital Twin Implementation

✅ PID-Based Closed Loop Level Control

✅ Siemens S7-1200 PLC Programming

✅ Factory I/O Virtual Process Simulation

✅ Industrial Ethernet Communication

✅ Real-Time Process Monitoring

✅ Virtual Commissioning

✅ Industry 4.0 Demonstration

# 📷 Project Screenshots

## 📸 Project Demonstration

### Digital Twin Running in Real-Time

<p align="center">
<img src="docs/images/digital-twin-demo.png" width="900">
</p>

**Figure 1:** Real-time synchronization between Siemens TIA Portal (PID Compact) and Factory I/O during closed-loop level control.

Example:

- TIA Portal PID Compact
- Factory I/O Virtual Tank
- Driver Configuration
- Communication Setup
- Digital Twin Implementation

---

## 📊 Results

✔ Successfully developed a Digital Twin for a real-time level process.

✔ Established real-time communication between Siemens S7-1200 PLC and Factory I/O.

✔ Implemented PID Compact controller for maintaining the desired tank level.

✔ Achieved stable synchronization between Set Point (SP) and Process Variable (PV).

✔ Demonstrated Industrial Automation concepts using virtual commissioning.
---

# 📸 Project Gallery

### Factory I/O Digital Twin

*(Screenshots of Factory I/O simulation will be added here.)*

### Siemens TIA Portal

*(Screenshots of PLC program and PID Compact monitoring will be added here.)*

### Communication

*(Industrial Ethernet communication screenshots will be added here.)*

# 🚀 Future Scope

- SCADA Integration
- Cloud-Based Digital Twin
- IIoT Connectivity
- AI-Based Predictive Maintenance
- Multi-Tank Process Automation
- Industrial Data Analytics

---

# 📚 References

- Siemens S7-1200 System Manual
- Siemens TIA Portal Documentation
- Factory I/O Documentation
- IEC 61131-3 Standard
- Research Papers on Digital Twin Technology

---

# 👨‍💻 Author

**Kishore Kumar A**

Final Year  
Electronics and Instrumentation Engineering  
Anna University

---

## ⭐ If you found this project useful, consider giving it a Star!
