# Projeto de IA para Previsão de Score de Crédito

Este projeto utiliza algoritmos de Machine Learning para prever o score de crédito de clientes com base em seus dados financeiros e históricos.

## Funcionalidades

- Análise e tratamento da base de dados dos clientes.
- Treinamento de modelos de Machine Learning para classificação do score de crédito.
- Comparação de modelos (Random Forest e KNN) para escolher o melhor.
- Uso do melhor modelo para prever o score de novos clientes.

## Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Pré-requisitos

Antes de executar o projeto, instale as bibliotecas necessárias com o seguinte comando:

```bash
pip install pandas scikit-learn
```

## Como Executar

1. Certifique-se de que tem o Python e Jupyter Notebook instalados.
2. Abra o Jupyter Notebook e execute o arquivo principal (`projeto_credito.ipynb`).
3. O modelo será treinado e testado automaticamente.
4. Após a escolha do melhor modelo, ele será usado para prever novos clientes.

## Estrutura do Projeto

```
/
|-- main.ipynb             # Notebook principal com todo o código e análise
|-- clientes.csv           # Base de dados inicial com informações dos clientes
|-- novos_clientes.csv     # Dados de novos clientes para previsão
|-- README.md              # Documentação do projeto
```

## Como Funciona

1. A base de dados `clientes.csv` é carregada e analisada.
2. Os dados categóricos são transformados em valores numéricos com `LabelEncoder`.
3. O conjunto de dados é dividido em treino e teste.
4. Dois modelos são treinados: Random Forest e KNN.
5. O modelo com melhor acurácia é escolhido.
6. Novos clientes em `novos_clientes.csv` são avaliados pelo modelo.

## Autor

Vinícius Vilela Novelo