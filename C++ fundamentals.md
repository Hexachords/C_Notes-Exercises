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