# EX 54 D program to print all the letters of the English alphabet.
# DATE:
# AIM:
To write a C program to print all the letters of the English alphabet.

# Algorithm:
1. Start
2. Initialize a character variable ch with 'A'.
3. Loop from 'A' to 'Z':
4. Print the character.
5. Print a space after each character.
6. End the loop once 'Z' is printed.
7. End
# Program:
```
#include <stdio.h>

int main() {
    char ch;
    
    for (ch = 'A'; ch <= 'Z'; ch++) {
        printf("%c ", ch);
    }
    
    return 0;
}
```
# Output:
<img width="567" height="153" alt="image" src="https://github.com/user-attachments/assets/4e05c065-7705-4317-b97b-c9f4111f5793" />

# Result:
Thus the program was executed and the output was verified successfully.
