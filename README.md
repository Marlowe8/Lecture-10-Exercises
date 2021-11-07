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


				      
