#include <iostream>
#include <cstring>
#include <iomanip>
using namespace std;

char B = 42;
int A = 0;

int main()
{

    cout << "Enter amount: ";
    cin >> A;

    for (int i = 0; i < A; ++i)
    {

        for (int j = 0; j < (A-i)-1 ; ++j)
        {
            cout << ".";
        }
        for (int k = 0; k < A- (A-i)+1; ++k)
        {
          cout << "*";
        }
        cout << " " << endl;
    }




  return 0;
}
