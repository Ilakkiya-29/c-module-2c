# c-module-2c

# EX NO:2-c) Addition of two numbers using function. 

# AIM: 
To write a C program to add two numbers using functions .

# ALGORITHM:
Get two numbers as inputs from the user.
Write a function to add those two numbers and call the function using the given numbers as arguments.

# PROGRAM:
```
#include <stdio.h>
int nis(int ,int);
int nis(int n1 ,int n2)
{
    printf("The Result of Addition is:%d",n1+n2);
    return 0;
}
int main()
{
    int num1,num2;
    scanf("%d %d",&num1,&num2);
    nis(num1,num2);
}
```

# OUTPUT: 
<img width="784" height="107" alt="image" src="https://github.com/user-attachments/assets/05f91d92-f6ec-4675-a8fa-857b07d2a82f" />


# RESULT: 
Thus the C program to add two given numbers using functions is successfully executed.
