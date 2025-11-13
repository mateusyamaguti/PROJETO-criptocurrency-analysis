crypto-project/
│
├── data/
│   ├── raw/               ← dados originais brutos (ex: arquivos .csv, .json)
│   ├── processed/         ← dados limpos/preparados
│   └── external/          ← dados de fontes externas (APIs, exchanges, etc)
│
├── notebooks/
│   ├── 01_data_ingestion.ipynb      ← ingestão de dados (API, downloads)
│   ├── 02_data_cleaning.ipynb       ← limpeza, tratamento, EDA inicial
│   ├── 03_feature_engineering.ipynb  ← criação de variáveis, janelas de tempo, agregações
│   ├── 04_modeling.ipynb            ← modelos de previsão / análise
│   └── 05_visualization.ipynb       ← gráficos, dashboards, insights
│
├── src/
│   ├── __init__.py
│   ├── data_loader.py               ← funções para baixar/chamar APIs
│   ├── data_cleaner.py              ← funções de limpeza/tratamento
│   ├── features.py                  ← funções para engenharia de features
│   └── model.py                     ← funções de treinamento/avaliação de modelos
│
├── requirements.txt                 ← pacotes Python necessários
├── README.md                        ← descrição do projeto, objetivos, estrutura
└── environment.yml / environment.json (opcional) ← configuração de ambiente


# prompt inicial
Agora, outra questão. Gostaria de fazer um projeto de Data Science voltado para análise de criptomoedas. Para isso, gostaria que você me auxiliasse primeiramente a criar um estrutura de projeto utilizando inicialmente o jupyter notebook com ide, e também me dar orientações dos primeiros passos. Por fim, apresente uma tabela de artigos ou trabalhos a respeito e por último site ou API's que eu consiga retirar as informações sobre criptomoedas

### Objetivo
Painel de análise de criptomoedas
 - Painel de consulta de criptomoedas
 - Mostrar valor do dia
 - Mostrar grafico de variação temporal
 -- Permitir que o grafico se ajuste a dia, semana, mês, ano e desde o início
 -- Escolher a criptomoeda que será analisada
 
