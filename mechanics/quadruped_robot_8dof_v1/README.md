Quadruped Robot 8dof v1
=======================
<img src="images/quadruped_8dof_jump_1.jpg" width="600"><br>*The quadruped robot Solo performs a 26cm jump.     (Picture by W. Scheible)*  

Description
------------
<img src="images/solo_iso.jpg" width="500"> <br>   

* 8dof - 8 degree of freedom robot
* Power and communication over wire (24V / 4 x CAN)
* Weight 2.2kg
* Vicon markers on base

The robot consists of:  
* 8 x identical actuator module - details here -> [Actuator module](../actuator_module_v1)  
* 4 x identical lower leg with foot contact switch - details here -> [Foot Contact Switch](../foot_contact_switch_v1)
* 4 x Texas Instruments dual motor driver electronics - details here -> [TI Electronics](../../electronics/ti_electronics)

Dimensions
-----------
<img src="images/quadruped_8dof_1.png" width="600"> <br>   

Motion Sequences
---------------
<img src="images/solo_motion_sequences.jpg" width="600"> <br>

Electronics
-----------
<img src="images/quadruped_electronics_1.jpg" width="600"> <br>   

3D Printed Parts
-----------------
<img src="images/body_bottom_part_1.png" width="400"> <br>
<img src="images/body_top_part_1.png" width="400"> <br>
* Body Shell Bottom Part - 230g - [STL file](stl_files/quadruped_body_bottom_part.STL)  
* Body Shell Top Part - 110g - [STL file](stl_files/quadruped_body_top_part.STL)

3D Printing Orientation - SLS Printer
----------------------

<img src="images/print_orientation_body_shell_bottom_part.png" width="600"><br>  
____
<img src="images/print_orientation_body_shell_top_part.png" width="600"><br>  
___
Body Shell Preparation
-------------------------
<img src="images/body_shell_preparation_1.png" width="600"> <br>*Shell preparation - Threads and threaded inserts*
___
<img src="images/body_shell_preparation_2.png" width="600"> <br>*Shell fasteners - SHCS = Socket Head Cap Screw*

___
Off-the-shelf Components
--------------------------
### Strain relief

<img src="images/cable_gland.jpg" width="400"> <br>

* Cable gland for strain relief of the umbilical cable  
* Lapp Skintop M16 x 1,5 - Lapp Product Number 53111210 - RS 365-8450

**Important:**
The cable gland thread is M16 x 1,5mm - the standard metric thread is M16 x 2mm.  
Make sure to use a M16 x 1,5mm fine pitch thread cutter to prepare the thread in the 3d printed shell.
___
### Vicon Markers
<img src="images/vicon_marker.jpg" width="500"> <br>*Reflective Markers for motion capture system*

* 10 x 9.5mm Vicon Markers on the base
* M4 x 10 set screws for a attachment
___
PDF Drawings
---------------------

<a href="quadruped_8dof_v1.PDF"><img src="images/quadruped_pdf.png" width="500"></a><br>*Quadruped Overview - Click on picture to view PDF drawing*
____
<a href="details/vicon_markers_quadruped.PDF"><img src="images/quadruped_marker_positions_pdf.png" width="500"></a><br>*Vicon Marker Placement - Click on picture to view PDF drawing*

* You can download the Vicon Object here: [Quadruped Vicon Object](details/quadruped.vsk)
___
Coordinate System
--------------------
<img src="images/quadruped_coordinate_system_8.jpg" width="400"> <br>  
___
3D Model for Visualization
---------------------------
The simplified stl files for visualization and simulation can be found here: [STL Files Visualization](stl_files_for_visualization).

<img src="images/quadruped_simulation.png" width="400"> <br>

<img src="images/quadruped_simplified_positions_coordinate_systems.png" width="600"> <br>
____
Inertia Parameters for Simulation
---------------
The inertial values are being used in this repository: [Robot Properties Solo](https://github.com/open-dynamic-robot-initiative/robot_properties_solo)

<a href="details/quadruped_inertia_parameters.pdf"><img src="images/quadruped_inertia_pdf.png" width="500"></a><br>*Quadruped Inertia Parameters - Click on picture to view PDF drawing*
___

Quadruped Robot In The Dark
---------------------------
<img src="images/solo_in_dark_1.jpg" width="500"> <br>*In the picture you can see the light from the foot sensor leds and the microcontroller status leds*

---
## View the quadruped cad model in your web browser <br>

<a href="https://open-dynamic-robot-initiative.github.io/cad_files/quadruped_8dof_v1"><img src="images/quadruped_cad_1.png" width="300"></a><br> *Quadruped Robot 8dof v1 <br> Click on the picture to view the biped cad model in your browser*

---
Authors
--------
Felix Grimminger

License
-------
BSD 3-Clause License

## Copyright
Copyright (c) 2019-2020, Max Planck Gesellschaft and New York University

## More Information
[Open Dynamic Robot Initiative - Webpage](https://open-dynamic-robot-initiative.github.io)  
[Open Dynamic Robot Initiative - YouTube Channel](https://www.youtube.com/channel/UCx32JW2oIrax47Gjq8zNI-w)   
[Open Dynamic Robot Initiative - Forum](https://odri.discourse.group/categories)  
[Open Dynamic Robot Initiative - Paper](https://arxiv.org/pdf/1910.00093.pdf)  
[Hardware Overview](../../README.md#open-robot-actuator-hardware)  
[Software Overview](https://github.com/open-dynamic-robot-initiative/open-dynamic-robot-initiative.github.io/wiki)
