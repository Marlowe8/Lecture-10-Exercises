# Lecture-10-Exercises

//CountDown
#include <iostream>
using namespace std;
int main() {
		
	for (int i = 10; i > 0; i--) {
		cout << i << endl;
		if (i == 1) {
			cout << "We have lift off!!" << endl;
		}
	}

	return 0;
}

/For loop
  #include <iostream>
using namespace std;

int main()
{
    int i;
    for (i = 20; i <= 24; i++) {
        if (i % 2 == 0) {
        cout << i << " even" << endl;
        }
        else {
            cout << i <<" odd" << endl;
        }

    }

    return 0;
}

/For loop
#include <iostream>
using namespace std;
int main() {
		
	for (int i = 0; i < 7; i++) {
		for (int j = 0; j < 7; j++) {
			cout << "*";
		}
		cout << endl;
	}

	return 0;
}

/For loop
	#include <iostream>
#include <string>
using namespace std;



int main(){
	string str = "ARSH";
	int i;
	for (i = 0; i < str.size(); i++) {
		cout << str.at(i) << endl;
	}


	return 0;
}

/For loop
	#include <iostream>
using namespace std;



int main(){
	int choice;
	int i = 0;
	cout << "case 1: counts up from 0 to 50 in " << endl <<
		"increments of 1." << endl <<
		"case 2: counts down from 50 to 0 " << endl <<
		"in decrements of 1. " << endl <<
		"case 3: counts up from 30 to 50 in " << endl <<
		"increments of 1. " << endl <<
		"case 4: counts down from 50 to 10 " << endl <<
		"in decrements of 2. " << endl <<
		"case 5: counts up from 100 to 200 " << endl <<
		"in increments of 5 " << endl;
	cin >> choice;
	system("cls");
	if (cin.fail()) {
		system("cls");
		cout << "error" << endl;
	}
	switch (choice) {
	case 1: {for (i; i <= 50; i++) {
		cout << i << endl;
	}}break;
	case 2: {for (i = 50; i >= 0; i--) {
		cout << i << endl;
	}}break;
	case 3: {for (i = 30; i <= 50; i++) {
		cout << i << endl;
	}}break;
	case 4: {for (i = 50; i >= 10;) {
		cout << i << endl;
		i -= 2;
	}}break;
	case 5: {for (i = 100; i <= 200;) {
		cout << i << endl;
		i += 5;
	}}break;
	default:
	{
		system("cls");
		cout << "error" << endl;
	}break;
	}
	return 0;
}				 

				  
/Nested Loop Desecending 
 #include <iostream>
#include <string>
using namespace std;



int main(){

	int i;
	int j;
	for (i = 0; i < 7; i++) {
		for (j = i; j < 7; j++) {
			cout << "*";
		}
		cout << endl;
	}

	return 0;
}

/Nested Loop Ascending
	#include <iostream>
#include <string>
using namespace std;



int main(){

	int i;
	int j;
	for (i = 0; i < 5; i++) {
		for (j = 0; j <= i; j++) {
			cout << "*";
		}
		cout << endl;
	}

	return 0;
}
	
/Nested loop Rising and Falling
	#include <iostream>
#include <string>
using namespace std;



int main(){

	int i;
	int j;
	for (i = 0; i < 5; i++) {
		for (j = 0; j <= i; j++) {
			cout << "*";
		}
		cout << endl;
	}
	for (i = 0; i < 4; i++) {
		for (j = i; j < 4; j++) {
			cout << "*";
		}
		cout << endl;
	}

	return 0;
}
	
/Nested loop Cubes
	#include <iostream>
#include <cmath>
using namespace std;



int main() {


	int i;
	int user;
	cout << "Range for cubes" << endl;
	cout << "Enter where to start the cube: "; cin >> i;
	cout << "\nEnter where to end the cube: "; cin >> user;
	if (cin.fail()) {
		system("cls");
		cout << "Error";
	}
	for (i; i <= user; i++) {
		cout << "Number is :" << i << " and the cube of " << i << " is " << pow(i, 3) << endl;
	}

	return 0;
}
				       
//Nested loop Find the 9s
#include <iostream>
#include <cmath>
using namespace std;



int main(){


	int i;
	int result =0;
	for (i = 100; i <= 200; i++) {
		if (i % 9 == 0) {
			cout << i << endl;
			result += i;
		}
	}
	cout << "add all: " << result;
	return 0;
}										     
