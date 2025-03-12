# c-3
Rhombus pattern
#include <stdio.h>
int main()
{
    int n,j,i,s;
    printf("enter the rows :");
    scanf("%d", &n);
    for (i=1;i<=n;i++){
       for(s=1;s<=n-i;s++){
           printf(" ");
       }
       for(j=1;j<=(2*i-1);j++){ 
           printf("*");
       }
       printf("\n");
     }
     for (i=n;i>=1;i--){
       for(s=1;s<=n-i;s++){
           printf(" ");
       }
       for(j=1;j<=(2*i-1);j++){ 
           printf("*");
       }
       printf("\n");
     }


    return 0;
}
