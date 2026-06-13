# Hardware PCB Designs Portfolio

Welcome to my **Hardware PCB Designs** repository! 🚀

This repo showcases a collection of my **printed circuit board (PCB) designs**, created for various applications including motor control, embedded systems, IoT boards, and power electronics. Each project includes schematic files, PCB layouts, and supporting documentation (mostly developed with **KiCad** and **Altium**).

📍 **Repo link:** [AhmedAbo-Eita/Hardware_PCB_Designs](https://github.com/AhmedAbo-Eita/Hardware_PCB_Designs)

---

## 📁 Projects Overview

Each folder contains a standalone hardware project. Here is a summary of the available designs:

### 🔹 **BLDC_Motor_Driver** *(In Progress)*
- BLDC motor driver board design.
- Includes an Altium project.
- Focuses on gate driver and power stage for brushless DC motor control.
- **Path:** [`BLDC_Motor_Driver`](./BLDC_Motor_Driver)

### 🔹 **Mixed_Signal_Board_FEDEVEL_Course** *(Done)*
- Mixed-signal board focused on Analog Signal Acquisition and Generation.
- Features an STM32 interfacing with high-precision 14-bit ADC and 16-bit DAC.
- Designed as part of the FEDEVEL Academy course. Includes 3rd order Butterworth filters and low-noise routing.
- **Path:** [`Mixed_Signal_Board_FEDEVEL_Course`](./Mixed_Signal_Board_FEDEVEL_Course)

### 🔹 **MCU_Data_Logger** *(Done)*
- MCU-based data logging hardware.
- A system designed for capturing and storing sensor data.
- **Path:** [`MCU_Data_Logger`](./MCU_Data_Logger)

### 🔹 **STM32F103C8T6_Dev_Board** *(Done)*
- Custom development board for the **STM32F103C8T6** (ARM Cortex-M3).
- Includes power circuitry, debug interface, and full I/O breakout.
- **Path:** [`STM32F103C8T6_Dev_Board`](./STM32F103C8T6_Dev_Board)

### 🔹 **Synchrouns_Buck_Converter_48V_12V** *(Done)*
- Synchronous buck DC-DC converter.
- Converts **48 V to 12 V** with high efficiency.
- Suitable for industrial and embedded power applications.
- **Path:** [`Synchrouns_Buck_Converter_48V_12V`](./Synchrouns_Buck_Converter_48V_12V)

---

## 📌 How to Explore

1. Clone the repository:

   ```sh
   git clone https://github.com/AhmedAbo-Eita/Hardware_PCB_Designs.git
   ```

2. Navigate to the project directories to access the schematic (`.kicad_sch` / `.SchDoc`) and PCB layout (`.kicad_pcb` / `.PcbDoc`) files.

## 🛠️ Tools Used
- **KiCad** (Primary tool for most projects)
- **Altium Designer** (Used for the BLDC Motor Driver project)

---
*Feel free to explore the projects and use them as a reference for your own hardware designs!*
