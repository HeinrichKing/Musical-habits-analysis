# Análisis de hábitos musicales entre ciudades

Este proyecto analiza datos reales de transmisión de música online para estudiar los hábitos de escucha de usuarios y usuarias en dos ciudades ficticias: Springfield y Shelbyville.

## 🎯 Objetivo del proyecto

El propósito es explorar, limpiar y analizar datos para identificar patrones de comportamiento según la ciudad y el día de la semana. Para ello, se divide el trabajo en distintas etapas que permiten estructurar el análisis paso a paso y sacar conclusiones sólidas.

## 📁 Estructura del proyecto

### 🔹 Etapa 1: Descripción de los datos  
Se realiza una primera exploración del conjunto de datos, identificando su estructura, características principales y posibles problemas.

### 🔹 Etapa 2: Preprocesamiento de los datos  
Se limpia el dataset corrigiendo nombres de columnas, eliminando duplicados y gestionando valores ausentes.

### 🔹 Etapa 3: Análisis  
Se evalúan las diferencias de comportamiento entre usuarios/as de ambas ciudades y cómo varía su actividad dependiendo del día de la semana.

### 🔹 Conclusiones  
Se resumen los hallazgos más relevantes y se proponen interpretaciones basadas en el análisis.

## 📊 Diccionario de datos

El archivo de datos es: `/datasets/music_project_en.csv`. Las columnas que contiene son:

- `userID`: Identificador único de usuario/a.  
- `Track`: Nombre de la canción.  
- `artist`: Nombre del artista.  
- `genre`: Género musical.  
- `City`: Ciudad del usuario/a.  
- `time`: Hora en que se reprodujo la pista (HH:MM:SS).  
- `Day`: Día de la semana.

---

🔍 Proyecto realizado como parte de un curso de análisis de datos.  
💻 Herramientas utilizadas: Python, Pandas, Jupyter Notebook.
