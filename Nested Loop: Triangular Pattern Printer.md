## Nested Loop:Triangular Pattern Printer in C
## Aim
To write a C program that prints a triangular pattern of $ symbols using nested loops based on a user-defined value n.

## Algorithm
Declare variables n, i, and j.

Read the value of n from the user.

Use a for loop to iterate i from n to 1.

Inside the outer loop, use another for loop to iterate j from 1 to i and print "$".

After each inner loop, print a newline character (\n) to move to the next line.

## Program
```
#include <stdio.h>
int main() {
    int n, i, j;
    printf("Enter the number of rows: ");
    scanf("%d", &n);
    for (i = n; i >= 1; i--) {
        // Inner loop to print $ symbols
        for (j = 1; j <= i; j++) {
            printf("$");
        }
        // Move to next line
        printf("\n");
    }
}
```

## Output
```
Input:
Enter the number of rows: 5
Output:
$$$$$
$$$$
$$$
$$
$
```




## Result
The above programme is implemented and executed.
