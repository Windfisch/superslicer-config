# My SuperSlicer configuration

This repo contains my personal SuperSlicer configuration for a Creality Ender 5 printer. (Which is comparable to the Ender 3 in most aspects)

The following modifications have been made from a stock Ender 5 printer:

- The old Melzi mainboard was upgraded to a BTT E3 Mini (with quieter stepper drivers)
- Replaced firmware with Klipper
- Installed a BLTouch / 3DTouch probe
- Added a second extruder motor and a filament Y adapter. The second motor is driven by the old melzi board (klipper supports using multiple boards on one printer)

The printer is networked, but I left out the `physical_printers` directory because it contains secrets such as API keys.
