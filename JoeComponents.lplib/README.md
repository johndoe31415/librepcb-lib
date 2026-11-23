# librepcb-components
This is a set of components and libraries which I have created for the
excellent open source EDA software [librePCB](https://github.com/librepcb/librepcb).

## LibrePCB Wishlist
Just some things I noticed while working with LibrePCB to improve usability.
Latest version I worked with is 0.2.0-unstable 0046d47387.

  * Placing of nets: when extending a net, the subnets may be in a straight
    line, but internally it still are two different pieces, making it awkward.
    Auto-merge nets that are in a straight line.
  * Placing of components on nets: There is by default no connection when
    copy/pasting components on a net, meaning you'll have to move the net,
    place the component, then append a net to actually connect to the components
    pin. Should auto-connect when overlapping a pin
  * Pins in symbols should have different forms, e.g., a CLK triangle or an
    inverted circle.
  * Pin text in symbols is always fixed to the pin itself. Should also have a
    configurable offset.
  * Symbol editor cannot resize rectangles, have to recreate them.
  * Symbol editor does not allow for overhead line, e.g, !CS where there's a
    line above !CS to indicate the signal is active-low.
  * Copy-paste mouse cursor sometimes is offset to the actual part, making it
    difficult to move part (have to put down and then move again).
  * Text cannot be placed on schematic.
  * Highlighting of a particular net throughout the whole schematic.
  * More keyboard shortcuts for everything (net, rotate, place component, etc.)
  * In footprint editor, ability to modify multiple parts at once (e.g., mark
    four pads and change size of all of them to 2.2mm x 0.8mm)

## License
CC0-1.0.
