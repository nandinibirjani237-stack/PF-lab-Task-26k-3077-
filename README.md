# Task1
#include <stdio.h>
int main() {
printf ("enter marks"); 
<br>scanf ("%d",&marks) ;<br>
printf ("enter income"); <br>
scanf ("%d",&income) ;<br>
if (marks>=80|| income<50000){
printf("Student qualifiles for scholarship");
} <br>else 
printf("Student doesnot qualifiles for scholarship");<br>
}
return 0;<br>
}
<br>
**Task 2** <br>
#include <stdio.h><br>
<br>int main() {
<br>int days;
<br>printf ("enter days"); 
<br>scanf("%d", &days) ;<br>
if (days==0)<br>
printf("no days");<br>
｝
else if (days>=1 || days<=5)<br>
printf("days = 50"');<br>
else if (days>=6 |1 days<=10)<br>
{
printf("days = 100"');<br>
}
<br>else{
printf("days=200");<br>
}
return 0; <br>
}

# Task 3<br>
#include <stdio.h>
#include <string.h>
int main() {
char name [30];
printf("enter your name");
fgets(name, sizeof (name),stdin);
name [strcspn(name, "In")]= 0 ;
puts (name) ;
return 0;
}
# Task 4
int main() {

float length;

float width;

printf("enter the length");

scanf ("%f",&length);

printf("enter the width");

scanf(%f",&width) ;

float area = length*width;


printf("area of rectangle is %f\n", area);

fLoat perimeter=2* (Length+width);

printf("Perimeter is %f",perimeter);
return 0;
}

# Task 5
#include <stdio.h>
int main () {
int value, square, cube;
printf( "enter the value");
scanf ("%d",&value);
square = value*value;
printf("%d", square);
cube = value*value*value;
printf("\n%d", cube) ;
return 0;
}

# Task 6
int main () {
float celsius, fehrenheit;
printf("enter the celsius");
scanf("%f",&celsius);
fehrenheit=(celsius*9/5)+32;
printf ("%f", fehrenheit);
return 0;
}

# Task 7
#include <stdio.h>
int main () {
int val1, val,val3;
float avg;
printf( "enter vall");
scanf ("%d",&val1);
printf ("enter val2"); 
scanf ("%d",&val2):
printf ("enter val3"); 
scanf ("%d",&val3);
avg=(val1+val2+val3)/3;
printf ("%f", avg);
}
return 0;
}

# Task 8
#include <stdio.h>
int main () {
int marks;
printf( "enter marks");
scanf ("%d", &marks) ;
if (marks>=50) {
printf("pass");
}
printf("fail");
}
return 0;
}
