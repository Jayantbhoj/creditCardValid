# Credit Card Number Validator (Luhn Algorithm)

This program uses the Luhn Algorithm to validate credit card numbers entered by the user.

## Overview

The program prompts the user to input a credit card number for validation using the Luhn Algorithm. It checks the validity of the number by performing the following steps:

1. **Step 1**: Doubles every second digit from the right, adding both digits if the result is a two-digit number. It then sums all the obtained answers.
2. **Step 2**: Adds every odd-placed digit from the right to the previously calculated sum.
3. **Step 3**: Checks if the final sum is a multiple of 10. If yes, it declares the credit card number as valid; otherwise, it marks it as invalid.

## Usage

- Run the program.
- Input a credit card number when prompted. Enter 'exit' to quit the program.
- The program validates the number and displays whether it's valid or invalid.

## Instructions

- Clone or download the repository.
- Compile and run the `creditCardValid.cpp` file in a C++ environment.
- Follow the on-screen prompts to input a credit card number for validation.

Feel free to use this program to quickly verify credit card numbers using the Luhn Algorithm.

**Note**: This program is a basic demonstration and might not cover all aspects of credit card validation and security.
