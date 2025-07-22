# Móudlo Machine Learning (ML) - Especialização CD (UFN)

Repositório destinado aos materiais de aula (turma 2025).

## Unidades/sub-unidades:

### 1. Fundamentos de Machine Learning
- Problemas de regressão
- Problenas de classificacao
- Problemas de agrupamento

### 2. Detecção de anomalias e Redes Neurais
- Detecção de anomalias
- Redução de dimensionalidade
- Redes Neurais Artificiais (foco em MLP)

### 3. AutoML e Deploy
- Fundamentos e aplicações de AutoML
- Deploy de modelos em produção
- Case: simulando um sistema de detecção de fraudes



## Detalhamento de tópicos abordados:

1.0 **Introdução**: (O que é Machine Learning, tipos de aprendizado, dados treino e teste, problemas de regressão, classificação, agrupamento, metodologia CRISP-DM, Algoritmos de ML e Aplicações, validação de modelos, Underfitting/Overfitting)

1.1 **Algortimos de Regressão**: previsão de custos em saúde e preenchimento de nulos com KNN em um dataset de Real Estate (cases com Python)

1.2 **Algortimos de Classificação**: previsão de churn (case com Python)

1.3 **Algoritmos de Agrupamento**: segmentação de uma base clientes (case com Python)

2.1 **Deteção de anomalias**

2.2 Redução de dimensionalidade com **Análise de Componentes Principais (PCA)** (case com Python)

2.3 **Redes Neurais Artificiais** (foco em Multi-Layer Perceptron)

3.1 **Ferramentas de autoML**: comparando e tunando modelos de ML com a biblioteca PyCaret (case com Python)

3.2 **Deploy** de máquinas preditivas com **Streamlit** ([repositório](https://github.com/OviedoVR/MLpredictSales) GitHub)

3.3 Case: **Simulando um sistema de detecção de fraudes**


## Cases Hands-on (desenvolvimento do zero em aula):
- Previsão do valor a ser investido em campanhas de marketing (regressão)
- Previsão do risco de crédito para uma base de clientes (classificação)
- Segmentação de clientes de um shopping (agrupamento)

## Onde encontrar bases de dados para praticar:

> **Web:**

- Kaggle: https://www.kaggle.com/datasets
- Dados gov br: https://dados.gov.br/dados/conjuntos-dados
- Data playground da Maven Analytics: https://mavenanalytics.io/data-playground
- Real World: https://data.world/datasets/open-data
  
> **Seaborn:**

```python
import seaborn as sns
sns.get_dataset_names()
# retorna uma lista de datasets disponíveis na biblioteca seaborn
```

Exemplo de uso:

```python
import pandas as pd
import seaborn as sns

tips = sns.load_dataset('tips')
tips.head()
```

## Links úteis:

- [Cheat Sheet Machine Learning](https://github.com/OviedoVR/ML_especializacao_2025/blob/main/cheatsheet/ML_cheat_sheet.ipynb)
- [Compilado de Pandas](https://oviedovr.github.io/compilado-pandas/)
- [DataViz with Plotly](https://oviedovr.github.io/DatavizWithPlotly/)