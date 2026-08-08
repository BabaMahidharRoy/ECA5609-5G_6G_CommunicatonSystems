# Experiment 5.3
## Code
```Matlab
clc;
clear;
close all; 
rb_bw = 180e3;   
users = 1:5; 
alloc_RB = [10 12 8 15 5]; 
mod_eff = [2 4 6 4 2];    
throughput = (alloc_RB .* rb_bw .* mod_eff) / 1e6; 
disp('User Throughput (Mbps):') 
disp(throughput') 
figure 

subplot(2,1,1) 
plot(users, throughput, '-o','LineWidth',2) 
title('OFDMA User Throughput') 
xlabel('User Index') 
ylabel('Throughput (Mbps)') 
grid on 

subplot(2,1,2) 
plot(alloc_RB, throughput, '-s','LineWidth',2) 
title('Resource Blocks vs Throughput') 
xlabel('Allocated Resource Blocks') 
ylabel('Throughput (Mbps)'
...
```
## Output
![Output](obj3.png)
