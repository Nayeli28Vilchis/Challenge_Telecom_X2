# Challenge_Telecom_X2
📊 Análisis de Cancelación de Clientes (Churn) – Telecom X
📌 Descripción

En este proyecto se analiza un dataset de clientes de una empresa de telecomunicaciones para identificar factores relacionados con la cancelación del servicio (churn) y construir modelos de machine learning que permitan predecir qué clientes tienen mayor probabilidad de cancelar.

**🎯 Objetivo**

Analizar el comportamiento de los clientes.

Identificar variables que influyen en la cancelación.

Entrenar modelos predictivos para detectar clientes con riesgo de churn.

**🧹 Preparación de datos**

Se realizaron las siguientes etapas:

Limpieza y exploración del dataset

Eliminación de variables irrelevantes (ej. customerID)

Transformación de variables categóricas con One-Hot Encoding

Balanceo de clases usando SMOTE

Normalización de datos para modelos sensibles a escala

**🤖 Modelos utilizados**

Se entrenaron dos modelos de clasificación:

Regresión Logística (requiere normalización)

Random Forest (no requiere normalización)

Los modelos se evaluaron utilizando accuracy, precision, recall, F1-score y matriz de confusión.

**🔍 Resultados**

El modelo Random Forest mostró mejor desempeño en la predicción de cancelación.

Se identificó que variables como tipo de contrato, tiempo de permanencia del cliente y cargos mensuales tienen mayor influencia en la cancelación.

**🛠️ Tecnologías utilizadas**

Python

Pandas

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn

Google Colab

**🚀 Conclusión**

El análisis permite identificar patrones relacionados con la cancelación de clientes y demuestra cómo el uso de análisis de datos y machine learning puede ayudar a las empresas a mejorar sus estrategias de retención.
