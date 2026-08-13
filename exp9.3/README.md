# EXP 9.3
## Code
```Matlab
clc; 
clear; 
close all; 
antennas = [4 8 16 32 64];        
gain = 10*log10(antennas);        
figure 
bar(antennas, gain) 
grid on 
xlabel('Number of Antenna Elements') 
ylabel('Antenna Gain (dB)') 
title('Antenna Gain for Different Antenna Array Sizes')
...
```
## Output
![Output](obj3.png
)<img width="706" height="532" alt="obj3" src="https://github.com/user-attachments/assets/174c29f2-4c14-44df-8ca4-5bd2e93e07af" />
