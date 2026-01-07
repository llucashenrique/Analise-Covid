#  Análise de Dados: Letalidade por Região

Este repositório contém um projeto de análise de dados epidemiológicos focado na correlação entre o volume de casos e a mortalidade registrada. O objetivo é visualizar a "eficiência" de saúde e testagem através da métrica de **casos por morte**.

## Descrição do Projeto

O projeto processa um conjunto de dados estruturado para calcular e exibir a relação entre diagnósticos positivos e óbitos. A principal métrica analisada é o indicador que mostra quantos casos são registrados para cada 1 morte em cada país ou região.

## Estrutura dos Dados

O projeto utiliza um DataFrame com as seguintes colunas principais:
*   **Country/Region**: Nome da localidade.
*   **ano / mes**: Período temporal dos dados.
*   **total_casos**: Acumulado de casos confirmados.
*   **total_mortes**: Acumulado de óbitos.
*   **casos_por_morte**: Proporção calculada (Casos ÷ Mortes).

## Tecnologias Utilizadas

*   **Python 3.x**
*   **Pandas**: Para manipulação e tratamento dos dados.
*   **Plotly Express**: Para criação de gráficos interativos e dinâmicos.

## Visualização de Dados

A visualização principal consiste em um gráfico de dispersão (Scatter Plot) interativo onde:
1.  **Eixo X**: Total de Casos.
2.  **Eixo Y**: Total de Mortes.
3.  **Cores**: Representam a métrica `casos_por_morte`, permitindo identificar rapidamente regiões com maior taxa de letalidade ou melhor cobertura de testagem.

## Como rodar o projeto

1.  Certifique-se de ter o Python instalado.
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas plotly
    ```
3.  Execute o script Python para gerar a visualização no navegador.

---
*Dados processados para fins de análise em 2026.*


<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

test

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         test and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── test   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes test a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------