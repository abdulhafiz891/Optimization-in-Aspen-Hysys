# Optimization-in-Aspen-Hysys
Numerical calculation to find a Min or Max value

![Aspen_Hysys_V12.1](https://img.shields.io/badge/Aspen%20Hysys-V12.1-brightgreen)

The Process Flow Diagram from the process

![image](https://user-images.githubusercontent.com/121662875/230938694-611255d7-8028-4567-a5d8-50008c072254.png)

A distillation column is used for the optimization simulation

# Step 1
![image](https://user-images.githubusercontent.com/121662875/230940165-c300328b-b7f5-429c-983f-10505afa75b2.png)

The optimizer can be access from the home tab, find optimizer. Then set which streams as the variables, lower and upper boundry. 

# Step 2

![image](https://user-images.githubusercontent.com/121662875/230940083-abbf495b-e3a8-4315-ac20-07637096d5e3.png)

From the optimizer, click the spreadsheet at the bottom left to set the specific parameter that can be modified. In this simulation, the condenser and reboiler duty, light key component at the top : mass flow and mass fraction, heavy key component at the bottom : mass flow and mass fraction are the variables. Total 6 variables to from an equation below to find the lowest cost for maximum yield.

![image](https://user-images.githubusercontent.com/121662875/230942511-58aba909-0312-47a6-b4c9-f5fbe8b4cd40.png)

Add another 5 variables which are the cost of the feed, utilities and products price. ignore the profit price because initially it was not calculated.

# The formula
![image](https://user-images.githubusercontent.com/121662875/230943006-c644cce6-30d2-440e-a2e0-cc81f8ca8bcb.png)

# Conclusion
The optimization can be part of a full process that can use multiple times in a single simulation. For simplicity, it is shown for one equipment but it can be done for more than one. Other than distillation column, reactor or any other major equipment can be tested for the highest yield. 
