# Trabalhando com Listas

### O que é uma lista?

Uma **lista** é uma estrutura de dados que pode armazenar múltiplos valores em uma única variável.  
Ela pode conter elementos de **diferentes tipos** e é **mutável** (pode ser alterada).

```python
frutas = ["maçã", "banana", "laranja"]
numeros = [1, 2, 3, 4]
mistura = ["Python", 3.14, True]
```

### Acessando elementos da lista

```python
print(frutas[0])   # maçã
print(frutas[-1])  # laranja (último elemento)
```

### Modificando elementos

```python
frutas[1] = "uva"
print(frutas)  # ['maçã', 'uva', 'laranja']
```

### Principais métodos de lista

```python
frutas.append("abacaxi")     # Adiciona ao final
frutas.insert(1, "kiwi")     # Insere na posição 1
frutas.remove("maçã")        # Remove o item "maçã"
frutas.pop()                 # Remove o último item
frutas.sort()                # Ordena a lista
print(frutas)
```

### Tamanho da lista

```python
print(len(frutas))  # Número de elementos
```

### Iterando com `for`

```python
for fruta in frutas:
    print(fruta)
```