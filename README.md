#include<stdio.h>     //reverse the numbers
int main () {
    printf("the the number");
    scanf("%d",&n);
    while(n!=0) 
        { 
         rd=n%10;
         rev=rev*10+rd;
         n=n/10;
         }
         printf("reverse=%d",rev);
         return 0;
         }
