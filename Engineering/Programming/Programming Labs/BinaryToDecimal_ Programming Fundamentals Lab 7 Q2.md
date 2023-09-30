```java
package Q2;  
  
public class BinaryToDecimal {  
    //create array  
	private int[] binaryArray;  
  
	public BinaryToDecimal(){  
        //set array length to default  
		binaryArray = new int[1];  
	}  
  
    public BinaryToDecimal(int[] array){  
        //set array length to array received  
		//binaryArray = new int[array.length]; (not needed to initialize)
		//array becomes received array 
		binaryArray = array;  
 }  
  
    public void displayArray(){  
        //print out array  
		System.out.print("[");  
		for(int i=0; i<binaryArray.length; i++){  
            System.out.print(binaryArray[i] + " ");  
		}  
        System.out.println("\b]");  
	}  
  
    public void doubleTheSizeZeroPadding(){  
        //create temporary array twice the size of binaryArray  
		int[] tempArr = new int[2*binaryArray.length];  
		//copy the elements of binaryArray to right side of the temp array.
		//All other values are 0 by default  
		System.arraycopy(binaryArray, 0, tempArr, (binaryArray.length/2)+2,
		  binaryArray.length);  
		//binary array becomes the temporary array. effectively doubling 
		//binary array  
		binaryArray = tempArr;  
	}  
  
    public int[] reverseArray(){  
        //create array to store reverse of binaryArray  
		int[] revArr = new int[binaryArray.length];  
		//go through each element of array  
		for(int i=0; i<binaryArray.length; i++){  
            //go through "reverse Array"; starting at 0; going to end  
			//go through "array"; starting at end; going to 0; 
			//for each runthrough "reverse array" at its element becomes
			//"array" at its element 
			revArr[i] = binaryArray[binaryArray.length-i-1];  
		}  
        //return the reversed array  
		return revArr;  
	}  
  
    public void shiftRight(){  
        //create temporary array  
		int[] tempArr = new int[binaryArray.length];  
		for(int i=0; i<binaryArray.length; i++){  
            //store value of array in temp array, one spot to the right  
			//if at the end of binary array; temp array at 0 becomes value
			if(i+1<binaryArray.length)  
                tempArr[i+1] = binaryArray[i];  
			else tempArr[0] = binaryArray[i];  
		}  
        //array becomes the temp array. effectively shifting everything to
        //the right  
		binaryArray = tempArr;  
	}  
  
    public void shuffleArray(){  
        //run through array  
		for(int i=0; i<binaryArray.length; i++){  
            //for each element, pick another random element  
			int j = (int)(Math.random()*binaryArray.length);  
  
			//swap values at i and j of array  
			int temp = binaryArray[i];  
			binaryArray[i] = binaryArray[j];  
		binaryArray[j] = temp;  
		}  
    }  
  
    public int getDecimalValue(){  
        //create variable to store result  
		int result = 0;  
		//calculate result  
		for(int i=0; i<binaryArray.length; i++){  
            result += (binaryArray[binaryArray.length-i-1]*(MyMethod.myPow(2,
              i)));  
		}  
        return result;  
	}  
}
```