#include<stdio.h>
main()
{
int i,n,x,y,z;
scanf("%d",&n);
x=0;
y=1;
printf("%d",y);
for(i=0;i<=n;i++){
z=x+y;
x=y;
y=z;
printf(" %d",z);
}
}
