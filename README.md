# 📊 Análise e Manipulação de Dados com Pandas

Este repositório apresenta um Jupyter Notebook (`Pandas.ipynb`) que serve como um estudo de caso prático para demonstração e aplicação da biblioteca **Pandas** em Python. O Pandas é a ferramenta fundamental para trabalhar com dados tabulares (estruturados), permitindo uma análise flexível e eficiente.

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é explorar as funcionalidades essenciais do Pandas para importar, inspecionar e manipular dados, transformando dados brutos em insights estruturados.

## 🛠️ Principais Técnicas e Funcionalidades Exploradas

O notebook demonstra diversas etapas críticas do fluxo de trabalho de um analista de dados:

### 1. Importação e Estruturação de Dados

* **Leitura de Dados:** Uso de `pd.read_csv()` para importar dados a partir de um arquivo CSV (`supermarket_sales1.csv`), configurando o delimitador (`sep=';'`) e garantindo a correta leitura de colunas de data (`parse_dates=['Date']`).
* **Inspeção Inicial:** Utilização de métodos como `.shape` (para verificar o número de linhas e colunas) e `.head()` (para visualizar as primeiras entradas) para entender a estrutura do DataFrame.

### 2. Manipulação e Filtragem

* **Seleção Condicional:** Demonstração de técnicas avançadas de filtragem e consulta de dados, combinando **múltiplas condições** lógicas.
    * O notebook inclui exemplos de como selecionar registros onde a coluna 'Gender' **não** é 'Female' **E** a coluna 'City' é 'Yangon', utilizando o poderoso método `.loc[]` e operadores booleanos (`!=`, `&`).

### 3. Visualização e Análise (Potencial)

* Embora os exemplos iniciais sejam focados em manipulação, este notebook serve como uma base sólida para futuras etapas de análise exploratória de dados (EDA) e visualizações.

---

## 🚀 Como Rodar o Notebook

Para replicar a análise:

1.  Clone este repositório.
2.  Certifique-se de que a biblioteca Pandas e o arquivo `supermarket_sales1.csv` estão no mesmo diretório.
3.  Execute o notebook em um ambiente que possua o **Pandas** instalado (Jupyter, Google Colab ou VS Code com o kernel Python adequado).
