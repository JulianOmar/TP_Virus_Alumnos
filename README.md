# Examen Práctico - Predicción de Virus

Este proyecto consiste en desarrollar un modelo de clasificación para predecir la presencia de un virus en pacientes internados en un hospital. Los datos utilizados provienen de un archivo llamado `TP_Virus_Alumnos.csv`, que contiene variables relacionadas con las condiciones de los pacientes, tales como datos generales (edad, peso, altura, condición laboral) y mediciones específicas como análisis de sangre (BLD), hormonales (LVL) y otros análisis reactivos (REC).

## Objetivo del Proyecto

El objetivo principal es construir un modelo que prediga con la mayor precisión posible si un paciente presenta el virus (clase 1). Dado que el tratamiento es invasivo y la gravedad del virus es moderada, es fundamental maximizar la detección de casos positivos (clase 1) y minimizar los falsos positivos, para evitar tratar innecesariamente a personas que no tienen el virus.

## Estructura del Proyecto

1. **Preprocesamiento de Datos**: Realización de transformaciones y limpiezas necesarias para preparar los datos para el modelado.
2. **Exploración de Modelos**: Evaluación de distintos modelos de clasificación para seleccionar el que mejor se ajuste al problema.
3. **Métricas de Evaluación**: Dado el tipo de problema, se da prioridad a maximizar la métrica de recall para atrapar la mayor cantidad de positivos posibles, y minimizar los falsos positivos.
4. **Validación Cruzada**: Aplicación de técnicas de validación cruzada para asegurar la robustez del modelo y evitar errores comunes como fuga de datos o sesgo de selección.

## Cómo Ejecutar el Proyecto

1. Descargue el archivo del dataset `TP_Virus_Alumnos.csv`.
2. Ejecute el notebook para preprocesar los datos y entrenar el modelo.
3. El modelo final puede ser evaluado utilizando un conjunto de datos de prueba para medir su rendimiento.

## Evaluación del Proyecto

- **Calidad de la clasificación**: Basada en las métricas de rendimiento del modelo.
- **Fundamentación**: Explicación clara de los pasos y transformaciones realizadas.
- **Facilidad de Producción**: El modelo debe ser fácilmente adaptable a un entorno de producción.

###

* Tecnologías Usadas: Python,Scikit-Learn, 
* Librerias de visualizacion: Matplotlib, Seaborn, Pandas
