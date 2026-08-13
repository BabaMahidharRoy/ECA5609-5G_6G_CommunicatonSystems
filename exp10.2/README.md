# EXP 10.2
## Code
```Matlab
clc; 
clear; 
close all; 
slices = categorical({'eMBB','URLLC','mMTC','Private','IoT'}); 
utilization = [85 70 60 75 50]; 
figure; 
bar(slices, utilization); 
grid on; 
xlabel('Network Slice Type'); 
ylabel('Slice Utilization (%)'); 
title('Slice Utilization in 5G Network Slicing'); 
ylim([0 100]);
...
```
# Output
![Output](obj2.png)<img width="715" height="533" alt="obj2" src="https://github.com/user-attachments/assets/d1f5a16d-8d64-49f5-830b-99d1a137adfe" />
