# CountTrailingZeros
  code is implemented in c++;
       #include<iostream>
#include<limits.h>
using namespace std;
int countTrailingZero(int n)
{
    int res = 0 ;
    for(int i = 5;i<=n;i=i*5)
    {
        res = res+(n/i);
    } return res;
}
int main()
{
    int n;
    cin>>n;
    cout<<countTrailingZero(n);
    return 0;
}


// code with brdocder007
