[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Ejskvh5l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22048915&assignment_repo_type=AssignmentRepo)

# Lab: Python Print Function ✨🐍

## Problem Description
You are given an integer **n**.  
Without using **any string methods or string building** (no `str()`, no `join()`, no f-strings, no `+` on strings, no lists of strings, etc.), print the integers from **1 to n** concatenated together as a single string with **no spaces**.

**Intended way**: Use a loop with `print(i, end='')` 💡  
**Example**  
`n = 3` → `123`  
`n = 10` → `12345678910`

**Important Rule** 🥺: I will check your code manually — **no string operations allowed**! Only direct printing with `end=''`.

## Constraints
- 1 ≤ n ≤ 150

## Input Format
A single integer **n**.

## Output Format
A single line with the numbers from 1 to n concatenated, no spaces.

## How to Work & Test Locally
1. Edit **only inside the `print_numbers(n)` function** in `main.py` (where it says `# Your code here!`).
2. To check your work: Run `python tests.py` → you get cute pass/fail feedback for all test cases! ✨
3. To test like real submission: Run `python main.py`, enter a number, and see the output.
4. When all tests pass, commit & push~! 🎉

## Sample Test Cases

### Sample Input 0 → Output
`3` → `123`

### Test Case 1
`1` → `1`

### Test Case 2
`5` → `12345`

### Test Case 3
`10` → `12345678910`

### Test Case 4
`15` → `123456789101112131415`

### Hidden Test Case (for fun)
Try `n=20` locally! Expected: `1234567891011121314151617181920`

Happy coding, my little Python kitties~! Let's make those numbers dance together perfectly! 🐾💕
