# daa-insertion_sort
Objective
Implement the Insertion Sort algorithm and analyze its time and space complexities.

Programming Language
Python

Algorithm
Start from the second element.
Store the current element as the key.
Compare the key with previous elements.
Shift larger elements one position to the right.
Insert the key at the correct position.
Repeat until the array is sorted.
How to Run
Install Python 3.

Open the terminal.

Execute the following command:

python insertion_sort.py
Enter the number of elements.

Enter the array elements.

View the sorted output.

Sample Input
6
64
25
12
22
11
90
Sample Output
Enter number of elements: 6
Enter the elements:
64
25
12
22
11
90
Sorted Array:
11 12 22 25 64 90
Time Complexity
Case	Big O	Theta (Θ)	Omega (Ω)
Best Case	O(n)	Θ(n)	Ω(n)
Average Case	O(n²)	Θ(n²)	Ω(n²)
Worst Case	O(n²)	Θ(n²)	Ω(n²)
Space Complexity
O(1) – Insertion Sort is an in-place sorting algorithm that requires constant auxiliary space.
Advantages
Simple to implement.
Efficient for small datasets.
Stable sorting algorithm.
In-place sorting algorithm.
Disadvantages
Inefficient for large datasets.
Average and worst-case time complexity is O(n²).
Course Outcome
CO1 – Analyze any given algorithm and express its time and space complexities using asymptotic notations.

