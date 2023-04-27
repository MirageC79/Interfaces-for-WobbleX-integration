# Prusa i3 MK3

These parts will allow installation of WobbleX Isolators WS8 on a Prusa i3 MK3.

I own self-sourced i3, not an Original Prusa i3, therefore any feedback on the parts will be greatly appreciated.

Installation requires the carriage nuts to be installed on the bottom of the x-end parts, whereas the Original Prusa i3 locates them at the top of the parts. There are 2 replacement printed parts that must be printed, they are simply the original parts mirrored on the Y axis with `mirror([0, 1, 0])` added to the OpenSCAD source file.

## BOM
Bill of Material required to accomplish this modification:
|  Qty    |   Description      |    Link  |
|  :---:  |--------------------|----------|
|  2      | WobbleX WS8 kit for 8mm lead screw from Mellow 3D<br>Kit Includes:<br>  Qty8 - 3mm diam X 8mm longs pins<br>  Qty4 - 4mm ball screws<br>  Qty1 - WobbleX Assembly (Magnets and pins loaded)  | https://s.click.aliexpress.com/e/_DFcwPoH |
|  4      | 8mm T-Nut Adapter | [wobblex-printed-adapter-24mm.stl](/Prusa_i3/MK3/wobblex-printed-adapter-24mm.stl) |
|  1      | Mirrored x-end-idler | [x-end-idler.stl](/Prusa_i3/MK3/x-end-idler.stl) |
|  1      | Mirrored x-end-motor | [x-end-motor.stl](/Prusa_i3/MK3/x-end-motor.stl) |
|  8      | Brass inserts for M3 screw<br>Min. OD: 4.2mm<br>Max length: 6mm | AliExpress, Amazon, etc... (like https://a.co/d/g6m5mwx) |
|  8      | M3X16 Screws | AliExpress, Amazon, etc... |

## STL files:  
[GitHub Directory](https://github.com/MirageC79/Interfaces-for-WobbleX-integration/tree/main/Prusa_i3/MK3)
<br> 
<br>


![img](/Prusa_i3/MK3/x-end-idler_installation.png)
<br>
![img](/Prusa_i3/MK3/x-end-motor_installation.png)
<br>
![img](/Prusa_i3/MK3/x-end-motor_under_view.png)
<br>
