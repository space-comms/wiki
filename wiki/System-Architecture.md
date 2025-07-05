# System Architecture

## Overview

A CubeSat's architecture defines how subsystems fit and interact within the satellite’s volume, power, and data budgets.

## High-Level Block Diagram

- **Structure:** The frame and mounting points for all hardware.
- **EPS (Electrical Power System):** Solar panels, batteries, power distribution.
- **OBC (On-Board Computer):** Central controller, handles logic and data.
- **ADCS (Attitude Determination & Control):** Controls orientation in space.
- **Communications:** Radios and antennas for ground-space links.
- **Thermal:** Keeps everything within safe temperature range.
- **Payload:** The main mission instrument or experiment.

## Data/Power Flow

- EPS distributes power to all subsystems.
- OBC manages commands, collects data from subsystems and payload.
- ADCS receives commands from OBC, uses sensors/actuators to orient satellite.
- Comms links OBC and ground station.

## Interface Standards

- **Electrical:** Use of I2C, CAN, or UART buses.
- **Mechanical:** CubeSat Kit and CalPoly standards for size/mounting.
- **Software:** Modular, event-driven code structure.

---

### References

- [CubeSat Kit Block Diagram](https://www.cubesatkit.com/)
- [Open Source Satellite Programme Architecture](https://www.opensourcesatellite.org/)