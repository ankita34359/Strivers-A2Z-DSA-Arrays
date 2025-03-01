# Find the Largest element in an array by sorting the array in ascending order.

## Theory Solution1: Sorting

We can sort the array in ascending order, hence the largest element will be at the last index of the array. 

## Approach: 

Sort the array in ascending order.

Print the (size of the array -1)th index.

## DryRun: 

Before sorting: arr[] = {2,5,1,3,0};

After sorting: arr[] = {0,1,2,3,5};

**Hence answer** : arr[sizeofthearray-1] =5

## Complexity Analysis

Time Complexity: O(N*log(N))

Space Complexity: O(n)

## Solution

(!Screenshot)[i1.png]
