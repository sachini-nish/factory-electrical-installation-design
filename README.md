# Industrial Facility Electrical Installation Design

## Overview
This repository contains the comprehensive electrical installation design report, calculations, and schematic drawings for a proposed factory building comprising a heavy-duty production floor and an administrative office area[cite: 1, 3, 6]. 

Completed as part of the **EE323 - Electrical Installation** module at the Department of Electrical Engineering, University of Moratuwa.

---

## Key Engineering Highlights

* **Load Estimation & Maximum Demand:** Calculated the aggregate three-phase and single-phase loads, factoring in diversity and phase balancing to determine a total factory demand of **249.31 A** and selecting a **250 A** incomer MCCB[cite: 16].
* **Transformer Sizing:** Recommended a **225 kVA / 480 V** transformer to safely support the calculated facility load profile[cite: 17].
* **Distribution Architecture:** Designed a Main Distribution Board (MDB) feeding two Sub-Distribution Boards (**SDB1** for production machinery/high-bays and **SDB2** for office zones/facilities) with dedicated phase allocations to minimize neutral currents[cite: 25, 27].
* **Cable & Protection Sizing:** Performed rigorous thermal, grouping, and voltage-drop (< 5%) calculations to select appropriate copper conductor cross-sections (ranging from $1 \text{ mm}^2$ lighting circuits to $95 \text{ mm}^2$ main feeders) and protective device ratings (Type B, C, and D MCBs/MCCBs)[cite: 16, 17, 24, 26].
* **Schematics & Layouts:** Developed detailed AutoCAD drawings mapping out radial/ring socket circuits, cable paths, and complete Electrical Single-Line Diagrams (SLDs)[cite: 8, 10, 27].

---

## System Specifications Summary

| Subsystem / Load | Operating Current / Rating | Protection Device | Cable Size (Phase / Neutral / PE) |
| :--- | :--- | :--- | :--- |
| **Machine 1 (MC1)** | 82.07 A (3-phase) | 100 A, 4-Pole, Type D | 35 mm² / 25 mm² / 4 mm² |
| **Machine 2 (MC2)** | 34.91 A (3-phase) | 63 A, 4-Pole, Type D | 10 mm² / 10 mm² / 4 mm² |
| **Machine 3 (MC3)** | 32.34 A (1-phase) | 40 A, 2-Pole, Type D | 6 mm² / 6 mm² / 4 mm² |
| **Machine 4 (MC4)** | 25.27 A (1-phase) | 30 A, 2-Pole, Type D | 4 mm² / 4 mm² / 4 mm² |
| **Water Pump** | 16.98 A (3-phase) | 20 A, 4-Pole, Type D | 4 mm² / 4 mm² / 4 mm² |
| **Air Conditioner** | 27.17 A (3-phase) | 30 A, 4-Pole, Type B | 6 mm² / 6 mm² / 4 mm² |

---

## Author
* **N.A.S.N. Jayasekara** (Index: 230276F) 
* Department of Electrical Engineering, University of Moratuwa
