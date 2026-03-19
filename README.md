# radar_system

## Theory
The proposed system is an **ESP32-based Radar and Defence Prototype** designed to simulate how surveillance and automated defence mechanisms work.  
The system uses an **ultrasonic (US) sensor** to detect objects (representing enemy targets) and activates a defence response when a target is identified within a defined range.

---

## Project Overview

A radar system that works as follows:

- The ultrasonic sensor emits high-frequency sound waves.  
- Echoes reflected from objects are received back.  
- The ESP32 calculates distance using the **time-of-flight principle**.  
- A servo motor rotates the sensor, scanning a defined angular range (for example, 0°–180°).  
- Each scan cycle maps **angle + distance** data.  
- Object presence is interpreted as a potential target (enemy).

  ## Diagram

![Radar Diagram](image.png)
