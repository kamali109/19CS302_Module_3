# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.

## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by:KAMALI.S 
RegisterNumber: 212222060109 
  #include<stdio.h> 
  Int dectobin(int d){ 
int bin =0,base=1,rem; 
while(d>0) 
{ 
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10; 
} 
printf(" = %d in binary",bin); 
return 0; 
} 
int main() 
{ 
int dec; 
scanf("%d",&dec); 
printf("%d in decimal",dec); 
dectobin(dec); 
return 0; 
} 
```
## Output:
```
<img width="821" height="236" alt="image" src="https://github.com/user-attachments/assets/9e3d5dc9-0eb1-4e95-96b7-975c1080417d" />
```
## Result:
Thus the program was executed and the output was verified successfully.
