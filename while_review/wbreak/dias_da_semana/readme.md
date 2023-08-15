# Explicando o codigo


```python
dias_semana = ['segunda-feira', 'terça-feira', 'quarta-feira']

i = 0
while dias_semana:
    i = i+1
    if i == 1:
        print("O dia da semana que corresponde a posição", i, "da lista dias_semana é:", dias_semana[i]) 
    break
```

### 1 parte:

Primeiro temos umas lista:

```python
dias_semana = ['segunda-feira', 'terça-feira', 'quarta-feira']
```

### 2 parte:

Depois criamos a variavel i, para acessar a lista e os elementos da lista, sendo assim iniciamos a variavel com 0:

```python
i = 0
```

### 2 parte:

Este while diferente dos outros não contem uma condição ainda, isso por que queremos percorrer todos elementos da lista, sendo todos os três elementos que são inciados em 0,1 e 2, contendo os tres elementos: segunda-feira,terça-feira,quarta-feira. 

***E como se disséssemos ao while: enquanto houver elementos na lista, faça alguma coisa.***

```python
while dias_semana:
```

### 3 parte:

Variavel de controle do while

```python
i = i+1
```

### 4 parte:

Dentro do while abrimos um bloco codigo if, para encontrarmos o indice ou posição, se o o = for igual a 1, vamos acessar o indice do elemento correspondendo ao 1.

```python
if i == 1:
```

### 5 parte:

Sera impresso o dia da semana apos ***i == 1***

```python
print("O dia da semana que corresponde a posição", i, "da lista dias_semana é:", dias_semana[i])
```

### 6 parte:

Apos a operação for seucedida o codigo para.

```python
break
```

### Resultado : 

```
O dia da semana que corresponde a posição 1 da lista dias_semana é: terça-feira
```