java c
CVEN9840 – Structural Health Monitoring 2024
Assignment 2
Question 1 (35%)
A bridge is sitting on top of four piers as shown in below. The bridge is subject to a ground motion as a result of an earthquake.
Assume the ground displacement is modelled as a harmonic loading ug (t)= U0sin(ഥ(w)t) with U0 being 0.5m.
The mass of the bridge deck is Mdeck  = 6×106  kg.  The piers have a circular cross section with a height of L=10m, and a radius of 3m. 
Consider an elastic modulus of E = 20 GPa for the piers
(1) Plot the time response of the bridge for 10 seconds under the loading if ഥ(w) = 2/wn where wn   is the natural frequency of the bridge.
(2) Determine the maximum bending stress at the base of the pier 2 if the excitation frequency varies between w1 = 2/wn to w2 = 2wn  where wn   is the natural frequency of the bridge.
(3) As a result of material deterioration, the elastic modulus of the material in all piers has dropped by 10%. Investigate this damage by comparing the responses of the healthy and damaged bridge in time and frequency domain and discuss your results. You can compare displacement, velocity, acceleration and strain time responses. 
(4) If a strain gauge is installed at the outer surface of the pier 2 in the bottom, compare the time response of strain between the healthy and damaged bridge if the excitation frequency is w1   = 2/wn where wn   is the natural frequency of the healthy bridge.
Assumptions:
-       Consider a SDOF vibration system in horizontal direction.
-       Assume zero initial conditions.
-        Damping ratio is ζ  =  10% .
-        Ignore the mass of the piers.
-       The stiffness is due to the piers only.
-       The deck of the bridge is rigid.
-       The effect of damage is only on pier stiffness.

Question 2 (35%) 
An experimental modal test has been conducted on a free-free beam.
To this aim, the beam has been hitted with a modal hammer at 6 evenly-spaced locations along the length of the beam, e.g. points 1 to points 6 and each time the acceleration response has been recorded at free end,   e.g. point 1. As a result, six frequency response functions (Inertance) have been produced as H11 , H12 , H13 , H14 , H15 and H16 which, respectively, describe the inertance measured at poi代 写CVEN9840 – Structural Health Monitoring 2024 Assignment 2Matlab
代做程序编程语言nt 1 once the impact excitation is applied at points, 1, 2, 3, 4, 5 and 6.

Please find these six recorded inertances in your Moodle page.
The first column in each FRF is frequency in Hz and the second column is the corresponding complex value of the measured inertance. With the assumption of structural damping for the  system, establish the curve fitting method in MATLAB to identify the first three vibration modes in terms of natural frequencies, mode shapes and modal damping.
Present step by step procedure in your report.
Hints: 
You should first convert the inertance measurement into receptance.
You should take advantage of the circularity of receptance for a system with a structural damping.
You should use the presented MATLAB code in the slides (Fit a Circle in MATLAB) to fit a circle to your data.
You can compare the ratios between the first three frequencies and the first mode with the picture shown. Further, you can qualitatively compare the first three mode shapes with the ones shown.

Question 3 (30%) 
A box girder bridge is composed of two tunnels, i.e. East Tunnel and West Tunnel as shown in figure.
Five timely synchronized accelerometer sensors have been placed at different sections along the span in each tunnel to continuously measure the vibration response of the bridge at a sampling frequency of f=25Hz. 
As a result of continuous measurement over a course of 15 hours, 908 datasets have been generated which each dataset includes the vibration response of the bridge in one-minute obtained at 25Hz. 
Due to the operation of large machineries on the bridge, it was realized that bridge had a significantly large vibration level at multiple datasets. 


Use appropriate feature extraction and statistical learning algorithm to identify presence of those large events.
Compare results using different time/frequency features as well as different learning techniques and discuss the results. 
Each row, i.e. 1:908 in the files corresponds to the vibration responses from one dataset. Each column, i.e. 1:5 corresponds to the response obtained from one sensor.
Hint: One approach is to calculate frequency spectra, then reduce dimensionality by PCA and then apply SVM!





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
