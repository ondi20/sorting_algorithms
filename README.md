# sorting_algorithms
Alx project on Sorting Algorithm.
Objectives
    At least four different sorting algorithms
    What is the Big O notation, and how to evaluate the time complexity of an algorithm
    How to select the best sorting algorithm for a given input
    What is a stable sorting algorithm

**Four Different Sorting Algorithms:**

1. **Bubble Sort:**
   - Time Complexity:
     - Best Case: O(n) (when the array is already sorted)
     - Average Case: O(n^2)
     - Worst Case: O(n^2) (when the array is sorted in reverse order)
   - Explanation: Bubble sort compares adjacent elements and swaps them if they are in the wrong order. It repeats this process until the array is sorted.

2. **Insertion Sort:**
   - Time Complexity:
     - Best Case: O(n) (when the array is already sorted)
     - Average Case: O(n^2)
     - Worst Case: O(n^2) (when the array is sorted in reverse order)
   - Explanation: Insertion sort builds the sorted array one element at a time by repeatedly taking elements from the unsorted part and inserting them into their correct position.

3. **Merge Sort:**
   - Time Complexity:
     - Best Case: O(n log n)
     - Average Case: O(n log n)
     - Worst Case: O(n log n)
   - Explanation: Merge sort follows the divide-and-conquer strategy. It recursively divides the array into halves, sorts each half, and then merges them back together.

4. **Quick Sort:**
   - Time Complexity:
     - Best Case: O(n log n)
     - Average Case: O(n log n)
     - Worst Case: O(n^2) (rare, occurs when the pivot selection is poor)
   - Explanation: Quick sort also uses the divide-and-conquer approach. It selects a pivot element and partitions the array into two sub-arrays such that elements smaller than the pivot are on the left, and elements larger than the pivot are on the right.

**Big O Notation:**
- Big O notation is a way to describe the upper bound of the time complexity of an algorithm. It provides an asymptotic analysis, describing how the time complexity grows relative to the size of the input.

**Evaluating Time Complexity:**
- Analyzing the number of basic operations an algorithm performs as a function of the input size.
- Ignoring constant factors and lower-order terms.
- Focus on the dominant factor that has the most significant impact on the growth rate.

**Selecting the Best Sorting Algorithm:**
- Depends on the characteristics of the input data and the specific requirements.
- Consider the size of the input (small or large), whether the data is nearly sorted, and the space complexity.
- For small datasets or nearly sorted data, simpler algorithms like Insertion Sort or Bubble Sort may be efficient.
- For larger datasets, Merge Sort or Quick Sort, with their better average time complexity, are often preferred.

**Stable Sorting Algorithm:**
- A sorting algorithm is stable if the relative order of equal elements is preserved in the sorted output.
- For example, if there are two elements with equal keys in the input, a stable sort will guarantee that their order remains the same in the sorted output.
- Examples of stable sorting algorithms include Merge Sort and Insertion Sort.