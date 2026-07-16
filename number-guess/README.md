# Number-Guess 🎯

A simple number guessing game in C where the program picks a random number between 1 and 100. The user keeps guessing until they find it, and after each guess, the program indicates if it's too high, too low, or correct. The program also tracks the number of attempts.

## ✨ Features
- Random number generation between 1 and 100
- Interactive gameplay with feedback on each guess (too high/too low)
- Attempt counter to track guesses
- Input validation for invalid entries
- Simple text-based interface

## 📋 Requirements
- C compiler (gcc, clang)
- Standard C library

## 🛠️ Build & Run

### Compile
```bash
gcc -Wall -Wextra -Werror NumberGuess.c -o number_guess
```

### Run
```bash
./number_guess
```

## 💡 Example Usage
```
=== Number Guessing Game ===
Guess a number between 1 and 100:
> 50
Too low! Try again.
> 75
Too high! Try again.
> 63
🎉 Correct! You found it in 3 attempts.
```

## 📝 License
MIT License - See LICENSE file for details
