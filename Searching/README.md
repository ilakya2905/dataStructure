# Searching
Searching is the process of finding some particular element in the list.
## Binary Search:
1. Binary search follows divide and conquer approach in which, the list is divided into two halves and the item is compared with the middle element of the list. 

2. If the match is found then, the location of middle element is returned otherwise, we search into either of the halves depending upon the result produced through the match.

3. The list should be sorted.

4. Time Complexity  - O(log(n)

## Linear Search:
1. Linear search is the simplest search algorithm and often called sequential search. 

2. In this type of searching, we simply traverse the list completely and match each element of the list with the item whose location is to be found. 

3. If the match found then location of the item is returned otherwise the algorithm return NULL.

4. Linear search is mostly used to search an unordered list in which the items are not sorted. 

5. Time Complexity - O(n)

## Interpolation Search:
1. The Interpolation Search is an improvement over Binary Search for instances, where the values in a sorted array are uniformly distributed. 

2. Binary Search always goes to the middle element to check. On the other hand, interpolation search may go to different locations according to the value of the key being searched.

3. mid = Low + ((High - Low) / (A[High] - A[Low])) * (item to be searched - A[Low])

4. Time Complexity - O(log(log(n)))
