This is a console-based implementation of a quiz game developed using C++. The game features a menu-driven interface and presents users with multiple-choice questions stored in a file (`questions.txt`). The player selects answers using number keys (1-4). The objective is to answer as many questions correctly as possible, earning 1 point for each correct answer. If the player selects a wrong answer, the game ends.

The game dynamically loads questions from a file, ensuring a different experience in each session. It includes a score tracking system, where scores are stored in `score.txt` after each game. The highest score is also displayed. Players have the option to view past scores or clear all saved scores.

At the start of the game, instructions and an introduction are displayed by reading from `gameintro.txt`. This project demonstrates fundamental file I/O, use of external libraries like `<conio.h>` for real-time input, and basic logic implementation using arrays, conditionals, and loops.

Key feature:

* Console interface using standard input/output
* Dynamic question loading from `questions.txt`
* Real-time input using `_getch()` (Windows-only)
* File-based score tracking (`score.txt`)
* Instruction display from `gameintro.txt`
* Options to view or clear previous scores
* Educational project for beginners learning C++
