# Aim : To Analyze Sorting Techniques
1. [Selection Sort](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/Lab%20-1%20:%20Analysis%20of%20Sorting%20Techniques.md#selection-sort-algorithm)
2. [Insertion Sort](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/Lab%20-1%20:%20Analysis%20of%20Sorting%20Techniques.md#2-insertion-sort-algorithm)
  
# Theory : 

### 1. Selection Sort Algorithm
![Algorithm](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/selection-sort.jpg)

### Selection Sort Example
##### Step 0: Consider the Initial Array, arr[] = {17, 34, 25, 49, 09} 
The entire array is currently unsorted. The sorted portion is empty.

#### Step 1: 1st Iteration
Find the smallest element in the entire array and swap it with the first position.

| i | j | minindex | arr[] | Comparison (arr[i] vs arr[j]) | Swap?| Updated Array |
| - | - | -------- | ----- | ----------------------------- | ---- | ------------- |
| 0 |	1 |	0	| [17, 34, 25, 49, 9]	| 17 < 34 |	No |	[17, 34, 25, 49, 9] |
| 0	| 2	| 0	| [17, 34, 25, 49, 9]	| 17 < 25	| No | [17, 34, 25, 49, 9] |
| 0	| 3 | 0 |	[17, 34, 25, 49, 9]	| 17 < 49	| No | [17, 34, 25, 49, 9] |
| 0	| 4	| 4 |	[17, 34, 25, 49, 9]	| 17 > 9	| Yes	| [9, 34, 25, 49, 17] |

arr[] = {09, 34, 25, 49, 17}
The first element, 09 is now in its correct position, and the array is divided into a sorted portion {09} and an unsorted portion {34, 25, 49, 17}.

## Step 2: 2nd Iteration
Find the smallest element in the remaining unsorted portion {34, 25, 49, 17} and swap it with the second position.

| i | j | minindex | arr[] | Comparison (arr[i] vs arr[j]) | Swap?	| Updated Array |
| - | - | -------- | ----- | ----------------------------- | ---- | ------------- |
| 1 |	2 |	1 |	[9, 34, 25, 49, 17]	| 34 > 25 |	No |	[9, 34, 25, 49, 17] |
| 1	| 3	| 2	| [9, 34, 25, 49, 17]	| 34 < 49	| No | [9, 34, 25, 49, 17] |
| 1	| 4 |	4	| [9, 34, 25, 49, 17]	| 34 > 17	| Yes	| [9, 17, 25, 49, 34] |

arr[] = {09, 17, 25, 49, 34}
Here, sorted portion is {09,17} and unsorted portion is {25,49,34}

## Step 3: 3rd Iteration
Find the smallest element in the remaining unsorted portion {25, 49, 34} and swap it with the third position.

| i | j | minindex | arr[] | Comparison (arr[i] vs arr[j]) | Swap?	| Updated Array |
| - | - | -------- | ----- | ----------------------------- | ---- | ------------- |
| 2	| 3	| 2 |	[9, 17, 25, 49, 34]	| 25 < 49	| No |	[9, 17, 25, 49, 34] |
| 2	| 4	| 2	| [9, 17, 25, 49, 34]	| 25 < 34	| No |	[9, 17, 25, 49, 34] |

At the end of this iteration, element 25 is already in its correct position.

arr[] = {09, 17, 25, 49, 34}
Here, sorted portion is {09,17,25} and unsorted portion is {49,34}

## Step 4: 4th Iteration
Find the smallest element in the remaining unsorted portion {49, 34} and swap it with the fourth position.

| i | j | minindex | arr[] | Comparison (arr[i] vs arr[j]) | Swap?	| Updated Array |
| - | - | -------- | ----- | ----------------------------- | ---- | ------------- |
| 3	| 4	| 3	| [9, 17, 25, 49, 34]	| 49 > 34	| Yes |	[9, 17, 25, 34, 49] |

Now, after the 4th iteration, only one element remains 49, which is inherently in its correct place as it’s the last and largest element in the list.

So, at the end of the 4th iteration, the entire array is sorted in ascending order:

arr[] = {09, 17, 25, 34, 49}
That completes the selection sort for the given array

==========================================================================

### 2. Insertion Sort Algorithm
![Algorithm](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/Insertion_Sort-0.jpg)

### Insertion Sort Example
![Example](https://github.com/LifnaJos/Design-Analysis-of-Algorithm-Lab/blob/main/Experiments/Insertion-Sort-example.jpg)

# Program : 
// Attach the Program 
# Output :
// Attach the Output
# Conclusion : 
* Understood the concept of Selection Sort & Insertion Sort
* Was able to compute the Time Complexity of both the Sorting techniques based on Frequency Count Method
* Implemented and tested the complexity of the Sorting techniques.

# Online Resources
* [Selctrion Sort - Shiksha.com](https://www.shiksha.com/online-courses/articles/selection-sort/)
* [Insertion Sort](https://naemazam.medium.com/insertion-sort-algorithm-in-data-structures-with-example-7129003768ba)
