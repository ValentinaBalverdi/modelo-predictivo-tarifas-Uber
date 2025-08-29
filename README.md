# 🚖 Predicción de tarifas de Uber con Machine Learning  

Este proyecto implementa un **modelo de regresión supervisada** para predecir el precio de viajes en Uber a partir de información geográfica, temporal y de pasajeros.  
Forma parte de un trabajo académico, pero está adaptado como **proyecto demostrativo de Data Science y Machine Learning**.

---

## 📊 Descripción del proyecto  
El objetivo fue construir un **pipeline completo de Machine Learning** utilizando **Python y Scikit-learn**, que incluye:  

- **Exploración y análisis de datos (EDA):** histogramas, scatterplots, boxplots, matriz de correlación.  
- **Preprocesamiento:** manejo de valores faltantes y outliers, codificación de variables categóricas, escalado de datos.  
- **Modelado:**  
  - Regresión lineal múltiple (OLS).  
  - Descenso por gradiente y variantes.  
  - Regularización con **Lasso, Ridge y Elastic Net**.  
- **Optimización de hiperparámetros** para mejorar desempeño.  
- **Evaluación de modelos** con métricas de regresión (R², MSE, RMSE, MAE, MAPE).  
- **Visualizaciones** de curvas de error, gráficos de residuos y comparación de modelos.  

---

## 🛠️ Tecnologías utilizadas  
- **Lenguaje:** Python 3  
- **Librerías principales:**  
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - Scikit-learn  

---

## 📂 Estructura del repositorio  
├── data/ # Dataset original (uber_fares.csv)
├── notebooks/ # Notebook principal con el pipeline de ML
├── results/ # Gráficos y salidas relevantes
└── README.md # Documentación del proyecto


---

## 🎯 Objetivos de aprendizaje  
- Desarrollar habilidades en **preprocesamiento de datos y EDA**.  
- Comprender y aplicar **modelos de regresión y regularización**.  
- Mejorar el entendimiento de la **optimización de hiperparámetros**.  
- Comunicar resultados de forma clara mediante **visualizaciones y métricas**.  

---

## 📈 Resultados  
Tras la comparación de modelos, se obtuvo un **mejor desempeño con regularización Ridge** respecto a la regresión lineal simple, mostrando una reducción en el error y un fitting más estable.  
El análisis de residuos permitió identificar patrones y evaluar la calidad de los ajustes.

---

## 🚀 Cómo usar este proyecto  
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/usuario/nombre-repo.git
   cd nombre-repo
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
4. Abrir el notebook principal y ejecutar las celdas:
   ```bash
   jupyter notebook TP-regresion-AA1.ipynb
---

## 👩‍💻 Autoría
Proyecto desarrollado en el marco de la Tecnicatura Universitaria en Inteligencia Artificial (UNR).
Compartido como muestra de habilidades en Data Science y Machine Learning.
