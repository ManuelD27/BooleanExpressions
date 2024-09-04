# Boolean Expressions

This is a basic C program that demonstrates various boolean expressions.

## Description

The program compares numbers using different boolean operators and prints the results. It uses the following comparisons:
- `>` Greater than
- `<` Less than
- `==` Equal to
- `>=` Greater than or equal to
- `<=` Less than or equal to
- `!=` Not equal to

## Files

- `boolean_expressions.c`: The main C file containing the code for this project.

## How to Compile and Run

1. **Compile the Program**:
   - Open a terminal and navigate to the directory containing `boolean_expressions.c`.
   - Run the following command to compile the program:
     ```sh
     gcc -o boolean_expressions boolean_expressions.c
     ```

2. **Run the Program**:
   - Execute the compiled program using:
     - **Windows:**
       ```sh
       boolean_expressions.exe
       ```
     - **Mac/Linux:**
       ```sh
       ./boolean_expressions
       ```

## Code

Here is the code for the program:

```c
#include <stdio.h>
#include <stdbool.h>

int main() {
    
    bool value1 = 32 > 30;
    bool value2 = 30 < 32;
    bool value3 = 35 == 35;
    bool value4 = 35 != 90;
    bool value5 = 9 >= 6;
    bool value6 = 9 <= 6;
    
    printf("%d\n", value1);
    printf("%d\n", value2);
    printf("%d\n", value3);
    printf("%d\n", value4);
    printf("%d\n", value5);
    printf("%d\n", value6);

    return 0;
}
