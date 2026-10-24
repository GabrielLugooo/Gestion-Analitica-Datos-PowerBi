# Medidas DAX

```DAX
Calendario =
CALENDAR(
    MIN(sales[Date]),
    MAX(features[Date])
)
```

```DAX
Año = YEAR(Calendario[Date])
```

```DAX
Total ventas = SUM(sales[Weekly_Sales])
Venta máxima = MAX(sales[Weekly_Sales])
Venta mínima = MIN(sales[Weekly_Sales])
```

```DAX
Ventas festivo =
CALCULATE(
    [Total ventas],
    sales[IsHoliday] = TRUE()
)

Ventas no festivo =
CALCULATE(
    [Total ventas],
    sales[IsHoliday] = FALSE()
)

Diferencia ventas festivo vs no festivo =
[Ventas festivo] - [Ventas no festivo]
```

```DAX
Semanas festivas =
CALCULATE(
    DISTINCTCOUNT(sales[StoreWeekKey]),
    sales[IsHoliday] = TRUE()
)

Semanas no festivas =
CALCULATE(
    DISTINCTCOUNT(sales[StoreWeekKey]),
    sales[IsHoliday] = FALSE()
)

Promedio ventas por tienda-semana festiva =
DIVIDE([Ventas festivo], [Semanas festivas])

Promedio ventas por tienda-semana no festiva =
DIVIDE([Ventas no festivo], [Semanas no festivas])
```

```DAX
Tipo de día =
IF(
    sales[IsHoliday] = TRUE(),
    "Festivo",
    "No festivo"
)
```

La comprobación temporal de integridad de claves fue:

```DAX
Filas de ventas sin features =
COALESCE(
    COUNTROWS(
        FILTER(
            ALL(sales),
            ISBLANK(RELATED(features[StoreWeekKey]))
        )
    ),
    0
)
```

El resultado fue 0. Esta medida de auditoría se eliminó del informe final.
