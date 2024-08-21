![Logo da Ada Tech Crusos](./assets/LogoAdaCabecalho.png)

<hr>

<p></p>
<p align="center">
   <img src="https://img.shields.io/static/v1?label=STATUS&message=%20CONLUÍDO&color=RED&style=for-the-badge" #vitrinedev/>
</p>

### PROJETO SISTEMA PESSOAL FINANCEIRO - SANTANDER CODERS | ADA TECH

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)

- [Regras](#regras)

- [Funcionalidades](#funcionalidades)

- [Desafios](#desafios)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Acesso ao projeto](#acesso-ao-projeto)

- [Colaboradores](#colaboradores)

## Descrição do projeto 

<p align="justify">

Santander Coders 2024 - Turma 1174

Projeto - Módulo Lógica de Programação II

SISTEMA DE CONTROLE FINANCEIRO

Para finalizar o módulo de Lógica de Programação II, precisamos desenvolver um pequeno "sistema financeiro" para gerenciar algumas operações! Este sistema recebe e armazena movimentações financeiras em um arquivo ".json" (escolha do grupo, mas poderia ser em ".csv")!
</p>

## Regras

`Regra 1:` Criar novos registros e identificar a data em que o registro foi feito, qual foi o tipo de movimentação, e seu valor.

`Regra 2:` Os tipos de registros são três: despesas, receita ou investimento.

`Regra 3:` No caso de receita, o valor deve ser tratado como numérico e
armazenado normalmente.

`Regra 4:` No caso de despesas, o valor deve ser recebido como positivo, mas
armazenado como negativo.

`Regra 5:` No caso de investimento, deveremos ter algumas informações
adicionais: o valor que foi investido e a taxa de juros do investimento.
Lembre-se de que o montante (M) para uma dada taxa de juros *i* após *t* dias pode ser calculado pela seguinte relação: `M = V * (1 + i)^t`. Para realizar o cálculo, armazene a data
em que o investimento foi efetuado e exiba o montante, com o rendimento, na data de consulta da pessoa usuária.

## Funcionalidades

`Funcionalidade 1:` Ler registros: Deverá ser possível consultar os registros por data, tipo ou
valor. Ou seja, se a pessoa usuária quiser consultar todos os registros do dia "20/03/2024", o sistema deve ser capaz de imprimir tudo que foi registrado naquela data. (Ou seja, neste caso, é necessário que o arquivo seja aberto e lido, filtrando resultados, quando necessário).

`Funcionalidade 2:` Atualizar registros: No caso de atualização, pode-se atualizar o valor e o tipo. Automaticamente, a nova data deverá ser a de atualização do registro.

`Funcionalidade 3:` Deletar registros: Deverá ser possível deletar o registro (caso necessário, considere o índice do elemento como ID).

`Funcionalidade 4:` Criar uma função que atualize os valores de rendimento sempre que chamada.

`Funcionalidade 5:` Criar uma função 'exportar_relatorio', que exporte um relatorio final em csv ou json.

`Funcionalidade 6:` Criar pelo menos uma função de agrupamento, que seja capaz de mostrar o
total de valor baseado em alguma informação (mês, tipo...). Esta função é de livre escolha do grupo. Pode ser, por exemplo, a média de receitas/despesas em um determinado mês, o rendimento médio dos investimentos em um dado período etc.

`Funcionalidade 7:` Crie valores separados para identificar a data (dia, mês, ano).

## Desafios

`Desafio 1:` Não utilizar a biblioteca "Pandas" para resolução desse exercício.

`Desafio 2:` Aplicar somente as referências aprendidas em aulas para manipulção de strings, estruturas de dados básicas e manipulação de arquivos básicos.

`Desafio 3:` Possibilidade de importar a biblioteca "datetime" e "json".

`Desafio 4:` Os códigos para criação do sistema poderão ser entregues via github, ou
diretamente colocados nesta pasta do Google Drive. Indicar claramente, no
nome do arquivo, o grupo correspondente.

## Ferramentas utilizadas

[![My Skills](https://skillicons.dev/icons?i=python)](https://skillicons.dev)

###

## Acesso ao projeto

Você pode [acessar o código fonte do projeto](https://github.com/jjofilho/projeto_sistema_pessoal_financeiro).

## Colaboradores

| [<img src="https://avatars.githubusercontent.com/u/84856576?v=4" width=115> <br><sub>Instrutor ADA Carlos Stefano</sub>](https://github.com/carlos-stefano) | [<img src="https://avatars.githubusercontent.com/u/106630081?v=4" width=115> <br><sub>Gabriel Maio</sub>](https://github.com/Gabriel-maio) | [<img src="https://avatars.githubusercontent.com/u/170963236?s=96&v=4" width=115><br><sub>João Oliveira</sub>](https://github.com/jjofilho) | [<img src="https://avatars.githubusercontent.com/u/130763076?v=4" width=115><br><sub>Luiza Souza Simões</sub>](https://github.com/luizassimoes) |  [<img src="https://avatars.githubusercontent.com/u/51492135?v=4" width=115><br><sub>Rafael Bittencourt</sub>](https://github.com/Rabittencourt) |
| :---: | :---: | :---: | :---: | :---: |
