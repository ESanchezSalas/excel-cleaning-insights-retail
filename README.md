# Excel avanzado — Limpieza e insights (M0)

Proyecto de **Excel + Power Query** para **normalizar y consolidar** datos de ventas y dejarlos listos para análisis descriptivo (tablas dinámicas y métricas).

## Objetivo
Transformar datos heterogéneos en una tabla limpia (**FactSales**) y documentar el flujo de limpieza.

## Stack
Excel · **Power Query (M)**

## Cómo reproducir (resumen)
1. Abrir Excel → **Datos** → **Desde archivo/carpeta** (según tu fuente).
2. En **Power Query** aplicar transformaciones (tipos, TRIM/CLEAN, merges, **Unpivot**, columnas calculadas).
3. Cargar salida como **FactSales** y analizar con pivots (por Store/Dept/IsHoliday, estacionalidad, CV).

## Resultados esperados
- Dataset estandarizado listo para pivots.
- Estadísticos por tienda/departamento.
- Comparación feriado vs. no feriado.
- Vista de estacionalidad y variabilidad.

## Estructura del repo
- [`data/processed/FactSales_M0.xlsx`](data/processed/FactSales_M0.xlsx) → **tabla limpia final**  
- [`docs/pasos_M.md`](docs/pasos_M.md) → **transformaciones en Power Query** (M)  
- [`docs/diagramas/MER-DER.pdf`](docs/diagramas/MER-DER.pdf) → **modelo entidad–relación**  
- [`docs/Documentacion_PI_M0.pdf`](docs/Documentacion_PI_M0.pdf) → **documentación** (estadísticas e insights)

> Nota: si se requieren fuentes en bruto, se ubican en `data/raw/` (no incluidas aquí por tamaño/privacidad).

## Próximos pasos
- Añadir validaciones (calidad de datos) y reglas DQ.
- Publicar un resumen visual (capturas) con principales KPIs.
