Welcome to my simulation!

This simulation works on principles of Newtonian gravity, and the goal was to come up with a simulation that is accurate (to some degree) with as little initial parameters as possible.

Essentially, positions were derived by assuming perfectly elliptical orbits of a known eccentricity, whereby two distance parameters were known: the distance at the furthest point of orbit between the planet and the sun, 
and the distance between the earth and the planet at one particular day. These parameters could, realistically speaking, be approximated to some degree of accuracy without any sophisticated instrumentation. 

What was done next was a series of rather interesting modifications to each planet's orbital parameters through two main linear transformations: a phase shift and a rotation. Orbits were all simplified to be along one plane
in order to solve the system of equations necessary, as more distance parameters would be required to map the planets in 3-dimensional space otherwise.

Some additional funky projections were done for the planet pluto as well, since its "3-dimensional tilt" was far too significant to neglect.


***********************************        HOW TO RUN        ******************************

1. Extract the zip file 
2. Open one of the following files in matlab: solarsystem_final.m, solarsys_toscale.m (to see realistic planetary scale), solarsys_slider.m (to control the date of the simulation with a slider rather than a continuous cycle)
3. Enjoy! 
