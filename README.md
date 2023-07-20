# Análisis y visualización de la evolución histórica del acceso a internet de los mercados y a nivel global.

## RESUMEN:
En el contexto de una empresa que ofrece servicios vinculados a redes móviles en cinco países se solicitó realizar un estudio sobre el acceso a internet en lineas de alta velocidad y por suscripcion a lineas moviles tanto a nivel comparativo de la situación actual como de la evolución historica en diferentes mercados puntuales y a nivel global.
El proyecto contaba con datos provenientes de distintas fuentes volcados a archivos Ms Excel a los cuales fue necesario aplicarles múltiples procesos de transformación. Una vez concluida la etapa de ETL los datos se vincularon a LookerStudio donde se realizo el informe para su entrega y visualización.
Las conclusiones mas destacadas fueron: 
- El crecimiento exponencial del acceso a internet a nivel global
- La velocidad exponencial exponencial de las suscripciones moviles entre 1990 y 2010. 
- El estancamiento de las suscripciones moviles a nivel global
- El continuo crecimiento de las suscripciones de banca ancha
- La inversión de la que inicialmente fuera una hegemonia de occidente por sobre oriente en el acceso a internet y suscripción a lineas moviles.

## INTRODUCCIÓN:
En el contexto de una empresa que ofrece servicios vinculados a redes móviles en cinco países (China, Emiratos Árabes, India, Islas Caimán y USA) se solicitó la creación de un informe que presente la evolución de las suscripciones a líneas móviles e internet, así como otros aspectos relacionados con el uso de internet y aplicaciones móviles que diera cuenta de lo siguiente:

  - Evolución de suscripciones a líneas móviles por cada 100 habitantes entre 1980 y 2020
  - Evolución de de suscripciones a Internet por cada 100 habitantes entre 1998 a 2020
  - Comparación de la distribución global de usuarios de Internet en 2001 y en 2020.
  - Top 5 países con más suscripciones a Internet por cada 100 habitantes en 2020.
  - Los 3 tipos de aplicaciones moviles más demandados en China.
  - Top 5 países con más usuarios de internet en los años 2001 y 2020.

El proyecto cuentaba con datos proveniente de distintas fuentes volcados a archivos Ms Excel. La plataforma elegida para la presentación y visualización del reporte fue Google LookerStudio.

## METODOLOGÍA:
### ETL
El objetivo principal fue preparar los datos para su posterior carga y análisis en Looker Studio, una herramienta de visualización y generación de informes con lo cual se procedio segun las siguientes consideraciones:

- Extracción de datos: Se recibieron los archivos en formato .xls
- Seguridad de los datos: Se definio que los mismos eran de libre acceso.
- Calidad. Verificación y validación temprana de los datos: Se observaron datos coherentes y consistentes pero que en muchos casos no respetaban las mismas convenciones y se evidencio la necesidad de un profundo trabajo de transformación y limpieza.
- Limpieza, transformación de datos e integracion de los datos:
  + Eliminación de redundancias y datos irrelevantes :  
  Se observo información duplicada entre los diferente archivos de Excel.
  Con el fin de reducir el volumen de datos y eliminar información redundante, se realizó una reorganización de las columnas. Se seleccionaron aquellas que eran relevantes para el informe solicitado y se descartaron las que no aportaban valor significativo. 
  + Simplificación:
  Se ajustaron los nombres de las columnas para asegurar la coherencia y facilitar su interpretación.
  + Unificación:
  Los datos se organizaron en dos hojas de excel de un solo archivo de Excel.
  Se observo que la colección final contenían información relacionada con las suscripciones a líneas móviles e internet de todos los paises del mundo asi como de algunas regiones destacadas y se decidio no eliminar la información de las regiones ya que podria ser util en el futuro.
  + Eliminación de espacios innecesarios y corrección de tabulaciones
  + Normalización del uso de la "," y el "." para valores numéricos con decimales

### CARGA DE DATOS 
Se obtuvo finalmente un unico archivo de Excel con dos hojas que se subio a Google Drive. Allī se lo convirtio a un libro de Google Spreadsheets para ser consumido por LookerStudio.

## RESULTADOS
https://lookerstudio.google.com/s/vnpzffEAGOw

[(Imágenes)](https://lookerstudio.google.com/s/vnpzffEAGOw)

## CONCLUSIONES
Los datos analizados en el actual estudio arrojo como conclusiones que existio un crecimiento del acceso a internet a nivel global a partir del año 2000 y un crecimiento exponencial de las suscripciones moviles entre 1990 y 2010, punto en el cual las suscripciones a redes moviles alcanzaron un punto de inflexión hasta alcanzar un punto de aparente estancamiento en el año 2018 en adelante.
En contraposición las suscripciones a servicios de internet de banca ancha, consideradas como cantidad desuscripciones por cada 100 habitantes. si bien tuvo un impacto entre los años 2011 y 2015. se recupero luego de 2015 y continua hasta 2020 con un tasa sostenida de crecimiento continuo.
Algo muy destacado fue la inversión de la que inicialmente fuera una hegemonia de occidente por sobre oriente en el acceso a internet y suscripción a lineas moviles. Se observo que si bien en 2001 la cantidad de usuarios de internet en USA eran unos 140 millones, y en China solo 33 millones, en 2020 China tiene 1000millones de usuarios de internet mientras hay solo 300millones en USA. Ppor otra parte considerando que China en 2020 tenia 1444 millones de habitantes y USA 331 millones el porcentaje de habitantes con acceso a internet en USA sigue siendo mayor con un 90% respecto al de China con un 70%.
Asimismo se observo que de los paises que 3 de los 4 paises que integran el grupoo conocido como BRIC ocupan el top 5 de paises con mas cantidad de usuarios de internet.

Palabras clave: ETL, datos, Excel, normalización, Looker Studio, análisis de datos, visualización
