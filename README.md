/*
a) start program setup (#include<iostream>, etc)
b) declare all headers
c) enter if/else if statment for right triangle
d) pause the compiler, and return to 0
*/

#include<iostream>
#incliude<cmath>
using namespace std;
int main ()
{

int a,b,c;

cout<<"Enter the length of three sides"<<endl;
cin>>a>>b>>c;
if(pow(c,2)-pow(b,2)-pow(a,2)==0)
cout<<"It is a right triangle"<<endl;
else if (pow(b,2)-pow(a,2)+pow(c,2)==0)
cout<<"It's a right triangle"<<endl;
else if (pow(c,2)-poe(b,2)+pow(a,2)==0)
cout<<It's a right triangle"<<endl;
else
cout<<"It is not a right triangle"<<endl;

system("pause");
return 0;

}
