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
