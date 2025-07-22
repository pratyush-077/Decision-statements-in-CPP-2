# Decision making statements in C++ using loops
# Pratyush Saha
# PRN-24070123078
Loops in C++ and Their Uses
In C++, loops are used to execute a block of code repeatedly until a condition is met.
They help avoid writing repetitive code and make programs more efficient.

Types of Loops in C++
1. for Loop
Used when the number of iterations is known.

Syntax:

cpp
Copy
Edit
for (initialization; condition; update) {
    // Code to repeat
}
Example: Print numbers 1 to 5

cpp
Copy
Edit
for (int i = 1; i <= 5; i++) {
    cout << i << " ";
}
2. while Loop
Used when the number of iterations is not known (condition checked before each iteration).

Syntax:

cpp
Copy
Edit
while (condition) {
    // Code to repeat
}
Example: Print numbers 1 to 5

cpp
Copy
Edit
int i = 1;
while (i <= 5) {
    cout << i << " ";
    i++;
}
3. do-while Loop
Similar to while, but executes at least once, even if the condition is false (condition checked after execution).

Syntax:

cpp
Copy
Edit
do {
    // Code to repeat
} while (condition);
Example:

cpp
Copy
Edit
int i = 1;
do {
    cout << i << " ";
    i++;
} while (i <= 5);
4. Nested Loops
Loops inside another loop (useful for tables, patterns, matrices).

Example: Multiplication Table (1 to 3)

cpp
Copy
Edit
for (int i = 1; i <= 3; i++) {
    for (int j = 1; j <= 3; j++) {
        cout << i * j << "\t";
    }
    cout << endl;
}
Uses of Loops
Repetitive tasks (printing sequences, taking multiple inputs).

Iterating arrays and strings.

Mathematical calculations (factorials, sums, tables).

Pattern printing (pyramids, stars, etc.).

Games and simulations (running game loops).

Real-time programs (checking sensors, inputs continuously).

