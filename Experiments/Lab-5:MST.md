# Aim : Implement and analyze Minimum cost spanning tree using Kruskal algorithm (Greedy Method)
  
# Theory : 

### 1. Greedy Method
* Used to solve optimization problems by making a series of choices, each of which looks best at the moment.
* Ensures that a locally optimal choice at each step leads to a globally optimal solution.
* Key Characteristics
  
  -- **Greedy Choice Property** : A globally optimal solution can be reached by making locally optimal choices.
  
  -- **Optimal Substructure** : A problem has an optimal substructure if an optimal solution to the problem contains optimal solutions to its subproblems.

### 2. Minimum cost spanning tree using Kruskal algorithm
- What is a Minimum Spanning Tree?
- Properties of Minimum Spanning Tree
- Applications of Minimum Spannning Tree
- Difference between Kruskals Algorithm and Prims Algorithm to construct a Minimum Spanning Tree
  
![Example](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/MST-K.png)

**Algorithm**
1. Sort all the edges in non-decreasing order of their weight.
2. Pick the smallest edge. Check if it forms a cycle with the spanning tree formed so far.
    ○ If the cycle is not formed, include this edge. 
    ○ Else, discard it. 
3. Repeat step#2 until there are (V-1) edges in the spanning tree.
 
 **Note :**
 - Greedy Choice Property: At every step, pick the minimum-weight edge without forming a cycle.
 - Optimal Substructure Property: The MST for the entire graph builds upon the MSTs of its subgraphs.

### 3. Minimum cost spanning tree using Kruskal algorithm Analysis
![Analysis](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/MST-K-Analysis.png)

# Program : 
// Attach the Program written in Java
  
# Output :
// Attach the Output

# Conclusion : 
* Understood the concept of Greedy Method.
* Understood construct Mininum Spanning Tree using Kruskals Algorithm and how Greedy Method is applied.
* Understood how to compute the Time Complexity for Mininum Spanning Tree using Kruskals Algorithm
  
# Online Resources
* [Mininum Spanning Tree using Kruskals Algorithm]()
