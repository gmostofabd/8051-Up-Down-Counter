#  ⚙️ **8051 Up-Down Counter using Seven-Segment Display (SSD)**

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802195-3d1d0b39-7d0f-4a25-88e8-6e8e4f05cb55.png" alt="AT89C51 UP DN COUNTER 7 Segment" width="70%">
</p>

---

## 📖 **Overview**

This project demonstrates a **simple Up-Down Counter** using the **AT89C51 Microcontroller**, part of the **8051 MCU family**, with its output shown on a **Seven-Segment Display (SSD)**. The counter is operated via **push buttons** that control incrementing, decrementing, and resetting the counter value. 

The program is written in **Assembly language**, and the circuit is simulated using **Proteus** (Version 8.9). This repository includes the following essential files:

- **Assembly Code** for the AT89C51 microcontroller
- **Precompiled HEX File** for direct upload
- **Proteus Simulation Circuit**

The circuit has been tested on both simulation and real hardware to ensure proper functionality in both environments.

---

## ⚙️ **Key Features**

| Feature                      | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🔢 **Up-Down Counter**         | Real-time counting with 7-segment display                                   |
| 🎛️ **Push Button Controls**    | Buttons for incrementing, decrementing, and resetting the counter            |
| 🖥️ **Proteus Simulation**      | Ready-to-use simulation circuit (Proteus 8.9 compatible)                     |
| 💾 **Assembly Programming**    | Written entirely in **Assembly language** for the AT89C51                    |
| 🛠️ **Real Hardware Support**   | Tested successfully on physical hardware                                    |

---

## 📦 **Contents**

This repository includes:

- `AT89C51_Up_Down_Counter.asm` – Assembly source code.
- `AT89C51_Up_Down_Counter.hex` – Precompiled HEX file for direct microcontroller upload.
- `Proteus_Simulation.pdsprj` – Proteus Design Suite simulation file.
- **Screenshots** – Demonstrations from the Proteus simulation:

<p align="center">
  <img src="your-screenshot-link1" alt="Simulation Screenshot 1" width="70%">
  <img src="your-screenshot-link2" alt="Simulation Screenshot 2" width="70%">
  <img src="your-screenshot-link3" alt="Simulation Screenshot 3" width="70%">
</p>

---

## 🛠️ **Hardware & Circuit Information**

### **Required Hardware:**
- **AT89C51 Microcontroller**: The core of the project, controlling the up-down counting.
- **Seven-Segment Display (SSD)**: A common cathode display used for output.
- **Push Buttons**: To control the counter’s increment, decrement, and reset functions.
- **Transistors (e.g., NPN)**: To drive the SSD segments.
- **Resistors**: For current-limiting to protect the microcontroller and SSD.
- **Power Supply**: A 5V DC power supply.

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/203802987-13da40f2-8b33-4ebd-ad10-d2c8eb3dfa45.png" alt="7 Segment Display (Common Cathode)" width="70%">
</p>

### **Circuit Explanation**:

The **Seven-Segment Display** in this project is a **common cathode** type, meaning all cathodes are connected to ground. The microcontroller sends signals to the anode pins via **transistor drivers** to control which segments are illuminated, forming the numbers 0–9.

Each push button connects to an input pin of the microcontroller to increment, decrement, or reset the counter value. Resistors are used for current-limiting, ensuring that the microcontroller and display are protected.

---

## 🖥️ **Installation & Usage**

### **Step-by-Step Guide:**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/8051_Up_Down_Counter_SSD.git
   ```

2. **Compile the Assembly Code**:
   Open the `AT89C51_Up_Down_Counter.asm` file in **MIDE-51** (or a compatible IDE), and compile it to generate the **HEX file**.

3. **Simulate in Proteus**:
   Open the **Proteus Design Suite** and load the provided simulation file. Run the simulation to visualize the up-down counter functionality.

4. **Program the Microcontroller**:
   If working with real hardware, upload the **HEX file** to the AT89C51 microcontroller using a compatible programmer.

5. **Test the Circuit**:
   Assemble the hardware based on the provided circuit diagram, power it on, and use the push buttons to verify incrementing, decrementing, and resetting the counter.

---

## 🔗 **Additional Information**

### **Seven-Segment Display**:
A **common cathode** display uses 8 LEDs (7 segments + 1 decimal point) to display digits 0-9. The microcontroller sends a combination of HIGH/LOW signals to these LEDs to form the digits.

### **Push Button Functionality**:
- **Increment Button**: Increases the counter value by 1.
- **Decrement Button**: Decreases the counter value by 1.
- **Reset Button**: Resets the counter to 0.

Refer to the comments within the assembly code for additional insight or view the **Proteus Simulation Circuit** for an accurate representation of how the hardware works.

---

## 🤝 **Contributing**

We welcome any contributions! If you have suggestions for improvements, feel free to submit a pull request or open an issue. Whether it's bug fixes, feature enhancements, or optimization of the assembly code, your contributions are highly valued.

---

## 📧 **Contact**

For any inquiries, suggestions, or assistance, feel free to reach out via email:

[mostofa.melab@gmail.com](mailto:mostofa.melab@gmail.com)

---

<p align="center">
  <img src="your-contact-graphic.png" alt="Contact Graphic" width="50%">
</p>

If you found this project helpful, please give it a ⭐ on GitHub!
```

### Key Additions:
1. **Consistent Section Headers** for improved readability.
2. **Step-by-step instructions** for users to clone, compile, simulate, and test the project.
3. **Graphics** to enhance engagement and support understanding of the text.
4. **Contribution section** encouraging community involvement.
5. **Call to Action** for GitHub stars and email support.

Let me know if you want any further adjustments!
