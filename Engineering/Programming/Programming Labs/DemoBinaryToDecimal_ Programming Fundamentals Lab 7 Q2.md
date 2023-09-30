```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-03-21 * In this task the program will perform operations on arrays that represent binary numbers **********************************/  
package Q2;  
  
public class DemoBinaryToDecimal {  
    public static void main(String[] args){  
        //create array  
		int[] binaryArray = new int[4];  
  
		MyMethod.myHeader("Jacob Dreyer", 7, 2);  
  
		//randomly populate array with 1 or 0  
		for(int i=0; i<binaryArray.length; i++){  
            binaryArray[i] = (int)(Math.round(Math.random()));  
		}  
  
        //create new BinaryToDecimal class (will allow operations to array to
        //be done)  
		//pass in created array (this will be the array that is manipulated)
		BinaryToDecimal btd = new BinaryToDecimal(binaryArray);  
  
		//print out various manipulations to array  
  
		System.out.print("The 4 bit number: ");  
		btd.displayArray();  
		System.out.printf("The corresponding decimal value is: %d\n",
		  btd.getDecimalValue());  
		btd.doubleTheSizeZeroPadding();  
		System.out.print("The 8 bit number, after the size is doubled and
		  zero padded: ");  
		btd.displayArray();  
		System.out.printf("The corresponding decimal value is: %d\n",
		  btd.getDecimalValue());  
  
		BinaryToDecimal btd2 = new BinaryToDecimal(btd.reverseArray());  
		System.out.print("The 8 bit number after reversing the array: ");  
		btd2.displayArray();  
		System.out.printf("The corresponding decimal value is: %d\n",
		  btd2.getDecimalValue());  
		btd2.shiftRight();  
		System.out.print("The 8 bit number after the shift right operation:
		  ");  
		btd2.displayArray();  
		System.out.printf("The corresponding decimal value is: %d\n",
		  btd2.getDecimalValue());  
		btd2.shuffleArray();  
		System.out.print("The 8 bit number after the shuffling operation: ");  
		btd2.displayArray();  
		System.out.printf("The corresponding decimal value is: %d\n",
		  btd2.getDecimalValue());  
  
		//print footer  
		MyMethod.myFooter();  
	}  
}
```