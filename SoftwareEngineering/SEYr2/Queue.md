## Queue
- A collection following First-in first-out principle
- Unlike [[Stack]]s a queue is open at both ends. One end is used to insert data(add) and the other is used to remove date (remove)


▪ Here are the steps (Algorithm) with integer type data: 
	– Create an array of size c: c will be the capacity of the queue. 
	– Crate two variables front and rear. The front will hold the index of the first element of the array and the rear will hold the index of the last element, if they exist. 
	– Assign zero to both variables front and rear. It means the queue is empty. 
	– Enqueue operation: check whether the rear is equal to the capacity or not otherwise add an element in the array and increment rear. 
	– Dequeue: remove the item from the front index (0) and increment front. 
	– Dequeue (alternative idea): remove the item from the front index (0) of the array 
	   by moving all the elements to the left by 1. Fill in the rear element by 0 and then decrement rear.

#### Applications
- Direct Applications
	- Waiting Lists
	- Access to Shared resources
	- Multiprogramming
- In direct Applications
	- Auxillary data structure for algorithms
	- Component of other data structures

#### Circular Queue
The rear is connected back to the front position to make a ring