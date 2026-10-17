# Week-4-HW-ASSIGNMENT
Array Week 4 – Category C Practice Problems
1. Two Sum

File: TwoSum.java

Algorithm:

Read the integer array and target value.
Traverse the array using an outer loop.
For each element, use an inner loop starting from the next position.
Check whether the sum of the two elements equals the target.
If a matching pair is found, return its indices.
If no pair is found, return [-1, -1].

Time Complexity: O(n²)
Space Complexity: O(1), excluding the returned array.

2. Best Time to Buy and Sell Stock

File: BestTimeToBuyAndSellStock.java

Algorithm:

Read the array of stock prices.
Initialize the minimum price with the first element and maximum profit with zero.
Traverse the remaining prices.
Calculate the profit using the current price minus the minimum price.
Update the maximum profit if the calculated profit is greater.
Update the minimum price if the current price is smaller.
Return the maximum profit.

Time Complexity: O(n)
Space Complexity: O(1).

3. Contains Duplicate

File: ContainsDuplicate.java

Algorithm:

Read the integer array.
Use an outer loop to select each element.
Use an inner loop to compare it with all subsequent elements.
If any two elements are equal, return true.
If no duplicate is found after checking all pairs, return false.

Time Complexity: O(n²)
Space Complexity: O(1).

4. Merge Two Sorted Arrays

File: MergeTwoSortedArrays.java

Algorithm:

Read the two sorted integer arrays.
Create a result array large enough to hold all elements.
Initialize pointers for both input arrays and the result array.
Compare the current elements of the input arrays.
Copy the smaller element into the result and advance its pointer.
Continue until one input array is exhausted.
Copy all remaining elements from the other array.
Return the merged sorted array.

Time Complexity: O(n + m)
Space Complexity: O(n + m).

Here, n and m are the lengths of the two input arrays.

5. Rotate Array

File: RotateArray.java

Algorithm:

Read the integer array and the number of right rotations k.
Handle an empty or null array.
Calculate the effective rotations using k % n, where n is the array length.
Create a new array of the same size.
Traverse the original array and calculate each new position using (i + k) % n.
Place each element at its new position.
Return the rotated array.

Time Complexity: O(n)
Space Complexity: O(n).

Conclusion

These five programs demonstrate nested loops, array traversal, minimum and maximum tracking, two-pointer techniques, and modulo-based indexing in Java.
