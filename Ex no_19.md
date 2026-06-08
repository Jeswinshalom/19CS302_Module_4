# EX 19 C program to input character from user and check whether character is uppercase or lowercase alphabet using simple if
## DATE:
## AIM:
To write a C program to input character from user and check whether character is uppercase or lowercase alphabet using simple if
## Algorithm
1.Start
2.Declare variables: num, leftShift, rightShift
3.Display the message: "Enter an integer"
4.Read the integer num from the user
5.Perform left shift: leftShift = num << 1
6.Perform right shift: rightShift = num >> 1
7.Display the original number num
8.Display the result of the left shift (leftShift)
9.Display the result of the right shift (rightShift)
10.End
## Program:
```
#include <stdio.h>
#include <ctype.h>
int main()
{
    char ch;
    scanf("%c", &ch);
    if(ch >='A' && ch<='Z')
    {
        printf("It is uppercase character");
    }
    else if(ch >='a' && ch<='z')
    {
        printf("It is in lowercase character");
    }
    else
    {
           printf("It is not an alphabet");
    }
    return 0;
}
```

## Output:
<img width="1133" height="200" alt="Screenshot 2026-06-08 142051" src="https://github.com/user-attachments/assets/52e6da28-d0e9-4b1e-9784-b780b4fd7792" />


## Result:
Thus the program was executed and the output was verified successfully.
