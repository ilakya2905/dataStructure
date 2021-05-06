# Quick Sort
###### uses divide and conquer method
###### stable and in place sorting algorithm
##### Partition method
###### uses pivot value to sort - initially it is taken as the first element of the array
###### in each iteration, the pivot value is placed in its right position by making all the elements right to the pivot greater than pivot and all elements left to the pivot lesser than pivot
###### and the correct position is returned 
###### based on the pivot element position returned, the array is splitted into two and sorts the pivot value in the same way

### Time Complexity:
###### Best case and average case:
O(n*logn)
###### worst case:
O(n^2) happens only when we try to sort already sorted array
### When to use???
Efficient sorting algorithm in all ways but dont use this method to sort already sorted array because the time complexity is O(n^2)
