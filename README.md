# Análise de Aluguéis em São Paulo

Este projeto realiza uma análise exploratória e modelagem de dados de aluguéis em São Paulo, utilizando técnicas de Regressão Linear e Modelagem preditiva

## Bibliotecas Utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Dados

Os dados utilizados neste projeto são do arquivo `base-alugueis-sp (1).csv`. Este arquivo contém informações sobre diversos imóveis disponíveis para aluguel em São Paulo.

## Análise Exploratória

A análise exploratória inclui a verificação de dados nulos, a visualização da distribuição dos aluguéis através de um boxplot e a remoção de outliers. Além disso, foram gerados gráficos para visualizar a relação entre o aluguel e outras variáveis, como a área do imóvel e o número de quartos.

## Pré-processamento

O pré-processamento dos dados envolveu a remoção de colunas que não seriam utilizadas no modelo e a normalização dos dados.

## Modelagem

Foi utilizado um modelo de Regressão Linear para prever o valor do aluguel com base nas outras variáveis do dataset. O modelo foi treinado com 80% dos dados e testado com os 20% restantes.

## Resultados

Os resultados do modelo são exibidos através de um gráfico de dispersão comparando os valores reais e previstos de aluguel. Além disso, foi calculada a média do aluguel real e previsto por área.Os resultados apresentados foram satisfatórios no sentido de que não estão extrapolados para mais ou menos

## Visualizações

O projeto inclui diversas visualizações para auxiliar na análise dos dados e na avaliação do modelo. Estas visualizações incluem histogramas, gráficos de dispersão e gráficos de barras.