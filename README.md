# Caso práctico: DW y  ETL

![image](https://github.com/melissamelendezrojano/DataWarehouse_ETL_CasoPractico/assets/90320256/c7e6e486-6379-45eb-8418-afececb182ec)


El objetivo de este caso práctico es poner en práctica los conceptos de inteligencia de negocio y data warehousing, haciendo hincapié en el diseño e implementación del modelo multidimensional y modelo de estrella, así como en los conceptos de dimensión, hechos, jerarquías, niveles, métricas y operaciones OLAP.

Del mismo modo, se pondrán en práctica los conocimientos sobre inteligencia de negocio y ETL, prestando especial atención al diseño e implementación del proceso básico ETL hasta culminar en un modelo en estrella, así como en la implementación de dimensión y hechos en la capa física.

#### ESCENARIO:

El departamento antifraude de una compañía de mystery shopping desea hacer un seguimiento y analizar la información relativa a las encuestas que realiza en los distintos centros de sus clientes. Para ello, solicita:

1. Un análisis y diseño del data warehouse que daría respuesta a los usuarios analíticos del departamento antifraude, suponiendo que los usuarios aún no tienen claro el tipo de análisis que quieren realizar.

2. Partiendo del análisis y diseño previo realizado, y usando Pentaho Data Integration, realizar la implementación del proceso ETL con el objetivo de:

 - Identificar y extraer los datos de las fuentes.

 - Procesar los datos y aplicar procesos de limpieza y calidad del dato.

 - Generar y cargar los datos en el modelo físico de estrella identificado en la fase de diseño.

3. Posteriormente, partiendo del análisis y diseño previo realizado y conociendo ya la tecnología seleccionada, en este caso Pentaho Business Analytics, ha de realizarse una implementación ágil del modelo multidimensional.

El objetivo en este caso práctico es la implementación del modelo multidimensional sobre diseño del data warehouse que daría respuesta a los usuarios analíticos del departamento antifraude, suponiendo que los usuarios aún no tienen claro el tipo de análisis que quieren realizar.

###### Se deberá realizar:

- La implementación de un pequeño modelo multidimensional, haciendo uso de Pentaho Business Analytics Server y su herramienta wizard para modelado multidimensional o puede utilizar cualquier otra herramienta para realizar el modelado.

- La implementación de un pequeño proceso ETL, haciendo uso de Pentaho Data Integration (PDI) o cualquier otra herramienta que cumpla las mismas funciones.

Para la realización de este ejercicio práctico se partirá de los datos **IMF_M5_Mystery_Shopping.csv**

------------

#### Para seguir el desarrollo del caso práctico:

1. Se realiza una primera visualización de datos con Python y se encuentra en el archivo [VisualizacionDatos.ipynb](https://github.com/melissamelendezrojano/DataWarehouse_ETL_CasoPractico/blob/main/VisualizacionDatos.ipynb)

2. El desarrollo del caso práctico se encuentra en el archivo [casopractico_m5.pdf](https://github.com/melissamelendezrojano/DataWarehouse_ETL_CasoPractico/blob/main/casopractico_m5.pdf) donde se explica detalladamente el proceso seguido.
