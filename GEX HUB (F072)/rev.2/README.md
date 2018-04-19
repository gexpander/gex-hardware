GEX F072 hub prototype board, rev.2
============================

This revision fixes some issues with the first version.

- Connectors now all have both 3V3 and 5V
- BOOT jumper was moved to the A connector and inverted, so putting on a jumper to short it with 3V3 enables bootloader
- Added the NRST pin to the A connector
- Removed the debug connector footprint (was wrong before anyway, and all pins are in the connectors now)
- Added a position for a reset button on the backside
- Added some useful info to the backside silk layer

This revision should be compatible with the previous HUB firmware without any changes.
