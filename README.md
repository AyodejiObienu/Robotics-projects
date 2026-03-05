# 🤖 Robotics Engineering Lab
> **Hands-on robotics, electronics, and embedded systems experiments using Arduino**

This repository documents my practical journey into robotics engineering, embedded systems, and electronic circuit design. It contains experiments, component explorations, and mini-projects built using Arduino microcontrollers, various sensors, actuators, and electronic components.

The goal of this repository is to develop a deep understanding of hardware-software interaction, build increasingly complex robotic systems, and eventually integrate these components into a fully functional robot platform.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Learning Goals](#learning-goals)
- [Hardware Components Used](#hardware-components-used)
- [Project Structure](#project-structure)
- [Architecture Of Experiments](#architecture-of-experiments)
- [Installation & Setup](#installation-&-setup)
- [Usage](#usage)
- [Core Concepts Explored](#core-concepts-explored)
- [Technical Stack](#technical-stack)
- [Future Robotics Projects](#future-robotics-projects)


---

## 🎯 Overview

This repository contains progressive robotics experiments designed to develop practical understanding of:

1. **🕹️ Microcontroller programming**
2. **🧠 Intelligence Layer** - Analyzes student complaints and generates actionable recommendations based on institutional capacity
3. **⚡ Electronic circuits**
4. **🦻 Sensor integration**
5. **🦾 Motor control**
6. **🖼️ Embedded system design**
7. **🫱🏾‍🫲🏾 Hardware-software interaction**

Each project focuses on one or more electronic components, exploring how they work both electrically and programmatically using Arduino C/C++.

The repository documents:

1. Circuit setups
2. Code implementations
3. Code implementations
4. Experiment outcomes
5. Engineering concepts behind each component

These experiments form the foundation for larger robotics systems, where multiple components work together in an integrated robotic platform.

---

## 🔴 Learning Goals
> **The objective of this repository is to develop strong practical knowledge in the following areas:**

### Embedded Systems Programming
Understanding how software interacts directly with hardware through microcontrollers.

### Circuit Design
Learning how to design circuits safely and efficiently using breadboards and electronic components.

### Sensor Integration
Working with sensors to gather environmental data such as:

1. light
2. distance
3. temperature
4. humidity

### Actuator Control
Using motors and electronic outputs to control movement and physical systems.

### Robotics Systems Thinking
Understanding how small electronic modules combine to form larger robotic systems.

---

## 🔌 Hardware Components Used
The following electronic components are explored across different experiments:

### Microcontrollers
Arduino Uno

### Basic Electronic Components
-Breadboard
-Jumper wires
-Resistors
-LEDs
-RGB LEDs
-Push buttons
-Potentiometers

### Sensors
-Photoresistors
-Photodetectors
-HC-SR04 ultrasonic distance sensor
-DHT11 temperature and humidity sensor
-Infrared remote receiver

### Actuators
-Servo motors
-DC motors
-Stepper motors
-Active buzzers
-Passive buzzers

### Logic Components
-74HC595 Serial-to-Parallel Shift Register

### Displays
-LCD Displays

---

## 📁 Project Structure

```
Robotics-projects/

├── README.md
│
├── Piezo_Buzzer/
│   ├── buzzer_code.ino
│   └── circuit_diagram.png
│
├── LED_Experiments/
│   ├── led_blink.ino
│   ├── rgb_led_control.ino
│
├── Push_Button/
│   ├── push_button_input.ino
│
├── Potentiometer/
│   ├── analog_read.ino
│
├── Motor_Control/
│   ├── dc_motor_control.ino
│   ├── servo_control.ino
│
├── Sensors/
│   ├── ultrasonic_distance.ino
│   ├── temperature_humidity.ino
│
├── Shift_Register_74HC595/
│   ├── binary_counter.ino
│   ├── shift_operations.ino
│
└── Advanced_Projects/
    ├── remote_controlled_rgb_led
    ├── ultrasonic_distance_meter
    └── lcd_calculator
```
Each folder contains:

-Arduino code
-circuit description
-experiment notes

## 🏗️ Experiment Architecture

### Most experiments follow a consistent structure:

```
┌───────────────────────────────┐
│        Arduino Program        │
│      (C/C++ in Arduino IDE)   │
└───────────────┬───────────────┘
                │
                ▼
      ┌───────────────────┐
      │ Arduino UNO Board │
      └─────────┬─────────┘
                │
                ▼
     ┌──────────────────────┐
     │ Electronic Component │
     │ (Sensor or Actuator) │
     └─────────┬────────────┘
               │
               ▼
       Physical Output/Input

```
Example interactions include:

-Sensor → Arduino → Serial Monitor
-Button → Arduino → LED
-Potentiometer → Arduino → Motor Speed
-Ultrasonic Sensor → Arduino → Distance Calculation

## 💻 Technical Stack
```
| Layer           | Technology               | Purpose                 |
| --------------- | ------------------------ | ----------------------- |
| Microcontroller | Arduino Uno              | Embedded control        |
| Programming     | Arduino C/C++            | Hardware programming    |
| IDE             | Arduino IDE              | Development environment |
| Electronics     | Breadboards & components | Circuit prototyping     |
| Visualization   | Serial Monitor / Plotter | Data monitoring         |

```
🧠 Core Concepts Explored
> **Through these experiments, the following engineering concepts are studied:**

## Circuit Fundamentals

Voltage
Current
Resistance
Ohm’s Law

### Microcontroller Programming

Digital Input/Output
Analog Input
PWM (Pulse Width Modulation)

### Motor Control

Servo motor positioning
DC motor speed control
Direction control

### Sensor Data Processing

Distance measurement using ultrasonic sensors
Light detection using photoresistors
Temperature and humidity sensing

### Logic & Digital Systems

Using the 74HC595 shift register to understand:
Binary counters
Logical shift left
Logical shift right
Circular bit shifting

### Serial Communication

Using the Arduino Serial Monitor and Serial Plotter to:

visualize sensor data
monitor real-time signals
debug systems


### 🚀 Installation & Setup

Requirements

Arduino IDE
Arduino Uno board
USB cable
Electronic components used in experiments

## Step 1 — Install Arduino IDE

Download from:
https://www.arduino.cc/en/software

## Step 2 — Connect Arduino

Connect the Arduino board to your computer using a USB cable.

## Step 3 — Upload Code

Open any .ino file from the repository inside the Arduino IDE.

Select:

Tools → Board → Arduino Uno
Tools → Port → Select COM Port

Then upload the program.

### 📖 Usage

> **Each project folder contains an experiment using specific components.**

Typical workflow:

Build the circuit using the breadboard
Open the corresponding .ino file
Upload the program to the Arduino board
Observe the output (LED, motor, sensor data, etc.)
Monitor output using Serial Monitor or Serial Plotter


### 🔬 Example Experiments
## LED Experiments

Learning how to control LEDs and RGB LEDs using digital signals.

## Push Button Input

Understanding pull-up and pull-down resistor configurations.

## Ultrasonic Distance Measurement

Using the HC-SR04 sensor to measure distances and build a portable distance meter.

## Temperature Monitoring

Using the DHT11 sensor to measure temperature and humidity and display results on an LCD screen.

## Shift Register Experiments

Using the 74HC595 shift register to control multiple outputs from limited Arduino pins.

### 🧪 Advanced Projects

Some more complex systems built using combinations of components include:

## Remote Controlled RGB LED

Using an infrared remote to control LED brightness and color.

## Ultrasonic Distance Sensor Device

Portable device capable of measuring and displaying distance.

## LCD Calculator

A simple calculator built using an LCD display and microcontroller logic.

### 🤖 Future Robotics Projects

> **These experiments will eventually lead to larger integrated robotics systems.**

Planned future work includes:

## Integrated Robot Platform

Building a robot that combines:

sensors
motors
remote control
data display
environment interaction

## Robot Simulation

Future simulations will be done using:
AutoCAD
Autodesk Fusion 360

These tools will be used for:

robot chassis design
component layout
mechanical structure modeling

### 📈 Learning Progress

This repository documents my progress as I continue developing skills in:

robotics engineering
embedded systems
circuit design
sensor integration
motor control
hardware programming

Each new experiment builds toward designing and constructing complex robotic systems.

###👨‍💻 Author

Obienu Baubajisos Ayodeji
Computer Engineering Major

Interests:

Robotics
Artificial Intelligence
Embedded Systems
Intelligent Infrastructure Platforms

GitHub:
https://github.com/AyodejiObienu
LinkedIn:
www.linkedin.com/in/baubajisos-obienu-4b877835a

### 🚧 Status

Active Development

New experiments and robotics systems will continue to be added as learning progresses.
```






