## 🔥 Proyecto ML — Detección de Fraude en Transacciones (Python & Scikit-Learn)

Desarrollé un modelo de Machine Learning para detectar transacciones fraudulentas en un dataset con **284k registros** y un **fuerte desbalance de clases** (fraudes <1%). Realicé un EDA completo, visualizaciones y preprocesamiento para construir un sistema robusto centrado en maximizar la detección de la clase minoritaria.

### 🔧 Enfoque Técnico
- Análisis exploratorio y visualización de **30 variables** (Time, Amount, V1–V28).  
- Manejo del desbalance mediante **class_weight='balanced'**.  
- Entrenamiento y comparación de modelos, seleccionando **Random Forest** como mejor opción.  
- Implementación de un enfoque híbrido (muestreo + pesos) para mejorar la sensibilidad del modelo.

### 📊 Resultados del Modelo (RandomForest)
- **Precision:** 0.829  
- **Recall:** 0.789  
- **F1 Score:** 0.808  
- **AUC:** 0.978  

Incluye generación de matriz de confusión, curva ROC, análisis de correlaciones y visualización del desbalance.

### ✅ Resultado Final
Modelo optimizado capaz de identificar fraudes con alta precisión y recall, funcionando eficazmente incluso en escenarios de desbalance extremo.
