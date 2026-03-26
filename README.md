# program-4b
C module 4

EX NO:4-b) Count the number of punctuation characters. 

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AIM:
To write a C program to count the number of punctuation characters in a given string.

ALGORITHM:
1) Get a string as a input from the user.
2) Count the number of punctuation characters using for loop and if else statements.
3) Print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    fgets(str,sizeof(str),stdin);
    int count=0;
    for(int i=0;str[i]!='\0';i++)
    {
        if(str[i]==','||str[i]=='.'||str[i]=='!')
        count++;
    }
    printf("%d",count);
}
```
OUTPUT:
<img width="538" height="146" alt="Screenshot 2025-10-20 135551" src="https://github.com/user-attachments/assets/47185009-7ce2-4fc3-b633-bc2ba64e0fcb" />

RESULT:
Thus the C program to count the number of punctuation characters is executed successfully.











