# Databricks: Delta Lake avanzado


## Sesión 1:  Fundamentos y arquitectura interna de Delta Lake 

•	Objetivo 
Comprender Delta Lake no como un formato de almacenamiento, sino como un sistema transaccional distribuido que habilita el modelo Lakehouse y garantiza consistencia sobre almacenamiento cloud. 

•	Contenido 
1.	Delta Lake dentro de la evolución del Data Lake 
2.	Arquitectura interna de Delta Lake 
3.	Estructura y funcionamiento del _delta_log 
4.	Funcionamiento en tiempo de ejecución 
5.	Time Travel, RESTORE y Change Data Feed 
6.	OPTIMIZE, VACUUM y gestión del ciclo de vida del dato 
7.	Optimización del layout físico: particionado, Z-ORDER y Liquid Clustering 


## Sesión 2:  Delta Lake en el modelo Lakehouse: Control Plane y Data Plane

•	Objetivo 
 Entender la ubicación real del dato y los metadatos en Databricks, y cómo Delta Lake se integra con Unity Catalog dentro del modelo de gobernanza y seguridad enterprise. 

•	Contenido 
1.	Separación entre Control Plane y Data Plane 
2.	Ubicación física de los archivos Delta en cloud storage 
3.	Delta Lake y Unity Catalog 
4.	Managed Tables vs External Tables desde la perspectiva del ciclo de vida 
5.	Riesgos arquitectónicos y gobernanza del almacenamiento 
6.	Permisos, auditoría y lineage aplicados a tablas Delta 


## Sesión 3:  Delta Lake como motor unificado de Ingesta Incremental y Streaming 

•	Objetivo 
 Comprender cómo Delta Lake unifica procesamiento batch y streaming, habilitando pipelines incrementales robustos, consistentes y escalables dentro del modelo Lakehouse. 
 
•	Contenido 
1. 	Modelo unificado Batch + Streaming en Delta Lake 
2. 	Structured Streaming aplicado a tablas Delta 
3.	Incremental Data Ingestion basado en el Delta Log 
4.	Auto Loader y detección eficiente de nuevos archivos 
5.	Opciones avanzadas de Auto Loader 

