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
<img width="802" height="348" alt="image" src="https://github.com/user-attachments/assets/d40d7dff-477a-4abe-bd0c-c0263af4a466" />
RESULT:
Thus the code run successfully!
