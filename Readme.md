## Problem Statement:
Given the parameteric equation of the curve defined as:  
```
x(t) = t·cos(θ) - e^(M·|t|)·sin(0.3t)·sin(θ) + X
y(t) = 42 + t·sin(θ) + e^(M·|t|)·sin(0.3t)·cos(θ)
``` 
Given range of the unknown values:  
 0° < θ < 50°  
 0 < X < 100  
 -0.05 < M < 0.05  
 6 < t < 60  

Find the values of the θ, X and M such that the fitted curve passes through the provided data points and minimizes the L1 distance error between the predicted and actual points.  


## Final Parameter Values:  
theta (rad) = 4.90610464e-01  
theta (deg) =  28.10990898228646  
M = 2.14413236e-02  
X = 5.49005240e+01  


## Final Equation:  
```
\left(t*\cos(0.490610)-e^{0.021441\cdot\operatorname{abs}\left(t\right)}*\sin(0.3t)\sin(0.490610)+54.900935,\ 42+t*\sin(0.490610)+e^{0.021441\cdot\operatorname{abs}\left(t\right)}*\sin(0.3t)\cos(0.490610)\right)
```
