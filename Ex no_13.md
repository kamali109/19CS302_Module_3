# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.

## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include<stdio.h> 
int main() 
{ 
int i,j,n,a[10][10]; 
scanf("%d",&n); 
for(i=0;i<n;i++) 
{ 
for(j=0;j<n;j++) 
{ 
scanf("%d",&a[i][j]); 
} 
}for(i=0;i<n;i++) 
{ 
for(j=0;j<=n;j++) 
{ 
if(a[i][j]%2==1) 
{ 
printf("a[%d][%d] is %d \n",i,j,a[i][j]); 
} 
} 
printf("\n"); 
} 
return 0; 
}
```

## Output:

<img width="724" height="347" alt="image" src="https://github.com/user-attachments/assets/d0ba3574-409b-46bf-a35c-a40d9a2f58b8" />


## Result:
Thus the program was executed and the output was verified successfully.
