# Satellite_Gravity_Gradient_Model
Experimental model calculating a gravity gradient map as measured by a satellite, currently very much work in progress.  
The goal is to create a tool that simulates the measurement of a gravity gradiometer on a satellite platform, which is a instrument measuring the gravitational pull on 1 direction, in this case the perpendicular direction, which is also the direction of weight force.

The model allows the user to generate a mass map, in the form of a 2D array where each value corresponds to a local value of mass distribution. 
It then calculates the gravity signal as measured by 2 sensors, separated by a distance called _baseline_ along the perpendicular direction.

The model is divided in a few blocks as in figure. 

![Project diagram][diagram]





[diagram]: https://github.com/RaffaToSpace/Satellite_Gravity_Gradient_Model/blob/master/images/project_diagram.png "Project diagram"
