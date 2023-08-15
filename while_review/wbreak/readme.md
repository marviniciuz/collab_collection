# BREAK

O break interno é conhecido como uma ferramenta de controle de fluxo . Existe outro chamado continue que é usado basicamente para pular uma iteração ou continuar com a próxima iteração.

breaksó pode ocorrer sintaticamente aninhado em um loop ***for*** or ***while***, mas não aninhado em uma função ou definição de classe dentro desse loop.
 
O intuito do ***break*** e de quebrar uma certa iteração estabelecendo um limite antes sendo assim e necessario utilizar 

```python

while condição :
    codigo 
    if condição:
        break
```
## Exemplo de codigo: 

```python
i = 0

while i < 10:
    print(i)
    if i == 7:
        break
```

### Resultado : 

0
1
2
3
4
5
6
