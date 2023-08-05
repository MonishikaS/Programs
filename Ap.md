```c
#include <stdio.h>
int main()
{
    int i, v, d, n, t;
    printf("Enter the number of terms in AP series\n");
    scanf("%d", &t);
    printf("\nEnter the first term:-");
    scanf("%d", &n);
    printf("\nEnter the common difference:-");
    scanf("%d", &d);
    v = n;
    printf("AP Series is :-\n");
    for (i = 0; i < t; i++)
    {
        printf("%d ", v);
        v = v + d;
    }
    return 0;
}


Output:-
Enter the number of terms in AP series
5
Enter the first term:-1
Enter the common difference:-3
AP Series is :-
1 4 7 10 13
```
