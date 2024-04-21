# Multithreading
Methodology:
Matrix Generation: Random matrices of size 1000x1000 were generated along with a constant matrix of the same size.
Matrix Multiplication: Matrix multiplication was performed using different numbers of threads (1 to 8). The multiplication was carried out sequentially for each matrix in the set.
Time Measurement: The time taken for each multiplication operation was recorded using the time module in Python.
CPU Usage: CPU usage during each multiplication operation was monitored using the psutil library in Python.
Result Recording: The average time taken and CPU usage for each thread count were recorded.
Visualization: Results were presented in tabular form and plotted on graphs for easy interpretation.
Result Table:
The result table consists of the following columns:

Threads: Number of threads used for matrix multiplication.
Time Taken (sec): Average time taken for matrix multiplication with the specified number of threads.
CPU Usage (%): Average CPU usage during matrix multiplication with the specified number of threads.
Result Graph:
The result graph consists of two parts:

Time Taken vs. Number of Threads: This graph shows how the time taken for matrix multiplication varies with the number of threads used. It helps identify the relationship between parallelism and computation time.
CPU Usage vs. Number of Threads: This set of graphs plots the CPU usage for individual cores against the number of threads used. It provides insights into how efficiently the CPU resources are utilized with increasing thread count
