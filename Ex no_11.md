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
https://private-user-images.githubusercontent.com/145656057/441027366-6092ab3b-7c24-4c24-8c3b-23662be759ee.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQwMjM1NjMsIm5iZiI6MTc3NDAyMzI2MywicGF0aCI6Ii8xNDU2NTYwNTcvNDQxMDI3MzY2LTYwOTJhYjNiLTdjMjQtNGMyNC04YzNiLTIzNjYyYmU3NTllZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMyMFQxNjE0MjNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yYjU1MWU3NjA3YjdhMGYzMjJjZWZiMzExYmVmNDg0YzYyZWFkNjQxOWJjYjc0MzM0MzVkNzc3YzkyOTk2MTY2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Ej5983avpBnp1GJBrdjRJTf04cJz0mFydIyBfBqKo6c
```
## Result:
Thus the program was executed and the output was verified successfully.
