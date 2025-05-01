# Task: [Task Name from tasks.md]

**Phase:** [Phase Number and Name]

**Goal:**

[Clearly state the learning objective of this task. What should you understand or be able to do after completing it?]

**Concepts to Learn:**

*   [List the key concepts related to this task.]
*   [Use bullet points for clarity.]

**Resources:**

*   [Provide links to tutorials, documentation, articles, or videos.]
*   [Be specific about what each resource covers in relation to this task.]
*   [Example: Python Official Documentation on Data Types: [Link]]
*   [Example: Codecademy Python Course - Variables Section: [Link]]

**Practice Exercises/Code Examples:**

```python
# Add simple code examples or mini-exercises here to reinforce concepts.

# Example: Declaring variables
my_integer = 10
my_string = "Hello, Python!"
my_boolean = True

print(my_integer)
print(my_string)
print(my_boolean)
```

**Example Files (Phase 1)**

Here are examples for the first few files in Phase 1:

**`python_roadmap/phase_1_fundamentals/1.1_variables_and_data_types.md`**

# Task: Learn about variables and data types

**Phase:** 1: Python Fundamentals

**Goal:**

Understand how to store and represent different types of information in Python using variables and its built-in data types.

**Concepts to Learn:**

*   What is a variable and how to declare one.
*   Integer (`int`) data type.
*   Floating-point number (`float`) data type.
*   String (`str`) data type.
*   Boolean (`bool`) data type (True/False).
*   Using the `type()` function to check a variable's data type.
*   Basic type casting (converting between data types).

**Resources:**

*   Python Official Documentation - Data Types: https://docs.python.org/3/library/datatypes.html
*   Real Python - Python Variables Explained: https://realpython.com/python-variables/
*   Programiz - Python Data Types: https://www.programiz.com/python-programming/variables-data-types

**Practice Exercises/Code Examples:**

```python
# Declare variables of different data types
age = 30
price = 19.99
name = "Alice"
is_student = True

# Print the variables and their types
print(f"Age: {age}, Type: {type(age)}")
print(f"Price: {price}, Type: {type(price)}")
print(f"Name: {name}, Type: {type(name)}")
print(f"Is Student: {is_student}, Type: {type(is_student)}")

# Type casting example
age_string = str(age)
print(f"Age as string: {age_string}, Type: {type(age_string)}")

price_integer = int(price)
print(f"Price as integer: {price_integer}, Type: {type(price_integer)}") # Note: This truncates the decimal part
```

**`python_roadmap/phase_1_fundamentals/1.2_operators.md`**
# Task: Understand operators

**Phase:** 1: Python Fundamentals

**Goal:**

Learn how to perform operations on variables and values using various Python operators.

**Concepts to Learn:**

*   Arithmetic operators (+, -, *, /, %, //, **).
*   Comparison operators (==, !=, >, <, >=, <=).
*   Logical operators (and, or, not).
*   Assignment operators (=, +=, -=, *=, /=, etc.).
*   Operator precedence (order of operations).

**Resources:**

*   Python Official Documentation - Operators: https://docs.python.org/3/reference/expressions.html#operators
*   Programiz - Python Operators: https://www.programiz.com/python-programming/operators
*   Real Python - Python Operators and Expressions: https://realpython.com/python-operators-expressions/

### Practice Exercises/Code Examples:

```python
# Arithmetic operators
a = 10
b = 5
print(f"a + b = {a + b}")
print(f"a - b = {a - b}")
print(f"a * b = {a * b}")
print(f"a / b = {a / b}") # Division results in a float
print(f"a % b = {a % b}") # Modulo (remainder)
print(f"a // b = {a // b}") # Floor division (integer division)
print(f"a ** b = {a ** b}") # Exponentiation

# Comparison operators
x = 15
y = 20
print(f"x == y: {x == y}")
print(f"x != y: {x != y}")
print(f"x < y: {x < y}")

# Logical operators
is_sunny = True
is_warm = False
print(f"is_sunny and is_warm: {is_sunny and is_warm}")
print(f"is_sunny or is_warm: {is_sunny or is_warm}")
print(f"not is_sunny: {not is_sunny}")

# Assignment operators
count = 0
count += 1 # Equivalent to count = count + 1
print(f"Count after increment: {count}")
```

**Continuing for Other Tasks and Phases:**

You would continue this process for every task listed in your `tasks.md` file. Remember to:

*   **Customize the Goal:** Make sure the goal for each file accurately reflects the learning objective.
*   **Add Relevant Concepts:** List the specific concepts covered in that task.
*   **Find and Link Resources:** Search for and include high-quality resources for each topic. The more varied the resources (documentation, tutorials, videos), the better.
*   **Provide Meaningful Practice:** Include code examples that demonstrate the concepts and suggest small exercises for you to try.
*   **Use the "Your Notes" Section:** This is crucial for personal learning. Jot down explanations in your own words, common pitfalls to avoid, or ideas for how to apply the concepts.
*   **Update `tasks.md`:** As you complete the detailed file for a task and feel you understand it, remember to mark it as completed in your main `tasks.md` file.

This system provides a structured and detailed approach to your learning journey. Good luck building out the rest of the files!
