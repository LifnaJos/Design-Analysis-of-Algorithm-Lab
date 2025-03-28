# Aim : Implement and analyze Longest common subsequence (Dynamic Programming)
  
# Theory : 
#### 1. Dynamic Programming
- Its a strategy used in algorithm design to solve optimization problems
- It breaks down the given problem into smaller overlapping subproblems and storing their solutions to avoid redundant computations.
- **Key Concepts of Dynamic Programming**
   1. **Optimal Substructure** : Deriving the solution to the overall problem from the solutions of its subproblems.
   2. **Overlapping Subproblems** : if the same smaller problems are solved multiple times.
   3. **Memoization (Top-Down Approach)** : Store the results of previously solved subproblems in a table (hashmap or array) to avoid recomputation.
   4. **Tabulation (Bottom-Up Approach)** : Solve smaller subproblems first and use their results to build up the solution to larger subproblems.
#### 2. Longest Common Subsequene (LCS) Problem
Given two sequences (strings), find the Longest Common Subsequence (LCS) that appears in both strings in the same relative order but not necessarily contiguous.

**Subsequence** : string generated from the original string by deleting 0 or more characters, without changing the relative order of the remaining characters.

![Example](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/lcs-ex.png)

#### 3. Algorithm to compute LCS using DP Method and Simulation
1. **Define the DP Table**
   
   dp[n][m] of order (n+1) *( m+1)        // where n = len(X) and m = len(Y)

![LCS-sol-1](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/lcs-sol-1.png)

2. **Define a Recurrence Relation**

a. If X[i−1] == Y[j−1] 

  dp[i][j] = 1 + dp[i−1][j−1]          //then this character is part of LCS

b. Else

  dp[i][j] = max⁡(dp[i−1][j], dp[i][j−1])

![LCS-sol-2](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/lcs-sol-2.png)

3. **LCS Construction**

a. Start from dp[m][n]         //(bottom-right corner of the table).

b. If X[i−1]==Y[j−1], 

   add X[i]  to the result.

c. Else

   move to the direction where dp[i][j] has the maximum value.

![LCS-sol3](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/lcs-sol.png)

#### 4. Complexity Analysis
![Analysis](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/lcs-complexity.png)

# Program : 
// Attach the Programs written in Java
  
# Output :
// Attach the Output

# Conclusion : 
* Understood the concept of Dynamic Programming (DP) method
* Understood the logic behind computing Longest Common Subsequence using DP method.
* Understood how to calculate the Complexity of LCS using DP method
  
# Online Resources
- [Longest Common Subsequence - Visualization-1](https://algorithm-visualizer.org/dynamic-programming/longest-common-subsequence)
- [Longest Common Subsequence - Visualization-2](https://lcs.netlify.app/)
- [Longest Common Subsequence - Visualization-3](https://www.cs.usfca.edu/~galles/visualization/DPLCS.html)
