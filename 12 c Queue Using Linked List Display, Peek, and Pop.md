# 12 c Queue Using Linked List – Display, Peek, and Pop

## Aim

To implement a queue with a fixed maximum size using Python's queue module, insert elements into the queue, and check whether the queue is full using the full() method.


## Algorithm

1. Import the Queue module from the queue library.

2. Create a queue with a maximum size of 4 using Queue(maxsize=4).

3. Insert elements into the queue using put():

     Insert 'a'

     Insert 'b'

     Insert 'c'

4. Check if the queue is full using queue.full():

5. If it returns True, print "Queue is full".

6.Otherwise, print "Queue is not full".

## Program
Reg no: 212223020021
Name: Ranjith P

```
from queue import Queue

queue = Queue(maxsize = 4)

queue.put('a')
queue.put('b')
queue.put('c')

if queue.full():
    print("Queue is full")
else:
    print("Queue is not full")
```

## OUTPUT
![Screenshot 2025-05-20 223700](https://github.com/user-attachments/assets/c7fb0cbd-3a2f-456d-b7b1-ebf8f164bfd6)



## RESULT
Result: Thus, the given program is implemented and executed successfully .
