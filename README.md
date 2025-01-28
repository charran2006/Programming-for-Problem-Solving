ALGORITHM TO CALCULATE SUM OF EVEN NUMBERS:
Input: Read an integer value n from the user (this is the upper limit)
Initialize: Set a variable sum = 0 to store the sum of even numbers.
Loop: Start a loop from i=1 to n.
For each iteration, check if the current number i is even (i.e., i%2==0).
If i is even, add i to sum
Output: After the loop finishes, print the value of sum, which represents the sum of all even numbers from 1 to n.





PSEUDOCODE:


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
