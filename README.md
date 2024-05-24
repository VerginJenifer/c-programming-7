# C program to read a value and check whether a number is equal to 145 (strong number) using if-else
## AIM:
To Write a C program to read a value and check whether a number is equal to 145 (strong number) using if-else.
## ALGORITHM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the input value and other necessary variables for calculations.
4. Prompt the user to enter a value.
5. Read the input value from the user.
6. Initialize variables for factorial calculation and result storage.
7. Use if-else statements to check if the input value is equal to 145 (a strong number).
8. Within the if statement, calculate the sum of factorials of individual digits.
9. Compare the sum with the input value.
10. If the sum is equal to the input value, print that the number is a strong number.
11. If not, print that the number is not a strong number.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int x;
    scanf("%d",&x);
    if (x==145)
    {
        printf("Number is a strong number");
    }
    else
    {
        printf("Number is NOT a strong number");
    }
    return 0;
}
```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-7/assets/136251012/983234eb-9559-4b25-bc34-db8dd57a9b6a)
## RESULT:
Thus, C program to read a value and check whether a number is equal to 145 (strong number) using if-else was ececuted successfullly.
