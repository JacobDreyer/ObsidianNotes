##### C++ Reference
https://en.cppreference.com/w/

#### Building
- Creating an executable file
- goes through entire project aand builds everything (that isnt already built)

##### Clean
- gets rid of objects. Just source code\

##### Rebuild
- Clean + Build

##### IOStream
allows us to do input/output
```c++
#include <iostream>
```

##### Console Text
- cout - console text out
- endl - end line
```c++
std::cout << "text" << std::endl

using namespace std;
cout << "text";

```

##### Read Input
- cin - reads from console
```c++
std::cin >> var

cin.getline(var, 50);  //copys entire line to var. up to 50. used to copy to 
						//c-style sting
```

##### Variables
Declaring:
```c++
int num = 0;
int num {0};
```

##### \\n
- Goes within text in brackets (to be printed)
- isnt printed. goes to next line
```c++
cout << "hello \n this is the next line";
```
##### \\b - Backspace
##### \\t - Tab


##### sizeof
- size in bytes of a type or variable
```c++
sizeof(var);
sizeof var;
```

##### Constant
```c++
const int {1};

#define pi 3.14
```

##### Array
```c++
int arr [var];
int arr [3] {1,5,3};
int arr [2][5];
int arr [3][4]{
	{0,4,3,5},{1,6,2,8},{9,5,8,1}
};

arr[2] = 90;
```

##### Vectors
- An array that can grow and shrink
```c++
#include <vector>

std::vector <int> vec (10); //auto set to 0
std::vector <int> vec {1,4,4,7,8};
std::vector <int> vec (365, 80);    //365 slots initialized to 80

vec[1] = 2;
vec.at(2) = 3;

vec.push_back(90); //adds an element //90 in this case
vec.size(); //# of elements in vector
```

##### Casting
```c++
static_cast<double>(var)
```

##### Conditional Operator
```c++
(expression) ? exper1 : exper2 //expression true: execute exper1
								//   ^       false: execute exper 2
```

##### For loop
```c++
for(int i=1; i<5; i++){
}

for(int i{1}, j{3};i<=5;i++,++j){
}

int scores [] {100, 97, 90};
for(auto score : scores)           //score becomes/goes through each element 
                                   //of scores //auto: automatically  
							       //determines type of score. in this case 
                                   //int                             
```

##### While
```c++
while(bool == true){
}

do {
 //stuff
} while (expression);
```

##### Continue and Break
- continue goes to start of loop
- break ends loop. goes to next statement

##### Characters
```c++
#include <cctype>

isalpha(c) //true if c is a letter
isalnum(c) //true if c is a letter or digit
isdigit(c) //true if c is a digit
islower(c) //true if c is lowecase
isprint(c) //true if c is a printable character
ispunct(c) //true if c is punctuation'
isupper(c) //true if c is upper case
isspace(c) //true if c is a whitespace

tolower(c) //returns lowercase of c
toupper(c) //returns uppercase of c
```

##### C-style Strings
```c++
char my_name[] {"Jacob"};
char str[80];
my_name[3];

#include <cstring>

strcopy(str, "Hello"); //copys second string to first
strlen(str);           //returns string length
strcat(str, "there");  //add second string to first string
strcmp(str, "another"); //compare. returns zero: is the same

#include <cstdlib>

```

#### C++ Strings
- can grow and shrink
```c++
#include <string>

std::

string s1;
string s2 {"Jacob"};
string s3 {s2};
string s4 {"Jacob", 3} // Jac
string s5 {s3, 0, 2};
string s6 {3, 'X'}; //XXX

s1 = "C++ Rocks!";
s2 = s1;

string sentence;

sentence = part1 + " " + part2 + " language";
sentence2 = "text" + "more text"; //wont work

s2[0];
s2.at(0);

s1.subtr(start_index, length) //creates substring
s1.find(search_string); //returns index of beginning of string or character
						//searched for
s1.erase(start_index, length); //erases
s1.clear()                     //clears entire string

getline(cin, s1) //used for including whitespace from keyboard
getline(cin, s1, 'x')// x is where you want to stop reading line
```

##### Functions
```c++
int addNumbers(int a, int b); //or
int addNumbers(int, int);        //prototype. located at top with #include
									// needed for each defined function
int addNumbers(int a = 2, int b = 1); //with default values

int addNumbers(int a, int b){
	return a + b;
}
void addNumbers(){

}
void addNumbers(int numbers [], size_t size){

}

addNumbers(a,b);
```
Pass By Reference:
```c++
void scale_number(int &num){
	num = 100;
}
```

##### Pointers
- can be used to access data defined outside the function
- operate on arrays efficiently
- Allocate memory
```c++
int *int_ptr;

int_ptr = &randomIntegerVar;

*int_ptr = 200;   //randomIntegerVar = 200;

delete int_ptr    //clear that spot in memory
```

##### Classes
```c++
class Class_Name{
	int var

	void method(){
	}
}

main(){
	Player play;

	Player *enemy = new Player();
	delete enemy;
}
```