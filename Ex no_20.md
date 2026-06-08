# EX 20 C program to convert the string 'LION' into lowercase
## DATE:
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1. Start.
2. Define the required variable.
3. Convert the string to lowercase.
4. Read the value using scanf.
5. Print out the answer.
6. End..

## Program:
```
#include <stdio.h>
#include <ctype.h>
int main() {
    char string[100]; 
    fgets(string, sizeof(string), stdin);
    for (int i = 0; string[i] != '\0'; i++) {
        string[i] = tolower(string[i]);
    }
    printf("Lower case String is:%s", string);
    return 0;
}

```

## Output:
<img width="1126" height="201" alt="image" src="https://github.com/user-attachments/assets/d4dc0a3b-dd6e-45d2-8a67-36b1ddf73733" />

## Result:
Thus the program was executed and the output was verified successfully.
