# EXP11.1
## Code
```Matlab
clc;
clear;
close all; 
time = 1:10; 
soil_moisture = [30 35 28 25 20 18 22 30 40 45]; 
threshold = 40; 
figure 
subplot(2,1,1) 
plot(time, soil_moisture, '-o', 'LineWidth', 2) 
title('Soil Moisture Monitoring in IoT Smart Agriculture') 
xlabel('Time (Hours)') 
ylabel('Soil Moisture (%)') 
grid on 
hold on 
yline(threshold,'r--','Threshold') 
status = soil_moisture >= threshold; 
subplot(2,1,2) 
stem(time, status, 'filled', 'LineWidth', 2) 
title('Soil Condition Status (1=Wet, 0=Dry)') 
xlabel('Time (Hours)') 
ylabel('Status') 
grid on
...
```
## Output
![Output](obj1.png)<img width="707" height="537" alt="obj1" src="https://github.com/user-attachments/assets/024809c6-633a-454e-8f00-88a10f5b1099" />
