# Projeto de Análise de Dados - Preço da Gasolina no Brasil

Este é um projeto desenvolvido como parte do curso **Análise de Dados com Pandas e SQL** da Asimov Academy. Neste projeto, exploramos conjuntos de dados relacionados aos preços da gasolina no Brasil, com o objetivo de realizar análises descritivas e responder a diversas perguntas utilizando as bibliotecas pandas em Python.

## Sobre o Projeto

O objetivo deste projeto é praticar e aplicar os conceitos aprendidos durante o curso de Análise de Dados com Pandas e SQL da Asimov Academy. Para isso, realizamos uma série de análises sobre os preços da gasolina no Brasil, utilizando dois conjuntos de dados distintos: "gasolina_2000+.csv" e "gasolina_2010+.csv".

## Etapas do Projeto

1. **Carregamento e Combinação de Dados:** Inicialmente, carregamos os conjuntos de dados em DataFrames separados e os combinamos em um único DataFrame usando a biblioteca pandas.

2. **Exploração Inicial dos Dados:** Utilizamos os métodos `head()` e `info()` para investigar as colunas e entender a estrutura dos dados.

3. **Manipulação de Datas:** Convertemos as colunas de datas para o tipo `Timestamp` utilizando o método `pd.to_datetime()`.

4. **Criação de Novas Colunas:** Criamos uma nova coluna representando o ano e o mês a partir da coluna de datas.

5. **Análise Exploratória de Dados:** Utilizamos diversas funções do pandas, como `value_counts()`, para explorar os tipos de produtos, calcular médias de preços e identificar tendências ao longo do tempo.

6. **Desafio:** Criamos uma tabela contendo uma série temporal com a diferença absoluta e percentual entre os valores mais baratos e caros da gasolina, destacando os estados onde esses preços foram registrados.

## Tecnologias Utilizadas

- Python
- Biblioteca Pandas
- Jupyter Notebook

## Como Utilizar

Para utilizar este projeto, basta clonar este repositório em sua máquina local e executar o arquivo Jupyter Notebook (.ipynb) em um ambiente compatível com Python.
