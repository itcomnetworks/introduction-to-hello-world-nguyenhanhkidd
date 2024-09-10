[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1He66eLM)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15855686)
# Autograding Example: C++
This example project is written in C++, and tested with make and [Catch2](https://github.com/catchorg/Catch2).

### The assignment
The tests are failing right now because of a bad base case in the factorial function. Correcting the base case will fix the tests.

### Setup command
N/A

### Run command
`make test`

### Notes
- `g++` can be used to compile and link C++ applications for use with existing test harnesses or other C++ testing frameworks.
- If students push `a.out` files, the autograder may attempt to run that version instead of a newly compiled binary. If this happens, and your student isn't on Linux, the script will crash. To fix this issue, it's recommended to clean before building.
