# Experient 7.1
## Code
```Matlab
clc; 
clear; 
close all; 
antennas = [2 4 8 16 32];           
gain = 10*log10(antennas);          
figure 
bar(antennas, gain) 
grid on 
% Number of Antenna Elements 
% Beamforming Gain (dB) 
xlabel('Number of Antenna Elements') 
ylabel('Beamforming Gain (dB)') 
title('Beamforming Gain for Different Antenna Array Sizes')
...
```
## Output
![Output](obj1.png)
