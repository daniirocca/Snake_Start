# Manipulando Strings

### O que é uma string?

Uma **string** é uma sequência de caracteres usada para representar texto.  
Em Python, strings são definidas entre **aspas simples** `'texto'` ou **aspas duplas** `"texto"`:

```python
mensagem = "Olá, mundo!"
nome = 'Ana'
```

### Operações comuns com strings

#### 🔹 Concatenar (juntar strings)

```python
nome = "Ana"
mensagem = "Olá, " + nome
print(mensagem)  # Olá, Ana
```

#### 🔹 f-strings (interpolação moderna)

```python
idade = 25
print(f"Eu tenho {idade} anos.")  # Eu tenho 25 anos.
```

#### 🔹 Tamanho da string

```python
texto = "Python"
print(len(texto))  # 6
```

#### 🔹 Acessar caracteres

```python
fruta = "banana"
print(fruta[0])   # b
print(fruta[-1])  # a (último caractere)
```

#### 🔹 Fatiamento (slicing)

```python
frase = "Descomplicando Python"
print(frase[0:13])   # Descomplicando
print(frase[:5])     # Desco
print(frase[5:])     # mplicando Python
```
