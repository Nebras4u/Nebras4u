# 👋 Hello, I'm Nebras Damsarkho

**Mechatronics Engineer | Industrial Automation Specialist | Digital Twin Developer**

📍 Damascus, Syria
✉️ nebras4u@gmail.com

---

## 🎯 About Me

**Mechatronics engineer** with over **7 years of experience** in industrial automation, high-power electrical systems, and maintenance management. I build **digital twins of industrial robots** that connect Siemens PLCs to NVIDIA Isaac Sim, with a focus on **PLC-driven simulation** and **virtual commissioning**.

Currently maintaining **[isaac-plc-digital-twin](https://github.com/Nebras4u/isaac-plc-digital-twin)**, an open-source, vendor-neutral platform for PLC ↔ ROS 2 ↔ Isaac Sim integration (simulation and research use).

---

## 🚀 Featured Projects

### 1. Isaac Digital Twin: Vendor-Neutral Platform

> **Siemens S7-1500 (PLCSIM Advanced) ↔ ROS 2 ↔ NVIDIA Isaac Sim 5.1**
> A configuration-driven digital twin for the KUKA KR210 L150 L. Switch the PLC transport by editing one YAML line.

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/Nebras4u/isaac-plc-digital-twin/blob/main/LICENSE)
[![Releases](https://img.shields.io/badge/releases-GitHub-blue.svg)](https://github.com/Nebras4u/isaac-plc-digital-twin/releases)
[![Platform](https://img.shields.io/badge/platform-Linux%20%2B%20Windows-lightgrey.svg)](https://github.com/Nebras4u/isaac-plc-digital-twin)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble%20%7C%20Jazzy-blue.svg)](https://docs.ros.org/)
[![Isaac Sim](https://img.shields.io/badge/Isaac%20Sim-5.1-green.svg)](https://developer.nvidia.com/isaac-sim)

**Highlights:**
- **Vendor-neutral transport:** `tcp_json` · `opcua` · `plc_api` behind a single `PlcDriver` interface
- **Ruckig online trajectory generation:** jerk-limited, time-optimal
- **Counter-based heartbeat protocol:** does not depend on clock synchronization between machines (measured inter-machine drift: about +95.7 ppm, stable)
- **Measured results (simulation):** 0.0254° max steady-state tracking error on joint_2; 5.2 ms mean PLC read latency (16.3 ms max) after TCP-JSON optimization. Full method and latency breakdown in the repository
- **Declarative config validation:** Pydantic v2 schema with versioning and an audit hash
- **Troubleshooting log:** 39 documented issues with root cause and fix

**Tech:** Python · Siemens S7-1500 (PLCSIM Advanced v6.0) · OPC UA · TCP/JSON · ROS 2 · NVIDIA Isaac Sim 5.1 · Ruckig · KUKA KR210

**Status:** Active development, research platform. Simulation only; not a certified safety function.

---

### 2. GlassSync: Industrial Digital Twin Platform

> **Siemens S7-1500 + CoppeliaSim**: digital twin platform for robotic glass handling.

[![GlassSync](https://img.shields.io/badge/GlassSync-Digital_Twin-blue.svg)](https://github.com/Nebras4u/GlassSync)

**Highlights:**
- Real-time PLC data mirroring to 3D simulation
- MOVEIT Manual Control & What-If Simulation modes
- OPC UA communication with timestamp-free writing
- CoppeliaSim IK for accurate robot motion

**Tech:** Python · Siemens S7-1500 · OPC UA · CoppeliaSim · ZMQ · TimescaleDB · Tkinter

---

## 📺 Digital Twin Video Series

A YouTube series documenting real integration work: setup, debugging, and verification of the full control stack.

[![YouTube Playlist](https://img.shields.io/badge/YouTube-Digital_Twin_Series-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLMadf0IBbtAE)

- **Episode #1:** Offline PLC/Sim Comparison (S7-1500T + ROS 2 + Isaac Sim)
- **Episode #2:** Live PLC/ROS 2/Isaac comparison *(planned)*

---

## 🛠️ Technical Skills

| Category | Technologies |
|----------|--------------|
| **PLC & Automation** | Siemens S7-300/400/1200/1500, PCS7, TIA Portal, WinCC, DCS |
| **Robotics** | KUKA KRC2, ROS 2, NVIDIA Isaac Sim 5.1, CoppeliaSim, URDF, Kinematics |
| **Digital Twin** | Python, OPC UA, TCP/JSON, Real-Time Simulation, Virtual Commissioning |
| **IIoT** | Node.js, MQTT, TimescaleDB, Predictive Maintenance |
| **Industrial Protocols** | Profibus, Profinet, Modbus, OPC UA |
| **VFDs** | ABB, Siemens, LS, Delta |

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nebras-damsarkho)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nebras4u)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nebras4u@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLMadf0IBbtAE)

---

## 📌 Keywords

`Industrial Automation` `Siemens PLC` `S7-1500` `TIA Portal` `PCS7` `SCADA` `DCS` `VFD` `KUKA Robotics` `KR210` `ROS 2` `NVIDIA Isaac Sim` `Digital Twin` `OPC UA` `Virtual Commissioning` `Ruckig` `IIoT` `Predictive Maintenance` `Industry 4.0` `Python` `Node.js` `MQTT` `TimescaleDB` `URDF` `GlassSync`
