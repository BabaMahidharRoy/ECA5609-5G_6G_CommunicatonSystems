# exp15.1
## code
```matlab
clc; 
clear; 
close all; 
% Time samples 
t = 1:10; 
% Prediction Accuracy (%) 
Accuracy = [90 91 92 93 94 95 96 97 98 99]; 
% Actual Network Traffic (Mbps) 
Traffic = [45 50 55 60 65 70 75 80 85 90]; 
figure 
% -------- Graph 1 -------- 
subplot(2,1,1) 
plot(t,Accuracy,'-o','LineWidth',2) 
title('AI Prediction Accuracy over Time') 
xlabel('Time Interval') 
ylabel('Prediction Accuracy (%)') 
grid on 
% -------- Graph 2 -------- 
subplot(2,1,2) 
bar(Traffic) 
title('Network Traffic Samples Used for AI Prediction') 
xlabel('Traffic Sample') 
ylabel('Traffic (Mbps)') 
grid on
...
```
## output
![output](obj1.png)<img width="1389" height="680" alt="obj1" src="https://github.com/user-attachments/assets/c46063d1-9845-4464-ae0d-999f4c4a12fd" />
