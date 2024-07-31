#include<iostream>
using namespace std;
int main()
{
   string name;
   cout<<"Enter your name: ";
   cin>>name;
   int n=name.length();
   for(int i=0;i<n/2;i++)
   {
       int temp=name[i];
       name[i]=name[n-i-1];
       name[n-i-1]=temp;
   }
   cout<<"Reversed name is: "<<name;
}
