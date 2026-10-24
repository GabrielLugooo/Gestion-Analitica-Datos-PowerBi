# Proyecto integrador de Gestión Analítica de Datos

Portfolio Power BI del Proyecto Integrador de Henry. El proyecto transforma los datos de ventas minoristas de 2011 y 2012 en un modelo analítico verificable y un informe interactivo con KPIs, segmentadores y hallazgos descriptivos.

## Contenido

- `PowerBI/PI_Henry_PowerBI.pbix`: archivo principal de Power BI con tres páginas: Portada, Reporte General y Ventas 2012 - Temperatura > 20.
- `Datos/Datawarehouse_inicial.xlsx`: libro original de referencia del proyecto.
- `Datos/raw/`: CSV originales de ventas, características semanales y tiendas.
- `docs/INFORME_FINAL.md`: informe detallado de limpieza, modelo, medidas, hallazgos, validaciones y limitaciones.
- `docs/MEDIDAS_DAX.md`: fórmulas DAX implementadas.

## Abrir el proyecto

Abrir `PowerBI/PI_Henry_PowerBI.pbix` con Power BI Desktop. El modelo contiene los datos importados. Para actualizar desde los CSV del repositorio en otro equipo, modificar los orígenes de las consultas de Power Query para apuntar a `Datos/raw/`.

## Resultados validados

- Filas: `sales` 280.891; `features` 4.680; `stores` 45; `location` 12.
- Claves de `features[StoreWeekKey]` únicas y cero filas de ventas sin correspondencia en `features`.
- Ventas totales 2011–2012: 4.448.332.866,70.
- Ventas 2012 con `Temperature > 20`: 1.994.956.776,32.

## Alcance y cautelas

Las columnas ajustadas de combustible y desempleo son reglas documentadas para valores con escala inconsistente; no se presentan como correcciones oficiales. Se conservan los campos originales. El umbral de temperatura usa la escala de la fuente, cuya unidad no fue confirmada. El total de 2012 cubre ventas solo hasta el 26 de octubre, por lo que no representa un año calendario completo.


