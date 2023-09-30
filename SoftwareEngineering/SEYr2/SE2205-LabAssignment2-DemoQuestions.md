Here are some sample questions for your demo-prep. The TAs can ask any kind of question if those are related to this lab. 
1. What is ‘natural order’. 
Ordering provided by the JVM (Java Virtual Machine)

3. What is ‘order by comparator’. 
ordering provided by comparator (compareTo method)

5. What do you need to do if you would like to sort the instantiated objects of a class called ‘MyClass’ using natural order? 
using sort method (must import comparable)

7. What is stability of sorting algorithm. 
maintains previous ordering of items with equal values
- if obj1 = obj2 and previously it was obj1, obj2 it would still be that

9. How the stability of a sorting algorithm is ensured. 
check and if two elements are equal preserve that order (don't swap them)

11. Can any sorting algorithm be made stable? 
yes you just need to implement something to check if equal and if so retain position

13. What are the inherently stable sorting algorithms? 
merge sort, insertion sort, bubble sort

15. Can Radix sort be used to sort the instantiated objects of a class called ‘MyClass’. What is the reasoning of your response? 
yes provided its given an integer to sort by (grade). the method would need to be modified to accept MyClass and check the integer value.

17. If you sort an array with same dataset, with the same algorithm, in the same machine twice, will the execution time for both runs will be the same? What is the basis of your response? 
no because in one iteration they could be completely sorted which may shorten sort time depending on method used

19. How have you picked the pivot in the quick sort algorithm? What is the justification of this choice? 
we picked the last element in the array
It is quick to just choose that and since the list is unsorted and we are picking randomly it doesnt matter where we get it from

21. If you call the quick-sort method to sort an already sorted array based on the implementation you presented what would happen in terms of time and space complexity. What is the basis of your response? 
the complexity(no change in space complexity) would be the same as merge sort(nlogn) because the process becomes essentially the same as merge sort

23. Modify any algorithm to do the sorting in descending order. 
24. Explain how you generate a random number between min and max inclusive using Math.random() method. 
26. If you have a smaller dataset of 50 elements, which algorithm would you choose to sort that set, and why? 
insertion sort because you dont call methods recursively

28. If you create a class MyClass that implements Comparable interface, would you prefer choosing primitive datatype (when needed) over Wrapper class object reference. What is the basis of your response? 
29. If you would like to do Bucket-search Strings that use alphabetical characters, how many buckets would you need to accomplish this? Why? 
26 one for each letter

31. What would be your preference between Merge and quick sort? Why? 
merge sort because i understand it better
large datasets: Merge
storage: quick

33. If you are sorting integer data set, what would be your sorting algorithm choice? Why? 
bucket sort. i understand it well and its quick

35. Point out in the code, how the best-case time complexity of Insertion sort is O(n). Also, do the same for Bubble sort.
Insertion:
all smaller than key
or list is 1 which does same thing
Bubble:
because you only need to run through the code/list once
say list is sorted you only need to run through once to realise everything is sorted and doesnt need to be swapped