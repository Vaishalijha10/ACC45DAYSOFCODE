# ACC45DAYSOFCODE
#include<stdio.h>
#include<conio.h>
void main()
{
int m,e,h,s,sst,p;
printf("enter the no. of maths:");
scanf("%d",&m);
printf("enter the no. of english:");
scanf("%d",&e);
printf("enter the no. of hindi:");
scanf("%d",&h);
printf("enter the no. of science:");
scanf("%d",&s);
printf("enter the no. of social science:");
scanf("%d",&sst);
p=((m+e+h+s+sst)*100)/500;
printf("here is percentage:",p);
getch();
}
