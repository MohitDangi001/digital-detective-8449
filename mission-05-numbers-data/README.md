# Mission 5 — Numbers and Data

## 1. Mission Objective

To understand number systems, convert numbers between decimal, binary and hexadecimal, verify conversions using Python, build a number converter program, and learn the basics of text encoding.

## 2. Manual Number Conversions

| Task | Conversion | Answer |
|---|---|---|
| 1 | Decimal 13 to binary | 1101 |
| 2 | Decimal 25 to binary | 11001 |
| 3 | Binary 1010 to decimal | 10 |
| 4 | Binary 1101 to decimal | 13 |
| 5 | Hexadecimal A to decimal | 10 |
| 6 | Hexadecimal 1F to decimal | 31 |
| 7 | Binary 1111 to hexadecimal | F |

## 3. Python Verification

Used Python's built-in conversion functions to verify the manual calculations.

| Python Expression | Result |
|---|---|
| `bin(13)` | `0b1101` |
| `bin(25)` | `0b11001` |
| `int('1010', 2)` | `10` |
| `int('1101', 2)` | `13` |
| `hex(25)` | `0x19` |
| `hex(13)` | `0xd` |
| `int('A', 16)` | `10` |
| `int('1F', 16)` | `31` |
| `hex(int('1111', 2))` | `0xf` |

All Python results matched the manual calculations.

## 4. Number Converter Program

Created `number_converter.py` using Python.

The program:
- Accepts a positive decimal number from the user.
- Converts the input text into an integer using `int()`.
- Displays its binary representation using `bin()`.
- Displays its hexadecimal representation using `hex()`.

### Code

```python
number = int(input("Enter a positive decimal number: "))

print("Binary:", bin(number))
print("Hexadecimal:", hex(number))
```

### Test Results

| Input | Binary | Hexadecimal |
|---|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 255 | 0b11111111 | 0xff |

All three test cases produced the expected results.

## 5. Text Encoding and ASCII

ASCII decimal values:
- Uppercase A = 65
- Lowercase a = 97

Python verification using `ord()`:
- `ord('A')` = 65
- `ord('a')` = 97
- `ord('₹')` = 8377

Computers need encoding standards to map characters to numeric values and bytes consistently so that text can be stored, transmitted and decoded correctly.

The Indian Rupee symbol (₹) is an example of a character outside basic ASCII. Unicode and UTF-8 support a much wider range of characters.

## 6. Commands and Functions Used

- `python3` — launches the Python interpreter.
- `input()` — accepts user input.
- `int()` — converts text into an integer or parses a number in a specified base.
- `bin()` — converts an integer into binary.
- `hex()` — converts an integer into hexadecimal.
- `ord()` — returns the Unicode code point of a character.
- `exit()` — exits Python interactive mode.

## 7. My Understanding

I learned that:
- Binary uses base 2, decimal uses base 10, and hexadecimal uses base 16.
- Computers use binary to represent data through two distinguishable electronic states.
- Python provides built-in functions to convert numbers between different bases.
- Text encoding allows computers to represent characters using numeric values.
- Terminal commands and Python expressions must be entered in their respective environments.

## 8. Difficulties Faced and Solutions

I initially entered Python expressions directly into the macOS Terminal shell instead of the Python interpreter. I learned to launch Python using `python3` and enter Python expressions at the `>>>` prompt.

I also learned that the converter expects a decimal number, not a Python expression.

## 9. Evidence and Files

- `number_converter.py` — decimal-to-binary and hexadecimal converter.
- This README — manual calculations, Python verification, test results and text-encoding notes.

## 10. Commit Details

- Commit ID: `1f1903f`
- Commit Message: `Build number converter and practise data representation`
- Branch: `main`
- Remote: `origin`
- Status: Successfully pushed to GitHub.