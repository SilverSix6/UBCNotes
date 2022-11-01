### Sept 13 : Unit Testing
- https://dev.java/learn/ - Generics and Lambdas
- https://www.javatpoint.com/corejava-interview-questions - Review Questions

### Sept 15 : Complexities
- https://www.geeksforgeeks.org/analysis-of-algorithms-set-1-asymptotic-analysis/ - 6 Subsections
- https://www.khanacademy.org/computing/computer-science/algorithms/asymptoticnotation/a/asymptotic-notation
https://greenteapress.com/thinkdast/html/thinkdast003.html
https://www.geeksforgeeks.org/practice-questions-time-complexity-analysis/ - Review Questions
- sort by asymptotic complexity:  
2^n, log(n), n^2, sqrt(n), n, n*log(n)

### Sept 20 : Array List
- https://jenkov.com/tutorials/java/arrays.html
- https://jenkov.com/tutorials/java-collections/list.html
- https://www.softwaretestinghelp.com/doubly-linked-list-in-java/ - Doubly Linked List
- https://www.javatpoint.com/dynamic-array-in-java
- https://www.geeksforgeeks.org/system-arraycopy-in-java/
- https://howtodoinjava.com/java/cloning/a-guide-to-object-cloning-in-java/
- Reading Guide:  
	At this point, you should be able to explain  
	- the difference between shallow and deep copying,  
	- what a copy constructor is  
	- how to copy an object using clone  
	- how serialization is an expensive solution to deep copying  
	Note that cloning and serialization do not call the constructor, which may  be an issue in some cases, e.g., a static method counting how many objects are implemented

### Sept 27 :
- https://introcs.cs.princeton.edu/java/23recursion/ - Recursion
- https://www.digitalocean.com/community/tutorials/java-linkedlist-linkedlist-java - LinkedList and Deque
- https://greenteapress.com/thinkdast/html/thinkdast007.html#sec40 - Stack
- https://www.geeksforgeeks.org/stack-class-in-java/ - Java Stack
- https://www.geeksforgeeks.org/queue-interface-java/ - Java Queue
- https://www.geeksforgeeks.org/deque-interface-java-example/ - Java Deque
- https://www.geeksforgeeks.org/collection-vs-collections-in-java-with-example/ - Collection vs Collections Java
- Remember the main operations and their complexity  
Queue: FIFO. enqueue, dequeue; all in O(1). Java Queue is an interface  
with add, remove, iterator; implementations: LinkedList, ArrayDeque.  
Priority queues are implemented differently and will be seen when we look  
at heap  
Stack: LIFO. pop, push; all in O(1). Java Stack is a class.  
Deque (double-ended queue): support add and remove at both ends; Java  
Deque is an interface. implementations: LinkedList, ArrayDeque

