# Predição da Qualidade de Vinhos Tintos

Este projeto tem como objetivo analisar dados físico-químicos de vinhos tintos para entender como essas características influenciam sua qualidade final. A partir disso, buscamos preparar os dados para a aplicação de modelos preditivos, seguindo boas práticas de análise e pré-processamento.

## Objetivo

Investigar padrões e relações entre os atributos dos vinhos tintos e a nota de qualidade atribuída, com foco em preparar um dataset limpo, escalado e interpretável para uso em modelos de machine learning.

## Dataset

O dataset utilizado é o **Wine Quality (Red)**, disponível publicamente no repositório da UCI Machine Learning. Ele contém informações de 1.599 amostras de vinho tinto, com 11 atributos físico-químicos e uma variável-alvo (`quality`), que representa a qualidade sensorial do vinho avaliada por especialistas.

## Etapas Realizadas

### 🔍 Análise Exploratória (EDA)
- Visualização da distribuição de variáveis
- Cálculo de estatísticas descritivas
- Análise de correlação entre atributos
- Identificação de padrões e outliers

### ⚙️ Pré-Processamento
- Separação entre variáveis preditoras (X) e variável alvo (y)
- Divisão em dados de treino e teste (70/30)
- Aplicação de normalização (MinMaxScaler)
- Criação de versões dos dados normalizados e padronizados
- Seleção automatizada das variáveis mais relevantes com base na correlação


## Conclusão

A análise mostrou que variáveis como **teor alcoólico**, **ácido volátil** e **sulfatos** têm forte relação com a qualidade do vinho. A normalização e a redução do número de atributos com base na análise de correlação permitem preparar um dataset mais limpo e eficiente para aplicação de modelos de machine learning supervisionado (regressão).

## Fonte dos dados

[UCI Machine Learning Repository - Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)

---
