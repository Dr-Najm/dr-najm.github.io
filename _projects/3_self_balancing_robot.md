---
layout: page
title: Self-Balancing Robot Platform for Control Systems Research
description: An Arduino-based inverted pendulum platform serving as a continuously evolving testbed for PID control development, stability analysis, and undergraduate control systems education.
img: assets/img/projects/balancing_robot.jpg
importance: 3
category: control systems
tags: [control-systems, embedded-systems, robotics]
related_publications: false
---

## Overview

This project develops and maintains a self-balancing robot platform — an inverted pendulum implementation — used both as a research testbed for control algorithm development and as an educational tool for undergraduate control systems courses.

The platform is continuously evolved as new control strategies are explored and as it is adapted for teaching purposes, making it a living engineering artefact rather than a one-off prototype.

---

## Technical Stack

**Hardware**
- Arduino Nano microcontroller
- IMU (Inertial Measurement Unit) for real-time orientation feedback
- Dual-motor drive system

**Software & Control**
- IMU-based feedback control loop
- PID controller implementation with tunable gains
- Auto-trim calibration routine for balance point identification
- Panic/failsafe mechanisms for out-of-range states
- Configurable motor direction logic for flexible hardware integration

---

## Control Engineering Features

The platform is designed to expose and exercise the core challenges of feedback control:

- **PID Tuning** — systematic gain adjustment to achieve stable balancing behaviour
- **Stability Analysis** — characterisation of system response to disturbances
- **Sensor Fusion** — processing IMU data for reliable angle estimation
- **Failsafe Logic** — handling edge cases and preventing hardware damage during instability

---

## Educational Use

The platform is integrated into undergraduate control systems teaching as a hands-on demonstration and experimental tool. Students interact with a real physical system to:

- Observe the effect of PID gain changes on transient response
- Understand the relationship between sensor feedback and actuator output
- Develop intuition for stability margins and control system design

This bridges the gap between theoretical control systems concepts and observable physical behaviour.

---

## Engineering Significance

The self-balancing robot is a canonical control systems problem with rich practical complexity — sensor noise, actuator dynamics, mechanical compliance, and real-time computation constraints all interact in ways that cannot be fully captured by simulation alone. This platform provides a compact, accessible, and reconfigurable environment for confronting these challenges directly.
