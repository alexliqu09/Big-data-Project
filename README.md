<h1><center><b>Analytcs for Premier leages Football Players</b></center></h1>

<h2><b>Resumen</b></h2>
En el proyecto, se trabajó con una fuente de datos CSV de la Premier League que contenía información sobre los jugadores en diferentes temporadas desde 2014 hasta 2022. Se realizó un proceso de ingesta de datos en Databricks, en el cual se llevó a cabo la transformación y limpieza de los datos, así como el almacenamiento de los mismos en diferentes capas: landing, bronze, silver y gold.

En la capa de landing, se almacenaron los datos crudos en CSV, separados por carpetas de temporadas. En la capa bronze, se realizó la transformación y limpieza de los datos, y se almacenaron en formato parquet. En la capa silver, se llevaron a cabo operaciones de agregación para obtener estadísticas de los jugadores en cada temporada, y se almacenaron también en formato parquet. Finalmente, en la capa gold se generaron estadísticas por temporada y jugador, se ordenaron y se guardaron en formato parquet.

Para visualizar los datos, se conectó Power BI a Databricks y se importó el archivo csv generado apartir de las transformaciones de la capa gold. Luego se generaron visualizaciones y se creó un reporte que permite a los usuarios interactuar con los datos de los jugadores y sus estadísticas.
<p>

<h2><b>Pipeline</b></h2>

Pipeline del trabajo realizado.
![image](src/pipeline.png)

<h2><b>Power BI</b></h2>

Visualización de los jugadores con algunas estadisticas.

<div style="text-align:center;">
  <img src="src/powerbi.jpeg" alt="Descripción de la imagen" width="1000" height="600">
</div>
