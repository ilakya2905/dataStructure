# Linear Queue
1. A queue can be defined as an ordered list which enables insert operations to be performed at one end called REAR and delete operations to be performed at another end called FRONT.


2. Queue is referred to be as First In First Out list.


3. For example, people waiting in line for a rail ticket form a queue.

# Circular Queue:
1. There was one limitation in the array implementation of Queue. If the rear reaches to the end position of the Queue then there might be possibility that some vacant spaces are left in the beginning which cannot be utilized. So, to overcome such limitations, the concept of the circular queue was introduced.

2. A circular queue is similar to a linear queue as it is also based on the FIFO (First In First Out) principle except that the last position is connected to the first position in a circular queue that forms a circle. It is also known as a Ring Buffer.

# Deque
Deque is a linear data structure in which the insertion and deletion operations are performed from both ends. We can say that deque is a generalized version of the queue.

### Operations
#### Enqueue: 
The enqueue operation is used to insert the element at the rear end of the queue. It returns void.
#### Dequeue: 
The dequeue operation performs the deletion from the front-end of the queue. It also returns the element which has been removed from the front-end. It returns an integer value. The dequeue operation can also be designed to void.
#### Peek: 
This is the third operation that returns the element, which is pointed by the front pointer in the queue but does not delete it.
#### Queue overflow (isfull): 
When the Queue is completely full, then it shows the overflow condition.
#### Queue underflow (isempty): 
When the Queue is empty, i.e., no elements are in the Queue then it throws the underflow condition.
