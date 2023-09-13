# Sorting-Visualizer
This project is a very simple UI and it allows the users to visualize different sorting algorithms. I have given an option to select the array size, and speed of the visualization and the sorting algorithm. Each element of the array is displayed as a bar. The operations are colour coded such that:

Blue - Element is in unsorted position
Yellow - Selected
Red - Swap the bars
Green - Element is in sorted position
There are numerous sorting algorithms available, each with unique properties and ideal application scenarios. Here are a few popular sorting formulas:

Bubble Sort: Easy to understand. Due to its O(n2) time complexity, it is not appropriate for processing huge datasets. If the items are in the improper sequence, it continuously switches the neighbouring ones.

Insertion Sort: Effective for tiny datasets or data that is almost sorted. Has an O(n2) worst-case and average time complexity. By continually inserting a new element into the portion of the array that has already been sorted, builds the final sorted array one item at a time.

Selection/Choosing Sort: Simple and simple to comprehend. O(n2) and unsuitable for huge datasets. The input is split into a sorted and an unsorted region, and then the minimal element is repeatedly chosen from the unsorted part and moved to the sorted region.

Merge/Combine Sort: A strategy of "divide and conquer." Efficient for large datasets, with an O(n log n) time complexity. Splits the input array in half, sorts the two halves iteratively, and then combines the two sorted halves.

Quick/Fast Sort: One more divide-and-conquer strategy. For smaller datasets, merge sort is typically faster. has a worst-case time complexity of O(n log n) and an average time complexity of O(n log n). selects a "pivot" element and divides the array into two sub-arrays, with elements greater than the pivot on the right and those less than the pivot on the left. The sub-arrays are sorted recursively.

Heap/Stack Sort: Efficient for sizable datasets, with a steady O(n log n) time complexity. Creates a binary heap, from which the maximum element is repeatedly extracted to create the sorted array.

Radix Sort: Suitable for sorting fixed-length texts or numbers. The time complexity varies with the amount of characters or digits, usually being O(nk), where k is the number of characters or digits.

Bucket/Container Sort: Helpful for grouping items into a few buckets. Time complexity can range from O(n) to O(n2) and is dependent on the distribution of the elements.
