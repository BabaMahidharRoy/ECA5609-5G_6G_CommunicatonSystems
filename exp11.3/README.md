# EXP 11.3
## Output
```Matlab
clc;
clear;
close all; 
time = 1:10; 
soil_moisture = [30 35 28 25 20 18 22 30 40 45]; 
threshold = 40; 
efficiency = (soil_moisture ./ threshold) * 100; 
efficiency(efficiency > 100) = 100; % limit to 100% 
figure 
subplot(2,1,1) 
plot(time, soil_moisture, '-o','LineWidth',2) 
title('Soil Moisture Variation') 
xlabel('Time (Hours)') 
ylabel('Soil Moisture (%)') 
grid on 
hold on 
yline(threshold,'r--','Threshold') 
subplot(2,1,2) 
plot(time, efficiency, '-s','LineWidth',2) 
title('Irrigation Efficiency (%) in Smart Agriculture') 
xlabel('Time (Hours)') 
ylabel('Efficiency (%)') 
grid on
...
```
## Output
![Output](obj1.png)<img width="1399" height="688" alt="obj1" src="https://github.com/user-attachments/assets/cc63c88e-0179-4827-aafd-f6ff6b49b134" />
