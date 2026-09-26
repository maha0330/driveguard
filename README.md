# driveguard
# 🚗 DriveGuard

## AI-Based Driver Drowsiness & Distraction Detection System

DriveGuard is a real-time **computer vision-based driver monitoring prototype** designed to demonstrate how facial landmarks can be used to identify signs associated with driver drowsiness and distraction.

The system uses a webcam to monitor the driver's face, analyzes eye movement using **Eye Aspect Ratio (EAR)**, estimates head orientation, and provides visual and audio alerts when potentially unsafe behavior is detected.

> **Important:** DriveGuard is an educational and demonstration prototype. It is not a certified automotive safety system and must not be used as the sole safety mechanism while driving.

---

## 🎯 Project Objective

Driver fatigue and distraction can reduce a driver's ability to respond to changing road conditions.

The objective of DriveGuard is to demonstrate a computer vision system that can:

- 👁️ Monitor the driver's eyes
- 😴 Detect prolonged eye closure
- 🧭 Monitor approximate head orientation
- 👀 Detect prolonged looking-away behavior
- 🔊 Generate an audio warning
- ⚠️ Display visual safety warnings
- 📊 Count drowsiness and distraction events
- 📷 Process the driver's face in real time using a webcam

---

# ✨ Main Features

## 😴 1. Drowsiness Detection

DriveGuard calculates the **Eye Aspect Ratio (EAR)** from facial landmarks.

When the driver's eyes remain closed for a configurable amount of time, the system considers it a possible drowsiness event.

The system then:

- Changes the safety status
- Displays a warning
- Increases the drowsiness counter
- Activates a continuous audio alarm

Example:

```text
⚠️ DROWSINESS DETECTED

WAKE UP! PLEASE STAY ALERT!
