# Interfaces-for-WobbleX-integration

### Printers currently supported:
**Voron**
   - [Trident](https://github.com/MirageC79/Interfaces-for-WobbleX-integration/tree/main/Voron/Trident)  
   - V0 ............... *rear panel impacted, investigating feasibility and demand*  
<details><summary> Coming Soon: </summary>
<p>  

**Creality**
   - Ender 3 .......... *coming soon...*  

**RatRig**
   - V-Core 3 ........ *coming soon...*  
   - V-Minion ........ *coming soon...*  

**VzBoT**
   - VZ235 ........... *coming soon...*  
   - VZ330 ........... *coming soon...*  
</p>
</details>
<br>

## What is WobbleX ?
The WobbleX isolators were born after spending a lot of efforts in creating a strong and reliable triple Z axis for self levelling with multi-axis printing provisions.
Because building a DIY 3D printer can induce a lot variability into the end result, we needed a way to limit the impact of:
- Components sources and origin
- Printed parts tolerances
- Assembly process
- User modifications 
- etc...

## How does it work?
This metallic version of the Wobble Rings from EvoMoto will compensate for screw wobbling AND nut tilting.  This 4 axis compensation ensures that the XY position of the bed will not be changed even if the screw is trying to.  It will also prevent the Z distance from being affected by a curved screw axis which would tilt the nut.

Each WobbleX Isolator is composed of an aluminum cross sandwiched between 4 Ball bearings and roller pins. The ball bearings will self center and retain themselves on the assembly using disc magnets.

One interface disc will allow the WobbleX to slide and pivot on the Screw Nut while the other interface disc will match the bed mount.  
![screen-gif](./Pictures/WobbleX_Gif12fps.gif)

## How can you integrate this on your printer?
In this repository you will find CADs and STLs that can be adapted to various 3D printers in order to benefit from the best Z wobble management system out there.

Buy WobbleX on Aliexpress Mellow 3D Official Store: https://s.click.aliexpress.com/e/_DDdeMyP

Preview of HevORT ZR2.6 Z axis integrating WS12 WobbleX:
[![Video](/Pictures/YT_ZR2.6_Preview.jpg)](https://www.youtube.com/watch?v=mLhklORNFBQ)

## Credits:
- EvoMoto for the awesome Idea
- Mellow 3D for materializing this idea
- HevORT Community for the support


