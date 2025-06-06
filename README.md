# Telecom X – Análisis de Evasión de Clientes

![Portada](images/cover.png)

[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)  
[![Licence: MIT](https://img.shields.io/badge/licence-MIT-green.svg)](LICENSE)  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<tu-usuario>/TelecomX-Churn-Analysis/blob/main/notebooks/01_churn_analysis.ipynb)

## Tabla de Contenido
1. [Propósito](#propósito)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Ejemplos de Gráficos e Insights](#ejemplos-de-gráficos-e-insights)
4. [Instrucciones de Ejecución](#instrucciones-de-ejecución)
5. [Tecnologías Utilizadas](#tecnologías-utilizadas)
6. [Contribuyentes](#contribuyentes)
7. [Licencia](#licencia)

---

## Propósito

Este repositorio contiene el análisis exploratorio de datos (EDA) del **Proyecto Telecom X** cuyo objetivo es **identificar los factores que impulsan la deserción (churn) de clientes**.  
Los hallazgos servirán de insumo para que el equipo de Data Science construya modelos predictivos y diseñe estrategias de retención.

---

## Estructura del Proyecto

```text
TelecomX-Churn-Analysis/
│
├── data/                         # Datos brutos y procesados
│   └── TelecomX_Data.json
│
├── notebooks/                    # Notebooks Jupyter/Colab
│   └── 01_churn_analysis.ipynb
│
├── reports/                      # Informes generados
│   └── EDA_insights.md
│
├── images/                       # Figuras para el README / reportes
│   ├── churn_rate_by_contract.png
│   ├── heatmap_correlations.png
│   └── monthly_churn_trend.png
│
├── requirements.txt              # Dependencias de Python
└── README.md
