#include <iostream>
#include <ctime>

using namespace std;

int main() {
    int hours;
    int minutes;
    time_t now = time(0);
    char* dt;

    dt = ctime(&now);
    cout << "The time is " << dt << endl;
    cout << "How much time after the current time are you looking for? Print hours followed by minutes in whole numbers, separated by a space: ";
    cin >> hours >> minutes;
    cout << endl;

    now = now + (hours * 3600) + (minutes * 60);
    cout << "The time stamp will be " << now << endl;

    dt = ctime(&now);

    cout << "This is equivalent to " << dt <<endl;
    cout << "To print the intended time, print the following: <t:" << now << "> " << endl;

    system("pause");

}
