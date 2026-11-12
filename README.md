# Aeolus-V1 IoT Development Board

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![KiCad](https://img.shields.io/badge/KiCad-FFFFFF?style=flat-square&logo=kicad&logoColor=blue)](https://www.kicad.org/)
[![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)](https://www.espressif.com/)

A custom-designed, compact ESP32-based IoT development board featuring integrated power management and sensor interfaces, complete with full schematic capture, layout, and manufacturing-ready fabrication files.
##  Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)

##  About the Project

This project contains the complete hardware design files for the Aeolus-V1. Designed as a compact Internet of Things (IoT) development platform, it leverages the ESP32 microcontroller and incorporates built-in power management alongside versatile sensor interfaces to streamline the prototyping of connected wireless devices.

### Tech Stack
*   **EDA Software:** KiCad (for schematic capture and PCB layout)
*   **Hardware Type:** ESP32 Microcontroller

##  Getting Started

Follow these instructions to view or modify the hardware design files locally.

### Prerequisites

*   [KiCad EDA](https://www.kicad.org/download/) to open the core project files.
*   A PDF viewer to read the exported schematics.
*   A Gerber viewer (if you only want to inspect the manufacturing layers).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedHassanExp/Aeolus-v1.git
2. Navigate to the project directory
   ```bash
   cd Aeolus-v1-main
3. Open `Aeolus-v1.kicad_pro` project file using KiCad.

## Repository Structure

The repository is organized to separate the editable design files from the static manufacturing outputs:

*   **Design Files:**
     The Hardware/ directory contains the core KiCad project files, including the schematic (Aeolus-v1.kicad_sch), the physical layout (Aeolus-v1.kicad_pcb), and a PDF export of the design (Aeolus-v1.pdf).
*    **Board Renders:**
      High-resolution 3D renders of the physical layout are available as Aeolus-V1-PCB Isometric.png and Aeolus-V1-PCB top.png.  
*    **Manufacturing Files (Manufacturing/):** 
      This directory contains everything a fabrication house like JLCPCB or PCBWay needs to manufacture and assemble the board:
      * **Aeolus-v1-gerber.rar:** The compressed Gerber layers and drill files for PCB fabrication.
      * **Aeolus-v1-BOM.csv:** The complete Bill of Materials for component sourcing and assembly.
      * **Aeolus-V1-bottom-pos.csv:** and **Aeolus-V1-top-pos.csv:** The centroid/pick-and-place data for automated SMD assembly.
