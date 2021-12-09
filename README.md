# Mini Projeto Final 
Este projeto foi realizado de forma individual onde era necessário trabalhar com um dataset pré-definido pelos professores que tratava sobre uma campanha de marketing. O intuito era que fosse utilizada as ferramentas aprendidas em sala de aula de forma prática aplicando os conceitos de ETL.

## Requesitos

### Nivel Infra
O Dataset deve ser salvo em ambiente cloud(Drive ou Cloud Storage)
Os DataFrames devem ser obrigatoriamente salvos em uma bucket do CloudStorage

### Nivel Pandas
O arquivo está em outra linguagem e deve ter seus dados traduzidos para Português-BR
Realizar a extração corretamente para um dataframe
Verificar a existência de dados inconsistentes e realizar a limpeza para NaN ou NA
Realizar o drop(se necessário) de colunas do dataframe
Todos os passos devem ser comentados

### Nivel PySpark
Deverá ser montada a estrutura do DataFrame utilizando o StructType
Realizar a mudança de nome de pelo menos 2 colunas
Deverá criar pelo menos duas novas colunas contendo alguma informação relevante sobre as outras colunas já existentes(Use a sua capacidade analítica)
Deverá utilizar filtros, ordenação e agrupamento, trazendo dados relevantes para o negócio em questão. (Use a sua capacidade analítica)
Utilizar pelo menos duas Window Functions

### Nivel SparkSQL
Utilizar no minimo 10 consultas diferentes utilizando o SparkSQL, comentando o porquê de ter escolhido essas funções e explicando o que cada consulta faz.
