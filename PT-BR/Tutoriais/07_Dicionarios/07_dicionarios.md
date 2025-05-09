# Dicionários em Python

### O que é um dicionário?

Um **dicionário** é uma coleção de **pares chave–valor**.  
Você usa uma **chave única** para acessar um **valor** associado.

```python
pessoa = {
    "nome": "Ana",
    "idade": 25,
    "profissao": "Engenheira"
}
```

### Acessando valores

```python
print(pessoa["nome"])      # Ana
print(pessoa.get("idade")) # 25
```

### Adicionando ou modificando valores

```python
pessoa["idade"] = 26             # Atualiza
pessoa["cidade"] = "São Paulo"  # Adiciona nova chave
```

### Removendo itens

```python
del pessoa["profissao"]
pessoa.pop("cidade")
```

### Iterando sobre o dicionário

```python
for chave, valor in pessoa.items():
    print(f"{chave}: {valor}")
```

### Métodos úteis

```python
pessoa.keys()    # Retorna as chaves
pessoa.values()  # Retorna os valores
pessoa.items()   # Retorna pares chave–valor
```
