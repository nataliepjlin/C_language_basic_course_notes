```C
#include <stdio.h>
int main(){
    int n;
    int ni;
    int sum=0;
    int i;
//    int total;
    printf("Enter n:");
    scanf("%d",&n); //記得&不要漏掉!
//    printf("n= %d \n",n);
    for(i=1;i<=n;i++){
        printf("Enter %d of %d integer(s):",i,n);
        scanf("%d",&ni);
        sum+=ni;
//        printf("now_sum= %d \n",sum);
    }
//    printf("Sum is %d.",total); //use Ctrl + Shift + C to comment out
    printf("The sum of these %d integers is %d.\n",n,sum);
    return 0;
```