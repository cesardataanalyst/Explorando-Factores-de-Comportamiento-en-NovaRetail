# NovaRetail+ | Análisis del Comportamiento de los Clientes

🇺🇸 English | 🇪🇸 [Versión en Español](README_ES.md)

---

# 📊 NovaRetail+ | Análisis del Comportamiento de los Clientes 

## 📌 Contexto y problema de negocio

NovaRetail+ busca comprender mejor el comportamiento de sus clientes y los factores que pueden estar relacionados con los ingresos anuales generados por cada cliente.
Desde una perspectiva de negocio, comprender estas relaciones permite identificar patrones de comportamiento que pueden ser relevantes para áreas como **marketing, retención de clientes y crecimiento de ingresos**.
Este proyecto utiliza técnicas de análisis exploratorio y análisis de correlación para estudiar la relación entre diferentes variables de comportamiento de los clientes y sus ingresos anuales.
**Importante**: el análisis identifica asociaciones entre variables. Estas asociaciones no implican necesariamente una relación causal.

---
## 🎯 Objetivo del análisis
El objetivo principal es identificar qué **factores del comportamiento de los clientes presentan una mayor asociación con los ingresos anuales**.

## Preguntas de análisis
El proyecto busca responder las siguientes preguntas:
- ¿Qué variables presentan una mayor relación con los ingresos anuales?
- ¿Existe una relación entre la frecuencia de compra y los ingresos anuales?
- ¿Cómo se relacionan las visitas mensuales con los ingresos?
- ¿Qué relación presenta el gasto en publicidad con los ingresos generados?
- ¿Qué asociación existe entre la membresía Premium y los ingresos anuales?
- ¿Qué relación presenta el churn con los ingresos?
- ¿Qué patrones de comportamiento pueden ser relevantes para las decisiones de negocio?

## 📊 Origen de los datos
El análisis utiliza un dataset de comportamiento de clientes:
* novaretail_comportamiento_clientes_2024.csv
El dataset contiene información relacionada con diferentes características y comportamientos de los clientes durante el periodo analizado.
La información se utiliza para estudiar las relaciones entre variables de comportamiento y el ingreso anual de los clientes.

## 🛠️ Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## 🔎 Metodología
El análisis se desarrolló mediante un proceso de exploración, preparación, visualización y análisis estadístico.
### 1. Carga y exploración inicial
Se realizó una revisión inicial del dataset para comprender:
- Estructura de los datos.
- Variables disponibles.
- Tipos de datos.
- Características generales de la información.

### 2. Preparación y validación de datos
Se revisó la calidad de los datos antes de realizar el análisis, incluyendo la validación de las variables utilizadas y su preparación para las diferentes técnicas estadísticas.

### 3. Análisis exploratorio
Se utilizaron estadísticas descriptivas y visualizaciones para comprender la distribución y el comportamiento de las principales variables.

### 4. Análisis de correlación
Se aplicaron diferentes técnicas de asociación dependiendo del tipo de variables analizadas:
- Pearson: para analizar relaciones lineales entre variables numéricas.
- Spearman: para evaluar relaciones monotónicas.
- Point-biserial: para analizar la asociación entre una variable binaria y una variable numérica.
- Cramér's V: para analizar la asociación entre variables categóricas.

### 5. Interpretación de resultados
Los resultados de las diferentes técnicas fueron comparados e interpretados desde una perspectiva de negocio, buscando identificar qué variables presentan asociaciones relevantes con el ingreso anual.

## Estructura del Proyecto

NovaRetail/
│
├── datasets/
│   └── novaretail_comportamiento_clientes_2024.csv
│
├── S8 Student Version-Project-NovaRetail.ipynb
│
├── README.md
│
└── images/
    ├── heatmap.png
    ├── scatterplot1.png
    └── pairplot.png

--- 

## 📈 Principales resultados
El análisis permitió identificar diferentes niveles de asociación entre las variables de comportamiento y el ingreso anual de los clientes.
- Las compras de los clientes por mes mostraron la relación positiva más fuerte con el ingreso anual.
  - Las visitas mensuales presentaron una asociación positiva moderada.
  - El gasto en publicidad mostró una relación positiva débil..
  - La membresía Premium y el abandono de clientes mostraron asociaciones relativamente débiles con los ingresos anuales.

## Mejoras futuras 
- Construir modelos predictivos para el ingreso anual.
- Incorporar segmentación adicional de clientes.
- Explorar las relaciones causales más allá del análisis de correlación.

### 🛒 Compras mensuales
La cantidad de compras realizadas por mes presentó la relación positiva más fuerte con los ingresos anuales dentro de las variables analizadas.
Este resultado indica que la frecuencia de compra es una variable relevante para comprender el comportamiento asociado con la generación de ingresos.

### 👀 Visitas mensuales
Las visitas mensuales mostraron una asociación positiva moderada con los ingresos anuales.
Esto permite observar una relación entre el nivel de interacción de los clientes con la plataforma y los ingresos registrados.

### 📢 Gasto en publicidad
El gasto en publicidad presentó una relación positiva débil con los ingresos anuales.
Este resultado debe interpretarse como una asociación observada en los datos y no como evidencia de que un mayor gasto publicitario cause directamente mayores ingresos.

### ⭐ Membresía Premium
La membresía Premium presentó una asociación relativamente débil con los ingresos anuales dentro del análisis realizado.

### 🔄 Churn
La variable de churn también presentó una asociación relativamente débil con los ingresos anuales.

## Contenido del Notebook
El análisis se desarrolla en las siguientes etapas:

1. Carga y exploración inicial de los datos.
2. Limpieza, preparación y validación del conjunto de datos.
3. Estadística descriptiva
4. Visualización exploratoria.
5. Análisis de correlación mediante:
   - Correlación de Pearson
   - Correlación de Spearman
   - Correlación Point-biserial
   - V de Cramér
6. Interpretación de resultados.
7. Conclusiones de negocio.
8. Limitaciones y propuestas de mejora.

---

## 📊 Gráficos e indicadores
El proyecto utiliza diferentes visualizaciones para facilitar la interpretación de los resultados, incluyendo:
- Distribuciones de las variables.
- Gráficos de relación entre variables.
- Visualizaciones de comportamiento de los clientes.
- Análisis de correlaciones.
- Comparaciones entre variables categóricas y numéricas.

Los principales indicadores utilizados corresponden a las medidas de asociación obtenidas mediante Pearson, Spearman, point-biserial y Cramér's V.

   ---
## 💡 Interpretación para el negocio
Los resultados muestran que las variables relacionadas con la actividad de compra y la interacción de los clientes son relevantes para comprender las diferencias observadas en los ingresos anuales.
En particular, la frecuencia de compras mensuales destaca dentro de las variables analizadas por presentar la asociación positiva más fuerte con el ingreso anual.
Las demás variables deben interpretarse considerando el nivel de asociación encontrado y el alcance del análisis.

## 🚀 Recomendaciones de negocio
A partir de los resultados obtenidos, se pueden plantear las siguientes líneas de acción para profundizar el análisis y apoyar decisiones:

1. Analizar la frecuencia de compra
Considerar la frecuencia de compra como una variable relevante para segmentar clientes y estudiar diferentes patrones de generación de ingresos.

2. Profundizar en el comportamiento de los clientes
Analizar conjuntamente frecuencia de compra, visitas y otras variables de comportamiento para identificar perfiles de clientes con patrones diferenciados.

3. Evaluar las estrategias de marketing
Utilizar el análisis de asociación entre gasto publicitario e ingresos como punto de partida para estudios más detallados sobre el desempeño de las inversiones en marketing.

4. Analizar la membresía Premium
Profundizar en el comportamiento de los clientes Premium y compararlo con otros segmentos para comprender mejor su relación con los ingresos.

5. Profundizar en churn
Analizar el comportamiento de los clientes que abandonan el servicio y estudiar otras variables que puedan contribuir a explicar la retención o pérdida de clientes.

6. Avanzar hacia modelos predictivos
Como siguiente etapa, el análisis puede ampliarse mediante modelos predictivos para estudiar qué variables permiten explicar o predecir mejor el ingreso anual.
Estas recomendaciones representan líneas de análisis derivadas de los resultados observados. No implican relaciones causales que no hayan sido demostradas en este proyecto.

## ⚠️ Limitaciones del análisis
Este proyecto se basa principalmente en análisis exploratorio y medidas de asociación.
Por lo tanto:
- Una correlación no demuestra causalidad.
- Una asociación débil no significa necesariamente que una variable carezca de importancia para el negocio.
- Los resultados dependen de las variables disponibles en el dataset.
- Para establecer relaciones causales sería necesario realizar análisis adicionales.
- Los modelos predictivos requieren una etapa adicional de modelado y validación.

## ▶️ Cómo reproducir el análisis
1.	Clonar o descargar el repositorio.
2.	Instalar las librerías necesarias:
pip install pandas numpy matplotlib seaborn scipy
3.	Colocar el dataset en la ruta correspondiente:
/datasets/novaretail_comportamiento_clientes_2024.csv
4.	Abrir el notebook:
S8 Student Version-Project-NovaRetail.ipynb
5.	Ejecutar el notebook de principio a fin.

---
  
