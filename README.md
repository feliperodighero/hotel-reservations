<div align="center">

  <h1>Hotel Reservations</h1>

  <p>
    Projeto Completo de Ciência de Dados
  </p>

<p>
  <a href="https://github.com/feliperodighero/hotel-reservations/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/feliperodighero/hotel-reservations" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/feliperodighero/hotel-reservations" alt="last update" />
  </a>
  <a href="https://github.com/feliperodighero/hotel-reservations/network/members">
    <img src="https://img.shields.io/github/forks/feliperodighero/hotel-reservations" alt="forks" />
  </a>
  <a href="https://github.com/feliperodighero/hotel-reservations/stargazers">
    <img src="https://img.shields.io/github/stars/feliperodighero/hotel-reservations" alt="stars" />
  </a>
  <a href="https://github.com/feliperodighero/hotel-reservations/issues/">
    <img src="https://img.shields.io/github/issues/feliperodighero/hotel-reservations" alt="open issues" />
  </a>
  <a href="https://github.com/feliperodighero/hotel-reservations/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/feliperodighero/hotel-reservations.svg" alt="license" />
  </a>
</p>
</div>
<br />

## ✨ Sobre o Projeto

O objetivo deste projeto é **analisar** e **prever o cancelamento de reservas de hotel**, com base no dataset [Hotel Reservations](https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset/data), disponível no Kaggle, que contém diversas variáveis relacionadas ao comportamento dos clientes e características das reservas.

A partir desse conjunto de dados, são aplicadas técnicas de análise exploratória e modelos de machine learning para entender os padrões e construir um modelo preditivo eficiente.

## 🛠 Tecnologias Utilizadas

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge" alt="Python" />
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=fff&style=for-the-badge" alt="pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=fff&style=for-the-badge" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=fff&style=for-the-badge" alt="NumPy" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=for-the-badge" alt="Jupyter" />
</p>

## 📊 Resultados Obtidos

Os resultados foram bastante satisfatórios com a aplicação da técnica de Stacking, que combinou os modelos RandomForestClassifier, ExtraTreesClassifier e DecisionTreeClassifier. Essa abordagem proporcionou uma melhora significativa no desempenho, demonstrando que técnicas baseadas em ensemble podem ser extremamente eficazes em problemas de classificação, atingindo 98% de AUC.

As visualizações, por meio da matriz de confusão e da curva ROC, reforçaram a alta performance dos modelos desenvolvidos, evidenciando sua capacidade de generalização e sua aplicabilidade prática.

Diante disso, conclui-se que a utilização de modelos de machine learning, aliada a uma boa análise e tratamento dos dados, é uma estratégia eficiente para auxiliar hotéis na previsão de cancelamentos. Isso permite que adotem medidas preventivas e estratégias comerciais mais assertivas, otimizando sua gestão e tomada de decisões.

Relatório Completo: [Relatório](./reports/Relatório%20-%20Felipe%20Rodighero%20Zarichta.pdf)
Projeto Completo: [Notebook1](./notebooks/1-data-analysis.ipynb) e [Notebook2](./notebooks/2-model-training.ipynb)

## 🚀 Como Executar Localmente

### Pré-requisitos

- Python 3.12 >

### Clonar o Projeto

`git clone https://github.com/feliperodighero/hotel-reservations.git`

### Instalar as Bibliotecas

`pip install -r requirements.txt`

## Estrutura do Projeto

```
├── README.md          <- Resumo sobre o projeto.
├── data
│   ├── external       <- Datasets utilizados.
│
│
├── models             <- Modelos treinados, resultados de modelos, etc.
│
├── notebooks          <- Jupyter Notebooks, com as análises e treinamento
│                         de modelos
│
│
├── references         <- Referências e outros materiais
│
├── reports            <- Relatórios sobre as análises e resultados
│   └── figures        <- Imagens usadas nas análises e relatórios
│
├── requirements.txt   <- Lista de dependências do projeto
```
