Project 03: Knapsack
Goals of the project
Solve the knapsack problem using dynamic programming. 
Compare and contrast with "greedy" approach to solving the problem.
Input:


Given n items and corresponding value vector v1, v2, ..., vn and the weight vector w1, w2, ..., wn. Let k = capacity of the knapsack. 

All of these will be read from text files: File _c.txt contains the capacity, _v.txt contains n values and _w.txt contains n weights. Some files to test your program can be download from here. Note: Files p00_c.txt, p00_v.txt and p00_w.txt contain data for the problem that we solved in class.

Task 1: Dynamic Programming approach

Implement dynamic programming based algorithm to determine the optimal value of the knapsack and the set of items that yield this optimal value. (see sample output below)
Task 2: Greedy approach
Implement a greedy algorithm that arranges the the objects in the decreasing order of value to weight ratio, then select the objects in this order until the weight of the next object exceeds the remaining capacity.
Task 3: Comparison
Display the optimal values, subset yielding the optimal value and CPU times of both approaches. Note, items begin with index 1 and so the set of all items = {1, 2, 3, ...., n}
Task 4: Analysis
Compare and contrast the CPU times of both approaches in form of a graph that plots n (number of items) on x-axis and time on y-axis (for each of task 1 and task 2).
Comment on which approach is faster and why?
