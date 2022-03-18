# Script

As part of our diploma thesis in the year 2022 at the Higher Technical College Wiener Neustadt 
, in close collaboration with robo4you, we developed a semi-autonomous 3D mapping drone for GPS-denied areas. 
The autonomous, universal mapping and navigation drone can locate itself within an unknown environment and dynamically navigate around obstacles while creating a 3d point-cloud for further usage.



## Mapping
The UAV is equipped with a stereo-camera feeding depth-imagery and odometry data
into a SLAM algorithm abstracting a model of its surroundings and assessing the drone's current pose.

## Path-Planning


## Architecture
To ensure optimal computational load balancing while maintaining real-time constraints, 
all computations concerning mapping are performed onboard while path-planning and 
user feedback is sourced to a client computer wirelessly connected to the drone. 


## Outlook
The system allows for exploring hazardous environments in an easy-to-use and safe manner.
To test the system as close to its industrial competitors, we moved the drone through underground tunnels of the HTL.

## Closing
Finally, we want to thank the HTL Wiener Neustadt, robo4you and our supervisor Dr Mag Michael Stifter, for making this project possible.
