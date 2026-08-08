# Experiment 7.3
## Code
```Mtlab
clc; 
clear; 
close all; 
theta = [-60 -30 0 30 60];     
gain = [1 1 1 1 1];            
figure 
% Main Lobe Direction (degrees) 
% Constant normalized gain 
polarplot(deg2rad(theta), gain, 'o', 'LineWidth', 2) 
title('Main Lobe Direction in Analog Beamforming')
...
```
## Output
![Output](obj3.png)
