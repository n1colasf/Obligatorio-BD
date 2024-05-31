# Obligatorio BIG DATA

### Universidad ORT Uruguay

<hr>

### Certificado de Big Data - Analista TI

## Análisis de datos de la ciudad de Barcelona

#### Gerónimo de Lisa - Nicolas Fernandez

### **Julio 2024**

<hr>

### Introducción

[Ver Letra](/Letra%20Obligatorio.pdf)

En este trabajo se analizarán los datos de la ciudad de Barcelona de acuerdo a los objetivos propuestos en el trabajo.

<br />
<hr>

### Objetivos

Para el obligatorio se deberán utilizar las herramientas utilizadas en el curso. Deberá seleccionar un conjunto de datos
tabulares con más de 4 tablas y deberá seleccionar 8 preguntas relativas a los datos para contestarlas.

<br />
<hr>

### Desarrollo

**Parte 1**

Los pasos a seguir son:

- Tomar los datos que fueron seleccionados junto al docente.
- Realizar un análisis exploratorio de los datos vía pandas, identificando el tipo de datos que hay en cada columna y
  que significado tienen dentro del dominio de los datos
- Revisar valores nulos o faltantes y limpiarlos si es necesario. Revisar registros duplicados. Claves primarias únicas.
- Los archivos resultantes se deberán almacenar en otra carpeta.
- A partir de estos nuevos archivos, se deben crear visualizaciones dentro de otro
  notebook con las herramientas dadas en clase u otras de elección del equipo, que ayuden a responder las preguntas
  seleccionadas.

**Parte 2**

El mismo análisis realizado en la parte 1 realizarlo vía Spark, ya sea dentro de la máquina virtual si se tienen
créditos si no dentro de Google Collab.

**Parte 3**

Se píde desarrollar un dashboard que responda algunas de las preguntas planteadas, implementado en Tableau Public o
superset.

**Parte 4**

Una vez que termine con la exploración y limpieza de datos, deberá elegir una forma de modelarlos, esta puede ser,
Normalizada, Diagrama Estrella, Data Vault, o OBT. Describir en
Hive, como lo modelaría, que tablas crearía y de que tipo (externas, internas).

<br />
<hr>

### Datos

A continuación se muestra una tabla con los 17 datasets utilizados en el análisis de datos de la ciudad de Barcelona,
junto con su nombre y enlace a su ubicación:

| Nombre del dataset                    | Enlace                                                          | Dataset limpiado                            |
|---------------------------------------|-----------------------------------------------------------------|---------------------------------------------|
| Accidents 2017                        | [Enlace 1](/datasets/accidents_2017.csv)                        | [Nuevo 1](/new_datasets/accidents_2017.csv) |
| Air quality Nov2017                   | [Enlace 2](/datasets/air_quality_Nov2017.csv)                   |                                             |
| Air stations Nov2017                  | [Enlace 3](/datasets/air_stations_Nov2017.csv)                  |                                             |
| Births                                | [Enlace 4](/datasets/births.csv)                                |                                             |
| Bus stops                             | [Enlace 5](/datasets/bus_stops.csv)                             |                                             |
| Deaths                                | [Enlace 6](/datasets/deaths.csv)                                |                                             |
| Immigrants by nationality             | [Enlace 7](/datasets/immigrants_by_nationality.csv)             |                                             |
| Immigrants emigrants by age           | [Enlace 8](/datasets/immigrants_emigrants_by_age.csv)           |                                             |
| Immigrants emigrants by destination   | [Enlace 9](/datasets/immigrants_emigrants_by_destination.csv)   |                                             |
| Immigrants emigrants by destination 2 | [Enlace 10](/datasets/immigrants_emigrants_by_destination2.csv) |                                             |
| Immigrants emigrants by sex           | [Enlace 11](/datasets/immigrants_emigrants_by_sex.csv)          |                                             |
| Life expectancy                       | [Enlace 12](/datasets/life_expectancy.csv)                      |                                             |
| Most frequent baby names              | [Enlace 13](/datasets/most_frequent_baby_names.csv)             |                                             |
| Most frequent names                   | [Enlace 14](/datasets/most_frequent_names.csv)                  |                                             |
| Population                            | [Enlace 15](/datasets/population.csv)                           |                                             |
| Transports                            | [Enlace 16](/datasets/transports.csv)                           |                                             |
| Unemployment                          | [Enlace 17](/datasets/unemployment.csv)                         |                                             |

<br />
<hr>

### Preguntas

1.
2.
3.
4.
5.
6.
7.
8.

<br />
<hr>

### Análisis

**Parte 1**

[Ver Notebook de Análisis de Datos](/analisis/parte1a_analisis_datos.ipynb)

[Ver Notebook de Respuestas a Preguntas](/analisis/parte1b_analisis_preguntas.ipynb)

**Parte 2**

[Ver Notebook de Análisis con Spark](/analisis/Parte%202.ipynb)

**Parte 3**

[Ver Dashboard](https://ubicacion_dashboard)

**Parte 4**

[Ver Diagrama](/analisis/Parte%204.png)

<br />
<hr>

### Conclusiones

En este trabajo se analizaron los datos de la ciudad de Barcelona, se realizaron visualizaciones y se respondieron
preguntas planteadas. Se utilizó tanto Python con Pandas como Spark para el análisis de los datos. Se creó un dashboard
en Tableau Public y se modelaron los datos en Hive.

Se puede concluir que...
