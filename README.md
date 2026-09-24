# automatic-night-light-arduino
An automatic night light system using Arduino and an LDR sensor.
# Automatic Night Light using Arduino

## 📌 Project Overview

This project is an automatic night light system built using Arduino and an LDR (Light Dependent Resistor).

The system detects the surrounding light intensity and automatically controls an LED. The LED turns ON when the environment becomes dark and turns OFF when sufficient light is available.

## 🎯 Objective

To design a simple automatic lighting system that reduces unnecessary power consumption by switching the light according to the surrounding light conditions.

## 🛠️ Components Used

- Arduino Uno
- LDR / Photoresistor
- 10kΩ Resistor
- LED
- 220Ω Resistor
- Jumper Wires

## ⚙️ Working Principle

1. The LDR senses the surrounding light intensity.
2. Arduino reads the LDR value through analog pin A0.
3. When the light level falls below the defined threshold, the Arduino turns the LED ON.
4. When sufficient light is detected, the LED turns OFF.

## 🔌 Circuit

The circuit was designed and tested using Tinkercad Circuits.

![Circuit](tinkercad-circuit.png)

## 💻 Code

The Arduino source code is available in:

`automatic-night-light.ino`

## 🧪 Simulation

The project was simulated and tested using Tinkercad.

## 🚀 Future Improvements

- Automatic brightness control
- ESP32-based IoT version
- Mobile monitoring
- Solar-powered operation
- Multiple-light control

## 📚 Technologies Used

- Arduino
- Embedded C/C++
- LDR Sensor
- Tinkercad Circuits

## 👩‍💻 Author

Tanmaya
