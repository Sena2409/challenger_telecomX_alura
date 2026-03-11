# Análise de Churn de Clientes — Telecom X

## 📊 Sobre o Projeto

Este projeto tem como objetivo analisar a **evasão de clientes (Churn)** da empresa fictícia **Telecom X**, identificando padrões que possam ajudar a compreender por que determinados clientes cancelam seus serviços.

A análise foi realizada a partir de um conjunto de dados em formato **JSON**, contendo informações sobre perfil dos clientes, serviços contratados, características da conta e status de cancelamento.

O projeto segue as etapas clássicas de **ETL (Extração, Transformação e Carga)** e **Análise Exploratória de Dados (EDA)** utilizando Python.

---

## 🎯 Objetivo

Identificar possíveis fatores associados ao **cancelamento de clientes**, permitindo que a empresa possa desenvolver estratégias de **retenção e fidelização**.

---

## 🛠 Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔄 Processo de ETL

### Extração

Os dados foram carregados a partir de um arquivo **JSON**, contendo informações estruturadas sobre clientes e serviços.

---

### Transformação

Durante essa etapa foram realizadas diversas transformações para preparar os dados para análise:

* Normalização de estruturas JSON aninhadas
* Expansão das colunas:

  * `customer`
  * `phone`
  * `internet`
  * `account`
* Padronização dos nomes das colunas
* Conversão de variáveis numéricas
* Ajuste de variáveis categóricas para facilitar a análise

Após essas etapas, os dados foram organizados em um **DataFrame estruturado**.

---

### Carga

Os dados tratados foram carregados em um DataFrame final utilizado para realizar a **análise exploratória de dados**.

---

## 📈 Análise Exploratória de Dados (EDA)

Durante a análise foram investigadas relações entre diferentes características dos clientes e a ocorrência de churn.

Algumas análises realizadas incluem:

* Distribuição de clientes que cancelaram ou permaneceram
* Relação entre **tipo de contrato e churn**
* Análise do **valor de cobrança mensal**
* Relação entre **tempo de contrato (tenure)** e cancelamento
* Comparação entre **serviços contratados e evasão de clientes**

Essas análises ajudam a identificar padrões importantes no comportamento dos clientes.

---

## 🔍 Principais Insights

Alguns padrões observados na análise:

* Clientes com **contratos mensais (Month-to-month)** apresentam maior taxa de churn
* Clientes com **menor tempo de permanência (tenure)** tendem a cancelar mais rapidamente
* O valor da cobrança mensal pode influenciar na decisão de cancelamento
* Certos serviços adicionais podem estar associados a diferentes níveis de retenção

Esses insights podem auxiliar a empresa na criação de estratégias para **reduzir a evasão de clientes**.

---

## 📂 Estrutura do Projeto

```
challenger_telecomX_alura
│
├── TelecomX_BR.ipynb
├── TelecomX_Data.json
├── README.md
└── dicionario_dados.md
```

---

## 🚀 Possíveis Melhorias Futuras

Como próximos passos, este projeto pode evoluir para:

* Criação de **modelos de Machine Learning para previsão de churn**
* Construção de **dashboards interativos**
* Análises mais profundas sobre comportamento de clientes
* Estratégias preditivas de retenção

---

## 👨‍💻 Autor

Projeto desenvolvido por **Lucas Sena**.

LinkedIn: *(adicione seu link aqui se quiser)*
