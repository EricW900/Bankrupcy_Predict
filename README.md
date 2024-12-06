# 🏦 Modelo Preditivo de Falências Bancárias  

Este projeto utiliza **Machine Learning** para prever a falência de bancos com base em dados reais, incluindo classes desbalanceadas. Foi desenvolvido como parte de minha jornada de aprendizado em **Data Science** e **Inteligência Artificial**.

## 🚀 Visão Geral  
O objetivo principal foi criar um modelo preditivo eficiente, lidando com o desafio de desbalanceamento nas classes, em que apenas **5% dos bancos no dataset estavam classificados como em falência**. Para resolver isso, apliquei técnicas avançadas de balanceamento de dados e escolhi o modelo mais adequado após experimentação e validações.  

## 🛠️ Ferramentas e Técnicas Utilizadas  
- **Linguagem:** Python  
- **Bibliotecas:** scikit-learn, pandas, numpy, CatBoost, matplotlib, seaborn  
- **Técnicas:**  
  - Balanceamento de classes: SMOTE, Tomek Links  
  - Modelos testados: Random Forest, XGBoost, HistGradientBoostingClassifier, CatBoost  
  - Validação cruzada e ajuste de hiperparâmetros  
  - Métricas principais: Recall, AUC-ROC, Acurácia  

## 📊 Resultados  
O modelo escolhido foi o **CatBoost**, que apresentou os melhores resultados:  
- **Recall (classe 'Falência')**: 88%  
- **Acurácia Geral**: 78%  
- **AUC-ROC**: 0.85  

### 🔍 Avaliação do Modelo  
#### 1️⃣ Matriz de Confusão  
_Visualização da matriz de confusão do modelo final:_  
![Matriz_de_Confusao](https://github.com/user-attachments/assets/fc6ad380-87e0-4bba-82e6-a71cecdccb2e)

#### 2️⃣ Curva ROC-AUC  
_Gráfico da curva ROC-AUC para avaliar a performance do modelo:_  
![Curva_ROC](https://github.com/user-attachments/assets/2aee3470-82ff-4df9-820f-0d234b67d6e6)

#### 3️⃣ Relatório de Classificação  
_Resumo do Classification Report:_  
![accuracy_score](https://github.com/user-attachments/assets/fe5682c8-0bc3-40ce-bb5f-efbaa56649e0)
