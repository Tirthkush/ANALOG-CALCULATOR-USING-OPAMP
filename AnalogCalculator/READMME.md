# Analog Calculator Using Op-Amp

This project implements an analog calculator using op-amp based building blocks.

## Structure
- `MAINCalculator.asc` → Main calculator schematic
- `Circuit Files/Adder` → Adder block
- `Circuit Files/Subtractor` → Subtractor block
- `Circuit Files/Log` → Log block
- `Circuit Files/Antilog` → Antilog block
- `Circuit Files/Integrator` → Integrator block
- `Circuit Files/Differentiator` → Differentiator block

## Usage
1. Clone or download this repository.
2. Ensure all sub‑circuit symbol (`.asy`) and schematic (`.asc`) files are present in their respective folders.
3. Open `AnalogCalculator.asc` in LTspice (or your simulator).
4. The main calculator schematic references the sub‑circuits, so they must remain in the same folder structure.

## Notes
- Each block has its own README describing its files.
- The calculator requires all blocks together to function correctly.

