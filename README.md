# 0x1B. C - Sorting algorithms & Big O

- sorting algorithm is an algorithm that puts elements of a list into an order
- A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

## Tasks in this project
0) 0. Bubble sort
1) Insertion sort
2) Selection sort
3) Quick sort
4) Shell sort - Knuth Sequence
5) Cocktail shaker sort
6) Counting sort
7) Merge sort
8) Heap sort
9) Radix sort
10)  Bitonic sort
11) Quick Sort - Hoare Partition scheme
12) Dealer

### Big O notation Summary
The O in "Big O" refers to as "Order"(or precisely "order of")
so you could get its idea literally that it's used to order something to compare them.

#### "Big O" does two things:
- Estimates how many steps of the method your computer applies to accomplish a task.
- Facilitate the process to compare with others in order to determine whether it's good or not?
- "Big O' achieves the above two with standardized Notations.

In practice, there are a very limited number of big-Oh expressions that you will encounter and need to worry about:

The good:
- O(1) Constant: The program takes the same time to run no matter how big the input is.
- O(log n) Logarithmic: The program run-time increases only slowly, even with big increases in the size of the input.

The bad:
- O(n) Linear: The program run-time increases proportionally to the size of the input.
- O(n^k) Polynomial: - Processing time grows faster and faster - as a polynomial function - as the size of the input increases.
... and the ugly:

- O(k^n) Exponential The program run-time increases very quickly with even moderate increases in the size of the problem - it is only practical to process small data sets with exponential algorithms.
- O(n!) Factorial The program run-time will be longer than you can afford to wait for anything but the very smallest and most trivial-seeming datasets. 
