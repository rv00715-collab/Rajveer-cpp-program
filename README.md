#include <iostream.h>

void main() {
    int year;
    cout << "Enter a year: ";
    cin >> year;

    if ((year % 400 == 0) || (year % 4 == 0 && year % 100 != 0)) {
        cout << year << " is a Leap Year." << endl;
    } 
    else {
        cout << year << " is NOT a Leap Year." << endl;
    }
}
