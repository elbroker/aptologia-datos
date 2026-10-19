---
license: cc-by-4.0
language:
- es
- en
pretty_name: "Vivienda en Medellín: precio por m², arriendo, habitaciones, estrato y administración (octubre 2026)"
size_categories:
- n<1K
tags:
- real-estate
- housing
- latin-america
- open-data
- medellín
- rent
- price-per-square-metre
configs:
- config_name: vivienda_medellin_por_comuna_venta_arriendo_estrato_2026_datos
  data_files: data/vivienda_medellin_por_comuna_venta_arriendo_estrato_2026_datos.csv
  default: true
---

Estudio completo, gráficas y metodología (fuente canónica): https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-medellin-por-comuna-venta-arriendo-estrato-2026

# Vivienda en Medellín: precio por m², arriendo, habitaciones, estrato y administración (octubre 2026)

La comuna con el metro cuadrado más caro de Medellín es Santa Elena, con 10,43 millones de pesos en la mediana de apartamentos en venta; la más barata de la muestra es Aranjuez, con 4,38 millones de pesos. Un apartamento de 2 habitaciones se arrienda por 4,20 millones de pesos al mes en la mediana y se vende por 720 millones de pesos. La rentabilidad bruta implícita del arriendo es 7,9 % anual. La administración equivale al 11,2 % del canon (700.000 pesos al mes en la mediana).

- **Fecha de actualización:** 2026-10-18
- **Autor:** Daniel Mauricio Pinzón Pineda ([ORCID 0009-0007-5142-366X](https://orcid.org/0009-0007-5142-366X))
- **Editor:** Aptología
- **Fuente canónica:** https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-medellin-por-comuna-venta-arriendo-estrato-2026
- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## English summary

Housing in Medellín (apartments, Oct 2026): sale USD 2356/m²; 2-bedroom rent USD 1320/month; gross yield 7.9%. Source: Aptología, 2026-10-18.

## Archivos

- `vivienda-medellin-por-comuna-venta-arriendo-estrato-2026.md`: estudio completo (markdown).
- `data/vivienda_medellin_por_comuna_venta_arriendo_estrato_2026_datos.csv`
- `charts/m2-por-estrato.png`
- `charts/m2-venta-comunas.png`
- `charts/m2-por-estrato.svg`
- `charts/m2-venta-comunas.svg`

CSV en UTF-8, separados por comas, con encabezado. Los precios van en la moneda que indica cada columna (pesos colombianos, moneda local o dólares); las conversiones a dólares usan la tasa citada en la metodología del estudio.

## Cita

Pinzón Pineda, Daniel Mauricio (2026). *Vivienda en Medellín: precio por m², arriendo, habitaciones, estrato y administración (octubre 2026)*. Aptología. https://github.com/elbroker/aptologia-datos/tree/main/estudios/vivienda-medellin-por-comuna-venta-arriendo-estrato-2026
