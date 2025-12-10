# About

TS14 – TROPIC01 Arduino Shield
A KiCad-based hardware project designed to interface the TROPIC01 device with standard Arduino development boards.

This shield allows easy integration of TROPIC01 into Arduino-based environments for development, testing, and prototyping.
It is intended for internal use and partner evaluation setups, following the Arduino mechanical and electrical interface.

# Project structure

* `*.kicad_pro` - KiCad project file
* `*.kicad_sch` - Schematic file
* `*.kicad_pcb` - PCB layout file
* `./out/` -  Generated Gerber files for PCB manufacturing
* `./bom/` - Bill of materials, including order codes and interactive BOM
* `./img/` - Images (e.g. PCB renders)
* `*_schematics.pdf` - Exported schematic diagrams (latest version)

# Manufacturing instructions:

## Assembly

IC1/CON1: Chose one variant, assembly IC1 or CON1 (not both on one board).
Chose `bom/bom_variant_*`.

Because Arduino boards use female sockets, the shield's connectors must be mounted on the top side 
to allow the pins to extend through to the bottom side for proper connection. \

There are no any special requirements for C and R components.
Where not specified the R tolerance is 5% and C 20%.

## PCB

* Number of cu layers: 2
* Board Thickness: 1.6
* Core: FR4
* Size: 58 x 53mm
* Mask: Blue
* Silkscreen: Yes (TOP only)
