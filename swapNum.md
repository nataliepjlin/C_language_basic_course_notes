Ver 1
```C
#include <stdio.h>
int main(){
    int n1,n2,tmp;
    printf("Enter the first integer:");
    scanf("%d",&n1);
    printf("Enter the second integer:");
    scanf("%d",&n2);
    printf("init n1=%d, n2=%d \n",n1,n2);
    tmp=n1;
    n1=n2;
    n2=tmp;
    printf("swapped. n1=%d, n2=%d",n1,n2);
    return 0;
}
```
Ver 2 (has some restrictions)
```C
#include <stdio.h>
#include<stdio.h>
int main(){
    int n1,n2;

    printf("Please enter integer 1: ");
    scanf("%d",&n1);
    printf("Please enter integer 2: ");
    scanf("%d",&n2);
    printf("Initial values: n1=%d, n2=%d \n",n1,n2);
    n1=n1+n2;
    n2=n1-n2; //sum-n2=n1(swapping value)
    n1=n1-n2; //sum-(n2)'=sum-n1=n2
    printf("Swapped. Now values: n1=%d, n2=%d ",n1,n2);
    return 0;
}
```