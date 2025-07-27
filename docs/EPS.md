# Electrical Power System (EPS)

## Function

EPS generates, stores, and distributes electrical power to all CubeSat subsystems.

## Main Components

- **Solar Panels:** Mounted on CubeSat faces; convert sunlight into electricity.
- **Batteries:** Store energy for eclipse periods (when in Earth's shadow).
- **Power Distribution Board:** Regulates voltage, monitors current, and protects circuits.

## Design Considerations

- **Power Budget:** Calculate generation vs. consumption (consider worst-case scenarios).
- **Battery Chemistry:** Li-Ion or Li-Poly with protection circuitry.
- **Redundancy:** Critical for reliability—include fuses, backup paths.
- **Thermal:** Batteries must stay within safe operating range.

## Testing

- Solar simulator for panel tests
- Battery charge/discharge cycles
- Load testing for distribution board

---

### References

- [CubeSat 101: Power Systems](https://www.nasa.gov/sites/default/files/atoms/files/nasa_csli_cubesat_101_508.pdf)
- [Open Source Satellite Programme EPS](https://www.opensourcesatellite.org/)