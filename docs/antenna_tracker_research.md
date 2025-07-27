# Antenna Tracker Project Research

## Overview
The antenna tracker automates pointing for satellite passes. We evaluated several tracking algorithms and hardware options.

## Hardware
- Arduino Mega with motor drivers
- 3D-printed azimuth/elevation mount
- GPS and digital compass for calibration

## Software
- Predicts satellite passes using TLE data (PyEphem)
- Web dashboard for manual override

## Experiment Log
- 2025-04-12: First automated ISS pass tracking
- 2025-05-01: Improved accuracy with PID tuning

## References
- [PyEphem](https://rhodesmill.org/pyephem/)
- [AMSAT Antenna Rotator Projects](https://www.amsat.org/rotator/)
