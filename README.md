## ASI-Imaging-Rig
A 3D printable imaging rig for ZWO ASIAir based automated imaging system

<img src="Render 1.jpg"
     alt="Render"
     style="float: left; margin-right: 10px;" />
<img src="Render 2.jpg"
     alt="Render"
     style="float: left; margin-right: 10px;" />
<img src="Render 3.jpg"
     alt="Render"
     style="float: left; margin-right: 10px;" />

### A few notes:

- All the mocked up gear (Camera, Filter Wheel, Lens, etc.) in the main CAD file are dimensionally accurate.
- This setup works well for me, but note that my system is only 135mm Focal Length and over 5 arcseconds per pixel. There is likely a good amount of flex between the guidescope and the main camera with this system and if you go to 200mm or higher plate scale you may need to modify for better rigidity. 
- The belt is printable in TPU filament. It works surprisingly well with minimal stretching. Note that the belt and teeth here are not quite standard. YMMV

### Plans for the future:
- The biggest imporovement would be to move the EAF to underneath the camera lens and design a direct gearing system that doesn't use a belt. The belt works OK, but I need to set the backlash compensation to basically the maximum that the ZWO firmware allows. I think a direct gearing mechanism would work much better while also being more compact. This would also eliminate the need for the guidescope riser, which is a huge source of flexure. 


### License Stuff..
These files are distributed under the GNU license. You are free to use them for non-commercial use only. 
