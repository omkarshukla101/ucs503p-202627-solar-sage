# 📐 Diagrams

This section contains all system design diagrams for the Solar Sage AI project.

## Use Case Diagram

The use case diagram shows the interactions between actors (Operator, Drone, System) and the core functionalities of the Solar Sage AI platform.

![Use Case Diagram](use_case_diagram.png){ width="100%" loading=lazy }

---

## Data Flow Diagrams

### Level 0 — Context Diagram

The context-level DFD shows the system as a single process with external entities (Operator, Drone, Solar Panels) and the data flows between them.

![DFD Level 0](dfd%20diagrams/dfd_level0.png){ width="100%" loading=lazy }

---

### Level 1 — Subsystem Diagram

The Level 1 DFD breaks the system into its major subsystems: Image Processing, Decision Engine, Actuation Controller, and Dashboard.

![DFD Level 1](dfd%20diagrams/dfd_level1.png){ width="100%" loading=lazy }

---

### Level 2 — Detailed Diagram

The Level 2 DFD provides a granular view of internal data flows within each subsystem, including the multi-agent decision pipeline.

![DFD Level 2](dfd%20diagrams/dfd_level2.png){ width="100%" loading=lazy }
