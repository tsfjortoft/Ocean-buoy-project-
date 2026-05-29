# Ocean Buoy Project — Ocean Space Race 2024

A collaborative project developed for the **Ocean Space Race** competition hosted by NTNU in Trondheim, in partnership with **Runde Environmental Centre**. The goal was to design and deploy data-collecting ocean buoys to track current patterns and identify areas where plastic and other pollutants accumulate — enabling more targeted ocean cleanup efforts.

---

## Background

Plastic pollution in the ocean does not spread randomly — it follows current patterns and tends to accumulate in specific areas. By mapping these currents at multiple depths, we aimed to predict where surface debris would end up, and provide data that could inform cleanup operations and help protect the marine ecosystem.

---

## What We Built

Four fully functional ocean buoys, each consisting of:

- **3D printed hull** designed in Fusion 360 and printed on Creality CR10 printers
- **Epoxy coating** applied to the exterior for saltwater resistance
- **Physical sails mounted at varying depths** to capture current influence at different water levels
- **Raspberry Pi Pico** with the following sensors:
  - GPS — for tracking buoy position and drift over time
  - Temperature sensor — for water temperature profiling
- **Web dashboard** for real-time data visualisation, including an interactive map showing buoy positions and collected readings

---

## My Contributions

My primary responsibility was the physical build:

- Designed the buoy hull in **Fusion 360**, iterating on the model to balance buoyancy, sensor housing, and structural integrity
- Managed the full **3D print workflow** on Creality CR10 printers, including print settings and post-processing
- Applied **epoxy coating** to all four buoys to ensure saltwater durability
- Collaborated with the team on sensor integration, soldering, firmware, and the web dashboard

---

## Tech & Tools

| Area | Tools / Methods |
|---|---|
| CAD Design | Fusion 360 |
| 3D Printing | Creality CR10, FDM |
| Waterproofing | Epoxy lamination |
| Microcontroller | Raspberry Pi Pico |
| Firmware | MicroPython |
| Data visualisation | Web dashboard with interactive map |

---

## Repository Contents

```
├── cad/          Fusion 360 source file and exported STLs
├── firmware/     Raspberry Pi Pico sensor code
└── images/       Photos from design, print, and deployment
```

---

## Partners

- [NTNU — Norwegian University of Science and Technology](https://www.ntnu.no)
- [Runde Environmental Centre](https://rundemiljosenter.no](https://runde.no/)
