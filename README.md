# apple--atx--conversion


# Mac Pro A1186 to ATX Conversion

![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Phase](https://img.shields.io/badge/phase-planning-blue)

## Overview

Engineering project converting a Mac Pro A1186 (2006-2008) tower into a high-performance ATX gaming/workstation build. This project emphasizes thermal analysis, design validation, and professional documentation to demonstrate end-to-end product development capabilities.

**Primary Engineering Challenge:** The Mac Pro A1186 was designed for Apple's specific thermal solution. Adapting it for modern high-TDP components (360W+ combined heat load) requires CFD analysis and validation to prevent thermal throttling.

## Target Specifications

- **CPU:** AMD Ryzen 7 7800X3D (120W TDP)
- **GPU:** NVIDIA RTX 5070 (~220W TDP)
- **Form Factor:** ATX motherboard
- **Thermal Goal:** No throttling under sustained load
- **Acoustic Goal:** <45 dBA at 1m during gaming

## Project Scope

This project demonstrates three core engineering competencies:

1. **Mechanical Design & Fabrication**
   - Precise CAD modeling in TinkerCAD
   - Custom bracket design and fabrication
   - Case modification with dimensional tolerances

2. **Thermal Analysis & Validation**
   - CFD simulation to optimize airflow
   - Fan placement analysis
   - Real-world validation against predictions

3. **Technical Documentation**
   - Complete design process documentation
   - Problem-solving logs
   - Replicable build instructions

## Key Metrics (Target)

| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| CPU Temp (Load) | <85°C | TBD | ⏳ Pending |
| GPU Temp (Load) | <80°C | TBD | ⏳ Pending |
| Noise Level (Gaming) | <45 dBA | TBD | ⏳ Pending |
| Total Cost | <$1,200 | TBD | ⏳ Pending |

## Documentation

- [Design Requirements](docs/00-design-requirements.md) - Project specifications and success criteria

## Project Timeline

- **Phase 1:** Planning & Measurement ← *Current Phase*
- **Phase 2:** Thermal Analysis
- **Phase 3:** Design & Fabrication
- **Phase 4:** Assembly
- **Phase 5:** Validation & Testing
- **Phase 6:** Final Documentation

## Portfolio

Full 3D model progression and high-resolution photography available on my portfolio website: [link TBD]

## Tools & Technologies

- **CAD:** TinkerCAD
- **Thermal Analysis:** SimScale / OpenFOAM (TBD)
- **Fabrication:** Drill press, Dremel, hand tools
- **Validation:** HWiNFO64, SPL meter

---

*This project is part of my mechanical engineering portfolio demonstrating product development lifecycle skills including requirements definition, thermal analysis, design iteration, and validation testing.*
```

---

## Now: CAD Measurement Checklist

Here's what you need to measure from your Mac Pro A1186 case to create an accurate CAD model:

### Critical Dimensions Checklist

Save this as `cad/measurements/case-dimensions.txt` when you create the folder:
```
MAC PRO A1186 MEASUREMENT LOG
Date: [Fill in when measuring]
Tools Used: [e.g., digital calipers, tape measure, ruler]

================================================================================
EXTERIOR DIMENSIONS (for reference)
================================================================================
Overall Height (with feet):     _____ inches / _____ mm
Overall Width (with handles):   _____ inches / _____ mm  
Overall Depth (with handles):   _____ inches / _____ mm

================================================================================
INTERIOR USABLE SPACE (CRITICAL)
================================================================================
Internal Height:    16.0 inches / 406 mm (verified: Y/N)
Internal Width:      7.5 inches / 191 mm (verified: Y/N)
Internal Depth:     18.0 inches / 457 mm (verified: Y/N)

NOTES: Measure from inside wall to inside wall, excluding any ribs/protrusions

================================================================================
MOTHERBOARD MOUNTING AREA
================================================================================
[] Back wall to front interior face:        _____ inches / _____ mm
[] Floor to ceiling:                        _____ inches / _____ mm
[] Side to side clearance:                  _____ inches / _____ mm

[] ATX board dimensions (for reference): 12" × 9.6" (305mm × 244mm)
[] Will ATX board fit flat against back wall? (Y/N): _____

[] Standoff mounting points available? (Y/N): _____
   If NO: Plan to drill/tap new holes

================================================================================
PSU MOUNTING AREA
================================================================================
[] Preferred PSU location: [ ] Top-rear  [ ] Bottom-rear  [ ] Other: _____

[] Available depth for PSU:                 _____ inches / _____ mm
[] Available width for PSU:                 _____ inches / _____ mm
[] Available height for PSU:                _____ inches / _____ mm

[] Standard ATX PSU dimensions (reference): 5.9" × 3.4" × (5.5"-7")
[] PSU clearance adequate? (Y/N): _____

================================================================================
GPU CLEARANCE
================================================================================
[] Maximum GPU length possible:             _____ inches / _____ mm
   (Measure from back I/O area to nearest obstruction)

[] Height clearance above motherboard:      _____ inches / _____ mm
[] Width clearance (for thick cards):       _____ inches / _____ mm

[] Typical RTX 5070 length (estimate): 10-12 inches (254-305mm)
[] GPU will fit? (Y/N): _____

================================================================================
DRIVE MOUNTING
================================================================================
[] 2.5" SSD mounting location: _____________________
   Dimensions available:       _____ × _____ inches

[] 3.5" HDD mounting location: _____________________
   Dimensions available:       _____ × _____ inches

================================================================================
COOLING / VENTILATION
================================================================================
FRONT PANEL:
[] Existing vent holes/openings:            _____ × _____ inches
[] Can be enlarged? (Y/N): _____
[] Potential fan mounting locations:
   - Location 1: _____ mm fan possible (80/120/140mm?)
   - Location 2: _____ mm fan possible

REAR PANEL:
[] Existing vent holes/openings:            _____ × _____ inches
[] Standard 120mm fan mount available? (Y/N): _____
[] If no, can one be cut? (Y/N): _____

TOP PANEL:
[] Ventilation present? (Y/N): _____
[] Could fans be added? (Y/N): _____

SIDE PANELS:
[] Ventilation present? (Y/N): _____
[] Could vents be added without ruining aesthetic? (Y/N): _____

================================================================================
OBSTRUCTIONS / FEATURES
================================================================================
List any internal features that might interfere with components:

[] Original drive cage location:     _____________________ (keep/remove?)
[] Original fan shrouds:             _____________________ (keep/remove?)
[] Internal structural ribs:         _____________________ (location)
[] Cable management channels:        _____________________ (usable?)
[] Other: ________________________________

================================================================================
MATERIAL THICKNESS
================================================================================
[] Wall thickness (for drilling planning):  _____ inches / _____ mm
[] Material type: [ ] Aluminum  [ ] Steel  [ ] Other: _____

================================================================================
PHOTOS TAKEN
================================================================================
[] Overall exterior (6 sides)
[] Interior empty case (multiple angles)
[] Close-up of mounting areas
[] Close-up of ventilation areas
[] Any problem areas identified

================================================================================
NOTES / CONCERNS
================================================================================
[Space for observations, tight clearances, potential issues identified]






================================================================================
