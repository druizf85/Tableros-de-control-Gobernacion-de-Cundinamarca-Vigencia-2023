# Tableros de control - Gobernación de Cundinamarca Vigencia 2023

Para la vigencia 2023 la Gobernación de Cundinamarca contaba con 23 dependencias que hacían parte del nivel centralizado de la contratación:
-	Secretaria de Salud
-	Secretaría de Prensa y Comunicaciones
-	Secretaría de Transporte y Movilidad
-	Secretaria General
-	Secretaria de Gobierno
-	Secretaria de Tecnologías de la Información y las Comunicaciones
-	Secretaría de Competitividad y Desarrollo Económico
-	Secretaria de Ciencia tecnología e Innovación
-	Secretaria de Desarrollo e Inclusión Social
-	Secretaria de la Mujer y Equidad de Genero
-	Secretaria del Ambiente
-	Secretaria de Hacienda
-	Secretaria de Educación
-	Secretaria de Hábitat y Vivienda
-	Secretaría de Asuntos Internacionales
-	Unidad Administrativa Especial para la Gestión del Riesgo de Desastres de Cundinamarca
-	Secretaria de Integración Regional
-	Secretaria Jurídica
-	Secretaria de Planeación
-	Secretaría de la Función Pública
-	Secretaria de Agricultura y Desarrollo Rural
-	Secretaría de Minas Energía y Gas
-	Alta Consejería para la Felicidad

Teniendo en cuenta que se debía llevar un orden y ciertos estándares en la contratación del nivel centralizado, dentro de la Dirección de Contratación de la Secretaría Jurídica de la Gobernación de Cundinamarca se tenía la necesidad de crear tableros de control que les permitieran a los diferentes participes del sistema de compras públicas conocer en tiempo real el estado de cada proceso de contratación para la vigencia 2023 y poder identificar, por entidad centralizada, diferentes aspectos que son relevantes para la toma de decisiones a nivel gerencial, dentro de los cuales se destacan, entre otros aspectos, los siguientes:

(i)	Cantidad de procesos publicados. 
(ii)	Valor de los procesos. 
(iii)	Modalidades de contratación. 
(iv)	Tipos de contrato. 
(v)	Justificación de modalidades. 
(vi)	Buscador por proceso. 
(vii)	Estadísticas de cantidad de ofertas recibidas. 

Para dar solución a esta problemática se consolidó un equipo multidisciplinario, con experiencia en estructuración y ejecución de contratos estatales y con los conocimientos en analítica de datos enfocados en contratación, se procedió a investigar qué opciones existían como fuentes de información confiables y actualizadas. Además, esto permitiría a los proveedores, ciudadanía y entes de control poder utilizarlo para realizar un seguimiento continuo.

Dentro de las problemáticas a resolver se establecieron proyectos que se debían abordar, el seguimiento a los procesos que se publican en tiempo real, los contratos firmados en el periodo de gobierno (2020-2023) y la consolidación, estandarización y seguimiento a los planes anuales de adquisiciones publicados por las diferentes dependencias del nivel centralizado.
Para cada uno de estos tres proyectos se elaboró un proceso extracción, transformación y carga de los datos (ETL - Extract, Transform, Load) desde diversas fuentes hacia el repositorio de datos que alimentará las visualizaciones del tablero (Microsoft Power BI). El proceso consistirá en diversas etapas:

(i)	Extracción (Extract): Identificar las fuentes de datos relevantes para el tablero de control.

•	Establecer conexiones seguras y eficientes con estas fuentes de datos, utilizando protocolos de seguridad.
•	Implementar rutinas de extracción automatizadas para garantizar la actualización regular de los datos.

(ii)	Transformación (Transform):

•	Realizar la limpieza de los datos extranjeros para eliminar valores nulos, datos duplicados, inconsistencias y errores tipográficos que puedan afectar la calidad de las visualizaciones.
•	Aplicar transformaciones y cálculos necesarios para derivar nuevas métricas o indicadores relevantes para el tablero de control.
•	Unificar y estandarizar la estructura de los datos procedentes de diferentes fuentes para facilitar su análisis y visualización.
•	Identificar y tratar valores atípicos o outliers que puedan distorsionar las conclusiones extraídas del análisis de datos.

(iii)	Carga (Load):

•	Diseñar el esquema de la base de datos que almacenará los datos transformados, asegurando una estructura óptima para el almacenamiento eficiente y la recuperación rápida de la información.
•	Establecer procesos de carga automatizados que transfieran los datos limpios y transformados desde el área de preparación hacia la base de datos del tablero de control.
•	Implementar mecanismos de control de calidad para verificar la integridad y consistencia de los datos cargados, mediante la comparación de conteos de registros y validaciones de integridad referencial si corresponde.

Una vez que se han recopilado y procesado los datos, se procedió a diseñar y configurar cada uno de los tableros de control: 

1.	TABLERO DE CONTROL SEGUIMIENTO A PROCESOS DE CONTRATACIÓN PUBLICADOS
Tablero de control de acceso público que incorpora la información publicada en el SECOP II para la vigencia 2023, con el fin de que los interesados puedan verificar de manera precisa, actualizada e interactiva los datos de los procesos publicados y con un periodo de actualización diaria.

Visualizaciones

•	Cifras generales - cantidad y valor de procesos de contratación y porcentajes de participación en la actual vigencia.
•	Número de ofertas que realizaron los proponentes de los procesos de contratación consultados. 
•	Visualización estado general del proceso de contratación.
•	Visualización modalidad de contratación.
•	Visualizaciones cantidad y valor contratos en tiempo real.
•	Visualización cantidades de contratos por tipo de contrato.
•	Visualización cantidades de contratos por justificación de modalidad de contratación.
•	Tabla con la información general de los procesos de contratación. En esta tabla se identifican las siguientes columnas: Dependencia, Número de proceso, Número de contrato, Estado del contrato, Objeto contractual, Valor del proceso, Fecha de publicación del proceso, Modalidad y Enlace del Proceso.

![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/70304ef6-91b5-4019-9702-83cf5d2a97f4)
![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/a8e457c5-8db5-40c6-b300-9409062507c8)


Este tablero se encuentra actualmente publicado en el siguiente enlace:

https://app.powerbi.com/view?r=eyJrIjoiMDBlMjBiZDItNTVkMS00ZTkxLWEyYjEtYTljZGJkZGIyN2FlIiwidCI6IjY0ZjMwZDYzLTE4MjctNDlkOC05OTUxLTFkYjE3ZDA5NDllNCJ9&pageName=ReportSection

2.	TABLERO DE CONTROL CONTRATACIÓN HISTÓRICA 

Tablero de control de acceso público que incorpora la información contractual histórica publicada en el Sistema Electrónico de Contratación Pública - SECOP, el cual se compone de: (i) SECOP I, (ii) SECOP II y (iii) Tienda Virtual del Estado Colombiano – TVEC, con el fin de que la entidad pueda verificar de manera precisa la información de los contratos firmados históricamente con un periodo de actualización diaria.

Visualizaciones

•	Cifras generales - cantidad y valor de contratos y porcentajes de participación.
•	Visualizaciones cantidad y valor contratos.
•	Visualización participación por estado del contrato.
•	Visualización modalidad de contratación.
•	Matriz de clasificación UNSPSC por cantidades y valores de contratos.
•	Diagrama de Pareto – Valor total contratado por Segmento.
•	Visualización cantidades y valores de contratos por plataforma.
•	Tabla con la información general de los contratos. En esta tabla se identifican las siguientes columnas: Dependencia, Número de contrato, Estado del Contrato, Objeto contractual, Modalidad contractual, Año de firma y Enlace del Proceso.

![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/763fa210-d4c2-499a-9416-be4c26f8be15)
![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/fe09dff0-2599-4412-beeb-c33e2347e7fe)
![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/229120e2-1d89-4ff3-b499-652f17713505)


Este tablero se encuentra actualmente publicado en el siguiente enlace:

https://app.powerbi.com/view?r=eyJrIjoiMjI4NDFmN2ItM2I5Yy00ZDNmLWIwMzUtMzM0ZDZmYzBjYWYyIiwidCI6IjY0ZjMwZDYzLTE4MjctNDlkOC05OTUxLTFkYjE3ZDA5NDllNCJ9 

3.	TABLERO DE CONTROL – PLANES ANUALES DE ADQUISICIONES VIGENCIA ACTUAL

Tablero de control que incorpora la información que se registra por cada dependencia de la Entidad Estatal respecto de los Planes Anuales de Adquisiciones en el Sistema Electrónico de Contratación Pública - SECOP II, con el fin de que la entidad pueda ejercer control mediante los datos detallados de los Planes Anuales de Adquisiciones publicados de manera actualizada y realizar comparativos con respecto a los procesos contractuales publicados y también con los Planes Anuales de Adquisiciones publicados inicialmente para esta vigencia.

Visualizaciones

•	Cifras generales - cantidad y valor estimada de procesos de contratación.
•	Matriz de clasificación UNSPSC por cantidades y valores de las necesidades del PAA.
•	Cantidad de versiones del PAA por dependencia.
•	Tabla con la información general de las necesidades. En esta tabla se identifican las siguientes columnas: Dependencia, Número de contrato, Estado del Contrato, Objeto contractual, Modalidad contractual, Año de firma y Enlace del Proceso.
•	Visualizaciones comparativas de las necesidades contra los procesos publicados en cantidad y valor por dependencia.
•	Visualizaciones comparativas de las necesidades actuales contra las necesidades publicadas inicialmente en cantidad y valor por dependencia.

![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/6d373e3a-7af7-44ab-9dc2-84231eee8857)
![image](https://github.com/druizf85/Tableros-de-control---Gobernaci-n-de-Cundinamarca/assets/121362745/f99f585b-2fc0-4ea5-8ce9-a83209ae6dec)


Este tablero se encuentra actualmente publicado en el siguiente enlace:

https://app.powerbi.com/view?r=eyJrIjoiMTdiMWNhYjItNDY0OS00M2E2LTk3YTctYWEwZWI1NzA1YTg3IiwidCI6IjY0ZjMwZDYzLTE4MjctNDlkOC05OTUxLTFkYjE3ZDA5NDllNCJ9 

Para estos tres tableros de control se realizaron las respectivas pruebas y ajustes de manera permanente, ya que se debe hacer un seguimiento su funcionamiento con el fin de asegurarse de que exista un rendimiento óptimo, de que la información extraída y proyectada es fiable, que los objetos visuales funcionan correctamente y verificar ajustes adicionales al modelo de datos creado debido a la actualización de información en tiempo real.

Por otro lado, se elaboró la documentación de la metodología implementada, procesos de transformación y demás ajustes realizados a las diferentes versiones del tablero de control. Además, se crearon y socializaron los manuales de usuario para cada uno de los tableros desarrollados y publicados.

Finalmente, estos tableros fueron una herramienta socializada a nivel interno, se realizaron jornadas de capacitación, tanto a nivel de la dirección como para los usuarios finales, con el fin de que pudieran sacar todo el provecho al tablero de control de manera efectiva.

Además, estos tableros de control se implementaron para diferentes fines:

-	Estandarizar procesos internos de publicación de contratos para las 23 dependencias del nivel centralizado.
-	Verificación de la liquidación de los contratos publicados desde la vigencia 2020 a 2023.
-	Seguimiento a la publicación de procesos de contratación que fueron planeados y generación de alertas en los tiempos de contratación de la entidad.
-	Fuente de información para los informes de gestión solicitados a nivel gerencial.
