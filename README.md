# Would-you-like-to-continue
#Asking the user if he wants to keep playing
#include<iostream>
using namespace std;
int main()
{
	char choice;   //declaring variable with datatype char
	cout << "Would you like to continue? " << endl;   //asking the user if he wants to continue playing
	cin >> choice;  //the userinput will be stored in variable choice
	switch (choice)   //the userinput will be evaluated
	{
	case 'Y':    //if he enters 'y' either in uppercase or lowercase then the following statement will be executed
	case'y':
		cout << "Alright! Keep playing." << endl;
		break;
	case'N':    //if he enters alphabet 'n' either in uppercase or lowercase then the following statement will be executed
	case'n':
		cout << "Time to take a nap! " << endl;
		break;
	default:     //if the user enters any other character besides 'y' or 'n' then the default case will be executed
		cout << "Invalid data entered..." << endl;
		break;
	}
	return 0;
}
