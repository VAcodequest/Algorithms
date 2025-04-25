# Algorithms
This particular repository contains Python code from my learning experience. This contains everything I know about algorithms and everything I am currently learning.

### ◇ Binary Search:  
Searches a sorted array in O(log n) time by repeatedly dividing the search interval in half.

### ◇ Linear Search:  
Examines each element sequentially until the target value is located or the end of the array is reached.

### ◇ Jump Search:  
Advances by fixed intervals (√n) in a sorted array, then performs a linear scan within the identified block.

### ◇ Bubble Sort:  
Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. Simple but inefficient (O(n²)).

### ◇ Selection Sort:  
Finds the minimum element from the unsorted part and places it at the beginning. Performs well on small datasets but has O(n²) complexity.

### ◇ Insertion Sort:  
Builds the final sorted list one item at a time by comparing each new element to those already sorted and inserting it at the correct position.

### ◇ Merge Sort:  
A divide-and-conquer algorithm that splits the array into halves, recursively sorts them, and merges the sorted halves into a final sorted array. Runs in O(n log n) time.

### ◇ Heap Sort:
Transforms the input array into a max heap structure, then repeatedly extracts the maximum element and maintains the heap property. Offers consistent O(n log n) performance and does not require additional memory for recursion.

### ◇ Quick Sort:
A divide-and-conquer algorithm that selects a pivot element, partitions the array around the pivot, and recursively applies the same strategy to the sub-arrays. Efficient for large datasets with average-case time complexity of O(n log n).

### ◇ Counting Sort
A non-comparative sorting algorithm ideal for sorting integers in a fixed range. It counts the occurrences of each element and calculates their positions directly. Runs in O(n + k) time where k is the range of input values.

### ◇ Radix Sort
A non-comparative sorting algorithm that processes integer keys digit-by-digit, from the least significant digit to the most significant. It relies on a stable sub-sorting method (like Counting Sort) and runs in O(nk) time, where k is the number of digits.
