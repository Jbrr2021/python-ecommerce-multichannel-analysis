# Análise de Dados em E-commerce Multicanal com Métricas Comportamentais

Este projeto apresenta uma análise exploratória de dados de um dataset de **e-commerce multicanal**, com foco em comportamento do cliente, receita, churn, engajamento e valor de longo prazo.

A análise foi desenvolvida com **Python**, **Pandas**, **Matplotlib** e **Google Colab**, com o objetivo de transformar dados em insights de negócio e fortalecer meu portfólio em análise de dados.

---

## Fonte dos dados

Dataset utilizado: **Multi-Channel E-commerce with Behavioral Metrics**  
Plataforma: **Kaggle**  
Link da base:  
https://www.kaggle.com/datasets/rifatalam3/multi-channel-e-commerce-with-behavioral-metrics

---

## Objetivos da análise

Nesta análise, busquei:

- entender a estrutura e a qualidade do dataset
- validar a consistência temporal dos dados
- identificar canais com melhor desempenho
- comparar receita total e receita média por canal
- analisar churn por segmento e por canal
- observar métricas de engajamento e retenção
- avaliar indicadores como CLV, CLV/CAC e rentabilidade
- construir uma visão mais próxima de um cenário real de negócio

---

## Principais análises realizadas

Durante o projeto, foram explorados os seguintes pontos:

- inspeção inicial da base
- verificação de valores ausentes
- validação de inconsistências temporais
- receita líquida por canal
- volume de clientes por canal
- receita líquida por produto
- churn geral
- churn por segmento
- churn por canal
- receita média por canal
- CLV por segmento
- CLV médio por canal
- relação CLV/CAC por canal
- profitability score por faixa de receita
- engajamento por canal
- newsletter x churn
- email open rate x churn
- criação de base limpa para análises mais confiáveis

---

## Principais insights

Alguns dos principais achados do projeto foram:

- o canal **Search** liderou em receita total e volume de clientes
- a receita média por canal apresentou pouca diferença entre os canais
- o produto **Product_E** apresentou destaque em receita líquida
- as taxas de churn mostraram pouca variação entre segmentos e canais
- o canal **Referral** se destacou em **CLV** e **CLV/CAC**
- foi necessário criar uma **base limpa**, devido a inconsistências temporais entre data de aquisição e data de compra

---

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- KaggleHub
- Google Colab
- GitHub

---

## Estrutura do projeto

```bash
.
├── README.md
└── analise_ecommerce_multicanal.ipynb
