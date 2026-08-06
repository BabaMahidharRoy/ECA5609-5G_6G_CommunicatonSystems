# Experiment 3.2
## Code
```Matlab
clc;
clear;
close all; 
d = 2;  % fixed distance (km) 
f = [900 3500 28000];  % MHz 
PL = 32.44 + 20*log10(f) + 20*log10(d);

figure 
subplot(2,1,1) 
plot(f,PL,'-o','LineWidth',2) 
title('Propagation Loss vs Operating Frequency') 
xlabel('Frequency (MHz)') 
ylabel('Propagation Loss (dB)') 
grid on 

subplot(2,1,2) 
bar(PL) 
title('Comparison of Propagation Loss Across Bands') 
xlabel('Frequency Bands (Index: 1=Sub-1GHz, 2=Mid-band, 3=mmWave)') 
ylabel('Propagation Loss (dB)') 
xticklabels({'Sub-1GHz','Mid-band','mmWave'}) 
grid on
...
```
## Output
![Output](exp3obj2.png)
