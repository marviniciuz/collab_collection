# CODIGO ACIMA FUNCIONA DA SEGUINTE FORMA:


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