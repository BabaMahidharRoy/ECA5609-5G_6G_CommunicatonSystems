# EXP 9.1
## Code
```Matlab
clc; 
clear; 
close all; 
snr = 0:5:30; 
snr_linear = 10.^(snr/10); 
capacity = log2(1 + snr_linear); 
figure; 
plot(snr,capacity,'-o','LineWidth',2,'MarkerSize',6); 
grid on; 
xlabel('SNR (dB)'); 
ylabel('Channel Capacity (bps/Hz)'); 
title('Channel Capacity vs SNR');
...
```
## Output
![Output](obj1.png)<img width="708" height="532" alt="obj1" src="https://github.com/user-attachments/assets/6c44911f-b8a7-4d4f-b989-d5a2f51f3867" />
