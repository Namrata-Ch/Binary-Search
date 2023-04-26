# Binary-Search

Binary Search is a searching algorithm for finding an element's position in a sorted array.In this approach, the element is always searched in the middle of a portion of an array.
Binary search can be implemented only on a sorted list of items. If the elements are not sorted already, we need to sort them first.

# Conditions for when to apply Binary Search in a Data Structure:

To apply binary search in any data structure, the data structure must maintain the following properties:

The data structure must be sorted.
Access to any element of the data structure takes constant time

# How to Implement Binary Search?
The basic steps to perform Binary Search are:

Set the low index to the first element of the array and the high index to the last element.
Set the middle index to the average of the low and high indices.
If the element at the middle index is the target element, return the middle index.
Otherwise, based on the value of the key to be found and the value of the middle element, decide the next search space.
If the target is less than the element at the middle index, set the high index to middle index – 1.
If the target is greater than the element at the middle index, set the low index to middle index + 1.
Perform step 2 repeatedly until the target element is found or the search space is exhausted.
The Binary Search Algorithm can be implemented in the following two ways

Iterative Binary Search Algorithm
Recursive Binary Search Algorithm
