# TELCOMX_1
Proyecto: Análisis de Evasión de Clientes (Churn) – TelecomX

Descripción:
Este proyecto analiza los factores que influyen en la evasión de clientes (Churn) de la empresa TelecomX. Se realiza un análisis exploratorio de datos para identificar patrones de comportamiento y características asociadas al abandono del servicio, con el objetivo de mejorar la retención de clientes y orientar acciones estratégicas.

Objetivos:

Comprender la distribución de Churn entre los clientes.

Analizar cómo variables categóricas (contrato, método de pago, servicios) afectan la evasión.

Explorar la relación de variables numéricas (gasto mensual, total gastado, tiempo como cliente) con Churn.

Proporcionar insights y recomendaciones estratégicas basadas en datos.

Estructura del proyecto:

notebook_churn.ipynb: Notebook principal con análisis y visualizaciones.

TelecomX_Data.json: Dataset original descargado desde la API.

README.txt: Este archivo.

requirements.txt: Dependencias necesarias para ejecutar el proyecto.

Instalación y requisitos:
Se recomienda crear un entorno virtual e instalar las dependencias necesarias. Dependencias principales: pandas, numpy, matplotlib, seaborn, jupyter.

Uso del proyecto:

Abrir notebook_churn.ipynb en Jupyter o Colab.

Cargar los datos desde el archivo JSON o directamente desde la API.

Ejecutar las celdas paso a paso: limpieza de datos, análisis exploratorio y visualizaciones.

Revisar conclusiones y recomendaciones al final del notebook.

Contenido del análisis:

Limpieza y tratamiento de datos: conversión de tipos, manejo de valores nulos, renombrado de columnas y estandarización de categorías.

Análisis exploratorio: distribución de Churn, relación con variables categóricas y numéricas.

Conclusiones e insights: factores que influyen en la evasión de clientes.

Recomendaciones: estrategias para mejorar la retención.

Problemas y soluciones comunes:

Asegurarse de convertir Churn a valores numéricos (0/1) antes de cálculos estadísticos.

Valores no numéricos en columnas de gasto deben convertirse a numérico y rellenarse NaN con la mediana.

Normalizar strings en columnas categóricas para evitar inconsistencias al agrupar.

Autor: Diego Roberto Montero
Fecha: 2025
