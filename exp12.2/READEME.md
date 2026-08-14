# exp 12.2
## Code
```Matlab
clc; 
clear; 
close all; 
% SNR values (dB) 
SNR = 0:5:30; 
% Simulated Latency (ms) 
NB_IoT = [180 160 145 130 120 110 100]; 
LTE_M  = [90 80 70 60 50 45 40]; 
disp('SNR(dB)   NB-IoT Latency(ms)   LTE-M Latency(ms)') 
disp([SNR' NB_IoT' LTE_M']) 
figure 
% -------- Graph 1 -------- 
subplot(2,1,1) 
plot(SNR,NB_IoT,'-o','LineWidth',2) 
title('NB-IoT Latency vs SNR') 
xlabel('Signal-to-Noise Ratio (dB)') 
ylabel('Latency (ms)') 
grid on 
% -------- Graph 2 -------- 
subplot(2,1,2) 
plot(SNR,LTE_M,'-s','LineWidth',2) 
title('LTE-M Latency vs SNR') 
xlabel('Signal-to-Noise Ratio (dB)') 
ylabel('Latency (ms)') 
grid on
...
```
## Output
![Output](obj2.png)<img width="1392" height="681" alt="obj2" src="https://github.com/user-attachments/assets/99806e6e-d0bd-4489-a850-7f4caaa5fc03" />

