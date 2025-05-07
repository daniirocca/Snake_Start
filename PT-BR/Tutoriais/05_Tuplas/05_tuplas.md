# Tuplas em Python

### O que é uma tupla?

Uma **tupla** é uma estrutura de dados **imutável** que armazena múltiplos valores.  
Ela é parecida com uma lista, mas **não pode ser alterada** após sua criação.

```python
pessoa = ("Ana", 25, "Engenheira")
```

### Quando usar tuplas?

- Quando os dados **não devem ser modificados**
- Para representar **dados fixos** (ex: coordenadas, datas, RGB)
- Melhor desempenho do que listas para leitura

### Acessando elementos

```python
print(pessoa[0])  # Ana
print(pessoa[-1]) # Engenheira
```

### Tamanho da tupla

```python
print(len(pessoa))  # 3
```

### Desempacotamento de tupla

```python
nome, idade, profissao = pessoa
print(nome)       # Ana
print(profissao)  # Engenheira
```

### Tuplas com um único elemento

Use uma vírgula no final:

```python
tupla_unica = (42,)
print(type(tupla_unica))  # <class 'tuple'>
```

**Curiosidade:** Por serem imutáveis, tuplas podem ser usadas como **chaves de dicionários** (listas não!).