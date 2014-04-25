# InteractiveOS

The goal for this application is to make available
skeleton(s) information to other applications such as
PureData. This information includes joint location in 3D 
space, joint velocity, and recognized gestures. 

Other functions of this program is to draw the skeleton in 3D
space displaying the above information, and also to compare a 
user's movement to a recorded sequence of movements and offer
useful guidence for the user to align with the recorded movement. 

Later developments would include ability to recognize an over-extension
of a limb, the torso, or the neck, and to detect (rough) weight distribution 
to bring the users awareness to adjust accordingly (per-posture correction 
as opposed to sequence correction, possible because of weight/center detection).
 
A long term goal would be to design an AI that learns the user's body 
(taking in paramters such as mass distribution, age, injury, past medical issues...etc.)
and finds the path of greatest aid for that person. 

# Design ideal

Ideally, I would like to develop the C# portion of this kit as a 
generic helper and starting point for more specialized projects.


# List of resouces so far

http://msdn.microsoft.com/en-us/library/microsoft.kinect.aspx

http://puredata.info/ Download the extended version. 

C# OSC Implementation: http://opensoundcontrol.org/implementation/osc-net-v1-2
I'm using version 1.4.1, which the DLL is in the main directory.


