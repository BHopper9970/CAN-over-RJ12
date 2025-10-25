This repo hosts KiCAD symbols and footprints for several FRC electrical devices,
including:

- RoboRIO
- Spark MAX
- Talon FXS
- Talon SRX
- Thrifty Nova

These libraries can be used to create custom printed circuit boards that
interface with off-the-shelf FRC electrical components.

# Using the Libraries with an Existing KiCAD Project

1. Download this repository and place its contents into your KiCAD project,
   inside a new folder named `FRC`.

2. Import the schematic symbols by going to Preferences → Manage Symbol
   Libraries, and importing FRC.kicad_sym as a new project-specific library. If
   you got step 1 right, you can set the library path to
   `${KIPRJMOD}/FRC/FRC.kicad_sym`

![](/screenshots/symbol-lib.png)

3. Import the footprints by going to Preferences → Manage Footprint Libraries,
   and importing FRC.pretty as a new project-specific footprint library. If you
   got step 1 right, you can set the library path to
   `${KIPRJMOD}/FRC/FRC.pretty`

![](/screenshots/footprint-lib.png)

# Examples

![](/screenshots/spark-max-board.png)

![](/screenshots/qscrot-250515-110658.png)

![](/screenshots/qscrot-250511-102100.png)
