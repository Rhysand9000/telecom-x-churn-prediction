# 📊 Telecom X - Churn Prediction

Proyecto desarrollado como parte de la **Especialización en Data Science** de **Alura Latam**.  
El objetivo es aplicar técnicas de Machine Learning para predecir la cancelación de clientes (*churn*) en la empresa ficticia **Telecom X**.

---

## 📂 Estructura del Repositorio

```
telecom-x-churn-prediction/
│
├── data/
│   └── datos_tratados_telecom.csv   # Dataset procesado
│
├── notebooks/
│   └── churn_prediction.ipynb       # Notebook principal con el análisis y modelado
│
├── informe.pdf                      # Informe final con análisis, resultados y conclusiones
│
├── LICENSE                          # Licencia MIT
└── README.md                        # Este archivo
```

---

## 🚀 Instrucciones de Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/Rhysand9000/telecom-x-churn-prediction.git
cd telecom-x-churn-prediction
```

### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

Dependencias principales:
- Python 3.9+
- Pandas
- Numpy
- Scikit-learn
- Matplotlib / Seaborn

### 3️⃣ Abrir el Notebook en Google Colab
Puedes abrir el notebook directamente desde GitHub en Google Colab:  

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rhysand9000/telecom-x-churn-prediction/blob/main/notebooks/churn_prediction.ipynb)

---

## 📊 Flujo del Proyecto

1. **Exploración de datos**
   - Revisión de datos faltantes
   - Distribución de variables
   - Análisis de correlación

2. **Selección de variables**
   - Correlaciones con churn
   - Gráficas exploratorias (`tenure`, `Facturación_Total`)

3. **Modelado predictivo**
   - Regresión Logística (con normalización)
   - Random Forest (sin normalización)
   - Comparación de métricas: Accuracy, Precision, Recall, F1-score, ROC AUC

4. **Interpretación de resultados**
   - Importancia de variables por modelo
   - Factores más influyentes en la cancelación

5. **Informe final**
   - Documento PDF con análisis detallado, gráficas y conclusiones

---

## 📈 Resultados principales

- El **modelo de Regresión Logística** obtuvo el mejor desempeño en ROC AUC.  
- Variables clave relacionadas con la cancelación:
  - **Tenure (antigüedad)** bajo → mayor probabilidad de churn.  
  - **Facturación baja** → mayor riesgo de cancelación.  
  - **Internet Fiber Optic** y **método de pago Electronic Check** muestran asociación con mayor churn.  

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**.  
Puedes usarlo libremente, citando este repositorio.  

---

✍️ Proyecto realizado por **Renzo Echevarria** como parte de la Especialización en **Data Science – Alura Latam**.
