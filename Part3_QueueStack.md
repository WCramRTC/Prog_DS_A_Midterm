# Part 3 - Data Structures and a proper Coding Problem

## Part 1 - Creating ALL of your Data Structures

1. Create a new Project called DataStructures_YourName.
2. Comment your name at the type
3. Submit this Repository online AND
4. Post the repo link on your profile
5. Do the following process ( make sure to comment your code )


Add 4 Classes to this project.

1. LinkedList - Singly
2. LinkedList - Doubly
3. Queue
4. Stack

These should all be generic, have all the apropriate methods and functionality to have them work.

### Full List of Expected Methods

1. **LinkedList - Singly:**
   - `AddFirst(T item)`: Adds an item to the beginning of the list.
   - `AddLast(T item)`: Adds an item to the end of the list.
   - `RemoveFirst()`: Removes and returns the first item in the list.
   - `RemoveLast()`: Removes and returns the last item in the list.
   - `Contains(T item)`: Checks if the list contains a specific item.
   - `Clear()`: Removes all items from the list.
   - `Count`: Returns the number of items in the list.

2. **LinkedList - Doubly:**
   - `AddFirst(T item)`: Adds an item to the beginning of the list.
   - `AddLast(T item)`: Adds an item to the end of the list.
   - `RemoveFirst()`: Removes and returns the first item in the list.
   - `RemoveLast()`: Removes and returns the last item in the list.
   - `Contains(T item)`: Checks if the list contains a specific item.
   - `Clear()`: Removes all items from the list.
   - `Count`: Returns the number of items in the list.
   - `AddBefore(LinkedListNode<T> node, T item)`: Adds an item before a specific node.
   - `AddAfter(LinkedListNode<T> node, T item)`: Adds an item after a specific node.
   - `Find(T item)`: Finds the first occurrence of a specific item.
   
3. **Queue:**
   - `Enqueue(T item)`: Adds an item to the end of the queue.
   - `Dequeue()`: Removes and returns the item from the front of the queue.
   - `Peek()`: Returns the item at the front of the queue without removing it.
   - `IsEmpty`: Checks if the queue is empty.
   - `Count`: Returns the number of items in the queue.
   
4. **Stack:**
   - `Push(T item)`: Adds an item to the top of the stack.
   - `Pop()`: Removes and returns the item from the top of the stack.
   - `Peek()`: Returns the item at the top of the stack without removing it.
   - `IsEmpty`: Checks if the stack is empty.
   - `Count`: Returns the number of items in the stack.

You can refer to your guided assignments for these.


| Description                                     | Points |
| ----------------------------------------------- | ------ |
| Creating a new project with a unique name       | 5      |
| Adding your name as a comment in each class     | 5      |
| Creating a LinkedList - Singly class           | 5      |
| Implementing all required methods for LinkedList - Singly | 15     |
| Creating a LinkedList - Doubly class           | 5      |
| Implementing all required methods for LinkedList - Doubly | 15     |
| Creating a Queue class                         | 5      |
| Implementing all required methods for Queue    | 15     |
| Creating a Stack class                         | 5      |
| Implementing all required methods for Stack    | 15     |
| Properly commenting the code for clarity and understanding | 5     |
| **Total**                                       | **100** |

## Part 2 - Due a week after midterm 

The "queue with two stacks" problem is a classic algorithmic challenge that involves implementing a queue data structure using two stacks. A queue is a First In, First Out (FIFO) data structure, meaning the first element added to the queue will be the first one to be removed. A stack, on the other hand, is a Last In, First Out (LIFO) data structure, where the last element added to the stack is the first one to be removed.

The challenge lies in using two stacks, which inherently operate in a LIFO manner, to achieve the FIFO functionality of a queue. This involves cleverly manipulating the order of elements as they are moved between the two stacks.