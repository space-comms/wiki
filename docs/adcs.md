# LUCIA Attitude Determination and Control System (ADCS)

## Purpose

The ADCS is responsible for determining and controlling the orientation of the satellite in space.

## Sensors

- Magnetometers
- Three-axis digital output gyroscope (A3G4250D)
- Geomagnetic sensor (RM3100)
- Temperature sensor (STD875)
- Sun sensors

## Actuators

- Magnetorquers (electromagnetic rods)
- Reaction wheels (for precise pointing, if mission requires)

## Algorithms

- Sensor fusion for attitude determination
- Control loops for actuation (e.g., PID controllers)

## Modes

- Detumble (stabilization after deployment)
- Sun-pointing or nadir-pointing (for payload operations)
- Safe mode (minimal power consumption)

## CubeSat Subsystems

- Interface

The function of the interface is to transmit information from the sensors to the microcontroller and from the microcontrollers to the actuators. The sensor system consists of all the elements that collect data necessary for the ADCS to operate. This comprises sensors that monitor temperature as well as orientation and placement as well as velocity.

- Controller

The system that unites sensors and actuators is known as a controller. In order to achieve the intended orientation, it calculates the positioning from the data acquired, compares it to the desired position, and determines the rotations to apply to the actuators.

- Actuator

All the elements that move the CubeSat are included in the actuator system. They involve rotations about the three axes of roll, pitch, and yaw. The basic satellite actuators are magnetorquers, reaction wheels, and a control momentum gyroscope.

- Sensor

The basic satellite sensors are a gyroscope, gyrometer, startrackers, sun sensors, magnetometers, and temperature sensors. 

## Design and Implementation

- The ADCS is based on implementing the controller and sensor subsystems to monitor attitude determination.
- The STM32F205 microcontroller is used on the board as the main controller. External circuits are designed on the board to be compatible with the microcontroller and ADCS functions. The supplied circuit feeds the board from the voltage supplied by solar panels. The ADCS board's sensors subsystem include a magnetometer, temperature, and gyroscope sensors. The ADCS board circuits are simulated using KiCAD.

## Software interface of the ADCS
- The STMF205 microcontroller is programmed based on the J-TAG interface connection pin by debugging through SPI communication protocol. Separate wires are used for the clock and data line. Sensor and STM connections are made using I2C pins. The data from STDS75 and A3G4250D sensors are read using the I2C communication protocol.

## ADCS Structure
- primary objective of ADCS is to record intial angular momentum and random rotation during deployment, identify the CubeSat's attitude, and either maintain or change the CubeSat's attitude in accordance with the satellite's information.
- An amplifier called the "LMP7704MT" amplifies the voltage produced by the solar cells when they are connected to one another via a pico-blade. A joint action group is used to easily debug the device. Three H-bridge drivers are intended for use with brush motors. The gyroscope, magnetometer, and temperature sensors are connected to the board.
- The three H-bridge drivers (

## Sensors in ADCS
- an array of sensors, actuators, and a backup microcontroller with algorithms make up the ADCS.

## References

- [CubeSat ADCS Design](https://www.cubesat.org/)
- [Open Source Satellite Programme: ADCS](https://www.opensourcesatellite.org/)
