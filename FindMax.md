#include <iostream>
using namespace std;

int main()
{
    int a, b;
    int maxVal;

    cout << "Enter integer a: ";
    cin >> a;

    cout << "Enter integer b: ";
    cin >> b;

    if (a > b)
    {
        maxVal = a;
    }
    else
    {
        maxVal = b;
    }

    cout << "The largest value is: " << maxVal << endl;

    return 0;
}
