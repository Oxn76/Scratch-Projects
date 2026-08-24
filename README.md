# Scratch Projects
## Overview

This repository contains two separate Scratch programming projects.

Both projects are designed as programming exercises to demonstrate fundamental concepts such as:

* Variables
* Loops
* Conditions
* User input
* String manipulation
* Arithmetic and modulo operations
* Displaying results

---

# Project 1 — Word Processing

## Purpose

The first project asks the user to enter a word and then creates a new version of the word with `*` placed between and around its letters.

For example:

```text
osama
```

becomes:

```text
*o*s*a*m*a*
```

## How It Works

When the **Green Flag** is clicked:

1. The program asks the user to enter a word.
2. The answer is stored in the `word` variable.
3. `star_word` is initialized with `*`.
4. `position` is set to `1`.
5. The program repeats once for every character in the word.
6. During each repetition:

   * It gets the character at the current position.
   * Adds the character to `star_word`.
   * Adds another `*`.
   * Displays the current result.
   * Increases `position` by `1`.

For the word `osama`, the result is built step by step:

```text
*o*
*o*s*
*o*s*a*
*o*s*a*m*
*o*s*a*m*a*
```

The final result is:

```text
*o*s*a*m*a*
```

## Concepts Demonstrated

* User input
* Variables
* Strings
* String length
* Accessing individual characters
* String concatenation
* `repeat` loops
* Incrementing variables

---

# Project 2 — Number Exercises

The second project contains two related programming exercises that use numbers, loops, conditions, and variables.

---

## Part 1 — Counting from 1 to 10

### Purpose

This part demonstrates how to use a `repeat until` loop to count from `1` to `10`.

### How It Works

When the **Green Flag** is clicked:

1. `number` is set to `1`.
2. The program repeats until `number > 10`.
3. It displays the current number.
4. `number` is increased by `1`.

The program displays:

```text
1
2
3
4
5
6
7
8
9
10
```

After the number becomes `11`, the condition `number > 10` becomes true and the loop stops.

### Concepts Demonstrated

* Variables
* `repeat until`
* Conditions
* Incrementing a variable
* Counting

---

## Part 2 — Finding and Counting Even Numbers

### Purpose

This part identifies the even numbers between `2` and `8` and counts how many even numbers there are.

### How It Works

This part starts when the **Space key** is pressed.

The program:

1. Sets `number` to `2`.
2. Sets `count` to `0`.
3. Repeats until `number > 8`.
4. Checks whether `number mod 2 = 0`.
5. If the remainder is `0`, the number is even.
6. Displays the even number.
7. Increases `count` by `1`.
8. Increases `number` by `1`.

The program finds:

```text
2, 4, 6, 8
```

The final result is:

```text
4
```

because there are four even numbers.

### Concepts Demonstrated

* `repeat until`
* `if` conditions
* Variables
* Incrementing
* Modulo (`mod`)
* Identifying even numbers
* Counting results

---

## Controls

| Action        | Result                                              |
| ------------- | --------------------------------------------------- |
| 🟢 Green Flag | Starts Project 1 and the counting part of Project 2 |
| Space Key     | Starts the even-number part of Project 2            |

The two projects are separate, but the scripts are stored together in the same Scratch file/repository.

---

# Project Variables

The Scratch file contains five variables:

| Variable    | Purpose                                      |
| ----------- | -------------------------------------------- |
| `word`      | Stores the word entered by the user          |
| `star_word` | Builds the word with `*` between the letters |
| `position`  | Keeps track of the current character         |
| `number`    | Used for the number exercises                |
| `count`     | Counts the number of even numbers found      |

The project was previously run using the word `osama`, resulting in:

```text
word      = osama
star_word = *o*s*a*m*a*
position  = 6
number    = 9
count     = 4
```

These values match the expected results of the programs.

---

# Scratch File Information

The Scratch file contains:

* 1 Stage
* 1 Sprite
* 5 Variables
* 3 SVG assets
* 2 WAV audio files
* 32 Scratch blocks

The project does not use:

* Lists
* Custom blocks/functions
* Extensions
* Broadcast messages
* Comments
* Complex animations
* Collision detection
* Game levels
* Scoring systems
* Menus or user interfaces
* Costume-changing logic
* Sound-playing logic

The project was created/saved using **Scratch 3.29.1**.

---

# Learning Objectives

## Project 1 — Word Processing

Practices:

* User input
* Variables
* String manipulation
* String length
* Accessing individual characters
* Loops
* Building a new string

## Project 2 — Number Exercises

Practices:

* Variables
* `repeat until`
* `if` conditions
* Counting
* Incrementing variables
* Modulo operations
* Identifying even numbers

---

# Conclusion

Overall, this repository contains **two separate Scratch programming projects**.

**Project 1** focuses on processing a user-entered word and adding `*` between its characters.

**Project 2** focuses on basic numerical programming. It demonstrates counting from `1` to `10` and finding and counting the even numbers from `2` to `8`.

Together, the projects demonstrate fundamental programming concepts including **variables, loops, conditions, user input, string manipulation, arithmetic, modulo operations, and output**.
