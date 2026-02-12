# Sistemas Inteligentes para la Gestión en la Empresa

## 📊 Práctica 1: Pre-procesamiento y Clasificación (Dataset Diabetes)

El objetivo es realizar un flujo completo de ciencia de datos sobre el dataset «Diabetes Health Indicators» de Kaggle para predecir la presencia de la enfermedad.

### Tareas Principales
* **Análisis Exploratorio (EDA):** Visualización de variables y detección de conflictos iniciales.
* **Limpieza de Datos:** Tratamiento de valores perdidos (codificados como -999) e identificación de valores atípicos (*outliers*).
* **Ingeniería de Características:** Selección de variables mediante análisis de correlación.
    * Reducción de dimensionalidad mediante PCA (Análisis de Componentes Principales).
    * Normalización y discretización de datos.
* **Modelado:** Implementación y comparación de al menos dos técnicas de clasificación binaria.



## 🦅 Práctica 2: Deep Learning Multimodal (CUB-200-2011)

Desarrollo de un modelo de clasificación basado en redes neuronales profundas para la identificación de especies de pájaros, utilizando el dataset CUB-200-2011.

### Implementación Técnica
* **Arquitectura de Red:** Uso de redes neuronales convolucionales (CNN) mediante **PyTorch**.
* **Aprendizaje Multimodal:** Integración de imágenes y metadatos (atributos numéricos y descripciones).
* **Optimización Avanzada:**
    * Ajuste de hiperparámetros y topología de la red.
    * Gestión de experimentos y logging con **Weights And Biases (WANDB)**.
    * Aplicación de técnicas de **Transfer Learning** y fine-tuning.
* **Explicabilidad:** Uso de modelos explicables para justificar las predicciones basadas en atributos visuales específicos del dataset.


## 🛡️ Trabajo de Teoría: Clasificación de Ciberataques

Estudio y modelado predictivo sobre el dataset **Cyber Security Attacks** para la identificación de amenazas: DDoS, Intrusion y Malware.

### Resumen Técnico
* **Análisis y Pre-procesamiento:** Binarización de alertas para gestionar la alta tasa de datos faltantes y estudio de evolución temporal.
* **Ingeniería de Características:** Extracción de metadatos de dispositivos (Navegador y SO) mediante expresiones regulares.
* **Modelado:** Evaluación de modelos clásicos (Random Forest, XGBoost) frente a una **Red Neuronal Convolucional (CNN)**.
* **Arquitectura Final:** Implementación de un modelo **Ensemble (Soft Voting)** 


## 🛠️ Stack Tecnológico
* **Lenguajes:** Python 
* **Machine Learning:** Scikit-learn, caret, tidymodels, DataExplorer.
* **Deep Learning:** PyTorch, Keras, TensorFlow.
* **Herramientas de Gestión:** Weights & Biases (WANDB), Optuna, Google Colab.

---
**Autor:** [cristinadam1](https://github.com/cristinadam1)
*Máster en Ingeniería Informática - Universidad de Granada (UGR)*
