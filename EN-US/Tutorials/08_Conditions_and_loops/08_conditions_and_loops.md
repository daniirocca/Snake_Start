# Conditions and Loops

### Conditionals (`if`, `elif`, `else`)

Allow your code to **make decisions**.

```python
age = 18

if age >= 18:
    print("You're an adult.")
elif age == 17:
    print("Almost there!")
else:
    print("You're a minor.")
```

### Comparison operators

| Operator | Meaning            | Example      |
|----------|--------------------|--------------|
| `==`     | Equal              | `a == b`     |
| `!=`     | Not equal          | `a != b`     |
| `>`      | Greater than       | `a > b`      |
| `<`      | Less than          | `a < b`      |
| `>=`     | Greater or equal   | `a >= b`     |
| `<=`     | Less or equal      | `a <= b`     |

---

### `for` loop

Used to **iterate** over sequences like lists or strings.

```python
fruits = ["apple", "banana", "grape"]

for fruit in fruits:
    print(fruit)
```

#### With `range()`

```python
for i in range(5):
    print(i)  # 0, 1, 2, 3, 4
```

---

### `while` loop

Repeats code **while** the condition is true.

```python
counter = 0

while counter < 3:
    print("Counting:", counter)
    counter += 1
```

---

🧠 **Resumo:**  
- Use `if` para tomar decisões  
- Use `for` para percorrer coleções  
- Use `while` quando não souber exatamente quantas vezes repetir

🎯 **Próximo passo:** Vamos aprender sobre **funções** – como criar blocos reutilizáveis de código!
