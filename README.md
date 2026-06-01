# CAD Techniques in the Production of Electronic Modules - Academic Project (Quadraphonic Amplifier)

## Description
This repository contains the complete hardware design and development documentation for a high-fidelity 4-channel (quadraphonic) audio amplifier. Developed as an academic project, it covers the entire electronic design automation (EDA) workflow, ranging from initial circuit schematic capture to custom PCB layout optimization and production file generation.

## Key Features
* **Quadraphonic Audio Output:** Clean 4-channel signal amplification architecture designed for multi-directional audio setups.
* **Component Optimization:** Careful selection of electronic components based on thermal performance, operational stability, and signal-to-noise ratio.
* **Custom PCB Layout:** Multi-layer custom circuit board routing with dedicated trace width rules for power lines and noise reduction techniques for audio signals.

## Technical Specifications & Tools
* **ECAD / EDA Software:** Altium Designer (or specify software used, e.g., OrCAD / KiCad)
* **Design Elements:** Schematic Design (.SchDoc), PCB Layout Routing (.PcbDoc), Component Libraries, and Bill of Materials (BOM).
* **Core Concepts:** Signal integrity, thermal management, ground planes configuration, and multi-channel hardware synchronization.

---

## How to View and Use the Project Files

Since this is a hardware development project, you will need compatible Electronic Computer-Aided Design (ECAD) software to review or modify the source files.

### Option 1: Opening the Native Project Files
1. Clone or download this repository to your local machine.
2. Open your ECAD tool (e.g., **Altium Designer**).
3. Navigate to **File > Open > Project** and select the main project file (`.PrjPcb` or equivalent).
4. From the project tree, you can explore the schematic captures (`.SchDoc`) and the multi-layer layout design (`.PcbDoc`).

### Option 2: Visualizing Production & Output Files
If you do not have ECAD software installed, you can review the design implementation through the generated outputs provided in the repository:
* **`Outputs/` or `Documentation/` Folder:** Look inside for fully generated schematic diagrams and layout designs exported in standard **PDF** format.
* **Manufacturing Data:** Check the **Gerber Files** and **NC Drill** data sets inside the fabrication folders, which are ready to be uploaded straight to standard web-based PCB viewers (such as Gerber Viewer tools).
