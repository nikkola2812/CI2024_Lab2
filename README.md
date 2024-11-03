# CI2024_Lab2
This solution for the Traveling Salesman Problem is using two different approaches:

Greedy Algorithm (Nearest Neighbor): This algorithm begins at a designated starting city and iteratively selects the nearest unvisited city to visit next. It continues this process until all cities have been visited, finally returning to the starting city. The greedy approach is simple and fast, but it does not always yield the optimal solution.

Steady-State Evolutionary Algorithm: This genetic algorithm starts by generating a population of random paths that represent possible solutions. It also uses cycle crossover to combine the genetic information of two parent paths to produce offspring therefore enhancing the diversity of the population. Also, random mutations are introduced to further explore the solution space. After several generations, the algorithm is supposed to select the best-performing paths based on their total travel cost aiming to find a near optimal solution, however I was struggling with the results having face the error of 'ERROR:root:Path must start and end at the same city.'

