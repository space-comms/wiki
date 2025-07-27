# On-Board Computer (OBC) Software for LUCIA

## Architecture
The OBC runs FreeRTOS on an STM32 microcontroller. Software is modular, with separate tasks for telemetry, command handling, and payload operations.

## Features
- Watchdog timer for fault tolerance
- Telemetry packetization (CCSDS standard)
- Uplink command parser
- Persistent storage using FRAM

## Development Log
- 2025-02-10: RTOS ported to STM32F405
- 2025-03-01: Implemented telemetry downlink

## References
- [FreeRTOS](https://www.freertos.org/)
- [CCSDS Telemetry Standard](https://public.ccsds.org/Pubs/133x0b1c2.pdf)
