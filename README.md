# Arithmetic-Operators
This repository contains a comprehensive collection of programs that demonstrate the use of arithmetic operators.
<br>
<p align="center">
<strong>Experiment No 3</strong>
</p>
<br>

## Aim
<br>
To add two numbers in C++
<br>

## Software Used
<br>
- Dev C++
<br>

## Theory
<br>
<p>Arithmetic operators in C++ are fundamental tools used to perform mathematical operations on operands. These operators include addition (+), subtraction (-), multiplication (*), division (/), and modulus (%). They allow programmers to execute basic arithmetic calculations within their code, enabling the manipulation and transformation of data.</p>
<p>Each operator serves a specific purpose: the addition operator (+) adds two operands, while the subtraction operator (-) subtracts one operand from another. Multiplication (*) is used to multiply two operands, and division (/) divides one operand by another, producing a quotient. The modulus operator (%) finds the remainder of the division of one operand by another, useful in operations requiring remainder calculations.</p>

## Algorithm

<br>
Step 1: Start
<br>
Step 2: Declare three variables:number1,number2,sum.
<br>
Step 3: Input the first number (num1) from the user.
<br>
Step 4: Input the second number (num2) from the user.
<br>
Step 5: sum=num1+num2
<br>
Step 6: Display sum
<br>
Step 7: End
<br>

## Program Code

<br>

```cpp
#include <iostream>
using namespace std;

int main() {
    int number1;
    int number2;
    int sum;
    cout << "Enter the first number: ";
    cin >> number1;
    cout << "Enter the second number: ";
    cin >> number2;
    sum = number1 + number2;
    cout << "The sum of " << number1 << " and " << number2 << " is: " << sum << endl;
    return 0;
}
```

<br>

## Output

<br>

![image](https://github.com/user-attachments/assets/4e8131b7-63c6-41b4-8aa1-1df42eee00da)


## Conclusion

<br>
Hence we learned about adding two numbers in C++, where the input is provided by the user.
<br>
