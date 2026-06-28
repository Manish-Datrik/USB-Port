# USB Hub PCB Design

## About the Project

This project is a USB Hub PCB that I designed using EasyEDA. The main goal of this project was to learn how a PCB is designed from the beginning. Instead of only studying the theory, I wanted to understand how electronic circuits are actually made and converted into a real PCB.

In this project, I designed the complete schematic, placed all the components, connected them, created the PCB layout, routed all the tracks, checked for errors, and generated the files needed for PCB manufacturing.

---

## What I Used

- EasyEDA
- USB Type-C Connector
- USB Connectors
- Resistors
- Capacitors
- LED
- ESD Protection IC
- Pin Header

---

## What I Did

### 1. Started the Project

First, I created a new project in EasyEDA and opened a new schematic page.

---

### 2. Added Components

I searched and placed all the required components one by one from the EasyEDA library.

Some of the components I used are:

- USB Type-C Connector
- USB Connectors
- ESD Protection IC
- 100nF Capacitor
- 10uF Capacitor
- 330Ω Resistor
- Two 5.1kΩ Resistors
- Green LED
- Ferrite Bead
- Pin Header
- Test Points

---

### 3. Created the Schematic

After placing all the components, I connected them using wires and net labels.

I connected:

- Power (VBUS)
- Ground (GND)
- USB D+
- USB D-
- CC1
- CC2

I also connected the LED with a resistor and added capacitors for power filtering.

---

### 5. Converted to PCB

After the schematic was complete, I converted it into PCB mode using EasyEDA.

All the components appeared on the PCB editor.

---

### 6. Placed the Components

I arranged all the components properly.

I kept the USB connectors near the board edge and placed the other parts close to the connector so the routing would be easier.

---

### 7. Routed the PCB

Next, I connected all the components using PCB tracks.

I made sure the tracks were neat and avoided unnecessary crossings.

Power and signal lines were routed carefully.

---

### 8. Final Checking

After routing was completed, I checked the PCB once again for any errors.

I also made sure every component was connected correctly.

---

### 9. Generated Manufacturing Files

Finally, I generated the Gerber files and other manufacturing files that can be used to order the PCB from a PCB manufacturer.

---

## What I Learned

While working on this project, I learned:

- How to use EasyEDA
- How to draw a schematic
- How to select electronic components
- How to connect components correctly
- How to convert a schematic into a PCB
- How to place components on a PCB
- How to route PCB tracks
- How to check for design errors
- How to generate Gerber files

This project gave me practical experience in PCB design and helped me understand the complete process from circuit design to manufacturing.

---

## Project Files

```
USB-Hub-PCB
│
├── Schematic
├── PCB Layout
├── Gerber Files
├── Images
└── README.md
```

**Manish Vanjari**


Hyderabad, India

GitHub: https://github.com/Manish-Datrik
