# Lecture5



//Biography
#include <iostream>
#include <string>
using namespace std;

int main() {

	string name;
	int age;
	string hometown;

	cout << "Type your name! " << endl;
	getline(cin, name);
	cout << "Hello " << name << " Where do you live?" << endl;
	getline(cin, hometown);

	cout << name << " What is your age?" << endl;
	cin >> age;

	cout << "Your name is " << name << endl;
	cout << "You live in " << hometown << endl;
	cout << "Your age is " << age << endl;
	
	return 0;
}
  
  
  
  //Temperature checker Celcius and Fahrenheit
  
  #include <iostream>
using namespace std;

int main() {
	cout << "Temperature Checker!" << endl << endl;

	double temp;
	char choices;

	cout << "Type 'C' to convert Celcius to Fahrenheit" << endl;
	cout << "Type 'F' to convert Fahrenheit to Celcius" << endl;
	cin >> choices;
	switch (choices) {
		{
	case 'C':
	case 'c':
		cout << "Type the celcius" << endl;
		cin >> temp;

		cout << (temp * 9 / 5) + 32;
		break;
		}
		{
	case 'F':
	case 'f':
		cout << "Type the Fahrenheit" << endl;
		cin >> temp;

		cout << (temp - 32) * 5/9;
			break;
		}
	default:
		cout << "Invalid Input!";
	}
}
  
  
  //Circle
  #include <iostream>
using namespace std;


int main() {
	double pi = 3.141;
	double radius;
	double area;
	cout << "Enter the radius of circle" << endl;
	cin >> radius;
	area = pi * radius * radius;

	cout << "The area of circle is " << area;

	return 0;
}
  
  
  //Tri,square,rect
  #include <iostream>
#include <string>
using namespace std;



int main()
{
    double length, width;

    cout << "Enter Length" << endl;
    cin >> length;
    cout << "Enter Width" << endl;
    cin >> width;

    double rect, tri, square;
    rect = length * width;
    tri = (length * width) * 0.5;
    square = length * length;

    cout << "Area of rectangle is " << rect;
    cout << "Area of triangle is " << tri;
    cout << "Area of square is " << square;


    return 0;
}
