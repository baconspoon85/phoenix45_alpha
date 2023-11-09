This directory contains a Lagacy Vault 45 compatible version of the Phoenix 45 Alpha PCB.
The schematic mostly the same except for a few layout options: The shift key options were removed. Make sure you have two 1.5u R4 caps. Several bottom row options were also removed and adjusted to avoid interference with mounting screws and posts. 2u spacebars were added with stabilizer support. It may not be possible to have stabilizers and the encoder option together in the same build configuration. There is a KLE in this directory showing just the bottom row options. No matrix positions have been added or removed. All other changes are to component positions and edge cuts, meaning the BOM and firmware for the Phoenix 45 version are compatible. You will need separate position files and gerbers generated from this project file. Those are included in the Fabrication directory. Additionally, since both boards are mounted via the plate, the custom plate is needed. There is a seperate project file containing the plate outline as a DXF file, as well as a KiCad project directory containing fabrication files for an FR4 plate.

Firmware was stripped down from original galvy fork:
https://github.com/galvy0/qmk_firmware/tree/galvy/keyboards/galvy/jd45_alpha

...to fit vial:
https://github.com/baconspoon85/vial-qmk/tree/vial/keyboards/baconspoon85/vault45_alpha

Vial and default QMK hex files are in the "Firmware" directory.