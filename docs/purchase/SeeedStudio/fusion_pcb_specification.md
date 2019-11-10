# Fusion PCB Specification

## PCB Gerber

The Gerber format is an open 2D binary vector image file format.
It is the standard file used by printed circuit board (PCB) industry software to describe
the printed circuit board images: copper layers, solder mask, legend, etc.

Gerber files should be inside a .rar or.zip archive with standard file extensions:

| Extension | Layer |
|-----------|-------|
| pcbname.GTL | Top Copper |
| pcbname.GTS | Top Soldermask |
| pcbname.GTO | Top Silkscreen |
| pcbname.GBL | Bottom copper |
| pcbname.GBS | Bottom Soldermask |
| pcbname.GBO | Bottom Silkscreen |
| pcbname.TXT | Drills |
| pcbname.GML/GKO | Board Outline |
| pcbname.GL2 | Inner Layer2 (for ≥4 layer) |
| pcbname.GL3 | Inner Layer3 (for ≥4 layer) |

Notes:

1. Gerber file must be the RS-274x format.

2. Drill file (PCBname.TXT) should be Excellon format.

3. Gerber file and Drill file (PCB name.TXT) must be put in the same folder.

4. Board outline is required.
