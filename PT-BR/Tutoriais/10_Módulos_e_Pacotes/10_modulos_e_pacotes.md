# Módulos e Pacotes em Python

### O que é um módulo?

Um **módulo** é qualquer arquivo `.py` que pode conter funções, variáveis ou classes.  
Você pode **importar** esse arquivo em outros códigos Python para reutilizar o que escreveu.

### Criando e usando um módulo

Crie um arquivo chamado `meu_modulo.py`:

```python
# meu_modulo.py
def saudacao(nome):
    return f"Olá, {nome}!"
```

Agora use esse módulo em outro arquivo:

```python
# main.py
import meu_modulo

print(meu_modulo.saudacao("Ana"))  # Olá, Ana!
```

### Importações específicas

```python
from meu_modulo import saudacao

print(saudacao("Carlos"))  # Olá, Carlos!
```

---

### O que é um pacote?

Um **pacote** é uma **pasta que contém vários módulos** e um arquivo especial chamado `__init__.py` (pode estar vazio).  
Serve para **organizar melhor** seu código em partes reutilizáveis.

```
meu_pacote/
├── __init__.py
├── saudacoes.py
├── calculos.py
```

Uso em outro script:

```python
from meu_pacote.saudacoes import saudacao
```