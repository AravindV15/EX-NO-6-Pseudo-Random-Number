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

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Random numbers are:\n");

    for (i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}
```

# OUTPUT:
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/ba449f78-c071-4b39-9129-da2d1fe7e995" />


# RESULT:
Thus, the implementation of Pseudorandom Number Generation Using Standard library has been executed successfully
