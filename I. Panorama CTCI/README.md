# Capítulo I: Panorama del Ecosistema de Ciencia, Tecnología, Conocimiento e Innovación en Chile de los últimos 10 años

## Descripción

Fuentes de información, códigos y base de datos con los que se realiza el análisis sobre el Ecosistema CTCI en Chile durante los últimos 10 años. El análisis se divide en 5 secciones:

- Contexto nacional
- Estructura
- Estructura - Relaciones entre actores
- Funcionamiento
- Desempeño

## Estructura

Los archivos se agrupan en 5 carpetas principales que representan cada una de las secciones del análisis:

    .
    ├── Contexto nacional
    │   └── ... 
    ├── Estructura              
    │   └── ... 
    ├── Estructura - Relaciones entre actores
    │   └── ... 
    ├── Funcionamiento
    │   └── ... 
    └── Desempeño
        └── ... 

Dentro de cada carpeta se encontrarán 3 subcarpetas:

    .
    ├── ...
    │    ├── Datos
    │    │
    │    ├── Notebooks
    │    │
    │    └── Gráficos
    ... 

donde **Datos** contiene archivos de bases de datos utilizadas en los notebooks, **Notebooks** contiene los archivos _.ipynb_ contenedores de los códigos empleados para manipular los datos y generar imágenes, y **Gráficos** contiene las imágenes generadas a través de los notebooks. Es de relevancia destacar que los gráficos generados se encuentran tanto en formato _.png_ así como _.svg_, lo cual garantiza una buena resolución de las imágenes.

Por otro lado, se encuentran 2 archivos de tipo _.xlsx_ (hojas de cálculo). Estos son:

- _Listado\_indicadores\_Ecosistema\_CTCI.xlsx_: Contiene el glosario utilizado, así como también todas y cada una de las secciones que son abordadas en el Capítulo I del informe. Dentro de cada sección también son nombrados los indicadores analizados. La revisión de estas hojas de cálculo sirve como guía para explorar esta sección del repositorio, así como también el Capítulo I del informe.

- _Bases\_de\_Datos\_Estudio\_CTCI.xlsx_: Contiene el listado de los instrumentos CTCI, los ITPs, y las incubadoras, aceleradoras y Hubs considerados en este estudio.
