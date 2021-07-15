# Ignite - NodeJS
### Dev: Marcello Caon
### Instrutora: Dani


## Aula 01
### Comandos Importantes utilizados

// dentro do diretório

yarn init -y

yarn add typescript -D // add typescript em desenvolvimento

yarn tsc --init // inicializa typescript no projeto

yarn add express

yarn add @types/express -D

yarn add ts-node-dev -D

// No package.json colocar o script

"scripts": {
"dev": "ts-node-dev src/server.ts"
}

yarn add uuid

## Aula 02



# Regras do Projeto
### Requisitos
  
    [ ] Deve ser possível criar uma conta
    [ ] Deve ser possível buscar o extrato bancário do cliente
    [ ] Deve ser possível realizar um depósito
    [ ] Deve ser possível realizar um saque
    [ ] Deve ser possível buscar o extrato bancário do cliente por data
    [ ] Deve ser possível atualizar dados da conta do cliente
    [ ] Deve ser possível obter dados da conta do cliente
    [ ] Deve ser possível deletar uma conta

### Regras de Negócio

    [ ] Não deve ser possível cadastrar uma conta com CPF já existente
    [ ] Não deve ser possível fazer depósito em uma conta não existente
    [ ] Não deve ser possível buscar extrato em uma conta não existente
    [ ] Não deve ser possível fazer saque em uma conta não existente
    [ ] Não deve ser possível excluir uma conta não existente
    [ ] Não deve ser possível faer saque quando o saldo for insuficiente


