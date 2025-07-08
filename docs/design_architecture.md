# LUCIA Satellite Design Architecture

Designing LUCIA involves defining the interfaces and integration of all major subsystems within the physical and operational constraints of a CubeSat.

## System Architecture

- **Structure:** The CubeSat frame is constructed from aerospace-grade aluminum or composite materials, providing rigidity, protection, and mounting for all subsystems. For LUCIA, we use a 1U standard.
- **Subsystem Placement:** Careful layout is essential to maximize space, thermal management, and wiring efficiency.
- **Modularity:** All boards and components are designed for easy integration and replacement.

## Mechanical Design

- **Frame:** 1U (10x10x10 cm) skeleton, conforming to the CubeSat Design Specification.
- **Deployables:** Antennas or solar panels may use spring-loaded or burn-wire mechanisms for deployment post-launch.
- **Shielding:** Radiation and thermal protection, where necessary, to ensure survivability of electronics.

## Integration

- **Subsystem Interfaces:** Standardized connectors and protocols (e.g., I2C, CAN, UART) for inter-module communication.
- **Testing:** Mechanical and electrical fit-checks, vibration and shock testing to simulate launch conditions.

---

## References

- [CubeSat Kit Mechanical Interface](https://www.cubesatkit.com/docs/datasheet/CSK_Mechanical_Interface_RevA.pdf)
- [ESA CubeSat Handbook](https://www.esa.int/Education/ESA_Academy/CubeSat_Support)