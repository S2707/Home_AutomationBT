# Task-2 Home_Automation using Bluthooth
# COMPANY: CODETECH IT SOLUTIONS
# NAME: Shreya Patwadkar
# INTERN ID: CT08HWU
# DOMAIN: Embedded Systems
# BATCH DURATION: December 30th, 2024 to January 30th, 2025
# MENTOR NAME: Vaishali
# DESCRIPTION 
This simulation represents a microcontroller-based control system utilizing an Arduino Uno R3, a Bluetooth module (HC-05), and relay control circuits. The purpose of the circuit is to allow wireless control of various electrical devices via a Bluetooth connection.
# Key Components:
1. Arduino Uno R3
2. HC-05 Bluetooth Module
3. Relays
4. Transistors 2N222
5. Diodes(1N4007)
6. Resistors
7. Load Device
# Operation:
1. The HC-05 Bluetooth module receives commands from a paired device and transmits them to the Arduino via serial communication.
2. Based on the received commands, the Arduino sets its digital output pins (8, 9, and 10) HIGH or LOW to control the transistors.
3. When a digital pin goes HIGH, the corresponding transistor switches on, energizing the associated relay coil.
4. The relay contacts close, completing the circuit for the connected load device (e.g., light bulb, buzzer, or LED), which then operates.
   
# Circuit Digram Of the Task
![Image](https://github.com/user-attachments/assets/182b2cfc-fe3f-4397-b408-2efbe8a51b77)

# OUTPUT
https://github.com/user-attachments/assets/d665d161-9135-4a36-83fa-2b0726f2fd6f
