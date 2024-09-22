# **AT89C51 Up Down Counter on 7-Segment Display (Assembly + Proteus)**

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802195-3d1d0b39-7d0f-4a25-88e8-6e8e4f05cb55.png" alt="AT89C51 UP DN COUNTER 7 Segment" width="70%">
</p>

---

## 📖 **Overview**

This repository contains a **simple Up Down Counter** project using the **AT89C51 Microcontroller** from the **8051 MCU series**, interfaced with a **Seven-Segment Display (SSD)** and controlled using **Push Buttons**. The project utilizes **Assembly programming**, and the simulation is built using **Proteus** (Version 8.9).

Both the **Assembly Code**, **Hex Code**, and the **Proteus simulation circuit** are included in this repository. The design has been **tested on real hardware** and has shown no issues.

<br/>

## ⚙️ **Features**

- **Up-Down Counter** with real-time visualization on a **7-segment display**.
- **Push buttons** for incrementing and decrementing the counter.
- Designed and simulated in **Proteus** and works seamlessly on **real hardware**.
- Uses **Assembly Language** for 8051 microcontroller programming.
  
<br/>

## 🛠️ **Hardware & Circuit Information**

In the real hardware implementation, current-limiting resistors are required for the **LEDs inside the Seven-Segment Display**. The **common cathode pin** of the display needs an external **current driver circuit**, which is managed by a **transistor** in this design. 

Below is a simplified diagram of the **7-segment display** pinout and internal circuit that explains the data pattern for the **common cathode display** type.

<br/>

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802987-13da40f2-8b33-4ebd-ad10-d2c8eb3dfa45.png" alt="7 Segment Display (Common Cathode)" width="70%">
</p>

<br/>

## 🧰 **Included Files**

- **Assembly Code** – Written for the **AT89C51** microcontroller.
- **HEX File** – Pre-compiled for uploading directly to the microcontroller.
- **Proteus Simulation Circuit** – Designed for version 8.9 of Proteus Design Suite.

<br/>

## 🖥️ **Installation & Usage**

1. **Clone this repository**:

   ```bash
   git clone https://github.com/yourusername/AT89C51_Up_Down_Counter_7_Segment_Assembly_Proteus.git
   ```

2. **Assembly Code**: Open and compile the assembly code using **MIDE-51** or any 8051 compatible IDE.

3. **Simulate in Proteus**: Use **Proteus 8.9 or higher** to run the provided simulation file and visualize the up/down counter functionality.

4. **Program the Microcontroller**: Upload the **hex file** to your AT89C51 development board using **avrdudes** or a similar programmer.

<br/>

## 🔗 **Additional Information**

The **7-segment display** used in this project is a **common cathode** type. The **push buttons** control the count, and a **transistor driver circuit** is used to manage the current required by the display. For more details about interfacing, refer to the circuit diagram provided in the repository.

---

Feel free to explore the project and contribute if you have ideas for improvement!

## 📧 **Contact**

For any inquiries or suggestions, feel free to reach out at [mostofa.melab@gmail.com](mailto:mostofa.melab@gmail.com).

---
