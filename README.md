# Python - Hello World

## Project Overview
This project is part of the **Holberton School** curriculum.  
It introduces the basics of **Python programming**, including running Python scripts, printing text, string manipulation, and basic formatting using f-strings.  

By the end of this project, you will be able to:  
- Run Python scripts from the shell.  
- Execute inline Python code.  
- Print text, integers, and floats using Python.  
- Manipulate strings: slicing, concatenation, and repetition.  
- Follow the **Zen of Python** principles.  
- Respect Python coding standards (PEP8 / pycodestyle).  

---

## Files and Scripts

| File | Description |
|------|-------------|
| `0-run` | Shell script that runs a Python file stored in the `$PYFILE` environment variable. |
| `1-run_inline` | Shell script that runs Python code stored in the `$PYCODE` environment variable. |
| `2-print.py` | Python script that prints: `"Programming is like building a multilingual puzzle"`. |
| `3-print_number.py` | Python script that prints an integer using f-strings. |
| `4-print_float.py` | Python script that prints a float with 2 decimal precision using f-strings. |
| `5-print_string.py` | Python script that prints a string 3 times and its first 9 characters. |
| `6-concat.py` | Python script that concatenates two strings and prints the result. |
| `7-edges.py` | Python script that prints the first 3 letters, last 2 letters, and middle of a word. |
| `8-concat_edges.py` | Python script that creates a new sentence by concatenating slices of strings. |
| `9-easter_egg.py` | Python script that prints **The Zen of Python** by Tim Peters. |

---

## Requirements

- All Python scripts must:  
  - Start with `#!/usr/bin/python3`  
  - Be executable (`chmod +x <file>`)  
  - Pass `pycodestyle` checks (version 2.7.*)  
  - End with a new line  

- All Shell scripts must:  
  - Start with `#!/bin/bash`  
  - Be executable  
  - Work on **Ubuntu 20.04 LTS**  

---

## How to Run

1. **Run Python file using `0-run`:**  
```bash
export PYFILE=main.py
./0-run
