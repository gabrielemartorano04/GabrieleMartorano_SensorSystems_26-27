# 🎚️ Sensor Systems — Coursework & Projects (A.Y. 2026-2027)

This repository contains all the homework assignments, practical laboratory projects, and C firmware developed for the **Sensor Systems** course. The course focuses on bridging the gap between physical sensors and digital data processing through embedded systems.

* **University:** Politecnico di Milano — Department of Electronics, Information and Bioengineering (DEIB)
* **Professors:** Prof. Federica Villa, Ing. Arianna De Vecchi, Ing. Christian Veronesi
* **Authors:** Alessandro Carboni, Alberto Casareale, Federico Colombi, Luca Lorusso and Gabriele Martorano

---

## 📖 Course Overview

The curriculum explores analog sensor technologies and their digital integration into embedded systems, divided into two core areas:

1. **Sensors & Front-End Circuits:** Theoretical principles and circuit design for optical (photodiodes, CMOS), thermal, magnetic, piezoelectric, and proximity sensors, alongside MEMS accelerometers and microphones.
2. **Microcontrollers & Firmware:** Programming ARM Cortex-M4 cores to interface with hardware sensors. This involves low-level peripheral management, including **GPIO, PWM, ADC, SPI, I2C, and USART**.

---

## 🛠️ Hardware & Software Stack

| Category | Technology / Component |
| :--- | :--- |
| **Microcontroller (MCU)** | ST-Nucleo F401RE (ARM Cortex-M4) |
| **Expansion Board** | Custom POLIMI Sensor Expansion Board |
| **Programming Language** | Embedded C |
| **Toolchain & Setup** | STM32CubeMX (Hardware config & pin mapping) |

---

## 🔬 Laboratory Activities & Assignments

Weekly homework assignments were tackled in teams, requiring the development of a practical embedded project from bare-metal configuration to the final firmware, accompanied by a short summary report. 

The projects implemented in this repository include:

* 💡 **Light Interaction:** Analog data acquisition via Light Dependent Resistors (LDR) using the ADC.
* 👏 **Clap Detection:** Real-time LED activation via acoustic clap detection using a microphone.
* 🔘 **Interrupt Management:** Advanced Digital Input/Output (GPIO) configuration and External Interrupt (EXTI) handling.
* 📡 **Serial Communication:** Asynchronous serial data transmission and reception via the USART interface.
* 🌡️ **Smart Temperature Sensing:** Interfacing and reading environmental data from the LM75 smart temperature sensor via the **I2C** bus.
* 🚀 **Motion Tracking:** Spatial data acquisition (x, y, z axes) using a 3-axis MEMS accelerometer via digital protocols.

---

> **Note:** All implementations rely on the *Sensor Systems* reference materials and datasheets provided during the laboratory sessions.
