Printing a message to the console
```C++
#include <iostream>**  
using namespace std;

int main(){
	cout << "Hello world!";
	cout << " This " << "also " << "works";
	return 0;
	
}
```

Like JS requires an ; at the end of each statement

**Headers**
headers contain information needed for the program to work 
include is used for adding header files to the program
```C++
#include <iostream>  
```

**Namespace**
provides a scope to the names of the elements inside of it 
tells the compiler to use the std (standard) namespace
std = Standard Library
```C++
using namespace std;
```

**Line break**
endl  or \n is used to create a new line
```C++
#include <iostream>
using namespace std;

int main(){
	cout << "This will create a new line" <<endl;
	cout << "below the previous statement \n";
	cout << "FIN" ;
return 0;
}

```

**Coments**
// is used to create a single line comment
/* */ is used to create multiline comments
```C++
#include <iostream>
using namespace std;

// single line comment
/*

Multi-Line
Comments

*/

```

**Variables**
require a data type for the variable before it is declared
```C++
#include <iostream>
using namespace std;
int main(){
	int myNum = 9;
	int numA,numB; // declare multiple variables
	numA = 5;
	numB = 8; 
	
	
	int sum = myNum *2 ;
	
	cout << sum; // Prints sum
	return 0;
}

```
const is used to create constant variables that can't be modified 

```cpp
const int number = 10;
```
-   _Int ("%d"):_ 32 Bit integer
-   _Long ("%ld"):_ 64 bit integer
-   _Char ("%c"):_ Character type
-   _Float ("%f"):_ 32 bit real value
-   _Double ("%lf"):_ 64 bit real value

**User input**
cin is used to get input >>

scanf and printf are faster

```C++
#include <iostream>
using namespace std;

int main(){
	int num; // Declare variable num
	
	cout << "Enter a number or perish \n" // sends prompt to the console
	
	cin >> num; // Takes input from console

}

```

**Arithmetic Operators**
![[Pasted image 20220302121155.png]]

**Assigment operators**


```C++
x += 4; // equivalent to x = x + 4
x -= 5; // equivalent to x = x - 5


x++ // equal to x=x+1
x-- // equal to x=x-1

	
	
++x; // prefix  
x++; // postfix

```

**Prefix** increments the value, and then proceeds with the expression.  
```C++
x = 5;  
y = **++x**;  
// x is 6, y is 6

```


**Postfix** evaluates the expression and then performs the incrementing.

```C++
x = 5;  
y = **x++**;  
// x is 6, y is 5
```

**While/if/Else Loops**
```C++
if (condition) {  
	//statements  
}
else {
	//statements  
	}

while (condition) {  
	//statement(s);  
}

do {  
	statement(s);  
} 
while (condition); 

```

![[Pasted image 20220312134853.png]]

**For Loop**

```C++
for ( init; condition; increment ) {  
	statement(s);  
	}
for (int x = 1; x < 10; x++) {  
	// some code  
	}
```

**Switch Case**
```C++
switch (expression) {  
	case value1:  
		//statement(s);  
		break;  
	case value2:  
		//statement(s);  
		break;  
	...  
	case value99:  
		//statement(s);  
		break;  
	default:
		cout <<"Default case if no others are met" ;
}
```

**Logic Operators**
![[Pasted image 20220305201147.png]]

**Data types**
**Integers** (whole numbers), such as -7, 42.  
**Floating point** numbers, such as 3.14, -42.67.
**Characters** are single letters or symbols, and must be enclosed between **single quotes**, like 'a', 'b', etc.
Boolean data type returns just two possible values: **true** (1) and **false** (0).

**signed**: A signed integer can hold both negative and positive numbers.  
**unsigned**: An unsigned integer can hold only positive values.  
**short**: Half of the default size.  
**long**: Twice the default size.

a **float** is 4 bytes,
a **double** is 8, 
a **long double** can be equivalent to a double (8 bytes), or 16 bytes

**ARRAYS**
Arrays are used to hold multiple bytes of information
```C++

int b[5] = {11, 45, 62, 70, 88};

// b[2] = 62
```
**Multi-Dimensional Arrays**
```C++
// type name[size1][size2]...[sizeN];
int x[3][4];


int x[2][3] = {  
{2, 3, 4}, // 1st row  
{8, 9, 10} // 2nd row  
		};
//or 

int x[2][3] = {{2, 3, 4}, {8, 9, 10}};

```

**Pointers**
A **pointer** is a variable, and like any other variable, it must be declared before you can work with it.  
The **asterisk** sign is used to declare a pointer (the same asterisk that you use for multiplication), however, in this statement the asterisk is being used to designate a variable as a pointer.
```C++
& // used to denote an address in memory
	
	
int *ip; // pointer to an integer  
double *dp; // pointer to a double  
float *fp; // pointer to a float  
char *ch; // pointer to a character	
```

![[Pasted image 20220311152350.png]]
![[Pasted image 20220323134439.png]]