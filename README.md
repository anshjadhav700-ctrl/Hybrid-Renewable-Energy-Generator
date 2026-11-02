# Green Power: A Hybrid Model Combining Vertical Axis Wind Turbine and Solar Photovoltaic

A hybrid renewable energy system that combines a **Vertical Axis Wind Turbine (VAWT)** and a **Solar PV panel** to provide continuous, reliable DC power in varying weather conditions.

**Department of E&TC, NKOCET, Solapur**

## Overview
Solar panels only work in daylight and wind turbines need wind. This project combines both so that the battery keeps getting charged whichever source is available. The VAWT starts at low wind speeds and accepts wind from any direction, which makes it a good match for small, off-grid setups.

## Features
- Dual renewable sources (Solar + Wind)
- VAWT works at low wind speeds and from any direction
- Charge controller with battery storage for continuous supply
- Protection against overcharging, deep discharge and reverse current
- Compact, low-cost and low-maintenance
- Suitable for rural homes, farms, street lighting and off-grid sites

## Block Diagram
![Block Diagram](Block_Diagram/Blcokd.png)

> Replace `block_diagram.png` with your actual file name.

**Working:** Solar PV (via MPPT controller) and the VAWT generator (via its own charge controller) charge a central battery. The battery supplies the DC load, with protection and metering monitoring voltage, current and battery health.

## Circuit Diagram
![Circuit Diagram](Circuit_Diagram/circuit_diagram.png)

> Replace `circuit_diagram.png` with your actual file name.

## Hardware Components
| Component | Specification | Purpose |
|---|---|---|
| Solar PV Panel | 10W / 20W / 50W, poly/mono-crystalline | Converts sunlight into DC power |
| VAWT | 2-4 blades, low wind speed operation | Captures wind from any direction |
| Charge Controller | 12V, 10A / 20A hybrid | Regulates charging, protects battery |
| Battery | 12V, 7Ah / 12Ah lead-acid / Li-ion | Stores energy for continuous supply |
| Stepper Motor | 5V / 12V / 24V | Used as generator / rotational element |
| Wires & Cables | Copper, 1 sq.mm / 2.5 sq.mm | Power transfer with minimum loss |

## Cost Estimation
| Component | Approx. Cost (INR) |
|---|---|
| Solar Panel | 1800 |
| Charge Controller | 400 |
| Battery | 900 |
| Stepper Motor | 700 |
| Wooden Structure | 3000 |

## Repository Structure
```
Green-Power-Hybrid-VAWT-Solar/
├── README.md
├── LICENSE
├── .gitignore
├── Block_Diagram/    # System block diagram
├── Circuit_Diagram/  # Circuit connections
└── Report/           # Full project report (PDF)
```

## Applications
Rural electrification, standalone home systems, agricultural lighting and pumps, street lighting, small workshops, portable and emergency power.

## Future Scope
- IoT-based monitoring
- MPPT for both sources
- Advanced Li-ion batteries / supercapacitors
- Smart city and rooftop installations
- Grid integration

