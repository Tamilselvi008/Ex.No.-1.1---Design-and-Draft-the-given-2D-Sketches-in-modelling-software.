# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.
Date:05-10-2026
## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE

. Creating the central circle
Open Autodesk Fusion and create a new design.
 Select the Create Sketch option and choose the XY plane.
   <img width="1920" height="1010" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/fe6504ee-3c44-4c66-b1db-423a450b3928" />

 From the Sketch toolbar, select Create → Circle → Center Diameter Circle.
 Click on the origin to set the centre of the circle.
 Draw the outer circle and specify its diameter as 40 mm using the Sketch Dimension option.
 This circle acts as the reference geometry for creating the central inner profile.
<img width="1920" height="1011" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/337d6154-ba59-4232-a977-5b5ec0378ee2" />

 Creating small circles using Circular Pattern
Select the Center Diameter Circle option again.
 Draw a small circle on the circumference of the Ø40 mm circle.
 Apply a radius dimension of 6 mm to the small circle.
 Select the small circle and navigate to Sketch → Create → Circular Pattern.
In the Circular Pattern dialogue box, select the small circle under the Objects section.
 Select the origin of the sketch as the pattern centre.
 Set the pattern quantity to 6 and the angle to 360°.
 Click OK to complete the pattern.
 Six equally spaced circles are now arranged around the central Ø40 mm circle.
 <img width="1920" height="1007" alt="Screenshot (164)" src="https://github.com/user-attachments/assets/d61ca758-f90a-47eb-9368-1acedc7d9a81" />


 Creating the upper circular features
 Select Create → Circle → Center Diameter Circle.
 Draw the upper outer circle with a diameter of 32 mm.
 Draw another concentric circle inside it with a diameter of 20 mm.
 Position the centre of these circles along the vertical centreline.
 Using the Sketch Dimension (D) tool, set the vertical distance between the sketch origin and the centre of the upper circular feature to 65 mm.
 Ensure that both circles are concentric and properly aligned with the vertical centreline.
   <img width="1920" height="1017" alt="Screenshot (167)" src="https://github.com/user-attachments/assets/d022ea8a-af96-4a21-a8d5-58097efbf681" />

 Creating the upper curved portion
 Select the Circle tool from the Sketch Create toolbar.
 Draw a circle with a radius of 64 mm to construct the curved outer boundary.
 Create another circle with a diameter of 66 mm, as specified in the reference drawing.
 Position the circles according to the required geometry.
 Use the Trim command (T) to remove the unwanted portions of the circles.
 Carefully retain only the required curved segments that form the upper connecting profile.
   <img width="1920" height="1010" alt="Screenshot (151)" src="https://github.com/user-attachments/assets/9dea5c4f-97fe-4452-bd7c-d96559d26b32" />

 Check the alignment of the curves with the upper circular feature and central profile.
 Creating the left-side circular features
Select Create → Circle → Center Diameter Circle.
 Draw the outer left-side circle and apply a radius of 10 mm.
 Draw another circle at the same centre and apply a radius of 7 mm.
 These concentric circles form the left-side circular feature.
   
<img width="1920" height="1000" alt="Screenshot (170)" src="https://github.com/user-attachments/assets/16f71d6d-dac1-4d34-abc9-d11dc804f713" />

 Creating the curved portion around the left-side feature
 Select the Circle tool from the Create toolbar.
 Draw a circle with a radius of 20 mm near the left-side circular feature.
 Position it to create the required curved connection between the side feature and the main body.
 Select the Trim option from the Modify toolbar or press T.
  <img width="1920" height="1004" alt="Screenshot (171)" src="https://github.com/user-attachments/assets/fcc3a364-930a-466e-818d-4a59fa1f700e" />

 Remove the unwanted portions of the circle.
 Retain the required arc that forms the smooth connecting boundary.
 Check the connection between the curved portion and the adjacent sketch geometry.
 Creating the lower circular features
 Select Create → Circle → Center Diameter Circle.
Draw the lower outer circle on the vertical centreline.
 Apply a radius of 20 mm to the outer circle.
 Draw a smaller concentric circle inside it.
 Apply a radius of 10 mm to the inner circle.
   <img width="1920" height="1006" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/492ba925-ea39-4913-9518-02508d94862b" />

 Creating the lower connecting curve
 Select the Circle tool from the Sketch Create toolbar.
 Draw another circle with a radius of 20 mm beside the lower circular feature.
 Position the circle so that it forms the required curved connection between the lower feature and the main body.
 Use the Trim command to remove the unwanted portions of the circle.
 Retain only the required arc for the outer boundary.
 Navigate to the Constraints section of the Sketch toolbar.
 Select the Tangent Constraint option.
   <img width="1920" height="1007" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/9bcf6dc9-c0a4-4070-88f4-500f5ac5bcfc" />

 Select the required arc and the adjacent curve or circle to establish a smooth tangent connection.
 Repeat the tangent constraint wherever necessary to obtain a smooth and continuous outer profile.
 Mirroring the sketch using the Mirror option
 After completing the required geometry on one side, identify the vertical centreline of the sketch.
 Navigate to Sketch → Create → Mirror.
 In the Mirror dialogue box, select the required sketch curves under the Objects section.
 Under the Mirror Line section, select the vertical centreline.
 Ensure that all the required curves and circular features are selected.
 Click OK to complete the mirroring operation.
 The selected geometry is now reproduced symmetrically on the opposite side.
 Check both sides to ensure that the mirrored curves are properly aligned and connected.
  <img width="1920" height="997" alt="Screenshot (179)" src="https://github.com/user-attachments/assets/e8fc1fdb-c260-445b-8596-e045c1e6bfbd" />

 Applying constraints and completing the sketch
 Examine the complete sketch and identify any curves that need additional constraints.
 Apply the Tangent Constraint wherever two curves or arcs need to meet smoothly.
 Use coincident constraints wherever endpoints must connect.
 Check the dimensions of all circular features and curved portions.
Remove any unnecessary or unwanted sketch geometry using the Trim command.
 Ensure that the outer profile is properly connected and symmetrical.
 After verifying the dimensions and constraints, click Finish Sketch in the top-right corner of the Fusion workspace.
 <img width="1920" height="1007" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/65364f46-d140-41b6-aa88-f12bb1015d89" />

 Extruding the completed sketch
 After finishing the sketch, navigate to the Solid workspace.
Select the Extrude option from the Create toolbar.
Click on the required closed sketch profile to select the region.
 Enter the required extrusion distance in the Extrude dialogue box.
Select the appropriate extrusion direction.
 Check the preview to ensure that the profile is extruded correctly.
Click OK to complete the operation.
 <img width="1920" height="1017" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/e4ab06df-8754-41ec-a682-6c641e9a76b1" />

 The 2D sketch is now converted into a 3D solid model.
Note: Enter the extrusion thickness specified by your assignment or instructor.
 Viewing the 3D projection
After completing the extrusion, locate the Home icon in the ViewCube area.
 Click the Home icon to return to the default isometric viewing position.
 Observe the completed 3D model from different directions.
<img width="1920" height="1020" alt="Screenshot (158)" src="https://github.com/user-attachments/assets/f33372ab-2810-4acb-b70f-97219f1b0eb3" />

 After checking the 3D model, navigate to File → New Drawing → From Design.
   <img width="1920" height="1007" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/6a601963-58e1-4991-9237-3dc2ae522262" />

 Place the Front View of the model on the drawing sheet.
 Use the projected view option to generate the Top View and Right View.
 Check the drawing to confirm that all three views correctly represent the 3D model.
 Saving the final drawing
 After completing the drawing, review all the views and dimensions.
 Add the appropriate drawing title and other required details.
  
## OUTPUT
<img width="1920" height="1015" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/e815123e-c388-4322-9f6d-cb4348bfacdb" />

## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
