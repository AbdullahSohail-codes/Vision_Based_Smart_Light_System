# 👤💡 Face Detection LED Control — IoT Project

An IoT-based system that combines computer vision with hardware control. A camera continuously monitors the area, and when a human face is detected, the system automatically turns on an LED. When no face is present, the LED turns off.

This project demonstrates how AI-based detection can trigger real-world physical actions, and it can be extended into smart lighting, security alerts, or presence-based automation systems.

## Features
- Real-time face detection using a camera feed
- Automatically turns the LED ON when a face is detected
- Turns the LED OFF when no face is present
- Fast response between detection and hardware action
- Easy to extend to buzzers, relays, door locks, or notifications

## How It Works
1. The camera captures a live video stream.
2. Each frame is processed by a face detection algorithm.
3. If a face is found, a signal is sent to the microcontroller.
4. The microcontroller switches the LED ON (or OFF when no face is detected).

## Possible Applications
- Smart presence-based lighting
- Basic security and intrusion alert systems
- Energy-saving automation
- Foundation for smart door or attendance systems

## Purpose
Built to explore the integration of Computer Vision and IoT, and to show how software-based AI detection can control physical hardware in real time.
