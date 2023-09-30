#### Code:
```java
public static <T extends Comparable<? super T>>long selectionSort(T[] a){  
    double startTime=0; //used to store starttime of sorting  
    double totalTime=0; //used to store total time of sorting  
  
    startTime = System.nanoTime(); //set start time  
  
    for(int i=0; i<a.length-1; i++){     //runs length of array times. each 
    //time swap element at index i with the smallest element out of elements 
    //ahead of it  
        int minValIndex = i;        //index of smallest element in array. init 
							        //with first element  
        for(int j=i; j<a.length; j++){               //runs through every 
        //element of array following array[i] (includes array[i]) and find 
        //index of smallest element  
            if(a[j].compareTo(a[minValIndex]) < 0){  //checks if current 
            //element is smaller than element at index of smallest element  
                minValIndex = j;    //if so store index of value to swap later  
            }  
        }  
  
        T temp = a[i];        //swap a[i] and smallest element following a[i]  
        a[i] = a[minValIndex];  
        a[minValIndex] = temp;  
  
    }  
  
    totalTime = System.nanoTime() - startTime; //calculate and store totalTime  
  
    return (long) totalTime;                   //return total time  
}
```