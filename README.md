# verilog-projects-
Here are my Projects based on verilog 
# Digital Thermometer Using Verilog 🌡️

Welcome to the **Digital Thermometer** project! This repository showcases a hardware-based design of a digital thermometer implemented using **Verilog HDL**, designed to measure and display temperature in real-time. It is a simple yet practical project that demonstrates interfacing with sensors, data conversion, and visualization on hardware.

---

## Features ✨
- **Real-Time Temperature Measurement**: Converts the analog signal from a temperature sensor (ADC value) into Celsius.
- **7-Segment Display**: Displays the temperature on a 7-segment display, refreshing dynamically with updated readings.
- **Overheat Alert System**: Triggers an alert signal if the temperature exceeds 50°C.

---

## Project Overview 📜

This digital thermometer simulates the behavior of a hardware thermometer using **Verilog**. The project can be implemented on an FPGA for real-world applications. Here's a breakdown of the system:

1. **Temperature Sensor Simulation**: 
   - ADC data (10-bit) represents the analog signal from the sensor.
   - Sensor follows a linear response (10mV per °C).

2. **Temperature Conversion**:
   - Converts the ADC value to temperature in Celsius using the formula:  
     \[
     \text{Temperature (°C)} = \frac{\text{ADC Value} \times 100}{1023}
     \]

3. **7-Segment Display**:
   - Displays the temperature as a 2-digit value.
   - Includes Verilog logic to encode and drive the 7-segment display.

4. **Alert System**:
   - A high-temperature warning signal is triggered when the temperature exceeds 50°C.

---
