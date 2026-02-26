# # 📡 TelecomX – Churn Prediction Challenge

Bienvenido a **TelecomX Churn Prediction**, un proyecto de Ciencia de Datos enfocado en la identificación y predicción de clientes con alta probabilidad de abandono (Churn).

Este proyecto forma parte de un challenge práctico de Alura One donde se desarrolla un flujo completo de Machine Learning: desde el análisis exploratorio hasta la evaluación comparativa de múltiples modelos de clasificación.

---

## 🎯 Objetivo del Proyecto

El objetivo principal es **predecir qué clientes tienen mayor probabilidad de cancelar el servicio**, utilizando variables demográficas, contractuales y de comportamiento.

La meta no es solo entrenar modelos, sino:

- 📊 Comprender los factores que influyen en el churn
- 🧠 Comparar distintos algoritmos de clasificación
- 📈 Evaluar métricas relevantes para negocio
- 🔎 Identificar el modelo con mejor desempeño

---

## 🧩 Metodología Aplicada

El proyecto sigue un flujo estructurado de análisis:

### 1️⃣ Análisis Exploratorio de Datos (EDA)
- Distribución de la variable objetivo
- Correlaciones entre variables numéricas
- Identificación de variables relevantes
- Análisis de patrones asociados al churn

### 2️⃣ Preprocesamiento
- Separación de variables numéricas y categóricas
- Codificación con One-Hot Encoding
- Escalado de variables numéricas
- Uso de `ColumnTransformer`
- Implementación de `Pipeline` para evitar data leakage

### 3️⃣ Modelado
Se entrenaron y compararon múltiples modelos de clasificación:

- Logistic Regression
- Decision Tree
- Decision Tree (Balanced)
- Random Forest
- Gradient Boosting

### 4️⃣ Evaluación
Se utilizaron métricas clave para problemas de churn:

- Accuracy
- Recall (Churn)
- F1-score
- ROC-AUC

---

## 📊 Resultados Destacados

Entre los modelos evaluados:

- 📈 **Gradient Boosting** mostró la mejor capacidad discriminativa (mayor ROC-AUC).
- ⚖ **Logistic Regression** presentó el mejor equilibrio general entre Recall y F1-score.
- 🌲 Los árboles individuales mostraron menor capacidad de generalización.
- 🌳 Los modelos ensamblados superaron claramente a los modelos simples.

Esto demuestra la importancia de comparar arquitecturas antes de elegir un modelo final.

---

## 💡 Principales Insights

- El problema presenta señales de desbalance en la clase churn.
- La optimización de hiperparámetros puede mejorar significativamente el rendimiento.
- Ajustar el umbral de clasificación podría incrementar la detección de clientes en riesgo.
- Modelos más complejos no siempre superan ampliamente a modelos lineales bien ajustados.

---

## 🛠️ Tecnologías Utilizadas

- 🐍 Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn
- Jupyter Notebook

---

## 📁 Estructura del Proyecto
