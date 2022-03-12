 Find whether the given character is an upper-case alphabet, a lower-case alphabet, or a non-alphabetic character.
 
 ```c++
#include <iostream>
using namespace std;

int main(){
	char input;
	cout << "Please enter in a single key :";
	cin >> input;
	// Gets input from console
	
	
	
		if (input >= 65 && input <= 90 ){
 			cout <<"upper-case alphabet" ;
			} // if input falls within the ASCII range for capital letters

		else if (input >= 97 && input <= 122 ){
			cout <<"lower-case alphabet" ;
			// If input falls within the ASCII range for lower case letters
			}

		else{
 			cout <<"not an alphabet" ;
			// for all other cases print this statement
			}	
	return 0;

```