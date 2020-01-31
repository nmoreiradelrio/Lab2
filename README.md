#include <iostream>

using namespace std;

int main() {
  cout << "Enter the number of copies of “Big C++: Late Objects, (3rd Edition)” by Cay Horstmann that you would like to purchase. Each copy costs $40.46.\n";

int a;
double b;
b = 40.46;
cin >> a;

  cout << "Enter the number of copies of “Effective Modern C++: 42 Specific Ways to Improve Your Use of C++11 and C++14” by Scott Meyers that you would like to purchase. Each copy costs $35.48.\n";

int c;
double d;
d = 35.48;
cin >> c;

  cout << "Enter the number of copies of “C++ Primer Plus (6th Edition) (Developer's Library)” by Stephen Prata that you would like to purchase. Each copy costs $42.35.\n";

int e;
double f;
f = 42.35;
cin >> e;

double bookTotal;
bookTotal = (b*a)+(d*c)+(f*e);

  cout << "The total cost of books is:  $" << bookTotal;
  cout << endl;

double salesTax;
salesTax = (b+d+f)*.0725;  

  cout << "Sales tax at 7.25% is:       $"<< salesTax;
  cout << endl;

double shipping;
shipping = 5.99;

  cout << "Shipping for your order is:  $" << shipping;
  cout << endl;

double total;
total = bookTotal+salesTax+shipping;

  cout << "Total cost of your order is: $" << total;
  cout << endl;
}


