# Variáveis e Tipos de Dados

### O que são variáveis?

Variáveis são como “caixinhas” onde você pode guardar valores para usar depois.  
Elas têm um **nome** e armazenam algum **dado**.

```python
nome = "Ana"
idade = 25
altura = 1.65
```

No exemplo acima, criamos três variáveis com tipos diferentes:

- `nome` → texto (string)
- `idade` → número inteiro (int)
- `altura` → número decimal (float)

### Regras para nomes de variáveis

- Devem começar com uma letra ou underline `_`
- Podem conter letras, números e `_`
- Não podem conter espaços nem caracteres especiais
- São **sensíveis a maiúsculas e minúsculas** (ex: `Nome` ≠ `nome`)

```python
_valido = 123
nome_completo = "João Silva"
```

### Tipos de dados básicos

| Tipo      | Exemplo           | Descrição                    |
|-----------|-------------------|------------------------------|
| `int`     | `10`, `-5`, `0`   | Números inteiros             |
| `float`   | `3.14`, `-0.5`    | Números decimais             |
| `str`     | `"texto"`         | Cadeia de caracteres (texto) |
| `bool`    | `True`, `False`   | Booleanos (verdadeiro/falso) |

### Verificando o tipo de uma variável

```python
print(type(nome))     # <class 'str'>
print(type(idade))    # <class 'int'>
print(type(altura))   # <class 'float'>
```
