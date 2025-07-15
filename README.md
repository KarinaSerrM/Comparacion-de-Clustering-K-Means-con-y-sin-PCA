# Comparación de Clustering K-Means con y sin PCA

Este repositorio contiene un proyecto de machine learning no supervisado que explora técnicas de agrupamiento mediante el algoritmo K-Means. Se analizan los resultados aplicando el algoritmo tanto sobre los datos originales como sobre datos transformados con Análisis de Componentes Principales (PCA).

## Objetivo

Evaluar y comparar los resultados del agrupamiento K-Means con y sin reducción de dimensionalidad para identificar patrones relevantes en los datos y mejorar la visualización de los grupos.

## Flujo de trabajo

### 1. Agrupamiento sin transformación
- Aplicación de K-Means directamente sobre los datos originales
- Identificación del número óptimo de clústeres mediante el método del codo
- Visualización de los grupos formados y análisis de relaciones entre variables

### 2. PCA y nuevo agrupamiento
- Transformación de datos con PCA
- Aplicación de K-Means sobre las componentes principales
- Repetición del proceso de selección de clústeres y visualización con dispersión en 2D

### 3. Comparación entre enfoques
- Evaluación de resultados obtenidos con ambos métodos
- Discusión sobre ventajas y limitaciones de usar PCA antes del clustering
- Interpretación del impacto en la visualización y la simplificación de datos

## Herramientas utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn

## Conclusiones

- K-Means sin transformación ofrece agrupamientos fieles pero menos visuales.
- PCA ayuda a representar los grupos de forma clara y mejora la interpretación gráfica.
- Ambos enfoques pueden complementarse dependiendo del objetivo del análisis.
- La combinación de clustering y PCA resulta útil para explorar datos con alta dimensionalidad.
