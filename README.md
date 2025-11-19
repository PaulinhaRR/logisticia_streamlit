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

projeto_logistica/
├─ data/
│ ├─ logistica_5000.csv
│ └─ logistica_5000.parquet # (opcional: versão otimizada)
├─ notebook/
│ └─ eda_logistica.ipynb
├─ app/
│ └─ app.py # Streamlit dashboard
├─ scripts/
│ └─ preprocess.py # script para gerar parquet e colunas
├─ requirements.txt
└─ README.md

## 🧰 Tecnologias usadas

- Python (pandas, numpy)
- Plotly (visualizações)
- Streamlit (dashboard)
- (opcional) DuckDB / parquet para leitura eficiente

---


