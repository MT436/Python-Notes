# 🔁 Python 3 Loops: `for` and `while`

Loops in Python are used to **repeat a block of code multiple times**. Python provides two main loop types:

- `for` loop — best for iterating over a known sequence
- `while` loop — best when the number of repetitions is unknown

---

## 🔷 `for` Loop

The `for` loop is used to iterate over a sequence (like a list, string, or range).

### ✅ Syntax

```python
for item in sequence:
    # do something
    print(item)
````

### 🔹 Example 1: Looping Through a List

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

### 🔹 Example 2: Using `range()`

```python
for i in range(5):
    print(i)  # Output: 0 to 4
```

### 🔹 Example 3: Looping Through a String

```python
for letter in "Python":
    print(letter)
```

---

## 🔶 `while` Loop

The `while` loop runs **as long as a condition is `True`**.

### ✅ Syntax

```python
while condition:
    # repeat this block
    print("Running...")
```

### 🔹 Example 1: Simple Counter

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

### 🔹 Example 2: Infinite Loop (with `break`)

```python
while True:
    print("This will run once")
    break
```

---

## ⏹ Loop Control Statements

Control how a loop behaves with:

| Keyword    | Description                                                      |
| ---------- | ---------------------------------------------------------------- |
| `break`    | Exit the loop immediately                                        |
| `continue` | Skip the rest of the current iteration                           |
| `else`     | Optional block that runs if loop completes normally (no `break`) |

### 🔸 Example with `break` and `continue`

```python
for i in range(5):
    if i == 3:
        break
    print(i)  # Stops at 2

for i in range(5):
    if i == 3:
        continue
    print(i)  # Skips 3
```

# ⏸️ Python 3: The `pass` Statement

The `pass` statement is a **null operation** — it does nothing when executed. It is used as a **placeholder** in your code where syntax requires a statement but you don’t want to write any code yet.

---

## ✅ Why Use `pass`?

- To create minimal class or function definitions before implementing them  
- To write empty loops or conditionals temporarily  
- To avoid syntax errors when code is incomplete

---

## 🔹 Examples

### Empty Function

```python
def my_function():
    pass  # TODO: implement later
````

### Empty Loop

```python
for i in range(5):
    pass  # Loop body to be added later
```

### Empty Conditional

```python
if some_condition:
    pass  # No action needed here (yet)
```

---

## 🧠 Notes

* `pass` does **not** affect program flow or logic.
* Useful during development to keep code syntactically correct.

---

💡 Use `pass` as a simple placeholder so your program runs without errors even if the logic is incomplete.

---

## 📌 Summary

| Feature      | Use Case                                 |
| ------------ | ---------------------------------------- |
| `for` loop   | Iterating over known sequences           |
| `while` loop | Looping while a condition remains `True` |
| `break`      | Stop the loop before it finishes         |
| `continue`   | Skip the current loop iteration          |
| `else`       | Runs if loop completes without `break`   |
