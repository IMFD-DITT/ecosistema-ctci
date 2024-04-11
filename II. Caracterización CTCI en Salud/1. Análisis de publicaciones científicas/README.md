# Análisis de publicaciones científicas

En esta carpeta, se encuentra el código y los datos empleados para el análisis de publicaciones científicas referentes a la temática *Salud*.

## Fuente

Los datos considerados, corresponden a los artículos disponibles en la base de datos OpenAlex. Cada base de datos usada es entregada por OpenAlex por medio del siguiente enlace base:
`'https://api.openalex.org/works?filter=concepts.wikidata:{CONCEPTS},institutions.country_code:cl,from_publication_date:{FROM_DATE},to_publication_data:{TO_DATE},type:article&cursor={PAGE}'`
donde
- CONCEPTS: concepto o conceptos a buscar en los artículos
- FROM_DATA: fecha desde donde se consideran artículos
- TO_DATA: fecha hasta donde se consideran artículos
- PAGE: corresponde a la página de resultados

## Notebook
El notebook _Análisis\_publicaciones.ipynb_ está estructurado en 4 secciones principales, cuyos nombres aluden a la temática de las publicaciones que se analizan,
- _MEDICINE_
- _CANCER_
- _DIABETES_
- _CARDIOVASCULAR DISEASE_

en cada sección se realiza una petición a OpenAlex para obtener los datos solicitados, según los parámetros definidos y los conceptos a buscar.

Luego se realizan diferentes análisis, tanto como el conteo de la cantidad de artículos publicados por año relacionados al tema específico, así como también el análisis de las keywords más frecuentes, y el conteo del tipo de instituciones involucradas en las publicaciones.

Y finalmente tiene una sección denominada _GENERAL_, en la cual se realiza un conteo de las publicaciones totales para cada temática analizada.