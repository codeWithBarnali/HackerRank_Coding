# HackerRank_Coding
1) Sum and Difference of Two Numbers

Task

Your task is to take two numbers of int data type, two numbers of float data type as input and output their sum:

Declare  variables: two of type int and two of type float.
Read  lines of input from stdin (according to the sequence given in the 'Input Format' section below) and initialize your  variables.
Use the  and  operator to perform the following operations:
Print the sum and difference of two int variable on a new line.
Print the sum and difference of two float variable rounded to one decimal place on a new line.
Input Format

The first line contains two integers.
The second line contains two floating point numbers.

Constraints

 integer variables 
 float variables 
Output Format

Print the sum and difference of both integers separated by a space on the first line, and the sum and difference of both float (scaled to  decimal place) separated by a space on the second line.
-------------------------------------------------------------------------------------------------------------------------------------
Sample Input

10 4
4.0 2.0
Sample Output

14 6
6.0 2.0
------------------------------------------------------------------------------------------------------------------------------------
Explanation

When we sum the integers  and , we get the integer . When we subtract the second number  from the first number , we get  as their difference.
When we sum the floating-point numbers  and , we get . When we subtract the second number  from the first number , we get  as their difference.



CODE 1-------------------------------------------------------------------------------

#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main()
{
	int i,j;
    float k,l;
    scanf("%d %d\n", &i,&j);
    scanf("%f %f",&k,&l);
    printf("%d %d\n",i+j,i-j);
    printf("%.1f %.1f",k+l,k-l);
    return 0;
}

CODE 2----------------------------------------------------------------------------------------
#include<stdio.h>

int main(){
    int i, j;
    float f, g;
    scanf("%d %d %f %f", &i, &j, &f, &g);
    printf("%d %d\n%.1f %.1f", i+j, i-j, f+g, f-g);
    return 0;
}

