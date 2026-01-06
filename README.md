# Estudo com PySpark - NYC Taxi Data
Este projeto tem como objetivo estudar e praticar o uso do **PySpark** para manipulação e transformação de dados em larga escala, utilizando como base o conjunto público de corridas de táxi da cidade de Nova York (**NYC Yellow Taxi Trips**), que contém informações sobre milhões de corridas de táxi.

## Objetivo do Estudo
Explorar conceitos fundamentais do PySpark, como:
- Leitura e limpeza de dados em larga escala;
- Criação de novas colunas e transformações;
- Cálculo de métricas derivadas (ex: velocidade média e taxa de gorjeta);
- Discretização de colunas numéricas (*binning*);
- Filtragem e tratamento de valores inconsistentes.

## Estrutura do Projeto
```
.
├── data/                  # Dados brutos ou processados localmente
├── notebooks/             # Notebooks com análises e transformações em PySpark
├── .venv/                 # Ambiente virtual (criado pelo uv ou Python venv)
├── pyproject.toml         # Configuração do ambiente e dependências
├── uv.lock                # Arquivo de bloqueio do gerenciador de pacotes uv
├── .python-version        # Versão do Python utilizada
├── .gitignore             # Arquivos e pastas ignorados pelo Git
└── README.md              # Este arquivo
```

## Como Excutar
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/azzolinovarella/pyspark-study.git # ou git@github.com:azzolinovarella/pyspark-study.git
   cd pyspark-study
   ```

2. **Crie o ambiente e instale as dependências:**
   ```bash
   uv sync
   ```

3. **Abra o Jupyter Notebook:**
   ```bash
   uv run jupyter notebook
   ```

## Objetivo
O foco deste projeto é **aprendizado e prática com PySpark**, incluindo:
- Leitura e limpeza de dados;
- Criação de colunas derivadas e enriquecimento de datasets;
- Aplicação de funções de janela (window functions);
- Uso de partições e otimização de execução;
- Escrita de resultados em formatos otimizados (como Parquet).

## Observações
- Este projeto **não possui fins comerciais**.
- Os dados utilizados são públicos e disponibilizados pelo **NYC Taxi & Limousine Commission (TLC)** e **Kaggle**.
