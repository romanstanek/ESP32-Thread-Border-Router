# ESP32-Thread-Border-Router

# ESP32-S3-POE-ETH Enclosure (FreeCAD Macro)

A parametric FreeCAD macro that generates a 3D-printable enclosure for:
- Waveshare ESP32-S3-POE-ETH (main board)
- Optional Seeed XIAO ESP32-C6 (held by corner tabs)

Features:
- Screw-down or snap-fit lid
- RJ45 cutout
- Optional vents (two rows along base sidewalls)
- Parametric standoffs, wall thickness, clearances

## Usage
1. Open FreeCAD (0.20+).
2. Go to **Macro → Macros → Create** and paste the code from `ESP32S3_POE_ETH_Enclosure.py`.
3. Execute to generate the model.
4. Export `Base` and `Lid` as STL for 3D printing.

## Parameters
See the top of the `.py` file for all adjustable parameters (wall thickness, vent spacing, XIAO enable, etc.).

## License
MIT
