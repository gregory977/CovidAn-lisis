# CovidDatabase
#Contexto análisis de casos de Covid
Por Gregory Ahumada

1. Esta es una investigación sobre el comportamiendo de contagios de Covid en 
los departamentos de Cundinamarca y Boyacá, entre los años 2020 y 2023.

2. Para esta investigación se analizaron más de 20 mil pacientes teniendo en
cuenta información como edad, ubicación, fechas de contagio, género y tipo de 
contagio.

3. La base de datos principal con la que se trabajó es
/content/Casos_positivos_de_COVID-19-Cund-Boy.csv 

4. El ejercicio de análisis de datos planteó tres partes, consolidación del 
modelo de datos en SQL, proceso de ETL de la base de datos y creación de un
dashboard interactivo para analizar el comportamiento del Covid.

5.Para la cración del modelo de datos se trabajó con Azure Data Studio debido
a altunos inconvenientes del sistema en MySql Server.

6. A partir de una tabla principal de casos, se desprenden las tablas de
municipios, departamentos, género, tipo de contagio y estado.

7. Para el proceso de ETL, se utilizó la herramienta Python Colab por su
practicidad y el proceso inició con el análisis primario de la base de datos.
Es decir, análisis de variables, caracteres, columnas, medidas, etc.

8. Luego se hizo un proceso de renombrar algunas columnas y ajustarlas.

9. Para agilizar el proceso de diagramado, se crearon en colab las tablas a 
partir de las columnas de la tabla original y fueron descargadas.

10. Posteriormente, se hizo el proceso de revisión del diagrama en Power BI
previo a la cración del dashboard.

11. Para la creación del dashboard se le dio principal importancia a la revisión
de la tasa de mortalidad, la cual se evalúa a través de la evolución de
contagios, fechas, ubicación geográfica, estado, sexo y tipo de contagio.

