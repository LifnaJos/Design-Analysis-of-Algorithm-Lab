# Aim : Implement and analyze Quick sort  (Divide & Conquer)
  
# Theory : 

### 1. Divide & Conquer Strategy
The Divide-And-Conquer paradigm uses the following strategy to solve problems.
- Step - 1 : Break the problem into subproblems
- Step - 2 : Solve the subproblems (recursively)
- Step - 3 : Combine results of the subproblems

### 2. Quick Sort Algorithm
Given an array A of n numbers
- Step - 1 : Pick some element x ← A[i]. We call x the pivot.
- Step - 2 : Split the rest of A into A< (the elements less than x) and A> (the elements greater than x).
- Step - 3 : Rearrange A into [A<, x, A>].
- Step - 4 : Recurse on A<, A>.

![Algorithm](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/Screenshot%20from%202025-02-10%2020-05-08.png)

### 3. Quick Sort Example

![Example-0](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/partitionA.png)

![Example-1](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/partitionB.png)

### 4. Quick Sort Analysis

![Analysis]()

# Program : 
// Attach the Program written in Java
- Task - 1 : Write a simple Java program to perform sorting and check the correctness of the code.
- Task - 2 : Randomize the code to accept the input size from the user and invoke random function to generate numbers in the array.
- Task - 3 : Track the #Comparisons, #Swaps and also use time function in Java to measure the time taken for sorting
- Task - 4 : Generate the following table for Analysis
  
| Input size, N | #Comparisons | #Swaps  | Time taken (ns) |
| :-------------:| :--------: | :--------------:  | :----------: |
| 10             |    |   |  |  |
| 100             |    |   |  |  |
| 1000             |    |   |  |  |
| 10000             |    |   |  |  |
| 100000             |    |   |  |  |
| 100000             |    |   |  |  |

- Task - 5 : Plot the graph with N on the X-axis and T(n) on the Y-axis
  
# Output :
// Attach the Output

# Conclusion : 
* Understood the concept of Divide and Conquer Strategy upon Quick Sort
* Was able to compute the Time Complexity of both the Sorting techniques based on Recurrence Relations
* Implemented and tested the complexity of the Quick Sort

# Online Resources
* [Quick Sort](https://web.stanford.edu/class/archive/cs/cs161/cs161.1166/lectures/lecture5.pdf)
