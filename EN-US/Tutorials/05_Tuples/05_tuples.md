# Tuples in Python

### What is a tuple?

A **tuple** is an **immutable** data structure that stores multiple values.  
It’s similar to a list, but **cannot be modified** after it's created.

```python
person = ("Ana", 25, "Engineer")
```

### When to use tuples?

- When data **should not change**
- To represent **fixed values** (e.g., coordinates, dates, RGB)
- Faster than lists when reading data

### Accessing elements

```python
print(person[0])   # Ana
print(person[-1])  # Engineer
```

### Tuple length

```python
print(len(person))  # 3
```

### Tuple unpacking

```python
name, age, profession = person
print(name)       # Ana
print(profession) # Engineer
```

### Tuples with a single element

Use a comma at the end:

```python
single_tuple = (42,)
print(type(single_tuple))  # <class 'tuple'>
```

**Curiosity:** Because they are immutable, tuples can be used as **dictionary keys** (not lists!).