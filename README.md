# G-Sat (Gryphon Satellite): Leeds CubeSat Project

Welcome to the official repository for the G-Sat ("Gryphon Satellite") project, developed by the Leeds Space // Comms Group at Leeds University. This open-source initiative aims to design, build, and launch a functional CubeSat, while providing a comprehensive educational resource on CubeSats and the complete satellite development process.

## Project Vision

**G-Sat (Gryphon Satellite)** is an academic satellite mission intended to pioneer accessible space engineering at Leeds University. Our mission is not only to develop and launch a satellite, but to document every step, decision, and lesson so that future teams and independent learners can follow and build upon our work.

## What is a CubeSat?

A CubeSat is a class of miniaturized satellite with standardized sizes and interfaces, most commonly organized in units of 10 x 10 x 10 cm ("1U"). CubeSats have transformed access to space for educational, research, and commercial purposes due to their modularity, affordability, and use of commercial off-the-shelf (COTS) components.

---

## The CubeSat Development Process: Overview

Building a CubeSat like G-Sat involves multiple phases and specialized subsystems. Here is a high-level overview:

1. **Mission Concept and Requirements**
   - Define objectives, such as scientific goals or technology demonstrations.
   - Perform feasibility studies and trade-off analyses.

2. **System Architecture**
   - Design the overall structure and interfaces between subsystems.
   - Balance power, mass, volume, and communication needs.

3. **Subsystem Design**
   - **Structure:** Mechanical frame, deployables, shielding.
   - **Power (EPS):** Solar panels, batteries, power management.
   - **On-Board Computer (OBC):** Central processing, data handling.
   - **Attitude Determination and Control System (ADCS):** Orientation, sensors, actuators.
   - **Communications (Comms):** Radio systems, antennas, ground link.
   - **Payload:** The scientific or engineering instrument(s).
   - **Thermal:** Insulation, heaters, thermal analysis.

4. **Integration and Testing**
   - Assemble subsystems, perform functional and environmental testing.
   - Verify interfaces and simulate mission scenarios.

5. **Launch and Operations**
   - Final integration with deployer/launch vehicle.
   - Regulatory clearance and coordination.
   - Ground station setup and operations planning.

---

## G-Sat Subsystems: Detailed Descriptions

- See the `docs/` directory for in-depth guides and the [Wiki](../../wiki) for expanded tutorials and background.

| Subsystem | Description | Example Docs |
|-----------|-------------|--------------|
| Structure | Aluminum or composite frame, deployables, shielding | [docs/design_architecture.md](docs/design_architecture.md) |
| EPS | Solar panels, battery selection, power regulation | [docs/power_system.md](docs/power_system.md) |
| OBC | Microcontroller/processor, software, fault handling | [docs/obc.md](docs/obc.md) |
| ADCS | Magnetometers, gyros, reaction wheels, sun sensors | [docs/adcs.md](docs/adcs.md) |
| Comms | VHF/UHF/S-band radios, protocols, ground station | [docs/comms_system.md](docs/comms_system.md) |
| Payload | Cameras, sensors, custom experiment | [docs/payload.md](docs/payload.md) |
| Thermal | Passive/active thermal control, analysis | [docs/thermal.md](docs/thermal.md) |

---

## Why G-Sat ("Gryphon Satellite")?

The Gryphon is the emblem of Leeds, symbolizing vigilance, strength, and innovation. G-Sat aspires to embody these traits, marking Leeds University’s first foray into space with a mission built on transparency, collaboration, and education.

---

## References and Further Reading


- [Mini Bible](https://www.mdpi.com/2076-3417/9/15/3110) - A good introduction to some key details about CubeSat missions
- [CubeSat101](https://www.nasa.gov/wp-content/uploads/2017/03/nasa_csli_cubesat_101_508.pdf?emrc=05d3e2) - The Bible. Read this if you don't read anything else.
- [How to make a CubeSat team](https://s3vi.ndc.nasa.gov/ssri-kb/static/resources/University%20CubeSat%20Project%20Management%20for%20Success.pdf)
- [AMSAT UK: Getting Started with Amateur Radio Satellites](https://amsat-uk.org/beginners/)
- [CubeSat](https://www.cubesat.org/) - Official website for CubeSat
- [CubeSat Poly Design](https://static1.squarespace.com/static/5418c831e4b0fa4ecac1bacd/t/56e9b62337013b6c063a655a/1458157095454/cds_rev13_final2.pdf) - CubeSat Design
- [Open Source Satellite Programme](https://www.opensourcesatellite.org/)
- [RHIT-SmallSat](https://rose-bic.atlassian.net/wiki/spaces/SmallSat/overview?homepageId=9404872) - A student satellite team
- [IIT Bombay Student Satellite Team](https://www.aero.iitb.ac.in/satelliteWiki/index.php/Building_the_Team) - Another student satellite

---

## Getting Started

- See `docs/cubesat_overview.md` for fundamentals.
- Explore subsystem documentation for in-depth design.
- Check the [Wiki](../../wiki) for hands-on tutorials and examples.

---

## Contributing

We welcome contributions from students, enthusiasts, and professionals interested in space technology! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---
