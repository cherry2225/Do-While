#include<iostream>
using namespace std;
int main()
{
	int a=0, sum=0;
	
	do 
	{
		sum+=a;
		cout<<"Enter a Number:"<<endl;
		cin>>a;
	}
	while(a>=0);
	cout<<"The sum = "<<sum<<endl;
	return 0;
}
