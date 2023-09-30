- Uses a recursive approach based on the [[Divide and Conquer Algorithm]]
- Divide
	- If S has at least 2 elements
	- Select a random element x called pivot and partition S into 3 sequences
		- L storing elements less than x
		- E storing elements equal to x
		- G storing elements greater than x
- Recur: Recursively sort sequence L and G
- Conquer: put elements back into S
![[Pasted image 20221027181635.png]]

#### [[Time Complexity]]
The worst case running time is O($n^2$)

In the best case the pivot is the median of the data-set so it will divide the data set each time into two parts of about the same size so the time complexity will be the same as [[Merge Sort]]: O($n\log n$)

Average time is also found to be O($n\log n$)

The height of the quick sort tree will be log n because:
number of items in list $n = 2^s$ where s is the number of levels. So $\log_2 n = \log n = s$

#### [[Space Complexity]]
Best case scenario O($\log n$)

Worst Case scenario $O(n)$

#### In-Place Partitioning
##### Steps:
1. Choose the pivot point and swap it with the last element of the array
2. Use two indices; The lest most l and the right most r
3. In the partition step index l scans the sequence from left to right and index r scans the sequence from right to left, until they cross each other
4. A swap is performed when the lth element is larger than the pivot and rth element is smaller than the pivot
5. A final swap with the pivot completes one partition step

Now all the above steps are repeated recursively for the resultant partitions

#### Pivot Selection
- Is important for the efficiency of the [[Algorithms]]
- Ideally the pivot should be the median value in the array
	- However to find this you need a sorted array
- ==Recommended==
	- Choose the median of the first last and middle locations

#### Code:
```java
public static <T extends Comparable<? super T>> long quickSort(T[] s, int a, int b){  
    double startTime=0; //start time of sort  
    double totalTime=0; //will calculate total time of sort  
  
    startTime = System.nanoTime(); //store start time  
  
    if(a >= b) return 0; //a and b are first and last indexes so if a is greater or equal than b its sorted  
    int left = a;  
    int right = b-1;  
    T pivot = s[b];      //pivot is last element in array  
    T temp;              //will be used when swapping  
    while(left <= right){  
        //scan until reaching value equal or larger than pivot or right marker  
        while(left <= right && s[left].compareTo(pivot)<0){  
            left++;  
        }  
  
        while(left <= right && s[right].compareTo(pivot)>0){ 
        //same as above but move to the left (started at the right)  
            right--;  
        }  
  
        if(left <= right){ 
        //indexes did not cross so swap the values and shrink the range  
            temp = s[left];  
            s[left] = s[right];  
            s[right] = temp;  
            left++;  
            right--;  
        }  
    }  
    temp = s[left]; 
    //swap pivot with s[left]. and because this must mean left >= right this      
    //is now the middle. the pivots correct location  
    s[left] = s[b];  
    s[b] = temp;  
  
    quickSort(s,a,left-1); //recursively sort each side of pivot  
    quickSort(s,left+1,b);  
  
    totalTime = System.nanoTime() - startTime; //calculate total sort time  
  
    return (long) totalTime; //return sort time  
}
```