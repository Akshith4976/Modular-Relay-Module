# Modular Analog Sensor Relay Module

A simple and low-cost modular relay module designed for **analog sensors**. Instead of redesigning the circuit for every application, different analog sensors can be connected to the same module to control a relay based on an adjustable threshold.

## Features

* Supports multiple **analog sensors**
* Adjustable switching threshold
* Comparator hysteresis for stable switching
* Flyback diode for transistor protection
* Easy to integrate into DIY and automation projects

## Supported Analog Sensors

This module is designed **only for analog output sensors**, such as:

* 🌡️ Analog Temperature Sensor (LM35, TMP36)
* ☀️ LDR (Light Dependent Resistor)
* 🌱 Soil Moisture Sensor (Analog Output)
* 🎚️ Potentiometer (for testing and calibration)
* 🌧️ Analog Rain Sensor
* 🌫️ Analog Gas Sensors (MQ Series)
* Any sensor that provides an analog voltage output.

> **Note:** Digital-only sensors are **not supported** without additional circuitry.

## Applications

* 💧 Automatic plant watering systems
* 💡 Automatic light control
* 🚰 Water tank or pump control
* 🌡️ Temperature-based fan or heater control
* 🌧️ Rain detection systems
* 🏠 Home automation projects
* General analog threshold switching

## Component Values

| Component | Value  |
| --------- | ------ |
| R2        | 10 kΩ  |
| R3        | 10 kΩ  |
| R4        | 1 kΩ   |
| R5        | 100 kΩ |

## Files Included

* Circuit Schematic
* PCB Design Files
* Gerber Files

## Improvements

Compared to the initial version:

* Added **100 kΩ hysteresis feedback resistor** for stable relay operation.
* Added **flyback diode** across the relay coil to protect the transistor from back EMF.

## License

This project is open source. Feel free to use, modify, and improve it for personal or educational purposes.
