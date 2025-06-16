# 🏠 House Price Prediction

Este projeto tem como objetivo prever o preço de imóveis com base em atributos estruturados, como número de banheiros, andar, presença de varanda, entre outros. Utilizamos algoritmos de regressão, com destaque para o **XGBoost Regressor**, que apresentou excelente desempenho com um **R² superior a 0.87**.

---

## 🎯 Objetivos do Projeto

- Identificar os principais fatores que influenciam o preço dos imóveis.
- Aplicar algoritmos de regressão para realizar previsões de preço.
- Comparar o desempenho entre diferentes modelos (Regressão Linear e XGBoost).
- Avaliar os modelos por meio de métricas como **R²**, **MSE** e **RMSE**.

---

## 🧠 Tecnologias Utilizadas

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **LinearRegression**
- **XGBoost**
- **Matplotlib**, **Seaborn** (para visualizações)
- **Jupyter Notebook**

---

## 📁 Estrutura do Projeto

### `house_prices_tratamento/`
Contém a etapa de análise e pré-processamento dos dados. Aqui foram realizadas limpeza, tratamento e extração de features para facilitar a modelagem.

- `House_prices_análise_e_tratamento.ipynb`: Notebook com a análise exploratória, tratamento de dados e preparação das features.
- `house_prices_tratado.csv`: Arquivo CSV com os dados tratados e prontos para modelagem.

### `house_prices_modelo/`
Contém a etapa de construção e avaliação dos modelos preditivos, utilizando os dados tratados da etapa anterior.

- `House_prices_model.ipynb`: Notebook com a construção dos modelos de Regressão Linear e XGBoost.
- `House_prices_prediction_test.ipynb`: Notebook de teste com previsão de preço por m² de um imóvel fictício.
- `XGBoost_model_prediction.pkl`: Arquivo `.pkl` com o modelo treinado utilizando o XGBoost.

---

## ✅ Resultados

- O modelo **XGBoost Regressor** obteve um desempenho superior em relação à regressão linear.
- Métricas obtidas com o XGBoost:
  - **R²:** > 0.87
  - **MSE** e **RMSE** apresentaram bons valores, indicando baixa margem de erro nas previsões.

---

## 🗄️ Base de Dados

- Os dados utilizados neste projeto estão disponíveis publicamente no **Kaggle**.
- Abaixo clique para acessar o projeto no kaggle:
- **[🏠House Price](https://www.kaggle.com/datasets/juhibhojani/house-price)**

