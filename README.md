# 🐍 Curso: Análisis de Datos con Python (Pandas, NumPy y Matplotlib)

> **Certificación completada:** Octubre de 2025
> **Instructor:** [Federico Garay](https://www.udemy.com/user/federicogaray/)  
> **Plataforma:** Udemy  
> **Duración total:** 1.5 horas  
> **Idioma:** Español  
> **Calificación del curso:** ★★★★☆ (4.5 / 5)  

---

## 📊 Descripción general

Este curso me permitió desarrollar habilidades prácticas en **análisis de datos con Python**, utilizando tres de las bibliotecas más potentes y demandadas en el entorno profesional:

- **Pandas** → manipulación y análisis de datos tabulares (DataFrames y Series)  
- **NumPy** → cálculos numéricos y vectorización eficiente  
- **Matplotlib** → visualización de datos mediante gráficos simples y personalizados  

A través de ejercicios guiados y proyectos prácticos, aprendí a **leer, limpiar, transformar, agrupar y visualizar** datos de manera efectiva y profesional.

---

## 🎯 Objetivos de aprendizaje alcanzados

- Comprender los conceptos básicos del **análisis de datos con Python**.  
- Utilizar **Pandas** para manipular y procesar grandes volúmenes de información.  
- Entender el funcionamiento de **DataFrames, indexación, ordenamiento y agrupaciones (`groupby`)**.  
- Crear **gráficos simples** con Matplotlib para representar tendencias y distribuciones.  
- Trabajar con **NumPy** para cálculos vectorizados y manejo de estructuras multidimensionales.  
- Aplicar técnicas de **limpieza de datos** y **análisis exploratorio** (EDA).  

---

## 🧠 Tecnologías utilizadas

| Herramienta | Descripción |
|--------------|-------------|
| **Python 3** | Lenguaje principal para análisis de datos |
| **Pandas** | Manipulación y análisis eficiente de datos estructurados |
| **NumPy** | Cálculo científico y operaciones vectorizadas |
| **Matplotlib** | Generación de gráficos y visualizaciones básicas |
| **Jupyter Notebook / Google Colab** | Entorno interactivo de desarrollo |

---

## 📚 Ejemplo de código trabajado

```python
import pandas as pd
import matplotlib.pyplot as plt

# Cargar datos
tabla = pd.read_csv('VentasPorProveedor.csv', sep=';')
tabla['Ganancia'] = tabla['Ganancia'].str.replace(',', '.').astype(float)

# Filtrar categoría
alimentos = tabla[tabla['Categoría'] == 'Comestibles']

# Visualizar
alimentos['Artículo'].value_counts().plot(kind='bar', figsize=(10,5))
plt.title('Artículos comestibles más vendidos')
plt.xlabel('Artículo')
plt.ylabel('Cantidad')
plt.show()

```
## 👨‍🏫 Instructor

Federico Garay
Instructor Best-Seller en Udemy, con más de 400.000 estudiantes y más de 50 cursos publicados.
Apasionado por enseñar, aprender y compartir conocimientos sobre programación, análisis de datos y productividad digital.

## 🏁 Resultados obtenidos
✔ Manejo fluido de la biblioteca Pandas.

✔ Capacidad para realizar análisis de datos y visualizaciones básicas.

✔ Comprensión sólida del flujo de trabajo analítico con Python.

✔ Mejora de la eficiencia en la manipulación y exploración de datasets.


💬 Reflexión personal

Este curso me ha permitido reforzar mis fundamentos en análisis de datos con Python, mejorando mi capacidad para procesar, visualizar y comprender información estructurada.
La combinación de teoría y práctica fue clave para afianzar conceptos como indexación, limpieza de datos y creación de gráficos.
