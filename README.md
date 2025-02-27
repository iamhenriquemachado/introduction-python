# Introduction to Python

Python is a versatile programming language used for building various types of applications. It is open-source, meaning it's free to use, and has a rich ecosystem of packages that allow developers to leverage existing code instead of starting from scratch. Its syntax is simple and resembles natural language, making it beginner-friendly.

## Why Python?
- **Use cases:** Task automation, web applications, artificial intelligence, data science, and more.
- **Big tech adoption:** Used by companies like Spotify, Instagram, and Netflix.
- **Speed of development:** While Python can be slower than some languages, its simplicity and extensive libraries make development faster.

## How to Run Python Code

### Code Comments
```python
# This is a comment
```

### Performing Calculations
```python
print(4 + 5)
```

### Calculation Cheat Sheet
| Syntax | Action | Example | Output |
|--------|--------|---------|--------|
| * | Multiply | `4 * 10` | 40 |
| + | Addition | `7 + 9` | 16 |
| - | Subtract | `23 - 4` | 19 |
| / | Division | `27 / 3` | 9 |
| ** | Power | `3 ** 2` | 9 |
| % | Modulo | `7 % 4` | 3 |

### Examples:
```python
# Add 19 and 17
print(19+17)

# Subtract 12 from 99
print(99-12)

# Multiply 27 by 23
print(27*23)

# Divide 99 by 12
print(99/12)
```

## Variables and Data Types

### Variables
Variables store information that can be reused and updated.
```python
x = 10
name = "Python"
```

### Data Types
- **Integers**: Whole numbers (e.g., 80, 125, 330)
- **Float**: Numbers with decimal values (e.g., 3.14, 25.5)
- **Strings**: Text enclosed in quotes ('text' or "text")
- **Booleans**: True or False values

Check the type of a variable:
```python
print(type(x))
```

## Working with Strings

### Replacing Parts of Strings
```python
my_text = "Hello, my name’s Henrique."
my_text = my_text.replace("Henrique", "John")
```

### Changing Case
```python
text = "Hello World"
print(text.lower())  # Convert to lowercase
print(text.upper())  # Convert to uppercase
```

### Multi-line Strings
```python
my_text = """This is a multi-line string.
It spans multiple lines."""
```

## Lists
Lists store multiple values in a single variable.
```python
prices = [10, 20, 30]
```

### Accessing Elements
```python
print(prices[0])  # First element
print(prices[-1])  # Last element
print(prices[1:3])  # Second and third elements
```

## Dictionaries
Dictionaries store data in key-value pairs.
```python
products_dict = {"AG32": 10}
```

### Accessing Data
```python
print(products_dict["AG32"])  # Get value
print(products_dict.keys())  # Get all keys
print(products_dict.values())  # Get all values
```

### Adding a Key-Value Pair
```python
products_dict["UI56"] = 40
```

## Sets and Tuples

### Sets
Sets contain **unique** values and are unordered.
```python
unique_numbers = {1, 2, 3, 3, 4}
print(unique_numbers)  # Output: {1, 2, 3, 4}
```

### Tuples
Tuples are immutable (cannot be changed after creation).
```python
tuple_example = (1, 2, 3)
print(tuple_example)
```

## Conditional Statements and Operators

### Comparison Operators
| Operator | Meaning |
|----------|---------|
| == | Equals |
| != | Not equal |
| > | Greater than |
| < | Less than |
| >= | Greater than or equal to |
| <= | Less than or equal to |

Example:
```python
x = 10
y = 20
if x < y:
    print("x is smaller than y")
```

## Loops

### For Loop
```python
for value in range(5):
    print(value)
```

### While Loop
```python
count = 0
while count < 5:
    print(count)
    count += 1
```

## Building a Workflow
Python allows automation and scripting to create efficient workflows. Explore libraries such as Pandas, NumPy, and Flask for advanced use cases.

---

### Contributions
Feel free to contribute by adding more examples, use cases, and best practices!

### License
This project is open-source and free to use.

---

