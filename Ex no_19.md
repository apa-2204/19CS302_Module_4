# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE: 30/04/2025
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
Start the program.

1.Declare an integer variable and two more for storing left and right shift results.

2.Read an integer and number of shift positions from the user.

3.Perform left shift (num << n) and right shift (num >> n) operations.

4.Display the original, left shifted, and right shifted values.

## Program:
```
#include <stdio.h>

int main() {
    int num, shift;
    int leftShift, rightShift;

    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift: ");
    scanf("%d", &shift);

    leftShift = num << shift;
    rightShift = num >> shift;

    printf("Original number: %d\n", num);
    printf("After left shift by %d positions: %d\n", shift, leftShift);
    printf("After right shift by %d positions: %d\n", shift, rightShift);

    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/3f4ee992-b1b4-4bf8-bbb0-fd190988765f)



## Result:
Thus the program was executed and the output was verified successfully.
