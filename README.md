# DC-Motor-Speed-Controller-Circuit
PWM (Pulse Width Modulated) controller circuit for controlling the speed of DC Motors.

## Circuit Diagram
![Circuit Diagram](https://github.com/user-attachments/assets/821815f2-4c95-43e0-baa3-987364d4d640)

## Overview
This project demonstrates how to use a **555 timer IC** in astable mode to generate a **PWM signal** for controlling the speed of **DC motors** and brightness of **LEDs**. By adjusting the duty cycle, the speed of the motor can be varied efficiently.

## Features
- Adjustable **duty cycle** for fine control of motor speed.
- Supports **low-power loads (single LEDs)** and **high-power loads (LED strips, DC motors)** using a **MOSFET switch**.
- Operates with **5V - 12V DC power supply**.
- Simple **hardware-based solution** (no microcontroller required).

## Components Required
| Component       | Specification   | Quantity |
|----------------|----------------|----------|
| 555 Timer IC   | NE555           | 1        |
| Resistor       | 1KΩ             | 1        |
| Resistor       | 100Ω            | 1        |
| Potentiometer  | 47KΩ            | 1        |
| Capacitor      | 100nF           | 1        |
| Capacitor      | 10µF            | 1        |
| Diode          | 1N4148          | 2        |
| MOSFET         | IRFZ44N         | 1        |
| Breadboard     | -               | 1        |
| Jumper Wires   | -               | As needed |
| Power Supply   | 5V - 12V DC     | 1        |

## Working Principle
- The **555 timer IC** operates in **astable mode** to generate a **PWM signal**.
- The **duty cycle** of the PWM signal determines the **speed of the motor** or **brightness of an LED**.
- A **potentiometer and diodes** allow **independent control of ON and OFF times**, adjusting the duty cycle.
- A **MOSFET (IRFZ44N)** is used as a **switch** to control high-power loads like **DC motors or LED strips**.

## Applications
- **DC Motor Speed Control** – Robotics, fans, motorized applications.
- **LED Brightness Control** – LED strips for decoration and lighting.
- **Servo Motor Control** – Used in automation and robotics.
- **Inverter Circuits** – Generates PWM signals for transformers.

## Improvements & Modifications
- **Preset Speed Selection** – Replace the **potentiometer** with **switches + fixed resistors** for preset speeds (25%, 50%, 75%, 100%).
- **Microcontroller Integration** – Use **Arduino, ESP32, or PIC** for software-based **PWM control**.
- **Higher Power Handling** – Use a **stronger MOSFET (e.g., IRF540N)** for **higher current loads**.
- **Feedback System** – Add a **tachometer** to **maintain constant speed**.

## References
- **youtube video link** : https://youtu.be/QH-R0NyjlY4?si=imVwCNgoQ4xN1hFb.
- **website** : https://elonics.org/pwm-dc-motor-speed-and-led-dimmer-circuit-using-555-ic/
- **canvalink** : https://www.canva.com/design/DAGjpDdfTE0/8MwBPGtSqkQqUyJnnQxA-Q/edit.

---
