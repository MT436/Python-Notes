# ⚙️ Python 3 Built-in Functions

Python includes a powerful set of **built-in functions** that are always available without importing any libraries.

These functions help with:

- 🧮 Math & numbers
- 🧑‍💻 Type conversion
- 🧾 Input/output
- 🔁 Working with sequences
- 🧰 Utility operations

---

## ✅ Common Built-in Functions

| Function     | Description                                | Example                         |
|--------------|--------------------------------------------|----------------------------------|
| `print()`    | Display output                             | `print("Hello")`                |
| `input()`    | Take user input as a string                | `name = input("Enter name: ")`  |
| `len()`      | Get the length of a sequence               | `len("Python")` → `6`           |
| `type()`     | Check the data type                        | `type(123)` → `<class 'int'>`   |
| `int()`      | Convert to integer                         | `int("5")` → `5`                 |
| `float()`    | Convert to float                           | `float("3.14")` → `3.14`         |
| `str()`      | Convert to string                          | `str(42)` → `"42"`               |
| `abs()`      | Absolute value                             | `abs(-7)` → `7`                  |
| `max()`      | Maximum of values                          | `max(4, 7, 2)` → `7`             |
| `min()`      | Minimum of values                          | `min(4, 7, 2)` → `2`             |
| `sum()`      | Sum of iterable elements                   | `sum([1, 2, 3])` → `6`           |
| `round()`    | Round to nearest value                     | `round(3.14159, 2)` → `3.14`     |
| `sorted()`   | Return sorted list                         | `sorted([3, 1, 2])` → `[1, 2, 3]`|
| `range()`    | Generate sequence of numbers               | `list(range(3))` → `[0, 1, 2]`   |
| `enumerate()`| Get index-value pairs                      | `enumerate(['a', 'b'])`         |
| `zip()`      | Combine multiple iterables                 | `zip([1,2], ['a','b'])`          |

---

## 🧪 Example

```python
name = input("Enter your name: ")
print(f"Hello, {name.upper()}!")

numbers = [10, 20, 30]
print("Max:", max(numbers))
print("Sum:", sum(numbers))
print("Length:", len(numbers))
````

---

## 🧠 Pro Tip

You can list all built-in functions in Python using:

```python
print(dir(__builtins__))
```

Or explore the [official Python documentation](https://docs.python.org/3/library/functions.html) for the full reference.

---

💡 These built-in functions save time, reduce errors, and make your code cleaner and more readable.
