# **Projeto de Manipulação e Análise de Dados do Censo de 2010 com CNEFE - BAHIA do IBGE**

Este projeto tem como objetivo explorar e analisar os dados da CNEFE - BAHIA do IBGE referentes ao Censo de 2010. Através deste projeto, você encontrará informações sobre a manipulação de grandes bases de dados, técnicas de similaridade de strings usando o algoritmo de Jaro-Winkler, e a utilização de ferramentas como PySpark, Pandas, Jellyfish e Jupyter Notebook.

## Índice

1. [Informações Gerais](#informações-gerais)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Manipulação de Dados](#manipulação-de-dados)
4. [Similaridade de Strings](#similaridade-de-strings)
5. [Como Executar o Projeto](#como-executar-o-projeto)
6. [Referências](#referências)

## **Informações Gerais**

O projeto consiste na manipulação e análise de dados da CNEF(Cadastro Nacional de Endereços para Fins Estatísticos) - BAHIA do IBGE referentes ao Censo de 2010. A base de dados contém informações relevantes que podem ser utilizadas para diversas análises e estudos.

### **Base de Dados**

A base de dados CNEFE - BAHIA do Censo de 2010 pode ser encontrada [aqui](https://www.ibge.gov.br/estatisticas/sociais/populacao/38734-cadastro-nacional-de-enderecos-para-fins-estatisticos.html?edicao=38735&t=downloads). Certifique-se de baixar e descompactar os dados antes de prosseguir com a execução do projeto.

## **Tecnologias Utilizadas**

- Python 3.11.4
- Java 17
- Spark 3.5.1
- PySpark
- Pandas
- Jellyfish
- Jupyter Notebook

## **Manipulação de Dados**

Para a manipulação de grandes bases de dados, foi utilizado o PySpark, que é uma ferramenta poderosa para processamento de dados em larga escala. Com o PySpark, foi possível realizar operações como filtragem, transformação e agregação de dados de maneira eficiente.

Além do PySpark, também foi utilizado o Pandas para algumas análises exploratórias e manipulações de dados que não exigiam processamento em larga escala.

Para a visualização e execução de análises interativas, o Jupyter Notebook foi utilizado. Ele permite a criação de notebooks que combinam código, texto e visualizações, facilitando a exploração e apresentação dos dados.

## **Similaridade de Strings**

Para a análise de similaridade entre strings, foi utilizado o algoritmo de Jaro-Winkler da biblioteca Jellyfish. Este algoritmo é útil para comparar a similaridade entre duas strings, o que pode ser útil em diversas aplicações, como de duplicação de registros e correção de erros de digitação.

## **Como Executar o Projeto**
**Todas as etapas do projeto estão devidamente comentadas e separadas no NoteBook.**
1. Certifique-se de ter todas as tecnologias e bibliotecas instaladas conforme descrito nas [Tecnologias Utilizadas](#tecnologias-utilizadas).
2. Baixe e descompacte a base de dados da CNEFE - BAHIA do Censo de 2010 do IBGE.
3. Clone este repositório e navegue até o diretório do projeto.
4. Execute o script principal do projeto.

   ```bash
   desafio.ipynb
   Jaro-Winkler.ipynb
5. Todos os dados gerados estarão em "Bases_Geradas"
