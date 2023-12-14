# binary-to-decimal
#include<iostream>
#include <math.h>
using namespace std;
int main()
{
    int n,s=0,i=0;
    cout<<"enter a binary number"<<endl;
    cin>>n;
    while(n!=0)
    {
        int d=n%10;
        s=s+(d*(pow(2,i)));
        i++;
        n=n/10;
    }
    cout<<s;
}
