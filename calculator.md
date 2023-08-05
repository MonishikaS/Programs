```c
#include <stdio.h>  
int main()  
{  
    // declare local variables  
    char opt;  
    int n1,n2,r;     
    printf (" Select an operator (+, -, *, /) to perform an operation in C calculator \n ");  
    scanf ("%c", &opt); // take an operator  
    printf (" Enter the first number: ");  
    scanf(" %d", &n1); // take fist number  
    printf (" Enter the second number: ");  
    scanf (" %d", &n2); // take second number  
      
    if (opt == '+')  
    {  
        r = n1 + n2; // add two numbers  
        printf (" Addition of %d and %d is: %d", n1, n2, r);  
    }  
      
    else if (opt == '-')  
    {  
        r = n1 - n2; // subtract two numbers  
        printf (" Subtraction of %d and %d is: %d", n1, n2, r);  
    }  
      
    else if (opt == '*')  
    {  
        r = n1 * n2; // multiply two numbers  
        printf (" Multiplication of %d and %d is: %d", n1, n2, r);  
    }  
      
    else if (opt == '/')  
    {  
        if (n2 == 0)   // if n2 == 0, take another number  
        {  
            printf (" \n Divisor cannot be zero. Please enter another value ");  
            scanf ("%d", &n2);        
        }  
        r = n1 / n2; // divide two numbers  
        printf (" Division of %d and %d is: %d", n1, n2, r);  
    }  
    else  
    {  
        printf(" \n You have entered wrong inputs ");  
    }  
    return 0;  
}

Output:-
 Select an operator (+, -, *, /) to perform an operation in C calculator 
 *
 Enter the first number: 2
 Enter the second number: 4
 Multiplication of 2 and 4 is: 8

```
