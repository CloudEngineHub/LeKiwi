# 3D Printing
> **Estimated time:** ~34 hours

We provide ready-to-print STL files for the 3D-printed parts below. These can be printed with generic PLA filament on consumer-grade FDM printers. We tested on a [Bambu Lab P1S](https://us.store.bambulab.com/products/p1s) printer.

## Parts


| Item | Quantity | Notes | 
|:---|:---:|:---:|
| [Base plate Top](/3DPrintMeshes/base_plate_layer2.stl) | 1 | |
| [Base plate Bottom](/3DPrintMeshes/base_plate_layer1.stl) | 1 | |
| [Drive motor mount](/3DPrintMeshes/drive_motor_mount.stl) | 3 | |
| [Servo wheel hub](/3DPrintMeshes/servo_wheel_hub.stl) | 3 | <sup>[1](#footnote1)</sup> |
| [Servo controller mount](/3DPrintMeshes/servo_controller_mount.stl) | 1 | |
| [Battery mount](/3DPrintMeshes/battery_mount.stl) | 1 | |
| [RasPi case Top](/3DPrintMeshes/pi_case_top.stl) | 1 | <sup>[2](#footnote2)</sup> |
| [RasPi case Bottom](/3DPrintMeshes/pi_case_bottom.stl) | 1 | <sup>[2](#footnote2)</sup> |
| [Workspace camera mount](/3DPrintMeshes/base_camera_mount.stl) | 1 | |
| [Wrist camera mount](/3DPrintMeshes/wrist_camera_mount.stl) | 1 | |
| [Modified Follower Arm Base](/3DPrintMeshes/modified_base_arm.stl) | 1 | **Optional** |
| [Follower arm](https://github.com/TheRobotStudio/SO-ARM100) | 1 | |
| [Leader arm](https://github.com/TheRobotStudio/SO-ARM100) | 1 | |


> **Note**: Make sure to enable supports where specified!
<!-- > STL files are already oriented and ready-to-print.  -->


## Printing Instructions
Assuming you already have access to a 3D printer<sup>[3](#footnote3)</sup>, follow these steps to print all the parts above.

### 1. Setup Printer
1. Calibrate the printer and level beds according to printer-specific instructions
2. Clean the print bed
3. Load-in filament

### 2. Print the Parts
1. Upload STL file to printing/slicing software
2. Enable supports if specified and slice. We tested with the following settings:
    - Infill Density: 15%
    - Layer Height: 0.2 mm
    - Printing Speed: 150 mm/s
3. If needed, upload G-code (slice file) to printer and print

### 3. Take Down
1. Remove printed part(s) from printer
2. Clean print bed if needed
3. Remove any supports from printed parts

> For tutorials on how to assemble the robot, checkout the [Assembly](Assembly.md) page!

## Footnotes
<a name="footnote1">1</a>: Modified from VEX design

<a name="footnote2">2</a>: Taken from [Micro Center design](https://www.printables.com/model/605060-raspberry-pi-5-case-wpower-button-v2)

<a name="footnote3">3</a>: If not, we recommend [Bambu Lab](https://bambulab.com/en-us) or [Prusa](https://www.prusa3d.com/), or checkout this [list of brands](https://github.com/ad-si/awesome-3d-printing?tab=readme-ov-file#3d-printer-brands).
