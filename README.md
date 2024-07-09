# Design and Fabrication of Robot Manipulator Arm using 3D Printing Techniques

## Project Overview
This project involved the design and fabrication of an industrial robot manipulator arm utilizing 3D printing techniques. The objective was to create a robot arm with optimized reach, reduced torque requirements, and maximized workspace area. The design process included multiple iterations and extensive testing to ensure the effectiveness and efficiency of the final product.

## Key Features
- **CAD Design:** Developed the robot arm in CREO Parametric with multiple iterations of link lengths and arrangements. Each iteration was tested for better reach, lower torque requirements, and maximized workspace area by importing into Altair Inspire for motion analysis.
- **Joint and Gear Mechanism Design:** Conceptualized and designed the joint definitions, incorporating gears and structures for motion transmission from the stepper motor to the links.
- **Motion Analysis:** Conducted extensive testing and analysis of motion transmission through gravitational and contact forces. Defined contact surfaces and forces on the gear mechanism and analyzed various load conditions using Altair Inspire.
- **Design Optimization:** Performed topographical optimization on non-crucial sections based on stress analysis results to refine and enhance the design.
- **3D Printing Technique Evaluation:** Compared and determined the most effective 3D printing technique based on criteria such as time, cost, and required stiffness.
- **Forward Kinematics:** Applied Denavit-Hartenberg rules to generate forward kinematics equations for the robot arm structure.

## Detailed Description
### CAD Design and Iteration
The project began with the creation of an initial CAD design of the robot arm using CREO Parametric. Multiple iterations were produced, each improving upon the previous design in terms of reach, torque requirements, and workspace area. These iterations were imported into Altair Inspire for motion analysis, ensuring that each version met the desired performance criteria.

Clippings from the Report

***First Iteration Results*** - Design, Workspace and Torque Requirements
<p align="left">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/9c4ea211-2462-4466-8cba-9e5a85cd6ed4" alt="Screenshot 1" width="200"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/9318acc8-8c41-4e33-a8c6-0ddac3b41521" alt="Screenshot 2" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/aad4b5cb-b907-40d7-a8d9-5fcc58b11828" alt="Screenshot 3" width="400"/>
</p>

***Final Iteration Results*** - Design, Workspace and Torque Requirements

<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/1f68eb65-aed9-47d7-a0d8-f3faedf8bde2" alt="Screenshot" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/9b4c13cf-fa67-4439-aebf-52cbe47001e7" alt="Screenshot 1" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/f2d7630d-6ba6-4535-96c6-7a329d8a77fd" alt="Screenshot 2" width="400"/>
</p>

***Percentage Reduction in Torque for Each Iteration***
<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/050afd84-47dd-4304-84e6-9a1d403ca0cf" alt="Screenshot" width="500"/>
</p>


### Joint and Gear Mechanism
The design included detailed joint definitions and the incorporation of gears and structures necessary for effective motion transmission. The stepper motor's movement was transmitted to the robot arm's links through these gears, enabling precise and controlled movements.

<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/28ccc6b7-4715-4975-a8ca-17c85b08f66b" alt="Picture2" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/080808f2-c739-4e44-9f39-d05cab157f15" alt="Picture3" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/d5053fc8-d27b-43fe-a71f-9fd0aa78c307" width="300">

</p>



### Motion Analysis
Extensive motion analysis was performed to test the effectiveness of the design. This involved analyzing motion transmission through gravitational and contact forces, defining contact surfaces, and applying various load conditions. Altair Inspire was used for these analyses, ensuring that the design could withstand operational stresses.

<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/31edc3ed-c2a8-4e44-a647-dac203c08401" alt="Media1" width="300"/>
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/22570552-651e-4998-b8e8-1c790a9597de" alt="Media2" width="300"/>
</p>


### Design Optimization
Based on stress analysis results, topographical optimization was performed on non-crucial sections of the design. This optimization aimed to reduce material usage and weight while maintaining structural integrity, ultimately enhancing the overall design.

***Topographical Optimization on Heavy Part***

<p align="center">
<img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/a8a5328c-67ff-47ad-bfcb-d8653ed90db0" width="400"/>
</p>



***Final Design Based on Optimization Results***

<p align="center">
<img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/61de248f-10fd-4302-b215-ad6cfed894f8" width="400"/>
</p>


### 3D Printing Technique Evaluation
Various 3D printing techniques were evaluated to determine the most suitable method for fabricating the robot arm. Factors such as time, cost, and required stiffness were considered in this evaluation to ensure the final product met the necessary specifications.

***3D Printed Parts***

<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/90c1e8e5-52d7-4f4c-ab80-2978011c1241" width="100">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/8e1b9678-faa2-457a-accc-be91ee9cb77f" width="100">
</p>
<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/c11d19f3-33f7-4862-a6e4-be67d89e409f" width="400">
</p>

### Forward Kinematics
Forward kinematics equations were generated using Denavit-Hartenberg rules. These equations provided a mathematical model of the robot arm's movements, enabling precise control and operation.

***DH Table based on Robot Dimensions***
<p align="center">
  <img src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/6b80c642-2405-424b-b9f4-ef11262e3ce2" alt="unnamed" width="100"/>
  <img width="400" alt="Screenshot 2024-07-09 170959" src="https://github.com/rishabh-bavithran/Robot_Manipulator_Arm/assets/145865695/c04e0a84-939f-4e4c-80fb-531b2183b4c0">
</p>



## Conclusion
The design and fabrication of the robot manipulator arm were successfully completed, resulting in a highly optimized and efficient industrial robot arm. This project demonstrated the effective use of 3D printing techniques in robotics and provided valuable insights into design optimization and motion analysis.
