<h1> :bar_chart: Churn de Clientes - Telecom X</h1>

## :round_pushpin: Introdução ao projeto
Este projeto faz parte de um desafio de análise de dados focado em um problema de negócio: a alta taxa de evasão de clientes (Churn) na empresa fictícia Telecom X. Como analista de dados, o objetivo foi explorar uma base de dados de clientes para identificar os principais fatores e perfis que levam ao cancelamento dos serviços.

## :books: Linguagem e Bibliotecas uilizadas
* Python
* Pandas
* Matplotlib
* json
* seaborn
* Numpy
* Ploty Express
* Requests
  
## :notebook_with_decorative_cover: Como utiliza-lo
🚀 Como Utilizar o Projeto

## 1. Clone o repositório ou baixe os arquivos .ipynb
```bash
git clone https://github.com/Gu1lhermeOliveira/Challenge_TelecomX.git
````

## 2. Instale as depedências (caso ainda não tenha)
```bash
import pandas as pd
import requests
import json
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import plotly.express as px
````

## 3. Abra o Google colab ou editor de código da sua escolha
```bash
google colab
````

## :dart: Objetivos da analise

* Identificar o perfil dos clientes com maior probabilidade de cancelamento;
* Analisar a relação entre os serviços contratados (ex: tipo de internet, serviços de proteção, etc...) e a taxa de churn;
* Verificar o impacto do tipo de contrato e do método de pagamento na retenção de clientes;
* verificar a relação entre os (tipos de pagamento, tipos de contrato) e a taxa de churn;
* Entender como o tempo de contrato (meses_de_contrato) e os gastos (gasto_mensal, gasto_total) se correlacionam com a decisão de cancelar.
* Gerar insights para que a empresa possa desenvolver estratégias de retenção eficazes.

## :chart_with_downwards_trend: Visualização
### 1. 
![image](images/meses_contrato_e_cancelamento.png)

### 2.
![image](images/taxa_cancelamento_meses_contrato.png)

### 3. 
![image](images/tipo_pagamento_cancelamento.png)

### 4.
![image](images/meses_contrato_gastos_totais_e_cancelamento.png)

### 5.
![image](images/meses_contrato_gastos_mensais_e_cancelamento.png)

### 6.
![image](images/boxplot.png)

### 6.
![image](images/tipo_internet_cancelamento.png)

## :bulb: Insights

<h3> Taxa de Cancelamento (%) por Gênero</h3>

⦁  Maior Taxa de Cancelamentos é por parte das Mulheres 0,76% a mais que os Homens;

<h3> Taxa de Cancelamento (%) em idosos </h3>

⦁  Maior Taxa de Cancelamentos é maior em pessoas com mais de 65 anos;

<h3> Relação entre Meses de Contrato e Cancelamento </h3>

⦁  Clientes com baixo tempo de casa e alto gasto mensal são o nosso maior risco. A combinação de ser novo na base com uma fatura cara é muito decisivo para o cancelamento. 

<h3> Taxa de Cancelamento (%) por Meio de Pagamento </h3>

⦁  A forma de pagamentos com mais clientes é o Check Eletronic e a com mais cancelamentos também com 45,29% de taxa de cancelamento;

<h3> Meses de Contrato vs Gastos Totais e Cancelamento </h3>

⦁	Quanto Maior é o tempo de contrato maior é o Gasto Total / Quanto Menor o Gasto Total maior é o numero de Cancelamentos;

⦁	Clientes com tempo de contrato de até 29 meses tem maior numero de Cancelamentos;

⦁	Gastos Mensais maiores que 60 tem maior taxa de Cancelamento.

<h3> Tipo de Contrato e Cancelamento </h3>

⦁	Tipo de Contrato Mês a Mês tem o maior numero de Cancelamentos ;

⦁	 Contratos com maior duração tem menor numero de cancelamentos ;

⦁	 Totalizando 214 cancelamentos para contratos com maior duração.

<h3>Taxa de Cancelamento (%) por tipo de Internet</h3>

⦁	Clientes com o serviço de internet por fibra optica tem maior taxa de cancelamento, indica que os clientes não estão percebendo um custo-benefíco que justifique o preço;

⦁	Clientes que optaram pelo tipo de internet DSL(internet que utiliza a linha telefônica) são os que menos cancelaram;

⦁	Clientes que não optarem por serviço de internet tem um cancelamento menor ainda em relação ao DSL e Fibra Optica.




## ⚠️ Autor do projeto

### Linkedin: www.linkedin.com/in/guilhermedooliveira
