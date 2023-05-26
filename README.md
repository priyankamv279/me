#include <iostream>

int main() 
  {
    int num1, num2, sum;
    
    // Read the first number from the user
    std::cout << "Enter the first number: ";
    std::cin >> num1;
    
    // Read the second number from the user
    std::cout << "Enter the second number: ";
    std::cin >> num2;
    
    // Calculate the sum
    sum = num1 + num2;
    
    // Display the result
    std::cout << "The sum of " << num1 << " and " << num2 << " is " << sum << std::endl;
    
    return 0;
}
