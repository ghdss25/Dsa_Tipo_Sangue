# Dsa_Tipo_Sangue - Tipos de Sangue

A finalidade desta planilha é analisar os índices de massa corporal (IMCs) dos usuários da empresa Data Science Academy para determinar a elegibilidade de doação de sangue de acordo com seus tipos sanguíneos.

Neste cálculo, utilizamos o peso dividido pela altura ao quadrado para obter o IMC de cada usuário. Aqueles com IMC abaixo de 25 serão considerados abaixo do peso e não estarão aptos para realizar a doação de sangue. 
Por outro lado, os usuários com IMC igual ou acima de 25 poderão participar da doação de sangue.

Essa análise visa garantir a segurança e o bem-estar tanto dos doadores quanto dos receptores, seguindo as diretrizes e normas recomendadas para procedimentos de doação de sangue.

A empresa gentilmente disponibilizou um conjunto de dados com o objetivo de realizar uma análise exploratória. Com base nessa análise, poderemos obter insights importantes,
identificar padrões, tendências e relações entre os diferentes elementos presentes nos dados. O esquema ficou assim: 

```bash

  Nome_Completo
  Título
  E-mail
  Sexo
  Profissão
  Nascimento
  Telefone
  Tipo Sanguineo
  Última Consulta
  Ano_Consulta
  Mês_Consulta
  Dia_Consulta
  Imc
  Cidade
  Endereço
  Código Postal

```

## Passos para a realização das análises da Dsa_Tipo_Sangue. 

```bash

  1 - Importação de Bibliotecas para a Planilha
  2 - Importação da Planilha de Tipo Sanguíneo do Usuário
  3 - Conversão da Ultima Consulta em formato dia, mês e ano
  4 - Cálculo do Imc dos Usuários
  5 - Retirando as colunas de Peso e Altura
  6 - Mesclando Nome e Sobrenome
  7 - Apagando Nome e o Sobrenome dos usuários
  8 - Mudar as posições das colunas na Planilha Tipo_Sangue
  9 - Definindo as tabelas e suas colunas para um banco de dados
  10 - Conexão para o Banco de dados
  11 - Definição de Star Schema para Dim_Usuario
  12 - Definição de Star Schema para Dim_Telefone
  13 - Definição de Star Schema para Dim_Situacao_Sanguinea
  14 - Definição de Star Schema para Dim_Endereco
  15 - Consultas das Tabelas: Dim_Situacao_Sanguinea, Consulta da Tabela Dim_Endereco

```

* Nome das Tabelas para o banco de dados do tipos sanguíneos

```bash

    1 - Tabela Usuário
    2 - Tabela Telefone
    3 - Tabela Situacao_Sangue
    4 - Tabela Endereço
    
```

# Análise dos dados da Dsa_Tipo_Sangue 

. Na Linguagem Python 

```bash

 1 - Total dos Imcs dos Usuarios
 2 - Total dos Imcs por Profisão
 3 - Total dos Imcs por Cidade
 4 - Total dos Imcs por Tipo Sanguineo
 5 - Total dos Imcs por Sexo
 6 - Mostre na coluna Ultima Consulta as datas referentes aos anos acima de 2018
 7 - Total dos Imcs por Dia, Ano e Mês
 8 - Faça uma consulta que mostre o Imc dos nomes dos usuarios com as respectivas cidades e o Tipo Sanguíneo
 9 - Quais são as pessoas com o tipo sanguineo que está acima e abaíxo do peso?

```

. No Power BI 

```bash

  1 - Cidade, Nome e Tipo de Sangue por Total
  2 - Total de Imc por Cidade
  3 - Total e Média de Imc por Profissão
  4 - Total e Média de Imc Títulos
  5 - Usuários Acima do Peso
  6 - Usuários Abaixo do Peso
  7 - Imc por Tipo de Sangue
  8 - Imc por Sexo
  9 - Meta da Média do Imc  dos Usuários
  10 - Meta da Média do Imc por Cidades
  11 - Meta da Média do Imc por Profissões
  12 - Meta da Média do Imc dos Sexos
  13 - Meta da Média do Imc  do Sangue
```

## Tecnologias Utilizadas  

** O projeto foi desenvolvido com as seguintes tecnologia ** 

- [anaconda](https://www.anaconda.com/) 

- [jupyter notebook](https://jupyter.org/)

- [Python](https://www.python.org/)

- [Power BI](https://powerbi.microsoft.com/pt-br/)

- [Sqlite3](https://www.sqlite.org/index.html)

# Visualização do Projeto em Python e Power BI 

 1. Power BI

 ```bash

  ## 1 - Clique no arquivo Dsa_Tipo_Sangue_Banco.pbix 
  ## 2 - Vai aparecer um link chamado View raw, aperte nele e abra o projeto no Power BI Desktop

  Obs: O Power BI só vai funcionar somente na versões Windows 7, 8, 8.1, 10 ou 11

```

 2. Python
    
```bash

  ## 1 - Clique no arquivo SSA.ipynb e no outro chamado Tipos sanguíneos.ipynb
  ## 2 - Já vai aparecer pronto o formato da Ide Python - Jupyter Notebook para a visualização do código 

```
