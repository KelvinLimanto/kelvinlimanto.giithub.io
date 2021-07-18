---
layout: post
title:  "2019 Summer F4 CADathon"
date:   2019-08-06 16:03:25 -0400
categories: Posts
---
![Cover Render Image](/img/2019sumcad_1.png)

This is my submission to the seventh Bi-annual CADathon hosted by F4. This robot was designed to FIRST Robotics Competition (FRC) rules and specifications to play in a virtual game. This would be my second time entering an F4 CADathon. I had gotten third place last time, so the pressure was on to do better. I had to design something unique, both in look and strategy. The premise of this challenge is to pick up and throw two different sized rubber balls into goals at the ends of the field. There was some terrain on the field so a traditional multidirectional drive train couldn’t be used. This challenge also seemed like an extremely defensive heavy game with a lot of blocking and pushing. 

This challenge was called Finite Charge and I had three days to plan, CAD, render and document a submission. My robot design can be split up into five main subassemblies: the drive train, ball intake, ball serial sorter and loader, ball shooter, and endgame mechanism. 

![Underside Drive Train Render](/img/2019sumcad_drivetrain.jpg)

The drive train has a dual mode feature with practically two drive trains built into a single frame. The primary drive system is the omni-directional H-drive. Ten sets of omni wheels provide enough traction to move the robot around in any direction making alignment for intaking and shooting balls easier. The two omni-wheels in the center of the robot responsible for strafing movement side to side only engaged the ground when powered. Geared to the same primary motors is the track secondary drive system. Deployed by some large pneumatic cylinders on a pivot, the track secondary drive system provides extra traction and drive surface area to play defense and go over field terrain. When the tread system is deployed, the robot is practically unmovable, but when the primary omni-directional drive is deployed, the robot can move with higher top speed in any direction.

![Robot With Balls Loaded Render](/img/2019sumcad_2.png)

The intake is fairly simple with a couple mecanum wheels to center the balls before entering the robot. Long pneumatic cylinders can extend or retract the intake. Since there are two different size balls that the intake has to grab, the intake is sprung down with coil springs to maintain contact with the balls throughout the intake process. 

The serializer consisting of a conveyor and mecanum rollers is responsible for separating the different sized balls within the robot. Since the different sized balls are thrown into different goals, it is necessary to line all of the same sized balls together to shoot at once. Pneumatic cylinders change the mounting angle of the mecanum wheel rollers to increase or decrease the distance between them. Depending on if the mecanum wheel rollers are far or close to each other will determine which sized balls will be loaded into the primary loading chamber. A conveyor belt at the bottom pushes the balls that are the wrong size to be loaded into the primary loading chamber to the back. Both the primary chamber and secondary chamber are mounted on powered 4-bar linkages. The linkages must change position depending on what sized balls are being loaded. I will admit that this one mechanism is the one mechanism that I do not have full confidence will work in real life. The balls may or may not behave in the real world the same as in cad. Additionally I do not know how compliant the balls themselves are, so I just built compliancy in the ball handling mechanisms to be safe.

Built into the mecanum wheel roller primary loading system frame is the flywheel shooter. Should be simple enough to know how it works without an explanation, but a fast flying wheel contacts balls and launches them. The momentary angular momentum and speed of the flywheel at ball contact compared to the mass of the ball determines launching velocity. 

At the rear of the robot is the end game mechanism. Two clamps grip the descending pole onto a large wheel. Servo-controlled disk brakes geared to the large wheel control the rate of descent. This entire mechanism is built into the frame of the robot to make sure there is enough rigidity to safely descend.

![Robot Sorting Balls Render](/img/2019sumcad_3.png)

After panic rendering my robot design on three separate computers just to submit on time, I ranked 3rd place again. However there were more participants in this CADathon than previous CADathons. 

**Skills Enhanced**
- CAD (PTC Creo Paramtric)
- Rendering (Keyshot)