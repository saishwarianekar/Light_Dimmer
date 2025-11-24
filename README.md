#  AC Lamp Illumination Control with Precision

This project demonstrates **precise AC lamp brightness control** using microcontroller-based **phase angle control** with a TRIAC and **zero-cross detection** for smooth and stable illumination control.



##  Features
- Smooth AC lamp dimming using **phase angle control**  
- **Zero-cross based** accurate TRIAC triggering  
- Microcontroller-timed firing pulses  
- Flicker-free illumination  
- Safe AC load control for home & industrial use  



##  Hardware Components Used
- **Microcontroller** (Arduino / PIC / AVR / ARM)  
- **Zero Cross Detection (ZCD) circuit**  
- **TRIAC (BT136)**  
- **Optoisolator (MOC3021)**  
- **AC Lamp**  
- Resistors, capacitors, diodes  



##  Software Tools
- **Arduino IDE**  
- **Proteus** (for circuit simulation)  



##  Working Principle
1. Zero Cross Detector senses each AC zero-crossing  
2. Microcontroller receives ZCD interrupt pulse  
3. A delay is applied to determine the firing angle  
4. TRIAC is triggered via **MOC3021 optoisolator**  
5. Lamp brightness varies based on the firing delay  



##  Applications
- Smart home lighting automation  
- Energy-efficient light dimming  
- Stage & theatre illumination  
- Industrial AC load control  
- Ceiling / table fan speed control *(with modifications)*  


