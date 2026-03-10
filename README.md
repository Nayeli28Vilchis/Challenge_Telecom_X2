# Challenge_Telecom_X2
📊 Análisis de Cancelación de Clientes (Churn) – Telecom X
📌 Descripción del proyecto

En este proyecto se analizan datos de clientes de una empresa de telecomunicaciones con el objetivo de entender qué factores influyen en la cancelación del servicio (churn) y construir modelos que permitan predecir qué clientes tienen mayor probabilidad de cancelar.

El proyecto incluye limpieza de datos, análisis exploratorio, preparación de datos, entrenamiento de modelos de machine learning y evaluación de resultados.

🎯 Objetivos

Analizar el comportamiento de los clientes.

Identificar variables relacionadas con la cancelación.

Entrenar modelos predictivos para detectar clientes con riesgo de churn.

Proponer estrategias de retención basadas en los resultados.

📂 Dataset

El dataset contiene información sobre clientes de telecomunicaciones, incluyendo:

Información del cliente

Servicios contratados

Tipo de contrato

Método de pago

Cargos mensuales y totales

Variable objetivo Churn (si el cliente canceló o no)

Archivo utilizado:

TelecomX_Data.json
🧹 Preparación de datos

Durante el proceso se realizaron las siguientes etapas:

Carga y exploración del dataset

Limpieza de datos

Eliminación de variables irrelevantes (como customerID)

Transformación de variables categóricas mediante One-Hot Encoding

Análisis del desbalance de clases

Balanceo de datos utilizando SMOTE

Normalización de variables para modelos sensibles a escala

📊 Análisis exploratorio

Se analizaron diferentes variables para identificar patrones relacionados con la cancelación:

Tipo de contrato

Tiempo de permanencia del cliente

Cargos mensuales

Gasto total del cliente

Se utilizaron visualizaciones como:

gráficos de barras

boxplots

matriz de correlación

🤖 Modelos utilizados

Se entrenaron dos modelos de machine learning:

Regresión Logística

Modelo sensible a la escala de los datos, por lo que se aplicó normalización con StandardScaler.

Random Forest

Modelo basado en árboles de decisión que no requiere normalización y puede capturar relaciones más complejas entre las variables.

📈 Evaluación de modelos

Los modelos fueron evaluados utilizando:

Accuracy

Precision

Recall

F1-score

Matriz de confusión

El modelo Random Forest mostró mejor desempeño general en la predicción de cancelación.

🔍 Factores importantes en la cancelación

El análisis mostró que algunos factores tienen mayor influencia en la cancelación de clientes:

Tipo de contrato (mes a mes)

Tiempo de permanencia del cliente

Cargos mensuales

Servicios contratados

Los clientes con contratos mensuales y menor tiempo en la empresa tienen mayor probabilidad de cancelar el servicio.

💡 Recomendaciones

Con base en los resultados, algunas estrategias para reducir la cancelación podrían ser:

Incentivar contratos de mayor duración.

Prestar mayor atención a clientes nuevos.

Revisar la estructura de precios de los planes.

Utilizar modelos predictivos para identificar clientes con alto riesgo de cancelación.

🛠️ Tecnologías utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn

Google Colab

📁 Estructura del proyecto
Challenge_Telecom_X2
│
├── TelecomX_Data.json
├── TelecomX_Analysis.ipynb
├── README.md
└── requirements.txt
🚀 Conclusión

Este proyecto muestra cómo el análisis de datos y el machine learning pueden ayudar a entender el comportamiento de los clientes y apoyar la toma de decisiones en una empresa. Identificar clientes con riesgo de cancelación permite implementar estrategias de retención y mejorar la relación con los clientes.
