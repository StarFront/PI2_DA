# Siniestros viales

![primera img](https://chequeado.com/wp-content/uploads/2022/06/siniestro-viales-3.jpg)

En la ciudad de Buenos Aires, ocurren diariamente numerosos accidentes en diversas condiciones de conducción, involucrando a peatones, ciclistas, automovilistas y motociclistas, e incluso los transportes públicos no están exentos de estar involucrados.

Los siniestros viales, también llamados accidentes de tráfico o de tránsito, son eventos que tienen lugar en las vías públicas e incluyen colisiones entre vehículos, atropellos, choques con objetos fijos y caídas de vehículos. Estos incidentes pueden resultar en daños materiales, lesiones graves o fatales.

En una ciudad como Buenos Aires, la preocupación por los siniestros viales es considerable debido al alto volumen de tráfico y la densidad poblacional, afectando la seguridad de residentes y visitantes, así como la infraestructura vial y los servicios de emergencia.

Las tasas de mortalidad relacionadas con siniestros viales son indicadores críticos de la seguridad vial, calculándose por el número de muertes en relación con la población o la cantidad de vehículos registrados. Reducir estas tasas es esencial para mejorar la seguridad y proteger vidas.

En Argentina, alrededor de 4,000 personas mueren anualmente en siniestros viales, siendo la principal causa de muertes violentas. Entre 2018 y 2022, se registraron 19,630 muertes según el Sistema Nacional de Información Criminal, equivalente a 11 personas por día. En 2022, se contabilizaron 3,828 muertes. La probabilidad de morir en un siniestro vial es dos o tres veces mayor que en incidentes de inseguridad delictiva.

# Descripción del proyecto:

El propósito principal de este proyecto es realizar un análisis de datos vinculados a homicidios en siniestros viales ocurridos en la Ciudad de Buenos Aires entre 2016 y 2021. La meta es generar información significativa que pueda ser aprovechada por las autoridades locales para implementar medidas eficaces con el fin de disminuir la cantidad de víctimas mortales en accidentes de tránsito.

# Metodología y herramientas:

Este proyecto fue realizado a partir de los siguientes procesos:

Recopilación de Datos: Se accedió a un conjunto de datos proporcionado por la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, el cual contenía información detallada sobre homicidios en accidentes de tránsito. Además, se obtuvo información geoespacial precisa sobre la ubicación de las cámaras de control vehicular en la ciudad de fuentes confiables.

Preprocesamiento de Datos: Se llevó a cabo el preprocesamiento de los datos mediante el uso de la biblioteca Pandas para organizar y filtrar la información de manera adecuada. Para el conjunto de datos relacionado con las cámaras, se creó un archivo GeoJSON utilizando datos geográficos.

Análisis Exploratorio de Datos (EDA): Se ejecutó un análisis exploratorio de datos en un entorno de cuaderno Jupyter con el objetivo de extraer información valiosa sobre los homicidios en siniestros viales, así como sobre la ubicación geográfica de las cámaras de control vehicular.

Utilizando las siguientes herramientas:

- Python
- Pandas
- Power BI
- NumPy
- GeoPandas
- Matplotlib
- Scikit-Learn

# Estructura de navegación de los archivos:

- Eda.ipynb: Archivo tipo Jupyter Notebook donde se realiza el Análisis exploratorio de datos.
- KPI.ipynb: Archivo tipo Jupyter Notebook que contiene la realización de los KPI's expuestos en el dashboard.
- Datasets: Carpeta donde se encuentran los archivos "vanilla" que se usaron para el proyecto.
- Recursos_dashboard: Carpeta con los datos procesados y preparados para ser ingresados al DashBoard.

# Análisis a profundidad de los datos

## Distribución por Género de las Víctimas

![victimas por genero](https://i.imgur.com/cZjtpX5.png)

Al examinar los datos de homicidios en siniestros viales, se aprecia que los hombres constituyen la mayoría de las víctimas anuales en accidentes de tráfico. Este descubrimiento sugiere la necesidad de implementar medidas específicas de seguridad y concientización dirigidas a los conductores masculinos con el objetivo de reducir la tasa de accidentes mortales.

## Tipos de Vehículos Involucrados
Los datos también indican que las motocicletas son uno de los tipos de vehículos más frecuentemente implicados en accidentes mortales. Esto señala la importancia de centrar las políticas de seguridad vial en mejorar la seguridad de los motociclistas, como la promoción del uso obligatorio de cascos y la educación sobre la conducción segura de motocicletas.

## Comunas con Mayor Riesgo
Destaca la comuna 1 como la que presenta la mayor cantidad de accidentes mortales en la Ciudad de Buenos Aires. Este hallazgo sugiere la necesidad de intensificar las iniciativas de seguridad vial en esta área específica, como la implementación de zonas de velocidad controlada y campañas educativas dirigidas a los residentes de la comuna 1.

![victimas por comunas](https://i.imgur.com/aQFglUF.png)

## Cámaras de Control Vehicular
En relación con las cámaras de control vehicular, se observa que la comuna 13 cuenta con la mayor cantidad de cinemómetros. No obstante, la comuna 1 lidera en términos de la cantidad de cámaras con análisis de video. Esto podría indicar que la comuna 1 tiene un enfoque más avanzado en la monitorización y la aplicación de la ley en comparación con otras comunas.

![control vehicular](https://i.imgur.com/dZjzCW3.png)

## Cambios en las Muertes Anuales
Es destacable la disminución en el número de muertes anuales en el año 2020. Este fenómeno podría estar vinculado a las restricciones de movilidad impuestas debido a la pandemia de COVID-19. Esto plantea la pregunta de si algunas de estas restricciones deberían mantenerse o modificarse para mantener una disminución en la tasa de accidentes mortales.

![muertes anuales](https://i.imgur.com/oHNP2vI.png)

## Meses de Mayor Riesgo
Se evidencia que una considerable cantidad de siniestros viales mortales ocurren en el mes de diciembre, posiblemente relacionado con las festividades y el aumento de la movilidad durante las vacaciones. Esto resalta la importancia de reforzar la vigilancia y la concientización durante estos períodos festivos.

![muertes por mes](https://i.imgur.com/2lzvr4I.png)

## Tipos de Vías
Al examinar los tipos de vías, se observa que las autopistas registran la menor cantidad de siniestros mortales. Esto podría deberse a una mejor planificación de la seguridad vial en estas vías. Este hallazgo sugiere la necesidad de implementar estrategias similares en otras áreas con tasas de accidentes más elevadas.

## Cómo Contribuir:

Análisis Continuo: Se recomienda mantener un análisis continuo de los datos, actualizando regularmente la información sobre homicidios en siniestros viales en la Ciudad de Buenos Aires. Esto permitirá identificar tendencias a lo largo del tiempo y evaluar la efectividad de las medidas implementadas.

Enfoque en Educación Vial: Dado que los datos sugieren que los hombres constituyen la mayoría de las víctimas, propongo desarrollar iniciativas específicas de educación vial dirigidas a este grupo demográfico. Esto podría incluir campañas de concientización sobre prácticas de conducción seguras y el fomento del respeto a las normas de tráfico.

Intervenciones Específicas por Tipo de Vehículo: Dado que las motocicletas son frecuentemente involucradas en accidentes mortales, se sugiere la implementación de medidas específicas para mejorar la seguridad de los motociclistas. Esto podría incluir programas de capacitación obligatorios, controles de seguridad más estrictos y campañas de concientización.

Enfoque en Comuna 1: Dada la alta incidencia de accidentes mortales en la Comuna 1, se propone intensificar las iniciativas de seguridad vial en esta área. Esto podría incluir la implementación de medidas de control de velocidad, mejoras en la señalización y programas educativos específicos para la comunidad local.

Optimización de la Red de Cámaras: Considerando la variabilidad en la cantidad y tipo de cámaras de control vehicular en distintas comunas, se sugiere una revisión y optimización de la distribución de estas cámaras. Esto puede implicar reubicaciones estratégicas para una mejor cobertura y eficacia en la monitorización.

Evaluación de Restricciones COVID-19: Dado el descenso en el número de muertes anuales en 2020, relacionado con las restricciones de movilidad por la pandemia, sería beneficioso evaluar la posibilidad de mantener ciertas restricciones para reducir la tasa de accidentes mortales, ajustándolas según la situación actual.

Refuerzo en Meses de Mayor Riesgo: Dado que diciembre presenta una mayor cantidad de siniestros mortales, se sugiere implementar medidas especiales de vigilancia y concientización durante este mes. Esto podría incluir campañas específicas y aumento de patrullajes.

Implementación de Estrategias en Otras Áreas: Considerando que las autopistas muestran la menor cantidad de siniestros mortales, se sugiere estudiar las estrategias de seguridad vial utilizadas en estas vías y evaluar su aplicación en otras áreas con tasas de accidentes más elevadas.

# Documentación:

[municipio.json](https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG)

[Camaras_control_vehicular](https://data.buenosaires.gob.ar/dataset/camaras-fijas-control-vehicular)

[Poblacion Buenos Aires](https://es.wikipedia.org/wiki/Buenos_Aires)
