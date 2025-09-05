# Galon-Nathaniel-A

#include <iostream>
#include <string>
using namespace std;

int main() {
    string fullName, courseYrSec, birthday, motto;

    // Input
    cout << "Enter your Full Name: ";
    getline(cin, fullName);

    cout << "Enter your Course, Year & Section: ";
    getline(cin, courseYrSec);

    cout << "Enter your Birthday: ";
    getline(cin, birthday);

    cout << "Enter your Motto/Motivation in Life: ";
    getline(cin, motto);

    // Output
    cout << "\nHi! I'm " << fullName << " of " << courseYrSec 
         << ". Welcome to Data Structures and Algorithm!" << endl;
    cout << "My Birthday is on " << birthday 
         << ", and my motto/motivation in life is " << motto << "." << endl;

    return 0;
}
