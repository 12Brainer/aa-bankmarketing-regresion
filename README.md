# 🤖 Aprendizaje Automático — Trabajo Práctico 02

Este repositorio contiene el **Trabajo Práctico 02** del curso **Aprendizaje Automático**.  
El objetivo principal es diseñar y ejecutar un **experimento de regresión** utilizando el dataset **Bank Marketing (bank-full.csv)**.

---

## 📂 Contenido del notebook

- **Diseño del Experimento**  
  Descripción detallada del flujo de trabajo aplicado para el problema de regresión.

- **Dataset Bank Marketing**  
  - 45,211 registros y 17 atributos relacionados con campañas de marketing de un banco.  
  - Variable objetivo: **suscripción a un depósito a plazo fijo**.  

- **Preprocesamiento**  
  - Análisis exploratorio del dataset.  
  - Visualización y análisis del balance de clases.  
  - Limpieza de datos y verificación de valores nulos.  
  - Codificación de variables categóricas con **OneHotEncoder**.  
  - Escalamiento de atributos numéricos.  

- **División de Datos**  
  Separación en **entrenamiento (80%)** y **evaluación (20%)**.

---

## ⚙️ Requisitos

Para ejecutar este notebook necesitas:

- Python 3.8+
- [Jupyter Notebook](https://jupyter.org/) o [JupyterLab](https://jupyter.org/install)
- Librerías:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `category_encoders`
  - `matplotlib`

Instala las dependencias con:

```bash
pip install numpy pandas scikit-learn category_encoders matplotlib
