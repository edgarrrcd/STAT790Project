This is a project for the Master of Arts in Applied Mathematics at CUNY Hunter College. 

The work presented was done using the SINDy package and Python.
For more information regarding SINDy, visit: https://github.com/dynamicslab/pysindy

The goal was to find the optimal threshold for any dynamical system. For this project, the optimal threshold was defined as the largest threshold that gives nontrivial outputs.

Attempts were made on the Linear 2D Dynamic Oscillator and the Cubic 2D Oscillator.

The first attempt was employing a Greedy Algorithm on the Linear 2D Dynamic Oscillator. However, this method overshoots and was not effective. The bisection method was attempted, 
where the interval was determined by manual inspection of the optimal thresholds for a couple of initial conditions. Using the bisection method proved to generate results that were 
closer to the true optimal threshold.

However, this methodology ad hoc due to the SINDy package. Hence the SINDy package needs to be re written to that will one to write a program that will find the optimal threshold
for any dynamical system of interest.
