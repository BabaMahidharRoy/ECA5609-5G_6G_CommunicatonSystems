# EXP 10.1
## Code
```Matlab
clc; 
clear; 
close all; 
slices = {'eMBB','URLLC','mMTC','Private','IoT'}; 
count = [1 1 1 1 1];      
figure 
bar(count) 
% One instance of each network slice 
grid on 
set(gca,'XTickLabel',slices) 
xlabel('Network Slice Type') 
ylabel('Number of Network Slices') 
title('Number of Configured 5G Network Slices')
...
```
## Output
![Output](obj1.png)<img width="711" height="529" alt="obj1" src="https://github.com/user-attachments/assets/de5878d9-ffcc-43a9-8fb2-735b8e4a6e5c" />
