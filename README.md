# Double Inverted Pendulum

## Physical Model

The two-link pendulum model has the following parameters:

* m<sub>1</sub>: Mass of the first link.
* m<sub>2</sub>: Mass of the second link.
* r<sub>1</sub>: Distance from first joint to first mass center of mass.
* r<sub>2</sub>: Distance from second joint to second mass center of mass.
* l<sub>1</sub>: Length of the first link.
* l<sub>2</sub>: Length of the second link.

The variables are 

$\theta$<sub>1</sub>: Angle of the first joint. It is the angle between horizon (right/east) to first link.

$\theta$<sub>2</sub>: Angle of the second joint. It is the angle between first link to the second link.

For both angles counter clockwise is positive.

The equations of motion are described as follows

$M$($q$) $\ddot{q}$ + $v$($\dot{q}$, $q$) + $g$($q$) = $\tau$

Where 

$q$ = [$\theta$<sub>1</sub>, $\theta$<sub>2</sub>]<sup>T</sup>



## Brain Dump

We need a class that holds the dynamic of the inverted pendulum.

A configuration file that holds the specification of the inverted pendulum (length of the links, location of center of the mass, mass of each link, etc.)
