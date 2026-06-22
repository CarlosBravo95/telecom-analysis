# telecom-analysis
Data analytics project for ConnectaTel to identify high-value customer patterns, resolve data anomalies, and build demographic and usage-based segmentations.
# ES
# Análisis de Perfiles de Consumo y Segmentación - ConnectaTel 🚀

## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es analizar los perfiles de uso y datos demográficos de los usuarios de ConnectaTel para identificar patrones de consumo, corregir anomalías estructurales en los datos y generar una segmentación estratégica por edad y nivel de actividad.

## 📊 Datasets Utilizados
* **Datos de Usuarios (`users`):** Información demográfica como edad, ciudad, fecha de registro y tipo de plan.
* **Datos de Consumo (`usage`):** Registros mensuales de actividad que incluyen mensajes enviados, llamadas realizadas y minutos consumidos.

## ⚙️ Etapas del Análisis Realizadas
1.  **Limpieza de Datos:** Corrección de valores nulos (asimilados a 0 consumo) y valores estructurales erróneos (*sentinels* en edad).
2.  **Análisis Descriptivo:** Exploración estadística básica de las tendencias centrales del dataset.
3.  **Auditoría de Outliers:** Identificación cuantitativa de usuarios atípicos mediante el método de Rango Intercuartílico (IQR).
4.  **Segmentación:** Creación de nuevas reglas lógicas de negocio por grupos de edad y niveles de uso.
5.  **Insights Ejecutivos:** Formulación de recomendaciones comerciales estratégicas para la toma de decisiones.

## 🚀 Cómo Ejecutar el Notebook
Este proyecto está diseñado para ejecutarse de manera directa y en la nube a través de **Google Colab**. Solo debes abrir el archivo con extensión `.ipynb` en tu repositorio y presionar el botón superior "Open in Colab" para correr las celdas de forma secuencial.

## 📋 Guía de Reproducción
Para que los resultados se repliquen de forma exacta, asegúrate de cargar los archivos originales de los datasets en el entorno de ejecución antes de inicializar el código de carga de datos en pandas. Los filtros y segmentaciones vectorizadas se calcularán automáticamente respetando las dimensiones íntegras de la muestra.
