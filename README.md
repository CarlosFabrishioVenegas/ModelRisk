# 🧠 Credit Scoring MRM — Proyecto de Modelado Predictivo

## 📋 Descripción General

Este proyecto tiene como objetivo el desarrollo de un **modelo de Credit Scoring** utilizando técnicas estadísticas y de machine learning.  
A lo largo del proceso se aplican metodologías rigurosas para el **análisis exploratorio, ingeniería de características, selección de variables, entrenamiento de modelos lineales y ensambles, y calibración final del modelo**.

---

## 🧩 Estructura del Proyecto

### **1. Entendimiento y Análisis Exploratorio de Datos (EDA)**
Análisis inicial de la base de datos para comprender su estructura, distribución y calidad:
- Inspección de tipos de variables.
- Estadísticos descriptivos.
- Detección de valores atípicos y faltantes.
- Visualización de correlaciones y patrones.

---

### **2. Feature Engineering**
Transformación y limpieza de las variables para mejorar la calidad del modelo:
- **3.1 Tratamiento de Outliers Principales:** detección y corrección de valores extremos.
- **3.2 Tratamiento de Missing:** imputación de valores faltantes mediante estrategias estadísticas.
- **3.3 Tratamiento de Outliers:** técnicas adicionales de control de valores anómalos.

---

### **3. Feature Selection**
Selección de las variables más relevantes para el modelo:
- **4.1 Variables Cuasi Constantes:** eliminación de variables con baja variabilidad.
- **4.2 Análisis WOE e IV:** cálculo del Weight of Evidence (WOE) e Information Value (IV) para evaluar la capacidad predictiva.
- **4.3 Codificación de Variables:** transformación de variables categóricas.
- **4.4 Análisis de Correlaciones:** identificación y control de multicolinealidad.
- **4.5 Candidatos de Bases:** definición de subconjuntos de variables óptimas.

---

### **4. Entrenamiento de Modelos Lineales**
Implementación y calibración de modelos de regresión:
- **5.1 - 5.2** Regresión Lineal y Regresión Lineal Calibrada.
- **5.3 - 5.4** Regularización L1 (Lasso) y su versión calibrada.
- **5.5 - 5.6** Regularización Ridge y Ridge Calibrado.
- **5.7 - 5.8** Regularización Elastic Net y Elastic Net Calibrado.

---

### **5. Generación de Score y Offsets**
- **6.1 Comparativa de modelos logísticos.**
- **6.2 Creación de los *offsets*** para ajustar la puntuación del modelo en base a los resultados.

---

### **6. Modelos Ensamblados (Árboles de Decisión)**
Uso de modelos basados en árboles para mejorar el desempeño predictivo:
- **7.1 - 7.2** Árboles de decisión con y sin balanceo.
- **7.3 - 7.4** Bagging (Random Forest) con ajuste de hiperparámetros.
- **7.5** Boosting (Gradient Boosting).
- **8.1** Técnicas adicionales de balanceo.
- **10.1** Selección del mejor modelo ensamblado.
- **10.2** Guardado del modelo final entrenado.

---

### **7. Interpretabilidad y Valoración**
- **11.** Análisis de **SHAP values** e importancia de variables.
- **12.1** Evaluación de la capacidad discriminante del modelo.
- **12.2** Métricas de clasificación (ROC, AUC, KS, Precision, Recall, F1, etc.).

---

### **8. Calibración del Modelo**
- **13.1 Curvas de Calibración / Brier Score:** evaluación y ajuste de la probabilidad predicha para alinearla con las tasas reales observadas.

---

## ⚙️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.10+
- **Librerías principales:**  
  `pandas`, `numpy`, `scikit-learn`, `statsmodels`, `matplotlib`, `seaborn`, `shap`
- **Entorno:** Jupyter Notebook / Visual Studio Code

---

## 🧾 Resultados Esperados
- Modelo de Credit Scoring calibrado y validado.  
- Métricas de desempeño estables (AUC > 0.7).  
- Variables seleccionadas con fuerte relación predictiva.  
- Scorecard o puntuación ajustada al comportamiento real.

---

## 👨‍💻 Autor
**Carlos Fabrishio Venegas Arana**  
📊 Data Scientist | Machine Learning Specialist  
📫 [LinkedIn](https://www.linkedin.com/in/carlos-fabrishio-venegas-arana/)


