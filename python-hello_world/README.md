# Python - Hello World

## Project Overview
This project is part of the Holberton School curriculum. It introduces the fundamentals of **Python programming**, including:

- Running Python scripts and inline code
- Printing text, integers, and floats
- String manipulation: slicing, concatenation, repetition
- Using f-strings for formatting
- Understanding the Zen of Python
- Following Python coding style (PEP8 / pycodestyle)

---

## Files and Scripts

| File | Description |
|------|-------------|
| `0-run` | Shell script to run a Python file stored in the `$PYFILE` environment variable. |
| `1-run_inline` | Shell script to run Python code stored in the `$PYCODE` environment variable. |
| `2-print.py` | Prints: `"Programming is like building a multilingual puzzle"` |
| `3-print_number.py` | Prints an integer followed by `"Battery street"` using f-strings |
| `4-print_float.py` | Prints a float with 2 decimal precision using f-strings |
| `5-print_string.py` | Prints a string 3 times and its first 9 characters |
| `6-concat.py` | Concatenates two strings and prints the result |
| `7-edges.py` | Prints first 3 letters, last 2 letters, and middle of a word |
| `8-concat_edges.py` | Combines string slices to create a new sentence |
| `9-easter_egg.py` | Prints **The Zen of Python** by Tim Peters |

---

## Requirements

- Python scripts:
  - Start with `#!/usr/bin/python3`
  - Be executable (`chmod +x <file>`)
  - Pass `pycodestyle` checks
  - End with a new line
- Shell scripts:
  - Start with `#!/bin/bash`
  - Be executable
  - Work on **Ubuntu 20.04 LTS**

---

## How to Run

1. **Run a Python file with `0-run`:**
```bash
export PYFILE=main.py
./0-run
