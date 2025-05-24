# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE:
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1.Start
2.Read the integer num
3.Read the integer leftShift (number of positions to shift left)
4.Read the integer rightShift (number of positions to shift right)
5.Compute Left Shift Result:
6.leftResult = num << leftShift
7.Compute Right Shift Result:
8.rightResult = num >> rightShift
9.Display the original number num
10.Display the result of left shift leftResult
11.Display the result of right shift rightResult
12.End
## Program:
```
#include <stdio.h>

int main() {
    int num, leftShift, rightShift, leftResult, rightResult;

    // Input the number and shift values
    printf("Enter an integer: ");
    scanf("%d", &num);

    printf("Enter number of positions to shift left: ");
    scanf("%d", &leftShift);

    printf("Enter number of positions to shift right: ");
    scanf("%d", &rightShift);

    // Perform left and right shifts
    leftResult = num << leftShift;
    rightResult = num >> rightShift;

    // Display results
    printf("\nOriginal number: %d\n", num);
    printf("After left shift by %d positions: %d\n", leftShift, leftResult);
    printf("After right shift by %d positions: %d\n", rightShift, rightResult);

    return 0;
}

```

## Output:
Enter an integer: 10\
Enter number of positions to shift left: 2\
Enter number of positions to shift right: 1

## Result:
Thus the program was executed and the output was verified successfully.
