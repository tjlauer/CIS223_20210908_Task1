# CIS223_Task1

In this practice, we will be implementing a queue using TWOSTACK object.
- You are required to use python.
- For help you can use the lecture slides.

<br><hr>

## The Problem - Part 1

<b>Write a class called TWOSTACK that uses python list to implement two stacks sharing the same python list. The class has following methods. Implement each of these methods.</b><br>
<br>
<b>a.</b> <code>Push1(key)</code> Adds a new value to the stack1. Returns True on success else returns false.<br>
<b>b.</b> <code>Push2(key)</code> Adds a new value to the stack2. Returns True on success else returns false.<br>
<b>c.</b> <code>Pop1()</code> Returns the last value added to the stack1 and removes the value from the stack1.<br>
<b>d.</b> <code>Pop2()</code> Returns the last value added to the stack2 and removes the value from the stack2.<br>
<b>e.</b> <code>Peek1()</code> Returns the last value added to the stack1 and does not removes the value from the stack1.<br>
<b>f.</b> <code>Peek2()</code> Returns the last value added to the stack2 and does not removes the value from the stack2.<br>
<b>g.</b> <code>isFull1()</code> Returns true if the stack1 is full, false otherwise.<br>
<b>h.</b> <code>isFull2()</code> Returns true if the stack2 is full, false otherwise.<br>
<b>i.</b> <code>isEmpty1()</code> Returns true if the stack1 is empty, false otherwise.<br>
<b>j.</b> <code>isEmpty2()</code> Returns true if the stack2 is empty, false otherwise.<br>
<br>
<em>The <code>__init__</code> method for the TWOSTACK class should take two parameters size1 and size2 denoting the maximum size of each stack (apart from the self parameter).</em><br>

<br><hr>

## The Problem - Part 2

<b>Write a class called QUEUE that uses instance of TWOSTACK class. The class also implements the following methods.</b><br>
<br>
<b>a.</b> <code>Enqueue(key)</code> Adds an item at the end of the queue.<br>
<b>b.</b> <code>Dequeue()</code> Returns the item at the beginning of the queue.<br>
<b>c.</b> <code>isFull()</code> Returns true if the queue is full, false otherwise.<br>
<b>d.</b> <code>isEmpty()</code> Returns true if the queue is empty, false otherwise.<br>
<br>
<em>During initialization, of the queue we will also pass a parameter to set the maximum queue size. This should be distributed equally between the two stacks. In your driver code check if this number is even.</em><br>

<br><hr>

## The Problem - Part 3

<b>Write a driver code to test your implementation and show that it is working for different scenarios.</b><br>
