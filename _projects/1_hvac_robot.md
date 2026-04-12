---
layout: page
title: HVAC Duct Cleaning & Inspection Robotic System
description: A full-stack mechatronic system for automated cleaning and inspection of HVAC duct networks, integrating active brush mechanisms, embedded sensing, tethered power delivery, and real-time vision.
img: assets/img/projects/hvac_robot.jpg
importance: 1
category: robotics
tags: [robotics, mechatronics, embedded-systems, field-robotics]
related_publications: false
---

## Overview

This project develops a deployable robotic system for automated cleaning and inspection of HVAC duct networks, targeting real-world industrial adoption. The system integrates confined-space navigation, active cleaning, environmental sensing, and real-time vision into a single field-deployable platform.

The project comprises four interconnected subsystems developed and validated as an integrated whole:

---

## Subsystem 1: Autonomous HVAC Duct Navigation Robot

The core mobile platform is designed to navigate confined duct geometries and carry the cleaning and sensing payload.

**Core Capabilities**
- Confined-space mobile navigation inside duct systems
- Onboard air quality sensing (particulate and contamination monitoring)
- Real-time inspection via embedded vision system
- Full-stack mechatronic system integration
- Sensor fusion and environmental data acquisition

The platform is designed from the outset for harsh, constrained environments, with a clear engineering trajectory from prototype to field-deployable system.

---

## Subsystem 2: Active Brush Mechanism with Dynamic Stability Optimization

A dedicated cleaning subsystem focused on maximising cleaning efficiency while maintaining mechanical stability under load.

**System Features**
- Linear actuator-driven, height-adjustable brush assembly
- Crane-like linkage for controlled brush positioning
- Tunable contact force with duct surfaces

**Key Engineering Insights**

Early prototyping identified instability arising from a single-hinge architecture. Design iteration involved a structured trade-off analysis between compliance and structural rigidity, leading to a migration toward multi-point constraint mechanisms with reduced oscillation under operational load.

---

## Subsystem 3: Tethered Monitoring & Power Delivery Robot

A robust robotic system designed for high-reliability operation in constrained or hazardous environments, providing stable power and communication over extended cable runs.

**System Architecture**
- 24V tethered power delivery over cables up to 15 m in length
- Custom-built controller interface
- Embedded camera system with real-time video streaming and recording capability
- Noise-resistant signal handling for reliable communication

**Key Design Challenges**
- Voltage drop and power stability management across cable length
- EMI and noise mitigation to preserve signal integrity
- Compact integration of the vision system within the robot chassis

---

## Subsystem 4: Wired Control & Power Distribution System

A supporting power and control infrastructure subsystem bridging laboratory prototypes to field-deployable robotic systems.

**Key Features**
- Mains-powered input with regulated 24V output
- Aluminium enclosure for heat dissipation and mechanical durability
- Integrated safety considerations including isolation and protection circuitry

This subsystem standardises the power and control interface across the robotic ecosystem, enabling reliable and repeatable tethered deployment.

---

## Engineering Significance

The HVAC robotic system represents a full-stack mechatronic integration challenge — combining mechanism design, embedded sensing, power electronics, and field robotics into a single coherent system. The project emphasises engineering rigour across the full development lifecycle, from concept and prototyping through to validation and deployment readiness.
