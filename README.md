# xgboost-depressao

## Modelo de Machine Learning para Análise de Saúde Mental

Este projeto utiliza uma base de dados pública (Kaggle) contendo informações sobre fatores comportamentais, demográficos e profissionais para construir um modelo de machine learning que prevê risco relacionado à saúde mental (pensamentos suicidas).

O objetivo é explorar variáveis que impactam esse risco e criar uma solução preditiva com boa acurácia, além de interpretar as principais features que influenciam o modelo.

## Estrutura do Projeto
notebook com o pipeline completo de pré-processamento, treinamento e avaliação

Visualizações da matriz de confusão e importância das variáveis

Modelo XGBoost para classificação binária

## Preparação dos Dados
Preenchimento de valores ausentes usando mediana ou valores fixos

Remoção de colunas irrelevantes (id, City, Name)

Codificação de variáveis categóricas com LabelEncoder e OneHotEncoder

Normalização das variáveis numéricas com StandardScaler

## Modelo
Modelo XGBoost Classifier configurado para classificação binária com objetivo binary:logistic

Divisão dos dados em treino e teste (80/20) com estratificação

Métricas avaliadas: acurácia, relatório de classificação, matriz de confusão

## Resultados
Acurácia do modelo: (adicione aqui o valor obtido)

Matriz de confusão para análise dos falsos positivos e falsos negativos

Gráfico com as 15 variáveis mais importantes para a predição
