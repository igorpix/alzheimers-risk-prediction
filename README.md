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

![confusion](![image](https://github.com/user-attachments/assets/46490f17-ebff-4b0c-acb4-944b66bedd2c)
)

### Curva ROC

![roc](figs/roc_curve.png)

### Importância das Features

![features](figs/feature_importance.png)

---

## 📁 Organização do Código

- `Alzheimer_Risk_Prediction.ipynb`: notebook com todo o código
- `figs/`: pasta com os gráficos gerados
- `requirements.txt`: dependências do projeto

---

## ✅ Conclusão

O modelo foi capaz de atingir um desempenho razoável, com destaque para variáveis como idade, presença do alelo APOE-ε4, histórico familiar e país de origem. Melhorias futuras podem incluir redes neurais ou ensemble models.

---

## 🧠 Autor

Projeto desenvolvido por [Seu Nome] para a disciplina PPGEEC2318.

