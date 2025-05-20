19CS301:##  12 d Queue Using Linked List – Managing Rice Bag Sales

## Aim

To write a Python program to add 4 elements to a queue and print the elements present at the front and rear of the queue.

## Algorithm

1.Initialize an empty list to act as a queue.

2.Add initial rice bags to the queue using append():

      'Jan_RB1_250'

      'Feb_RB2_250'

       'Mar_RB3_250'

3.Sell (remove) the oldest rice bag using pop(0) — this removes the first item (FIFO behavior).

4.Add new rice bags:

       "Apr_RB4_250"

       "May_RB5_250"

       "June_RB6_250"

5.Sell two more rice bags using pop(0) twice.

6.Display the remaining queue.

7.Identify and print:

8.The next rice bag for sale using queue[0] (front of the queue).

9.The latest rice bag added using queue[2] (rear of the queue assuming at least 3 items remain).

## Program
Reg no:212223020021
Name: Ranjith P

```python

#queue = []

queue.append('Jan_RB1_250')
queue.append('Feb_RB2_250')
queue.append('Mar_RB3_250')

queue.pop(0)
queue.append("Apr_RB4_250")
queue.append("May_RB5_250")
queue.append("June_RB6_250")
queue.pop(0)
queue.pop(0)

print(queue)
front=queue[0]
print("\nNext rice bag ready for sale ....",front)
rear=queue[2]
print("\nNew rice bag ....",rear)
```

## OUTPUT
![Screenshot 2025-05-20 224338](https://github.com/user-attachments/assets/418df774-c270-432d-ba6d-431d3f851d1d)


## RESULT
Result: Thus, the given program is implemented and executed successfully .


