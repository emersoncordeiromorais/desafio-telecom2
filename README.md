# 📊 Análise de Evasão de Clientes - TelecomX

Este projeto tem como objetivo identificar os principais fatores associados à **evasão de clientes (churn)** em uma operadora de telecomunicações brasileira, utilizando técnicas de **aprendizado supervisionado**.

## 🎯 Objetivo

Analisar os dados históricos dos clientes para prever a probabilidade de cancelamento de contrato, com base nas variáveis mais relevantes. Foram utilizados os algoritmos:

- 🌳 Árvore de Decisão (Decision Tree)
- 🤝 K-Nearest Neighbors (KNN)

Com base nos resultados dos modelos, são propostas **estratégias de retenção** para reduzir o churn.

## 🧠 Técnicas Utilizadas

- Pré-processamento de dados
  - Tratamento de valores ausentes
  - Codificação de variáveis categóricas (One-Hot Encoding)
  - Normalização
- Seleção de variáveis
- Treinamento e avaliação de modelos (train/test split)
- Análise de importância das variáveis
- Métricas de desempenho (Acurácia, Matriz de Confusão)

## 📁 Estrutura do Projeto

- `TelecomX_BR_Final_2.ipynb` — Notebook com toda a análise, visualizações e conclusões.
- `dados_clientes.csv` — (Opcional, se aplicável) Base de dados com informações dos clientes.

## 📌 Conclusões

- Determinadas variáveis (como tipo de contrato, tempo como cliente, e serviços contratados) mostraram alta influência na evasão.
- Estratégias direcionadas podem ser traçadas com base nos perfis de maior risco identificados.
