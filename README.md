# Módulo: Análise de Dados - COVID-19 Dashboard
Caderno de Exercícios  

---

## Tópicos

1. Introdução
2. Análise Exploratória de Dados
3. Visualização Interativa de Dados
4. Storytelling

---

## Exercícios

Este *notebook* serve como um guia para **você continuar** a construção da sua própria análise exploratória de dados interativa. Sinta-se à vontade para copiar os códigos da aula, mas busque explorar os dados ao máximo. Por fim, publique seu *notebook* no [Kaggle](https://www.kaggle.com/) e seu *dashboard* no [Google Data Studio](https://datastudio.google.com/).

---

## COVID Dashboard

### 1. Contexto

Escreva uma breve descrição do problema.

### 2. Pacotes e bibliotecas

As seguintes bibliotecas foram importadas para análise e visualização de dados:

- **Pacotes nativos do Python**: `os`
- **Pacotes de terceiros**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly.express`

```python
# Pacotes nativos do python
import os

# Pacotes de terceiros
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Pacotes para visualizações interativas
import plotly.express as px

# Configuração do Matplotlib para gráficos inline
%matplotlib inline
