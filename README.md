**Predicción de fibrosis hepática en pacientes con insuficiencia cardíaca mediante inteligencia artificial utilizando variables clínicas y el FibroScan como referencia diagnóstica.**

**Descripción:**

Este repositorio contiene el código fuente desarrollado para el Trabajo de Fin de Máster (TFM) titulado "Predicción de fibrosis hepática en pacientes con insuficiencia cardíaca mediante inteligencia artificial utilizando variables clínicas y el FibroScan como referencia diagnóstica".

El objetivo principal de este proyecto es desarrollar un sistema basado en Machine Learning capaz de predecir la fibrosis hepática en pacientes con insuficiencia cardíaca, especialmente en escenarios donde el acceso a herramientas de diagnóstico como el FibroScan es limitado. Para ello, se utilizan variables clínicas relevantes, complementadas con las mediciones del FibroScan como referencia diagnóstica.

**Metodología:**

El desarrollo de los modelos de Machine Learning siguió un enfoque iterativo y adaptativo:

**Clasificación Multiclase Inicial:** Se exploró inicialmente un modelo de Gradient Boosting para la clasificación multiclase de los diferentes grados de fibrosis.

**Transición a Clasificación Binaria:** Debido al desbalance de datos y la complejidad inherente a los grados intermedios de fibrosis, se optó por un enfoque de clasificación binaria utilizando un segundo modelo de Gradient Boosting. Este cambio permitió optimizar el rendimiento de los modelos, priorizando métricas como la sensibilidad para una detección temprana de la enfermedad.

**Análisis de Importancia de Variables:** Se obtuvieron las variables más importantes del modelo de Gradient Boosting binario.

**Modelo de Regresión Logística:** Con las variables de mayor importancia identificadas, se entrenó un modelo de Regresión Logística. Este enfoque busca mejorar la interpretabilidad del modelo y validar la relevancia clínica de los predictores identificados.
