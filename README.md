# Control Universal 4-Slot DIN41612 Backplane
A 4 slot DIN 41612 backplane for use with the EuroBEEB and compatible cards

- Designed in KiCAD, in addition to giving 4x DIN connectors on a 1" (5HP spacing) allowing mounting in a 24HP enclosure with 2HP blanking plates at either end.
- Board has pads for power supply inputs (actually only +5V and GND are needed for a standard EuroBEEB) and test points for access to all Data, Control and Address lines.  These TPs are labelled on the under/back side for easy access when this is mounted in a rack.  The TPs are on a 0.1" pitch, so headers can be used if desired.
- Board is <100x100mm so should be low-cost fabrication.

Note that this isn't strictly a 'backplane' in the DIN enclosure sense.  Rather than mounting the PCB to 'backplane' fixtures in an enclosure, the PCB should simply be soldered across the row of vertical DIN female connectors and then the connectors mounted to specific connector mounting rails.  Please take this into consideration if ordering enclosure parts from Verotec or your preferred enclosure supplier.
