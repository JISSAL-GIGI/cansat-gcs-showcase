# Ground Control System (GCS) — Public Showcase

> 🚀 **This is a public showcase repository.**  
>  
> The **complete source code** for this project is maintained in a **private repository**  
> and is available **on request for evaluation purposes only**.

---

## Overview

**Ground Control System (GCS)** is a PyQt5-based desktop application designed to monitor and control
dual-drone / CanSat-style missions.

The system focuses on **real-time telemetry visualization**, **mission awareness**, and
**operator-friendly UI design**.

This repository showcases the **architecture, features, and overall system complexity**
without exposing the full implementation.

---

## Key Features

- **Dual-vehicle telemetry handling**
- **Live map visualization** (GPS positions, paths, detections)
- **Mission geofencing** using polygon overlays
- **System health monitoring**
  - Battery
  - Communication link
  - Autonomy state
  - Payload status
- **Real-time plots and gauges**
- **Mission event logging**
- **Modular, extensible architecture**

---

## Architecture Overview

The GCS is structured around clearly separated components:

- **UI Layer**
  - PyQt5-based dashboard
  - Real-time widgets and indicators

- **Telemetry Layer**
  - Parsing and validation of incoming data
  - State management for multiple vehicles

- **Mapping Layer**
  - GPS visualization
  - Path tracing and overlays

- **Data Layer**
  - Local mission logging
  - Structured telemetry records

📌 See the included **architecture diagram** for a high-level view of the system design.

---

## Repository Contents

This showcase repository intentionally contains **only non-sensitive material**:

- `gcs_interface_stub.py`  
  → Structural stub illustrating application layout (no implementation logic)

- `gcs-architecture-diagram.svg`  
  → High-level system architecture diagram

- Screenshots / images  
  → UI and visualization examples

❌ **Not included**:
- Full application logic
- Algorithms
- Real telemetry handling code
- Databases with real mission data

---

## Technology Stack

- **Python**
- **PyQt5** (desktop UI)
- **Mapping / visualization tools**
- **SQLite** (used in the full implementation)
- **Event-driven, modular design**

---

## Intended Use

This repository is intended for:

- Recruiters
- Reviewers
- Academic / project evaluation
- Portfolio demonstration

It is **not intended to be runnable** as-is.

---

## Full Implementation (Private Repository)

This public repository represents a **showcase version** of the NIDAR Ground Control System.

The **complete, fully functional implementation** — including:
- real-time telemetry handling
- full UI logic
- mission execution workflows
- data storage and processing
- system integration code

is maintained in a **separate private repository**.

The private repository exists to:
- protect original intellectual property
- comply with academic / competition constraints
- prevent misuse of mission-critical software

🔒 **Full source code is available on request** for:
- recruiters
- academic reviewers
- collaborators

Please contact the author if access is required for evaluation purposes.

---

## License

Copyright © 2025 Jissal.  
All rights reserved.

This repository is provided **for viewing and evaluation purposes only**.  
No permission is granted to use, copy, modify, or redistribute the software
or its concepts without explicit written permission.

---

## Author

**Jissal Gigi**  
Ground Control Systems • Drone Software • CanSat Projects
