

  
A chater bus can transport **60** passengers at once.  
Given the number of passengers waiting in the bus station as input
Calculate and output how many empty seats the last bus will have.







```C++
#include <iostream>

using namespace std;

  

int main() {
	// Declare variables
	int bus, passengers, seats;
	bus = 60 ;

	cin >> passengers;
	// prompt for input and assign it to passengers

	seats = passengers % bus;
	cout << bus - seats;
	/** gets the remainder of the passangers and assigns it to seats
	 then subtracts seats from bus to get the remainder **/
	
	return 0;

}

```