# Queue

A Queue is similair to a stack except it is First In First Out (FIFO). Meaning the first item added the to the queue is the only item that can be removed.

# In Memory

In memory, a queue looks like this:

![Image of queue in Memory](images/Queue.png)

A Queue is a linear data structure that follows FIFO.  The first item added is the first item removed

# Operations

A queue supports the following operations:

* Enqueue: Adds a new item to the "back" of the queue.  This is an O(1) operation as a queue keeps track of the rear of the queue.
* Dequeue: Removes the item on the "front" of the queue. This is also O(1) for the same reason as the Enqueue operation.

# Use Cases

A queue is useful if you need to keep track of what data came in first.  For example, anonline game may need to track what player performed an action first.

A queue is not as useful as a deque because a deque can add items to either end of the list.

# Example

```
my_queue = Queue()
my_queue.enqueue(452)
my_queue.enqueue(1523)
my_queue.enqueue(19)
my_queue.dequeue()
print(my_queue)
```