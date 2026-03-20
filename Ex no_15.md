# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: KAMALI.S
RegisterNumber:  212222060109
*/
#include <stdio.h> 
int main() { 
    int arr[100], n; 
    scanf("%d", &n); 
    for (int i = 0; i < n; i++) { 
        scanf("%d", &arr[i]); 
    } 
    for (int i = 0; i < n; i++) { 
        if (arr[i] % 2 == 0) 
            printf("E "); 
        else 
            printf("%d ", arr[i]); 
    } 
    printf("\n"); 
    return 0; 
} 

```

## Output:


<img width="795" height="173" alt="image" src="https://github.com/user-attachments/assets/8d269b32-baa0-4bc0-b4b0-788c0dbb354d" />

## Result:
Thus the program was executed and the output was verified successfully.
