# 📊 Análisis de Retención y Comportamiento de Clientes - ConnectaTel (LATAM)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SciPy / Stats](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
[![GitHub Notebook](https://img.shields.io/badge/📖_Ver_Notebook-Online-blue?style=for-the-badge&logo=github)](./S7_Version_Estudiante_Project_ConnectaTel_aprobado.ipynb)

---

## 📝 Descripción del Proyecto

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** y pruebas de hipótesis estadísticas sobre la base de usuarios de **ConnectaTel**, una empresa del sector de telecomunicaciones en Latinoamérica. 

El objetivo principal es examinar los patrones de comportamiento de los clientes, evaluar métricas de consumo y facturación, e identificar factores de riesgo asociados a la retención de usuarios, documentando todo el proceso analítico con visualizaciones claras.

---

## 🎯 Objetivos Principales

1. **Estructuración y Limpieza de Datos:** Procesamiento de variables categóricas y numéricas, manejo de nulos y tratamiento de *outliers*.
2. **Análisis Exploratorio de Datos (EDA):** Identificación de patrones de consumo y hábitos de uso de servicios en la región.
3. **Pruebas de Hipótesis Estadísticas:** Validación rigurosa de supuestos de negocio sobre métricas clave (ingresos y fidelidad del usuario).
4. **Insights y Recomendaciones:** Generación de hallazgos orientados a optimizar las estrategias de negocio.

---

## 📊 Análisis Ejecutivo e *Insights*

⚠️ **Calidad y Limpieza de Datos (Data Hygiene)**
- **Tipos de datos erróneos:** Inconsistencias detectadas en los atributos de fecha (*date*).
- **Valores nulos:** Presencia de nulos en `Churn_date` (descartados al no formar parte del alcance analítico actual).
- **Falsos nulos:** Detección de registros vacíos o anómalos en el atributo de ubicación (`ciudad`).

🔍 **Segmentación Demográfica y de Comportamiento**
- **Segmentos por Edad:** Se identifica que los **adultos** son los principales usuarios del servicio tradicional, mientras que la participación de los **jóvenes** es baja. 
  - *Hipótesis:* Los jóvenes priorizan canales de comunicación digital (redes sociales y aplicaciones de mensajería), haciendo menor uso de llamadas y mensajes de texto tradicionales.
- **Nivel de Uso:** Se observa una alta asimetría; cerca del **90% de los usuarios** se agrupa en un clúster de bajo consumo (menos de 10 llamadas y 10 mensajes), frente a un nicho específico de *power users* con un consumo aproximado de 250 interacciones.

💡 **Recomendaciones Estratégicas**
- **Ampliar el scope de análisis:** Incorporar métricas de consumo de datos móviles y tráfico en redes sociales para capturar con precisión el comportamiento del segmento joven.
- **Auditoría de captura:** Revisar los procesos de registro en el atributo `duration` (minutos de llamada) para asegurar la correcta captura de los datos y evitar sesgos analíticos.

---

## 🛠️ Tecnologías y Librerías Utilizadas

- **Lenguaje:** Python 3.x
- **Manipulación de Datos:** `pandas`, `numpy`
- **Visualización de Datos:** `matplotlib`, `seaborn`
- **Análisis Estadístico:** `scipy.stats`
- **Entorno de Desarrollo:** Jupyter Notebooks

---

## 👁️ Cómo Visualizar el Proyecto

Puedes explorar el código fuente, los gráficos y las conclusiones directamente en el navegador haciendo clic en el siguiente enlace (sin necesidad de ejecutar celdas ni configurar entornos):

👉 **[Ver el Notebook completo de Análisis (S7_Version_Estudiante_Project_ConnectaTel_aprobado.ipynb)](./S7_Version_Estudiante_Project_ConnectaTel_aprobado.ipynb)**

---
