# Proyectos-Power-BI
# 📊 **Proyectos realizados en Power BI** 📊

<br>

📈 Proyecto 01 - Streaming Show TV.

![Vista2](https://github.com/josesosaeric/DataAnalayst/blob/main/Home.png)

<br>

![Vista2](https://github.com/josesosaeric/DataAnalayst/blob/main/Modelo%20Relacional.png)

<br>


#### *Objetivo del Proyecto:*
Analizar el catálogo de contenidos de Netflix a nivel global, permitiendo explorar de manera interactiva la cantidad de shows, películas y series distribuidos por país, tipo, categoría, año, y otros atributos clave. El objetivo es brindar una visión clara del alcance, la diversidad y la evolución del contenido en la plataforma.

#### *Herramientas Utilizadas:*
- Power BI Desktop: Para la visualización de datos, modelado y creación del dashboard interactivo.
- Power Query: Para la preparación, limpieza y transformación de los datos.
- DAX: Para la creación de medidas e indicadores personalizados.
- Interacción con botones y bookmarks: Para navegar de forma dinámica entre vistas y secciones del informe.

#### *Proceso de Análisis:*
1. *Preparación de Datos:*
  - Transformación y limpieza de la base de datos de Netflix utilizando Power Query.
  - Separación entre dimensiones y hechos para mantener un modelo estructurado.
  - Creación de indicadores clave para análisis agregados.
  - Identificación y eliminación de duplicados (si los había en reparto, directores, títulos, etc.).

2. *Visualizaciones y Dashboards:*
 **Panel principal (Home)** con KPIs que muestran:
- Total de shows
- Total de películas
- Total de series
- Total de países con contenido


**Gráficos destacados:**
- Gráfico de anillo: muestra la proporción de "Movies" vs "TV Shows".
- Histograma por dimensiones: permite ver la distribución del contenido por atributos como país, categoría o tipo.
- Mapa mundial: visualiza los países con más presencia de shows en la plataforma.
- Matriz detallada: permite ver la tendencia por año, cruzando dimensiones (ej. país, tipo) con indicadores como cantidad de títulos o directores.

**Panel lateral** de navegación con botones interactivos:
- Reseteo: regresa a la vista inicial del dashboard.
- Indicadores: muestra una lista desplegable con los indicadores clave.
- Dimensiones: muestra las diferentes dimensiones disponibles.
- Filtro: activa una sección para filtrar los datos por distintos campos.
- Regresar: disponible en cada sección para volver a la vista anterior.


<br>

![Vista2](https://github.com/josesosaeric/DataAnalayst/blob/main/Indicadores.png)

<br>


3. *Respuestas a las Preguntas Clave:*
   - ¿Qué tipo de contenido (películas o series) predomina en la plataforma?
   - ¿En qué países hay más títulos disponibles?
   - ¿Cuál es la categoría con mayor cantidad de shows?
   - ¿Cuáles son los directores y actores más frecuentes?
   - ¿Cómo ha sido la evolución del catálogo de Netflix a lo largo de los años?

#### *Desafíos y Soluciones:*
Visualizar múltiples dimensiones e indicadores sin saturar la interfaz	Implementación de un panel interactivo con botones que permite cambiar entre vistas y mantener el orden visual
Mostrar datos geográficos con precisión	Uso de un mapa para representar la cantidad de shows por país con color y tamaño
Navegación intuitiva entre vistas y secciones	Uso de bookmarks (marcadores) y botones para facilitar la experiencia del usuario final

#### *Resultados Finales:*
- Un dashboard intuitivo y profesional que permite entender la magnitud y diversidad del catálogo de Netflix.
- Visualizaciones dinámicas que permiten a cualquier usuario responder sus propias preguntas filtrando por país, tipo, categoría, etc.
- Herramienta útil tanto para usuarios curiosos como para posibles análisis de mercado, contenido o distribución geográfica.

#### *Habilidades Demostradas:*
- Modelado de datos estructurado (hechos y dimensiones)
- Creación de KPIs con DAX
- Visualización efectiva de información en Power BI
- Uso avanzado de bookmarks y botones para navegación dinámica
- Enfoque en la experiencia del usuario (UX)
- Análisis geográfico con mapas
- Diseño limpio y profesional



📈 Proyecto 02 - Ventas Globales.

![Vista2](https://github.com/josesosaeric/DataAnalayst/blob/main/EvolucionVentaMargenRP1.png)

<br>

![Vista2](https://github.com/josesosaeric/DataAnalayst/blob/main/TopClientesProductosRP1.png)

<br>

#### *Objetivo del Proyecto:*
El objetivo principal fue analizar los datos de ventas a nivel mundial de una empresa internacional para responder a cuatro preguntas clave relacionadas con el margen de ganancia, los clientes más importantes, los productos más vendidos y el desempeño mensual de las ventas en los años 2018 y 2019.

#### *Herramientas Utilizadas:*
- *Power BI*: Para la creación de visualizaciones y dashboards interactivos.
- *DAX (Data Analysis Expressions)*: Para la creación de medidas y columnas calculadas.
- *Excel*: Para la revisión inicial de los datos.

#### *Proceso de Análisis:*
1. *Preparación de Datos:*
   - Cargué los datos en Power BI y verifiqué la estructura de las tablas y sus relaciones.
   - Identifiqué problemas en los datos, como fechas mal formateadas y clientes sin identificar (índice -1), y los corregí utilizando fórmulas de DAX.

2. *Visualizaciones y Dashboards:*
   - Creé dos dashboards principales:
     - *Evolución de Ventas y Margen*: Enfocado en comparar el margen de ganancia y las ventas entre 2018 y 2019, con segmentaciones por país, canal de venta y fecha.
     - *Top Clientes y Productos*: Enfocado en identificar los clientes que más compraron en 2018 y los 5 productos más vendidos por cada uno.

3. *Respuestas a las Preguntas Clave:*
   - *Margen de Ganancia por Canal*: Calculé el margen de ganancia (precio total menos costo total) por canal (Internet y Reseller) para cada año. Encontré que el canal Internet generó mayores ganancias en comparación con Reseller.
   - *Clientes que Más Compraron en 2018*: Identifiqué a los clientes con mayores ventas por país y los 5 productos más comprados por cada uno. Por ejemplo, en Canadá, el cliente Samantha Jenkins compró 41 unidades, siendo el producto más vendido el "Patch Kit/8 Patches".
   - *Mes de Mayor Venta en 2019*: Determiné que noviembre fue el mes con mayores ventas en 2019, con un total de $716,226.67.
   - *Comparación de Ventas 2018 vs. 2019*: Todos los meses de 2019 superaron en ventas a los de 2018, lo que indica un crecimiento positivo en el negocio.

#### *Desafíos y Soluciones:*
- *Problemas con Fechas*: Power BI no reconocía la columna de fechas original, por lo que creé una nueva columna utilizando DAX para extraer el año, mes y día de un índice numérico.
- *Clientes sin Identificar*: El 33.42% de los clientes tenían un índice -1, lo que dificultaba su identificación. Decidí trabajar con los datos disponibles y segmentar por canal para no perder información relevante.

#### *Resultados Finales:*
- *Dashboard Interactivo*: Creé un dashboard interactivo que permite a los usuarios explorar los datos por país, canal de venta y período de tiempo.
- *Conclusiones Claras*: Identifiqué tendencias clave, como el crecimiento del canal Internet y los productos más populares entre los clientes principales.

#### *Habilidades Demostradas:*
- *Manejo de Power BI*: Creación de visualizaciones avanzadas, uso de segmentaciones y manejo de relaciones entre tablas.
- *Análisis de Datos*: Identificación de problemas en los datos y aplicación de soluciones técnicas.
- *Comunicación de Resultados*: Presentación clara y visual de los hallazgos, con gráficos y tablas que facilitan la comprensión de los datos.


Last Edited on: 15/12/2024

