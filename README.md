<img align="center" src="https://i.imgur.com/gJzyKft.png" alt="gabriellugo" />

# GESTION ANALITICA DE DATOS CON POWER BI

<a href="https://github.com/GabrielLugooo/Gestion-Analitica-Datos-PowerBi/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Analitica%20Datos%20PowerBi%20Español-000000" alt="Analitica Datos PowerBi Español" /></a>
<a href="https://github.com/GabrielLugooo/Gestion-Analitica-Datos-PowerBi/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Analitica%20Datos%20PowerBi%20Inglés-green" alt="Analitica Datos PowerBi Inglés" /></a>

## Objetivos

El proyecto transforma los datos de ventas minoristas de 2011 y 2012 en un modelo analítico verificable y un informe interactivo con KPIs, segmentadores y hallazgos descriptivos.

## Habilidades Aprendidas

- Importación e integración de datos desde archivos `.csv` y `.xlsx.`
- Limpieza, transformación y tipado de datos con `Power Query`.
- Aplicación de configuraciones regionales para interpretar fechas y valores numéricos correctamente.
- Tratamiento de valores faltantes y conservación de los datos originales para mantener su trazabilidad.
- Creación de columnas derivadas para normalizar variables con escalas inconsistentes.
- Diseño de un modelo de datos analítico con tablas de hechos y dimensiones.
- Creación de claves compuestas para relacionar ventas con las características semanales de cada tienda.
- Configuración de relaciones uno a muchos y validación de la integridad de los datos.
- Creación de una tabla calendario para analizar las ventas a lo largo del tiempo.
- Desarrollo de medidas y columnas calculadas con `DAX`.
- Cálculo de indicadores de ventas totales, máximas, mínimas, promedios y ventas por tipo de día.
- Análisis de ventas por tienda, tipo de tienda, ubicación, período, feriados y temperatura.
- Diseño de informes interactivos con gráficos, tarjetas, segmentadores y navegación entre páginas.
- Documentación de resultados, controles de calidad, hallazgos y limitaciones del análisis.

## Herramientas Usadas

![Static Badge](https://img.shields.io/badge/Power%20BI-000000?logo=powerbi&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Power%20Query-000000?logo=microsoft&logoSize=auto)
![Static Badge](https://img.shields.io/badge/DAX-000000?logo=powerbi&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Microsoft%20Excel-000000?logo=microsoftexcel&logoSize=auto)
![Static Badge](https://img.shields.io/badge/CSV-000000?logo=files&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Git-000000?logo=git&logoSize=auto)
![Static Badge](https://img.shields.io/badge/GitHub-000000?logo=github&logoSize=auto)

- `Power BI Desktop` (modelado de datos, medidas y creación de informes interactivos)
- `Power Query` (extracción, limpieza y transformación de datos)
- `DAX` (creación de medidas, columnas calculadas y validaciones)
- `Microsoft Excel` (archivo de referencia del proyecto)
- Archivos `.csv` (fuentes de ventas, características semanales y tiendas)
- `Git` y `GitHub` (control de versiones, documentación y publicación del proyecto)

## Proyecto

### Vista Previa

<img align="center" src="https://i.imgur.com/PxzSyIP.jpeg" alt="PowerBi_Analytics_01" />
<img align="center" src="https://i.imgur.com/9QTQ4Db.jpeg" alt="PowerBi_Analytics_02" />
<img align="center" src="https://i.imgur.com/wXW8nY2.jpeg" alt="PowerBi_Analytics_03" />
<img align="center" src="https://i.imgur.com/3hzTJi2.jpeg" alt="PowerBi_Analytics_04" />

### Contenidos

- `powerbi/PI_GAD_PowerBI.pbix`: archivo principal de Power BI con tres páginas: Portada, Reporte General y Ventas 2012 - Temperatura > 20.
- `datos/Datawarehouse.xlsx`: libro original de referencia del proyecto.
- `datos/raw/`: CSV originales de ventas, características semanales y tiendas.
- `docs/Informe_Final.md`: informe detallado de limpieza, modelo, medidas, hallazgos, validaciones y limitaciones.
- `docs/Medidas_DAX.md`: fórmulas DAX implementadas.

### Abrir el proyecto

Abrir `powerbi/PI_GAD_PowerBI.pbix` con Power BI Desktop. El modelo contiene los datos importados. Para actualizar desde los CSV del repositorio en otro equipo, modificar los orígenes de las consultas de Power Query para apuntar a `datos/raw/`.

### Resultados validados

- Filas: `sales` 280.891; `features` 4.680; `stores` 45; `location` 12.
- Claves de `features[StoreWeekKey]` únicas y cero filas de ventas sin correspondencia en `features`.
- Ventas totales 2011–2012: 4.448.332.866,70.
- Ventas 2012 con `Temperature > 20`: 1.994.956.776,32.

## Limitaciones

Las columnas ajustadas de combustible y desempleo son reglas documentadas para valores con escala inconsistente; no se presentan como correcciones oficiales. Se conservan los campos originales.

El umbral de temperatura usa la escala de la fuente, cuya unidad no fue confirmada.

El total de 2012 cubre ventas solo hasta el 26 de octubre, por lo que no representa un año calendario completo.

---

<h3 align="left">Conecta Conmigo</h3>

<p align="left">
<a href="https://www.youtube.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=55200&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="http://www.tiktok.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=118638&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="https://instagram.com/gabriellugooo_" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=32309&format=png" alt="gabriellugooo_" height="40" width="40" /></a>
<a href="https://x.com/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=phOKFKYpe00C&format=png" alt="gabriellugooo" height="40" width="40" /></a>
<a href="https://www.linkedin.com/in/hernando-gabriel-lugo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=8808&format=png" alt="hernando-gabriel-lugo" height="40" width="40" /></a>
<a href="https://github.com/GabrielLugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=80&id=AngkmzgE6d3E&format=png" alt="gabriellugooo" height="34" width="34" /></a>
<a href="mailto:lugohernandogabriel@gmail.com"> <img align="center" src="https://img.icons8.com/?size=50&id=38036&format=png" alt="lugohernandogabriel@gmail.com" height="40" width="40" /></a>
<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://simpleicons.org/icons/linktree.svg" alt="gabriellugooo" height="40" width="40" /></a>
</p>

<p align="left">
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/Readme%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Español-000000" alt="Versión Español" /></a>
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Inglés-Green" alt="Versión Inglés" /></a>

</p>

<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Créditos-Gabriel%20Lugo-green" alt="Créditos" /></a>
<img align="center" src="https://komarev.com/ghpvc/?username=GabrielLugoo&label=Vistas%20del%20Perfil&color=green&base=2000" alt="GabrielLugooo" />
<a href="" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" /></a>
