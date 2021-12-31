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
- Período Analisado: Dezembro/2020 à Novembro/2021
- Arquivos fonte em formato .csv
- Os arquivos foram abertos para observar como se apresentam, como estão organizados e se apresentam erros ou outros problemas.
- Os Arquivos foram importados para o Banco de Dados SQL Server Management Studio.

## Processando, Limpando e Transformando os Dados:
- Foi criada uma coluna calculada de diferença de tempo de saída e de chegada em cada arquivo .csv para verificar valores inconsistentes com essa [**query**](Query_Add_Column)
- Os arquivos .csv importadas para o SQL Server foram unidas em uma única tabela através dessa [**query**](Query_Union_ALL)
- O número total de registros(linhas) a serem preparadas para análise é de 5.479.096
- Para retirar valores nulos, tempo de duração negativo ou zerado e id's duplicados foi utilizada essa [**Query**](Query_Cleaning_Data) 
- Total de registros a serem analizadas após o tratamento dos dados ficou em 4.491.263 (81,97% dos registros totais)

## Visualização de Dados:
O Banco de Dados Final, obtido através do SSMS (SQL Server Management Studio), foi importado para o Microsoft PowerBi, com a intenção de desenvolver os gráficos e realizar as análises.

### Total de Registros por Tipo de Usuário:
![**imagem**](Qtd_Registros.png)

#### Observações

### Quantidade de Eventos por Tipo de Bicicleta:
![**imagem**](Qtd_Registros_Tipo_Bike.png)
#### Observações

### Tempo de Utilização (Duração) Por Dia da Semana e Por Tipo de Usuário
![**imagem**](Media_Tempo_Dia_Semana.png)
![**imagem**](Media_Tempo_Dia_Semana_Tipo_Bike.png)
#### Observações

### Quantidade de Eventos Por dia da Semana e Por Tipo de Usuário
![**imagem**](Qtd_Registros_Dia_Semana.png)
#### Observações
