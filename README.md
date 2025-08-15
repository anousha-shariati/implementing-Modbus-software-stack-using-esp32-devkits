# implementing-Modbus-software-stack-using-esp32-devkits
internet of things second project spring 2024 Amirkabir University of Technology (Tehran Polytechnic)

This project involves implementing a software-based Modbus communication system to enable interaction between multiple devices designated as a Master, a Controller (Relay), and an Actuator (Temperature Sensor). Each device has specific features that facilitate packet-based communication over a serial port, allowing the Master to request data or control the state of the connected devices.

Project Overview:

The objective is to implement a Modbus communication system with the following components:

1. Master: Manages packet sending and receiving for Coil Read, Single Register Write, and Input Register Read.

2. Controller (Relay): Responds to packet requests from the Master to toggle relay states and relay the current status.

3. Actuator (Temperature Sensor): Responds to input read requests, measures the temperature via an LM75 sensor, and transmits the temperature reading back to the Master.

Prerequisites:

Hardware: 
1. ESP32 or similar microcontroller board for each device
2. LM75 temperature sensor for the Actuator
3. relay module for the Controller

Software: Arduino IDE with serial communication libraries.



