# diabetes-data-analysis
Proyecto de análisis exploratorio de indicadores de salud relacionados con la diabetes.

# Análisis de Indicadores de Salud Relacionados con la Diabetes

Este proyecto tiene como objetivo realizar un análisis exploratorio de un conjunto de datos de salud recopilados por el sistema de vigilancia de factores de riesgo del comportamiento (BRFSS) en 2015. A través de este análisis, se busca identificar factores que podrían estar asociados con la diabetes y entender mejor el comportamiento de ciertas variables de salud en la población.

##  Dataset

El dataset utilizado proviene de Kaggle:  
**"Diabetes Health Indicators Dataset"**  
Contiene más de 250,000 registros con diversas variables relacionadas a salud física, mental y estilo de vida.

**Fuente**: [Kaggle - Diabetes Health Indicators](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

**Archivo utilizado**: `diabetes_012_health_indicators_BRFSS2015.csv`

##  Objetivo del análisis

- Explorar la distribución de la diabetes en la población.
- Identificar variables que podrían estar asociadas a la diabetes.
- Visualizar relaciones entre indicadores de salud (IMC, actividad física, calidad de sueño, etc.).
- Comunicar hallazgos clave de forma clara y visual.

##  Herramientas utilizadas

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook / Google Colab
- Git & GitHub

##  Estructura del proyecto

```bash
📁 diabetes-data-analysis
├── diabetes_012_health_indicators_BRFSS2015.csv  # Dataset original
├── diabetes_analysis.ipynb                       # Análisis completo en Jupyter Notebook
└── README.md                                     # Este archivo

```

## 📌 Variables destacadas

- `Diabetes_binary`: variable objetivo (1 = tiene diabetes, 0 = no tiene)
- `BMI`: índice de masa corporal
- `PhysicalActivity`, `SleepHours`, `Smoker`, `AlcoholDrinkers`, etc.

## 📈 Resultados esperados

- Identificación de patrones en los datos.
- Visualizaciones claras que comuniquen relaciones significativas.
- Conclusiones accionables para el entendimiento del riesgo de diabetes.

## 📎 Cómo ejecutar el análisis

1. Clona este repositorio:
```bash
git clone https://github.com/tu_usuario/diabetes-data-analysis.git

