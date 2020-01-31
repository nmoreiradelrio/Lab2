#include <iostream>
 
int main() {
 std::cout << "Enter the number of copies of “Big C++: Late Objects, (3rd Edition)” by Cay Horstmann that you would like to purchase. Each copy costs $40.46.\n";
 
int a;
double b;
b = 40.46;
std::cin >> a;
 
 std::cout << "Enter the number of copies of “Effective Modern C++: 42 Specific Ways to Improve Your Use of C++11 and C++14” by Scott Meyers that you would like to purchase. Each copy costs $35.48.\n";
 
int c;
double d;
d = 35.48;
std::cin >> c;
 
 std::cout << "Enter the number of copies of “C++ Primer Plus (6th Edition) (Developer's Library)” by Stephen Prata that you would like to purchase. Each copy costs $42.35.\n";
 
int e;
double f;
f = 42.35;
std::cin >> e;
 
double bookTotal;
bookTotal = (b*a)+(d*c)+(f*e);
 
 std::cout << "The total cost of books is:  $" << bookTotal;
 std::cout << std::endl;
 
double salesTax;
salesTax = (b+d+f)*.0725; 
 
 std::cout << "Sales tax at 7.25% is:       $"<< salesTax;
 std::cout << std::endl;
 
double shipping;
shipping = 5.99;
 
 std::cout << "Shipping for your order is:  $" << shipping;
 std::cout << std::endl;
 
double total;
total = bookTotal+salesTax+shipping;
 
 std::cout << "Total cost of your order is: $" << total;
 std::cout << std::endl;
}


