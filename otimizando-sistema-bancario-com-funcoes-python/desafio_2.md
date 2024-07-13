# Desafio 2: Otimizando o Sistema Bancário com Funções Python

    Guilherme Arthur de Carvalho
    Analista de sistemas
    @decarvalhogui
    
- [GitHub](https://github.com/guicarvalho) 
- [Linkedin](https://www.linkedin.com/in/decarvalhogui/) 



## Objetivo Geral

Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

<hr>

## Desafio

Precisamos deixar nosso código mais modularizado, para isso vamos criar funções para as operações existentes: sacar, depositar e visualizar histórico (extrato). Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usuário).

<hr>

## Separação em funções

Devemos criar funções para todas as operações do sistema. Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. O retorno e a forma como serão chamadas, pode ser definidas por você da forma que achar melhor.

<hr>

## Saque

A função saque deve receber os argumentos apenas por nome (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrado.

<hr>

## Depósito

A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato. 

<hr>

## Extrato

A função extrato deve receber os argumentos apenas por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

<hr>

## Novas funções

Precisamos criar duas novas funções: criar usuário e criar conta corrente. Fique a vontade para adicionar mais funções, exemplo: listar contas.

<hr>

## Criar usuário (cliente)

O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, cpf e endereço. O endereço é uma string com o formato: logradouro, nro - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não podemos cadastrar 2 usuários com o mesmo CPF.

<hr>

## Criar conta corrente

O progama deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

<hr>

## Dica

Para vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF informado para cada usuário da lista.

<hr>
