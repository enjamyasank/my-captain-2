# my-captain-2
#include<stdio.h>
void main()
{int marks;
printf("enter the marks of the student");
scanf("%d",&marks);
if(marks>=85&&marks<=100)
printf("student has got grade A");
if(marks>=70&&marks<=84)
printf("student has got grade B");
if(marks>=55&&marks<=69)
printf("student has got grade C");
if(marks>=40&&marks<=54)
printf("student has got grade D");
else
printf("student has got grade F");
}
