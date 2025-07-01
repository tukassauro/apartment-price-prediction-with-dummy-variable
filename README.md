# Multiple Linear Regression: Apartment Price Prediction

This project explores a real estate dataset using **multiple linear regression** to predict apartment prices. The analysis focuses on how two features — **apartment size** and **sea view** — influence the final price.

## 🧠 Objective
The goal is to evaluate how much of the apartment's price variation can be explained by its **size in square meters** and whether it has a **sea view** (a dummy variable with values 0 or 1).

## 🔍 Features
- **Price (dependent variable)** — The target variable we aim to predict.
- **Size** — A continuous independent variable.
- **Sea View** — A binary dummy variable (1 = has sea view, 0 = no sea view).

## 🧪 Methodology
Using the `statsmodels` library, we applied an OLS (Ordinary Least Squares) regression model and interpreted the coefficients, p-values, and R². The dummy variable helped us isolate the impact of sea view presence on price, controlling for size.

## 📊 Key Learnings
- Dummy variables are crucial for incorporating categorical data into regression models.
- Regression coefficients can be interpreted as the average change in price given a one-unit change in the predictor, holding other variables constant.
- A significant p-value for the dummy variable would indicate that having a sea view affects apartment pricing.

---

# Regressão Linear Múltipla: Predição de Preço de Apartamentos

Este projeto utiliza **regressão linear múltipla** para prever o preço de apartamentos com base em duas variáveis explicativas: **tamanho** e **vista para o mar**.

## 🧠 Objetivo
Avaliar o quanto o **tamanho do imóvel** e a presença de **vista para o mar** (variável dummy) influenciam o preço do apartamento.

## 🔍 Variáveis
- **Preço (variável dependente)** — A variável que queremos prever.
- **Tamanho** — Variável contínua que representa a metragem do imóvel.
- **Vista para o mar** — Variável dummy binária (1 = tem vista, 0 = não tem).

## 🧪 Metodologia
Utilizamos a biblioteca `statsmodels` para aplicar o modelo de regressão OLS (Mínimos Quadrados Ordinários), analisando os coeficientes, valores-p e R². A variável dummy permitiu quantificar o impacto isolado da vista para o mar, controlando o tamanho.

## 📊 Aprendizados
- Variáveis dummy são essenciais para incluir dados categóricos em modelos de regressão.
- Coeficientes da regressão indicam a variação média no preço a cada unidade de mudança em uma variável, mantendo as outras constantes.
- Um valor-p significativo para a dummy indicaria que a vista para o mar tem impacto no preço final do apartamento.
