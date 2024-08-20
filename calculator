#include <iostream>
using namespace std;
int main() {
	float num_1, num_2;
	int n;
	char A, B;
	do {												
		cout << "Enter first number: ";					
		cin >> num_1;
		cout << "Enter second number: ";					
		cin >> num_2;
		cout << "Press 1 to continue calculation :\n";
		cin >> n;										
		if (n == 1) {
			float c;
			cout << "Enter a arthematic operator (+, -, /, *): ";
			cin >> A;
			switch (A) {
			case '+':
				c = num_1 + num_2;
				cout << "Sum of two numbers are : " << c;
				break;

			case '-':
				c = num_1 - num_2;
				cout << "Subtraction of two numbers are : " << c;
				break;

			case '*':
				c = num_1 * num_2;
				cout << "Product of two numbers are : " << c;
				break;

			case '/':
				c = num_1 / num_2;
				cout << "Division of two numbers are: " << c;
				break;

			default:
				cout << "Invalid selection of operator";
				break;
			}
		}
		else
			cout << "Invalid Input :\n";

		cout << "\n\nWould you like to restart the process(press y):\n\n";
		cout << "To exit the process input N: \n";
		cin >> B;
	} while (B == 'y');

}
