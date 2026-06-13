# Proyecto Integrador: Análisis, Limpieza y Sintetización de Datos (Labs 01 - 10)

## 👤 Información del Alumno
* **Nombre:** Jerry Morales Rivera
* **Materia:** Extracción de Conocimientos de Base de Datos
* **Cuatrimestre:** 9° cuatrimentre

---

## 📝 Descripción General
Este repositorio compendia un flujo completo de Ciencia de Datos estructurado a lo largo de diversas prácticas de laboratorio. El proyecto abarca desde la exploración inicial de estructuras de datos y optimización de memoria para datasets de gran volumen (más de 1,000,000 de registros), hasta la implementación del ciclo **DIKW** (*Data, Information, Knowledge, Wisdom*) utilizando datasets históricos. 

Asimismo, se aborda formalmente la auditoría de calidad de datos, la mitigación de anomalías bajo el principio **GIGO** (*Garbage In, Garbage Out*) mediante la limpieza de datos atípicos, y finalmente la modelación avanzada para la generación y validación de datos sintéticos mediante cópulas paramétricas.

## 🎯 Objetivo
Desarrollar e implementar un pipeline integral de procesamiento de datos utilizando Python para auditar la calidad de la información, limpiar y transformar dataframes complejos, y aplicar modelos sintéticos (*Gaussian Copula Synthesizer*) evaluando cuantitativamente su fidelidad estadística frente a datos reales para la toma de decisiones.

---

## 📊 Datasets Utilizados
El análisis y experimentación se fundamentó en los siguientes conjuntos de datos distribuidos en los laboratorios:
1. **Dataset de Telecomunicaciones (`telecom_churn.csv`):** Datos orientados al análisis de deserción de clientes (*Churn*) con variables demográficas y de consumo telefónico.
2. **Dataset de Pasajeros del Titanic:** Utilizado para la abstracción del modelo jerárquico DIKW, evaluando correlaciones de supervivencia, género, clases y tarifas.
3. **Dataset Transaccional de Retail Financiero / Clientes:** Datos con registros intencionalmente "sucios" (valores nulos, correos inválidos, montos negativos y duplicados artificiales) para la simulación del principio GIGO.
4. **Datasets Masivos Optimizados:** Dataframes generados programáticamente con más de 1,000,000 de filas para pruebas de estrés de memoria e imputación veloz.

---

## 🛠️ Herramientas Utilizadas
El entorno de desarrollo y las tecnologías empleadas incluyen:
* **Lenguaje de Programación:** Python 3
* **Entorno de Desarrollo:** Jupyter Notebook (`.ipynb`) / Anaconda Distribution
* **Librerías Core de Análisis:** `pandas`, `numpy`
* **Librerías de Visualización:** `matplotlib.pyplot`, `seaborn`
* **Modelado y Datos Sintéticos:** `sdv` (*Synthetic Data Vault*), `GaussianCopulaSynthesizer`, `sdmetrics` (`QualityReport`)
* **Generación de Datos de Prueba:** `faker`, `random`

---

## 🚀 Instrucciones de Ejecución General

Para replicar localmente los análisis y ejecutar los cuadernos de Jupyter, sigue estos pasos:

1. **Clonar este repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
   cd tu-repositorio
