# text_wave 🌊

A small C program that prints text as a **wave animation** in the terminal. Each character moves up and down smoothly using a sine function, creating a flowing wave effect.

## ✨ Features
- Simple, easy-to-understand code
- Uses **ANSI escape codes** to animate in the terminal
- Works with any text input
- Smooth sine-based wave motion
- Fun visual effect in pure C

## 📋 Requirements
- C compiler (gcc, clang)
- Math library (libm)
- ANSI-compatible terminal

## 🛠️ Build & Run

### Compile
```bash
gcc -Wall -Wextra -Werror text_wave.c -o text_wave -lm
```

### Run
```bash
./text_wave "Hello 42!"
```

## 💡 Example
```bash
./text_wave "Wave!"
```
Watch as each character flows up and down in a smooth wave pattern!

## 📝 License
MIT License - See LICENSE file for details
