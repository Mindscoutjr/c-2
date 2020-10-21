#include <iostream>

using namespace std;

int main()
{
    int a,b; 
    cout<<"\nHere are the numbers";
    cout<<"\nThe First Number is\t";
    cin>>a;
    cout<<"\nThe second Number is\t";
    cin>>b;
    a=a+b;   //20+10= a=30
    b=a-b;  //30-10 = b=20
    a=a-b; //30-10 = 20 
    
    cout<<"\nThe First Result is"<<a;
    cout<<"\nThe Second Result is"<<b;
    

    return 0;
}
