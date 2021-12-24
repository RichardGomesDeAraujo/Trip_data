# Trip_data
## Projeto: 
Google Data Analytics - Case Study

## Cenário: 
Analisar o banco de dados de uma empresa de compartilhamento de bicicletas situada em Chicago/IL, que contava com uma frota de 5.824 bicicletas, em 692 estações distribuidas pela cidade na época a ser analisada.

A Empresa tem três planos de preços: Single-Ride, Full-Day, e Annual Membership, onde os usuários Single-ride e Full-day são chamados de Usuários Casuais (Casual) e os Annual Membership como Usuários Membros (Member).

A Empresa também disponibiliza três tipos de bicicletas: Reclining Bike, Hand Tricycles, e Cargo Bikes para transformar o compartilhamento mais inclusivo à pessoas com necessidades especiais ou pessoas que não podem utilizar uma bicicleta comum com duas rodas.

## Objetivo do Projeto:
Verificar as diferenças de uso entre os Usuários Casuais e os Usuários Membros.

## Preparação da Fonte de Dados:
- Dados publicos: Motivate International Inc. (Divvy Bicycle Sharing Service from Chicago) - [**Ver Licença**](https://www.divvybikes.com/data-license-agreement)
- Período Analisado: Novembro/2020 à Outubro/2021
- Arquivos fonte em formato .csv
- Abrindo e visualizando os arquivos para observar como se apresentam, como estão organizados, se apresentam erros ou outros problemas.
- Arquivos salvos em formato .xls (Arquivos .xls são consideravelmente menores do que arquivos .csv, o que facilita a importação para sistemas de Bancos de Dados com licenças gratuitas de utilização)
- Arquivos Importados para o Banco de Dados SQL Server Management Studio.

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

#### Observações

### Tempo de Utilização (Duração) Por Dia da Semana e Por Tipo de Usuário

#### Observações

### Quantidade de Eventos Por dia da Semana e Por Tipo de Usuário

#### Observações
