# transformerless_pcb_project
This repository contains my first PCB design project, where I designed a transformer-less capacitive power supply using KiCad. The project includes the complete schematic, PCB layout, and 3D visualization.

🔧 Project Overview

This circuit is a simple AC to DC low-current power supply built without using a bulky transformer. Instead, it uses a capacitive dropper (X-rated capacitor) along with rectifier diodes, Zener regulation, and filtering capacitors to deliver a low-voltage DC output suitable for small loads such as sensors, indicator circuits, or low-power microcontroller modules.

The goal of this project was:

To understand transformer-less power supply design

To learn KiCad schematic capture, PCB routing, and 3D modeling

To build a compact power module for learning and experimentation

📘 Working Principle

The circuit uses a capacitive dropper method:

Capacitor C1 (X-rated) drops the AC mains voltage safely.

Resistors R1 and R2 discharge and limit surge current.

Diodes D1–D4 (1N4007) form a full-bridge rectifier.

C3 (filter capacitor) smooths the rectified DC.

Zener diode D5 regulates the voltage to a safe DC level.

LED D7 indicates power ON.

Optional filtering capacitor C2 stabilizes the output further.

⚠️ Warning: Transformer-less supplies are directly connected to AC mains.
The circuit is not isolated — dangerous to touch while powered.
Use only for learning and low-risk isolated testing.

🛠️ Features

Compact transformer-less power module

Full-bridge rectification using 1N4007 diodes

Zener-regulated DC output

LED power indicator

Low-cost and space-efficient PCB

First project designed fully in KiCad

🧩 Schematic

Includes:

Capacitive dropper input

Bridge rectifier

Zener voltage regulator

Filter capacitors

Output terminals

(Schematic image added in repo)

🖼️ PCB & 3D View

Designed using KiCad PCB Editor:

Proper track routing

Component labeling

Correct diode orientation

3D model preview for visualization and enclosure planning

(3D image added in repo)

📂 Repository Contents
/Schematic
/PCB Layout
/3D View
/Project Files (.kicad_pcb, .sch)
/README.md

🚀 Future Improvements

Add fuse for safety

Add MOV or TVS diode for surge protection

Include optocoupler isolation

Add a regulated 5V/3.3V output version

📝 Notes

This is my first PCB design, created for learning and improving my skills in:

KiCad

Power electronics

PCB design principles

Suggestions and improvements are welcome!
