# Adjustable-Power-Supply-PCB
Overview:

This project presents the design of an Adjustable Power Supply PCB created using KiCad. The circuit is based on the LM317 adjustable voltage regulator, which allows the output voltage to be varied by using a potentiometer.
The goal of this project is to design a simple and efficient PCB that can convert a fixed DC input voltage into a stable and adjustable DC output, suitable for electronics experiments and small lab applications.

Features:

• Adjustable output voltage using a potentiometer
• Stable voltage regulation with LM317
• Protection diodes for regulator safety
• Compact and beginner-friendly PCB layout
• Designed using KiCad PCB design software

Components Used:

 LM317 Voltage Regulator (TO-220 Package)
 Resistor R1 – 240 Ω
 Potentiometer – 10 kΩ
 Capacitor C1 – 0.1 µF
 Capacitor C2 – 10 µF
 Diodes – 1N4007 (2 units)
 Input Terminal Block
 Output Terminal Block

Working Principle:

The LM317 voltage regulator allows adjustable voltage regulation through a resistor divider network. The resistor (R1) and the potentiometer form a feedback network that sets the output voltage level.
The output voltage is given by:
Vout = 1.25 × (1 + R2 / R1)
By adjusting the potentiometer, the output voltage can be varied smoothly depending on the input supply voltage.

Applications:

• Electronics laboratory power supply
• Testing small circuits and sensors
• Educational learning in power electronics and PCB design

Files Included:

 KiCad Schematic Files
 PCB Layout Files
 Gerber Files for PCB Manufacturing
 Project Documentation
Tools Used:

KiCad (for schematic and PCB design)
