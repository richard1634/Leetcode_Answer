Approach 1: Two Pointer Approach (Accepted) 

Algorithm

The intuition behind this approach is that there is a pointer for every number of the sum. Having three pointers allows the algorithm to make a minimal amount of passes on the array. By sorting the input array, we can move the pointers right if the sum is too small or left if it is too big.

How this approach works? 

Initially, we create a for loop for iterating the array. During each iteration of the array, we take two pointers, one after the index of the current iteration(named left pointer) and one at the end of the array (named right pointer). If the sum of these pointers is 0, we append the pointers to the result array and continue. Since the array is sorted, if the result is too small, we can continuously move the left pointer right one index to yield a higher sum. If the result is too big, we can continuously move the right pointer left to find a smaller sum. We can continuously move the left and right pointers until we find a sum of 0 or until the left pointer’s index meets the right pointer’s index, meaning every possible combination has been scanned.


Complexity Analysis: O((N^2)/2) = O(n^2).
Space complexity: Space for 2 pointers. O(1). Constant space is used.
