# Aim : Implement and analyze Fractional Knapsack Problem (Greedy Method)
  
# Theory : 

### 1. Greedy Method
* Used to solve optimization problems by making a series of choices, each of which looks best at the moment.
* Ensures that a locally optimal choice at each step leads to a globally optimal solution.
* Key Characteristics
  
  -- **Greedy Choice Property** : A globally optimal solution can be reached by making locally optimal choices.
  
  -- **Optimal Substructure** : A problem has an optimal substructure if an optimal solution to the problem contains optimal solutions to its subproblems.

### 2. Fractional Knapsack Problem & Solution
![Problem](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/f1.png)

**Algorithm**
1. Sort items in descending order based on their value/weight ratio.
2. Iterate through the sorted items, adding as much as possible to the knapsack:
   * If the item fits completely, take the whole item.
   * If the item does not fit completely, take a fraction of it.
5. Stop when the knapsack is full.

### 3. Fractional Knapsack Analysis
* Sorting the items: O(nlog⁡n) (since sorting takes log time)
* Iterating through items: O(n) (one scan of the items)
* Overall complexity: O(nlog⁡n)

# Program : 
// Attach the Program written in Java
  
# Output :
// Attach the Output

# Conclusion : 
* Understood the concept of Greedy Method.
* Understood Fractional Knapsack Problem and how to apply Greedy Method to solve the problem.
* Understood how to compute the Time Complexity for Fractrional Knapsack Problem Algorithm
  
# Online Resources
* [Fractional Knapsack Problem](https://www.hello-algo.com/en/chapter_greedy/fractional_knapsack_problem/)
* [0/1 Knapsack Simulation](https://augustineaykara.github.io/Knapsack-Calculator/)
