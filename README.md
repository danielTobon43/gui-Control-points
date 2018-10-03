# gui-Control-points
Gui for select image pixel reference for iTree3DMap. This program uses the control point registration GUI of OpenMVG as base.

----------------

## GUI
<img src="./example/control.png" align="center" height="500" width="640"><br>

## Dependencies
* OpenMVG
* Cereal
* runit


## Compile
     cmake ../
     make


## Test
    usage: ./control_point_Reg <sfm data bin/xml> <output dir>
