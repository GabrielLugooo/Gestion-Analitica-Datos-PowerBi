<img align="center" src="https://i.imgur.com/gJzyKft.png" alt="gabriellugo" />

# ANALYTICAL DATA MANAGEMENT WITH POWER BI

<a href="https://github.com/GabrielLugooo/Gestion-Analitica-Datos-PowerBi/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Analytical%20Data%20PowerBi%20English-000000" alt="Analytical Data Management PowerBi English" /></a>
<a href="https://github.com/GabrielLugooo/Gestion-Analitica-Datos-PowerBi/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Analytical%20Data%20PowerBi%20Spanish-green" alt="Analytical Data Management PowerBi Spanish" /></a>

## Objectives

The project transforms retail sales data from 2011 and 2012 into a verifiable analytical model and an interactive report featuring KPIs, slicers, and descriptive insights.

## Skills Acquired

- Importing and integrating data from `.csv` and `.xlsx` files.
- Cleaning, transforming, and assigning data types using `Power Query`.
- Applying regional settings to correctly interpret dates and numerical values.
- Handling missing values ​​while preserving original data to ensure traceability.
- Creating derived columns to normalize variables with inconsistent scales.
- Designing an analytical data model with fact and dimension tables.
- Creating composite keys to link sales data with the weekly characteristics of each store.
- Configuring one-to-many relationships and validating data integrity.
- Creating a calendar table to analyze sales over time.
- Developing measures and calculated columns using `DAX`.
- Calculating sales metrics, including totals, maximums, minimums, averages, and sales by day type.
- Analyzing sales by store, store type, location, time period, holidays, and temperature.
- Designing interactive reports with charts, cards, slicers, and cross-page navigation.
- Documenting results, quality controls, key findings, and the limitations of the analysis.

## Tools Used

![Static Badge](https://img.shields.io/badge/Power%20BI-000000?logo=powerbi&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Power%20Query-000000?logo=microsoft&logoSize=auto)
![Static Badge](https://img.shields.io/badge/DAX-000000?logo=powerbi&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Microsoft%20Excel-000000?logo=microsoftexcel&logoSize=auto)
![Static Badge](https://img.shields.io/badge/CSV-000000?logo=files&logoSize=auto)
![Static Badge](https://img.shields.io/badge/Git-000000?logo=git&logoSize=auto)
![Static Badge](https://img.shields.io/badge/GitHub-000000?logo=github&logoSize=auto)

- `Power BI Desktop` (data modeling, measures, and creation of interactive reports)
- `Power Query` (data extraction, cleaning, and transformation)
- `DAX` (creation of measures, calculated columns, and validations)
- `Microsoft Excel` (project reference file)
- `.csv` files (sources for sales, weekly features, and stores)
- `Git` and `GitHub` (version control, documentation, and project publishing)

## Project

### Preview

<img align="center" src="https://i.imgur.com/PxzSyIP.jpeg" alt="PowerBi_Analytics_01" />
<img align="center" src="https://i.imgur.com/9QTQ4Db.jpeg" alt="PowerBi_Analytics_02" />
<img align="center" src="https://i.imgur.com/wXW8nY2.jpeg" alt="PowerBi_Analytics_03" />
<img align="center" src="https://i.imgur.com/3hzTJi2.jpeg" alt="PowerBi_Analytics_04" />

### Contents

- `powerbi/PI_GAD_PowerBI.pbix`: Main Power BI file containing three pages: Cover, General Report, and 2012 Sales – Temperature > 20.
- `datos/Datawarehouse.xlsx`: Original reference workbook for the project.
- `datos/raw/`: Original CSV files containing sales, weekly features, and store data.
- `docs/Informe_Final.md`: Detailed report covering data cleaning, the data model, measures, findings, validations, and limitations.
- `docs/Medidas_DAX.md`: Implemented DAX formulas.

### Opening the Project

Open `powerbi/PI_GAD_PowerBI.pbix` using Power BI Desktop. The model includes the imported data. To refresh the data from the repository's CSV files on a different machine, update the Power Query data source paths to point to the `datos/raw/` directory.

### Validated Results

- Row counts: `sales` 280,891; `features` 4,680; `stores` 45; `location` 12.
- Unique `features[StoreWeekKey]` values; zero sales rows without a corresponding match in the `features` table.
- Total sales (2011–2012): 4,448,332,866.70.
- 2012 sales where `Temperature > 20`: 1,994,956,776.32.

## Limitations

The adjusted fuel and unemployment columns are based on documented rules for values ​​with inconsistent scales; they are not presented as official corrections. The original fields have been retained.

The temperature threshold is based on the scale provided in the source data; the specific unit of measurement has not been confirmed.

The 2012 total covers sales only up to October 26th; therefore, it does not represent a full calendar year.

---

<h3 align="left">Conect With Me</h3>

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
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/Readme.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/English%20Version-000000" alt="English Version" /></a>
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Spanish%20Version-Green" alt="Spanish Version" /></a>
</p>

<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Créditos-Gabriel%20Lugo-green" alt="Créditos" /></a>
<img align="center" src="https://komarev.com/ghpvc/?username=GabrielLugoo&label=Vistas%20del%20Perfil&color=green&base=2000" alt="GabrielLugooo" />
<a href="" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" /></a>
