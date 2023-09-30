- Steps through data set from one end to the other and compares adjacent pairs
- Elements are swapped if they are in the wrong order
- After the first pass; last element is the largest
- After second; last two are 2 largest (largest is still last)
- etc.
- The pass only goes through unsorted portion

- [[Big O Notation]] Time Complexity = $O(n^2)$

#### Code:
```java
public static < T extends Comparable <? super T >> long bubbleSort(T[] a){  
    double startTime=0;         //will be used to store start time of sorting  
    double totalTime=0;         //will be used to store total time of sorting  
  
    startTime = System.nanoTime(); //store start time  
  
    for(int i=0; i<a.length-1; i++){        
    //runs sort as many times as there are elements in array  
        for(int j=0; j<a.length-i-1; j++){  //run array length minus how many 
        //times outer loop has run (can do this because each run through puts 
        //the largest element to the right so it doesnt need to be 
        //sorted/swapped)  
            if(a[j].compareTo(a[j+1])>0){   
	            //check if a[j] is larger than a[j+1]. if so swap them  
                T temp = a[j];              //swap a[j] and a[j+1]  
                a[j] = a[j+1];  
                a[j+1] = temp;  
            }  
        }  
    }  
  
    totalTime = System.nanoTime() - startTime; //calculate total time  
  
    return (long) totalTime; //return total time  
}
```