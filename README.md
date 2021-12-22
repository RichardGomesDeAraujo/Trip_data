# Trip_data
## Projeto: 
Google Data Analytics - Case Study

## Cenário: 
Analisar o banco de dados de uma empresa de compartilhamento de bicicletas situada na cidade de Nova York.

A empresa possui dois tipos de usuarios: 

- Usuários Casuais
- Usuários Membros

## Objetivo do Projeto:
Verificar as diferenças de uso entre os Usuários Casuais e os Usuários Membros.

## Fonte de Dados:
- Dados publicos: Motivate International Inc. (Divvy Bicycle Sharing Service from Chicago) - [**Ver Licença**](https://www.divvybikes.com/data-license-agreement)
- Período Analisado: Novembro/2020 à Outubro/2021 
- Tabelas Importadas para o Banco de Dados SQL Server com extensão .xls

## Processando, Limpando e Transformando os Dados:
- Utilizado o SQL Server Management Studio para unir todas as tabelas e criar um único Dataset através dessa query
- Número total de linhas
- Query para retirar valores nulos, 
- Query para retirar duração de uso zerada e com duração de uso negativa
- Query para retirar valores duplicados

## Visualização de Dados:
O Banco de Dados Final, obtido através do SSMS(SQL Server Management Studio), ficou com um total de   linhas, e foi importado para o Microsoft PowerBi, com a intenção de desenvolver os gráficos e realizar as análises.

### Número Total de Usuários:

#### Observações

### Quantidade de Eventos por Tipo de Bicicleta:

### Observações

### Tempo de Utilização (Duração) Por Dia da Semana e Por Tipo de Usuário

#### Observações

### Quantidade de Eventos Por dia da Semana e Por Tipo de Usuário

#### Observações
