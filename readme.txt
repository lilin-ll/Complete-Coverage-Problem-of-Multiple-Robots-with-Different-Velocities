The presented 

%*************************Experiment-B   Comparison Experiments with Balanced MRTA algorithms********************%
Simulation setup: A set oftwenty mission environmentsisrandomlygeneratedandmodeledintobinary images . More precisely,
• The size of the mission environment includes two classes: Small ([ROW,COL] = 55×55 cells) and Medium ([ROW,COL] = 100×100 cells).
• The number of obstacles includes two levels: 10% and 20% of the total number of cells in the mission envi- ronment. A random function automatically generates the row and column coordinates of every obstacle.
• The number of robots varies from 10, 20, 30, 40, 50, 80 to 100 robots.
• Random robots' starting positions.
Moreover, in order to produce comparable results, we randomly generated 10 sets of robot starting points for each environment and applied the credit-based algorithm in environments with different starting points.

Simulation Data:
The \in folder saves the 10 sets of robot starting points for each environment. 
The \out folder saves the corresponding MRTA results of the credit-based algorithm.

%************** Experiment-C   Comparison Experiments with unBalanced optimal MRTA ******************%
Simulation setup: A set of sixteen target areas are randomly generated and have been modeled into binary images according to the approach in 35 . More precisely,
• The size of mission environment includes four classes: Small ([ROW,COL] = 55×55 cells) , Medium ([ROW,COL] = 100×100 cells), Large ([ROW,COL] = 200×200 cells) and VeryLarge ([ROW,COL] = 300×300 cells).
• The number of obstacles includes two levels: 10%  and 20% of the total number of cells in the mission environment. A random function automatically generates the row and column coordinates of every obstacle.
• The number of robots varies from 10, 30, 40, 50, 100, 150, 200 to 300 robots.
• A random function automatically generates the row and column coordinates of robots’starting positions.
•We generate an integer array by a random function and normalize it to a float array. The optimal task numbers for a multi-robot system are obtained by multiplying the total number of tasks and the normalized array.

Simulation Data:
The 'matlab_in' file saves the information of the target areas and robots’starting positions,.
The 'ratio_in' file saves the  float array, which equals to the optimal task numbers of the multi-robot system divided by the total number of tasks.
The 'matlab_out' file represents the correponding MRTA results.






 