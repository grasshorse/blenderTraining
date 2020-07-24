# Blender Beginner Tutorial [Blender Guru](https://www.youtube.com/playlist?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U)

## [Part 7 - Level 1](https://www.youtube.com/watch?v=jmSgsaNSQ6s&list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&index=7) Materials


## [Part 6 - Level 1](https://www.youtube.com/watch?v=jmSgsaNSQ6s&list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&index=6) Rendering


## [Part 5 - Level 1](https://www.youtube.com/watch?v=jmSgsaNSQ6s&list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&index=5) Sculpting
1. Make a copy of object before modification [TC 1:21](https://youtu.be/6OTX3ZdYvEA?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=81)
  - Select both Icing and Donut 
  - Shift D (Duplicate)
  - Type M -> Move to Collection -> New Collection (name: Archive)
  - Uncheck Archive in Scene Collection to hide
2. Sculpt Donut [TC 2:29](https://youtu.be/6OTX3ZdYvEA?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=149)
  - Select Donut
  - Add Modifier -> Apply
  - Should get a new mesh
  - Back to Object Mode (Tab)
  - Click Sculpting (Middle Top Menu bar)
  - Type F (change size of brush)
  - Right click on Scupt -> Click Header -> Show Tool Settings
    - so all sculpt tools show up [TC 3:19](https://youtu.be/6OTX3ZdYvEA?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=199)
  - Turn off X symetry (so bush is cursor only)
  - Left mouse to pull out
  - Cntrl Left Mouse to push

## [Part 4 - Level 1](https://www.youtube.com/watch?v=jmSgsaNSQ6s&list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&index=5) Make Icing drip
1. Click on Icing Object in Object Mode
2. Turn off Modifier view [TC 0:12](https://youtu.be/jmSgsaNSQ6s?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=12)
  - On Icing -> Click Wrench
  - In Modifier Unselect the box to turn off modifier in edit mode
  - In edit mode you should only see the mesh
3. Subdivide Mesh [TC 1:15](https://youtu.be/jmSgsaNSQ6s?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=75)
  - With Icing selected, in Edit Mode
  - Alt-A selects all
  - Right Click on Mesh -> Subdivide
  - Will subdivide and bring up Subdivide options in lower left
  - Put Smoothness to 1.000
4. Modify icing edge [TC 2:47](https://youtu.be/jmSgsaNSQ6s?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=167)
  - Turn on Proportional Editing (upper middle curve icon)
  - Select Edge Alt-Left-Click (Select -> Edge)
  - Invert Selection Ctrl-i (Select -> Invert)
  - Hide Selection type H (Alt-H to unhide)
  - Turn "Snap to Face" on (Magnet to turn on snapping)
  - Dropdown next to Magnet to turn on "to Face"
  - Also in Dropdown select Project Individual Elements so that All the effected vertex moves stick to face
5. Make drips [TC 7:06](https://youtu.be/jmSgsaNSQ6s?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=426)
  - Select 2 verticies
  - Type E (Extrude) and pull down to create a new extruded face
  - Repeat... use S to scale
  - In the Icing Properties (the Wrench)
  - Create Crease: Inner - 1.000 [TC 11:20](https://youtu.be/jmSgsaNSQ6s?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=680)
  - Icing should hug the donut better
6. Save as blenderDonutL1P4.blend

## [Part 3 - Level 1](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U) Make Icing through Modifiers
1. Duplicate half donut
  - Numberpad 1 -> Y view (front on view)
    - or click on y axix top right
    - or "~" pie and select
    - or "Alt-MiddleMouse-Drag" to snap to axis
2. Select top mesh points [TC 2:26](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=146)
  - Xray mode Click on boxes in top right or Alt-Z
  - Select top vertices
  - Shift-D (to duplicate)
  - Escape (so it snaps back to original position)
3. Make selected Vertices it's own object [TC 3:37](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=217)
  - Type P then Selection
  - Tab out of edit mode and should have 2 objects
4. Name objects [TC 4:33](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=273)
  - Click on Scene->Collection->Torus000 
  - Double click Torus to rename to Icing
  - Click on other object -> F2 -> Rename to Donut
5. How to select mesh ontop of mesh [TC 5:15](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=315)
  - Select one vertix
  - Type CTRL-L (will select all the other connected vertices)
  - Type P -> Selection to create the object
  - or delete the mesh
6. Adjust Clipping [TC 6:11](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=371)
  - Type N (or click sidebar arrow)
  - View -> Clip Start -> 0.001m
7. Add thickness to icing [TC 7:33](https://youtu.be/R2qjqqfkH6E?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=453)
  - Select Icing Object
  - Click "Add Modifier" -> Solidify
  - Adjust Offset to 1.0 (or to taste)
  - Adjust Thickness to 0.002m
  - Move modifier order so Solidify is first, then Subsurface is next to get the right smoothing of icing
8. Save as blenderDonutL1P3.blend

## [Part 2 - Level 1](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U) Add Torus Object
1. Add Torus [TC 0:40](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=40)
  - Shift-A M T
2. Mod Torus [TC 1:00](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=60)
  - Click "Add Torus" Settings box in lower left corner
  - Adjust Major Radius to 5cm [TC 2:41](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=161)
  - Adjust Minor Radius 2.5cm
  - Adjust Major Segments to 28
  - Adjust Minor Segments to 12
3. Edit object to introduce imperfections [TC 5:36](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=336)
  - Click "Edit Mode" in top left corner or type "Tab" to switch between object and edit mode
  - Turn on "Proprtional Editing" in top right corner the curve thing on
  - Select vertex and use 'scroll wheel' to adjust the editing influence
  - Distort the donut
4. Smooth donut [TC 9:53](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=593)
  - Object Mode right-click donut object
  - Select "Shade Smooth"
5. Make Higher Res [TC 10:36](https://youtu.be/RaT-uG5wgUw?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=636)
  - Click on "Wrench" with object selected
  - Click on "Add Modifier"
  - Click on "Subdivision Surface"
  - Should smooth out donut
6. Save as blenderDonutL1P2.blend
  
## [Part 1 - Level 1](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U) Basic Viewport navigation
1. Index [TC 1:11](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=71) Blender Beginner Series Index
2. Move Object [TC 2:42](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=162) Move Object
3. Rotate Object [TC 3:13](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=193) Rotate Object
4. Scale Object [TC 3:44)(https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=224) Scale Object
5. Memorize HotKeys [TC 4:39](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=279)
  - G: Grab to Move Object [TC 4:42](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=282)
    - Type X, Y, Z to constrain axis or Middle Mouse button click to snap to axis
    - Left click accept
    - Right click cancel (or esc)
    - cmd-Z to undo
  - R: Rotate
  - S: Scale
6. Viewport Navigation in 3D [TC 7:20](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=440)
  - Middle Mouse Button "Orbit View"
  - Shift - Middle Mouse Button "Pan View"
  - Scroll wheel - Zoom
  - Click and hold on Axis orbiter for "Orbit View"
  - Click and hold on Hand icon to "Pan View"
  - Click and hold on + icon to "Zoom View"
  - Emulate 3 button mouse with Alt [TC 9:17](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=557)
    - Edit -> Preferences -> Input -> Click Emulate 3 button mouse
  - Focus on Object
    - Click Object
    - type "." Numpad
  - Bring up pie menu with "~" key (the shift-"`") select from pie
7. Add Objects [TC 11:35](https://youtu.be/TPrnSACiTJ4?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U&t=695)
  - Click "Add" menu at top
  - Shift-A brings up Add popup
8. Monkey on Fire
  - Add Monkey Object
  - Type "F3" key
  - Type "smoke" into search
  - Should create a partical box around object
  - Press Play
   
