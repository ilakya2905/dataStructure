# Counting Sort
###### not in place, stable sorting algorithm
###### find the max element from the array
###### create a new array with size 1 greater than the maximum element and initize the array elements to 0 and another array for output with size n
###### for each element in the original array, increament the value of that element in new array created (ie) if element = 3, then -> newArray[3]++;
###### store the cummlative sum of all the elements in the new array 
###### for each element in the original array: do the following
if 3 is the element from original array --->indexInOutput = newArray[3]-1  -----> output[indexInoutput] = 3 and decrement the value in new array --> newArray[3]--

### Time complexity:
##### For all three cases: O(n+k)

### Space complexity: O(max)

### When to use?
use when the maximum element is smaller because it uses more space.
