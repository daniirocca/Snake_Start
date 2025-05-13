# Modules and Packages in Python

### What is a module?

A **module** is any `.py` file that contains functions, variables, or classes.  
You can **import** it into other Python files to reuse your code.

### Creating and using a module

Create a file named `my_module.py`:

```python
# my_module.py
def greet(name):
    return f"Hello, {name}!"
```

Now use it in another file:

```python
# main.py
import my_module

print(my_module.greet("Ana"))  # Hello, Ana!
```

### Specific imports

```python
from my_module import greet

print(greet("Carlos"))  # Hello, Carlos!
```

---

### What is a package?

A **package** is a **folder that contains multiple modules** and an `__init__.py` file (can be empty).  
It helps **organize your project** into reusable parts.

```
my_package/
├── __init__.py
├── greetings.py
├── math_tools.py
```

Usage in another script:

```python
from my_package.greetings import greet
```