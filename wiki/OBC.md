# On-Board Computer (OBC)

## Function

The OBC is the CubeSat’s brain, controlling all operations, handling data, and interfacing with other subsystems.

## Hardware

- Microcontroller (e.g., ARM Cortex-M, MSP430) or microprocessor (Raspberry Pi Compute Module)
- Non-volatile storage (Flash, SD card) for software/data
- Watchdog timers for fault recovery

## Software

- Real-time OS (e.g., FreeRTOS) or custom firmware
- Task scheduling, telemetry, health monitoring, error handling
- Data handling for payload and subsystems

## Redundancy and Fault Tolerance

- Dual OBCs, if mass/power allow
- Safe-mode routines, hardware and software watchdogs

## Testing

- Unit and integration tests for all software
- Fault injection and recovery drills
- In-orbit software upgrade capability (if possible)

---

### References

- [Open Source Satellite OBC](https://www.opensourcesatellite.org/)
- [CubeSat OBC Design](https://www.cubesat.org/)