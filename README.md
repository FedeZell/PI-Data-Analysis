# <h1 align="center">**`Siniestros Viales de la Ciudad Autónoma de Buenos Aires`**</h1>

<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 500>

## Introducción
Para este proyecto se me encomendó la tarea de llevar a cabo el rol de `Data Analyst` en relación al Observatorio de Movilidad y Seguridad Vial (OMSV) de la Ciudad Autónoma de Buenos Aires (CABA) con el objetivo de recopilar y sintetizar información que le permita al gobierno locales tomar medidas para disminuir la cantidad de víctimas fatales de los accidentes viales, para lo cual se me proporcionó unos datasets que registran los siniestros ocurridos en CABA durante el lapso de 2016 a 2021.

## Fuente de datos
Para este proyecto se me facilitó el archivo [homicidios](https://docs.google.com/spreadsheets/d/1nq00jGIZHQ1RLSET43zKnUsMsoFb-pBg/edit#gid=1625530738) que contiene dos hojas (HECHOS y Víctimas), con información relevante de los siniestros, y un [diccionario](https://docs.google.com/spreadsheets/d/1Op98U-Hh2a3Q7uuznAzdl4Bf8r8qPr4m/edit#gid=1771770012), que describe las categorías presentes en el dataset, ambos archivos en formato xlxs.

## Extracción, Transformación y Carga de Datos (ETL)
Como fase inicial del proyecto se lleva a cabo un proceso de rigurosa limpieza de los datos para preparalos para su posterior análisis. Se llevaron a cabo procedimientos como imputación de valores faltantes, estandarizacón de los datos, eliminación de valores duplicados, entre otros.

## Análisis Exploratorio de Datos (EDA)
En esta fase se realizó una exhaustiva con el objetivo de vislumbrar patrones y generar información valiosa para la devolución. Entre los procesos realizados se destacan la elaboración de gráficos para hacer comparaciones entre distintos tipos de variables.

## Herramientas
Para este proyecto se utilizó `Power BI Desktop` para crear el dashboard interactivo. A su vez, para la tarea de limpieza y análisis se utilizó `Python` y varias de sus librerías, entre ellas `Pandas`, para llevar adelante el proceso de ETL, y `Matplotlib` y `Seaborn`, para desarrollar las visualizaciones a lo largo del EDA.

## Referencias
- [Data](https://github.com/FedeZell/PI-Data-Analysis/tree/main/Data)
- [Notebooks](https://github.com/FedeZell/PI-Data-Analysis/tree/main/Notebooks)
- [Dashboard](https://github.com/FedeZell/PI-Data-Analysis/blob/main/Siniestros%20Viales.pbix)

# Autor
- Federico Germán Zellweger Semino
- E-mail: fedezell97@gmail.com
