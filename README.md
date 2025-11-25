# 📊 Estatística Descritiva em Python: Análise de Dados no iFood

## 🎓 Contexto do Projeto
Este repositório contém os exercícios e a análise final realizados como parte do **Módulo de Estatística com Python**, integrante da minha formação em **Ciência de Dados**, na Escola DNC. O trabalho foca estritamente em **Estatística Descritiva**, utilizando bibliotecas essenciais como Pandas, Seaborn e NumPy para manipulação e análise de dados.

O projeto explora uma base de dados real do segmento de *Food Delivery* (iFood), aplicando os fundamentos matemáticos necessários para extrair *insights*.

---

## 🔬 Análise e Operações Estatísticas Detalhadas

O trabalho foi dividido em três notebooks principais, detalhando as operações matemáticas e estatísticas realizadas:

### **1. Classificação e Preparação de Variáveis** (`classificando_variaveis.ipynb`)
Este notebook foca na limpeza e organização inicial dos dados:
* **Identificação de Tipos de Variáveis**: Determinação de quais colunas são **quantitativas** (contínuas/discretas) e **qualitativas** (nominais/ordinais).
* **Inspeção de Valores Únicos**: Uso de métodos como `df.unique()` para entender a diversidade de categorias.

### **2. Cálculos Estatísticos e Tratamento de Outliers** (`calculos_estatisticos.ipynb`)
Esta é a etapa central, na qual as métricas de **Estatística Descritiva** são aplicadas:
* **Medidas de Tendência Central**: Cálculo de **Média**, **Mediana** e **Moda** para variáveis-chave (`delivery_fee`, `delivery_time`, etc.).
* **Medidas de Dispersão**: Cálculo de **Desvio Padrão** ($\sigma$) e **Variância** ($\sigma^2$) para quantificar o *spread* (dispersão) dos dados.
* **Tratamento de *Outliers***: Remoção de valores extremos utilizando o método do **Intervalo Interquartil (IQR)**, garantindo a robustez das análises subsequentes.

### **3. Análise de Correlações e Agrupamentos** (`correlacoes_variaveis.ipynb`)
Neste notebook, investigamos as relações entre as variáveis:
* **Matriz de Correlação**: Cálculo da **Correlação de Pearson** 
* **Mapa de calor**: para identificar o grau de relação linear entre pares de variáveis quantitativas (ex.: relação entre `distance` e `delivery_time`).
<img width="325" height="283" alt="image" src="https://github.com/user-attachments/assets/b39cc5ec-f1cb-4f0d-81e2-5b6bfe3158fb" />
* **Análise de Agrupamento (`groupby`)**: Agrupamento da base de dados por variáveis categóricas (como `price_range`) para comparar a **média** da taxa e tempo de entrega entre os diferentes grupos.

---

## 📁 Estrutura do Repositório
* `notebooks/`: Contém os Jupyter Notebooks com os códigos e análises.
* `data/`: Contém o conjunto de dados utilizado na análise.
