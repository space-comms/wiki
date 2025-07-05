# Attitude Determination & Control System (ADCS)

## Function

ADCS determines and controls the orientation (attitude) of the CubeSat in space.

## Sensors

- **Magnetometers:** Detect Earth's magnetic field.
- **Sun Sensors:** Detect Sun’s position.
- **Gyroscopes:** Measure rate of rotation.

## Actuators

- **Magnetorquers:** Generate torque using electromagnetic coils.
- **Reaction Wheels:** Provide fine pointing (if required by mission).

## Control Algorithms

- Sensor fusion (Kalman filtering)
- PID control loops for actuation

## Modes of Operation

- **Detumble:** Stabilizes satellite post-deployment.
- **Sun-pointing/Nadir-pointing:** For payload or power optimization.
- **Safe mode:** Minimal activity to conserve energy.

## Testing

- Hardware-in-the-loop simulation
- Magnetic field simulators

---

### References

- [CubeSat ADCS Design](https://www.cubesat.org/)
- [Open Source Satellite Programme: ADCS](https://www.opensourcesatellite.org/)