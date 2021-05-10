# Projeto para entender como as branches funcionam

## Branch master ou main

É a branch principal do repositório, é a partir dela que nosso sitema será entregue os clientes.

O 'git' usa o nome da branch como master o 'github' como main.

para converter use ''git branch -M main'' depois que fizer o primeiro commit a partir do repositório cirado com o ''git init''
```
# manipulação de branch
para listar use
````
$ git branch --list
`````

para excluir um a branch

```
$ git branch -d nome_da_branch
´´´
 
Para alterar o nome de uma branch 
```
$ git branch -m nome_da_branch
```