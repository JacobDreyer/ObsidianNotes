#### Code:
```java
public static < T extends Comparable <? super T >> long insertionSort(T[] a){  
    double startTime=0;  
    double totalTime=0;  
  
    startTime = System.nanoTime();  
  
    int j=0;  
  
    for(int i=1; i<a.length; i++){      //run through length of array  
        T key = a[i];            //key stores element for current run through  
        for(j=i-1; j>=0 && a[j].compareTo(key)>0; j--){  
        //run until j isnt a valid index or we find an element smaller than 
        //key  
            a[j+1] = a[j];                               
            //if we find an element larger than key we set the next element to 
            //that element  
        }  
        a[j+1]=key;   //once we find a element smaller than key or h isnt a 
				        //valid index (=-1) we set a[j+1] to key. if j = -1 
				        //this sets first element of array to key  
    }  
  
    totalTime = System.nanoTime() - startTime;      //calculate total time  
  
    return (long) totalTime; //return total time  
}
```