# Electronic-Heartbeat-Reader

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Components Used](#components-used)
- [System Description](#system-description)
- [Circuit Diagram & Explanation](#circuit-diagram--explanation)
- [Results](#results)
- [Cost Estimation](#cost-estimation)
- [Conclusion](#conclusion)
- [Team Members](#team-members)

---

## Overview
The **Electronic Heartbeat Reader** is a portable and low-cost device designed to detect and display human heartbeats. It uses a microphone with a stethoscope to capture the heart's vibrations and processes the signal using amplification and filtering stages. The processed heartbeat signal is then visualized on a 0.96-inch OLED display.

---

## Features
- Detects real-time heartbeats
- Portable and easy to build
- Visualizes heartbeat waveform or BPM
- Useful for medical monitoring, fitness tracking, and educational purposes

---

## Components Used
| Component                | Description                          |
|--------------------------|--------------------------------------|
| IC LM741 Op-Amp          | Signal amplification & filtering     |
| Capacitors & Resistors   | Signal control and filtering         |
| OLED Display (0.96 inch) | Shows BPM and waveform               |
| Microphone Condenser     | Captures heart vibrations            |
| Arduino UNO              | Controls signal processing & display |
| 9V Battery               | Power supply                         |
| IC Holder, Veroboard     | Circuit building                     |
| Stethoscope              | Transmits heartbeat to microphone    |

---

## System Description
The system works in three stages:
1. **Signal Capture** – Heartbeat is captured via stethoscope connected to a condenser microphone.
2. **Signal Processing** – The signal is amplified and filtered using op-amp-based amplifier and low-pass filter circuits.
3. **Display Output** – The final signal is processed and displayed as a waveform or BPM value on the OLED screen.

---

## Circuit Diagram & Explanation
The circuit includes:
- **Amplifier 1:** Boosts weak microphone signals  
- **Low Pass Filter:** Removes high-frequency noise  
- **Amplifier 2:** Further amplifies the filtered signal  
- **Display:** Shows BPM or waveform

<p align="center">
<img src="https://github.com/user-attachments/assets/911c4852-e10f-4d94-b466-82373629e006", width="620">
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/b2213924-d896-4be7-b2c9-2ffc39b2b9ae", width="620">
</p>

<p align="center">
    <strong>Fig: Hardware Demonstration in Vero Board </strong>
</p>

**Signal Flow:**  
`Microphone → Amplifier → LPF → Amplifier → OLED Display`

---

## Results
- **Standard BPM (Medical Report):** 60–80 BPM  
- **Measured BPM (Project Output):** 60–70 BPM  

The OLED successfully displayed the heartbeat, proving effective signal detection and visualization.

---

## Cost Estimation
**Estimated Cost:** ~1500 BDT

Includes:
- Electrical components
- Labor & assembly
- Miscellaneous expenses

The design is affordable, easy to replicate, and ideal for personal or educational use.

---

## Conclusion
This project demonstrates a functional heartbeat reader built using fundamental electronics concepts. It's cost-effective, simple to assemble, and can be enhanced further (e.g., wireless features or data storage). It provides an excellent learning platform for biomedical electronics.

---

## Team Members
**Group Name:** Amplifier  
- Md. Nayon Khan – 021 221 045  
- Suvom Karmakar – 021 221 027  
- Md. Ratul Hassan – 021 221 036  
- Shakil Ahmed – 021 221 040  

**Submitted to:**  
Dr. Sadid Muneer, Ph.D  
Assistant Professor  
Department of Electrical and Electronic Engineering  
United International University

