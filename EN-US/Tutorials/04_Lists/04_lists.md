# Working with Lists

### What is a list?

A **list** is a data structure that can store multiple values in a single variable.  
It can contain **different types** of elements and is **mutable** (can be changed).

```python
fruits = ["apple", "banana", "orange"]
numbers = [1, 2, 3, 4]
mixed = ["Python", 3.14, True]
```

### Accessing elements

```python
print(fruits[0])    # apple
print(fruits[-1])   # orange (last element)
```

### Modifying elements

```python
fruits[1] = "grape"
print(fruits)  # ['apple', 'grape', 'orange']
```

### Common list methods

```python
fruits.append("pineapple")   # Add to the end
fruits.insert(1, "kiwi")     # Insert at position 1
fruits.remove("apple")       # Remove "apple"
fruits.pop()                 # Remove the last item
fruits.sort()                # Sort the list
print(fruits)
```

### Length of a list

```python
print(len(fruits))  # Number of elements
```

### Looping with `for`

```python
for fruit in fruits:
    print(fruit)
```