# square.c
#include<stdio.h>
int main() 
{ 
int ans,n; 
printf("enter a number:");
scanf("%d",&n); 
int findsquare(int);
ans= findsquare(n); 
printf("square is %d",ans);
return 0;
} 
int findsquare(int n) 
{ 
return(n*n);
}
