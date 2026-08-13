# EXP 10.3
## Code
```Matlab
clc; 
clear; 
close all; 
slices = [1 2 3 4 5]; 
latency = [25 5 40 15 60]; 
figure; 
plot(slices, latency, '-o','LineWidth',2,'MarkerSize',8); 
grid on; 
xticks(slices); 
xticklabels({'eMBB','URLLC','mMTC','Private','IoT'}); 
xlabel('Network Slice Type'); 
ylabel('End-to-End Latency (ms)'); 
title('5G Network Slicing: End-to-End Latency'); 
ylim([0 70]);
...
```
## Output
![Output](obj3.png)<img width="690" height="533" alt="obj3" src="https://github.com/user-attachments/assets/710e0a11-9e35-474e-b1e7-28470ab5b5ef" />
