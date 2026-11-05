# Desk Lamp Controller PCB (Arduino Nano)

![KiCad](https://img.shields.io/badge/Made%20with-KiCad-blue?style=flat-square&logo=kicad)

A compact printed circuit board (PCB) design for a desk lamp controller, regulating 5V LEDs, powered by an Arduino Nano v3.x microcontroller board.

---

## 🛠 Technical Specifications

* **Main Controller:** Arduino Nano v3.x
* **Load/Output:** 5V LED regulation
* **Inputs/Controls:** Push buttons / Custom input logic
* **EDA Tool:** KiCad

---

## 📁 Repository Structure

```text
.
├── 3dAndOther/                             # 3D STEP model for mechanical CAD (.step)
├── spo2_stuffYT.pretty/                    # Custom project footprint library
├── A_controller_fo_a_desk lamp.kicad_pcb   # PCB layout and routing
├── A_controller_fo_a_desk lamp.kicad_pro   # Main KiCad project file
├── A_controller_fo_a_desk lamp.kicad_sch   # Schematic diagram
├── TrainingYTWSPO2Staff.kicad_sym          # Custom project symbol library
├── fp-lib-table                            # Footprint library table for custom dependencies
├── gerbers.zip                             # Ready-to-manufacture Gerber and Drill files
├── .gitignore                              # Git ignore rules for KiCad temp files
└── README.md                               # Project documentation

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Getting Started
1. Opening the Project in KiCad
To open this project with all custom symbols and footprints properly linked:

Clone this repository or download it as a ZIP archive.

Open the A_controller_fo_a_desk lamp.kicad_pro file in KiCad.

All custom symbols (TrainingYTWSPO2Staff.kicad_sym) and footprints (spo2_stuffYT.pretty) will load automatically via the local fp-lib-table.

2. Manufacturing (JLCPCB, PCBWay, etc.)
All necessary fabrication files are bundled in the gerbers.zip archive. Simply upload this ZIP file directly to your preferred PCB manufacturer's website.

3. Enclosure Design
The 3dAndOther/ directory contains a 3D model of the populated board in .step format. It is ready to be imported into SolidWorks, Fusion 360, or FreeCAD for designing a custom desk lamp enclosure.

👨‍💻 Author
Nazar Hryshko

Student at Wrocław University of Science and Technology (Politechnika Wrocławska)

📄 License
This project is distributed under the CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P). You are free to redistribute and modify this hardware design.
