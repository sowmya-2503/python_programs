# Python Programming Practice

A collection of **Python programming practice programs** covering fundamental programming concepts such as conditionals, loops, numbers, arrays, strings, file handling, and basic problem-solving.

The repository currently contains **89 Python practice programs** organized as notebook code cells.

## 📚 Topics Covered

### 1. Basic Conditional Programs

Programs covering fundamental `if`, `elif`, and `else` concepts:

* Find maximum between two and three numbers
* Check whether a number is positive, negative, or zero
* Check divisibility by 5 and 11
* Check whether a number is even or odd
* Check whether a year is a leap year
* Check whether a character is an alphabet
* Check vowels and consonants
* Identify alphabets, digits, and special characters
* Check uppercase and lowercase characters
* Display the day of the week

### 2. Basic Calculation Programs

* Count currency notes for a given amount
* Calculate percentage and grade
* Calculate gross salary
* Calculate electricity bill
* Multiplication table
* Calculate powers
* Calculate factorial

### 3. Loops and Number Series

* Print natural numbers
* Print natural numbers in reverse
* Print alphabets from A to Z
* Print even and odd numbers
* Calculate sums of natural, even, and odd numbers
* Generate Fibonacci series

### 4. Number Programs

Programs for practicing digit manipulation and number properties:

* Count digits
* Find first and last digit
* Sum of first and last digit
* Reverse a number
* Check palindrome numbers
* Calculate sum and product of digits
* Find digit frequency
* Convert numbers to words
* Display ASCII values
* Find factors
* Check prime numbers
* Generate prime numbers
* Find prime factors
* Check Armstrong numbers
* Check perfect numbers
* Check strong numbers

### 5. Array Programs

Programs using Python lists/arrays:

* Find negative elements
* Find the second-largest element
* Find maximum and minimum elements
* Count even and odd elements
* Count negative elements
* Copy arrays
* Delete elements at a specified position
* Count element frequency
* Find unique elements
* Count duplicate elements
* Print alternate elements

### 6. String Programs

String manipulation and character-processing exercises:

* Find string length
* Compare strings
* Concatenate strings
* Count alphabets, digits, and special characters
* Count vowels and consonants
* Count words
* Reverse a string
* Check string palindrome
* Find first and last occurrence of a character
* Find all occurrences of a character
* Count character occurrences
* Find highest and lowest frequency characters
* Count frequency of each character
* Reverse the case of characters

### 7. File Handling

Basic Python file I/O exercises:

* Create a file and write content
* Separate even, odd, and prime numbers into files
* Copy contents from one file to another
* Merge two files
* Count characters, words, and lines in a file

### 8. Combined Number Problems

The notebook also includes programs that combine multiple concepts:

* Check whether a number is prime, Armstrong, or perfect
* Find prime numbers within an interval
* Find strong numbers within an interval
* Find Armstrong numbers within an interval
* Find perfect numbers within an interval

### 9. Mini Programs

* ATM transaction simulation

## 🛠️ Requirements

* Python 3.x
* Jupyter Notebook or another environment capable of running `.ipynb` files

Most programs use only Python's built-in functionality and do not require external libraries.

## 🚀 Getting Started

Clone or download the repository and open:

```text
python_programs.ipynb
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

Then open `python_programs.ipynb` and run the cells individually.

### Using JupyterLab

```bash
jupyter lab
```

## 💡 How to Use

Each notebook cell generally contains one standalone programming exercise.

For example, a typical program:

```python
def is_prime(n):
    if n < 2:
        return False

    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False

    return True

n = int(input("Enter a number: "))
print("Prime" if is_prime(n) else "Not Prime")
```

Run the cell and provide the requested input when prompted.

## 🎯 Learning Goals

This repository is intended to provide practice with:

* Python syntax and basic programming
* Conditional statements
* `for` and `while` loops
* Functions
* Lists and arrays
* Strings
* Dictionaries
* Number theory problems
* Input/output
* File handling
* Basic problem-solving techniques

## 📁 Repository Structure

```text
.
└── python_programs.ipynb
```

The notebook contains the complete collection of practice programs.

## ⚠️ Notes

Some exercises appear more than once in the notebook, particularly array operations such as deleting elements, counting frequencies, finding unique elements, and counting duplicates.

The file-handling examples also expect input files such as `numbers.txt`, `source.txt`, and `file1.txt`/`file2.txt` to exist when those cells are executed.

## 🤝 Contributing

Contributions are welcome. You can improve the repository by:

* Adding new Python practice problems
* Improving existing solutions
* Adding explanations and sample outputs
* Organizing exercises into separate notebooks or Python files
* Fixing bugs or edge cases

## 📄 License

No license information is currently specified in the repository.
