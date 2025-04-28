🧠 Alzheimer Risk Prediction
Este projeto tem como objetivo prever o risco de Alzheimer com base em variáveis clínicas, demográficas, de estilo de vida e condições médicas. Ele foi desenvolvido como parte do Projeto 01 da disciplina de Aprendizado de Máquina (PPGEEC2318).

📊 Problema
Classificação binária: prever se um paciente tem ou não Alzheimer com base em diversos atributos.

Dataset usado: Operation Mind Shield Dataset

🧪 Tecnologias Utilizadas
Python

Pandas, NumPy, Scikit-learn

PyTorch

Matplotlib, Seaborn

🔍 Etapas do Projeto
1. Análise Exploratória
Sem valores ausentes

Variáveis numéricas e binárias

Variável-alvo: Diagnosis (0 = Não, 1 = Sim)

2. Pré-processamento
Remoção de colunas irrelevantes (PatientID e DoctorInCharge)

Normalização com StandardScaler

Separação em treino e teste (80/20)

3. Modelo
Regressão logística com PyTorch (nn.Linear + Sigmoid)

Função de perda: BCELoss

Otimizador: SGD

Treinamento por 100 épocas

4. Avaliação
Acurácia: 83,0%

Precisão: 78,9%

Recall: 71,2%

F1-score: 74,9%

AUC: 0.87

Métricas obtidas com sklearn.metrics

📈 Visualizações
Matriz de Confusão

![image](https://github.com/user-attachments/assets/fbdef099-2270-47a4-a860-f93217dbd79f)

✅ Conclusão
O modelo atingiu um bom desempenho, evidenciado por alta acurácia e AUC. As variáveis clínicas, comportamentais e de estilo de vida mostraram impacto relevante na previsão do risco de Alzheimer.
Melhorias futuras podem incluir redes neurais profundas ou técnicas de ensemble para refinar ainda mais a classificação.

🧠 Autor
Projeto desenvolvido por Igor Matias de Lima Dantas para a disciplina PPGEEC2318.
