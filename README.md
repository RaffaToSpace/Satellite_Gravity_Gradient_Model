# Satellite_Gravity_Gradient_Model
Experimental model calculating a gravity gradient map as measured by a satellite, currently very much work in progress.  
The goal is to create a tool that simulates the measurement of a gravity gradiometer on a satellite platform, which is a instrument measuring the gravitational pull on 1 direction, in this case the perpendicular direction, which is also the direction of weight force.

## Intro
Satellite gravimetry and gradiometry are techniques in fast development, with impactful applications, [as NASA's GRACE](https://www.nasa.gov/mission_pages/Grace/index.html) and [ESA's GOCE](https://www.esa.int/Applications/Observing_the_Earth/GOCE) have shown. A large effort is currently undergoing to develop novel kinds of gravity sensors, e.g. quantum technology based ones, that could work in a single or double sensor differential configuration, hence measuring the absolute gravity pull or the gravity gradient along the axis of the sensors (see Wikipaedia page for [gradiometry](https://en.wikipedia.org/wiki/Gravity_gradiometry), and there is a lot of material on gravity sensors that can be found online).


## How it works
The model allows the user to generate a mass map, in the form of a 2D array where each value corresponds to a local value of mass distribution. 
It then calculates the gravity signal as measured by 2 sensors, separated by a distance called _baseline_ along the perpendicular direction.

The model is divided in a few blocks as in figure. 

![Project diagram][diagram]

## Installation and use
In the current state (2.0), you just need the main project notebook. Use the random map generator or load a suitable map matrix and use the gravity signal functions to get a gravity signal map and a satellite sensing map. A more complete description of the functions and the modelling process will follow.



[diagram]: https://github.com/RaffaToSpace/Satellite_Gravity_Gradient_Model/blob/master/images/project_diagram.png "Project diagram"
