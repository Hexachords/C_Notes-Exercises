create a program that accepts the input of two numbers and prints their sum.

```C++
#include <iostream>
using namespace std;

int main(){
	int a,b,sum;
	
	// Gets input for variable a
	cout << "Please enter the first number \n";
	cin >> a;
	// Gets input for variable b
	cout << "Please enter the second number \n";
	cin >> b;
	
	// Adds variable a +b and then prints to console
	sum = a + b;
	cout << "The sum is : \n" << sum;



	return 0;
}

```