---
layout: project
title: Piston Frame System
description: Advanced CAD Project
technologies: [Design Drawing, Hand Calcuations]
image: /assets/images/Piston-Frame-System.jpg
---

For a class, we were asked to design a frame in a 2D space of 150 cm long by 50 cm tall where we need to use a ridigd bar of a fixed length of your choosing with 3 pins, two which need to be connected to the ground and the linear actuator. However, the key is to make it so the frame/mechanism could lift to the highest possible maximum height while also supporting the highest maximum weight. The linear actuator was chosen from the cataloug given. Me and a few friends were able to discuss the best design after a few iterations. We kept discussion what would happen if we were to move the piston to certain locations on the bar and what forces the bars would experience and if the location of the bar/linear actuator would cause any torsion/bending (which we didn't want since they were both ridgid). We then ended up with the shown drawing with hand calculations provided to solve for the maximum height assuming all conditions were met. 

Given Components
Two ground-mounted pin supports at A and B
One floating pin at C
A rigid bar/beam AC and BC
Linear actuator mounted between C and ground
Actuator model used: IMA 55 RN055
Max thrust: 35.81 kN
Stroke length: 457.2 mm
Max angle used: 45°


Horizontal distance between ground supports: 𝐴𝐵 = 920 mm
Lifting height limited to: ≤500 mm (design limit)
Mechanism height at C = 460 mm
For a 45° actuator angle: 𝐻
=
460
sin
⁡
45
∘
≈
650.54
 mm
H=
sin45
∘
460
	​

≈650.54 mm

(this matches your drawing)

Member lengths (measured from your diagram):
𝐴𝐶=650.54mm
𝐵𝐶 = 356.71 mm

Stroke = 457.2 mm

One actuated DOF (actuator extension)
The structure itself is a pin–pin–pin triangular linkage with 1 DOF

Treat AC and BC as rigid two-force members.

Analysis:
Apply a vertical load 𝐹 load at C and find reactions at A and B and the internal forces in AC and BC.
FBD as shown in picture
Used geometry of 45 degree angles with sin and cos for link AC
For link BC, used pythageoran theorem 
Found Equiliibirum at joint C
    Sum of forces in the X direction
    Sum of forces in the Y direction
    Internal member forces
    Must also withstand the actuator's force

Step 2:
Beam horizontal base is 0.92 m
Simplily supported beam
There is a downwards load F load acting on it
Calculated the verticle force values to be 25.3 kN down at C and up at B
This is a classic two point load bending scenario.

Calculating the internal moments to find reactions A and B, you get B=37.95 and A=12.65. 
When you contruct the bending moment diagram, at C Mc=5.82 and at B Mb=3.0 where 5.82 is the Max moment
Calculate the Deformation to be 0.0184 m and the I has to be 1.12 x 10^-7 m^4

We want a cross section taht give the I to be at least 1.12 x 10^-7 as stated above. 
The best mass efficient option is  102 x 102 x 15.9 steel section. 
