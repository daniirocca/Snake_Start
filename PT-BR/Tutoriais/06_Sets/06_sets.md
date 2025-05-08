# Conjuntos (Sets) em Python

### O que é um set?

Um **set** é uma coleção **não ordenada** e **sem elementos repetidos**.  
É útil quando você precisa garantir que todos os itens sejam únicos.

```python
numeros = {1, 2, 3, 3, 4}
print(numeros)  # {1, 2, 3, 4}
```

### Criando sets

```python
set_vazio = set()
set_animais = {"gato", "cachorro", "papagaio"}
```

### Principais operações com sets

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))        # União → {1, 2, 3, 4, 5}
print(a.intersection(b)) # Interseção → {3}
print(a.difference(b))   # Diferença → {1, 2}
```

### Métodos úteis

```python
animais = {"gato", "cachorro"}

animais.add("coelho")      # Adiciona um item
animais.remove("gato")     # Remove um item
animais.discard("tigre")   # Remove se existir (sem erro)
print("coelho" in animais) # Verifica se está presente
```