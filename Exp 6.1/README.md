<img width="1466" height="508" alt="obj1" src="https://github.com/user-attachments/assets/2609e03f-fa8c-45da-8be7-fdaaaf7f8bbe" />
# Experiment 6.1
## Code
```Matlab
clc; 
clear; 
close all; 
scs = [15 30 60 120 240];      
mu = 0:4;                      
bar(scs) 
grid on 
set(gca,'XTick',1:5) 
set(gca,'XTickLabel',mu) 

xlabel('Numerology Index (\mu)') 
ylabel('Subcarrier Spacing (kHz)') 
title('5G NR Subcarrier Spacing for Different Numerologies')
...
```
## Output
![Output](obj1)
