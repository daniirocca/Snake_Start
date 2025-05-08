# Sets in Python

### What is a set?

A **set** is an **unordered** collection with **no duplicate items**.  
It’s useful when you need to ensure uniqueness.

```python
numbers = {1, 2, 3, 3, 4}
print(numbers)  # {1, 2, 3, 4}
```

### Creating sets

```python
empty_set = set()
animals = {"cat", "dog", "parrot"}
```

### Common set operations

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))        # Union → {1, 2, 3, 4, 5}
print(a.intersection(b)) # Intersection → {3}
print(a.difference(b))   # Difference → {1, 2}
```

### Useful methods

```python
animals = {"cat", "dog"}

animals.add("rabbit")         # Add item
animals.remove("cat")         # Remove item
animals.discard("tiger")      # Safe remove (no error)
print("rabbit" in animals)    # Membership check
```