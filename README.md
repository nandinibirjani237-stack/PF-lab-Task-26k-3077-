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
#include <stdio.h><br>
#include <string.h><br>
<br>int main() {
<br>char name [30];
<br>printf("enter your name");
<br>fgets(name, sizeof (name),stdin);<br>
name [strcspn(name, "In")]= 0 ;<br>
puts (name) ;<br>
return 0;<br>
}<br>
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
#include <stdio.h><br>
<br>int main () {
<br>int value, square, cube;
<br>printf( "enter the value");
<br>scanf ("%d",&value);
<br>square = value*value;
<br>printf("%d", square);
<br>cube = value*value*value;
<br>printf("\n%d", cube) ;
<br>return 0;
}

# Task 6
<br>int main () {
<br>float celsius, fehrenheit;
<br>printf("enter the celsius");
<br>scanf("%f",&celsius);
fehrenheit=(celsius*9/5)+32;<br>
printf ("%f", fehrenheit);<br>
return 0;<br>
}

# Task 7
#include <stdio.h><br>
<br>int main () {
<br>int val1, val,val3;
<br>float avg;
<br>printf( "enter vall");
<br>scanf ("%d",&val1);
<br>printf ("enter val2"); 
<br>scanf ("%d",&val2):
<br>printf ("enter val3"); 
<br>scanf ("%d",&val3);
avg=(val1+val2+val3)/3;
printf ("%f", avg);<br>
}
return 0;<br>
}

# Task 8
#include <stdio.h><br>
int main () {
int marks;
printf( "enter marks");<br>
scanf ("%d", &marks) ;<br>
<br>if (marks>=50) {
printf("pass");
}
<br>printf("fail");
}
<br>return 0;
}
