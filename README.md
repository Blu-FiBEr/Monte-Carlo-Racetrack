# Problem Statement:
- Consider driving a race car in a race track as shown in the excel sheet .
- The car will always be at any one of the discrete grid positions shown in the sheet.
- The green grids are start positions and orange are finishing positions.
- The blue grid represent valid positions the car can take.
- The red grids represents the boundaries which the car is supposed to avoid.
- The velocity is discrete and is the number of grid cells moved horizontally and vertically per time step.
- The agent can control the acceleration of the car. It has to learn which accelerations are optimal for different states.

# Solution:
- Both On-Policy and Off-Policy Monte Carlo learning methods have been implemented.
- The perfomance of both methods has been analysed in the report.
- The report also presents the different algorithmic tricks used for efficient practical implementations.
- The single ipynb file contains code for modelling both the racetrack environment and the agent controling the car.
- Pygame has been used to visualize the optimal paths that the agent learns.

# How to run:
## To run the programme:
1. First run the cell under Imports section
2. Then run the cells under Environment Section
3. Then run the cells under On-Policy agent section
4. Then run the cells under Off-Policy agent section
5. Then run the cells according to which agent you want to see.
6. For, visualisation, you will have to run the "On_policy_test()" function again and again to see different starting states.
7. Same for "Off_policy_test()".
