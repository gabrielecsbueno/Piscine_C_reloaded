# Piscine Reloaded

A series of exercises that consolidates the fundamental C concepts learned during the 42 Piscine — from shell scripting to function pointers and file reading.

**Language:** C / Shell

---

## Shell (ex00 – ex05)

First contact with shell scripts.

---

## Basic Functions and Conditionals (ex06 – ex08)

Introduction to writing functions in C, using loops and conditional structures.

- **ex06 — ft_print_alphabet** — Prints the lowercase alphabet using a `while` loop
- **ex07 — ft_print_numbers** — Prints digits from 0 to 9 using a `while` loop
- **ex08 — ft_is_negative** — Takes an integer and prints `N` if negative or `P` if positive

---

## Pointers (ex09 – ex11)

Concept of pointers: accessing and modifying values by reference.

- **ex09 — ft_ft** — Assigns the value `42` to an integer via pointer
- **ex10 — ft_swap** — Swaps the values of two integers via pointers
- **ex11 — ft_div_mod** — Calculates division and modulo, storing the results via pointers

---

## Iteration and Recursion (ex12 – ex14)

Comparison between the two approaches to solve the same problem.

- **ex12 — ft_iterative_factorial** — Calculates factorial iteratively using `while`
- **ex13 — ft_recursive_factorial** — Calculates factorial recursively
- **ex14 — ft_sqrt** — Returns the integer square root of a number (or 0 if not exact)

---

## String Manipulation (ex15 – ex17)

Fundamental functions for working with strings in C.

- **ex15 — ft_putstr** — Prints a string character by character
- **ex16 — ft_strlen** — Returns the length of a string
- **ex17 — ft_strcmp** — Compares two strings lexicographically, returning -1, 0 or 1

---

## Command-Line Arguments (ex18 – ex19)

Using `argc` and `argv` to receive and process arguments in the terminal.

- **ex18 — ft_print_params** — Prints each argument passed to the program on a separate line
- **ex19 — ft_sort_params** — Sorts and prints arguments in lexicographic order (bubble sort)

---

## Dynamic Memory Allocation (ex20 – ex21)

Using `malloc` to allocate memory at runtime.

- **ex20 — ft_strdup** — Duplicates a string by dynamically allocating memory
- **ex21 — ft_range** — Creates and returns an array of integers between `min` and `max`

---

## Headers, Macros and Structs (ex22 – ex23)

Code organisation with header files, macros and custom types.

- **ex22 — ft_abs.h** — Defines the `ABS(Value)` macro that returns the absolute value of a number
- **ex23 — ft_point.h** — Defines the `t_point` struct with `x` and `y` fields to represent a 2D point

---

## Makefile and Compilation (ex24)

Build automation with Makefile and generation of a static library.

- **ex24 — libft** — Creates the static library `libft.a` with rules `all`, `clean`, `fclean` and `re`

---

## Function Pointers (ex25 – ex26)

Functions that receive other functions as arguments.

- **ex25 — ft_foreach** — Applies a function to each element of an integer array
- **ex26 — ft_count_if** — Counts how many elements of a string array satisfy a condition

---

## File I/O (ex27)

Reading files using the `open`, `read`, `write` and `close` syscalls.

- **ex27 — ft_display_file** — Reads and displays the content of a file passed as an argument

---

## How to compile

For exercises with Makefile (ex24 and ex27):

```bash
cd ex24
make        # compiles and generates libft.a
make clean  # removes object files
make fclean # removes objects and the library
make re     # recompiles everything from scratch
```

For individual C exercises:

```bash
gcc -Wall -Wextra -Werror ft_iterative_factorial.c -o factorial
./factorial
```

For Shell scripts:

```bash
chmod +x find_sh.sh
./find_sh.sh
```
