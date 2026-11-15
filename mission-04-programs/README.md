# Mission 4 — How Programs Run

## 1. Task / objective

Run a simple Python program and understand the difference between compilers and interpreters.

## 2. Work completed

- Created a Python file named `hello.py`.
- Wrote a simple Python print statement.
- Executed the program using Python 3 from Terminal.
- Observed the program output.
- Studied the differences between compilers and interpreters.

### Program created

File: `hello.py`

```python
print("Hello from Python")
```

Expected output:

```text
Hello from Python
```

### Compiler vs Interpreter

| Comparison | Compiler | Interpreter |
|---|---|---|
| When translation happens | Before execution | During execution |
| Typical output | Translated code or executable | Usually no separate executable |
| Example | GCC (C compiler) | Python interpreter |
| Advantage | Can produce fast-running programs | Convenient for testing and interactive execution |

## 3. Commands / tools used

| Command / tool | Purpose |
|---|---|
| `python3` | Runs Python programs using Python 3. |
| `print()` | Displays text or values as program output. |
| Terminal | Used to execute the Python program. |
| VS Code | Used to create and edit the Python file. |

## 4. My understanding

A compiler translates source code into another form, often machine code, before the program runs. An interpreter executes program instructions at runtime.

A compiler can produce a standalone executable, while an interpreter commonly executes instructions through its runtime environment.

Python commonly compiles source code into bytecode before executing it using its virtual machine. Therefore, real programming language implementations can combine compilation and interpretation.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Created the Python file, executed it using Python 3 and reviewed the concepts of compilation and interpretation.

## 7. Evidence / files

- `mission-04-programs/hello.py`
- `mission-04-programs/README.md`
- Python execution output observed in Terminal.

## 8. Commit details

- **Commit ID:** `299d9ca`
- **Commit message:** `Add Python program and compiler interpreter comparison`
- **Branch:** `main`
- **Remote:** `origin`
- **Status:** Successfully pushed to GitHub.
- **Verification:** Working tree clean; local branch is up to date with `origin/main`.