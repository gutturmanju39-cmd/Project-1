# Project-1
Adding two numbers

#include <stdio.h>

int main() {
    int num1, num2, sum;

    // Ask the user to enter two numbers
    printf("Enter first number: ");
    scanf("%d", &num1);

    printf("Enter second number: ");
    scanf("%d", &num2);

    // Calculate the sum
    sum = num1 + num2;

    // Display the result
    printf("Sum: %d\n", sum);

    return 0;
}
