#include <iostream>
using namespace std;

int main() {
    // Enter a degree in Fahrenheit
    double fahrenheit;
    cout << "Enter a degree in Fahrenheit ";
    cin >> fahrenheit;
    
    //Obtain a celsius degree
    double celsius = (5.0 / 9) * (fahrenheit - 32);
    
    //Display answer
    cout << fahrenheit << " degrees Fahrenheit is " << celsius << " degrees Celsius" << endl;
    
    return 0;
}
