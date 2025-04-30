# EX 19 C program to find smallest among three elements and display the result.
## DATE: 30/04/2025
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

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
![image](https://github.com/user-attachments/assets/8abc4f10-8136-47d7-9b51-80b86e546983)



## Result:
Thus the program was executed and the output was verified successfully.
