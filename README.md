# Análise Exploratória Geoespacial: Circuitos Históricos da Fórmula 1 (1950-2023)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-44a833?style=for-the-badge&logo=seaborn&logoColor=white)

## 📌 Visão Geral do Projeto

Este projeto consiste em uma Análise Exploratória de Dados (EDA) focado na distribuição geográfica e na evolução histórica dos circuitos que já sediaram GPs de Fórmula 1 ao redor do mundo, desde o início da categoria em 1950 até o ano de 2023.

O objetivo principal foi transformar dados brutos de tabelas (`.csv`) em insights visuais de alto impacto, utilizando Python para entender a transição do esporte de um nicho europeu para um espetáculo global.

## 🎯 Objetivos Específicos

1.  **ETL (Extração, Transformação e Limpeza):** Consolidar e tratar bases de dados históricas da F1.
2.  **Análise Quantitativa:** Identificar os países com maior concentração histórica de circuitos.
3.  **Visualização Geoespacial:** Mapear a distribuição dos circuitos utilizando coordenadas de latitude e longitude.
4.  **Análise Temporal:** Observar a evolução e o deslocamento geográfico dos circuitos ao longo das décadas.

## 💻 Tecnologias e Bibliotecas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Visualização de Dados:** Seaborn, Matplotlib

## 🛠️ Etapas do Desenvolvimento

O desenvolvimento seguiu o pipeline clássico de Ciência de Dados:

1.  **Carregamento e Inspeção:** Importação dos dados (`pd.read_csv`) e análise inicial dos tipos (`info`, `dtypes`).
2.  **Tratamento de Dados:** Remoção de valores nulos, ajuste de formatos de datas (conversão para `datetime`) e padronização de nomes de colunas.
3.  **Análise Descritiva:** Uso de `value_counts` para ranquear os países com mais circuitos sediados.
4.  **Plotagem Geoespacial:** Criação de gráficos de dispersão (`scatterplot`) utilizando latitude e longitude como eixos X e Y para visualizar a distribuição dos circuitos no "mapa-múndi".

## 📊 Principais Insights de Negócio

* **Forte Concentração Européia:** A análise quantitativa revelou que, historicamente, a Europa detém a grande maioria dos circuitos, evidenciando as raízes do esporte.
* **Expansão Global Recente:** A visualização geoespacial permite identificar claramente o surgimento e a consolidação de circuitos nas Américas, Ásia e Oriente Médio nas últimas décadas, refletindo a estratégia de expansão comercial da categoria.

---
Desenvolvido por **Daniel Borges Prates** | [LinkedIn](https://www.linkedin.com/in/seu-perfil)
