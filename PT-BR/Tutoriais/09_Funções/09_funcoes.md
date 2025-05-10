# Funções em Python

### O que é uma função?

Funções são **blocos de código reutilizáveis** que realizam uma tarefa.  
Elas ajudam a **organizar**, **reaproveitar** e **facilitar** a manutenção do código.

```python
def saudacao():
    print("Olá!")
```

### Chamando uma função

```python
saudacao()  # Olá!
```

---

### Funções com parâmetros

Você pode passar **informações** para a função usando parâmetros:

```python
def saudacao_nome(nome):
    print(f"Olá, {nome}!")

saudacao_nome("Ana")  # Olá, Ana!
```

---

### Funções com retorno

Funções podem **retornar valores** com `return`:

```python
def soma(a, b):
    return a + b

resultado = soma(3, 5)
print(resultado)  # 8
```

---

### Parâmetros opcionais (com valor padrão)

```python
def saudacao(nome="visitante"):
    print(f"Olá, {nome}!")

saudacao()         # Olá, visitante!
saudacao("Lucas")  # Olá, Lucas!
```
