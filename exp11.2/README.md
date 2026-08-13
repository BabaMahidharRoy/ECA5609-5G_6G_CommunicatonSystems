# EXP11.2
## Output
```Matlab
clc;
clear;
close all; 
time = 1:10; 
soil_moisture = [30 35 28 25 20 18 22 30 40 45]; 
threshold = 40;
pump_status = soil_moisture < threshold; 
figure 
subplot(2,1,1) 
plot(time, soil_moisture, '-o','LineWidth',2) 
title('Soil Moisture vs Pump Control') 
xlabel('Time (Hours)') 
ylabel('Soil Moisture (%)') 
grid on 
hold on 
yline(threshold,'r--','Threshold') 
subplot(2,1,2) 
stem(time, pump_status, 'filled','LineWidth',2) 
title('Water Pump Status (1=ON, 0=OFF)') 
xlabel('Time (Hours)') 
ylabel('Pump Status') 
grid on
...
```
## Output
![Output](obj2.png)<img width="698" height="529" alt="obj2" src="https://github.com/user-attachments/assets/eb845214-9ef0-4007-80aa-65fbca94ed85" />
