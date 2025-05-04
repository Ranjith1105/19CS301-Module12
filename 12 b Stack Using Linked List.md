# Ex.No 12.b Stack Using Linked List – Push and Index Display

## Aim

To write a Python program that takes 3 inputs from the user, inserts them into a stack, and displays each element along with its index.

## Algorithm

1.Start
2.Initialize an empty stack.
3.Repeat 3 times:
     Accept an input from the user.
     Insert the input into the stack using append().
4.For each element in the stack:
5.Display its index and value.
6.End

## Program

```

stack = []

stack.append(input("Insert the first element:"))
stack.append(input("\nInsert the second element:"))
stack.append(input("\nInsert the third element:"))

print('\nInitial stack: ' + str(stack))

for i in range(len(stack)):
    print(i, end=" ")
    print(stack[i])


```

## Output
![Screenshot 2025-05-04 074302](https://github.com/user-attachments/assets/f4927a17-3bd3-4626-93ea-07dc8f573379)


## Result
 Thus, the given program is implemented and executed successfully .

