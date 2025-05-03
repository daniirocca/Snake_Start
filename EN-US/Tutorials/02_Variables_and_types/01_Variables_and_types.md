# Variables and Data Types

### What are variables?

Variables are like “boxes” you can use to store values.  
They have a **name** and hold some **data**.

```python
name = "Ana"
age = 25
height = 1.65
```

In this example, we created three variables with different types:

- `name` → text (string)
- `age` → whole number (int)
- `height` → decimal number (float)

### Variable naming rules

- Must start with a letter or underscore `_`
- Can contain letters, numbers, and `_`
- No spaces or special characters
- **Case-sensitive** (e.g., `Name` ≠ `name`)

```python
_valid = 123
full_name = "John Doe"
```

### Basic data types

| Type     | Example         | Description                  |
|----------|-----------------|------------------------------|
| `int`    | `10`, `-5`, `0` | Integer numbers              |
| `float`  | `3.14`, `-0.5`  | Decimal numbers              |
| `str`    | `"text"`        | Strings (text)               |
| `bool`   | `True`, `False` | Boolean values (true/false)  |

### Checking the type of a variable

```python
print(type(name))    # <class 'str'>
print(type(age))     # <class 'int'>
print(type(height))  # <class 'float'>
```

---

🎯 **Próximo passo:** Vamos aprender a trabalhar com **strings** — como manipulá-las, cortá-las e combiná-las!