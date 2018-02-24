# Vector-C-
A simple program to show use of vector in C++
#include<iostream>
#include<vector>
int main()
{
 int i,n,sum=o;
 cout<<"Enter the value of n ";
 cin>>n;
 vector <int> ar(n);
 cout<<"\nEnter the values in array ";
 for(i=0;i<n;i++)
 {
  cin>>ar[i];
  sum=sum+ar[i];
  }
  cout<<sum;
 return 0;
 }
