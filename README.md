# Dados sobre Violência Contra a Mulher nos estados do Pará e Paraná
Tratamento e análise de dados sobre violência doméstica nos estados do Pará e Paraná.

## Descrição dos Arquivos

### Validação das Versões Originais

Os arquivos deste grupo foram utilizados para validar os resultados obtidos no trabalho original "Análise de dados criminais sobre violência contra a mulher nos estados Pará e Paraná", de Mariana Kniss (https://acervodigital.ufpr.br/xmlui/handle/1884/85647).

- **tratamento-dados-pa.ipynb:** Notebook de tratamento dos dados do estado do Pará, desenvolvido com a utilização do PySpark.
- **tratamento-dados-pr.ipynb:** Notebook de tratamento dos dados do estado do Paraná, desenvolvido com a utilização do PySpark.
- **leitura-dos-arquivos-formatados.ipynb:** Notebook para leitura dos arquivos resultantes da etapa de tratamento.

### Aptação das Versões Originais

Nestes arquivos, os códigos foram adaptados para a utilização do pacote Pandas.

- **tratamento-dados-pa-pandas.ipynb:** Notebook de tratamento dos dados do estado do Pará, desenvolvido com a utilização do Pandas.
- **tratamento-dados-pr-pandas.ipynb:** Notebook de tratamento dos dados do estado do Paraná, desenvolvido com a utilização do Pandas.
- **leitura-dos-arquivos-formatados-pandas.ipynb:** Notebook para leitura dos arquivos resultantes da etapa de tratamento e **junção dos arquivos em uma base única**.

### Análise Exploratória

Arquivos responsável por possibilitar uma visão geral do conjunto de dados.

- **analise-exploratoria.ipynb:** Notebook de análise exploratória dos dados utilizando o Pandas.

### Mineração de Dados

Uma vez que o processo de mineração de dados foi realizado no software Orange, o arquivo contendo o fluxo de trabalho do processo foi disponibilizado.

- **orange/mineracao-de-dados.ows:** Arquivo resultante do processo de mineração.