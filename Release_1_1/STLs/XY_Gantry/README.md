XY Gantry Options
=================

## Linear Rail Instructions

### Running RobotDigg or LDO Rails? ###

If you are using RobotDigg or LDO rails, you should to use the STLs in the `for_6.0mm_thick_rails` folder for the tensioner spacer and rail mounts, as these rails are 0.5mm thinner.

### Spacer Sizing Tips ###

- Before printing the tensioner spacer, try slicing the main toolhead plate (with whatever settings you will/did use to print it) and check the distance from the bottom to the surface that sits underneath the upside-down rail. The model is 6.5mm thick, but depending on your slicer and its settings, the part may be sliced slightly thicker or thinner.
- Try slicing the tensioner spacer and check it's sliced height from top to bottom.
    - For 6.5mm (normal) rails, the spacer height should be 13.5mm thicker than the toolhead plate measurement.
    - For 6.0mm (Robotdigg) rails, the spacer height should be 14.0mm thicker than the toolhead plate measurement
    - For example, if the toolhead plate slices at 6.6mm thick and you're using Robotdigg rails, size the spacers so that they are sliced 20.6mm tall.
- Scale the tensioner spacer (in the z axis only) if it is the wrong size when sliced.
- For best alignment of the final assembly, you may choose to physically measure the toolhead plate after printing it, then print the spacers with an extra layer and carefully sand them down to final dimension. Be sure to keep the top and bottom surfaces flat and parallel when sanding.

## XY Shim Placement

The number of shims to place in the x- and y-axis drive stacks depends on the overall height of your idlers (either 13mm or 14mm). The eDrawing shows xy corner drives with 14mm idlers. The table below shows the shim height needed at each location:

|                   | 13mm Idlers                   | 14mm Idlers                   |
| ---               | ---                           | ---                           |
| Idler on top      | ![](Images/13mm_lower.png)    | ![](Images/14mm_lower.png)    |
| Idler on bottom   | ![](Images/13mm_upper.png)    | ![](Images/14mm_upper.png)    |