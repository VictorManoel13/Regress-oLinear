# Regressão Linear Simples em Python

Este repositório contém um exemplo simples de uma regressão linear usando Python e `scikit-learn`. O objetivo deste projeto é demonstrar como criar e treinar um modelo de regressão linear básico para prever valores com base em uma variável independente.

## Descrição

A **regressão linear** é uma técnica estatística usada para modelar e prever a relação entre uma variável dependente e uma ou mais variáveis independentes. No caso de uma **regressão linear simples**, usamos uma única variável independente para prever o valor da variável dependente.

Neste exemplo, geramos dados fictícios que seguem a equação linear:

\[ y = 4 + 3X + \text{ruído} \]

O modelo é treinado para ajustar uma linha reta que melhor se aproxima dos dados, minimizando o erro entre os valores previstos e os valores reais.

## Requisitos

Para rodar este projeto, você precisará das seguintes bibliotecas Python:

- `numpy`
- `matplotlib`
- `scikit-learn`

Você pode instalar todas as dependências necessárias usando o arquivo `requirements.txt` incluído neste repositório.

```bash
pip install -r requirements.txt
