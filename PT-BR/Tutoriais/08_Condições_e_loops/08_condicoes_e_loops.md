# Condições e Loops

### Condicionais (`if`, `elif`, `else`)

Permitem tomar **decisões** no seu código.

```python
idade = 18

if idade >= 18:
    print("Você é maior de idade.")
elif idade == 17:
    print("Falta pouco!")
else:
    print("Você é menor de idade.")
```

### Operadores de comparação

| Operador | Significado        | Exemplo      |
|----------|--------------------|--------------|
| `==`     | Igual               | `a == b`     |
| `!=`     | Diferente           | `a != b`     |
| `>`      | Maior que           | `a > b`      |
| `<`      | Menor que           | `a < b`      |
| `>=`     | Maior ou igual      | `a >= b`     |
| `<=`     | Menor ou igual      | `a <= b`     |

---

### Laço `for`

Usado para **iterar** sobre sequências como listas ou strings.

```python
frutas = ["maçã", "banana", "uva"]

for fruta in frutas:
    print(fruta)
```

#### Com `range()`

```python
for i in range(5):
    print(i)  # 0, 1, 2, 3, 4
```

---

### Laço `while`

Repete o bloco de código **enquanto** a condição for verdadeira.

```python
contador = 0

while contador < 3:
    print("Contando:", contador)
    contador += 1
```