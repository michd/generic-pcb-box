# Generic PCB box

I design most of my PCBs to have mounting holes in them, in a square shape.

This repository provides a parameterised OpenSCAD design to accomodate such PCBs.

It comes with two parts: the bottom of the box and, the top of the box. The height of these is configurable, as well as a bunch of other things.

If you want to use this, you will probably (almost certainly) need to adapt the design to add holes for connectors, LEDs, switches, or what have you.

I suggest going about that by surrounding `bottom_case()` in a `difference() {}` block, and specifying your holes under `bottom_case()`. Similar for holes in `top_box()`

The STL file here is provided purely to show what a resulting box might look like.
