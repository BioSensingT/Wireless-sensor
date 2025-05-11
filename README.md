# Wireless-sensor

Project Overview
This repository provides the complete software stack for the paper "Palm-size Wireless Piezoelectric Immune-biosensing System for Rapid E. coli O157:H7 Detection ". 
It consists of two self-contained components:

Android User Interface – A native Android application, built with Android Studio, that enables remote control of the sensor hardware and real-time visualization of measurement data.

Embedded Firmware – Microcontroller firmware that initializes and manages a UART port for Bluetooth communication, bridging the sensor electronics and the Android app.

Android User Interface
The Android application offers a streamlined control panel and interactive charts for live impedance spectroscopy and frequency-shift monitoring. Key features include:

Measurement Configuration: Select excitation frequencies and voltage amplitudes with intuitive sliders and dropdowns.

Live Data Streaming: View real-time plots of impedance magnitude, phase, and resonant frequency shift.

Bluetooth Management: Scan for, pair with, and manage connections to the biosensor via BLE.

Data Logging & Export: Record measurement sessions locally and export TXT files for offline analysis.

Embedded Firmware
The firmware component runs on the sensor’s microcontroller. It:

UART Initialization: Configures baud rate, parity, and flow control to match the Bluetooth module’s specifications.

Protocol Handling: Implements a simple, robust command-response protocol for parameter updates and data transmission.

Power Efficiency: Uses low-power UART modes and sleep states to prolong battery life during idle periods.





License
MIT License
 
© 2025 University of Arkansas

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
