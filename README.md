# 💓 Heart Disease Classification

Este projeto utiliza algoritmos de Machine Learning para prever a presença de doenças cardíacas com base em dados clínicos de pacientes.

---

## 📁 Dataset

O dataset utilizado é o [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset), contendo variáveis como idade, pressão arterial, níveis de colesterol, entre outras.

---

## 🎯 Objetivo

Criar modelos que possam prever se um paciente tem ou não uma doença cardíaca com alta acurácia.

---

## 🧪 Modelos Treinados

-  Random Forest (com e sem tuning)
-  XGBoost
-  K-Nearest Neighbors (KNN)
-  Support Vector Machine (SVC)
-  Logistic Regression


---

## ⚙️ Pré-processamento

-  Exclusão da feature `fbs`, após análise de correlação com a variável alvo.
-  Escalonamento aplicado com `StandardScaler` (para modelos sensíveis à escala).
-  Divisão dos dados: `train_test_split` com 40% para teste (em virtude do tamanho do dataset).

---

## 📊 Visualizações

-  Matriz de Correlação
-  Curva ROC
-  Importância das Features
-  Acurácia: treino e teste
-  Validação Cruzada com Stratified K-Fold

---

## 🧠 Resultados

-  **Melhor modelo:** `RandomForestClassifier` com tuning leve
-  **Acurácia no conjunto de teste:** `0.9927`
-  **Train score:** `1.0`
-  **ROC AUC Score:** `1.0`
-  **Cross Validation Score médio:** `1.0`

---

## 🧬 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/otaviooalmeida/heart-disease-classifier.git
   cd heart-disease-classifier
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook (caso ainda não tenha, execute: pip install notebook):
   ```bash
   jupyter notebook

