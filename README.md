# vwgroupretail
Test vwgroupretai - Data Analytics Qlik
Resumen del trabajo realizado:
1.	Obtención de Datos (Python – Jupyter Notebook):
 He analizado la estructura HTML de la página https://exclusive.vwgroupretail.es/vehiculo-de-ocasion/ para identificar los selectores necesarios y realizando el Web Scraping con Python (librerías requests y BeautifulSoup), he extraído 1.800 registros, incluyendo información como marca, modelo, precio, kilometraje y otros datos pertinentes.Los datos se han limpiado y guardado en un archivo CSV.2.	Carga y Transformación en Qlik:
Debido a dificultades técnicas para conectar con Supabase, los datos se han cargado desde Google Drive hacia Qlik Cloud.En el editor de carga de Qlik se han aplicado transformaciones adicionales, como convertir precios a formato numérico, separar marca y modelo, crear rangos de precios y preparar el conjunto de datos para el análisis. 
3.	Visualizaciones en Qlik:
He creado visualizaciones básicas para el análisis, incluyendo:Diagramas de dispersión para observar la relación entre kilometraje y precio.Gráficos de barras para comparar la distribución de precios entre diferentes marcas.Histogramas para visualizar la concentración de vehículos por rango de precio.4.	Informe con NPrinting:
 
No ha sido posible establecer la conexión con NPrinting para generar el informe final. Por consiguiente, adjunto el reporte realizado en Qlik, así como los scripts empleados tanto en Python como en Qlik, detallando los pasos seguidos para que el proceso se entienda de inicio a fin.
