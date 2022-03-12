Take an input in seconds and convert it to total hours,minutes and days, then print it to the console

```Cpp
#include <iostream>

using namespace std;

int main() {


	int hours, minutes, seconds,input;
	cout << "Please input an amount of seconds: "<< endl;
	cin >> input;
	cout << "You entered :" << input << endl;

	hours = input/3600;
	minutes = (input% 3600)/60 ;
	seconds = (input % 3600)%60;


	cout << "Time in hours, minutes and seconds = ";
	cout << hours << "h :";
	cout << minutes << "m :";
	cout << seconds << "s";

}

```