#include <stdio.h>

int main() {
    int n, sum = 0;

    // Step 1: Input n from the user
    printf("Enter the value of n: ");
    scanf("%d", &n);

    // Step 2: Loop through numbers from 1 to n
    for (int i = 1; i <= n; i++) {
        // Step 3: Check if the number is even
        if (i % 2 == 0) {
            sum += i;  // Add even number to sum
        }
    }

    // Step 4: Output the sum
    printf("The sum of even numbers from 1 to %d is: %d\n", n, sum);

    return 0;
}
