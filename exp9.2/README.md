# EXP 9.2
## Code
```MATLAB
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
![Output](ob2.png)<img width="709" height="539" alt="obj2" src="https://github.com/user-attachments/assets/f2ff6b77-7dd9-4ce8-87e0-c0182f7ca165" />
