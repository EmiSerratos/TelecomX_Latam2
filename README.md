# 📊 TelecomX LATAM – Predicción de Cancelación de Clientes (Churn)

Este proyecto aborda el desafío de **predecir qué clientes tienen mayor probabilidad de cancelar su servicio** en TelecomX LATAM.  
El análisis combina técnicas de **Machine Learning** con una visión estratégica orientada a la retención de clientes.  

---

## 🎯 Objetivo

- Construir modelos predictivos capaces de anticipar la **cancelación de clientes (churn)**.  
- Identificar los **factores más influyentes** en la decisión de baja.  
- Proponer **estrategias de retención** basadas en los hallazgos.  

---

## 🛠️ Tecnologías utilizadas

- **Python 3** 🐍  
- **Pandas & NumPy** 📊  
- **Matplotlib & Seaborn** 📈  
- **Scikit-learn** 🤖  
- **Google Colab / Jupyter** 📓  

---

## 📂 Estructura del proyecto

- `datos_tratados.csv` → Dataset preprocesado a partir del análisis exploratorio.  
- `TelecomX_LATAM_Challenge3.ipynb` → Notebook con todo el pipeline de predicción.  

---

## 🔎 Análisis realizado

1. **Preprocesamiento de datos**
   - Eliminación de columnas irrelevantes (ej. identificadores únicos).  
   - Codificación de variables categóricas (one-hot encoding).  
   - Tratamiento de desbalance de clases (SMOTE).  
   - Normalización para modelos sensibles a la escala.  

2. **Modelado**
   - **Regresión Logística** (con escalado).  
   - **Random Forest** (sin escalado).  

3. **Evaluación de Modelos**
   - Accuracy, Precisión, Recall, F1-score.  
   - Matriz de confusión.  
   - Comparación crítica de desempeño.  

4. **Análisis de Variables Relevantes**
   - **Regresión Logística:** coeficientes como indicadores de impacto.  
   - **Random Forest:** importancia de variables en las divisiones de los árboles.  

---

## 💡 Principales hallazgos

- **Mayor permanencia (tenure)** y **contratos largos (1–2 años)** reducen la probabilidad de cancelación.  
- Los clientes con **método de pago Electronic Check** muestran mayor tendencia al churn.  
- **Servicios adicionales (OnlineBackup, OnlineSecurity)** actúan como factores de fidelización.  
- **Facturación sin papel (PaperlessBilling)** presenta relación positiva con el churn: requiere análisis adicional.  

---

## 🚀 Recomendaciones estratégicas

- Fortalecer el **onboarding en los primeros meses** para reducir cancelaciones tempranas.  
- Incentivar la migración hacia **contratos más largos** mediante descuentos o beneficios.  
- Promover **métodos de pago automáticos y seguros**.  
- Optimizar la experiencia digital para clientes con **PaperlessBilling**.  
- Ofrecer y destacar los **servicios de valor agregado** como respaldo y seguridad en línea.  

---

## ✨ Autor

Proyecto desarrollado por **Emilio Serratos**  with ChatGPT
