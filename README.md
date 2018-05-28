# Microbit component library and footprint for Kicad

For use with [KiCad](http://kicad-pcb.org/), an open source PCB design/layout tool.

The [micro:bit](http://microbit.org/) has an 80 pin edge connector (not all pins are active). 

Sockets (right-angle) for the edge connector can be obtained from [Kitronik](https://www.kitronik.co.uk):

[Edge Connector Breakout Board for the BBC micro:bit](https://www.kitronik.co.uk/5601-edge-connector-breakout-board.html)

This library was written for the through-hole, angled version of the socket.

### Contents:

- [microbit-edge-connector-lib](./microbit-edge-connector-lib) - Schematic Component Library 
- [microbit-edge-connector.pretty](./microbit-edge-connector-lib.pretty) - PCB Footprint
- [Datasheet](./Datasheet) - Connector Datasheet

### How to use:

Schematic editor:

- Open dialog: Preferences -> Component Libraries
- "Add", browse to ```microbit-edge-connector-lib```

CvPcb (association of components->footprints)

- Open dialog: Preferences -> Footprint Libraries
- "Append with Wizard", browse to the directory ```microbit-edge-connector.pretty```

### License:

MIT
