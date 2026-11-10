# Clasificación de imágenes de vocales manuscritas mediante aprendizaje supervisado

Proyecto final de la asignatura **Inteligencia Artificial**, desarrollado en la Universidad del Magdalena durante el periodo **2026-II**.

## Integrantes

- Izquierdo Camargo David Elías — Código: 2023214087
- Martínez Monsalvo Luis Jaime — Código: 2023214025
- Sierra Zapata Angelica — Código: 2023214030

## Descripción

El proyecto aborda la clasificación automática de imágenes de vocales manuscritas: **A, E, I, O y U**. Se entrenaron y compararon distintos modelos de aprendizaje supervisado para determinar cuál ofrecía el mejor desempeño sobre el conjunto de prueba.

## Modelos evaluados

- Random Forest
- Árbol de decisión
- Perceptrón multicapa (MLP)
- Regresión logística multiclase (Softmax)
- Red neuronal convolucional (CNN)

## Conjunto de datos

Se utilizaron imágenes pertenecientes al conjunto de datos:

[Handwriting Letter and Number Dataset — Kaggle](https://www.kaggle.com/datasets/straighttoheaven/handwriting-letter-and-number-dataset)

## Resultados principales

| Modelo | Exactitud en prueba |
|---|---:|
| Red neuronal convolucional (CNN) | 99,90 % |
| Regresión logística multiclase (Softmax) | 99,80 % |
| Perceptrón multicapa (MLP) | 99,70 % |
| Random Forest | 99,61 % |
| Árbol de decisión | 96,25 % |

La **CNN** obtuvo la exactitud más alta en el conjunto de prueba. El notebook también documenta el procesamiento de las imágenes, la optimización de hiperparámetros, las matrices de confusión y el análisis de los resultados.

## Notebook del proyecto

[Ver el notebook completo](./Clasificacion_Vocales_Manuscritas_Aprendizaje_Supervisado.ipynb)
