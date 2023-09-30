Does not compare objects

- It avoids comparison by creating and distributing elements into buckets according to their radix (base(binary, octal, etc))
- It treats array elements as if they were strings of the same length
- It then groups elements by a specified digit or character of a string; this digit is known as key
	- Elements placed into buckets based on the matching key
- For elements with more than one significant digit this bucketing process is repeated for each digit

| 123 | 398 | 210 | 019 | 528 | 003 | 513 | 129 | 220 | 294 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

| 0   | 3   | 4   | 8   | 9   |
| --- | --- | --- | --- | --- |
| 210 | 123 | 294 | 398 | 019 |
| 220 | 003 |     | 528 | 129    |
|     | 513 |     |     |     |

| 210 | 220 | 123 | 003 | 513 | 294 | 398 | 528 | 019 | 129 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

| 0   | 1   | 2   | 9   |
| --- | --- | --- | --- |
| 003 | 210 | 220 | 294 |
|     | 513 | 123 | 398    |
|     | 019 | 528 |     |
|     |     | 129 |     |

| 003 | 210 | 513 | 019 | 220 | 123 | 528 | 129 | 294 | 398 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

| 0   | 1   | 2   | 3   | 5   |
| --- | --- | --- | --- | --- |
| 003 | 123 | 210 | 398 | 513 |
| 019 | 129 | 220 |     | 528 |
|     |     | 294 |     |     |

| 003 | 019 | 123 | 129 | 210 | 220 | 294 | 398 | 513 | 528 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

#### Code:
```java
public static long bucketSort(Integer[] a, int first, int last, int maxDigits){  
    double startTime=0;  
    double totalTime=0;  
  
    startTime = System.nanoTime();  
  
    Vector<Integer>[] bucket = new Vector[10];  
    //instantiate each bucket;  
    for (int i = 0; i < 10; i++)  
        bucket[i] = new Vector<>();  
        
    for (int i = 0; i < maxDigits; i++) {             //repeat for each digit  
        //clear the Vector buckets        
        for (int j = 0; j < 10; j++) {  
            bucket[j].removeAllElements();  
        }  
        //Placing a[index] at end of bucket[digit]  
        for (int index = first; index <= last; index++) {  
            Integer digit = findDigit(a[index], i);  
            bucket[digit].add(a[index]);  
        }  
        //placing all the buckets back into the array  
        int index = 0;  
        for (int m = 0; m < 10; m++) {  
            for (int n = 0; n < bucket[m].size(); n++) {  
                a[index++] = bucket[m].get(n);  
            }  
        }  
    }  
  
    totalTime = System.nanoTime() - startTime;  
  
    return (long) totalTime;  
}  
  
public static Integer findDigit(Integer number, int i) {  
    int target = 0;  
    for (int k = 0; k <= i; k++) {  
        target = number % 10;  
        number = number / 10;  
    }  
    return target;  
}
```
