# 🏠 Predição de Preços de Imóveis  

## 📘 Descrição do Projeto  
O presente projeto tem como finalidade realizar uma análise exploratória e preditiva de uma base de dados referente aos preços de imóveis. O estudo busca compreender os principais fatores que influenciam o valor de mercado das propriedades e, a partir disso, desenvolver um modelo de aprendizado de máquina capaz de estimar preços futuros com base em variáveis explicativas relevantes.  

Esse tipo de análise é amplamente utilizado em setores imobiliários, bancos e plataformas de anúncios, auxiliando na precificação mais assertiva e estratégica dos imóveis.  

---

## 🎯 Objetivos  

**Objetivo Geral:**  
Desenvolver um modelo preditivo capaz de estimar o preço de imóveis com base em variáveis descritivas.  

**Objetivos Específicos:**  
- Realizar a coleta e o tratamento dos dados.  
- Analisar estatisticamente as variáveis e suas correlações.  
- Visualizar padrões e tendências nos preços dos imóveis.  
- Testar diferentes modelos de aprendizado de máquina.  
- Avaliar o desempenho dos modelos e selecionar o mais eficiente.  

---

## 🧠 Metodologia  

1. **Coleta e preparação dos dados**  
   - Importação e análise inicial da base de dados.  
   - Tratamento de valores ausentes e inconsistências.  
   - Codificação de variáveis categóricas.  
   - Normalização e padronização dos dados.  

2. **Análise Exploratória de Dados (EDA)**  
   - Visualizações gráficas com *matplotlib* e *seaborn*.  
   - Identificação de correlações entre variáveis.  
   - Análise de distribuição dos preços e demais atributos.  

3. **Modelagem Preditiva**  
   - Separação dos dados em conjuntos de treino e teste.  
   - Aplicação de algoritmos de regressão (ex: *Linear Regression*, *Random Forest*, *XGBoost*).  
   - Ajuste de hiperparâmetros e comparação de métricas.  

4. **Avaliação de Desempenho**  
   - Métricas utilizadas: MAE, RMSE e R².  
   - Interpretação dos resultados e escolha do melhor modelo.  

---

## 🧩 Tecnologias Utilizadas  

- **Linguagem:** Python  
- **Bibliotecas:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Seaborn  
  - Matplotlib  
  - Optuna (para otimização de hiperparâmetros)  

---

## 📊 Resultados Esperados  

- Identificação das variáveis que mais influenciam o preço dos imóveis.  
- Criação de um modelo robusto e generalizável para previsão de preços.  
- Geração de insights que possam auxiliar na tomada de decisões no mercado imobiliário.  

---

## 📁 Estrutura do Projeto  

```
├── notebook   # Notebook principal do projeto  
├── README.md                      # Descrição geral do projeto  
├── data/                          # Pasta com bases de dados utilizadas  
├── models/                        # Modelos treinados e salvos  
└── images/                        # Gráficos e visualizações geradas
```

---
### [LINK DA BASE DE DADOS](https://www.kaggle.com/datasets/juhibhojani/house-price)
