# Hardware PCB Designs Portfolio

Welcome to the Hardware PCB Designs repository.

This repository showcases a collection of printed circuit board (PCB) designs created for various applications, including motor control, embedded systems, IoT devices, and power electronics. Each project includes schematic files, PCB layouts, manufacturing outputs, and supporting documentation (developed primarily with KiCad and Altium Designer).

Repository Link: [AhmedAbo-Eita/Hardware_PCB_Designs](https://github.com/AhmedAbo-Eita/Hardware_PCB_Designs)

---

## Projects Overview

Each folder contains a standalone hardware project. Here is a summary of the available designs:

### BLDC_MC_V1.0 *(Done)*
- **Description:** 60V / 30A high-performance 3-phase BLDC & PMSM motor controller (ESC) designed for robotics, e-mobility, and industrial automation.
- **Hardware Architecture:** STM32G431RBT6 (ARM Cortex-M4 @ 170 MHz) with TI DRV8353HRTAR smart gate driver and 6x Infineon BSC027N10NS5 100V OptiMOS MOSFETs.
- **Stackup & Ratings:** 8-Layer High-TG180 FR4 PCB (2 oz outer / 1 oz inner copper), 24V – 60V DC bus input, 30A continuous phase current, up to 100 kHz PWM.
- **Key Features:** Low-side 3-shunt Kelvin current sensing, active virtual ground BEMF voltage sensing, buffered Hall sensor interface, CAN / CAN-FD bus (TCAN334DR), USB Type-C, LM74700-Q1 ideal diode reverse polarity protection, and 256 Kbit SPI EEPROM.
- **Deliverables:** Complete multi-sheet schematic, fabrication Gerbers, Excellon drill files, BOM, Pick & Place files, and 3D renders.
- **Path:** [`BLDC_MC_V1.0`](./BLDC_MC_V1.0)

### BLDC_Motor_Driver *(In Progress)*
- **Description:** Brushless DC motor driver board design.
- **Tool:** Altium Designer.
- **Key Features:** Focuses on gate driver architecture and power stage layout for brushless DC motor control.
- **Path:** [`BLDC_Motor_Driver`](./BLDC_Motor_Driver)

### Four_Port_USB3.0_Hub *(In Progress)*
- **Description:** 4-Port USB 3.0 Hub design for high-speed peripheral expansion.
- **Tool:** Altium Designer.
- **Path:** [`Four_Port_USB3.0_Hub`](./Four_Port_USB3.0_Hub)

### Mixed_Signal_Board_FEDEVEL_Course *(Done)*
- **Description:** Mixed-signal board focused on analog signal acquisition and generation.
- **Key Features:** Features an STM32 interfacing with a high-precision 14-bit ADC and 16-bit DAC. Includes 3rd-order Butterworth filters and low-noise mixed-signal routing. Designed as part of the FEDEVEL Academy course.
- **Path:** [`Mixed_Signal_Board_FEDEVEL_Course`](./Mixed_Signal_Board_FEDEVEL_Course)

### MCU_Data_Logger *(Done)*
- **Description:** Microcontroller-based data logging hardware.
- **Key Features:** Designed for high-reliability sensor data capture, acquisition, and non-volatile storage.
- **Path:** [`MCU_Data_Logger`](./MCU_Data_Logger)

### STM32F103C8T6_Dev_Board *(Done)*
- **Description:** Custom development board for the STM32F103C8T6 (ARM Cortex-M3).
- **Key Features:** Integrated power regulation circuitry, SWD debug interface, and complete I/O header breakout.
- **Path:** [`STM32F103C8T6_Dev_Board`](./STM32F103C8T6_Dev_Board)

### Synchrouns_Buck_Converter_48V_12V *(Done)*
- **Description:** High-efficiency synchronous buck DC-DC converter.
- **Key Features:** Steps down 48 V to 12 V with high conversion efficiency. Suitable for industrial and embedded power applications.
- **Path:** [`Synchrouns_Buck_Converter_48V_12V`](./Synchrouns_Buck_Converter_48V_12V)

---

## How to Explore

1. Clone the repository:

   ```sh
   git clone https://github.com/AhmedAbo-Eita/Hardware_PCB_Designs.git
   ```

2. Navigate to the project directories to access the schematic (`.kicad_sch` / `.SchDoc`) and PCB layout (`.kicad_pcb` / `.PcbDoc`) files.

## Tools & Software

- **KiCad** (Used for BLDC_MC_V1.0 and embedded projects)
- **Altium Designer** (Used for multi-sheet mixed-signal and motor driver designs)

---

Feel free to explore the projects and use them as a reference for your own hardware designs.
