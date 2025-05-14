# Error Handling in Python

### Why handle errors?

Errors (exceptions) can **stop your program**.  
Proper handling helps you **prevent crashes** and make your code more reliable.

---

### `try` / `except` block

```python
try:
    number = int(input("Enter a number: "))
    print(10 / number)
except ValueError:
    print("Error: Invalid number.")
except ZeroDivisionError:
    print("Error: Cannot divide by zero.")
```

---

### `else` and `finally`

```python
try:
    print("Trying...")
    result = 10 / 2
except ZeroDivisionError:
    print("Division error")
else:
    print("All good!")  # Runs if no exception
finally:
    print("End of block")  # Always runs
```

---

### Common exceptions

| Exception           | Happens when...                      |
|---------------------|--------------------------------------|
| `ValueError`        | Invalid value in a conversion        |
| `ZeroDivisionError` | Division by zero                     |
| `TypeError`         | Wrong type used in an operation      |
| `IndexError`        | List index out of range              |
| `KeyError`          | Dictionary key not found             |

---

✅ **Resumo:**  
- Use `try`/`except` para capturar e tratar exceções  
- Use `else` para ações quando não há erro  
- Use `finally` para garantir execução final (ex: fechar arquivos)

🎯 Parabéns! Agora você já conhece os principais fundamentos da linguagem Python.
