# Proyecto de Análisis de Datos: Mejora de la Seguridad en la Aviación

## Introducción

Este proyecto de análisis de datos tiene como objetivo principal abordar la problemática de la seguridad en la industria de la aviación, específicamente la prevención de accidentes aéreos. Los accidentes aéreos son eventos imprevistos y altamente indeseados que pueden resultar en daños tanto aeronáuticos como humanos, y su prevención es esencial para la seguridad de los pasajeros y la integridad de las aeronaves.

En este contexto, la Organización de Aviación Civil Internacional (OACI), un organismo de la Organización de las Naciones Unidas, ha iniciado este proyecto en colaboración con una consultora de datos. El objetivo es analizar en profundidad los accidentes aéreos que han ocurrido desde el inicio del siglo XX. Para lograr esto, se utilizará un conjunto de datos sobre accidentes de aviones, y se buscará cruzar esta información con otras fuentes relevantes para obtener una visión más completa de los factores que contribuyen a los accidentes.

Los entregables clave de este proyecto incluyen:

## Reporte de Análisis Exploratorio de Datos (EDA)

### Resumen de Datos

- El dataset contiene información sobre accidentes aéreos.
- Consta de 5008 filas y diversas columnas.
- Se han realizado múltiples transformaciones y limpieza de datos para mejorar su calidad.

### Resumen de las Transformaciones y Limpieza de Datos

- Se han cambiado los nombres de las columnas a minúsculas y sin espacios.
- Se han identificado valores faltantes y se han reemplazado con NaN en varias columnas.
- Se han corregido datos erróneos, como sustituir '?' por 0 en columnas relevantes.
- Se han modificado los formatos de fecha y hora.
- Se ha categorizado la columna 'route' en 'commercial' y 'no_category'.
- Se ha categorizado 'ac_type' en categorías adecuadas.
- Se ha asignado una categoría a 'operador' en función de patrones de búsqueda.
- Se ha realizado una exploración de valores faltantes en varias columnas.

### Exploración de Datos

- La exploración de datos incluye el análisis de la frecuencia de las categorías de vuelo.
- Se ha creado una visualización de accidentes aéreos por década.
- Se ha generado un gráfico que muestra el total de accidentes por tipo de vuelo.
- También se ha producido un gráfico que muestra el total de accidentes por operador, filtrando aquellos con más de 10 accidentes registrados.

### Conclusión

- El dataset ha sido sometido a un proceso de limpieza y transformación de datos que ha mejorado su calidad y utilidad.
- Se ha realizado una exploración inicial de los datos, lo que proporciona una comprensión básica de las categorías de vuelo, los operadores y la evolución de los accidentes aéreos a lo largo de las décadas.
- Estos resultados pueden servir como punto de partida para análisis más detallados y específicos relacionados con la seguridad y las tendencias de accidentes aéreos.

## Dashboard Interactivo

Se desarrollará un dashboard interactivo que permitirá explorar los datos de accidentes aéreos de manera detallada. Este dashboard incluirá filtros que facilitarán la selección de datos específicos para un análisis más profundo.

## Análisis y Conclusiones

Se realizarán análisis en profundidad utilizando los datos y visualizaciones disponibles en el dashboard. Se buscará comprender las causas y tendencias de los accidentes aéreos y se propondrán medidas para mejorar la seguridad en la aviación.

## Indicadores Clave de Desempeño (KPIs)

### KPI 1
La disminución de un 10% en la tasa de fatalidad de la tripulación en los últimos 10 años, en comparación con la década anterior, tendrá un impacto significativo en la seguridad de la industria de la aviación.

### KPI 2
Existe una relación significativa entre las diferentes categorías de accidentes aéreos que puede ayudar a determinar una disminución de accidentes en la última década en comparación con la década anterior.

**Este proyecto busca contribuir significativamente a la seguridad en la aviación al proporcionar información valiosa y análisis detallados que puedan guiar a la OACI y otras partes interesadas en la toma de decisiones informadas para prevenir accidentes aéreos en el futuro.**