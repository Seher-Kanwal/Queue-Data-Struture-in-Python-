![Queue](https://www.101computing.net/wp/wp-content/uploads/queue-diagram.png)

# Queue-Data-Struture-in-Python

   Queue is a linear data structure that stores items in First In First Out (FIFO) manner. With a queue the least recently 
   added item is removed first. A good example of queue is any queue of consumers for a resource where the consumer that came
   first is served first.
   
   
## Different operations that can be performed on the Queue: 
* Enqueue: 

        Adds an item to the queue. If the queue is full, then it is said to be an Overflow condition – Time Complexity : O(1)
* Dequeue:

       Removes an item from the queue. The items are popped in the same order in which they are pushed. If the queue is empty, 
       then it is said to be an Underflow condition – Time Complexity : O(1)
* Front: 

       Get the front item from queue – Time Complexity : O(1)
* Rear:

       Get the last item from queue – Time Complexity : O(1)
* Empty:

      The queue.isEmpty() method returns True if the queue is empty, else returns False. Time Complexity : O(1)
       
 # Implementation:
 
     There are various ways to implement a queue in Python. Queue in Python can be implemented by the following ways:
     * list
     
           List is a Python’s built-in data structure that can be used as a queue. Instead of enqueue() and dequeue(), append() and pop()
           function is used. 
           However, lists are quite slow for this purpose because inserting or deleting an element at the beginning requires shifting all 
           of the other elements by one, requiring O(n) time.
           
     * collections.deque
     
           Queue in Python can be implemented using deque class from the collections module. Deque is preferred over list in the cases where
           we need quicker append and pop operations from both the ends of container, as deque provides an O(1) time complexity for append 
           and pop operations as compared to list which provides O(n) time complexity. Instead of enqueue and deque, append() and popleft()
           functions are used.
     
     
 ### Note : implemention by using these methods are given in the reposirty 
 
 # Usage of the Queue:
 
* CPU scheduling, Disk Scheduling
* When data is transferred asynchronously between two processes.The queue is used for synchronization. For example: IO Buffers, pipes, file IO, etc
* Handling of interrupts in real-time systems.
* Call Center phone systems use Queues to hold people calling them in order.

 

