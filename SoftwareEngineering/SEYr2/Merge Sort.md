- Follows Divide and Conquer approach.
- It continuously divides the unsorted list with n element until it reaches single element sub-lists
- Then is repeatedly merges the sub-lists together to produce new sorted sub-lists until all elements are fully mergered into a single sorted array
- [[Big O Notation]] time complexity : $O(n\log n)$

#### Merging
- When Merging 2 sub-lists:
- Start at first element of each list
- check which is smaller
- add the smaller one to the whole array and move to second element of that list
- check which is smaller (2nd element of first list vs 1st element of second)
- repeat

#### Code:
```java
public static <T extends Comparable<? super T>> long mergeSort(T[] S){  
    double startTime=0; //stores start time of sort  
    double totalTime=0; //stores total time of sort  
  
    startTime = System.nanoTime();  //get start time  
  
    int n=S.length;     //n is size of array  
    if(n<2) return 0;   //if n is less than two we cant split more so we just 
                        //end this call  
  
    int mid = n/2;      //calculcate middle of array and store in mid  
    T[] S1 = Arrays.copyOfRange(S,0,mid); //Copy first half of array to S1  
    T[] S2 = Arrays.copyOfRange(S,mid,n);       //copy second half of array to S2  
  
    mergeSort(S1); //merge sort these sub arrays  
    mergeSort(S2);  
  
    /*****************Merge****************/  
    //merging the sub arrays together  
    int i=0;  
    int j=0;  
  
    while(i+j < n){ //if i+j is equal to size of array then every element in 
                    //each sub array has been merged so we can stop  
        if(j==S2.length || (i<S1.length && S1[i].compareTo(S2[j]) < 0)){ 
        //if j has reached end of S2 then every element from S2 has been added 
        //to the new Array so just add elements from first sub array  
                                                                         
        //or if i hasnt reached end of its array and element at i in subArray1 
        //is less than element at j in sub array2            
        S[i+j] = S1[i++];                                            
        //add that element to array and increase i(moves to next element in 
        //sub array1 for next comparison)  
                                                                         
        //sum of i+j is how many elements have already been added(sorted) and 
        //because array starts at 0 this stores value at next unsorted element 
        //in array        
        } else {    //if j hasnt reached its end and i has or S2[j] is smaller  
            S[i+j] = S2[j++];   
            //same as above just add element from subarray2 instead of element 
            //from subarray1  
        }  
    }  
  
    /**************************************/  
  
    totalTime = System.nanoTime() - startTime; //calculate total sort time  
  
    return (long) totalTime;                    //return total sort time  
}
```