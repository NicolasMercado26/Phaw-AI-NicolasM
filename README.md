
# Repositorio del concurso de Phaw AI: Predicción de enfermedades coronarias

Este repositorio contiene los archivos desarrollados para el concurso de PhawAI. Fue desarrollado por **Nicolás Mercado**.


**Detalles del modelo final elegido** <br>
Finalmente se utilizó un modelo de boosting *LightGBM* con una optimización de hiperparámetros utilizando *Optuna*

---

##  Componentes Principales

### 1️⃣ **EDA y entramiento final**
Este cuadernillo contiene el exploratory data analysis y además todo el procedimiento que se siguió para elegir un modelo y además mejorar su desempeño. En este archivo se puede observar:
- Comparación de modelos
- K-fold para analizar cual modelo generaliza mejor
- Optimización de hiperparámetros
- Oversampling (SMOTE)
- Imputación de datos (Iterative imputer)



### 2️⃣ **Enfoques con técnicas de Deep learning**
**Técnicas de Deep Learning** <br> En este cuadernillo se ven dos técnicas de deep learning para trabajar con data tabular:
- Autoencoder para extraer features
- Tab-Net
Se utilizaron los frameworks: *Pytorch* y *Keras* 

### 3️⃣ **Feature Engineering**
En este cuadernillo se observa como se crearon múltiples variables a partir de las ya existentes. Ninguna mejoró significativamente el rendimiento del modelo.



## 📂 Estructura del Repositorio

```plaintext
📦 Repositorio
├── 1. EDA y entramiento final
├── 2. Enfoques con técnicas de Deep learning.ipynb 
├── 3. Feature Engineering.ipynb 
├── 4. resultado.csv      
└── README.md              