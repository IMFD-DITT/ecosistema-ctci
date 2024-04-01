# Capítulo II: Análisis y Caracterización de las actividades de Ciencia, Tecnología, Conocimiento e Innovación en Salud

## Descripción

Fuentes de información, códigos y base de datos con los que se realiza el análisis de las contribuciones del Ecosistema CTCI en el área de la Salud en Chile (Capítulo II del informe). El análisis se divide en 2 secciones:

- Análisis de publicaciones científicas
- Análisis de proyectos

La metodología adoptada, en ambas subsecciones, incorpora criterios definidos para la toma de decisiones, facilitando la replicabilidad del estudio en otras temáticas de interés.

## Estructura

Los archivos se agrupan en 2 carpetas principales que representan cada una de las secciones del análisis:

    .
    ├── Análisis de publicaciones científicas
    │   └── ... 
    │
    └── Análisis de proyectos
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

Cabe destacar que las imágenes de redes de coautoría de publicaciones científicas, presentes en el informe, no se encuentran en este repositorio. Esto debido a que fueron generadas a través de VOSviewer, y no por medio de códigos presentes en los notebooks. Sin embargo, si se encuentran dentro de _Análisis de publicaciones científicas/Datos_ los datos empleados para generar aquellas redes.

## Autores

Este trabajo fue llevado a cabo por personal del **Instituto Milenio Fundamentos de los Datos**, en su Dirección de Innovación y Transferencia Tecnológica, como parte del proyecto "Estudio del
Panorama General del Ecosistema de Ciencia, Tecnología, Conocimiento e Innovación en Chile", mandatado por el Consejo Nacional de Ciencia, Tecnología, Conocimiento e Innovación (Licitación ID 1098710-19-LE23).

