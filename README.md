# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:

```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    // Step 3: Get the number of random numbers
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    // Step 2: Seed the random number generator
    srand(time(0));

    // Step 4: Generate and print the numbers
    printf("Generated numbers:\n");
    for(i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    // Step 5: End program
    return 0;
}

```

# OUTPUT:

<img width="628" height="350" alt="image" src="https://github.com/user-attachments/assets/65a88b24-a0d1-4ee6-a6a7-c5dae81ecf9d" />


# RESULT:
