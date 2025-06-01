# 🐍 Python 3: `if`, `elif`, `else` – Conditional Statements

In Python, `if`, `elif`, and `else` are used to make decisions in your code. These **conditional statements** execute different blocks of code depending on whether conditions are `True` or `False`.

---

## ✅ `if` Statement

The `if` block runs only when the condition is `True`.

```python
x = 5

if x > 0:
    print("x is positive")
````

---

## 🔄 `elif` – Else If

The `elif` block runs if the `if` condition is `False`, and the `elif` condition is `True`.

```python
x = 0

if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
```

---

## 🔚 `else` – Default Case

The `else` block runs only if all previous conditions are `False`.

```python
x = -3

if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")
```

---

## 🧠 Notes

* Use **`if`** to test the first condition.
* Use **`elif`** to test additional conditions.
* Use **`else`** for a default fallback.
* Conditions use comparison operators like: `==`, `!=`, `>`, `<`, `>=`, `<=`.
* Python uses **indentation** (4 spaces by default) to define blocks of code.

---

## 🧪 Example

```python
temperature = 30

if temperature > 35:
    print("It's very hot")
elif temperature > 25:
    print("It's warm")
else:
    print("It's cool or cold")
```

**Output:**

```
It's warm
```
