# Pipes and Ducts along a curve
Technique for creating a line that can generate all the geometry for pipe and duct runs.

1. Create the run _chase line_
    1. Add a plane
        - Shft-A M P
    2. Delete all but 1 vertices
        - Tab (edit)
        - Click on one verticies -> Ctrl-I (invert selection) -> X (Delete) Vertices
    3. Create chase run by extruding the remaining vertex along the desired 3D path
        - Click on vertex
        - E (extrude) Y (contrain Y) move click
        - E (extrude) X (contrain X) move click
        - E (extrude) Z (contrain Z) move click
    4. Check for double verticies
        - In Edit Mode Select all
        - W -> Merge Verticies by Distance
    5. Apply Bevel to 2D line run
        - Ctrl-Shift-B
    6. Convert line to curve
        - Object -> Convert To -> Curve from MeshText
2. Create cross-section object (2D single object)
    1. Tab (object mode)
    2. Add Circle
        - Shft-A (Add) C (curve) C (Circle)
        - BezierCircle curve (under wrench) -> Shape: 2D (this is not required but keeps cross-section 2d)
    3. Position object keeping orign where it was as this will align the cross section of the chase
        - A (all) G (grab) move and click to set
        - Shft-D (duplicate) move S (scale) and click to set
    4. Tab (object mode)
3. Add cross-section to path
    1. Select Chase
    2. BezierCircle curve (under wrench) -> Geometry -> Bevel -> Object: Select cross-section object name
    3. The chase should have your cross-section object as pipes
    4. Scale and adjust the cross-section to view
    5. Edit Chase path to adjust 3D path
4. Add a duct to cross-section
    1. Tab (object mode)
    2. Add a plane
        - Shft-A (add) M (mesh) P (plane)
    3. Select and delete verticies then extrude to create box with line only
    4. Make sure you close box with a line 
        - forgot right-click join
    5. Bevel corners
        - Ctrl-Shift-B (2D bevel)
    6. Convert this mesh to curve
        - Object -> Convert To -> Curve from MeshText
    7. Join new object with cross-section object
        - Ctrl-J (Join objects)
    8. New cross-section should be generated along chase
5. Save as blenderPipesDucts.blend

  
### Reference
- [Blender 2.8. Modelling with Curves, how to make pipes](https://www.youtube.com/watch?v=F2SIbAxLftc)
