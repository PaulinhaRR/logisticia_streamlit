# 🚚 RapidLog — Projeto de Análise Logística (Portfólio)

**Autor:** Paula Oliveira  
**Projeto:** Análise de desempenho logístico e dashboard interativo (Streamlit)  
**Dataset:** `logistica_5000.csv` (5.000 registros sintéticos gerados para this case study)


## 🧾 Resumo do projeto

A RapidLog é uma empresa fictícia de entregas para e-commerce que me ontratou para analisar o desempenho das suas operações de transporte durante um período recente. O objetivo é identificar gargalos, entender padrões por cidade e sugerir melhorias para reduzir o tempo de entrega e os custos.

Este repositório apresenta:
- Análise exploratória dos dados (EDA)  
- Pré-processamento e criação de métricas (tempo de entrega, atrasos, frete médio)  
- Visualizações interativas com Plotly  
- Dashboard interativo em Streamlit com sidebar e filtros  
- Dataset sintético usado (`logistica_5000.csv`)

## 📁 Estrutura do repositório
```bash

seu_projeto/
│
├── app/
│   └── app.py
│
├── data/
│   └── logistica_5000.csv
│
├── notebook/
│   └── eda_logistica.ipynb
│
├── .streamlit/
│   └── app.yaml   ← (arquivo de configuração)
│
├── requirements.txt
└── README.md

---

## 🧰 Tecnologias usadas

- Python (pandas, numpy)
- Plotly (visualizações)
- Streamlit (dashboard)
- (opcional) DuckDB / parquet para leitura eficiente

---
## 🔢 Descrição do dataset

`logistica_5000.csv` contém as seguintes colunas:

- `pedido_id` (int): identificador do pedido  
- `data_compra` (datetime): data e hora da compra  
- `cidade` (str): cidade de destino  
- `frete` (float): custo do frete em R$  
- `data_envio` (datetime): data em que o pedido foi enviado  
- `data_entrega` (datetime): data em que o pedido foi entregue  
- `tempo_entrega_dias` (int): dias entre compra e entrega

O dataset é sintético (gerado para fins de aprendizado), mas contém características realistas para análises logísticas.

---

## ⚙️ Como rodar (local)

1. Criar ambiente virtual e instalar dependências:
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# mac / linux
source venv/bin/activate

pip install -r requirements.txt


2. Rodar o Jupyter Notebook (EDA):

jupyter notebook notebook/eda_logistica.ipynb


3. streamlit run app/app.py

