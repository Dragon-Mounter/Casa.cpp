#include <iostream>
#include <string> 

using namespace std;

int main()
{
    int a;
    int b;
    int c;
    int d;
    int e;
    cout << "Dati-mi primul termen:" << endl;
    cin >> a ;
    cout << "Dati-mi al doilea termen:" << endl;
    cin >> b;
    cout << "Dati-mi al treilea termen:" << endl;
    cin >> c;
    cout << "Dati-mi al patrulea termen:" << endl;
    cin >> d;
    cout << "Dati-mi al cincilea termen:" << endl;
    cin >> e;
     int summ = a + b + c + d + e;  
     std::string s = std::to_string(summ);
     cout << "Suma este: " + s << endl;
     return 0;
}
