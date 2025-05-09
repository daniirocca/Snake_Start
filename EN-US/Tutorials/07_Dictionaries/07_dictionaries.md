# Dictionaries in Python

### What is a dictionary?

A **dictionary** is a collection of **key–value pairs**.  
You use a **unique key** to access a related **value**.

```python
person = {
    "name": "Ana",
    "age": 25,
    "profession": "Engineer"
}
```

### Accessing values

```python
print(person["name"])      # Ana
print(person.get("age"))   # 25
```

### Adding or modifying values

```python
person["age"] = 26               # Update
person["city"] = "São Paulo"     # Add new key
```

### Removing items

```python
del person["profession"]
person.pop("city")
```

### Looping through the dictionary

```python
for key, value in person.items():
    print(f"{key}: {value}")
```

### Useful methods

```python
person.keys()     # Returns all keys
person.values()   # Returns all values
person.items()    # Returns key–value pairs
```