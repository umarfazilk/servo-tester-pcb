# Servo Tester PCB Design

A compact **Servo Motor Tester PCB** designed using **KiCad 10.0**.
This project is based on the **NE555 timer IC**, which generates a variable PWM signal to test and control standard servo motors.

The board includes a potentiometer for manual pulse width adjustment, input power connector, servo output connector, LED indicator, and a clean PCB layout with 3D visualization.

---

## Project Overview

This PCB is designed to test servo motors without using any microcontroller.
The NE555 timer is configured to generate a servo control signal, and the potentiometer allows the user to vary the output pulse width. This makes it useful for checking servo rotation, testing servo response, and basic electronics learning.

---

## Features

* NE555-based servo signal generation
* Potentiometer-controlled pulse adjustment
* Dedicated 3-pin servo output header
* Power input connector
* LED power/status indicator
* Compact PCB layout
* Through-hole component design for easy soldering
* KiCad schematic, PCB layout, and 3D model included

---

## Circuit Working

The circuit uses the **NE555 timer IC** in an astable/PWM signal generation configuration.
The timing components such as resistors, capacitor, diode, and potentiometer control the charge and discharge timing of the capacitor.

By rotating the potentiometer, the output pulse width changes.
This varying pulse signal is sent to the servo signal pin through the 3-pin output connector.

The servo connector provides:

* GND
* VCC
* SIG

The LED section is used as a power/status indication.

---

## Main Components Used

| Component          | Description                         |
| ------------------ | ----------------------------------- |
| NE555P             | Timer IC used for signal generation |
| 100K Potentiometer | Controls the servo pulse width      |
| 1N4148             | Signal diode for timing control     |
| 22nF Capacitor     | Timing capacitor                    |
| Resistors          | Timing and LED current limiting     |
| LED                | Power/status indicator              |
| 2-pin Header       | Power input                         |
| 3-pin Header       | Servo output connector              |

---

## PCB Preview

### 3D Model View 1

![3D Model 1](3d%20model%201.png)

### 3D Model View 2

![3D Model 2](3d%20model%202.png)

### PCB Layout

![PCB Layout](layout%20img.png)

### Schematic

![Schematic](schematic%20img.png)

---

## Project Files

| File                     | Description                               |
| ------------------------ | ----------------------------------------- |
| `servo tester.kicad_pro` | KiCad project file                        |
| `servo tester.kicad_sch` | Schematic file                            |
| `servo tester.kicad_pcb` | PCB layout file                           |
| `3d model 1.png`         | 3D render image                           |
| `3d model 2.png`         | 3D render image                           |
| `layout img.png`         | PCB layout image                          |
| `schematic img.png`      | Circuit schematic image                   |
| `.gitignore`             | Git ignore file for KiCad temporary files |

---

## Applications

* Servo motor testing
* PWM signal generation learning
* 555 timer practical circuit study
* Basic PCB design practice
* Electronics mini project
* Hardware prototyping and testing

---

## Tools Used

* KiCad 10.0
* PCB Editor
* Schematic Editor
* 3D Viewer

---

## Learning Outcome

Through this project, I practiced:

* NE555 timer-based circuit design
* Servo motor control signal concept
* Schematic design in KiCad
* PCB layout routing
* Component placement
* 3D PCB visualization
* GitHub project documentation

---

## Author

**Umar Fazil K**
Electronics and Communication Engineering Student
Passionate about Electronics, PCB Design, Embedded Systems, and Hardware Development.

---

## License

This project is open for learning and educational purposes.
