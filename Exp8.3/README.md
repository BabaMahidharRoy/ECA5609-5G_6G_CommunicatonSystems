# Experiment 8.3
## Code
```Matlab
clc; 
clear; 
close all; 
desired = [-60 -30 0 30 60];      
actual = [-58 -32 1 29 62];       
error = abs(desired - actual);    
figure 
% Desired Steering Angle (degrees) 
% Actual Beam Direction (degrees) 
% Beam Direction Error 
plot(desired, error, 'o-', 'LineWidth', 2) 
grid on 
xlabel('Desired Steering Angle (Degrees)') 
ylabel('Beam Direction Error (Degrees)') 
title('Beam Direction Error for Different Steering Angles')
...
```
## Output
![Output](obj3.png)<img width="707" height="559" alt="obj3" src="https://github.com/user-attachments/assets/c8657d33-90e4-4aa7-915b-7fff2fa53352" />
