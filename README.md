# 🎬 Análisis de Películas – The Movies Dataset (Kaggle)

## 📊 Descripción del Proyecto

Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) utilizando Python sobre el dataset **The Movies Dataset** disponible en Kaggle.

El objetivo es analizar:

- Tendencias temporales de películas en la plataforma
- Mejores películas en cuanto a calificaciones y popularidad
- Identificación de películas cuya reseña menciona "Mexic"
- Hallar el Top 10 de películas relacionadas con México mejor calificadas

---

## 📂 Dataset

Dataset original:

https://www.kaggle.com/datasets/ranjan2215d/the-movies-dataset

Contiene información sobre más de 9,000 películas, incluyendo:

- Título
- Fecha de lanzamiento
- Popularidad
- Calificación promedio (vote_average)
- Número de votos
- Resumen (overview)

---

## 🛠️ Tecnologías Utilizadas

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🧹 Proceso de Limpieza de Datos

Durante el análisis se realizaron las siguientes transformaciones:

- Conversión de `release_date` a formato datetime
- Creación de la variable `year`
- Análisis de valores nulos en variables
- Conversión de columnas numéricas cuando fue necesario

---

## 📈 Análisis Realizado

### 1️⃣ Exploración General
- Revisión de estructura del dataset (`info`, `describe`)

![DESCRIBE](https://github.com/user-attachments/assets/9af6a61e-86b7-49b1-8367-782b16b16f32)

- Identificación de valores faltantes

### 2️⃣ Análisis de Popularidad y Rating

![vote_average](https://github.com/user-attachments/assets/9b438992-b82c-410e-acfb-3b44a067229e)

- Top 10 películas por rating
  
- Top 10 películas por popularidad

![popularidad](https://github.com/user-attachments/assets/6ce82ab8-9f53-4e69-89b7-569f58dfe8af)

### 3️⃣ Análisis Temporal

![rating por ano](https://github.com/user-attachments/assets/1e0736a6-293b-4553-821a-fe8b0b47c97e)

- Promedio de rating por año
  
- Gráfico de correlación entre rating y década

![Rating por decada](https://github.com/user-attachments/assets/746122fd-53a9-4f2c-8657-eb4d65bd8ff6)


### 4️⃣ Caso de Estudio: México

![consulta mexico](https://github.com/user-attachments/assets/6952aa14-1779-43a8-9eef-ad495533317b)

- Filtrado de películas cuya reseña contiene "Mexic"
- Identificación del Top 10 mejor calificadas
- Visualización mediante gráfico de barras

![mexico top](https://github.com/user-attachments/assets/7a31bda5-da86-4196-9142-69d3abf31b5b)

---

## 🎯 Principales Hallazgos

Las películas Life is Beautiful y Cinema Paradiso son las mejores votadas de la plataforma mientras que Inside Out 2 y Despicable Me 4 tienen la mayor popularidad. Los ratings promedio por año son más altos para las películas más antiguas, mientras que las peores se encuentran entre los años 2010-2015 aproximadamente. El gráfico por décadas refuerza la idea de que las películas en la plataforma de los años 1920-1960, si bien no son muchas, tienen una gran calidad. Además se ve que al menos 82 películas tienen relación con México o los mexicanos, siendo Radical y Out of the Clear Blue Sky las mejor valoradas entre ellas.

---

## 👤 Autor

José Serrano  

