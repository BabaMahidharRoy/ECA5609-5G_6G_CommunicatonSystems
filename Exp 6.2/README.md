# Experiment 6.2
## Code
```Matlab
clear; 
close all; 
scs = [15 30 60 120 240];          
 
slot = [1 0.5 0.25 0.125 0.0625]; 
plot(scs, slot, 'o-', 'LineWidth', 2) 
grid on 
xlabel('Subcarrier Spacing (kHz)') 
ylabel('Slot Duration (ms)') 
title('5G NR Slot Duration for Different Subcarrier Spacing')
...
```
## Output
![Output](obj2.png)
