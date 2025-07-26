Yashvesh Singh 24070123138
#include<iostream>
using namespace std;
int main() {
      cout << "  Simple Calculator  " << endl;
      float a,b;
      cout << "Enter the first number: ";
      cin >> a;
      cout << "Enter the second number: ";
      cin >> b;
      float sum = a + b;
      float diff = a - b;
      float mult = a * b;
      float div = a / b;
      cout << "\nSum: " << sum; 
      cout << "\nDifference: " << diff;  
      cout << "\nProduct: " << mult;  
      cout << "\nDivision: " << div;  
    return 0;
    
}
output:
  Simple Calculator  
Enter the first number: 20
Enter the second number: 22

Sum: 42
Difference: -2
Product: 440
Division: 0.909091
