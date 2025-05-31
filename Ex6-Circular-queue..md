# Ex6 Dequeue Elements from Circular Queue
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1. Start
2. Define a queue with a fixed size SIZE and initialize front and rear pointers.
3. Define the deQueue() function to remove and return an element from the front of the queue.
4. Check if the queue is empty using isEmpty(); if empty, print an error message.
5. If the queue has one element, reset both front and rear to -1.
6. If the queue has more than one element, update front to the next index using modulo operation ((front + 1) % SIZE).
7. Return the removed element from the front of the queue.
8.  End

## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: SUBHASHINI B
RegisterNumber: 21223040211   
*/
int deQueue() {
  int element;
  if (isEmpty())
  {
    printf("Queue is empty !! \n");
    return (-1);
  } else 
  {
    element = items[front];
    if (front == rear) 
    {
      front = -1;
      rear = -1;
    } 
    
    else 
    {
      front = (front + 1) % SIZE;
    }
   
    return (element);
  }
}
```

## Output:

![Screenshot 2025-04-29 093921](https://github.com/user-attachments/assets/1ea2e9d8-9f72-442e-ba68-3360ab645b50)


## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
