# code-3

#include<bits/stdc++.h>
using namespace std;

int main()
{
  int n; 
  cin>>n;     
  int a = 1;
  int b = 1;
  int curr;
  if(n==1 || n==2){
        curr =1;
  }
  for (int i = 3; i <= n; i += 1) {
        curr = a + b;
        a = b;
        b = curr;
  }
  cout<<curr<<"\n";
}       
