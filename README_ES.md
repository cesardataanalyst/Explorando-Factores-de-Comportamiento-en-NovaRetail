# NovaRetail+ | Análisis del Comportamiento de los Clientes

🇺🇸 English | 🇪🇸 [Versión en Español](README_ES.md)

---

# 📊 NovaRetail+ | Análisis del Comportamiento de los Clientes 

## Descripción del Proyecto 

Este proyecto analiza el comportamiento de los clientes de **NovaRetail+** para identificar qué variables presentan la mayor asociación con los ingresos anuales generados por cada cliente. 

A través de técnicas de **Análisis Exploratorio de Datos (EDA)** y distintos métodos de correlación, se estudian patrones de comportamiento que pueden servir como apoyo para la toma de decisiones en áreas como marketing, fidelización de clientes y crecimiento de ingresos. 
---
## Objetivo

Determinar cuáles variables del comportamiento del cliente presentan una mayor relación con el ingreso anual generado, utilizando diferentes medidas estadísticas de correlación para variables numéricas y categóricas.

## Estructura del Proyecto

```
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
```
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
8. ## Tecnologías Utilizadas

   - Python
   - Pandas
   - NumPy
   - Matplotlib
   - Seaborn
   - SciPy
   - Jupyter Notebook
   
   ---

   ## Principales Resultados
El análisis permitió identificar que:

- Las **compras mensuales** presentan la relación positiva más fuerte con el ingreso anual del cliente.
- Las **visitas mensuales** muestran una asociación positiva moderada.
- El **gasto en publicidad dirigida** presenta una asociación positiva débil.
- La **membresía premium** y el **abandono del cliente (churn)** muestran asociaciones relativamente bajas con el ingreso anual.

Estos resultados sugieren que la frecuencia de compra constituye el principal indicador relacionado con la generación de ingresos dentro del conjunto de datos analizado.

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio.

2. Instalar las librerias requeridas:

   ```
   bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
   3. Ubicar el conjunto de datos:
   ```
   6. /datasets/novaretail_comportamiento_clientes_2024.csv
    ```
   Abrir el notebook:
  ```
S8 Student Version-Project-NovaRetail.ipynb
```
5. Ejecutar todas las celdas.
---
9. ## Principales hallazgos
  - Las compras de los clientes por mes mostraron la relación positiva más fuerte con el ingreso anual.
  - Las visitas mensuales presentaron una asociación positiva moderada.
  - El gasto en publicidad mostró una relación positiva débil..
  - La membresía Premium y el abandono de clientes mostraron asociaciones relativamente débiles con los ingresos anuales.
---
  ## Mejoras futuras 
- Construir modelos predictivos para el ingreso anual.
- Incorporar segmentación adicional de clientes.
- Explorar las relaciones causales más allá del análisis de correlación.
