# Experiment 3.3
## Code
```Matlab
clc;
clear;
close all; 
f = [900 3500 28000]; 
d = 2; 
PL = 32.44 + 20*log10(f) + 20*log10(d);

figure 
subplot(2,1,1) 
plot(f, PL, '-o', 'LineWidth', 2) 
title('Propagation Loss vs Operating Frequency') 
xlabel('Frequency (MHz)') 
ylabel('Propagation Loss (dB)') 
grid on 

subplot(2,1,2) 
plot(1:3, PL, '-s', 'LineWidth', 2) 
title('Band-wise Propagation Loss Comparison') 
xlabel('Band Index (1=Sub1GHz, 2=Mid-band, 3=mmWave)') 
ylabel('Propagation Loss (dB)') 
grid on
...
```
## Output
![Output](exp3obj3.png)
