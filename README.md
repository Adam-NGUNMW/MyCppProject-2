# MyCppProject-2

#include <iostream>
#include <string>

using namespace std;


string ReadName()
{

	string Name;
	cout << " Enter Your Name : " << endl;
	getline(cin, Name);

	return Name;
}


void PrintName(string Name)
{
	cout << " \n Your Name is : " << Name << "\n";

}

int main()
{
	PrintName(ReadName());
	

}

