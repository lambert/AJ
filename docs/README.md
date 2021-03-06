# Parallax/Scenix SX28AC/DP Board

![Parallax logo](Parallax_Inc_logo.png)

Author: Bert Timmerman

Organisation: Me Organized ??

Date: 20181117

[License information](../LICENSE.md)

![CC-BY-SA logo](CC-BY-SA.png)

## Specification.

### Description.

...

### Functions.

ID  | Description               |
----|---------------------------|
.   | .                         |

### Modes of operation.

ID  | Description                                  |
----|----------------------------------------------|
.   | .                                            |

### Inputs.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
.    | .                                    | .        |

### Controls.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
.    | .                                    | .        |

### Outputs.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
.    | .                                    | .        |

### Indicators.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
.    | .                                    | .        |

### Power supply.

### Protection and fail-safes.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
F1   | Littlefuse	1206L025YR It = 500 mA    | Top      |

### Replaceable parts.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
U1   | SX28AC/DP-G                          | Top      |

### Connectors.

ID   | Description                          | Location |
-----|--------------------------------------|----------|
.    | .                                    | .        |

### Physical dimensions and form factors.

Description           | Dimensions                      |
----------------------|---------------------------------|
.                     | .                               |

## Basic Design.

### Schematic entry.

#### Schematic files.

Schematics are prepared with gschem version 1.6.2.20110115, a schematic
entry application part of the GPL'd EDA suite of tools "gschem and
friends" (geda-gaf).

Attributes for symbols are managed either from within gschem, or with
gattrib, the attribute editing application from the same suite of tools.

Schematic files can be found here: [link to schematic files](../ecad/gschem/)

#### Design Rule Check (DRC).

After schematic entry a check is done by running gnetlist with the
"geda" backend as to visually check for missing reference designators,
missing device values, shorted nets and not connected pins on symbols.

The gnetlist backend "geda" will list components, renamed nets, and
resulting connectivity of nets in a structured list.

DRC files can be found here: [link to DRC files](../ecad/gschem/DRC/)

#### Bill Of materials (BOM).

Preliminary BOMs are generated from schematics by running gnetlist with the "bom" backend.

BOM files can be found here: [link to BOM files](../ecad/gschem/BOM)

### Calculations.

...

### Simulations.

#### gnucap simulations.

##### Schematic files (graphic representation only).

Schematic representations of circuits for simulation were prepared with
gschem.

Schematic files can be found here: [link to schematic files](../ecad/gschem/)

##### Input files.

Various circuit files (*.ckt) may contain subcircuits and calls to
models included in the gnucap software package.

Input files can be found here: [link to schematic files](../ecad/gnucap/)

##### Data files.

For every simulation a single data file was generated by gnucap by means
of a Makefile rule.

##### Data processing files.

For every required output graph a gnuplot post processing job was done.

##### Output files.

Output files are typically Portable Network Graphic files (*.png).

Default size of graphs is 640 by 480 pixels.

Detailed graphs were made where required.

##### Discussion of results.

All input files were processed with gnucap version 0.35 and all data
files were processed with gnuplot version 4.2 patchlevel 6.

#### ktechlab simulations.

...

### Breadboard prototyping.

...

## Design For Manufacturing.

### Schematic entry.

#### Schematic files.

Schematics are prepared with gschem version 1.6.2.20110115, a schematic
entry application part of the GPL'd EDA suite of tools "gschem and
friends" (geda-gaf).

Attributes for symbols are managed either from within gschem, or with
gattrib, the attribute editing application from the same suite of tools.

Schematic files can be found here: [link to schematic files](../ecad/gschem/)

#### Design Rule Check (DRC).

After schematic entry a check is done by running gnetlist with the
"geda" backend as to visually check for missing reference designators,
missing device values, shorted nets and not connected pins on symbols.

The gnetlist backend "geda" will list components, renamed nets, and
resulting connectivity of nets in a structured list.

DRC files can be found here: [link to DRC files](../ecad/gschem/DRC/)

#### Netlists.

Connectivity for the pcb layout editor is generated with gnetlist from
the schematics.

Pin renaming for the pcb layout editor is generated with gnetlist from
the schematics.

Netlist files can be found here: [link to DRC files](../ecad/gschem/pcb_netlist/)

#### Bill Of Materials.

...

### Printed Circuit Board design.

#### Layout files.

[link to layout files](../ecad/pcb/)

#### Visual Testing files.

[link to eyecandy](../ecad/pcb/eyecandy/)

#### Design Rules Check.

...

#### Gerber files.

...

#### Bill Of Materials.

[link to BOM](../ecad/pcb/bom/README.md)

#### Pick-and-Place files.

[link to Pick and Place files](../ecad/pcb/pnp/README.md)

#### IPC-D-356 netlist files.

[link to IPC-D-356 netlist files](../ecad/pcb/test/README.md)

## Manufacturing.

### Printed Circuit Boards.

#### Quotations.

[link to SeeedStudio fabrication services](purchase/SeeedStudio/fusion_pcb_specification.md)

[link to OSH Park fabrication services](purchase/OSH_Park/fabrication_services.md)

#### SeeedStudio.

[link to SeeedStudio directory](purchase/SeeedStudio/)

#### OSH Park.

[link to OSH Park directory](purchase/OSH_Park/)

#### QA/QC Testing.

...

### Printed Circuit Assembly.

#### Quotations.

...

#### Purchase Orders.

...

#### QA/QC Testing.

...

## Testing and Test Records.

...


