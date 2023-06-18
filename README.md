# Windy-Grid-World
Windy Grid World Solution(using SARSA_Q-learning)
Windy Grid World (Sutton & Barto, pg. 130,131)
Consider the game depicted in the following diagram
![image](https://github.com/Lomai9/Windy-Grid-World/assets/77353623/fe72e58a-b1d1-4175-b6dc-b0ab7cd06b75)
You are to implement several algorithms to solve this problem:
1. Sarsa
2. Q-learning
Compare all solutions in terms of the optimal policies and episodes necessary for convergence. Select 
the best values for  ε   and α for each case. If they are different, discuss why. 
Re-solve the windy gridworld task with King’s moves, assuming that the effect of the wind, if there is 
any, is stochastic, sometimes varying by 1 from the mean values given for each column. That is, a third 
of the time you move exactly according to these values, as in the previous exercise, but also a third of 
the time you move one cell above that, and another third of the time you move one cell below that. 
For example, if the agent is one cell to the right of the goal and it chooses to move left, then one-third of 
the time the agent will move one cell above the goal, one-third of the time you move two cells above 
the goal, and one-third of the time you move to the goal. YOU SHOULD ONLY USE THIS APPROACH

Mathematically, when the wind is defined by w, the location of the agent in y after the execution of the 
action without stochastic wind will be y = a(s) + w. Then, the stochastic output y— will be:
![3](https://github.com/Lomai9/Windy-Grid-World/assets/77353623/2d78b98a-6c5f-4159-9c75-8b7f92cf7317)
