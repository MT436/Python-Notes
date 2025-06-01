# 🧠 Python 3 Comprehensions: List, Set, and Dictionary

Comprehensions provide a concise and readable way to create collections in Python. They are often more efficient and elegant than traditional loops.

---

## 🔹 List Comprehension

Creates a new list by applying an expression to each item in a sequence.

```python
# Squares of numbers 0 to 4
squares = [x**2 for x in range(5)]
print(squares)  # Output: [0, 1, 4, 9, 16]
````

### With Condition

```python
# Even numbers from 0 to 9
evens = [x for x in range(10) if x % 2 == 0]
print(evens)  # Output: [0, 2, 4, 6, 8]
```

---

## 🔹 Set Comprehension

Creates a set — an unordered collection of unique items.

```python
words = ["apple", "banana", "cherry", "apple"]
unique_lengths = {len(word) for word in words}
print(unique_lengths)  # Output: {5, 6}
```

---

## 🔹 Dictionary Comprehension

Creates a dictionary by generating key-value pairs.

```python
# Number and its square as key-value pairs
squares_dict = {x: x**2 for x in range(5)}
print(squares_dict)  # Output: {0: 0, 1: 1, 2: 4, 3: 9, 4: 16}
```

### With Condition

```python
# Squares of even numbers only
even_squares = {x: x**2 for x in range(10) if x % 2 == 0}
print(even_squares)  # Output: {0: 0, 2: 4, 4: 16, 6: 36, 8: 64}
```

---

## 📌 Summary

| Comprehension Type | Syntax Example                      | Description                  |
| ------------------ | ----------------------------------- | ---------------------------- |
| List               | `[expr for item in iterable]`       | Creates a list               |
| Set                | `{expr for item in iterable}`       | Creates a set (unique items) |
| Dictionary         | `{key: value for item in iterable}` | Creates a dictionary         |

---

💡 Comprehensions are powerful tools to write clean, readable, and efficient Python code!

```
