# 🏠 Análisis EDA: La Vivienda en España como Valor Refugio

El objetivo central de este análisis es determinar si el **mercado inmobiliario español** actúa como un activo refugio frente a escenarios de incertidumbre económica, analizando su resiliencia frente a la inflación y otros activos tradicionales.

---

## 📋 Descripción del Proyecto

Para validar esta hipótesis, el estudio se desglosa en los siguientes hitos estratégicos:

*   **Capacidad de cobertura (Hedge):** Análisis de la revalorización de la vivienda frente al **IPC** y su correlación histórica con el **oro**.
*   **Desacople financiero:** Investigación de la resiliencia del precio de venta frente a la subida del **Euríbor**.
*   **Rentabilidad del alquiler:** Evolución del mercado de arrendamiento como motor independiente del ciclo de venta.
*   **Brecha de accesibilidad:** Determinación del **"Ratio de Esfuerzo Crítico"** (Salarios vs. Precios).
*   **Análisis Histórico:** Contraste del ciclo actual frente a la crisis de **2008** para identificar patrones de solvencia.

---

## 📊 Visualizaciones Destacadas

<p align="center">
  <img src="EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Gif_Readme.gif" width="100%" alt="Análisis de Vivienda">
</p>

![Infografía Vivienda vs Oro](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Infografia%20EDA%20Vivienda%20como%20valor%20refugio%20en%20España.png)

---

## 🛠️ Stack Tecnológico


| Herramienta | Uso Principal |
| :--- | :--- |
| **Python** | Lenguaje base del análisis |
| **Pandas / NumPy** | Procesamiento y limpieza de datos |
| **Matplotlib / Seaborn** | Visualización estadística avanzada |
| **Scikit-Learn** | Modelado de regresión lineal |
| **Functools** | Optimización de procesos funcionales |

> **Fuentes de datos:** INE (Instituto Nacional de Estadística), Idealista y portales de datos abiertos.

---



## 📂 Estructura del Repositorio

*   `data/`: Datasets originales (`raw`) y procesados (`processed`).
*   `notebooks/`: 
    *   `exploratory/`: Análisis individuales por fuente.
    *   `00_Main_Analysis.ipynb`: **Notebook principal** con la narrativa completa y conclusiones.
*   `reports/figures/`: Gráficos y visualizaciones exportadas.
*   `requirements.txt`: Archivo de dependencias para replicar el entorno.

---



