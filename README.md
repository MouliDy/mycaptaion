#include<iostream>
using namespace std;
 
int main()
{ int hr,min,sec,total;
    cout << "Enter time: " << endl;
    cout << "Hours? ";
    cin >> hr;
    cout << "Minutes? ";
    cin >> min;
    cout << "Seconds? ";
    cin >> sec;
    total = (hr*60*60)+(min*60)+sec;
    cout << "The time is = 0"<< hr <<":0" << min << ":0"<< sec<< endl;
    
   cout << "Time in total seconds: " << total;
}
