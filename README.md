# Arduino Smart Home Automation and Security Prototype

**CEIS101 IoT Course Project | DeVry University**  
**Project by Mildred Owens**

## Overview

A course project exploring the fundamentals of Internet of Things (IoT), electronics, programming, and automation by developing a **smart-home security and lighting prototype** using an Arduino Mega 2560 and supporting electronic components.

The original 29-page course presentation documents the progression from **Tinkercad circuit simulation** to a physical breadboard prototype with door-status indication, proximity-based alerts, and lighting controlled by a photoresistor.

This was an **educational prototype**, not a production home-security system. The presentation discusses IoT and networking concepts but does not demonstrate a deployed internet-connected home automation service.

## Demonstrated components

| Component | Function in the project |
| --- | --- |
| Arduino Mega 2560 | Microcontroller for programmed input and output |
| Breadboard, jumper wires, LEDs | Prototyping and visual status indication |
| Door sensor / switch input | Responding to door-open and door-closed states |
| Ultrasonic distance sensor | Detecting nearby objects by measured distance |
| Buzzer | Audible security alert |
| Photoresistor | Ambient-light-dependent automated LED |
| Arduino IDE | Code editing, upload and Serial Monitor output |
| Tinkercad | Early circuit planning and simulation |
| Excel | Plotting measured distance against time |

## Project evolution

**Module 2: Planning and simulation.** Used Tinkercad to arrange the microcontroller, breadboard, and circuits, with screenshots of the simulation and code.

**Module 3: Initial LED circuit.** Assembled a physical Arduino Mega 2560 circuit and recorded serial output as the LED changed state.

**Module 4: Door-status monitoring.** Added a door input, a green indicator for the closed state, and a security alert for the open state. Captured physical-circuit images, code, and Arduino Serial Monitor messages.

**Module 5: Distance monitoring.** Added an ultrasonic sensor and different indicator levels for proximity, including a red alert and buzzer at a programmed near-distance threshold. Graphed sampled distance readings over time in Excel.

**Module 6: Automated lighting.** Added a photoresistor so an LED responds to reduced light levels, with circuit photographs, code, and serial output.

## Troubleshooting and lessons

The project presentation documents component identification, identifying nonworking LEDs using a meter, replacing a faulty photoresistor after checking wiring and code, and reorganizing the circuit to address short jumper wires. See [Troubleshooting and Learning Evidence](docs/TROUBLESHOOTING.md).

## Evidence

**Original course presentation:** [CEIS 101 IoT Smart Home Automation.pdf](CEIS%20101%20IoT%20Smart%20Home%20Automation.pdf) *(upload pending)*

The presentation includes 29 pages of photographs, Tinkercad screenshots, Arduino code excerpts, Serial Monitor results, an Excel distance-time graph, and documented technical challenges.

## Skills demonstrated

Circuit simulation · Arduino IDE · introductory embedded programming · digital inputs and outputs · hardware integration · door-state monitoring · ultrasonic sensing · threshold-based alerts · photoresistor automation · serial-output inspection · basic data visualization · diagnostic troubleshooting · technical documentation

## Authorship and scope

This repository presents **Mildred Owens's original DeVry CEIS101 academic project**. Screenshots, design decisions, observations and reported results are presented as historical course evidence. The original PDF contains code excerpts and documentation, not necessarily a complete reproducible source-code repository.

The learning process helped establish foundations for later work in systems integration, cybersecurity, and the independent CIPHER project.
