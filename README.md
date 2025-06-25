IoT Smart Plug System
Overview
This project presents the design and implementation of an IoT-enabled smart plug system for remote monitoring and control of home appliances. The smart plug integrates motion and temperature sensors, manual switches, relays, buzzer alerts, and LCD display, all managed via secure, real-time logic for enhanced safety, energy efficiency, and user convenience.

Features
Remote and manual control of appliances

Real-time monitoring via LCD display

Motion and temperature-based automation

Buzzer alerts for safety and fault conditions

Secure communication and device authentication

Energy usage optimization

Hardware Components
PIR motion sensor (HC-SR501)

Temperature sensor (e.g., LM35)

Manual push buttons (ON/Reset)

Potentiometer (for threshold adjustments)

Relays (appliance control)

Buzzer (audio alert)

LCD display (status and alerts)

Microcontroller (Arduino-compatible)

Software & Logic
Arduino code for sensor reading, relay control, and display updates

Boolean logic for safe operation:

Smart_Plug_Output = (PIR ∨ Button1 ∨ Pot) ∧ ¬Temp ∧ ¬Button2

Secure MQTT/TLS communication for cloud integration

Security
End-to-end data encryption

Secure device authentication and communication protocols

Regular firmware updates and intrusion detection

Usage
Upload the Arduino code to your microcontroller.

Connect the hardware as per the wiring diagram.

Monitor and control appliances via the LCD and manual buttons.

Receive alerts for motion, temperature, and reset events.
