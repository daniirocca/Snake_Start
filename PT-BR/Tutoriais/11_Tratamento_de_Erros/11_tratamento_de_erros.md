# Tratamento de Erros em Python

### Por que tratar erros?

Erros (exceções) podem causar a **interrupção** do programa.  
Com o tratamento correto, é possível **evitar falhas inesperadas** e deixar o código mais robusto.

---

### Bloco `try` / `except`

```python
try:
    numero = int(input("Digite um número: "))
    print(10 / numero)
except ValueError:
    print("Erro: Você não digitou um número válido.")
except ZeroDivisionError:
    print("Erro: Não é possível dividir por zero.")
```

---

### `else` e `finally`

```python
try:
    print("Tentando...")
    resultado = 10 / 2
except ZeroDivisionError:
    print("Erro de divisão")
else:
    print("Tudo certo!")  # Executa se não houve erro
finally:
    print("Fim do bloco")  # Sempre executa
```

---

### Tipos comuns de exceções

| Exceção             | Ocorre quando...                     |
|---------------------|--------------------------------------|
| `ValueError`        | Valor inválido em uma conversão      |
| `ZeroDivisionError` | Divisão por zero                     |
| `TypeError`         | Operação com tipo errado             |
| `IndexError`        | Índice fora da faixa de uma lista    |
| `KeyError`          | Chave não existente em um dicionário |
