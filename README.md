# 🧠 Alzheimer Risk Prediction

Este projeto tem como objetivo prever o risco de Alzheimer com base em variáveis clínicas, demográficas, de estilo de vida e fatores genéticos. Ele foi desenvolvido como parte do Projeto 01 da disciplina de Aprendizado de Máquina (PPGEEC2318).

## 📊 Problema

Classificação binária: prever se um paciente tem ou não Alzheimer com base em diversos atributos.

Dataset usado: [Alzheimer's Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/ankushpanday1/alzheimers-prediction-dataset-global)

---

## 🧪 Tecnologias Utilizadas

- Python
- Pandas, NumPy, Scikit-learn
- PyTorch
- Matplotlib, Seaborn

---

## 🔍 Etapas do Projeto

### 1. Análise Exploratória
- Sem valores ausentes
- Distribuição equilibrada entre variáveis
- Variável-alvo: `Alzheimer’s Diagnosis` (Yes/No)

### 2. Pré-processamento
- One-Hot Encoding das variáveis categóricas
- Normalização com StandardScaler
- Separação em treino e teste (80/20)

### 3. Modelo
- Regressão logística com PyTorch (`nn.Linear + Sigmoid`)
- Função de perda: `BCELoss`
- Otimizador: `SGD`
- Treinamento por 100 épocas

### 4. Avaliação
- Acurácia: **71,5%**
- Precisão: **67,3%**
- Recall: **60,5%**
- F1-score: **63,7%**
- AUC: **0.77**
- Métricas obtidas com `sklearn.metrics`

---

## 📈 Visualizações

### Matriz de Confusão

![image](https://github.com/user-attachments/assets/f5b9d3d8-2f2c-45c3-8d7e-b1c786266d33)


### Curva ROC

![image](https://github.com/user-attachments/assets/1e660817-c98b-4ff1-be5a-dd70708ae7a7)


### Importância das Features

![image](https://github.com/user-attachments/assets/c1131d21-01a9-4040-8dc0-ad07878a7b31)


---


## ✅ Conclusão

O modelo foi capaz de atingir um desempenho razoável, com destaque para variáveis como idade, presença do alelo APOE-ε4, histórico familiar e país de origem. Melhorias futuras podem incluir redes neurais ou ensemble models.

---

## 🧠 Autor

Projeto desenvolvido por Igor Matias de Lima Dantas para a disciplina PPGEEC2318.

