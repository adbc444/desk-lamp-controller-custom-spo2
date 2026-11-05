\# Desk Lamp PWM Controller PCB







A compact printed circuit board (PCB) design for a desk lamp controller featuring PWM brightness regulation for 5V LED strips, powered by an Arduino Nano v3.x microcontroller.



\---



\## 🛠 Technical Specifications



\* \*\*Microcontroller:\*\* Microchip Arduino Nano v3.x (SOIC-8 / DIP-8)

\* \*\*Functionality:\*\* PWM control of a power MOSFET for 5V LED load regulation

\* \*\*Inputs/Controls:\*\* Potentiometer and/or monostable push button

\* \*\*EDA Tool:\*\* KiCad



\---



\## 📁 Repository Structure



```text

.

├── 3dAndOther/                             # 3D STEP model for mechanical CAD (.step)

├── spo2\_stuffYT.pretty/                    # Custom project footprint library

├── A\_controller\_fo\_a\_desk lamp.kicad\_pcb   # PCB layout and routing

├── A\_controller\_fo\_a\_desk lamp.kicad\_pro   # Main KiCad project file

├── A\_controller\_fo\_a\_desk lamp.kicad\_sch   # Schematic diagram

├── TrainingYTWSPO2Staff.kicad\_sym          # Custom project symbol library

├── fp-lib-table                            # Footprint library table for custom dependencies

├── gerbers.zip                             # Ready-to-manufacture Gerber and Drill files

├── .gitignore                              # Git ignore rules for KiCad temp files

└── README.md                               # Project documentation

