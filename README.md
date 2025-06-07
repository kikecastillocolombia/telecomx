# 📊 Análisis de Evasión de Clientes (Churn)

Este proyecto analiza los datos de clientes de una empresa de telecomunicaciones con el objetivo de entender los factores asociados a la evasión (churn), es decir, aquellos clientes que deciden cancelar el servicio.

---

## 🧠 Objetivo

Identificar patrones y relaciones en los datos que permitan:
- Predecir la evasión de clientes.
- Proponer estrategias para retenerlos.

---

## 📁 Estructura del Proyecto

```

.
├── churn\_analysis.ipynb       # Notebook con el análisis completo
├── README.md                  # Este archivo
├── data/                      # Carpeta con los datasets originales (privados)
├── outputs/                   # Carpeta con los gráficos generados

````

---

## ⚙️ Requisitos

Instala las librerías necesarias con:

```bash
pip install pandas numpy matplotlib seaborn
````

---

## 🚀 Cómo usar este proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/tu_usuario/churn-analysis.git
cd churn-analysis
```

2. Abre el notebook `churn_analysis.ipynb` en Jupyter o Google Colab.

3. Ejecuta las celdas paso a paso.

---

## 🧹 Limpieza y Transformación de Datos

* Se eliminaron valores nulos y filas con evasión "desconocido".
* Se convirtieron variables categóricas binarizadas (sí/no → 1/0).
* Se estandarizaron nombres de columnas para facilitar el análisis.

---

## 📊 Análisis Exploratorio

### 🔸 Distribución general de evasión

### 🔸 Comparación por Género

### 🔸 Contrato vs Evasión

### 🔸 Método de pago

### 🔸 Tenure y Total Charges

---

## 🔍 Conclusiones

* Los contratos mensuales tienen mayor probabilidad de evasión.
* El método de pago electrónico (sin factura) está relacionado con mayor churn.
* Los clientes con más antigüedad tienden a quedarse.

---

## 💡 Recomendaciones

* Promover contratos anuales o bianuales con beneficios extra.
* Incentivar pagos con factura y automatizados.
* Ofrecer retención proactiva a clientes nuevos en los primeros meses.

---
