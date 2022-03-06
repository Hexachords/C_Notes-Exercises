You need to make a countdown app.  
Given a number **N** as input, output numbers from N to 1 on separate lines.  
Also, when the current countdown number is a multiple of 5, the app should output "Beep".  
  
**Sample Input:**  
12  
  
**Sample Output:**  
12  
11  
10  
Beep  
9  
8  
7  
6  
5  
Beep  
4  
3  
2  
1


```C++

#include <iostream>

using namespace std;

  

int main() {
	int n;
	cin >> n; // Get input for n

	while (n > 0) {
		// begin loop for each multiple of 5 print n and "Beep"
		if (n%5 == 0){
			cout <<n << endl;
			cout <<"Beep"<< endl;
			n--;
			}

		else{
			// in all other cases print n
			cout << n << endl;
			n--;
			}
 }

 return 0;

}
```