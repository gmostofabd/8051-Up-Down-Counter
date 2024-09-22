# ⚙️ **8051 Up-Down Counter using Seven-Segment Display (SSD)**

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802195-3d1d0b39-7d0f-4a25-88e8-6e8e4f05cb55.png" alt="AT89C51 UP DN COUNTER 7 Segment" width="70%">
</p>

---

## 📖 **Overview**

This project demonstrates a **simple Up-Down Counter** using the **[AT89C51](https://www.atmel.com/products/microcontrollers/8051.aspx)** Microcontroller, part of the **[8051 MCU](https://en.wikipedia.org/wiki/Intel_MCS-51)** family. The counter output is displayed on a **Seven-Segment Display (SSD)** and controlled by external **push buttons** for incrementing, decrementing, and resetting.

The program is written in **[Assembly language](https://en.wikipedia.org/wiki/Assembly_language)**, and the circuit is simulated using **[Proteus](https://www.labcenter.com/)** (Version 8.9). This repository includes:
- **[Assembly Code](https://en.wikipedia.org/wiki/Assembly_language)**
- **Precompiled HEX File**
- **[Proteus Simulation Circuit](https://www.labcenter.com/)**

The project has been successfully tested on both simulation and real hardware.

---

## 🔑 **Keywords**

**[AT89C51 Microcontroller](https://www.atmel.com/products/microcontrollers/8051.aspx)** | 
**[8051](https://en.wikipedia.org/wiki/Intel_MCS-51)** | 
**[Assembly Language](https://en.wikipedia.org/wiki/Assembly_language)** | 
**[Simulation](https://www.labcenter.com/)** | 
**[Proteus](https://www.labcenter.com/)** | 
**[Microcontroller Programming](https://en.wikipedia.org/wiki/Microcontroller)**

---

## ⚙️ **Key Features**

<div align="center">

| Feature                      | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🔢 **Up-Down Counter**         | Real-time counting with a 7-segment display                                  |
| 🎛️ **Push Button Controls**    | Buttons for incrementing, decrementing, and resetting the counter            |
| 🖥️ **Proteus Simulation**      | Ready-to-use simulation circuit (Proteus 8.9 compatible)                     |
| 💾 **Assembly Programming**    | Written entirely in **Assembly language** for the AT89C51                    |
| 🛠️ **Real Hardware Support**   | Tested successfully on physical hardware                                    |

</div>

---

---

## 📦 **Contents**

<div align="center">

| File                          | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `AT89C51_Up_Down_Counter.asm`  | Assembly source code for the AT89C51 microcontroller                        |
| `AT89C51_Up_Down_Counter.hex`  | Precompiled HEX file for direct microcontroller upload                      |
| `Proteus_Simulation.pdsprj`    | Proteus Design Suite simulation file                                        |
| **Screenshots**                | Demonstrations from the Proteus simulation                                  |

</div>

---
## 🛠️ **Hardware & Circuit Information**

<div align="center">

| Hardware Component             | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| **AT89C51 Microcontroller**     | Core of the project, controlling the up-down counting                        |
| **Seven-Segment Display (SSD)** | A common cathode display for output                                          |
| **Push Buttons**                | Used for incrementing, decrementing, and resetting the counter               |
| **Transistors (e.g., NPN)**     | To drive the SSD segments                                                    |
| **Resistors**                   | For current-limiting to protect the microcontroller and SSD                  |
| **Power Supply**                | A 5V DC power supply for the microcontroller and SSD circuit                 |

</div>

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802987-13da40f2-8b33-4ebd-ad10-d2c8eb3dfa45.png" alt="7 Segment Display (Common Cathode)" width="70%">
</p>

### **Circuit Explanation**:

The **Seven-Segment Display** in this project is a **common cathode** type, meaning all cathodes are connected to ground. The microcontroller sends signals to the anode pins through **transistor drivers** to control which segments are illuminated, forming numbers 0–9.

Each push button is connected to an input pin on the microcontroller, allowing the counter value to be incremented, decremented, or reset. **Resistors** ensure proper current control to prevent damage to the microcontroller and display.

---

## 🖥️ **Installation & Usage**

### **Step-by-Step Guide:**

1. **Clone this repository**:
   ```bash
   git clone https://github.com/gmostofabd/8051_Up_Down_Counter_SSD.git
   ```

2. **Compile the Assembly Code**:
   Open the `AT89C51_Up_Down_Counter.asm` file in **MIDE-51** or a compatible IDE, and compile it to generate the **HEX file**.

3. **Simulate in Proteus**:
   Open **Proteus Design Suite**, load the provided simulation file, and run the simulation to observe the counter’s behavior.

4. **Program the Microcontroller**:
   For real hardware, upload the **HEX file** to the AT89C51 microcontroller using a programmer.

5. **Test the Circuit**:
   Assemble the hardware based on the provided circuit diagram, power it on, and test the push buttons for incrementing, decrementing, and resetting the counter.

---

## 🔗 **Additional Information**

### **Seven-Segment Display**:
The **common cathode** display has 8 LEDs (7 segments and 1 decimal point) to represent digits 0-9. The microcontroller drives the LEDs through combinations of HIGH/LOW signals.

### **Push Button Controls**:
- **Increment Button**: Increases the counter by 1.
- **Decrement Button**: Decreases the counter by 1.
- **Reset Button**: Resets the counter to 0.

For a deeper understanding of the circuit and code, explore the **Proteus simulation** and the comments in the assembly source file.

---

## 🤝 **Contributing**

We welcome contributions! Feel free to submit pull requests or open issues for any bug fixes, feature enhancements, or optimizations to the assembly code.

---

## 📧 **Contact**

For any inquiries or assistance, reach out at [mostofa.melab@gmail.com](mailto:mostofa.melab@gmail.com).

---



<p align="center">
  <img src="your-contact-graphic.png" alt="Contact Graphic" width="50%">
</p>

If you found this project helpful, give it a ⭐ on GitHub!
