# Thermal Flow Sensor PHIDL Design - CMOS Compatible

## Project Overview
This project focuses on the **design, simulation, and layout development** of a **CMOS-compatible thermal flow sensor with a dual-heater structure**. Unlike traditional single-heater designs, the **dual-heater configuration** provides **more uniform heat distribution**, leading to improved **sensitivity, accuracy, and faster response times**. 

The sensor is **optimized for airflow measurement applications**, including:
- **Medical respiration monitoring**
- **HVAC airflow control**
- **Industrial gas flow sensing**

The work incorporates **PHIDL-based layout design, mask variation analysis, and microfabrication planning**, ensuring the sensor meets high-performance requirements.

---

## **Project Components**
### 1️⃣ Background and Motivation
- Based on **research from IEEE MEMS Conference 2023**, this sensor enhances **thermal performance** using a **parallel dual-heater (DH) structure**.
- **Performance metrics**:
  - Sensitivity: **403.25 mV/(m/s)/W** (compared to 83.7 mV/(m/s)/W for traditional designs)
  - Measurement range: **±40 m/s**
  - Response time: **1.8 ms at 16.7 m/s**
- Applications: **Medical devices, HVAC control, and industrial flow sensing.**

### 2️⃣ Sensor Design & PHIDL Layout
- **Micro-scale design** with dimensions:  
  - **800μm × 700μm × 525μm** (overall size)
  - **Bridge widths: 45μm** (for heater and sensor)
- PHIDL-based **mask design** includes:
  - **Mask 1** – Initial layer etching  
  - **Mask 2** – Sensor definition  
  - **Mask 3** – Final structure  

### 3️⃣ Fabrication Process
- CMOS-compatible **MEMS process flow**:
  - **Photolithography & etching**
  - **Deposition & metal patterning**
  - **Final release & packaging**

### 4️⃣ Device Variations & Test Structures
- **Multiple mask designs** to test size variations  
- **Test structures** include:
  - **Lithographic resolution patterns**
  - **Inter-layer alignment markers**
  - **Resistance pads for calibration**
