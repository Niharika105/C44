# C44
Structure 
#include<stdio.h>
struct student{
char name[50];
int age;
float marks;
    };
int main(){
struct student s1={"Niharika",20,49.6};
printf ("student name is %s\n",s1.name);
printf ("age:%d\n",s1.age);
printf("marks:%.4f\n",s1.marks);
return 0;

}
