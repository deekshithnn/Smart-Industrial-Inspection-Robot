# Smart Industrial Inspection Robot
### AI-Based Autonomous Inspection, Voice Interaction & IoT Machine Monitoring

## Project Overview

An intelligent autonomous mobile robot designed for industrial inspection, machine-condition monitoring, obstacle avoidance and human-robot interaction.

The system integrates ESP32 embedded control, AI-based computer vision, offline voice recognition, sensor monitoring and IoT technologies.

## Key Features

- Autonomous navigation and obstacle avoidance.
- YOLO-based person detection using ESP32-CAM and Python.
- Live camera streaming.
- Voice interaction using INMP441 microphone.
- Offline speech recognition using Vosk.
- Spoken responses using MAX98357A audio amplifier and speaker.
- Temperature and humidity monitoring.
- Vibration monitoring using SW-420 and MPU6050.
- Motor current monitoring using ACS712.
- Real-time sensor data recording.
- Flask-based IoT monitoring dashboard.
- Remote robot movement control.

## Voice Interaction System

The robot supports voice-based human interaction.

**Hardware:**
- INMP441 I2S microphone.
- MAX98357A I2S audio amplifier.
- Speaker.
- ESP32 and laptop-assisted audio processing.

**Software:**
- Python.
- Vosk offline speech recognition.
- Text-to-speech processing.
- Wi-Fi communication.

**Working principle:**

1. YOLO detects a person through the camera.
2. The robot stops its motors.
3. The robot greets the detected person.
4. The microphone captures the person's speech.
5. Vosk converts speech into text.
6. The system generates an appropriate response.
7. The speaker plays the response.
8. The robot resumes its autonomous operation after the interaction ends.

## Hardware Components

| Component | Function |
|---|---|
| ESP32 DevKit V1 | Main controller |
| ESP32-CAM | Camera and video streaming |
| L298N | Motor driver |
| Four DC geared motors | Robot movement |
| HC-SR04 | Obstacle detection |
| Servo motor | Ultrasonic scanning |
| DHT11 | Temperature and humidity |
| SW-420 | Vibration detection |
| MPU6050 | Motion and vibration analysis |
| ACS712 | Current monitoring |
| INMP441 | Voice input |
| MAX98357A | Audio output |

## Software Technologies

- Arduino IDE and Embedded C/C++
- Python
- Flask
- OpenCV
- YOLO
- Vosk
- Wi-Fi communication
- HTML, CSS and JavaScript

## Applications

- Industrial equipment inspection.
- Remote machine monitoring.
- Intelligent factory surveillance.
- Human-robot interaction.
- Obstacle-aware autonomous inspection.
- Industrial safety monitoring.

## Future Enhancements

- Machine-learning-based predictive maintenance.
- Advanced industrial fault classification.
- Autonomous mapping and navigation.
- Edge AI-based anomaly detection.
- Improved conversational AI.
- Industrial-grade power and motor control systems.

## Project Status

The project integrates autonomous robot movement, obstacle detection, camera streaming, YOLO-based person detection, sensor monitoring and voice interaction.

Further development focuses on improving motor performance, conversational intelligence and industrial reliability.

## Project Domains

Embedded Systems | Robotics | Artificial Intelligence | Internet of Things | Computer Vision | Industrial Automation
