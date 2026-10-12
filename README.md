# Palindrome Assignment

**Name:** Guduru Kaveri  
**Programming Language:** Python

## About the Project
This project checks whether a given number or string is a palindrome.

A palindrome reads the same forward and backward.

## Examples
- `madam` → Palindrome
- `hello` → Not a Palindrome
- `121` → Palindrome
- `123` → Not a Palindrome

## Python Program
```python
text = input("Enter a number or string: ")

if text == text[::-1]:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## How to Run
1. Install Python.
2. Download or clone this repository.
3. Open the terminal in the project folder.
4. Run:

```bash
python palindrome.py
```

## Sample Output
```text
Enter a number or string: madam
Palindrome
```

## Concepts Used
- Python
- User Input
- If-Else Statements
- String Slicing
- Reverse String Comparison


