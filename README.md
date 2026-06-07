# SmartHome - AUTOMATION

This was the first project I ever worked on. It won second place at the State Review of Student Projects at the Faculty of Electrical Engineering and Computing for the 2016/2017 academic year, which is why it holds a special place among all the projects I have completed. 

<br>
<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/SmartHome-AUTOMATION/Picture1.jpg" alt="Banner" width="720" />
</div>
<br>

## Overview

Smart Home Automation prototype developed as an educational and IoT project focused on home automation, remote monitoring, and energy-efficient control of household devices.
This project demonstrates how modern smart home systems can integrate sensors, microcontrollers, and automation software into a single platform capable of monitoring and controlling various aspects of a home environment.

<br>
<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/SmartHome-AUTOMATION/Picture2.jpg" alt="Smarthome in the making" width="720" />
</div>
<br>

The system is designed to:

* Control indoor and outdoor lighting
* Manage heating and cooling systems
* Automate blinds
* Provide remote access through smartphones, tablets, or computers
* Improve comfort while reducing energy consumption

## Architecture

<br>
<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/SmartHome-AUTOMATION/Picture4.jpg" alt="Mockup in Croatian" width="720" />
</div>
<br>

The prototype is built around a distributed IoT architecture consisting of:

### Raspberry Pi 3

Acts as the central communication hub (broker) responsible for receiving and distributing information between connected devices.

### OpenHAB 2

An open-source home automation platform used as the central control interface. OpenHAB enables integration of various smart devices and provides a unified management system.

### ESP8266 / NodeMCU

Wi-Fi-enabled microcontrollers used for communication between sensors, actuators, and the central system.

### WeMos D1

Microcontroller platform compatible with Arduino, used for sensor acquisition and device control.

### Relay Modules

Relay boards allow low-voltage microcontrollers to safely switch higher-power household appliances and electrical circuits.

## Features

* Wireless home automation network
* Sensor-based decision making
* Remote device control over Wi-Fi
* Real-time monitoring
* Web server integration
* Relay control for household appliances
* Modular and expandable architecture

## Technologies Used

* Raspberry Pi 3
* OpenHAB 2
* ESP8266 (NodeMCU)
* WeMos D1
* Arduino Framework
* Wi-Fi Networking
* Relay Modules
* Embedded C/C++
* IoT Architecture


## Educational Purpose

<br>
<div align="center">
    <img src="https://raw.githubusercontent.com/BrunosCodeLab/Images/refs/heads/main/SmartHome-AUTOMATION/Picture3.jpg" alt="Mockup in Croatian" width="720" />
</div>
<br>

This project was created to explore concepts of IoT, embedded systems, wireless communication, and home automation by combining hardware and software components into a functional smart home prototype.
