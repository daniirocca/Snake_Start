# Working with Strings

### What is a string?

A **string** is a sequence of characters used to represent text.  
In Python, strings are written using **single** `'text'` or **double quotes** `"text"`:

```python
message = "Hello, world!"
name = 'Ana'
```

### Common string operations

#### 🔹 Concatenation (joining strings)

```python
name = "Ana"
message = "Hello, " + name
print(message)  # Hello, Ana
```

#### 🔹 f-strings (modern string interpolation)

```python
age = 25
print(f"I am {age} years old.")  # I am 25 years old.
```

#### 🔹 String length

```python
text = "Python"
print(len(text))  # 6
```

#### 🔹 Accessing characters

```python
fruit = "banana"
print(fruit[0])   # b
print(fruit[-1])  # a (last character)
```

#### 🔹 Slicing

```python
sentence = "Descomplicando Python"
print(sentence[0:13])  # Descomplicando
print(sentence[:5])    # Desco
print(sentence[5:])    # mplicando Python
```
