# SDR Experiments for CubeSat Telemetry

## Introduction
We use software-defined radio (SDR) to receive and decode telemetry from LUCIA and other satellites. SDR enables flexible demodulation and real-time signal analysis.

## Hardware
- RTL-SDR v3
- Nooelec NESDR Smart
- Custom-built LNA

## Software
- GQRX for spectrum visualization
- GNURadio for demodulation and decoding
- SatNOGS client for automated reception

## Experiment Log
- 2025-03-12: Successfully received NOAA-19 APT images
- 2025-04-05: Decoded APRS packets from ISS

## References
- [RTL-SDR Blog](https://www.rtl-sdr.com/)
- [SatNOGS Wiki](https://wiki.satnogs.org/)
