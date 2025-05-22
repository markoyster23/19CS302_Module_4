# EX 17 C Program to compare two strings without using strcmp().
## DATE:
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Start. 
2. Define a variables a,b,c. 
3. Write program to find the smallest among the three numbers. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End. 

## Program:
```
#include<stdio.h> 
int main() 
{ 
int a,b,c;  
scanf("%d%d%d",&a,&b,&c);  
if(a<b && a<c) 
{ 
printf("%d is the smallest number.",a); 
} 
else if(b<a && b<c) 
{ 
printf("%d is the smallest number.",b); 
} 
else 
{ 
printf("%d is the smallest number.",c); 
} 
}
```

## Output:
10 25 5\
The smallest number is: 5

## Result:
Thus the program was executed and the output was verified successfully.
