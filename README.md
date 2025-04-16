# Noise-Activated Street Lighting System

This repository contains the design and simulation files for a **Noise-Activated Street Lighting System**, developed as part of the **Analog Circuits course project (April 2025)**.

## 🧠 Project Overview

The system is designed to automatically turn ON a streetlight in response to loud sounds (such as a vehicle horn or emergency siren), and then turn it OFF after a short delay. This approach improves **energy efficiency** and enhances **road safety**, especially in areas like tunnels, accident-prone zones, and low-visibility environments.

## 🎯 Objective

To build an analog circuit that detects high sound levels using a microphone, amplifies the signal, and uses it to trigger a relay that powers a streetlight.

## ⚙️ Components Used

- **Condenser Microphone** – Captures ambient sound  
- **BC107 NPN Transistors** – For signal amplification  
- **Resistors** – 1kΩ, 10kΩ, 100kΩ, etc.  
- **Capacitors** – 10µF, 100µF, etc.  
- **Diodes** – 1N4007 for protection and rectification  
- **Relay Module (5V/12V SPDT)** – Controls the streetlight  
- **LED** – Represents the streetlight  
- **Power Supply** – 9V to 12V DC  
- **Breadboard/PCB and jumper wires**

## 🛠️ Working Principle

1. **Sound Detection:**  
   A microphone captures surrounding noise and generates a small signal.

2. **Amplification:**  
   The signal is amplified using a transistor-based amplifier.

3. **Switching Action:**  
   The amplified signal activates a relay circuit, turning ON the LED (streetlight).

4. **Timed Shutoff:**  
   The light remains ON for a brief time (determined by RC discharge), then shuts OFF automatically.

## 🧪 Simulation Tools

- **Proteus** – For circuit simulation  
- **LTspice** – For waveform analysis and analog behavior verification

## 📌 Applications

- Smart city infrastructure
- Tunnel and highway lighting
- Emergency response lighting
- Parking lots and industrial zones

## 🧑‍🎓 Academic Info

**Course**: Analog Circuits  
**Semester**: 4th  
**Department**: Electronics and Communication Engineering  
**Institution**: Model Engineering College
**Date**: April 2025

---

> **Note**: This is a purely analog circuit implementation — no microcontroller or programming was used.

## 📬 Contact

For queries or suggestions, feel free to reach out via email (gautham.p.nair05@gmail.com) or raise an issue in this repository.

---

