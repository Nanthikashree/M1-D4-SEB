# M1-D4-SEB
AIM:
Write a C program to swap two numbers without using third variable.

PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    printf("Numbers before swapping: %d %d",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("\nNumbers after swapping: %d %d",a,b);
    
}
```
OUTPUT:
 <img width="1005" height="381" alt="image" src="https://github.com/user-attachments/assets/9e08af9d-b8c3-4d8c-a8f5-5946eadd1fea" />

RESULT:
Thus the code run successfully!
