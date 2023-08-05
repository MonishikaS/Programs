```c
#include <stdio.h>
int main()
{
    int i,v,r,n,t;
    printf("Enter the number of terms in GP series\n");
    scanf("%d", &t);
    printf("\nEnter the first term:-");
    scanf("%d",&n);
    printf("\nEnter the common difference:-");
    scanf("%d",&r);
    v=n;
    printf("GP Series is :-\n");
    for(i=0;i<t;i++){
        printf("%d ", v);
        v= v * r;
    }
 return 0;
}
```

Output:-

Enter the number of terms in GP series
5

Enter the first term:-1

Enter the common difference:-3
GP Series is :-
1 3 9 27 81
