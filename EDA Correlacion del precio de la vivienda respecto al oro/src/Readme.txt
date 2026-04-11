# 🏠 Análisis EDA: La Vivienda en España como Valor Refugio

![Status](https://shields.io)
![Topic](https://shields.io)
![Python](https://shields.io)

## 📋 Descripción del Proyecto
Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** exhaustivo sobre el mercado inmobiliario español. El objetivo principal es determinar si la vivienda sigue funcionando como un "activo refugio" frente a la inflación y la volatilidad de otros mercados financieros en el contexto actual.

Se analizan variables como precios de compra/alquiler, tipos de interés, volumen de transacciones y rentabilidad por comunidades autónomas.

## 🎯 Objetivos Principales
*   **Evolución histórica:** Comparar el crecimiento del precio de la vivienda frente al IPC.
*   **Análisis Geográfico:** Identificar las zonas con mayor tensión de precios y mayor rentabilidad.
*   **Correlación con Tipos de Interés:** Estudiar cómo afecta la subida del Euríbor a la demanda.
*   **Visualización de Insights:** Crear gráficos interactivos que faciliten la toma de decisiones de inversión.

## 📊 Visualizaciones Destacadas
Aquí puedes ver algunos de los hallazgos clave extraídos del análisis:

![Evolución de Precios](reports/figures/nombre_de_tu_grafico_1.png)
*Descripción breve: Por ejemplo, comparativa del precio m2 vs inflación.*

![Mapa de Rentabilidad](reports/figures/nombre_de_tu_grafico_2.png)
*Descripción breve: Por ejemplo, rentabilidad bruta por Comunidades Autónomas.*

## 🛠️ Stack Tecnológico
*   **Lenguaje:** Python.
*   **Librerías:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`.
*   **Fuentes de datos:** INE (Instituto Nacional de Estadística), Idealista y portales de datos abiertos.

## 📂 Estructura del Repositorio
*   `data/`: Contiene los datasets originales (`raw`) y el dataset final combinado (`processed`).
*   `notebooks/`: 
    *   `exploratory/`: Análisis individuales de cada fuente de datos.
    *   `00_Main_Analysis.ipynb`: El notebook principal con toda la narrativa y conclusiones.
*   `reports/figures/`: Gráficos y visualizaciones generadas.
*   `requirements.txt`: Librerías necesarias para replicar el entorno.
