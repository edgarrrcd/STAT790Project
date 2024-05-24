This is a project for the Master of Arts in Applied Mathematics at CUNY Hunter College under the mentorship of Professor Vincent Ryan Martinez.

The work presented was done using the SINDy package and Python.
For more information regarding SINDy, visit: https://github.com/dynamicslab/pysindy

The goal was to find the optimal threshold for any dynamical system. For this project, the "optimal" threshold was defined as the largest threshold that gives nontrivial outputs (i.e. we aim to find the maximum threshold the user should not exceed).


Attempts were made on the Linear 2D Dynamic and Cubic 2D Oscillators.

The first attempt was employing a Greedy Algorithm on the Linear 2D Dynamic Oscillator. However, this method overshoots and was not effective. The bisection method was attempted, 
where the interval was determined by manually inspecting the optimal thresholds for a couple of initial conditions. The bisection method generated results  
closer to the true optimal threshold.

However, this methodology ad hoc due to the SINDy package. Hence, the SINDy package needs to be rewritten that will allow one to write a program that will find the optimal threshold
for any dynamical system of interest.
