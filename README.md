# Taller de Programación Orientada a Objetos

## Integrantes

- Guillermo Andrés Minero Alfaro
- Gabriela Isabel Castillo Mena
- Ruben Armando Vigil Mejia

## Descripción

Actividad práctica donde construimos un pequeño pipeline de datos usando Programación Orientada a Objetos en Python.

## Objetivo

Construir un pipeline de datos aplicando abstracción, herencia, encapsulamiento, mixins y polimorfismo.

## Requisitos

- Python 3
- Pandas
- Matplotlib
- Google Colab o Jupyter Notebook

## Uso

1. Abrir `main.ipynb` en Google Colab o Jupyter Notebook.
2. Subir el archivo `exercises.csv` al entorno de ejecución.
3. Ajustar `file_path` si es necesario.
4. Ejecutar las celdas en orden.

## Fases

1. Arquitectura base y mixins
2. Ingesta y transformación de datos
3. Análisis y orquestación del pipeline

## Flujo del pipeline

1. `DataLoader` carga el archivo CSV y valida las columnas requeridas.
2. `DataCleaner` limpia los datos, convierte tipos e imputa valores faltantes.
3. `DataAnalyst` genera reportes por consola, gráficos o ambos.

## Componentes principales

- `DataComponent`: clase abstracta base.
- `ValidatorMixin`: validación de archivos y columnas.
- `LoggerMixin`: seguimiento de mensajes en consola.
- `DataLoader`: carga de datos desde CSV.
- `DataCleaner`: limpieza y transformación de datos.
- `DataAnalyst`: análisis y generación de reportes.
