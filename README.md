# Análise Companhia de Seguros

## Descrição do Projeto
O objetivo é atrair mais motoristas durante o horário de pico, para isso é prever a quantidade de pedidos de táxi para a próxima hora. 
Foi construído um modelo para tal predição.

## Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas e Numpy: Biblioteca para manipulação e análise de dados.
- Sklearn: Biblioteca para construção de modelo de machine learning.
- Matplotlib.pyplot e Seaborn: Biblioteca para construção de gráficos
- statsmodels.tsa.seasonal: Trabalhar com séries temporais

## Tabela
O conjunto de dados possui os seguntes campos:
- datetime: data e hora do pedido
- num_orders: número de pedidos por hora

## Metodologia
**Análise Exploratória de Dados**
- Importar as bibliotecas necessárias
- Carregar e visualizar os dados

**Análise dos dados**
- Tendência
- Sazonalidade
- Resíduos
- Média móvel

**Preparação para Modelagem**
- Divisão do conjunto em treino e teste
- Enriquecimento dos dados

**Modelos de Machine Learning**
- Calibração de hiperparâmetros
- Regressão Linear
- Floresta Aleatória
- Análise de métricas

## Aprendizados
- Análise de dados: interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- Preparação do conjunto para aplicações em Machine Learning: separação do conjunto original em teste e treino, além da seleção das features e target do modelo.
- Funções: construção e aplicação de funções para simplificar o código.
- Regras de negócios: aplicação de regras de negócio para resolução de problemas.
- Séries Temporais: análise e previsão de séries temporais
- Aplicação de modelos de Machine Learning: aplicação, seleção de hiperparâmetros, teste e avalição do modelo.
- Documentação de projetos: elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- Utilização de bibliotecas e ferramentas: aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python.
- Tomada de decisões baseadas em dados: uso de insights derivados da análise de dados para orientar decisões estratégicas.
