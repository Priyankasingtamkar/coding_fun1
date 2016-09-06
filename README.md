# coding_fun1
#include<stdio.h>
#include<conio.h>
void main()
{
int i=1;
clrscr();
for(i=1;i<=100;i++)
{
if(i%3==0 && i%5==0)
printf("\n fizz buzz)
else if (i%3==0)
printf("\t fizz");
else if(i%5==0)
printf("\t buzz");
else
printf("\t %d",i);
}
getch();
}
