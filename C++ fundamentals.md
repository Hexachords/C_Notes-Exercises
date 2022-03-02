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
**User input**
cin is used to get input >>

```C++
#include <iostream>
using namespace std;

int main(){
	int num; // Declare variable num
	
	cout << "Enter a number or perish \n" // sends prompt to the console
	
	cin >> num; // Takes input from console



}

```
