# AT89C51_Up_Down_Counter_7_Segment_Assembly_Proteus
A simple Up Down Counter using 8051 MCU series (AT89C51), Seven Segment Display (SSD) and Push Buttons
![AT89C51_UP_DN_COUNTER_7_Segment](https://user-images.githubusercontent.com/78910261/203802195-3d1d0b39-7d0f-4a25-88e8-6e8e4f05cb55.png)
Assembly Code, Hex Code and Proteus circuit (Version 8.9) are available. The code has been tested over real harware without any problem.

Below image will give a clear idea about the real hardware, pin out, internal circuit and the data pattern to use a common cathode type display.

Real hard wire will require resistors for limiting current through each LED inside the SSD. Common Pin is a source or sink for the sum current of all eight LEDs, so that this pin may require extra current driver circuit. in our circuit we used a transistor to do the same.
![7 Segment Display (Common Cathode)](https://user-images.githubusercontent.com/78910261/203802987-13da40f2-8b33-4ebd-ad10-d2c8eb3dfa45.png)
