# ERTES_Comunidad_Valenciana

El código facilita un dataset obtenido de la pagina de datos abiertos de la GVA.
Esto fue un estudio que se hizo para analizar el impacto del covid-19 sobre el las empresas que operan
en la comunidad valenciana independientemente de su sede social.

Al ser un trabajo individual y puramente académico, fue realizado en Colab.
Se realiza una limpieza previa de los datos, eligiendo las variables a utilizar en este caso:

FECHA_SOLICITUD --> Fecha generada el dia de la solicitud
PROVINCIA --> Provincia en la que la empresa tiene su sede social.
MUNICIPIO --> Municipio en el que la empresa tiene su sede social.
SECTOR --> Sector al que pertenecen las empresas
CAUSA --> Causa de la solicitud del expediente de regulación
TOTAL_CON_TRAB_SUS --> Total de trabajadores con concesión de suspensión
TRAB_HOMBRES_SUS --> Hombres para los cuales se ha solicitado suspensión
TRAB_MUJERES_SUS --> Mujeres para las cuales se ha solicitado suspensión
TRAB_SINDET_SUS --> Personas de género indeterminado para las cuales se ha solicitado suspensión

Sobre estos datos se realizan diferentes análisis, como el impacto sobre los sectores y cada tipo de género, el motivo por el 
cual se ha solicitado la suspension, o que provincia ha resultado mas afectada, entre otros detalles.
Es realmente interesante.

Como complemento, se han agredado las localizaciones para poder crear un mapa interactivo con la libreria ploty 
y asi visualizar el impacto anual a nivel nacional de las solictudes.

Si lo desea puede descargar el notebook e interactuar con los mapas interactivos para comprobar visualmente
el impacto de los Ertes sobre cada sector. 
Ademas son muy interesantes los filtros de año y motivo de suspension en uno 
y filtro de año y sector afectado en otro.

Un saludo.
Juanjo.
