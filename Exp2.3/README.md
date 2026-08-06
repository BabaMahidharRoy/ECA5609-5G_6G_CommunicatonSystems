# Experiment 2.3
## code
```Matlab
clc; clear; close all; 
Users = 1:8;              
TotalSlots = 5;           
Alloc = zeros(1,8);       
Alloc(1:TotalSlots) = 1;  % Assign slots to first users 
Blocked = 1 - Alloc;      
% Remaining users blocked 
disp('User Wise Slot Allocation') 
disp(table(Users',Alloc','VariableNames',{'User','Status(1=Allocated,0=Blocked)'})) 

figure 
subplot(2,1,1) 
stem(Users,Alloc,'filled','LineWidth',2) 
title('TDMA Slot Allocation per User') 
xlabel('User Index') 
ylabel('Slot Status (1=Allocated, 0=Blocked)') 
ylim([-0.2 1.2])

grid on
subplot(2,1,2) 
plot(Users,Alloc,'-o','LineWidth',2) 
hold on 
plot(Users,Blocked,'-s','LineWidth',2) 
title('TDMA Slot Utilization Analysis') 
xlabel('User Index') 
ylabel('Status') 
legend('Allocated','Blocked')
grid on 
...
```
## Output
![Output](obj3.png]
