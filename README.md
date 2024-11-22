# Modelo SIR para el Análisis de la COVID-19 en Tokio

Este repositorio contiene la implementación del modelo SIR (Susceptibles, Infectados, Recuperados) aplicado al análisis de la propagación de la COVID-19 en Tokio, basado en datos reales. El objetivo principal es simular y analizar la dinámica de la epidemia utilizando métodos numéricos y herramientas matemáticas como el análisis de estabilidad mediante la matriz Jacobiana.

## Descripción

El modelo SIR es ampliamente utilizado para estudiar la propagación de enfermedades infecciosas. Este proyecto incluye:
- Preprocesamiento de datos reales obtenidos de Kaggle.
- Implementación del sistema de ecuaciones diferenciales del modelo SIR.
- Estimación de parámetros (\(\beta\) y \(\gamma\)) mediante ajuste de curvas con `SciPy`.
- Análisis de estabilidad utilizando la matriz Jacobiana y valores propios.
- Visualización de la evolución de infectados y recuperados en Tokio.

## Contenido del Repositorio

- `ModeloSIR.ipynb`: Implementación principal del modelo SIR y análisis de estabilidad.
- `data/`: Carpeta que contiene los datos utilizados para el análisis, incluyendo:
  - `covid_jpn_prefecture.csv`: Datos de COVID-19 por prefectura en Japón.
- `README.md`: Descripción del proyecto y cómo usarlo.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/foodwebdx/Modelo-SIR-compu-cientifica.git
   cd sir-covid19-tokyo
