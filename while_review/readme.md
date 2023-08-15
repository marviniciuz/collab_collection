# WHILE 

```python
while condição:
    bloco de codigo
    variavel de controle
 ```  

Beleza, no while, primeiro temos a a condição, depois vem a ação caso esta condição seja verdadeira, mas pra que o codigo não vire um loop infinito, e necessario adicionar um controle.

## exemplo:
```python
i = 1
while i <= 5:
    print(i)
    i += 1
```
Temos a variavel ***i = 1***, que inicialmente contem o valor de 1, logo em seguida abrimos o bloco de codigo ***while***:

### 1 parte:
equanto i for menor ou igual a 5:
```python
while i <= 5:
``` 

### 2 parte:
equanto i for menor ou igual a 5, imprime o valor de i.
```python
print(i)
```
***imprime o valor de i?***

Sim, sabemos que o valor de ***i = 1***, mas ai e que entra variavel de controle, a que faz com que o codigo não vire um loop infinito.

### 3 parte:
A cada iteração do codigo sera adicinado +1, sendo assim, inicia com 1 e finaliza com 5, por que a condição e ***equanto i for menor ou igual a 5***, este codigo imprime o valor 5, mas não segue em diante, dada a sua condição.

```python
i += 1 
```

## EXPLICNADO O CODIGO :

```python
i = 1

L = int(input("digite um numero inteito"))

while i < 10:
  if L == 0:
     L = int(input("digite um numero inteito"))
  else:
    L = L + 2
    i = i + 1
    print(L)
```

O valor de ***i = 1***, ate ai tudo ok, essa variavel controla o fluxo do ***while*** sendo assim atribuimos um valor inicial que poderia ser qualquer um.

Depois temos a condição dentro do ***while*** que e enquanto i for menor que 10, exectute o codigo abaixo, que codigo? ***Beleza***

## Vamos por partes

Depois criamos a variavel L, sendo um input que vai receber um valor do usuario que sera inserido.

### Primeira parte:
```python
if L == 0:
     L = int(input("digite um numero inteito"))
```
Aqui limitamos o usuario, que limite?

O limite e de não digitar atribuir o valor 0 na variavel L, mas e se for digitado qualquer numero diferente de 0?

### Segunda parte:

```python
else:
    L = L + 2
    i = i + 1
```

Aqui somamos o valor de L + 2, depois precisamos atribuir um valor para i, que o q faz o programa iniciar e parar, para iniciar ate que vai tendo em vista que o valor de ***i = 1***, mas para dar continuidade nas somas de ***L + 2*** precisamos mudar o valor de i, sendo assim utilizamos o mesmo metodo utilizado em ***L + 2***, so que ***i = i + 1***.

## Finalizando com um print:

```python
print(L)
```